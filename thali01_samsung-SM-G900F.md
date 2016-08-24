#### Test 79763830e108614_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-24 13:23:40.607  5283  5283 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-24 13:23:40.607  5283  5283 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
,08-24 13:23:40.607  5283  5283 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-24 13:23:40.607  5283  5283 I art     : System.exit called, status: 0
08-24 13:23:40.607  5283  5283 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-24 13:23:40.647  5257  5257 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
--------- beginning of system
08-24 13:23:40.647   755  1410 I ActivityManager: Process com.samsung.aasaservice (pid 5283)(adj 0) has died(137,715)
08-24 13:23:40.647   755  1410 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-24 13:23:40.647   755  1410 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-24 13:23:40.647   755  1410 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-24 13:23:40.677  6233  6233 E Zygote  : v2
08-24 13:23:40.677  6233  6233 I libpersona: KNOX_SDCARD checking this for 10014
08-24 13:23:40.677  6233  6233 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:40.677  6233  6233 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:40.677  6233  6233 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:40.677  6233  6233 E Zygote  : accessInfo : 0
08-24 13:23:40.677  6233  6233 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-24 13:23:40.687   755   846 I ActivityManager: Start proc 6233:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-24 13:23:40.687   755  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 13:23:40.707  6233  6233 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:40.707  6233  6233 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:40.717   755  1757 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d127a82 6233:com.google.android.partnersetup/u0a14}
08-24 13:23:40.717   755  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-24 13:23:40.717  6233  6233 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-24 13:23:40.737  6233  6233 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-24 13:23:40.757   755  1756 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d127a82 6233:com.google.android.partnersetup/u0a14}
08-24 13:23:40.777   755  1756 I ActivityManager: Start proc 6253:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-24 13:23:40.777  6253  6253 E Zygote  : v2
08-24 13:23:40.777  6253  6253 I libpersona: KNOX_SDCARD checking this for 10015
08-24 13:23:40.777  6253  6253 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:40.787  6253  6253 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:40.787  6253  6253 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:40.787  6253  6253 E Zygote  : accessInfo : 0
08-24 13:23:40.787  6253  6253 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-24 13:23:40.787   755   768 I ActivityManager: Killing 5370:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
08-24 13:23:40.807   755  1586 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
08-24 13:23:40.827  6253  6253 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:40.827  6253  6253 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:40.837   755   769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8863dc9 6253:com.samsung.groupcast/u0a15}
08-24 13:23:40.847  6253  6253 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-24 13:23:40.867  6253  6253 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-24 13:23:40.887  6253  6253 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-24 13:23:40.897  6253  6253 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-24 13:23:40.897  6253  6253 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-24 13:23:40.897  6253  6253 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-24 13:23:40.897  6253  6253 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-24 13:23:40.897  6253  6253 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-24 13:23:40.897  6253  6253 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-24 13:23:40.897  6253  6253 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 13:23:40.897  6253  6253 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 13:23:40.897  6253  6253 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:23:40.897  6253  6253 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-24 13:23:40.897  6253  6253 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 13:23:40.897  6253  6253 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 13:23:40.897  6253  6253 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 13:23:40.897  6253  6253 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 13:23:40.907   755  1410 I ActivityManager: Killing 5431:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-24 13:23:40.907   755  1410 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a44703 1893:com.sec.android.app.shealth:remote/u0a34}
08-24 13:23:40.927  6265  6265 E Zygote  : v2
08-24 13:23:40.927   755   768 I ActivityManager: Start proc 6265:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-24 13:23:40.927  6265  6265 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:40.927  6265  6265 I libpersona: KNOX_SDCARD checking this for 10041
08-24 13:23:40.927  6265  6265 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:40.927  6265  6265 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:40.927  6265  6265 E Zygote  : accessInfo : 0
08-24 13:23:40.927  6265  6265 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-24 13:23:40.937   755  1218 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-24 13:23:40.957  6265  6265 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:40.957  6265  6265 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:40.967   755   769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a71bcce 6265:com.samsung.android.sdk.samsunglink/u0a41}
08-24 13:23:40.967  6265  6265 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-24 13:23:41.067  6265  6265 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 13:23:41.067  6265  6265 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 13:23:41.127  6265  6265 I SL_DEBUG: isLoggable:: isProductShip = 1
08-24 13:23:41.137  6265  6265 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-24 13:23:41.147   755   769 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-24 13:23:41.147   755  1410 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-24 13:23:41.157   755  1641 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-24 13:23:41.157   755  1586 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-24 13:23:41.157   755  1492 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-24 13:23:41.167   755  1757 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-24 13:23:41.167   755  1756 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-24 13:23:41.167   755   768 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-24 13:23:41.167   755  1218 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-24 13:23:41.177   755  1748 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-24 13:23:41.317  6265  6265 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-24 13:23:41.327  6265  6265 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-24 13:23:41.327  6265  6265 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-24 13:23:41.327  6265  6265 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-24 13:23:41.327  6265  6265 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-24 13:23:41.327  6265  6265 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-24 13:23:41.327  6265  6265 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-24 13:23:41.327  6265  6265 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-24 13:23:41.327  6265  6265 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 13:23:41.327  6265  6265 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 13:23:41.327  6265  6265 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:23:41.327  6265  6265 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-24 13:23:41.327  6265  6265 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 13:23:41.327  6265  6265 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 13:23:41.327  6265  6265 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 13:23:41.327  6265  6265 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 13:23:41.337   755  1410 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b39e29d 1649:android.process.acore/u0a19}
08-24 13:23:41.357   755  1410 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d06b2c8 5027:com.sec.android.gallery3d/u0a47}
08-24 13:23:41.357  5027  5027 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-24 13:23:41.367   755  1748 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-24 13:23:41.397  6288  6288 E Zygote  : v2
08-24 13:23:41.397   755   769 I ActivityManager: Start proc 6288:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-24 13:23:41.397  6288  6288 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:41.397  6288  6288 I libpersona: KNOX_SDCARD checking this for 10050
08-24 13:23:41.397  6288  6288 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:41.397  6288  6288 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:41.397  6288  6288 E Zygote  : accessInfo : 0
08-24 13:23:41.397  6288  6288 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-24 13:23:41.447  6288  6288 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:41.447  6288  6288 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:41.457   755  1756 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2cf57e 6288:com.sec.android.app.myfiles/u0a50}
08-24 13:23:41.467  6288  6288 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-24 13:23:41.497  6288  6288 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-24 13:23:41.567  6288  6288 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-24 13:23:41.597   755  1905 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de7ec66 2838:com.android.settings/1000}
08-24 13:23:41.627   325   325 E installd: system dir 0 : /system/app/
08-24 13:23:41.627   325   325 E installd: system dir 1 : /system/priv-app/
08-24 13:23:41.627   325   325 E installd: system dir 2 : /vendor/app/
08-24 13:23:41.627   325   325 E installd: system dir 3 : /oem/app/
08-24 13:23:41.637   755  1641 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de7ec66 2838:com.android.settings/1000}
08-24 13:23:41.657   755   919 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-24 13:23:41.657   755  1757 I ActivityManager: Start proc 6303:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-24 13:23:41.657  6303  6303 E Zygote  : v2
08-24 13:23:41.657  6303  6303 I libpersona: KNOX_SDCARD checking this for 10169
08-24 13:23:41.657  6303  6303 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:41.667  6303  6303 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:41.667  6303  6303 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:41.667  6303  6303 E Zygote  : accessInfo : 0
08-24 13:23:41.667  6303  6303 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-24 13:23:41.697   755   846 I ActivityManager: Start proc 6314:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-24 13:23:41.697  6314  6314 E Zygote  : v2
08-24 13:23:41.697  6314  6314 I libpersona: KNOX_SDCARD checking this for 10210
08-24 13:23:41.697  6314  6314 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:41.697  6314  6314 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:41.697  6314  6314 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:41.697  6314  6314 E Zygote  : accessInfo : 0
08-24 13:23:41.697  6314  6314 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-24 13:23:41.727  6303  6303 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:41.727  6303  6303 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:41.737   755  1756 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{91eeb8a 6303:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-24 13:23:41.747  2205  2205 E audit   : type=1400 msg=audit(1472037821.747:284): avc:  denied  { execmod } for  pid=6234 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 13:23:41.747  6314  6314 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:41.747  6314  6314 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:41.747  2205  2205 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:41.747  2205  2205 E audit   : type=1300 msg=audit(1472037821.747:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f93000 a1=51000 a2=5 a3=4 items=0 ppid=3551 ppcomm=adbd pid=6234 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 13:23:41.757  2205  2205 E audit   : type=1327 msg=audit(1472037821.747:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 13:23:41.757  2205  2205 E audit   : type=1320 msg=audit(1472037821.747:284): 
08-24 13:23:41.757  6303  6303 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-24 13:23:41.767  6314  6314 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-24 13:23:41.777  6303  6303 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-24 13:23:41.787  6314  6314 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-24 13:23:41.787  6314  6314 D AASAservice: onCreate()
08-24 13:23:41.797   755  1586 I ActivityManager: Killing 4033:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-24 13:23:41.807  5257  5257 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-24 13:23:41.817   755  1641 I ActivityManager: Killing 5472:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
08-24 13:23:41.827   755  1641 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f93585c 1730:com.android.phone/1001}
08-24 13:23:41.827  2205  2205 E audit   : type=1400 msg=audit(1472037821.827:285): avc:  denied  { execmod } for  pid=6234 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 13:23:41.827  2205  2205 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:41.827  2205  2205 E audit   : type=1300 msg=audit(1472037821.827:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f53000 a1=51000 a2=5 a3=4 items=0 ppid=3551 ppcomm=adbd pid=6234 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 13:23:41.827  2205  2205 E audit   : type=1327 msg=audit(1472037821.827:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 13:23:41.827  2205  2205 E audit   : type=1320 msg=audit(1472037821.827:285): 
08-24 13:23:41.827   755  1492 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
08-24 13:23:41.847   755  1905 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
08-24 13:23:41.857   755  1757 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2795151 1831:com.google.android.googlequicksearchbox:search/u0a61}
08-24 13:23:41.867   755  1586 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2795151 1831:com.google.android.googlequicksearchbox:search/u0a61}
08-24 13:23:41.877   755  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c8fb618 6170:com.samsung.android.sm.provider/1000}
08-24 13:23:41.887  2205  2205 E audit   : type=1400 msg=audit(1472037821.887:286): avc:  denied  { execmod } for  pid=6234 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 13:23:41.887  2205  2205 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:41.887  2205  2205 E audit   : type=1300 msg=audit(1472037821.887:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f53000 a1=51000 a2=5 a3=4 items=0 ppid=3551 ppcomm=adbd pid=6234 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 13:23:41.887  2205  2205 E audit   : type=1327 msg=audit(1472037821.887:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-24 13:23:41.887  2205  2205 E audit   : type=1320 msg=audit(1472037821.887:286): 
08-24 13:23:41.887  6234  6234 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 13:23:41.897  6234  6234 D AndroidRuntime: CheckJNI is OFF
08-24 13:23:41.897  6234  6234 D AndroidRuntime: readGMSProperty: start
08-24 13:23:41.897  6234  6234 D AndroidRuntime: readGMSProperty: already setted!!
08-24 13:23:41.897  6234  6234 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 13:23:41.897  6234  6234 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 13:23:41.897  6234  6234 D AndroidRuntime: readGMSProperty: end
08-24 13:23:41.897  6234  6234 D AndroidRuntime: addProductProperty: start
08-24 13:23:41.907  6234  6234 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 13:23:41.907  6234  6234 W art     : af0e5000-b200b000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-24 13:23:41.907  6234  6234 W art     : b200b000-b427a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-24 13:23:41.907  6234  6234 W art     : b427a000-b427b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-24 13:23:41.907  6234  6234 W art     : b427b000-b42a4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 13:23:41.907  6234  6234 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-24 13:23:41.907  6234  6234 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-24 13:23:41.907  6234  6234 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-24 13:23:41.907  6234  6234 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-24 13:23:41.907  6234  6234 W art     : b4823000-b4826000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-24 13:23:41.907  6234  6234 W art     : b4826000-b4827000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-24 13:23:41.907  6234  6234 W art     : b4827000-b4828000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-24 13:23:41.907  6234  6234 W art     : b4828000-b4829000 r--p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b4829000-b4849000 r--s 00000000 00:0b 9219       /dev/__properties__
08-24 13:23:41.907  6234  6234 W art     : b4849000-b525a000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-24 13:23:41.907  6234  6234 W art     : b525a000-b525b000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b525b000-b52a4000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-24 13:23:41.907  6234  6234 W art     : b52a4000-b52a5000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-24 13:23:41.907  6234  6234 W art     : b52a5000-b52ad000 rw-p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b52ad000-b52ae000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.907  6234  6234 W art     : b52ae000-b52e3000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-24 13:23:41.907  6234  6234 W art     : b52e3000-b52e4000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b52e4000-b52e5000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-24 13:23:41.907  6234  6234 W art     : b52e5000-b52e6000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-24 13:23:41.907  6234  6234 W art     : b52e6000-b533e000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-24 13:23:41.907  6234  6234 W art     : b533e000-b533f000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b533f000-b5340000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-24 13:23:41.907  6234  6234 W art     : b5340000-b5341000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-24 13:23:41.907  6234  6234 W art     : b5342000-b5348000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 13:23:41.907  6234  6234 W art     : b5348000-b5349000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 13:23:41.907  6234  6234 W art     : b5349000-b534a000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 13:23:41.907  6234  6234 W art     : b534a000-b534c000 rw-p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b534d000-b5357000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 13:23:41.907  6234  6234 W art     : b5357000-b535a000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 13:23:41.907  6234  6234 W art     : b535a000-b535b000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 13:23:41.907  6234  6234 W art     : b535c000-b5373000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 13:23:41.907  6234  6234 W art     : b5373000-b5374000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5374000-b5375000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 13:23:41.907  6234  6234 W art     : b5375000-b5376000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 13:23:41.907  6234  6234 W art     : b5377000-b5381000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-24 13:23:41.907  6234  6234 W art     : b5381000-b5382000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-24 13:23:41.907  6234  6234 W art     : b5382000-b5383000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-24 13:23:41.907  6234  6234 W art     : b5383000-b5387000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 13:23:41.907  6234  6234 W art     : b5387000-b5388000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 13:23:41.907  6234  6234 W art     : b5388000-b5389000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 13:23:41.907  6234  6234 W art     : b5389000-b539f000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-24 13:23:41.907  6234  6234 W art     : b539f000-b53a0000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-24 13:23:41.907  6234  6234 W art     : b53a0000-b53a1000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-24 13:23:41.907  6234  6234 W art     : b53a1000-b53ae000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-24 13:23:41.907  6234  6234 W art     : b53ae000-b53af000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-24 13:23:41.907  6234  6234 W art     : b53af000-b53b0000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-24 13:23:41.907  6234  6234 W art     : b53b0000-b5410000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-24 13:23:41.907  6234  6234 W art     : b5410000-b5413000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-24 13:23:41.907  6234  6234 W art     : b5413000-b5417000 rw-p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5417000-b5478000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-24 13:23:41.907  6234  6234 W art     : b5478000-b5479000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-24 13:23:41.907  6234  6234 W art     : b5479000-b54c8000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-24 13:23:41.907  6234  6234 W art     : b54c8000-b54ca000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-24 13:23:41.907  6234  6234 W art     : b54ca000-b54cb000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-24 13:23:41.907  6234  6234 W art     : b54cb000-b54cc000 rw-p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b54cc000-b54d3000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 13:23:41.907  6234  6234 W art     : b54d3000-b54d4000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 13:23:41.907  6234  6234 W art     : b54d4000-b54d5000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 13:23:41.907  6234  6234 W art     : b54d6000-b54d9000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 13:23:41.907  6234  6234 W art     : b54d9000-b54da000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 13:23:41.907  6234  6234 W art     : b54da000-b54db000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 13:23:41.907  6234  6234 W art     : b54dc000-b54e0000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-24 13:23:41.907  6234  6234 W art     : b54e0000-b54e1000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b54e1000-b54e2000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-24 13:23:41.907  6234  6234 W art     : b54e2000-b54e3000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-24 13:23:41.907  6234  6234 W art     : b54e4000-b5501000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 13:23:41.907  6234  6234 W art     : b5501000-b5502000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 13:23:41.907  6234  6234 W art     : b5502000-b5503000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 13:23:41.907  6234  6234 W art     : b5504000-b5509000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 13:23:41.907  6234  6234 W art     : b5509000-b550a000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 13:23:41.907  6234  6234 W art     : b550a000-b550b000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 13:23:41.907  6234  6234 W art     : b550c000-b553d000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 13:23:41.907  6234  6234 W art     : b553d000-b5540000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 13:23:41.907  6234  6234 W art     : b5540000-b5541000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 13:23:41.907  6234  6234 W art     : b5542000-b557d000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-24 13:23:41.907  6234  6234 W art     : b557d000-b557e000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-24 13:23:41.907  6234  6234 W art     : b557e000-b557f000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-24 13:23:41.907  6234  6234 W art     : b5580000-b5587000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-24 13:23:41.907  6234  6234 W art     : b5587000-b5588000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5588000-b5589000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-24 13:23:41.907  6234  6234 W art     : b5589000-b558a000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-24 13:23:41.907  6234  6234 W art     : b558a000-b558b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.907  6234  6234 W art     : b558b000-b55a2000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-24 13:23:41.907  6234  6234 W art     : b55a2000-b55a3000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b55a3000-b55a6000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-24 13:23:41.907  6234  6234 W art     : b55a6000-b55a7000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-24 13:23:41.907  6234  6234 W art     : b55a7000-b55c6000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-24 13:23:41.907  6234  6234 W art     : b55c6000-b55c7000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-24 13:23:41.907  6234  6234 W art     : b55c7000-b55c8000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-24 13:23:41.907  6234  6234 W art     : b55c8000-b5606000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-24 13:23:41.907  6234  6234 W art     : b5606000-b5607000 ---p 00000000 00:00 0 
08-24 13:23:41.927   755  1756 I ActivityManager: Start proc 6330:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-24 13:23:41.907  6234  6234 W art     : b5607000-b5609000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-24 13:23:41.907  6234  6234 W art     : b5609000-b560a000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-24 13:23:41.907  6234  6234 W art     : b560b000-b5612000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 13:23:41.907  6234  6234 W art     : b5612000-b5613000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 13:23:41.907  6234  6234 W art     : b5613000-b5614000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 13:23:41.907  6234  6234 W art     : b5615000-b5618000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 13:23:41.907  6234  6234 W art     : b5618000-b5619000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 13:23:41.907  6234  6234 W art     : b5619000-b561a000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 13:23:41.907  6234  6234 W art     : b561a000-b5620000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 13:23:41.907  6234  6234 W art     : b5620000-b5621000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5621000-b5622000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 13:23:41.907  6234  6234 W art     : b5622000-b5623000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 13:23:41.907  6234  6234 W art     : b5623000-b562c000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-24 13:23:41.907  6234  6234 W art     : b562c000-b562d000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-24 13:23:41.907  6234  6234 W art     : b562d000-b562e000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-24 13:23:41.907  6234  6234 W art     : b562e000-b56bf000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 13:23:41.907  6234  6234 W art     : b56bf000-b56c0000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b56c0000-b56cb000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 13:23:41.907  6234  6234 W art     : b56cb000-b56cc000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 13:23:41.907  6234  6234 W art     : b56cd000-b56df000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-24 13:23:41.907  6234  6234 W art     : b56df000-b56e0000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-24 13:23:41.907  6234  6234 W art     : b56e0000-b56e1000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-24 13:23:41.907  6234  6234 W art     : b56e2000-b56e7000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-24 13:23:41.907  6234  6234 W art     : b56e7000-b56e8000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-24 13:23:41.907  6234  6234 W art     : b56e8000-b56e9000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-24 13:23:41.907  6234  6234 W art     : b56ea000-b5757000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-24 13:23:41.907  6234  6234 W art     : b5757000-b5758000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5758000-b575a000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-24 13:23:41.907  6234  6234 W art     : b575a000-b575b000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-24 13:23:41.907  6234  6234 W art     : b575b000-b575c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.907  6234  6234 W art     : b575c000-b5763000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 13:23:41.907  6234  6234 W art     : b5763000-b5764000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 13:23:41.907  6234  6234 W art     : b5764000-b5765000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 13:23:41.907  6234  6234 W art     : b5766000-b57e6000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 13:23:41.907  6234  6234 W art     : b57e6000-b57e7000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b57e7000-b57e8000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 13:23:41.907  6234  6234 W art     : b57e8000-b57e9000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 13:23:41.907  6234  6234 W art     : b57e9000-b5800000 rw-p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5800000-b5837000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-24 13:23:41.907  6234  6234 W art     : ib/libqc-opt.so
08-24 13:23:41.907  6234  6234 W art     : b5837000-b5838000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 13:23:41.907  6234  6234 W art     : b5838000-b5839000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 13:23:41.907  6234  6234 W art     : b5839000-b5855000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 13:23:41.937  6330  6330 I libpersona: KNOX_SDCARD checking this for 5012
08-24 13:23:41.907  6234  6234 W art     : b5855000-b5856000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 13:23:41.937  6330  6330 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:41.907  6234  6234 W art     : b5856000-b5857000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 13:23:41.907  6234  6234 W art     : b5858000-b58b9000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-24 13:23:41.907  6234  6234 W art     : b58b9000-b58bb000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-24 13:23:41.907  6234  6234 W art     : b58bb000-b58bc000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-24 13:23:41.907  6234  6234 W art     : b58bd000-b58e4000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-24 13:23:41.907  6234  6234 W art     : b58e4000-b58e5000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b58e5000-b58e6000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-24 13:23:41.907  6234  6234 W art     : b58e6000-b58e7000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-24 13:23:41.907  6234  6234 W art     : b58e8000-b58f0000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 13:23:41.907  6234  6234 W art     : b58f0000-b58f2000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 13:23:41.907  6234  6234 W art     : b58f2000-b58f3000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 13:23:41.907  6234  6234 W art     : b58f4000-b58f7000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-24 13:23:41.907  6234  6234 W art     : b58f7000-b58f8000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-24 13:23:41.907  6234  6234 W art     : b58f8000-b58f9000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-24 13:23:41.907  6234  6234 W art     : b58f9000-b58fd000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-24 13:23:41.907  6234  6234 W art     : b58fd000-b58fe000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b58fe000-b58ff000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-24 13:23:41.907  6234  6234 W art     : b58ff000-b5900000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-24 13:23:41.907  6234  6234 W art     : b5900000-b5910000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-24 13:23:41.907  6234  6234 W art     : b5910000-b5911000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-24 13:23:41.907  6234  6234 W art     : b5911000-b5912000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-24 13:23:41.907  6234  6234 W art     : b5912000-b5958000 rw-p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5958000-b5961000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-24 13:23:41.907  6234  6234 W art     : b5961000-b5962000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-24 13:23:41.907  6234  6234 W art     : b5962000-b5963000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-24 13:23:41.907  6234  6234 W art     : b5964000-b5969000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-24 13:23:41.907  6234  6234 W art     : b5969000-b596a000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-24 13:23:41.907  6234  6234 W art     : b596a000-b596b000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-24 13:23:41.907  6234  6234 W art     : b596b000-b596e000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 13:23:41.907  6234  6234 W art     : b596e000-b596f000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b596f000-b5970000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 13:23:41.907  6234  6234 W art     : b5970000-b5971000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 13:23:41.907  6234  6234 W art     : b5972000-b598a000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 13:23:41.907  6234  6234 W art     : b598a000-b598b000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b598b000-b598c000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 13:23:41.907  6234  6234 W art     : b598c000-b598d000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 13:23:41.907  6234  6234 W art     : b598d000-b598e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:23:41.907  6234  6234 W art     : b598e000-b5b28000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-24 13:23:41.907  6234  6234 W art     : b5b28000-b5b29000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5b29000-b5b36000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-24 13:23:41.907  6234  6234 W art     : b5b36000-b5b37000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-24 13:23:41.907  6234  6234 W art     : b5b37000-b5b3b000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-24 13:23:41.907  6234  6234 W art     : b5b3b000-b5b3c000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5b3c000-b5b3d000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-24 13:23:41.907  6234  6234 W art     : b5b3d000-b5b3e000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-24 13:23:41.907  6234  6234 W art     : b5b3e000-b5b51000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-24 13:23:41.907  6234  6234 W art     : b5b51000-b5b52000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-24 13:23:41.907  6234  6234 W art     : b5b52000-b5b53000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-24 13:23:41.907  6234  6234 W art     : b5b54000-b5b9f000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-24 13:23:41.907  6234  6234 W art     : b5b9f000-b5ba0000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-24 13:23:41.907  6234  6234 W art     : b5ba0000-b5ba1000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-24 13:23:41.907  6234  6234 W art     : b5ba1000-b5ba3000 rw-p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5ba4000-b5bb5000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 13:23:41.907  6234  6234 W art     : b5bb5000-b5bb6000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5bb6000-b5bb7000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 13:23:41.907  6234  6234 W art     : b5bb7000-b5bb8000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 13:23:41.907  6234  6234 W art     : b5bb8000-b5bb9000 r--p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5bb9000-b5bc3000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-24 13:23:41.907  6234  6234 W art     : b5bc3000-b5bc5000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-24 13:23:41.907  6234  6234 W art     : b5bc5000-b5bc6000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-24 13:23:41.907  6234  6234 W art     : b5bc6000-b5bdf000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-24 13:23:41.907  6234  6234 W art     : b5bdf000-b5be0000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-24 13:23:41.907  6234  6234 W art     : b5be0000-b5be3000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-24 13:23:41.907  6234  6234 W art     : b5be3000-b5be7000 rw-p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5be7000-b5c5b000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-24 13:23:41.907  6234  6234 W art     : b5c5b000-b5c5c000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5c5c000-b5c5f000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-24 13:23:41.907  6234  6234 W art     : b5c5f000-b5c60000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-24 13:23:41.907  6234  6234 W art     : b5c60000-b5c61000 r--p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5c61000-b5c64000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-24 13:23:41.907  6234  6234 W art     : b5c64000-b5c65000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-24 13:23:41.907  6234  6234 W art     : b5c65000-b5c66000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-24 13:23:41.907  6234  6234 W art     : b5c66000-b5c67000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.907  6234  6234 W art     : b5c67000-b5c6c000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 13:23:41.907  6234  6234 W art     : b5c6c000-b5c6d000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 13:23:41.907  6234  6234 W art     : b5c6d000-b5c6e000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 13:23:41.907  6234  6234 W art     : b5c6e000-b5c6f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.907  6234  6234 W art     : b5c6f000-b5c72000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 13:23:41.907  6234  6234 W art     : b5c72000-b5c73000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 13:23:41.907  6234  6234 W art     : b5c73000-b5c74000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 13:23:41.907  6234  6234 W art     : b5c74000-b5c75000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.907  6234  6234 W art     : b5c75000-b5c79000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-24 13:23:41.907  6234  6234 W art     : b5c79000-b5c7a000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-24 13:23:41.907  6234  6234 W art     : b5c7a000-b5c7b000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-24 13:23:41.907  6234  6234 W art     : b5c7b000-b5c7c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:23:41.907  6234  6234 W art     : b5c7c000-b5c80000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 13:23:41.907  6234  6234 W art     : b5c80000-b5c81000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 13:23:41.907  6234  6234 W art     : b5c81000-b5c82000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 13:23:41.907  6234  6234 W art     : b5c82000-b5c83000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.907  6234  6234 W art     : b5c83000-b5c91000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-24 13:23:41.907  6234  6234 W art     : b5c91000-b5c92000 ---p 00000000 00:00 0 
08-24 13:23:41.907  6234  6234 W art     : b5c92000-b5c93000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-24 13:23:41.907  6234  6234 W art     : b5c93000-b5c94000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-24 13:23:41.907  6234  6234 W art     : b5c94000-b5c9e000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 13:23:41.907  6234  6234 W art     : b5c9e000-b5ca1000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 13:23:41.907  6234  6234 W art     : b5ca1000-b5ca2000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 13:23:41.907  6234  6234 W art     : b5ca2000-b5ca3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.907  6234  6234 W art     : b5ca3000-b5cad000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-24 13:23:41.907  6234  6234 W art     : b5cad000-b5cb0000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-24 13:23:41.907  6234  6234 W art     : b5cb0000-b5cb1000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-24 13:23:41.907  6234  6234 W art     : b5cb1000-b5cb5000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-24 13:23:41.907  6234  6234 W art     : b5cb5000-b5cb6000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-24 13:23:41.907  6234  6234 W art     : b5cb6000-b5cb7000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-24 13:23:41.907  6234  6234 W art     : b5cb7000-b5cb8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.907  6234  6234 W art     : b5cb8000-b5cc5000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-24 13:23:41.907  6234  6234 W art     : b5cc5000-b5cc7000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-24 13:23:41.907  6234  6234 W art     : b5cc7000-b5cc8000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-24 13:23:41.907  6234  6234 W art     : b5cc8000-b60da000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-24 13:23:41.907  6234  6234 W art     : b60da000-b60db000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b60db000-b60e4000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-24 13:23:41.917  6234  6234 W art     : b60e4000-b60e8000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-24 13:23:41.917  6234  6234 W art     : b60e8000-b60e9000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b60e9000-b60f0000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-24 13:23:41.917  6234  6234 W art     : b60f0000-b60f1000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-24 13:23:41.917  6234  6234 W art     : b60f1000-b60f2000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-24 13:23:41.917  6234  6234 W art     : b60f2000-b60f3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b60f3000-b610e000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-24 13:23:41.917  6234  6234 W art     : b610e000-b610f000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-24 13:23:41.917  6234  6234 W art     : b610f000-b6110000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-24 13:23:41.917  6234  6234 W art     : b6110000-b6111000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b6111000-b615d000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 13:23:41.917  6234  6234 W art     : b615d000-b615e000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b615e000-b615f000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 13:23:41.917  6234  6234 W art     : b615f000-b6160000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 13:23:41.917  6234  6234 W art     : b6160000-b6161000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b6161000-b6165000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-24 13:23:41.917  6234  6234 W art     : b6165000-b6166000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6166000-b6167000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-24 13:23:41.917  6234  6234 W art     : b6167000-b6168000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-24 13:23:41.917  6234  6234 W art     : b6168000-b61a0000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-24 13:23:41.917  6234  6234 W art     : b61a0000-b61a1000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-24 13:23:41.917  6234  6234 W art     : b61a1000-b61a2000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-24 13:23:41.917  6234  6234 W art     : b61a2000-b61a3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b61a3000-b6241000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-24 13:23:41.917  6234  6234 W art     : b6241000-b6242000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6242000-b6260000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-24 13:23:41.917  6234  6234 W art     : b6260000-b6261000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-24 13:23:41.917  6234  6234 W art     : b6261000-b63d4000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-24 13:23:41.917  6234  6234 W art     : b63d4000-b63df000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-24 13:23:41.917  6234  6234 W art     : b63df000-b63e0000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-24 13:23:41.917  6234  6234 W art     : b63e0000-b64f7000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-24 13:23:41.917  6234  6234 W art     : b64f7000-b6502000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-24 13:23:41.917  6234  6234 W art     : b6502000-b6503000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-24 13:23:41.917  6234  6234 W art     : b6503000-b6507000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6507000-b652b000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-24 13:23:41.917  6234  6234 W art     : b652b000-b652d000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-24 13:23:41.917  6234  6234 W art     : b652d000-b652e000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-24 13:23:41.917  6234  6234 W art     : b652e000-b65d4000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-24 13:23:41.917  6234  6234 W art     : b65d4000-b65e1000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-24 13:23:41.917  6234  6234 W art     : b65e1000-b65e2000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-24 13:23:41.917  6234  6234 W art     : b65e2000-b65e3000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b65e3000-b6636000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-24 13:23:41.917  6234  6234 W art     : b6636000-b6637000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6637000-b6638000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-24 13:23:41.917  6234  6234 W art     : b6638000-b6639000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-24 13:23:41.917  6234  6234 W art     : b6639000-b663e000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b663e000-b6650000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-24 13:23:41.917  6234  6234 W art     : b6650000-b6651000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6651000-b6652000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-24 13:23:41.917  6234  6234 W art     : b6652000-b6653000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-24 13:23:41.917  6234  6234 W art     : b6653000-b665a000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 13:23:41.917  6234  6234 W art     : b665a000-b665b000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 13:23:41.917  6234  6234 W art     : b665b000-b665c000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 13:23:41.917  6234  6234 W art     : b665c000-b665d000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b665d000-b6660000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-24 13:23:41.917  6234  6234 W art     : b6660000-b6661000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-24 13:23:41.917  6234  6234 W art     : b6661000-b6662000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-24 13:23:41.917  6234  6234 W art     : b6662000-b6666000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-24 13:23:41.917  6234  6234 W art     : b6666000-b6667000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-24 13:23:41.917  6234  6234 W art     : b6667000-b6668000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-24 13:23:41.917  6234  6234 W art     : b6668000-b6676000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-24 13:23:41.917  6234  6234 W art     : b6676000-b6677000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6677000-b6678000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-24 13:23:41.917  6234  6234 W art     : b6678000-b6679000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-24 13:23:41.917  6234  6234 W art     : b6679000-b6682000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 13:23:41.917  6234  6234 W art     : b6682000-b6683000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 13:23:41.917  6234  6234 W art     : b6683000-b6684000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 13:23:41.917  6234  6234 W art     : b6684000-b66ea000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-24 13:23:41.917  6234  6234 W art     : b66ea000-b66eb000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b66eb000-b66ed000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-24 13:23:41.917  6234  6234 W art     : b66ed000-b66f6000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-24 13:23:41.917  6234  6234 W art     : b66f6000-b66f9000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b66f9000-b6790000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-24 13:23:41.917  6234  6234 W art     : b6790000-b6792000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-24 13:23:41.917  6234  6234 W art     : b6792000-b6793000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-24 13:23:41.917  6234  6234 W art     : b6793000-b6794000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6794000-b6ab5000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-24 13:23:41.917  6234  6234 W art     : b6ab5000-b6ab6000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6ab6000-b6ad1000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-24 13:23:41.917  6234  6234 W art     : b6ad1000-b6ad5000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-24 13:23:41.917  6234  6234 W art     : b6ad5000-b6ada000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6ada000-b6ae2000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 13:23:41.917  6234  6234 W art     : b6ae2000-b6ae3000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 13:23:41.917  6234  6234 W art     : b6ae3000-b6ae4000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 13:23:41.917  6234  6234 W art     : b6ae4000-b6b12000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-24 13:23:41.917  6234  6234 W art     : b6b12000-b6b13000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6b13000-b6b1a000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-24 13:23:41.917  6234  6234 W art     : b6b1a000-b6b1b000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-24 13:23:41.917  6234  6234 W art     : b6b1b000-b6b61000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-24 13:23:41.917  6234  6234 W art     : b6b61000-b6b62000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6b62000-b6b65000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-24 13:23:41.917  6234  6234 W art     : b6b65000-b6b66000 rw-p 000,49000 b3:17 1049       /system/lib/libinputflinger.so
08-24 13:23:41.917  6234  6234 W art     : b6b66000-b6b81000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-24 13:23:41.917  6234  6234 W art     : b6b81000-b6b85000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-24 13:23:41.917  6234  6234 W art     : b6b85000-b6b86000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-24 13:23:41.917  6234  6234 W art     : b6b86000-b6bd3000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-24 13:23:41.917  6234  6234 W art     : b6bd3000-b6bd4000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6bd4000-b6be0000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-24 13:23:41.917  6234  6234 W art     : b6be0000-b6be1000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-24 13:23:41.917  6234  6234 W art     : b6be1000-b6bee000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-24 13:23:41.917  6234  6234 W art     : b6bee000-b6bef000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6bef000-b6bf0000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-24 13:23:41.917  6234  6234 W art     : b6bf0000-b6bf1000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-24 13:23:41.917  6234  6234 W art     : b6bf1000-b6bf9000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-24 13:23:41.917  6234  6234 W art     : b6bf9000-b6bfa000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6bfa000-b6bfb000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-24 13:23:41.917  6234  6234 W art     : b6bfb000-b6bfc000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-24 13:23:41.917  6234  6234 W art     : b6bfc000-b6c03000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-24 13:23:41.917  6234  6234 W art     : b6c03000-b6c04000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-24 13:23:41.917  6234  6234 W art     : b6c04000-b6c05000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-24 13:23:41.917  6234  6234 W art     : b6c05000-b6c19000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-24 13:23:41.917  6234  6234 W art     : b6c19000-b6c1b000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-24 13:23:41.917  6234  6234 W art     : b6c1b000-b6c1c000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-24 13:23:41.917  6234  6234 W art     : b6c1c000-b6c44000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-24 13:23:41.917  6234  6234 W art     : b6c44000-b6c46000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-24 13:23:41.917  6234  6234 W art     : b6c46000-b6c47000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-24 13:23:41.917  6234  6234 W art     : b6c47000-b6c4a000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-24 13:23:41.917  6234  6234 W art     : b6c4a000-b6c4b000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-24 13:23:41.917  6234  6234 W art     : b6c4b000-b6c4c000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-24 13:23:41.917  6234  6234 W art     : b6c4c000-b6c55000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-24 13:23:41.917  6234  6234 W art     : b6c55000-b6c56000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-24 13:23:41.917  6234  6234 W art     : b6c56000-b6c57000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-24 13:23:41.917  6234  6234 W art     : b6c57000-b6c77000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-24 13:23:41.917  6234  6234 W art     : b6c77000-b6c78000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-24 13:23:41.917  6234  6234 W art     : b6c78000-b6c79000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-24 13:23:41.917  6234  6234 W art     : b6c79000-b6cec000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-24 13:23:41.917  6234  6234 W art     : b6cec000-b6cf0000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-24 13:23:41.917  6234  6234 W art     : b6cf0000-b6cf3000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-24 13:23:41.917  6234  6234 W art     : b6cf3000-b6cfd000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6cfd000-b6d85000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-24 13:23:41.917  6234  6234 W art     : b6d85000-b6d86000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6d86000-b6d8a000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-24 13:23:41.917  6234  6234 W art     : b6d8a000-b6d8b000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-24 13:23:41.917  6234  6234 W art     : b6d8b000-b6d8c000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6d8c000-b6db5000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-24 13:23:41.917  6234  6234 W art     : b6db5000-b6db6000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6db6000-b6db9000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-24 13:23:41.917  6234  6234 W art     : b6db9000-b6dba000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-24 13:23:41.917  6234  6234 W art     : b6dba000-b6e94000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 13:23:41.917  6234  6234 W art     : b6e94000-b6e9b000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 13:23:41.917  6234  6234 W art     : b6e9b000-b6ea3000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 13:23:41.917  6234  6234 W art     : b6ea3000-b6ea4000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6ea4000-b6ea5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:23:41.917  6234  6234 W art     : b6ea5000-b6ea6000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-24 13:23:41.917  6234  6234 W art     : b6ea6000-b6ea7000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b6ea7000-b6eaa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b6eaa000-b6ecf000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-24 13:23:41.917  6234  6234 W art     : b6ecf000-b6ed0000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6ed0000-b6ed7000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-24 13:23:41.917  6234  6234 W art     : b6ed7000-b6ed8000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-24 13:23:41.917  6234  6234 W art     : b6ed8000-b6edf000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-24 13:23:41.917  6234  6234 W art     : b6edf000-b6ee0000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-24 13:23:41.917  6234  6234 W art     : b6ee0000-b6ee1000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-24 13:23:41.917  6234  6234 W art     : b6ee1000-b6ee2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b6ee2000-b6efa000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-24 13:23:41.917  6234  6234 W art     : b6efa000-b6efb000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6efb000-b6efc000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-24 13:23:41.917  6234  6234 W art     : b6efc000-b6efd000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-24 13:23:41.917  6234  6234 W art     : b6efd000-b6f0b000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-24 13:23:41.917  6234  6234 W art     : b6f0b000-b6f0c000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6f0c000-b6f0d000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-24 13:23:41.917  6234  6234 W art     : b6f0d000-b6f0e000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-24 13:23:41.917  6234  6234 W art     : b6f0e000-b6f0f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:23:41.917  6234  6234 W art     : b6f0f000-b6f11000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b6f11000-b6f12000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b6f12000-b6f13000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:23:41.917  6234  6234 W art     : b6f13000-b6f14000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-24 13:23:41.917  6234  6234 W art     : b6f14000-b6f15000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:23:41.917  6234  6234 W art     : b6f15000-b6f35000 r--s 00000000 00:0b 9219       /dev/__properties__
08-24 13:23:41.917  6234  6234 W art     : b6f35000-b6f36000 r--p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6f36000-b6f37000 ---p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6f37000-b6f39000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-24 13:23:41.917  6234  6234 W art     : b6f39000-b6f3a000 r-xp 00000000 00:00 0          [sigpage]
08-24 13:23:41.917  6234  6234 W art     : b6f3a000-b6f55000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-24 13:23:41.917  6234  6234 W art     : b6f55000-b6f56000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-24 13:23:41.917  6234  6234 W art     : b6f56000-b6f58000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-24 13:23:41.917  6234  6234 W art     : b6f58000-b6f5a000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : b6f5a000-b6f5f000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-24 13:23:41.917  6234  6234 W art     : b6f5f000-b6f60000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-24 13:23:41.917  6234  6234 W art     : b6f60000-b6f61000 rw-p 00000000 00:00 0 
08-24 13:23:41.917  6234  6234 W art     : bef76000-bef97000 rw-p 00000000 00:00 0          [stack]
08-24 13:23:41.917  6234  6234 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-24 13:23:41.937  6330  6330 E Zygote  : v2
08-24 13:23:41.937  6330  6330 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:41.937  6330  6330 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:41.937  6330  6330 E Zygote  : accessInfo : 0
08-24 13:23:41.937  6330  6330 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-24 13:23:41.937  1831  6327 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-24 13:23:41.987  6234  6234 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 13:23:42.007  6330  6330 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:42.007  6330  6330 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:42.017   755  1492 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13c0871 6330:com.samsung.android.sm.devicesecurity/5012}
08-24 13:23:42.037  6330  6330 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-24 13:23:42.047  1831  6327 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-24 13:23:42.047  6330  6330 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-24 13:23:42.047  6234  6234 I Radio-JNI: register_android_hardware_Radio DONE
08-24 13:23:42.057  6234  6234 E AffinityControl: AffinityControl: registerfunction enter
08-24 13:23:42.087  1831  6327 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-24 13:23:42.087  6234  6234 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 13:23:42.107   755  1756 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-24 13:23:42.127   755  1756 D ActivityManager: mDVFSHelper.acquire()
08-24 13:23:42.127   755  1756 V WindowManager: addAppToken: AppWindowToken{bd61bc4 token=Token{c1186d7 ActivityRecord{9883656 u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-24 13:23:42.137   755   894 D SecWifiDisplayUtil: Metadata value : none
08-24 13:23:42.137   755   894 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a1b1f5c V.E...... R.....ID 0,0-0,0}
08-24 13:23:42.137  6349  6349 E Zygote  : v2
08-24 13:23:42.137  6349  6349 I libpersona: KNOX_SDCARD checking this for 10004
08-24 13:23:42.137   755   894 D ISSUE_DEBUG: InputChannelName : a114b3a Starting com.test.thalitest
08-24 13:23:42.137  6349  6349 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:42.137  6349  6349 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:42.147  6349  6349 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:42.147   755  1756 I ActivityManager: Start proc 6349:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-24 13:23:42.147  6349  6349 E Zygote  : accessInfo : 0
08-24 13:23:42.147  6349  6349 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-24 13:23:42.147   755  1756 D InputDispatcher: Focused application set to: xxxx
08-24 13:23:42.147   755  1756 D InputDispatcher: Focus left window: 4377
08-24 13:23:42.147  6234  6234 D AndroidRuntime: Shutting down VM
08-24 13:23:42.157   293   293 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-24 13:23:42.167   755   894 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:755 uid:1000
08-24 13:23:42.167   755   894 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 13:23:42.167   755   894 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:755 uid:1000
08-24 13:23:42.167   755   894 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-24 13:23:42.167   755   894 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-24 13:23:42.177   755  1586 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee11484 3181:com.android.contacts/u0a19}
08-24 13:23:42.177   755   848 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{8e404 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-24 13:23:42.177  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-24 13:23:42.187   755   768 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-24 13:23:42.207  6349  6349 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:42.207  6349  6349 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:42.207   755  1410 I ActivityManager: Start proc 6361:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-24 13:23:42.207  6361  6361 E Zygote  : v2
08-24 13:23:42.207  6361  6361 I libpersona: KNOX_SDCARD checking this for 10049
08-24 13:23:42.207  6361  6361 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:42.207  6361  6361 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:42.207  6361  6361 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:42.217  6361  6361 E Zygote  : accessInfo : 0
08-24 13:23:42.217   755   894 V WindowStateAnimator: Finishing drawing window Window{a114b3a u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-24 13:23:42.217  6361  6361 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-24 13:23:42.227   755  1905 V WindowOrientationListener: setCurrentAppOrientation :-1
08-24 13:23:42.227   755  1905 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-24 13:23:42.227   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8fe364
08-24 13:23:42.257  6361  6361 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:42.257  6361  6361 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:42.267   755  1905 D ActivityManager:  Launching com.test.thalitest, updated priority
08-24 13:23:42.287  4377  4377 V ActivityThread: updateVisibility : ActivityRecord{6281af1 token=android.os.BinderProxy@b63577c {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-24 13:23:42.287  1743  1859 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-24 13:23:42.287  1743  1743 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-24 13:23:42.297   293  1807 D libEGL  : eglTerminate EGLDisplay = 0xb476f64c
08-24 13:23:42.297   293  1807 D libEGL  : eglTerminate EGLDisplay = 0xb476f64c
08-24 13:23:42.297   293  4975 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
08-24 13:23:42.297   293   356 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
08-24 13:23:42.307   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8fe3a4
08-24 13:23:42.317   293  1807 I SurfaceFlinger: id=19 Removed YUIInstallC (5/9)
08-24 13:23:42.327   293  4975 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/9)
08-24 13:23:42.327   755   848 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a114b3a u0 d0 Starting com.test.thalitest}
08-24 13:23:42.327  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-24 13:23:42.337  6349  6349 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-24 13:23:42.337   755  1642 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{159fdf4 6361:com.android.mms/u0a49}
08-24 13:23:42.337   755   846 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-24 13:23:42.347   755  3404 D M       : limitCPUFreq:: freq = -1
08-24 13:23:42.347   755  3404 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 755  tag : SIOP_ARM_MAX@25
08-24 13:23:42.347   755  3404 D M       : limitGPUFreq:: freq = -1
08-24 13:23:42.367  1743  1743 V ActivityThread: updateVisibility : ActivityRecord{5c28b5b token=android.os.BinderProxy@e0bf1c5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 13:23:42.367  1743  1743 D Launcher: onTrimMemory. Level: 20
08-24 13:23:42.367  2083  2094 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
,08-24 13:23:42.387   755  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 13:23:42.397  6349  6349 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 13:23:42.397  6349  6349 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 13:23:42.417  6349  6349 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-24 13:23:42.427  2801  6374 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-24 13:23:42.427  6361  6361 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 13:23:42.447  6349  6349 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-24 13:23:42.467  6349  6349 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 13:23:42.477  6349  6349 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 5138-5142)
,08-24 13:23:42.477  6349  6349 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-24 13:23:42.487   755   765 I art     : Background partial concurrent mark sweep GC freed 50332(2MB) AllocSpace objects, 9(320KB) LOS objects, 27% free, 42MB/58MB, paused 2.701ms total 174.963ms
,08-24 13:23:42.487  6361  6361 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-24 13:23:42.497  6349  6349 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32711cc}
,08-24 13:23:42.497  6349  6349 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-24 13:23:42.497  6349  6349 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 13:23:42.507  6349  6377 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-24 13:23:42.507  6349  6349 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 13:23:42.527  6361  6361 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-24 13:23:42.547  1831  6327 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 604 ms] updated apps [took 604 ms] 
,08-24 13:23:42.547  6349  6349 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 13:23:42.547  6349  6349 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 13:23:42.547  6349  6349 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 13:23:42.547  6349  6349 I Adreno-EGL: Local Branch: ss
08-24 13:23:42.547  6349  6349 I Adreno-EGL: Remote Branch: 
08-24 13:23:42.547  6349  6349 I Adreno-EGL: Local Patches: 
08-24 13:23:42.547  6349  6349 I Adreno-EGL: Reconstruct Branch: 
,08-24 13:23:42.557  6349  6349 D libEGL  : eglInitialize EGLDisplay = 0xbe813dac
,08-24 13:23:42.577  6361  6361 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-24 13:23:42.587  6361  6382 D Mms/ArtClassLoader: init before art first
,08-24 13:23:42.587  6361  6383 D Mms/ArtClassLoader: init before art second
,08-24 13:23:42.587   755  1757 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-24 13:23:42.597   755  1757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-24 13:23:42.617  6361  6361 D Mms/TelephonyPermission: start operation mode monitor
,08-24 13:23:42.627  6361  6361 D Mms/TelephonyPermission: User ID is null set current User Id
,08-24 13:23:42.627  6361  6384 D Mms/ArtClassLoader: init before art third
,08-24 13:23:42.637  6361  6384 D Mms/ArtClassLoader: init [DONE] art
,08-24 13:23:42.647  6361  6361 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 13:23:42.647  6361  6361 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-24 13:23:42.657  6349  6349 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-24 13:23:42.667  6349  6349 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 13:23:42.667  6349  6349 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-24 13:23:42.667  6349  6349 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-24 13:23:42.667  6349  6349 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-24 13:23:42.677  6361  6361 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-24 13:23:42.677  6361  6361 D Mms/TelephonyPermission: isDefault true
,08-24 13:23:42.677  6361  6361 D Mms/MmsApp: onCreate() com.android.mms
,08-24 13:23:42.687  6349  6349 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-24 13:23:42.697  6349  6349 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-24 13:23:42.707  6361  6361 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-24 13:23:42.707  6361  6361 D Mms/MmsApp: [start]    initCountryIso consume time = 132.798801
,08-24 13:23:42.717   755  1410 D CountryDetector: The first listener is added
,08-24 13:23:42.717  6361  6361 D Mms/MmsApp: [end]    initCountryIso consume time = 9.493021
08-24 13:23:42.717  6361  6361 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.108073
,08-24 13:23:42.747  6361  6361 D Mms/MmsConfig: before partial update
,08-24 13:23:42.757  6361  6382 D Mms/ArtClassLoader: init [DONE] art
,08-24 13:23:42.757  6349  6349 D SecWifiDisplayUtil: Metadata value : none
,08-24 13:23:42.767  6361  6383 D Mms/ArtClassLoader: init [DONE] art
,08-24 13:23:42.767  6349  6349 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{413768a I.E...... R.....ID 0,0-0,0}
,08-24 13:23:42.767  6349  6408 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 13:23:42.767   755   768 D ISSUE_DEBUG: InputChannelName : 8df6bb5 com.test.thalitest/com.test.thalitest.MainActivity
,08-24 13:23:42.777   755  1757 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-24 13:23:42.777   755  1757 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-24 13:23:42.777   755   755 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-24 13:23:42.777   755   755 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-24 13:23:42.787  6349  6349 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6349
,08-24 13:23:42.787   755  1218 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6349 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 13:23:42.787   755  1331 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-24 13:23:42.787   755  1331 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 13:23:42.787   755  1331 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-24 13:23:42.787   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-24 13:23:42.797   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 13:23:42.797   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-24 13:23:42.797   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-24 13:23:42.797   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-24 13:23:42.797  6361  6361 D Mms/MmsConfig: Load Resize quality : 80
,08-24 13:23:42.797   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-24 13:23:42.797   755  1331 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 13:23:42.797  6361  6361 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 13:23:42.797  6361  6361 D EasySignUpManager_1.0.5: isAuth is false
08-24 13:23:42.797  6361  6361 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-24 13:23:42.797  6361  6361 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-24 13:23:42.807  6349  6349 D SecWifiDisplayUtil: Metadata value : none
08-24 13:23:42.807  6361  6361 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-24 13:23:42.807  6361  6361 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 13:23:42.807  6361  6361 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-24 13:23:42.807  6361  6361 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-24 13:23:42.807  6361  6361 D EasySignUpManager_1.0.5: isAuth is false
08-24 13:23:42.807  6361  6361 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-24 13:23:42.807  6361  6361 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
08-24 13:23:42.807  6349  6377 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-24 13:23:42.817   293   293 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-24 13:23:42.817  1730  1741 D TP/MmsSmsProvider: query, match:2117, calling pid = 6361, accessRestricted = false
,08-24 13:23:42.817  1730  1741 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 0.937 ms
,08-24 13:23:42.827  6361  6361 E CscParser: mps_code.dat does not exist
08-24 13:23:42.827  6361  6361 E CscParser: customer_path =/system/csc/customer.xml
08-24 13:23:42.827  6361  6361 E CscParser: fileName + /system/csc/customer.xml
,08-24 13:23:42.827   755  1641 D InputDispatcher: Focus entered window: 6349
,08-24 13:23:42.827   755   894 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:755 uid:1000
,08-24 13:23:42.827   755   894 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 13:23:42.827  6349  6408 D libEGL  : eglInitialize EGLDisplay = 0x9caba7c4
08-24 13:23:42.827  6349  6408 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 13:23:42.827   755   894 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:755 uid:1000
08-24 13:23:42.827   755   894 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-24 13:23:42.837  6361  6361 E CscParser: mps_code.dat does not exist
08-24 13:23:42.837  6361  6361 E CscParser: customer_path =/system/csc/customer.xml
08-24 13:23:42.837  6361  6361 E CscParser: fileName + /system/csc/customer.xml
,08-24 13:23:42.847  6361  6361 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-24 13:23:42.847  6361  6361 D Mms/MmsConfig:  enable multiwindow = true
,08-24 13:23:42.847  6361  6361 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-24 13:23:42.847  6361  6361 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-24 13:23:42.847  6361  6361 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-24 13:23:42.847  6361  6361 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-24 13:23:42.847  6361  6361 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-24 13:23:42.847  6361  6361 E Mms/MessageUtils: setCountryDetector : update country detector info 
,08-24 13:23:42.847  6361  6361 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-24 13:23:42.857  6361  6361 D Mms/MmsConfig: [end]    init() consume time = 132.212709
,08-24 13:23:42.857  6361  6361 D Mms/Contact: [start]    init() consume time = 3.85151
,08-24 13:23:42.867  1730  2081 D TP/MmsSmsProvider: query, match:13, calling pid = 6361, accessRestricted = false
,08-24 13:23:42.867  1730  2081 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.403 ms
,08-24 13:23:42.877  6349  6349 V ActivityThread: updateVisibility : ActivityRecord{b0f71ad token=android.os.BinderProxy@bb018f5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-24 13:23:42.887  6361  6361 D Mms/Contact: [end]    init consume time = 24.82099
,08-24 13:23:42.887  6349  6349 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-24 13:23:42.887  6349  6349 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 13:23:42.897  6361  6361 D Mms:transaction: roaming -> false (slotId = 0)
08-24 13:23:42.897  6361  6361 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 13:23:42.897  6361  6361 D Mms:transaction: auto download without roaming -> true
08-24 13:23:42.897  6361  6361 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-24 13:23:42.897  6361  6361 D Mms:transaction: roaming -> false (slotId = 1)
08-24 13:23:42.897  6361  6361 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-24 13:23:42.897  6361  6361 D Mms:transaction: auto download without roaming -> true
08-24 13:23:42.897  6361  6361 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-24 13:23:42.897  6361  6361 D Mms:transaction: auto download during roaming secondary -> false
08-24 13:23:42.897  6361  6361 D Mms:transaction: mAutoDownload ------> true
,08-24 13:23:42.897  6361  6416 D Mms/DraftCache: [start]    rebuildCache consume time = 18.506093
,08-24 13:23:42.907  1730  1742 D TP/MmsSmsProvider: query, match:12, calling pid = 6361, accessRestricted = false
08-24 13:23:42.907  1730  1742 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.856 ms
,08-24 13:23:42.917   755  1905 V WindowStateAnimator: Finishing drawing window Window{8df6bb5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-24 13:23:42.917  6349  6349 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-24 13:23:42.917   755  1757 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-24 13:23:42.917   755   894 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-24 13:23:42.917   755   755 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-24 13:23:42.917   755   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +598ms (total +795ms)
08-24 13:23:42.927   755   755 I KnoxTimeoutHandler: SD activityfalse
,08-24 13:23:42.927   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8fe364
,08-24 13:23:42.927   755   894 D ActivityManager: mDVFSHelper.release()
,08-24 13:23:42.927   755   894 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9883656 u0 com.test.thalitest/.MainActivity t168} time:105597
,08-24 13:23:42.937   755   894 D ViewRootImpl: #3 mView = null
,08-24 13:23:42.937   293   356 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
,08-24 13:23:42.937   293  1807 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,08-24 13:23:42.947   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8fe3a4
,08-24 13:23:42.947  6349  6349 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-24 13:23:42.947  6349  6349 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@bb018f5 time:105616
,08-24 13:23:42.957  6361  6416 D Mms/DraftCache: [end]    rebuildCache consume time = 55.335938
,08-24 13:23:42.977  6349  6420 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 13:23:42.977  6349  6420 D libEGL  : eglInitialize EGLDisplay = 0x9b3ed3ec
,08-24 13:23:42.977  6361  6361 D ComposerPerformance: 1472037822989 ms / [DONE] Composer constructor
,08-24 13:23:42.977  6361  6361 D CII     : Log Level [5]
08-24 13:23:42.977  6361  6361 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-24 13:23:42.977  6361  6422 D Mms/Conversation: [start]    init() consume time = 23.876041
,08-24 13:23:42.977  1730  2081 D TP/MmsSmsProvider: delete, match:1, calling pid = 6361
,08-24 13:23:42.977  1730  2081 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-24 13:23:42.977  1730  2081 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-24 13:23:42.987  6361  6361 I Mms/ReservationManager: ReservationManager()
,08-24 13:23:42.987  6361  6361 I Mms/ReservationManager: resetAfterConnected()
08-24 13:23:42.987  1730  2081 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-24 13:23:42.987  1730  2081 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,08-24 13:23:42.987  1730  2081 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-24 13:23:42.987  1730  2081 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-24 13:23:42.997  1730  1968 D TP/MmsSmsProvider: query, match:7, calling pid = 6361, accessRestricted = false
,08-24 13:23:42.997  1730  1968 D TP/MmsSmsProvider: query, match 7:Elapsed time : 4.082 ms
,08-24 13:23:42.997  6361  6361 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-24 13:23:43.007  1730  2081 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
,08-24 13:23:43.007  1730  2081 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-24 13:23:43.007  1730  2081 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-24 13:23:43.007  1730  2081 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 7.909 ms
08-24 13:23:43.007  1730  2081 D TP/MmsSmsProvider: need read changed broadcast:false
,08-24 13:23:43.007  6361  6422 D Mms/Conversation: [end]    init consume time = 24.100417
,08-24 13:23:43.007  6361  6422 D Mms/MessagingNotification: [start]    init() consume time = 2.464531
,08-24 13:23:43.007  6361  6361 D Mms/MmsApp: [end]    onCreate() consume time = 1.22599
08-24 13:23:43.007  6361  6361 D Mms/MmsApp: [end]    onCreate() consume time = 0.233906
,08-24 13:23:43.007  6361  6422 D Mms/MessagingNotification: [end]    init consume time = 0.957917
08-24 13:23:43.007  6361  6361 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-24 13:23:43.007  6361  6361 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-24 13:23:43.007  6361  6361 D Mms:transaction: roaming -> false (slotId = 0)
08-24 13:23:43.007  6361  6361 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 13:23:43.007  6361  6361 D Mms:transaction: auto download without roaming -> true
,08-24 13:23:43.017  6361  6361 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-24 13:23:43.017  6361  6361 D Mms:transaction: mAutoDownload ------> true
,08-24 13:23:43.017  6424  6424 E Zygote  : v2
08-24 13:23:43.017  6424  6424 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:23:43.017  6424  6424 I libpersona: KNOX_SDCARD not a persona
,08-24 13:23:43.017   755  1642 I ActivityManager: Start proc 6424:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
08-24 13:23:43.017  6424  6424 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:43.017  6424  6424 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 13:23:43.027   755  1642 I ActivityManager: Killing 5063:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-24 13:23:43.027  6424  6424 E Zygote  : accessInfo : 0
,08-24 13:23:43.037  6349  6349 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6349
,08-24 13:23:43.037  6361  6436 D Mms/Synchronizer: [start]    doSync consume time = 32.001354
,08-24 13:23:43.047  6361  6435 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 8.414479
,08-24 13:23:43.057  6424  6424 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:43.057  1730  1741 D TP/MmsSmsProvider: query, match:0, calling pid = 6361, accessRestricted = false
08-24 13:23:43.057  1730  1741 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-24 13:23:43.057  6424  6424 D ActivityThread: Added TimaKeyStore provider
,08-24 13:23:43.057  1730  1741 D TP/MmsSmsProvider: query, match 0:Elapsed time : 0.909 ms
,08-24 13:23:43.067  1730  1968 D TP/MmsSmsProvider: query, match:400, calling pid = 6361, accessRestricted = false
,08-24 13:23:43.077  1730  1742 D TP/MmsSmsProvider: update, match:300, calling pid = 6361
08-24 13:23:43.077  1730  1742 V TP/MmsSmsProvider: syncDBData start
,08-24 13:23:43.077   755  1748 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{721c1fa 6424:com.samsung.android.bbc.bbcagent/1000}
,08-24 13:23:43.077  1730  1742 V TP/MmsSmsProvider: syncDBData sms end
,08-24 13:23:43.077  1730  1742 V TP/MmsSmsProvider: syncDBData mms end
,08-24 13:23:43.077  1730  1742 V TP/MmsSmsProvider: syncDBData end
,08-24 13:23:43.077  1730  1742 D TP/MmsSmsProvider: update, match 300:Elapsed time : 3.618 ms
,08-24 13:23:43.077   755  1757 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-24 13:23:43.087  6361  6436 D Mms/Synchronizer: [end]    doSync consume time = 37.815417
,08-24 13:23:43.087  6361  6435 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 1.422552
,08-24 13:23:43.097  6424  6424 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-24 13:23:43.097  6007  6019 D BadgeProvider: query, [selection] : package=?
,08-24 13:23:43.097  6361  6422 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-24 13:23:43.117  1730  1968 D TP/SmsProvider: query,matched:26, calling pid = 6361
,08-24 13:23:43.117  1730  1968 D TP/SmsProvider: query, match 26:Elapsed time : 1.873 ms
,08-24 13:23:43.117  6424  6424 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-24 13:23:43.137  1730  2081 D TP/MmsSmsProvider: query, match:6, calling pid = 6361, accessRestricted = false
,08-24 13:23:43.137  1730  2081 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.315 ms
,08-24 13:23:43.177  6440  6440 E Zygote  : v2
08-24 13:23:43.177  6440  6440 I libpersona: KNOX_SDCARD checking this for 10024
08-24 13:23:43.177  6440  6440 I libpersona: KNOX_SDCARD not a persona
,08-24 13:23:43.177   755  1642 I ActivityManager: Start proc 6440:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-24 13:23:43.177  6440  6440 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:43.177  6440  6440 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 13:23:43.177  6440  6440 E Zygote  : accessInfo : 0
,08-24 13:23:43.177  6440  6440 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-24 13:23:43.187  6446  6446 E Zygote  : v2
,08-24 13:23:43.187  6446  6446 I libpersona: KNOX_SDCARD checking this for 10097
08-24 13:23:43.187   755  1218 I ActivityManager: Start proc 6446:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-24 13:23:43.187  6446  6446 I libpersona: KNOX_SDCARD not a persona
,08-24 13:23:43.187  6446  6446 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 13:23:43.187  6446  6446 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:43.187   755  1218 I ActivityManager: Killing 5051:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-24 13:23:43.197  6446  6446 E Zygote  : accessInfo : 0
,08-24 13:23:43.197  6446  6446 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-24 13:23:43.217  6446  6446 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:43.217  6446  6446 D ActivityThread: Added TimaKeyStore provider
,08-24 13:23:43.227  6440  6440 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:43.227  6440  6440 D ActivityThread: Added TimaKeyStore provider
,08-24 13:23:43.227  6349  6349 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 13:23:43.237   755  1410 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3d5f3ab 6446:com.google.android.apps.docs/u0a97}
,08-24 13:23:43.237   755  1756 I ActivityManager: Killing 5100:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-24 13:23:43.247   755  1757 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-24 13:23:43.247  6446  6446 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-24 13:23:43.267   755   768 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-24 13:23:43.267  6440  6440 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-24 13:23:43.277  6446  6446 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-24 13:23:43.287  6440  6440 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-24 13:23:43.337  6349  6464 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1697384144
,08-24 13:23:43.347  6349  6464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 13:23:43.347  6349  6464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 13:23:43.347  6349  6464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 13:23:43.347  6349  6464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 13:23:43.347  6349  6464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 13:23:43.347  6349  6464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c7d2eb added. We now have 1 listener(s)
,08-24 13:23:43.347   755  3408 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-24 13:23:43.347  6349  6464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-24 13:23:43.347  6349  6464 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
08-24 13:23:43.347  6440  6440 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-24 13:23:43.357  6349  6464 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 13:23:43.357  6349  6464 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-24 13:23:43.357  6349  6464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cefdc06 added. We now have 1 listener(s)
08-24 13:23:43.357  6349  6464 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 13:23:43.357  6349  6464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 13:23:43.357  6349  6464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 13:23:43.357  6349  6464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 13:23:43.357  6349  6464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 13:23:43.357  6349  6464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 13:23:43.367  6349  6464 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 13:23:43.367  6349  6464 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-24 13:23:43.367  6361  6422 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-24 13:23:43.367  6349  6464 D BluetoothAdapter: STATE_ON
,08-24 13:23:43.377  6349  6464 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 13:23:43.377  6349  6464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:23:43.377  6349  6464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:23:43.377  6349  6464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 13:23:43.377  6349  6464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:23:43.377  6349  6464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:23:43.377  6349  6464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:23:43.377  6349  6464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:23:43.377  6349  6464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 13:23:43.377  6349  6464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-24 13:23:43.377  6349  6464 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 13:23:43.377  6349  6464 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 13:23:43.377  6349  6349 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 13:23:43.377  6349  6349 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 13:23:43.397  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-24 13:23:43.397  6349  6349 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 13:23:43.397  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-24 13:23:43.397  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-24 13:23:43.397  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-24 13:23:43.407  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-24 13:23:43.407  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-24 13:23:43.407  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-24 13:23:43.407  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-24 13:23:43.407  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-24 13:23:43.407  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-24 13:23:43.407  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-24 13:23:43.407  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-24 13:23:43.417  6440  6440 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-24 13:23:43.417   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:23:43.527   755  6145 I HarmonyEASService: Updating for all 1
,08-24 13:23:43.527  2801  4993 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-24 13:23:43.587  2801  4993 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-24 13:23:43.637  2801  4993 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-24 13:23:43.637  6446  6468 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-24 13:23:43.637  6446  6468 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 13:23:43.637  6446  6468 I GAv4    :   adb logcat -s GAv4
,08-24 13:23:43.657  6446  6468 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
08-24 13:23:43.657   755  1410 V AlarmManager:  remove PendingIntent] PendingIntent{986a7d9: PendingIntentRecord{4fc59e com.google.android.apps.docs broadcastIntent}}
08-24 13:23:43.657  6446  6468 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-24 13:23:43.667  6446  6468 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-24 13:23:43.687  6446  6474 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-24 13:23:43.737  6446  6446 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
08-24 13:23:43.737  6446  6446 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
08-24 13:23:43.777  6446  6468 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-24 13:23:43.777  6446  6468 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-24 13:23:43.777  6446  6468 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-24 13:23:43.777  6446  6468 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
08-24 13:23:43.777  1451  1451 D Recents : onTaskStackChanged
08-24 13:23:43.777  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
08-24 13:23:43.807  6480  6480 E Zygote  : v2
08-24 13:23:43.807  6480  6480 I libpersona: KNOX_SDCARD checking this for 10098
08-24 13:23:43.807  6480  6480 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:43.807  6480  6480 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:43.807  6480  6480 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:43.807  6480  6480 E Zygote  : accessInfo : 0
08-24 13:23:43.807  6480  6480 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
08-24 13:23:43.807   755  1218 I ActivityManager: Start proc 6480:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-24 13:23:43.807   755  1218 I ActivityManager: Killing 5413:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
08-24 13:23:43.827   755  1756 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
08-24 13:23:43.837  6480  6480 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:43.837  6480  6480 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:43.847   755  1641 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{46e9daa 6480:com.sec.android.automotive.drivelink/u0a98}
08-24 13:23:43.857  2033  2033 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-24 13:23:43.857  6480  6480 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
08-24 13:23:43.857  2033  2033 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-24 13:23:43.887  6480  6480 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
08-24 13:23:43.897  2033  2033 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-24 13:23:43.927  6480  6480 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
08-24 13:23:43.937   755  1218 V AlarmManager:  remove PendingIntent] PendingIntent{c793802: PendingIntentRecord{239a513 com.sec.android.automotive.drivelink broadcastIntent}}
08-24 13:23:43.947  6480  6496 I GMPM    : App measurement is starting up
08-24 13:23:43.947  6480  6480 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
08-24 13:23:43.947  6480  6496 E GMPM    : getGoogleAppId failed with status: 10
08-24 13:23:43.947  6480  6496 E GMPM    : Uploading is not possible. App measurement disabled
08-24 13:23:43.957   755  1642 V AlarmManager:  remove PendingIntent] PendingIntent{2894350: PendingIntentRecord{239a513 com.sec.android.automotive.drivelink broadcastIntent}}
08-24 13:23:43.957  6446  6469 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
08-24 13:23:43.977  6480  6480 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
08-24 13:23:43.977  6480  6480 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
08-24 13:23:43.997  6446  6469 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
08-24 13:23:44.027  6446  6469 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-24 13:23:44.027  6446  6469 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
08-24 13:23:44.027  6446  6469 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
08-24 13:23:44.027  6502  6502 E Zygote  : v2
08-24 13:23:44.027  6502  6502 I libpersona: KNOX_SDCARD checking this for 10032
08-24 13:23:44.027  6502  6502 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:44.027  6502  6502 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:44.027  6502  6502 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:44.037  6502  6502 E Zygote  : accessInfo : 0
08-24 13:23:44.037  6502  6502 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
08-24 13:23:44.037   755  1905 I ActivityManager: Start proc 6502:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
08-24 13:23:44.037   755  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-24 13:23:44.057  6502  6502 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:44.057  6502  6502 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:44.057   755  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-24 13:23:44.067  6446  6469 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-24 13:23:44.067  6502  6502 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
08-24 13:23:44.097  6502  6502 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
08-24 13:23:44.177  6480  6480 D [CarMode]: [DLAppUiUpdater]-test local  en_US
08-24 13:23:44.187  6480  6480 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
08-24 13:23:44.187  6480  6480 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
08-24 13:23:44.207  6480  6480 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDWed Aug 24 13:23:44 GMT+02:00 2016
08-24 13:23:44.217   755  1642 I ActivityManager: Start proc 6517:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-24 13:23:44.217  6517  6517 E Zygote  : v2
08-24 13:23:44.217  6517  6517 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:23:44.217  6517  6517 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:44.217  6517  6517 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:44.217  6517  6517 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:44.217  6517  6517 E Zygote  : accessInfo : 0
08-24 13:23:44.217   755  1642 I ActivityManager: Killing 5382:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
08-24 13:23:44.217   755  1642 I ActivityManager: Killing 4994:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
08-24 13:23:44.237  6480  6480 D DialogFlow: initQueue()
08-24 13:23:44.237  6517  6517 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:44.237  6517  6517 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:44.257   755  1905 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc7447c 6517:com.samsung.android.app.filterinstaller/1000}
08-24 13:23:44.257   755   768 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
08-24 13:23:44.257  6502  6502 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
08-24 13:23:44.267  6517  6517 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
08-24 13:23:44.267   755  1492 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
08-24 13:23:44.287  6349  6465 W jxcore-log: Initializing JXcore engine
08-24 13:23:44.287  6349  6465 W jxcore-log: JXcore engine is ready
08-24 13:23:44.297  6502  6502 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
08-24 13:23:44.297  6517  6517 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
08-24 13:23:44.307  6517  6517 E FilterPackageIntentReceiver: This package is not a effect filter
08-24 13:23:44.317  6530  6530 E Zygote  : v2
08-24 13:23:44.317  6530  6530 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:23:44.317  6530  6530 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:44.317   755  1641 I ActivityManager: Start proc 6530:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-24 13:23:44.317  6530  6530 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:44.317  6530  6530 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:44.317  6530  6530 E Zygote  : accessInfo : 0
08-24 13:23:44.317   755  1641 I ActivityManager: Killing 5518:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
08-24 13:23:44.327   755  1748 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
08-24 13:23:44.337  2205  2205 E audit   : type=1400 msg=audit(1472037824.337:287): avc:  denied  { ioctl } for  pid=6465 comm="Thread-895" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 13:23:44.337  2205  2205 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:44.337  2205  2205 E audit   : type=1300 msg=audit(1472037824.337:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=98f043c8 items=0 ppid=352 ppcomm=main pid=6465 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-895" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-24 13:23:44.337  2205  2205 E audit   : type=1327 msg=audit(1472037824.337:287): proctitle="com.test.thalitest"
08-24 13:23:44.337  2205  2205 E audit   : type=1320 msg=audit(1472037824.337:287): 
08-24 13:23:44.337  2205  2205 E audit   : type=1400 msg=audit(1472037824.337:288): avc:  denied  { ioctl } for  pid=6465 comm="Thread-895" path="socket:[40306]" dev="sockfs" ino=40306 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-24 13:23:44.337  2205  2205 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:44.337  2205  2205 E audit   : type=1300 msg=audit(1472037824.337:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=98f043c8 items=0 ppid=352 ppcomm=main pid=6465 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-895" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-24 13:23:44.337  2205  2205 E audit   : type=1327 msg=audit(1472037824.337:288): proctitle="com.test.thalitest"
08-24 13:23:44.337  2205  2205 E audit   : type=1320 msg=audit(1472037824.337:288): 
08-24 13:23:44.347  6530  6530 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:44.347  6530  6530 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:44.347  6349  6465 W jxcore-log: Starting JXcore engine
08-24 13:23:44.357   755  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e822c68 6530:com.samsung.helphub/1000}
08-24 13:23:44.357  6530  6530 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
08-24 13:23:44.367   755  1492 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
08-24 13:23:44.377  6530  6530 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
08-24 13:23:44.387  6502  6502 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
08-24 13:23:44.387  6502  6502 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
08-24 13:23:44.397  6502  6502 D DialogFlow: initQueue()
08-24 13:23:44.417   755  1756 I ActivityManager: Start proc 6545:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-24 13:23:44.417  6545  6545 E Zygote  : v2
08-24 13:23:44.417  6545  6545 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:23:44.417  6545  6545 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:44.417  6545  6545 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:44.417  6545  6545 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:44.417   755  1756 I ActivityManager: Killing 5242:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
08-24 13:23:44.417  6545  6545 E Zygote  : accessInfo : 0
08-24 13:23:44.437   755   768 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
08-24 13:23:44.437  6349  6465 W jxcore-log: Platform android
08-24 13:23:44.437  6349  6465 W jxcore-log: 
08-24 13:23:44.437  6349  6465 W jxcore-log: Process ARCH arm
08-24 13:23:44.437  6349  6465 W jxcore-log: 
08-24 13:23:44.447  6545  6545 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:44.447  6545  6545 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:44.447   755  1642 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{525f903 6545:com.samsung.android.app.mirrorlink/1000}
08-24 13:23:44.457  6545  6545 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
08-24 13:23:44.467  6545  6545 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
08-24 13:23:44.507  6545  6545 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
08-24 13:23:44.507  6545  6545 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
08-24 13:23:44.507   755  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b34a30 5633:com.google.android.apps.plus/u0a134}
08-24 13:23:44.517   755  1757 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b34a30 5633:com.google.android.apps.plus/u0a134}
08-24 13:23:44.537   755   769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b34a30 5633:com.google.android.apps.plus/u0a134}
08-24 13:23:44.567   755  1492 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
08-24 13:23:44.577   755   769 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
08-24 13:23:44.577   755  1642 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
08-24 13:23:44.577   755  1586 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
08-24 13:23:44.577   755  1756 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
08-24 13:23:44.587   755   768 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
08-24 13:23:44.587   755  1757 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
08-24 13:23:44.587   755  1410 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
08-24 13:23:44.607  6559  6559 E Zygote  : v2
08-24 13:23:44.607  6559  6559 I libpersona: KNOX_SDCARD checking this for 10165
08-24 13:23:44.607  6559  6559 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:44.607  6559  6559 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:44.607  6559  6559 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:44.607   755  1756 I ActivityManager: Start proc 6559:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-24 13:23:44.607  6559  6559 E Zygote  : accessInfo : 0
08-24 13:23:44.607  6559  6559 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
08-24 13:23:44.617   755  1756 I ActivityManager: Killing 5546:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
08-24 13:23:44.627   755  1757 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
08-24 13:23:44.637  6559  6559 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:44.637  6559  6559 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:44.637  6349  6465 I jxcore-log: JXcore Cordova bridge is ready!
08-24 13:23:44.637  6349  6465 I jxcore-log: 
08-24 13:23:44.637  6349  6465 W jxcore-log: JXcore engine is started
08-24 13:23:44.637   755  1410 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4326afe 6559:com.sec.kidsplat.installer/u0a165}
08-24 13:23:44.647  6349  6464 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 13:23:44.647  6349  6349 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-24 13:23:44.647  6559  6559 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
08-24 13:23:44.667  6559  6559 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
08-24 13:23:44.667   755  1641 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4326afe 6559:com.sec.kidsplat.installer/u0a165}
08-24 13:23:44.677  6559  6559 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
08-24 13:23:44.687  6571  6571 E Zygote  : v2
08-24 13:23:44.687  6571  6571 I libpersona: KNOX_SDCARD checking this for 10142
08-24 13:23:44.687  6571  6571 E Zygote  : isSdpEnabledProcess - SDP enabled
08-24 13:23:44.687  6571  6571 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:44.687   755   769 I ActivityManager: Start proc 6571:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
08-24 13:23:44.687  6571  6571 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:23:44.687  6571  6571 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:23:44.687   755   769 I ActivityManager: Killing 5534:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
08-24 13:23:44.687  6571  6571 E Zygote  : accessInfo : 64
08-24 13:23:44.687  6571  6571 E Zygote  : isSdpEnabledProcess - SDP enabled
08-24 13:23:44.687  6571  6571 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-24 13:23:44.687  6571  6571 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
08-24 13:23:44.707   755  1642 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
08-24 13:23:44.707  6571  6571 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:44.707  6571  6571 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:44.717   755   768 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{485225f 6571:com.sec.android.app.sbrowser/u0a142}
08-24 13:23:44.737  6571  6571 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-24 13:23:44.747  6571  6571 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-24 13:23:44.817  6571  6571 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-24 13:23:44.827  6571  6571 D ManifestProvider: onCreate()
,08-24 13:23:44.837  6571  6571 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-24 13:23:44.837  6571  6571 I SBrowserUtils: getSystemProperty of country_code : Poland
08-24 13:23:44.837  6571  6571 I SBrowserUtils: getSystemProperty of country_code : Poland
08-24 13:23:44.837  6571  6571 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-24 13:23:44.847  6571  6571 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-24 13:23:44.847  6571  6571 D [MM]MHDataBaseProvider: onCreate()
,08-24 13:23:44.867  6571  6571 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@473491)
,08-24 13:23:44.877   755  1410 I ActivityManager: Killing 5616:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-24 13:23:44.887   755  1410 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a832bb 2033:com.google.android.gms.persistent/u0a11}
,08-24 13:23:44.897   755  1586 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{adb6e54 2801:com.google.android.gms/u0a11}
,08-24 13:23:44.897  2801  6586 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 13:23:44.897   755  1748 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-24 13:23:44.907  2801  6585 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-24 13:23:44.907  2801  6586 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 13:23:44.917  2801  2801 D AsyncTaskServiceImpl: Submit a task: nzm
,08-24 13:23:44.927  2801  6586 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 13:23:44.937  2801  6586 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-24 13:23:44.937   755  1492 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a832bb 2033:com.google.android.gms.persistent/u0a11}
,08-24 13:23:44.947  2801  4993 D nzm     : Processing package: com.test.thalitest
,08-24 13:23:44.957   755   768 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{adb6e54 2801:com.google.android.gms/u0a11}
,08-24 13:23:44.957  2801  2801 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 13:23:44.977  2801  4993 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-24 13:23:44.977  2801  4993 D nzm     : Found info for package com.test.thalitest in db.
,08-24 13:23:45.027  3471  3471 D FactoryTest: User mode
,08-24 13:23:45.027  3471  3471 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-24 13:23:45.027  3471  3471 D MTPRx   : still no open session command from host, so toast
,08-24 13:23:45.027   755  1641 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-24 13:23:45.047  6361  6361 I Mms/MmsApp:  start initViewCache mms
,08-24 13:23:45.047   755  1641 D ActivityManager: mDVFSHelper.acquire()
,08-24 13:23:45.047   755  1641 V WindowManager: addAppToken: AppWindowToken{bfcdf62 token=Token{21cbe2d ActivityRecord{8e6fd44 u0 com.samsung.android.MtpApplication/.USBConnection t169}}} to stack=1 task=169 at 0
,08-24 13:23:45.057   755  1641 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-24 13:23:45.067   755   846 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-24 13:23:45.077   755  1641 D InputDispatcher: Focused application set to: xxxx
,08-24 13:23:45.077   755  1641 D InputDispatcher: Focus left window: 6349
,08-24 13:23:45.087   755   894 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:755 uid:1000
,08-24 13:23:45.087   755   894 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 13:23:45.087   755   894 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:755 uid:1000
,08-24 13:23:45.087   755   894 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-24 13:23:45.087  3471  3471 E MTPRx   : started activity for popup
,08-24 13:23:45.097  3471  3471 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-24 13:23:45.097  3471  3471 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-24 13:23:45.107   755  1748 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ac98f67 5691:com.android.vending/u0a29}
,08-24 13:23:45.117  3471  3471 D MTPUSBConnection: onCreate in USBConnection
08-24 13:23:45.117  3471  3471 V MTPUSBConnection: Registering broadcast receiver.
,08-24 13:23:45.117  3471  3471 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-24 13:23:45.117   755  1756 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-24 13:23:45.167  3471  3471 D TAG     : dev.kiessupport is : TRUE
,08-24 13:23:45.177   755  1364 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-24 13:23:45.207  3471  3471 D SecWifiDisplayUtil: Metadata value : none
,08-24 13:23:45.207  3471  3471 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5aa4325 V.E...... R.....I. 0,0-0,0}
,08-24 13:23:45.217  3471  6594 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 13:23:45.217   755  1586 D ISSUE_DEBUG: InputChannelName : 9a22b47 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-24 13:23:45.217   755  1586 D InputDispatcher: Focus entered window: 3471
,08-24 13:23:45.217   755   894 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:755 uid:1000
08-24 13:23:45.217   755   894 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 13:23:45.217   755   894 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:755 uid:1000
08-24 13:23:45.217   755   894 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-24 13:23:45.217   755   848 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9a22b47 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-24 13:23:45.217  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-24 13:23:45.247  3471  3471 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a7eb1dd I.E...... R.....I. 0,0-0,0}
,08-24 13:23:45.257   755  1756 D ISSUE_DEBUG: InputChannelName : 6568c9d com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-24 13:23:45.257   755  1410 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-24 13:23:45.257   755  1410 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-24 13:23:45.257   755   755 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-24 13:23:45.257   755   755 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-24 13:23:45.257   755   755 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-24 13:23:45.267   755   765 I art     : Background partial concurrent mark sweep GC freed 29003(1856KB) AllocSpace objects, 3(60KB) LOS objects, 27% free, 42MB/58MB, paused 10.276ms total 186.143ms
,08-24 13:23:45.287   293   293 I SurfaceFlinger: id=23 createSurf (145x145),1 flag=4, VSBConnecti
,08-24 13:23:45.287   755  1757 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5614d4c u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23d86fb 6036:com.sec.android.app.samsungapps/u0a39}
,08-24 13:23:45.297  5691  5691 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-24 13:23:45.297   755  1748 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a21dee0 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8e839ae 5739:com.sec.android.app.shealth/u0a34}
,08-24 13:23:45.307  3471  6594 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 13:23:45.307  3471  6594 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 13:23:45.307  3471  6594 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 13:23:45.307  3471  6594 I Adreno-EGL: Local Branch: ss
08-24 13:23:45.307  3471  6594 I Adreno-EGL: Remote Branch: 
08-24 13:23:45.307  3471  6594 I Adreno-EGL: Local Patches: 
08-24 13:23:45.307  3471  6594 I Adreno-EGL: Reconstruct Branch: 
,08-24 13:23:45.307  3471  6594 D libEGL  : eglInitialize EGLDisplay = 0x9f0d47c4
,08-24 13:23:45.317  3471  6594 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 13:23:45.317  2033  2033 D WearableService: callingUid 10011, callindPid: 2033
08-24 13:23:45.337   755  1586 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a21dee0 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a44703 1893:com.sec.android.app.shealth:remote/u0a34}
08-24 13:23:45.337  5691  5691 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-24 13:23:45.377   293   293 I SurfaceFlinger: id=24 createSurf (193x193),1 flag=4, VSBConnecti
,08-24 13:23:45.377  5691  5691 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-24 13:23:45.397  5691  5691 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-24 13:23:45.397  3471  3471 V ActivityThread: updateVisibility : ActivityRecord{61f3520 token=android.os.BinderProxy@d920cfa {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-24 13:23:45.407  3471  3471 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 13:23:45.417   755  1756 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a21dee0 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a44703 1893:com.sec.android.app.shealth:remote/u0a34}
,08-24 13:23:45.517   755  1756 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{976090c u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a832bb 2033:com.google.android.gms.persistent/u0a11}
,08-24 13:23:45.537   755  1748 V WindowStateAnimator: Finishing drawing window Window{9a22b47 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-24 13:23:45.537  3471  3471 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-24 13:23:45.537   755  1757 V WindowStateAnimator: Finishing drawing window Window{6568c9d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-24 13:23:45.537  3471  3471 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-24 13:23:45.537  3471  3471 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-24 13:23:45.547   755  1410 V WindowStateAnimator: Finishing drawing window Window{9a22b47 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-24 13:23:45.547   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8fe364
,08-24 13:23:45.547   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8fe364
08-24 13:23:45.547   755  1218 V WindowStateAnimator: Finishing drawing window Window{6568c9d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-24 13:23:45.547  3471  3471 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d920cfa time:108216
,08-24 13:23:45.547   755   894 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-24 13:23:45.547   755   755 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-24 13:23:45.547   755   894 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +473ms (total +500ms)
,08-24 13:23:45.547   755   894 D ActivityManager: mDVFSHelper.release()
08-24 13:23:45.547   755   894 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8e6fd44 u0 com.samsung.android.MtpApplication/.USBConnection t169} time:108219
,08-24 13:23:45.557   755   755 I KnoxTimeoutHandler: SD activityfalse
,08-24 13:23:45.567   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8fe364
,08-24 13:23:45.677  6502  6544 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-24 13:23:45.677  6502  6544 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-24 13:23:45.717  6502  6544 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 13:23:45.717  6502  6544 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-24 13:23:45.717  6502  6544 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-24 13:23:45.727  6502  6544 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 13:23:45.727  6502  6544 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-24 13:23:45.737  6361  6361 D Mms/BubbleViewCache: fillCache bubble = 4
,08-24 13:23:46.107   755  3408 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-24 13:23:46.217  2801  4950 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-24 13:23:46.257  1451  1451 D Recents : onTaskStackChanged
,08-24 13:23:46.267  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-24 13:23:46.277  2801  4950 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 13:23:46.287  2801  4950 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 13:23:46.287  2801  4950 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-24 13:23:46.697   755  1237 V AlarmManager: Expired Alarm result :4
,08-24 13:23:46.697   755  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-24 13:23:46.697   755  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-24 13:23:46.717   755  1642 V AlarmManager:  remove PendingIntent] PendingIntent{84f046a: PendingIntentRecord{23ec2b3 com.google.android.gms broadcastIntent}}
,08-24 13:23:46.777   755  1410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:23:46.777   755  1410 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-24 13:23:46.777   755  1410 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:23:46.777   755  1410 D BatteryService: stay LED for charging
08-24 13:23:46.777   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:23:46.777   755   755 I MotionRecognitionService: Plugged
08-24 13:23:46.777   755   755 D MotionRecognitionService:   cableConnection= 1
08-24 13:23:46.777   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 13:23:46.777   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:23:46.777  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:23:46.777  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:23:46.777  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:23:46.787  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:23:46.787  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:23:46.807  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 13:23:46.807  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:23:46.807  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:23:46.907   755  3404 D SSRM:n  : SIOP:: AP = 470, PST = 454, CUR = 350, LCD = 0
,08-24 13:23:46.927   755  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 13:23:48.417   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:23:51.127   755  3404 D M       : limitCPUFreq:: freq = 1728000
,08-24 13:23:51.127   755  3404 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 755  pkgName : SIOP_ARM_MAX@25
,08-24 13:23:51.127   755  3404 D M       : limitGPUFreq:: freq = 389000000
,08-24 13:23:51.147   755  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 13:23:51.687   755   919 D PackageManager: [MSG] MCS_UNBIND
,08-24 13:23:51.707   755  1586 I ActivityManager: Killing 4719:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-24 13:23:51.767   755  1756 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-24 13:23:52.167   755   919 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-24 13:23:52.177   755   919 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-24 13:23:55.727  6349  6465 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 13:23:55.727  6349  6465 I jxcore-log: 
,08-24 13:23:55.727  6349  6465 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 13:23:55.727  6349  6465 I jxcore-log: 
,08-24 13:23:55.737  6349  6465 D BluetoothAdapter: STATE_ON
,08-24 13:23:55.737  6349  6465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:23:55.737  6349  6465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:23:55.737  6349  6465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 13:23:55.737  6349  6465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:23:55.737  6349  6465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:23:55.737  6349  6465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:23:55.737  6349  6465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:23:55.737  6349  6465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 13:23:55.747  6349  6465 D BluetoothAdapter: STATE_ON
,08-24 13:23:55.747  6349  6465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 13:23:55.747  6349  6465 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 13:23:55.747  6349  6465 I jxcore-log: 
,08-24 13:23:55.747  6349  6465 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 13:23:55.747  6349  6465 I jxcore-log: 
,08-24 13:23:56.317   755   846 I ActivityManager: Waited long enough for: ServiceRecord{91497a6 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,08-24 13:23:56.407  6349  6465 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-24 13:23:56.407  6349  6465 I jxcore-log: Failed to execute UT.
08-24 13:23:56.407  6349  6465 I jxcore-log: 
,08-24 13:23:56.407  6349  6465 I jxcore-log: Unit Test app is loaded
08-24 13:23:56.407  6349  6465 I jxcore-log: 
,08-24 13:23:56.417  6349  6465 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 13:23:56.417  6349  6465 I jxcore-log: 
,08-24 13:23:56.427  6349  6465 I jxcore-log: My device name is: samsung-SM-G900F
08-24 13:23:56.427  6349  6465 I jxcore-log: 
,08-24 13:23:56.427  6349  6465 I jxcore-log: WARN testUtils: myNameCallback not set!
08-24 13:23:56.427  6349  6465 I jxcore-log: 
,08-24 13:23:56.427  6349  6349 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 13:23:56.757   755  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-24 13:23:56.757   755  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-24 13:23:56.967   755  3404 D SSRM:n  : SIOP:: AP = 440, PST = 451, CUR = 350, LCD = 0
,08-24 13:23:56.977   755  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 13:23:57.567   755   769 I ActivityManager: Killing 5257:com.policydm/1000 (adj 15): DHA:empty #37
,08-24 13:23:57.607   755  1757 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-24 13:23:57.617  6314  6314 D AASAservice: onDestroy()
,08-24 13:23:57.617  6314  6314 I art     : System.exit called, status: 80
,08-24 13:23:57.617  6314  6314 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-24 13:23:57.627   755   769 I ActivityManager: Process com.samsung.aasaservice (pid 6314)(adj 0) has died(95,694)
,08-24 13:23:57.627   755   769 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-24 13:23:57.667   352   352 I Zygote  : Process 6314 exited cleanly (80)
,08-24 13:23:58.327   755  1588 E Watchdog: !@Sync 3 [08-24 13:23:58.336]
,08-24 13:23:59.987   755  1237 V AlarmManager: Expired Alarm result :8
,08-24 13:24:01.627  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 13:24:01.627  6349  6465 I jxcore-log: 
,08-24 13:24:01.857   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:24:01.857   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:24:01.857   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:24:02.847  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 13:24:02.847  6349  6465 I jxcore-log: 
,08-24 13:24:02.877  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 13:24:02.877  6349  6465 I jxcore-log: 
,08-24 13:24:02.877  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 13:24:02.877  6349  6465 I jxcore-log: 
,08-24 13:24:02.907  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 13:24:02.907  6349  6465 I jxcore-log: 
,08-24 13:24:02.907  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 13:24:02.907  6349  6465 I jxcore-log: 
,08-24 13:24:03.647   755  1237 V AlarmManager: Expired Alarm result :4
,08-24 13:24:03.707   755   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9a7b6c2 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a832bb 2033:com.google.android.gms.persistent/u0a11}
,08-24 13:24:03.717   755  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:03.717   755  1218 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4362, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:24:03.717  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 13:24:03.717  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
08-24 13:24:03.727  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:24:03.727   755  1218 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:24:03.727   755  1218 D BatteryService: stay LED for charging
,08-24 13:24:03.737   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:24:03.737  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 13:24:03.737   755  1586 V AlarmManager:  remove PendingIntent] PendingIntent{2241cd3: PendingIntentRecord{9e3ba70 com.google.android.gms broadcastIntent}}
,08-24 13:24:03.737  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 13:24:03.737   755   755 I MotionRecognitionService: Plugged
,08-24 13:24:03.737   755   755 D MotionRecognitionService:   cableConnection= 1
08-24 13:24:03.737   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:24:03.737   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:24:03.747  5691  5731 I Finsky  : [813] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-24 13:24:03.747  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:24:03.747  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:24:03.747  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:24:03.747  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:24:03.747  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 13:24:03.747  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:24:03.757  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:24:03.757  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:24:03.757  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:24:03.757  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:03.757  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:24:03.757  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 13:24:03.757  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 13:24:03.757  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:03.777  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:24:03.827  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:24:03.917   755  1586 V AlarmManager:  remove PendingIntent] PendingIntent{188d709: PendingIntentRecord{9e3ba70 com.google.android.gms broadcastIntent}}
,08-24 13:24:04.007  2801  6669 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-24 13:24:04.007  2801  6669 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-24 13:24:04.037  2033  2033 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:24:04.047   755   769 V AlarmManager:  remove PendingIntent] PendingIntent{bee8128: PendingIntentRecord{9e3ba70 com.google.android.gms broadcastIntent}}
,08-24 13:24:04.067   755   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cd75e41 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a832bb 2033:com.google.android.gms.persistent/u0a11}
,08-24 13:24:04.107   755   768 V AlarmManager:  remove PendingIntent] PendingIntent{db11fe6: PendingIntentRecord{9e3ba70 com.google.android.gms broadcastIntent}}
,08-24 13:24:04.147   755  1641 V AlarmManager:  remove PendingIntent] PendingIntent{e06d927: PendingIntentRecord{9e3ba70 com.google.android.gms broadcastIntent}}
,08-24 13:24:04.227  5691  5731 I Finsky  : [813] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-24 13:24:04.227  5691  5691 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-24 13:24:04.387  6675  6675 E Zygote  : v2
08-24 13:24:04.387  6675  6675 I libpersona: KNOX_SDCARD checking this for 10011
08-24 13:24:04.387  6675  6675 I libpersona: KNOX_SDCARD not a persona
,08-24 13:24:04.387  6675  6675 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:24:04.387  6675  6675 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:24:04.387  6675  6675 E Zygote  : accessInfo : 0
08-24 13:24:04.387  6675  6675 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-24 13:24:04.407   755  1642 I ActivityManager: Start proc 6675:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-24 13:24:04.447  6675  6675 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:24:04.447  6675  6675 D ActivityThread: Added TimaKeyStore provider
,08-24 13:24:04.457  6675  6675 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-24 13:24:04.507  6675  6675 I MultiDex: VM with version 2.1.0 has multidex support
08-24 13:24:04.507  6675  6675 I MultiDex: install
08-24 13:24:04.507  6675  6675 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 13:24:04.537  6675  6675 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-24 13:24:04.547  6675  6675 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-24 13:24:04.547  6675  6675 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-24 13:24:04.557  6675  6675 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-24 13:24:04.587  6675  6675 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 13:24:04.607  6675  6675 D ChimeraCfgMgr: Reading stored module config
,08-24 13:24:04.717  6675  6690 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-24 13:24:04.747  2033  2033 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=b82d5df2-6df8-4a8c-abbc-88d8872a756d
,08-24 13:24:04.777  2033  2033 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:24:04.777  2033  2033 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:24:04.777   322   960 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6675)
,08-24 13:24:04.827   322   953 D WVCdm   : Instantiating CDM.
,08-24 13:24:04.827   322   322 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6675)
08-24 13:24:04.827   322   322 I WVCdm   : CdmEngine::OpenSession
08-24 13:24:04.827   322   322 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-24 13:24:04.837   322   322 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-24 13:24:04.847   322   322 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-24 13:24:04.847   322   322 D DrmWidevineDash: Service_Initialize: starts!
08-24 13:24:04.847   322   322 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-24 13:24:04.847   322   322 D QSEECOMAPI: : App is not loaded in QSEE
08-24 13:24:04.847   322   322 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-24 13:24:04.847   322   322 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-24 13:24:04.847   322   322 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-24 13:24:04.847   322   322 D QSEECOMAPI: : App is not loaded in QSEE
08-24 13:24:04.847   322   322 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-24 13:24:04.847   322   322 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-24 13:24:04.847   322   322 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-24 13:24:04.847   322   322 D QSEECOMAPI: : App is not loaded in QSEE
,08-24 13:24:04.877   322   322 D QSEECOMAPI: : Loaded image: APP id = 3
,08-24 13:24:04.877   322   322 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-24 13:24:04.877   322   322 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaefd3000
08-24 13:24:04.877   322   322 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaefd3000
,08-24 13:24:04.887   322   322 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-24 13:24:04.887   322   322 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-24 13:24:04.887   322   322 D DrmWidevineDash: hlos api version =  10
08-24 13:24:04.887   322   322 D DrmWidevineDash: tz api version =  10
08-24 13:24:04.887   322   322 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-24 13:24:04.887   322   322 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-24 13:24:04.907   322   322 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-24 13:24:04.907   322   322 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-24 13:24:04.907   322   322 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbe9d16b4
,08-24 13:24:04.907   322   322 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-24 13:24:04.907   322   322 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-24 13:24:04.907   322   322 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1e5da98, dataLength=8
,08-24 13:24:04.907   322   322 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-24 13:24:04.907   322   322 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1dcae00, wrapped_rsa_key_length=1280
,08-24 13:24:04.917   322   322 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-24 13:24:04.917   322   322 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-24 13:24:04.917   322   977 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-24 13:24:04.917   322   977 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-24 13:24:04.917   322   977 I WVCdm   : CdmEngine::GenerateKeyRequest
08-24 13:24:04.917   322   977 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xaea3f980, idLength=0xaedf8f2c
,08-24 13:24:04.917  6675  6687 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 13:24:04.917  6675  6687 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-24 13:24:04.927   306  1173 D EnterpriseController: netId is 0
08-24 13:24:04.927   306  1173 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 13:24:04.927   322   977 D DrmWidevineDash: hlos api version =  10
,08-24 13:24:04.927   322   977 D DrmWidevineDash: tz api version =  10
08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-24 13:24:04.927   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:24:04.927   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:24:04.927   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,08-24 13:24:04.927   322   977 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-24 13:24:04.937   322   977 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-24 13:24:04.937   322   977 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,08-24 13:24:04.937   322   977 D WVCdm   : PrepareKeyRequest: nonce=2612209304
,08-24 13:24:04.947   322   977 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1dc5800
08-24 13:24:04.947   322   977 D DrmWidevineDash: message_length=1631, signature=0xae274cc0, signature_length=2933886980
,08-24 13:24:04.987  6675  6687 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6675, getuid(): 10011
,08-24 13:24:04.997  2033  2423 W GCoreFlp: No location to return for getLastLocation()
,08-24 13:24:05.057   322   977 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-24 13:24:05.067  2801  6670 D UdcContextInitService: registered all accounts: true
,08-24 13:24:05.067   322   953 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6675)
08-24 13:24:05.067   322   953 I WVCdm   : CdmEngine::CloseSession
08-24 13:24:05.067   322   953 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-24 13:24:05.067   322   953 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-24 13:24:05.067   322   953 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-24 13:24:05.067   322   953 D DrmWidevineDash: Service_Uninitialize: starts!
,08-24 13:24:05.067   322   953 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-24 13:24:05.067   322   953 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,08-24 13:24:05.067   322   953 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-24 13:24:05.067   322   953 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-24 13:24:05.077  2033  2527 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 13:24:05.097  2033  2642 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-24 13:24:05.147  6675  6687 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6675, getuid(): 10011
,08-24 13:24:05.257  6675  6687 I qtaguid : Untagging socket 21
,08-24 13:24:05.307  6675  6687 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-24 13:24:05.307  6675  6687 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-24 13:24:05.807  6708  6708 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-24 13:24:05.957  6708  6708 I dex2oat : ----------------------------------------------------
08-24 13:24:05.957  6708  6708 I dex2oat : <SS>: S T A R T I N G . . .
08-24 13:24:05.957  6708  6708 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
08-24 13:24:05.957  6708  6708 I dex2oat : dex2oat took 157.391ms (threads: 4) arena alloc=234KB java alloc=39KB native alloc=1542KB free=1529KB
,08-24 13:24:05.967  6675  6687 W System  : ClassLoader referenced unknown path: 
,08-24 13:24:05.967  6675  6687 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-24 13:24:05.977  6675  6687 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 13:24:05.977  6675  6687 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 13:24:05.977  6675  6687 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 13:24:05.977  6675  6687 I Adreno-EGL: Local Branch: ss
08-24 13:24:05.977  6675  6687 I Adreno-EGL: Remote Branch: 
08-24 13:24:05.977  6675  6687 I Adreno-EGL: Local Patches: 
08-24 13:24:05.977  6675  6687 I Adreno-EGL: Reconstruct Branch: 
,08-24 13:24:05.977  6675  6687 D libEGL  : eglInitialize EGLDisplay = 0xb2f8e264
,08-24 13:24:06.047  6675  6687 D libEGL  : eglTerminate EGLDisplay = 0xb2f8e2bc
,08-24 13:24:06.167  6675  6687 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 13:24:06.167  6675  6687 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 13:24:06.167  6675  6687 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 13:24:06.167  6675  6687 I Adreno-EGL: Local Branch: ss
08-24 13:24:06.167  6675  6687 I Adreno-EGL: Remote Branch: 
08-24 13:24:06.167  6675  6687 I Adreno-EGL: Local Patches: 
08-24 13:24:06.167  6675  6687 I Adreno-EGL: Reconstruct Branch: 
08-24 13:24:06.167  6675  6687 D libEGL  : eglInitialize EGLDisplay = 0xb2f8e264
,08-24 13:24:06.217  6675  6687 D libEGL  : eglTerminate EGLDisplay = 0xb2f8e2bc
,08-24 13:24:06.227  6675  6687 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-24 13:24:06.227  6675  6687 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-24 13:24:06.227  6675  6687 I Adreno-EGL: Build Date: 01/28/16 Thu
08-24 13:24:06.227  6675  6687 I Adreno-EGL: Local Branch: ss
08-24 13:24:06.227  6675  6687 I Adreno-EGL: Remote Branch: 
08-24 13:24:06.227  6675  6687 I Adreno-EGL: Local Patches: 
08-24 13:24:06.227  6675  6687 I Adreno-EGL: Reconstruct Branch: 
,08-24 13:24:06.227  6675  6687 D libEGL  : eglInitialize EGLDisplay = 0xb2f8e264
,08-24 13:24:06.277  6675  6687 D libEGL  : eglTerminate EGLDisplay = 0xb2f8e2bc
,08-24 13:24:06.447  2033  6672 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:06.447  2033  6672 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:06.447   306  1173 D EnterpriseController: netId is 0
08-24 13:24:06.447   306  1173 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 13:24:06.447  2033  6672 I qtaguid : Tagging socket 46 with tag 1000040100000000{268436481,0} uid 10011, pid: 2033, getuid(): 10011
,08-24 13:24:06.497  2033  6672 I qtaguid : Tagging socket 50 with tag 1000040100000000{268436481,0} uid 10011, pid: 2033, getuid(): 10011
,08-24 13:24:06.877   755  1748 V AlarmManager:  remove PendingIntent] PendingIntent{1b5b401: PendingIntentRecord{9e3ba70 com.google.android.gms broadcastIntent}}
,08-24 13:24:06.917  2033  2642 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 13:24:06.917  2033  2642 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-24 13:24:06.927  2033  2642 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-24 13:24:05.215+0200, stopTime=2016-08-24 13:24:06.936+0200, duration=1721ms
,08-24 13:24:06.937  2033  6736 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:06.937  2033  6736 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:06.937   306  1173 D EnterpriseController: netId is 0
08-24 13:24:06.937   306  1173 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 13:24:06.937  2033  6736 I qtaguid : Tagging socket 52 with tag 1000310500000000{268448005,0} uid 10011, pid: 2033, getuid(): 10011
,08-24 13:24:06.977  2033  6736 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} uid 10011, pid: 2033, getuid(): 10011
,08-24 13:24:07.027   755  3404 D SSRM:n  : SIOP:: AP = 430, PST = 447, CUR = 350, LCD = 0
08-24 13:24:07.027   755  3404 D M       : limitCPUFreq:: freq = -1
,08-24 13:24:07.027   755  3404 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 755  tag : SIOP_ARM_MAX@25
08-24 13:24:07.027   755  3404 D M       : limitGPUFreq:: freq = -1
,08-24 13:24:07.027   755  3404 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 1
,08-24 13:24:07.027  2782  2782 D ContentApp:  LEVEL : 1
,08-24 13:24:07.047   755   846 I ActivityManager: Start proc 6744:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,08-24 13:24:07.047   755  1322 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-24 13:24:07.057  6744  6744 E Zygote  : v2
08-24 13:24:07.057  6744  6744 I libpersona: KNOX_SDCARD checking this for 10053
08-24 13:24:07.057  6744  6744 I libpersona: KNOX_SDCARD not a persona
,08-24 13:24:07.057  6744  6744 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:24:07.057  6744  6744 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 13:24:07.057  6744  6744 E Zygote  : accessInfo : 0
,08-24 13:24:07.057  6744  6744 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-24 13:24:07.057   755  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 13:24:07.107  6744  6744 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:24:07.107  6744  6744 D ActivityThread: Added TimaKeyStore provider
,08-24 13:24:07.117   755  1756 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4d84e7 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12a2894 6744:com.sec.android.app.videoplayer/u0a53}
,08-24 13:24:07.117   755  1322 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-24 13:24:07.127  6744  6744 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-24 13:24:07.147  6744  6744 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-24 13:24:07.177  6744  6744 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-24 13:24:07.197  6744  6744 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-24 13:24:07.197  6744  6744 D videowall-Global: core_num = 4
,08-24 13:24:07.217  6744  6744 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,08-24 13:24:07.217  6744  6744 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-24 13:24:07.227  6744  6744 D TranscodeReceiver:  SIOP_LEVEL: 1
,08-24 13:24:07.237  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 13:24:07.237  6349  6465 I jxcore-log: 
,08-24 13:24:07.247  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 13:24:07.247  6349  6465 I jxcore-log: 
,08-24 13:24:07.257  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 13:24:07.257  6349  6465 I jxcore-log: 
,08-24 13:24:07.407  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 13:24:07.407  6349  6465 I jxcore-log: 
,08-24 13:24:07.427  2033  6736 I qtaguid : Untagging socket 52
08-24 13:24:07.427   755   769 V AlarmManager:  remove PendingIntent] PendingIntent{dc88f3d: PendingIntentRecord{9e3ba70 com.google.android.gms broadcastIntent}}
,08-24 13:24:07.487  2033  2642 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-24 13:24:07.617  2033  6764 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 13:24:07.617  2033  6759 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 13:24:07.637  2033  6764 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 13:24:07.637  2033  6759 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 13:24:07.647  2033  6764 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 13:24:07.657  2033  6759 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 13:24:07.657  2033  6759 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-24 13:24:07.667  2033  6759 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 13:24:07.737   755  1756 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:24:07.777  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 13:24:07.777  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:07.777   306  1173 D EnterpriseController: netId is 0
08-24 13:24:07.777   306  1173 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 13:24:07.777  2033  6759 I qtaguid : Tagging socket 63 with tag 11065c0800000000{285629448,0} uid -1, pid: 2033, getuid(): 10011
,08-24 13:24:07.867  2033  6759 I qtaguid : Tagging socket 66 with tag 11065c0800000000{285629448,0} uid -1, pid: 2033, getuid(): 10011
,08-24 13:24:08.247   755  1218 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:24:08.257  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 13:24:08.257  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:08.257  2033  6759 I qtaguid : Tagging socket 63 with tag 11065c9100000000{285629585,0} uid -1, pid: 2033, getuid(): 10011
,08-24 13:24:08.317  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 13:24:08.317  6349  6465 I jxcore-log: 
,08-24 13:24:08.417   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:24:08.427   755  1642 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:24:08.427  2033  6759 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-24 13:24:08.437  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 13:24:08.437  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:08.437  2033  6759 I qtaguid : Tagging socket 63 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2033, getuid(): 10011
,08-24 13:24:08.557  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 13:24:08.557  6349  6465 I jxcore-log: 
,08-24 13:24:08.567  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 13:24:08.567  6349  6465 I jxcore-log: 
,08-24 13:24:08.577   755  1586 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:24:08.587  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 13:24:08.587  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:08.587  2033  6759 I qtaguid : Tagging socket 63 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2033, getuid(): 10011
,08-24 13:24:08.767  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 13:24:08.767  6349  6465 I jxcore-log: 
,08-24 13:24:08.787  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 13:24:08.787  6349  6465 I jxcore-log: 
,08-24 13:24:08.787  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 13:24:08.787  6349  6465 I jxcore-log: 
,08-24 13:24:08.797  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 13:24:08.797  6349  6465 I jxcore-log: 
,08-24 13:24:08.817  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 13:24:08.817  6349  6465 I jxcore-log: 
,08-24 13:24:08.837  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 13:24:08.837  6349  6465 I jxcore-log: 
,08-24 13:24:08.917  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 13:24:08.917  6349  6465 I jxcore-log: 
,08-24 13:24:08.927  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 13:24:08.927  6349  6465 I jxcore-log: 
,08-24 13:24:08.957   755  1410 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:24:08.957  6349  6465 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 13:24:08.957  6349  6465 I jxcore-log: 
,08-24 13:24:08.957  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 13:24:08.957  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:08.957  2033  6759 I qtaguid : Tagging socket 63 with tag 11065fff00000000{285630463,0} uid -1, pid: 2033, getuid(): 10011
,08-24 13:24:08.967  6349  6465 D BluetoothAdapter: STATE_ON
,08-24 13:24:08.967  6349  6465 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-24 13:24:08.967  6349  6465 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-24 13:24:08.967  6349  6465 I jxcore-log: 
,08-24 13:24:09.027  2033  6737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 13:24:09.027  2033  6737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:09.027  2033  6737 I qtaguid : Tagging socket 52 with tag 1000310200000000{268448002,0} uid 10011, pid: 2033, getuid(): 10011
,08-24 13:24:09.067   755  1757 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:24:09.087  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:09.087  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:09.087  2033  6759 I qtaguid : Tagging socket 63 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2033, getuid(): 10011
,08-24 13:24:09.307  2033  6737 I qtaguid : Untagging socket 52
,08-24 13:24:09.327  2033  2642 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-24 13:24:09.337   755  1586 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:24:09.347  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:09.347  2033  6759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:24:09.347  2033  6759 I qtaguid : Tagging socket 63 with tag 11065b5800000000{285629272,0} uid -1, pid: 2033, getuid(): 10011
,08-24 13:24:09.517   755  1641 V AlarmManager:  remove PendingIntent] PendingIntent{a9f62c: PendingIntentRecord{9e3ba70 com.google.android.gms broadcastIntent}}
,08-24 13:24:11.387   755  1218 I ActivityManager: Killing 5887:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-24 13:24:11.437   755  1492 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-24 13:24:13.817   755  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:13.827   755  1218 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4386, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:24:13.827   755  1218 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:24:13.827   755  1218 D BatteryService: stay LED for charging
,08-24 13:24:13.827   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:24:13.847   755   755 I MotionRecognitionService: Plugged
,08-24 13:24:13.847   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:24:13.857   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:24:13.857   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:24:13.857  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:13.857  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:13.857  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:24:13.877  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:24:13.877  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:24:13.887  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:13.887  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:13.887  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:16.177   755   765 I art     : Background partial concurrent mark sweep GC freed 37536(2MB) AllocSpace objects, 23(460KB) LOS objects, 27% free, 42MB/58MB, paused 2.139ms total 267.070ms
,08-24 13:24:17.127   755  3404 D SSRM:n  : SIOP:: AP = 410, PST = 439, CUR = 350, LCD = 0
,08-24 13:24:23.887   755  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:23.887   755  1218 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:24:23.897   755  1218 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:24:23.897   755  1218 D BatteryService: stay LED for charging
,08-24 13:24:23.897   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:24:23.907   755   755 I MotionRecognitionService: Plugged
,08-24 13:24:23.917   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:24:23.917   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:24:23.917   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:24:23.927  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:23.927  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:23.927  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:24:23.957  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:24:23.957  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:24:23.957  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:23.967  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:23.967  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:26.617   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:24:26.617   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:24:26.617   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:24:27.197   755  3404 D SSRM:n  : SIOP:: AP = 380, PST = 429, CUR = 350, LCD = 0
,08-24 13:24:27.197   755  3404 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,08-24 13:24:27.257  2782  2782 D ContentApp:  LEVEL : 0
,08-24 13:24:27.267   755   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{36768f5 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12a2894 6744:com.sec.android.app.videoplayer/u0a53}
,08-24 13:24:27.277   755  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-24 13:24:27.277  6744  6744 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-24 13:24:27.287  6744  6744 D TranscodeReceiver:  SIOP_LEVEL: 0
,08-24 13:24:28.327   755  1588 E Watchdog: !@Sync 4 [08-24 13:24:28.340]
,08-24 13:24:28.427   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:24:29.287  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:24:33.967   755  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:33.977   755  1642 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:24:33.977   755  1642 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:24:33.977   755  1642 D BatteryService: stay LED for charging
,08-24 13:24:33.987   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:24:33.997   755   755 I MotionRecognitionService: Plugged
,08-24 13:24:34.007   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:24:34.007   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:24:34.007   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:24:34.007  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:34.007  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:34.007  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:24:34.027  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:24:34.027  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:24:34.037  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:34.037  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:34.037  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:34.707   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:24:34.707   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:24:34.707   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:24:37.337   755  3404 D SSRM:n  : SIOP:: AP = 360, PST = 422, CUR = 350, LCD = 0
,08-24 13:24:44.047   755  1641 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:44.057   755  1641 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4390, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:24:44.057   755  1641 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:24:44.067   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:24:44.077   755   755 I MotionRecognitionService: Plugged
,08-24 13:24:44.077   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:24:44.077   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:24:44.087   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:24:44.097   755  1641 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,08-24 13:24:44.097   755  1641 D BatteryService: stay LED for charging
,08-24 13:24:44.107  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:44.107  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:44.107  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:24:44.117  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:24:44.117  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:24:44.127  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:44.127  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:44.137  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 13:24:47.407   755  3404 D SSRM:n  : SIOP:: AP = 350, PST = 414, CUR = 350, LCD = 0
,08-24 13:24:48.427   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:24:49.737   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:24:49.737   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:24:49.737   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:24:54.167   755  1641 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:54.167   755  1641 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:24:54.177   755  1641 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:24:54.177   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:24:54.187   755   755 I MotionRecognitionService: Plugged
,08-24 13:24:54.187   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:24:54.187   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:24:54.187   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:24:54.197   755  1641 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,08-24 13:24:54.197   755  1641 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 755) 
,08-24 13:24:54.207   755  1641 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,08-24 13:24:54.207  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:54.207  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:24:54.207  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:24:54.207  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:24:54.217   755  1641 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-24 13:24:54.227   755  1641 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-24 13:24:54.227  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:24:54.227  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:24:54.237  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:24:54.237  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:24:54.237  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:24:54.247  2801  4989 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 13:24:54.247   755  1641 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-24 13:24:54.247   755  1641 D BatteryService: turn on LED for fully charged
,08-24 13:24:54.627   755  1220 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,08-24 13:24:54.627   755   904 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,08-24 13:24:54.627   755   904 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-24 13:24:54.637   755   904 D SensorManager: unregisterListener ::   
,08-24 13:24:54.647   755   904 D lights  : led_pattern : 5 +
,08-24 13:24:54.657   755   904 D lights  : led_pattern : 5 -
,08-24 13:24:54.667   755   904 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-24 13:24:54.667   755   904 V AlarmManager:  remove PendingIntent] PendingIntent{8387c17: PendingIntentRecord{6a60804 android broadcastIntent}}
,08-24 13:24:57.467   755  3404 D SSRM:n  : SIOP:: AP = 340, PST = 405, CUR = 350, LCD = 0
,08-24 13:24:57.477   755  3404 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-24 13:24:57.487  2782  2782 D ContentApp:  LEVEL : -1
,08-24 13:24:57.507   755   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{780868a u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12a2894 6744:com.sec.android.app.videoplayer/u0a53}
,08-24 13:24:57.517  6744  6744 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-24 13:24:57.517  6744  6744 D TranscodeReceiver:  SIOP_LEVEL: -1
,08-24 13:24:58.337   755  1588 E Watchdog: !@Sync 5 [08-24 13:24:58.351]
,08-24 13:24:58.457   755  3408 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-24 13:24:58.467   755   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ffe652e u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c8fb618 6170:com.samsung.android.sm.provider/1000}
,08-24 13:24:58.577   755  3408 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,08-24 13:24:58.597   755   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f2d425c u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c8fb618 6170:com.samsung.android.sm.provider/1000}
,08-24 13:24:59.987   755  1237 V AlarmManager: Expired Alarm result :8
,08-24 13:25:04.227   755   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:04.227   755   769 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:25:04.227   755   769 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:25:04.237   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:25:04.247   755   755 I MotionRecognitionService: Plugged
,08-24 13:25:04.247   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:25:04.247   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:25:04.257   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:25:04.257   755   769 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 13:25:04.257   755   769 D BatteryService: stay LED for fully charged
,08-24 13:25:04.267  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:25:04.267  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:25:04.277  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:25:04.297  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:25:04.297  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:25:04.307  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:04.307  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:04.307  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:07.567   755  3404 D SSRM:n  : SIOP:: AP = 340, PST = 397, CUR = 350, LCD = 0
,08-24 13:25:08.437   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:25:14.307   755   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:14.317   755   769 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:25:14.317   755   769 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:25:14.317   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:25:14.337   755   755 I MotionRecognitionService: Plugged
,08-24 13:25:14.337   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:25:14.337   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:25:14.347   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:25:14.347   755   769 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 13:25:14.347   755   769 D BatteryService: stay LED for fully charged
,08-24 13:25:14.347  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:25:14.347  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:25:14.347  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:25:14.367  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:25:14.367  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:25:14.377  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:14.377  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:14.377  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:17.627   755  3404 D SSRM:n  : SIOP:: AP = 330, PST = 385, CUR = 350, LCD = 0
,08-24 13:25:24.387   755  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:24.397   755  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:25:24.397   755  1748 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:25:24.407   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:25:24.417   755   755 I MotionRecognitionService: Plugged
,08-24 13:25:24.417   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:25:24.417   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:25:24.427   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:25:24.427   755  1748 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 13:25:24.427   755  1748 D BatteryService: stay LED for fully charged
,08-24 13:25:24.447  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:25:24.447  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:25:24.447  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:25:24.457  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:25:24.457  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:25:24.467  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:24.467  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:24.467  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:27.687   755  3404 D SSRM:n  : SIOP:: AP = 330, PST = 371, CUR = 350, LCD = 0
,08-24 13:25:28.347   755  1588 E Watchdog: !@Sync 6 [08-24 13:25:28.357]
,08-24 13:25:28.437   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:25:29.297  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:25:33.247  2033  3289 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 13:25:34.467   755  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:37.757   755  3404 D SSRM:n  : SIOP:: AP = 330, PST = 360, CUR = 350, LCD = 0
,08-24 13:25:44.547   755  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:44.557   755  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:25:44.557   755  1642 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:25:44.557   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:25:44.577   755   755 I MotionRecognitionService: Plugged
,08-24 13:25:44.577   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:25:44.577   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:25:44.577   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:25:44.587   755  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 13:25:44.587   755  1642 D BatteryService: stay LED for fully charged
,08-24 13:25:44.597  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:25:44.597  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:25:44.597  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:25:44.607  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:25:44.607  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:25:44.617  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:44.617  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:44.627  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:47.817   755  3404 D SSRM:n  : SIOP:: AP = 320, PST = 349, CUR = 350, LCD = 0
,08-24 13:25:48.437   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:25:54.637   755  1757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:54.637   755  1757 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:25:54.637   755  1757 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:25:54.647   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:25:54.657   755   755 I MotionRecognitionService: Plugged
,08-24 13:25:54.657   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:25:54.657   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:25:54.667   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:25:54.667   755  1757 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 13:25:54.677   755  1757 D BatteryService: stay LED for fully charged
,08-24 13:25:54.687  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:25:54.697  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:25:54.697  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:25:54.707  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:25:54.707  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:25:54.717  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:54.717  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:54.717  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:25:57.877   755  3404 D SSRM:n  : SIOP:: AP = 320, PST = 340, CUR = 350, LCD = 0
,08-24 13:25:58.347   755  1588 E Watchdog: !@Sync 7 [08-24 13:25:58.361]
,08-24 13:26:04.707   755  1410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:04.717   755  1410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:26:04.717   755  1410 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:26:04.717   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:26:04.737   755   755 I MotionRecognitionService: Plugged
,08-24 13:26:04.737   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:26:04.737   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:26:04.747   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:26:04.747   755  1410 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 13:26:04.747   755  1410 D BatteryService: stay LED for fully charged
,08-24 13:26:04.747  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:26:04.747  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:26:04.747  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:26:04.767  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:26:04.767  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:26:04.787  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:04.787  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:04.787  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:07.937   755  3404 D SSRM:n  : SIOP:: AP = 320, PST = 334, CUR = 350, LCD = 0
,08-24 13:26:08.447   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:26:14.787   755  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:14.797   755  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:26:14.797   755  1756 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:26:14.797   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:26:14.817   755   755 I MotionRecognitionService: Plugged
,08-24 13:26:14.817   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:26:14.817   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:26:14.827   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:26:14.827   755  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-24 13:26:14.827   755  1756 D BatteryService: stay LED for fully charged
,08-24 13:26:14.847  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:26:14.847  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:26:14.847  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:26:14.857  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:26:14.857  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:26:14.867  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:14.867  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:14.877  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:17.997   755  3404 D SSRM:n  : SIOP:: AP = 320, PST = 330, CUR = 350, LCD = 0
,08-24 13:26:24.877   755  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:24.877   755  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:26:24.877   755  1748 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:26:24.887   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:26:24.897   755   755 I MotionRecognitionService: Plugged
,08-24 13:26:24.897   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:26:24.897   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:26:24.897   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:26:24.907   755  1748 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 13:26:24.907   755  1748 D BatteryService: stay LED for fully charged
,08-24 13:26:24.917  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:26:24.917  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:26:24.917  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:26:24.947  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:26:24.947  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:26:24.947  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:24.957  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:24.957  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:28.057   755  3404 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 350, LCD = 0
,08-24 13:26:28.357   755  1588 E Watchdog: !@Sync 8 [08-24 13:26:28.366]
,08-24 13:26:28.447   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:26:29.357  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:26:29.577  1649  1774 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 215ms lastUpdatedAfter : 167164ms
,08-24 13:26:34.947   755  1905 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:38.117   755  3404 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 350, LCD = 0
,08-24 13:26:45.037   755  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:45.047   755  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:26:45.047   755  1642 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:26:45.047   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:26:45.057   755   755 I MotionRecognitionService: Plugged
,08-24 13:26:45.067   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:26:45.067   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:26:45.067   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:26:45.077   755  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 13:26:45.077   755  1642 D BatteryService: stay LED for fully charged
,08-24 13:26:45.097  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:26:45.097  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:26:45.097  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:26:45.107  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:26:45.107  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:26:45.117  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:45.127  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:45.127  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:26:48.177   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 350, LCD = 0
,08-24 13:26:48.457   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:26:55.127   755  1410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:58.237   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 320, CUR = 350, LCD = 0
,08-24 13:26:58.357   755  1588 E Watchdog: !@Sync 9 [08-24 13:26:58.370]
,08-24 13:27:05.197   755  1641 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:27:08.297   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 350, LCD = 0
,08-24 13:27:08.457   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:27:13.407   755  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:27:13.417   755  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 13:27:13.417   755  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 13:27:13.437   755  1231 I TLC_TIMA_PKM_initialize: initializing...
,08-24 13:27:13.437   755  1231 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,08-24 13:27:13.437   755  1231 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-24 13:27:13.437   755  1231 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,08-24 13:27:13.437   755  1231 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-24 13:27:13.447   755  1231 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-24 13:27:13.447   755  1231 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
08-24 13:27:13.447   755  1231 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,08-24 13:27:13.447   755  1231 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-24 13:27:13.447   755  1231 D QSEECOMAPI: : App is not loaded in QSEE
,08-24 13:27:13.497   755  1231 D QSEECOMAPI: : Loaded image: APP id = 3
,08-24 13:27:13.507   755  1231 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-24 13:27:13.517   755  1231 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-24 13:27:15.287   755  1757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:27:15.287   755  1757 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:27:15.297   755  1757 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:27:15.297   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:27:15.307   755   755 I MotionRecognitionService: Plugged
,08-24 13:27:15.307   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:27:15.307   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:27:15.307   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:27:15.317   755  1757 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,08-24 13:27:15.317   755  1757 D BatteryService: stay LED for fully charged
,08-24 13:27:15.327  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:27:15.327  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:27:15.327  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:27:15.347  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:27:15.347  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:27:15.357  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:15.367  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:15.367  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:16.817   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 13:27:16.817   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 13:27:16.837   755  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:27:16.837   755  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:27:18.357   755  3404 D SSRM:n  : SIOP:: AP = 320, PST = 317, CUR = 350, LCD = 0
,08-24 13:27:28.367   755  1588 E Watchdog: !@Sync 10 [08-24 13:27:28.374]
,08-24 13:27:28.417   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 350, LCD = 0
,08-24 13:27:28.457   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:27:29.667  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:27:29.717   755  1237 V AlarmManager: Expired Alarm result :4
,08-24 13:27:29.807   755  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:27:29.807   755  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-24 13:27:29.807   755  1748 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:27:29.807   755  1748 D BatteryService: stay LED for fully charged
,08-24 13:27:29.817   755  1237 I ActivityManager: Start proc 6837:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-24 13:27:29.827  6837  6837 E Zygote  : v2
,08-24 13:27:29.827  6837  6837 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:27:29.827  6837  6837 I libpersona: KNOX_SDCARD not a persona
,08-24 13:27:29.837  6837  6837 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 13:27:29.837  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 13:27:29.837  6837  6837 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:27:29.837  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-24 13:27:29.837  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:27:29.847  6837  6837 E Zygote  : accessInfo : 0
,08-24 13:27:29.857  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 13:27:29.877  1561  1561 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-24 13:27:29.877  1561  1561 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-24 13:27:29.897  1561  1561 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-24 13:27:29.897  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 13:27:29.897   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:27:29.907  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:27:29.907  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:27:29.907  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:27:29.927  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:27:29.927  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:27:29.927  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:27:29.927  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:27:29.937   755   755 I MotionRecognitionService: Plugged
,08-24 13:27:29.937   755   755 D MotionRecognitionService:   cableConnection= 1
08-24 13:27:29.937   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 13:27:29.937   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:27:29.947  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 13:27:29.947  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:27:29.947  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:27:29.947  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:27:29.947  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:29.947  6837  6837 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:27:29.947  6837  6837 D ActivityThread: Added TimaKeyStore provider
08-24 13:27:29.957  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:29.957  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:27:29.957  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:27:29.967  6837  6837 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-24 13:27:29.987  6837  6837 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-24 13:27:29.997  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:27:30.007   755  1218 I ActivityManager: Killing 5908:com.google.android.apps.photos/u0a199 (adj 15): DHA:empty #37
,08-24 13:27:30.027   755  1492 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-24 13:27:33.457   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:27:33.457   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:27:33.457   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:27:33.637  1561  1561 I wpa_supplicant: nl80211: Received scan results (28 BSSes)
,08-24 13:27:33.647   306  1170 D Netd    : Iface wlan0 link up
,08-24 13:27:33.657   755   854 D Tethering: interfaceLinkStateChanged wlan0, true
,08-24 13:27:33.657   755   854 D Tethering: interfaceStatusChanged wlan0, true
,08-24 13:27:33.667  1561  1561 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,08-24 13:27:33.697   755  1323 D WifiP2pService: InactiveState{ what=147461 }
,08-24 13:27:33.697   755  1323 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-24 13:27:33.697   755  1323 D WifiP2pService: DefaultState{ what=147461 }
,08-24 13:27:33.747   755   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1c1ec06 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d73770e 1379:com.android.systemui/u0a58}
,08-24 13:27:38.477   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 350, LCD = 0
,08-24 13:27:39.897   755  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:27:39.897   755  1492 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:27:39.897   755  1492 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:27:39.907   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:27:39.917   755   755 I MotionRecognitionService: Plugged
,08-24 13:27:39.917   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:27:39.917   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:27:39.927   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:27:39.937   755  1492 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 42ms
,08-24 13:27:39.937   755  1492 D BatteryService: stay LED for fully charged
,08-24 13:27:39.947  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:27:39.947  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:27:39.947  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:27:39.957  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:27:39.957  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:27:39.967  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:39.967  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:39.967  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:48.467   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:27:48.547   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 350, LCD = 0
,08-24 13:27:49.657   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:27:49.657   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:27:49.657   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:27:49.977   755  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:27:49.977   755  1492 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:27:49.977   755  1492 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:27:49.987   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:27:49.997   755   755 I MotionRecognitionService: Plugged
,08-24 13:27:49.997   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:27:49.997   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:27:50.007   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:27:50.007   755  1492 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 13:27:50.007   755  1492 D BatteryService: stay LED for fully charged
,08-24 13:27:50.017  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:27:50.017  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:27:50.017  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:27:50.047  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:27:50.047  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:27:50.057  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:50.057  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:27:50.057  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:58.367   755  1588 E Watchdog: !@Sync 11 [08-24 13:27:58.381]
,08-24 13:27:58.607   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 350, LCD = 0
,08-24 13:28:00.007   755  1237 V AlarmManager: Expired Alarm result :8
,08-24 13:28:00.087   755  1641 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:28:00.087   755  1641 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:28:00.087   755  1641 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:28:00.097   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:28:00.107   755   755 I MotionRecognitionService: Plugged
,08-24 13:28:00.107   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:28:00.107   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:28:00.117   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:28:00.117   755  1641 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-24 13:28:00.117   755  1641 D BatteryService: stay LED for fully charged
,08-24 13:28:00.137  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:28:00.137  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:28:00.147  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:28:00.157  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:28:00.157  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:28:00.167  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:00.167  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:00.167  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:05.437   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:28:05.447   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:28:05.447   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:28:05.537  5691  5715 I PlayCommon: [797] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 13:28:05.557  2033  2033 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:28:05.567  2033  2033 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:28:05.567  2033  2033 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:28:05.627  5691  5715 I PlayCommon: [797] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-24 13:28:05.627  5691  5715 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:28:05.627  5691  5715 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:28:05.627   306  1173 D EnterpriseController: netId is 0
,08-24 13:28:05.627   306  1173 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-24 13:28:06.327  5691  5715 I PlayCommon: [797] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-24 13:28:08.467   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:28:08.667   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 350, LCD = 0
,08-24 13:28:10.167   755  1905 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:28:18.727   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 350, LCD = 0
,08-24 13:28:20.247   755  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:28:20.257   755  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:28:20.257   755  1756 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:28:20.257   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:28:20.277   755   755 I MotionRecognitionService: Plugged
,08-24 13:28:20.277   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:28:20.277   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:28:20.277   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:28:20.287   755  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 13:28:20.287   755  1756 D BatteryService: stay LED for fully charged
,08-24 13:28:20.297  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:28:20.297  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:28:20.297  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:28:20.307  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:28:20.307  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:28:20.317  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:20.317  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:20.327  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:24.497   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:28:24.497   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:28:24.497   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:28:28.377   755  1588 E Watchdog: !@Sync 12 [08-24 13:28:28.386]
,08-24 13:28:28.477   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:28:28.777   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 350, LCD = 0
,08-24 13:28:29.697  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:28:30.347   755  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:28:30.357   755  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:28:30.357   755  1756 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:28:30.357   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:28:30.367   755   755 I MotionRecognitionService: Plugged
,08-24 13:28:30.367   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:28:30.377   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:28:30.377   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:28:30.377   755  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-24 13:28:30.387   755  1756 D BatteryService: stay LED for fully charged
,08-24 13:28:30.397  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:28:30.397  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:28:30.397  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:28:30.407  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:28:30.407  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:28:30.417  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:30.417  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:28:30.417  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:38.837   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 350, LCD = 0
,08-24 13:28:48.477   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:28:48.887   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 350, LCD = 0
,08-24 13:28:58.377   755  1588 E Watchdog: !@Sync 13 [08-24 13:28:58.390]
,08-24 13:28:58.947   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-24 13:29:00.417   755  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:29:00.417   755  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:29:00.427   755  1642 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:29:00.427   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:29:00.437   755   755 I MotionRecognitionService: Plugged
,08-24 13:29:00.447   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:29:00.447   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:29:00.447   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:29:00.447   755  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 13:29:00.457   755  1642 D BatteryService: stay LED for fully charged
,08-24 13:29:00.467  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:29:00.467  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:29:00.467  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:29:00.497  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:29:00.497  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:29:00.497  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:29:00.497  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:29:00.497  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:29:05.257   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:29:05.257   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:29:05.257   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:29:08.477   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:29:09.007   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-24 13:29:19.077   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-24 13:29:24.537   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:29:24.537   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:29:24.537   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:29:28.387   755  1588 E Watchdog: !@Sync 14 [08-24 13:29:28.396]
,08-24 13:29:28.487   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:29:29.137   755  3404 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-24 13:29:29.717  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:29:29.907  1649  1774 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 175ms lastUpdatedAfter : 180330ms
,08-24 13:29:30.487   755   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:29:30.497   755   768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:29:30.497   755   768 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:29:30.497   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:29:30.507   755   755 I MotionRecognitionService: Plugged
,08-24 13:29:30.517   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:29:30.517   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:29:30.517   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:29:30.527   755   768 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 13:29:30.527   755   768 D BatteryService: stay LED for fully charged
,08-24 13:29:30.547  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:29:30.547  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:29:30.547  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:29:30.557  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:29:30.557  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:29:30.567  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:29:30.567  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:29:30.567  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:29:39.197   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 350, LCD = 0
,08-24 13:29:48.487   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:29:49.267   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 350, LCD = 0
,08-24 13:29:58.387   755  1588 E Watchdog: !@Sync 15 [08-24 13:29:58.400]
,08-24 13:29:59.337   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 350, LCD = 0
,08-24 13:30:00.557   755  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:30:00.567   755  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:30:00.567   755  1748 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:30:00.567   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:30:00.577   755   755 I MotionRecognitionService: Plugged
,08-24 13:30:00.577   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:30:00.587   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:30:00.587   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:30:00.597   755  1748 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-24 13:30:00.597   755  1748 D BatteryService: stay LED for fully charged
,08-24 13:30:00.597  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:30:00.597  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:30:00.597  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:30:00.607  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:30:00.617  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:30:00.627  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:30:00.627  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:30:00.627  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:30:02.767   369   369 I bootchecker: bootchecker wake up!!
,08-24 13:30:08.487   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:30:09.397   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 350, LCD = 0
,08-24 13:30:19.457   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 350, LCD = 0
,08-24 13:30:28.397   755  1588 E Watchdog: !@Sync 16 [08-24 13:30:28.406]
,08-24 13:30:28.497   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:30:29.517   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 350, LCD = 0
,08-24 13:30:29.917  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:30:30.637   755  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:30:30.647   755  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:30:30.647   755  1218 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:30:30.647   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:30:30.657   755   755 I MotionRecognitionService: Plugged
,08-24 13:30:30.667   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:30:30.667   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:30:30.667   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:30:30.677   755  1218 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 13:30:30.677   755  1218 D BatteryService: stay LED for fully charged
,08-24 13:30:30.697  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:30:30.697  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:30:30.697  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:30:30.707  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:30:30.707  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:30:30.717  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:30:30.717  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:30:30.717  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:30:39.577   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 350, LCD = 0
,08-24 13:30:48.497   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:30:49.637   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 350, LCD = 0
,08-24 13:30:58.397   755  1588 E Watchdog: !@Sync 17 [08-24 13:30:58.410]
,08-24 13:30:59.707   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 350, LCD = 0
,08-24 13:31:00.007   755  1237 V AlarmManager: Expired Alarm result :8
,08-24 13:31:00.007   755  1237 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=542662 batch.start=679238
,08-24 13:31:00.017  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 13:31:00.017  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-24 13:31:00.027  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:31:00.067  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 13:31:00.087  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 13:31:00.107  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:31:00.117  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:31:00.117  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:31:00.117  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:31:00.117  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:31:00.117  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:31:00.127  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:31:00.187  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:31:00.707   755  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:31:00.717   755  1492 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:31:00.717   755  1492 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:31:00.717   755  1492 D BatteryService: stay LED for fully charged
,08-24 13:31:00.727   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:31:00.747  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:31:00.747  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:31:00.747  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:31:00.747   755   755 I MotionRecognitionService: Plugged
,08-24 13:31:00.747   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:31:00.747   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 13:31:00.747   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:31:00.767  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:31:00.767  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:31:00.777  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:31:00.777  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:31:00.777  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:31:08.497   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:31:09.787   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:31:19.847   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:31:28.407   755  1588 E Watchdog: !@Sync 18 [08-24 13:31:28.415]
,08-24 13:31:28.507   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:31:29.917   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:31:29.947  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:31:30.777   755  1641 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:31:30.787   755  1641 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:31:30.787   755  1641 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:31:30.787   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:31:30.807   755   755 I MotionRecognitionService: Plugged
,08-24 13:31:30.807   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:31:30.807   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:31:30.807   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:31:30.817   755  1641 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 13:31:30.817   755  1641 D BatteryService: stay LED for fully charged
,08-24 13:31:30.837  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:31:30.837  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:31:30.837  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:31:30.857  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:31:30.857  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:31:30.867  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:31:30.867  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:31:30.867  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:31:39.977   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:31:48.507   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:31:50.027   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:31:58.407   755  1588 E Watchdog: !@Sync 19 [08-24 13:31:58.419]
,08-24 13:31:59.987   755  1237 V AlarmManager: Expired Alarm result :8
,08-24 13:32:00.087   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:32:00.847   755  1905 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:32:00.847   755  1905 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:32:00.857   755  1905 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:32:00.857   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:32:00.867   755   755 I MotionRecognitionService: Plugged
,08-24 13:32:00.877   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:32:00.877   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:32:00.877   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:32:00.887   755  1905 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-24 13:32:00.887   755  1905 D BatteryService: stay LED for fully charged
,08-24 13:32:00.897  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:32:00.897  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:32:00.897  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:32:00.907  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:32:00.907  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:32:00.917  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:00.927  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:00.927  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:06.897   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:32:06.897   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:32:06.897   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:32:08.517   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:32:10.137   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:32:13.397   755  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:32:13.397   755  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 13:32:13.397   755  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 13:32:14.857   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 13:32:14.857   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 13:32:14.867   755  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:32:14.867   755  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:32:20.197   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:32:21.937   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:32:21.937   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:32:21.937   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:32:28.417   755  1588 E Watchdog: !@Sync 20 [08-24 13:32:28.424]
,08-24 13:32:28.517   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:32:30.047  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:32:30.177  1649  1774 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 113ms lastUpdatedAfter : 180267ms
,08-24 13:32:30.237   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:32:30.927   755   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:32:30.927   755   769 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:32:30.937   755   769 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:32:30.937   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:32:30.947   755   755 I MotionRecognitionService: Plugged
,08-24 13:32:30.957   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:32:30.957   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:32:30.957   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:32:30.967   755   769 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-24 13:32:30.967   755   769 D BatteryService: stay LED for fully charged
,08-24 13:32:30.987  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:32:30.987  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:32:30.987  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:32:31.007  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:32:31.007  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:32:31.017  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:31.017  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:31.017  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.427   755   834 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
,08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.437   755   834 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.447   755   834 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-24 13:32:32.457   755   834 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-24 13:32:32.657   755   894 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,08-24 13:32:32.667   755   894 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,08-24 13:32:40.297   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:32:48.517   755  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:32:50.357   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:32:58.417   755  1588 E Watchdog: !@Sync 21 [08-24 13:32:58.428]
,08-24 13:33:00.407   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:33:00.997   755  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:33:01.007   755  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:33:01.007   755  1748 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:33:01.007   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:33:01.017   755  1748 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 18ms
,08-24 13:33:01.027   755  1748 D BatteryService: stay LED for fully charged
,08-24 13:33:01.037   755   755 I MotionRecognitionService: Plugged
,08-24 13:33:01.037   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:33:01.037   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:33:01.047   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:33:01.047  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:33:01.047  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:33:01.047  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:33:01.067  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:33:01.067  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:33:01.077  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:33:01.077  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:33:01.077  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:33:06.357   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:33:06.357   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:33:06.357   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:33:06.377   755  1756 I ActivityManager: Killing 4495:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 617s, lastActivityTime 617s
,08-24 13:33:06.377   755  1756 I ActivityManager: Killing 3869:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 620s, lastActivityTime 620s
,08-24 13:33:06.457   292   292 I ServiceManager: service 'AtCmdFwd' died
,08-24 13:33:06.457   375  4843 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,08-24 13:33:06.467   375  4843 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:33:06.467   755  1586 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,08-24 13:33:06.467   755  1586 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
08-24 13:33:06.467   755  1586 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,08-24 13:33:06.507   755  1642 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,08-24 13:33:06.507   755  1642 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
08-24 13:33:06.507   755  1642 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10962ms
,08-24 13:33:07.467   375  4843 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:33:07.547   755   846 I ActivityManager: Start proc 6913:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,08-24 13:33:07.557  6913  6913 E Zygote  : v2
,08-24 13:33:07.557  6913  6913 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:33:07.557  6913  6913 I libpersona: KNOX_SDCARD not a persona
,08-24 13:33:07.557  6913  6913 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 13:33:07.557  6913  6913 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 13:33:07.567  6913  6913 E Zygote  : accessInfo : 0
,08-24 13:33:07.607  6913  6913 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 13:33:07.607  6913  6913 D ActivityThread: Added TimaKeyStore provider
,08-24 13:33:07.637  6913  6913 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,08-24 13:33:07.657  6913  6913 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,08-24 13:33:07.657  6913  6913 D AtFwdService: onCreate method
,08-24 13:33:07.657  6913  6913 I AtFwdService: Instantiate AtCmdFwd Service
,08-24 13:33:07.677  6913  6925 D AtCkpdCmdHandler: De-queing command
,08-24 13:33:10.467   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:33:16.577   755  1237 V AlarmManager: Expired Alarm result :8
,08-24 13:33:17.547  6927  6927 E Zygote  : v2
,08-24 13:33:17.547   755   846 I ActivityManager: Start proc 6927:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,08-24 13:33:17.557  6927  6927 I libpersona: KNOX_SDCARD checking this for 10026
,08-24 13:33:17.557  6927  6927 I libpersona: KNOX_SDCARD not a persona
,08-24 13:33:17.557  6927  6927 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 13:33:17.557  6927  6927 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 13:33:17.557  6927  6927 E Zygote  : accessInfo : 0
,08-24 13:33:17.567  6927  6927 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,08-24 13:33:17.607  6927  6927 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 13:33:17.607  6927  6927 D ActivityThread: Added TimaKeyStore provider
,08-24 13:33:17.627  6927  6927 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,08-24 13:33:17.657  6927  6927 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,08-24 13:33:17.667  6927  6927 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,08-24 13:33:17.667  6927  6927 D ContextualPageNotification: resetAllNotification : all clear!!!
,08-24 13:33:20.527   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:33:21.497   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-24 13:33:21.497   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-24 13:33:21.497   306  1169 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-24 13:33:21.507   755   769 I ActivityManager: Killing 3736:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 635s, lastActivityTime 601s
,08-24 13:33:21.517   755   769 I ActivityManager: Killing 1509:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 602s, lastActivityTime 602s
,08-24 13:33:21.587   755  1492 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,08-24 13:33:21.587   755  1492 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,08-24 13:33:21.607   755  1748 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,08-24 13:33:21.607   755  1748 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
08-24 13:33:21.607   755  1748 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,08-24 13:33:22.697  6940  6940 E Zygote  : v2
,08-24 13:33:22.697  6940  6940 I libpersona: KNOX_SDCARD checking this for 10181
08-24 13:33:22.697  6940  6940 I libpersona: KNOX_SDCARD not a persona
,08-24 13:33:22.697  6940  6940 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:33:22.697  6940  6940 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 13:33:22.707  6940  6940 E Zygote  : accessInfo : 0
,08-24 13:33:22.707  6940  6940 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,08-24 13:33:22.707   755   846 I ActivityManager: Start proc 6940:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,08-24 13:33:22.707   755  1322 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-24 13:33:22.757  6940  6940 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 13:33:22.757  6940  6940 D ActivityThread: Added TimaKeyStore provider
,08-24 13:33:22.777   755  1322 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,08-24 13:33:22.787  6940  6940 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,08-24 13:33:22.837  6940  6940 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,08-24 13:33:22.867  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,08-24 13:33:22.877  6940  6940 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-24 13:33:22.877   755   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c50aa51 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de362b6 6940:com.sec.android.daemonapp/u0a181}
,08-24 13:33:22.887  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,08-24 13:33:22.887  6940  6940 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-24 13:33:22.897  6940  6940 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,08-24 13:33:22.897  6940  6940 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-24 13:33:22.897  6940  6940 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,08-24 13:33:22.897  6940  6940 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-24 13:33:22.947  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 13:33:22.947  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-24 13:33:22.947  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,08-24 13:33:22.967  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 13:33:22.967  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-24 13:33:22.967  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,08-24 13:33:22.977  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-24 13:33:23.027  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,08-24 13:33:23.057  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 13:33:23.057  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-24 13:33:23.067  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,08-24 13:33:23.077  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-24 13:33:23.087  6940  6940 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-24 13:33:23.097  6940  6940 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-24 13:33:23.097  6940  6940 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-24 13:33:23.097  6940  6940 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-24 13:33:23.097  6940  6940 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-24 13:33:23.097  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-24 13:33:23.097  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-24 13:33:23.107  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,08-24 13:33:23.107  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,08-24 13:33:23.107  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-24 13:33:23.117  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,08-24 13:33:23.127  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null,
,08-24 13:33:23.157   755  1410 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4baf442 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de362b6 6940:com.sec.android.daemonapp/u0a181}
,08-24 13:33:23.187  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 13:33:23.187  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-24 13:33:23.187  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 13:33:23.197  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 13:33:23.207  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-24 13:33:23.207  6940  6940 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-24 13:33:23.207  6940  6940 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-24 13:33:23.207  6940  6940 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-24 13:33:23.207  6940  6940 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-24 13:33:23.217  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-24 13:33:23.217  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-24 13:33:23.217  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,08-24 13:33:23.217  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,08-24 13:33:23.217  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-24 13:33:23.227  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 13:33:23.237  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-24 13:33:23.257   755  1756 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7124c53 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de362b6 6940:com.sec.android.daemonapp/u0a181}
,08-24 13:33:23.277  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 13:33:23.287  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-24 13:33:23.287  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 13:33:23.297  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 13:33:23.307  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-24 13:33:23.307  6940  6940 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-24 13:33:23.307  6940  6940 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-24 13:33:23.307  6940  6940 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-24 13:33:23.307  6940  6940 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-24 13:33:23.317  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-24 13:33:23.317  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-24 13:33:23.317  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,08-24 13:33:23.317  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,08-24 13:33:23.317  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-24 13:33:23.327  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 13:33:23.337  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-24 13:33:23.357   755  1642 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{13df990 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de362b6 6940:com.sec.android.daemonapp/u0a181}
,08-24 13:33:23.377  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-24 13:33:23.377  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-24 13:33:23.377  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 13:33:23.387  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 13:33:23.397  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-24 13:33:23.397  6940  6940 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-24 13:33:23.397  6940  6940 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-24 13:33:23.397  6940  6940 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-24 13:33:23.397  6940  6940 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-24 13:33:23.397  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-24 13:33:23.397  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-24 13:33:23.407  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,08-24 13:33:23.407  6940  6940 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,08-24 13:33:23.407  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-24 13:33:23.407  6940  6940 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 13:33:23.417  6940  6940 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-24 13:33:28.427   755  1588 E Watchdog: !@Sync 22 [08-24 13:33:28.432]
,08-24 13:33:30.217  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:33:30.577   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:33:31.077   755  1905 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:33:31.077   755  1905 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:33:31.077   755  1905 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:33:31.087   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:33:31.097   755   755 I MotionRecognitionService: Plugged
,08-24 13:33:31.097   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:33:31.097   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:33:31.097   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:33:31.107   755  1905 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-24 13:33:31.107   755  1905 D BatteryService: stay LED for fully charged
,08-24 13:33:31.117  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:33:31.117  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:33:31.117  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:33:31.147  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:33:31.147  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:33:31.157  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:33:31.157  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:33:31.157  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:33:40.637   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:33:50.687   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:33:58.427   755  1588 E Watchdog: !@Sync 23 [08-24 13:33:58.437]
,08-24 13:34:00.747   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:34:01.147   755  1641 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:34:01.157   755  1641 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:34:01.157   755  1641 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:34:01.157   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:34:01.167   755   755 I MotionRecognitionService: Plugged
,08-24 13:34:01.177   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:34:01.177   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:34:01.177   755  1641 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-24 13:34:01.187   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:34:01.187   755  1641 D BatteryService: stay LED for fully charged
,08-24 13:34:01.197  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:34:01.197  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:34:01.197  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:34:01.207  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:34:01.207  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:34:01.217  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:01.227  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:01.227  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:10.797   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:34:20.847   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:34:28.427   755  1588 E Watchdog: !@Sync 24 [08-24 13:34:28.441]
,08-24 13:34:30.367  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:34:30.917   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:34:31.227   755  1757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:34:31.237   755  1757 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:34:31.237   755  1757 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:34:31.237   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:34:31.247   755   755 I MotionRecognitionService: Plugged
,08-24 13:34:31.257   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:34:31.257   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:34:31.257   755  1757 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,08-24 13:34:31.267   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:34:31.267   755  1757 D BatteryService: stay LED for fully charged
,08-24 13:34:31.287  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:34:31.287  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:34:31.287  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:34:31.307  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:34:31.307  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:34:31.317  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:31.317  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:31.317  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:40.967   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:34:51.017   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:34:54.677   755  1237 V AlarmManager: Expired Alarm result :8
,08-24 13:34:58.437   755  1588 E Watchdog: !@Sync 25 [08-24 13:34:58.446]
,08-24 13:35:01.097   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:35:01.307   755  1905 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:35:01.307   755  1905 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:35:01.317   755  1905 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:35:01.317   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:35:01.327   755   755 I MotionRecognitionService: Plugged
,08-24 13:35:01.327   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:35:01.337   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:35:01.337   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:35:01.337   755  1905 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 13:35:01.347   755  1905 D BatteryService: stay LED for fully charged
,08-24 13:35:01.347  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:35:01.347  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:35:01.347  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:35:01.357  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:35:01.367  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:35:01.377  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:01.377  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:01.377  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:11.147   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:35:21.197   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:35:28.437   755  1588 E Watchdog: !@Sync 26 [08-24 13:35:28.450]
,08-24 13:35:30.387  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:35:30.497  1649  1774 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 96ms lastUpdatedAfter : 180321ms
,08-24 13:35:31.257   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:35:31.387   755  1641 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:35:31.397   755  1641 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:35:31.397   755  1641 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:35:31.397   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:35:31.417   755   755 I MotionRecognitionService: Plugged
,08-24 13:35:31.417   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:35:31.417   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:35:31.417   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:35:31.427   755  1641 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 13:35:31.427   755  1641 D BatteryService: stay LED for fully charged
,08-24 13:35:31.447  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:35:31.447  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:35:31.447  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:35:31.457  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:35:31.457  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:35:31.467  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:31.467  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:31.467  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:32.647   755  2308 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,08-24 13:35:32.657   755  2308 V MARsPolicyManager: updateSMDBValues
,08-24 13:35:32.657   755   891 E MARsDBManager: updateDBAll : begin --size 1
,08-24 13:35:32.697   755   891 I ActivityManager: Killing 1893:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 781s, lastActivityTime 707s
,08-24 13:35:32.697   755   891 I ActivityManager: Killing 6265:com.samsung.android.sdk.samsunglink/u0a41 (adj 8): SSR - service for lastStateTime 711s, lastActivityTime 711s
,08-24 13:35:32.757   755   891 E MARsDBManager: updateDBAll : end
,08-24 13:35:32.757   755   891 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,08-24 13:35:32.807   755  1492 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,08-24 13:35:32.807   755  1492 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,08-24 13:35:32.817  5739  5739 D HealthConsole: Service for HealthDataStore is disconnected
,08-24 13:35:32.827   755  1642 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-24 13:35:32.827   755  1642 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-24 13:35:32.827   755  1642 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 1000ms
08-24 13:35:32.827   755  1642 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
,08-24 13:35:32.827   755  1642 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10999ms
,08-24 13:35:32.857   755  1748 I ActivityManager: Start proc 6974:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,08-24 13:35:32.867  6974  6974 E Zygote  : v2
,08-24 13:35:32.867  6974  6974 I libpersona: KNOX_SDCARD checking this for 10034
08-24 13:35:32.867  6974  6974 I libpersona: KNOX_SDCARD not a persona
,08-24 13:35:32.867  6974  6974 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-24 13:35:32.867  6974  6974 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 13:35:32.877  6974  6974 E Zygote  : accessInfo : 0
08-24 13:35:32.877  6974  6974 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,08-24 13:35:32.907  6974  6974 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:35:32.907  6974  6974 D ActivityThread: Added TimaKeyStore provider
,08-24 13:35:32.927  6974  6974 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-24 13:35:32.947  6974  6974 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-24 13:35:32.947  6974  6974 I MultiDex: VM with version 2.1.0 has multidex support
08-24 13:35:32.947  6974  6974 I MultiDex: install
08-24 13:35:32.947  6974  6974 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-24 13:35:32.947  6974  6974 I MultiDex: install
08-24 13:35:32.947  6974  6974 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 13:35:33.067  7003  7003 E Zygote  : v2
08-24 13:35:33.067  7003  7003 I libpersona: KNOX_SDCARD checking this for 10016
08-24 13:35:33.067  7003  7003 I libpersona: KNOX_SDCARD not a persona
,08-24 13:35:33.067  7003  7003 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:35:33.067  7003  7003 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-24 13:35:33.067   755  1410 I ActivityManager: Start proc 7003:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,08-24 13:35:33.067  7003  7003 E Zygote  : accessInfo : 0
08-24 13:35:33.067  7003  7003 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,08-24 13:35:33.097  7003  7003 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:35:33.097  7003  7003 D ActivityThread: Added TimaKeyStore provider
,08-24 13:35:33.117  7003  7003 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,08-24 13:35:33.177  6974  6974 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,08-24 13:35:33.187  6974  6974 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-24 13:35:33.227   755   765 I art     : Background sticky concurrent mark sweep GC freed 73616(8MB) AllocSpace objects, 345(6MB) LOS objects, 27% free, 42MB/58MB, paused 2.704ms total 110.868ms
,08-24 13:35:33.237  1379  1379 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,08-24 13:35:33.247   755  1748 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,08-24 13:35:33.247   755  1757 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,08-24 13:35:33.257   755  1218 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,08-24 13:35:33.257   755  1641 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,08-24 13:35:33.277  1379  1379 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{ceee9a4 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,08-24 13:35:33.277  1379  1379 D AdaptiveEventManager: M updateContainers()
08-24 13:35:33.277  1379  1379 D AdaptiveEventContainerSmall: C updatePedoContainer()
,08-24 13:35:33.277  1379  1379 D AdaptiveEventContainerSmall: handlePedoUpdate()
,08-24 13:35:33.277  1379  1379 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,08-24 13:35:33.287  6974  6974 I Health.HealthService: HealthService: onCreate() start (6974)
,08-24 13:35:33.487  5739  5739 D HealthDataStore: Service for HealthDataStore is connected
,08-24 13:35:33.497  5739  5739 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-24 13:35:33.517   755  1586 I ActivityManager: Killing 5938:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-24 13:35:33.537  5739  5739 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
08-24 13:35:33.537  5739  5739 E HealthDataStore: disconnectService: Context instance is invalid
,08-24 13:35:33.577   755  1492 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,08-24 13:35:33.627  6974  6974 D HealthDataStore: Service for HealthDataStore is connected
,08-24 13:35:33.627  6974  6974 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-24 13:35:33.627  6974  6974 D HealthConsole: Service for HealthDataConsole is connected
,08-24 13:35:33.637  6974  6974 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-24 13:35:33.637  6974  6974 E HealthDataStore: disconnectService: Context instance is invalid
,08-24 13:35:33.857  6974  7021 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,08-24 13:35:33.917  6974  7030 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,08-24 13:35:33.937  7003  7013 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-24 13:35:33.947   436   436 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7003
08-24 13:35:33.947   436   436 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,08-24 13:35:34.137  7003  7013 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,08-24 13:35:34.217  6974  7030 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,08-24 13:35:34.347  6974  7030 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
08-24 13:35:34.347  6974  7030 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-24 13:35:34.597   436   436 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,08-24 13:35:34.657  7003  7013 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,08-24 13:35:34.657  7003  7013 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,08-24 13:35:34.657  7003  7013 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,08-24 13:35:41.317   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:35:51.377   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:35:58.447   755  1588 E Watchdog: !@Sync 27 [08-24 13:35:58.456]
,08-24 13:36:01.487   755  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:36:01.507   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:36:11.557   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:36:21.617   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:36:28.447   755  1588 E Watchdog: !@Sync 28 [08-24 13:36:28.460]
,08-24 13:36:30.517  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:36:31.547   755   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:36:31.557   755   769 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:36:31.557   755   769 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:36:31.557   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:36:31.567   755   755 I MotionRecognitionService: Plugged
,08-24 13:36:31.577   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:36:31.577   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:36:31.577   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:36:31.587   755   769 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 13:36:31.587   755   769 D BatteryService: stay LED for fully charged
,08-24 13:36:31.597  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:36:31.597  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:36:31.597  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:36:31.637  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:31.637  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:31.637  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:31.637  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:36:31.637  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:36:31.687   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:36:41.747   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:36:51.797   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:36:58.457   755  1588 E Watchdog: !@Sync 29 [08-24 13:36:58.466]
,08-24 13:37:01.627   755  1757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:37:01.857   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:37:11.917   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:37:13.397   755  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:37:13.397   755  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 13:37:13.397   755  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 13:37:16.757   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 13:37:16.757   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 13:37:16.767   755  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:37:16.767   755  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:37:21.997   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:37:28.457   755  1588 E Watchdog: !@Sync 30 [08-24 13:37:28.470]
,08-24 13:37:30.577  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:37:32.047   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:37:34.897   755  1237 V AlarmManager: Expired Alarm result :4
,08-24 13:37:34.947  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 13:37:34.947  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-24 13:37:34.947  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:37:34.987   755  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:37:35.007  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 13:37:35.007  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 13:37:35.017  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:37:35.017  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:37:35.017   755   846 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,08-24 13:37:35.017  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:37:35.027  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:37:35.027  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:37:35.027  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:37:35.037  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:37:35.037   755   755 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,08-24 13:37:35.047   755   755 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-24 13:37:35.047   755   755 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-24 13:37:35.057   755   755 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-24 13:37:35.067  2196  2412 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-24 13:37:35.077  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.077  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-24 13:37:35.077  2196  2412 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-24 13:37:35.077  2196  2412 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
08-24 13:37:35.077  2196  2412 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-24 13:37:35.077  2196  2489 D bt_upio : upio_start_stop_timer : timer_settime success
,08-24 13:37:35.077  2196  2489 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,08-24 13:37:35.087  2196  2489 D bt_vendor: op for 7
,08-24 13:37:35.087  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.087  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.087  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.087  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.087  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.087  2196  2489 D bt_vendor: op for 7
,08-24 13:37:35.087  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.087  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.087  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.087  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.087  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.097  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.097  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.097  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.097  2196  2489 D bt_vendor: op for 7
,08-24 13:37:35.097  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.097  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.097  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.097  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.097  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.097  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.097  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.097  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.097  2196  2489 D bt_vendor: op for 7
,08-24 13:37:35.097  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.097  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.097  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.097  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.097  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.097  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.097  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.107  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.107  2196  2489 D bt_vendor: op for 7
,08-24 13:37:35.107  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.107  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.107  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.107  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.107  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.107  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.107  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.107  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.107  2196  2489 D bt_vendor: op for 7
,08-24 13:37:35.107  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.107  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.107  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.107  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.107  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.107  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.107  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.107  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.117  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.117  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.117  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.127  2196  2489 D bt_vendor: op for 7
08-24 13:37:35.127  2196  2489 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-24 13:37:35.127  2196  2489 D bt_upio : BT_WAKE is asserted already
,08-24 13:37:35.137   755  1757 V AlarmManager:  remove PendingIntent] PendingIntent{df31cfa: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.157  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-24 13:37:35.157   755  1756 V AlarmManager:  remove PendingIntent] PendingIntent{6b3b2ab: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.177   755  1586 V AlarmManager:  remove PendingIntent] PendingIntent{6355d08: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.187   755  1748 V AlarmManager:  remove PendingIntent] PendingIntent{3413ca1: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.187   755   769 V AlarmManager:  remove PendingIntent] PendingIntent{8c60ec6: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.197   755  1410 V AlarmManager:  remove PendingIntent] PendingIntent{7f8ce87: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.197   755  1748 V AlarmManager:  remove PendingIntent] PendingIntent{74741b4: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.197   755   769 V AlarmManager:  remove PendingIntent] PendingIntent{49401dd: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.207   755  1410 V AlarmManager:  remove PendingIntent] PendingIntent{9845152: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.207   755  1757 V AlarmManager:  remove PendingIntent] PendingIntent{589cc23: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.217   755  1905 V AlarmManager:  remove PendingIntent] PendingIntent{df0c520: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.217   755   768 V AlarmManager:  remove PendingIntent] PendingIntent{253ded9: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.217   755  1757 V AlarmManager:  remove PendingIntent] PendingIntent{72309e: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.227   755  1905 V AlarmManager:  remove PendingIntent] PendingIntent{3a3077f: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.227   755   768 V AlarmManager:  remove PendingIntent] PendingIntent{3ed134c: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.237   755  1757 V AlarmManager:  remove PendingIntent] PendingIntent{9a8f95: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.237   755  1905 V AlarmManager:  remove PendingIntent] PendingIntent{bccb8aa: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.247   755   768 V AlarmManager:  remove PendingIntent] PendingIntent{3ea9c9b: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.247   755  1757 V AlarmManager:  remove PendingIntent] PendingIntent{17e1838: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.257   755  1905 V AlarmManager:  remove PendingIntent] PendingIntent{1619011: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.257   755   768 V AlarmManager:  remove PendingIntent] PendingIntent{e95b576: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.257   755  1748 V AlarmManager:  remove PendingIntent] PendingIntent{24c6777: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.267   755  1641 V AlarmManager:  remove PendingIntent] PendingIntent{f187fe4: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.267   755  1756 V AlarmManager:  remove PendingIntent] PendingIntent{2be1c4d: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.267   755   768 V AlarmManager:  remove PendingIntent] PendingIntent{81fb302: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.277   755  1748 V AlarmManager:  remove PendingIntent] PendingIntent{3960413: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.277   755  1641 V AlarmManager:  remove PendingIntent] PendingIntent{5cfb650: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.277   755  1756 V AlarmManager:  remove PendingIntent] PendingIntent{4dd3049: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.287   755   768 V AlarmManager:  remove PendingIntent] PendingIntent{859fd4e: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.287   755  1748 V AlarmManager:  remove PendingIntent] PendingIntent{1d2ce6f: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.287   755  1641 V AlarmManager:  remove PendingIntent] PendingIntent{a81e77c: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.287   755  1756 V AlarmManager:  remove PendingIntent] PendingIntent{3bf8805: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.297   755  1218 V AlarmManager:  remove PendingIntent] PendingIntent{cdca05a: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.297   755  1642 V AlarmManager:  remove PendingIntent] PendingIntent{267e28b: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.297   755  1905 V AlarmManager:  remove PendingIntent] PendingIntent{fc3ff68: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.307   755  1410 V AlarmManager:  remove PendingIntent] PendingIntent{b59f81: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.307   755  1492 V AlarmManager:  remove PendingIntent] PendingIntent{2b46826: PendingIntentRecord{5a59325 com.android.bluetooth broadcastIntent}}
,08-24 13:37:35.427   755  1220 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,08-24 13:37:35.427   755   904 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,08-24 13:37:35.437   755   904 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-24 13:37:35.447   755   904 D SensorManager: unregisterListener ::   
,08-24 13:37:35.447   755   904 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-24 13:37:35.447   755   904 V AlarmManager:  remove PendingIntent] PendingIntent{8387c17: PendingIntentRecord{6a60804 android broadcastIntent}}
,08-24 13:37:35.877  2196  2718 D bt_upio : ..proc_btwrite_timeout..
,08-24 13:37:35.877  2196  2718 D bt_upio : upio_set : pio 0 action 1, polarity 1
,08-24 13:37:42.107   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:37:52.157   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:37:58.467   755  1588 E Watchdog: !@Sync 31 [08-24 13:37:58.476]
,08-24 13:37:59.987   755  1237 V AlarmManager: Expired Alarm result :8
,08-24 13:38:02.217   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:38:05.047   755  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:38:05.047   755  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:38:05.047   755  1756 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:38:05.057   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:38:05.067   755   755 I MotionRecognitionService: Plugged
,08-24 13:38:05.067   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:38:05.067   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:38:05.077   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:38:05.077   755  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 13:38:05.087   755  1756 D BatteryService: stay LED for fully charged
,08-24 13:38:05.087  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:38:05.087  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:38:05.087  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:38:05.097  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:38:05.107  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:38:05.117  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:05.117  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:38:05.117  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:12.267   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:38:22.327   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0,
,08-24 13:38:28.467   755  1588 E Watchdog: !@Sync 32 [08-24 13:38:28.480]
,08-24 13:38:30.597  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:38:30.747  1649  1774 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 134ms lastUpdatedAfter : 180243ms
,08-24 13:38:32.377   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:38:35.117   755  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:38:35.117   755  1492 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:38:35.117   755  1492 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:38:35.127   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:38:35.137   755   755 I MotionRecognitionService: Plugged
,08-24 13:38:35.137   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:38:35.137   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:38:35.137   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:38:35.147   755  1492 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-24 13:38:35.147   755  1492 D BatteryService: stay LED for fully charged
,08-24 13:38:35.157  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:38:35.157  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:38:35.157  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:38:35.187  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:38:35.187  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:38:35.197  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:35.197  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:38:35.197  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:42.437   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:38:52.487   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:38:58.477   755  1588 E Watchdog: !@Sync 33 [08-24 13:38:58.486]
,08-24 13:39:02.547   755  3404 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-24 13:39:05.187   755  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:39:05.187   755  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:39:05.187   755  1756 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:39:05.197   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:39:05.207   755   755 I MotionRecognitionService: Plugged
,08-24 13:39:05.207   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:39:05.207   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:39:05.217   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:39:05.217   755  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-24 13:39:05.227   755  1756 D BatteryService: stay LED for fully charged
,08-24 13:39:05.237  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:39:05.237  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:39:05.237  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:39:05.247  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:39:05.247  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:39:05.257  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:39:05.257  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:39:05.257  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:39:12.597   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 350, LCD = 0
,08-24 13:39:22.657   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 350, LCD = 0
,08-24 13:39:28.477   755  1588 E Watchdog: !@Sync 34 [08-24 13:39:28.490]
,08-24 13:39:30.757  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:39:32.717   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 350, LCD = 0
,08-24 13:39:35.237   755  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:39:35.247   755  1492 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:39:35.247   755  1492 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:39:35.247   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:39:35.267   755   755 I MotionRecognitionService: Plugged
,08-24 13:39:35.267   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:39:35.267   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:39:35.277   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:39:35.277   755  1492 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 13:39:35.277   755  1492 D BatteryService: stay LED for fully charged
,08-24 13:39:35.287  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:39:35.287  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:39:35.287  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:39:35.297  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:39:35.297  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:39:35.307  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:39:35.317  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:39:35.317  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:39:42.777   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 350, LCD = 0
,08-24 13:39:52.837   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 350, LCD = 0
,08-24 13:39:58.487   755  1588 E Watchdog: !@Sync 35 [08-24 13:39:58.496]
,08-24 13:40:02.907   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 350, LCD = 0
,08-24 13:40:05.307   755  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:40:05.317   755  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:40:05.317   755  1756 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:40:05.317   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:40:05.327   755   755 I MotionRecognitionService: Plugged
,08-24 13:40:05.327   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:40:05.327   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:40:05.327   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:40:05.337   755  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 19ms
,08-24 13:40:05.337   755  1756 D BatteryService: stay LED for fully charged
,08-24 13:40:05.347  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:40:05.347  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:40:05.347  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:40:05.387  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:40:05.387  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:40:05.387  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:40:05.387  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:40:05.387  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:40:12.967   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 350, LCD = 0
,08-24 13:40:23.027   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 350, LCD = 0
,08-24 13:40:28.487   755  1588 E Watchdog: !@Sync 36 [08-24 13:40:28.501]
,08-24 13:40:30.867  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:40:33.087   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 350, LCD = 0
,08-24 13:40:35.377   755  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:40:35.387   755  1492 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:40:35.387   755  1492 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:40:35.397   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:40:35.407   755   755 I MotionRecognitionService: Plugged
,08-24 13:40:35.407   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:40:35.407   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:40:35.407   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:40:35.427   755  1492 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 38ms
,08-24 13:40:35.427   755  1492 D BatteryService: stay LED for fully charged
,08-24 13:40:35.437  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:40:35.437  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:40:35.437  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:40:35.457  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:40:35.457  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:40:35.467  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:40:35.467  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:40:35.467  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:40:43.147   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:40:53.207   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:40:58.497   755  1588 E Watchdog: !@Sync 37 [08-24 13:40:58.506]
,08-24 13:41:03.257   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:41:05.447   755  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:41:05.457   755  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:41:05.457   755  1756 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:41:05.457   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:41:05.467   755   755 I MotionRecognitionService: Plugged
,08-24 13:41:05.477   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:41:05.477   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:41:05.477   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:41:05.487   755  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-24 13:41:05.487   755  1756 D BatteryService: stay LED for fully charged
,08-24 13:41:05.487  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:41:05.487  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:41:05.487  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:41:05.497  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:41:05.507  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:41:05.517  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:05.517  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:05.517  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:13.317   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:41:23.377   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:41:28.497   755  1588 E Watchdog: !@Sync 38 [08-24 13:41:28.510]
,08-24 13:41:30.907  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:41:31.077  1649  1774 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 153ms lastUpdatedAfter : 180329ms
,08-24 13:41:33.427   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:41:35.517   755  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:41:35.517   755  1492 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:41:35.517   755  1492 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:41:35.527   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:41:35.537   755   755 I MotionRecognitionService: Plugged
,08-24 13:41:35.537   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:41:35.537   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:41:35.547   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:41:35.547   755  1492 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-24 13:41:35.557   755  1492 D BatteryService: stay LED for fully charged
,08-24 13:41:35.567  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:41:35.577  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:41:35.577  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:41:35.597  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:41:35.597  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:41:35.607  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:35.607  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:41:35.607  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:43.477   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:41:53.537   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:41:58.507   755  1588 E Watchdog: !@Sync 39 [08-24 13:41:58.516]
,08-24 13:42:03.607   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:42:05.587   755  1905 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:42:13.397   755  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:42:13.397   755  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 13:42:13.397   755  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 13:42:13.667   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:42:14.867   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 13:42:14.867   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 13:42:14.877   755  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:42:14.877   755  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:42:23.737   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:42:25.097   755   834 I UsageStatsService: User[0] Flushing usage stats to disk
,08-24 13:42:28.507   755  1588 E Watchdog: !@Sync 40 [08-24 13:42:28.520]
,08-24 13:42:31.087  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:42:33.787   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:42:35.647   755  1410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:42:43.837   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:42:53.897   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:42:58.517   755  1588 E Watchdog: !@Sync 41 [08-24 13:42:58.526]
,08-24 13:43:03.947   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:43:05.717   755   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:43:05.727   755   768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:43:05.727   755   768 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:43:05.727   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:43:05.747   755   755 I MotionRecognitionService: Plugged
,08-24 13:43:05.747   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:43:05.747   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:43:05.747   755   768 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-24 13:43:05.757   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:43:05.757   755   768 D BatteryService: stay LED for fully charged
,08-24 13:43:05.777  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:43:05.777  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:43:05.777  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:43:05.797  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:43:05.797  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:43:05.807  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:05.807  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:05.807  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:06.377  5691  5715 I PlayCommon: [797] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 13:43:06.387  5691  5715 I PlayCommon: [797] com.google.android.play.a.al.e(732): No file ready to send
,08-24 13:43:14.007   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:43:24.057   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:43:28.517   755  1588 E Watchdog: !@Sync 42 [08-24 13:43:28.530]
,08-24 13:43:31.187  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:43:34.117   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:43:35.787   755  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:43:35.787   755  1492 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:43:35.787   755  1492 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:43:35.797   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:43:35.807   755   755 I MotionRecognitionService: Plugged
,08-24 13:43:35.807   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:43:35.807   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:43:35.817   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:43:35.817   755  1492 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-24 13:43:35.817   755  1492 D BatteryService: stay LED for fully charged
,08-24 13:43:35.837  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:43:35.837  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:43:35.837  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:43:35.847  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:43:35.847  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:43:35.857  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:35.857  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:35.857  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:44.167   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:43:54.227   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:43:58.527   755  1588 E Watchdog: !@Sync 43 [08-24 13:43:58.535]
,08-24 13:44:04.297   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:44:05.847   755   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:44:05.857   755   768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:44:05.857   755   768 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:44:05.857   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:44:05.867   755   755 I MotionRecognitionService: Plugged
,08-24 13:44:05.877   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:44:05.877   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:44:05.877   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:44:05.887   755   768 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-24 13:44:05.887   755   768 D BatteryService: stay LED for fully charged
,08-24 13:44:05.897  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:44:05.897  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:44:05.897  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:44:05.937  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:44:05.937  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:44:05.937  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:44:05.937  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:44:05.937  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:44:14.357   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:44:24.437   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:44:28.527   755  1588 E Watchdog: !@Sync 44 [08-24 13:44:28.539]
,08-24 13:44:31.207  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:44:31.377  1649  1774 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 158ms lastUpdatedAfter : 180301ms
,08-24 13:44:34.487   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:44:35.917   755   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:44:44.547   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:44:54.597   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:44:58.537   755  1588 E Watchdog: !@Sync 45 [08-24 13:44:58.543]
,08-24 13:45:04.647   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:45:05.987   755  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:45:05.987   755  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:45:05.997   755  1642 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:45:05.997   755  1642 D BatteryService: stay LED for fully charged
,08-24 13:45:05.997   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:45:06.017   755   755 I MotionRecognitionService: Plugged
,08-24 13:45:06.027  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:45:06.027  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:45:06.027  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:45:06.037   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:45:06.037   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-24 13:45:06.037   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:45:06.047  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:45:06.047  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:45:06.057  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:06.057  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:45:06.057  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:14.707   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:45:24.757   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:45:28.537   755  1588 E Watchdog: !@Sync 46 [08-24 13:45:28.548]
,08-24 13:45:31.387  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:45:34.817   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:45:36.047   755   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:45:36.057   755   768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:45:36.057   755   768 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:45:36.057   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:45:36.067   755   755 I MotionRecognitionService: Plugged
,08-24 13:45:36.077   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:45:36.077   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:45:36.077   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:45:36.087   755   768 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-24 13:45:36.087   755   768 D BatteryService: stay LED for fully charged
,08-24 13:45:36.097  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:45:36.097  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:45:36.097  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:45:36.137  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:36.137  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:45:36.137  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:36.137  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:45:36.137  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:45:44.867   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:45:54.917   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:45:58.547   755  1588 E Watchdog: !@Sync 47 [08-24 13:45:58.552]
,08-24 13:46:04.967   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:46:06.117   755  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:46:06.127   755  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:46:06.127   755  1642 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:46:06.127   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:46:06.137   755   755 I MotionRecognitionService: Plugged
,08-24 13:46:06.147   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:46:06.147   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:46:06.157   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:46:06.157   755  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-24 13:46:06.157   755  1642 D BatteryService: stay LED for fully charged
,08-24 13:46:06.177  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:46:06.177  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:46:06.187  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:46:06.197  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:46:06.197  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:46:06.207  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:06.207  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:46:06.207  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:15.027   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:46:25.077   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:46:28.547   755  1588 E Watchdog: !@Sync 48 [08-24 13:46:28.559]
,08-24 13:46:31.477  1649  1774 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-24 13:46:35.137   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:46:36.187   755   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:46:36.187   755   768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-24 13:46:36.187   755   768 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-24 13:46:36.197   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:46:36.207   755   755 I MotionRecognitionService: Plugged
,08-24 13:46:36.207   755   755 D MotionRecognitionService:   cableConnection= 1
,08-24 13:46:36.207   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-24 13:46:36.207   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-24 13:46:36.217   755   768 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-24 13:46:36.217   755   768 D BatteryService: stay LED for fully charged
,08-24 13:46:36.237  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:46:36.237  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:46:36.237  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:46:36.247  2196  2196 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:46:36.247  2196  2731 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:46:36.257  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:36.257  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:36.257  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:45.187   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:46:55.237   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:46:58.557   755  1588 E Watchdog: !@Sync 49 [08-24 13:46:58.564]
,08-24 13:47:05.297   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
,08-24 13:47:06.247   755  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:47:13.397   755  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:47:13.397   755  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 13:47:13.397   755  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,TIME-OUT KILL (timeout was 1400000ms),08-24 13:47:15.357   755  3404 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 350, LCD = 0
08-24 13:47:16.777   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
08-24 13:47:16.777   755  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
08-24 13:47:16.777   755  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
08-24 13:47:16.787   755  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
08-24 13:47:17.787  2205  2205 E audit   : type=1400 msg=audit(1472039237.787:293): avc:  denied  { execmod } for  pid=7098 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 13:47:17.787  2205  2205 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 13:47:17.787  2205  2205 E audit   : type=1300 msg=audit(1472039237.787:293): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f95000 a1=51000 a2=5 a3=4 items=0 ppid=3551 ppcomm=adbd pid=7098 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 13:47:17.787  2205  2205 E audit   : type=1327 msg=audit(1472039237.787:293): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-24 13:47:17.787  2205  2205 E audit   : type=1320 msg=audit(1472039237.787:293): 
08-24 13:47:17.857  2205  2205 E audit   : type=1400 msg=audit(1472039237.857:294): avc:  denied  { execmod } for  pid=7098 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 13:47:17.857  2205  2205 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 13:47:17.857  2205  2205 E audit   : type=1300 msg=audit(1472039237.857:294): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f55000 a1=51000 a2=5 a3=4 items=0 ppid=3551 ppcomm=adbd pid=7098 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 13:47:17.857  2205  2205 E audit   : type=1327 msg=audit(1472039237.857:294): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-24 13:47:17.857  2205  2205 E audit   : type=1320 msg=audit(1472039237.857:294): 
08-24 13:47:17.927  2205  2205 E audit   : type=1400 msg=audit(1472039237.927:295): avc:  denied  { execmod } for  pid=7098 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-24 13:47:17.927  7098  7098 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 13:47:17.927  2205  2205 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-24 13:47:17.927  2205  2205 E audit   : type=1300 msg=audit(1472039237.927:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f55000 a1=51000 a2=5 a3=4 items=0 ppid=3551 ppcomm=adbd pid=7098 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-24 13:47:17.937  2205  2205 E audit   : type=1327 msg=audit(1472039237.927:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-24 13:47:17.937  2205  2205 E audit   : type=1320 msg=audit(1472039237.927:295): 
08-24 13:47:17.937  7098  7098 D AndroidRuntime: CheckJNI is OFF
08-24 13:47:17.937  7098  7098 D AndroidRuntime: readGMSProperty: start
08-24 13:47:17.937  7098  7098 D AndroidRuntime: readGMSProperty: already setted!!
08-24 13:47:17.937  7098  7098 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 13:47:17.937  7098  7098 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 13:47:17.937  7098  7098 D AndroidRuntime: readGMSProperty: end
08-24 13:47:17.937  7098  7098 D AndroidRuntime: addProductProperty: start
08-24 13:47:17.947  7098  7098 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 13:47:17.947  7098  7098 W art     : aedbc000-b1ce2000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-24 13:47:17.947  7098  7098 W art     : b1ce2000-b3f51000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-24 13:47:17.947  7098  7098 W art     : b3f51000-b3f52000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-24 13:47:17.947  7098  7098 W art     : b3f52000-b3f53000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.947  7098  7098 W art     : b427b000-b42a4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-24 13:47:17.947  7098  7098 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-24 13:47:17.947  7098  7098 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-24 13:47:17.947  7098  7098 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-24 13:47:17.947  7098  7098 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-24 13:47:17.947  7098  7098 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
08-24 13:47:17.947  7098  7098 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-24 13:47:17.947  7098  7098 W art     : b4826000-b4829000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-24 13:47:17.947  7098  7098 W art     : b4829000-b482a000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-24 13:47:17.947  7098  7098 W art     : b482a000-b482b000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-24 13:47:17.947  7098  7098 W art     : b482b000-b482c000 r--p 00000000 00:00 0 
08-24 13:47:17.947  7098  7098 W art     : b482c000-b484c000 r--s 00000000 00:0b 9219       /dev/__properties__
08-24 13:47:17.947  7098  7098 W art     : b484c000-b525d000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-24 13:47:17.947  7098  7098 W art     : b525d000-b525e000 ---p 00000000 00:00 0 
08-24 13:47:17.947  7098  7098 W art     : b525e000-b52a7000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-24 13:47:17.947  7098  7098 W art     : b52a7000-b52a8000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-24 13:47:17.947  7098  7098 W art     : b52a8000-b52b0000 rw-p 00000000 00:00 0 
08-24 13:47:17.947  7098  7098 W art     : b52b0000-b52b1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.947  7098  7098 W art     : b52b1000-b52e6000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-24 13:47:17.947  7098  7098 W art     : b52e6000-b52e7000 ---p 00000000 00:00 0 
08-24 13:47:17.947  7098  7098 W art     : b52e7000-b52e8000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-24 13:47:17.947  7098  7098 W art     : b52e8000-b52e9000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-24 13:47:17.947  7098  7098 W art     : b52e9000-b5341000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-24 13:47:17.947  7098  7098 W art     : b5341000-b5342000 ---p 00000000 00:00 0 
08-24 13:47:17.947  7098  7098 W art     : b5342000-b5343000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-24 13:47:17.947  7098  7098 W art     : b5343000-b5344000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-24 13:47:17.947  7098  7098 W art     : b5345000-b534b000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 13:47:17.947  7098  7098 W art     : b534b000-b534c000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 13:47:17.947  7098  7098 W art     : b534c000-b534d000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-24 13:47:17.947  7098  7098 W art     : b534d000-b534f000 rw-p 00000000 00:00 0 
08-24 13:47:17.947  7098  7098 W art     : b5350000-b535a000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 13:47:17.947  7098  7098 W art     : b535a000-b535d000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 13:47:17.947  7098  7098 W art     : b535d000-b535e000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-24 13:47:17.947  7098  7098 W art     : b535f000-b5376000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 13:47:17.947  7098  7098 W art     : b5376000-b5377000 ---p 00000000 00:00 0 
08-24 13:47:17.947  7098  7098 W art     : b5377000-b5378000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 13:47:17.947  7098  7098 W art     : b5378000-b5379000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-24 13:47:17.947  7098  7098 W art     : b537a000-b5384000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-24 13:47:17.947  7098  7098 W art     : b5384000-b5385000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-24 13:47:17.947  7098  7098 W art     : b5385000-b5386000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-24 13:47:17.947  7098  7098 W art     : b5386000-b538a000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 13:47:17.947  7098  7098 W art     : b538a000-b538b000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 13:47:17.957  7098  7098 W art     : b538b000-b538c000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-24 13:47:17.957  7098  7098 W art     : b538c000-b53a2000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-24 13:47:17.957  7098  7098 W art     : b53a2000-b53a3000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-24 13:47:17.957  7098  7098 W art     : b53a3000-b53a4000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-24 13:47:17.957  7098  7098 W art     : b53a4000-b53b1000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-24 13:47:17.957  7098  7098 W art     : b53b1000-b53b2000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-24 13:47:17.957  7098  7098 W art     : b53b2000-b53b3000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-24 13:47:17.957  7098  7098 W art     : b53b3000-b5413000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-24 13:47:17.957  7098  7098 W art     : b5413000-b5416000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-24 13:47:17.957  7098  7098 W art     : b5416000-b541a000 rw-p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b541a000-b547b000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-24 13:47:17.957  7098  7098 W art     : b547b000-b547c000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-24 13:47:17.957  7098  7098 W art     : b547c000-b54cb000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-24 13:47:17.957  7098  7098 W art     : b54cb000-b54cd000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-24 13:47:17.957  7098  7098 W art     : b54cd000-b54ce000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-24 13:47:17.957  7098  7098 W art     : b54ce000-b54cf000 rw-p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b54cf000-b54d6000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 13:47:17.957  7098  7098 W art     : b54d6000-b54d7000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-24 13:47:17.957  7098  7098 W art     : b54d7000-b54d8000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-24 13:47:17.957  7098  7098 W art     : avc_common.so
08-24 13:47:17.957  7098  7098 W art     : b54d9000-b54dc000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 13:47:17.957  7098  7098 W art     : b54dc000-b54dd000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-24 13:47:17.957  7098  7098 W art     : b54dd000-b54de000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-24 13:47:17.957  7098  7098 W art     : enc_common.so
08-24 13:47:17.957  7098  7098 W art     : b54df000-b54e3000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-24 13:47:17.957  7098  7098 W art     : b54e3000-b54e4000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b54e4000-b54e5000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-24 13:47:17.957  7098  7098 W art     : b54e5000-b54e6000 rw-p 00005000 b3:17 2510       /syste
08-24 13:47:17.957  7098  7098 W art     : m/lib/libpowermanager.so
08-24 13:47:17.957  7098  7098 W art     : b54e7000-b5504000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 13:47:17.957  7098  7098 W art     : b5504000-b5505000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 13:47:17.957  7098  7098 W art     : b5505000-b5506000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-24 13:47:17.957  7098  7098 W art     : b5507000-b550c000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 13:47:17.957  7098  7098 W art     : b550c000-b550d000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 13:47:17.957  7098  7098 W art     : b550d000-b550e000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-24 13:47:17.957  7098  7098 W art     : b550f000-b5540000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 13:47:17.957  7098  7098 W art     : b5540000-b5543000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 13:47:17.957  7098  7098 W art     : b5543000-b5544000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-24 13:47:17.957  7098  7098 W art     : b5545000-b5580000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-24 13:47:17.957  7098  7098 W art     : b5580000-b5581000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-24 13:47:17.957  7098  7098 W art     : b5581000-b5582000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-24 13:47:17.957  7098  7098 W art     : b5583000-b558a000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-24 13:47:17.957  7098  7098 W art     : b558a000-b558b000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b558b000-b558c000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-24 13:47:17.957  7098  7098 W art     : b558c000-b558d000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-24 13:47:17.957  7098  7098 W art     : b558d000-b558e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.957  7098  7098 W art     : b558e000-b55a5000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-24 13:47:17.957  7098  7098 W art     : b55a5000-b55a6000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b55a6000-b55a9000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-24 13:47:17.957  7098  7098 W art     : b55a9000-b55aa000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-24 13:47:17.957  7098  7098 W art     : b55aa000-b55c9000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-24 13:47:17.957  7098  7098 W art     : b55c9000-b55ca000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-24 13:47:17.957  7098  7098 W art     : b55ca000-b55cb000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-24 13:47:17.957  7098  7098 W art     : b55cb000-b5609000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-24 13:47:17.957  7098  7098 W art     : b5609000-b560a000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b560a000-b560c000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-24 13:47:17.957  7098  7098 W art     : b560c000-b560d000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-24 13:47:17.957  7098  7098 W art     : b560e000-b5615000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 13:47:17.957  7098  7098 W art     : b5615000-b5616000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 13:47:17.957  7098  7098 W art     : b5616000-b5617000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-24 13:47:17.957  7098  7098 W art     : b5618000-b561b000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 13:47:17.957  7098  7098 W art     : b561b000-b561c000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 13:47:17.957  7098  7098 W art     : b561c000-b561d000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-24 13:47:17.957  7098  7098 W art     : b561d000-b5623000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 13:47:17.957  7098  7098 W art     : b5623000-b5624000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b5624000-b5625000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 13:47:17.957  7098  7098 W art     : b5625000-b5626000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-24 13:47:17.957  7098  7098 W art     : b5626000-b562f000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-24 13:47:17.957  7098  7098 W art     : b562f000-b5630000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-24 13:47:17.957  7098  7098 W art     : b5630000-b5631000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-24 13:47:17.957  7098  7098 W art     : b5631000-b56c2000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 13:47:17.957  7098  7098 W art     : b56c2000-b56c3000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b56c3000-b56ce000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 13:47:17.957  7098  7098 W art     : b56ce000-b56cf000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-24 13:47:17.957  7098  7098 W art     : b56d0000-b56e2000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-24 13:47:17.957  7098  7098 W art     : b56e2000-b56e3000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-24 13:47:17.957  7098  7098 W art     : b56e3000-b56e4000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-24 13:47:17.957  7098  7098 W art     : b56e5000-b56ea000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-24 13:47:17.957  7098  7098 W art     : b56ea000-b56eb000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-24 13:47:17.957  7098  7098 W art     : b56eb000-b56ec000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-24 13:47:17.957  7098  7098 W art     : b56ed000-b575a000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-24 13:47:17.957  7098  7098 W art     : b575a000-b575b000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b575b000-b575d000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-24 13:47:17.957  7098  7098 W art     : b575d000-b575e000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-24 13:47:17.957  7098  7098 W art     : b575e000-b575f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.957  7098  7098 W art     : b575f000-b5766000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 13:47:17.957  7098  7098 W art     : b5766000-b5767000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 13:47:17.957  7098  7098 W art     : b5767000-b5768000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-24 13:47:17.957  7098  7098 W art     : b5769000-b57e9000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 13:47:17.957  7098  7098 W art     : b57e9000-b57ea000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b57ea000-b57eb000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 13:47:17.957  7098  7098 W art     : b57eb000-b57ec000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-24 13:47:17.957  7098  7098 W art     : b57ec000-b5803000 rw-p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b5803000-b583a000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-24 13:47:17.957  7098  7098 W art     : ib/libqc-opt.so
08-24 13:47:17.957  7098  7098 W art     : b583a000-b583b000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 13:47:17.957  7098  7098 W art     : b583b000-b583c000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-24 13:47:17.957  7098  7098 W art     : b583c000-b5858000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 13:47:17.957  7098  7098 W art     : b5858000-b5859000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 13:47:17.957  7098  7098 W art     : b5859000-b585a000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-24 13:47:17.957  7098  7098 W art     : b585b000-b58bc000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-24 13:47:17.957  7098  7098 W art     : b58bc000-b58be000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-24 13:47:17.957  7098  7098 W art     : b58be000-b58bf000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-24 13:47:17.957  7098  7098 W art     : b58c0000-b58e7000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-24 13:47:17.957  7098  7098 W art     : b58e7000-b58e8000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b58e8000-b58e9000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-24 13:47:17.957  7098  7098 W art     : b58e9000-b58ea000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-24 13:47:17.957  7098  7098 W art     : b58eb000-b58f3000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 13:47:17.957  7098  7098 W art     : b58f3000-b58f5000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 13:47:17.957  7098  7098 W art     : b58f5000-b58f6000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-24 13:47:17.957  7098  7098 W art     : b58f7000-b58fa000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-24 13:47:17.957  7098  7098 W art     : b58fa000-b58fb000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-24 13:47:17.957  7098  7098 W art     : b58fb000-b58fc000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-24 13:47:17.957  7098  7098 W art     : b58fc000-b5900000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-24 13:47:17.957  7098  7098 W art     : b5900000-b5901000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b5901000-b5902000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-24 13:47:17.957  7098  7098 W art     : b5902000-b5903000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-24 13:47:17.957  7098  7098 W art     : b5903000-b5913000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-24 13:47:17.957  7098  7098 W art     : b5913000-b5914000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-24 13:47:17.957  7098  7098 W art     : b5914000-b5915000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-24 13:47:17.957  7098  7098 W art     : b5915000-b595b000 rw-p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b595b000-b5964000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-24 13:47:17.957  7098  7098 W art     : b5964000-b5965000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-24 13:47:17.957  7098  7098 W art     : b5965000-b5966000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-24 13:47:17.957  7098  7098 W art     : b5967000-b596c000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-24 13:47:17.957  7098  7098 W art     : b596c000-b596d000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-24 13:47:17.957  7098  7098 W art     : b596d000-b596e000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-24 13:47:17.957  7098  7098 W art     : b596e000-b5971000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 13:47:17.957  7098  7098 W art     : b5971000-b5972000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b5972000-b5973000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 13:47:17.957  7098  7098 W art     : b5973000-b5974000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-24 13:47:17.957  7098  7098 W art     : b5975000-b598d000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 13:47:17.957  7098  7098 W art     : b598d000-b598e000 ---p 00000000 00:00 0 
08-24 13:47:17.957  7098  7098 W art     : b598e000-b598f000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 13:47:17.957  7098  7098 W art     : b598f000-b5990000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-24 13:47:17.957  7098  7098 W art     : b5991000-b5b2b000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-24 13:47:17.967  7098  7098 W art     : b5b2b000-b5b2c000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b5b2c000-b5b39000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-24 13:47:17.967  7098  7098 W art     : b5b39000-b5b3a000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-24 13:47:17.967  7098  7098 W art     : b5b3a000-b5b3e000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-24 13:47:17.967  7098  7098 W art     : b5b3e000-b5b3f000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b5b3f000-b5b40000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-24 13:47:17.967  7098  7098 W art     : b5b40000-b5b41000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-24 13:47:17.967  7098  7098 W art     : b5b41000-b5b54000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-24 13:47:17.967  7098  7098 W art     : b5b54000-b5b55000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-24 13:47:17.967  7098  7098 W art     : b5b55000-b5b56000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-24 13:47:17.967  7098  7098 W art     : b5b56000-b5b57000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:47:17.967  7098  7098 W art     : b5b57000-b5ba2000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-24 13:47:17.967  7098  7098 W art     : b5ba2000-b5ba3000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-24 13:47:17.967  7098  7098 W art     : b5ba3000-b5ba4000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-24 13:47:17.967  7098  7098 W art     : b5ba4000-b5ba6000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b5ba7000-b5bb8000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 13:47:17.967  7098  7098 W art     : b5bb8000-b5bb9000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b5bb9000-b5bba000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 13:47:17.967  7098  7098 W art     : b5bba000-b5bbb000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-24 13:47:17.967  7098  7098 W art     : b5bbc000-b5bc6000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-24 13:47:17.967  7098  7098 W art     : b5bc6000-b5bc8000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-24 13:47:17.967  7098  7098 W art     : b5bc8000-b5bc9000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-24 13:47:17.967  7098  7098 W art     : b5bc9000-b5be2000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-24 13:47:17.967  7098  7098 W art     : b5be2000-b5be3000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-24 13:47:17.967  7098  7098 W art     : b5be3000-b5be6000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-24 13:47:17.967  7098  7098 W art     : b5be6000-b5bea000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b5bea000-b5c5e000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-24 13:47:17.967  7098  7098 W art     : b5c5e000-b5c5f000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b5c5f000-b5c62000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-24 13:47:17.967  7098  7098 W art     : b5c62000-b5c63000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-24 13:47:17.967  7098  7098 W art     : b5c63000-b5c64000 r--p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b5c64000-b5c67000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-24 13:47:17.967  7098  7098 W art     : b5c67000-b5c68000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-24 13:47:17.967  7098  7098 W art     : b5c68000-b5c69000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-24 13:47:17.967  7098  7098 W art     : b5c69000-b5c6a000 r--p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b5c6a000-b5c6f000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 13:47:17.967  7098  7098 W art     : b5c6f000-b5c70000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 13:47:17.967  7098  7098 W art     : b5c70000-b5c71000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-24 13:47:17.967  7098  7098 W art     : b5c71000-b5c72000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.967  7098  7098 W art     : b5c72000-b5c75000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 13:47:17.967  7098  7098 W art     : b5c75000-b5c76000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 13:47:17.967  7098  7098 W art     : b5c76000-b5c77000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-24 13:47:17.967  7098  7098 W art     : b5c77000-b5c78000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.967  7098  7098 W art     : b5c78000-b5c7c000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-24 13:47:17.967  7098  7098 W art     : b5c7c000-b5c7d000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-24 13:47:17.967  7098  7098 W art     : b5c7d000-b5c7e000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-24 13:47:17.967  7098  7098 W art     : b5c7e000-b5c7f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:47:17.967  7098  7098 W art     : b5c7f000-b5c83000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 13:47:17.967  7098  7098 W art     : b5c83000-b5c84000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 13:47:17.967  7098  7098 W art     : b5c84000-b5c85000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-24 13:47:17.967  7098  7098 W art     : b5c85000-b5c86000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.967  7098  7098 W art     : b5c86000-b5c94000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-24 13:47:17.967  7098  7098 W art     : b5c94000-b5c95000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b5c95000-b5c96000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-24 13:47:17.967  7098  7098 W art     : b5c96000-b5c97000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-24 13:47:17.967  7098  7098 W art     : b5c97000-b5ca1000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 13:47:17.967  7098  7098 W art     : b5ca1000-b5ca4000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 13:47:17.967  7098  7098 W art     : b5ca4000-b5ca5000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-24 13:47:17.967  7098  7098 W art     : b5ca5000-b5ca6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.967  7098  7098 W art     : b5ca6000-b5cb0000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-24 13:47:17.967  7098  7098 W art     : b5cb0000-b5cb3000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-24 13:47:17.967  7098  7098 W art     : b5cb3000-b5cb4000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-24 13:47:17.967  7098  7098 W art     : b5cb4000-b5cb8000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-24 13:47:17.967  7098  7098 W art     : b5cb8000-b5cb9000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-24 13:47:17.967  7098  7098 W art     : b5cb9000-b5cba000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-24 13:47:17.967  7098  7098 W art     : b5cba000-b5cbb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.967  7098  7098 W art     : b5cbb000-b5cc8000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-24 13:47:17.967  7098  7098 W art     : b5cc8000-b5cca000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-24 13:47:17.967  7098  7098 W art     : b5cca000-b5ccb000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-24 13:47:17.967  7098  7098 W art     : b5ccb000-b60dd000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-24 13:47:17.967  7098  7098 W art     : b60dd000-b60de000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b60de000-b60e7000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-24 13:47:17.967  7098  7098 W art     : b60e7000-b60eb000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-24 13:47:17.967  7098  7098 W art     : b60eb000-b60ec000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b60ec000-b60f3000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-24 13:47:17.967  7098  7098 W art     : b60f3000-b60f4000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-24 13:47:17.967  7098  7098 W art     : b60f4000-b60f5000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-24 13:47:17.967  7098  7098 W art     : b60f5000-b60f6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.967  7098  7098 W art     : b60f6000-b6111000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-24 13:47:17.967  7098  7098 W art     : b6111000-b6112000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-24 13:47:17.967  7098  7098 W art     : b6112000-b6113000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-24 13:47:17.967  7098  7098 W art     : b6113000-b6114000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.967  7098  7098 W art     : b6114000-b6160000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 13:47:17.967  7098  7098 W art     : b6160000-b6161000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6161000-b6162000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 13:47:17.967  7098  7098 W art     : b6162000-b6163000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-24 13:47:17.967  7098  7098 W art     : b6163000-b6164000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.967  7098  7098 W art     : b6164000-b6168000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-24 13:47:17.967  7098  7098 W art     : b6168000-b6169000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6169000-b616a000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-24 13:47:17.967  7098  7098 W art     : b616a000-b616b000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-24 13:47:17.967  7098  7098 W art     : b616b000-b61a3000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-24 13:47:17.967  7098  7098 W art     : b61a3000-b61a4000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-24 13:47:17.967  7098  7098 W art     : b61a4000-b61a5000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-24 13:47:17.967  7098  7098 W art     : b61a5000-b61a6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.967  7098  7098 W art     : b61a6000-b6244000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-24 13:47:17.967  7098  7098 W art     : b6244000-b6245000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6245000-b6263000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-24 13:47:17.967  7098  7098 W art     : b6263000-b6264000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-24 13:47:17.967  7098  7098 W art     : b6264000-b63d7000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-24 13:47:17.967  7098  7098 W art     : b63d7000-b63e2000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-24 13:47:17.967  7098  7098 W art     : b63e2000-b63e3000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-24 13:47:17.967  7098  7098 W art     : b63e3000-b64fa000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-24 13:47:17.967  7098  7098 W art     : b64fa000-b6505000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-24 13:47:17.967  7098  7098 W art     : b6505000-b6506000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-24 13:47:17.967  7098  7098 W art     : b6506000-b650a000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b650a000-b652e000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-24 13:47:17.967  7098  7098 W art     : b652e000-b6530000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-24 13:47:17.967  7098  7098 W art     : b6530000-b6531000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-24 13:47:17.967  7098  7098 W art     : b6531000-b65d7000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-24 13:47:17.967  7098  7098 W art     : b65d7000-b65e4000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-24 13:47:17.967  7098  7098 W art     : b65e4000-b65e5000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-24 13:47:17.967  7098  7098 W art     : b65e5000-b65e6000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b65e6000-b6639000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-24 13:47:17.967  7098  7098 W art     : b6639000-b663a000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b663a000-b663b000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-24 13:47:17.967  7098  7098 W art     : b663b000-b663c000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-24 13:47:17.967  7098  7098 W art     : b663c000-b6641000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6641000-b6653000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-24 13:47:17.967  7098  7098 W art     : b6653000-b6654000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6654000-b6655000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-24 13:47:17.967  7098  7098 W art     : b6655000-b6656000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-24 13:47:17.967  7098  7098 W art     : b6656000-b665d000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 13:47:17.967  7098  7098 W art     : b665d000-b665e000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 13:47:17.967  7098  7098 W art     : b665e000-b665f000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-24 13:47:17.967  7098  7098 W art     : b665f000-b6660000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6660000-b6663000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-24 13:47:17.967  7098  7098 W art     : b6663000-b6664000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-24 13:47:17.967  7098  7098 W art     : b6664000-b6665000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-24 13:47:17.967  7098  7098 W art     : b6665000-b6669000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-24 13:47:17.967  7098  7098 W art     : b6669000-b666a000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-24 13:47:17.967  7098  7098 W art     : b666a000-b666b000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-24 13:47:17.967  7098  7098 W art     : b666b000-b6679000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-24 13:47:17.967  7098  7098 W art     : b6679000-b667a000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b667a000-b667b000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-24 13:47:17.967  7098  7098 W art     : b667b000-b667c000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-24 13:47:17.967  7098  7098 W art     : b667c000-b6685000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 13:47:17.967  7098  7098 W art     : b6685000-b6686000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 13:47:17.967  7098  7098 W art     : b6686000-b6687000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-24 13:47:17.967  7098  7098 W art     : b6687000-b66ed000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-24 13:47:17.967  7098  7098 W art     : b66ed000-b66ee000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b66ee000-b66f0000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-24 13:47:17.967  7098  7098 W art     : b66f0000-b66f9000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-24 13:47:17.967  7098  7098 W art     : b66f9000-b66fc000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b66fc000-b6793000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-24 13:47:17.967  7098  7098 W art     : b6793000-b6795000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-24 13:47:17.967  7098  7098 W art     : b6795000-b6796000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-24 13:47:17.967  7098  7098 W art     : b6796000-b6797000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6797000-b6ab8000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-24 13:47:17.967  7098  7098 W art     : b6ab8000-b6ab9000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6ab9000-b6ad4000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-24 13:47:17.967  7098  7098 W art     : b6ad4000-b6ad8000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-24 13:47:17.967  7098  7098 W art     : b6ad8000-b6add000 rw-p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6add000-b6ae5000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 13:47:17.967  7098  7098 W art     : b6ae5000-b6ae6000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 13:47:17.967  7098  7098 W art     : b6ae6000-b6ae7000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-24 13:47:17.967  7098  7098 W art     : b6ae7000-b6b15000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-24 13:47:17.967  7098  7098 W art     : b6b15000-b6b16000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6b16000-b6b1d000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-24 13:47:17.967  7098  7098 W art     : b6b1d000-b6b1e000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-24 13:47:17.967  7098  7098 W art     : b6b1e000-b6b64000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-24 13:47:17.967  7098  7098 W art     : b6b64000-b6b65000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6b65000-b6b68000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-24 13:47:17.967  7098  7098 W art     : b6b68000-b6b69000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-24 13:47:17.967  7098  7098 W art     : b6b69000-b6b84000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-24 13:47:17.967  7098  7098 W art     : b6b84000-b6b88000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-24 13:47:17.967  7098  7098 W art     : b6b88000-b6b89000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-24 13:47:17.967  7098  7098 W art     : b6b89000-b6bd6000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-24 13:47:17.967  7098  7098 W art     : b6bd6000-b6bd7000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6bd7000-b6be3000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-24 13:47:17.967  7098  7098 W art     : b6be3000-b6be4000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-24 13:47:17.967  7098  7098 W art     : b6be4000-b6bf1000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-24 13:47:17.967  7098  7098 W art     : b6bf1000-b6bf2000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6bf2000-b6bf3000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-24 13:47:17.967  7098  7098 W art     : b6bf3000-b6bf4000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-24 13:47:17.967  7098  7098 W art     : b6bf4000-b6bfc000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-24 13:47:17.967  7098  7098 W art     : b6bfc000-b6bfd000 ---p 00000000 00:00 0 
08-24 13:47:17.967  7098  7098 W art     : b6bfd000-b6bfe000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-24 13:47:17.967  7098  7098 W art     : b6bfe000-b6bff000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-24 13:47:17.967  7098  7098 W art     : b6bff000-b6c06000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-24 13:47:17.967  7098  7098 W art     : b6c06000-b6c07000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-24 13:47:17.967  7098  7098 W art     : b6c07000-b6c08000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-24 13:47:17.967  7098  7098 W art     : b6c08000-b6c1c000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-24 13:47:17.967  7098  7098 W art     : b6c1c000-b6c1e000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-24 13:47:17.967  7098  7098 W art     : b6c1e000-b6c1f000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-24 13:47:17.967  7098  7098 W art     : b6c1f000-b6c47000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-24 13:47:17.967  7098  7098 W art     : b6c47000-b6c49000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-24 13:47:17.967  7098  7098 W art     : b6c49000-b6c4a000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-24 13:47:17.967  7098  7098 W art     : b6c4a000-b6c4d000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-24 13:47:17.967  7098  7098 W art     : b6c4d000-b6c4e000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-24 13:47:17.967  7098  7098 W art     : b6c4e000-b6c4f000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-24 13:47:17.967  7098  7098 W art     : b6c4f000-b6c58000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-24 13:47:17.967  7098  7098 W art     : b6c58000-b6c59000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-24 13:47:17.967  7098  7098 W art     : b6c59000-b6c5a000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-24 13:47:17.967  7098  7098 W art     : b6c5a000-b6c7a000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-24 13:47:17.967  7098  7098 W art     : b6c7a000-b6c7b000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-24 13:47:17.967  7098  7098 W art     : b6c7b000-b6c7c000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-24 13:47:17.977  7098  7098 W art     : b6c7c000-b6cef000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-24 13:47:17.977  7098  7098 W art     : b6cef000-b6cf3000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-24 13:47:17.977  7098  7098 W art     : b6cf3000-b6cf6000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-24 13:47:17.977  7098  7098 W art     : b6cf6000-b6d00000 rw-p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6d00000-b6d88000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-24 13:47:17.977  7098  7098 W art     : b6d88000-b6d89000 ---p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6d89000-b6d8d000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-24 13:47:17.977  7098  7098 W art     : b6d8d000-b6d8e000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-24 13:47:17.977  7098  7098 W art     : b6d8e000-b6d8f000 rw-p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6d8f000-b6db8000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-24 13:47:17.977  7098  7098 W art     : b6db8000-b6db9000 ---p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6db9000-b6dbc000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-24 13:47:17.977  7098  7098 W art     : b6dbc000-b6dbd000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-24 13:47:17.977  7098  7098 W art     : b6dbd000-b6e97000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 13:47:17.977  7098  7098 W art     : b6e97000-b6e9e000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 13:47:17.977  7098  7098 W art     : b6e9e000-b6ea6000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-24 13:47:17.977  7098  7098 W art     : b6ea6000-b6ea7000 rw-p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6ea7000-b6ea8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:47:17.977  7098  7098 W art     : b6ea8000-b6ea9000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-24 13:47:17.977  7098  7098 W art     : b6ea9000-b6eaa000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.977  7098  7098 W art     : b6eaa000-b6ead000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.977  7098  7098 W art     : b6ead000-b6ed2000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-24 13:47:17.977  7098  7098 W art     : b6ed2000-b6ed3000 ---p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6ed3000-b6eda000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-24 13:47:17.977  7098  7098 W art     : b6eda000-b6edb000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-24 13:47:17.977  7098  7098 W art     : b6edb000-b6ee2000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-24 13:47:17.977  7098  7098 W art     : b6ee2000-b6ee3000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-24 13:47:17.977  7098  7098 W art     : b6ee3000-b6ee4000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-24 13:47:17.977  7098  7098 W art     : b6ee4000-b6ee5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.977  7098  7098 W art     : b6ee5000-b6efd000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-24 13:47:17.977  7098  7098 W art     : b6efd000-b6efe000 ---p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6efe000-b6eff000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-24 13:47:17.977  7098  7098 W art     : b6eff000-b6f00000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-24 13:47:17.977  7098  7098 W art     : b6f00000-b6f0e000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-24 13:47:17.977  7098  7098 W art     : b6f0e000-b6f0f000 ---p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6f0f000-b6f10000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-24 13:47:17.977  7098  7098 W art     : b6f10000-b6f11000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-24 13:47:17.977  7098  7098 W art     : b6f11000-b6f12000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:47:17.977  7098  7098 W art     : b6f12000-b6f14000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.977  7098  7098 W art     : b6f14000-b6f15000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.977  7098  7098 W art     : b6f15000-b6f16000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-24 13:47:17.977  7098  7098 W art     : b6f16000-b6f17000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-24 13:47:17.977  7098  7098 W art     : b6f17000-b6f18000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-24 13:47:17.977  7098  7098 W art     : b6f18000-b6f38000 r--s 00000000 00:0b 9219       /dev/__properties__
08-24 13:47:17.977  7098  7098 W art     : b6f38000-b6f39000 r--p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6f39000-b6f3a000 ---p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6f3a000-b6f3c000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-24 13:47:17.977  7098  7098 W art     : b6f3c000-b6f3d000 r-xp 00000000 00:00 0          [sigpage]
08-24 13:47:17.977  7098  7098 W art     : b6f3d000-b6f58000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-24 13:47:17.977  7098  7098 W art     : b6f58000-b6f59000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-24 13:47:17.977  7098  7098 W art     : b6f59000-b6f5b000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-24 13:47:17.977  7098  7098 W art     : b6f5b000-b6f5d000 rw-p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : b6f5d000-b6f62000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-24 13:47:17.977  7098  7098 W art     : b6f62000-b6f63000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-24 13:47:17.977  7098  7098 W art     : b6f63000-b6f64000 rw-p 00000000 00:00 0 
08-24 13:47:17.977  7098  7098 W art     : bee81000-beea2000 rw-p 00000000 00:00 0          [stack]
08-24 13:47:17.977  7098  7098 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-24 13:47:18.067  7098  7098 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 13:47:18.187  7098  7098 I Radio-JNI: register_android_hardware_Radio DONE
08-24 13:47:18.207  7098  7098 E AffinityControl: AffinityControl: registerfunction enter
08-24 13:47:18.237  7098  7098 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-24 13:47:18.277   755   768 D PackageManager: START PACKAGE DELETE: observer{32513127}
08-24 13:47:18.277   755   768 D PackageManager: pkg{<packageName>}
08-24 13:47:18.277   755   768 D PackageManager: user{0}
08-24 13:47:18.277   755   768 D PackageManager: caller{2000}
08-24 13:47:18.277   755   768 D PackageManager: flags{2}
08-24 13:47:18.277   755   768 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-24 13:47:18.277   755   768 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-24 13:47:18.277   755   768 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-24 13:47:18.277   755   768 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 13:47:18.277   755   768 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 13:47:18.277   755   919 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-24 13:47:18.277   755   919 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-24 13:47:18.277   755   919 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-24 13:47:18.277   755   919 D ApplicationPolicy: getApplicationUninstallationEnabled
08-24 13:47:18.277   755   919 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-24 13:47:18.287   755   919 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-24 13:47:18.287   755   919 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-24 13:47:18.287   755   919 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-24 13:47:18.287   755   846 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-24 13:47:18.297   755   919 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-24 13:47:18.297   755   919 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-24 13:47:18.297   755   846 I ActivityManager: Killing 6349:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
08-24 13:47:18.307   755   846 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 13:47:18.307   755   846 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-24 13:47:18.347   755   846 I ActivityManager: Start proc 7129:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-24 13:47:18.347   755   846 I ActivityManager: Killing 6974:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 705s, lastActivityTime 705s
08-24 13:47:18.347   755   846 I ActivityManager: Killing 6940:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 835s, lastActivityTime 835s
08-24 13:47:18.347  7129  7129 E Zygote  : v2
08-24 13:47:18.347  7129  7129 I libpersona: KNOX_SDCARD checking this for 10004
08-24 13:47:18.347  7129  7129 I libpersona: KNOX_SDCARD not a persona
08-24 13:47:18.347   755   846 I ActivityManager: Killing 6927:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 840s, lastActivityTime 840s
08-24 13:47:18.347  7129  7129 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:47:18.347   755   846 I ActivityManager: Killing 6913:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 850s, lastActivityTime 850s
08-24 13:47:18.347  7129  7129 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:47:18.347  7129  7129 E Zygote  : accessInfo : 0
08-24 13:47:18.347  7129  7129 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-24 13:47:18.357   755   846 I ActivityManager:   Force finishing activity ActivityRecord{9883656 u0 com.test.thalitest/.MainActivity t168}
08-24 13:47:18.367   293   356 I SurfaceFlinger: id=22 Removed NainActivit (4/10)
08-24 13:47:18.367   293  4975 I SurfaceFlinger: id=22 Removed NainActivit (-2/10)
08-24 13:47:18.377   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8fe38c
08-24 13:47:18.397  7129  7129 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:47:18.397  7129  7129 D ActivityThread: Added TimaKeyStore provider
08-24 13:47:18.407   292   292 I ServiceManager: service 'AtCmdFwd' died
08-24 13:47:18.407   375  4844 I Atfwd_Sendcmd: AtCmdFwd : binderDied
08-24 13:47:18.407   375  4844 I ServiceManager: Waiting for service AtCmdFwd...
08-24 13:47:18.417   755   919 D AASAinstall: there is not AASApackages.xml file
08-24 13:47:18.477   755  1492 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@a8daa14)
08-24 13:47:18.477   755  1331 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 13:47:18.477   755  1331 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 13:47:18.477   755  1331 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 13:47:18.477   755  1586 D GraphicsStats: Buffer count: 5
08-24 13:47:18.937   755   919 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
08-24 13:47:19.157   755   919 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
08-24 13:47:19.157   755  1756 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
08-24 13:47:19.157   755  1756 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-24 13:47:19.157   755  1756 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 1000ms
08-24 13:47:19.167   755   894 I Choreographer: Skipped 46 frames!  The application may be doing too much work on its main thread.
08-24 13:47:19.177   755  1757 I ActivityManager: Killing 5986:com.android.email/u0a162 (adj 15): DHA:empty #37
08-24 13:47:19.187   755   769 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
08-24 13:47:19.187   755   769 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
08-24 13:47:19.187   755   769 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 10970ms
08-24 13:47:19.217   755  1748 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
08-24 13:47:19.217   755  1748 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
08-24 13:47:19.217   755  1748 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20946ms
08-24 13:47:19.227   755   768 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
08-24 13:47:19.227   755   768 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
08-24 13:47:19.227   755   768 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 30934ms
08-24 13:47:19.237  7129  7129 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-24 13:47:19.247   331   331 W keystore: ENTER clear_uid from uid 1000 for 10004
08-24 13:47:19.247   755   919 I art     : Starting a blocking GC Explicit
08-24 13:47:19.257  7129  7129 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-24 13:47:19.257  7129  7129 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
08-24 13:47:19.257  7129  7129 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-24 13:47:19.257  7129  7129 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
08-24 13:47:19.267   755  1410 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
08-24 13:47:19.277  7129  7129 D AndroidRuntime: Shutting down VM
08-24 13:47:19.297  7129  7129 E AndroidRuntime: FATAL EXCEPTION: main
08-24 13:47:19.297  7129  7129 E AndroidRuntime: Process: com.test.thalitest, PID: 7129
08-24 13:47:19.297  7129  7129 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-24 13:47:19.297  7129  7129 E AndroidRuntime: 	... ,9 more
08-24 13:47:19.307  7129  7129 I Process : Sending signal. PID: 7129 SIG: 9
08-24 13:47:19.317  7177  7177 E Zygote  : v2
08-24 13:47:19.317   755   846 I ActivityManager: Start proc 7177:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
08-24 13:47:19.317  7177  7177 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-24 13:47:19.317  7177  7177 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:47:19.317  7177  7177 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-24 13:47:19.317  7177  7177 I libpersona: KNOX_SDCARD not a persona
08-24 13:47:19.327  7177  7177 E Zygote  : accessInfo : 0
08-24 13:47:19.327   755  1757 I ActivityManager: Process com.test.thalitest (pid 7129)(adj 9) has died(193,716)
08-24 13:47:19.327   755  1757 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 13:47:19.327   755  1757 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-24 13:47:19.327   755  1757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
08-24 13:47:19.337   755   846 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
08-24 13:47:19.337   755   846 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
08-24 13:47:19.357  7177  7177 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:47:19.357  7177  7177 D ActivityThread: Added TimaKeyStore provider
08-24 13:47:19.367   755  1642 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79bb2bd u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8eee0b2 7177:com.samsung.android.sm/1000}
08-24 13:47:19.367  7177  7177 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
08-24 13:47:19.407   375  4844 I ServiceManager: Waiting for service AtCmdFwd...
08-24 13:47:19.427  7177  7177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
08-24 13:47:19.437   755   768 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{79bb2bd u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{adb6e54 2801:com.google.android.gms/u0a11}
08-24 13:47:19.467   755   919 I art     : Explicit concurrent mark sweep GC freed 53770(2MB) AllocSpace objects, 4(80KB) LOS objects, 27% free, 42MB/58MB, paused 4.325ms total 216.422ms

```
