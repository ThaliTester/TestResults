#### Test 7976383036177d0_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
08-10 16:35:15.235   744  1235 V AlarmManager: Expired Alarm result :8
,--------- beginning of main
08-10 16:35:15.265  5287  5287 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-10 16:35:15.265  5287  5287 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-10 16:35:15.265  5287  5287 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-10 16:35:15.265  5287  5287 I art     : System.exit called, status: 0
08-10 16:35:15.265  5287  5287 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-10 16:35:15.305  5244  5244 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-10 16:35:15.315   744  1414 I ActivityManager: Process com.samsung.aasaservice (pid 5287)(adj 0) has died(132,737)
08-10 16:35:15.315   744  1414 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-10 16:35:15.315   744  1414 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-10 16:35:15.315   744  1414 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-10 16:35:15.335  6281  6281 E Zygote  : v2
08-10 16:35:15.335  6281  6281 I libpersona: KNOX_SDCARD checking this for 10014
08-10 16:35:15.335   744   806 I ActivityManager: Start proc 6281:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-10 16:35:15.335  6281  6281 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:15.335   744  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-10 16:35:15.335  6281  6281 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:15.335  6281  6281 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:15.335  6281  6281 E Zygote  : accessInfo : 0
08-10 16:35:15.335  6281  6281 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-10 16:35:15.365  6281  6281 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:15.365  6281  6281 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:15.375   744   757 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9da881f 6281:com.google.android.partnersetup/u0a14}
08-10 16:35:15.375   744  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-10 16:35:15.385  6281  6281 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-10 16:35:15.395  6281  6281 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-10 16:35:15.415   744  2093 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9da881f 6281:com.google.android.partnersetup/u0a14}
08-10 16:35:15.435  6302  6302 E Zygote  : v2
08-10 16:35:15.435   744  2155 I ActivityManager: Start proc 6302:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-10 16:35:15.435  6302  6302 I libpersona: KNOX_SDCARD checking this for 10015
08-10 16:35:15.435  6302  6302 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:15.435  6302  6302 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:15.435  6302  6302 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:15.435  6302  6302 E Zygote  : accessInfo : 0
08-10 16:35:15.435  6302  6302 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-10 16:35:15.445   744  1493 I ActivityManager: Killing 5435:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-10 16:35:15.455  6302  6302 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:15.455  6302  6302 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:15.465   744  1988 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-10 16:35:15.475   744  2169 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a029ca 6302:com.samsung.groupcast/u0a15}
08-10 16:35:15.475  6302  6302 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-10 16:35:15.495  6302  6302 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-10 16:35:15.515  6302  6302 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-10 16:35:15.515  6302  6302 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-10 16:35:15.515  6302  6302 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-10 16:35:15.515  6302  6302 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-10 16:35:15.515  6302  6302 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-10 16:35:15.525  6302  6302 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-10 16:35:15.525  6302  6302 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-10 16:35:15.525  6302  6302 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-10 16:35:15.525  6302  6302 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-10 16:35:15.525  6302  6302 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:15.525  6302  6302 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-10 16:35:15.525  6302  6302 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-10 16:35:15.525  6302  6302 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 16:35:15.525  6302  6302 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-10 16:35:15.525  6302  6302 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-10 16:35:15.525   744  2093 I ActivityManager: Killing 3990:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-10 16:35:15.535   744  2093 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd29749 1937:com.sec.android.app.shealth:remote/u0a34}
08-10 16:35:15.545   744   757 I ActivityManager: Start proc 6314:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-10 16:35:15.545  6314  6314 E Zygote  : v2
08-10 16:35:15.545  6314  6314 I libpersona: KNOX_SDCARD checking this for 10041
08-10 16:35:15.545  6314  6314 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:15.545  6314  6314 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:15.545  6314  6314 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:15.545  6314  6314 E Zygote  : accessInfo : 0
08-10 16:35:15.545  6314  6314 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-10 16:35:15.555   744  2169 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
08-10 16:35:15.565  6314  6314 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:15.565  6314  6314 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:15.575   744  2139 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a29873b 6314:com.samsung.android.sdk.samsunglink/u0a41}
08-10 16:35:15.585  6314  6314 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-10 16:35:15.665  6314  6314 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-10 16:35:15.665  6314  6314 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-10 16:35:15.715  6314  6314 I SL_DEBUG: isLoggable:: isProductShip = 1
08-10 16:35:15.725  6314  6314 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-10 16:35:15.735   744  2169 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-10 16:35:15.735   744  1414 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-10 16:35:15.735   744   759 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-10 16:35:15.735   744  2093 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-10 16:35:15.745   744  2139 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-10 16:35:15.745   744  1988 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-10 16:35:15.745   744  1677 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-10 16:35:15.745   744  1868 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-10 16:35:15.745   744  2155 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-10 16:35:15.755   744  1493 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-10 16:35:15.845  6314  6314 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-10 16:35:15.845  6314  6314 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-10 16:35:15.845  6314  6314 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-10 16:35:15.845  6314  6314 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-10 16:35:15.845  6314  6314 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-10 16:35:15.845  6314  6314 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-10 16:35:15.845  6314  6314 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-10 16:35:15.845  6314  6314 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-10 16:35:15.845  6314  6314 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-10 16:35:15.845  6314  6314 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-10 16:35:15.845  6314  6314 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:15.845  6314  6314 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-10 16:35:15.845  6314  6314 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-10 16:35:15.845  6314  6314 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 16:35:15.845  6314  6314 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-10 16:35:15.845  6314  6314 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-10 16:35:15.855   744  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e9d8467 1709:android.process.acore/u0a19}
08-10 16:35:15.865   744  2155 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de8bd 4999:com.sec.android.gallery3d/u0a47}
08-10 16:35:15.865  4999  4999 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-10 16:35:15.875   744  1218 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-10 16:35:15.885  6337  6337 E Zygote  : v2
08-10 16:35:15.885  6337  6337 I libpersona: KNOX_SDCARD checking this for 10050
08-10 16:35:15.885  6337  6337 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:15.885   744   757 I ActivityManager: Start proc 6337:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-10 16:35:15.885  6337  6337 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:15.885  6337  6337 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:15.895  6337  6337 E Zygote  : accessInfo : 0
08-10 16:35:15.895  6337  6337 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-10 16:35:15.915  6337  6337 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:15.915  6337  6337 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:15.925   744  1868 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c06b52b 6337:com.sec.android.app.myfiles/u0a50}
08-10 16:35:15.925   744   757 I ActivityManager: Killing 5510:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
08-10 16:35:15.935  6337  6337 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-10 16:35:15.935   744  2139 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
08-10 16:35:15.955  6337  6337 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-10 16:35:15.985  6337  6337 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-10 16:35:16.005   744  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7848ea 2853:com.android.settings/1000}
08-10 16:35:16.005   329   329 E installd: system dir 0 : /system/app/
08-10 16:35:16.005   329   329 E installd: system dir 1 : /system/priv-app/
08-10 16:35:16.005   329   329 E installd: system dir 2 : /vendor/app/
08-10 16:35:16.005   329   329 E installd: system dir 3 : /oem/app/
08-10 16:35:16.015   744   901 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-10 16:35:16.025   744  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7848ea 2853:com.android.settings/1000}
08-10 16:35:16.035   744  1677 I ActivityManager: Start proc 6352:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-10 16:35:16.035  6352  6352 E Zygote  : v2
08-10 16:35:16.035  6352  6352 I libpersona: KNOX_SDCARD checking this for 10169
08-10 16:35:16.035  6352  6352 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:16.045  6352  6352 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:16.045  6352  6352 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:16.045  6352  6352 E Zygote  : accessInfo : 0
08-10 16:35:16.045  6352  6352 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-10 16:35:16.065  6352  6352 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:16.065  6352  6352 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:16.075   744  2155 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb97907 6352:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-10 16:35:16.075  6352  6352 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-10 16:35:16.085  6352  6352 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-10 16:35:16.105   744  2093 I ActivityManager: Killing 5134:com.android.mms/u0a49 (adj 15): DHA:empty #37
08-10 16:35:16.105   744  2093 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73be284 1647:com.android.phone/1001}
08-10 16:35:16.115   744  1493 D CountryDetector: No listener is left
08-10 16:35:16.115  2045  2045 E audit   : type=1400 msg=audit(1470839716.115:284): avc:  denied  { execmod } for  pid=6279 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 16:35:16.115  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:16.115  2045  2045 E audit   : type=1300 msg=audit(1470839716.115:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb8000 a1=51000 a2=5 a3=4 items=0 ppid=3546 ppcomm=adbd pid=6279 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 16:35:16.115  2045  2045 E audit   : type=1327 msg=audit(1470839716.115:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-10 16:35:16.115  2045  2045 E audit   : type=1320 msg=audit(1470839716.115:284): 
08-10 16:35:16.115   744  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2ae4197 1788:com.google.android.googlequicksearchbox:search/u0a61}
08-10 16:35:16.125   744  1677 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
08-10 16:35:16.145   744  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2ae4197 1788:com.google.android.googlequicksearchbox:search/u0a61}
08-10 16:35:16.145   744  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2af05d 6213:com.samsung.android.sm.provider/1000}
08-10 16:35:16.165  6366  6366 E Zygote  : v2
08-10 16:35:16.165   744   757 I ActivityManager: Start proc 6366:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-10 16:35:16.175  6366  6366 I libpersona: KNOX_SDCARD checking this for 5012
08-10 16:35:16.175  6366  6366 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:16.175  6366  6366 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:16.175  6366  6366 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:16.175  6366  6366 E Zygote  : accessInfo : 0
08-10 16:35:16.175  6366  6366 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-10 16:35:16.175  1788  6364 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-10 16:35:16.175  2045  2045 E audit   : type=1400 msg=audit(1470839716.175:285): avc:  denied  { execmod } for  pid=6279 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 16:35:16.175  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:16.175  2045  2045 E audit   : type=1300 msg=audit(1470839716.175:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f77000 a1=51000 a2=5 a3=4 items=0 ppid=3546 ppcomm=adbd pid=6279 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 16:35:16.175  2045  2045 E audit   : type=1327 msg=audit(1470839716.175:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-10 16:35:16.175  2045  2045 E audit   : type=1320 msg=audit(1470839716.175:285): 
08-10 16:35:16.195  6366  6366 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:16.195  6366  6366 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:16.205   744  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{272ddd2 6366:com.samsung.android.sm.devicesecurity/5012}
08-10 16:35:16.215  6366  6366 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-10 16:35:16.225  2045  2045 E audit   : type=1400 msg=audit(1470839716.225:286): avc:  denied  { execmod } for  pid=6279 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 16:35:16.225  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:16.225  2045  2045 E audit   : type=1300 msg=audit(1470839716.225:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f75000 a1=51000 a2=5 a3=4 items=0 ppid=3546 ppcomm=adbd pid=6279 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 16:35:16.225  2045  2045 E audit   : type=1327 msg=audit(1470839716.225:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-10 16:35:16.225  2045  2045 E audit   : type=1320 msg=audit(1470839716.225:286): 
08-10 16:35:16.225  6279  6279 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 16:35:16.225  6366  6366 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-10 16:35:16.235  6279  6279 D AndroidRuntime: CheckJNI is OFF
08-10 16:35:16.235  6279  6279 D AndroidRuntime: readGMSProperty: start
08-10 16:35:16.235  6279  6279 D AndroidRuntime: readGMSProperty: already setted!!
08-10 16:35:16.235  6279  6279 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-10 16:35:16.235  6279  6279 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-10 16:35:16.235  6279  6279 D AndroidRuntime: readGMSProperty: end
08-10 16:35:16.235  6279  6279 D AndroidRuntime: addProductProperty: start
08-10 16:35:16.235  6279  6279 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-10 16:35:16.235  6279  6279 W art     : af124000-b204a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-10 16:35:16.235  6279  6279 W art     : b204a000-b42b9000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-10 16:35:16.235  6279  6279 W art     : b42b9000-b42ba000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-10 16:35:16.235  6279  6279 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-10 16:35:16.235  6279  6279 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-10 16:35:16.235  6279  6279 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-10 16:35:16.235  6279  6279 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-10 16:35:16.235  6279  6279 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-10 16:35:16.235  6279  6279 W art     : b4845000-b4848000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-10 16:35:16.235  6279  6279 W art     : b4848000-b4849000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-10 16:35:16.235  6279  6279 W art     : b4849000-b484a000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-10 16:35:16.235  6279  6279 W art     : b484a000-b484b000 r--p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b484b000-b486b000 r--s 00000000 00:0b 8210       /dev/__properties__
08-10 16:35:16.235  6279  6279 W art     : b486b000-b527c000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-10 16:35:16.235  6279  6279 W art     : b527c000-b527d000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b527d000-b52c6000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-10 16:35:16.235  6279  6279 W art     : b52c6000-b52c7000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-10 16:35:16.235  6279  6279 W art     : b52c7000-b52cf000 rw-p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b52cf000-b52d0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.235  6279  6279 W art     : b52d0000-b5305000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-10 16:35:16.235  6279  6279 W art     : b5305000-b5306000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5306000-b5307000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-10 16:35:16.235  6279  6279 W art     : b5307000-b5308000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-10 16:35:16.235  6279  6279 W art     : b5308000-b5360000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-10 16:35:16.235  6279  6279 W art     : b5360000-b5361000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5361000-b5362000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-10 16:35:16.235  6279  6279 W art     : b5362000-b5363000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-10 16:35:16.235  6279  6279 W art     : b5364000-b536a000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 16:35:16.235  6279  6279 W art     : b536a000-b536b000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 16:35:16.235  6279  6279 W art     : b536b000-b536c000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 16:35:16.235  6279  6279 W art     : b536c000-b536e000 rw-p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b536f000-b5379000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 16:35:16.235  6279  6279 W art     : b5379000-b537c000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 16:35:16.235  6279  6279 W art     : b537c000-b537d000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 16:35:16.235  6279  6279 W art     : b537e000-b5395000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 16:35:16.235  6279  6279 W art     : b5395000-b5396000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5396000-b5397000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 16:35:16.235  6279  6279 W art     : b5397000-b5398000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 16:35:16.235  6279  6279 W art     : b5399000-b53a3000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-10 16:35:16.235  6279  6279 W art     : b53a3000-b53a4000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-10 16:35:16.235  6279  6279 W art     : b53a4000-b53a5000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-10 16:35:16.235  6279  6279 W art     : b53a5000-b53a9000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 16:35:16.235  6279  6279 W art     : b53a9000-b53aa000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 16:35:16.235  6279  6279 W art     : b53aa000-b53ab000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 16:35:16.235  6279  6279 W art     : b53ab000-b53c1000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-10 16:35:16.235  6279  6279 W art     : b53c1000-b53c2000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-10 16:35:16.235  6279  6279 W art     : b53c2000-b53c3000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-10 16:35:16.235  6279  6279 W art     : b53c3000-b53d0000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-10 16:35:16.235  6279  6279 W art     : b53d0000-b53d1000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-10 16:35:16.235  6279  6279 W art     : b53d1000-b53d2000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-10 16:35:16.235  6279  6279 W art     : b53d2000-b5432000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-10 16:35:16.235  6279  6279 W art     : b5432000-b5435000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-10 16:35:16.235  6279  6279 W art     : b5435000-b5439000 rw-p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5439000-b549a000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-10 16:35:16.235  6279  6279 W art     : b549a000-b549b000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-10 16:35:16.235  6279  6279 W art     : b549b000-b54ea000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-10 16:35:16.235  6279  6279 W art     : b54ea000-b54ec000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-10 16:35:16.235  6279  6279 W art     : b54ec000-b54ed000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-10 16:35:16.235  6279  6279 W art     : b54ed000-b54ee000 rw-p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b54ee000-b54f5000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-10 16:35:16.235  6279  6279 W art     : b54f5000-b54f6000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-10 16:35:16.235  6279  6279 W art     : b54f6000-b54f7000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-10 16:35:16.235  6279  6279 W art     : avc_common.so
08-10 16:35:16.235  6279  6279 W art     : b54f8000-b54fb000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-10 16:35:16.235  6279  6279 W art     : b54fb000-b54fc000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-10 16:35:16.235  6279  6279 W art     : b54fc000-b54fd000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-10 16:35:16.235  6279  6279 W art     : enc_common.so
08-10 16:35:16.235  6279  6279 W art     : b54fe000-b5502000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-10 16:35:16.235  6279  6279 W art     : b5502000-b5503000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5503000-b5504000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-10 16:35:16.235  6279  6279 W art     : b5504000-b5505000 rw-p 00005000 b3:17 2510       /syste
08-10 16:35:16.235  6279  6279 W art     : m/lib/libpowermanager.so
08-10 16:35:16.235  6279  6279 W art     : b5506000-b5523000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 16:35:16.235  6279  6279 W art     : b5523000-b5524000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 16:35:16.235  6279  6279 W art     : b5524000-b5525000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 16:35:16.235  6279  6279 W art     : b5526000-b552b000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 16:35:16.235  6279  6279 W art     : b552b000-b552c000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 16:35:16.235  6279  6279 W art     : b552c000-b552d000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 16:35:16.235  6279  6279 W art     : b552e000-b555f000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 16:35:16.235  6279  6279 W art     : b555f000-b5562000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 16:35:16.235  6279  6279 W art     : b5562000-b5563000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 16:35:16.235  6279  6279 W art     : b5564000-b559f000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-10 16:35:16.235  6279  6279 W art     : b559f000-b55a0000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-10 16:35:16.235  6279  6279 W art     : b55a0000-b55a1000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-10 16:35:16.235  6279  6279 W art     : b55a2000-b55a9000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-10 16:35:16.235  6279  6279 W art     : b55a9000-b55aa000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b55aa000-b55ab000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-10 16:35:16.235  6279  6279 W art     : b55ab000-b55ac000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-10 16:35:16.235  6279  6279 W art     : b55ac000-b55ad000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.235  6279  6279 W art     : b55ad000-b55c4000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-10 16:35:16.235  6279  6279 W art     : b55c4000-b55c5000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b55c5000-b55c8000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-10 16:35:16.235  6279  6279 W art     : b55c8000-b55c9000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-10 16:35:16.235  6279  6279 W art     : b55c9000-b55e8000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-10 16:35:16.235  6279  6279 W art     : b55e8000-b55e9000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-10 16:35:16.235  6279  6279 W art     : b55e9000-b55ea000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-10 16:35:16.235  6279  6279 W art     : b55ea000-b5628000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-10 16:35:16.235  6279  6279 W art     : b5628000-b5629000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5629000-b562b000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-10 16:35:16.235  6279  6279 W art     : b562b000-b562c000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-10 16:35:16.235  6279  6279 W art     : b562d000-b5634000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 16:35:16.235  6279  6279 W art     : b5634000-b5635000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 16:35:16.235  6279  6279 W art     : b5635000-b5636000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 16:35:16.235  6279  6279 W art     : b5637000-b563a000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 16:35:16.235  6279  6279 W art     : b563a000-b563b000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 16:35:16.235  6279  6279 W art     : b563b000-b563c000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 16:35:16.235  6279  6279 W art     : b563c000-b5642000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 16:35:16.235  6279  6279 W art     : b5642000-b5643000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5643000-b5644000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 16:35:16.235  6279  6279 W art     : b5644000-b5645000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 16:35:16.235  6279  6279 W art     : b5645000-b564e000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-10 16:35:16.235  6279  6279 W art     : b564e000-b564f000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-10 16:35:16.235  6279  6279 W art     : b564f000-b5650000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-10 16:35:16.235  6279  6279 W art     : b5650000-b56e1000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 16:35:16.235  6279  6279 W art     : b56e1000-b56e2000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b56e2000-b56ed000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 16:35:16.235  6279  6279 W art     : b56ed000-b56ee000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 16:35:16.235  6279  6279 W art     : b56ef000-b5701000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-10 16:35:16.235  6279  6279 W art     : b5701000-b5702000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-10 16:35:16.235  6279  6279 W art     : b5702000-b5703000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-10 16:35:16.235  6279  6279 W art     : b5704000-b5709000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-10 16:35:16.235  6279  6279 W art     : b5709000-b570a000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-10 16:35:16.235  6279  6279 W art     : b570a000-b570b000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-10 16:35:16.235  6279  6279 W art     : b570c000-b5779000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-10 16:35:16.235  6279  6279 W art     : b5779000-b577a000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b577a000-b577c000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-10 16:35:16.235  6279  6279 W art     : b577c000-b577d000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-10 16:35:16.235  6279  6279 W art     : b577d000-b577e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.235  6279  6279 W art     : b577e000-b5785000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 16:35:16.235  6279  6279 W art     : b5785000-b5786000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 16:35:16.235  6279  6279 W art     : b5786000-b5787000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 16:35:16.235  6279  6279 W art     : b5788000-b5808000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 16:35:16.235  6279  6279 W art     : b5808000-b5809000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5809000-b580a000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 16:35:16.235  6279  6279 W art     : b580a000-b580b000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 16:35:16.235  6279  6279 W art     : b580b000-b5822000 rw-p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5822000-b5859000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-10 16:35:16.235  6279  6279 W art     : ib/libqc-opt.so
08-10 16:35:16.235  6279  6279 W art     : b5859000-b585a000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-10 16:35:16.235  6279  6279 W art     : b585a000-b585b000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-10 16:35:16.235  6279  6279 W art     : b585b000-b5877000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 16:35:16.235  6279  6279 W art     : b5877000-b5878000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 16:35:16.235  6279  6279 W art     : b5878000-b5879000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 16:35:16.235  6279  6279 W art     : b587a000-b58db000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-10 16:35:16.235  6279  6279 W art     : b58db000-b58dd000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-10 16:35:16.235  6279  6279 W art     : b58dd000-b58de000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-10 16:35:16.235  6279  6279 W art     : b58df000-b5906000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-10 16:35:16.235  6279  6279 W art     : b5906000-b5907000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5907000-b5908000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-10 16:35:16.235  6279  6279 W art     : b5908000-b5909000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-10 16:35:16.235  6279  6279 W art     : b590a000-b5912000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 16:35:16.235  6279  6279 W art     : b5912000-b5914000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 16:35:16.235  6279  6279 W art     : b5914000-b5915000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 16:35:16.235  6279  6279 W art     : b5916000-b5919000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-10 16:35:16.235  6279  6279 W art     : b5919000-b591a000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-10 16:35:16.235  6279  6279 W art     : b591a000-b591b000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-10 16:35:16.235  6279  6279 W art     : b591b000-b591f000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-10 16:35:16.235  6279  6279 W art     : b591f000-b5920000 ---p 00000000 00:00 0 
08-10 16:35:16.235  6279  6279 W art     : b5920000-b5921000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-10 16:35:16.235  6279  6279 W art     : b5921000-b5922000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-10 16:35:16.235  6279  6279 W art     : b5922000-b5932000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-10 16:35:16.245  6279  6279 W art     : b5932000-b5933000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-10 16:35:16.245  6279  6279 W art     : b5933000-b5934000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-10 16:35:16.245  6279  6279 W art     : b5934000-b597a000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b597a000-b5983000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-10 16:35:16.245  6279  6279 W art     : b5983000-b5984000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-10 16:35:16.245  6279  6279 W art     : b5984000-b5985000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-10 16:35:16.245  6279  6279 W art     : b5986000-b598b000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-10 16:35:16.245  6279  6279 W art     : b598b000-b598c000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-10 16:35:16.245  6279  6279 W art     : b598c000-b598d000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-10 16:35:16.245  6279  6279 W art     : b598d000-b5990000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 16:35:16.245  6279  6279 W art     : b5990000-b5991000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b5991000-b5992000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 16:35:16.255  1788  6364 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-10 16:35:16.245  6279  6279 W art     : b5992000-b5993000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 16:35:16.245  6279  6279 W art     : b5994000-b59ac000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 16:35:16.245  6279  6279 W art     : b59ac000-b59ad000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b59ad000-b59ae000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 16:35:16.245  6279  6279 W art     : b59ae000-b59af000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 16:35:16.245  6279  6279 W art     : b59b0000-b5b4a000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-10 16:35:16.245  6279  6279 W art     : b5b4a000-b5b4b000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b5b4b000-b5b58000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-10 16:35:16.245  6279  6279 W art     : b5b58000-b5b59000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-10 16:35:16.245  6279  6279 W art     : b5b59000-b5b5d000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-10 16:35:16.245  6279  6279 W art     : b5b5d000-b5b5e000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b5b5e000-b5b5f000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-10 16:35:16.245  6279  6279 W art     : b5b5f000-b5b60000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-10 16:35:16.245  6279  6279 W art     : b5b60000-b5b73000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-10 16:35:16.245  6279  6279 W art     : b5b73000-b5b74000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-10 16:35:16.245  6279  6279 W art     : b5b74000-b5b75000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-10 16:35:16.245  6279  6279 W art     : b5b75000-b5b76000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 16:35:16.245  6279  6279 W art     : b5b76000-b5bc1000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-10 16:35:16.245  6279  6279 W art     : b5bc1000-b5bc2000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-10 16:35:16.245  6279  6279 W art     : b5bc2000-b5bc3000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-10 16:35:16.245  6279  6279 W art     : b5bc3000-b5bc5000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b5bc6000-b5bd7000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 16:35:16.245  6279  6279 W art     : b5bd7000-b5bd8000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b5bd8000-b5bd9000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 16:35:16.245  6279  6279 W art     : b5bd9000-b5bda000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 16:35:16.245  6279  6279 W art     : b5bdb000-b5be5000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-10 16:35:16.245  6279  6279 W art     : b5be5000-b5be7000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-10 16:35:16.245  6279  6279 W art     : b5be7000-b5be8000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-10 16:35:16.245  6279  6279 W art     : b5be8000-b5c01000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-10 16:35:16.245  6279  6279 W art     : b5c01000-b5c02000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-10 16:35:16.245  6279  6279 W art     : b5c02000-b5c05000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-10 16:35:16.245  6279  6279 W art     : b5c05000-b5c09000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b5c09000-b5c7d000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-10 16:35:16.245  6279  6279 W art     : b5c7d000-b5c7e000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b5c7e000-b5c81000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-10 16:35:16.245  6279  6279 W art     : b5c81000-b5c82000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-10 16:35:16.245  6279  6279 W art     : b5c82000-b5c83000 r--p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b5c83000-b5c86000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-10 16:35:16.245  6279  6279 W art     : b5c86000-b5c87000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-10 16:35:16.245  6279  6279 W art     : b5c87000-b5c88000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-10 16:35:16.245  6279  6279 W art     : b5c88000-b5c89000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b5c89000-b5c8e000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 16:35:16.245  6279  6279 W art     : b5c8e000-b5c8f000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 16:35:16.245  6279  6279 W art     : b5c8f000-b5c90000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 16:35:16.245  6279  6279 W art     : b5c90000-b5c91000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b5c91000-b5c94000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 16:35:16.245  6279  6279 W art     : b5c94000-b5c95000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 16:35:16.245  6279  6279 W art     : b5c95000-b5c96000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 16:35:16.245  6279  6279 W art     : b5c96000-b5c97000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b5c97000-b5c9b000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-10 16:35:16.245  6279  6279 W art     : b5c9b000-b5c9c000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-10 16:35:16.245  6279  6279 W art     : b5c9c000-b5c9d000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-10 16:35:16.245  6279  6279 W art     : b5c9d000-b5c9e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 16:35:16.245  6279  6279 W art     : b5c9e000-b5ca2000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 16:35:16.245  6279  6279 W art     : b5ca2000-b5ca3000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 16:35:16.245  6279  6279 W art     : b5ca3000-b5ca4000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 16:35:16.245  6279  6279 W art     : b5ca4000-b5ca5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b5ca5000-b5cb3000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-10 16:35:16.245  6279  6279 W art     : b5cb3000-b5cb4000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b5cb4000-b5cb5000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-10 16:35:16.245  6279  6279 W art     : b5cb5000-b5cb6000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-10 16:35:16.245  6279  6279 W art     : b5cb6000-b5cc0000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 16:35:16.245  6279  6279 W art     : b5cc0000-b5cc3000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 16:35:16.245  6279  6279 W art     : b5cc3000-b5cc4000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 16:35:16.245  6279  6279 W art     : b5cc4000-b5cc5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b5cc5000-b5ccf000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-10 16:35:16.245  6279  6279 W art     : b5ccf000-b5cd2000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-10 16:35:16.245  6279  6279 W art     : b5cd2000-b5cd3000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-10 16:35:16.245  6279  6279 W art     : b5cd3000-b5cd7000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-10 16:35:16.245  6279  6279 W art     : b5cd7000-b5cd8000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-10 16:35:16.245  6279  6279 W art     : b5cd8000-b5cd9000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-10 16:35:16.245  6279  6279 W art     : b5cd9000-b5cda000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b5cda000-b5ce7000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-10 16:35:16.245  6279  6279 W art     : b5ce7000-b5ce9000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-10 16:35:16.245  6279  6279 W art     : b5ce9000-b5cea000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-10 16:35:16.245  6279  6279 W art     : b5cea000-b60fc000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-10 16:35:16.245  6279  6279 W art     : b60fc000-b60fd000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b60fd000-b6106000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-10 16:35:16.245  6279  6279 W art     : b6106000-b610a000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-10 16:35:16.245  6279  6279 W art     : b610a000-b610b000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b610b000-b6112000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-10 16:35:16.245  6279  6279 W art     : b6112000-b6113000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-10 16:35:16.245  6279  6279 W art     : b6113000-b6114000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-10 16:35:16.245  6279  6279 W art     : b6114000-b6115000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b6115000-b6130000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-10 16:35:16.245  6279  6279 W art     : b6130000-b6131000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-10 16:35:16.245  6279  6279 W art     : b6131000-b6132000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-10 16:35:16.245  6279  6279 W art     : b6132000-b6133000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b6133000-b617f000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 16:35:16.245  6279  6279 W art     : b617f000-b6180000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6180000-b6181000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 16:35:16.245  6279  6279 W art     : b6181000-b6182000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 16:35:16.245  6279  6279 W art     : b6182000-b6183000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b6183000-b6187000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-10 16:35:16.245  6279  6279 W art     : b6187000-b6188000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6188000-b6189000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-10 16:35:16.245  6279  6279 W art     : b6189000-b618a000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-10 16:35:16.245  6279  6279 W art     : b618a000-b61c2000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-10 16:35:16.245  6279  6279 W art     : b61c2000-b61c3000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-10 16:35:16.245  6279  6279 W art     : b61c3000-b61c4000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-10 16:35:16.245  6279  6279 W art     : b61c4000-b61c5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b61c5000-b6263000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-10 16:35:16.245  6279  6279 W art     : b6263000-b6264000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6264000-b6282000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-10 16:35:16.245  6279  6279 W art     : b6282000-b6283000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-10 16:35:16.245  6279  6279 W art     : b6283000-b63f6000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-10 16:35:16.245  6279  6279 W art     : b63f6000-b6401000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-10 16:35:16.245  6279  6279 W art     : b6401000-b6402000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-10 16:35:16.245  6279  6279 W art     : b6402000-b6519000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-10 16:35:16.245  6279  6279 W art     : b6519000-b6524000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-10 16:35:16.245  6279  6279 W art     : b6524000-b6525000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-10 16:35:16.245  6279  6279 W art     : b6525000-b6529000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6529000-b654d000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-10 16:35:16.245  6279  6279 W art     : b654d000-b654f000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-10 16:35:16.245  6279  6279 W art     : b654f000-b6550000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-10 16:35:16.245  6279  6279 W art     : b6550000-b65f6000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-10 16:35:16.245  6279  6279 W art     : b65f6000-b6603000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-10 16:35:16.245  6279  6279 W art     : b6603000-b6604000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-10 16:35:16.245  6279  6279 W art     : b6604000-b6605000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6605000-b6658000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-10 16:35:16.245  6279  6279 W art     : b6658000-b6659000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6659000-b665a000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-10 16:35:16.245  6279  6279 W art     : b665a000-b665b000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-10 16:35:16.245  6279  6279 W art     : b665b000-b6660000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6660000-b6672000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-10 16:35:16.245  6279  6279 W art     : b6672000-b6673000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6673000-b6674000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-10 16:35:16.245  6279  6279 W art     : b6674000-b6675000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-10 16:35:16.245  6279  6279 W art     : b6675000-b667c000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 16:35:16.245  6279  6279 W art     : b667c000-b667d000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 16:35:16.245  6279  6279 W art     : b667d000-b667e000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 16:35:16.245  6279  6279 W art     : b667e000-b667f000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b667f000-b6682000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-10 16:35:16.245  6279  6279 W art     : b6682000-b6683000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-10 16:35:16.245  6279  6279 W art     : b6683000-b6684000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-10 16:35:16.245  6279  6279 W art     : b6684000-b6688000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-10 16:35:16.245  6279  6279 W art     : b6688000-b6689000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-10 16:35:16.245  6279  6279 W art     : b6689000-b668a000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-10 16:35:16.245  6279  6279 W art     : b668a000-b6698000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-10 16:35:16.245  6279  6279 W art     : b6698000-b6699000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6699000-b669a000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-10 16:35:16.245  6279  6279 W art     : b669a000-b669b000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-10 16:35:16.245  6279  6279 W art     : b669b000-b66a4000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 16:35:16.245  6279  6279 W art     : b66a4000-b66a5000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 16:35:16.245  6279  6279 W art     : b66a5000-b66a6000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 16:35:16.245  6279  6279 W art     : b66a6000-b670c000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-10 16:35:16.245  6279  6279 W art     : b670c000-b670d000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b670d000-b670f000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-10 16:35:16.245  6279  6279 W art     : b670f000-b6718000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-10 16:35:16.245  6279  6279 W art     : b6718000-b671b000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b671b000-b67b2000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-10 16:35:16.245  6279  6279 W art     : b67b2000-b67b4000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-10 16:35:16.245  6279  6279 W art     : b67b4000-b67b5000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-10 16:35:16.245  6279  6279 W art     : b67b5000-b67b6000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b67b6000-b6ad7000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-10 16:35:16.245  6279  6279 W art     : b6ad7000-b6ad8000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6ad8000-b6af3000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-10 16:35:16.245  6279  6279 W art     : b6af3000-b6af7000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-10 16:35:16.245  6279  6279 W art     : b6af7000-b6afc000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6afc000-b6b04000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 16:35:16.245  6279  6279 W art     : b6b04000-b6b05000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 16:35:16.245  6279  6279 W art     : b6b05000-b6b06000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 16:35:16.245  6279  6279 W art     : b6b06000-b6b34000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-10 16:35:16.245  6279  6279 W art     : b6b34000-b6b35000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6b35000-b6b3c000 r--p 0002e000 b3:17 564        /system/lib/libcam,era_client.so
08-10 16:35:16.245  6279  6279 W art     : b6b3c000-b6b3d000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-10 16:35:16.245  6279  6279 W art     : b6b3d000-b6b83000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-10 16:35:16.245  6279  6279 W art     : b6b83000-b6b84000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6b84000-b6b87000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-10 16:35:16.245  6279  6279 W art     : b6b87000-b6b88000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-10 16:35:16.245  6279  6279 W art     : b6b88000-b6ba3000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-10 16:35:16.245  6279  6279 W art     : b6ba3000-b6ba7000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-10 16:35:16.245  6279  6279 W art     : b6ba7000-b6ba8000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-10 16:35:16.245  6279  6279 W art     : b6ba8000-b6bf5000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-10 16:35:16.245  6279  6279 W art     : b6bf5000-b6bf6000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6bf6000-b6c02000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-10 16:35:16.245  6279  6279 W art     : b6c02000-b6c03000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-10 16:35:16.245  6279  6279 W art     : b6c03000-b6c10000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-10 16:35:16.245  6279  6279 W art     : b6c10000-b6c11000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6c11000-b6c12000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-10 16:35:16.245  6279  6279 W art     : b6c12000-b6c13000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-10 16:35:16.245  6279  6279 W art     : b6c13000-b6c1b000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-10 16:35:16.245  6279  6279 W art     : b6c1b000-b6c1c000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6c1c000-b6c1d000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-10 16:35:16.245  6279  6279 W art     : b6c1d000-b6c1e000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-10 16:35:16.245  6279  6279 W art     : b6c1e000-b6c25000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-10 16:35:16.245  6279  6279 W art     : b6c25000-b6c26000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-10 16:35:16.245  6279  6279 W art     : b6c26000-b6c27000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-10 16:35:16.245  6279  6279 W art     : b6c27000-b6c3b000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-10 16:35:16.245  6279  6279 W art     : b6c3b000-b6c3d000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-10 16:35:16.245  6279  6279 W art     : b6c3d000-b6c3e000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-10 16:35:16.245  6279  6279 W art     : b6c3e000-b6c66000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-10 16:35:16.245  6279  6279 W art     : b6c66000-b6c68000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-10 16:35:16.245  6279  6279 W art     : b6c68000-b6c69000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-10 16:35:16.245  6279  6279 W art     : b6c69000-b6c6c000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-10 16:35:16.245  6279  6279 W art     : b6c6c000-b6c6d000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-10 16:35:16.245  6279  6279 W art     : b6c6d000-b6c6e000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-10 16:35:16.245  6279  6279 W art     : b6c6e000-b6c77000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-10 16:35:16.245  6279  6279 W art     : b6c77000-b6c78000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-10 16:35:16.245  6279  6279 W art     : b6c78000-b6c79000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-10 16:35:16.245  6279  6279 W art     : b6c79000-b6c99000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-10 16:35:16.245  6279  6279 W art     : b6c99000-b6c9a000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-10 16:35:16.245  6279  6279 W art     : b6c9a000-b6c9b000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-10 16:35:16.245  6279  6279 W art     : b6c9b000-b6d0e000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-10 16:35:16.245  6279  6279 W art     : b6d0e000-b6d12000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-10 16:35:16.245  6279  6279 W art     : b6d12000-b6d15000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-10 16:35:16.245  6279  6279 W art     : b6d15000-b6d1f000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6d1f000-b6da7000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-10 16:35:16.245  6279  6279 W art     : b6da7000-b6da8000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6da8000-b6dac000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-10 16:35:16.245  6279  6279 W art     : b6dac000-b6dad000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-10 16:35:16.245  6279  6279 W art     : b6dad000-b6dae000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6dae000-b6dd7000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-10 16:35:16.245  6279  6279 W art     : b6dd7000-b6dd8000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6dd8000-b6ddb000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-10 16:35:16.245  6279  6279 W art     : b6ddb000-b6ddc000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-10 16:35:16.245  6279  6279 W art     : b6ddc000-b6eb6000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 16:35:16.245  6279  6279 W art     : b6eb6000-b6ebd000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 16:35:16.245  6279  6279 W art     : b6ebd000-b6ec5000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 16:35:16.245  6279  6279 W art     : b6ec5000-b6ec6000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6ec6000-b6ec7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 16:35:16.245  6279  6279 W art     : b6ec7000-b6ec8000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-10 16:35:16.245  6279  6279 W art     : b6ec8000-b6ec9000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b6ec9000-b6ecc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b6ecc000-b6ef1000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-10 16:35:16.245  6279  6279 W art     : b6ef1000-b6ef2000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6ef2000-b6ef9000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-10 16:35:16.245  6279  6279 W art     : b6ef9000-b6efa000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-10 16:35:16.245  6279  6279 W art     : b6efa000-b6f01000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-10 16:35:16.245  6279  6279 W art     : b6f01000-b6f02000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-10 16:35:16.245  6279  6279 W art     : b6f02000-b6f03000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-10 16:35:16.245  6279  6279 W art     : b6f03000-b6f04000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b6f04000-b6f1c000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-10 16:35:16.245  6279  6279 W art     : b6f1c000-b6f1d000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6f1d000-b6f1e000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-10 16:35:16.245  6279  6279 W art     : b6f1e000-b6f1f000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-10 16:35:16.245  6279  6279 W art     : b6f1f000-b6f2d000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-10 16:35:16.245  6279  6279 W art     : b6f2d000-b6f2e000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6f2e000-b6f2f000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-10 16:35:16.245  6279  6279 W art     : b6f2f000-b6f30000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-10 16:35:16.245  6279  6279 W art     : b6f30000-b6f31000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 16:35:16.245  6279  6279 W art     : b6f31000-b6f33000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b6f33000-b6f34000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b6f34000-b6f35000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 16:35:16.245  6279  6279 W art     : b6f35000-b6f36000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-10 16:35:16.245  6279  6279 W art     : b6f36000-b6f37000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:16.245  6279  6279 W art     : b6f37000-b6f57000 r--s 00000000 00:0b 8210       /dev/__properties__
08-10 16:35:16.245  6279  6279 W art     : b6f57000-b6f58000 r--p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6f58000-b6f59000 ---p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6f59000-b6f5b000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-10 16:35:16.245  6279  6279 W art     : b6f5b000-b6f5c000 r-xp 00000000 00:00 0          [sigpage]
08-10 16:35:16.245  6279  6279 W art     : b6f5c000-b6f77000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-10 16:35:16.245  6279  6279 W art     : b6f77000-b6f78000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-10 16:35:16.245  6279  6279 W art     : b6f78000-b6f7a000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-10 16:35:16.245  6279  6279 W art     : b6f7a000-b6f7c000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : b6f7c000-b6f81000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-10 16:35:16.245  6279  6279 W art     : b6f81000-b6f82000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-10 16:35:16.245  6279  6279 W art     : b6f82000-b6f83000 rw-p 00000000 00:00 0 
08-10 16:35:16.245  6279  6279 W art     : bef57000-bef78000 rw-p 00000000 00:00 0          [stack]
08-10 16:35:16.245  6279  6279 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-10 16:35:16.285   744  1677 I ActivityManager: Killing 5522:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
08-10 16:35:16.285  6279  6279 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 16:35:16.285  1788  6364 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-10 16:35:16.285   744  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1784a48 3188:com.android.contacts/u0a19}
08-10 16:35:16.305  6383  6383 E Zygote  : v2
08-10 16:35:16.305  6383  6383 I libpersona: KNOX_SDCARD checking this for 10049
08-10 16:35:16.305  6383  6383 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:16.305   744  2155 I ActivityManager: Start proc 6383:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-10 16:35:16.305  6383  6383 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:16.305  6383  6383 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:16.305  6383  6383 E Zygote  : accessInfo : 0
08-10 16:35:16.305  6383  6383 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-10 16:35:16.325   744   806 I ActivityManager: Start proc 6393:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-10 16:35:16.325  6393  6393 E Zygote  : v2
08-10 16:35:16.325  6393  6393 I libpersona: KNOX_SDCARD checking this for 10210
08-10 16:35:16.325  6393  6393 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:16.325  6393  6393 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:16.325  6393  6393 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:16.325  6393  6393 E Zygote  : accessInfo : 0
08-10 16:35:16.325  6393  6393 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-10 16:35:16.325  6279  6279 I Radio-JNI: register_android_hardware_Radio DONE
08-10 16:35:16.325   744  1988 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
08-10 16:35:16.335  6279  6279 E AffinityControl: AffinityControl: registerfunction enter
08-10 16:35:16.355   744  1218 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-10 16:35:16.355  6279  6279 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-10 16:35:16.365   744  3404 D SSRM:n  : SIOP:: AP = 470, PST = 450, CUR = 450, LCD = 0
08-10 16:35:16.365  6383  6383 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:16.365  6383  6383 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:16.375  6393  6393 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:16.375  6393  6393 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:16.375   744  2093 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-10 16:35:16.385   744  2093 D ActivityManager: mDVFSHelper.acquire()
08-10 16:35:16.385   744  2093 D FocusedStackFrame: Set to : 0
08-10 16:35:16.385   744  2093 V WindowManager: addAppToken: AppWindowToken{b50ce15 token=Token{3b33bcc ActivityRecord{87e81ff u0 com.test.thalitest/.MainActivity t152}}} to stack=1 task=152 at 0
08-10 16:35:16.395   744   863 D SecWifiDisplayUtil: Metadata value : none
08-10 16:35:16.395   744   863 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{92daacd V.E...... R.....ID 0,0-0,0}
08-10 16:35:16.405   744   863 D ISSUE_DEBUG: InputChannelName : 107693 Starting com.test.thalitest
08-10 16:35:16.405   744  2093 I ActivityManager: Start proc 6410:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-10 16:35:16.405  6410  6410 E Zygote  : v2
08-10 16:35:16.405  6410  6410 I libpersona: KNOX_SDCARD checking this for 10004
08-10 16:35:16.405  6410  6410 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:16.405  6410  6410 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:16.405  6410  6410 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:16.405   744  2093 D InputDispatcher: Focused application set to: xxxx
08-10 16:35:16.405  6410  6410 E Zygote  : accessInfo : 0
08-10 16:35:16.405   744  2093 D InputDispatcher: Focus left window: 1665
08-10 16:35:16.405  6410  6410 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-10 16:35:16.405   744  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-10 16:35:16.415  6279  6279 D AndroidRuntime: Shutting down VM
08-10 16:35:16.415   744  2139 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3d576d0 6383:com.android.mms/u0a49}
08-10 16:35:16.415   293   293 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
08-10 16:35:16.425   744  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-10 16:35:16.425   744  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-10 16:35:16.475  6410  6410 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:16.475  6410  6410 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:16.475  6393  6393 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-10 16:35:16.485   744  1678 V WindowOrientationListener: setCurrentAppOrientation :-1
08-10 16:35:16.485   744  1678 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-10 16:35:16.485   744   863 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:744 uid:1000
08-10 16:35:16.485   744   863 D PointerIcon: setMouseCustomIcon IconType is same.101
08-10 16:35:16.485   744   863 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:744 uid:1000
08-10 16:35:16.485   744   863 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-10 16:35:16.485   744   863 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-10 16:35:16.485   744   809 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{107693 u0 d0 Starting com.test.thalitest}
08-10 16:35:16.485  1375  1375 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-10 16:35:16.495   744  1678 D ActivityManager:  Launching com.test.thalitest, updated priority
08-10 16:35:16.495  6383  6383 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-10 16:35:16.505   744   806 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-10 16:35:16.515  1665  1869 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-10 16:35:16.515  1665  1665 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-10 16:35:16.525   744   863 V WindowStateAnimator: Finishing drawing window Window{107693 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-10 16:35:16.535  6393  6393 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-10 16:35:16.535   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed76364
08-10 16:35:16.535  6383  6383 W System  : ClassLoader referenced unknown path: imsmanager.jar
08-10 16:35:16.545  6383  6383 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-10 16:35:16.545  6393  6393 D AASAservice: onCreate()
08-10 16:35:16.545   293   382 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
08-10 16:35:16.545   293   382 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
08-10 16:35:16.555   293   382 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-10 16:35:16.555   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed763a4
08-10 16:35:16.555   293  1297 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-10 16:35:16.565  2364  2374 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-10 16:35:16.565  1665  1665 V ActivityThread: updateVisibility : ActivityRecord{1a94b85 token=android.os.BinderProxy@5228b3e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-10 16:35:16.565  1665  1665 D Launcher: onTrimMemory. Level: 20
,08-10 16:35:16.645   744   757 I ActivityManager: Killing 5063:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-10 16:35:16.645  6410  6410 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-10 16:35:16.655  5244  5244 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-10 16:35:16.665  6383  6383 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-10 16:35:16.675   744  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-10 16:35:16.685  6410  6410 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-10 16:35:16.695  6410  6410 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-10 16:35:16.695  4144  6423 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-10 16:35:16.715   744  2093 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-10 16:35:16.715  6410  6410 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-10 16:35:16.725  6383  6383 D Mms/TelephonyPermission: start operation mode monitor
,08-10 16:35:16.725  6383  6383 D Mms/TelephonyPermission: User ID is null set current User Id
,08-10 16:35:16.735  6383  6428 D Mms/ArtClassLoader: init before art second
,08-10 16:35:16.735  6383  6429 D Mms/ArtClassLoader: init before art third
,08-10 16:35:16.735  6383  6383 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-10 16:35:16.745  6383  6383 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
08-10 16:35:16.745  6410  6410 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-10 16:35:16.745  1788  6364 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 568 ms] updated apps [took 568 ms] 
,08-10 16:35:16.745  6410  6410 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 16:35:16.755  6410  6410 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 9550-9554)
08-10 16:35:16.755  6410  6410 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-10 16:35:16.755  6383  6427 D Mms/ArtClassLoader: init before art first
,08-10 16:35:16.765   744   754 I art     : Background partial concurrent mark sweep GC freed 55563(3MB) AllocSpace objects, 10(340KB) LOS objects, 27% free, 42MB/58MB, paused 1.803ms total 141.368ms
,08-10 16:35:16.775  6410  6432 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-10 16:35:16.775  6410  6410 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {861224e}
,08-10 16:35:16.775  6410  6410 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-10 16:35:16.775  6410  6410 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 16:35:16.775  6383  6383 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,08-10 16:35:16.775  6383  6383 D Mms/TelephonyPermission: isDefault true
,08-10 16:35:16.785  6410  6410 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-10 16:35:16.795  6383  6383 D Mms/MmsApp: onCreate() com.android.mms
,08-10 16:35:16.795  6383  6429 D Mms/ArtClassLoader: init [DONE] art
,08-10 16:35:16.815  6410  6410 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-10 16:35:16.815  6410  6410 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-10 16:35:16.815  6410  6410 I Adreno-EGL: Build Date: 01/28/16 Thu
08-10 16:35:16.815  6410  6410 I Adreno-EGL: Local Branch: ss
08-10 16:35:16.815  6410  6410 I Adreno-EGL: Remote Branch: 
08-10 16:35:16.815  6410  6410 I Adreno-EGL: Local Patches: 
08-10 16:35:16.815  6410  6410 I Adreno-EGL: Reconstruct Branch: 
,08-10 16:35:16.815  6410  6410 D libEGL  : eglInitialize EGLDisplay = 0xbeaa7dac
,08-10 16:35:16.855   744  2155 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-10 16:35:16.855   744  2155 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-10 16:35:16.885  6383  6383 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-10 16:35:16.895  6383  6383 D Mms/MmsApp: [start]    initCountryIso consume time = 226.762449
,08-10 16:35:16.895   744  1414 D CountryDetector: The first listener is added
,08-10 16:35:16.905  6383  6383 D Mms/MmsApp: [end]    initCountryIso consume time = 12.590885
08-10 16:35:16.905  6383  6383 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.099166
,08-10 16:35:16.905  6410  6410 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-10 16:35:16.925  6410  6410 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 16:35:16.925  6410  6410 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-10 16:35:16.925  6410  6410 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-10 16:35:16.925  6383  6383 D Mms/MmsConfig: before partial update
,08-10 16:35:16.945  6410  6410 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-10 16:35:16.965  6410  6410 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-10 16:35:16.975  6410  6410 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-10 16:35:16.985  6383  6428 D Mms/ArtClassLoader: init [DONE] art
,08-10 16:35:16.995  6383  6427 D Mms/ArtClassLoader: init [DONE] art
,08-10 16:35:16.995  6383  6383 D Mms/MmsConfig: Load Resize quality : 80
,08-10 16:35:16.995  6383  6383 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-10 16:35:16.995  6383  6383 D EasySignUpManager_1.0.5: isAuth is false
08-10 16:35:16.995  6383  6383 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-10 16:35:16.995  6383  6383 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-10 16:35:16.995  6383  6383 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-10 16:35:16.995  6383  6383 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-10 16:35:16.995  6383  6383 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-10 16:35:16.995  6383  6383 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-10 16:35:16.995  6383  6383 D EasySignUpManager_1.0.5: isAuth is false
08-10 16:35:16.995  6383  6383 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
,08-10 16:35:17.005  6383  6383 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-10 16:35:17.005  1647  1662 D TP/MmsSmsProvider: query, match:2117, calling pid = 6383, accessRestricted = false
,08-10 16:35:17.015  1647  1662 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.136 ms
,08-10 16:35:17.015  6383  6383 E CscParser: mps_code.dat does not exist
,08-10 16:35:17.015  6383  6383 E CscParser: customer_path =/system/csc/customer.xml
08-10 16:35:17.015  6383  6383 E CscParser: fileName + /system/csc/customer.xml
,08-10 16:35:17.025  6383  6383 E CscParser: mps_code.dat does not exist
,08-10 16:35:17.025  6383  6383 E CscParser: customer_path =/system/csc/customer.xml
08-10 16:35:17.025  6383  6383 E CscParser: fileName + /system/csc/customer.xml
,08-10 16:35:17.035  6383  6383 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-10 16:35:17.035  6383  6383 D Mms/MmsConfig:  enable multiwindow = true
,08-10 16:35:17.035  6383  6383 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-10 16:35:17.035  6383  6383 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-10 16:35:17.035  6383  6383 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-10 16:35:17.035  6383  6383 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-10 16:35:17.035  6383  6383 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-10 16:35:17.035  6383  6383 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-10 16:35:17.035  6383  6383 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-10 16:35:17.045   744  3441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-10 16:35:17.045  6383  6383 D Mms/MmsConfig: [end]    init() consume time = 139.736511
,08-10 16:35:17.045  6410  6410 D SecWifiDisplayUtil: Metadata value : none
,08-10 16:35:17.045  6410  6410 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{cc980dc I.E...... R.....ID 0,0-0,0}
,08-10 16:35:17.055  6383  6383 D Mms/Contact: [start]    init() consume time = 5.871302
,08-10 16:35:17.055  6410  6459 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 16:35:17.055   744   759 D ISSUE_DEBUG: InputChannelName : ba7503a com.test.thalitest/com.test.thalitest.MainActivity
,08-10 16:35:17.055   744  2139 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-10 16:35:17.055   744  2139 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-10 16:35:17.055   744   744 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-10 16:35:17.055   744   744 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-10 16:35:17.075  6383  6383 D Mms/Contact: [end]    init consume time = 22.131771
08-10 16:35:17.075  1647  1877 D TP/MmsSmsProvider: query, match:13, calling pid = 6383, accessRestricted = false
,08-10 16:35:17.075  1647  1877 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.325 ms
,08-10 16:35:17.075  6383  6463 D Mms/DraftCache: [start]    rebuildCache consume time = 4.385937
08-10 16:35:17.075  6410  6410 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6410
08-10 16:35:17.085   744  2169 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6410 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 16:35:17.085   744  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-10 16:35:17.085   744  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 16:35:17.085   744  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,08-10 16:35:17.085   744  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-10 16:35:17.085   744  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-10 16:35:17.085   744  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-10 16:35:17.085   744  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-10 16:35:17.085   744  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-10 16:35:17.085   744  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-10 16:35:17.085   744  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 16:35:17.085  1647  1663 D TP/MmsSmsProvider: query, match:12, calling pid = 6383, accessRestricted = false
08-10 16:35:17.095  1647  1663 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.090 ms
,08-10 16:35:17.095  6383  6383 D Mms:transaction: roaming -> false (slotId = 0)
08-10 16:35:17.095  6383  6383 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-10 16:35:17.095  6383  6383 D Mms:transaction: auto download without roaming -> true
08-10 16:35:17.095  6383  6383 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-10 16:35:17.095  6383  6383 D Mms:transaction: roaming -> false (slotId = 1)
08-10 16:35:17.095  6383  6383 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-10 16:35:17.095  6383  6383 D Mms:transaction: auto download without roaming -> true
08-10 16:35:17.095  6383  6383 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-10 16:35:17.095  6383  6383 D Mms:transaction: auto download during roaming secondary -> false
08-10 16:35:17.095  6383  6383 D Mms:transaction: mAutoDownload ------> true
,08-10 16:35:17.095  6410  6432 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-10 16:35:17.105  6383  6463 D Mms/DraftCache: [end]    rebuildCache consume time = 26.132709
,08-10 16:35:17.105  6410  6410 D SecWifiDisplayUtil: Metadata value : none
,08-10 16:35:17.115  6383  6383 D ComposerPerformance: 1470839717120 ms / [DONE] Composer constructor
,08-10 16:35:17.115   293   293 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,08-10 16:35:17.115  6383  6466 D Mms/Conversation: [start]    init() consume time = 11.032031
,08-10 16:35:17.115  6383  6383 D CII     : Log Level [5]
,08-10 16:35:17.115  6383  6383 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-10 16:35:17.115  1647  1877 D TP/MmsSmsProvider: delete, match:1, calling pid = 6383
08-10 16:35:17.115  1647  1877 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-10 16:35:17.115  1647  1877 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-10 16:35:17.115  6383  6383 I Mms/ReservationManager: ReservationManager()
,08-10 16:35:17.115  6383  6383 I Mms/ReservationManager: resetAfterConnected()
,08-10 16:35:17.125  1647  1877 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-10 16:35:17.125  1647  1877 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-10 16:35:17.125  1647  1877 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-10 16:35:17.125  1647  1877 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-10 16:35:17.135  1647  2606 D TP/MmsSmsProvider: query, match:7, calling pid = 6383, accessRestricted = false
,08-10 16:35:17.135   744  1218 D InputDispatcher: Focus entered window: 6410
,08-10 16:35:17.135  1647  2606 D TP/MmsSmsProvider: query, match 7:Elapsed time : 3.264 ms
,08-10 16:35:17.135   744   863 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:744 uid:1000
,08-10 16:35:17.135   744   863 D PointerIcon: setMouseCustomIcon IconType is same.101
08-10 16:35:17.135   744   863 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:744 uid:1000
08-10 16:35:17.135  6410  6459 D libEGL  : eglInitialize EGLDisplay = 0x9ca017c4
08-10 16:35:17.135  6410  6459 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 16:35:17.135   744   863 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-10 16:35:17.135  1647  1877 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
,08-10 16:35:17.135  1647  1877 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-10 16:35:17.135  1647  1877 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-10 16:35:17.135  1647  1877 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 6.499 ms
,08-10 16:35:17.135  1647  1877 D TP/MmsSmsProvider: need read changed broadcast:false
08-10 16:35:17.135  6383  6466 D Mms/Conversation: [end]    init consume time = 23.305572
,08-10 16:35:17.135  6383  6383 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-10 16:35:17.135  6383  6466 D Mms/MessagingNotification: [start]    init() consume time = 2.380365
,08-10 16:35:17.145  6383  6466 D Mms/MessagingNotification: [end]    init consume time = 1.911771
,08-10 16:35:17.145  6383  6383 D Mms/MmsApp: [end]    onCreate() consume time = 0.944063
08-10 16:35:17.145  6383  6383 D Mms/MmsApp: [end]    onCreate() consume time = 0.072344
,08-10 16:35:17.145  6383  6469 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.645833
,08-10 16:35:17.145  6383  6470 D Mms/Synchronizer: [start]    doSync consume time = 0.617812
,08-10 16:35:17.145  6383  6383 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-10 16:35:17.145  6383  6383 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-10 16:35:17.145  6383  6383 D Mms:transaction: roaming -> false (slotId = 0)
08-10 16:35:17.145  6383  6383 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-10 16:35:17.145  6383  6383 D Mms:transaction: auto download without roaming -> true
08-10 16:35:17.145  6383  6383 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-10 16:35:17.145  6383  6383 D Mms:transaction: mAutoDownload ------> true
,08-10 16:35:17.155  1647  1662 D TP/MmsSmsProvider: query, match:0, calling pid = 6383, accessRestricted = false
,08-10 16:35:17.155  1647  1662 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-10 16:35:17.155   744  2092 I ActivityManager: Start proc 6471:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
08-10 16:35:17.155  1647  1662 D TP/MmsSmsProvider: query, match 0:Elapsed time : 2.340 ms
,08-10 16:35:17.155   744  2092 I ActivityManager: Killing 5032:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-10 16:35:17.165  6471  6471 E Zygote  : v2
,08-10 16:35:17.165  6471  6471 I libpersona: KNOX_SDCARD checking this for 1000
08-10 16:35:17.165  6471  6471 I libpersona: KNOX_SDCARD not a persona
,08-10 16:35:17.165  6471  6471 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-10 16:35:17.165  6471  6471 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 16:35:17.165  6471  6471 E Zygote  : accessInfo : 0
,08-10 16:35:17.165  1647  1877 D TP/MmsSmsProvider: update, match:300, calling pid = 6383
08-10 16:35:17.165  1647  1877 V TP/MmsSmsProvider: syncDBData start
,08-10 16:35:17.165  1647  1877 V TP/MmsSmsProvider: syncDBData sms end
,08-10 16:35:17.165  1647  1877 V TP/MmsSmsProvider: syncDBData mms end
,08-10 16:35:17.165  1647  1877 V TP/MmsSmsProvider: syncDBData end
08-10 16:35:17.165  1647  1877 D TP/MmsSmsProvider: update, match 300:Elapsed time : 1.673 ms
,08-10 16:35:17.175  6066  6103 D BadgeProvider: query, [selection] : package=?
,08-10 16:35:17.175  1647  1663 D TP/MmsSmsProvider: query, match:400, calling pid = 6383, accessRestricted = false
,08-10 16:35:17.175  6383  6466 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-10 16:35:17.195  1647  2606 D TP/SmsProvider: query,matched:26, calling pid = 6383
,08-10 16:35:17.195  6383  6470 D Mms/Synchronizer: [end]    doSync consume time = 49.703542
,08-10 16:35:17.195  1647  2606 D TP/SmsProvider: query, match 26:Elapsed time : 1.514 ms
08-10 16:35:17.195  6410  6410 V ActivityThread: updateVisibility : ActivityRecord{4f03b47 token=android.os.BinderProxy@83d714f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-10 16:35:17.205  6410  6410 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-10 16:35:17.205   744  1414 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-10 16:35:17.225  6471  6471 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:17.225  6471  6471 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:17.225  1647  1877 D TP/MmsSmsProvider: query, match:6, calling pid = 6383, accessRestricted = false
,08-10 16:35:17.225  1647  1877 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.054 ms
,08-10 16:35:17.225   744  1493 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1943bea 6471:com.samsung.android.bbc.bbcagent/1000}
,08-10 16:35:17.235   744  2169 V WindowStateAnimator: Finishing drawing window Window{ba7503a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-10 16:35:17.235  6410  6410 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-10 16:35:17.235  6410  6410 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-10 16:35:17.235   744  1625 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-10 16:35:17.235  6383  6469 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 39.75651
,08-10 16:35:17.235   744   863 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-10 16:35:17.235   744   744 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-10 16:35:17.245   744   744 I KnoxTimeoutHandler: SD activityfalse
08-10 16:35:17.245   744   863 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +605ms (total +848ms)
,08-10 16:35:17.245   744   863 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{87e81ff u0 com.test.thalitest/.MainActivity t152} time:100042
08-10 16:35:17.245   744   863 D ActivityManager: mDVFSHelper.release()
,08-10 16:35:17.245   744   863 D ViewRootImpl: #3 mView = null
,08-10 16:35:17.245   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed76364
,08-10 16:35:17.245   293  1297 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
,08-10 16:35:17.255   293   417 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,08-10 16:35:17.265   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed763a4
,08-10 16:35:17.265  6471  6471 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-10 16:35:17.275  6410  6485 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 16:35:17.275  6410  6485 D libEGL  : eglInitialize EGLDisplay = 0x9b2103ec
,08-10 16:35:17.275   744  2139 V WindowStateAnimator: Finishing drawing window Window{ba7503a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-10 16:35:17.285   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed76364
,08-10 16:35:17.285  6410  6410 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-10 16:35:17.285   744  1694 I ActivityManager: Start proc 6489:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-10 16:35:17.285  6489  6489 E Zygote  : v2
08-10 16:35:17.285  6489  6489 I libpersona: KNOX_SDCARD checking this for 10024
08-10 16:35:17.285  6489  6489 I libpersona: KNOX_SDCARD not a persona
,08-10 16:35:17.285  6489  6489 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:17.285  6489  6489 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 16:35:17.285  6489  6489 E Zygote  : accessInfo : 0
,08-10 16:35:17.285  6489  6489 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-10 16:35:17.285  6410  6410 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@83d714f time:100089
,08-10 16:35:17.315  6489  6489 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 16:35:17.315  6489  6489 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:17.325   744  1218 I ActivityManager: Killing 5085:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-10 16:35:17.325  6410  6410 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6410
,08-10 16:35:17.335  6471  6471 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-10 16:35:17.335   744   757 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-10 16:35:17.345  6489  6489 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-10 16:35:17.365  6489  6489 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-10 16:35:17.385  6503  6503 E Zygote  : v2
08-10 16:35:17.385  6503  6503 I libpersona: KNOX_SDCARD checking this for 10097
08-10 16:35:17.385  6503  6503 I libpersona: KNOX_SDCARD not a persona
,08-10 16:35:17.385  6503  6503 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:17.385  6503  6503 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 16:35:17.385   744  1678 I ActivityManager: Start proc 6503:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-10 16:35:17.385  6503  6503 E Zygote  : accessInfo : 0
,08-10 16:35:17.385  6503  6503 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-10 16:35:17.385   744  1678 I ActivityManager: Killing 5404:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-10 16:35:17.415  6503  6503 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:17.415  6503  6503 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:17.425   744  1868 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-10 16:35:17.435   744  2169 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c76d78 6503:com.google.android.apps.docs/u0a97}
,08-10 16:35:17.435  6489  6489 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-10 16:35:17.435  6383  6466 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-10 16:35:17.445  6503  6503 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-10 16:35:17.465  6503  6503 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-10 16:35:17.465  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-10 16:35:17.475  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-10 16:35:17.475  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-10 16:35:17.475  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-10 16:35:17.475  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-10 16:35:17.475  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-10 16:35:17.475  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-10 16:35:17.475  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-10 16:35:17.485  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-10 16:35:17.485  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-10 16:35:17.485  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-10 16:35:17.485  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-10 16:35:17.485  6489  6489 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-10 16:35:17.485  6410  6410 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 16:35:17.585  6410  6516 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1708394192
,08-10 16:35:17.595  6410  6516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 16:35:17.595  6410  6516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 16:35:17.595  6410  6516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 16:35:17.595  6410  6516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 16:35:17.595  6410  6516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-10 16:35:17.595  6410  6516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff24255 added. We now have 1 listener(s)
,08-10 16:35:17.595  6410  6516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-10 16:35:17.595  6410  6516 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-10 16:35:17.595  6410  6516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 16:35:17.605  6410  6516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 16:35:17.605  6410  6516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98479f8 added. We now have 1 listener(s)
08-10 16:35:17.605  6410  6516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 16:35:17.605  6410  6516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 16:35:17.605  6410  6516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-10 16:35:17.605  6410  6516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 16:35:17.605  6410  6516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 16:35:17.605  6410  6516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-10 16:35:17.615  6410  6516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 16:35:17.615  6410  6516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-10 16:35:17.615  6410  6516 D BluetoothAdapter: STATE_ON
,08-10 16:35:17.625  6410  6516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-10 16:35:17.625  6410  6516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 16:35:17.625  6410  6516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 16:35:17.625  6410  6516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 16:35:17.625  6410  6516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 16:35:17.625  6410  6516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 16:35:17.625  6410  6516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 16:35:17.625  6410  6516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 16:35:17.625  6410  6516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 16:35:17.625  6410  6516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 16:35:17.625  6410  6516 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 16:35:17.625  6410  6516 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 16:35:17.635  6410  6410 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 16:35:17.635  6410  6410 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 16:35:17.655  6410  6410 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 16:35:17.655   744  3408 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-10 16:35:17.725  4144  4916 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-10 16:35:17.765  4144  4916 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-10 16:35:17.785  6503  6520 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-10 16:35:17.785  6503  6520 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 16:35:17.785  6503  6520 I GAv4    :   adb logcat -s GAv4
,08-10 16:35:17.805  6503  6520 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-10 16:35:17.805   744  2093 V AlarmManager:  remove PendingIntent] PendingIntent{1e61c8e: PendingIntentRecord{f819caf com.google.android.apps.docs broadcastIntent}}
,08-10 16:35:17.815  6503  6520 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 16:35:17.815  6503  6520 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 16:35:17.825  6503  6525 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 16:35:17.865  4144  4916 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-10 16:35:17.945  6503  6503 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-10 16:35:17.945  6503  6503 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-10 16:35:17.965  6503  6520 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-10 16:35:17.965  6503  6520 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-10 16:35:17.965  6503  6520 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,08-10 16:35:17.965  6503  6520 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-10 16:35:18.015  6532  6532 E Zygote  : v2
08-10 16:35:18.015  6532  6532 I libpersona: KNOX_SDCARD checking this for 10098
08-10 16:35:18.015  6532  6532 I libpersona: KNOX_SDCARD not a persona
,08-10 16:35:18.015  6532  6532 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:18.015  6532  6532 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 16:35:18.015  6532  6532 E Zygote  : accessInfo : 0
,08-10 16:35:18.025  6532  6532 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-10 16:35:18.025   744  2139 I ActivityManager: Start proc 6532:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-10 16:35:18.025   744  2139 I ActivityManager: Killing 4985:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-10 16:35:18.045  6532  6532 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 16:35:18.045  6532  6532 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:18.075   744   759 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d554cb 6532:com.sec.android.automotive.drivelink/u0a98}
,08-10 16:35:18.075   744  1218 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-10 16:35:18.085  1449  1449 D Recents : onTaskStackChanged
,08-10 16:35:18.085  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-10 16:35:18.095  6532  6532 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-10 16:35:18.105  6532  6532 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-10 16:35:18.135  6532  6532 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-10 16:35:18.145   744  1414 V AlarmManager:  remove PendingIntent] PendingIntent{2ad24a8: PendingIntentRecord{6d3fbc1 com.sec.android.automotive.drivelink broadcastIntent}}
,08-10 16:35:18.155  6532  6532 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-10 16:35:18.155  6532  6548 I GMPM    : App measurement is starting up
,08-10 16:35:18.165  6532  6548 E GMPM    : getGoogleAppId failed with status: 10
,08-10 16:35:18.165  6532  6548 E GMPM    : Uploading is not possible. App measurement disabled
,08-10 16:35:18.165   744  1678 V AlarmManager:  remove PendingIntent] PendingIntent{73d2f66: PendingIntentRecord{6d3fbc1 com.sec.android.automotive.drivelink broadcastIntent}}
,08-10 16:35:18.185   744  6192 I HarmonyEASService: Updating for all 1
,08-10 16:35:18.185  6532  6532 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-10 16:35:18.185  2040  2040 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-10 16:35:18.185  2040  2040 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-10 16:35:18.195  6532  6532 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-10 16:35:18.225  2040  2040 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-10 16:35:18.245   744  2093 I ActivityManager: Start proc 6554:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-10 16:35:18.245  6554  6554 E Zygote  : v2
08-10 16:35:18.245  6554  6554 I libpersona: KNOX_SDCARD checking this for 10032
08-10 16:35:18.245  6554  6554 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:18.245   744  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-10 16:35:18.245  6554  6554 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:18.245  6554  6554 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 16:35:18.255  6554  6554 E Zygote  : accessInfo : 0
,08-10 16:35:18.255  6554  6554 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-10 16:35:18.275  6554  6554 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 16:35:18.275  6554  6554 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:18.285   744  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-10 16:35:18.295  6554  6554 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-10 16:35:18.305  6503  6521 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-10 16:35:18.305  6554  6554 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-10 16:35:18.325  6410  6517 W jxcore-log: Initializing JXcore engine
08-10 16:35:18.325  6410  6517 W jxcore-log: JXcore engine is ready
,08-10 16:35:18.375  2045  2045 E audit   : type=1400 msg=audit(1470839718.375:287): avc:  denied  { ioctl } for  pid=6517 comm="Thread-916" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-10 16:35:18.375  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:18.375  2045  2045 E audit   : type=1300 msg=audit(1470839718.375:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a18d3c8 items=0 ppid=349 ppcomm=main pid=6517 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-916" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-10 16:35:18.375  2045  2045 E audit   : type=1327 msg=audit(1470839718.375:287): proctitle="com.test.thalitest"
08-10 16:35:18.375  2045  2045 E audit   : type=1320 msg=audit(1470839718.375:287): 
08-10 16:35:18.375  2045  2045 E audit   : type=1400 msg=audit(1470839718.375:288): avc:  denied  { ioctl } for  pid=6517 comm="Thread-916" path="socket:[38887]" dev="sockfs" ino=38887 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-10 16:35:18.375  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:18.375  2045  2045 E audit   : type=1300 msg=audit(1470839718.375:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9a18d3c8 items=0 ppid=349 ppcomm=main pid=6517 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-916" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-10 16:35:18.375  2045  2045 E audit   : type=1327 msg=audit(1470839718.375:288): proctitle="com.test.thalitest"
08-10 16:35:18.375  2045  2045 E audit   : type=1320 msg=audit(1470839718.375:288): 
,08-10 16:35:18.385  6410  6517 W jxcore-log: Starting JXcore engine
,08-10 16:35:18.395  6503  6521 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-10 16:35:18.415  6503  6521 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-10 16:35:18.415  6503  6521 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-10 16:35:18.415  6503  6521 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-10 16:35:18.435  6532  6532 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-10 16:35:18.445  6554  6554 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-10 16:35:18.455  6532  6532 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-10 16:35:18.455  6532  6532 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-10 16:35:18.465  6554  6554 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-10 16:35:18.465  6532  6532 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDWed Aug 10 16:35:18 GMT+02:00 2016
,08-10 16:35:18.475  6532  6532 D DialogFlow: initQueue()
,08-10 16:35:18.475  6503  6521 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-10 16:35:18.475  6569  6569 E Zygote  : v2
08-10 16:35:18.475  6569  6569 I libpersona: KNOX_SDCARD checking this for 1000
08-10 16:35:18.475  6569  6569 I libpersona: KNOX_SDCARD not a persona
,08-10 16:35:18.475  6569  6569 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:18.475  6569  6569 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:18.475   744  1988 I ActivityManager: Start proc 6569:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-10 16:35:18.485  6569  6569 E Zygote  : accessInfo : 0
,08-10 16:35:18.485   744  1988 I ActivityManager: Killing 5711:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
08-10 16:35:18.485   744  1988 I ActivityManager: Killing 5617:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-10 16:35:18.505   744  2169 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-10 16:35:18.505  6410  6517 W jxcore-log: Platform android
08-10 16:35:18.505  6410  6517 W jxcore-log: 
08-10 16:35:18.505  6410  6517 W jxcore-log: Process ARCH arm
08-10 16:35:18.505  6410  6517 W jxcore-log: 
,08-10 16:35:18.505  6569  6569 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:18.505  6569  6569 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:18.505   744  1694 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-10 16:35:18.515   744  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c707d8 6569:com.samsung.android.app.filterinstaller/1000}
,08-10 16:35:18.525  6569  6569 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-10 16:35:18.545  6569  6569 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-10 16:35:18.545   744  1868 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-10 16:35:18.555  6569  6569 E FilterPackageIntentReceiver: This package is not a effect filter
,08-10 16:35:18.565   744  1694 I ActivityManager: Start proc 6585:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-10 16:35:18.565  6585  6585 E Zygote  : v2
08-10 16:35:18.565  6585  6585 I libpersona: KNOX_SDCARD checking this for 1000
08-10 16:35:18.565  6585  6585 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:18.565  6585  6585 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:18.565  6585  6585 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 16:35:18.565  6585  6585 E Zygote  : accessInfo : 0
,08-10 16:35:18.565   744  1694 I ActivityManager: Killing 5462:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-10 16:35:18.595  6585  6585 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:18.595  6585  6585 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:18.595  6554  6554 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-10 16:35:18.595  6554  6554 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-10 16:35:18.605   744  2093 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-10 16:35:18.605  6554  6554 D DialogFlow: initQueue()
,08-10 16:35:18.615   744  2155 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d39233 6585:com.samsung.helphub/1000}
,08-10 16:35:18.615  6585  6585 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-10 16:35:18.635  6585  6585 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-10 16:35:18.685  6597  6597 E Zygote  : v2
08-10 16:35:18.685  6597  6597 I libpersona: KNOX_SDCARD checking this for 1000
08-10 16:35:18.685  6597  6597 I libpersona: KNOX_SDCARD not a persona
,08-10 16:35:18.685  6597  6597 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:18.685  6597  6597 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:18.685   744  1677 I ActivityManager: Start proc 6597:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-10 16:35:18.685   744  1677 I ActivityManager: Killing 5765:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-10 16:35:18.685  6410  6517 I jxcore-log: JXcore Cordova bridge is ready!
08-10 16:35:18.685  6410  6517 I jxcore-log: 
,08-10 16:35:18.685  6410  6517 W jxcore-log: JXcore engine is started
,08-10 16:35:18.685  6597  6597 E Zygote  : accessInfo : 0
,08-10 16:35:18.695  6410  6516 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 16:35:18.695  6410  6410 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 16:35:18.695   744  1493 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-10 16:35:18.725  6597  6597 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:18.725  6597  6597 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:18.725   744  2155 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{712f9f0 6597:com.samsung.android.app.mirrorlink/1000}
,08-10 16:35:18.735  6597  6597 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-10 16:35:18.745  6597  6597 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-10 16:35:18.775  6597  6597 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-10 16:35:18.775  6597  6597 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-10 16:35:18.785   744   757 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{26c1b07 5630:com.google.android.apps.plus/u0a134}
,08-10 16:35:18.795   744  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{26c1b07 5630:com.google.android.apps.plus/u0a134}
,08-10 16:35:18.805   744   759 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{26c1b07 5630:com.google.android.apps.plus/u0a134}
,08-10 16:35:18.845   744  2092 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-10 16:35:18.845   744  1625 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-10 16:35:18.845   744   757 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-10 16:35:18.845   744   759 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-10 16:35:18.855   744  2169 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-10 16:35:18.855   744  1677 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-10 16:35:18.855   744  1493 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-10 16:35:18.865   744  1868 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-10 16:35:18.885  6611  6611 E Zygote  : v2
08-10 16:35:18.885   744  1625 I ActivityManager: Start proc 6611:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-10 16:35:18.885  6611  6611 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:18.885  6611  6611 I libpersona: KNOX_SDCARD checking this for 10165
08-10 16:35:18.885  6611  6611 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:18.885  6611  6611 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:18.885  6611  6611 E Zygote  : accessInfo : 0
08-10 16:35:18.885  6611  6611 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-10 16:35:18.885   744  1625 I ActivityManager: Killing 5605:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-10 16:35:18.905  6611  6611 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:18.905   744   759 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
08-10 16:35:18.905  6611  6611 D ActivityThread: Added TimaKeyStore provider
08-10 16:35:18.915   744  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12b1e8f 6611:com.sec.kidsplat.installer/u0a165}
,08-10 16:35:18.925  6611  6611 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-10 16:35:18.935  6611  6611 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-10 16:35:18.945   744  2093 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12b1e8f 6611:com.sec.kidsplat.installer/u0a165}
,08-10 16:35:18.945  6611  6611 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-10 16:35:18.965  6623  6623 E Zygote  : v2
08-10 16:35:18.965   744  1677 I ActivityManager: Start proc 6623:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
08-10 16:35:18.965  6623  6623 E Zygote  : isSdpEnabledProcess - SDP enabled
08-10 16:35:18.965  6623  6623 I libpersona: KNOX_SDCARD checking this for 10142
08-10 16:35:18.965  6623  6623 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:18.965  6623  6623 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:18.965  6623  6623 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:18.965   744  1677 I ActivityManager: Killing 5216:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
08-10 16:35:18.965  6623  6623 E Zygote  : accessInfo : 64
08-10 16:35:18.965  6623  6623 E Zygote  : isSdpEnabledProcess - SDP enabled
08-10 16:35:18.965  6623  6623 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-10 16:35:18.965  6623  6623 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-10 16:35:18.985  6623  6623 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:18.985  6623  6623 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:18.995   744  1694 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{445c51c 6623:com.sec.android.app.sbrowser/u0a142}
,08-10 16:35:18.995   744  1218 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-10 16:35:19.005  6623  6623 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-10 16:35:19.015  6623  6623 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-10 16:35:19.035  6623  6623 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-10 16:35:19.035  6623  6623 D ManifestProvider: onCreate()
,08-10 16:35:19.045   744  1235 V AlarmManager: Expired Alarm result :4
,08-10 16:35:19.055  6623  6623 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-10 16:35:19.055  6623  6623 I SBrowserUtils: getSystemProperty of country_code : Poland
08-10 16:35:19.055  6623  6623 I SBrowserUtils: getSystemProperty of country_code : Poland
08-10 16:35:19.055  6623  6623 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-10 16:35:19.055  5656  5703 I Finsky  : [813] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-10 16:35:19.065  6623  6623 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-10 16:35:19.075  6623  6623 D [MM]MHDataBaseProvider: onCreate()
,08-10 16:35:19.095  6623  6623 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@b83b38b)
,08-10 16:35:19.105   744  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-10 16:35:19.105   744  2093 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4251, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-10 16:35:19.105   744  2093 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-10 16:35:19.105   744  2093 D BatteryService: stay LED for charging
08-10 16:35:19.105   744   744 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-10 16:35:19.105   744   744 I MotionRecognitionService: Plugged
08-10 16:35:19.105   744   744 D MotionRecognitionService:   cableConnection= 1
08-10 16:35:19.105   744   744 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-10 16:35:19.105   744   744 D MotionRecognitionService: skip setTransmitPower. 
,08-10 16:35:19.115  1375  1375 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-10 16:35:19.115  1375  1375 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-10 16:35:19.115  1375  1375 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-10 16:35:19.115  2025  2025 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-10 16:35:19.115  2025  2626 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-10 16:35:19.135  1375  1375 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-10 16:35:19.135  1375  1375 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-10 16:35:19.135  1375  1375 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-10 16:35:19.175   744   757 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b1f0fe 2040:com.google.android.gms.persistent/u0a11}
,08-10 16:35:19.185  6383  6383 I Mms/MmsApp:  start initViewCache mms
,08-10 16:35:19.195   744  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{342e3e 4144:com.google.android.gms/u0a11}
,08-10 16:35:19.205  4144  6641 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-10 16:35:19.215  4144  6640 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-10 16:35:19.225  4144  4144 D AsyncTaskServiceImpl: Submit a task: nzm
,08-10 16:35:19.235  4144  6641 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-10 16:35:19.255  4144  4916 D nzm     : Processing package: com.test.thalitest
,08-10 16:35:19.265   744  1694 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b1f0fe 2040:com.google.android.gms.persistent/u0a11}
,08-10 16:35:19.275  4144  6641 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-10 16:35:19.275  4144  6641 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-10 16:35:19.285   744   759 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{342e3e 4144:com.google.android.gms/u0a11}
,08-10 16:35:19.305  4144  4144 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-10 16:35:19.325  4144  4916 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-10 16:35:19.325  4144  4916 D nzm     : Found info for package com.test.thalitest in db.
,08-10 16:35:19.405   744  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{326165c 5656:com.android.vending/u0a29}
,08-10 16:35:19.445   744  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/152_task.xml.bak
,08-10 16:35:19.505   744  2092 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cce51a8 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6a98763 6165:com.sec.android.app.samsungapps/u0a39}
,08-10 16:35:19.505  5656  5656 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-10 16:35:19.515  5656  5656 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-10 16:35:19.515  6648  6648 E Zygote  : v2
08-10 16:35:19.515  6648  6648 I libpersona: KNOX_SDCARD checking this for 10034
08-10 16:35:19.515  6648  6648 I libpersona: KNOX_SDCARD not a persona
,08-10 16:35:19.515  6648  6648 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:19.515  6648  6648 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:19.515   744   757 I ActivityManager: Start proc 6648:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
,08-10 16:35:19.515  6648  6648 E Zygote  : accessInfo : 0
,08-10 16:35:19.515  6648  6648 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-10 16:35:19.545  2040  2040 D WearableService: callingUid 10011, callindPid: 2040
,08-10 16:35:19.545  6648  6648 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 16:35:19.545  6648  6648 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:19.565  5656  5656 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-10 16:35:19.565  5656  5656 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-10 16:35:19.565   744  1868 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c5e2613 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9623050 6648:com.sec.android.app.shealth/u0a34}
,08-10 16:35:19.595  6648  6648 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-10 16:35:19.605  6554  6583 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-10 16:35:19.605  6554  6583 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-10 16:35:19.615  6648  6648 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-10 16:35:19.635  6648  6648 I MultiDex: VM with version 2.1.0 has multidex support
08-10 16:35:19.635  6648  6648 I MultiDex: install
08-10 16:35:19.635  6648  6648 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-10 16:35:19.635  6648  6648 I MultiDex: install
08-10 16:35:19.635  6648  6648 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-10 16:35:19.645  6554  6583 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-10 16:35:19.645  6554  6583 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-10 16:35:19.645  6554  6583 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-10 16:35:19.655  6554  6583 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-10 16:35:19.655  6554  6583 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-10 16:35:19.685  6383  6383 D Mms/BubbleViewCache: fillCache bubble = 4
,08-10 16:35:19.745  6648  6648 D HealthDataStore: Service for HealthDataStore is connected
,08-10 16:35:19.745  6648  6648 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-10 16:35:19.745   744  1218 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c5e2613 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd29749 1937:com.sec.android.app.shealth:remote/u0a34}
,08-10 16:35:19.755   744  2092 I ActivityManager: Killing 5244:com.policydm/1000 (adj 15): DHA:empty #37
,08-10 16:35:19.765  6648  6648 D HealthConsole: Service for HealthDataConsole is connected
,08-10 16:35:19.785  6648  6648 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-10 16:35:19.785   744  1988 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-10 16:35:19.785  6393  6393 D AASAservice: onDestroy()
,08-10 16:35:19.785  6393  6393 I art     : System.exit called, status: 80
08-10 16:35:19.785  6648  6648 E HealthDataStore: disconnectService: Context instance is invalid
08-10 16:35:19.785  6393  6393 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-10 16:35:19.805   744  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c5e2613 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd29749 1937:com.sec.android.app.shealth:remote/u0a34}
,08-10 16:35:19.805   744  2092 I ActivityManager: Process com.samsung.aasaservice (pid 6393)(adj 0) has died(45,778)
,08-10 16:35:19.805   744  2092 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-10 16:35:19.855   349   349 I Zygote  : Process 6393 exited cleanly (80)
,08-10 16:35:19.855   744   744 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9e9e67 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b1f0fe 2040:com.google.android.gms.persistent/u0a11}
,08-10 16:35:19.875   744   744 I BackgroundCompactionService: onStart. jobID=801
,08-10 16:35:19.875   744   744 I BackgroundCompactionService: onStart done. jobID=801
,08-10 16:35:19.875   744  6666 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-10 16:35:19.885   744  6666 I BackgroundCompactionService: compact_memory command done
,08-10 16:35:20.045  6165  6165 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,08-10 16:35:20.045  6165  6165 D PreloadUpdateManagerStateMachine: exit::IDLE
08-10 16:35:20.045  6165  6165 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,08-10 16:35:20.045  6165  6165 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,08-10 16:35:20.045  6165  6165 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-10 16:35:20.045  6165  6165 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,08-10 16:35:20.045  6165  6165 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
08-10 16:35:20.045  6165  6165 D PreloadUpdateManagerStateMachine: entry::IDLE
,08-10 16:35:20.085  4144  6646 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-10 16:35:20.145  5656  5703 I Finsky  : [813] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-10 16:35:20.145  5656  5656 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-10 16:35:20.475  4144  4919 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-10 16:35:20.575  4144  4919 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-10 16:35:20.575  4144  4919 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-10 16:35:20.605  4144  4919 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-10 16:35:22.045   744  3441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-10 16:35:22.685   744  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-10 16:35:23.555  3636  3636 D FactoryTest: User mode
,08-10 16:35:23.555  3636  3636 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-10 16:35:23.555  3636  3636 D MTPRx   : still no open session command from host, so toast
,08-10 16:35:23.565   744  1414 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-10 16:35:23.565   744  1414 D ActivityManager: mDVFSHelper.acquire()
,08-10 16:35:23.575   744  1414 V WindowManager: addAppToken: AppWindowToken{c2b0e75 token=Token{846c1ac ActivityRecord{176f35f u0 com.samsung.android.MtpApplication/.USBConnection t153}}} to stack=1 task=153 at 0
,08-10 16:35:23.575   744  1414 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-10 16:35:23.585   744   806 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-10 16:35:23.595   744  1414 D InputDispatcher: Focused application set to: xxxx
,08-10 16:35:23.605   744  1414 D InputDispatcher: Focus left window: 6410
,08-10 16:35:23.605   744   863 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:744 uid:1000
,08-10 16:35:23.605   744   863 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-10 16:35:23.605   744   863 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:744 uid:1000
08-10 16:35:23.605   744   863 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-10 16:35:23.615   744  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-10 16:35:23.615  3636  3636 E MTPRx   : started activity for popup
,08-10 16:35:23.615  3636  3636 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-10 16:35:23.625  3636  3636 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-10 16:35:23.645  3636  3636 D MTPUSBConnection: onCreate in USBConnection
,08-10 16:35:23.645  3636  3636 V MTPUSBConnection: Registering broadcast receiver.
,08-10 16:35:23.645  3636  3636 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-10 16:35:23.645   744  1678 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-10 16:35:23.695  3636  3636 D TAG     : dev.kiessupport is : TRUE
,08-10 16:35:23.725  3636  3636 D SecWifiDisplayUtil: Metadata value : none
,08-10 16:35:23.725  3636  3636 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{67ecfff V.E...... R.....I. 0,0-0,0}
,08-10 16:35:23.735  3636  6686 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 16:35:23.735   744  1694 D ISSUE_DEBUG: InputChannelName : 643972d com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-10 16:35:23.735   744  1694 D InputDispatcher: Focus entered window: 3636
,08-10 16:35:23.735   744   809 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{643972d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-10 16:35:23.735  1375  1375 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-10 16:35:23.735   744   863 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:744 uid:1000
08-10 16:35:23.735   744   863 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-10 16:35:23.735   744   863 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:744 uid:1000
08-10 16:35:23.735   744   863 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-10 16:35:23.745  3636  3636 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ac8bff7 I.E...... R.....I. 0,0-0,0}
,08-10 16:35:23.745   744  1625 D ISSUE_DEBUG: InputChannelName : 30029f3 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-10 16:35:23.745   744  1694 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-10 16:35:23.745   744  1694 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-10 16:35:23.745   744   744 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-10 16:35:23.745   744   744 I KnoxTimeoutHandler: Shared devices show user statefalse
08-10 16:35:23.745   744   744 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-10 16:35:23.785   293   293 I SurfaceFlinger: id=16 createSurf (145x145),1 flag=4, VSBConnecti
,08-10 16:35:23.805  3636  6686 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-10 16:35:23.805  3636  6686 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-10 16:35:23.805  3636  6686 I Adreno-EGL: Build Date: 01/28/16 Thu
08-10 16:35:23.805  3636  6686 I Adreno-EGL: Local Branch: ss
08-10 16:35:23.805  3636  6686 I Adreno-EGL: Remote Branch: 
08-10 16:35:23.805  3636  6686 I Adreno-EGL: Local Patches: 
08-10 16:35:23.805  3636  6686 I Adreno-EGL: Reconstruct Branch: 
,08-10 16:35:23.815  3636  6686 D libEGL  : eglInitialize EGLDisplay = 0x9f0bf7c4
,08-10 16:35:23.815  3636  6686 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 16:35:23.845   293   293 I SurfaceFlinger: id=17 createSurf (193x193),1 flag=4, VSBConnecti
,08-10 16:35:23.865  3636  3636 V ActivityThread: updateVisibility : ActivityRecord{bfb68cd token=android.os.BinderProxy@59871cc {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-10 16:35:23.865  3636  3636 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-10 16:35:23.965   744  2139 V WindowStateAnimator: Finishing drawing window Window{643972d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-10 16:35:23.965  3636  3636 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-10 16:35:23.975   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed76364
,08-10 16:35:23.975   744  1414 V WindowStateAnimator: Finishing drawing window Window{30029f3 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-10 16:35:23.975  3636  3636 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-10 16:35:23.975  3636  3636 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-10 16:35:23.985   744   863 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-10 16:35:23.985   744   744 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-10 16:35:23.985   744   863 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +389ms (total +414ms)
,08-10 16:35:23.985   744   744 I KnoxTimeoutHandler: SD activityfalse
,08-10 16:35:23.985   744   863 D ActivityManager: mDVFSHelper.release()
08-10 16:35:23.985   744   757 V WindowStateAnimator: Finishing drawing window Window{643972d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-10 16:35:23.985   744  1988 V WindowStateAnimator: Finishing drawing window Window{30029f3 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-10 16:35:23.985   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed76364
08-10 16:35:23.985  3636  3636 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@59871cc time:106788
,08-10 16:35:23.985   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed76364
,08-10 16:35:23.985   744   863 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{176f35f u0 com.samsung.android.MtpApplication/.USBConnection t153} time:106789
,08-10 16:35:24.615   744  3408 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-10 16:35:24.755  1449  1449 D Recents : onTaskStackChanged
,08-10 16:35:24.765  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-10 16:35:26.065   744   901 D PackageManager: [MSG] MCS_UNBIND
,08-10 16:35:26.085   744  2155 I ActivityManager: Killing 5783:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-10 16:35:26.115   744  1218 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-10 16:35:26.365   744  1414 I ActivityManager: Killing 5900:com.google.android.gms:car/u0a11 (adj 15): DHA:empty #37
,08-10 16:35:26.395   744   757 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
,08-10 16:35:26.435   744   901 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-10 16:35:26.455   744   901 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-10 16:35:26.475   744  3404 D SSRM:n  : SIOP:: AP = 470, PST = 452, CUR = 450, LCD = 0
,08-10 16:35:27.045   744  3441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-10 16:35:29.145  6410  6517 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 16:35:29.145  6410  6517 I jxcore-log: 
,08-10 16:35:29.145  6410  6517 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 16:35:29.145  6410  6517 I jxcore-log: 
,08-10 16:35:29.155  6410  6517 D BluetoothAdapter: STATE_ON
,08-10 16:35:29.155  6410  6517 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 16:35:29.155  6410  6517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 16:35:29.155  6410  6517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 16:35:29.155  6410  6517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 16:35:29.155  6410  6517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 16:35:29.155  6410  6517 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 16:35:29.155  6410  6517 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 16:35:29.155  6410  6517 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 16:35:29.155  6410  6517 D BluetoothAdapter: STATE_ON
,08-10 16:35:29.155  6410  6517 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 16:35:29.155  6410  6517 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 16:35:29.155  6410  6517 I jxcore-log: 
,08-10 16:35:29.155  6410  6517 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 16:35:29.155  6410  6517 I jxcore-log: 
,08-10 16:35:29.505  6410  6517 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-10 16:35:29.505  6410  6517 I jxcore-log: Failed to execute UT.
08-10 16:35:29.505  6410  6517 I jxcore-log: 
08-10 16:35:29.505  6410  6517 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-10 16:35:29.505  6410  6517 I jxcore-log: 
,08-10 16:35:29.505  6410  6517 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 16:35:29.505  6410  6517 I jxcore-log: 
08-10 16:35:29.515  6410  6410 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-10 16:35:29.645   744  3404 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-10 16:35:30.465  2045  2045 E audit   : type=1400 msg=audit(1470839730.465:289): avc:  denied  { execmod } for  pid=6699 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 16:35:30.465  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:30.465  2045  2045 E audit   : type=1300 msg=audit(1470839730.465:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b402b000 a1=51000 a2=5 a3=4 items=0 ppid=3546 ppcomm=adbd pid=6699 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 16:35:30.465  2045  2045 E audit   : type=1327 msg=audit(1470839730.465:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-10 16:35:30.465  2045  2045 E audit   : type=1320 msg=audit(1470839730.465:289): 
,08-10 16:35:30.525  2045  2045 E audit   : type=1400 msg=audit(1470839730.525:290): avc:  denied  { execmod } for  pid=6699 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 16:35:30.525  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:30.525  2045  2045 E audit   : type=1300 msg=audit(1470839730.525:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3feb000 a1=51000 a2=5 a3=4 items=0 ppid=3546 ppcomm=adbd pid=6699 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 16:35:30.525  2045  2045 E audit   : type=1327 msg=audit(1470839730.525:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-10 16:35:30.525  2045  2045 E audit   : type=1320 msg=audit(1470839730.525:290): 
,08-10 16:35:30.575  2045  2045 E audit   : type=1400 msg=audit(1470839730.575:291): avc:  denied  { execmod } for  pid=6699 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 16:35:30.575  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:30.575  2045  2045 E audit   : type=1300 msg=audit(1470839730.575:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3feb000 a1=51000 a2=5 a3=4 items=0 ppid=3546 ppcomm=adbd pid=6699 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 16:35:30.575  2045  2045 E audit   : type=1327 msg=audit(1470839730.575:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-10 16:35:30.575  2045  2045 E audit   : type=1320 msg=audit(1470839730.575:291): 
08-10 16:35:30.575  6699  6699 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-10 16:35:30.585  6699  6699 D AndroidRuntime: CheckJNI is OFF
,08-10 16:35:30.585  6699  6699 D AndroidRuntime: readGMSProperty: start
,08-10 16:35:30.585  6699  6699 D AndroidRuntime: readGMSProperty: already setted!!,
,08-10 16:35:30.585  6699  6699 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-10 16:35:30.585  6699  6699 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,08-10 16:35:30.585  6699  6699 D AndroidRuntime: readGMSProperty: end
,08-10 16:35:30.585  6699  6699 D AndroidRuntime: addProductProperty: start
,08-10 16:35:30.595  6699  6699 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art,
08-10 16:35:30.595  6699  6699 W art     : af18e000-b20b4000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
,08-10 16:35:30.595  6699  6699 W art     : b20b4000-b4323000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
,08-10 16:35:30.595  6699  6699 W art     : b4323000-b4324000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-10 16:35:30.595  6699  6699 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so,
08-10 16:35:30.595  6699  6699 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
,08-10 16:35:30.595  6699  6699 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
,08-10 16:35:30.595  6699  6699 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
,08-10 16:35:30.595  6699  6699 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc],
08-10 16:35:30.595  6699  6699 W art     : b4890000-b48b9000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-10 16:35:30.595  6699  6699 W art     : b48b9000-b48bc000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so,
08-10 16:35:30.595  6699  6699 W art     : b48bc000-b48bd000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
,08-10 16:35:30.595  6699  6699 W art     : b48bd000-b48be000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so,
,08-10 16:35:30.595  6699  6699 W art     : b48be000-b48bf000 r--p 00000000 00:00 0 
,08-10 16:35:30.595  6699  6699 W art     : b48bf000-b48df000 r--s 00000000 00:0b 8210       /dev/__properties__,
08-10 16:35:30.595  6699  6699 W art     : b48df000-b52f0000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-10 16:35:30.595  6699  6699 W art     : b52f0000-b52f1000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b52f1000-b533a000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-10 16:35:30.595  6699  6699 W art     : b533a000-b533b000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
,08-10 16:35:30.595  6699  6699 W art     : b533b000-b5343000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5343000-b5344000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.595  6699  6699 W art     : b5344000-b5379000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-10 16:35:30.595  6699  6699 W art     : b5379000-b537a000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b537a000-b537b000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
,08-10 16:35:30.595  6699  6699 W art     : b537b000-b537c000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-10 16:35:30.595  6699  6699 W art     : b537c000-b53d4000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-10 16:35:30.595  6699  6699 W art     : b53d4000-b53d5000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b53d5000-b53d6000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-10 16:35:30.595  6699  6699 W art     : b53d6000-b53d7000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-10 16:35:30.595  6699  6699 W art     : b53d8000-b53de000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so,
08-10 16:35:30.595  6699  6699 W art     : b53de000-b53df000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 16:35:30.595  6699  6699 W art     : b53df000-b53e0000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 16:35:30.595  6699  6699 W art     : b53e0000-b53e2000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b53e3000-b53ed000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 16:35:30.595  6699  6699 W art     : b53ed000-b53f0000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-10 16:35:30.595  6699  6699 W art     : b53f0000-b53f1000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 16:35:30.595  6699  6699 W art     : b53f2000-b5409000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 16:35:30.595  6699  6699 W art     : b5409000-b540a000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b540a000-b540b000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 16:35:30.595  6699  6699 W art     : b540b000-b540c000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 16:35:30.595  6699  6699 W art     : b540d000-b5417000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
,08-10 16:35:30.595  6699  6699 W art     : b5417000-b5418000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-10 16:35:30.595  6699  6699 W art     : b5418000-b5419000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-10 16:35:30.595  6699  6699 W art     : b5419000-b541d000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 16:35:30.595  6699  6699 W art     : b541d000-b541e000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 16:35:30.595  6699  6699 W art     : b541e000-b541f000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-10 16:35:30.595  6699  6699 W art     : b541f000-b5435000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-10 16:35:30.595  6699  6699 W art     : b5435000-b5436000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-10 16:35:30.595  6699  6699 W art     : b5436000-b5437000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-10 16:35:30.595  6699  6699 W art     : b5437000-b5444000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-10 16:35:30.595  6699  6699 W art     : b5444000-b5445000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-10 16:35:30.595  6699  6699 W art     : b5445000-b5446000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so,
08-10 16:35:30.595  6699  6699 W art     : b5446000-b54a6000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-10 16:35:30.595  6699  6699 W art     : b54a6000-b54a9000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
,08-10 16:35:30.595  6699  6699 W art     : b54a9000-b54ad000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b54ad000-b550e000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-10 16:35:30.595  6699  6699 W art     : b550e000-b550f000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-10 16:35:30.595  6699  6699 W art     : b550f000-b555e000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-10 16:35:30.595  6699  6699 W art     : b555e000-b5560000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
,08-10 16:35:30.595  6699  6699 W art     : b5560000-b5561000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-10 16:35:30.595  6699  6699 W art     : b5561000-b5562000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5562000-b5569000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-10 16:35:30.595  6699  6699 W art     : b5569000-b556a000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-10 16:35:30.595  6699  6699 W art     : b556a000-b556b000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so,
08-10 16:35:30.595  6699  6699 W art     : b556c000-b556f000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-10 16:35:30.595  6699  6699 W art     : b556f000-b5570000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-10 16:35:30.595  6699  6699 W art     : b5570000-b5571000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-10 16:35:30.595  6699  6699 W art     : b5572000-b5576000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
,08-10 16:35:30.595  6699  6699 W art     : b5576000-b5577000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5577000-b5578000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-10 16:35:30.595  6699  6699 W art     : b5578000-b5579000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-10 16:35:30.595  6699  6699 W art     : b557a000-b5597000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
,08-10 16:35:30.595  6699  6699 W art     : b5597000-b5598000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 16:35:30.595  6699  6699 W art     : b5598000-b5599000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 16:35:30.595  6699  6699 W art     : b559a000-b559f000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 16:35:30.595  6699  6699 W art     : b559f000-b55a0000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 16:35:30.595  6699  6699 W art     : b55a0000-b55a1000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-10 16:35:30.595  6699  6699 W art     : b55a2000-b55d3000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 16:35:30.595  6699  6699 W art     : b55d3000-b55d6000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 16:35:30.595  6699  6699 W art     : b55d6000-b55d7000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 16:35:30.595  6699  6699 W art     : b55d8000-b5613000 r-xp 00000000 b3:17 893        /system/lib/libopus.so,
08-10 16:35:30.595  6699  6699 W art     : b5613000-b5614000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-10 16:35:30.595  6699  6699 W art     : b5614000-b5615000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-10 16:35:30.595  6699  6699 W art     : b5616000-b561d000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
,08-10 16:35:30.595  6699  6699 W art     : b561d000-b561e000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b561e000-b561f000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-10 16:35:30.595  6699  6699 W art     : b561f000-b5620000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-10 16:35:30.595  6699  6699 W art     : b5620000-b5621000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-10 16:35:30.595  6699  6699 W art     : b5621000-b5638000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-10 16:35:30.595  6699  6699 W art     : b5638000-b5639000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5639000-b563c000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
,08-10 16:35:30.595  6699  6699 W art     : b563c000-b563d000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-10 16:35:30.595  6699  6699 W art     : b563d000-b565c000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-10 16:35:30.595  6699  6699 W art     : b565c000-b565d000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-10 16:35:30.595  6699  6699 W art     : b565d000-b565e000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-10 16:35:30.595  6699  6699 W art     : b565e000-b569c000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
,08-10 16:35:30.595  6699  6699 W art     : b569c000-b569d000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b569d000-b569f000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-10 16:35:30.595  6699  6699 W art     : b569f000-b56a0000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-10 16:35:30.595  6699  6699 W art     : b56a1000-b56a8000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
,08-10 16:35:30.595  6699  6699 W art     : b56a8000-b56a9000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 16:35:30.595  6699  6699 W art     : b56a9000-b56aa000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 16:35:30.595  6699  6699 W art     : b56ab000-b56ae000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 16:35:30.595  6699  6699 W art     : b56ae000-b56af000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
,08-10 16:35:30.595  6699  6699 W art     : b56af000-b56b0000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 16:35:30.595  6699  6699 W art     : b56b0000-b56b6000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 16:35:30.595  6699  6699 W art     : b56b6000-b56b7000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b56b7000-b56b8000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-10 16:35:30.595  6699  6699 W art     : b56b8000-b56b9000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 16:35:30.595  6699  6699 W art     : b56b9000-b56c2000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-10 16:35:30.595  6699  6699 W art     : b56c2000-b56c3000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-10 16:35:30.595  6699  6699 W art     : b56c3000-b56c4000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-10 16:35:30.595  6699  6699 W art     : b56c4000-b5755000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
,08-10 16:35:30.595  6699  6699 W art     : b5755000-b5756000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5756000-b5761000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 16:35:30.595  6699  6699 W art     : b5761000-b5762000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 16:35:30.595  6699  6699 W art     : b5763000-b5775000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-10 16:35:30.595  6699  6699 W art     : b5775000-b5776000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
,08-10 16:35:30.595  6699  6699 W art     : b5776000-b5777000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-10 16:35:30.595  6699  6699 W art     : b5778000-b577d000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-10 16:35:30.595  6699  6699 W art     : b577d000-b577e000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-10 16:35:30.595  6699  6699 W art     : b577e000-b577f000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-10 16:35:30.595  6699  6699 W art     : b5780000-b57ed000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
,08-10 16:35:30.595  6699  6699 W art     : b57ed000-b57ee000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b57ee000-b57f0000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-10 16:35:30.595  6699  6699 W art     : b57f0000-b57f1000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so,
08-10 16:35:30.595  6699  6699 W art     : b57f1000-b57f2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.595  6699  6699 W art     : b57f2000-b57f9000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 16:35:30.595  6699  6699 W art     : b57f9000-b57fa000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 16:35:30.595  6699  6699 W art     : b57fa000-b57fb000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 16:35:30.595  6699  6699 W art     : b57fc000-b587c000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 16:35:30.595  6699  6699 W art     : b587c000-b587d000 ---p 00000000 00:00 0 
,08-10 16:35:30.595  6699  6699 W art     : b587d000-b587e000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 16:35:30.595  6699  6699 W art     : b587e000-b587f000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 16:35:30.595  6699  6699 W art     : b587f000-b5896000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5896000-b58cd000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-10 16:35:30.595  6699  6699 W art     : ib/libqc-opt.so
08-10 16:35:30.595  6699  6699 W art     : b58cd000-b58ce000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
,08-10 16:35:30.595  6699  6699 W art     : b58ce000-b58cf000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-10 16:35:30.595  6699  6699 W art     : b58cf000-b58eb000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 16:35:30.595  6699  6699 W art     : b58eb000-b58ec000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 16:35:30.595  6699  6699 W art     : b58ec000-b58ed000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 16:35:30.595  6699  6699 W art     : b58ee000-b594f000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-10 16:35:30.595  6699  6699 W art     : b594f000-b5951000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
,08-10 16:35:30.595  6699  6699 W art     : b5951000-b5952000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-10 16:35:30.595  6699  6699 W art     : b5953000-b597a000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-10 16:35:30.595  6699  6699 W art     : b597a000-b597b000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b597b000-b597c000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-10 16:35:30.595  6699  6699 W art     : b597c000-b597d000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-10 16:35:30.595  6699  6699 W art     : b597e000-b5986000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-10 16:35:30.595  6699  6699 W art     : b5986000-b5988000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 16:35:30.595  6699  6699 W art     : b5988000-b5989000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 16:35:30.595  6699  6699 W art     : b598a000-b598d000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-10 16:35:30.595  6699  6699 W art     : b598d000-b598e000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-10 16:35:30.595  6699  6699 W art     : b598e000-b598f000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-10 16:35:30.595  6699  6699 W art     : b598f000-b5993000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
,08-10 16:35:30.595  6699  6699 W art     : b5993000-b5994000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5994000-b5995000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-10 16:35:30.595  6699  6699 W art     : b5995000-b5996000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-10 16:35:30.595  6699  6699 W art     : b5996000-b59a6000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-10 16:35:30.595  6699  6699 W art     : b59a6000-b59a7000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-10 16:35:30.595  6699  6699 W art     : b59a7000-b59a8000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
,08-10 16:35:30.595  6699  6699 W art     : b59a8000-b59ee000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b59ee000-b59f7000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-10 16:35:30.595  6699  6699 W art     : b59f7000-b59f8000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-10 16:35:30.595  6699  6699 W art     : b59f8000-b59f9000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-10 16:35:30.595  6699  6699 W art     : b59fa000-b59ff000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-10 16:35:30.595  6699  6699 W art     : b59ff000-b5a00000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
,08-10 16:35:30.595  6699  6699 W art     : b5a00000-b5a01000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-10 16:35:30.595  6699  6699 W art     : b5a01000-b5a04000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 16:35:30.595  6699  6699 W art     : b5a04000-b5a05000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5a05000-b5a06000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 16:35:30.595  6699  6699 W art     : b5a06000-b5a07000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 16:35:30.595  6699  6699 W art     : b5a08000-b5a20000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so,
08-10 16:35:30.595  6699  6699 W art     : b5a20000-b5a21000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5a21000-b5a22000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 16:35:30.595  6699  6699 W art     : b5a22000-b5a23000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 16:35:30.595  6699  6699 W art     : b5a23000-b5a24000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 16:35:30.595  6699  6699 W art     : b5a24000-b5bbe000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
,08-10 16:35:30.595  6699  6699 W art     : b5bbe000-b5bbf000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5bbf000-b5bcc000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-10 16:35:30.595  6699  6699 W art     : b5bcc000-b5bcd000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-10 16:35:30.595  6699  6699 W art     : b5bcd000-b5bd1000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-10 16:35:30.595  6699  6699 W art     : b5bd1000-b5bd2000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5bd2000-b5bd3000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-10 16:35:30.595  6699  6699 W art     : b5bd3000-b5bd4000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
,08-10 16:35:30.595  6699  6699 W art     : b5bd4000-b5be7000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-10 16:35:30.595  6699  6699 W art     : b5be7000-b5be8000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-10 16:35:30.595  6699  6699 W art     : b5be8000-b5be9000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-10 16:35:30.595  6699  6699 W art     : b5bea000-b5c35000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-10 16:35:30.595  6699  6699 W art     : b5c35000-b5c36000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-10 16:35:30.595  6699  6699 W art     : b5c36000-b5c37000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-10 16:35:30.595  6699  6699 W art     : b5c37000-b5c39000 rw-p 00000000 00:00 0 
,08-10 16:35:30.595  6699  6699 W art     : b5c3a000-b5c4b000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 16:35:30.595  6699  6699 W art     : b5c4b000-b5c4c000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5c4c000-b5c4d000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 16:35:30.595  6699  6699 W art     : b5c4d000-b5c4e000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 16:35:30.595  6699  6699 W art     : b5c4e000-b5c4f000 r--p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5c4f000-b5c59000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
,08-10 16:35:30.595  6699  6699 W art     : b5c59000-b5c5b000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-10 16:35:30.595  6699  6699 W art     : b5c5b000-b5c5c000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-10 16:35:30.595  6699  6699 W art     : b5c5c000-b5c75000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-10 16:35:30.595  6699  6699 W art     : b5c75000-b5c76000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-10 16:35:30.595  6699  6699 W art     : b5c76000-b5c79000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so,
08-10 16:35:30.595  6699  6699 W art     : b5c79000-b5c7d000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5c7d000-b5cf1000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-10 16:35:30.595  6699  6699 W art     : b5cf1000-b5cf2000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5cf2000-b5cf5000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
,08-10 16:35:30.595  6699  6699 W art     : b5cf5000-b5cf6000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-10 16:35:30.595  6699  6699 W art     : b5cf6000-b5cf7000 r--p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b5cf7000-b5cfa000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-10 16:35:30.595  6699  6699 W art     : b5cfa000-b5cfb000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so,
08-10 16:35:30.595  6699  6699 W art     : b5cfb000-b5cfc000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-10 16:35:30.595  6699  6699 W art     : b5cfc000-b5cfd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.595  6699  6699 W art     : b5cfd000-b5d02000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 16:35:30.595  6699  6699 W art     : b5d02000-b5d03000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
,08-10 16:35:30.595  6699  6699 W art     : b5d03000-b5d04000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 16:35:30.595  6699  6699 W art     : b5d04000-b5d05000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.595  6699  6699 W art     : b5d05000-b5d08000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 16:35:30.595  6699  6699 W art     : b5d08000-b5d09000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so,
08-10 16:35:30.595  6699  6699 W art     : b5d09000-b5d0a000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 16:35:30.595  6699  6699 W art     : b5d0a000-b5d0b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.595  6699  6699 W art     : b5d0b000-b5d0f000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-10 16:35:30.595  6699  6699 W art     : b5d0f000-b5d10000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
,08-10 16:35:30.595  6699  6699 W art     : b5d10000-b5d11000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-10 16:35:30.595  6699  6699 W art     : b5d11000-b5d12000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 16:35:30.595  6699  6699 W art     : b5d12000-b5d16000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 16:35:30.595  6699  6699 W art     : b5d16000-b5d17000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
,08-10 16:35:30.595  6699  6699 W art     : b5d17000-b5d18000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 16:35:30.595  6699  6699 W art     : b5d18000-b5d19000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.595  6699  6699 W art     : b5d19000-b5d27000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-10 16:35:30.595  6699  6699 W art     : b5d27000-b5d28000 ---p 00000000 00:00 0 
,08-10 16:35:30.595  6699  6699 W art     : b5d28000-b5d29000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-10 16:35:30.595  6699  6699 W art     : b5d29000-b5d2a000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-10 16:35:30.595  6699  6699 W art     : b5d2a000-b5d34000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 16:35:30.595  6699  6699 W art     : b5d34000-b5d37000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so,
08-10 16:35:30.595  6699  6699 W art     : b5d37000-b5d38000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 16:35:30.595  6699  6699 W art     : b5d38000-b5d39000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.595  6699  6699 W art     : b5d39000-b5d43000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
,08-10 16:35:30.595  6699  6699 W art     : b5d43000-b5d46000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-10 16:35:30.595  6699  6699 W art     : b5d46000-b5d47000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-10 16:35:30.595  6699  6699 W art     : b5d47000-b5d4b000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
,08-10 16:35:30.595  6699  6699 W art     : b5d4b000-b5d4c000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-10 16:35:30.595  6699  6699 W art     : b5d4c000-b5d4d000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-10 16:35:30.595  6699  6699 W art     : b5d4d000-b5d4e000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-10 16:35:30.595  6699  6699 W art     : b5d4e000-b5d5b000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-10 16:35:30.595  6699  6699 W art     : b5d5b000-b5d5d000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-10 16:35:30.595  6699  6699 W art     : b5d5d000-b5d5e000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
,08-10 16:35:30.595  6699  6699 W art     : b5d5e000-b6170000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-10 16:35:30.595  6699  6699 W art     : b6170000-b6171000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b6171000-b617a000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-10 16:35:30.595  6699  6699 W art     : b617a000-b617e000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-10 16:35:30.595  6699  6699 W art     : b617e000-b617f000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b617f000-b6186000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
,08-10 16:35:30.595  6699  6699 W art     : b6186000-b6187000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-10 16:35:30.595  6699  6699 W art     : b6187000-b6188000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-10 16:35:30.595  6699  6699 W art     : b6188000-b6189000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.595  6699  6699 W art     : b6189000-b61a4000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-10 16:35:30.595  6699  6699 W art     : b61a4000-b61a5000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-10 16:35:30.595  6699  6699 W art     : b61a5000-b61a6000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-10 16:35:30.595  6699  6699 W art     : b61a6000-b61a7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.595  6699  6699 W art     : b61a7000-b61f3000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so,
08-10 16:35:30.595  6699  6699 W art     : b61f3000-b61f4000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b61f4000-b61f5000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 16:35:30.595  6699  6699 W art     : b61f5000-b61f6000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 16:35:30.595  6699  6699 W art     : b61f6000-b61f7000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-10 16:35:30.595  6699  6699 W art     : b61f7000-b61fb000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-10 16:35:30.595  6699  6699 W art     : b61fb000-b61fc000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b61fc000-b61fd000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-10 16:35:30.595  6699  6699 W art     : b61fd000-b61fe000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
,08-10 16:35:30.595  6699  6699 W art     : b61fe000-b6236000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-10 16:35:30.595  6699  6699 W art     : b6236000-b6237000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-10 16:35:30.595  6699  6699 W art     : b6237000-b6238000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-10 16:35:30.595  6699  6699 W art     : b6238000-b6239000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-10 16:35:30.595  6699  6699 W art     : b6239000-b62d7000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-10 16:35:30.595  6699  6699 W art     : b62d7000-b62d8000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b62d8000-b62f6000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-10 16:35:30.595  6699  6699 W art     : b62f6000-b62f7000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
,08-10 16:35:30.595  6699  6699 W art     : b62f7000-b646a000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-10 16:35:30.595  6699  6699 W art     : b646a000-b6475000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-10 16:35:30.595  6699  6699 W art     : b6475000-b6476000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-10 16:35:30.595  6699  6699 W art     : b6476000-b658d000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
,08-10 16:35:30.595  6699  6699 W art     : b658d000-b6598000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-10 16:35:30.595  6699  6699 W art     : b6598000-b6599000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-10 16:35:30.595  6699  6699 W art     : b6599000-b659d000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b659d000-b65c1000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
,08-10 16:35:30.595  6699  6699 W art     : b65c1000-b65c3000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-10 16:35:30.595  6699  6699 W art     : b65c3000-b65c4000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-10 16:35:30.595  6699  6699 W art     : b65c4000-b666a000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-10 16:35:30.595  6699  6699 W art     : b666a000-b6677000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
,08-10 16:35:30.595  6699  6699 W art     : b6677000-b6678000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-10 16:35:30.595  6699  6699 W art     : b6678000-b6679000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b6679000-b66cc000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-10 16:35:30.595  6699  6699 W art     : b66cc000-b66cd000 ---p 00000000 00:00 0 ,
08-10 16:35:30.595  6699  6699 W art     : b66cd000-b66ce000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-10 16:35:30.595  6699  6699 W art     : b66ce000-b66cf000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-10 16:35:30.595  6699  6699 W art     : b66cf000-b66d4000 rw-p 00000000 00:00 0 
,08-10 16:35:30.595  6699  6699 W art     : b66d4000-b66e6000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-10 16:35:30.595  6699  6699 W art     : b66e6000-b66e7000 ---p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b66e7000-b66e8000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
,08-10 16:35:30.595  6699  6699 W art     : b66e8000-b66e9000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-10 16:35:30.595  6699  6699 W art     : b66e9000-b66f0000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 16:35:30.595  6699  6699 W art     : b66f0000-b66f1000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
,08-10 16:35:30.595  6699  6699 W art     : b66f1000-b66f2000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 16:35:30.595  6699  6699 W art     : b66f2000-b66f3000 rw-p 00000000 00:00 0 
08-10 16:35:30.595  6699  6699 W art     : b66f3000-b66f6000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-10 16:35:30.605  6699  6699 W art     : b66f6000-b66f7000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
,08-10 16:35:30.605  6699  6699 W art     : b66f7000-b66f8000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-10 16:35:30.605  6699  6699 W art     : b66f8000-b66fc000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-10 16:35:30.605  6699  6699 W art     : b66fc000-b66fd000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-10 16:35:30.605  6699  6699 W art     : b66fd000-b66fe000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
,08-10 16:35:30.605  6699  6699 W art     : b66fe000-b670c000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-10 16:35:30.605  6699  6699 W art     : b670c000-b670d000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b670d000-b670e000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-10 16:35:30.605  6699  6699 W art     : b670e000-b670f000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-10 16:35:30.605  6699  6699 W art     : b670f000-b6718000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
,08-10 16:35:30.605  6699  6699 W art     : b6718000-b6719000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 16:35:30.605  6699  6699 W art     : b6719000-b671a000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 16:35:30.605  6699  6699 W art     : b671a000-b6780000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-10 16:35:30.605  6699  6699 W art     : b6780000-b6781000 ---p 00000000 00:00 0 
,08-10 16:35:30.605  6699  6699 W art     : b6781000-b6783000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-10 16:35:30.605  6699  6699 W art     : b6783000-b678c000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-10 16:35:30.605  6699  6699 W art     : b678c000-b678f000 rw-p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b678f000-b6826000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
,08-10 16:35:30.605  6699  6699 W art     : b6826000-b6828000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-10 16:35:30.605  6699  6699 W art     : b6828000-b6829000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-10 16:35:30.605  6699  6699 W art     : b6829000-b682a000 rw-p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b682a000-b6b4b000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
,08-10 16:35:30.605  6699  6699 W art     : b6b4b000-b6b4c000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6b4c000-b6b67000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-10 16:35:30.605  6699  6699 W art     : b6b67000-b6b6b000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
,08-10 16:35:30.605  6699  6699 W art     : b6b6b000-b6b70000 rw-p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6b70000-b6b78000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 16:35:30.605  6699  6699 W art     : b6b78000-b6b79000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 16:35:30.605  6699  6699 W art     : b6b79000-b6b7a000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 16:35:30.605  6699  6699 W art     : b6b7a000-b6ba8000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
,08-10 16:35:30.605  6699  6699 W art     : b6ba8000-b6ba9000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6ba9000-b6bb0000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-10 16:35:30.605  6699  6699 W art     : b6bb0000-b6bb1000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-10 16:35:30.605  6699  6699 W art     : b6bb1000-b6bf7000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
,08-10 16:35:30.605  6699  6699 W art     : b6bf7000-b6bf8000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6bf8000-b6bfb000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-10 16:35:30.605  6699  6699 W art     : b6bfb000-b6bfc000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-10 16:35:30.605  6699  6699 W art     : b6bfc000-b6c17000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so,
08-10 16:35:30.605  6699  6699 W art     : b6c17000-b6c1b000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-10 16:35:30.605  6699  6699 W art     : b6c1b000-b6c1c000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-10 16:35:30.605  6699  6699 W art     : b6c1c000-b6c69000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-10 16:35:30.605  6699  6699 W art     : b6c69000-b6c6a000 ---p 00000000 00:00 0 ,
08-10 16:35:30.605  6699  6699 W art     : b6c6a000-b6c76000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-10 16:35:30.605  6699  6699 W art     : b6c76000-b6c77000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-10 16:35:30.605  6699  6699 W art     : b6c77000-b6c84000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-10 16:35:30.605  6699  6699 W art     : b6c84000-b6c85000 ---p 00000000 00:00 0 
,08-10 16:35:30.605  6699  6699 W art     : b6c85000-b6c86000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-10 16:35:30.605  6699  6699 W art     : b6c86000-b6c87000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-10 16:35:30.605  6699  6699 W art     : b6c87000-b6c8f000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-10 16:35:30.605  6699  6699 W art     : b6c8f000-b6c90000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6c90000-b6c91000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
,08-10 16:35:30.605  6699  6699 W art     : b6c91000-b6c92000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-10 16:35:30.605  6699  6699 W art     : b6c92000-b6c99000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-10 16:35:30.605  6699  6699 W art     : b6c99000-b6c9a000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-10 16:35:30.605  6699  6699 W art     : b6c9a000-b6c9b000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-10 16:35:30.605  6699  6699 W art     : b6c9b000-b6caf000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so,
08-10 16:35:30.605  6699  6699 W art     : b6caf000-b6cb1000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-10 16:35:30.605  6699  6699 W art     : b6cb1000-b6cb2000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-10 16:35:30.605  6699  6699 W art     : b6cb2000-b6cda000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-10 16:35:30.605  6699  6699 W art     : b6cda000-b6cdc000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
,08-10 16:35:30.605  6699  6699 W art     : b6cdc000-b6cdd000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-10 16:35:30.605  6699  6699 W art     : b6cdd000-b6ce0000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-10 16:35:30.605  6699  6699 W art     : b6ce0000-b6ce1000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-10 16:35:30.605  6699  6699 W art     : b6ce1000-b6ce2000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-10 16:35:30.605  6699  6699 W art     : b6ce2000-b6ceb000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
,08-10 16:35:30.605  6699  6699 W art     : b6ceb000-b6cec000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-10 16:35:30.605  6699  6699 W art     : b6cec000-b6ced000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-10 16:35:30.605  6699  6699 W art     : b6ced000-b6d0d000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-10 16:35:30.605  6699  6699 W art     : b6d0d000-b6d0e000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-10 16:35:30.605  6699  6699 W art     : b6d0e000-b6d0f000 rw-p 00020000 b3:17 2560       /system/lib/libm.so,
08-10 16:35:30.605  6699  6699 W art     : b6d0f000-b6d82000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-10 16:35:30.605  6699  6699 W art     : b6d82000-b6d86000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-10 16:35:30.605  6699  6699 W art     : b6d86000-b6d89000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-10 16:35:30.605  6699  6699 W art     : b6d89000-b6d93000 rw-p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6d93000-b6e1b000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
,08-10 16:35:30.605  6699  6699 W art     : b6e1b000-b6e1c000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6e1c000-b6e20000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-10 16:35:30.605  6699  6699 W art     : b6e20000-b6e21000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-10 16:35:30.605  6699  6699 W art     : b6e21000-b6e22000 rw-p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6e22000-b6e4b000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so,
08-10 16:35:30.605  6699  6699 W art     : b6e4b000-b6e4c000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6e4c000-b6e4f000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-10 16:35:30.605  6699  6699 W art     : b6e4f000-b6e50000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-10 16:35:30.605  6699  6699 W art     : b6e50000-b6f2a000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
,08-10 16:35:30.605  6699  6699 W art     : b6f2a000-b6f31000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 16:35:30.605  6699  6699 W art     : b6f31000-b6f39000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 16:35:30.605  6699  6699 W art     : b6f39000-b6f3a000 rw-p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6f3a000-b6f3b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-10 16:35:30.605  6699  6699 W art     : b6f3b000-b6f3c000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-10 16:35:30.605  6699  6699 W art     : b6f3c000-b6f3d000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.605  6699  6699 W art     : b6f3d000-b6f40000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-10 16:35:30.605  6699  6699 W art     : b6f40000-b6f65000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-10 16:35:30.605  6699  6699 W art     : b6f65000-b6f66000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6f66000-b6f6d000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-10 16:35:30.605  6699  6699 W art     : b6f6d000-b6f6e000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
,08-10 16:35:30.605  6699  6699 W art     : b6f6e000-b6f75000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-10 16:35:30.605  6699  6699 W art     : b6f75000-b6f76000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-10 16:35:30.605  6699  6699 W art     : b6f76000-b6f77000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-10 16:35:30.605  6699  6699 W art     : b6f77000-b6f78000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-10 16:35:30.605  6699  6699 W art     : b6f78000-b6f90000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-10 16:35:30.605  6699  6699 W art     : b6f90000-b6f91000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6f91000-b6f92000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-10 16:35:30.605  6699  6699 W art     : b6f92000-b6f93000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-10 16:35:30.605  6699  6699 W art     : b6f93000-b6fa1000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so,
08-10 16:35:30.605  6699  6699 W art     : b6fa1000-b6fa2000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6fa2000-b6fa3000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-10 16:35:30.605  6699  6699 W art     : b6fa3000-b6fa4000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
,08-10 16:35:30.605  6699  6699 W art     : b6fa4000-b6fa5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 16:35:30.605  6699  6699 W art     : b6fa5000-b6fa7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.605  6699  6699 W art     : b6fa7000-b6fa8000 rw-p 00000000 00:00 0          [anon:linker_alloc]
,08-10 16:35:30.605  6699  6699 W art     : b6fa8000-b6fa9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 16:35:30.605  6699  6699 W art     : b6fa9000-b6faa000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-10 16:35:30.605  6699  6699 W art     : b6faa000-b6fab000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 16:35:30.605  6699  6699 W art     : b6fab000-b6fcb000 r--s 00000000 00:0b 8210       /dev/__properties__
,08-10 16:35:30.605  6699  6699 W art     : b6fcb000-b6fcc000 r--p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6fcc000-b6fcd000 ---p 00000000 00:00 0 
08-10 16:35:30.605  6699  6699 W art     : b6fcd000-b6fcf000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-10 16:35:30.605  6699  6699 W art     : b6fcf000-b6fd0000 r-xp 00000000 00:00 0          [sigpage]
,08-10 16:35:30.605  6699  6699 W art     : b6fd0000-b6feb000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-10 16:35:30.605  6699  6699 W art     : b6feb000-b6fec000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-10 16:35:30.605  6699  6699 W art     : b6fec000-b6fee000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-10 16:35:30.605  6699  6699 W art     : b6fee000-b6ff0000 rw-p 00000000 00:00 0 
,08-10 16:35:30.605  6699  6699 W art     : b6ff0000-b6ff5000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-10 16:35:30.605  6699  6699 W art     : b6ff5000-b6ff6000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-10 16:35:30.605  6699  6699 W art     : b6ff6000-b6ff7000 rw-p 00000000 00:00 0 
,08-10 16:35:30.605  6699  6699 W art     : befc1000-befe2000 rw-p 00000000 00:00 0          [stack]
08-10 16:35:30.605  6699  6699 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-10 16:35:30.665  6699  6699 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-10 16:35:30.715  6699  6699 I Radio-JNI: register_android_hardware_Radio DONE
,08-10 16:35:30.725  6699  6699 E AffinityControl: AffinityControl: registerfunction enter
,08-10 16:35:30.745  6699  6699 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 16:35:30.755   744  1625 D PackageManager: START PACKAGE DELETE: observer{147592880}
08-10 16:35:30.755   744  1625 D PackageManager: pkg{<packageName>}
08-10 16:35:30.755   744  1625 D PackageManager: user{0}
08-10 16:35:30.755   744  1625 D PackageManager: caller{2000}
08-10 16:35:30.755   744  1625 D PackageManager: flags{2}
08-10 16:35:30.755   744  1625 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-10 16:35:30.755   744  1625 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-10 16:35:30.755   744  1625 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-10 16:35:30.755   744  1625 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-10 16:35:30.755   744  1625 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-10 16:35:30.755   744   901 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-10 16:35:30.755   744   901 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-10 16:35:30.755   744   901 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-10 16:35:30.755   744   901 D ApplicationPolicy: getApplicationUninstallationEnabled
08-10 16:35:30.755   744   901 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-10 16:35:30.755   744   901 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-10 16:35:30.755   744   901 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-10 16:35:30.755   744   901 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-10 16:35:30.755   744   901 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-10 16:35:30.755   744   901 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-10 16:35:30.755   744   806 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-10 16:35:30.755   744   806 I ActivityManager: Killing 6410:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-10 16:35:30.775   744   806 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-10 16:35:30.775   744   806 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-10 16:35:30.785   744   806 I ActivityManager: Start proc 6708:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-10 16:35:30.785  6708  6708 E Zygote  : v2
08-10 16:35:30.785  6708  6708 I libpersona: KNOX_SDCARD checking this for 10004
08-10 16:35:30.785  6708  6708 I libpersona: KNOX_SDCARD not a persona
,08-10 16:35:30.795  6708  6708 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-10 16:35:30.795  6708  6708 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 16:35:30.795  6708  6708 E Zygote  : accessInfo : 0
,08-10 16:35:30.795  6708  6708 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-10 16:35:30.795   744   806 I ActivityManager:   Force finishing activity ActivityRecord{87e81ff u0 com.test.thalitest/.MainActivity t152}
,08-10 16:35:30.805   293   417 I SurfaceFlinger: id=15 Removed NainActivit (4/10)
,08-10 16:35:30.805   293  1296 I SurfaceFlinger: id=15 Removed NainActivit (-2/10)
,08-10 16:35:30.805   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed7638c
,08-10 16:35:30.815   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed7638c
,08-10 16:35:30.825   744  1694 D GraphicsStats: Buffer count: 4
,08-10 16:35:30.825   744  1414 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@9ef7929)
,08-10 16:35:30.825   744  1332 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 16:35:30.825   744  1332 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 16:35:30.835   744  1332 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 16:35:30.845   744   901 D AASAinstall: there is not AASApackages.xml file
,08-10 16:35:30.845  6708  6708 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 16:35:30.845  6708  6708 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:31.125   744   901 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-10 16:35:31.155   744   901 W PackageSettings: Skipping PackageSetting{b9de042 com.example.hello/10192} due to missing metadata
,08-10 16:35:31.215   744   901 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-10 16:35:31.215   744  2139 I ActivityManager: Killing 5380:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-10 16:35:31.225   331   331 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-10 16:35:31.235  6708  6708 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-10 16:35:31.235   744  1625 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-10 16:35:31.245  6708  6708 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-10 16:35:31.245  6708  6708 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-10 16:35:31.245  6708  6708 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-10 16:35:31.245  6708  6708 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-10 16:35:31.245   744   901 I art     : Starting a blocking GC Explicit
,08-10 16:35:31.255  6708  6708 D AndroidRuntime: Shutting down VM
,08-10 16:35:31.265  6708  6708 E AndroidRuntime: FATAL EXCEPTION: main
08-10 16:35:31.265  6708  6708 E AndroidRuntime: Process: com.test.thalitest, PID: 6708
08-10 16:35:31.265  6708  6708 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-10 16:35:31.265  6708  6708 E AndroidRuntime: 	... 9 more
,08-10 16:35:31.285  6728  6728 E Zygote  : v2
08-10 16:35:31.285   744   806 I ActivityManager: Start proc 6728:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
08-10 16:35:31.285  6728  6728 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 16:35:31.285  6728  6728 I libpersona: KNOX_SDCARD checking this for 1000
08-10 16:35:31.285  6728  6728 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 16:35:31.285  6728  6728 I libpersona: KNOX_SDCARD not a persona
08-10 16:35:31.285  6728  6728 E Zygote  : accessInfo : 0
08-10 16:35:31.285  6708  6708 I Process : Sending signal. PID: 6708 SIG: 9
,08-10 16:35:31.305   744  1677 I ActivityManager: Process com.test.thalitest (pid 6708)(adj 9) has died(160,740)
,08-10 16:35:31.305   744  1677 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-10 16:35:31.305   744  1677 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-10 16:35:31.315   744  1677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-10 16:35:31.315  6728  6728 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 16:35:31.315  6728  6728 D ActivityThread: Added TimaKeyStore provider
,08-10 16:35:31.325   744  1868 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9744ae u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e9724f 6728:com.samsung.android.sm/1000}
08-10 16:35:31.325   744   806 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
08-10 16:35:31.325   744   806 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-10 16:35:31.335  6728  6728 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-10 16:35:31.365  6728  6728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-10 16:35:31.375   744  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9744ae u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{342e3e 4144:com.google.android.gms/u0a11}
,08-10 16:35:31.405   744   901 I art     : Explicit concurrent mark sweep GC freed 93233(4MB) AllocSpace objects, 16(320KB) LOS objects, 27% free, 41MB/57MB, paused 1.827ms total 160.202ms
,08-10 16:35:31.435   744   901 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-10 16:35:31.435   744   901 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-10 16:35:31.435   744   901 D AASAinstall: there is not AASApackages.xml file
,08-10 16:35:31.435   744   901 D PackageManager: result of delete: 1{147592880}
,08-10 16:35:31.435  6699  6699 I art     : System.exit called, status: 0
08-10 16:35:31.435  6699  6699 I AndroidRuntime: VM exiting with result code 0.
,08-10 16:35:31.445   744   901 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-10 16:35:31.445   744   901 D PackageManager: userId{-1}
08-10 16:35:31.445   744   901 D PackageManager: andCode{true}
,08-10 16:35:31.455   744   901 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-10 16:35:31.465  5847  6753 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-10 16:35:31.475  5847  6753 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-10 16:35:31.475  5847  6753 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-10 16:35:31.495   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.505  1375  1375 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-10 16:35:31.505  1375  1375 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-10 16:35:31.505   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.505   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.505   744   863 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.505   744   863 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.515  1970  1970 E SamsungIME: mOCRHelper is null
,08-10 16:35:31.515   744  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 16:35:31.515  2040  2548 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-10 16:35:31.525   744   806 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7fb5c47 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9d3a664 4049:com.samsung.klmsagent/u0a18}
,08-10 16:35:31.525   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.525   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.535   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.535   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.535   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.535   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.535   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.535   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.535   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.535   744   744 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.535  4049  4049 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Wed Aug 10 16:35:31 GMT+02:00 2016
,08-10 16:35:31.545   744   744 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.545   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.545   744  1365 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/152_task.xml
,08-10 16:35:31.545   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.545   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.545   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.545   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.545  1647  1647 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-10 16:35:31.555  3188  3218 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-10 16:35:31.555  3188  3218 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-10 16:35:31.555   744  1365 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/152_task_thumbnail.png
,08-10 16:35:31.555   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.555   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.555   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.555   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.555   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.555   744   744 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.555  3188  3218 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-10 16:35:31.555  3188  3218 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-10 16:35:31.555   744  1218 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-10 16:35:31.555   744   799 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.565   744   744 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.565  4049  4049 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-10 16:35:31.565   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.565  4049  4049 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
08-10 16:35:31.565  4049  4049 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-10 16:35:31.565   744  1323 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-10 16:35:31.565   744  1323 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-10 16:35:31.565  4049  4049 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-10 16:35:31.565   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.565   744  1322 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-10 16:35:31.565   744  1322 D NtpTrustedTime: currentTimeMillis() cache hit
08-10 16:35:31.565   744  1322 V NetworkStats: performPollLocked(flags=0x3)
08-10 16:35:31.565   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.575   744  1988 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7fb5c47 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39f55ff 744:system/1000}
,08-10 16:35:31.575  4049  6759 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-10 16:35:31.575  4049  6759 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-10 16:35:31.575  4049  6759 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-10 16:35:31.575  4049  6759 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-10 16:35:31.575  4049  6759 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-10 16:35:31.575  4049  6759 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-10 16:35:31.575   744  1322 V NetworkStats: performPollLocked() took 7ms
08-10 16:35:31.575   744  1322 D NtpTrustedTime: currentTimeMillis() cache hit
,08-10 16:35:31.575  4049  6759 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-10 16:35:31.585   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.585   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.585   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.585   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.585  4049  6759 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-10 16:35:31.585   744  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,08-10 16:35:31.585   744  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,08-10 16:35:31.585   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.585   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.585   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.585  1641  6761 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595  1641  6761 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-10 16:35:31.595  1641  6761 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-10 16:35:31.595  1641  6761 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-10 16:35:31.595  1641  6761 D RegisteredComponentCache: Collect Tech packages for Knox
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   799 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   799 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 16:35:31.595   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.605   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.605   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.605   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.605   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.615   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.615   744   744 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-10 16:35:31.615  4049  6759 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-10 16:35:31.615  4049  6759 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-10 16:35:31.615  4049  6759 W System.err: mkdir failed: ENOENT (No such file or directory) : /data/user/0/com.samsung.klmsagent/databases
,08-10 16:35:31.615  4049  6759 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (2)
08-10 16:35:31.615  4049  6759 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131072) and mode_t (0) due to error (2)
08-10 16:35:31.615  4049  6759 E SQLiteLog: (14) cannot open file at line 31517 of [2ef4f3a5b1]
08-10 16:35:31.615  4049  6759 E SQLiteLog: (14) os_unix.c:31517: (2) open(/data/user/0/com.samsung.klmsagent/databases/klms.db) - 
08-10 16:35:31.615   744  1322 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x738d9000 in tid 1322 (NetworkStats)
,08-10 16:35:31.625  2045  2045 E audit_log: File locking failed. error= Bad file descriptor
08-10 16:35:31.625  4049  6759 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x733093a8 in tid 6759 (IntentService[K)
08-10 16:35:31.625  2045  2045 E audit_log: File locking failed. error= Bad file descriptor
,08-10 16:35:31.625  4049  6759 F libc    : Unable to open connection to debuggerd: Connection refused
,08-10 16:35:31.625  2045  2045 E audit_log: File locking failed. error= Bad file descriptor
,08-10 16:35:31.685   349   349 I Zygote  : Process 4049 exited due to signal (7)
,08-10 16:35:31.695   329   329 E installd: eof
08-10 16:35:31.695   329   329 E installd: failed to read size
08-10 16:35:31.695   329   329 I installd: closing connection
,08-10 16:35:31.695   292   292 I ServiceManager: service 'servicediscovery' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'updatelock' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'notification' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'location' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'country_detector' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'sec_location' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'search' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'execute' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'dropbox' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'wallpaper' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'audio' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'DockObserver' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'midi' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'usb' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'serial' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'kiesusb' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'jobscheduler' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'backup' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'appwidget' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'voiceinteraction' died
08-10 16:35:31.695  2853  2863 W Sensors : sensorservice died [0xad845800]
08-10 16:35:31.695   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'diskstats' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'mDNIe' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'AAS' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'MSCS' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'spengestureservice' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'quickconnect' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'samplingprofiler' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'commontime_management' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'dreams' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'graphicsstats' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'print' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'restrictions' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'media_session' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'media_router' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'trust' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'fingerprint' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'launcherapps' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'voip' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'sec_analytics' died
08-10 16:35:31.695   325   325 W AudioFlinger: power manager service died !!!
08-10 16:35:31.695   292   292 I ServiceManager: service 'telecom' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'edmnativehelper' died
08-10 16:35:31.695   325   325 W AudioFlinger: power manager service died !!!
08-10 16:35:31.695   292   292 I ServiceManager: service 'enterprise_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'statusbar' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'clipboard' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'clipboardEx' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'network_management' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'media_projection' died
08-10 16:35:,31.695   292   292 I ServiceManager: service 'lpnet' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'textservices' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'network_score' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'netstats' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'netpolicy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'wifip2p' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'wifi' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'wifihs20' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'wifiscanner' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'rttmanager' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'ethernet' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'connectivity' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'sb_service' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'input_method' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'accessibility' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'cover' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'mount' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'lock_settings' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'deviceidle' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'device_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'harmony_eas_service' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'sdp' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'sdp_log' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'dlp' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'log_manager_service' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'activity' died
08-10 16:35:31.695  1665  1875 W Sensors : sensorservice died [0xad6fa280]
08-10 16:35:31.695   292   292 I ServiceManager: service 'user' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'procstats' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'meminfo' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'gfxinfo' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'dbinfo' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'cpuinfo' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'permission' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'processinfo' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'sensorservice' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'battery' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'usagestats' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'webviewupdate' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'scheduling_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'telephony.registry' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'persona' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'display' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'persona_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'package' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'context_aware' died
08-10 16:35:31.695  2040  2070 W Sensors : sensorservice died [0xad845ec0]
08-10 16:35:31.695   292   292 I ServiceManager: service 'scontext' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'barbeam' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'multiwindow_facade' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'window' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'input' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'imms' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'bluetooth_manager' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'rcp' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'application_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'wifi_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'remoteinjection' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'edm_proxy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'mum_container_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'otp_service' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'SEAMService' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'media.camera.proxy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'account' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'content' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'DirEncryptService' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'LSManager' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'ReactiveService' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'EngineeringModeService' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'SatsService' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'sedenial' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'vibrator' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'tw_toolbox' died
08-10 16:35:31.715  2045  2045 E audit_log: File locking failed. error= Bad file descriptor
08-10 16:35:31.695   292   292 I ServiceManager: service 'tima' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'iccc' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'cepproxyks' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'emailksproxy' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'consumer_ir' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'alarm' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'uimode' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'batterystats' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'appops' died
08-10 16:35:31.695   292   292 I ServiceManager: service 'power' died
08-10 16:35:31.695   293   382 D libEGL  : eglTerminate EGLDisplay = 0xb69816fc
08-10 16:35:31.695  1937  1948 W Sensors : sensorservice died [0xad90aa80]
08-10 16:35:31.695   293   382 D libEGL  : eglTerminate EGLDisplay = 0xb69816fc
08-10 16:35:31.695   293   382 I SurfaceFlinger: restart the boot-animation @ binderDied
08-10 16:35:31.695  2126  2140 W Sensors : sensorservice died [0xadacd940]
08-10 16:35:31.705  1647  1647 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-10 16:35:31.705   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
08-10 16:35:31.705   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-10 16:35:31.715   293  1297 I SurfaceFlinger: id=9 Removed EimLayer(An (2/9)
08-10 16:35:31.715   293  1297 I SurfaceFlinger: id=6 Removed JmageWallpa (2/8)
08-10 16:35:31.715  2045  2045 E audit_log: File locking failed. error= Bad file descriptor
08-10 16:35:31.715   293  1297 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/8)
08-10 16:35:31.715   293  1297 I SurfaceFlinger: id=17 Removed VSBConnecti (3/7)
08-10 16:35:31.715   293  1297 I SurfaceFlinger: id=16 Removed VSBConnecti (4/6)
08-10 16:35:31.715   293  1297 I SurfaceFlinger: id=13 Removed DolorFade (5/5)
08-10 16:35:31.715   293  1297 I SurfaceFlinger: id=13 Removed DolorFade (-2/5)
08-10 16:35:31.715   293  1297 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/5)
08-10 16:35:31.715   293  1297 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/5)
08-10 16:35:31.715  2025  2025 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f018cef in tid 2025 (droid.bluetooth)
08-10 16:35:31.715  1641  1641 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x716012bd in tid 1641 (com.android.nfc)
08-10 16:35:31.715  2025  2025 F libc    : Unable to open connection to debuggerd: Connection refused
08-10 16:35:31.715  1641  1641 F libc    : Unable to open connection to debuggerd: Connection refused
08-10 16:35:31.715  1375  1624 E WifiManager: Channel connection lost
08-10 16:35:31.715  1647  2499 E WifiManager: Channel connection lost
08-10 16:35:31.715   293   417 I SurfaceFlinger: id=8 Removed EimLayer(Di (3/4)
08-10 16:35:31.725  2045  2045 E audit_log: File locking failed. error= Bad file descriptor
08-10 16:35:31.715   293  1296 I SurfaceFlinger: id=8 Removed EimLayer(Di (-2/4)
08-10 16:35:31.715   293  1296 I SurfaceFlinger: id=5 Removed TtatusBar (3/3)
08-10 16:35:31.715   293  1296 I SurfaceFlinger: id=5 Removed TtatusBar (-2/3)
08-10 16:35:31.715   293   417 I SurfaceFlinger: id=2 Removed GocusedStac (2/2)
08-10 16:35:31.715   293   417 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/1)
08-10 16:35:31.715   293   417 I SurfaceFlinger: id=4 Removed EimLayer(An (0/0)
08-10 16:35:31.715   293   417 I SurfaceFlinger: id=9 Removed EimLayer(An (-2/0)
08-10 16:35:31.715   293   417 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
08-10 16:35:31.715   293   417 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/0)
08-10 16:35:31.715   293   417 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/0)
08-10 16:35:31.715  2040  2545 E WifiManager: Channel connection lost
08-10 16:35:31.715  2853  3162 E WifiManager: Channel connection lost
08-10 16:35:31.715  1788  1919 E WifiManager: Channel connection lost
08-10 16:35:31.715  4144  4144 D AndroidRuntime: Shutting down VM
08-10 16:35:31.715  4144  4144 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x99bdad4e in tid 4144 (gle.android.gms)
08-10 16:35:31.715  4144  4144 F libc    : Unable to open connection to debuggerd: Connection refused
08-10 16:35:31.725  1375  3692 W Sensors : sensorservice died [0xad6ecd80]
08-10 16:35:31.735  6091  6143 E WifiManager: Channel connection lost
08-10 16:35:31.735  2853  2853 D BluetoothA2dp: Proxy object disconnected
08-10 16:35:31.735  2853  2853 D A2dpProfile: Bluetooth service disconnected
08-10 16:35:31.735  2105  2105 D BluetoothA2dp: Proxy object disconnected
08-10 16:35:31.735  2853  2853 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 16:35:31.735  2853  2853 D PanProfile: Bluetooth service disconnected
08-10 16:35:31.735  2853  2853 D BluetoothMap: Proxy object disconnected
08-10 16:35:31.735  2853  2853 D MapProfile: Bluetooth service disconnected
08-10 16:35:31.735  2853  2853 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ba022bd in tid 2853 (ndroid.settings)
08-10 16:35:31.735  2853  2853 F libc    : Unable to open connection to debuggerd: Connection refused
08-10 16:35:31.735  2045  2045 E audit_log: File locking failed. error= Bad file descriptor
,08-10 16:35:31.745   292   292 I ServiceManager: service 'nfc' died
08-10 16:35:31.745   292   292 I ServiceManager: service 'secontroller' died
08-10 16:35:31.745   292   292 I ServiceManager: service 'nfccontroller' died
08-10 16:35:31.775   349   349 I Zygote  : Process 1641 exited due to signal (7)
,08-10 16:35:31.785   349   349 I Zygote  : Process 2853 exited due to signal (7)
08-10 16:35:31.785   349  6729 I Zygote  : Process 2025 exited due to signal (7)
,08-10 16:35:31.785   349   349 I Zygote  : Process 4144 exited due to signal (7)
,08-10 16:35:31.955   291   291 I lowmemorykiller: ActivityManager disconnected
08-10 16:35:31.955   291   291 I lowmemorykiller: Closing Activity Manager data connection
08-10 16:35:31.955   293   559 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-10 16:35:31.955   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-10 16:35:32.205   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-10 16:35:32.205   293   559 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-10 16:35:32.215   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed763a4
,08-10 16:35:32.215   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed7638c
,08-10 16:35:32.215   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed7638c
,08-10 16:35:32.215   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed7638c
,08-10 16:35:32.215   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed763a4
,08-10 16:35:32.215   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed7638c
,08-10 16:35:32.215   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed7638c
08-10 16:35:32.215   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed7638c
,08-10 16:35:32.215   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed763a4

```
