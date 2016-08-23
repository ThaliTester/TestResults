#### Test 82337235c8e499b_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-23 13:40:39.552  5333  5333 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-23 13:40:39.552  5333  5333 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-23 13:40:39.552  5333  5333 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-23 13:40:39.562  5333  5333 I art     : System.exit called, status: 0
08-23 13:40:39.562  5333  5333 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
08-23 13:40:39.622   764   778 I ActivityManager: Process com.samsung.aasaservice (pid 5333)(adj 0) has died(143,716)
08-23 13:40:39.622   764   778 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-23 13:40:39.622   764   778 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-23 13:40:39.622   764   778 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-23 13:40:39.632  5304  5304 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-23 13:40:39.652   764   821 I ActivityManager: Start proc 6270:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-23 13:40:39.652  6270  6270 E Zygote  : v2
08-23 13:40:39.652  6270  6270 I libpersona: KNOX_SDCARD checking this for 10014
08-23 13:40:39.652  6270  6270 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:39.652  6270  6270 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:39.652  6270  6270 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:39.652   764  1324 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 13:40:39.652  6270  6270 E Zygote  : accessInfo : 0
08-23 13:40:39.652  6270  6270 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-23 13:40:39.692  6270  6270 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:39.692  6270  6270 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:39.702   764  1730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11cca4d 6270:com.google.android.partnersetup/u0a14}
08-23 13:40:39.702   764  1324 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-23 13:40:39.712  6270  6270 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-23 13:40:39.722  6270  6270 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-23 13:40:39.752   764  1769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11cca4d 6270:com.google.android.partnersetup/u0a14}
08-23 13:40:39.782  6285  6285 E Zygote  : v2
08-23 13:40:39.782   764  1607 I ActivityManager: Start proc 6285:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-23 13:40:39.782  6285  6285 I libpersona: KNOX_SDCARD checking this for 10015
08-23 13:40:39.782  6285  6285 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:39.782  6285  6285 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:39.782  6285  6285 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:39.782  6285  6285 E Zygote  : accessInfo : 0
08-23 13:40:39.782   764  1324 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 13:40:39.782  6285  6285 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-23 13:40:39.782   764  1324 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 13:40:39.792   764  1626 I ActivityManager: Killing 5427:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
08-23 13:40:39.802  6285  6285 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:39.802  6285  6285 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:39.812   764  1765 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c88bc50 6285:com.samsung.groupcast/u0a15}
08-23 13:40:39.822   764  1675 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
08-23 13:40:39.822  6285  6285 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-23 13:40:39.862  6285  6285 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-23 13:40:39.882  6285  6285 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-23 13:40:39.882  6285  6285 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-23 13:40:39.882  6285  6285 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-23 13:40:39.882  6285  6285 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-23 13:40:39.882  6285  6285 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-23 13:40:39.882  6285  6285 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 13:40:39.882  6285  6285 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 13:40:39.882  6285  6285 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 13:40:39.882  6285  6285 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 13:40:39.882  6285  6285 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:39.882  6285  6285 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 13:40:39.882  6285  6285 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 13:40:39.882  6285  6285 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:40:39.882  6285  6285 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 13:40:39.882  6285  6285 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 13:40:39.892   764  1439 I ActivityManager: Killing 5439:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
08-23 13:40:39.902   764  1439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2629d64 1869:com.sec.android.app.shealth:remote/u0a34}
08-23 13:40:39.922   764  1675 I ActivityManager: Start proc 6297:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-23 13:40:39.922  6297  6297 E Zygote  : v2
08-23 13:40:39.922  6297  6297 I libpersona: KNOX_SDCARD checking this for 10041
08-23 13:40:39.922  6297  6297 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:39.922  6297  6297 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:39.922  6297  6297 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:39.922  6297  6297 E Zygote  : accessInfo : 0
08-23 13:40:39.922  6297  6297 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-23 13:40:39.932   764  3712 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
08-23 13:40:39.952  6297  6297 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:39.952  6297  6297 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:39.962   764   778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{578be49 6297:com.samsung.android.sdk.samsunglink/u0a41}
08-23 13:40:39.962  6297  6297 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-23 13:40:40.062  6297  6297 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 13:40:40.062  6297  6297 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-23 13:40:40.132  6297  6297 I SL_DEBUG: isLoggable:: isProductShip = 1
08-23 13:40:40.132  6297  6297 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-23 13:40:40.152   764  1607 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-23 13:40:40.162   764  1321 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-23 13:40:40.162   764   778 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-23 13:40:40.172   764  1769 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-23 13:40:40.172   764  1730 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-23 13:40:40.172   764   777 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-23 13:40:40.182   764  1765 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-23 13:40:40.182   764  1731 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-23 13:40:40.182   764  1439 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-23 13:40:40.192   764  1296 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-23 13:40:40.332  6297  6297 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-23 13:40:40.332  6297  6297 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-23 13:40:40.332  6297  6297 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-23 13:40:40.332  6297  6297 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-23 13:40:40.332  6297  6297 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-23 13:40:40.332  6297  6297 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-23 13:40:40.332  6297  6297 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 13:40:40.332  6297  6297 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 13:40:40.332  6297  6297 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 13:40:40.332  6297  6297 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 13:40:40.332  6297  6297 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:40.332  6297  6297 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 13:40:40.332  6297  6297 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 13:40:40.332  6297  6297 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:40:40.332  6297  6297 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 13:40:40.332  6297  6297 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 13:40:40.342   764  1296 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b544cdd 1662:android.process.acore/u0a19}
08-23 13:40:40.362   764  1675 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f80bbd 5084:com.sec.android.gallery3d/u0a47}
08-23 13:40:40.362  5084  5084 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-23 13:40:40.372   764  1769 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-23 13:40:40.392  6321  6321 E Zygote  : v2
08-23 13:40:40.392   764   777 I ActivityManager: Start proc 6321:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-23 13:40:40.392  6321  6321 I libpersona: KNOX_SDCARD checking this for 10050
08-23 13:40:40.392  6321  6321 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:40.392  6321  6321 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:40.392  6321  6321 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:40.402  6321  6321 E Zygote  : accessInfo : 0
08-23 13:40:40.402  6321  6321 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-23 13:40:40.442  6321  6321 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:40.442  6321  6321 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:40.462   764  1675 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{970cbb9 6321:com.sec.android.app.myfiles/u0a50}
08-23 13:40:40.472  6321  6321 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-23 13:40:40.492  6321  6321 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-23 13:40:40.542  6321  6321 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-23 13:40:40.562   764  1607 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feaa7c3 2812:com.android.settings/1000}
08-23 13:40:40.582   332   332 E installd: system dir 0 : /system/app/
08-23 13:40:40.582   332   332 E installd: system dir 1 : /system/priv-app/
08-23 13:40:40.582   332   332 E installd: system dir 2 : /vendor/app/
08-23 13:40:40.582   332   332 E installd: system dir 3 : /oem/app/
08-23 13:40:40.592   764  1769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feaa7c3 2812:com.android.settings/1000}
08-23 13:40:40.602   764   916 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-23 13:40:40.612  6336  6336 E Zygote  : v2
08-23 13:40:40.612  6336  6336 I libpersona: KNOX_SDCARD checking this for 10169
08-23 13:40:40.612  6336  6336 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:40.612  6336  6336 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:40.612  6336  6336 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:40.612   764  1730 I ActivityManager: Start proc 6336:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-23 13:40:40.622  6336  6336 E Zygote  : accessInfo : 0
08-23 13:40:40.622  6336  6336 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-23 13:40:40.642  6347  6347 E Zygote  : v2
08-23 13:40:40.642  6347  6347 I libpersona: KNOX_SDCARD checking this for 10210
08-23 13:40:40.642  6347  6347 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:40.652  2322  2322 E audit   : type=1400 msg=audit(1471952440.642:284): avc:  denied  { execmod } for  pid=6268 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:40:40.642   764   821 I ActivityManager: Start proc 6347:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-23 13:40:40.652  2322  2322 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:40.652  2322  2322 E audit   : type=1300 msg=audit(1471952440.642:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f35000 a1=51000 a2=5 a3=4 items=0 ppid=3564 ppcomm=adbd pid=6268 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:40:40.652  2322  2322 E audit   : type=1327 msg=audit(1471952440.642:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 13:40:40.652  2322  2322 E audit   : type=1320 msg=audit(1471952440.642:284): 
08-23 13:40:40.652  6347  6347 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:40.652  6347  6347 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:40.652  6347  6347 E Zygote  : accessInfo : 0
08-23 13:40:40.652  6347  6347 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-23 13:40:40.672  6336  6336 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:40.672  6336  6336 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:40.682   764  1767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{496a75 6336:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-23 13:40:40.702  6347  6347 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:40.702  6347  6347 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:40.712  6336  6336 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-23 13:40:40.712  6347  6347 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-23 13:40:40.722  2322  2322 E audit   : type=1400 msg=audit(1471952440.722:285): avc:  denied  { execmod } for  pid=6268 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:40:40.722  2322  2322 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:40.722  2322  2322 E audit   : type=1300 msg=audit(1471952440.722:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3efa000 a1=51000 a2=5 a3=4 items=0 ppid=3564 ppcomm=adbd pid=6268 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:40:40.722  2322  2322 E audit   : type=1327 msg=audit(1471952440.722:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 13:40:40.722  2322  2322 E audit   : type=1320 msg=audit(1471952440.722:285): 
08-23 13:40:40.732  6336  6336 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-23 13:40:40.732  6347  6347 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-23 13:40:40.742  6347  6347 D AASAservice: onCreate()
08-23 13:40:40.742  5304  5304 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-23 13:40:40.742   764  1675 I ActivityManager: Killing 5451:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-23 13:40:40.762   764   777 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-23 13:40:40.772   764  1296 I ActivityManager: Killing 4063:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
08-23 13:40:40.782   764  1296 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d47c107 1701:com.android.phone/1001}
08-23 13:40:40.782  2322  2322 E audit   : type=1400 msg=audit(1471952440.782:286): avc:  denied  { execmod } for  pid=6268 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:40:40.782  2322  2322 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:40.782  2322  2322 E audit   : type=1300 msg=audit(1471952440.782:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ef8000 a1=51000 a2=5 a3=4 items=0 ppid=3564 ppcomm=adbd pid=6268 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:40:40.782  2322  2322 E audit   : type=1327 msg=audit(1471952440.782:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 13:40:40.782  2322  2322 E audit   : type=1320 msg=audit(1471952440.782:286): 
08-23 13:40:40.782  6268  6268 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 13:40:40.792  6268  6268 D AndroidRuntime: CheckJNI is OFF
08-23 13:40:40.792  6268  6268 D AndroidRuntime: readGMSProperty: start
08-23 13:40:40.792  6268  6268 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:40:40.792  6268  6268 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:40:40.792  6268  6268 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:40:40.792  6268  6268 D AndroidRuntime: readGMSProperty: end
08-23 13:40:40.792  6268  6268 D AndroidRuntime: addProductProperty: start
08-23 13:40:40.792   764  1296 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a995db8 1818:com.google.android.googlequicksearchbox:search/u0a61}
08-23 13:40:40.792  6268  6268 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:40:40.792  6268  6268 W art     : aed5c000-b1c82000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:40:40.792  6268  6268 W art     : b1c82000-b3ef1000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:40:40.792  6268  6268 W art     : b3ef1000-b3ef2000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:40:40.792  6268  6268 W art     : b3ef2000-b3ef3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.792  6268  6268 W art     : b423a000-b4263000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:40:40.792  6268  6268 W art     : b4263000-b46b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 13:40:40.792  6268  6268 W art     : b46b1000-b46b2000 ---p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b46b2000-b46bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 13:40:40.792  6268  6268 W art     : b46bc000-b46bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 13:40:40.792  6268  6268 W art     : b46bd000-b46bf000 rw-p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b46bf000-b46c0000 r--p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 13:40:40.792  6268  6268 W art     : b47c6000-b47c9000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:40:40.792  6268  6268 W art     : b47c9000-b47ca000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:40:40.792  6268  6268 W art     : b47ca000-b47cb000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:40:40.792  6268  6268 W art     : b47cb000-b47cc000 r--p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b47cc000-b47ec000 r--s 00000000 00:0b 9219       /dev/__properties__
08-23 13:40:40.792  6268  6268 W art     : b47ec000-b51fd000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:40:40.792  6268  6268 W art     : b51fd000-b51fe000 ---p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b51fe000-b5247000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:40:40.792  6268  6268 W art     : b5247000-b5248000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:40:40.792  6268  6268 W art     : b5248000-b5250000 rw-p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b5250000-b5251000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.792  6268  6268 W art     : b5251000-b5286000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:40:40.792  6268  6268 W art     : b5286000-b5287000 ---p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b5287000-b5288000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:40:40.792  6268  6268 W art     : b5288000-b5289000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:40:40.792  6268  6268 W art     : b5289000-b52e1000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 13:40:40.792  6268  6268 W art     : b52e1000-b52e2000 ---p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b52e2000-b52e3000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 13:40:40.792  6268  6268 W art     : b52e3000-b52e4000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 13:40:40.792  6268  6268 W art     : b52e5000-b52eb000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:40:40.792  6268  6268 W art     : b52eb000-b52ec000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:40:40.792  6268  6268 W art     : b52ec000-b52ed000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:40:40.792  6268  6268 W art     : b52ed000-b52ef000 rw-p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b52f0000-b52fa000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:40:40.792  6268  6268 W art     : b52fa000-b52fd000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:40:40.792  6268  6268 W art     : b52fd000-b52fe000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:40:40.792  6268  6268 W art     : b52ff000-b5316000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:40:40.792  6268  6268 W art     : b5316000-b5317000 ---p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b5317000-b5318000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:40:40.792  6268  6268 W art     : b5318000-b5319000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:40:40.792  6268  6268 W art     : b531a000-b5324000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:40:40.792  6268  6268 W art     : b5324000-b5325000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:40:40.792  6268  6268 W art     : b5325000-b5326000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:40:40.792  6268  6268 W art     : b5326000-b532a000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:40:40.792  6268  6268 W art     : b532a000-b532b000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:40:40.792  6268  6268 W art     : b532b000-b532c000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:40:40.792  6268  6268 W art     : b532c000-b5342000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 13:40:40.792  6268  6268 W art     : b5342000-b5343000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 13:40:40.792  6268  6268 W art     : b5343000-b5344000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 13:40:40.792  6268  6268 W art     : b5344000-b5351000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:40:40.792  6268  6268 W art     : b5351000-b5352000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:40:40.792  6268  6268 W art     : b5352000-b5353000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:40:40.792  6268  6268 W art     : b5353000-b53b3000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 13:40:40.792  6268  6268 W art     : b53b3000-b53b6000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 13:40:40.802   764  1321 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
08-23 13:40:40.792  6268  6268 W art     : b53b6000-b53ba000 rw-p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b53ba000-b541b000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:40:40.792  6268  6268 W art     : b541b000-b541c000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:40:40.792  6268  6268 W art     : b541c000-b546b000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:40:40.792  6268  6268 W art     : b546b000-b546d000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:40:40.792  6268  6268 W art     : b546d000-b546e000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:40:40.792  6268  6268 W art     : b546e000-b546f000 rw-p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b546f000-b5476000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:40:40.792  6268  6268 W art     : b5476000-b5477000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:40:40.792  6268  6268 W art     : b5477000-b5478000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:40:40.792  6268  6268 W art     : b5479000-b547c000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:40:40.792  6268  6268 W art     : b547c000-b547d000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:40:40.792  6268  6268 W art     : b547d000-b547e000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:40:40.792  6268  6268 W art     : b547f000-b5483000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:40:40.792  6268  6268 W art     : b5483000-b5484000 ---p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b5484000-b5485000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:40:40.792  6268  6268 W art     : b5485000-b5486000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:40:40.792  6268  6268 W art     : b5487000-b54a4000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:40:40.792  6268  6268 W art     : b54a4000-b54a5000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:40:40.792  6268  6268 W art     : b54a5000-b54a6000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:40:40.792  6268  6268 W art     : b54a7000-b54ac000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:40:40.792  6268  6268 W art     : b54ac000-b54ad000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:40:40.792  6268  6268 W art     : b54ad000-b54ae000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:40:40.792  6268  6268 W art     : b54af000-b54e0000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:40:40.792  6268  6268 W art     : b54e0000-b54e3000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:40:40.792  6268  6268 W art     : b54e3000-b54e4000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:40:40.792  6268  6268 W art     : b54e5000-b5520000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 13:40:40.792  6268  6268 W art     : b5520000-b5521000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 13:40:40.792  6268  6268 W art     : b5521000-b5522000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 13:40:40.792  6268  6268 W art     : b5523000-b552a000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:40:40.792  6268  6268 W art     : b552a000-b552b000 ---p 00000000 00:00 0 
08-23 13:40:40.792  6268  6268 W art     : b552b000-b552c000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:40:40.792  6268  6268 W art     : b552c000-b552d000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:40:40.792  6268  6268 W art     : b552d000-b552e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b552e000-b5545000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:40:40.802  6268  6268 W art     : b5545000-b5546000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5546000-b5549000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:40:40.802  6268  6268 W art     : b5549000-b554a000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:40:40.802  6268  6268 W art     : b554a000-b5569000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:40:40.802  6268  6268 W art     : b5569000-b556a000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:40:40.802  6268  6268 W art     : b556a000-b556b000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:40:40.802  6268  6268 W art     : b556b000-b55a9000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 13:40:40.802  6268  6268 W art     : b55a9000-b55aa000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b55aa000-b55ac000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 13:40:40.802  6268  6268 W art     : b55ac000-b55ad000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 13:40:40.802  6268  6268 W art     : b55ae000-b55b5000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:40:40.802  6268  6268 W art     : b55b5000-b55b6000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:40:40.802  6268  6268 W art     : b55b6000-b55b7000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:40:40.802  6268  6268 W art     : b55b8000-b55bb000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:40:40.802  6268  6268 W art     : b55bb000-b55bc000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:40:40.802  6268  6268 W art     : b55bc000-b55bd000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:40:40.802  6268  6268 W art     : b55bd000-b55c3000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:40:40.802  6268  6268 W art     : b55c3000-b55c4000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b55c4000-b55c5000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:40:40.802  6268  6268 W art     : b55c5000-b55c6000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:40:40.802  6268  6268 W art     : b55c6000-b55cf000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:40:40.802  6268  6268 W art     : b55cf000-b55d0000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:40:40.802  6268  6268 W art     : b55d0000-b55d1000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:40:40.802  6268  6268 W art     : b55d1000-b5662000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:40:40.802  6268  6268 W art     : b5662000-b5663000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5663000-b566e000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:40:40.802  6268  6268 W art     : b566e000-b566f000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:40:40.802  6268  6268 W art     : b5670000-b5682000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 13:40:40.802  6268  6268 W art     : b5682000-b5683000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 13:40:40.802  6268  6268 W art     : b5683000-b5684000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 13:40:40.802  6268  6268 W art     : b5685000-b568a000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:40:40.802  6268  6268 W art     : b568a000-b568b000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:40:40.802  6268  6268 W art     : b568b000-b568c000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:40:40.802  6268  6268 W art     : b568d000-b56fa000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:40:40.802  6268  6268 W art     : b56fa000-b56fb000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b56fb000-b56fd000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:40:40.802  6268  6268 W art     : b56fd000-b56fe000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:40:40.802  6268  6268 W art     : b56fe000-b56ff000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b56ff000-b5706000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:40:40.802  6268  6268 W art     : b5706000-b5707000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:40:40.802  6268  6268 W art     : b5707000-b5708000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:40:40.802  6268  6268 W art     : b5709000-b5789000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:40:40.802  6268  6268 W art     : b5789000-b578a000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b578a000-b578b000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:40:40.802  6268  6268 W art     : b578b000-b578c000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:40:40.802  6268  6268 W art     : b578c000-b57a3000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b57a3000-b57da000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 13:40:40.802  6268  6268 W art     : ib/libqc-opt.so
08-23 13:40:40.802  6268  6268 W art     : b57da000-b57db000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:40:40.802  6268  6268 W art     : b57db000-b57dc000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:40:40.802  6268  6268 W art     : b57dc000-b57f8000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:40:40.802  6268  6268 W art     : b57f8000-b57f9000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:40:40.802  6268  6268 W art     : b57f9000-b57fa000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:40:40.802  6268  6268 W art     : b57fb000-b585c000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 13:40:40.802  6268  6268 W art     : b585c000-b585e000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 13:40:40.802  6268  6268 W art     : b585e000-b585f000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 13:40:40.802  6268  6268 W art     : b5860000-b5887000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 13:40:40.802  6268  6268 W art     : b5887000-b5888000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5888000-b5889000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 13:40:40.802  6268  6268 W art     : b5889000-b588a000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 13:40:40.802  6268  6268 W art     : b588b000-b5893000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:40:40.802  6268  6268 W art     : b5893000-b5895000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:40:40.802  6268  6268 W art     : b5895000-b5896000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:40:40.802  6268  6268 W art     : b5897000-b589a000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 13:40:40.802  6268  6268 W art     : b589a000-b589b000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 13:40:40.802  6268  6268 W art     : b589b000-b589c000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 13:40:40.802  6268  6268 W art     : b589c000-b58a0000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:40:40.802  6268  6268 W art     : b58a0000-b58a1000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b58a1000-b58a2000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:40:40.802  6268  6268 W art     : b58a2000-b58a3000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:40:40.802  6268  6268 W art     : b58a3000-b58b3000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 13:40:40.802  6268  6268 W art     : b58b3000-b58b4000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 13:40:40.802  6268  6268 W art     : b58b4000-b58b5000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 13:40:40.802  6268  6268 W art     : b58b5000-b58fb000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b58fb000-b5904000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 13:40:40.802  6268  6268 W art     : b5904000-b5905000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 13:40:40.802  6268  6268 W art     : b5905000-b5906000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 13:40:40.802  6268  6268 W art     : b5907000-b590c000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 13:40:40.802  6268  6268 W art     : b590c000-b590d000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 13:40:40.802  6268  6268 W art     : b590d000-b590e000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 13:40:40.802  6268  6268 W art     : b590e000-b5911000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:40:40.802  6268  6268 W art     : b5911000-b5912000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5912000-b5913000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:40:40.802  6268  6268 W art     : b5913000-b5914000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:40:40.802  6268  6268 W art     : b5915000-b592d000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:40:40.802  6268  6268 W art     : b592d000-b592e000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b592e000-b592f000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:40:40.802  6268  6268 W art     : b592f000-b5930000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:40:40.802  6268  6268 W art     : b5931000-b5acb000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:40:40.802  6268  6268 W art     : b5acb000-b5acc000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5acc000-b5ad9000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:40:40.802  6268  6268 W art     : b5ad9000-b5ada000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:40:40.802  6268  6268 W art     : b5ada000-b5ade000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 13:40:40.802  6268  6268 W art     : b5ade000-b5adf000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5adf000-b5ae0000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 13:40:40.802  6268  6268 W art     : b5ae0000-b5ae1000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 13:40:40.802  6268  6268 W art     : b5ae1000-b5af4000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:40:40.802  6268  6268 W art     : b5af4000-b5af5000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:40:40.802  6268  6268 W art     : b5af5000-b5af6000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:40:40.802  6268  6268 W art     : b5af7000-b5b42000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:40:40.802  6268  6268 W art     : b5b42000-b5b43000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:40:40.802  6268  6268 W art     : b5b43000-b5b44000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:40:40.802  6268  6268 W art     : b5b44000-b5b46000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5b46000-b5b47000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:40.802  6268  6268 W art     : b5b47000-b5b58000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:40:40.802  6268  6268 W art     : b5b58000-b5b59000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5b59000-b5b5a000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:40:40.802  6268  6268 W art     : b5b5a000-b5b5b000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:40:40.802  6268  6268 W art     : b5b5c000-b5b66000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:40:40.802  6268  6268 W art     : b5b66000-b5b68000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:40:40.802  6268  6268 W art     : b5b68000-b5b69000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:40:40.802  6268  6268 W art     : b5b69000-b5b82000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:40:40.802  6268  6268 W art     : b5b82000-b5b83000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:40:40.802  6268  6268 W art     : b5b83000-b5b86000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:40:40.802  6268  6268 W art     : b5b86000-b5b8a000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5b8a000-b5bfe000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 13:40:40.802  6268  6268 W art     : b5bfe000-b5bff000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5bff000-b5c02000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 13:40:40.802  6268  6268 W art     : b5c02000-b5c03000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 13:40:40.802  6268  6268 W art     : b5c04000-b5c07000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:40:40.802  6268  6268 W art     : b5c07000-b5c08000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:40:40.802  6268  6268 W art     : b5c08000-b5c09000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:40:40.802  6268  6268 W art     : b5c09000-b5c0a000 r--p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5c0a000-b5c0f000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:40:40.802  6268  6268 W art     : b5c0f000-b5c10000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:40:40.802  6268  6268 W art     : b5c10000-b5c11000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:40:40.802  6268  6268 W art     : b5c11000-b5c12000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b5c12000-b5c15000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:40:40.802  6268  6268 W art     : b5c15000-b5c16000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:40:40.802  6268  6268 W art     : b5c16000-b5c17000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:40:40.802  6268  6268 W art     : b5c17000-b5c18000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b5c18000-b5c1c000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:40:40.802  6268  6268 W art     : b5c1c000-b5c1d000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:40:40.802  6268  6268 W art     : b5c1d000-b5c1e000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:40:40.802  6268  6268 W art     : b5c1e000-b5c1f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:40.802  6268  6268 W art     : b5c1f000-b5c23000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:40:40.802  6268  6268 W art     : b5c23000-b5c24000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:40:40.802  6268  6268 W art     : b5c24000-b5c25000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:40:40.802  6268  6268 W art     : b5c25000-b5c26000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b5c26000-b5c34000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 13:40:40.802  6268  6268 W art     : b5c34000-b5c35000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b5c35000-b5c36000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 13:40:40.802  6268  6268 W art     : b5c36000-b5c37000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 13:40:40.802  6268  6268 W art     : b5c37000-b5c41000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:40:40.802  6268  6268 W art     : b5c41000-b5c44000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:40:40.802  6268  6268 W art     : b5c44000-b5c45000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:40:40.802  6268  6268 W art     : b5c45000-b5c46000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b5c46000-b5c50000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 13:40:40.802  6268  6268 W art     : b5c50000-b5c53000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 13:40:40.802  6268  6268 W art     : b5c53000-b5c54000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 13:40:40.802  6268  6268 W art     : b5c54000-b5c58000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:40:40.802  6268  6268 W art     : b5c58000-b5c59000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:40:40.802  6268  6268 W art     : b5c59000-b5c5a000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:40:40.802  6268  6268 W art     : b5c5a000-b5c5b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b5c5b000-b5c68000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:40:40.802  6268  6268 W art     : b5c68000-b5c6a000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:40:40.802  6268  6268 W art     : b5c6a000-b5c6b000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:40:40.802  6268  6268 W art     : b5c6b000-b607d000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 13:40:40.802  6268  6268 W art     : b607d000-b607e000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b607e000-b6087000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 13:40:40.802  6268  6268 W art     : b6087000-b608b000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 13:40:40.802  6268  6268 W art     : b608b000-b608c000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b608c000-b6093000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-23 13:40:40.802  6268  6268 W art     : ioutils.so
08-23 13:40:40.802  6268  6268 W art     : b6093000-b6094000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:40:40.802  6268  6268 W art     : b6094000-b6095000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:40:40.802  6268  6268 W art     : b6095000-b6096000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b6096000-b60b1000 r-xp 00000000
08-23 13:40:40.802  6268  6268 W art     :  b3:17 1184       /system/lib/libz.so
08-23 13:40:40.802  6268  6268 W art     : b60b1000-b60b2000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 13:40:40.802  6268  6268 W art     : b60b2000-b60b3000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 13:40:40.802  6268  6268 W art     : b60b3000-b60b4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b60b4000-b6100000 r-xp 00000000 b3:17 994        
08-23 13:40:40.802  6268  6268 W art     : /system/lib/libharfbuzz_ng.so
08-23 13:40:40.802  6268  6268 W art     : b6100000-b6101000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6101000-b6102000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:40:40.802  6268  6268 W art     : b6102000-b6103000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:40:40.802  6268  6268 W art     : b6103000-b6104000 r--p 00000000 00:00 0          [anon:li
08-23 13:40:40.802  6268  6268 W art     : nker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b6104000-b6108000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:40:40.802  6268  6268 W art     : b6108000-b6109000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6109000-b610a000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:40:40.802  6268  6268 W art     : b610a000-b610b000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-23 13:40:40.802  6268  6268 W art     : sbhost.so
08-23 13:40:40.802  6268  6268 W art     : b610b000-b6143000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:40:40.802  6268  6268 W art     : b6143000-b6144000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:40:40.802  6268  6268 W art     : b6144000-b6145000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:40:40.802  6268  6268 W art     : b6145000-b6146000 r--p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     :          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b6146000-b61e4000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 13:40:40.802  6268  6268 W art     : b61e4000-b61e5000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b61e5000-b6203000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 13:40:40.802  6268  6268 W art     : b6203000-b6204000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
08-23 13:40:40.802  6268  6268 W art     : .so
08-23 13:40:40.802  6268  6268 W art     : b6204000-b6377000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:40:40.802  6268  6268 W art     : b6377000-b6382000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:40:40.802  6268  6268 W art     : b6382000-b6383000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:40:40.802  6268  6268 W art     : b6383000-b649a000 r-xp 00000000
08-23 13:40:40.802  6268  6268 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-23 13:40:40.802  6268  6268 W art     : b649a000-b64a5000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:40:40.802  6268  6268 W art     : b64a5000-b64a6000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:40:40.802  6268  6268 W art     : b64a6000-b64aa000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b64aa000-b64ce000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
08-23 13:40:40.802  6268  6268 W art     : o
08-23 13:40:40.802  6268  6268 W art     : b64ce000-b64d0000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 13:40:40.802  6268  6268 W art     : b64d0000-b64d1000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 13:40:40.802  6268  6268 W art     : b64d1000-b6577000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 13:40:40.802  6268  6268 W art     : b6577000-b6584000 r--p 000a5000 b3:17 13
08-23 13:40:40.802  6268  6268 W art     : 2        /system/lib/libcrypto.so
08-23 13:40:40.802  6268  6268 W art     : b6584000-b6585000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 13:40:40.802  6268  6268 W art     : b6585000-b6586000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6586000-b65d9000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:40:40.802  6268  6268 W art     : b65d9000-b65da000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b65da000-b65db000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:40:40.802  6268  6268 W art     : b65db000-b65dc000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:40:40.802  6268  6268 W art     : b65dc000-b65e1000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b65e1000-b65f3000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 13:40:40.802  6268  6268 W art     : b65f3000-b65f4000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b65f4000-b65f5000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 13:40:40.802  6268  6268 W art     : b65f5000-b65f6000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 13:40:40.802  6268  6268 W art     : b65f6000-b65fd000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:40:40.802  6268  6268 W art     : b65fd000-b65fe000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:40:40.802  6268  6268 W art     : b65fe000-b65ff000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:40:40.802  6268  6268 W art     : b65ff000-b6600000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6600000-b6603000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 13:40:40.802  6268  6268 W art     : b6603000-b6604000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 13:40:40.802  6268  6268 W art     : b6604000-b6605000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 13:40:40.802  6268  6268 W art     : b6605000-b6609000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 13:40:40.802  6268  6268 W art     : b6609000-b660a000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 13:40:40.802  6268  6268 W art     : b660a000-b660b000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 13:40:40.802  6268  6268 W art     : b660b000-b6619000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:40:40.802  6268  6268 W art     : b6619000-b661a000 ---p 00000000 00:00 0 
,08-23 13:40:40.802  6268  6268 W art     : b661a000-b661b000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:40:40.802  6268  6268 W art     : b661b000-b661c000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:40:40.802  6268  6268 W art     : b661c000-b6625000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:40:40.802  6268  6268 W art     : b6625000-b6626000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:40:40.802  6268  6268 W art     : b6626000-b6627000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:40:40.802  6268  6268 W art     : b6627000-b668d000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 13:40:40.802  6268  6268 W art     : b668d000-b668e000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b668e000-b6690000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 13:40:40.802  6268  6268 W art     : b6690000-b6699000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 13:40:40.802  6268  6268 W art     : b6699000-b669c000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b669c000-b6733000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 13:40:40.802  6268  6268 W art     : b6733000-b6735000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 13:40:40.802  6268  6268 W art     : b6735000-b6736000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 13:40:40.802  6268  6268 W art     : b6736000-b6737000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6737000-b6a58000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 13:40:40.802  6268  6268 W art     : b6a58000-b6a59000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6a59000-b6a74000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 13:40:40.802  6268  6268 W art     : b6a74000-b6a78000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 13:40:40.802  6268  6268 W art     : b6a78000-b6a7d000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6a7d000-b6a85000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:40:40.802  6268  6268 W art     : b6a85000-b6a86000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:40:40.802  6268  6268 W art     : b6a86000-b6a87000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:40:40.802  6268  6268 W art     : b6a87000-b6ab5000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:40:40.802  6268  6268 W art     : b6ab5000-b6ab6000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6ab6000-b6abd000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:40:40.802  6268  6268 W art     : b6abd000-b6abe000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:40:40.802  6268  6268 W art     : b6abe000-b6b04000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:40:40.802  6268  6268 W art     : b6b04000-b6b05000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6b05000-b6b08000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:40:40.802  6268  6268 W art     : b6b08000-b6b09000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:40:40.802  6268  6268 W art     : b6b09000-b6b24000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 13:40:40.802  6268  6268 W art     : b6b24000-b6b28000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 13:40:40.802  6268  6268 W art     : b6b28000-b6b29000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 13:40:40.802  6268  6268 W art     : b6b29000-b6b76000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 13:40:40.802  6268  6268 W art     : b6b76000-b6b77000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6b77000-b6b83000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 13:40:40.802  6268  6268 W art     : b6b83000-b6b84000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 13:40:40.802  6268  6268 W art     : b6b84000-b6b91000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 13:40:40.802  6268  6268 W art     : b6b91000-b6b92000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6b92000-b6b93000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 13:40:40.802  6268  6268 W art     : b6b93000-b6b94000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 13:40:40.802  6268  6268 W art     : b6b94000-b6b9c000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:40:40.802  6268  6268 W art     : b6b9c000-b6b9d000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6b9d000-b6b9e000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:40:40.802  6268  6268 W art     : b6b9e000-b6b9f000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:40:40.802  6268  6268 W art     : b6b9f000-b6ba6000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:40:40.802  6268  6268 W art     : b6ba6000-b6ba7000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:40:40.802  6268  6268 W art     : b6ba7000-b6ba8000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:40:40.802  6268  6268 W art     : b6ba8000-b6bbc000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 13:40:40.802  6268  6268 W art     : b6bbc000-b6bbe000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 13:40:40.802  6268  6268 W art     : b6bbe000-b6bbf000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 13:40:40.802  6268  6268 W art     : b6bbf000-b6be7000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:40:40.802  6268  6268 W art     : b6be7000-b6be9000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:40:40.802  6268  6268 W art     : b6be9000-b6bea000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:40:40.802  6268  6268 W art     : b6bea000-b6bed000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:40:40.802  6268  6268 W art     : b6bed000-b6bee000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:40:40.802  6268  6268 W art     : b6bee000-b6bef000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:40:40.802  6268  6268 W art     : b6bef000-b6bf8000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:40:40.852   764  3452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-23 13:40:40.802  6268  6268 W art     : b6bf8000-b6bf9000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:40:40.802  6268  6268 W art     : b6bf9000-b6bfa000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:40:40.802  6268  6268 W art     : b6bfa000-b6c1a000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 13:40:40.802  6268  6268 W art     : b6c1a000-b6c1b000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 13:40:40.802  6268  6268 W art     : b6c1b000-b6c1c000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 13:40:40.802  6268  6268 W art     : b6c1c000-b6c8f000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 13:40:40.802  6268  6268 W art     : b6c8f000-b6c93000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 13:40:40.802  6268  6268 W art     : b6c93000-b6c96000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 13:40:40.802  6268  6268 W art     : b6c96000-b6ca0000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6ca0000-b6d28000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 13:40:40.802  6268  6268 W art     : b6d28000-b6d29000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6d29000-b6d2d000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 13:40:40.802  6268  6268 W art     : b6d2d000-b6d2e000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 13:40:40.802  6268  6268 W art     : b6d2e000-b6d2f000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6d2f000-b6d58000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:40:40.802  6268  6268 W art     : b6d58000-b6d59000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6d59000-b6d5c000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:40:40.852   764  3712 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a995db8 1818:com.google.android.googlequicksearchbox:search/u0a61}
08-23 13:40:40.802  6268  6268 W art     : b6d5c000-b6d5d000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:40:40.802  6268  6268 W art     : b6d5d000-b6e37000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:40:40.802  6268  6268 W art     : b6e37000-b6e3e000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:40:40.802  6268  6268 W art     : b6e3e000-b6e46000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:40:40.802  6268  6268 W art     : b6e46000-b6e47000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6e47000-b6e48000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:40.802  6268  6268 W art     : b6e48000-b6e49000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 13:40:40.802  6268  6268 W art     : b6e49000-b6e4a000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b6e4a000-b6e4d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b6e4d000-b6e72000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 13:40:40.802  6268  6268 W art     : b6e72000-b6e73000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6e73000-b6e7a000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 13:40:40.802  6268  6268 W art     : b6e7a000-b6e7b000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 13:40:40.802  6268  6268 W art     : b6e7b000-b6e82000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 13:40:40.802  6268  6268 W art     : b6e82000-b6e83000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 13:40:40.802  6268  6268 W art     : b6e83000-b6e84000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 13:40:40.802  6268  6268 W art     : b6e84000-b6e85000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b6e85000-b6e9d000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 13:40:40.802  6268  6268 W art     : b6e9d000-b6e9e000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6e9e000-b6e9f000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 13:40:40.802  6268  6268 W art     : b6e9f000-b6ea0000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 13:40:40.802  6268  6268 W art     : b6ea0000-b6eae000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 13:40:40.802  6268  6268 W art     : b6eae000-b6eaf000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6eaf000-b6eb0000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 13:40:40.802  6268  6268 W art     : b6eb0000-b6eb1000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 13:40:40.802  6268  6268 W art     : b6eb1000-b6eb2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:40.802  6268  6268 W art     : b6eb2000-b6eb4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b6eb4000-b6eb5000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b6eb5000-b6eb6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:40.802  6268  6268 W art     : b6eb6000-b6eb7000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 13:40:40.802  6268  6268 W art     : b6eb7000-b6eb8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:40.802  6268  6268 W art     : b6eb8000-b6ed8000 r--s 00000000 00:0b 9219       /dev/__properties__
08-23 13:40:40.802  6268  6268 W art     : b6ed8000-b6ed9000 r--p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6ed9000-b6eda000 ---p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6eda000-b6edc000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 13:40:40.802  6268  6268 W art     : b6edc000-b6edd000 r-xp 00000000 00:00 0          [sigpage]
08-23 13:40:40.802  6268  6268 W art     : b6edd000-b6ef8000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 13:40:40.802  6268  6268 W art     : b6ef8000-b6ef9000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 13:40:40.802  6268  6268 W art     : b6ef9000-b6efb000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 13:40:40.802  6268  6268 W art     : b6efb000-b6efd000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : b6efd000-b6f02000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 13:40:40.802  6268  6268 W art     : b6f02000-b6f03000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 13:40:40.802  6268  6268 W art     : b6f03000-b6f04000 rw-p 00000000 00:00 0 
08-23 13:40:40.802  6268  6268 W art     : bea9b000-beabc000 rw-p 00000000 00:00 0          [stack]
08-23 13:40:40.802  6268  6268 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 13:40:40.852  6268  6268 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 13:40:40.862   764   778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{40d227b 6210:com.samsung.android.sm.provider/1000}
08-23 13:40:40.892   764  1731 I ActivityManager: Start proc 6367:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-23 13:40:40.892  6367  6367 E Zygote  : v2
08-23 13:40:40.892  6367  6367 I libpersona: KNOX_SDCARD checking this for 5012
08-23 13:40:40.892  6367  6367 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:40.892  6367  6367 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:40.892  6367  6367 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:40.892  6367  6367 E Zygote  : accessInfo : 0
08-23 13:40:40.892  6367  6367 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-23 13:40:40.912  6268  6268 I Radio-JNI: register_android_hardware_Radio DONE
08-23 13:40:40.912  1818  6360 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 13:40:40.922  6268  6268 E AffinityControl: AffinityControl: registerfunction enter
08-23 13:40:40.942  6268  6268 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 13:40:40.952  6367  6367 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:40.952  6367  6367 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:40.962   764  1607 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-23 13:40:40.982   764  1607 D ActivityManager: mDVFSHelper.acquire()
08-23 13:40:40.982   764  1607 V WindowManager: addAppToken: AppWindowToken{faedcd6 token=Token{bd338f1 ActivityRecord{3b5898 u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-23 13:40:40.992   764   879 D SecWifiDisplayUtil: Metadata value : none
08-23 13:40:40.992   764   879 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3c4b0ae V.E...... R.....ID 0,0-0,0}
08-23 13:40:40.992   764   879 D ISSUE_DEBUG: InputChannelName : bed39dc Starting com.test.thalitest
08-23 13:40:40.992   764  1607 I ActivityManager: Start proc 6381:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-23 13:40:41.002  6381  6381 E Zygote  : v2
08-23 13:40:41.002  6381  6381 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:41.002  6381  6381 I libpersona: KNOX_SDCARD checking this for 10004
08-23 13:40:41.002  6381  6381 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:41.002  6381  6381 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:41.002  6381  6381 E Zygote  : accessInfo : 0
08-23 13:40:41.002  6381  6381 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-23 13:40:41.002   764  1607 D InputDispatcher: Focused application set to: xxxx
08-23 13:40:41.012  1818  6360 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-23 13:40:41.012   764  1607 D InputDispatcher: Focus left window: 4455
08-23 13:40:41.022   294   294 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-23 13:40:41.022  6268  6268 D AndroidRuntime: Shutting down VM
08-23 13:40:41.032   764  1765 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cadae5 6367:com.samsung.android.sm.devicesecurity/5012}
08-23 13:40:41.032   764   823 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{20fc271 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-23 13:40:41.032  1385  1385 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-23 13:40:41.032   764   879 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:764 uid:1000
08-23 13:40:41.032   764   879 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:40:41.032   764   879 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:764 uid:1000
08-23 13:40:41.032   764   879 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 13:40:41.032   764   879 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-23 13:40:41.042  6381  6381 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:41.042  6381  6381 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:41.042   764  1607 V WindowOrientationListener: setCurrentAppOrientation :-1
08-23 13:40:41.042  1818  6360 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-23 13:40:41.042   764  1607 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-23 13:40:41.052   764   823 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{bed39dc u0 d0 Starting com.test.thalitest}
08-23 13:40:41.052  1385  1385 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-23 13:40:41.072  6367  6367 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-23 13:40:41.072   764  1607 D ActivityManager:  Launching com.test.thalitest, updated priority
08-23 13:40:41.092   764   879 V WindowStateAnimator: Finishing drawing window Window{bed39dc u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-23 13:40:41.092  1716  1856 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-23 13:40:41.092  1716  1716 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-23 13:40:41.092   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec41364
08-23 13:40:41.102  6367  6367 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-23 13:40:41.102   294   363 I SurfaceFlinger: id=19 Removed YUIInstallC (6/10)
08-23 13:40:41.102   294   358 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/10)
08-23 13:40:41.102   294   363 D libEGL  : eglTerminate EGLDisplay = 0xb66bf64c
08-23 13:40:41.102   294   363 D libEGL  : eglTerminate EGLDisplay = 0xb66bf64c
08-23 13:40:41.102   294   363 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
08-23 13:40:41.102   294   906 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-23 13:40:41.112  4455  4455 V ActivityThread: updateVisibility : ActivityRecord{6c33abc token=android.os.BinderProxy@3cbdc1d {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-23 13:40:41.112   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec413a4
08-23 13:40:41.122  2184  2196 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-23 13:40:41.122  1716  1716 V ActivityThread: updateVisibility : ActivityRecord{c879b33 token=android.os.BinderProxy@8496ddd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 13:40:41.122  1716  1716 D Launcher: onTrimMemory. Level: 20
08-23 13:40:41.422   764  1607 I WindowManager: Screenshot max retries 4 of Token{bd338f1 ActivityRecord{3b5898 u0 com.test.thalitest/.MainActivity t168}} appWin=Window{bed39dc u0 d0 Starting com.test.thalitest} drawState=4
08-23 13:40:41.422   764   821 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-23 13:40:41.452  6381  6381 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 13:40:41.462   764  3422 D M       : limitCPUFreq:: freq = -1
08-23 13:40:41.462   764  3422 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 764  tag : SIOP_ARM_MAX@25
08-23 13:40:41.462   764  3422 D M       : limitGPUFreq:: freq = -1
08-23 13:40:41.472   764  3422 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-23 13:40:41.482   764  1296 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-23 13:40:41.502  6381  6381 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 13:40:41.502  6381  6381 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 13:40:41.522  6381  6381 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
08-23 13:40:41.522   764  1439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{146ff3a 3180:com.android.contacts/u0a19}
08-23 13:40:41.542   764  1607 I ActivityManager: Start proc 6398:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-23 13:40:41.542  6398  6398 E Zygote  : v2
08-23 13:40:41.542  6398  6398 I libpersona: KNOX_SDCARD checking this for 10049
08-23 13:40:41.542  6398  6398 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:41.542  6398  6398 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:41.542  6398  6398 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:41.542  6398  6398 E Zygote  : accessInfo : 0
08-23 13:40:41.542  6398  6398 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-23 13:40:41.572  6381  6381 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 13:40:41.582  6381  6381 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 13:40:41.592  6398  6398 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:41.592  6398  6398 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:41.602  6381  6381 I cr_LibraryLoader: Time to load native libraries: 5 ms (timestamps 6637-6642)
08-23 13:40:41.602  6381  6381 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-23 13:40:41.602   764  1626 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d5b1e3 6398:com.android.mms/u0a49}
08-23 13:40:41.622  6381  6381 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {77b2a2d}
08-23 13:40:41.622  6381  6381 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-23 13:40:41.622  6381  6381 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 13:40:41.622  6398  6398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-23 13:40:41.632  6381  6417 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
08-23 13:40:41.632  6381  6381 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
08-23 13:40:41.642  4172  6397 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-23 13:40:41.662  1818  6360 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 743 ms] updated apps [took 743 ms] 
08-23 13:40:41.672  6398  6398 W System  : ClassLoader referenced unknown path: imsmanager.jar
08-23 13:40:41.672  6381  6381 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 13:40:41.672  6381  6381 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 13:40:41.672  6381  6381 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 13:40:41.672  6381  6381 I Adreno-EGL: Local Branch: ss
08-23 13:40:41.672  6381  6381 I Adreno-EGL: Remote Branch: 
08-23 13:40:41.672  6381  6381 I Adreno-EGL: Local Patches: 
08-23 13:40:41.672  6381  6381 I Adreno-EGL: Reconstruct Branch: 
08-23 13:40:41.672  6398  6398 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-23 13:40:41.672  6381  6381 D libEGL  : eglInitialize EGLDisplay = 0xbeb5cdac
08-23 13:40:41.712   764  1626 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
08-23 13:40:41.722   764  1626 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
08-23 13:40:41.732  6398  6398 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-23 13:40:41.742  6398  6438 D Mms/ArtClassLoader: init before art third
08-23 13:40:41.752  6398  6437 D Mms/ArtClassLoader: init before art second
08-23 13:40:41.752  6398  6398 D Mms/TelephonyPermission: start operation mode monitor
08-23 13:40:41.752  6398  6398 D Mms/TelephonyPermission: User ID is null set current User Id
08-23 13:40:41.752  6398  6436 D Mms/ArtClassLoader: init before art first
08-23 13:40:41.762  6398  6398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-23 13:40:41.772  6398  6398 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
08-23 13:40:41.772  6381  6381 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
08-23 13:40:41.782  6398  6398 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-23 13:40:41.782  6398  6398 D Mms/TelephonyPermission: isDefault true
08-23 13:40:41.782  6398  6398 D Mms/MmsApp: onCreate() com.android.mms
08-23 13:40:41.782  6381  6381 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 13:40:41.782  6381  6381 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
08-23 13:40:41.792  6381  6381 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
08-23 13:40:41.792  6381  6381 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
08-23 13:40:41.812  6381  6381 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
08-23 13:40:41.812  6398  6438 D Mms/ArtClassLoader: init [DONE] art
08-23 13:40:41.812  6381  6381 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-23 13:40:41.832  6398  6398 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
08-23 13:40:41.832  6398  6398 D Mms/MmsApp: [start]    initCountryIso consume time = 99.471718
08-23 13:40:41.832   764  1730 D CountryDetector: The first listener is added
08-23 13:40:41.842  6398  6398 D Mms/MmsApp: [end]    initCountryIso consume time = 7.871876
08-23 13:40:41.842  6398  6398 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.096406
08-23 13:40:41.852  6398  6398 D Mms/MmsConfig: before partial update
08-23 13:40:41.892  6398  6398 D Mms/MmsConfig: Load Resize quality : 80
08-23 13:40:41.892  6398  6436 D Mms/ArtClassLoader: init [DONE] art
08-23 13:40:41.902  6398  6437 D Mms/ArtClassLoader: init [DONE] art
08-23 13:40:41.912  6398  6398 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 13:40:41.912  6398  6398 D EasySignUpManager_1.0.5: isAuth is false
08-23 13:40:41.912  6398  6398 I EasySignUpManager_1.0.5: auth : false, join : 2
08-23 13:40:41.912  6398  6398 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
08-23 13:40:41.912  6398  6398 D EasySignUpManager_1.0.5: userSerialNumber = 0
08-23 13:40:41.912  6398  6398 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 13:40:41.912  6398  6398 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
08-23 13:40:41.912  6398  6398 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 13:40:41.912  6398  6398 D EasySignUpManager_1.0.5: isAuth is false
08-23 13:40:41.912  6398  6398 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-23 13:40:41.912  6398  6398 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
08-23 13:40:41.922  6381  6381 D SecWifiDisplayUtil: Metadata value : none
08-23 13:40:41.922   764   821 W ActivityManager: Activity pause timeout for ActivityRecord{3b5898 u0 com.test.thalitest/.MainActivity t168}
08-23 13:40:41.922  6381  6381 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9ec68d3 I.E...... R.....ID 0,0-0,0}
08-23 13:40:41.922  1701  1714 D TP/MmsSmsProvider: query, match:2117, calling pid = 6398, accessRestricted = false
08-23 13:40:41.922  6381  6449 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-23 13:40:41.932  1701  1714 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 3.022 ms
08-23 13:40:41.932   764  1675 D ISSUE_DEBUG: InputChannelName : 686466c com.test.thalitest/com.test.thalitest.MainActivity
08-23 13:40:41.932   764   778 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-23 13:40:41.932   764   778 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 13:40:41.932   764   764 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 13:40:41.942   764   764 I KnoxTimeoutHandler: Shared devices show user statefalse
08-23 13:40:41.942  6398  6398 E CscParser: mps_code.dat does not exist
08-23 13:40:41.942  6398  6398 E CscParser: customer_path =/system/csc/customer.xml
08-23 13:40:41.942  6398  6398 E CscParser: fileName + /system/csc/customer.xml
08-23 13:40:41.952  6398  6398 E CscParser: mps_code.dat does not exist
08-23 13:40:41.952  6398  6398 E CscParser: customer_path =/system/csc/customer.xml
08-23 13:40:41.952  6398  6398 E CscParser: fileName + /system/csc/customer.xml
08-23 13:40:41.952  6381  6381 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6381
08-23 13:40:41.952   764   778 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6381 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 13:40:41.952   764  1333 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-23 13:40:41.952   764  1333 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-23 13:40:41.952   764  1333 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-23 13:40:41.952   764  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:40:41.952   764  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:40:41.952   764  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-23 13:40:41.952   764  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:40:41.962   764  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:40:41.962   764  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-23 13:40:41.962   764  1333 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 13:40:41.962  6398  6398 D CscParser: getInstance fileName =/system/csc/customer.xml
08-23 13:40:41.962  6398  6398 D Mms/MmsConfig:  enable multiwindow = true
08-23 13:40:41.962  6398  6398 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
08-23 13:40:41.962  6398  6398 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-23 13:40:41.962  6398  6398 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-23 13:40:41.962  6398  6398 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-23 13:40:41.962  6398  6398 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-23 13:40:41.962  6398  6398 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-23 13:40:41.962  6398  6398 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-23 13:40:41.972  6381  6381 V ActivityThread: updateVisibility : ActivityRecord{f04c6c5 token=android.os.BinderProxy@571b2c2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 13:40:41.972  6381  6417 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
08-23 13:40:41.982  6381  6381 D SecWifiDisplayUtil: Metadata value : none
08-23 13:40:41.982  6398  6398 D Mms/MmsConfig: [end]    init() consume time = 136.024896
08-23 13:40:41.982  6398  6398 D Mms/Contact: [start]    init() consume time = 4.262812
08-23 13:40:41.992   294   294 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
08-23 13:40:41.992  1701  1713 D TP/MmsSmsProvider: query, match:13, calling pid = 6398, accessRestricted = false
08-23 13:40:41.992  1701  1713 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.082 ms
08-23 13:40:42.002  6398  6398 D Mms/Contact: [end]    init consume time = 23.590781
08-23 13:40:42.012   764  1675 D InputDispatcher: Focus entered window: 6381
08-23 13:40:42.012   764   879 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:764 uid:1000
08-23 13:40:42.012   764   879 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:40:42.012   764   879 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:764 uid:1000
08-23 13:40:42.012   764   879 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 13:40:42.012  6398  6456 D Mms/DraftCache: [start]    rebuildCache consume time = 3.982136
08-23 13:40:42.012  6381  6449 D libEGL  : eglInitialize EGLDisplay = 0x9c97a7c4
08-23 13:40:42.012  6381  6449 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 13:40:42.012  6398  6398 D Mms:transaction: roaming -> false (slotId = 0)
08-23 13:40:42.012  6398  6398 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 13:40:42.012  6398  6398 D Mms:transaction: auto download without roaming -> true
08-23 13:40:42.012  6398  6398 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-23 13:40:42.012  6398  6398 D Mms:transaction: roaming -> false (slotId = 1)
08-23 13:40:42.012  6398  6398 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-23 13:40:42.012  6398  6398 D Mms:transaction: auto download without roaming -> true
08-23 13:40:42.022  6398  6398 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-23 13:40:42.022  6398  6398 D Mms:transaction: auto download during roaming secondary -> false
08-23 13:40:42.022  6398  6398 D Mms:transaction: mAutoDownload ------> true
08-23 13:40:42.022  1701  1958 D TP/MmsSmsProvider: query, match:12, calling pid = 6398, accessRestricted = false
08-23 13:40:42.022  1701  1958 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.178 ms
08-23 13:40:42.022  6398  6456 D Mms/DraftCache: [end]    rebuildCache consume time = 11.469271
08-23 13:40:42.042  6398  6398 D ComposerPerformance: 1471952442049 ms / [DONE] Composer constructor
08-23 13:40:42.042  6398  6398 D CII     : Log Level [5]
08-23 13:40:42.042  6398  6398 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
08-23 13:40:42.042  6398  6458 D Mms/Conversation: [start]    init() consume time = 22.514999
08-23 13:40:42.042  1701  1713 D TP/MmsSmsProvider: delete, match:1, calling pid = 6398
08-23 13:40:42.042  1701  1713 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-23 13:40:42.042  1701  1713 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
08-23 13:40:42.052  1701  1713 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
08-23 13:40:42.052  1701  1713 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-23 13:40:42.052  1701  1713 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-23 13:40:42.052  1701  1713 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
08-23 13:40:42.062  6381  6381 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-23 13:40:42.062   764  1439 V WindowStateAnimator: Finishing drawing window Window{686466c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-23 13:40:42.062  6381  6381 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-23 13:40:42.072  6381  6381 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-23 13:40:42.072   764   879 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 13:40:42.072   764  1730 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 13:40:42.072   764   879 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +654ms (total +1s93ms)
08-23 13:40:42.072   764   764 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 13:40:42.072   764   764 I KnoxTimeoutHandler: SD activityfalse
08-23 13:40:42.082   764   879 D ActivityManager: mDVFSHelper.release()
08-23 13:40:42.082   764   879 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3b5898 u0 com.test.thalitest/.MainActivity t168} time:107122
08-23 13:40:42.082  1701  1713 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-23 13:40:42.082  1701  1713 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-23 13:40:42.082  1701  1713 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-23 13:40:42.082  1701  1713 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 35.127 ms
08-23 13:40:42.082  1701  1713 D TP/MmsSmsProvider: need read changed broadcast:false
08-23 13:40:42.082  6398  6398 I Mms/ReservationManager: ReservationManager()
08-23 13:40:42.082   764   879 D ViewRootImpl: #3 mView = null
08-23 13:40:42.082   294   358 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
08-23 13:40:42.082   294   906 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
08-23 13:40:42.092   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec413a4
08-23 13:40:42.092  6398  6398 I Mms/ReservationManager: resetAfterConnected()
08-23 13:40:42.102  1701  1958 D TP/MmsSmsProvider: query, match:7, calling pid = 6398, accessRestricted = false
08-23 13:40:42.102  1701  1958 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.342 ms
08-23 13:40:42.102  6398  6398 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-23 13:40:42.112  6398  6458 D Mms/Conversation: [end]    init consume time = 66.767657
08-23 13:40:42.122   764  1296 V WindowStateAnimator: Finishing drawing window Window{686466c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
08-23 13:40:42.122  6398  6458 D Mms/MessagingNotification: [start]    init() consume time = 8.053438
08-23 13:40:42.122  6381  6381 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-23 13:40:42.122   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec41364
08-23 13:40:42.122  6398  6458 D Mms/MessagingNotification: [end]    init consume time = 3.917395
08-23 13:40:42.122  6381  6381 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@571b2c2 time:107166
08-23 13:40:42.122  6398  6398 D Mms/MmsApp: [end]    onCreate() consume time = 1.230573
08-23 13:40:42.122  6398  6398 D Mms/MmsApp: [end]    onCreate() consume time = 0.256146
08-23 13:40:42.122  6398  6398 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
08-23 13:40:42.122  6398  6465 D Mms/Synchronizer: [start]    doSync consume time = 1.324896
08-23 13:40:42.122  6398  6464 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.700104
08-23 13:40:42.132  6381  6462 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:40:42.132  6381  6462 D libEGL  : eglInitialize EGLDisplay = 0x9a1d03ec
08-23 13:40:42.132  1701  2107 D TP/MmsSmsProvider: query, match:0, calling pid = 6398, accessRestricted = false
08-23 13:40:42.132  1701  2107 V TP/MmsSmsProvider: getSimpleConversations entered.
08-23 13:40:42.132  1701  2107 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.421 ms
08-23 13:40:42.142   764  1769 I ActivityManager: Start proc 6467:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
08-23 13:40:42.142  6467  6467 E Zygote  : v2
08-23 13:40:42.142  6467  6467 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:42.142  6467  6467 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:42.142  6467  6467 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:42.142  6467  6467 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:42.142  6467  6467 E Zygote  : accessInfo : 0
08-23 13:40:42.142  6398  6398 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-23 13:40:42.142  6398  6398 D Mms:transaction: roaming -> false (slotId = 0)
08-23 13:40:42.142  6398  6398 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 13:40:42.142  6398  6398 D Mms:transaction: auto download without roaming -> true
08-23 13:40:42.142  6398  6398 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-23 13:40:42.142  6398  6398 D Mms:transaction: mAutoDownload ------> true
08-23 13:40:42.142   764  1769 I ActivityManager: Killing 5106:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
08-23 13:40:42.152  1701  1958 D TP/MmsSmsProvider: update, match:300, calling pid = 6398
08-23 13:40:42.152  1701  1958 V TP/MmsSmsProvider: syncDBData start
08-23 13:40:42.152  1701  1958 V TP/MmsSmsProvider: syncDBData sms end
08-23 13:40:42.152  1701  1958 V TP/MmsSmsProvider: syncDBData mms end
08-23 13:40:42.152  1701  1958 V TP/MmsSmsProvider: syncDBData end
08-23 13:40:42.152  1701  1958 D TP/MmsSmsProvider: update, match 300:Elapsed time : 1.840 ms
08-23 13:40:42.152  6398  6465 D Mms/Synchronizer: [end]    doSync consume time = 28.902083
08-23 13:40:42.162   764  1675 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
08-23 13:40:42.172  1701  1714 D TP/MmsSmsProvider: query, match:400, calling pid = 6398, accessRestricted = false
08-23 13:40:42.172  6016  6030 D BadgeProvider: query, [selection] : package=?
08-23 13:40:42.182  6398  6464 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 22.322032
08-23 13:40:42.182  6398  6458 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-23 13:40:42.182  6381  6381 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6381
08-23 13:40:42.202  6467  6467 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:42.202  6467  6467 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:42.202  1701  1713 D TP/SmsProvider: query,matched:26, calling pid = 6398
08-23 13:40:42.202  1701  1713 D TP/SmsProvider: query, match 26:Elapsed time : 1.095 ms
08-23 13:40:42.212   764  1321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c874a5 6467:com.samsung.android.bbc.bbcagent/1000}
08-23 13:40:42.242  1701  1714 D TP/MmsSmsProvider: query, match:6, calling pid = 6398, accessRestricted = false
08-23 13:40:42.242  1701  1714 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.008 ms
08-23 13:40:42.242  6467  6467 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
08-23 13:40:42.272  6480  6480 E Zygote  : v2
08-23 13:40:42.272   764   778 I ActivityManager: Start proc 6480:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-23 13:40:42.272  6480  6480 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:42.272  6480  6480 I libpersona: KNOX_SDCARD checking this for 10024
08-23 13:40:42.272  6480  6480 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:42.272  6480  6480 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:42.272  6480  6480 E Zygote  : accessInfo : 0
08-23 13:40:42.272  6480  6480 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
08-23 13:40:42.312  6480  6480 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:42.312  6480  6480 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:42.312   764  1730 I ActivityManager: Killing 5121:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
08-23 13:40:42.322   764   774 I art     : Background partial concurrent mark sweep GC freed 57609(3MB) AllocSpace objects, 8(300KB) LOS objects, 27% free, 42MB/58MB, paused 4.140ms total 134.118ms
08-23 13:40:42.332  6480  6480 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
08-23 13:40:42.342   764   777 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
08-23 13:40:42.342  6467  6467 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
08-23 13:40:42.352  6480  6480 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
08-23 13:40:42.382  6381  6381 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-23 13:40:42.392   764  1321 I ActivityManager: Start proc 6493:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-23 13:40:42.392   764  1321 I ActivityManager: Killing 5150:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-23 13:40:42.402  6493  6493 E Zygote  : v2
08-23 13:40:42.402  6493  6493 I libpersona: KNOX_SDCARD checking this for 10097
08-23 13:40:42.402  6493  6493 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:42.402  6493  6493 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:42.402  6493  6493 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:42.402  3488  3488 D FactoryTest: User mode
08-23 13:40:42.402  6493  6493 E Zygote  : accessInfo : 0
08-23 13:40:42.402  3488  3488 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-23 13:40:42.402  3488  3488 D MTPRx   : still no open session command from host, so toast
08-23 13:40:42.402  6493  6493 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
08-23 13:40:42.402   764  1765 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-23 13:40:42.412  6480  6480 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-23 13:40:42.412  6398  6458 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-23 13:40:42.422   764  1765 D ActivityManager: mDVFSHelper.acquire()
,08-23 13:40:42.422   764  1765 V WindowManager: addAppToken: AppWindowToken{8f8cc88 token=Token{8a9302b ActivityRecord{f82207a u0 com.samsung.android.MtpApplication/.USBConnection t169}}} to stack=1 task=169 at 0
,08-23 13:40:42.422   764  1765 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-23 13:40:42.442   764   821 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-23 13:40:42.442   764  3426 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-23 13:40:42.452  6493  6493 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:42.452  6493  6493 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:42.462   764  1765 D InputDispatcher: Focused application set to: xxxx
,08-23 13:40:42.462   764  1765 D InputDispatcher: Focus left window: 6381
,08-23 13:40:42.462   764   879 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:764 uid:1000
08-23 13:40:42.462   764   879 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:40:42.462   764   879 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:764 uid:1000
08-23 13:40:42.462   764   879 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 13:40:42.462  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-23 13:40:42.462  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-23 13:40:42.472  3488  3488 E MTPRx   : started activity for popup
,08-23 13:40:42.472  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-23 13:40:42.472  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-23 13:40:42.472  3488  3488 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-23 13:40:42.472  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-23 13:40:42.472  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-23 13:40:42.472  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-23 13:40:42.472  3488  3488 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-23 13:40:42.472  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-23 13:40:42.472  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-23 13:40:42.482  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-23 13:40:42.482  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-23 13:40:42.482   764  1607 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{970b621 6493:com.google.android.apps.docs/u0a97}
,08-23 13:40:42.482  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-23 13:40:42.482  6480  6480 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-23 13:40:42.482  3488  3488 D MTPUSBConnection: onCreate in USBConnection
08-23 13:40:42.482  3488  3488 V MTPUSBConnection: Registering broadcast receiver.
,08-23 13:40:42.492   764  1769 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-23 13:40:42.492  6493  6493 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 13:40:42.502  3488  3488 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-23 13:40:42.502   764  1439 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-23 13:40:42.512  6493  6493 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-23 13:40:42.532  6381  6505 D jxcore_app_log: JniHelper::setJavaVM(0xb473c000), pthread_self() = -1723860688
,08-23 13:40:42.532  6381  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:40:42.532  6381  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:40:42.532  6381  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:40:42.532  6381  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:40:42.532  6381  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 13:40:42.532  6381  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b25a940 added. We now have 1 listener(s)
,08-23 13:40:42.542  6381  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-23 13:40:42.542  6381  6505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-23 13:40:42.542  6381  6505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 13:40:42.542  6381  6505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 13:40:42.542  3488  3488 D TAG     : dev.kiessupport is : TRUE
,08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 13:40:42.542  6381  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52fd21f added. We now have 1 listener(s)
,08-23 13:40:42.542  6381  6505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 13:40:42.552  6381  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:40:42.552  6381  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 13:40:42.552  6381  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 13:40:42.552  6381  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-23 13:40:42.552  6381  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 13:40:42.562  6381  6505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 13:40:42.562  6381  6505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-23 13:40:42.562  6381  6505 D BluetoothAdapter: STATE_ON
,08-23 13:40:42.562  6381  6505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-23 13:40:42.572  6381  6505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:40:42.572  6381  6505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:40:42.572  6381  6505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 13:40:42.572  6381  6505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:40:42.572  6381  6505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:40:42.572  6381  6505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:40:42.572  6381  6505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:40:42.572  6381  6505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:40:42.572  6381  6505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:40:42.572  6381  6505 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 13:40:42.572  6381  6505 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 13:40:42.572  6381  6381 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:40:42.572  3488  3488 D SecWifiDisplayUtil: Metadata value : none
08-23 13:40:42.572  6381  6381 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:40:42.572  3488  3488 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7d4bf32 V.E...... R.....I. 0,0-0,0}
,08-23 13:40:42.582  3488  6508 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 13:40:42.582   764  1439 D ISSUE_DEBUG: InputChannelName : afa7a1b com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-23 13:40:42.582   764   823 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{afa7a1b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-23 13:40:42.582  1385  1385 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
08-23 13:40:42.582   764  1439 D InputDispatcher: Focus entered window: 3488
08-23 13:40:42.582   764   879 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:764 uid:1000
08-23 13:40:42.582   764   879 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:40:42.582   764   879 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:764 uid:1000
08-23 13:40:42.582   764   879 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 13:40:42.592  3488  3488 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e41028a I.E...... R.....I. 0,0-0,0}
,08-23 13:40:42.592   764   777 D ISSUE_DEBUG: InputChannelName : d226991 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
08-23 13:40:42.592   764  1439 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-23 13:40:42.592   764  1439 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-23 13:40:42.592   764   764 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 13:40:42.602  6381  6381 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:40:42.602   764   764 I KnoxTimeoutHandler: Shared devices show user statefalse
08-23 13:40:42.602   764   764 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-23 13:40:42.622   294   294 I SurfaceFlinger: id=23 createSurf (145x145),1 flag=4, VSBConnecti
,08-23 13:40:42.642  3488  6508 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 13:40:42.642  3488  6508 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 13:40:42.642  3488  6508 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 13:40:42.642  3488  6508 I Adreno-EGL: Local Branch: ss
08-23 13:40:42.642  3488  6508 I Adreno-EGL: Remote Branch: 
08-23 13:40:42.642  3488  6508 I Adreno-EGL: Local Patches: 
08-23 13:40:42.642  3488  6508 I Adreno-EGL: Reconstruct Branch: 
,08-23 13:40:42.642  3488  6508 D libEGL  : eglInitialize EGLDisplay = 0x9efbb7c4
08-23 13:40:42.642  3488  6508 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 13:40:42.682   294   294 I SurfaceFlinger: id=24 createSurf (193x193),1 flag=4, VSBConnecti
,08-23 13:40:42.692  4172  5048 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-23 13:40:42.712  3488  3488 V ActivityThread: updateVisibility : ActivityRecord{63a4b71 token=android.os.BinderProxy@a82d483 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-23 13:40:42.722  3488  3488 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-23 13:40:42.732  6381  6390 W art     : Suspending all threads took: 8.534ms
,08-23 13:40:42.732   764  6190 I HarmonyEASService: Updating for all 1
,08-23 13:40:42.802  6381  6390 I art     : Background sticky concurrent mark sweep GC freed 49415(3MB) AllocSpace objects, 9(180KB) LOS objects, 30% free, 17MB/25MB, paused 17.662ms total 136.658ms
,08-23 13:40:42.812  4172  5048 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-23 13:40:42.832   764  1321 V WindowStateAnimator: Finishing drawing window Window{afa7a1b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-23 13:40:42.832  3488  3488 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-23 13:40:42.842   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec41364
,08-23 13:40:42.842   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec41364
,08-23 13:40:42.842   764  1767 V WindowStateAnimator: Finishing drawing window Window{d226991 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-23 13:40:42.842  3488  3488 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-23 13:40:42.842  3488  3488 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-23 13:40:42.852   764  1439 V WindowStateAnimator: Finishing drawing window Window{afa7a1b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-23 13:40:42.852   764  1730 V WindowStateAnimator: Finishing drawing window Window{d226991 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-23 13:40:42.852  3488  3488 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a82d483 time:107893
,08-23 13:40:42.852   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec41364
,08-23 13:40:42.852   764   879 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 13:40:42.852   764   764 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 13:40:42.852   764   879 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +401ms (total +431ms)
08-23 13:40:42.852   764   764 I KnoxTimeoutHandler: SD activityfalse
,08-23 13:40:42.862   764   879 D ActivityManager: mDVFSHelper.release()
,08-23 13:40:42.862   764   879 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f82207a u0 com.samsung.android.MtpApplication/.USBConnection t169} time:107905
,08-23 13:40:42.912  4172  5048 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-23 13:40:42.962  6493  6516 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-23 13:40:42.962  6493  6516 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 13:40:42.962  6493  6516 I GAv4    :   adb logcat -s GAv4
,08-23 13:40:42.992  6493  6516 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 13:40:42.992   764  1626 V AlarmManager:  remove PendingIntent] PendingIntent{f730dcd: PendingIntentRecord{bbf8682 com.google.android.apps.docs broadcastIntent}}
,08-23 13:40:42.992  6493  6516 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 13:40:42.992  6493  6516 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 13:40:43.002  6493  6522 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 13:40:43.062  6493  6493 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-23 13:40:43.062  6493  6493 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-23 13:40:43.092  6493  6516 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-23 13:40:43.092  6493  6516 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-23 13:40:43.092  6493  6516 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-23 13:40:43.092  6493  6516 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-23 13:40:43.132  6528  6528 E Zygote  : v2
08-23 13:40:43.132  6528  6528 I libpersona: KNOX_SDCARD checking this for 10098
08-23 13:40:43.132  6528  6528 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:43.132  6528  6528 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:43.132  6528  6528 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:43.132   764  1730 I ActivityManager: Start proc 6528:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-23 13:40:43.142  6528  6528 E Zygote  : accessInfo : 0
,08-23 13:40:43.142   764  1730 I ActivityManager: Killing 4646:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
08-23 13:40:43.142  6528  6528 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-23 13:40:43.162  6528  6528 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:43.162  6528  6528 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:43.162   764   777 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-23 13:40:43.182   764   778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4e388ce 6528:com.sec.android.automotive.drivelink/u0a98}
,08-23 13:40:43.182  6528  6528 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 13:40:43.202  6528  6528 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-23 13:40:43.212  2002  2002 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:40:43.212  2002  2002 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:40:43.232  6528  6528 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 13:40:43.242  2002  2002 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:40:43.252   764   777 V AlarmManager:  remove PendingIntent] PendingIntent{e73e3a6: PendingIntentRecord{f18b1e7 com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 13:40:43.252  6528  6544 I GMPM    : App measurement is starting up
,08-23 13:40:43.262  6528  6528 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-23 13:40:43.262  6528  6544 E GMPM    : getGoogleAppId failed with status: 10
,08-23 13:40:43.262  6528  6544 E GMPM    : Uploading is not possible. App measurement disabled
,08-23 13:40:43.262   764  1675 V AlarmManager:  remove PendingIntent] PendingIntent{3625194: PendingIntentRecord{f18b1e7 com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 13:40:43.282  6528  6528 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-23 13:40:43.292  6528  6528 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-23 13:40:43.292  6493  6517 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 13:40:43.342   764  1769 I ActivityManager: Start proc 6550:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
08-23 13:40:43.342   764  1324 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-23 13:40:43.342  6550  6550 E Zygote  : v2
,08-23 13:40:43.342  6550  6550 I libpersona: KNOX_SDCARD checking this for 10032
08-23 13:40:43.342  6550  6550 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:43.342  6550  6550 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:43.342  6550  6550 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:40:43.342  6550  6550 E Zygote  : accessInfo : 0
,08-23 13:40:43.342  6550  6550 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-23 13:40:43.372  6550  6550 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:43.372  6550  6550 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:43.372  6493  6517 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-23 13:40:43.382   764  1324 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-23 13:40:43.392  6550  6550 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-23 13:40:43.402  6550  6550 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-23 13:40:43.432  6493  6517 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-23 13:40:43.432  6493  6517 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-23 13:40:43.432  6493  6517 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 13:40:43.462   764  3426 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-23 13:40:43.472  6493  6517 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 13:40:43.482  6528  6528 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-23 13:40:43.502  6528  6528 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-23 13:40:43.502  6528  6528 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-23 13:40:43.512  6550  6550 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-23 13:40:43.522  6528  6528 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Aug 23 13:40:43 GMT+02:00 2016
,08-23 13:40:43.522  6528  6528 D DialogFlow: initQueue()
,08-23 13:40:43.532  6381  6507 W jxcore-log: Initializing JXcore engine
08-23 13:40:43.532  6381  6507 W jxcore-log: JXcore engine is ready
,08-23 13:40:43.532  6564  6564 E Zygote  : v2
,08-23 13:40:43.542  6564  6564 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:43.542  6564  6564 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:43.542  6564  6564 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:43.542   764   777 I ActivityManager: Start proc 6564:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-23 13:40:43.542  6564  6564 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:40:43.542  6564  6564 E Zygote  : accessInfo : 0
,08-23 13:40:43.542   764   777 I ActivityManager: Killing 5523:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-23 13:40:43.542   764   777 I ActivityManager: Killing 5050:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-23 13:40:43.572  6550  6550 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-23 13:40:43.582   764   778 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-23 13:40:43.582  6564  6564 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:43.582  6564  6564 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:43.592  2322  2322 E audit   : type=1400 msg=audit(1471952443.592:287): avc:  denied  { ioctl } for  pid=6507 comm="Thread-891" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 13:40:43.592  2322  2322 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-23 13:40:43.592  2322  2322 E audit   : type=1300 msg=audit(1471952443.592:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=992fa3c8 items=0 ppid=354 ppcomm=main pid=6507 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-891" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 13:40:43.592  2322  2322 E audit   : type=1327 msg=audit(1471952443.592:287): proctitle="com.test.thalitest"
08-23 13:40:43.592  2322  2322 E audit   : type=1320 msg=audit(1471952443.592:287): 
08-23 13:40:43.592  2322  2322 E audit   : type=1400 msg=audit(1471952443.592:288): avc:  denied  { ioctl } for  pid=6507 comm="Thread-891" path="socket:[41294]" dev="sockfs" ino=41294 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-23 13:40:43.592  2322  2322 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-23 13:40:43.592  2322  2322 E audit   : type=1300 msg=audit(1471952443.592:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=992fa3c8 items=0 ppid=354 ppcomm=main pid=6507 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-891" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 13:40:43.592  2322  2322 E audit   : type=1327 msg=audit(1471952443.592:288): proctitle="com.test.thalitest"
08-23 13:40:43.592  2322  2322 E audit   : type=1320 msg=audit(1471952443.592:288): 
,08-23 13:40:43.592   764  1607 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-23 13:40:43.602   764  1296 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{faff6df 6564:com.samsung.android.app.filterinstaller/1000}
,08-23 13:40:43.602  6381  6507 W jxcore-log: Starting JXcore engine
,08-23 13:40:43.602  1450  1450 D Recents : onTaskStackChanged
,08-23 13:40:43.612  6564  6564 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-23 13:40:43.612  1450  1450 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 13:40:43.622  6564  6564 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-23 13:40:43.622  1450  1450 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 13:40:43.632  6564  6564 E FilterPackageIntentReceiver: This package is not a effect filter
,08-23 13:40:43.642  6580  6580 E Zygote  : v2
,08-23 13:40:43.642  6580  6580 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:43.642  6580  6580 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:43.642  6580  6580 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:43.642  6580  6580 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:43.642   764   778 I ActivityManager: Start proc 6580:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-23 13:40:43.642  6580  6580 E Zygote  : accessInfo : 0
,08-23 13:40:43.642   764   778 I ActivityManager: Killing 5577:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-23 13:40:43.672  6580  6580 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:43.672  6580  6580 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:43.672   764  1675 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-23 13:40:43.672   764  1767 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-23 13:40:43.692   764  1321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a9e3f2c 6580:com.samsung.helphub/1000}
,08-23 13:40:43.702  6381  6507 W jxcore-log: Platform android
08-23 13:40:43.702  6381  6507 W jxcore-log: 
08-23 13:40:43.702  6381  6507 W jxcore-log: Process ARCH arm
08-23 13:40:43.702  6381  6507 W jxcore-log: 
,08-23 13:40:43.712  6580  6580 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-23 13:40:43.722  6550  6550 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-23 13:40:43.722  6550  6550 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-23 13:40:43.722  6550  6550 D DialogFlow: initQueue()
,08-23 13:40:43.732  6580  6580 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-23 13:40:43.772   764   778 I ActivityManager: Start proc 6592:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-23 13:40:43.772   764   778 I ActivityManager: Killing 5291:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-23 13:40:43.782  6592  6592 E Zygote  : v2
08-23 13:40:43.782  6592  6592 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:43.782  6592  6592 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:43.782  6592  6592 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:43.782  6592  6592 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:40:43.782  6592  6592 E Zygote  : accessInfo : 0
,08-23 13:40:43.782   764  1626 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-23 13:40:43.812  6592  6592 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:43.812  6592  6592 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:43.822   764  1296 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a5be2d7 6592:com.samsung.android.app.mirrorlink/1000}
,08-23 13:40:43.822  6592  6592 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-23 13:40:43.842  6592  6592 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-23 13:40:43.892  6592  6592 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-23 13:40:43.892  6592  6592 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-23 13:40:43.892   764  1626 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38abaca 5705:com.google.android.apps.plus/u0a134}
,08-23 13:40:43.912   764  1767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38abaca 5705:com.google.android.apps.plus/u0a134}
,08-23 13:40:43.912  6381  6507 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:40:43.912  6381  6507 I jxcore-log: 
,08-23 13:40:43.912  6381  6507 W jxcore-log: JXcore engine is started
,08-23 13:40:43.912  6381  6505 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 13:40:43.912  6381  6381 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 13:40:43.922   764  1765 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38abaca 5705:com.google.android.apps.plus/u0a134}
,08-23 13:40:43.942  6381  6507 E jxcore  : Error!: missing name after . operator
08-23 13:40:43.942  6381  6507 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:40:43.942  6381  6381 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 13:40:43.942  6381  6381 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:40:43.952   764   778 I ActivityManager: Killing 5616:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-23 13:40:43.962  6381  6381 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 13:40:43.962  6381  6381 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 13:40:43.962  6381  6381 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 13:40:43.962  6381  6381 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:40:43.962  6381  6381 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:40:43.962  6381  6381 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:40:43.962  6381  6381 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b25a940 removed from the list
,08-23 13:40:43.962  6381  6381 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:40:43.962  6381  6381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52fd21f removed from the list
08-23 13:40:43.962  6381  6381 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:40:43.962  6381  6381 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 13:40:43.962   764  1765 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-23 13:40:43.962   764  1607 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-23 13:40:43.972   764  1439 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-23 13:40:43.972  6381  6381 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 13:40:43.972  6381  6381 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,08-23 13:40:43.972   764  1769 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-23 13:40:43.972   764  1626 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-23 13:40:43.982  6381  6381 D ViewRootImpl: #3 mView = null
,08-23 13:40:43.982   294   906 I SurfaceFlinger: id=22 Removed NainActivit (4/10)
,08-23 13:40:43.982   294   363 I SurfaceFlinger: id=22 Removed NainActivit (-2/10)
,08-23 13:40:43.982   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec413a4
,08-23 13:40:43.992  6381  6381 D cr_Ime  : [ImeAdapter.java:587] detach
,08-23 13:40:43.992   764  1439 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-23 13:40:43.992   764  1296 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-23 13:40:44.002   764  1731 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-23 13:40:44.002   764  1769 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-23 13:40:44.002   764  1368 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-23 13:40:44.022  6608  6608 E Zygote  : v2
08-23 13:40:44.022   764   778 I ActivityManager: Start proc 6608:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-23 13:40:44.022  6608  6608 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:44.022  6608  6608 I libpersona: KNOX_SDCARD checking this for 10165
08-23 13:40:44.022  6608  6608 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:44.022  6608  6608 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:44.022  6608  6608 E Zygote  : accessInfo : 0
08-23 13:40:44.022  6608  6608 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-23 13:40:44.032   764  1607 I ActivityManager: Killing 5304:com.policydm/1000 (adj 15): DHA:empty #37
,08-23 13:40:44.052  6608  6608 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:44.052  6608  6608 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:44.062   764  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78c6de2 6608:com.sec.kidsplat.installer/u0a165}
,08-23 13:40:44.072  6608  6608 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-23 13:40:44.072   764  1626 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-23 13:40:44.072  6347  6347 D AASAservice: onDestroy()
,08-23 13:40:44.082  6347  6347 I art     : System.exit called, status: 80
,08-23 13:40:44.082  6347  6347 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-23 13:40:44.082  6608  6608 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-23 13:40:44.092   764  1321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78c6de2 6608:com.sec.kidsplat.installer/u0a165}
,08-23 13:40:44.092  6608  6608 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-23 13:40:44.102   764  1439 I ActivityManager: Process com.samsung.aasaservice (pid 6347)(adj 0) has died(51,748)
,08-23 13:40:44.102   764  1439 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-23 13:40:44.112   764  1626 I ActivityManager: Start proc 6622:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-23 13:40:44.112  6622  6622 E Zygote  : v2
08-23 13:40:44.112  6622  6622 I libpersona: KNOX_SDCARD checking this for 10142
08-23 13:40:44.112  6622  6622 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:44.112  6622  6622 E Zygote  : isSdpEnabledProcess - SDP enabled
,08-23 13:40:44.112  6622  6622 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 13:40:44.112  6622  6622 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:40:44.122  6622  6622 E Zygote  : accessInfo : 64
,08-23 13:40:44.122  6622  6622 E Zygote  : isSdpEnabledProcess - SDP enabled
08-23 13:40:44.122  6622  6622 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-23 13:40:44.122  6622  6622 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-23 13:40:44.142   354   354 I Zygote  : Process 6347 exited cleanly (80)
,08-23 13:40:44.142  6622  6622 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:44.142  6622  6622 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:44.152   764  1767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3931c30 6622:com.sec.android.app.sbrowser/u0a142}
,08-23 13:40:44.152  6622  6622 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 13:40:44.162  6398  6398 I Mms/MmsApp:  start initViewCache mms
,08-23 13:40:44.172  6622  6622 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-23 13:40:44.182  6622  6622 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 13:40:44.182  6622  6622 D ManifestProvider: onCreate()
,08-23 13:40:44.192  6622  6622 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-23 13:40:44.192  6622  6622 I SBrowserUtils: getSystemProperty of country_code : Poland
08-23 13:40:44.192  6622  6622 I SBrowserUtils: getSystemProperty of country_code : Poland
08-23 13:40:44.192  6622  6622 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-23 13:40:44.202  6622  6622 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-23 13:40:44.202  6622  6622 D [MM]MHDataBaseProvider: onCreate()
,08-23 13:40:44.222  6622  6622 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@f2d4bae)
,08-23 13:40:44.262   764   777 I ActivityManager: Killing 5642:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-23 13:40:44.272   764   777 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ff071b 2002:com.google.android.gms.persistent/u0a11}
,08-23 13:40:44.292  4172  6638 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:40:44.292  4172  6637 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-23 13:40:44.302   764  1675 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{32cce75 4172:com.google.android.gms/u0a11}
,08-23 13:40:44.302   764  1296 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-23 13:40:44.312  4172  6638 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:40:44.312  4172  4172 D AsyncTaskServiceImpl: Submit a task: nzm
,08-23 13:40:44.322   764  1769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ff071b 2002:com.google.android.gms.persistent/u0a11}
,08-23 13:40:44.342  4172  6638 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:40:44.352  4172  5048 D nzm     : Processing package: com.test.thalitest
,08-23 13:40:44.352  4172  6638 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:40:44.352   764  1769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{32cce75 4172:com.google.android.gms/u0a11}
,08-23 13:40:44.362  4172  4172 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-23 13:40:44.392  4172  5048 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-23 13:40:44.402   764  1238 V AlarmManager: Expired Alarm result :4
,08-23 13:40:44.412  4172  5048 D nzm     : Found info for package com.test.thalitest in db.
,08-23 13:40:44.462   764  1769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 13:40:44.462   764  1769 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-23 13:40:44.462   764  1769 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-23 13:40:44.462   764  1769 D BatteryService: stay LED for charging
08-23 13:40:44.462   764   764 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 13:40:44.472   764   764 I MotionRecognitionService: Plugged
08-23 13:40:44.472   764   764 D MotionRecognitionService:   cableConnection= 1
08-23 13:40:44.472   764   764 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 13:40:44.472   764   764 D MotionRecognitionService: skip setTransmitPower. 
08-23 13:40:44.472  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 13:40:44.472  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 13:40:44.472  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 13:40:44.472  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 13:40:44.472  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 13:40:44.472  2316  2316 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 13:40:44.482  2316  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 13:40:44.492   764  1626 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd5d8df 5730:com.android.vending/u0a29}
08-23 13:40:44.502  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 13:40:44.512  6398  6398 D Mms/BubbleViewCache: fillCache bubble = 4
,08-23 13:40:44.532   764   777 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5722df7 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f8299bd 6046:com.sec.android.app.samsungapps/u0a39}
,08-23 13:40:44.542  5730  5730 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-23 13:40:44.542   764  1767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{77df160 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{811d1c7 5788:com.sec.android.app.shealth/u0a34}
,08-23 13:40:44.562  5730  5730 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-23 13:40:44.562  2002  2002 D WearableService: callingUid 10011, callindPid: 2002
,08-23 13:40:44.582   764  3712 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{77df160 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2629d64 1869:com.sec.android.app.shealth:remote/u0a34}
,08-23 13:40:44.592  5730  5730 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-23 13:40:44.592  5730  5730 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-23 13:40:44.592   764  3422 D SSRM:n  : SIOP:: AP = 460, PST = 449, CUR = 350, LCD = 0
08-23 13:40:44.592   764  3422 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 1
,08-23 13:40:44.602  2769  2769 D ContentApp:  LEVEL : 1
,08-23 13:40:44.612   764  3422 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 13:40:44.612   764  1675 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{77df160 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2629d64 1869:com.sec.android.app.shealth:remote/u0a34}
,08-23 13:40:44.612  6550  6578 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-23 13:40:44.622  6550  6578 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 13:40:44.642  6550  6578 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-23 13:40:44.642  6550  6578 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-23 13:40:44.642  6550  6578 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-23 13:40:44.652  6550  6578 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-23 13:40:44.652  6550  6578 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 13:40:44.672   764  1730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff01ad5 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ff071b 2002:com.google.android.gms.persistent/u0a11}
,08-23 13:40:44.692   764  1324 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-23 13:40:44.692   764  1324 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-23 13:40:44.702   764   778 V AlarmManager:  remove PendingIntent] PendingIntent{72682ea: PendingIntentRecord{b6797fa com.google.android.gms broadcastIntent}}
,08-23 13:40:44.722  6648  6648 E Zygote  : v2
08-23 13:40:44.722  6648  6648 I libpersona: KNOX_SDCARD checking this for 10053
08-23 13:40:44.722  6648  6648 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:44.722   764   777 I ActivityManager: Start proc 6648:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
08-23 13:40:44.722  6648  6648 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:40:44.722  6648  6648 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:44.722  6648  6648 E Zygote  : accessInfo : 0
08-23 13:40:44.722  6648  6648 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-23 13:40:44.762  6648  6648 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:44.762  6648  6648 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:44.772   764   778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{24539db u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97c8c78 6648:com.sec.android.app.videoplayer/u0a53}
,08-23 13:40:44.782  6648  6648 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-23 13:40:44.842  6648  6648 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-23 13:40:44.892  6648  6648 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-23 13:40:44.922  6648  6648 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-23 13:40:44.922  6648  6648 D videowall-Global: core_num = 4
,08-23 13:40:44.932  6648  6648 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
08-23 13:40:44.932  6648  6648 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-23 13:40:44.952  6648  6648 D TranscodeReceiver:  SIOP_LEVEL: 1
,08-23 13:40:44.952   764  1296 I ActivityManager: Killing 4752:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-23 13:40:44.982   764  1769 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-23 13:40:44.992  2322  2322 E audit   : type=1400 msg=audit(1471952444.992:289): avc:  denied  { execmod } for  pid=6606 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:40:44.992  2322  2322 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:44.992  2322  2322 E audit   : type=1300 msg=audit(1471952444.992:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b400c000 a1=51000 a2=5 a3=4 items=0 ppid=3564 ppcomm=adbd pid=6606 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:40:44.992  2322  2322 E audit   : type=1327 msg=audit(1471952444.992:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 13:40:44.992  2322  2322 E audit   : type=1320 msg=audit(1471952444.992:289): 
,08-23 13:40:45.042  2322  2322 E audit   : type=1400 msg=audit(1471952445.042:290): avc:  denied  { execmod } for  pid=6606 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:40:45.042  2322  2322 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:45.042  2322  2322 E audit   : type=1300 msg=audit(1471952445.042:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcc000 a1=51000 a2=5 a3=4 items=0 ppid=3564 ppcomm=adbd pid=6606 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:40:45.042  2322  2322 E audit   : type=1327 msg=audit(1471952445.042:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 13:40:45.052  2322  2322 E audit   : type=1320 msg=audit(1471952445.042:290): 
,08-23 13:40:45.092  2322  2322 E audit   : type=1400 msg=audit(1471952445.092:291): avc:  denied  { execmod } for  pid=6606 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:40:45.092  2322  2322 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:40:45.092  2322  2322 E audit   : type=1300 msg=audit(1471952445.092:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcc000 a1=51000 a2=5 a3=4 items=0 ppid=3564 ppcomm=adbd pid=6606 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:40:45.092  2322  2322 E audit   : type=1327 msg=audit(1471952445.092:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 13:40:45.092  2322  2322 E audit   : type=1320 msg=audit(1471952445.092:291): 
,08-23 13:40:45.092  6606  6606 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 13:40:45.102  6606  6606 D AndroidRuntime: CheckJNI is OFF
08-23 13:40:45.102  6606  6606 D AndroidRuntime: readGMSProperty: start
08-23 13:40:45.102  6606  6606 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:40:45.102  6606  6606 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:40:45.102  6606  6606 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:40:45.102  6606  6606 D AndroidRuntime: readGMSProperty: end
08-23 13:40:45.102  6606  6606 D AndroidRuntime: addProductProperty: start
08-23 13:40:45.102  6606  6606 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:40:45.102  6606  6606 W art     : aee33000-b1d59000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:40:45.102  6606  6606 W art     : b1d59000-b3fc8000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:40:45.102  6606  6606 W art     : b3fc8000-b3fc9000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:40:45.102  6606  6606 W art     : b3fc9000-b3fca000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.102  6606  6606 W art     : b42fb000-b4324000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:40:45.102  6606  6606 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 13:40:45.102  6606  6606 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 13:40:45.102  6606  6606 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 13:40:45.102  6606  6606 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 13:40:45.102  6606  6606 W art     : b489f000-b48a2000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:40:45.102  6606  6606 W art     : b48a2000-b48a3000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:40:45.102  6606  6606 W art     : b48a3000-b48a4000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:40:45.102  6606  6606 W art     : b48a4000-b48a5000 r--p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b48a5000-b48c5000 r--s 00000000 00:0b 9219       /dev/__properties__
08-23 13:40:45.102  6606  6606 W art     : b48c5000-b52d6000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:40:45.102  6606  6606 W art     : b52d6000-b52d7000 ---p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b52d7000-b5320000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:40:45.102  6606  6606 W art     : b5320000-b5321000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:40:45.102  6606  6606 W art     : b5321000-b5329000 rw-p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b5329000-b532a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.102  6606  6606 W art     : b532a000-b535f000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:40:45.102  6606  6606 W art     : b535f000-b5360000 ---p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b5360000-b5361000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:40:45.102  6606  6606 W art     : b5361000-b5362000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:40:45.102  6606  6606 W art     : b5362000-b53ba000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 13:40:45.102  6606  6606 W art     : b53ba000-b53bb000 ---p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b53bb000-b53bc000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 13:40:45.102  6606  6606 W art     : b53bc000-b53bd000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 13:40:45.102  6606  6606 W art     : b53be000-b53c4000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:40:45.102  6606  6606 W art     : b53c4000-b53c5000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:40:45.102  6606  6606 W art     : b53c5000-b53c6000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:40:45.102  6606  6606 W art     : b53c6000-b53c8000 rw-p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b53c9000-b53d3000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:40:45.102  6606  6606 W art     : b53d3000-b53d6000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:40:45.102  6606  6606 W art     : b53d6000-b53d7000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:40:45.102  6606  6606 W art     : b53d8000-b53ef000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:40:45.102  6606  6606 W art     : b53ef000-b53f0000 ---p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b53f0000-b53f1000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:40:45.102  6606  6606 W art     : b53f1000-b53f2000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:40:45.102  6606  6606 W art     : b53f3000-b53fd000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:40:45.102  6606  6606 W art     : b53fd000-b53fe000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:40:45.102  6606  6606 W art     : b53fe000-b53ff000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:40:45.102  6606  6606 W art     : b53ff000-b5403000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:40:45.102  6606  6606 W art     : b5403000-b5404000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:40:45.102  6606  6606 W art     : b5404000-b5405000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:40:45.102  6606  6606 W art     : b5405000-b541b000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 13:40:45.102  6606  6606 W art     : b541b000-b541c000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 13:40:45.102  6606  6606 W art     : b541c000-b541d000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 13:40:45.102  6606  6606 W art     : b541d000-b542a000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:40:45.102  6606  6606 W art     : b542a000-b542b000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:40:45.102  6606  6606 W art     : b542b000-b542c000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:40:45.102  6606  6606 W art     : b542c000-b548c000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 13:40:45.102  6606  6606 W art     : b548c000-b548f000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 13:40:45.102  6606  6606 W art     : b548f000-b5493000 rw-p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b5493000-b54f4000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:40:45.102  6606  6606 W art     : b54f4000-b54f5000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:40:45.102  6606  6606 W art     : b54f5000-b5544000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:40:45.102  6606  6606 W art     : b5544000-b5546000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:40:45.102  6606  6606 W art     : b5546000-b5547000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:40:45.102  6606  6606 W art     : b5547000-b5548000 rw-p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b5548000-b554f000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:40:45.102  6606  6606 W art     : b554f000-b5550000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:40:45.102  6606  6606 W art     : b5550000-b5551000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-23 13:40:45.102  6606  6606 W art     : avc_common.so
08-23 13:40:45.102  6606  6606 W art     : b5552000-b5555000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:40:45.102  6606  6606 W art     : b5555000-b5556000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:40:45.102  6606  6606 W art     : b5556000-b5557000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-23 13:40:45.102  6606  6606 W art     : enc_common.so
08-23 13:40:45.102  6606  6606 W art     : b5558000-b555c000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:40:45.102  6606  6606 W art     : b555c000-b555d000 ---p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b555d000-b555e000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:40:45.102  6606  6606 W art     : b555e000-b555f000 rw-p 00005000 b3:17 2510       /syste
08-23 13:40:45.102  6606  6606 W art     : m/lib/libpowermanager.so
08-23 13:40:45.102  6606  6606 W art     : b5560000-b557d000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:40:45.102  6606  6606 W art     : b557d000-b557e000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:40:45.102  6606  6606 W art     : b557e000-b557f000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:40:45.102  6606  6606 W art     : b5580000-b5585000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:40:45.102  6606  6606 W art     : b5585000-b5586000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:40:45.102  6606  6606 W art     : b5586000-b5587000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:40:45.102  6606  6606 W art     : b5588000-b55b9000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:40:45.102  6606  6606 W art     : b55b9000-b55bc000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:40:45.102  6606  6606 W art     : b55bc000-b55bd000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:40:45.102  6606  6606 W art     : b55be000-b55f9000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 13:40:45.102  6606  6606 W art     : b55f9000-b55fa000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 13:40:45.102  6606  6606 W art     : b55fa000-b55fb000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 13:40:45.102  6606  6606 W art     : b55fc000-b5603000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:40:45.102  6606  6606 W art     : b5603000-b5604000 ---p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b5604000-b5605000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:40:45.102  6606  6606 W art     : b5605000-b5606000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:40:45.102  6606  6606 W art     : b5606000-b5607000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.102  6606  6606 W art     : b5607000-b561e000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:40:45.102  6606  6606 W art     : b561e000-b561f000 ---p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b561f000-b5622000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:40:45.102  6606  6606 W art     : b5622000-b5623000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:40:45.102  6606  6606 W art     : b5623000-b5642000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:40:45.102  6606  6606 W art     : b5642000-b5643000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:40:45.102  6606  6606 W art     : b5643000-b5644000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:40:45.102  6606  6606 W art     : b5644000-b5682000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 13:40:45.102  6606  6606 W art     : b5682000-b5683000 ---p 00000000 00:00 0 
08-23 13:40:45.102  6606  6606 W art     : b5683000-b5685000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 13:40:45.102  6606  6606 W art     : b5685000-b5686000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 13:40:45.102  6606  6606 W art     : b5687000-b568e000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:40:45.102  6606  6606 W art     : b568e000-b568f000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:40:45.102  6606  6606 W art     : b568f000-b5690000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:40:45.102  6606  6606 W art     : b5691000-b5694000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:40:45.102  6606  6606 W art     : b5694000-b5695000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:40:45.102  6606  6606 W art     : b5695000-b5696000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:40:45.102  6606  6606 W art     : b5696000-b569c000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:40:45.102  6606  6606 W art     : b569c000-b569d000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b569d000-b569e000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:40:45.112  6606  6606 W art     : b569e000-b569f000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:40:45.112  6606  6606 W art     : b569f000-b56a8000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:40:45.112  6606  6606 W art     : b56a8000-b56a9000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:40:45.112  6606  6606 W art     : b56a9000-b56aa000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:40:45.112  6606  6606 W art     : b56aa000-b573b000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:40:45.112  6606  6606 W art     : b573b000-b573c000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b573c000-b5747000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:40:45.112  6606  6606 W art     : b5747000-b5748000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:40:45.112  6606  6606 W art     : b5749000-b575b000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 13:40:45.112  6606  6606 W art     : b575b000-b575c000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 13:40:45.112  6606  6606 W art     : b575c000-b575d000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 13:40:45.112  6606  6606 W art     : b575e000-b5763000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:40:45.112  6606  6606 W art     : b5763000-b5764000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:40:45.112  6606  6606 W art     : b5764000-b5765000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:40:45.112  6606  6606 W art     : b5766000-b57d3000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:40:45.112  6606  6606 W art     : b57d3000-b57d4000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b57d4000-b57d6000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:40:45.112  6606  6606 W art     : b57d6000-b57d7000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:40:45.112  6606  6606 W art     : b57d7000-b57d8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b57d8000-b57df000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:40:45.112  6606  6606 W art     : b57df000-b57e0000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:40:45.112  6606  6606 W art     : b57e0000-b57e1000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:40:45.112  6606  6606 W art     : b57e2000-b5862000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:40:45.112  6606  6606 W art     : b5862000-b5863000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5863000-b5864000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:40:45.112  6606  6606 W art     : b5864000-b5865000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:40:45.112  6606  6606 W art     : b5865000-b587c000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b587c000-b58b3000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 13:40:45.112  6606  6606 W art     : ib/libqc-opt.so
08-23 13:40:45.112  6606  6606 W art     : b58b3000-b58b4000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:40:45.112  6606  6606 W art     : b58b4000-b58b5000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:40:45.112  6606  6606 W art     : b58b5000-b58d1000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:40:45.112  6606  6606 W art     : b58d1000-b58d2000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:40:45.112  6606  6606 W art     : b58d2000-b58d3000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:40:45.112  6606  6606 W art     : b58d4000-b5935000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 13:40:45.112  6606  6606 W art     : b5935000-b5937000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 13:40:45.112  6606  6606 W art     : b5937000-b5938000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 13:40:45.112  6606  6606 W art     : b5939000-b5960000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 13:40:45.112  6606  6606 W art     : b5960000-b5961000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5961000-b5962000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 13:40:45.112  6606  6606 W art     : b5962000-b5963000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 13:40:45.112  6606  6606 W art     : b5964000-b596c000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:40:45.112  6606  6606 W art     : b596c000-b596e000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:40:45.112  6606  6606 W art     : b596e000-b596f000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:40:45.112  6606  6606 W art     : b5970000-b5973000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 13:40:45.112  6606  6606 W art     : b5973000-b5974000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 13:40:45.112  6606  6606 W art     : b5974000-b5975000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 13:40:45.112  6606  6606 W art     : b5975000-b5979000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:40:45.112  6606  6606 W art     : b5979000-b597a000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b597a000-b597b000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:40:45.112  6606  6606 W art     : b597b000-b597c000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:40:45.112  6606  6606 W art     : b597c000-b598c000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 13:40:45.112  6606  6606 W art     : b598c000-b598d000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 13:40:45.112  6606  6606 W art     : b598d000-b598e000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 13:40:45.112  6606  6606 W art     : b598e000-b59d4000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b59d4000-b59dd000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 13:40:45.112  6606  6606 W art     : b59dd000-b59de000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 13:40:45.112  6606  6606 W art     : b59de000-b59df000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 13:40:45.112  6606  6606 W art     : b59e0000-b59e5000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 13:40:45.112  6606  6606 W art     : b59e5000-b59e6000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 13:40:45.112  6606  6606 W art     : b59e6000-b59e7000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 13:40:45.112  6606  6606 W art     : b59e7000-b59ea000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:40:45.112  6606  6606 W art     : b59ea000-b59eb000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b59eb000-b59ec000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:40:45.112  6606  6606 W art     : b59ec000-b59ed000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:40:45.112  6606  6606 W art     : b59ee000-b5a06000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:40:45.112  6606  6606 W art     : b5a06000-b5a07000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5a07000-b5a08000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:40:45.112  6606  6606 W art     : b5a08000-b5a09000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:40:45.112  6606  6606 W art     : b5a0a000-b5ba4000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:40:45.112  6606  6606 W art     : b5ba4000-b5ba5000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5ba5000-b5bb2000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:40:45.112  6606  6606 W art     : b5bb2000-b5bb3000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:40:45.112  6606  6606 W art     : b5bb3000-b5bb7000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 13:40:45.112  6606  6606 W art     : b5bb7000-b5bb8000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5bb8000-b5bb9000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 13:40:45.112  6606  6606 W art     : b5bb9000-b5bba000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 13:40:45.112  6606  6606 W art     : b5bba000-b5bcd000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:40:45.112  6606  6606 W art     : b5bcd000-b5bce000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:40:45.112  6606  6606 W art     : b5bce000-b5bcf000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:40:45.112  6606  6606 W art     : b5bcf000-b5bd0000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:45.112  6606  6606 W art     : b5bd0000-b5c1b000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:40:45.112  6606  6606 W art     : b5c1b000-b5c1c000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:40:45.112  6606  6606 W art     : b5c1c000-b5c1d000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:40:45.112  6606  6606 W art     : b5c1d000-b5c1f000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5c20000-b5c31000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:40:45.112  6606  6606 W art     : b5c31000-b5c32000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5c32000-b5c33000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:40:45.112  6606  6606 W art     : b5c33000-b5c34000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:40:45.112  6606  6606 W art     : b5c35000-b5c3f000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:40:45.112  6606  6606 W art     : b5c3f000-b5c41000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:40:45.112  6606  6606 W art     : b5c41000-b5c42000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:40:45.112  6606  6606 W art     : b5c42000-b5c5b000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:40:45.112  6606  6606 W art     : b5c5b000-b5c5c000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:40:45.112  6606  6606 W art     : b5c5c000-b5c5f000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:40:45.112  6606  6606 W art     : b5c5f000-b5c63000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5c63000-b5cd7000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 13:40:45.112  6606  6606 W art     : b5cd7000-b5cd8000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5cd8000-b5cdb000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 13:40:45.112  6606  6606 W art     : b5cdb000-b5cdc000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 13:40:45.112  6606  6606 W art     : b5cdc000-b5cdd000 r--p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5cdd000-b5ce0000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:40:45.112  6606  6606 W art     : b5ce0000-b5ce1000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:40:45.112  6606  6606 W art     : b5ce1000-b5ce2000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:40:45.112  6606  6606 W art     : b5ce2000-b5ce3000 r--p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5ce3000-b5ce8000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:40:45.112  6606  6606 W art     : b5ce8000-b5ce9000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:40:45.112  6606  6606 W art     : b5ce9000-b5cea000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:40:45.112  6606  6606 W art     : b5cea000-b5ceb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b5ceb000-b5cee000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:40:45.112  6606  6606 W art     : b5cee000-b5cef000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:40:45.112  6606  6606 W art     : b5cef000-b5cf0000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:40:45.112  6606  6606 W art     : b5cf0000-b5cf1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b5cf1000-b5cf5000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:40:45.112  6606  6606 W art     : b5cf5000-b5cf6000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:40:45.112  6606  6606 W art     : b5cf6000-b5cf7000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:40:45.112  6606  6606 W art     : b5cf7000-b5cf8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:45.112  6606  6606 W art     : b5cf8000-b5cfc000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:40:45.112  6606  6606 W art     : b5cfc000-b5cfd000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:40:45.112  6606  6606 W art     : b5cfd000-b5cfe000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:40:45.112  6606  6606 W art     : b5cfe000-b5cff000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b5cff000-b5d0d000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 13:40:45.112  6606  6606 W art     : b5d0d000-b5d0e000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b5d0e000-b5d0f000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 13:40:45.112  6606  6606 W art     : b5d0f000-b5d10000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 13:40:45.112  6606  6606 W art     : b5d10000-b5d1a000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:40:45.112  6606  6606 W art     : b5d1a000-b5d1d000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:40:45.112  6606  6606 W art     : b5d1d000-b5d1e000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:40:45.112  6606  6606 W art     : b5d1e000-b5d1f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b5d1f000-b5d29000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 13:40:45.112  6606  6606 W art     : b5d29000-b5d2c000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 13:40:45.112  6606  6606 W art     : b5d2c000-b5d2d000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 13:40:45.112  6606  6606 W art     : b5d2d000-b5d31000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:40:45.112  6606  6606 W art     : b5d31000-b5d32000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:40:45.112  6606  6606 W art     : b5d32000-b5d33000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
,08-23 13:40:45.112  6606  6606 W art     : b5d33000-b5d34000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b5d34000-b5d41000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:40:45.112  6606  6606 W art     : b5d41000-b5d43000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:40:45.112  6606  6606 W art     : b5d43000-b5d44000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:40:45.112  6606  6606 W art     : b5d44000-b6156000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 13:40:45.112  6606  6606 W art     : b6156000-b6157000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6157000-b6160000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 13:40:45.112  6606  6606 W art     : b6160000-b6164000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 13:40:45.112  6606  6606 W art     : b6164000-b6165000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6165000-b616c000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:40:45.112  6606  6606 W art     : b616c000-b616d000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:40:45.112  6606  6606 W art     : b616d000-b616e000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:40:45.112  6606  6606 W art     : b616e000-b616f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b616f000-b618a000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-23 13:40:45.112  6606  6606 W art     : b618a000-b618b000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 13:40:45.112  6606  6606 W art     : b618b000-b618c000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 13:40:45.112  6606  6606 W art     : b618c000-b618d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b618d000-b61d9000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:40:45.112  6606  6606 W art     : b61d9000-b61da000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b61da000-b61db000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:40:45.112  6606  6606 W art     : b61db000-b61dc000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:40:45.112  6606  6606 W art     : b61dc000-b61dd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b61dd000-b61e1000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:40:45.112  6606  6606 W art     : b61e1000-b61e2000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b61e2000-b61e3000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:40:45.112  6606  6606 W art     : b61e3000-b61e4000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:40:45.112  6606  6606 W art     : b61e4000-b621c000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:40:45.112  6606  6606 W art     : b621c000-b621d000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:40:45.112  6606  6606 W art     : b621d000-b621e000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:40:45.112  6606  6606 W art     : b621e000-b621f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b621f000-b62bd000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 13:40:45.112  6606  6606 W art     : b62bd000-b62be000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b62be000-b62dc000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 13:40:45.112  6606  6606 W art     : b62dc000-b62dd000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-23 13:40:45.112  6606  6606 W art     : b62dd000-b6450000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:40:45.112  6606  6606 W art     : b6450000-b645b000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:40:45.112  6606  6606 W art     : b645b000-b645c000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:40:45.112  6606  6606 W art     : b645c000-b6573000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:40:45.112  6606  6606 W art     : b6573000-b657e000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:40:45.112  6606  6606 W art     : b657e000-b657f000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:40:45.112  6606  6606 W art     : b657f000-b6583000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6583000-b65a7000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-23 13:40:45.112  6606  6606 W art     : b65a7000-b65a9000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 13:40:45.112  6606  6606 W art     : b65a9000-b65aa000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 13:40:45.112  6606  6606 W art     : b65aa000-b6650000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 13:40:45.112  6606  6606 W art     : b6650000-b665d000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-23 13:40:45.112  6606  6606 W art     : b665d000-b665e000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 13:40:45.112  6606  6606 W art     : b665e000-b665f000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b665f000-b66b2000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:40:45.112  6606  6606 W art     : b66b2000-b66b3000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b66b3000-b66b4000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:40:45.112  6606  6606 W art     : b66b4000-b66b5000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:40:45.112  6606  6606 W art     : b66b5000-b66ba000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b66ba000-b66cc000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 13:40:45.112  6606  6606 W art     : b66cc000-b66cd000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b66cd000-b66ce000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 13:40:45.112  6606  6606 W art     : b66ce000-b66cf000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 13:40:45.112  6606  6606 W art     : b66cf000-b66d6000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:40:45.112  6606  6606 W art     : b66d6000-b66d7000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:40:45.112  6606  6606 W art     : b66d7000-b66d8000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:40:45.112  6606  6606 W art     : b66d8000-b66d9000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b66d9000-b66dc000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 13:40:45.112  6606  6606 W art     : b66dc000-b66dd000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 13:40:45.112  6606  6606 W art     : b66dd000-b66de000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 13:40:45.112  6606  6606 W art     : b66de000-b66e2000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 13:40:45.112  6606  6606 W art     : b66e2000-b66e3000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 13:40:45.112  6606  6606 W art     : b66e3000-b66e4000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 13:40:45.112  6606  6606 W art     : b66e4000-b66f2000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:40:45.112  6606  6606 W art     : b66f2000-b66f3000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b66f3000-b66f4000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:40:45.112  6606  6606 W art     : b66f4000-b66f5000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:40:45.112  6606  6606 W art     : b66f5000-b66fe000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:40:45.112  6606  6606 W art     : b66fe000-b66ff000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:40:45.112  6606  6606 W art     : b66ff000-b6700000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:40:45.112  6606  6606 W art     : b6700000-b6766000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 13:40:45.112  6606  6606 W art     : b6766000-b6767000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6767000-b6769000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 13:40:45.112  6606  6606 W art     : b6769000-b6772000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 13:40:45.112  6606  6606 W art     : b6772000-b6775000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6775000-b680c000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 13:40:45.112  6606  6606 W art     : b680c000-b680e000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 13:40:45.112  6606  6606 W art     : b680e000-b680f000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 13:40:45.112  6606  6606 W art     : b680f000-b6810000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6810000-b6b31000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 13:40:45.112  6606  6606 W art     : b6b31000-b6b32000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6b32000-b6b4d000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 13:40:45.112  6606  6606 W art     : b6b4d000-b6b51000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 13:40:45.112  6606  6606 W art     : b6b51000-b6b56000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6b56000-b6b5e000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:40:45.112  6606  6606 W art     : b6b5e000-b6b5f000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:40:45.112  6606  6606 W art     : b6b5f000-b6b60000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:40:45.112  6606  6606 W art     : b6b60000-b6b8e000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:40:45.112  6606  6606 W art     : b6b8e000-b6b8f000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6b8f000-b6b96000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:40:45.112  6606  6606 W art     : b6b96000-b6b97000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:40:45.112  6606  6606 W art     : b6b97000-b6bdd000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:40:45.112  6606  6606 W art     : b6bdd000-b6bde000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6bde000-b6be1000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:40:45.112  6606  6606 W art     : b6be1000-b6be2000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:40:45.112  6606  6606 W art     : b6be2000-b6bfd000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 13:40:45.112  6606  6606 W art     : b6bfd000-b6c01000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 13:40:45.112  6606  6606 W art     : b6c01000-b6c02000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 13:40:45.112  6606  6606 W art     : b6c02000-b6c4f000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 13:40:45.112  6606  6606 W art     : b6c4f000-b6c50000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6c50000-b6c5c000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 13:40:45.112  6606  6606 W art     : b6c5c000-b6c5d000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 13:40:45.112  6606  6606 W art     : b6c5d000-b6c6a000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 13:40:45.112  6606  6606 W art     : b6c6a000-b6c6b000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6c6b000-b6c6c000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 13:40:45.112  6606  6606 W art     : b6c6c000-b6c6d000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 13:40:45.112  6606  6606 W art     : b6c6d000-b6c75000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:40:45.112  6606  6606 W art     : b6c75000-b6c76000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6c76000-b6c77000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:40:45.112  6606  6606 W art     : b6c77000-b6c78000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:40:45.112  6606  6606 W art     : b6c78000-b6c7f000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:40:45.112  6606  6606 W art     : b6c7f000-b6c80000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:40:45.112  6606  6606 W art     : b6c80000-b6c81000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:40:45.112  6606  6606 W art     : b6c81000-b6c95000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 13:40:45.112  6606  6606 W art     : b6c95000-b6c97000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 13:40:45.112  6606  6606 W art     : b6c97000-b6c98000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 13:40:45.112  6606  6606 W art     : b6c98000-b6cc0000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:40:45.112  6606  6606 W art     : b6cc0000-b6cc2000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:40:45.112  6606  6606 W art     : b6cc2000-b6cc3000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:40:45.112  6606  6606 W art     : b6cc3000-b6cc6000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:40:45.112  6606  6606 W art     : b6cc6000-b6cc7000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:40:45.112  6606  6606 W art     : b6cc7000-b6cc8000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:40:45.112  6606  6606 W art     : b6cc8000-b6cd1000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:40:45.112  6606  6606 W art     : b6cd1000-b6cd2000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:40:45.112  6606  6606 W art     : b6cd2000-b6cd3000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:40:45.112  6606  6606 W art     : b6cd3000-b6cf3000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 13:40:45.112  6606  6606 W art     : b6cf3000-b6cf4000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 13:40:45.112  6606  6606 W art     : b6cf4000-b6cf5000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 13:40:45.112  6606  6606 W art     : b6cf5000-b6d68000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 13:40:45.112  6606  6606 W art     : b6d68000-b6d6c000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 13:40:45.112  6606  6606 W art     : b6d6c000-b6d6f000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 13:40:45.112  6606  6606 W art     : b6d6f000-b6d79000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6d79000-b6e01000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 13:40:45.112  6606  6606 W art     : b6e01000-b6e02000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6e02000-b6e06000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 13:40:45.112  6606  6606 W art     : b6e06000-b6e07000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 13:40:45.112  6606  6606 W art     : b6e07000-b6e08000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6e08000-b6e31000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:40:45.112  6606  6606 W art     : b6e31000-b6e32000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6e32000-b6e35000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:40:45.112  6606  6606 W art     : b6e35000-b6e36000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:40:45.112  6606  6606 W art     : b6e36000-b6f10000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:40:45.112  6606  6606 W art     : b6f10000-b6f17000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:40:45.112  6606  6606 W art     : b6f17000-b6f1f000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:40:45.112  6606  6606 W art     : b6f1f000-b6f20000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6f20000-b6f21000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:45.112  6606  6606 W art     : b6f21000-b6f22000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 13:40:45.112  6606  6606 W art     : b6f22000-b6f23000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b6f23000-b6f26000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b6f26000-b6f4b000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 13:40:45.112  6606  6606 W art     : b6f4b000-b6f4c000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6f4c000-b6f53000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 13:40:45.112  6606  6606 W art     : b6f53000-b6f54000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 13:40:45.112  6606  6606 W art     : b6f54000-b6f5b000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 13:40:45.112  6606  6606 W art     : b6f5b000-b6f5c000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 13:40:45.112  6606  6606 W art     : b6f5c000-b6f5d000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 13:40:45.112  6606  6606 W art     : b6f5d000-b6f5e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b6f5e000-b6f76000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 13:40:45.112  6606  6606 W art     : b6f76000-b6f77000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6f77000-b6f78000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 13:40:45.112  6606  6606 W art     : b6f78000-b6f79000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 13:40:45.112  6606  6606 W art     : b6f79000-b6f87000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 13:40:45.112  6606  6606 W art     : b6f87000-b6f88000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6f88000-b6f89000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 13:40:45.112  6606  6606 W art     : b6f89000-b6f8a000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 13:40:45.112  6606  6606 W art     : b6f8a000-b6f8b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:45.112  6606  6606 W art     : b6f8b000-b6f8d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b6f8d000-b6f8e000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b6f8e000-b6f8f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:40:45.112  6606  6606 W art     : b6f8f000-b6f90000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 13:40:45.112  6606  6606 W art     : b6f90000-b6f91000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:40:45.112  6606  6606 W art     : b6f91000-b6fb1000 r--s 00000000 00:0b 9219       /dev/__properties__
08-23 13:40:45.112  6606  6606 W art     : b6fb1000-b6fb2000 r--p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6fb2000-b6fb3000 ---p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6fb3000-b6fb5000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 13:40:45.112  6606  6606 W art     : b6fb5000-b6fb6000 r-xp 00000000 00:00 0          [sigpage]
08-23 13:40:45.112  6606  6606 W art     : b6fb6000-b6fd1000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 13:40:45.112  6606  6606 W art     : b6fd1000-b6fd2000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 13:40:45.112  6606  6606 W art     : b6fd2000-b6fd4000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 13:40:45.112  6606  6606 W art     : b6fd4000-b6fd6000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : b6fd6000-b6fdb000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 13:40:45.112  6606  6606 W art     : b6fdb000-b6fdc000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 13:40:45.112  6606  6606 W art     : b6fdc000-b6fdd000 rw-p 00000000 00:00 0 
08-23 13:40:45.112  6606  6606 W art     : bec5d000-bec7e000 rw-p 00000000 00:00 0          [stack]
08-23 13:40:45.112  6606  6606 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 13:40:45.162  6606  6606 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 13:40:45.202  6606  6606 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 13:40:45.212  6606  6606 E AffinityControl: AffinityControl: registerfunction enter
,08-23 13:40:45.232  6606  6606 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:40:45.242   764  1607 D PackageManager: START PACKAGE DELETE: observer{161779537}
08-23 13:40:45.242   764  1607 D PackageManager: pkg{<packageName>}
08-23 13:40:45.242   764  1607 D PackageManager: user{0}
08-23 13:40:45.242   764  1607 D PackageManager: caller{2000}
08-23 13:40:45.242   764  1607 D PackageManager: flags{2}
08-23 13:40:45.242   764  1607 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 13:40:45.242   764  1607 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 13:40:45.242   764  1607 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 13:40:45.242   764  1607 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 13:40:45.242   764  1607 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 13:40:45.242   764   916 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 13:40:45.242   764   916 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 13:40:45.242   764   916 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 13:40:45.242   764   916 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 13:40:45.242   764   916 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 13:40:45.242   764   916 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-23 13:40:45.242   764   916 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-23 13:40:45.242   764   916 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-23 13:40:45.242   764   916 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-23 13:40:45.242   764   821 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-23 13:40:45.242   764   916 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-23 13:40:45.242   764   821 I ActivityManager: Killing 6381:com.test.thalitest/u0a4 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-23 13:40:45.252   764   821 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 13:40:45.252   764   821 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-23 13:40:45.262   764   916 D AASAinstall: there is not AASApackages.xml file
,08-23 13:40:45.282   764  1626 D GraphicsStats: Buffer count: 5
,08-23 13:40:45.282   764  1296 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@9d398b7)
08-23 13:40:45.282   764  1333 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:40:45.282   764  1333 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:40:45.282   764  1333 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:40:45.542   764   916 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-23 13:40:45.592  4172  5003 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-23 13:40:45.662   764   916 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-23 13:40:45.662  4172  5003 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-23 13:40:45.662   334   334 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-23 13:40:45.662   764   916 I art     : Starting a blocking GC Explicit
,08-23 13:40:45.792   764   916 I art     : Explicit concurrent mark sweep GC freed 104630(5MB) AllocSpace objects, 13(260KB) LOS objects, 27% free, 41MB/57MB, paused 1.312ms total 126.905ms
,08-23 13:40:45.822   764   916 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 13:40:45.822   764   916 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-23 13:40:45.822   764   916 D AASAinstall: there is not AASApackages.xml file
08-23 13:40:45.822   764   916 D PackageManager: result of delete: 1{161779537}
,08-23 13:40:45.822  6606  6606 I art     : System.exit called, status: 0
08-23 13:40:45.822  6606  6606 I AndroidRuntime: VM exiting with result code 0.
,08-23 13:40:45.822   764   916 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 13:40:45.822   764   916 D PackageManager: userId{-1}
08-23 13:40:45.822   764   916 D PackageManager: andCode{true}
,08-23 13:40:45.842  6065  6334 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-23 13:40:45.842   764   916 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-23 13:40:45.842  6065  6334 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-23 13:40:45.842  6065  6334 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-23 13:40:45.852   764  3452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 13:40:45.912   764   764 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.912   764   764 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.922   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
08-23 13:40:45.922   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.922  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,08-23 13:40:45.932  1385  1385 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-23 13:40:45.932   764   879 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.932   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.932   764   879 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.942   764  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 13:40:45.952   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.952   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.952   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.952   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.952   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.952   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.952   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.962  2002  2256 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 13:40:45.962   764   764 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.962  1701  1701 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 13:40:45.972   764   821 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c5d7a9a u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a87d50 4338:com.samsung.klmsagent/u0a18}
,08-23 13:40:45.972   764   764 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-23 13:40:45.972   764   764 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.972   764   764 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.972  1979  1979 E SamsungIME: mOCRHelper is null
,08-23 13:40:45.972   764   764 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.982   764   764 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.982   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.982  4338  4338 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Aug 23 13:40:45 GMT+02:00 2016
,08-23 13:40:45.982   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.992   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.992   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 13:40:45.992   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.992   764   764 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 13:40:45.992   764   764 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.992  1450  1462 I art     : Background partial concurrent mark sweep GC freed 5985(427KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 17MB/29MB, paused 219us total 101.521ms
,08-23 13:40:45.992   764   764 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-23 13:40:45.992  4338  4338 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-23 13:40:46.002  4338  4338 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-23 13:40:46.002  4338  4338 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 13:40:46.002  3180  3195 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 13:40:46.002   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.002   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.002   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.002  4338  4338 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 13:40:46.002  3180  3195 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 13:40:46.012  3180  3195 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 13:40:46.012  3180  3195 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 13:40:46.012   764  1767 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-23 13:40:46.012   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.012   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.012   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.012   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.012   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.012  4338  6691 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-23 13:40:46.012  4338  6691 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-23 13:40:46.022   764  1368 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/168_task.xml
,08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.022   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.022   764  1324 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
,08-23 13:40:46.022   764  1324 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-23 13:40:46.032   764  1323 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-23 13:40:46.032   764  1323 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 13:40:46.032   764  1323 V NetworkStats: performPollLocked(flags=0x3)
,08-23 13:40:46.032   764  1324 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9c938b3e in tid 1324 (NetworkPolicy)
,08-23 13:40:46.032   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.032   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:40:46.032  2322  2322 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:40:46.032   764   764 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:40:46.032  2322  2322 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:40:46.112  4455  4464 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ebc0b6c in tid 4464 (HeapTaskDaemon)
08-23 13:40:46.112  4455  4464 F libc    : Unable to open connection to debuggerd: Connection refused
,08-23 13:40:46.112  2322  2322 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:40:46.132  2184  2195 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2c24ffc in tid 2195 (HeapTaskDaemon)
,08-23 13:40:46.132  2184  2195 F libc    : Unable to open connection to debuggerd: Connection refused
,08-23 13:40:46.132  2322  2322 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:40:46.152  1716  1726 D libEGL  : eglTerminate EGLDisplay = 0xb2fb76d4
,08-23 13:40:46.172   354   354 I Zygote  : Process 2184 exited due to signal (7)
,08-23 13:40:46.172   354   354 I Zygote  : Process 4455 exited due to signal (7)
,08-23 13:40:46.172  1716  1716 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 has been disconnected from its service
,08-23 13:40:46.172  1716  1716 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ef3ff34 in tid 1716 (id.app.launcher)
,08-23 13:40:46.182  1716  1716 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 13:40:46.182  2322  2322 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:40:46.252   354   354 I Zygote  : Process 1716 exited due to signal (7)
,08-23 13:40:46.492   294   546 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
