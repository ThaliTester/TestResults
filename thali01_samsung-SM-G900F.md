#### Test 82337235c72b2f9_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
,08-23 13:54:16.801  4957  4957 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-23 13:54:16.801  4957  4957 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-23 13:54:16.801  4957  4957 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-23 13:54:16.811  4957  4957 I art     : System.exit called, status: 0
08-23 13:54:16.811  4957  4957 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
08-23 13:54:16.841   766  2307 I ActivityManager: Process com.samsung.aasaservice (pid 4957)(adj 0) has died(108,734)
08-23 13:54:16.841   766  2307 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-23 13:54:16.841   766  2307 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-23 13:54:16.841   766  2307 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-23 13:54:16.851  4936  4936 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-23 13:54:16.861   766   865 I ActivityManager: Start proc 6401:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-23 13:54:16.861   766  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 13:54:16.871  6401  6401 E Zygote  : v2
08-23 13:54:16.871  6401  6401 I libpersona: KNOX_SDCARD checking this for 10014
08-23 13:54:16.871  6401  6401 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:16.871  6401  6401 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:16.871  6401  6401 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:16.871  6401  6401 E Zygote  : accessInfo : 0
08-23 13:54:16.871  6401  6401 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-23 13:54:16.901  6401  6401 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:16.901  6401  6401 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:16.911   766   778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9311600 6401:com.google.android.partnersetup/u0a14}
08-23 13:54:16.911   766  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-23 13:54:16.921  6401  6401 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-23 13:54:16.931  6401  6401 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-23 13:54:16.951   766  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9311600 6401:com.google.android.partnersetup/u0a14}
08-23 13:54:16.971  6422  6422 E Zygote  : v2
08-23 13:54:16.971  6422  6422 I libpersona: KNOX_SDCARD checking this for 10015
08-23 13:54:16.971  6422  6422 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:16.971  6422  6422 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:16.981   766  1700 I ActivityManager: Start proc 6422:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-23 13:54:16.981  6422  6422 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:16.981  6422  6422 E Zygote  : accessInfo : 0
08-23 13:54:16.981  6422  6422 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-23 13:54:17.001  6422  6422 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:17.001  6422  6422 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:17.011   766  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0b5df 6422:com.samsung.groupcast/u0a15}
08-23 13:54:17.021  6422  6422 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-23 13:54:17.051   766  2306 I ActivityManager: Killing 5401:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #37
08-23 13:54:17.081   766   778 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
08-23 13:54:17.081  6422  6422 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-23 13:54:17.101  6422  6422 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-23 13:54:17.101  6422  6422 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-23 13:54:17.101  6422  6422 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-23 13:54:17.101  6422  6422 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-23 13:54:17.101  6422  6422 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-23 13:54:17.101  6422  6422 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 13:54:17.101  6422  6422 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 13:54:17.111  6422  6422 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 13:54:17.111  6422  6422 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 13:54:17.111  6422  6422 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:17.111  6422  6422 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 13:54:17.111  6422  6422 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 13:54:17.111  6422  6422 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:54:17.111  6422  6422 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 13:54:17.111  6422  6422 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 13:54:17.111   766  1730 I ActivityManager: Killing 5554:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
08-23 13:54:17.111   766  1730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54c365b 1884:com.sec.android.app.shealth:remote/u0a34}
08-23 13:54:17.141  6442  6442 E Zygote  : v2
08-23 13:54:17.141   766   778 I ActivityManager: Start proc 6442:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-23 13:54:17.141  6442  6442 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:17.141  6442  6442 I libpersona: KNOX_SDCARD checking this for 10041
08-23 13:54:17.141  6442  6442 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:17.141  6442  6442 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:17.141  6442  6442 E Zygote  : accessInfo : 0
08-23 13:54:17.141  6442  6442 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-23 13:54:17.151   766  1320 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
08-23 13:54:17.161  6442  6442 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:17.161  6442  6442 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:17.171   766  2307 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{91922c 6442:com.samsung.android.sdk.samsunglink/u0a41}
08-23 13:54:17.171  6442  6442 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-23 13:54:17.271  6442  6442 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 13:54:17.271  6442  6442 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-23 13:54:17.331  6442  6442 I SL_DEBUG: isLoggable:: isProductShip = 1
08-23 13:54:17.331  6442  6442 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-23 13:54:17.341   766   779 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-23 13:54:17.341   766  1425 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-23 13:54:17.351   766  2307 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-23 13:54:17.351   766  1700 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-23 13:54:17.351   766  2306 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-23 13:54:17.351   766  2303 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-23 13:54:17.351   766  1702 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-23 13:54:17.361   766  2310 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-23 13:54:17.361   766  1701 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-23 13:54:17.361   766  1730 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-23 13:54:17.451  6442  6442 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-23 13:54:17.461  6442  6442 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-23 13:54:17.461  6442  6442 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-23 13:54:17.461  6442  6442 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-23 13:54:17.461  6442  6442 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-23 13:54:17.461  6442  6442 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-23 13:54:17.461  6442  6442 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 13:54:17.461  6442  6442 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 13:54:17.461  6442  6442 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 13:54:17.461  6442  6442 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 13:54:17.461  6442  6442 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:17.461  6442  6442 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 13:54:17.461  6442  6442 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 13:54:17.461  6442  6442 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:54:17.461  6442  6442 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 13:54:17.461  6442  6442 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 13:54:17.461   766  2303 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13ff4bd 1704:android.process.acore/u0a19}
08-23 13:54:17.471  5145  5145 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-23 13:54:17.471   766  2303 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{af66c67 5145:com.sec.android.gallery3d/u0a47}
08-23 13:54:17.481   766   778 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-23 13:54:17.511   766  1703 I ActivityManager: Start proc 6465:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-23 13:54:17.511  6465  6465 E Zygote  : v2
08-23 13:54:17.511  6465  6465 I libpersona: KNOX_SDCARD checking this for 10050
08-23 13:54:17.511  6465  6465 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:17.511  6465  6465 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:17.511  6465  6465 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:17.511  6465  6465 E Zygote  : accessInfo : 0
08-23 13:54:17.511  6465  6465 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-23 13:54:17.541  6465  6465 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:17.541  6465  6465 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:17.541   766  1701 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{633de5c 6465:com.sec.android.app.myfiles/u0a50}
08-23 13:54:17.551  6465  6465 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-23 13:54:17.561  6465  6465 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-23 13:54:17.601  6465  6465 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-23 13:54:17.611   766  2306 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{66c261 5205:com.android.settings/1000}
08-23 13:54:17.621   331   331 E installd: system dir 0 : /system/app/
08-23 13:54:17.621   331   331 E installd: system dir 1 : /system/priv-app/
08-23 13:54:17.621   331   331 E installd: system dir 2 : /vendor/app/
08-23 13:54:17.621   331   331 E installd: system dir 3 : /oem/app/
08-23 13:54:17.631   766   938 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-23 13:54:17.631   766  1730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{66c261 5205:com.android.settings/1000}
08-23 13:54:17.641  6481  6481 E Zygote  : v2
08-23 13:54:17.641   766  1701 I ActivityManager: Start proc 6481:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-23 13:54:17.641  6481  6481 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:17.641  6481  6481 I libpersona: KNOX_SDCARD checking this for 10169
08-23 13:54:17.641  6481  6481 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:17.641  6481  6481 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:17.651  6481  6481 E Zygote  : accessInfo : 0
08-23 13:54:17.651  6481  6481 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-23 13:54:17.661  6302  6302 D CAR.SERVICE: onUnbind
08-23 13:54:17.661  6302  6302 D CAR.SERVICE: CSB onClientsDisconnected
08-23 13:54:17.661  6302  6302 D CAR.SERVICE: tearDown
08-23 13:54:17.661  6302  6302 D CAR.SERVICE: tearDownCarState
08-23 13:54:17.661  6302  6302 D CAR.SERVICE: Skip, car not connected.
08-23 13:54:17.661  6302  6302 D CAR.SERVICE: tearDownClientState
08-23 13:54:17.661  6302  6302 D CAR.SERVICE: requestStop
08-23 13:54:17.661  6302  6302 D CAR.SERVICE: onDestroy
08-23 13:54:17.671  6302  6302 D CAR.SERVICE: tearDown
08-23 13:54:17.671  6302  6302 D CAR.SERVICE: tearDownCarState
08-23 13:54:17.671  6302  6302 D CAR.SERVICE: Skip, car not connected.
08-23 13:54:17.671  6302  6302 D CAR.SERVICE: tearDownClientState
08-23 13:54:17.671  6302  6302 D CAR.SERVICE: requestStop
08-23 13:54:17.671  6481  6481 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:17.671  6481  6481 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:17.681   766  1700 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{94e8448 6481:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-23 13:54:17.681  6302  6302 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@e9db616 that was originally bound here
08-23 13:54:17.681  6302  6302 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@e9db616 that was originally bound here
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 13:54:17.681  6302  6302 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 13:54:17.681   766  2310 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@a6c72e1
08-23 13:54:17.681  6481  6481 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-23 13:54:17.691  6481  6481 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-23 13:54:17.711   766  1703 I ActivityManager: Killing 5572:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-23 13:54:17.711   766  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e496ef2 1667:com.android.phone/1001}
08-23 13:54:17.721  2218  2218 E audit   : type=1400 msg=audit(1471953257.721:284): avc:  denied  { execmod } for  pid=6406 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:54:17.721  2218  2218 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:17.721  2218  2218 E audit   : type=1300 msg=audit(1471953257.721:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b400c000 a1=51000 a2=5 a3=4 items=0 ppid=3578 ppcomm=adbd pid=6406 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:54:17.721  2218  2218 E audit   : type=1327 msg=audit(1471953257.721:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 13:54:17.721  2218  2218 E audit   : type=1320 msg=audit(1471953257.721:284): 
08-23 13:54:17.731   766  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e866580 1811:com.google.android.googlequicksearchbox:search/u0a61}
08-23 13:54:17.731   766  3426 D SSRM:n  : SIOP:: AP = 490, PST = 461, CUR = 350, LCD = 0
08-23 13:54:17.731   766  2307 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-23 13:54:17.751   766  2303 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e866580 1811:com.google.android.googlequicksearchbox:search/u0a61}
08-23 13:54:17.751   766  1411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bd48ec7 6344:com.samsung.android.sm.provider/1000}
08-23 13:54:17.771  6495  6495 E Zygote  : v2
08-23 13:54:17.771  6495  6495 I libpersona: KNOX_SDCARD checking this for 5012
08-23 13:54:17.771  6495  6495 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:17.771   766   778 I ActivityManager: Start proc 6495:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-23 13:54:17.781  6495  6495 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:17.781  6495  6495 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:17.781  6495  6495 E Zygote  : accessInfo : 0
08-23 13:54:17.781  6495  6495 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-23 13:54:17.781  2218  2218 E audit   : type=1400 msg=audit(1471953257.781:285): avc:  denied  { execmod } for  pid=6406 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:54:17.781  2218  2218 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:17.781  2218  2218 E audit   : type=1300 msg=audit(1471953257.781:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcc000 a1=51000 a2=5 a3=4 items=0 ppid=3578 ppcomm=adbd pid=6406 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:54:17.781  2218  2218 E audit   : type=1327 msg=audit(1471953257.781:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 13:54:17.781  2218  2218 E audit   : type=1320 msg=audit(1471953257.781:285): 
08-23 13:54:17.781  1811  6493 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 13:54:17.811  6495  6495 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:17.811  6495  6495 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:17.821   766  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1eb9cf4 6495:com.samsung.android.sm.devicesecurity/5012}
08-23 13:54:17.831  2218  2218 E audit   : type=1400 msg=audit(1471953257.831:286): avc:  denied  { execmod } for  pid=6406 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:54:17.831  2218  2218 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:17.831  2218  2218 E audit   : type=1300 msg=audit(1471953257.831:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcc000 a1=51000 a2=5 a3=4 items=0 ppid=3578 ppcomm=adbd pid=6406 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:54:17.831  2218  2218 E audit   : type=1327 msg=audit(1471953257.831:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 13:54:17.831  2218  2218 E audit   : type=1320 msg=audit(1471953257.831:286): 
08-23 13:54:17.831  6406  6406 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 13:54:17.831  6495  6495 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-23 13:54:17.831  6406  6406 D AndroidRuntime: CheckJNI is OFF
08-23 13:54:17.831  6406  6406 D AndroidRuntime: readGMSProperty: start
08-23 13:54:17.831  6406  6406 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:54:17.831  6406  6406 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:54:17.831  6406  6406 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:54:17.831  6406  6406 D AndroidRuntime: readGMSProperty: end
08-23 13:54:17.831  6406  6406 D AndroidRuntime: addProductProperty: start
08-23 13:54:17.841  6406  6406 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:54:17.841  6406  6406 W art     : aee33000-b1d59000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:54:17.841  6406  6406 W art     : b1d59000-b3fc8000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:54:17.841  6406  6406 W art     : b3fc8000-b3fc9000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:54:17.841  6406  6406 W art     : b3fc9000-b3fca000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b42fb000-b4324000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:54:17.841  6406  6406 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 13:54:17.841  6406  6406 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 13:54:17.841  6406  6406 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 13:54:17.841  6406  6406 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 13:54:17.841  6406  6406 W art     : b489e000-b48a1000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:54:17.841  6406  6406 W art     : b48a1000-b48a2000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:54:17.841  6406  6406 W art     : b48a2000-b48a3000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:54:17.841  6406  6406 W art     : b48a3000-b48a4000 r--p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b48a4000-b48c4000 r--s 00000000 00:0b 7184       /dev/__properties__
08-23 13:54:17.841  6406  6406 W art     : b48c4000-b52d5000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:54:17.841  6406  6406 W art     : b52d5000-b52d6000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b52d6000-b531f000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:54:17.841  6406  6406 W art     : b531f000-b5320000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:54:17.841  6406  6406 W art     : b5320000-b5328000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5328000-b5329000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b5329000-b535e000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:54:17.841  6406  6406 W art     : b535e000-b535f000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b535f000-b5360000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:54:17.841  6406  6406 W art     : b5360000-b5361000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:54:17.841  6406  6406 W art     : b5361000-b53b9000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 13:54:17.841  6406  6406 W art     : b53b9000-b53ba000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b53ba000-b53bb000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 13:54:17.841  6406  6406 W art     : b53bb000-b53bc000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 13:54:17.841  6406  6406 W art     : b53bd000-b53c3000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:54:17.841  6406  6406 W art     : b53c3000-b53c4000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:54:17.841  6406  6406 W art     : b53c4000-b53c5000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:54:17.841  6406  6406 W art     : b53c5000-b53c7000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b53c8000-b53d2000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:54:17.841  6406  6406 W art     : b53d2000-b53d5000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:54:17.841  6406  6406 W art     : b53d5000-b53d6000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:54:17.841  6406  6406 W art     : b53d7000-b53ee000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:54:17.841  6406  6406 W art     : b53ee000-b53ef000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b53ef000-b53f0000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:54:17.841  6406  6406 W art     : b53f0000-b53f1000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:54:17.841  6406  6406 W art     : b53f2000-b53fc000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:54:17.841  6406  6406 W art     : b53fc000-b53fd000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:54:17.841  6406  6406 W art     : b53fd000-b53fe000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:54:17.841  6406  6406 W art     : b53fe000-b5402000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:54:17.841  6406  6406 W art     : b5402000-b5403000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:54:17.841  6406  6406 W art     : b5403000-b5404000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:54:17.841  6406  6406 W art     : b5404000-b541a000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 13:54:17.841  6406  6406 W art     : b541a000-b541b000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 13:54:17.841  6406  6406 W art     : b541b000-b541c000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 13:54:17.841  6406  6406 W art     : b541c000-b5429000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:54:17.841  6406  6406 W art     : b5429000-b542a000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:54:17.841  6406  6406 W art     : b542a000-b542b000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:54:17.841  6406  6406 W art     : b542b000-b548b000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 13:54:17.841  6406  6406 W art     : b548b000-b548e000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 13:54:17.841  6406  6406 W art     : b548e000-b5492000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5492000-b54f3000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:54:17.841  6406  6406 W art     : b54f3000-b54f4000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:54:17.841  6406  6406 W art     : b54f4000-b5543000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:54:17.841  6406  6406 W art     : b5543000-b5545000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:54:17.841  6406  6406 W art     : b5545000-b5546000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:54:17.841  6406  6406 W art     : b5546000-b5547000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5547000-b554e000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:54:17.841  6406  6406 W art     : b554e000-b554f000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:54:17.841  6406  6406 W art     : b554f000-b5550000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-23 13:54:17.841  6406  6406 W art     : avc_common.so
08-23 13:54:17.841  6406  6406 W art     : b5551000-b5554000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:54:17.841  6406  6406 W art     : b5554000-b5555000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:54:17.841  6406  6406 W art     : b5555000-b5556000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-23 13:54:17.841  6406  6406 W art     : enc_common.so
08-23 13:54:17.841  6406  6406 W art     : b5557000-b555b000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:54:17.841  6406  6406 W art     : b555b000-b555c000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b555c000-b555d000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:54:17.841  6406  6406 W art     : b555d000-b555e000 rw-p 00005000 b3:17 2510       /syste
08-23 13:54:17.841  6406  6406 W art     : m/lib/libpowermanager.so
08-23 13:54:17.841  6406  6406 W art     : b555f000-b557c000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:54:17.841  6406  6406 W art     : b557c000-b557d000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:54:17.841  6406  6406 W art     : b557d000-b557e000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:54:17.841  6406  6406 W art     : b557f000-b5584000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:54:17.841  6406  6406 W art     : b5584000-b5585000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:54:17.841  6406  6406 W art     : b5585000-b5586000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:54:17.841  6406  6406 W art     : b5587000-b55b8000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:54:17.841  6406  6406 W art     : b55b8000-b55bb000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:54:17.841  6406  6406 W art     : b55bb000-b55bc000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:54:17.841  6406  6406 W art     : b55bd000-b55f8000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 13:54:17.841  6406  6406 W art     : b55f8000-b55f9000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 13:54:17.841  6406  6406 W art     : b55f9000-b55fa000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 13:54:17.841  6406  6406 W art     : b55fb000-b5602000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:54:17.841  6406  6406 W art     : b5602000-b5603000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5603000-b5604000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:54:17.841  6406  6406 W art     : b5604000-b5605000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:54:17.841  6406  6406 W art     : b5605000-b5606000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b5606000-b561d000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:54:17.841  6406  6406 W art     : b561d000-b561e000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b561e000-b5621000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:54:17.841  6406  6406 W art     : b5621000-b5622000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:54:17.841  6406  6406 W art     : b5622000-b5641000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:54:17.841  6406  6406 W art     : b5641000-b5642000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:54:17.841  6406  6406 W art     : b5642000-b5643000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:54:17.841  6406  6406 W art     : b5643000-b5681000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 13:54:17.841  6406  6406 W art     : b5681000-b5682000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5682000-b5684000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 13:54:17.851  1811  6493 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-23 13:54:17.841  6406  6406 W art     : b5684000-b5685000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 13:54:17.861  6508  6508 I libpersona: KNOX_SDCARD checking this for 10210
08-23 13:54:17.841  6406  6406 W art     : b5686000-b568d000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:54:17.861  6508  6508 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:17.841  6406  6406 W art     : b568d000-b568e000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:54:17.861   766   865 I ActivityManager: Start proc 6508:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-23 13:54:17.841  6406  6406 W art     : b568e000-b568f000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:54:17.841  6406  6406 W art     : b5690000-b5693000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:54:17.841  6406  6406 W art     : b5693000-b5694000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:54:17.841  6406  6406 W art     : b5694000-b5695000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:54:17.841  6406  6406 W art     : b5695000-b569b000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:54:17.841  6406  6406 W art     : b569b000-b569c000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b569c000-b569d000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:54:17.841  6406  6406 W art     : b569d000-b569e000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:54:17.841  6406  6406 W art     : b569e000-b56a7000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:54:17.841  6406  6406 W art     : b56a7000-b56a8000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:54:17.841  6406  6406 W art     : b56a8000-b56a9000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:54:17.841  6406  6406 W art     : b56a9000-b573a000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:54:17.841  6406  6406 W art     : b573a000-b573b000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b573b000-b5746000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:54:17.841  6406  6406 W art     : b5746000-b5747000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:54:17.841  6406  6406 W art     : b5748000-b575a000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 13:54:17.841  6406  6406 W art     : b575a000-b575b000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 13:54:17.841  6406  6406 W art     : b575b000-b575c000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 13:54:17.841  6406  6406 W art     : b575d000-b5762000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:54:17.841  6406  6406 W art     : b5762000-b5763000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:54:17.841  6406  6406 W art     : b5763000-b5764000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:54:17.841  6406  6406 W art     : b5765000-b57d2000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:54:17.841  6406  6406 W art     : b57d2000-b57d3000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b57d3000-b57d5000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:54:17.841  6406  6406 W art     : b57d5000-b57d6000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:54:17.841  6406  6406 W art     : b57d6000-b57d7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b57d7000-b57de000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:54:17.841  6406  6406 W art     : b57de000-b57df000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:54:17.841  6406  6406 W art     : b57df000-b57e0000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:54:17.841  6406  6406 W art     : b57e1000-b5861000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:54:17.841  6406  6406 W art     : b5861000-b5862000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5862000-b5863000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:54:17.841  6406  6406 W art     : b5863000-b5864000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:54:17.841  6406  6406 W art     : b5864000-b587b000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b587b000-b58b2000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 13:54:17.841  6406  6406 W art     : ib/libqc-opt.so
08-23 13:54:17.841  6406  6406 W art     : b58b2000-b58b3000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:54:17.841  6406  6406 W art     : b58b3000-b58b4000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:54:17.841  6406  6406 W art     : b58b4000-b58d0000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:54:17.841  6406  6406 W art     : b58d0000-b58d1000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:54:17.841  6406  6406 W art     : b58d1000-b58d2000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:54:17.841  6406  6406 W art     : b58d3000-b5934000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 13:54:17.841  6406  6406 W art     : b5934000-b5936000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 13:54:17.841  6406  6406 W art     : b5936000-b5937000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 13:54:17.841  6406  6406 W art     : b5938000-b595f000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 13:54:17.841  6406  6406 W art     : b595f000-b5960000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5960000-b5961000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 13:54:17.841  6406  6406 W art     : b5961000-b5962000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 13:54:17.841  6406  6406 W art     : b5963000-b596b000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:54:17.841  6406  6406 W art     : b596b000-b596d000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:54:17.841  6406  6406 W art     : b596d000-b596e000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:54:17.841  6406  6406 W art     : b596f000-b5972000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 13:54:17.841  6406  6406 W art     : b5972000-b5973000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 13:54:17.841  6406  6406 W art     : b5973000-b5974000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 13:54:17.841  6406  6406 W art     : b5974000-b5978000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:54:17.841  6406  6406 W art     : b5978000-b5979000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5979000-b597a000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:54:17.841  6406  6406 W art     : b597a000-b597b000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:54:17.841  6406  6406 W art     : b597b000-b598b000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 13:54:17.841  6406  6406 W art     : b598b000-b598c000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 13:54:17.841  6406  6406 W art     : b598c000-b598d000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 13:54:17.841  6406  6406 W art     : b598d000-b59d3000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b59d3000-b59dc000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 13:54:17.841  6406  6406 W art     : b59dc000-b59dd000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 13:54:17.841  6406  6406 W art     : b59dd000-b59de000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 13:54:17.841  6406  6406 W art     : b59df000-b59e4000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 13:54:17.841  6406  6406 W art     : b59e4000-b59e5000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 13:54:17.841  6406  6406 W art     : b59e5000-b59e6000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 13:54:17.841  6406  6406 W art     : b59e6000-b59e9000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:54:17.841  6406  6406 W art     : b59e9000-b59ea000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b59ea000-b59eb000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:54:17.841  6406  6406 W art     : b59eb000-b59ec000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:54:17.841  6406  6406 W art     : b59ed000-b5a05000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:54:17.841  6406  6406 W art     : b5a05000-b5a06000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5a06000-b5a07000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:54:17.841  6406  6406 W art     : b5a07000-b5a08000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:54:17.871  1811  6493 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-23 13:54:17.841  6406  6406 W art     : b5a09000-b5ba3000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:54:17.841  6406  6406 W art     : b5ba3000-b5ba4000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5ba4000-b5bb1000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:54:17.841  6406  6406 W art     : b5bb1000-b5bb2000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:54:17.841  6406  6406 W art     : b5bb2000-b5bb6000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 13:54:17.841  6406  6406 W art     : b5bb6000-b5bb7000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5bb7000-b5bb8000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 13:54:17.841  6406  6406 W art     : b5bb8000-b5bb9000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 13:54:17.841  6406  6406 W art     : b5bb9000-b5bcc000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:54:17.841  6406  6406 W art     : b5bcc000-b5bcd000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:54:17.841  6406  6406 W art     : b5bcd000-b5bce000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:54:17.841  6406  6406 W art     : b5bce000-b5bcf000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:54:17.841  6406  6406 W art     : b5bcf000-b5c1a000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:54:17.841  6406  6406 W art     : b5c1a000-b5c1b000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:54:17.841  6406  6406 W art     : b5c1b000-b5c1c000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:54:17.841  6406  6406 W art     : b5c1c000-b5c1e000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5c1f000-b5c30000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:54:17.841  6406  6406 W art     : b5c30000-b5c31000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5c31000-b5c32000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:54:17.841  6406  6406 W art     : b5c32000-b5c33000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:54:17.841  6406  6406 W art     : b5c34000-b5c3e000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:54:17.841  6406  6406 W art     : b5c3e000-b5c40000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:54:17.841  6406  6406 W art     : b5c40000-b5c41000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:54:17.841  6406  6406 W art     : b5c41000-b5c5a000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:54:17.841  6406  6406 W art     : b5c5a000-b5c5b000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:54:17.841  6406  6406 W art     : b5c5b000-b5c5e000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:54:17.841  6406  6406 W art     : b5c5e000-b5c62000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5c62000-b5cd6000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 13:54:17.841  6406  6406 W art     : b5cd6000-b5cd7000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5cd7000-b5cda000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 13:54:17.841  6406  6406 W art     : b5cda000-b5cdb000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 13:54:17.841  6406  6406 W art     : b5cdb000-b5cdc000 r--p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5cdc000-b5cdf000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:54:17.841  6406  6406 W art     : b5cdf000-b5ce0000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:54:17.841  6406  6406 W art     : b5ce0000-b5ce1000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:54:17.841  6406  6406 W art     : b5ce1000-b5ce2000 r--p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5ce2000-b5ce7000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:54:17.841  6406  6406 W art     : b5ce7000-b5ce8000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:54:17.841  6406  6406 W art     : b5ce8000-b5ce9000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:54:17.841  6406  6406 W art     : b5ce9000-b5cea000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b5cea000-b5ced000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:54:17.841  6406  6406 W art     : b5ced000-b5cee000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:54:17.841  6406  6406 W art     : b5cee000-b5cef000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:54:17.841  6406  6406 W art     : b5cef000-b5cf0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b5cf0000-b5cf4000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:54:17.841  6406  6406 W art     : b5cf4000-b5cf5000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:54:17.841  6406  6406 W art     : b5cf5000-b5cf6000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:54:17.841  6406  6406 W art     : b5cf6000-b5cf7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:54:17.841  6406  6406 W art     : b5cf7000-b5cfb000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:54:17.841  6406  6406 W art     : b5cfb000-b5cfc000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:54:17.841  6406  6406 W art     : b5cfc000-b5cfd000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:54:17.841  6406  6406 W art     : b5cfd000-b5cfe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b5cfe000-b5d0c000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 13:54:17.841  6406  6406 W art     : b5d0c000-b5d0d000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b5d0d000-b5d0e000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 13:54:17.841  6406  6406 W art     : b5d0e000-b5d0f000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 13:54:17.841  6406  6406 W art     : b5d0f000-b5d19000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:54:17.841  6406  6406 W art     : b5d19000-b5d1c000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:54:17.841  6406  6406 W art     : b5d1c000-b5d1d000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:54:17.841  6406  6406 W art     : b5d1d000-b5d1e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b5d1e000-b5d28000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 13:54:17.841  6406  6406 W art     : b5d28000-b5d2b000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 13:54:17.841  6406  6406 W art     : b5d2b000-b5d2c000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 13:54:17.841  6406  6406 W art     : b5d2c000-b5d30000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:54:17.841  6406  6406 W art     : b5d30000-b5d31000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:54:17.841  6406  6406 W art     : b5d31000-b5d32000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:54:17.841  6406  6406 W art     : b5d32000-b5d33000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b5d33000-b5d40000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:54:17.841  6406  6406 W art     : b5d40000-b5d42000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:54:17.841  6406  6406 W art     : b5d42000-b5d43000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:54:17.841  6406  6406 W art     : b5d43000-b6155000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 13:54:17.841  6406  6406 W art     : b6155000-b6156000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b6156000-b615f000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 13:54:17.841  6406  6406 W art     : b615f000-b6163000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 13:54:17.841  6406  6406 W art     : b6163000-b6164000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b6164000-b616b000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:54:17.841  6406  6406 W art     : b616b000-b616c000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:54:17.841  6406  6406 W art     : b616c000-b616d000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:54:17.841  6406  6406 W art     : b616d000-b616e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b616e000-b6189000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-23 13:54:17.841  6406  6406 W art     : b6189000-b618a000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 13:54:17.841  6406  6406 W art     : b618a000-b618b000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 13:54:17.841  6406  6406 W art     : b618b000-b618c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b618c000-b61d8000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:54:17.841  6406  6406 W art     : b61d8000-b61d9000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b61d9000-b61da000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:54:17.841  6406  6406 W art     : b61da000-b61db000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:54:17.841  6406  6406 W art     : b61db000-b61dc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b61dc000-b61e0000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:54:17.841  6406  6406 W art     : b61e0000-b61e1000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b61e1000-b61e2000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:54:17.841  6406  6406 W art     : b61e2000-b61e3000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:54:17.841  6406  6406 W art     : b61e3000-b621b000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:54:17.841  6406  6406 W art     : b621b000-b621c000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:54:17.841  6406  6406 W art     : b621c000-b621d000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:54:17.841  6406  6406 W art     : b621d000-b621e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.841  6406  6406 W art     : b621e000-b62bc000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 13:54:17.841  6406  6406 W art     : b62bc000-b62bd000 ---p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b62bd000-b62db000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 13:54:17.841  6406  6406 W art     : b62db000-b62dc000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-23 13:54:17.841  6406  6406 W art     : b62dc000-b644f000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:54:17.841  6406  6406 W art     : b644f000-b645a000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:54:17.841  6406  6406 W art     : b645a000-b645b000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:54:17.841  6406  6406 W art     : b645b000-b6572000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:54:17.841  6406  6406 W art     : b6572000-b657d000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:54:17.841  6406  6406 W art     : b657d000-b657e000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:54:17.841  6406  6406 W art     : b657e000-b6582000 rw-p 00000000 00:00 0 
08-23 13:54:17.841  6406  6406 W art     : b6582000-b65a6000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-23 13:54:17.841  6406  6406 W art     : b65a6000-b65a8000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 13:54:17.851  6406  6406 W art     : b65a8000-b65a9000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 13:54:17.851  6406  6406 W art     : b65a9000-b664f000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 13:54:17.851  6406  6406 W art     : b664f000-b665c000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-23 13:54:17.851  6406  6406 W art     : b665c000-b665d000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 13:54:17.851  6406  6406 W art     : b665d000-b665e000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b665e000-b66b1000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:54:17.851  6406  6406 W art     : b66b1000-b66b2000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b66b2000-b66b3000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:54:17.851  6406  6406 W art     : b66b3000-b66b4000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:54:17.851  6406  6406 W art     : b66b4000-b66b9000 rw-p 00000000 00:00 0 
,08-23 13:54:17.851  6406  6406 W art     : b66b9000-b66cb000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 13:54:17.851  6406  6406 W art     : b66cb000-b66cc000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b66cc000-b66cd000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 13:54:17.851  6406  6406 W art     : b66cd000-b66ce000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 13:54:17.851  6406  6406 W art     : b66ce000-b66d5000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:54:17.851  6406  6406 W art     : b66d5000-b66d6000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:54:17.851  6406  6406 W art     : b66d6000-b66d7000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:54:17.851  6406  6406 W art     : b66d7000-b66d8000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b66d8000-b66db000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 13:54:17.851  6406  6406 W art     : b66db000-b66dc000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 13:54:17.851  6406  6406 W art     : b66dc000-b66dd000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 13:54:17.851  6406  6406 W art     : b66dd000-b66e1000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 13:54:17.851  6406  6406 W art     : b66e1000-b66e2000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 13:54:17.851  6406  6406 W art     : b66e2000-b66e3000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 13:54:17.851  6406  6406 W art     : b66e3000-b66f1000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:54:17.851  6406  6406 W art     : b66f1000-b66f2000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b66f2000-b66f3000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:54:17.851  6406  6406 W art     : b66f3000-b66f4000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:54:17.851  6406  6406 W art     : b66f4000-b66fd000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:54:17.851  6406  6406 W art     : b66fd000-b66fe000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:54:17.851  6406  6406 W art     : b66fe000-b66ff000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:54:17.851  6406  6406 W art     : b66ff000-b6765000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 13:54:17.851  6406  6406 W art     : b6765000-b6766000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6766000-b6768000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 13:54:17.851  6406  6406 W art     : b6768000-b6771000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 13:54:17.851  6406  6406 W art     : b6771000-b6774000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6774000-b680b000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 13:54:17.851  6406  6406 W art     : b680b000-b680d000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 13:54:17.851  6406  6406 W art     : b680d000-b680e000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 13:54:17.851  6406  6406 W art     : b680e000-b680f000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b680f000-b6b30000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 13:54:17.851  6406  6406 W art     : b6b30000-b6b31000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6b31000-b6b4c000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 13:54:17.851  6406  6406 W art     : b6b4c000-b6b50000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 13:54:17.851  6406  6406 W art     : b6b50000-b6b55000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6b55000-b6b5d000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:54:17.851  6406  6406 W art     : b6b5d000-b6b5e000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:54:17.851  6406  6406 W art     : b6b5e000-b6b5f000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:54:17.851  6406  6406 W art     : b6b5f000-b6b8d000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:54:17.851  6406  6406 W art     : b6b8d000-b6b8e000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6b8e000-b6b95000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:54:17.851  6406  6406 W art     : b6b95000-b6b96000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:54:17.851  6406  6406 W art     : b6b96000-b6bdc000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:54:17.851  6406  6406 W art     : b6bdc000-b6bdd000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6bdd000-b6be0000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:54:17.851  6406  6406 W art     : b6be0000-b6be1000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:54:17.851  6406  6406 W art     : b6be1000-b6bfc000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 13:54:17.851  6406  6406 W art     : b6bfc000-b6c00000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 13:54:17.851  6406  6406 W art     : b6c00000-b6c01000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 13:54:17.851  6406  6406 W art     : b6c01000-b6c4e000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 13:54:17.851  6406  6406 W art     : b6c4e000-b6c4f000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6c4f000-b6c5b000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 13:54:17.851  6406  6406 W art     : b6c5b000-b6c5c000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 13:54:17.851  6406  6406 W art     : b6c5c000-b6c69000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 13:54:17.851  6406  6406 W art     : b6c69000-b6c6a000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6c6a000-b6c6b000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 13:54:17.851  6406  6406 W art     : b6c6b000-b6c6c000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 13:54:17.851  6406  6406 W art     : b6c6c000-b6c74000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:54:17.851  6406  6406 W art     : b6c74000-b6c75000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6c75000-b6c76000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:54:17.851  6406  6406 W art     : b6c76000-b6c77000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:54:17.851  6406  6406 W art     : b6c77000-b6c7e000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:54:17.851  6406  6406 W art     : b6c7e000-b6c7f000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:54:17.851  6406  6406 W art     : b6c7f000-b6c80000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:54:17.851  6406  6406 W art     : b6c80000-b6c94000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 13:54:17.851  6406  6406 W art     : b6c94000-b6c96000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 13:54:17.851  6406  6406 W art     : b6c96000-b6c97000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 13:54:17.851  6406  6406 W art     : b6c97000-b6cbf000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:54:17.851  6406  6406 W art     : b6cbf000-b6cc1000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:54:17.851  6406  6406 W art     : b6cc1000-b6cc2000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:54:17.851  6406  6406 W art     : b6cc2000-b6cc5000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:54:17.851  6406  6406 W art     : b6cc5000-b6cc6000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:54:17.851  6406  6406 W art     : b6cc6000-b6cc7000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:54:17.851  6406  6406 W art     : b6cc7000-b6cd0000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:54:17.851  6406  6406 W art     : b6cd0000-b6cd1000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:54:17.851  6406  6406 W art     : b6cd1000-b6cd2000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:54:17.851  6406  6406 W art     : b6cd2000-b6cf2000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 13:54:17.851  6406  6406 W art     : b6cf2000-b6cf3000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 13:54:17.851  6406  6406 W art     : b6cf3000-b6cf4000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 13:54:17.851  6406  6406 W art     : b6cf4000-b6d67000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 13:54:17.851  6406  6406 W art     : b6d67000-b6d6b000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 13:54:17.851  6406  6406 W art     : b6d6b000-b6d6e000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 13:54:17.851  6406  6406 W art     : b6d6e000-b6d78000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6d78000-b6e00000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 13:54:17.851  6406  6406 W art     : b6e00000-b6e01000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6e01000-b6e05000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 13:54:17.851  6406  6406 W art     : b6e05000-b6e06000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 13:54:17.851  6406  6406 W art     : b6e06000-b6e07000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6e07000-b6e30000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:54:17.851  6406  6406 W art     : b6e30000-b6e31000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6e31000-b6e34000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:54:17.851  6406  6406 W art     : b6e34000-b6e35000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:54:17.851  6406  6406 W art     : b6e35000-b6f0f000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:54:17.851  6406  6406 W art     : b6f0f000-b6f16000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:54:17.851  6406  6406 W art     : b6f16000-b6f1e000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:54:17.851  6406  6406 W art     : b6f1e000-b6f1f000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6f1f000-b6f20000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:54:17.851  6406  6406 W art     : b6f20000-b6f21000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 13:54:17.851  6406  6406 W art     : b6f21000-b6f22000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.851  6406  6406 W art     : b6f22000-b6f25000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.851  6406  6406 W art     : b6f25000-b6f4a000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 13:54:17.851  6406  6406 W art     : b6f4a000-b6f4b000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6f4b000-b6f52000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 13:54:17.851  6406  6406 W art     : b6f52000-b6f53000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 13:54:17.851  6406  6406 W art     : b6f53000-b6f5a000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 13:54:17.851  6406  6406 W art     : b6f5a000-b6f5b000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 13:54:17.851  6406  6406 W art     : b6f5b000-b6f5c000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 13:54:17.851  6406  6406 W art     : b6f5c000-b6f5d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.851  6406  6406 W art     : b6f5d000-b6f75000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 13:54:17.851  6406  6406 W art     : b6f75000-b6f76000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6f76000-b6f77000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 13:54:17.851  6406  6406 W art     : b6f77000-b6f78000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 13:54:17.851  6406  6406 W art     : b6f78000-b6f86000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 13:54:17.851  6406  6406 W art     : b6f86000-b6f87000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6f87000-b6f88000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 13:54:17.851  6406  6406 W art     : b6f88000-b6f89000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 13:54:17.851  6406  6406 W art     : b6f89000-b6f8a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:54:17.851  6406  6406 W art     : b6f8a000-b6f8c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.851  6406  6406 W art     : b6f8c000-b6f8d000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.851  6406  6406 W art     : b6f8d000-b6f8e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:54:17.851  6406  6406 W art     : b6f8e000-b6f8f000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 13:54:17.851  6406  6406 W art     : b6f8f000-b6f90000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:17.851  6406  6406 W art     : b6f90000-b6fb0000 r--s 00000000 00:0b 7184       /dev/__properties__
08-23 13:54:17.851  6406  6406 W art     : b6fb0000-b6fb1000 r--p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6fb1000-b6fb2000 ---p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6fb2000-b6fb4000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 13:54:17.851  6406  6406 W art     : b6fb4000-b6fb5000 r-xp 00000000 00:00 0          [sigpage]
08-23 13:54:17.851  6406  6406 W art     : b6fb5000-b6fd0000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 13:54:17.851  6406  6406 W art     : b6fd0000-b6fd1000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 13:54:17.851  6406  6406 W art     : b6fd1000-b6fd3000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 13:54:17.851  6406  6406 W art     : b6fd3000-b6fd5000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : b6fd5000-b6fda000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 13:54:17.851  6406  6406 W art     : b6fda000-b6fdb000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 13:54:17.851  6406  6406 W art     : b6fdb000-b6fdc000 rw-p 00000000 00:00 0 
08-23 13:54:17.851  6406  6406 W art     : be92c000-be94d000 rw-p 00000000 00:00 0          [stack]
08-23 13:54:17.851  6406  6406 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 13:54:17.861  6508  6508 E Zygote  : v2
08-23 13:54:17.861  6508  6508 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:17.861  6508  6508 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:17.861  6508  6508 E Zygote  : accessInfo : 0
08-23 13:54:17.861  6508  6508 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-23 13:54:17.861  6495  6495 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-23 13:54:17.891  6406  6406 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 13:54:17.921   766  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-23 13:54:17.931  6406  6406 I Radio-JNI: register_android_hardware_Radio DONE
08-23 13:54:17.931  6508  6508 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:17.931  6508  6508 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:17.941  6406  6406 E AffinityControl: AffinityControl: registerfunction enter
08-23 13:54:17.961   766   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{14b91d8 3201:com.android.contacts/u0a19}
08-23 13:54:17.961  6508  6508 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-23 13:54:17.961  6406  6406 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 13:54:17.971   766  1730 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-23 13:54:17.971  6508  6508 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-23 13:54:17.981  6508  6508 D AASAservice: onCreate()
08-23 13:54:17.991   766  1730 D ActivityManager: mDVFSHelper.acquire()
08-23 13:54:17.991   766  1730 V WindowManager: addAppToken: AppWindowToken{8cbf1d5 token=Token{4d9968c ActivityRecord{6ae8fbf u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-23 13:54:18.001  6528  6528 E Zygote  : v2
08-23 13:54:18.001   766  1730 I ActivityManager: Start proc 6528:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-23 13:54:18.001  6528  6528 I libpersona: KNOX_SDCARD checking this for 10004
08-23 13:54:18.001  6528  6528 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:18.001   766  1730 D InputDispatcher: Focused application set to: xxxx
08-23 13:54:18.001  6528  6528 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:18.001  6528  6528 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:18.011   766   905 D SecWifiDisplayUtil: Metadata value : none
08-23 13:54:18.011  6528  6528 E Zygote  : accessInfo : 0
08-23 13:54:18.011  6528  6528 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-23 13:54:18.011   766   905 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6f1868d V.E...... R.....ID 0,0-0,0}
08-23 13:54:18.011   766  1730 D InputDispatcher: Focus left window: 4442
08-23 13:54:18.011   766   905 D ISSUE_DEBUG: InputChannelName : 7171853 Starting com.test.thalitest
08-23 13:54:18.011   766  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 13:54:18.011  6406  6406 D AndroidRuntime: Shutting down VM
08-23 13:54:18.021  4936  4936 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-23 13:54:18.021   766  2303 I ActivityManager: Start proc 6539:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-23 13:54:18.021  6539  6539 E Zygote  : v2
08-23 13:54:18.021  6539  6539 I libpersona: KNOX_SDCARD checking this for 10049
08-23 13:54:18.031  6539  6539 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:18.031  6539  6539 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:18.031  6539  6539 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:18.031   294   294 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, uhalitest
08-23 13:54:18.031  6539  6539 E Zygote  : accessInfo : 0
08-23 13:54:18.031  6539  6539 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-23 13:54:18.041   766   869 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{4167da2 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-23 13:54:18.041  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-23 13:54:18.051   766   905 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:766 uid:1000
08-23 13:54:18.051   766   905 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:54:18.051   766   905 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:766 uid:1000
08-23 13:54:18.051   766   905 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 13:54:18.051   766   905 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-23 13:54:18.051  6528  6528 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:18.051  6528  6528 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:18.061  6539  6539 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:18.061  6539  6539 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:18.061   766  1411 I ActivityManager: Killing 5585:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
08-23 13:54:18.071   766  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 13:54:18.071   766   779 V WindowOrientationListener: setCurrentAppOrientation :-1
08-23 13:54:18.071   766   779 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-23 13:54:18.071   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe82a364
08-23 13:54:18.081   766   905 V WindowStateAnimator: Finishing drawing window Window{7171853 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-23 13:54:18.081   766   905 W DisplayManagerService: Failed to notify process 5585 that displays changed, assuming it died.
08-23 13:54:18.081   766   905 W DisplayManagerService: android.os.DeadObjectException
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1832)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1616)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:187)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1760)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:158)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:54:18.081   766   905 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 13:54:18.101   766   779 D ActivityManager:  Launching com.test.thalitest, updated priority
08-23 13:54:18.111  4442  4442 V ActivityThread: updateVisibility : ActivityRecord{7a8e4a6 token=android.os.BinderProxy@c81a615 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-23 13:54:18.111  1687  1866 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-23 13:54:18.111  1687  1687 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-23 13:54:18.121   294   358 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
08-23 13:54:18.121   294   358 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
08-23 13:54:18.131   294   358 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
08-23 13:54:18.141   294  1506 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
08-23 13:54:18.141   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a3a4
08-23 13:54:18.151  6528  6528 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 13:54:18.151   766  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff0e6af 6539:com.android.mms/u0a49}
08-23 13:54:18.151   766   865 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-23 13:54:18.151   766  1733 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
08-23 13:54:18.161   766   869 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{7171853 u0 d0 Starting com.test.thalitest}
08-23 13:54:18.161  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-23 13:54:18.181   294   361 I SurfaceFlinger: id=14 Removed YUIInstallC (5/9)
08-23 13:54:18.181   294   358 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/9)
08-23 13:54:18.191   766  3426 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-23 13:54:18.191  4241  6525 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-23 13:54:18.201  2149  2164 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-23 13:54:18.201  1687  1687 V ActivityThread: updateVisibility : ActivityRecord{1480e9c token=android.os.BinderProxy@5682578 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 13:54:18.201  1687  1687 D Launcher: onTrimMemory. Level: 20
08-23 13:54:18.201  6539  6539 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-23 13:54:18.201  6528  6528 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 13:54:18.211  6528  6528 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 13:54:18.231  6528  6528 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-23 13:54:18.251  6528  6528 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 13:54:18.251  6528  6528 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 13:54:18.261  6539  6539 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-23 13:54:18.261  6539  6539 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-23 13:54:18.261  6528  6528 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 9753-9757)
,08-23 13:54:18.261  6528  6528 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 13:54:18.281  1811  6493 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 493 ms] updated apps [took 493 ms] 
,08-23 13:54:18.281  6528  6528 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f5c9625}
,08-23 13:54:18.281  6528  6528 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 13:54:18.281  6528  6528 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 13:54:18.291  6528  6555 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-23 13:54:18.291  6528  6528 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 13:54:18.301   766   776 I art     : Background partial concurrent mark sweep GC freed 148271(9MB) AllocSpace objects, 11(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.934ms total 169.622ms
,08-23 13:54:18.311  6539  6539 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-23 13:54:18.321  6539  6562 D Mms/ArtClassLoader: init before art third
,08-23 13:54:18.321  6539  6561 D Mms/ArtClassLoader: init before art second
,08-23 13:54:18.321  6528  6528 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 13:54:18.321  6528  6528 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 13:54:18.321  6528  6528 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 13:54:18.321  6528  6528 I Adreno-EGL: Local Branch: ss
08-23 13:54:18.321  6528  6528 I Adreno-EGL: Remote Branch: 
08-23 13:54:18.321  6528  6528 I Adreno-EGL: Local Patches: 
08-23 13:54:18.321  6528  6528 I Adreno-EGL: Reconstruct Branch: 
,08-23 13:54:18.321  6539  6560 D Mms/ArtClassLoader: init before art first
,08-23 13:54:18.331  6539  6539 D Mms/TelephonyPermission: start operation mode monitor
,08-23 13:54:18.331  6539  6539 D Mms/TelephonyPermission: User ID is null set current User Id
,08-23 13:54:18.331  6528  6528 D libEGL  : eglInitialize EGLDisplay = 0xbee18dac
,08-23 13:54:18.361  6539  6562 D Mms/ArtClassLoader: init [DONE] art
,08-23 13:54:18.361  6539  6539 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 13:54:18.361  6539  6539 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 13:54:18.371   766  1703 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-23 13:54:18.371   766  1703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-23 13:54:18.401  6539  6539 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-23 13:54:18.401  6539  6539 D Mms/TelephonyPermission: isDefault true
,08-23 13:54:18.401  6539  6539 D Mms/MmsApp: onCreate() com.android.mms
,08-23 13:54:18.421  6528  6528 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-23 13:54:18.431  6528  6528 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 13:54:18.431  6528  6528 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-23 13:54:18.431  6528  6528 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-23 13:54:18.431  6528  6528 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-23 13:54:18.441  6539  6539 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-23 13:54:18.441  6539  6539 D Mms/MmsApp: [start]    initCountryIso consume time = 134.272968
,08-23 13:54:18.451   766   779 D CountryDetector: The first listener is added
,08-23 13:54:18.451  6539  6539 D Mms/MmsApp: [end]    initCountryIso consume time = 6.225782
08-23 13:54:18.451  6539  6539 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.125938
,08-23 13:54:18.461  6539  6539 D Mms/MmsConfig: before partial update
,08-23 13:54:18.471  6528  6528 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-23 13:54:18.481  6528  6528 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 13:54:18.501  6539  6560 D Mms/ArtClassLoader: init [DONE] art
,08-23 13:54:18.511  6539  6539 D Mms/MmsConfig: Load Resize quality : 80
,08-23 13:54:18.521  6539  6561 D Mms/ArtClassLoader: init [DONE] art
,08-23 13:54:18.521  6539  6539 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 13:54:18.521  6539  6539 D EasySignUpManager_1.0.5: isAuth is false
08-23 13:54:18.521  6539  6539 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-23 13:54:18.521  6539  6539 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-23 13:54:18.521  6539  6539 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-23 13:54:18.521  6539  6539 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 13:54:18.521  6539  6539 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-23 13:54:18.521  6539  6539 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 13:54:18.521  6539  6539 D EasySignUpManager_1.0.5: isAuth is false
08-23 13:54:18.521  6539  6539 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-23 13:54:18.521  6539  6539 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-23 13:54:18.531  1667  2592 D TP/MmsSmsProvider: query, match:2117, calling pid = 6539, accessRestricted = false
,08-23 13:54:18.531  1667  2592 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.164 ms
,08-23 13:54:18.551  6539  6539 E CscParser: mps_code.dat does not exist
,08-23 13:54:18.551  6539  6539 E CscParser: customer_path =/system/csc/customer.xml
08-23 13:54:18.551  6539  6539 E CscParser: fileName + /system/csc/customer.xml
,08-23 13:54:18.551  6539  6539 E CscParser: mps_code.dat does not exist
,08-23 13:54:18.551  6539  6539 E CscParser: customer_path =/system/csc/customer.xml
08-23 13:54:18.551  6539  6539 E CscParser: fileName + /system/csc/customer.xml
,08-23 13:54:18.561  6539  6539 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-23 13:54:18.561  6539  6539 D Mms/MmsConfig:  enable multiwindow = true
08-23 13:54:18.561  6539  6539 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-23 13:54:18.561  6539  6539 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-23 13:54:18.561  6539  6539 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-23 13:54:18.561  6539  6539 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-23 13:54:18.571  6539  6539 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-23 13:54:18.571  6539  6539 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-23 13:54:18.571  6539  6539 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-23 13:54:18.571  6539  6539 D Mms/MmsConfig: [end]    init() consume time = 119.275625
,08-23 13:54:18.571  6539  6539 D Mms/Contact: [start]    init() consume time = 3.619583
,08-23 13:54:18.591  1667  1680 D TP/MmsSmsProvider: query, match:13, calling pid = 6539, accessRestricted = false
,08-23 13:54:18.591  1667  1680 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.703 ms
,08-23 13:54:18.591  6528  6528 D SecWifiDisplayUtil: Metadata value : none
,08-23 13:54:18.591  6528  6528 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1ff9d8b I.E...... R.....ID 0,0-0,0}
08-23 13:54:18.601  6528  6588 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-23 13:54:18.601   766  1730 D ISSUE_DEBUG: InputChannelName : 6c5b908 com.test.thalitest/com.test.thalitest.MainActivity
08-23 13:54:18.601   766  1703 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-23 13:54:18.601   766  1703 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 13:54:18.601   766   766 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 13:54:18.601   766   766 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-23 13:54:18.601  6539  6539 D Mms/Contact: [end]    init consume time = 31.187395
,08-23 13:54:18.621  6528  6528 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6528
,08-23 13:54:18.631  6539  6590 D Mms/DraftCache: [start]    rebuildCache consume time = 21.912709
,08-23 13:54:18.631   766  1320 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6528 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:54:18.631   766  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-23 13:54:18.631  6539  6539 D Mms:transaction: roaming -> false (slotId = 0)
08-23 13:54:18.631  6539  6539 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 13:54:18.631  6539  6539 D Mms:transaction: auto download without roaming -> true
08-23 13:54:18.631  6539  6539 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-23 13:54:18.631  6539  6539 D Mms:transaction: roaming -> false (slotId = 1)
08-23 13:54:18.631  6539  6539 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-23 13:54:18.631  6539  6539 D Mms:transaction: auto download without roaming -> true
08-23 13:54:18.631  6539  6539 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-23 13:54:18.631  6539  6539 D Mms:transaction: auto download during roaming secondary -> false
08-23 13:54:18.631  6539  6539 D Mms:transaction: mAutoDownload ------> true
08-23 13:54:18.631   766  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-23 13:54:18.631   766  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-23 13:54:18.631   766  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:54:18.631   766  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:54:18.631   766  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:54:18.631   766  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-23 13:54:18.631   766  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:54:18.631   766  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-23 13:54:18.631   766  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:54:18.641  6528  6528 D SecWifiDisplayUtil: Metadata value : none
,08-23 13:54:18.651  6528  6555 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-23 13:54:18.661   294   294 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,08-23 13:54:18.661  1667  1679 D TP/MmsSmsProvider: query, match:12, calling pid = 6539, accessRestricted = false
,08-23 13:54:18.661  1667  1679 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.236 ms
,08-23 13:54:18.661  6539  6590 D Mms/DraftCache: [end]    rebuildCache consume time = 35.990469
,08-23 13:54:18.671   766  2310 D InputDispatcher: Focus entered window: 6528
,08-23 13:54:18.671  6528  6588 D libEGL  : eglInitialize EGLDisplay = 0x9cb797c4
,08-23 13:54:18.671   766   905 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:766 uid:1000
08-23 13:54:18.671  6528  6588 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 13:54:18.671   766   905 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:54:18.671   766   905 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:766 uid:1000
08-23 13:54:18.671   766   905 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 13:54:18.691  6539  6539 D ComposerPerformance: 1471953258703 ms / [DONE] Composer constructor
,08-23 13:54:18.701  6539  6539 D CII     : Log Level [5]
08-23 13:54:18.701  6539  6539 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-23 13:54:18.701  6539  6594 D Mms/Conversation: [start]    init() consume time = 35.366979
,08-23 13:54:18.701  1667  1680 D TP/MmsSmsProvider: delete, match:1, calling pid = 6539
08-23 13:54:18.701  1667  1680 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-23 13:54:18.701  1667  1680 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-23 13:54:18.701  1667  1680 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-23 13:54:18.701  1667  1680 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-23 13:54:18.701  1667  1680 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-23 13:54:18.711  6539  6539 I Mms/ReservationManager: ReservationManager()
,08-23 13:54:18.711  6539  6539 I Mms/ReservationManager: resetAfterConnected()
,08-23 13:54:18.711  1667  1680 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-23 13:54:18.721  1667  1916 D TP/MmsSmsProvider: query, match:7, calling pid = 6539, accessRestricted = false
,08-23 13:54:18.721  1667  1916 D TP/MmsSmsProvider: query, match 7:Elapsed time : 4.890 ms
,08-23 13:54:18.731  6539  6539 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-23 13:54:18.731  6528  6528 V ActivityThread: updateVisibility : ActivityRecord{f8687b2 token=android.os.BinderProxy@f62675a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 13:54:18.731  1667  1680 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-23 13:54:18.731  1667  1680 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-23 13:54:18.741  1667  1680 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,08-23 13:54:18.741  1667  1680 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 17.675 ms
08-23 13:54:18.741  1667  1680 D TP/MmsSmsProvider: need read changed broadcast:false
,08-23 13:54:18.741  6539  6594 D Mms/Conversation: [end]    init consume time = 38.25724
,08-23 13:54:18.741  6539  6594 D Mms/MessagingNotification: [start]    init() consume time = 3.84526
,08-23 13:54:18.741  6539  6594 D Mms/MessagingNotification: [end]    init consume time = 1.52151
,08-23 13:54:18.741  6528  6528 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-23 13:54:18.741  6528  6528 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-23 13:54:18.751  1667  2592 D TP/MmsSmsProvider: query, match:0, calling pid = 6539, accessRestricted = false
08-23 13:54:18.751  1667  2592 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-23 13:54:18.751  1667  2592 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.148 ms
,08-23 13:54:18.761  6539  6539 D Mms/MmsApp: [end]    onCreate() consume time = 14.898438
,08-23 13:54:18.761  6539  6539 D Mms/MmsApp: [end]    onCreate() consume time = 0.296302
,08-23 13:54:18.761  6539  6595 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 6.588802
,08-23 13:54:18.771  6204  6216 D BadgeProvider: query, [selection] : package=?
,08-23 13:54:18.771  6539  6539 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-23 13:54:18.771  6539  6539 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-23 13:54:18.771  6539  6539 D Mms:transaction: roaming -> false (slotId = 0)
08-23 13:54:18.771  6539  6539 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 13:54:18.771  6539  6539 D Mms:transaction: auto download without roaming -> true
08-23 13:54:18.771  6539  6539 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-23 13:54:18.771  6539  6539 D Mms:transaction: mAutoDownload ------> true
,08-23 13:54:18.771  6539  6596 D Mms/Synchronizer: [start]    doSync consume time = 7.552396
,08-23 13:54:18.771   766  1703 V WindowStateAnimator: Finishing drawing window Window{6c5b908 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-23 13:54:18.781  6528  6528 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-23 13:54:18.781   766  1733 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 13:54:18.781  6598  6598 E Zygote  : v2
08-23 13:54:18.781  6598  6598 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:54:18.781  6598  6598 I libpersona: KNOX_SDCARD not a persona
,08-23 13:54:18.781  6598  6598 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:18.781  6598  6598 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:18.791   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe82a364
08-23 13:54:18.791  6598  6598 E Zygote  : accessInfo : 0
,08-23 13:54:18.791   766  2310 I ActivityManager: Start proc 6598:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-23 13:54:18.801  1667  1679 D TP/MmsSmsProvider: query, match:400, calling pid = 6539, accessRestricted = false
,08-23 13:54:18.801   766  2310 I ActivityManager: Killing 4056:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
,08-23 13:54:18.801   766   905 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 13:54:18.801  6528  6528 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-23 13:54:18.801   766   905 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +671ms (total +810ms)
08-23 13:54:18.801  6528  6528 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f62675a time:100297
08-23 13:54:18.801   766   905 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6ae8fbf u0 com.test.thalitest/.MainActivity t168} time:100298
08-23 13:54:18.801   766   905 D ActivityManager: mDVFSHelper.release()
08-23 13:54:18.801   766   766 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 13:54:18.811   766   766 I KnoxTimeoutHandler: SD activityfalse
08-23 13:54:18.811   766   905 D ViewRootImpl: #3 mView = null
08-23 13:54:18.811   294   358 I SurfaceFlinger: id=16 Removed uhalitest (7/9)
08-23 13:54:18.811   294  4869 I SurfaceFlinger: id=16 Removed uhalitest (-2/9)
08-23 13:54:18.811  6528  6610 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:54:18.811  6528  6610 D libEGL  : eglInitialize EGLDisplay = 0x9b4503ec
,08-23 13:54:18.821   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a3a4
,08-23 13:54:18.821  1667  1680 D TP/MmsSmsProvider: update, match:300, calling pid = 6539
08-23 13:54:18.821  1667  1680 V TP/MmsSmsProvider: syncDBData start
,08-23 13:54:18.821  1667  1680 V TP/MmsSmsProvider: syncDBData sms end
08-23 13:54:18.821  1667  1680 V TP/MmsSmsProvider: syncDBData mms end
08-23 13:54:18.831  1667  1680 V TP/MmsSmsProvider: syncDBData end
08-23 13:54:18.831  1667  1680 D TP/MmsSmsProvider: update, match 300:Elapsed time : 5.224 ms
,08-23 13:54:18.831  6539  6594 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-23 13:54:18.831  6598  6598 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:54:18.831  6598  6598 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:18.841   766  1730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{703bc11 6598:com.samsung.android.bbc.bbcagent/1000}
,08-23 13:54:18.851   766  1702 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-23 13:54:18.851  1667  1916 D TP/SmsProvider: query,matched:26, calling pid = 6539
,08-23 13:54:18.861  1667  1916 D TP/SmsProvider: query, match 26:Elapsed time : 1.294 ms
,08-23 13:54:18.861  6598  6598 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-23 13:54:18.861  6539  6595 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 92.165416
,08-23 13:54:18.881  6528  6528 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6528
,08-23 13:54:18.881  1667  2592 D TP/MmsSmsProvider: query, match:6, calling pid = 6539, accessRestricted = false
,08-23 13:54:18.881  1667  2592 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.102 ms
,08-23 13:54:18.881  6539  6596 D Mms/Synchronizer: [end]    doSync consume time = 14.227292
,08-23 13:54:18.901  6598  6598 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-23 13:54:18.911   766  1702 I ActivityManager: Start proc 6616:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-23 13:54:18.911  6616  6616 E Zygote  : v2
,08-23 13:54:18.911  6616  6616 I libpersona: KNOX_SDCARD checking this for 10024
08-23 13:54:18.911  6616  6616 I libpersona: KNOX_SDCARD not a persona
,08-23 13:54:18.911  6616  6616 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:18.911  6616  6616 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:18.911  6616  6616 E Zygote  : accessInfo : 0
,08-23 13:54:18.911  6616  6616 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-23 13:54:18.941  6616  6616 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:18.941  6616  6616 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:18.951  6629  6629 E Zygote  : v2
08-23 13:54:18.951  6629  6629 I libpersona: KNOX_SDCARD checking this for 10097
08-23 13:54:18.951  6629  6629 I libpersona: KNOX_SDCARD not a persona
,08-23 13:54:18.951   766  1701 I ActivityManager: Start proc 6629:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-23 13:54:18.961   766  1323 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 13:54:18.961  6629  6629 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:18.961  6629  6629 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:18.961  6629  6629 E Zygote  : accessInfo : 0
08-23 13:54:18.961  6629  6629 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
08-23 13:54:18.961   766  1700 I ActivityManager: Killing 5183:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-23 13:54:18.961   766  1700 I ActivityManager: Killing 5286:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-23 13:54:18.971   766  1323 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 13:54:18.981  6616  6616 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-23 13:54:18.991  6629  6629 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:18.991  6629  6629 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:19.011   766  2310 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-23 13:54:19.021   766  2303 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60a7176 6629:com.google.android.apps.docs/u0a97}
,08-23 13:54:19.021   766  1700 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-23 13:54:19.021  6616  6616 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-23 13:54:19.031  6629  6629 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 13:54:19.051  6629  6629 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-23 13:54:19.061  6528  6528 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:54:19.061  6616  6616 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-23 13:54:19.071  6539  6594 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-23 13:54:19.101  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-23 13:54:19.101  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-23 13:54:19.101  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-23 13:54:19.101  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-23 13:54:19.101  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-23 13:54:19.101  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-23 13:54:19.111  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-23 13:54:19.111  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-23 13:54:19.111  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-23 13:54:19.111  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-23 13:54:19.111  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-23 13:54:19.111  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-23 13:54:19.111  6616  6616 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-23 13:54:19.161   766  3427 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-23 13:54:19.181  6528  6642 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1696073424
,08-23 13:54:19.181  6528  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:54:19.181  6528  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:54:19.181  6528  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:54:19.181  6528  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:54:19.181  6528  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 13:54:19.181  6528  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b247198 added. We now have 1 listener(s)
,08-23 13:54:19.191  6528  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-23 13:54:19.191  6528  6642 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-23 13:54:19.191  6528  6642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 13:54:19.191  6528  6642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 13:54:19.191  6528  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c1857 added. We now have 1 listener(s)
08-23 13:54:19.191  6528  6642 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 13:54:19.191  6528  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 13:54:19.191  6528  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-23 13:54:19.201  6528  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 13:54:19.201  6528  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 13:54:19.201  6528  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 13:54:19.201  6528  6642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 13:54:19.201  6528  6642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-23 13:54:19.211  6528  6642 D BluetoothAdapter: STATE_ON
,08-23 13:54:19.211  6528  6642 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 13:54:19.211  6528  6642 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:54:19.211  6528  6642 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:54:19.211  6528  6642 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 13:54:19.211  6528  6642 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:54:19.211  6528  6642 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:54:19.211  6528  6642 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:54:19.211  6528  6642 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:54:19.211  6528  6642 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:54:19.211  6528  6642 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-23 13:54:19.211  6528  6642 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 13:54:19.211  6528  6642 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 13:54:19.211  6528  6528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:54:19.211  6528  6528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:54:19.231  6528  6528 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:54:19.271  4241  4981 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-23 13:54:19.301   766  3455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 13:54:19.321  4241  4981 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-23 13:54:19.391  6629  6646 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-23 13:54:19.391  6629  6646 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 13:54:19.391  6629  6646 I GAv4    :   adb logcat -s GAv4
,08-23 13:54:19.421  6629  6646 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 13:54:19.431   766  1411 V AlarmManager:  remove PendingIntent] PendingIntent{502837c: PendingIntentRecord{409f405 com.google.android.apps.docs broadcastIntent}}
,08-23 13:54:19.431  6629  6646 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 13:54:19.431   766  6300 I HarmonyEASService: Updating for all 1
,08-23 13:54:19.431  6629  6646 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 13:54:19.441  6629  6652 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 13:54:19.471  4241  4981 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-23 13:54:19.551  6629  6629 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-23 13:54:19.551  6629  6629 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-23 13:54:19.571  6629  6646 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-23 13:54:19.571  6629  6646 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-23 13:54:19.571  6629  6646 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-23 13:54:19.571  6629  6646 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-23 13:54:19.611  1451  1451 D Recents : onTaskStackChanged
,08-23 13:54:19.611  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 13:54:19.631  6658  6658 E Zygote  : v2
08-23 13:54:19.631  6658  6658 I libpersona: KNOX_SDCARD checking this for 10098
08-23 13:54:19.631  6658  6658 I libpersona: KNOX_SDCARD not a persona
,08-23 13:54:19.631  6658  6658 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:19.631  6658  6658 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:19.631   766  2306 I ActivityManager: Start proc 6658:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-23 13:54:19.631  6658  6658 E Zygote  : accessInfo : 0
08-23 13:54:19.631  6658  6658 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-23 13:54:19.631   766  2306 I ActivityManager: Killing 5308:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-23 13:54:19.651   766  2307 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-23 13:54:19.661  6658  6658 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:19.671  6658  6658 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:19.671   766  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{93acb81 6658:com.sec.android.automotive.drivelink/u0a98}
,08-23 13:54:19.691  6658  6658 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 13:54:19.691  2075  2075 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:54:19.691  2075  2075 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:54:19.711  6658  6658 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-23 13:54:19.731  2075  2075 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:54:19.741  6658  6658 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 13:54:19.751   766  1702 V AlarmManager:  remove PendingIntent] PendingIntent{25469b9: PendingIntentRecord{43d91fe com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 13:54:19.761  6658  6674 I GMPM    : App measurement is starting up
,08-23 13:54:19.761  6658  6658 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-23 13:54:19.761  6658  6674 E GMPM    : getGoogleAppId failed with status: 10
,08-23 13:54:19.771  6658  6674 E GMPM    : Uploading is not possible. App measurement disabled
,08-23 13:54:19.771   766   778 V AlarmManager:  remove PendingIntent] PendingIntent{926bd5f: PendingIntentRecord{43d91fe com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 13:54:19.791  6629  6647 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 13:54:19.791  6658  6658 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-23 13:54:19.791  6658  6658 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-23 13:54:19.851   766   778 I ActivityManager: Start proc 6680:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-23 13:54:19.851   766  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-23 13:54:19.851  6680  6680 E Zygote  : v2
08-23 13:54:19.851  6680  6680 I libpersona: KNOX_SDCARD checking this for 10032
08-23 13:54:19.851  6680  6680 I libpersona: KNOX_SDCARD not a persona
,08-23 13:54:19.851  6680  6680 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:19.851  6680  6680 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:19.851  6680  6680 E Zygote  : accessInfo : 0
,08-23 13:54:19.851  6680  6680 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-23 13:54:19.851  6629  6647 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-23 13:54:19.871  6629  6647 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-23 13:54:19.871  6629  6647 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-23 13:54:19.881  6629  6647 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 13:54:19.891  6680  6680 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:19.891  6680  6680 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:19.901   766  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-23 13:54:19.911  6680  6680 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-23 13:54:19.911  6629  6647 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 13:54:19.921  6680  6680 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-23 13:54:20.011  6658  6658 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-23 13:54:20.021  6658  6658 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-23 13:54:20.021  6658  6658 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-23 13:54:20.051  6658  6658 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Aug 23 13:54:20 GMT+02:00 2016
,08-23 13:54:20.061  6658  6658 D DialogFlow: initQueue()
,08-23 13:54:20.061  6680  6680 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-23 13:54:20.061  6694  6694 E Zygote  : v2
08-23 13:54:20.061  6694  6694 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:54:20.061  6694  6694 I libpersona: KNOX_SDCARD not a persona
,08-23 13:54:20.061  6694  6694 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:20.061  6694  6694 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:20.061   766  2310 I ActivityManager: Start proc 6694:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-23 13:54:20.061  6694  6694 E Zygote  : accessInfo : 0
,08-23 13:54:20.071   766  2310 I ActivityManager: Killing 5260:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-23 13:54:20.071   766  2310 I ActivityManager: Killing 5517:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-23 13:54:20.111  6694  6694 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:20.111  6694  6694 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:20.121  6528  6643 W jxcore-log: Initializing JXcore engine
08-23 13:54:20.121  6528  6643 W jxcore-log: JXcore engine is ready
,08-23 13:54:20.121   766   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{57fe2d6 6694:com.samsung.android.app.filterinstaller/1000}
,08-23 13:54:20.121   766  2306 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-23 13:54:20.131   766  1702 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-23 13:54:20.141  6694  6694 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-23 13:54:20.141  6680  6680 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-23 13:54:20.151  6694  6694 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-23 13:54:20.161  6694  6694 E FilterPackageIntentReceiver: This package is not a effect filter
,08-23 13:54:20.171  6710  6710 E Zygote  : v2
,08-23 13:54:20.171  6710  6710 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:54:20.171  6710  6710 I libpersona: KNOX_SDCARD not a persona
,08-23 13:54:20.171  6710  6710 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:20.171   766  1701 I ActivityManager: Start proc 6710:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-23 13:54:20.171  6710  6710 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:20.171  6710  6710 E Zygote  : accessInfo : 0
,08-23 13:54:20.171   766  1701 I ActivityManager: Killing 5674:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-23 13:54:20.171  2218  2218 E audit   : type=1400 msg=audit(1471953260.171:287): avc:  denied  { ioctl } for  pid=6643 comm="Thread-915" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 13:54:20.171  2218  2218 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:20.171  2218  2218 E audit   : type=1300 msg=audit(1471953260.171:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ad523c8 items=0 ppid=349 ppcomm=main pid=6643 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-915" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
,08-23 13:54:20.171  2218  2218 E audit   : type=1327 msg=audit(1471953260.171:287): proctitle="com.test.thalitest"
08-23 13:54:20.171  2218  2218 E audit   : type=1320 msg=audit(1471953260.171:287): 
08-23 13:54:20.171  2218  2218 E audit   : type=1400 msg=audit(1471953260.171:288): avc:  denied  { ioctl } for  pid=6643 comm="Thread-915" path="socket:[40474]" dev="sockfs" ino=40474 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-23 13:54:20.171  2218  2218 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:20.171  2218  2218 E audit   : type=1300 msg=audit(1471953260.171:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=3 a3=9ad523c8 items=0 ppid=349 ppcomm=main pid=6643 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-915" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 13:54:20.171  2218  2218 E audit   : type=1327 msg=audit(1471953260.171:288): proctitle="com.test.thalitest"
08-23 13:54:20.171  2218  2218 E audit   : type=1320 msg=audit(1471953260.171:288): 
,08-23 13:54:20.191  6528  6643 W jxcore-log: Starting JXcore engine
,08-23 13:54:20.191   766  1730 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-23 13:54:20.201   766  1733 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-23 13:54:20.201  6710  6710 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:20.201  6710  6710 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:20.211   766  2303 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{614f957 6710:com.samsung.helphub/1000}
,08-23 13:54:20.221  6710  6710 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-23 13:54:20.221  6680  6680 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-23 13:54:20.221  6680  6680 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-23 13:54:20.231  6680  6680 D DialogFlow: initQueue()
,08-23 13:54:20.231  6710  6710 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-23 13:54:20.281  6722  6722 E Zygote  : v2
08-23 13:54:20.281  6722  6722 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:54:20.281  6722  6722 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:20.281   766  2310 I ActivityManager: Start proc 6722:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-23 13:54:20.281   766  2310 I ActivityManager: Killing 5425:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-23 13:54:20.281  6722  6722 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:20.281  6722  6722 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:20.281  6722  6722 E Zygote  : accessInfo : 0
,08-23 13:54:20.281  6528  6643 W jxcore-log: Platform android
08-23 13:54:20.281  6528  6643 W jxcore-log: 
08-23 13:54:20.281  6528  6643 W jxcore-log: Process ARCH arm
08-23 13:54:20.281  6528  6643 W jxcore-log: 
,08-23 13:54:20.291   766   778 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-23 13:54:20.311  6722  6722 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:54:20.311  6722  6722 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:20.321   766  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f076ae 6722:com.samsung.android.app.mirrorlink/1000}
,08-23 13:54:20.321  6722  6722 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-23 13:54:20.331  6722  6722 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-23 13:54:20.371  6722  6722 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-23 13:54:20.371  6722  6722 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-23 13:54:20.381   766  1411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{59aa331 5815:com.google.android.apps.plus/u0a134}
,08-23 13:54:20.391   766  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{59aa331 5815:com.google.android.apps.plus/u0a134}
,08-23 13:54:20.401   766  2307 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{59aa331 5815:com.google.android.apps.plus/u0a134}
,08-23 13:54:20.431   766  1700 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-23 13:54:20.441   766  1425 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-23 13:54:20.441   766  2310 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-23 13:54:20.441   766  1411 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-23 13:54:20.451   766  2307 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-23 13:54:20.451   766   779 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-23 13:54:20.451   766  2303 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-23 13:54:20.451   766  1730 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-23 13:54:20.471  6736  6736 E Zygote  : v2
08-23 13:54:20.471  6736  6736 I libpersona: KNOX_SDCARD checking this for 10165
08-23 13:54:20.471  6736  6736 I libpersona: KNOX_SDCARD not a persona
,08-23 13:54:20.471  6736  6736 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:20.471  6736  6736 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:20.471   766  1425 I ActivityManager: Start proc 6736:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-23 13:54:20.481  6736  6736 E Zygote  : accessInfo : 0
08-23 13:54:20.481  6736  6736 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-23 13:54:20.481   766  2310 I ActivityManager: Killing 5713:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-23 13:54:20.501   766  1411 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-23 13:54:20.501  6528  6643 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:54:20.501  6528  6643 I jxcore-log: 
,08-23 13:54:20.501  6528  6643 W jxcore-log: JXcore engine is started
08-23 13:54:20.501  6736  6736 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:20.501  6736  6736 D ActivityThread: Added TimaKeyStore provider
08-23 13:54:20.501  6528  6642 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 13:54:20.501  6528  6528 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 13:54:20.521   766   778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{425d8e5 6736:com.sec.kidsplat.installer/u0a165}
,08-23 13:54:20.521  6736  6736 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-23 13:54:20.531  6528  6643 E jxcore  : Error!: missing name after . operator
08-23 13:54:20.531  6528  6643 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:54:20.531  6528  6528 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 13:54:20.531  6528  6528 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
08-23 13:54:20.541   766  1425 D InputDispatcher: Focused application set to: xxxx
08-23 13:54:20.541  6736  6736 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
08-23 13:54:20.541   766  1425 I ActivityManager: Killing 5699:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
08-23 13:54:20.551  6528  6528 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 13:54:20.551  6528  6528 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 13:54:20.551  6528  6528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:54:20.551  6528  6528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:54:20.551  6528  6528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:54:20.551  6528  6528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:54:20.551  6528  6528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b247198 removed from the list
08-23 13:54:20.551  6528  6528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:54:20.551  6528  6528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c1857 removed from the list
08-23 13:54:20.551  6528  6528 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:54:20.551  6528  6528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 13:54:20.561   766  2303 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{425d8e5 6736:com.sec.kidsplat.installer/u0a165}
08-23 13:54:20.571   766  1730 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-23 13:54:20.571  6528  6528 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-23 13:54:20.571  6528  6528 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
08-23 13:54:20.571  6736  6736 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
08-23 13:54:20.581  6528  6528 D ViewRootImpl: #3 mView = null
08-23 13:54:20.581   294  1506 I SurfaceFlinger: id=17 Removed NainActivit (6/8)
,08-23 13:54:20.581   294   358 I SurfaceFlinger: id=17 Removed NainActivit (-2/8)
,08-23 13:54:20.581   766  2306 D InputDispatcher: Focus left window: 6528
,08-23 13:54:20.591  6748  6748 E Zygote  : v2
08-23 13:54:20.591  6748  6748 I libpersona: KNOX_SDCARD checking this for 10142
08-23 13:54:20.591  6748  6748 E Zygote  : isSdpEnabledProcess - SDP enabled
08-23 13:54:20.591  6748  6748 I libpersona: KNOX_SDCARD not a persona
,08-23 13:54:20.591   766  2310 I ActivityManager: Start proc 6748:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-23 13:54:20.591  6748  6748 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:20.591  6748  6748 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:20.591   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a3a4
,08-23 13:54:20.591   766  2310 I ActivityManager: Killing 5799:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
08-23 13:54:20.591  6748  6748 E Zygote  : accessInfo : 64
08-23 13:54:20.591  6748  6748 E Zygote  : isSdpEnabledProcess - SDP enabled
08-23 13:54:20.591  6748  6748 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-23 13:54:20.591  6748  6748 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-23 13:54:20.591   766   905 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:766 uid:1000
08-23 13:54:20.591   766   905 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:54:20.591   766   905 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:766 uid:1000
08-23 13:54:20.591   766   905 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 13:54:20.601  6528  6528 D cr_Ime  : [ImeAdapter.java:587] detach
08-23 13:54:20.601   766  2310 D ActivityManager: mDVFSHelper.acquire()
,08-23 13:54:20.601  6528  6528 E ViewRootImpl: sendUserActionEvent() mView == null
,08-23 13:54:20.611   766   865 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.wssyncmldm
,08-23 13:54:20.611   766  2310 V WindowOrientationListener: setCurrentAppOrientation :1
08-23 13:54:20.611   766  2310 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-23 13:54:20.611   766  1411 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-23 13:54:20.621  6748  6748 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:54:20.621  6748  6748 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:20.621  1687  1687 D Launcher: onRestart, Launcher: 82145185
,08-23 13:54:20.631   766  1700 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2514fba 6748:com.sec.android.app.sbrowser/u0a142}
,08-23 13:54:20.631  1687  1687 D Launcher: onStart, Launcher: 82145185
,08-23 13:54:20.631  4442  4442 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(754/onResume)] 
,08-23 13:54:20.641  1687  1687 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,08-23 13:54:20.641  1687  1687 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-23 13:54:20.641  1687  1687 D Launcher.HomeView: onStart
,08-23 13:54:20.661  6748  6748 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 13:54:20.661  1687  1687 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
08-23 13:54:20.661   766  2303 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-23 13:54:20.661   766  2303 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-23 13:54:20.661   766   766 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 13:54:20.661  4442  4442 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(747/onPause)] 
,08-23 13:54:20.661   766   766 I KnoxTimeoutHandler: Shared devices show user statefalse
08-23 13:54:20.661   766   766 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
08-23 13:54:20.661  1687  1687 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,08-23 13:54:20.661  2149  2163 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
,08-23 13:54:20.661  1687  1687 V ActivityThread: updateVisibility : ActivityRecord{1480e9c token=android.os.BinderProxy@5682578 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-23 13:54:20.671   294   294 I SurfaceFlinger: id=18 createSurf (145x145),1 flag=4, YUIInstallC
,08-23 13:54:20.671   766   869 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6a76e5d u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}
,08-23 13:54:20.671   766  1411 D InputDispatcher: Focus entered window: 4442
,08-23 13:54:20.671   294   294 I SurfaceFlinger: id=19 createSurf (1080x1920),1 flag=4, Mauncher
,08-23 13:54:20.681   294   294 I SurfaceFlinger: id=20 createSurf (1146x1992),1 flag=4, YUIInstallC
,08-23 13:54:20.681   766   869 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{e964707 u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}
,08-23 13:54:20.681  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-23 13:54:20.681   766   778 D InputDispatcher: Focus left window: 4442
,08-23 13:54:20.691   766   778 D InputDispatcher: Focus entered window: 4442
,08-23 13:54:20.691   766   905 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:766 uid:1000
,08-23 13:54:20.691   766   905 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:54:20.691   766   905 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:766 uid:1000
08-23 13:54:20.691   766   905 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 13:54:20.691   766   905 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:766 uid:1000
08-23 13:54:20.691   766   905 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:54:20.691   766   905 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:766 uid:1000
,08-23 13:54:20.691   766   905 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 13:54:20.701   344   406 I ThermalEngine: Sensor:tsens_tz_sensor5:85000 mC
08-23 13:54:20.701   344   422 I ThermalEngine: Sensor:tsens_tz_sensor5:85000 mC
08-23 13:54:20.701   344   422 I ThermalEngine: TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm raised 1 at 85.0 degC
,08-23 13:54:20.701   344   422 I ThermalEngine: ACTION: OPT_CURR_REQ 1
,08-23 13:54:20.711  4442  4442 V ActivityThread: updateVisibility : ActivityRecord{7a8e4a6 token=android.os.BinderProxy@c81a615 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-23 13:54:20.711   766  2306 V WindowStateAnimator: Finishing drawing window Window{6a76e5d u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: mDrawState=DRAW_PENDING
,08-23 13:54:20.721  6748  6748 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-23 13:54:20.721   294   358 I SurfaceFlinger: id=20 Removed YUIInstallC (8/10)
,08-23 13:54:20.721   294   361 I SurfaceFlinger: id=20 Removed YUIInstallC (-2/10)
,08-23 13:54:20.721   766   869 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6a76e5d u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}
08-23 13:54:20.721  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
,08-23 13:54:20.721   766  1700 D InputDispatcher: Focus left window: 4442
,08-23 13:54:20.721   766  1700 D InputDispatcher: Focus entered window: 4442
,08-23 13:54:20.731   766   905 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:766 uid:1000
08-23 13:54:20.731   766   905 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:54:20.731   766   905 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:766 uid:1000
08-23 13:54:20.731   766   905 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 13:54:20.731   766   905 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-23 13:54:20.731   766  1320 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 13:54:20.731   766   766 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 13:54:20.731   766   766 I KnoxTimeoutHandler: SD activityfalse
08-23 13:54:20.731   766   905 D ActivityManager: mDVFSHelper.release()
08-23 13:54:20.731   766   905 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5825de9 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity t167} time:102225
,08-23 13:54:20.751   766  1730 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 13:54:20.751   766  1730 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@6c5ce6b attribute=null, token = android.os.BinderProxy@60a9034
,08-23 13:54:20.751   766  1730 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVis) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,08-23 13:54:20.751  4442  4442 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c81a615 time:102247
,08-23 13:54:20.761  1928  1928 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-23 13:54:20.761  6748  6748 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 13:54:20.771  6748  6748 D ManifestProvider: onCreate()
,08-23 13:54:20.781  6748  6748 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-23 13:54:20.781  6748  6748 I SBrowserUtils: getSystemProperty of country_code : Poland
08-23 13:54:20.781  6748  6748 I SBrowserUtils: getSystemProperty of country_code : Poland
08-23 13:54:20.781  6748  6748 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-23 13:54:20.791  6748  6748 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-23 13:54:20.791  6748  6748 D [MM]MHDataBaseProvider: onCreate()
,08-23 13:54:20.801  6539  6539 I Mms/MmsApp:  start initViewCache mms
,08-23 13:54:20.811  6748  6748 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@539c5c6)
,08-23 13:54:20.831   766  1730 V WindowStateAnimator: Finishing drawing window Window{4167da2 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-23 13:54:20.841   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe82a364
,08-23 13:54:20.841  1687  1687 D Launcher.HomeView: onStop
,08-23 13:54:20.871   766   905 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 13:54:20.871   766   766 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 13:54:20.871   766   905 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f47caa0 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t165} time:102362
08-23 13:54:20.871   766   766 I KnoxTimeoutHandler: SD activityfalse
,08-23 13:54:20.891   766  2310 I ActivityManager: Killing 5910:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-23 13:54:20.891   766  2310 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef7e081 2075:com.google.android.gms.persistent/u0a11}
,08-23 13:54:20.901   344   408 I ThermalEngine: Sensor:tsens_tz_sensor6:87000 mC
,08-23 13:54:20.901   344   422 I ThermalEngine: Sensor:tsens_tz_sensor6:87000 mC
08-23 13:54:20.901   344   422 I ThermalEngine: TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm raised 1 at 87.0 degC
,08-23 13:54:20.911   766  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dbb9458 4241:com.google.android.gms/u0a11}
,08-23 13:54:20.911  4241  6770 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-23 13:54:20.911  4241  6771 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:54:20.921  4241  6771 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:54:20.931   766   779 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-23 13:54:20.941  4241  4241 D AsyncTaskServiceImpl: Submit a task: nzm
,08-23 13:54:20.941  4241  6771 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:54:20.951  4241  6771 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:54:20.961   766  1640 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef7e081 2075:com.google.android.gms.persistent/u0a11}
,08-23 13:54:20.961   766   776 I art     : Background partial concurrent mark sweep GC freed 28715(1817KB) AllocSpace objects, 1(20KB) LOS objects, 27% free, 42MB/58MB, paused 1.984ms total 117.847ms
,08-23 13:54:20.981   766  2306 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dbb9458 4241:com.google.android.gms/u0a11}
,08-23 13:54:20.991  4241  5103 D nzm     : Processing package: com.test.thalitest
,08-23 13:54:20.991  4241  4241 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-23 13:54:21.041   766  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-23 13:54:21.061  4241  5103 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-23 13:54:21.061  4241  5103 D nzm     : Found info for package com.test.thalitest in db.
,08-23 13:54:21.101   766  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{62b7061 5859:com.android.vending/u0a29}
,08-23 13:54:21.151  5859  5859 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-23 13:54:21.161   766   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33a7113 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f96619 6232:com.sec.android.app.samsungapps/u0a39}
,08-23 13:54:21.171  2075  2075 D WearableService: callingUid 10011, callindPid: 2075
,08-23 13:54:21.181   766  1700 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bc98436 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef7e081 2075:com.google.android.gms.persistent/u0a11}
,08-23 13:54:21.181   766  1730 V AlarmManager:  remove PendingIntent] PendingIntent{2d9ef37: PendingIntentRecord{3af8e32 com.google.android.gms broadcastIntent}}
,08-23 13:54:21.191  5859  5859 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-23 13:54:21.191   766  1700 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{937cca4 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{62b7061 5859:com.android.vending/u0a29}
,08-23 13:54:21.191  6539  6539 D Mms/BubbleViewCache: fillCache bubble = 4
,08-23 13:54:21.221  6779  6779 E Zygote  : v2
08-23 13:54:21.221  6779  6779 I libpersona: KNOX_SDCARD checking this for 10034
08-23 13:54:21.221  6779  6779 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:54:21.221  6779  6779 I libpersona: KNOX_SDCARD not a persona
08-23 13:54:21.221  6779  6779 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:54:21.221   766  1733 I ActivityManager: Start proc 6779:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-23 13:54:21.221  6779  6779 E Zygote  : accessInfo : 0
08-23 13:54:21.221  5859  5859 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
08-23 13:54:21.221  6779  6779 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
08-23 13:54:21.221  5859  5859 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-23 13:54:21.231  5859  6781 I Finsky  : [848] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-23 13:54:21.251  6779  6779 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:54:21.251  6779  6779 D ActivityThread: Added TimaKeyStore provider
,08-23 13:54:21.261  5859  5884 I PlayCommon: [817] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-23 13:54:21.261   766  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4a1adc2 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1d447d3 6779:com.sec.android.app.shealth/u0a34}
,08-23 13:54:21.271  6779  6779 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-23 13:54:21.281  5859  6792 I PlayCommon: [849] com.google.android.play.a.w.a(27553): Starting to flush logs
08-23 13:54:21.281  2075  2075 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:54:21.281  5859  6792 I PlayCommon: [849] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,08-23 13:54:21.311  6779  6779 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-23 13:54:21.311  5859  5884 I PlayCommon: [817] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-23 13:54:21.321  5859  5884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 13:54:21.321  5859  5884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 13:54:21.321   310  1190 D EnterpriseController: netId is 0
08-23 13:54:21.321   310  1190 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-23 13:54:21.321  6680  6709 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 13:54:21.321  6680  6709 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 13:54:21.331  6779  6779 I MultiDex: VM with version 2.1.0 has multidex support
08-23 13:54:21.331  6779  6779 I MultiDex: install
08-23 13:54:21.331  6779  6779 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-23 13:54:21.331  6779  6779 I MultiDex: install
08-23 13:54:21.331  6779  6779 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 13:54:21.361  6680  6709 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 13:54:21.361  6680  6709 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-23 13:54:21.361  6680  6709 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-23 13:54:21.371  6680  6709 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 13:54:21.371  6680  6709 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 13:54:21.411   766  1700 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4a1adc2 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54c365b 1884:com.sec.android.app.shealth:remote/u0a34}
,08-23 13:54:21.411  6779  6779 D HealthDataStore: Service for HealthDataStore is connected
,08-23 13:54:21.411  6779  6779 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-23 13:54:21.411  6779  6779 D HealthConsole: Service for HealthDataConsole is connected
,08-23 13:54:21.421  6779  6779 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-23 13:54:21.421  6779  6779 E HealthDataStore: disconnectService: Context instance is invalid
,08-23 13:54:21.431   766   778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4a1adc2 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54c365b 1884:com.sec.android.app.shealth:remote/u0a34}
,08-23 13:54:21.451   766  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2546cbe u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef7e081 2075:com.google.android.gms.persistent/u0a11}
,08-23 13:54:21.621  5859  5884 I PlayCommon: [817] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-23 13:54:21.621  5859  5884 I PlayCommon: [817] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-23 13:54:21.621  5859  5884 I PlayCommon: [817] com.google.android.play.a.al.e(732): No file ready to send
,08-23 13:54:21.641   766  1701 I ActivityManager: Killing 4702:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-23 13:54:21.661  1451  1451 D Recents : onTaskStackChanged
,08-23 13:54:21.671  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 13:54:21.681   766  2310 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-23 13:54:21.711  2218  2218 E audit   : type=1400 msg=audit(1471953261.701:289): avc:  denied  { execmod } for  pid=6760 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:54:21.711  2218  2218 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:21.711  2218  2218 E audit   : type=1300 msg=audit(1471953261.701:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f6b000 a1=51000 a2=5 a3=4 items=0 ppid=3578 ppcomm=adbd pid=6760 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:54:21.711  2218  2218 E audit   : type=1327 msg=audit(1471953261.701:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 13:54:21.711  2218  2218 E audit   : type=1320 msg=audit(1471953261.701:289): 
,08-23 13:54:21.761  2218  2218 E audit   : type=1400 msg=audit(1471953261.761:290): avc:  denied  { execmod } for  pid=6760 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:54:21.761  2218  2218 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:21.761  2218  2218 E audit   : type=1300 msg=audit(1471953261.761:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f2b000 a1=51000 a2=5 a3=4 items=0 ppid=3578 ppcomm=adbd pid=6760 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:54:21.761  2218  2218 E audit   : type=1327 msg=audit(1471953261.761:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 13:54:21.761  2218  2218 E audit   : type=1320 msg=audit(1471953261.761:290): 
,08-23 13:54:21.801  2218  2218 E audit   : type=1400 msg=audit(1471953261.801:291): avc:  denied  { execmod } for  pid=6760 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:54:21.801  2218  2218 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-23 13:54:21.801  2218  2218 E audit   : type=1300 msg=audit(1471953261.801:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f2b000 a1=51000 a2=5 a3=4 items=0 ppid=3578 ppcomm=adbd pid=6760 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:54:21.801  2218  2218 E audit   : type=1327 msg=audit(1471953261.801:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 13:54:21.801  2218  2218 E audit   : type=1320 msg=audit(1471953261.801:291): 
,08-23 13:54:21.801  6760  6760 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 13:54:21.811  6760  6760 D AndroidRuntime: CheckJNI is OFF
,08-23 13:54:21.811  6760  6760 D AndroidRuntime: readGMSProperty: start
08-23 13:54:21.811  6760  6760 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:54:21.811  6760  6760 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:54:21.811  6760  6760 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:54:21.811  6760  6760 D AndroidRuntime: readGMSProperty: end
08-23 13:54:21.811  6760  6760 D AndroidRuntime: addProductProperty: start
,08-23 13:54:21.821  6760  6760 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:54:21.821  6760  6760 W art     : af0ce000-b1ff4000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:54:21.821  6760  6760 W art     : b1ff4000-b4263000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:54:21.821  6760  6760 W art     : b4263000-b4264000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:54:21.821  6760  6760 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 13:54:21.821  6760  6760 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 13:54:21.821  6760  6760 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 13:54:21.821  6760  6760 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 13:54:21.821  6760  6760 W art     : b47d0000-b47f9000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:54:21.821  6760  6760 W art     : b47f9000-b47fc000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:54:21.821  6760  6760 W art     : b47fc000-b47fd000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:54:21.821  6760  6760 W art     : b47fd000-b47fe000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:54:21.821  6760  6760 W art     : b47fe000-b47ff000 r--p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b47ff000-b481f000 r--s 00000000 00:0b 7184       /dev/__properties__
08-23 13:54:21.821  6760  6760 W art     : b481f000-b5230000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:54:21.821  6760  6760 W art     : b5230000-b5231000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5231000-b527a000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:54:21.821  6760  6760 W art     : b527a000-b527b000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:54:21.821  6760  6760 W art     : b527b000-b5283000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5283000-b5284000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b5284000-b52b9000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:54:21.821  6760  6760 W art     : b52b9000-b52ba000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b52ba000-b52bb000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:54:21.821  6760  6760 W art     : b52bb000-b52bc000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:54:21.821  6760  6760 W art     : b52bc000-b5314000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 13:54:21.821  6760  6760 W art     : b5314000-b5315000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5315000-b5316000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 13:54:21.821  6760  6760 W art     : b5316000-b5317000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 13:54:21.821  6760  6760 W art     : b5318000-b531e000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:54:21.821  6760  6760 W art     : b531e000-b531f000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:54:21.821  6760  6760 W art     : b531f000-b5320000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:54:21.821  6760  6760 W art     : b5320000-b5322000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5323000-b532d000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:54:21.821  6760  6760 W art     : b532d000-b5330000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:54:21.821  ,6760  6760 W art     : b5330000-b5331000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:54:21.821  6760  6760 W art     : b5332000-b5349000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:54:21.821  6760  6760 W art     : b5349000-b534a000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b534a000-b534b000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:54:21.821  6760  6760 W art     : b534b000-b534c000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:54:21.821  6760  6760 W art     : b534d000-b5357000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:54:21.821  6760  6760 W art     : b5357000-b5358000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:54:21.821  6760  6760 W art     : b5358000-b5359000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:54:21.821  6760  6760 W art     : b5359000-b535d000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:54:21.821  6760  6760 W art     : b535d000-b535e000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:54:21.821  6760  6760 W art     : b535e000-b535f000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:54:21.821  6760  6760 W art     : b535f000-b5375000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 13:54:21.821  6760  6760 W art     : b5375000-b5376000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 13:54:21.821  6760  6760 W art     : b5376000-b5377000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 13:54:21.821  6760  6760 W art     : b5377000-b5384000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:54:21.821  6760  6760 W art     : b5384000-b5385000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:54:21.821  6760  6760 W art     : b5385000-b5386000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:54:21.821  6760  6760 W art     : b5386000-b53e6000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 13:54:21.821  6760  6760 W art     : b53e6000-b53e9000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 13:54:21.821  6760  6760 W art     : b53e9000-b53ed000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b53ed000-b544e000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:54:21.821  6760  6760 W art     : b544e000-b544f000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:54:21.821  6760  6760 W art     : b544f000-b549e000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:54:21.821  6760  6760 W art     : b549e000-b54a0000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:54:21.821  6760  6760 W art     : b54a0000-b54a1000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:54:21.821  6760  6760 W art     : b54a1000-b54a2000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b54a2000-b54a9000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:54:21.821  6760  6760 W art     : b54a9000-b54aa000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-23 13:54:21.821  6760  6760 W art     : b54aa000-b54ab000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:54:21.821  6760  6760 W art     : b54ac000-b54af000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:54:21.821  6760  6760 W art     : b54af000-b54b0000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:54:21.821  6760  6760 W art     : b54b0000-b54b1000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:54:21.821  6760  6760 W art     : b54b2000-b54b6000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:54:21.821  6760  6760 W art     : b54b6000-b54b7000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b54b7000-b54b8000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
,08-23 13:54:21.821  6760  6760 W art     : b54b8000-b54b9000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:54:21.821  6760  6760 W art     : b54ba000-b54d7000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:54:21.821  6760  6760 W art     : b54d7000-b54d8000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:54:21.821  6760  6760 W art     : b54d8000-b54d9000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:54:21.821  6760  6760 W art     : b54da000-b54df000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:54:21.821  6760  6760 W art     : b54df000-b54e0000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:54:21.821  6760  6760 W art     : b54e0000-b54e1000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-23 13:54:21.821  6760  6760 W art     : b54e2000-b5513000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:54:21.821  6760  6760 W art     : b5513000-b5516000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:54:21.821  6760  6760 W art     : b5516000-b5517000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:54:21.821  6760  6760 W art     : b5518000-b5553000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 13:54:21.821  6760  6760 W art     : b5553000-b5554000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 13:54:21.821  6760  6760 W art     : b5554000-b5555000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
,08-23 13:54:21.821  6760  6760 W art     : b5556000-b555d000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:54:21.821  6760  6760 W art     : b555d000-b555e000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b555e000-b555f000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:54:21.821  6760  6760 W art     : b555f000-b5560000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:54:21.821  6760  6760 W art     : b5560000-b5561000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b5561000-b5578000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
,08-23 13:54:21.821  6760  6760 W art     : b5578000-b5579000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5579000-b557c000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:54:21.821  6760  6760 W art     : b557c000-b557d000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:54:21.821  6760  6760 W art     : b557d000-b559c000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:54:21.821  6760  6760 W art     : b559c000-b559d000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:54:21.821  6760  6760 W art     : b559d000-b559e000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
,08-23 13:54:21.821  6760  6760 W art     : b559e000-b55dc000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 13:54:21.821  6760  6760 W art     : b55dc000-b55dd000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b55dd000-b55df000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 13:54:21.821  6760  6760 W art     : b55df000-b55e0000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 13:54:21.821  6760  6760 W art     : b55e1000-b55e8000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
,08-23 13:54:21.821  6760  6760 W art     : b55e8000-b55e9000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:54:21.821  6760  6760 W art     : b55e9000-b55ea000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:54:21.821  6760  6760 W art     : b55eb000-b55ee000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:54:21.821  6760  6760 W art     : b55ee000-b55ef000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:54:21.821  6760  6760 W art     : b55ef000-b55f0000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:54:21.821  6760  6760 W art     : b55f0000-b55f6000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-23 13:54:21.821  6760  6760 W art     : b55f6000-b55f7000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b55f7000-b55f8000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:54:21.821  6760  6760 W art     : b55f8000-b55f9000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:54:21.821  6760  6760 W art     : b55f9000-b5602000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:54:21.821  6760  6760 W art     : b5602000-b5603000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
,08-23 13:54:21.821  6760  6760 W art     : b5603000-b5604000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:54:21.821  6760  6760 W art     : b5604000-b5695000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:54:21.821  6760  6760 W art     : b5695000-b5696000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5696000-b56a1000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:54:21.821  6760  6760 W art     : b56a1000-b56a2000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:54:21.821  6760  6760 W art     : b56a3000-b56b5000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
,08-23 13:54:21.821  6760  6760 W art     : b56b5000-b56b6000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 13:54:21.821  6760  6760 W art     : b56b6000-b56b7000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 13:54:21.821  6760  6760 W art     : b56b8000-b56bd000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:54:21.821  6760  6760 W art     : b56bd000-b56be000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:54:21.821  6760  6760 W art     : b56be000-b56bf000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:54:21.821  6760  6760 W art     : b56c0000-b572d000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
,08-23 13:54:21.821  6760  6760 W art     : b572d000-b572e000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b572e000-b5730000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:54:21.821  6760  6760 W art     : b5730000-b5731000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:54:21.821  6760  6760 W art     : b5731000-b5732000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b5732000-b5739000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:54:21.821  6760  6760 W art     : b5739000-b573a000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-23 13:54:21.821  6760  6760 W art     : b573a000-b573b000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:54:21.821  6760  6760 W art     : b573c000-b57bc000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:54:21.821  6760  6760 W art     : b57bc000-b57bd000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b57bd000-b57be000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:54:21.821  6760  6760 W art     : b57be000-b57bf000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:54:21.821  6760  6760 W art     : b57bf000-b57d6000 rw-p 00000000 00:00 0 
,08-23 13:54:21.821  6760  6760 W art     : b57d6000-b580d000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 13:54:21.821  6760  6760 W art     : ib/libqc-opt.so
08-23 13:54:21.821  6760  6760 W art     : b580d000-b580e000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:54:21.821  6760  6760 W art     : b580e000-b580f000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:54:21.821  6760  6760 W art     : b580f000-b582b000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:54:21.821  6760  6760 W art     : b582b000-b582c000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
,08-23 13:54:21.821  6760  6760 W art     : b582c000-b582d000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:54:21.821  6760  6760 W art     : b582e000-b588f000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 13:54:21.821  6760  6760 W art     : b588f000-b5891000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 13:54:21.821  6760  6760 W art     : b5891000-b5892000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 13:54:21.821  6760  6760 W art     : b5893000-b58ba000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 13:54:21.821  6760  6760 W art     : b58ba000-b58bb000 ---p 00000000 00:00 0 
,08-23 13:54:21.821  6760  6760 W art     : b58bb000-b58bc000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 13:54:21.821  6760  6760 W art     : b58bc000-b58bd000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 13:54:21.821  6760  6760 W art     : b58be000-b58c6000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:54:21.821  6760  6760 W art     : b58c6000-b58c8000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:54:21.821  6760  6760 W art     : b58c8000-b58c9000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:54:21.821  6760  6760 W art     : b58ca000-b58cd000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
,08-23 13:54:21.821  6760  6760 W art     : b58cd000-b58ce000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 13:54:21.821  6760  6760 W art     : b58ce000-b58cf000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 13:54:21.821  6760  6760 W art     : b58cf000-b58d3000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:54:21.821  6760  6760 W art     : b58d3000-b58d4000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b58d4000-b58d5000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
,08-23 13:54:21.821  6760  6760 W art     : b58d5000-b58d6000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:54:21.821  6760  6760 W art     : b58d6000-b58e6000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 13:54:21.821  6760  6760 W art     : b58e6000-b58e7000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 13:54:21.821  6760  6760 W art     : b58e7000-b58e8000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
,08-23 13:54:21.821  6760  6760 W art     : b58e8000-b592e000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b592e000-b5937000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 13:54:21.821  6760  6760 W art     : b5937000-b5938000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 13:54:21.821  6760  6760 W art     : b5938000-b5939000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
,08-23 13:54:21.821  6760  6760 W art     : b593a000-b593f000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 13:54:21.821  6760  6760 W art     : b593f000-b5940000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 13:54:21.821  6760  6760 W art     : b5940000-b5941000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 13:54:21.821  6760  6760 W art     : b5941000-b5944000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:54:21.821  6760  6760 W art     : b5944000-b5945000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5945000-b5946000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-23 13:54:21.821  6760  6760 W art     : b5946000-b5947000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:54:21.821  6760  6760 W art     : b5948000-b5960000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:54:21.821  6760  6760 W art     : b5960000-b5961000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5961000-b5962000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:54:21.821  6760  6760 W art     : b5962000-b5963000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:54:21.821  6760  6760 W art     : b5963000-b5964000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-23 13:54:21.821  6760  6760 W art     : b5964000-b5afe000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:54:21.821  6760  6760 W art     : b5afe000-b5aff000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5aff000-b5b0c000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:54:21.821  6760  6760 W art     : b5b0c000-b5b0d000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:54:21.821  6760  6760 W art     : b5b0d000-b5b11000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 13:54:21.821  6760  6760 W art     : b5b11000-b5b12000 ---p 00000000 00:00 0 
,08-23 13:54:21.821  6760  6760 W art     : b5b12000-b5b13000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 13:54:21.821  6760  6760 W art     : b5b13000-b5b14000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 13:54:21.821  6760  6760 W art     : b5b14000-b5b27000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:54:21.821  6760  6760 W art     : b5b27000-b5b28000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:54:21.821  6760  6760 W art     : b5b28000-b5b29000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:54:21.821  6760  6760 W art     : b5b2a000-b5b75000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
,08-23 13:54:21.821  6760  6760 W art     : b5b75000-b5b76000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:54:21.821  6760  6760 W art     : b5b76000-b5b77000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:54:21.821  6760  6760 W art     : b5b77000-b5b79000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5b7a000-b5b8b000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:54:21.821  6760  6760 W art     : b5b8b000-b5b8c000 ---p 00000000 00:00 0 
,08-23 13:54:21.821  6760  6760 W art     : b5b8c000-b5b8d000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:54:21.821  6760  6760 W art     : b5b8d000-b5b8e000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:54:21.821  6760  6760 W art     : b5b8e000-b5b8f000 r--p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5b8f000-b5b99000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:54:21.821  6760  6760 W art     : b5b99000-b5b9b000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:54:21.821  6760  6760 W art     : b5b9b000-b5b9c000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
,08-23 13:54:21.821  6760  6760 W art     : b5b9c000-b5bb5000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:54:21.821  6760  6760 W art     : b5bb5000-b5bb6000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:54:21.821  6760  6760 W art     : b5bb6000-b5bb9000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:54:21.821  6760  6760 W art     : b5bb9000-b5bbd000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5bbd000-b5c31000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 13:54:21.821  6760  6760 W art     : b5c31000-b5c32000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5c32000-b5c35000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 13:54:21.821  6760  6760 W art     : b5c35000-b5c36000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 13:54:21.821  6760  6760 W art     : b5c36000-b5c37000 r--p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5c37000-b5c3a000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:54:21.821  6760  6760 W art     : b5c3a000-b5c3b000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:54:21.821  6760  6760 W art     : b5c3b000-b5c3c000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:54:21.821  6760  6760 W art     : b5c3c000-b5c3d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b5c3d000-b5c42000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:54:21.821  6760  6760 W art     : b5c42000-b5c43000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:54:21.821  6760  6760 W art     : b5c43000-b5c44000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:54:21.821  6760  6760 W art     : b5c44000-b5c45000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b5c45000-b5c48000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:54:21.821  6760  6760 W art     : b5c48000-b5c49000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:54:21.821  6760  6760 W art     : b5c49000-b5c4a000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:54:21.821  6760  6760 W art     : b5c4a000-b5c4b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b5c4b000-b5c4f000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:54:21.821  6760  6760 W art     : b5c4f000-b5c50000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:54:21.821  6760  6760 W art     : b5c50000-b5c51000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:54:21.821  6760  6760 W art     : b5c51000-b5c52000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:54:21.821  6760  6760 W art     : b5c52000-b5c56000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:54:21.821  6760  6760 W art     : b5c56000-b5c57000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:54:21.821  6760  6760 W art     : b5c57000-b5c58000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:54:21.821  6760  6760 W art     : b5c58000-b5c59000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b5c59000-b5c67000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 13:54:21.821  6760  6760 W art     : b5c67000-b5c68000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b5c68000-b5c69000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 13:54:21.821  6760  6760 W art     : b5c69000-b5c6a000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 13:54:21.821  6760  6760 W art     : b5c6a000-b5c74000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:54:21.821  6760  6760 W art     : b5c74000-b5c77000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:54:21.821  6760  6760 W art     : b5c77000-b5c78000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:54:21.821  6760  6760 W art     : b5c78000-b5c79000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b5c79000-b5c83000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 13:54:21.821  6760  6760 W art     : b5c83000-b5c86000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 13:54:21.821  6760  6760 W art     : b5c86000-b5c87000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 13:54:21.821  6760  6760 W art     : b5c87000-b5c8b000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:54:21.821  6760  6760 W art     : b5c8b000-b5c8c000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:54:21.821  6760  6760 W art     : b5c8c000-b5c8d000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:54:21.821  6760  6760 W art     : b5c8d000-b5c8e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b5c8e000-b5c9b000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:54:21.821  6760  6760 W art     : b5c9b000-b5c9d000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:54:21.821  6760  6760 W art     : b5c9d000-b5c9e000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:54:21.821  6760  6760 W art     : b5c9e000-b60b0000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 13:54:21.821  6760  6760 W art     : b60b0000-b60b1000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b60b1000-b60ba000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 13:54:21.821  6760  6760 W art     : b60ba000-b60be000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 13:54:21.821  6760  6760 W art     : b60be000-b60bf000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b60bf000-b60c6000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:54:21.821  6760  6760 W art     : b60c6000-b60c7000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:54:21.821  6760  6760 W art     : b60c7000-b60c8000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:54:21.821  6760  6760 W art     : b60c8000-b60c9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b60c9000-b60e4000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-23 13:54:21.821  6760  6760 W art     : b60e4000-b60e5000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 13:54:21.821  6760  6760 W art     : b60e5000-b60e6000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 13:54:21.821  6760  6760 W art     : b60e6000-b60e7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b60e7000-b6133000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:54:21.821  6760  6760 W art     : b6133000-b6134000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6134000-b6135000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:54:21.821  6760  6760 W art     : b6135000-b6136000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:54:21.821  6760  6760 W art     : b6136000-b6137000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b6137000-b613b000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:54:21.821  6760  6760 W art     : b613b000-b613c000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b613c000-b613d000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:54:21.821  6760  6760 W art     : b613d000-b613e000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:54:21.821  6760  6760 W art     : b613e000-b6176000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:54:21.821  6760  6760 W art     : b6176000-b6177000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:54:21.821  6760  6760 W art     : b6177000-b6178000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:54:21.821  6760  6760 W art     : b6178000-b6179000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b6179000-b6217000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 13:54:21.821  6760  6760 W art     : b6217000-b6218000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6218000-b6236000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
,08-23 13:54:21.821  6760  6760 W art     : b6236000-b6237000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-23 13:54:21.821  6760  6760 W art     : b6237000-b63aa000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:54:21.821  6760  6760 W art     : b63aa000-b63b5000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:54:21.821  6760  6760 W art     : b63b5000-b63b6000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:54:21.821  6760  6760 W art     : b63b6000-b64cd000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:54:21.821  6760  6760 W art     : b64cd000-b64d8000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:54:21.821  6760  6760 W art     : b64d8000-b64d9000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:54:21.821  6760  6760 W art     : b64d9000-b64dd000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b64dd000-b6501000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
,08-23 13:54:21.821  6760  6760 W art     : b6501000-b6503000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 13:54:21.821  6760  6760 W art     : b6503000-b6504000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 13:54:21.821  6760  6760 W art     : b6504000-b65aa000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 13:54:21.821  6760  6760 W art     : b65aa000-b65b7000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-23 13:54:21.821  6760  6760 W art     : b65b7000-b65b8000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 13:54:21.821  6760  6760 W art     : b65b8000-b65b9000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b65b9000-b660c000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:54:21.821  6760  6760 W art     : b660c000-b660d000 ---p 00000000 00:00 0 
,08-23 13:54:21.821  6760  6760 W art     : b660d000-b660e000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:54:21.821  6760  6760 W art     : b660e000-b660f000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:54:21.821  6760  6760 W art     : b660f000-b6614000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6614000-b6626000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 13:54:21.821  6760  6760 W art     : b6626000-b6627000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6627000-b6628000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 13:54:21.821  6760  6760 W art     : b6628000-b6629000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
,08-23 13:54:21.821  6760  6760 W art     : b6629000-b6630000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:54:21.821  6760  6760 W art     : b6630000-b6631000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:54:21.821  6760  6760 W art     : b6631000-b6632000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:54:21.821  6760  6760 W art     : b6632000-b6633000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6633000-b6636000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 13:54:21.821  6760  6760 W art     : b6636000-b6637000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
,08-23 13:54:21.821  6760  6760 W art     : b6637000-b6638000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 13:54:21.821  6760  6760 W art     : b6638000-b663c000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 13:54:21.821  6760  6760 W art     : b663c000-b663d000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 13:54:21.821  6760  6760 W art     : b663d000-b663e000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 13:54:21.821  6760  6760 W art     : b663e000-b664c000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:54:21.821  6760  6760 W art     : b664c000-b664d000 ---p 00000000 00:00 0 
,08-23 13:54:21.821  6760  6760 W art     : b664d000-b664e000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:54:21.821  6760  6760 W art     : b664e000-b664f000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:54:21.821  6760  6760 W art     : b664f000-b6658000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:54:21.821  6760  6760 W art     : b6658000-b6659000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:54:21.821  6760  6760 W art     : b6659000-b665a000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:54:21.821  6760  6760 W art     : b665a000-b66c0000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
,08-23 13:54:21.821  6760  6760 W art     : b66c0000-b66c1000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b66c1000-b66c3000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 13:54:21.821  6760  6760 W art     : b66c3000-b66cc000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 13:54:21.821  6760  6760 W art     : b66cc000-b66cf000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b66cf000-b6766000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 13:54:21.821  6760  6760 W art     : b6766000-b6768000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
,08-23 13:54:21.821  6760  6760 W art     : b6768000-b6769000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 13:54:21.821  6760  6760 W art     : b6769000-b676a000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b676a000-b6a8b000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 13:54:21.821  6760  6760 W art     : b6a8b000-b6a8c000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6a8c000-b6aa7000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 13:54:21.821  6760  6760 W art     : b6aa7000-b6aab000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
,08-23 13:54:21.821  6760  6760 W art     : b6aab000-b6ab0000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6ab0000-b6ab8000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:54:21.821  6760  6760 W art     : b6ab8000-b6ab9000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:54:21.821  6760  6760 W art     : b6ab9000-b6aba000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:54:21.821  6760  6760 W art     : b6aba000-b6ae8000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:54:21.821  6760  6760 W art     : b6ae8000-b6ae9000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6ae9000-b6af0000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:54:21.821  6760  6760 W art     : b6af0000-b6af1000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:54:21.821  6760  6760 W art     : b6af1000-b6b37000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:54:21.821  6760  6760 W art     : b6b37000-b6b38000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6b38000-b6b3b000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:54:21.821  6760  6760 W art     : b6b3b000-b6b3c000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:54:21.821  6760  6760 W art     : b6b3c000-b6b57000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 13:54:21.821  6760  6760 W art     : b6b57000-b6b5b000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 13:54:21.821  6760  6760 W art     : b6b5b000-b6b5c000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 13:54:21.821  6760  6760 W art     : b6b5c000-b6ba9000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 13:54:21.821  6760  6760 W art     : b6ba9000-b6baa000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6baa000-b6bb6000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 13:54:21.821  6760  6760 W art     : b6bb6000-b6bb7000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 13:54:21.821  6760  6760 W art     : b6bb7000-b6bc4000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 13:54:21.821  6760  6760 W art     : b6bc4000-b6bc5000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6bc5000-b6bc6000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 13:54:21.821  6760  6760 W art     : b6bc6000-b6bc7000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 13:54:21.821  6760  6760 W art     : b6bc7000-b6bcf000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:54:21.821  6760  6760 W art     : b6bcf000-b6bd0000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6bd0000-b6bd1000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:54:21.821  6760  6760 W art     : b6bd1000-b6bd2000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:54:21.821  6760  6760 W art     : b6bd2000-b6bd9000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:54:21.821  6760  6760 W art     : b6bd9000-b6bda000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:54:21.821  6760  6760 W art     : b6bda000-b6bdb000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:54:21.821  6760  6760 W art     : b6bdb000-b6bef000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 13:54:21.821  6760  6760 W art     : b6bef000-b6bf1000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 13:54:21.821  6760  6760 W art     : b6bf1000-b6bf2000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 13:54:21.821  6760  6760 W art     : b6bf2000-b6c1a000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:54:21.821  6760  6760 W art     : b6c1a000-b6c1c000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:54:21.821  6760  6760 W art     : b6c1c000-b6c1d000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:54:21.821  6760  6760 W art     : b6c1d000-b6c20000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:54:21.821  6760  6760 W art     : b6c20000-b6c21000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:54:21.821  6760  6760 W art     : b6c21000-b6c22000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:54:21.821  6760  6760 W art     : b6c22000-b6c2b000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:54:21.821  6760  6760 W art     : b6c2b000-b6c2c000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:54:21.821  6760  6760 W art     : b6c2c000-b6c2d000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:54:21.821  6760  6760 W art     : b6c2d000-b6c4d000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 13:54:21.821  6760  6760 W art     : b6c4d000-b6c4e000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 13:54:21.821  6760  6760 W art     : b6c4e000-b6c4f000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 13:54:21.821  6760  6760 W art     : b6c4f000-b6cc2000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 13:54:21.821  6760  6760 W art     : b6cc2000-b6cc6000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 13:54:21.821  6760  6760 W art     : b6cc6000-b6cc9000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 13:54:21.821  6760  6760 W art     : b6cc9000-b6cd3000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6cd3000-b6d5b000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 13:54:21.821  6760  6760 W art     : b6d5b000-b6d5c000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6d5c000-b6d60000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 13:54:21.821  6760  6760 W art     : b6d60000-b6d61000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 13:54:21.821  6760  6760 W art     : b6d61000-b6d62000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6d62000-b6d8b000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:54:21.821  6760  6760 W art     : b6d8b000-b6d8c000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6d8c000-b6d8f000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:54:21.821  6760  6760 W art     : b6d8f000-b6d90000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:54:21.821  6760  6760 W art     : b6d90000-b6e6a000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:54:21.821  6760  6760 W art     : b6e6a000-b6e71000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:54:21.821  6760  6760 W art     : b6e71000-b6e79000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:54:21.821  6760  6760 W art     : b6e79000-b6e7a000 rw-p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6e7a000-b6e7b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:54:21.821  6760  6760 W art     : b6e7b000-b6e7c000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 13:54:21.821  6760  6760 W art     : b6e7c000-b6e7d000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b6e7d000-b6e80000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b6e80000-b6ea5000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 13:54:21.821  6760  6760 W art     : b6ea5000-b6ea6000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6ea6000-b6ead000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 13:54:21.821  6760  6760 W art     : b6ead000-b6eae000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 13:54:21.821  6760  6760 W art     : b6eae000-b6eb5000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 13:54:21.821  6760  6760 W art     : b6eb5000-b6eb6000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 13:54:21.821  6760  6760 W art     : b6eb6000-b6eb7000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 13:54:21.821  6760  6760 W art     : b6eb7000-b6eb8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.821  6760  6760 W art     : b6eb8000-b6ed0000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 13:54:21.821  6760  6760 W art     : b6ed0000-b6ed1000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6ed1000-b6ed2000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 13:54:21.821  6760  6760 W art     : b6ed2000-b6ed3000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 13:54:21.821  6760  6760 W art     : b6ed3000-b6ee1000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 13:54:21.821  6760  6760 W art     : b6ee1000-b6ee2000 ---p 00000000 00:00 0 
08-23 13:54:21.821  6760  6760 W art     : b6ee2000-b6ee3000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 13:54:21.821  6760  6760 W art     : b6ee3000-b6ee4000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 13:54:21.831  6760  6760 W art     : b6ee4000-b6ee5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:54:21.831  6760  6760 W art     : b6ee5000-b6ee7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.831  6760  6760 W art     : b6ee7000-b6ee8000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.831  6760  6760 W art     : b6ee8000-b6ee9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:54:21.831  6760  6760 W art     : b6ee9000-b6eea000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 13:54:21.831  6760  6760 W art     : b6eea000-b6eeb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:54:21.831  6760  6760 W art     : b6eeb000-b6f0b000 r--s 00000000 00:0b 7184       /dev/__properties__
08-23 13:54:21.831  6760  6760 W art     : b6f0b000-b6f0c000 r--p 00000000 00:00 0 
08-23 13:54:21.831  6760  6760 W art     : b6f0c000-b6f0d000 ---p 00000000 00:00 0 
08-23 13:54:21.831  6760  6760 W art     : b6f0d000-b6f0f000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 13:54:21.831  6760  6760 W art     : b6f0f000-b6f10000 r-xp 00000000 00:00 0          [sigpage]
08-23 13:54:21.831  6760  6760 W art     : b6f10000-b6f2b000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 13:54:21.831  6760  6760 W art     : b6f2b000-b6f2c000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 13:54:21.831  6760  6760 W art     : b6f2c000-b6f2e000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 13:54:21.831  6760  6760 W art     : b6f2e000-b6f30000 rw-p 00000000 00:00 0 
08-23 13:54:21.831  6760  6760 W art     : b6f30000-b6f35000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 13:54:21.831  6760  6760 W art     : b6f35000-b6f36000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 13:54:21.831  6760  6760 W art     : b6f36000-b6f37000 rw-p 00000000 00:00 0 
08-23 13:54:21.831  6760  6760 W art     : be959000-be97a000 rw-p 00000000 00:00 0          [stack]
08-23 13:54:21.831  6760  6760 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 13:54:21.881  6760  6760 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 13:54:21.921  6760  6760 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 13:54:21.931  6760  6760 E AffinityControl: AffinityControl: registerfunction enter
,08-23 13:54:21.951  6760  6760 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:54:21.971   766  1702 D PackageManager: START PACKAGE DELETE: observer{549151},
08-23 13:54:21.971   766  1702 D PackageManager: pkg{<packageName>}
08-23 13:54:21.971   766  1702 D PackageManager: user{0}
08-23 13:54:21.971   766  1702 D PackageManager: caller{2000}
08-23 13:54:21.971   766  1702 D PackageManager: flags{2}
08-23 13:54:21.971   766  1702 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 13:54:21.971   766  1702 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 13:54:21.971   766  1702 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-23 13:54:21.971   766  1702 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 13:54:21.971   766  1702 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 13:54:21.971   766   938 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 13:54:21.971   766   938 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 13:54:21.971   766   938 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 13:54:21.971   766   938 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-23 13:54:21.971   766   938 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-23 13:54:21.971   766   938 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-23 13:54:21.971   766   938 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-23 13:54:21.971   766   938 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-23 13:54:21.971   766   865 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-23 13:54:21.971   766   865 I ActivityManager: Killing 6528:com.test.thalitest/u0a4 (adj 15): stop com.test.thalitest cause uninstall pkg,
,08-23 13:54:21.971   766   865 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-23 13:54:21.981   766   938 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-23 13:54:21.981   766   938 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-23 13:54:22.001   766   938 D AASAinstall: there is not AASApackages.xml file
,08-23 13:54:22.011   766  2310 D GraphicsStats: Buffer count: 4
,08-23 13:54:22.011   766  2307 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@e22fc6c)
,08-23 13:54:22.011   766  1332 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:54:22.011   766  1332 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:54:22.011   766  1332 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:54:22.051   344   408 I ThermalEngine: Sensor:tsens_tz_sensor6:74000 mC
,08-23 13:54:22.051   344   422 I ThermalEngine: Sensor:tsens_tz_sensor6:74000 mC
08-23 13:54:22.051   344   422 I ThermalEngine: TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm cleared 1 at 74.0 degC
,08-23 13:54:22.191  4241  5013 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-23 13:54:22.241   344   406 I ThermalEngine: Sensor:tsens_tz_sensor5:75000 mC
,08-23 13:54:22.251   344   422 I ThermalEngine: Sensor:tsens_tz_sensor5:75000 mC
08-23 13:54:22.251   344   422 I ThermalEngine: TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm cleared 1 at 75.0 degC
,08-23 13:54:22.251   344   422 I ThermalEngine: ACTION: OPT_CURR_REQ 0
,08-23 13:54:22.271   766   938 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-23 13:54:22.371   766   938 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-23 13:54:22.371  4241  5013 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-23 13:54:22.381   333   333 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-23 13:54:22.381   766   938 I art     : Starting a blocking GC Explicit
,08-23 13:54:22.471   766   938 I art     : Explicit concurrent mark sweep GC freed 82389(3MB) AllocSpace objects, 6(120KB) LOS objects, 27% free, 41MB/57MB, paused 1.278ms total 91.117ms
,08-23 13:54:22.501   766   938 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 13:54:22.501   766   938 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-23 13:54:22.501   766   938 D AASAinstall: there is not AASApackages.xml file
08-23 13:54:22.501   766   938 D PackageManager: result of delete: 1{549151}
,08-23 13:54:22.501  6760  6760 I art     : System.exit called, status: 0
08-23 13:54:22.501  6760  6760 I AndroidRuntime: VM exiting with result code 0.
,08-23 13:54:22.501   766   938 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 13:54:22.501   766   938 D PackageManager: userId{-1}
08-23 13:54:22.501   766   938 D PackageManager: andCode{true}
,08-23 13:54:22.511   766   938 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-23 13:54:22.541  6100  6479 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-23 13:54:22.551  6100  6479 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-23 13:54:22.551  6100  6479 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-23 13:54:22.591   766   766 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.591  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-23 13:54:22.591  1382  1382 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-23 13:54:22.601   766   905 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.601   766   766 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.601   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.601   766   905 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.611   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.611   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.611   766  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 13:54:22.611   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.611   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.611   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.611   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.611   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.611   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.611   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.621   766   766 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.621  1928  1928 E SamsungIME: mOCRHelper is null
,08-23 13:54:22.621   766   766 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.621   766   766 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.631   766   766 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.631   766   766 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.631   766   766 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.631   766   766 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.631   766   766 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.631   766   766 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.631   766   766 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.631   766  1365 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/168_task.xml
,08-23 13:54:22.631   766   766 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.631   766   766 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.641   766   766 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.641   766  1365 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/168_task_thumbnail.png
,08-23 13:54:22.641   766   766 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.641   766   865 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15172a5 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a0cc74 4279:com.samsung.klmsagent/u0a18}
,08-23 13:54:22.641   766   849 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
08-23 13:54:22.641   766   849 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-23 13:54:22.641   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.651  2075  2484 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 13:54:22.651  4279  4279 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Aug 23 13:54:22 GMT+02:00 2016
,08-23 13:54:22.651   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.651   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.661   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.661   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.661   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.661  4279  4279 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-23 13:54:22.661   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.661  1667  1667 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 13:54:22.661  4279  4279 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-23 13:54:22.671  3201  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 13:54:22.671  4279  4279 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671  3201  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671  3201  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671  3201  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766  1703 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766  2303 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15172a5 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b35f35 766:system/1000}
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.671  4279  4279 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-23 13:54:22.681  4279  6833 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-23 13:54:22.681  4279  6833 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
08-23 13:54:22.681  4279  6833 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-23 13:54:22.681  4279  6833 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-23 13:54:22.681  4279  6833 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-23 13:54:22.681  4279  6833 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
08-23 13:54:22.681   766   766 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.681   766   766 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.681  4279  6833 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-23 13:54:22.681   766   849 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.681  4279  6833 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-23 13:54:22.691   766   766 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.691   766   766 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.691  4279  6833 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
08-23 13:54:22.691  4279  6833 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
08-23 13:54:22.691   766   766 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.691   766   766 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.701   766  1323 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-23 13:54:22.701   766  1323 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-23 13:54:22.701   766   766 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.701   766   766 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.701  1662  6835 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
08-23 13:54:22.701  1662  6835 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
08-23 13:54:22.701   766   766 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.701   766   766 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
08-23 13:54:22.701  1662  6835 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-23 13:54:22.701  1662  6835 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-23 13:54:22.701  1662  6835 D RegisteredComponentCache: Collect Tech packages for Knox
08-23 13:54:22.701   766  1322 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-23 13:54:22.701   766  1322 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 13:54:22.701   766  1322 V NetworkStats: performPollLocked(flags=0x3)
08-23 13:54:22.711   766  1322 V NetworkStats: performPollLocked() took 5ms
08-23 13:54:22.711   766  1322 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 13:54:22.711   766  1322 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7334549c in tid 1322 (NetworkStats)
08-23 13:54:22.711  2218  2218 E audit_log: File locking failed. error= Bad file descriptor
08-23 13:54:22.711  2218  2218 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:54:22.791   292   292 I lowmemorykiller: ActivityManager disconnected
08-23 13:54:22.791   292   292 I lowmemorykiller: Closing Activity Manager data connection
,08-23 13:54:22.791   331   331 E installd: eof
08-23 13:54:22.791   331   331 E installd: failed to read size
08-23 13:54:22.791   331   331 I installd: closing connection
,08-23 13:54:22.791   293   293 I ServiceManager: service 'knox_ccm_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'enterprise_license_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'application_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'wifi_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'phone_restriction_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'remoteinjection' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'knox_ucsm_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'edm_proxy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'mum_container_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'enterprise_billing_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'otp_service' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'enterprise_shared_device_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'knox_timakeystore_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'enterprise_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'statusbar' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'clipboard' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'clipboardEx' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'network_management' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'ABTPersistenceService' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'textservices' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'network_score' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'netstats' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'netpolicy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'wifip2p' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'wifi' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'wifihs20' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'wifiscanner' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'rttmanager' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'ethernet' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'connectivity' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'sb_service' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'servicediscovery' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'updatelock' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'notification' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'devicestoragemonitor' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'location' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'country_detector' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'sec_location' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'search' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'execute' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'dropbox' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'wallpaper' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'audio' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'DockObserver' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'midi' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'usb' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'serial' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'kiesusb' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'jobscheduler' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'backup' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'appwidget' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'voiceinteraction' died
08-23 13:54:22.791  , 293   293 I ServiceManager: service 'SecExternalDisplayService' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'diskstats' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'mDNIe' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'AAS' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'MSCS' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'spengestureservice' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'quickconnect' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'samplingprofiler' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'commontime_management' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'dreams' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'graphicsstats' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'print' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'restrictions' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'media_session' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'media_router' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'trust' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'fingerprint' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'sec_analytics' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'telecom' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'activity' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'user' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'procstats' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'meminfo' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'gfxinfo' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'dbinfo' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'cpuinfo' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'permission' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'processinfo' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'sensorservice' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'mdm.remotedesktop' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'battery' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'usagestats' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'webviewupdate' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'scheduling_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'telephony.registry' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'persona' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'edmnativehelper' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'alarm' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'context_aware' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'scontext' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'barbeam' died
,08-23 13:54:22.791   293   293 I ServiceManager: service 'multiwindow_facade' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'window' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'input' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'launcherapps' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'voip' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'bluetooth_manager' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'rcp' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'persona_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'package' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'lpnet' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'imms' died
,08-23 13:54:22.791   293   293 I ServiceManager: service 'SEAMService' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'media.camera.proxy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'account' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'content' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'DirEncryptService' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'LSManager' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'ReactiveService' died
,08-23 13:54:22.791   293   293 I ServiceManager: service 'DeviceRootKeyService' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'EngineeringModeService' died,
08-23 13:54:22.791   293   293 I ServiceManager: service 'SatsService' died
,08-23 13:54:22.791   293   293 I ServiceManager: service 'sedenial' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'vibrator' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'tw_toolbox' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'tima' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'iccc' died
08-23 13:54:22.801  2218  2218 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:54:22.791   293   293 I ServiceManager: service 'cepproxyks' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'emailksproxy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'CustomFrequencyManagerService' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'consumer_ir' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'input_method' died
,08-23 13:54:22.791   293   293 I ServiceManager: service 'accessibility' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'cover' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'mount' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'lock_settings' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'deviceidle' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'device_policy' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'harmony_eas_service' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'sdp' died
08-23 13:54:22.791   293   293 I ServiceManager: service 'sdp_log' died
,08-23 13:54:22.791   293   293 I ServiceManager: service 'dlp' died
08-23 13:54:22.801   293   293 I ServiceManager: service 'log_manager_service' died
08-23 13:54:22.801   293   293 I ServiceManager: service 'uimode' died
08-23 13:54:22.801   293   293 I ServiceManager: service 'batterystats' died
08-23 13:54:22.801   293   293 I ServiceManager: service 'appops' died
08-23 13:54:22.801   293   293 I ServiceManager: service 'power' died
08-23 13:54:22.801   293   293 I ServiceManager: service 'display' died
,08-23 13:54:22.801   293   293 I ServiceManager: service 'media_projection' died
08-23 13:54:22.801  1687  1699 W Sensors : sensorservice died [0xacee3240]
08-23 13:54:22.801   294   358 D libEGL  : eglTerminate EGLDisplay = 0xb69816fc
08-23 13:54:22.801   294   358 D libEGL  : eglTerminate EGLDisplay = 0xb69816fc
08-23 13:54:22.801  1382  1406 W Sensors : sensorservice died [0xaced3d80]
,08-23 13:54:22.801   294   358 I SurfaceFlinger: restart the boot-animation @ binderDied
08-23 13:54:22.801   294   294 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
08-23 13:54:22.801   294   294 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-23 13:54:22.801  1667  2418 E WifiManager: Channel connection lost
08-23 13:54:22.801  5738  5840 E WifiManager: Channel connection lost
08-23 13:54:22.801  2075  2481 E WifiManager: Channel connection lost
,08-23 13:54:22.801   294  4869 I SurfaceFlinger: id=2 Removed GocusedStac (5/9)
08-23 13:54:22.801  1662  1662 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x716012bd in tid 1662 (com.android.nfc)
08-23 13:54:22.801  1662  1662 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 13:54:22.801  1884  1897 W Sensors : sensorservice died [0xb3a72e00]
,08-23 13:54:22.811  1667  1667 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
,08-23 13:54:22.811  2274  2302 W Sensors : sensorservice died [0xb3a72cc0]
,08-23 13:54:22.811  2211  2211 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ecadc64 in tid 2211 (droid.bluetooth)
08-23 13:54:22.811  2075  2093 W Sensors : sensorservice died [0xacee3ec0]
,08-23 13:54:22.811  2211  2211 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 13:54:22.811  2218  2218 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:54:22.811  1382  1611 E WifiManager: Channel connection lost
,08-23 13:54:22.811   328   934 W AudioFlinger: power manager service died !!!
,08-23 13:54:22.811   328   934 W AudioFlinger: power manager service died !!!
,08-23 13:54:22.821  1811  1991 E WifiManager: Channel connection lost
,08-23 13:54:22.831   294  4869 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
,08-23 13:54:22.841   294  4869 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-23 13:54:22.841   294  4869 I SurfaceFlinger: id=9 Removed EimLayer(Di (3/6)
08-23 13:54:22.841   294  4869 I SurfaceFlinger: id=10 Removed EimLayer(An (0/5)
,08-23 13:54:22.841   293   293 I ServiceManager: service 'nfc' died
08-23 13:54:22.841   293   293 I ServiceManager: service 'secontroller' died
08-23 13:54:22.841   293   293 I ServiceManager: service 'nfccontroller' died
08-23 13:54:22.841   294  4869 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-23 13:54:22.841   294  4869 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-23 13:54:22.841   294  4869 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-23 13:54:22.841  3201  3216 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e620cf7 in tid 3216 (AccountChangeLi)
,08-23 13:54:22.841  5205  5205 D BluetoothA2dp: Proxy object disconnected
08-23 13:54:22.841  3201  3216 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 13:54:22.841  5205  5205 D A2dpProfile: Bluetooth service disconnected
,08-23 13:54:22.841  2218  2218 E audit_log: File locking failed. error= Bad file descriptor
08-23 13:54:22.841   294  1506 I SurfaceFlinger: id=5 Removed TtatusBar (3/4)
08-23 13:54:22.841   294  1506 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-23 13:54:22.841   294  1506 I SurfaceFlinger: id=6 Removed JmageWallpa (0/3)
08-23 13:54:22.841   294  1506 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/3)
08-23 13:54:22.841   294   361 I SurfaceFlinger: id=19 Removed Mauncher (0/2)
08-23 13:54:22.841   294   361 I SurfaceFlinger: id=15 Removed DolorFade (1/1)
08-23 13:54:22.841   294   361 I SurfaceFlinger: id=15 Removed DolorFade (-2/1)
08-23 13:54:22.841   294   361 I SurfaceFlinger: id=9 Removed EimLayer(Di (-2/1)
08-23 13:54:22.841   294   361 I SurfaceFlinger: id=10 Removed EimLayer(An (-2/1)
08-23 13:54:22.841   294   361 I SurfaceFlinger: id=18 Removed YUIInstallC (0/0)
08-23 13:54:22.841  2261  2261 D BluetoothA2dp: Proxy object disconnected
08-23 13:54:22.841   294  6836 I SurfaceFlinger: id=18 Removed YUIInstallC (-2/0)
08-23 13:54:22.841   294  6836 I SurfaceFlinger: id=19 Removed Mauncher (-2/0)
,08-23 13:54:22.841  5205  5205 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 13:54:22.841  5205  5205 D PanProfile: Bluetooth service disconnected
08-23 13:54:22.841  5205  5205 D BluetoothMap: Proxy object disconnected
08-23 13:54:22.841  5205  5205 D MapProfile: Bluetooth service disconnected
,08-23 13:54:22.841  5205  5205 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9582bd in tid 5205 (ndroid.settings)
,08-23 13:54:22.841  5205  5205 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 13:54:22.841  2218  2218 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:54:22.861   349   349 I Zygote  : Process 1662 exited due to signal (7)
,08-23 13:54:22.881   349   349 I Zygote  : Process 5205 exited due to signal (7)
,08-23 13:54:22.881   349   349 I Zygote  : Process 2211 exited due to signal (7)
,08-23 13:54:22.891   349   349 I Zygote  : Process 3201 exited due to signal (7)
,08-23 13:54:23.051   294   571 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-23 13:54:23.051   294   294 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-23 13:54:23.281  1811  1811 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x70f97afa in tid 1811 (earchbox:search)
08-23 13:54:23.281  1811  1811 F libc    : Unable to open connection to debuggerd: Connection refused
,08-23 13:54:23.281  2218  2218 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:54:23.301   294   294 I SurfaceFlinger: Disp[0] Orientation 0=>0
08-23 13:54:23.301   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a3a4
,08-23 13:54:23.301   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a38c
,08-23 13:54:23.301   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a38c
08-23 13:54:23.301   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a38c
,08-23 13:54:23.311   294   571 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-23 13:54:23.311   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a3a4
,08-23 13:54:23.311   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a38c
,08-23 13:54:23.311   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe82a3a4

```
