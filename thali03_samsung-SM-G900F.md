#### Test 78968685da35147_thali03_samsung-SM-G900F Logs


```
--------- beginning of main
07-27 08:53:27.844  5634  5634 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
,07-27 08:53:27.854  5634  5634 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
07-27 08:53:27.854  5634  5634 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
07-27 08:53:27.854  5634  5634 I art     : System.exit called, status: 0
07-27 08:53:27.854  5634  5634 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
07-27 08:53:27.894   749   761 I ActivityManager: Process com.samsung.aasaservice (pid 5634)(adj 0) has died(84,807)
07-27 08:53:27.894   749   761 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
07-27 08:53:27.904   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
07-27 08:53:27.934   749  1733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2af4fb 1943:com.google.android.gms/u0a12}
07-27 08:53:27.964  1943  1943 W System  : ClassLoader referenced unknown path: /system/app/PlayGames/lib/arm
07-27 08:53:27.974  1943  1943 W ResourcesManager: getTopLevelResources: /system/app/PlayGames/PlayGames.apk / 1.0 running in com.google.android.gms rsrc of package null
07-27 08:53:27.974   749   911 D PackageManager: [MSG] MCS_UNBIND
07-27 08:53:28.024  1943  1943 W ResourcesManager: getTopLevelResources: /system/app/PlayGames/PlayGames.apk / 1.0 running in com.google.android.gms rsrc of package null
07-27 08:53:28.044  1943  5716 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-27 08:53:28.054  1943  5716 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-27 08:53:28.094   749  2079 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2af4fb 1943:com.google.android.gms/u0a12}
07-27 08:53:28.124  1943  1943 W ResourcesManager: getTopLevelResources: /system/app/PlayGames/PlayGames.apk / 1.0 running in com.google.android.gms rsrc of package null
07-27 08:53:28.134  1943  1943 D AsyncTaskServiceImpl: Submit a task: k
07-27 08:53:28.154   749  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2af4fb 1943:com.google.android.gms/u0a12}
07-27 08:53:28.164  1943  5722 D k       : Processing package: com.test.thalitest
07-27 08:53:28.174   749  1733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2af4fb 1943:com.google.android.gms/u0a12}
07-27 08:53:28.184   749  1625 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
07-27 08:53:28.194  1943  5722 D GassUtils: Found app info for package com.test.thalitest:19. Hash: a2bd24b46fbeac726286ced0f24b20678dd0e28251e0475d68c739957df89c32
07-27 08:53:28.194  1943  5722 D k       : Found info for package com.test.thalitest in db.
07-27 08:53:28.194   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
07-27 08:53:28.214   749  1740 I ActivityManager: Start proc 5726:com.google.android.partnersetup/u0a15 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
07-27 08:53:28.214  5726  5726 E Zygote  : v2
07-27 08:53:28.214  5726  5726 I libpersona: KNOX_SDCARD checking this for 10015
07-27 08:53:28.214  5726  5726 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:28.214  5726  5726 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:28.214  5726  5726 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:28.214  5726  5726 E Zygote  : accessInfo : 0
07-27 08:53:28.214  5726  5726 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
07-27 08:53:28.244  5726  5726 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:28.244  5726  5726 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:28.254   749  1712 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d654e54 5726:com.google.android.partnersetup/u0a15}
07-27 08:53:28.254  1943  5721 W BaseAppContext: Using Auth Proxy for data requests.
07-27 08:53:28.264  1943  5721 W BaseAppContext: Using Auth Proxy for data requests.
07-27 08:53:28.264  5726  5726 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
07-27 08:53:28.274  1943  5721 W BaseAppContext: Using Auth Proxy for data requests.
07-27 08:53:28.284  5726  5726 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
07-27 08:53:28.284   749  2078 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity newState = 2 callingPackage = 10012
07-27 08:53:28.304  1943  5721 W BaseAppContext: Using Auth Proxy for data requests.
07-27 08:53:28.324   749  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d654e54 5726:com.google.android.partnersetup/u0a15}
07-27 08:53:28.324  1943  5718 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
07-27 08:53:28.344  5743  5743 E Zygote  : v2
07-27 08:53:28.344  5743  5743 I libpersona: KNOX_SDCARD checking this for 10016
07-27 08:53:28.344  5743  5743 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:28.344  5743  5743 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:28.344  5743  5743 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:28.344   749  1747 I ActivityManager: Start proc 5743:com.samsung.groupcast/u0a16 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
07-27 08:53:28.344  5743  5743 E Zygote  : accessInfo : 0
07-27 08:53:28.344  5743  5743 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
07-27 08:53:28.354  1943  5721 W BaseAppContext: Using Auth Proxy for data requests.
07-27 08:53:28.364   749  1713 I ActivityManager: Killing 5065:com.sec.android.soagent/1000 (adj 15): DHA:empty #37
07-27 08:53:28.364  5743  5743 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:28.364  5743  5743 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:28.374   749  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{42e3943 5743:com.samsung.groupcast/u0a16}
07-27 08:53:28.384  5743  5743 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
07-27 08:53:28.394   749  1713 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.soagent, Auto Run ON
07-27 08:53:28.404  5743  5743 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
07-27 08:53:28.424  5743  5743 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
07-27 08:53:28.434  5743  5743 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
07-27 08:53:28.434  5743  5743 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:53:28.434  5743  5743 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
07-27 08:53:28.434  5743  5743 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
07-27 08:53:28.434  5743  5743 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
07-27 08:53:28.434  5743  5743 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
07-27 08:53:28.434  5743  5743 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
07-27 08:53:28.434  5743  5743 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
07-27 08:53:28.434  5743  5743 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:28.434  5743  5743 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:53:28.434  5743  5743 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-27 08:53:28.434  5743  5743 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:28.434  5743  5743 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-27 08:53:28.434  5743  5743 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-27 08:53:28.444   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{722f3df 5294:com.android.vending/u0a30}
07-27 08:53:28.464   749  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f630343 1887:com.sec.android.app.shealth:remote/u0a35}
07-27 08:53:28.464  5294  5294 D Finsky  : [1] PermissionPolicyService.onStartCommand: post-install permissions check for com.test.thalitest
07-27 08:53:28.484  5756  5756 E Zygote  : v2
07-27 08:53:28.484   749  1740 I ActivityManager: Start proc 5756:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
07-27 08:53:28.484  5756  5756 I libpersona: KNOX_SDCARD checking this for 10042
07-27 08:53:28.484  5756  5756 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:28.484  5756  5756 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:28.484  5756  5756 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:28.484  5756  5756 E Zygote  : accessInfo : 0
07-27 08:53:28.484  5756  5756 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
07-27 08:53:28.484  5294  5294 D Finsky  : [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
07-27 08:53:28.494   749   761 I ActivityManager: Killing 5100:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
07-27 08:53:28.504  5756  5756 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:28.504  5756  5756 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:28.504   749   762 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
07-27 08:53:28.514   749  1567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{376d83e 5756:com.samsung.android.sdk.samsunglink/u0a42}
07-27 08:53:28.524  5756  5756 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
07-27 08:53:28.604  5756  5756 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-27 08:53:28.604  5756  5756 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
07-27 08:53:28.674  5756  5756 I SL_DEBUG: isLoggable:: isProductShip = 1
07-27 08:53:28.674  5756  5756 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
07-27 08:53:28.694   749  2078 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10042
07-27 08:53:28.694   749  2079 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10042
07-27 08:53:28.694   749   761 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10042
07-27 08:53:28.694   749  1712 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10042
07-27 08:53:28.704   749  1415 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10042
07-27 08:53:28.704   749  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10042
07-27 08:53:28.704   749  1733 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10042
07-27 08:53:28.704   749  1713 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10042
07-27 08:53:28.714   749  1746 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10042
07-27 08:53:28.714   749  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10042
07-27 08:53:28.764  2335  2335 E audit   : type=1400 msg=audit(1469602408.764:278): avc:  denied  { execmod } for  pid=5703 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 08:53:28.764  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:28.774  2335  2335 E audit   : type=1300 msg=audit(1469602408.764:278): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff2000 a1=51000 a2=5 a3=4 items=0 ppid=3487 ppcomm=adbd pid=5703 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 08:53:28.774  2335  2335 E audit   : type=1327 msg=audit(1469602408.764:278): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-27 08:53:28.774  2335  2335 E audit   : type=1320 msg=audit(1469602408.764:278): 
07-27 08:53:28.824  2335  2335 E audit   : type=1400 msg=audit(1469602408.824:279): avc:  denied  { execmod } for  pid=5703 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 08:53:28.824  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:28.824  2335  2335 E audit   : type=1300 msg=audit(1469602408.824:279): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb5000 a1=51000 a2=5 a3=4 items=0 ppid=3487 ppcomm=adbd pid=5703 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 08:53:28.824  2335  2335 E audit   : type=1327 msg=audit(1469602408.824:279): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-27 08:53:28.824  2335  2335 E audit   : type=1320 msg=audit(1469602408.824:279): 
07-27 08:53:28.824  1943  5721 W ResourcesManager: getTopLevelResources: /system/app/PlayGames/PlayGames.apk / 1.0 running in com.google.android.gms rsrc of package null
07-27 08:53:28.824  5756  5756 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
07-27 08:53:28.834  5756  5756 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
07-27 08:53:28.834  5756  5756 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
07-27 08:53:28.834  5756  5756 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
07-27 08:53:28.834  5756  5756 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
07-27 08:53:28.834  5756  5756 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
07-27 08:53:28.834  5756  5756 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
07-27 08:53:28.834  5756  5756 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
07-27 08:53:28.834  5756  5756 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
07-27 08:53:28.834  5756  5756 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
07-27 08:53:28.834  5756  5756 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:28.834  5756  5756 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:53:28.834  5756  5756 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-27 08:53:28.834  5756  5756 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:28.834  5756  5756 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-27 08:53:28.834  5756  5756 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-27 08:53:28.834   749  2078 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6e34518 1716:android.process.acore/u0a20}
07-27 08:53:28.844   749  1712 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{263bb6a 4902:com.sec.android.gallery3d/u0a48}
07-27 08:53:28.854  4902  4902 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
07-27 08:53:28.854   749  1712 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:28.864  5782  5782 E Zygote  : v2
07-27 08:53:28.864   749  1567 I ActivityManager: Start proc 5782:com.sec.android.app.myfiles/u0a51 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
07-27 08:53:28.864  5782  5782 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:28.864  5782  5782 I libpersona: KNOX_SDCARD checking this for 10051
07-27 08:53:28.864  5782  5782 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:28.864  5782  5782 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:28.874  5782  5782 E Zygote  : accessInfo : 0
07-27 08:53:28.874  5782  5782 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
07-27 08:53:28.874  2335  2335 E audit   : type=1400 msg=audit(1469602408.874:280): avc:  denied  { execmod } for  pid=5703 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 08:53:28.874  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:28.874  2335  2335 E audit   : type=1300 msg=audit(1469602408.874:280): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb5000 a1=51000 a2=5 a3=4 items=0 ppid=3487 ppcomm=adbd pid=5703 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 08:53:28.874  2335  2335 E audit   : type=1327 msg=audit(1469602408.874:280): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-27 08:53:28.874  2335  2335 E audit   : type=1320 msg=audit(1469602408.874:280): 
07-27 08:53:28.874  5703  5703 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 08:53:28.884  5703  5703 D AndroidRuntime: CheckJNI is OFF
07-27 08:53:28.884  5703  5703 D AndroidRuntime: readGMSProperty: start
07-27 08:53:28.884  5703  5703 D AndroidRuntime: readGMSProperty: already setted!!
07-27 08:53:28.884  5703  5703 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-27 08:53:28.884  5703  5703 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-27 08:53:28.884  5703  5703 D AndroidRuntime: readGMSProperty: end
07-27 08:53:28.884  5703  5703 D AndroidRuntime: addProductProperty: start
07-27 08:53:28.884  5703  5703 W art     : 70aa4000-71821000 rw-p 00000000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
07-27 08:53:28.884  5703  5703 W art     : aee19000-b1d3f000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-27 08:53:28.884  5703  5703 W art     : b1d3f000-b3fae000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-27 08:53:28.884  5703  5703 W art     : b3fae000-b3faf000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-27 08:53:28.884  5703  5703 W art     : b3faf000-b3fb0000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.884  5703  5703 W art     : b42fa000-b4323000 r--p 00d7d000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
07-27 08:53:28.884  5703  5703 W art     : b4323000-b4771000 r-xp 00000000 b3:17 594        /system/lib/libart.so
07-27 08:53:28.884  5703  5703 W art     : b4771000-b4772000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b4772000-b477c000 r--p 0044e000 b3:17 594        /system/lib/libart.so
07-27 08:53:28.884  5703  5703 W art     : b477c000-b477d000 rw-p 00458000 b3:17 594        /system/lib/libart.so
07-27 08:53:28.884  5703  5703 W art     : b477d000-b477f000 rw-p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b477f000-b4780000 r--p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-27 08:53:28.884  5703  5703 W art     : b4882000-b4885000 r-xp 00000000 b3:17 2411       /system/lib/libsigchain.so
07-27 08:53:28.884  5703  5703 W art     : b4885000-b4886000 r--p 00002000 b3:17 2411       /system/lib/libsigchain.so
07-27 08:53:28.884  5703  5703 W art     : b4886000-b4887000 rw-p 00003000 b3:17 2411       /system/lib/libsigchain.so
07-27 08:53:28.884  5703  5703 W art     : b4887000-b4888000 r--p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b4888000-b48a8000 r--s 00000000 00:0b 6702       /dev/__properties__
07-27 08:53:28.884  5703  5703 W art     : b48a8000-b52b9000 r-xp 00000000 b3:17 2806       /system/lib/libLLVM.so
07-27 08:53:28.884  5703  5703 W art     : b52b9000-b52ba000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b52ba000-b5303000 r--p 00a11000 b3:17 2806       /system/lib/libLLVM.so
07-27 08:53:28.884  5703  5703 W art     : b5303000-b5304000 rw-p 00a5a000 b3:17 2806       /system/lib/libLLVM.so
07-27 08:53:28.884  5703  5703 W art     : b5304000-b530c000 rw-p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b530c000-b530d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.884  5703  5703 W art     : b530d000-b5342000 r-xp 00000000 b3:17 715        /system/lib/libbcinfo.so
07-27 08:53:28.884  5703  5703 W art     : b5342000-b5343000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b5343000-b5344000 r--p 00035000 b3:17 715        /system/lib/libbcinfo.so
07-27 08:53:28.884  5703  5703 W art     : b5344000-b5345000 rw-p 00036000 b3:17 715        /system/lib/libbcinfo.so
07-27 08:53:28.884  5703  5703 W art     : b5345000-b539d000 r-xp 00000000 b3:17 2786       /system/lib/libbcc.so
07-27 08:53:28.884  5703  5703 W art     : b539d000-b539e000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b539e000-b539f000 r--p 00058000 b3:17 2786       /system/lib/libbcc.so
07-27 08:53:28.884  5703  5703 W art     : b539f000-b53a0000 rw-p 00059000 b3:17 2786       /system/lib/libbcc.so
07-27 08:53:28.884  5703  5703 W art     : b53a1000-b53a7000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 08:53:28.884  5703  5703 W art     : b53a7000-b53a8000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 08:53:28.884  5703  5703 W art     : b53a8000-b53a9000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 08:53:28.884  5703  5703 W art     : b53a9000-b53ab000 rw-p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b53ac000-b53b6000 r-xp 00000000 b3:17 979        /system/lib/libcommon_time_client.so
07-27 08:53:28.884  5703  5703 W art     : b53b6000-b53b9000 r--p 00009000 b3:17 979        /system/lib/libcommon_time_client.so
07-27 08:53:28.884  5703  5703 W art     : b53b9000-b53ba000 rw-p 0000c000 b3:17 979        /system/lib/libcommon_time_client.so
07-27 08:53:28.884  5703  5703 W art     : b53bb000-b53d2000 r-xp 00000000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
07-27 08:53:28.884  5703  5703 W art     : b53d2000-b53d3000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b53d3000-b53d4000 r--p 00017000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
07-27 08:53:28.884  5703  5703 W art     : b53d4000-b53d5000 rw-p 00018000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
07-27 08:53:28.884  5703  5703 W art     : b53d6000-b53e0000 r-xp 00000000 b3:17 2679       /system/lib/libsec_km.so
07-27 08:53:28.884  5703  5703 W art     : b53e0000-b53e1000 r--p 00009000 b3:17 2679       /system/lib/libsec_km.so
07-27 08:53:28.884  5703  5703 W art     : b53e1000-b53e2000 rw-p 0000a000 b3:17 2679       /system/lib/libsec_km.so
07-27 08:53:28.884  5703  5703 W art     : b53e2000-b53e6000 r-xp 00000000 b3:17 2890       /system/lib/libSEF4MP4.so
07-27 08:53:28.884  5703  5703 W art     : b53e6000-b53e7000 r--p 00003000 b3:17 2890       /system/lib/libSEF4MP4.so
07-27 08:53:28.884  5703  5703 W art     : b53e7000-b53e8000 rw-p 00004000 b3:17 2890       /system/lib/libSEF4MP4.so
07-27 08:53:28.884  5703  5703 W art     : b53e8000-b53fe000 r-xp 00000000 b3:17 335        /system/lib/libSEF.so
07-27 08:53:28.884  5703  5703 W art     : b53fe000-b53ff000 r--p 00015000 b3:17 335        /system/lib/libSEF.so
07-27 08:53:28.884  5703  5703 W art     : b53ff000-b5400000 rw-p 00016000 b3:17 335        /system/lib/libSEF.so
07-27 08:53:28.884  5703  5703 W art     : b5400000-b540d000 r-xp 00000000 b3:17 965        /system/lib/libsfextcp.so
07-27 08:53:28.884  5703  5703 W art     : b540d000-b540e000 r--p 0000c000 b3:17 965        /system/lib/libsfextcp.so
07-27 08:53:28.884  5703  5703 W art     : b540e000-b540f000 rw-p 0000d000 b3:17 965        /system/lib/libsfextcp.so
07-27 08:53:28.884  5703  5703 W art     : b540f000-b546f000 r-xp 00000000 b3:17 201        /system/lib/libsavsff.so
07-27 08:53:28.884  5703  5703 W art     : b546f000-b5472000 rw-p 0005f000 b3:17 201        /system/lib/libsavsff.so
07-27 08:53:28.884  5703  5703 W art     : b5472000-b5476000 rw-p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b5476000-b54d7000 r-xp 00000000 b3:17 160        /system/lib/libsavscmn.so
07-27 08:53:28.884  5703  5703 W art     : b54d7000-b54d8000 rw-p 00061000 b3:17 160        /system/lib/libsavscmn.so
07-27 08:53:28.884  5703  5703 W art     : b54d8000-b5527000 r-xp 00000000 b3:17 2395       /system/lib/libomafldrm.so
07-27 08:53:28.884  5703  5703 W art     : b5527000-b5529000 r--p 0004e000 b3:17 2395       /system/lib/libomafldrm.so
07-27 08:53:28.884  5703  5703 W art     : b5529000-b552a000 rw-p 00050000 b3:17 2395       /system/lib/libomafldrm.so
07-27 08:53:28.884  5703  5703 W art     : b552a000-b552b000 rw-p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b552b000-b5532000 r-xp 00000000 b3:17 2587       /system/lib/libstagefright_avc_common.so
07-27 08:53:28.884  5703  5703 W art     : b5532000-b5533000 r--p 00006000 b3:17 2587       /system/lib/libstagefright_avc_common.so
07-27 08:53:28.884  5703  5703 W art     : b5533000-b5534000 rw-p 00007000 b3:17 2587       /system/lib/libstagefright_avc_common.so
07-27 08:53:28.884  5703  5703 W art     : b5535000-b5538000 r-xp 00000000 b3:17 2563       /system/lib/libstagefright_enc_common.so
07-27 08:53:28.884  5703  5703 W art     : b5538000-b5539000 r--p 00002000 b3:17 2563       /system/lib/libstagefright_enc_common.so
07-27 08:53:28.884  5703  5703 W art     : b5539000-b553a000 rw-p 00003000 b3:17 2563       /system/lib/libstagefright_enc_common.so
07-27 08:53:28.884  5703  5703 W art     : b553b000-b553f000 r-xp 00000000 b3:17 2517       /system/lib/libpowermanager.so
07-27 08:53:28.884  5703  5703 W art     : b553f000-b5540000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b5540000-b5541000 r--p 00004000 b3:17 2517       /system/lib/libpowermanager.so
07-27 08:53:28.884  5703  5703 W art     : b5541000-b5542000 rw-p 00005000 b3:17 2517       /system/lib/libpowermanager.so
07-27 08:53:28.884  5703  5703 W art     : b5543000-b5560000 r-xp 00000000 b3:17 2732       /system/lib/libvorbisidec.so
07-27 08:53:28.884  5703  5703 W art     : b5560000-b5561000 r--p 0001c000 b3:17 2732       /system/lib/libvorbisidec.so
07-27 08:53:28.884  5703  5703 W art     : b5561000-b5562000 rw-p 0001d000 b3:17 2732       /system/lib/libvorbisidec.so
07-27 08:53:28.884  5703  5703 W art     : b5563000-b5568000 r-xp 00000000 b3:17 2683       /system/lib/libstagefright_yuv.so
07-27 08:53:28.884  5703  5703 W art     : b5568000-b5569000 r--p 00004000 b3:17 2683       /system/lib/libstagefright_yuv.so
07-27 08:53:28.884  5703  5703 W art     : b5569000-b556a000 rw-p 00005000 b3:17 2683       /system/lib/libstagefright_yuv.so
07-27 08:53:28.884  5703  5703 W art     : b556b000-b559c000 r-xp 00000000 b3:17 1409       /system/lib/libstagefright_omx.so
07-27 08:53:28.884  5703  5703 W art     : b559c000-b559f000 r--p 00030000 b3:17 1409       /system/lib/libstagefright_omx.so
07-27 08:53:28.884  5703  5703 W art     : b559f000-b55a0000 rw-p 00033000 b3:17 1409       /system/lib/libstagefright_omx.so
07-27 08:53:28.884  5703  5703 W art     : b55a1000-b55dc000 r-xp 00000000 b3:17 2136       /system/lib/libopus.so
07-27 08:53:28.884  5703  5703 W art     : b55dc000-b55dd000 r--p 0003a000 b3:17 2136       /system/lib/libopus.so
07-27 08:53:28.884  5703  5703 W art     : b55dd000-b55de000 rw-p 0003b000 b3:17 2136       /system/lib/libopus.so
07-27 08:53:28.884  5703  5703 W art     : b55df000-b55e6000 r-xp 00000000 b3:17 2930       /system/lib/libmediautils.so
07-27 08:53:28.884  5703  5703 W art     : b55e6000-b55e7000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b55e7000-b55e8000 r--p 00007000 b3:17 2930       /system/lib/libmediautils.so
07-27 08:53:28.884  5703  5703 W art     : b55e8000-b55e9000 rw-p 00008000 b3:17 2930       /system/lib/libmediautils.so
07-27 08:53:28.884  5703  5703 W art     : b55e9000-b55ea000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.884  5703  5703 W art     : b55ea000-b5601000 r-xp 00000000 b3:17 726        /system/lib/libdrmframework.so
07-27 08:53:28.884  5703  5703 W art     : b5601000-b5602000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b5602000-b5605000 r--p 00017000 b3:17 726        /system/lib/libdrmframework.so
07-27 08:53:28.884  5703  5703 W art     : b5605000-b5606000 rw-p 0001a000 b3:17 726        /system/lib/libdrmframework.so
07-27 08:53:28.884  5703  5703 W art     : b5606000-b5625000 r-xp 00000000 b3:17 354        /system/lib/libRScpp.so
07-27 08:53:28.884  5703  5703 W art     : b5625000-b5626000 r--p 0001e000 b3:17 354        /system/lib/libRScpp.so
07-27 08:53:28.884  5703  5703 W art     : b5626000-b5627000 rw-p 0001f000 b3:17 354        /system/lib/libRScpp.so
07-27 08:53:28.884  5703  5703 W art     : b5627000-b5665000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-27 08:53:28.884  5703  5703 W art     : b5665000-b5666000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b5666000-b5668000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-27 08:53:28.884  5703  5703 W art     : b5668000-b5669000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-27 08:53:28.884  5703  5703 W art     : b566a000-b5671000 r-xp 00000000 b3:17 776        /system/lib/libspeexresampler.so
07-27 08:53:28.884  5703  5703 W art     : b5671000-b5672000 r--p 00006000 b3:17 776        /system/lib/libspeexresampler.so
07-27 08:53:28.884  5703  5703 W art     : b5672000-b5673000 rw-p 00007000 b3:17 776        /system/lib/libspeexresampler.so
07-27 08:53:28.884  5703  5703 W art     : b5674000-b5677000 r-xp 00000000 b3:17 764        /system/lib/libsamsungvad.so
07-27 08:53:28.884  5703  5703 W art     : b5677000-b5678000 r--p 00002000 b3:17 764        /system/lib/libsamsungvad.so
07-27 08:53:28.884  5703  5703 W art     : b5678000-b5679000 rw-p 00003000 b3:17 764        /system/lib/libsamsungvad.so
07-27 08:53:28.884  5703  5703 W art     : b5679000-b567f000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 08:53:28.884  5703  5703 W art     : b567f000-b5680000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b5680000-b5681000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 08:53:28.884  5703  5703 W art     : b5681000-b5682000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 08:53:28.884  5703  5703 W art     : b5682000-b568b000 r-xp 00000000 b3:17 2319       /system/lib/libnbaio.so
07-27 08:53:28.884  5703  5703 W art     : b568b000-b568c000 r--p 00008000 b3:17 2319       /system/lib/libnbaio.so
07-27 08:53:28.884  5703  5703 W art     : b568c000-b568d000 rw-p 00009000 b3:17 2319       /system/lib/libnbaio.so
07-27 08:53:28.884  5703  5703 W art     : b568d000-b571e000 r-xp 00000000 b3:17 108        /system/lib/libcrypto-rename.so
07-27 08:53:28.884  5703  5703 W art     : b571e000-b571f000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b571f000-b572a000 r--p 00091000 b3:17 108        /system/lib/libcrypto-rename.so
07-27 08:53:28.884  5703  5703 W art     : b572a000-b572b000 rw-p 0009c000 b3:17 108        /system/lib/libcrypto-rename.so
07-27 08:53:28.884  5703  5703 W art     : b572c000-b573e000 r-xp 00000000 b3:17 2931       /system/lib/libpcre.so
07-27 08:53:28.884  5703  5703 W art     : b573e000-b573f000 r--p 00011000 b3:17 2931       /system/lib/libpcre.so
07-27 08:53:28.884  5703  5703 W art     : b573f000-b5740000 rw-p 00012000 b3:17 2931       /system/lib/libpcre.so
07-27 08:53:28.884  5703  5703 W art     : b5741000-b5746000 r-xp 00000000 b3:17 2467       /system/lib/libwpa_client.so
07-27 08:53:28.884  5703  5703 W art     : b5746000-b5747000 r--p 00004000 b3:17 2467       /system/lib/libwpa_client.so
07-27 08:53:28.884  5703  5703 W art     : b5747000-b5748000 rw-p 00005000 b3:17 2467       /system/lib/libwpa_client.so
07-27 08:53:28.884  5703  5703 W art     : b5749000-b57b6000 r-xp 00000000 b3:17 2127       /system/lib/libGLES_trace.so
07-27 08:53:28.884  5703  5703 W art     : b57b6000-b57b7000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b57b7000-b57b9000 r--p 0006d000 b3:17 2127       /system/lib/libGLES_trace.so
07-27 08:53:28.884  5703  5703 W art     : b57b9000-b57ba000 rw-p 0006f000 b3:17 2127       /system/lib/libGLES_trace.so
07-27 08:53:28.884  5703  5703 W art     : b57ba000-b57bb000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.884  5703  5703 W art     : b57bb000-b57c2000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 08:53:28.884  5703  5703 W art     : b57c2000-b57c3000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 08:53:28.884  5703  5703 W art     : b57c3000-b57c4000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 08:53:28.884  5703  5703 W art     : b57c5000-b5845000 r-xp 00000000 b3:17 2886       /system/lib/libAstcEnc.so
07-27 08:53:28.884  5703  5703 W art     : b5845000-b5846000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b5846000-b5847000 r--p 00080000 b3:17 2886       /system/lib/libAstcEnc.so
07-27 08:53:28.884  5703  5703 W art     : b5847000-b5848000 rw-p 00081000 b3:17 2886       /system/lib/libAstcEnc.so
07-27 08:53:28.884  5703  5703 W art     : b5848000-b585f000 rw-p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b585f000-b5896000 r-xp 00000000 b3:17 3247       /system/vendor/l
07-27 08:53:28.884  5703  5703 W art     : ib/libqc-opt.so
07-27 08:53:28.884  5703  5703 W art     : b5896000-b5897000 r--p 00036000 b3:17 3247       /system/vendor/lib/libqc-opt.so
07-27 08:53:28.884  5703  5703 W art     : b5897000-b5898000 rw-p 00037000 b3:17 3247       /system/vendor/lib/libqc-opt.so
07-27 08:53:28.884  5703  5703 W art     : b5898000-b58b4000 r-xp 00000000 b3:17 407        /system/lib/libquramimagecodec.so
07-27 08:53:28.884  5703  5703 W art     : b58b4000-b58b5000 r--p 0001b000 b3:17 407        /system/lib/libquramimagecodec.so
07-27 08:53:28.884  5703  5703 W art     : b58b5000-b58b6000 rw-p 0001c000 b3:17 407        /system/lib/libquramimagecodec.so
07-27 08:53:28.884  5703  5703 W art     : b58b7000-b5918000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-27 08:53:28.884  5703  5703 W art     : b5918000-b591a000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-27 08:53:28.884  5703  5703 W art     : b591a000-b591b000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-27 08:53:28.884  5703  5703 W art     : b591c000-b5943000 r-xp 00000000 b3:17 2640       /system/lib/libpng.so
07-27 08:53:28.884  5703  5703 W art     : b5943000-b5944000 ---p 00000000 00:00 0 
07-27 08:53:28.884  5703  5703 W art     : b5944000-b5945000 r--p 00027000 b3:17 2640       /system/lib/libpng.so
07-27 08:53:28.884  5703  5703 W art     : b5945000-b5946000 rw-p 00028000 b3:17 2640       /system/lib/libpng.so
07-27 08:53:28.884  5703  5703 W art     : b5947000-b594f000 r-xp 00000000 b3:17 2191       /system/lib/libremotedesktop_client.so
07-27 08:53:28.884  5703  5703 W art     : b594f000-b5951000 r--p 00007000 b3:17 2191       /system/lib/libremotedesktop_client.so
07-27 08:53:28.884  5703  5703 W art     : b5951000-b5952000 rw-p 00009000 b3:17 2191       /system/lib/libremotedesktop_client.so
07-27 08:53:28.884  5703  5703 W art     : b5953000-b5956000 r-xp 00000000 b3:17 2506       /system/lib/libsync.so
07-27 08:53:28.884  5703  5703 W art     : b5956000-b5957000 r--p 00002000 b3:17 2506       /system/lib/libsync.so
07-27 08:53:28.884  5703  5703 W art     : b5957000-b5958000 rw-p 00003000 b3:17 2506       /system/lib/libsync.so
07-27 08:53:28.884  5703  5703 W art     : b5958000-b595c000 r-xp 00000000 b3:17 2639       /system/lib/libstdc++.so
07-27 08:53:28.884  5703  5703 W art     : b595c000-b595d000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b595d000-b595e000 r--p 00004000 b3:17 2639       /system/lib/libstdc++.so
07-27 08:53:28.894  5703  5703 W art     : b595e000-b595f000 rw-p 00005000 b3:17 2639       /system/lib/libstdc++.so
07-27 08:53:28.894  5703  5703 W art     : b595f000-b596f000 r-xp 00000000 b3:17 359        /system/lib/libunwind.so
07-27 08:53:28.894  5703  5703 W art     : b596f000-b5970000 r--p 0000f000 b3:17 359        /system/lib/libunwind.so
07-27 08:53:28.894  5703  5703 W art     : b5970000-b5971000 rw-p 00010000 b3:17 359        /system/lib/libunwind.so
07-27 08:53:28.894  5703  5703 W art     : b5971000-b59b7000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b59b7000-b59c0000 r-xp 00000000 b3:17 2903       /system/lib/libbase.so
07-27 08:53:28.894  5703  5703 W art     : b59c0000-b59c1000 r--p 00008000 b3:17 2903       /system/lib/libbase.so
07-27 08:53:28.894  5703  5703 W art     : b59c1000-b59c2000 rw-p 00009000 b3:17 2903       /system/lib/libbase.so
07-27 08:53:28.894  5703  5703 W art     : b59c3000-b59c8000 r-xp 00000000 b3:17 2659       /system/lib/libeffects.so
07-27 08:53:28.894  5703  5703 W art     : b59c8000-b59c9000 r--p 00004000 b3:17 2659       /system/lib/libeffects.so
07-27 08:53:28.894  5703  5703 W art     : b59c9000-b59ca000 rw-p 00005000 b3:17 2659       /system/lib/libeffects.so
07-27 08:53:28.894  5703  5703 W art     : b59ca000-b59cd000 r-xp 00000000 b3:17 1371       /system/lib/libstagefright_http_support.so
07-27 08:53:28.894  5703  5703 W art     : b59cd000-b59ce000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b59ce000-b59cf000 r--p 00003000 b3:17 1371       /system/lib/libstagefright_http_support.so
07-27 08:53:28.894  5703  5703 W art     : b59cf000-b59d0000 rw-p 00004000 b3:17 1371       /system/lib/libstagefright_http_support.so
07-27 08:53:28.894  5703  5703 W art     : b59d1000-b59e9000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 08:53:28.894  5703  5703 W art     : b59e9000-b59ea000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b59ea000-b59eb000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 08:53:28.894  5703  5703 W art     : b59eb000-b59ec000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 08:53:28.894  5703  5703 W art     : b59ed000-b5b87000 r-xp 00000000 b3:17 2790       /system/lib/libstagefright.so
07-27 08:53:28.894  5703  5703 W art     : b5b87000-b5b88000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b5b88000-b5b95000 r--p 0019a000 b3:17 2790       /system/lib/libstagefright.so
07-27 08:53:28.894  5703  5703 W art     : b5b95000-b5b96000 rw-p 001a7000 b3:17 2790       /system/lib/libstagefright.so
07-27 08:53:28.894  5703  5703 W art     : b5b96000-b5b9a000 r-xp 00000000 b3:17 2681       /system/lib/libpersona.so
07-27 08:53:28.894  5703  5703 W art     : b5b9a000-b5b9b000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b5b9b000-b5b9c000 r--p 00004000 b3:17 2681       /system/lib/libpersona.so
07-27 08:53:28.894  5703  5703 W art     : b5b9c000-b5b9d000 rw-p 00005000 b3:17 2681       /system/lib/libpersona.so
07-27 08:53:28.894  5703  5703 W art     : b5b9d000-b5bb0000 r-xp 00000000 b3:17 2920       /system/lib/libimagefilter.so
07-27 08:53:28.894  5703  5703 W art     : b5bb0000-b5bb1000 r--p 00012000 b3:17 2920       /system/lib/libimagefilter.so
07-27 08:53:28.894  5703  5703 W art     : b5bb1000-b5bb2000 rw-p 00013000 b3:17 2920       /system/lib/libimagefilter.so
07-27 08:53:28.894  5703  5703 W art     : b5bb3000-b5bfe000 r-xp 00000000 b3:17 2156       /system/lib/libsecure_storage.so
07-27 08:53:28.894  5703  5703 W art     : b5bfe000-b5bff000 r--p 0004a000 b3:17 2156       /system/lib/libsecure_storage.so
07-27 08:53:28.894  5703  5703 W art     : b5bff000-b5c00000 rw-p 0004b000 b3:17 2156       /system/lib/libsecure_storage.so
07-27 08:53:28.894  5703  5703 W art     : b5c00000-b5c02000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b5c02000-b5c03000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:53:28.894  5703  5703 W art     : b5c03000-b5c14000 r-xp 00000000 b3:17 2258       /system/lib/libsamsungeffect.so
07-27 08:53:28.894  5703  5703 W art     : b5c14000-b5c15000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b5c15000-b5c16000 r--p 00011000 b3:17 2258       /system/lib/libsamsungeffect.so
07-27 08:53:28.894  5703  5703 W art     : b5c16000-b5c17000 rw-p 00012000 b3:17 2258       /system/lib/libsamsungeffect.so
07-27 08:53:28.894  5703  5703 W art     : b5c18000-b5c22000 r-xp 00000000 b3:17 2321       /system/lib/libsensorhub.so
07-27 08:53:28.894  5703  5703 W art     : b5c22000-b5c24000 r--p 00009000 b3:17 2321       /system/lib/libsensorhub.so
07-27 08:53:28.894  5703  5703 W art     : b5c24000-b5c25000 rw-p 0000b000 b3:17 2321       /system/lib/libsensorhub.so
07-27 08:53:28.894  5703  5703 W art     : b5c25000-b5c3e000 r-xp 00000000 b3:17 2929       /system/lib/libmctraster.so
07-27 08:53:28.894  5703  5703 W art     : b5c3e000-b5c3f000 r--p 00018000 b3:17 2929       /system/lib/libmctraster.so
07-27 08:53:28.894  5703  5703 W art     : b5c3f000-b5c42000 rw-p 00019000 b3:17 2929       /system/lib/libmctraster.so
07-27 08:53:28.894  5703  5703 W art     : b5c42000-b5c46000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b5c46000-b5cba000 r-xp 00000000 b3:17 2777       /system/lib/libhwui.so
07-27 08:53:28.894  5703  5703 W art     : b5cba000-b5cbb000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b5cbb000-b5cbe000 r--p 00074000 b3:17 2777       /system/lib/libhwui.so
07-27 08:53:28.894  5703  5703 W art     : b5cbe000-b5cbf000 rw-p 00077000 b3:17 2777       /system/lib/libhwui.so
07-27 08:53:28.894  5703  5703 W art     : b5cc0000-b5cc3000 r-xp 00000000 b3:17 2497       /system/lib/libcc_manager.so
07-27 08:53:28.894  5703  5703 W art     : b5cc3000-b5cc4000 r--p 00002000 b3:17 2497       /system/lib/libcc_manager.so
07-27 08:53:28.894  5703  5703 W art     : b5cc4000-b5cc5000 rw-p 00003000 b3:17 2497       /system/lib/libcc_manager.so
07-27 08:53:28.894  5703  5703 W art     : b5cc5000-b5cc6000 r--p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b5cc6000-b5ccb000 r-xp 00000000 b3:17 2463       /system/lib/libsecnativefeature.so
07-27 08:53:28.894  5703  5703 W art     : b5ccb000-b5ccc000 r--p 00004000 b3:17 2463       /system/lib/libsecnativefeature.so
07-27 08:53:28.894  5703  5703 W art     : b5ccc000-b5ccd000 rw-p 00005000 b3:17 2463       /system/lib/libsecnativefeature.so
07-27 08:53:28.894  5703  5703 W art     : b5ccd000-b5cce000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b5cce000-b5cd1000 r-xp 00000000 b3:17 2939       /system/lib/libradio_metadata.so
07-27 08:53:28.894  5703  5703 W art     : b5cd1000-b5cd2000 r--p 00002000 b3:17 2939       /system/lib/libradio_metadata.so
07-27 08:53:28.894  5703  5703 W art     : b5cd2000-b5cd3000 rw-p 00003000 b3:17 2939       /system/lib/libradio_metadata.so
07-27 08:53:28.894  5703  5703 W art     : b5cd3000-b5cd4000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b5cd4000-b5cd8000 r-xp 00000000 b3:17 808        /system/lib/libnativebridge.so
07-27 08:53:28.894  5703  5703 W art     : b5cd8000-b5cd9000 r--p 00003000 b3:17 808        /system/lib/libnativebridge.so
07-27 08:53:28.894  5703  5703 W art     : b5cd9000-b5cda000 rw-p 00004000 b3:17 808        /system/lib/libnativebridge.so
07-27 08:53:28.894  5703  5703 W art     : b5cda000-b5cdb000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:53:28.894  5703  5703 W art     : b5cdb000-b5cdf000 r-xp 00000000 b3:17 2582       /system/lib/libprocessgroup.so
07-27 08:53:28.894  5703  5703 W art     : b5cdf000-b5ce0000 r--p 00003000 b3:17 2582       /system/lib/libprocessgroup.so
07-27 08:53:28.894  5703  5703 W art     : b5ce0000-b5ce1000 rw-p 00004000 b3:17 2582       /system/lib/libprocessgroup.so
07-27 08:53:28.894  5703  5703 W art     : b5ce1000-b5ce2000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b5ce2000-b5cf0000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-27 08:53:28.894  5703  5703 W art     : b5cf0000-b5cf1000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b5cf1000-b5cf2000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-27 08:53:28.894  5703  5703 W art     : b5cf2000-b5cf3000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-27 08:53:28.894  5703  5703 W art     : b5cf3000-b5cfd000 r-xp 00000000 b3:17 2193       /system/lib/libsoundtrigger.so
07-27 08:53:28.894  5703  5703 W art     : b5cfd000-b5d00000 r--p 00009000 b3:17 2193       /system/lib/libsoundtrigger.so
07-27 08:53:28.894  5703  5703 W art     : b5d00000-b5d01000 rw-p 0000c000 b3:17 2193       /system/lib/libsoundtrigger.so
07-27 08:53:28.894  5703  5703 W art     : b5d01000-b5d02000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b5d02000-b5d0c000 r-xp 00000000 b3:17 2938       /system/lib/libradio.so
07-27 08:53:28.894  5703  5703 W art     : b5d0c000-b5d0f000 r--p 00009000 b3:17 2938       /system/lib/libradio.so
07-27 08:53:28.894  5703  5703 W art     : b5d0f000-b5d10000 rw-p 0000c000 b3:17 2938       /system/lib/libradio.so
07-27 08:53:28.894  5703  5703 W art     : b5d10000-b5d14000 r-xp 00000000 b3:17 2413       /system/lib/libnetd_client.so
07-27 08:53:28.894  5703  5703 W art     : b5d14000-b5d15000 r--p 00003000 b3:17 2413       /system/lib/libnetd_client.so
07-27 08:53:28.894  5703  5703 W art     : b5d15000-b5d16000 rw-p 00004000 b3:17 2413       /system/lib/libnetd_client.so
07-27 08:53:28.894  5703  5703 W art     : b5d16000-b5d17000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b5d17000-b5d24000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-27 08:53:28.894  5703  5703 W art     : b5d24000-b5d26000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-27 08:53:28.894  5703  5703 W art     : b5d26000-b5d27000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-27 08:53:28.894  5703  5703 W art     : b5d27000-b6139000 r-xp 00000000 b3:17 299        /system/lib/libpdfium.so
07-27 08:53:28.894  5703  5703 W art     : b6139000-b613a000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b613a000-b6143000 r--p 00412000 b3:17 299        /system/lib/libpdfium.so
07-27 08:53:28.894  5703  5703 W art     : b6143000-b6147000 rw-p 0041b000 b3:17 299        /system/lib/libpdfium.so
07-27 08:53:28.894  5703  5703 W art     : b6147000-b6148000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6148000-b614f000 r-xp 00000000 b3:17 2571       /system/lib/libaud
07-27 08:53:28.894  5703  5703 W art     : ioutils.so
07-27 08:53:28.894  5703  5703 W art     : b614f000-b6150000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-27 08:53:28.894  5703  5703 W art     : b6150000-b6151000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-27 08:53:28.894  5703  5703 W art     : b6151000-b6152000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b6152000-b616d000 r-xp 00000000
07-27 08:53:28.894  5703  5703 W art     :  b3:17 1184       /system/lib/libz.so
07-27 08:53:28.894  5703  5703 W art     : b616d000-b616e000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-27 08:53:28.894  5703  5703 W art     : b616e000-b616f000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-27 08:53:28.894  5703  5703 W art     : b616f000-b6170000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b6170000-b61bc000 r-xp 00000000 b3:17 342        
07-27 08:53:28.894  5703  5703 W art     : /system/lib/libharfbuzz_ng.so
07-27 08:53:28.894  5703  5703 W art     : b61bc000-b61bd000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b61bd000-b61be000 r--p 0004c000 b3:17 342        /system/lib/libharfbuzz_ng.so
07-27 08:53:28.894  5703  5703 W art     : b61be000-b61bf000 rw-p 0004d000 b3:17 342        /system/lib/libharfbuzz_ng.so
07-27 08:53:28.894  5703  5703 W art     : b61bf000-b61c0000 r--p 00000000 00:00 0          [anon:li
07-27 08:53:28.894  5703  5703 W art     : nker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b61c0000-b61c4000 r-xp 00000000 b3:17 2688       /system/lib/libusbhost.so
07-27 08:53:28.894  5703  5703 W art     : b61c4000-b61c5000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b61c5000-b61c6000 r--p 00004000 b3:17 2688       /system/lib/libusbhost.so
07-27 08:53:28.894  5703  5703 W art     : b61c6000-b61c7000 rw-p 00005000 b3:17 2688       /system/lib/libu
07-27 08:53:28.894  5703  5703 W art     : sbhost.so
07-27 08:53:28.894  5703  5703 W art     : b61c7000-b61ff000 r-xp 00000000 b3:17 2749       /system/lib/libjpeg.so
07-27 08:53:28.894  5703  5703 W art     : b61ff000-b6200000 r--p 00037000 b3:17 2749       /system/lib/libjpeg.so
07-27 08:53:28.894  5703  5703 W art     : b6200000-b6201000 rw-p 00038000 b3:17 2749       /system/lib/libjpeg.so
07-27 08:53:28.894  5703  5703 W art     : b6201000-b6202000 r--p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     :          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b6202000-b62a0000 r-xp 00000000 b3:17 409        /system/lib/libmedia.so
07-27 08:53:28.894  5703  5703 W art     : b62a0000-b62a1000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b62a1000-b62bf000 r--p 0009e000 b3:17 409        /system/lib/libmedia.so
07-27 08:53:28.894  5703  5703 W art     : b62bf000-b62c0000 rw-p 000bc000 b3:17 409        /system/lib/libmedia
07-27 08:53:28.894  5703  5703 W art     : .so
07-27 08:53:28.894  5703  5703 W art     : b62c0000-b6433000 r-xp 00000000 b3:17 2204       /system/lib/libicui18n.so
07-27 08:53:28.894  5703  5703 W art     : b6433000-b643e000 r--p 00172000 b3:17 2204       /system/lib/libicui18n.so
07-27 08:53:28.894  5703  5703 W art     : b643e000-b643f000 rw-p 0017d000 b3:17 2204       /system/lib/libicui18n.so
07-27 08:53:28.894  5703  5703 W art     : b643f000-b6556000 r-xp 00000000
07-27 08:53:28.894  5703  5703 W art     :  b3:17 2041       /system/lib/libicuuc.so
07-27 08:53:28.894  5703  5703 W art     : b6556000-b6561000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-27 08:53:28.894  5703  5703 W art     : b6561000-b6562000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-27 08:53:28.894  5703  5703 W art     : b6562000-b6566000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6566000-b658a000 r-xp 00000000 b3:17 405        /system/lib/libssl.s
07-27 08:53:28.894  5703  5703 W art     : o
07-27 08:53:28.894  5703  5703 W art     : b658a000-b658c000 r--p 00023000 b3:17 405        /system/lib/libssl.so
07-27 08:53:28.894  5703  5703 W art     : b658c000-b658d000 rw-p 00025000 b3:17 405        /system/lib/libssl.so
07-27 08:53:28.894  5703  5703 W art     : b658d000-b6633000 r-xp 00000000 b3:17 110        /system/lib/libcrypto.so
07-27 08:53:28.894  5703  5703 W art     : b6633000-b6640000 r--p 000a5000 b3:17 11
07-27 08:53:28.894  5703  5703 W art     : 0        /system/lib/libcrypto.so
07-27 08:53:28.894  5703  5703 W art     : b6640000-b6641000 rw-p 000b2000 b3:17 110        /system/lib/libcrypto.so
07-27 08:53:28.894  5703  5703 W art     : b6641000-b6642000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6642000-b6695000 r-xp 00000000 b3:17 2736       /system/lib/libsonivox.so
07-27 08:53:28.894  5703  5703 W art     : b6695000-b6696000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6696000-b6697000 r--p 00053000 b3:17 2736       /system/lib/libsonivox.so
07-27 08:53:28.894  5703  5703 W art     : b6697000-b6698000 rw-p 00054000 b3:17 2736       /system/lib/libsonivox.so
07-27 08:53:28.894  5703  5703 W art     : b6698000-b669d000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b669d000-b66af000 r-xp 00000000 b3:17 2641       /system/lib/libselinux.so
07-27 08:53:28.894  5703  5703 W art     : b66af000-b66b0000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b66b0000-b66b1000 r--p 00012000 b3:17 2641       /system/lib/libselinux.so
07-27 08:53:28.894  5703  5703 W art     : b66b1000-b66b2000 rw-p 00013000 b3:17 2641       /system/lib/libselinux.so
07-27 08:53:28.894  5703  5703 W art     : b66b2000-b66b9000 r-xp 00000000 b3:17 2636       /system/lib/libhardware_legacy.so
07-27 08:53:28.894  5703  5703 W art     : b66b9000-b66ba000 r--p 00007000 b3:17 2636       /system/lib/libhardware_legacy.so
07-27 08:53:28.894  5703  5703 W art     : b66ba000-b66bb000 rw-p 00008000 b3:17 2636       /system/lib/libhardware_legacy.so
07-27 08:53:28.894  5703  5703 W art     : b66bb000-b66bc000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b66bc000-b66bf000 r-xp 00000000 b3:17 2414       /system/lib/libhardware.so
07-27 08:53:28.894  5703  5703 W art     : b66bf000-b66c0000 r--p 00002000 b3:17 2414       /system/lib/libhardware.so
07-27 08:53:28.894  5703  5703 W art     : b66c0000-b66c1000 rw-p 00003000 b3:17 2414       /system/lib/libhardware.so
07-27 08:53:28.894  5703  5703 W art     : b66c1000-b66c5000 r-xp 00000000 b3:17 2565       /system/lib/libETC1.so
07-27 08:53:28.894  5703  5703 W art     : b66c5000-b66c6000 r--p 00003000 b3:17 2565       /system/lib/libETC1.so
07-27 08:53:28.894  5703  5703 W art     : b66c6000-b66c7000 rw-p 00004000 b3:17 2565       /system/lib/libETC1.so
07-27 08:53:28.894  5703  5703 W art     : b66c7000-b66d5000 r-xp 00000000 b3:17 2725       /system/lib/libGLESv2.so
07-27 08:53:28.894  5703  5703 W art     : b66d5000-b66d6000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b66d6000-b66d7000 r--p 0000e000 b3:17 2725       /system/lib/libGLESv2.so
07-27 08:53:28.894  5703  5703 W art     : b66d7000-b66d8000 rw-p 0000f000 b3:17 2725       /system/lib/libGLESv2.so
07-27 08:53:28.894  5703  5703 W art     : b66d8000-b66e1000 r-xp 00000000 b3:17 2253       /system/lib/libGLESv1_CM.so
07-27 08:53:28.894  5703  5703 W art     : b66e1000-b66e2000 r--p 00008000 b3:17 2253       /system/lib/libGLESv1_CM.so
07-27 08:53:28.894  5703  5703 W art     : b66e2000-b66e3000 rw-p 00009000 b3:17 2253       /system/lib/libGLESv1_CM.so
07-27 08:53:28.894  5703  5703 W art     : b66e3000-b6749000 r-xp 00000000 b3:17 825        /system/lib/libEGL.so
07-27 08:53:28.894  5703  5703 W art     : b6749000-b674a000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b674a000-b674c000 r--p 00066000 b3:17 825        /system/lib/libEGL.so
07-27 08:53:28.894  5703  5703 W art     : b674c000-b6755000 rw-p 00068000 b3:17 825        /system/lib/libEGL.so
07-27 08:53:28.894  5703  5703 W art     : b6755000-b6758000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6758000-b67ef000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-27 08:53:28.894  5703  5703 W art     : b67ef000-b67f1000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-27 08:53:28.894  5703  5703 W art     : b67f1000-b67f2000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-27 08:53:28.894  5703  5703 W art     : b67f2000-b67f3000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b67f3000-b6b14000 r-xp 00000000 b3:17 286        /system/lib/libskia.so
07-27 08:53:28.894  5703  5703 W art     : b6b14000-b6b15000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6b15000-b6b30000 r--p 00321000 b3:17 286        /system/lib/libskia.so
07-27 08:53:28.894  5703  5703 W art     : b6b30000-b6b34000 rw-p 0033c000 b3:17 286        /system/lib/libskia.so
07-27 08:53:28.894  5703  5703 W art     : b6b34000-b6b39000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6b39000-b6b41000 r-xp 00000000 b3:17 2599       /system/lib/libcamera_metadata.so
07-27 08:53:28.894  5703  5703 W art     : b6b41000-b6b42000 r--p 00007000 b3:17 2599       /system/lib/libcamera_metadata.so
07-27 08:53:28.894  5703  5703 W art     : b6b42000-b6b43000 rw-p 00008000 b3:17 2599       /system/lib/libcamera_metadata.so
07-27 08:53:28.894  5703  5703 W art     : b6b43000-b6b71000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-27 08:53:28.894  5703  5703 W art     : b6b71000-b6b72000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6b72000-b6b79000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-27 08:53:28.894  5703  5703 W art     : b6b79000-b6b7a000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-27 08:53:28.894  5703  5703 W art     : b6b7a000-b6bc0000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-27 08:53:28.894  5703  5703 W art     : b6bc0000-b6bc1000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6bc1000-b6bc4000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-27 08:53:28.894  5703  5703 W art     : b6bc4000-b6bc5000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-27 08:53:28.894  5703  5703 W art     : b6bc5000-b6be0000 r-xp 00000000 b3:17 2538       /system/lib/libinput.so
07-27 08:53:28.894  5703  5703 W art     : b6be0000-b6be4000 r--p 0001a000 b3:17 2538       /system/lib/libinput.so
07-27 08:53:28.894  5703  5703 W art     : b6be4000-b6be5000 rw-p 0001e000 b3:17 2538       /system/lib/libinput.so
07-27 08:53:28.894  5703  5703 W art     : b6be5000-b6c32000 r-xp 00000000 b3:17 2763       /system/lib/libgui.so
07-27 08:53:28.894  5703  5703 W art     : b6c32000-b6c33000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6c33000-b6c3f000 r--p 0004d000 b3:17 2763       /system/lib/libgui.so
07-27 08:53:28.894  5703  5703 W art     : b6c3f000-b6c40000 rw-p 00059000 b3:17 2763       /system/lib/libgui.so
07-27 08:53:28.894  5703  5703 W art     : b6c40000-b6c4d000 r-xp 00000000 b3:17 2719       /system/lib/libui.so
07-27 08:53:28.894  5703  5703 W art     : b6c4d000-b6c4e000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6c4e000-b6c4f000 r--p 0000d000 b3:17 2719       /system/lib/libui.so
07-27 08:53:28.894  5703  5703 W art     : b6c4f000-b6c50000 rw-p 0000e000 b3:17 2719       /system/lib/libui.so
07-27 08:53:28.894  5703  5703 W art     : b6c50000-b6c58000 r-xp 00000000 b3:17 2160       /system/lib/libnetutils.so
07-27 08:53:28.894  5703  5703 W art     : b6c58000-b6c59000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6c59000-b6c5a000 r--p 00008000 b3:17 2160       /system/lib/libnetutils.so
07-27 08:53:28.894  5703  5703 W art     : b6c5a000-b6c5b000 rw-p 00009000 b3:17 2160       /system/lib/libnetutils.so
07-27 08:53:28.894  5703  5703 W art     : b6c5b000-b6c62000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-27 08:53:28.894  5703  5703 W art     : b6c62000-b6c63000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-27 08:53:28.894  5703  5703 W art     : b6c63000-b6c64000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-27 08:53:28.894  5703  5703 W art     : b6c64000-b6c78000 r-xp 00000000 b3:17 2082       /system/lib/libexpat.so
07-27 08:53:28.894  5703  5703 W art     : b6c78000-b6c7a000 r--p 00013000 b3:17 2082       /system/lib/libexpat.so
07-27 08:53:28.894  5703  5703 W art     : b6c7a000-b6c7b000 rw-p 00015000 b3:17 2082       /s,ystem/lib/libexpat.so
07-27 08:53:28.894  5703  5703 W art     : b6c7b000-b6ca3000 r-xp 00000000 b3:17 1012       /system/lib/libandroidfw.so
07-27 08:53:28.894  5703  5703 W art     : b6ca3000-b6ca5000 r--p 00027000 b3:17 1012       /system/lib/libandroidfw.so
07-27 08:53:28.894  5703  5703 W art     : b6ca5000-b6ca6000 rw-p 00029000 b3:17 1012       /system/lib/libandroidfw.so
07-27 08:53:28.894  5703  5703 W art     : b6ca6000-b6ca9000 r-xp 00000000 b3:17 2457       /system/lib/libmemtrack.so
07-27 08:53:28.894  5703  5703 W art     : b6ca9000-b6caa000 r--p 00002000 b3:17 2457       /system/lib/libmemtrack.so
07-27 08:53:28.894  5703  5703 W art     : b6caa000-b6cab000 rw-p 00003000 b3:17 2457       /system/lib/libmemtrack.so
07-27 08:53:28.894  5703  5703 W art     : b6cab000-b6cb4000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-27 08:53:28.894  5703  5703 W art     : b6cb4000-b6cb5000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-27 08:53:28.894  5703  5703 W art     : b6cb5000-b6cb6000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-27 08:53:28.894  5703  5703 W art     : b6cb6000-b6cd6000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-27 08:53:28.894  5703  5703 W art     : b6cd6000-b6cd7000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-27 08:53:28.894  5703  5703 W art     : b6cd7000-b6cd8000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-27 08:53:28.894  5703  5703 W art     : b6cd8000-b6d4b000 r-xp 00000000 b3:17 328        /system/lib/libc.so
07-27 08:53:28.894  5703  5703 W art     : b6d4b000-b6d4f000 r--p 00072000 b3:17 328        /system/lib/libc.so
07-27 08:53:28.894  5703  5703 W art     : b6d4f000-b6d52000 rw-p 00076000 b3:17 328        /system/lib/libc.so
07-27 08:53:28.894  5703  5703 W art     : b6d52000-b6d5c000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6d5c000-b6de4000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-27 08:53:28.894  5703  5703 W art     : b6de4000-b6de5000 ---p 00000000 00:00 0 
,07-27 08:53:28.894  5703  5703 W art     : b6de5000-b6de9000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-27 08:53:28.894  5703  5703 W art     : b6de9000-b6dea000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-27 08:53:28.894  5703  5703 W art     : b6dea000-b6deb000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6deb000-b6e14000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-27 08:53:28.894  5703  5703 W art     : b6e14000-b6e15000 ---p 00000000 00:00 0 
,07-27 08:53:28.894  5703  5703 W art     : b6e15000-b6e18000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-27 08:53:28.894  5703  5703 W art     : b6e18000-b6e19000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-27 08:53:28.894  5703  5703 W art     : b6e19000-b6ef3000 r-xp 00000000 b3:17 460        /system/lib/libandroid_runtime.so
07-27 08:53:28.894  5703  5703 W art     : b6ef3000-b6efa000 r--p 000d9000 b3:17 460        /system/lib/libandroid_runtime.so
07-27 08:53:28.894  5703  5703 W art     : b6efa000-b6f02000 rw-p 000e0000 b3:17 460        /system/lib/libandroid_runtime.so
07-27 08:53:28.894  5703  5703 W art     : b6f02000-b6f03000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6f03000-b6f04000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:53:28.894  5703  5703 W art     : b6f04000-b6f05000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-27 08:53:28.894  5703  5703 W art     : b6f05000-b6f06000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b6f06000-b6f09000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b6f09000-b6f2e000 r-xp 00000000 b3:17 2107       /system/lib/libbinder.so
07-27 08:53:28.894  5703  5703 W art     : b6f2e000-b6f2f000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6f2f000-b6f36000 r--p 00025000 b3:17 2107       /system/lib/libbinder.so
07-27 08:53:28.894  5703  5703 W art     : b6f36000-b6f37000 rw-p 0002c000 b3:17 2107       /system/lib/libbinder.so
07-27 08:53:28.894  5703  5703 W art     : b6f37000-b6f3e000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-27 08:53:28.894  5703  5703 W art     : b6f3e000-b6f3f000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-27 08:53:28.894  5703  5703 W art     : b6f3f000-b6f40000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-27 08:53:28.894  5703  5703 W art     : b6f40000-b6f41000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b6f41000-b6f59000 r-xp 00000000 b3:17 2149       /system/lib/libutils.so
07-27 08:53:28.894  5703  5703 W art     : b6f59000-b6f5a000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6f5a000-b6f5b000 r--p 00018000 b3:17 2149       /system/lib/libutils.so
07-27 08:53:28.894  5703  5703 W art     : b6f5b000-b6f5c000 rw-p 00019000 b3:17 2149       /system/lib/libutils.so
07-27 08:53:28.894  5703  5703 W art     : b6f5c000-b6f6a000 r-xp 00000000 b3:17 2714       /system/lib/libcutils.so
07-27 08:53:28.894  5703  5703 W art     : b6f6a000-b6f6b000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6f6b000-b6f6c000 r--p 0000e000 b3:17 2714       /system/lib/libcutils.so
07-27 08:53:28.894  5703  5703 W art     : b6f6c000-b6f6d000 rw-p 0000f000 b3:17 2714       /system/lib/libcutils.so
07-27 08:53:28.894  5703  5703 W art     : b6f6d000-b6f6e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:53:28.894  5703  5703 W art     : b6f6e000-b6f70000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b6f70000-b6f71000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b6f71000-b6f72000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:53:28.894  5703  5703 W art     : b6f72000-b6f73000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-27 08:53:28.894  5703  5703 W art     : b6f73000-b6f74000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:53:28.894  5703  5703 W art     : b6f74000-b6f94000 r--s 00000000 00:0b 6702       /dev/__properties__
07-27 08:53:28.894  5703  5703 W art     : b6f94000-b6f95000 r--p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6f95000-b6f96000 ---p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6f96000-b6f98000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-27 08:53:28.894  5703  5703 W art     : b6f98000-b6f99000, r-xp 00000000 00:00 0          [sigpage]
07-27 08:53:28.894  5703  5703 W art     : b6f99000-b6fb4000 r-xp 00000000 b3:17 2771       /system/bin/linker
07-27 08:53:28.894  5703  5703 W art     : b6fb4000-b6fb5000 r--p 0001a000 b3:17 2771       /system/bin/linker
07-27 08:53:28.894  5703  5703 W art     : b6fb5000-b6fb7000 rw-p 0001b000 b3:17 2771       /system/bin/linker
07-27 08:53:28.894  5703  5703 W art     : b6fb7000-b6fb9000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : b6fb9000-b6fbe000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-27 08:53:28.894  5703  5703 W art     : b6fbe000-b6fbf000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-27 08:53:28.894  5703  5703 W art     : b6fbf000-b6fc0000 rw-p 00000000 00:00 0 
07-27 08:53:28.894  5703  5703 W art     : bea58000-bea79000 rw-p 00000000 00:00 0          [stack]
07-27 08:53:28.894  5703  5703 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-27 08:53:28.934  5703  5703 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 08:53:28.934  5782  5782 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:28.934  5782  5782 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:28.944   749  1733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e27ccee 5782:com.sec.android.app.myfiles/u0a51}
07-27 08:53:28.954  5782  5782 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
07-27 08:53:28.964  5782  5782 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
07-27 08:53:28.974  5703  5703 I Radio-JNI: register_android_hardware_Radio DONE
07-27 08:53:28.984  5703  5703 E AffinityControl: AffinityControl: registerfunction enter
07-27 08:53:29.004  5703  5703 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 08:53:29.014  5782  5782 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
07-27 08:53:29.014   749  1567 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-27 08:53:29.034   749  1567 D ActivityManager: mDVFSHelper.acquire()
07-27 08:53:29.034   749  1567 D FocusedStackFrame: Set to : 0
07-27 08:53:29.034   749  1567 V WindowManager: addAppToken: AppWindowToken{3dcd425 token=Token{e12501c ActivityRecord{576f58f u0 com.test.thalitest/.MainActivity t102}}} to stack=1 task=102 at 0
07-27 08:53:29.044  5802  5802 E Zygote  : v2
07-27 08:53:29.044  5802  5802 I libpersona: KNOX_SDCARD checking this for 10004
07-27 08:53:29.044  5802  5802 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:29.044  5802  5802 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:29.044  5802  5802 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:29.044   749  1567 I ActivityManager: Start proc 5802:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-27 08:53:29.044   749  1567 D InputDispatcher: Focused application set to: xxxx
07-27 08:53:29.044   749   874 D SecWifiDisplayUtil: Metadata value : none
07-27 08:53:29.044   749   874 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{85262dd V.E...... R.....ID 0,0-0,0}
07-27 08:53:29.044  5802  5802 E Zygote  : accessInfo : 0
07-27 08:53:29.044  5802  5802 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-27 08:53:29.044   749  1567 D InputDispatcher: Focus left window: 1700
07-27 08:53:29.054   749   874 D ISSUE_DEBUG: InputChannelName : 6f99523 Starting com.test.thalitest
07-27 08:53:29.054   749  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-27 08:53:29.054  5703  5703 D AndroidRuntime: Shutting down VM
07-27 08:53:29.064   292   292 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
07-27 08:53:29.074  5802  5802 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:29.074  5802  5802 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:29.074   749   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:749 uid:1000
07-27 08:53:29.074   749   874 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:53:29.074   749   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:749 uid:1000
07-27 08:53:29.074   749   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 08:53:29.074   749  1740 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
07-27 08:53:29.074   749   874 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-27 08:53:29.074   749  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 08:53:29.084   749  1320 V WindowOrientationListener: setCurrentAppOrientation :-1
07-27 08:53:29.084   749  1320 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-27 08:53:29.084   320   320 E installd: system dir 0 : /system/app/
07-27 08:53:29.084   320   320 E installd: system dir 1 : /system/priv-app/
07-27 08:53:29.084   320   320 E installd: system dir 2 : /vendor/app/
07-27 08:53:29.084   320   320 E installd: system dir 3 : /oem/app/
07-27 08:53:29.094   749   828 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6f99523 u0 d0 Starting com.test.thalitest}
07-27 08:53:29.094  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-27 08:53:29.094  1700  1873 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
07-27 08:53:29.094  1700  1700 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
07-27 08:53:29.104   749  1320 D ActivityManager:  Launching com.test.thalitest, updated priority
07-27 08:53:29.104   749   911 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
07-27 08:53:29.124   292  1295 D libEGL  : eglTerminate EGLDisplay = 0xb46bf64c
07-27 08:53:29.134   292  1295 D libEGL  : eglTerminate EGLDisplay = 0xb46bf64c
07-27 08:53:29.134   749   874 V WindowStateAnimator: Finishing drawing window Window{6f99523 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-27 08:53:29.134   292  1295 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
07-27 08:53:29.134   292   359 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
07-27 08:53:29.134   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbea7a3a4
07-27 08:53:29.134   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbea7a364
07-27 08:53:29.144  2183  2194 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
07-27 08:53:29.144  1700  1700 V ActivityThread: updateVisibility : ActivityRecord{e77df5a token=android.os.BinderProxy@6d6d87d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-27 08:53:29.144  1700  1700 D Launcher: onTrimMemory. Level: 20
,07-27 08:53:29.304  1943  3910 I Icing   : Indexing 7FD7DC72F962A835E74969A77ACD5AA3CFBC05C4 from com.google.android.gms
,07-27 08:53:29.444   749  1320 I WindowManager: Screenshot max retries 4 of Token{e12501c ActivityRecord{576f58f u0 com.test.thalitest/.MainActivity t102}} appWin=Window{6f99523 u0 d0 Starting com.test.thalitest} drawState=4
,07-27 08:53:29.454   749   826 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,07-27 08:53:29.474   749  1625 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
,07-27 08:53:29.474  5802  5802 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-27 08:53:29.494   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:29.514  5802  5802 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-27 08:53:29.514  5802  5802 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-27 08:53:29.534  5802  5802 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
07-27 08:53:29.544   749  1747 I ActivityManager: Start proc 5822:com.samsung.android.provider.shootingmodeprovider/u0a170 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
07-27 08:53:29.564  5822  5822 E Zygote  : v2
07-27 08:53:29.564  5822  5822 I libpersona: KNOX_SDCARD checking this for 10170
07-27 08:53:29.564  5822  5822 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:29.564  5822  5822 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:29.564  5822  5822 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:29.564  5822  5822 E Zygote  : accessInfo : 0
07-27 08:53:29.564  5822  5822 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
07-27 08:53:29.564  5802  5802 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
07-27 08:53:29.564   749  1235 V AlarmManager: Expired Alarm result :8
07-27 08:53:29.574  5802  5802 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-27 08:53:29.584  5802  5802 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 7266-7270)
07-27 08:53:29.584  5802  5802 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-27 08:53:29.594  5822  5822 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:29.594  5822  5822 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:29.604   749  1712 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{517f84c 5822:com.samsung.android.provider.shootingmodeprovider/u0a170}
07-27 08:53:29.604  5802  5802 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d57cccd}
07-27 08:53:29.604  5802  5844 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
07-27 08:53:29.604  5802  5802 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-27 08:53:29.614  5822  5822 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
07-27 08:53:29.624  5802  5802 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:53:29.624  5822  5822 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
07-27 08:53:29.634  5802  5802 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-27 08:53:29.634  1943  3910 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
07-27 08:53:29.644  1943  3910 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
07-27 08:53:29.644  1943  3910 D Icing   : Loaded CLD2 Version V2.0 - 20141016
07-27 08:53:29.654  1943  3910 I Icing   : Indexing done 7FD7DC72F962A835E74969A77ACD5AA3CFBC05C4
07-27 08:53:29.664   749  2078 I ActivityManager: Killing 5116:com.sec.providers.settingsearch/u0a168 (adj 15): DHA:empty #37
07-27 08:53:29.664   749  2078 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e658400 1682:com.android.phone/1001}
07-27 08:53:29.674  5802  5846 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
07-27 08:53:29.684   749  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{736895c 1817:com.google.android.googlequicksearchbox:search/u0a62}
07-27 08:53:29.684   749  1733 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
07-27 08:53:29.694  5802  5802 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-27 08:53:29.694  5802  5802 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-27 08:53:29.694  5802  5802 I Adreno-EGL: Build Date: 01/28/16 Thu
07-27 08:53:29.694  5802  5802 I Adreno-EGL: Local Branch: ss
07-27 08:53:29.694  5802  5802 I Adreno-EGL: Remote Branch: 
07-27 08:53:29.694  5802  5802 I Adreno-EGL: Local Patches: 
07-27 08:53:29.694  5802  5802 I Adreno-EGL: Reconstruct Branch: 
07-27 08:53:29.704   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{736895c 1817:com.google.android.googlequicksearchbox:search/u0a62}
07-27 08:53:29.704  5802  5802 D libEGL  : eglInitialize EGLDisplay = 0xbec9cdac
07-27 08:53:29.704   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e26a5aa 5648:com.samsung.android.sm.provider/1000}
07-27 08:53:29.724  5853  5853 E Zygote  : v2
07-27 08:53:29.724  5853  5853 I libpersona: KNOX_SDCARD checking this for 5012
07-27 08:53:29.724  5853  5853 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:29.724  5853  5853 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:29.724  5853  5853 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:29.724   749  1414 I ActivityManager: Start proc 5853:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
07-27 08:53:29.734  5853  5853 E Zygote  : accessInfo : 0
07-27 08:53:29.734  5853  5853 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
07-27 08:53:29.734  1817  5851 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-27 08:53:29.744   749  1320 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
07-27 08:53:29.744   749  1320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
07-27 08:53:29.784  5853  5853 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:29.784  5853  5853 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:29.784   749  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bbb6f14 5853:com.samsung.android.sm.devicesecurity/5012}
07-27 08:53:29.804  5853  5853 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
07-27 08:53:29.804  5802  5802 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
07-27 08:53:29.814  1817  5851 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
07-27 08:53:29.824  5802  5802 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 08:53:29.824  5802  5802 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
07-27 08:53:29.824  5802  5802 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
07-27 08:53:29.824  5853  5853 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
07-27 08:53:29.824  5802  5802 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
07-27 08:53:29.824  1817  5851 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
07-27 08:53:29.834  5802  5802 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
07-27 08:53:29.844  5802  5802 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-27 08:53:29.864   749   762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{684f26b 3085:com.android.contacts/u0a20}
07-27 08:53:29.884   749  1415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca91db8 5007:com.android.mms/u0a50}
07-27 08:53:29.894  5802  5802 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{fc1ac73 I.E...... R.....ID 0,0-0,0}
07-27 08:53:29.894  5802  5802 D SecWifiDisplayUtil: Metadata value : none
07-27 08:53:29.894   749  1747 I ActivityManager: Start proc 5887:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
07-27 08:53:29.894  5887  5887 E Zygote  : v2
07-27 08:53:29.894  5887  5887 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:29.894  5887  5887 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:29.894  5802  5886 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-27 08:53:29.894  5887  5887 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:29.894  5887  5887 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:29.904  5887  5887 E Zygote  : accessInfo : 0
07-27 08:53:29.914   749  1740 D ISSUE_DEBUG: InputChannelName : d22410a com.test.thalitest/com.test.thalitest.MainActivity
07-27 08:53:29.914   749  1712 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-27 08:53:29.914   749  1712 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 08:53:29.914   749   749 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 08:53:29.914   749   749 I KnoxTimeoutHandler: Shared devices show user statefalse
07-27 08:53:29.944  5802  5802 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 5802
07-27 08:53:29.944  5887  5887 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:29.944  5887  5887 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:29.944  1817  5851 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 209 ms] updated apps [took 209 ms] 
07-27 08:53:29.944   749   762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d1e762 5887:com.samsung.android.bbc.bbcagent/1000}
07-27 08:53:29.954   749  1733 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/5802 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:29.954   749  1415 I ActivityManager: Killing 4843:com.samsung.android.sm/1000 (adj 15): DHA:empty #37
07-27 08:53:29.964  5887  5887 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
07-27 08:53:29.964  5802  5844 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
07-27 08:53:29.964  5802  5802 D SecWifiDisplayUtil: Metadata value : none
07-27 08:53:29.974   749  1746 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
07-27 08:53:29.974   292   292 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
07-27 08:53:29.984  5887  5887 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
07-27 08:53:29.994   749   761 D InputDispatcher: Focus entered window: 5802
07-27 08:53:30.004   749   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:749 uid:1000
07-27 08:53:30.004   749   874 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:53:30.004   749   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:749 uid:1000
07-27 08:53:30.004   749   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 08:53:30.004  5802  5886 D libEGL  : eglInitialize EGLDisplay = 0x9d63f7c4
07-27 08:53:30.004  5802  5886 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 08:53:30.014  5903  5903 E Zygote  : v2
07-27 08:53:30.014  5903  5903 I libpersona: KNOX_SDCARD checking this for 10098
07-27 08:53:30.014  5903  5903 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:30.014  5903  5903 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:30.014  5903  5903 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:30.014  5903  5903 E Zygote  : accessInfo : 0
07-27 08:53:30.014  5903  5903 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
07-27 08:53:30.014   749  1712 I ActivityManager: Start proc 5903:com.google.android.apps.docs/u0a98 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
07-27 08:53:30.024   749  1712 I ActivityManager: Killing 5151:com.sec.esdk.elm/u0a104 (adj 15): DHA:empty #37
07-27 08:53:30.044  5903  5903 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:30.044  5903  5903 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:30.044   749  1713 D ActivityManager: isAutoRunBlockedApp:: com.sec.esdk.elm, Auto Run ON
07-27 08:53:30.054   749  2078 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5ab90f3 5903:com.google.android.apps.docs/u0a98}
07-27 08:53:30.064  5802  5802 V ActivityThread: updateVisibility : ActivityRecord{ca4065c token=android.os.BinderProxy@64940e2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-27 08:53:30.064  5802  5802 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
07-27 08:53:30.064  5903  5903 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
07-27 08:53:30.084  5903  5903 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
07-27 08:53:30.084   749  2079 V WindowStateAnimator: Finishing drawing window Window{d22410a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
07-27 08:53:30.084  5802  5802 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-27 08:53:30.094  5802  5802 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-27 08:53:30.094   749  1320 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-27 08:53:30.094   749   874 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 08:53:30.094   749   749 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 08:53:30.094   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbea7a364
07-27 08:53:30.094   749   874 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +657ms (total +1s66ms)
07-27 08:53:30.104   749   749 I KnoxTimeoutHandler: SD activityfalse
07-27 08:53:30.104  5802  5802 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-27 08:53:30.104   749   874 D ActivityManager: mDVFSHelper.release()
07-27 08:53:30.104   749   874 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{576f58f u0 com.test.thalitest/.MainActivity t102} time:77792
07-27 08:53:30.104   749   874 D ViewRootImpl: #3 mView = null
07-27 08:53:30.104   292   361 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
07-27 08:53:30.104   292  1296 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
07-27 08:53:30.114   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbea7a3a4
07-27 08:53:30.124   749  1567 V WindowStateAnimator: Finishing drawing window Window{d22410a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
07-27 08:53:30.124  5802  5802 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@64940e2 time:77812
07-27 08:53:30.124  5802  5919 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:53:30.134  5802  5919 D libEGL  : eglInitialize EGLDisplay = 0x9c1583ec
07-27 08:53:30.134   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbea7a364
07-27 08:53:30.174  5802  5802 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5802
07-27 08:53:30.314   749  5608 I HarmonyEASService: Updating for all 1
07-27 08:53:30.334  5802  5802 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-27 08:53:30.414  5903  5929 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
07-27 08:53:30.414  5903  5929 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 08:53:30.414  5903  5929 I GAv4    :   adb logcat -s GAv4
07-27 08:53:30.434  5903  5929 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
07-27 08:53:30.434  5802  5930 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1693451984
07-27 08:53:30.434   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{22378dc: PendingIntentRecord{e15ade5 com.google.android.apps.docs broadcastIntent}}
07-27 08:53:30.434  5903  5929 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
07-27 08:53:30.434  5802  5930 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:53:30.434  5802  5930 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:53:30.434  5802  5930 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:53:30.434  5802  5930 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:53:30.434  5802  5930 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 08:53:30.434  5802  5930 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@507a692 added. We now have 1 listener(s)
07-27 08:53:30.434  5903  5929 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-27 08:53:30.444  5802  5930 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:3F:75:69
07-27 08:53:30.444  5802  5930 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:3F:75:69"
07-27 08:53:30.444  5802  5930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 08:53:30.444  5802  5930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 08:53:30.444  5903  5936 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:3F:75:69
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 08:53:30.444  5802  5930 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90a2519 added. We now have 1 listener(s)
07-27 08:53:30.444  5802  5930 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 08:53:30.444  5802  5930 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:30.444  5802  5930 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-27 08:53:30.444  5802  5930 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 08:53:30.444  5802  5930 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:53:30.444  5802  5930 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:53:30.444  5802  5930 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 08:53:30.454  5802  5930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:53:30.454  5802  5930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:3F:75:69
07-27 08:53:30.454  5802  5930 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:30.454  5802  5930 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:53:30.454  5802  5930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:30.454  5802  5930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:30.454  5802  5930 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:53:30.454  5802  5930 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:30.454  5802  5930 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:30.454  5802  5930 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:30.454  5802  5930 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:53:30.454  5802  5930 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 08:53:30.454  5802  5930 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:53:30.454  5802  5930 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 08:53:30.454   749  3344 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-27 08:53:30.484  5802  5802 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-27 08:53:30.514   749  2078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 08:53:30.514   749  2078 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4210, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-27 08:53:30.514   749  2078 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-27 08:53:30.514   749  2078 D BatteryService: stay LED for charging
07-27 08:53:30.514   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 08:53:30.514   749   749 I MotionRecognitionService: Plugged
07-27 08:53:30.514   749   749 D MotionRecognitionService:   cableConnection= 1
07-27 08:53:30.514   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:53:30.514   749   749 D MotionRecognitionService: skip setTransmitPower. 
07-27 08:53:30.514  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:53:30.514  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:53:30.514  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 08:53:30.534  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:53:30.544  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-27 08:53:30.544  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:53:30.544  5903  5903 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,07-27 08:53:30.544  5903  5903 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,07-27 08:53:30.574  5903  5929 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
07-27 08:53:30.574  5903  5929 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,07-27 08:53:30.574  5903  5929 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,07-27 08:53:30.574  5903  5929 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,07-27 08:53:30.634  5943  5943 E Zygote  : v2
,07-27 08:53:30.634  5943  5943 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:30.634   749  1414 I ActivityManager: Start proc 5943:com.sec.android.automotive.drivelink/u0a99 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
07-27 08:53:30.634  5943  5943 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:30.634  5943  5943 I libpersona: KNOX_SDCARD checking this for 10099
07-27 08:53:30.634  5943  5943 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:30.634   749  1414 I ActivityManager: Killing 5181:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): DHA:empty #37
07-27 08:53:30.644  5943  5943 E Zygote  : accessInfo : 0
,07-27 08:53:30.644  5943  5943 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,07-27 08:53:30.654   749  1567 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,07-27 08:53:30.684  5943  5943 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:30.684  5943  5943 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:30.694   749  2078 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a9ce3 5943:com.sec.android.automotive.drivelink/u0a99}
,07-27 08:53:30.694  5943  5943 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,07-27 08:53:30.714  5943  5943 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,07-27 08:53:30.714  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:53:30.714  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:53:30.734  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:53:30.804  5903  5931 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,07-27 08:53:30.824   749   759 I art     : Background partial concurrent mark sweep GC freed 125919(7MB) AllocSpace objects, 9(1652KB) LOS objects, 27% free, 41MB/57MB, paused 2.890ms total 162.182ms
,07-27 08:53:30.834  5903  5931 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm
,07-27 08:53:30.834  5943  5943 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,07-27 08:53:30.844   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{46cc55b: PendingIntentRecord{5d3f1f8 com.sec.android.automotive.drivelink broadcastIntent}}
,07-27 08:53:30.854  5943  5943 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,07-27 08:53:30.864  5943  5957 I GMPM    : App measurement is starting up
,07-27 08:53:30.874  5943  5957 E GMPM    : getGoogleAppId failed with status: 10
,07-27 08:53:30.884  5943  5957 E GMPM    : Uploading is not possible. App measurement disabled
,07-27 08:53:30.884   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{cc7c6d1: PendingIntentRecord{5d3f1f8 com.sec.android.automotive.drivelink broadcastIntent}}
,07-27 08:53:30.924  1451  1451 D Recents : onTaskStackChanged
,07-27 08:53:30.924  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-27 08:53:30.924  5903  5931 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-27 08:53:30.934  5943  5943 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,07-27 08:53:30.944  5943  5943 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,07-27 08:53:30.964  5903  5931 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:53:30.984  1943  3910 I Icing   : Indexing EF63CEC2998F8E1A114BBA3A5515DD2FA8B6047E from com.google.android.googlequicksearchbox
,07-27 08:53:31.004  5963  5963 E Zygote  : v2
,07-27 08:53:31.004  5963  5963 I libpersona: KNOX_SDCARD checking this for 10033
07-27 08:53:31.004   749  1567 I ActivityManager: Start proc 5963:com.vlingo.midas/u0a33 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
07-27 08:53:31.004  5963  5963 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:31.004   749  1323 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 08:53:31.004  5963  5963 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:31.004  5963  5963 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:31.004  5963  5963 E Zygote  : accessInfo : 0
,07-27 08:53:31.004   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:53:31.004  5963  5963 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,07-27 08:53:31.004   749  1323 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 08:53:31.044  5963  5963 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:31.044  5963  5963 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:31.044  1943  3910 I Icing   : Indexing done EF63CEC2998F8E1A114BBA3A5515DD2FA8B6047E
,07-27 08:53:31.054  5963  5963 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,07-27 08:53:31.064  5963  5963 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,07-27 08:53:31.134  5802  5937 W jxcore-log: Initializing JXcore engine
07-27 08:53:31.134  5802  5937 W jxcore-log: JXcore engine is ready
,07-27 08:53:31.144  5943  5943 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,07-27 08:53:31.154  5943  5943 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,07-27 08:53:31.154  5943  5943 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,07-27 08:53:31.154  5943  5943 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDWed Jul 27 08:53:31 GMT+02:00 2016
,07-27 08:53:31.164  5977  5977 E Zygote  : v2
,07-27 08:53:31.164   749   761 I ActivityManager: Start proc 5977:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
07-27 08:53:31.164  5977  5977 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:31.164  5977  5977 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:31.164  5977  5977 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:31.164  5977  5977 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:31.164  5977  5977 E Zygote  : accessInfo : 0
07-27 08:53:31.164   749   761 I ActivityManager: Killing 5139:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #37
07-27 08:53:31.164   749   761 I ActivityManager: Killing 5198:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): DHA:empty #37
,07-27 08:53:31.174  5943  5943 D DialogFlow: initQueue()
,07-27 08:53:31.174  5963  5963 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=DBT
,07-27 08:53:31.184  2335  2335 E audit   : type=1400 msg=audit(1469602411.184:281): avc:  denied  { ioctl } for  pid=5937 comm="Thread-819" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-27 08:53:31.184  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:31.184  2335  2335 E audit   : type=1300 msg=audit(1469602411.184:281): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=993243c8 items=0 ppid=349 ppcomm=main pid=5937 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-819" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:53:31.184  2335  2335 E audit   : type=1327 msg=audit(1469602411.184:281): proctitle="com.test.thalitest"
07-27 08:53:31.184  2335  2335 E audit   : type=1320 msg=audit(1469602411.184:281): 
,07-27 08:53:31.184  2335  2335 E audit   : type=1400 msg=audit(1469602411.184:282): avc:  denied  { ioctl } for  pid=5937 comm="Thread-819" path="socket:[37079]" dev="sockfs" ino=37079 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-27 08:53:31.184  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:31.194  2335  2335 E audit   : type=1300 msg=audit(1469602411.184:282): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=3 a3=993243c8 items=0 ppid=349 ppcomm=main pid=5937 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-819" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:53:31.194  2335  2335 E audit   : type=1327 msg=audit(1469602411.184:282): proctitle="com.test.thalitest"
07-27 08:53:31.194  2335  2335 E audit   : type=1320 msg=audit(1469602411.184:282): 
,07-27 08:53:31.194   749  2078 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,07-27 08:53:31.194  5977  5977 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:31.194  5977  5977 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:31.204  5963  5963 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,07-27 08:53:31.204  5802  5937 W jxcore-log: Starting JXcore engine
,07-27 08:53:31.204   749  1733 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
,07-27 08:53:31.214   749  1740 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84f0810 5977:com.samsung.android.app.filterinstaller/1000}
,07-27 08:53:31.224  5977  5977 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,07-27 08:53:31.234  5977  5977 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,07-27 08:53:31.244  5977  5977 E FilterPackageIntentReceiver: This package is not a effect filter
,07-27 08:53:31.244   749  2078 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10033
,07-27 08:53:31.254  5993  5993 E Zygote  : v2
07-27 08:53:31.254  5993  5993 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:31.254  5993  5993 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:31.254  5993  5993 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:31.254   749  1415 I ActivityManager: Start proc 5993:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
07-27 08:53:31.254  5993  5993 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:31.254  5993  5993 E Zygote  : accessInfo : 0
07-27 08:53:31.254   749  1415 I ActivityManager: Killing 5165:com.android.exchange/u0a164 (adj 15): DHA:empty #37
,07-27 08:53:31.274   749  1414 D ActivityManager: isAutoRunBlockedApp:: com.android.exchange, Auto Run ON
,07-27 08:53:31.284  5993  5993 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:31.284  5993  5993 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:31.294   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{325bb4b 5993:com.samsung.helphub/1000}
,07-27 08:53:31.294  5993  5993 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,07-27 08:53:31.294  5963  5963 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,07-27 08:53:31.304  5963  5963 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,07-27 08:53:31.304  5802  5937 W jxcore-log: Platform android
07-27 08:53:31.304  5802  5937 W jxcore-log: 
07-27 08:53:31.304  5802  5937 W jxcore-log: Process ARCH arm
07-27 08:53:31.304  5802  5937 W jxcore-log: 
,07-27 08:53:31.314  5993  5993 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,07-27 08:53:31.324  5963  5963 D DialogFlow: initQueue()
,07-27 08:53:31.364   749  1712 I ActivityManager: Start proc 6005:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,07-27 08:53:31.364  6005  6005 E Zygote  : v2
07-27 08:53:31.364  6005  6005 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:31.364  6005  6005 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:31.364  6005  6005 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:31.364  6005  6005 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:31.364  6005  6005 E Zygote  : accessInfo : 0
07-27 08:53:31.364   749  1712 I ActivityManager: Killing 5219:com.sec.android.app.sns3/u0a36 (adj 15): DHA:empty #37
,07-27 08:53:31.384   749  2079 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sns3, Auto Run ON
,07-27 08:53:31.394  6005  6005 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:31.394  6005  6005 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:31.394   749  1567 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d23c928 6005:com.samsung.android.app.mirrorlink/1000}
,07-27 08:53:31.414  6005  6005 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,07-27 08:53:31.424  6005  6005 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,07-27 08:53:31.464  6005  6005 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,07-27 08:53:31.464  6005  6005 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,07-27 08:53:31.464   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2844273 5368:com.google.android.apps.plus/u0a135}
,07-27 08:53:31.474   749  2079 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2844273 5368:com.google.android.apps.plus/u0a135}
,07-27 08:53:31.504   749  1733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2844273 5368:com.google.android.apps.plus/u0a135}
,07-27 08:53:31.504  5802  5937 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:53:31.504  5802  5937 I jxcore-log: 
,07-27 08:53:31.504  5802  5937 W jxcore-log: JXcore engine is started
,07-27 08:53:31.514  5802  5930 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:53:31.514  5802  5802 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:53:31.544   749  2078 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10135
,07-27 08:53:31.544   749   761 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10135
,07-27 08:53:31.554   749  1740 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10135
07-27 08:53:31.554   749  1415 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10135
07-27 08:53:31.554   749  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10135
07-27 08:53:31.554   749  1746 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10135
,07-27 08:53:31.554   749  1567 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10135
,07-27 08:53:31.564   749  1712 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10135
,07-27 08:53:31.584   749  1740 I ActivityManager: Start proc 6019:com.sec.kidsplat.installer/u0a166 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,07-27 08:53:31.584  6019  6019 E Zygote  : v2
07-27 08:53:31.584  6019  6019 I libpersona: KNOX_SDCARD checking this for 10166
07-27 08:53:31.584  6019  6019 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:31.584  6019  6019 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:31.584  6019  6019 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:31.584  6019  6019 E Zygote  : accessInfo : 0
,07-27 08:53:31.584  6019  6019 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,07-27 08:53:31.594   749  1740 I ActivityManager: Killing 5037:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,07-27 08:53:31.604  6019  6019 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:31.604  6019  6019 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:31.614   749  1746 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,07-27 08:53:31.614   749   762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{192c127 6019:com.sec.kidsplat.installer/u0a166}
,07-27 08:53:31.624  6019  6019 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,07-27 08:53:31.634  6019  6019 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,07-27 08:53:31.644   749  1415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{192c127 6019:com.sec.kidsplat.installer/u0a166}
,07-27 08:53:31.644  6019  6019 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,07-27 08:53:31.654   749  1567 I ActivityManager: Start proc 6031:com.sec.android.app.sbrowser/u0a143 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,07-27 08:53:31.654  6031  6031 E Zygote  : v2
07-27 08:53:31.654  6031  6031 I libpersona: KNOX_SDCARD checking this for 10143
07-27 08:53:31.654  6031  6031 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:31.654  6031  6031 E Zygote  : isSdpEnabledProcess - SDP enabled
,07-27 08:53:31.654  6031  6031 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:31.654  6031  6031 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:31.654   749  1567 I ActivityManager: Killing 5079:com.wssyncmldm/1000 (adj 15): DHA:empty #37
,07-27 08:53:31.654  6031  6031 E Zygote  : accessInfo : 64
07-27 08:53:31.654  6031  6031 E Zygote  : isSdpEnabledProcess - SDP enabled
07-27 08:53:31.654  6031  6031 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10143 / [uid]: 10143
,07-27 08:53:31.664  6031  6031 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,07-27 08:53:31.684   749  1712 D ActivityManager: isAutoRunBlockedApp:: com.wssyncmldm, Auto Run ON
,07-27 08:53:31.684  6031  6031 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:31.684  6031  6031 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:31.694   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d804fd4 6031:com.sec.android.app.sbrowser/u0a143}
,07-27 08:53:31.704  6031  6031 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,07-27 08:53:31.724  6031  6031 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,07-27 08:53:31.784  6031  6031 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,07-27 08:53:31.784  6031  6031 D ManifestProvider: onCreate()
,07-27 08:53:31.794  6031  6031 I SBrowserUtils: getSystemProperty of sales_code : DBT
07-27 08:53:31.794  6031  6031 I SBrowserUtils: getSystemProperty of country_code : Germany
07-27 08:53:31.794  6031  6031 I SBrowserUtils: getSystemProperty of country_code : Germany
,07-27 08:53:31.794  6031  6031 I SBrowserUtils: getSystemProperty of countryiso_code : DE
,07-27 08:53:31.804  6031  6031 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,07-27 08:53:31.804  6031  6031 D [MM]MHDataBaseProvider: onCreate()
,07-27 08:53:31.824  6031  6031 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@91d0bce)
,07-27 08:53:31.844  6045  6045 E Zygote  : v2
07-27 08:53:31.844   749  1740 I ActivityManager: Start proc 6045:com.sec.android.app.samsungapps/u0a40 for broadcast-3 com.sec.android.app.samsungapps/.MyPackageReplacedReceiver
07-27 08:53:31.844  6045  6045 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:31.844  6045  6045 I libpersona: KNOX_SDCARD checking this for 10040
07-27 08:53:31.844  6045  6045 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:31.844  6045  6045 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:31.844  6045  6045 E Zygote  : accessInfo : 0
07-27 08:53:31.844   749  1740 I ActivityManager: Killing 5249:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): DHA:empty #37
07-27 08:53:31.844  6045  6045 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,07-27 08:53:31.864   749  1747 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.SPlannerAppWidget, Auto Run ON
,07-27 08:53:31.874  6045  6045 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:31.874  6045  6045 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:31.874   749  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4682172 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ecc57d 6045:com.sec.android.app.samsungapps/u0a40}
,07-27 08:53:31.884  6045  6045 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.sec.android.app.samsungapps rsrc of package null
,07-27 08:53:31.904  6045  6045 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-2/lib/arm
,07-27 08:53:31.984   749  2079 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9aa5c72 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8be352 5454:com.sec.android.app.shealth/u0a35}
,07-27 08:53:31.994   749  2079 I ActivityManager: Killing 4805:com.android.calendar/u0a150 (adj 15): DHA:empty #37
,07-27 08:53:31.994   749  2079 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9aa5c72 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f630343 1887:com.sec.android.app.shealth:remote/u0a35}
,07-27 08:53:32.004   749  1747 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
,07-27 08:53:32.014   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9aa5c72 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f630343 1887:com.sec.android.app.shealth:remote/u0a35}
,07-27 08:53:32.084  5963  5991 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-27 08:53:32.084  5963  5991 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
07-27 08:53:32.084   749  1367 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/102_task.xml.bak
,07-27 08:53:32.104  5963  5991 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-27 08:53:32.104  5963  5991 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
07-27 08:53:32.104  5963  5991 I System.out: INFO:Resource not found:/Common.properties Using default values
,07-27 08:53:32.114  5963  5991 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-27 08:53:32.114  5963  5991 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-27 08:53:35.104   749  1733 I ActivityManager: Killing 4884:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,07-27 08:53:35.134   749  1625 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,07-27 08:53:35.514   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:36.004   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:53:36.874   749  3343 D SSRM:n  : SIOP:: AP = 460, PST = 461, CUR = 300, LCD = 0
,07-27 08:53:38.174  1943  6080 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-27 08:53:39.074   749   911 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-27 08:53:39.094   749   911 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-27 08:53:39.144   749   911 D PackageManager: [MSG] MCS_UNBIND
,07-27 08:53:39.144   749  1712 I ActivityManager: Killing 4918:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,07-27 08:53:39.194   749  1733 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,07-27 08:53:41.004   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:53:41.864  5802  5937 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 08:53:41.864  5802  5937 I jxcore-log: 
,07-27 08:53:41.864  5802  5937 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 08:53:41.864  5802  5937 I jxcore-log: 
,07-27 08:53:41.864  5802  5937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:41.864  5802  5937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:53:41.864  5802  5937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:41.864  5802  5937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:41.864  5802  5937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:53:41.864  5802  5937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:41.864  5802  5937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:41.864  5802  5937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:41.864  5802  5937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:53:41.864  5802  5937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:41.864  5802  5937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:53:41.864  5802  5937 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 08:53:41.864  5802  5937 I jxcore-log: 
,07-27 08:53:41.874  5802  5937 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
07-27 08:53:41.874  5802  5937 I jxcore-log: 
,07-27 08:53:42.214  5802  5937 I jxcore-log: Unit Test app is loaded
07-27 08:53:42.214  5802  5937 I jxcore-log: 
,07-27 08:53:42.214  5802  5937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 08:53:42.214  5802  5937 I jxcore-log: 
,07-27 08:53:42.224  5802  5937 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-27 08:53:42.224  5802  5802 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 08:53:42.234   749  1746 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-27 08:53:42.234   749  1746 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-27 08:53:42.244   749  1746 E SContext.CaeProvider: setAttribute() : attribute is null!
,07-27 08:53:42.244   749  1746 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,07-27 08:53:42.254   749  1746 V CAE     : start(ContextProvider.java:128)
,07-27 08:53:42.254   749  1746 V CAE     : clear(ActivityTrackerRunner.java:108)
,07-27 08:53:42.254   749  1746 V CAE     : enable(ActivityTrackerRunner.java:84)
,07-27 08:53:42.254   749  1746 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 53, 42,
,07-27 08:53:42.254   749  1746 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 53, 42
,07-27 08:53:42.254   329   561 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 53, 42
,07-27 08:53:42.264   749  1746 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-27 08:53:42.264   749  1746 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-27 08:53:42.274   749  1746 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-27 08:53:42.274   749  1746 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-27 08:53:42.274   749  1746 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,07-27 08:53:42.274   749  1746 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@a7c9540, Service : ACTIVITY_TRACKER(1)
07-27 08:53:42.274   749  1746 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
,07-27 08:53:42.274   749  1746 D SContextService: 	.registerCallback : 1, client=
07-27 08:53:42.274   749  1746 D SContextService: ===== SContext Service List =====
07-27 08:53:42.274   749  1746 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@53dcdbe, Service : Activity Tracker
07-27 08:53:42.274   749  1746 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@c053c79, service=Activity Tracker
,07-27 08:53:42.274   749  1746 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
,07-27 08:53:42.284   749  1746 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
,07-27 08:53:42.284   749  1746 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
,07-27 08:53:42.284   749  1746 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
07-27 08:53:42.284   749  1746 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
07-27 08:53:42.284   329   329 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-27 08:53:42.284   749  1746 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,07-27 08:53:42.284   749  1746 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-27 08:53:42.294   749  1746 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
,07-27 08:53:42.304   749  1746 D SContextService: requestToUpdate() : service = Activity Tracker
07-27 08:53:42.304   749  1746 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@c053c79, service=Activity Tracker
07-27 08:53:42.304   749  1746 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
,07-27 08:53:42.304   749  1746 D WifiService: setWifiEnabled: true pid=5802, uid=10004
,07-27 08:53:42.304   749  1325 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,07-27 08:53:42.304   749  1746 W ActivityManager: Permission Denial: getCurrentUser() from pid=5802, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
,07-27 08:53:42.304   749  1325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18701 com.android.server.wifi.WifiStateMachine.access$3900:292 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8638 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,07-27 08:53:42.314   749  1325 D WifiBigDataLog: init : 
,07-27 08:53:42.314   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef4ae1f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5b3690 2384:com.samsung.android.providers.context/u0a175}
,07-27 08:53:42.314   749  1746 W WifiService: Failed getting userId using ActivityManagerNative
07-27 08:53:42.314   749  1746 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5802, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:53:42.314   749  1746 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28165)
07-27 08:53:42.314   749  1746 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2437)
07-27 08:53:42.314   749  1746 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2425)
07-27 08:53:42.314   749  1746 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-27 08:53:42.314   749  1746 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-27 08:53:42.314   749  1746 D SettingsProvider: isChangeAllowed() : name = wifi_on
,07-27 08:53:42.314   749  1326 D WifiController: [FCC]setFccChannel() is called !!!
,07-27 08:53:42.314   749  1712 I WifiService: disconnect: pid=5802, uid=10004
07-27 08:53:42.314   749  1326 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,07-27 08:53:42.314   749  1326 D WifiStateMachine: setFccChannel: channel = 0
,07-27 08:53:42.324   749  1326 D SecContentProvider: insert(), uri = 2
,07-27 08:53:42.324  5802  5937 D BluetoothAdapter: enable()
,07-27 08:53:42.324   749  1325 E WifiHW  : ##################### set firmware type 0 #####################
,07-27 08:53:42.324   305  1133 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-27 08:53:42.324   305  1133 I WifiHW  : module is semco 3RD
07-27 08:53:42.324   305  1133 E WifiHW  : ==========[WIFI] SEMCO 3RD MODULE ===========
07-27 08:53:42.324   305  1133 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_semco3rd
07-27 08:53:42.324   305  1133 E WifiHW  : TEMP_FAILURE_RETRY complete
07-27 08:53:42.324   305  1133 D SoftapController: Softap fwReload - Ok
,07-27 08:53:42.324   329   560 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 1, 122, -64, 88, 0, 0
,07-27 08:53:42.334   749  1747 W ActivityManager: Permission Denial: getCurrentUser() from pid=5802, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
,07-27 08:53:42.334   749  1238 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 1, 122, -64, 88, 0, 0
,07-27 08:53:42.334   749  1237 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 6, 53, 42,
,07-27 08:53:42.334   749  1237 D SensorHubManager: SendSensorHubData: send data = -63, 14, 6, 53, 42
07-27 08:53:42.334   329   561 D Sensorhubs: sendContextData: -63, 14, 6, 53, 42
,07-27 08:53:42.344   749  1747 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-27 08:53:42.344   749  1747 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5802, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:53:42.344   749  1747 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28165)
07-27 08:53:42.344   749  1747 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2848)
07-27 08:53:42.344   749  1747 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2838)
07-27 08:53:42.344   749  1747 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1218)
07-27 08:53:42.344   749  1747 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
07-27 08:53:42.344   749  1747 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:42.344   749  1747 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 08:53:42.344   749  1747 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-27 08:53:42.344   305  1133 D CommandListener: Setting iface cfg
07-27 08:53:42.344   305  1133 D CommandListener: Trying to bring down wlan0
,07-27 08:53:42.344   305  1133 D CommandListener: Clearing all IP addresses on wlan0
,07-27 08:53:42.354   749  1237 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_SLEEP
,07-27 08:53:42.354   749  1747 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,07-27 08:53:42.354   749  1325 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-27 08:53:42.354   749  1237 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
,07-27 08:53:42.354   749  1237 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 1, 122, -64, 88, 0, 0,
,07-27 08:53:42.354  5802  5937 I jxcore-log: My device name is: samsung-SM-G900F
07-27 08:53:42.354  5802  5937 I jxcore-log: 
,07-27 08:53:42.364   749  1237 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,07-27 08:53:42.364  5802  5937 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 08:53:42.364  5802  5937 I jxcore-log: 
,07-27 08:53:42.364   749   873 I ActivityManager: Start proc 6090:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 08:53:42.364  6090  6090 E Zygote  : v2
07-27 08:53:42.364  6090  6090 I libpersona: KNOX_SDCARD checking this for 1002
07-27 08:53:42.364  6090  6090 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:42.374  6090  6090 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:42.374  6090  6090 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:42.374  6090  6090 E Zygote  : accessInfo : 0
,07-27 08:53:42.374   749  1237 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1469602421848]
,07-27 08:53:42.374   749  1240 D SContextService: updateSContext() : event = Activity Tracker
,07-27 08:53:42.374   749   749 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,07-27 08:53:42.384   749   749 D WifiService: ACTIVITY_STATUS_UNKNOWN 
07-27 08:53:42.384   749   749 D WifiService: setWifiScanWithSensor bMove = 0
,07-27 08:53:42.384   749   749 D WifiStateMachine: setWifiScanMove bMove = 0
07-27 08:53:42.384   749   749 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
,07-27 08:53:42.414  6090  6090 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:42.414  6090  6090 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:42.434  6090  6090 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:53:42.454   749  1325 D wifi    : Can not initialize the vendor function pointer table
07-27 08:53:42.454   749  1325 E WifiNative-HAL: Could not start hal
07-27 08:53:42.454   749  1325 E WifiStateMachine: Failed to start HAL
,07-27 08:53:42.454   749  1325 E WifiHW  : supplicant_name : p2p_supplicant
,07-27 08:53:42.474  6090  6090 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding GattService
,07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding HeadsetService
,07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding A2dpService
07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding HidService
,07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding HealthService
07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding PanService
,07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding BluetoothMapService
,07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding SapService
07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-27 08:53:42.514  6090  6090 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-27 08:53:42.514  6090  6090 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-27 08:53:42.524   749  1625 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
07-27 08:53:42.524   749  1625 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.524   749  1625 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:42.524   749  1625 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:42.524   749  1625 D SettingsProvider: selectionArgs: false
07-27 08:53:42.524   749  1625 D SettingsProvider: selectionArgs: 1002
07-27 08:53:42.524   749  1625 D SettingsProvider: ret = -1
,07-27 08:53:42.524   749  1733 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-27 08:53:42.524   749  1733 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.524   749  1733 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:42.524   749  1733 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:42.524   749  1733 D SettingsProvider: selectionArgs: false
07-27 08:53:42.524   749  1733 D SettingsProvider: selectionArgs: 1002
,07-27 08:53:42.524   749  1733 D SettingsProvider: ret = -1
07-27 08:53:42.524   749  1740 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,07-27 08:53:42.524   749  1740 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.524   749  1740 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:42.524   749  1740 D SettingsProvider: selectionArgs: false
07-27 08:53:42.524   749  1740 D SettingsProvider: selectionArgs: 1002
07-27 08:53:42.524   749  1740 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-27 08:53:42.524   749  1740 D SettingsProvider: ret = -1
07-27 08:53:42.524   749   762 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
,07-27 08:53:42.524   749   762 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.524   749   762 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:42.524   749   762 D SettingsProvider: selectionArgs: false
07-27 08:53:42.524   749   762 D SettingsProvider: selectionArgs: 1002
,07-27 08:53:42.524   749   762 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:42.524   749   762 D SettingsProvider: ret = -1
,07-27 08:53:42.524   749   761 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-27 08:53:42.524   749   761 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.524   749   761 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:42.524   749   761 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:42.524   749   761 D SettingsProvider: selectionArgs: false
07-27 08:53:42.524   749   761 D SettingsProvider: selectionArgs: 1002
07-27 08:53:42.524   749   761 D SettingsProvider: ret = -1
,07-27 08:53:42.524   749  1415 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
07-27 08:53:42.524   749  1415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.524   749  1415 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:42.524   749  1415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:42.524   749  1415 D SettingsProvider: selectionArgs: false
07-27 08:53:42.524   749  1415 D SettingsProvider: selectionArgs: 1002
,07-27 08:53:42.524   749  1415 D SettingsProvider: ret = -1
07-27 08:53:42.524   749  1713 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,07-27 08:53:42.524   749  1713 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.524   749  1713 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:42.524   749  1713 D SettingsProvider: selectionArgs: false
07-27 08:53:42.524   749  1713 D SettingsProvider: selectionArgs: 1002
07-27 08:53:42.524   749  1713 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-27 08:53:42.534   749  1713 D SettingsProvider: ret = -1
,07-27 08:53:42.534   749  1567 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
07-27 08:53:42.534   749  1567 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.534   749  1567 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:42.534   749  1567 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:42.534   749  1567 D SettingsProvider: selectionArgs: false
07-27 08:53:42.534   749  1567 D SettingsProvider: selectionArgs: 1002
07-27 08:53:42.534   749  1567 D SettingsProvider: ret = -1
,07-27 08:53:42.534   749  1746 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:53:42.534   749  1746 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.534   749  1746 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-27 08:53:42.534   749  1746 D SettingsProvider: selectionArgs: false
07-27 08:53:42.534   749  1746 D SettingsProvider: selectionArgs: 1002
07-27 08:53:42.534   749  1746 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:42.534   749  1746 D SettingsProvider: ret = -1
07-27 08:53:42.534   749  1712 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:53:42.534   749  1712 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:42.534   749  1712 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:42.534   749  1712 D SettingsProvider: selectionArgs: false
07-27 08:53:42.534   749  1712 D SettingsProvider: selectionArgs: 1002
07-27 08:53:42.534   749  1712 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:42.534   749  1712 D SettingsProvider: ret = -1
,07-27 08:53:42.544  6111  6111 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-27 08:53:42.544  6111  6111 I wpa_supplicant: Successfully initialized wpa_supplicant
07-27 08:53:42.544  6111  6111 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,07-27 08:53:42.544  6111  6111 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-27 08:53:42.564   749  1325 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-27 08:53:42.564   749   749 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:42.574   749   749 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:42.574   749  1330 I WifiHs20Service: Message received 5011
07-27 08:53:42.574  1379  1379 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:53:42.574  1379  1379 D STATUSBAR-WifiTile: Wifi onReceive(2)
,07-27 08:53:42.574  1379  1379 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=2
,07-27 08:53:42.574  1379  1379 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:53:42.574  6111  6111 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-27 08:53:42.574   388   388 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6111
07-27 08:53:42.574   388   388 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
07-27 08:53:42.574  6111  6111 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 08:53:42.574  6111  6111 I wpa_supplicant: ssSupport state is = 1
07-27 08:53:42.574  6111  6111 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-27 08:53:42.574  6111  6111 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-27 08:53:42.574   388   388 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6111
07-27 08:53:42.574   388   388 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
07-27 08:53:42.584  1379  1379 D HotspotTile: onReceive : 2, 0
07-27 08:53:42.584  5802  5802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:53:42.584   749  1333 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-27 08:53:42.584  1379  3017 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 08:53:42.584  1682  2006 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-27 08:53:42.584  1682  2006 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-27 08:53:42.584   749  1333 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-27 08:53:42.584  1379  1379 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
07-27 08:53:42.584   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{184217 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3415604 5802:com.test.thalitest/u0a4}
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584  6111  6111 I SecureStorage: [INFO]: SPID(0x00000007)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.584   749  1415 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:42.604  6090  6090 D BluetoothAdapterState: make() - Creating AdapterState
07-27 08:53:42.604  6090  6090 I bt_bluedroid: init
07-27 08:53:42.604  6090  6116 I BluetoothAdapterState: Entering OffState
07-27 08:53:42.604   749   826 I ActivityManager: Start proc 6118:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
07-27 08:53:42.604  6118  6118 E Zygote  : v2
07-27 08:53:42.604  6118  6118 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:42.604  6118  6118 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:42.614  6118  6118 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:42.614  6118  6118 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:42.614  6118  6118 E Zygote  : accessInfo : 0
,07-27 08:53:42.614  6090  6117 E bt_core_counter: counter_init unable to open counter port
07-27 08:53:42.614  6090  6117 E bt_core_module: module_init failed to initialize "counter_module"
07-27 08:53:42.614  6090  6117 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 08:53:42.614  6090  6117 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 08:53:42.614  6090  6117 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 08:53:42.614  6090  6117 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 08:53:42.614  6090  6090 I bt_bluedroid: get_profile_interface socket
,07-27 08:53:42.614  6090  6090 W bt_btif : btif_get_adapter_property 2
07-27 08:53:42.614  6090  6090 W bt_btif : btif_get_adapter_property 1
,07-27 08:53:42.624  6090  6128 D BluetoothAdapterProperties: Address is:B0:C5:59:3F:75:69
07-27 08:53:42.624  6090  6128 E BluetoothServiceJni: populateRssiValuesNative
,07-27 08:53:42.624  6090  6128 I bt_bluedroid: getModelRssiValues
07-27 08:53:42.624  6090  6128 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-27 08:53:42.624  6090  6128 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 08:53:42.624  6090  6090 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-27 08:53:42.624   749   749 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,07-27 08:53:42.624  6090  6128 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy S5)
,07-27 08:53:42.624  6090  6090 I bt_bluedroid: get_profile_interface sdp
,07-27 08:53:42.634  6090  6100 I bt_bluedroid: config_hci_snoop_log
,07-27 08:53:42.634   749   873 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-27 08:53:42.644  6090  6116 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-27 08:53:42.644  6090  6116 D BluetoothAdapterProperties: Setting state to 14
07-27 08:53:42.644  6090  6116 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-27 08:53:42.644  6090  6116 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:53:42.644  6090  6116 D BluetoothAdapterService: updateAdapterState state is 14
,07-27 08:53:42.644  6090  6116 D BluetoothAdapterService: Autoconnection is available 
07-27 08:53:42.644  6090  6116 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,07-27 08:53:42.644   749   873 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
,07-27 08:53:42.644  6090  6116 D BluetoothSecureManager: getInstant: null
07-27 08:53:42.644  6090  6116 D BluetoothSecureManager: calling getMethod for getService
07-27 08:53:42.644  6090  6116 D BluetoothSecureManager: calling getService
,07-27 08:53:42.644  6090  6116 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@e3bd9fc
,07-27 08:53:42.644   749   761 D BluetoothSecureManagerService: isSecureModeEnabled
07-27 08:53:42.644   749   761 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
07-27 08:53:42.644  6090  6116 D BtConfig.SecureMode: isSecureModeOn:false
07-27 08:53:42.644  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 08:53:42.644  6090  6116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-27 08:53:42.644  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 08:53:42.654  6090  6116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,07-27 08:53:42.654  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 08:53:42.654  6090  6116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,07-27 08:53:42.654  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 08:53:42.654  6090  6116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-27 08:53:42.654  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-27 08:53:42.654  6090  6116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-27 08:53:42.654  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 08:53:42.654  6090  6116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-27 08:53:42.654  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 08:53:42.654  6090  6116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-27 08:53:42.654  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-27 08:53:42.654  6090  6116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
07-27 08:53:42.654  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 08:53:42.654  6090  6116 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:53:42.654  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 08:53:42.654  6090  6116 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 08:53:42.654  6090  6116 D BluetoothBondStateMachine: make
,07-27 08:53:42.654  6118  6118 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:42.654  6118  6118 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:42.654  6090  6133 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 08:53:42.664  1379  1379 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-27 08:53:42.664  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:42.664  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:42.664  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:42.664  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:42.664   749  1320 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{184217 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4abb2b 6118:com.samsung.android.securitylogagent/1000}
,07-27 08:53:42.674  6090  6116 I BluetoothAdapterState: Entering PendingCommandState
,07-27 08:53:42.674  6090  6090 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,07-27 08:53:42.674  6118  6118 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package null
,07-27 08:53:42.684  6090  6090 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 08:53:42.684  6090  6090 D BtGatt.GattService: Received start request. Starting profile...
07-27 08:53:42.684  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
07-27 08:53:42.684  6090  6090 D BtGatt.GattService: start()
07-27 08:53:42.684  6090  6090 I bt_bluedroid: get_profile_interface gatt
,07-27 08:53:42.684  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
07-27 08:53:42.684  6090  6090 D BtGatt.AdvertiseManager: advertise manager created
07-27 08:53:42.684  6090  6090 D BtGatt.AdvertiseManager: start
,07-27 08:53:42.684  6090  6090 D BtGatt.ScanManager: start
,07-27 08:53:42.684  6090  6090 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,07-27 08:53:42.704  6118  6118 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm
,07-27 08:53:42.704  6090  6090 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,07-27 08:53:42.714   749   762 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:42.714  6090  6090 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
07-27 08:53:42.714  6118  6118 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-27 08:53:42.714  6118  6118 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:53:42.714  6118  6118 D SecurityLogAgent: StateMachine : Current State = 1
07-27 08:53:42.714  6090  6090 E BtGatt.GattService: notifyProfileServiceStateChanged
,07-27 08:53:42.714  6090  6090 E BluetoothAdapterService: handleMessage() - Message: 1
,07-27 08:53:42.714  6090  6090 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,07-27 08:53:42.714  6118  6118 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 08:53:42.714  6090  6090 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:42.724  6090  6090 V BluetoothAdapterState: isTurningOn()=false
07-27 08:53:42.724  6090  6090 V BluetoothAdapterState: isBleTurningOn()=true
07-27 08:53:42.724  6090  6090 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:53:42.724  6090  6116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-27 08:53:42.724  6148  6148 E Zygote  : v2
07-27 08:53:42.724  6148  6148 I libpersona: KNOX_SDCARD checking this for 10171
07-27 08:53:42.724  6148  6148 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:42.724  6148  6148 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:42.724  6148  6148 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:42.734  6148  6148 E Zygote  : accessInfo : 0
,07-27 08:53:42.734  6148  6148 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=tv.peel.smartremote 
,07-27 08:53:42.734   749  1712 I ActivityManager: Start proc 6148:tv.peel.smartremote/u0a171 for broadcast-5 tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver
,07-27 08:53:42.734   749  1323 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 08:53:42.734  6090  6116 I bt_bluedroid: enable
07-27 08:53:42.734  6090  6117 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-27 08:53:42.734  6090  6117 I bt_hci  : start_up
,07-27 08:53:42.734   749  1712 I ActivityManager: Killing 4941:com.sec.android.app.music:service/u0a44 (adj 15): DHA:empty #37
,07-27 08:53:42.744   749  1323 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 08:53:42.754  6090  6117 I bt_vendor: alloc value 0xb2b24979
,07-27 08:53:42.754  6090  6117 I bt_vendor: init
07-27 08:53:42.754  6090  6117 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 08:53:42.754  6090  6117 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-27 08:53:42.754  6090  6117 D bt_vendor: op for 5
07-27 08:53:42.754  6090  6117 D bt_vendor: op for 0
,07-27 08:53:42.754  6090  6117 I bt_upio : upio_set_bluetooth_power(on: 0)
,07-27 08:53:42.754  6090  6117 D bt_upio : is_emulator_context : 0
07-27 08:53:42.754  6090  6117 D bt_upio : is_rfkill_disabled ? [0]
07-27 08:53:42.754  6090  6117 D bt_upio : is_rfkill_disabled ? [0]
,07-27 08:53:42.754   749  1415 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,07-27 08:53:42.754  6090  6117 D bt_vendor: op for 0
,07-27 08:53:42.754  6090  6117 I bt_upio : upio_set_bluetooth_power(on: 1)
07-27 08:53:42.754  6090  6117 D bt_upio : is_emulator_context : 0
07-27 08:53:42.754  6090  6117 D bt_upio : is_rfkill_disabled ? [0]
,07-27 08:53:42.764  6090  6117 D bt_hci  : start_up starting async portion
,07-27 08:53:42.764  6090  6158 I bt_hci  : event_finish_startup
07-27 08:53:42.764  6090  6158 I bt_hci_h4: hal_open
07-27 08:53:42.764  6090  6158 D bt_vendor: op for 3
07-27 08:53:42.764  6090  6158 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 08:53:42.764  6090  6158 I bt_userial_vendor: userial_vendor_open():UART is setup
,07-27 08:53:42.764  6090  6158 I bt_userial_vendor: device fd = 60 open
07-27 08:53:42.764  6090  6158 D bt_vendor: op for 1
,07-27 08:53:42.764  6090  6158 E bt_hwcfg: Start CFG HW, HCI reset
,07-27 08:53:42.774  6148  6148 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:42.774  6148  6148 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:42.784   749  1567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{184217 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1bb3a0 6148:tv.peel.smartremote/u0a171}
,07-27 08:53:42.784  6148  6148 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,07-27 08:53:42.824  6148  6148 W System  : ClassLoader referenced unknown path: /system/app/SmartRemote_KL/lib/arm
,07-27 08:53:42.844  6090  6158 E bt_hwcfg: Read Local Name after HCI reset
,07-27 08:53:42.844   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{c466b59: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:42.864   388   388 I SecureStorage: [INFO]: SPID(0x00000007)Secure Storage Daemon finished processing with result: 0
,07-27 08:53:42.864  6111  6111 I SecureStorage: [INFO]: SPID(0x00000007)Processing data has been completed
,07-27 08:53:42.864  6148  6148 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 08:53:42.864  6148  6148 I MultiDex: install
07-27 08:53:42.864  6148  6148 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:53:42.864  6090  6158 D bt_hwcfg: Chipset BCM4350C0
,07-27 08:53:42.864  6090  6158 D bt_hwcfg: Target name = [BCM4350C0]
,07-27 08:53:42.874  6090  6158 I bt_hwcfg: module_type[semco3rd].
07-27 08:53:42.874  6090  6158 I bt_hwcfg: module_type[semco3rd] is invalid.
07-27 08:53:42.874  6090  6158 E bt_hwcfg: patchram path ORG . BCM4350C0
,07-27 08:53:42.874  6090  6158 E bt_hwcfg: patchram path ORG .. BCM4350C0
07-27 08:53:42.874  6090  6158 E bt_hwcfg: patchram path ORG libpn547_fw.so BCM4350C0
07-27 08:53:42.874  6090  6158 E bt_hwcfg: patchram path ORG bcm4350_V0353.0733_wisol.hcd BCM4350C0
07-27 08:53:42.874  6090  6158 E bt_hwcfg: patchram path ORG bcm4350_V0353.0727.hcd BCM4350C0
07-27 08:53:42.874  6090  6158 E bt_hwcfg: fw ver (org)0.0
,07-27 08:53:42.884  6090  6158 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
,07-27 08:53:42.884  6090  6158 E bt_hwcfg: Remove module rev, try again BCM4350
07-27 08:53:42.884  6090  6158 D bt_hwcfg: Target name = [BCM4350]
07-27 08:53:42.884  6090  6158 I bt_hwcfg: module_type[semco3rd].
07-27 08:53:42.884  6090  6158 I bt_hwcfg: module_type[semco3rd] is invalid.
,07-27 08:53:42.884  6090  6158 E bt_hwcfg: patchram path ORG . BCM4350
07-27 08:53:42.884  6090  6158 E bt_hwcfg: patchram path ORG .. BCM4350
07-27 08:53:42.884  6090  6158 E bt_hwcfg: patchram path ORG libpn547_fw.so BCM4350
07-27 08:53:42.884  6090  6158 E bt_hwcfg: patchram path ORG bcm4350_V0353.0733_wisol.hcd BCM4350
07-27 08:53:42.884  6090  6158 I bt_hwcfg: patch(org) : bcm4350_V0353.0733_wisol.hcd
,07-27 08:53:42.884  6090  6158 E bt_hwcfg: Module type exists. Skip
07-27 08:53:42.884  6090  6158 E bt_hwcfg: patchram path ORG bcm4350_V0353.0727.hcd BCM4350
07-27 08:53:42.884  6090  6158 I bt_hwcfg: patch(org) : bcm4350_V0353.0727.hcd
07-27 08:53:42.884  6090  6158 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4350_V0353.0727.hcd
07-27 08:53:42.884  6090  6158 E bt_hwcfg: ORG patchram base 0353
,07-27 08:53:42.884  6090  6158 E bt_hwcfg: ORG patchram minor 0727
07-27 08:53:42.884  6090  6158 E bt_hwcfg: fw ver (org)353.727
07-27 08:53:42.884  6090  6158 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4350_V0353.0727.hcd
,07-27 08:53:42.884  6090  6158 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-27 08:53:42.884  6111  6111 I wpa_supplicant: Ctrl_iface: loading system cred
07-27 08:53:42.884   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{e87031e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:42.884  6111  6111 I SecureStorage: [INFO]: SPID(0x00000007)Checking if this device supports Secure Storage
,07-27 08:53:42.894   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{9a3a7ff: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:42.894  6090  6158 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-27 08:53:42.904  6111  6111 I SecureStorage: [INFO]: SPID(0x00000007)This device supports Secure Storage
,07-27 08:53:42.904   388   388 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 1010, gid 1010, pid 6111
07-27 08:53:42.904   388   388 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x0000010C
07-27 08:53:42.904  6111  6111 I SecureStorage: [INFO]: SPID(0x00000007)SS Daemon is running
07-27 08:53:42.904  6111  6111 I wpa_supplicant: ssSupport state is = 1
,07-27 08:53:42.914  6111  6111 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:42.914  6111  6111 E wpa_supplicant: SIM READ ERROR
07-27 08:53:42.914  6111  6111 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:42.914  6111  6111 E wpa_supplicant: SIM READ ERROR
07-27 08:53:42.914  6111  6111 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 08:53:42.914  6111  6111 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:42.914  6111  6111 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:42.914  6111  6111 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:53:42.994   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{61869cc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:42.994   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{8696415: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.004  6148  6148 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-27 08:53:43.024  6148  6148 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,07-27 08:53:43.034  6148  6148 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 08:53:43.034  6148  6148 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 726-729)
07-27 08:53:43.034  6148  6148 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 08:53:43.044   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{e9c332a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.044   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{c94c51b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.044   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{d4856b8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.054   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{c892c91: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.054   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{b2257f6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.054   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{2b097f7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.054   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{20300cd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.064  6148  6148 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {64940e2}
07-27 08:53:43.064  6148  6148 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 08:53:43.064  6148  6148 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 08:53:43.064   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{113fd82: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.064   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{14cbc93: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.064   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{bd344d0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.074   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{cbdcc9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.074   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{886fce: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.074   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{37c8eef: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.074   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{b6fddfc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.074  6148  6148 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-27 08:53:43.074   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{12c7c85: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.084   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{1bfbada: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.084   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{82d2b0b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.084  6148  6148 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,07-27 08:53:43.084   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{3dadde8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.084   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{d3d5c01: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.094   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{eeeaaa6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.094   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{6016ce7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.094   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{f73f094: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.094   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{e22b73d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.104   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{ecacb32: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.104   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{edf083: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.104   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{ce98200: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.104   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{1088a39: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.104   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{bd6687e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.114   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{d9511df: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.114   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{564be2c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.114   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{fde90f5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.114   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{46c8e8a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.114   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{e62ecfb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.114   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{9759118: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.124   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{9d44771: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.124   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{f8d0956: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.124   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{6695dd7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.124   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{bea6c4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.124   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{794e9ad: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.124   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{26864e2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.134   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{dfc0073: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.134   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{8616b30: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.134   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{74373a9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.134   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{2abed2e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.134   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{50c30cf: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.144   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{c2a0a5c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.144   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{c36a165: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.144   749  1568 E Watchdog: !@Sync 2 [07-27 08:53:43.157]
,07-27 08:53:43.144   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{18dae3a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.144   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{f450aeb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.144   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{67b7048: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.154   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{e74eee1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.154   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{b987406: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.154   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{5e76ac7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.154   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{2fb48f4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.164   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{5f0981d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.164   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{937ca92: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.164   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{b65ec63: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.174   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{ffe0060: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.174   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{d839919: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.174   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{c03fdde: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.184   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{cc0ebbf: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.184   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{ab2c28c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.184   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{9abadd5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.184   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{4ce19ea: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.194   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{ca284db: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.194   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{20f7b78: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.194   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{f065251: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.194   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{e6beab6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.194   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{43a93b7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.194   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{c7cd724: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.204   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{48cc28d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.204   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{943fc42: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.204   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{5dab453: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.204   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{c424190: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.204   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{d8ffa89: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.204   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{3999a8e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.214   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{d5242af: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.214   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{eb1e6bc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.214   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{774b645: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.214   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{a98d19a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.214   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{a0a5acb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.224   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{214b2a8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.224   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{72f71c1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.224   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{226d66: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.224   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{ee1d8a7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.224   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{e565154: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.224   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{28068fd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.234   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{157f9f2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.234   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{3c95843: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.234   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{c712ec0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.234   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{ef97f9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.234   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{9e7c33e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.234   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{51f359f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.244   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{89a76ec: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.244   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{88bab5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.244   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{18d54a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.244   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{ccb8cbb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.244   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{b2e15d8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.244   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{a574d31: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.254   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{596fc16: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.254   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{11c3997: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.254   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{45ab784: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.254   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{2a28b6d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.254   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{8fec3a2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.264   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{560d833: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.264   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{68dc7f0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.264   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e97169: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:43.264   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{42977ee: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.264   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{846c48f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.264   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{b9f731c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.274   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{b9ebb25: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.274   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{33924fa: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.274   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{bf51aab: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.274   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{bea508: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.274   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{3a4e4a1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.284   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{6496c6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.284   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{3e8b687: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.284   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{51d09b4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.284   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{b8a29dd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:43.284   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{835952: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.284   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{4903423: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.294   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{75b0d20: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.294   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{68486d9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.294   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{c59b89e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.294   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{a7ef7f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.294   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{db3db4c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.294   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{b2db795: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.304   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{2a4c0aa: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.304   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{56049b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:43.304   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{4e96038: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:43.304   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{5ff3811: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.304   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{ee63d76: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.304   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{e064f77: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.324   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{1f047e4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.324   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{78e444d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.324   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{f0bb02: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.324   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{5066c13: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.334   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{25bfe50: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.334   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{a87d849: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.334   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{133854e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.334   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{de1b66f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.334   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{78aaf7c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.344   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{d6cb005: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.344   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{dc6a85a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.344   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{47d4a8b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.344   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{8914768: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.344   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{c0d4781: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.354   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{c36f026: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.354   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{3f40467: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.354   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{6e77214: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.354   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{4c5dabd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.364   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{c11e8b2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.364   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{4328003: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.364   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{1d39b80: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.364   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{57a65b9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.364   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{631ddfe: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.374   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{553195f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.374   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{496efac: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.374   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{c52a475: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.374   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{4c9dc0a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.374   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{4b9ec7b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.384   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{b595a98: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.384   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{83612f1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.384   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{31aed6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.384   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{7f0d557: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.384   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{ad58844: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.394   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{507ed2d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.394   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{c71e262: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.394   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{9436ff3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.394   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{6c4e4b0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.394   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{fa32f29: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.394   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{38fc2ae: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.404   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{21b184f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.404   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{30b9bdc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.404   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{d9694e5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.404   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{8995bba: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.414   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{f1aea6b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.414   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{ba499c8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.414   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{4a09a61: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.414   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{f717986: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.414   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{9fbc247: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.424   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{f4d8a74: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.424   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{deb7b9d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.424   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{55ba812: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.424   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{5283be3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.424   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{8f2d9e0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.434   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{1093499: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.434   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{648335e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.434   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{518b33f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.434   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{3dbb40c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.434   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{2af8155: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.444   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{ae0276a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.444   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{36f445b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.444   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{69604f8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.444   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{333ddd1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.444   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:53:43.454   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{a278a4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.484   305  1126 D Netd    : Iface wlan0 link up
07-27 08:53:43.484   305  1126 D Netd    : Iface wlan0 link up
,07-27 08:53:43.484   749   832 D Tethering: interfaceLinkStateChanged wlan0, true
,07-27 08:53:43.484   749   832 D Tethering: interfaceStatusChanged wlan0, true
07-27 08:53:43.484  6148  6173 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,07-27 08:53:43.484   749   873 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
,07-27 08:53:43.484   749   873 D Tethering: NAP Supported and not Wifi Model
,07-27 08:53:43.484   749   832 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:53:43.484   749   832 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:53:43.494   749   873 E Tethering: No numeric data
,07-27 08:53:43.494   749   873 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 08:53:43.494   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{345fa4b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.494  1379  1379 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-27 08:53:43.494  1379  1379 D HotspotTile: updateTetherState():false, false
,07-27 08:53:43.504   749  1322 D NtpTrustedTime: forceRefresh: no connectivity
,07-27 08:53:43.504   749  1322 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:53:43.504   749  1322 V NetworkStats: performPollLocked() took 3ms
,07-27 08:53:43.514   749  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 08:53:43.514   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{1ec32e6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.514   749  1625 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-27 08:53:43.514   749  1625 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-27 08:53:43.514   749  1625 D BatteryService: stay LED for charging
,07-27 08:53:43.514   749  1323 D NtpTrustedTime: forceRefresh: no connectivity
,07-27 08:53:43.514   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{cf7f027: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.514   749   749 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e752d4 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{83a0580 749:system/1000}
,07-27 08:53:43.514  6148  6148 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-27 08:53:43.514  6148  6148 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-27 08:53:43.514  6148  6148 I Adreno-EGL: Build Date: 01/28/16 Thu
07-27 08:53:43.514  6148  6148 I Adreno-EGL: Local Branch: ss
07-27 08:53:43.514  6148  6148 I Adreno-EGL: Remote Branch: 
07-27 08:53:43.514  6148  6148 I Adreno-EGL: Local Patches: 
07-27 08:53:43.514  6148  6148 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:53:43.524   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 08:53:43.524   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{2b30c7d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.524  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:53:43.524  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:53:43.524  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:53:43.534  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:53:43.534  6148  6148 D libEGL  : eglInitialize EGLDisplay = 0xbec9d23c
,07-27 08:53:43.554   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{774b8be: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.554  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:53:43.554  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:53:43.554   749   749 I MotionRecognitionService: Plugged
07-27 08:53:43.554   749   749 D MotionRecognitionService:   cableConnection= 1
07-27 08:53:43.554   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:53:43.554   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:53:43.554   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{df0bd1f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.554   749   749 I BackgroundCompactionService: onStart. jobID=801
,07-27 08:53:43.554   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{e1a286c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.564  6111  6111 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-27 08:53:43.564   749   749 I BackgroundCompactionService: onStart done. jobID=801
07-27 08:53:43.564  6111  6111 I SecureStorage: [INFO]: SPID(0x00000007)Checking if this device supports Secure Storage
,07-27 08:53:43.564   749  6190 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,07-27 08:53:43.564   749  6190 I BackgroundCompactionService: compact_memory command done
,07-27 08:53:43.584   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{53fa2ca: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.584  6111  6111 I SecureStorage: [INFO]: SPID(0x00000007)This device supports Secure Storage
,07-27 08:53:43.584   388   388 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 1010, gid 1010, pid 6111
07-27 08:53:43.584   388   388 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x0000010C
07-27 08:53:43.584  6111  6111 I SecureStorage: [INFO]: SPID(0x00000007)SS Daemon is running
07-27 08:53:43.584  6111  6111 I wpa_supplicant: ssSupport state is = 1
,07-27 08:53:43.594  6111  6111 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:53:43.594   305  1126 D Netd    : Iface p2p0 link up
,07-27 08:53:43.594   305  1126 D Netd    : Iface p2p0 link up
,07-27 08:53:43.594   749   832 D Tethering: interfaceLinkStateChanged p2p0, true
,07-27 08:53:43.594   749   832 D Tethering: interfaceStatusChanged p2p0, true
,07-27 08:53:43.594   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{1ee0c3b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.594   749   832 D Tethering: interfaceLinkStateChanged p2p0, true
,07-27 08:53:43.594   749   832 D Tethering: interfaceStatusChanged p2p0, true
,07-27 08:53:43.594   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{ab75f58: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.604   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{53098b1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.604   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e1d2196: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.604   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{2a73117: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.604   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{ef1904: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.614   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{c850eed: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.614   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{781c122: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.614   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{d63c7b3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.614   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{1c6c170: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.624  6090  6158 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 08:53:43.624  6090  6158 I bt_hwcfg: FW Download delta = 778659
07-27 08:53:43.624  6090  6158 D bt_hwcfg: Settlement delay -- 100 ms
,07-27 08:53:43.624  6090  6158 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 08:53:43.624   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{d30ace9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.624   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{79ecd6e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.624   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{2492c0f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.634   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{72e849c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.634   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{7de2ea5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.634   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{46e527a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.634   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{4767a2b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.644   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{7ed4e88: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.644   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{3281021: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.644   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{77f1c46: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.644   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{fe08e07: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.654   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{e4ccb34: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.654   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{ad48d5d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.654   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{280b6d2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.654   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{ee03a3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.664   749  1747 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
,07-27 08:53:43.664   749  1747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-27 08:53:43.674   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{1ae441b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.674   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{7d569b8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.684   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{8644391: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.684   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{26d22f6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.694   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{96306f7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.694   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{5536964: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.704   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{5f887cd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.714  6111  6111 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-27 08:53:43.714   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{9c07882: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.734   749  1325 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
07-27 08:53:43.734   749  1325 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
07-27 08:53:43.734  6090  6158 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-27 08:53:43.734   749  1325 D WifiNative-wlan0: callSECApiBoolean - ID [301]
07-27 08:53:43.744  6111  6111 I wpa_supplicant: HOTSPOT20_ENABLE called ON
,07-27 08:53:43.744  6111  6111 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:43.744  6111  6111 E wpa_supplicant: SIM READ ERROR
07-27 08:53:43.744  6111  6111 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 08:53:43.754   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{2371b93: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.754  6111  6111 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-27 08:53:43.754  6111  6111 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,07-27 08:53:43.754   749  1325 D WifiNative-wlan0: callSECApiInt - ID [210]
,07-27 08:53:43.764   749   749 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:43.764   749   749 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:43.764   749  1327 D HS20StateMachine: WIFI_STATE_ENABLED
,07-27 08:53:43.764   749  1327 D HS20StateMachine: reloadCredentialsToSupplicant
,07-27 08:53:43.764   749  1327 D HotspotDBHandler: getCredentialIds
,07-27 08:53:43.764  1379  1379 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:53:43.764  1379  1379 D STATUSBAR-WifiTile: Wifi onReceive(3)
07-27 08:53:43.764  1379  1379 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=3
,07-27 08:53:43.764  1379  1379 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:43.764  1379  1379 D HotspotTile: onReceive : 3, 0
07-27 08:53:43.764   749  1330 I WifiHs20Service: Message received 5011
,07-27 08:53:43.764  5802  5802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:43.774  5802  5802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:53:43.774  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:43.774  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:43.774  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:53:43.774  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:43.774  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:43.774  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:43.774  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:53:43.774  5802  5802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:43.774  5802  5802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:53:43.774   749  1333 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-27 08:53:43.774  1682  1697 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-27 08:53:43.774  1682  1697 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-27 08:53:43.774   749  1333 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-27 08:53:43.774   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{28fb7d0 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3415604 5802:com.test.thalitest/u0a4}
,07-27 08:53:43.774   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{c12d3c9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.774   749  1746 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.774   749  1746 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.774   749  1746 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.774   749  1746 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.774   749  1746 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:43.774   749  1746 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.774   749  1746 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:43.784   749  1746 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.784   749  1746 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.784   749  1746 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:43.784   749  1746 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.784   749  1746 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.784   749  1746 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:43.784   749  1746 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:43.784  6111  6111 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-27 08:53:43.784   749  1325 D WifiConfigStore: Loading config and enabling all networks 
,07-27 08:53:43.794  6209  6209 E Zygote  : v2
07-27 08:53:43.794  6209  6209 I libpersona: KNOX_SDCARD checking this for 10210
07-27 08:53:43.794  6209  6209 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:43.794   749  1327 I ActivityManager: Start proc 6209:com.samsung.hs20provider/u0a210 for content provider com.samsung.hs20provider/.Hs20Provider
,07-27 08:53:43.794  6209  6209 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 08:53:43.794  6209  6209 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:43.794  6209  6209 E Zygote  : accessInfo : 0
,07-27 08:53:43.794  6209  6209 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,07-27 08:53:43.794   749  1325 I WifiConfigStore: "NG700" is a verified password AP: true
07-27 08:53:43.794   749  1325 E WifiConfigStore: Not a HS20
,07-27 08:53:43.804   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{28fb7d0 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4abb2b 6118:com.samsung.android.securitylogagent/1000}
,07-27 08:53:43.804   749  1325 D WifiConfigStore: loaded 0 passpoint configs
07-27 08:53:43.804   749  1325 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 08:53:43.804   749  1325 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-27 08:53:43.804   749  1415 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:43.804   749  1325 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-27 08:53:43.804   749  1325 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-27 08:53:43.804  6118  6118 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 08:53:43.804  6118  6118 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:53:43.804  6118  6118 D SecurityLogAgent: StateMachine : Current State = 1
07-27 08:53:43.804  6118  6118 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 08:53:43.804  1379  3017 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 08:53:43.814  1379  1379 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-27 08:53:43.814   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{28fb7d0 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1bb3a0 6148:tv.peel.smartremote/u0a171}
,07-27 08:53:43.814   749   826 I ActivityManager: Waited long enough for: ServiceRecord{553b116 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,07-27 08:53:43.824   749   749 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-27 08:53:43.824   749  1325 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
07-27 08:53:43.824   749   749 D WifiHs20Service: reason: 2
,07-27 08:53:43.824   749  1330 I WifiHs20Service: Message received 5014
07-27 08:53:43.824   749  1330 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-27 08:53:43.824   749  1330 E WifiHs20Service: The changed config is NULL
07-27 08:53:43.824   749  1325 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-27 08:53:43.824  6209  6209 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:43.824  6209  6209 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:43.824   749  1325 D WifiNative-wlan0: callSECApiBoolean - ID [13]
07-27 08:53:43.824  6111  6111 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-27 08:53:43.824  6111  6111 I wpa_supplicant: resume autoscan
07-27 08:53:43.824  6111  6111 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-27 08:53:43.824  6111  6111 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-27 08:53:43.824  6111  6111 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-27 08:53:43.824  6111  6111 I wpa_supplicant: reset timer : RESET_TIMER 0
07-27 08:53:43.824  6111  6111 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 08:53:43.824  6111  6111 I wpa_supplicant: First Scan Start
,07-27 08:53:43.824  6111  6111 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 08:53:43.834  6090  6158 I bt_hwcfg: vendor lib fwcfg completed
07-27 08:53:43.834  6090  6158 I bt_vendor: firmware callback
07-27 08:53:43.834  6090  6158 I bt_hci  : firmware_config_callback
,07-27 08:53:43.834   749  1325 D WifiNative-wlan0: Setting external_sim to 1
,07-27 08:53:43.834   749  1325 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
07-27 08:53:43.834   749  1325 D WifiStateMachine: Setting OUI to DA-A1-19
,07-27 08:53:43.834  6090  6222 I bt_btu_task: Bluetooth chip preload is complete
,07-27 08:53:43.844  6111  6111 I wpa_supplicant: bt_status is set be DISCONNECTED
,07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_HCI
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 08:53:43.844  6090  6222 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-27 08:53:43.844   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{37b4139: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.844   749  1325 E WifiNative-wlan0: do suspend true
,07-27 08:53:43.844  6209  6209 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package null
,07-27 08:53:43.854   749  1324 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-27 08:53:43.854   749  1325 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started,
07-27 08:53:43.854   305  1133 D CommandListener: Setting iface cfg
07-27 08:53:43.854   305  1133 D CommandListener: Trying to bring up p2p0
,07-27 08:53:43.854   749   749 D RttService: SCAN_AVAILABLE : 3
,07-27 08:53:43.854   749  1351 E WifiScanningService: could not start HAL
,07-27 08:53:43.864   749  1324 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 08:53:43.864   749  1352 D RttService: DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 08:53:43.864  1379  1379 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02061d/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f02017c/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:53:43.864   749  1324 D SecContentProvider: insert(), uri = 2
,07-27 08:53:43.864   749  1325 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-27 08:53:43.864  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:43.864   749  1325 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
07-27 08:53:43.864   749  1325 D WifiStateMachine: setFccChannelNative: channel = 0
07-27 08:53:43.864   749  1325 D WifiNative-wlan0: callSECApiInt - ID [230]
,07-27 08:53:43.864  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:43.864  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:43.864  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:43.864  6209  6209 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm
,07-27 08:53:43.874   749  1324 D WifiP2pService: P2pEnablingState
,07-27 08:53:43.874   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{eb820df: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.874   749  1324 D WifiP2pService: P2pEnablingState{ what=147457 }
,07-27 08:53:43.874   749  1324 D WifiP2pService: P2p socket connection successful
,07-27 08:53:43.874   749  1324 D WifiP2pService: P2pEnabledState
,07-27 08:53:43.874   749  1324 D SecContentProvider: insert(), uri = 2
,07-27 08:53:43.874   749   749 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-27 08:53:43.884   749   874 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,07-27 08:53:43.884   749  1324 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,07-27 08:53:43.884   749   874 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-27 08:53:43.884   749   874 D WifiDisplayController: disconnect
,07-27 08:53:43.884   749   874 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 08:53:43.884   749  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:53:43.884   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{9e4212c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.884   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:43.884  1379  1379 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-27 08:53:43.894   749  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:53:43.894   749  1324 D WifiP2pService: create mNetworkAgent
,07-27 08:53:43.894   749  1567 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 08:53:43.894  1379  1379 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 08:53:43.894   749  1324 D P2pNetworkAgent: NetworkAgent: Registering NetworkAgent
,07-27 08:53:43.894   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{43a298a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.904  6209  6219 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:53:43.904  6209  6219 D HotspotProvider: CREDENTIAL
07-27 08:53:43.904  6209  6219 D HotspotProvider: No prepend tags
,07-27 08:53:43.904   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{581df73: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.904   749  1324 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:53:43.904   749  1332 D ConnectivityService: Got NetworkAgent Messenger
,07-27 08:53:43.904   749  1332 E ConnectivityService: updateNetworkInfo()
,07-27 08:53:43.904   749  1332 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:43.904   749  1332 D ConnectivityService: NetworkAgent connected
,07-27 08:53:43.914   749  1332 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 13
,07-27 08:53:43.914   749   874 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:43.914   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{351eaa9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.914   749  1327 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
,07-27 08:53:43.914   749  1327 D HS20StateMachine: enter : DiscoveringState
,07-27 08:53:43.914  6111  6111 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,07-27 08:53:43.914  6111  6111 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,07-27 08:53:43.914  6148  6148 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-27 08:53:43.924   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{716982e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.924  1682  1698 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-27 08:53:43.924   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{890ffcf: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.924   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{cc82d5c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.934   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{978093a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.934   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{7c7c9eb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.944   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{658c348: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.944   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{fb45e1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.944   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{74d7f06: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.944   749  1324 E WifiP2pService: Failed to set my phone number info into probe response
,07-27 08:53:43.944  6148  6148 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:53:43.944  6148  6148 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-27 08:53:43.944  6148  6148 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-27 08:53:43.954   749  1324 D WifiNative-p2p0: p2pGetDeviceAddress
,07-27 08:53:43.954   749  1324 D WifiNative-p2p0: p2pGetDeviceAddress returning ee:1f:72:18:8b:78
,07-27 08:53:43.954  6148  6148 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-27 08:53:43.954   749  1324 D WifiP2pService: DeviceAddress: ee:8b:78
,07-27 08:53:43.954   749   874 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Thali Test (Galaxy S5)
07-27 08:53:43.954   749   874 D WifiDisplayController:  deviceAddress: ee:1f:72:18:8b:78
07-27 08:53:43.954   749   874 D WifiDisplayController:  primary type: 10-0050F204-5
07-27 08:53:43.954   749   874 D WifiDisplayController:  secondary type: null
07-27 08:53:43.954   749   874 D WifiDisplayController:  wps: 0
07-27 08:53:43.954   749   874 D WifiDisplayController:  grpcapab: 0
07-27 08:53:43.954   749   874 D WifiDisplayController:  devcapab: 0
07-27 08:53:43.954   749   874 D WifiDisplayController:  status: 3
07-27 08:53:43.954   749   874 D WifiDisplayController:  wfdInfo: null
07-27 08:53:43.954   749   874 D WifiDisplayController:  groupownerAddress: null
07-27 08:53:43.954   749   874 D WifiDisplayController:  GOdeviceName: null
07-27 08:53:43.954   749   874 D WifiDisplayController:  interfaceAddress: 
07-27 08:53:43.954   749   874 D WifiDisplayController:  SConnectInfo : null
07-27 08:53:43.954   749   874 D WifiDisplayController:  contactInfoHash : null
07-27 08:53:43.954   749   874 D WifiDisplayController:  ssDevInfo : 0
07-27 08:53:43.954   749   874 D WifiDisplayController:  iconIdx : 0
,07-27 08:53:43.954   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{d5719c7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.954   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{edacbf4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.964   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{55f1d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.964   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{2b28592: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.964   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{ba18b63: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.974   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{dd2b360: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.974   749  1324 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-27 08:53:43.974   749  1324 D WifiP2pService: InactiveState
07-27 08:53:43.974   749  1324 D P2pNetworkAgent: NetworkAgent: NetworkAgent fully connected
,07-27 08:53:43.974   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{19dd019: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:43.974   749  1332 E ConnectivityService: updateNetworkInfo()
,07-27 08:53:43.974   749  1324 D WifiP2pService: InactiveState{ what=143376 }
,07-27 08:53:43.974   749  1332 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
07-27 08:53:43.974   749  1324 D WifiP2pService: P2pEnabledState{ what=143376 }
07-27 08:53:43.974   749  1324 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,07-27 08:53:43.974  6148  6148 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-27 08:53:43.984  6148  6148 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:53:43.984  6148  6148 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-27 08:53:43.984  6148  6148 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-27 08:53:43.984  6148  6148 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-27 08:53:43.994   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{1ef68de: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.994   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{e977abf: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.994   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{c9fa58c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.994   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{ab254d5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:43.994   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{58534ea: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.004   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{6d303db: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.004   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{9678e78: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.004   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{7506951: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.004   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{2f9b5b6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.014   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{a7402b7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.014  6148  6148 I ClientConfig: Set OkHttp cache (max size: 52MB) to /data/user/0/tv.peel.smartremote/cache/peel-cache
,07-27 08:53:44.014   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{cc31a24: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.014   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{ce1498d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.014   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{637742: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.024   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{7bc1353: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.024   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{e29b490: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.024   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{425f189: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.024   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{cb5c58e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.024   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{56a91af: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.034   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{31d89bc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.034   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{6f31d45: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.034   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{ccac9a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.044   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{cd899cb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.044   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{51785a8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.044   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{dad48c1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.044   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{538f866: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.044   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{9d507a7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.054   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{a335454: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.054   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{884affd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.054   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{8cc34f2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.054   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{c407743: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.054   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{c9b61c0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.064   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{714ef9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.064   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{3e4ae3e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.064  6090  6222 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,07-27 08:53:44.064  6090  6222 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb2a78269
07-27 08:53:44.064  6090  6222 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb2a78269 
07-27 08:53:44.064  6090  6222 E bt_btm  : btm_ble_set_search_if search_if=4
,07-27 08:53:44.074  6090  6128 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 33024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 1024 mIsExtendedScanSupported = false mIsDebugLogSupported = false mAobleSupported = 0
,07-27 08:53:44.074   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{769449f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.074   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{cb4d9ec: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.084  6090  6128 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,07-27 08:53:44.084  6090  6128 D bt_hci  : do_postload posting postload work item
07-27 08:53:44.084  6090  6158 I bt_hci  : event_postload
07-27 08:53:44.084  6090  6158 D bt_vendor: op for 2
07-27 08:53:44.084  6090  6158 D bt_hwcfg: hw_sco_config
07-27 08:53:44.084  6090  6158 I bt_vendor: sco_config_cb
07-27 08:53:44.084  6090  6158 I bt_hci  : sco_config_callback postload finished.
07-27 08:53:44.084  6090  6158 D bt_vendor: op for 6
07-27 08:53:44.084  6090  6158 D bt_upio : upio_set : pio 2 action 2, polarity 0
07-27 08:53:44.084  6090  6128 E bt_btif_sock: btif_sock_init: !vhci_init
07-27 08:53:44.084  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.084  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 08:53:44.084  6090  6158 D bt_upio : upio_start_stop_timer : timer_settime success
07-27 08:53:44.084  6090  6158 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
07-27 08:53:44.084  6090  6128 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
,07-27 08:53:44.084  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.084  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.084  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.084  6090  6128 D bt_bte_conf: Device ID record 1 : primary
07-27 08:53:44.084  6090  6128 D bt_bte_conf:   vendorId            = 0075
07-27 08:53:44.084  6090  6128 D bt_bte_conf:   vendorIdSource      = 0001
07-27 08:53:44.084  6090  6128 D bt_bte_conf:   product             = 0100
07-27 08:53:44.084  6090  6128 D bt_bte_conf:   version             = 0200
07-27 08:53:44.084  6090  6128 D bt_bte_conf:   clientExecutableURL = 
07-27 08:53:44.084  6090  6128 D bt_bte_conf:   serviceDescription  = 
07-27 08:53:44.084  6090  6128 D bt_bte_conf:   documentationURL    = 
07-27 08:53:44.084  6090  6128 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-27 08:53:44.084  6090  6117 D bt_stack_manager: event_start_up_stack finished
07-27 08:53:44.084  6090  6128 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
07-27 08:53:44.084  6090  6128 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 7
07-27 08:53:44.084  6090  6128 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24844
07-27 08:53:44.084  6090  6128 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4354 37.4MHz SEMCO-B80 K-LTE-0353
07-27 08:53:44.084  6090  6128 D BluetoothDataManager: firmwareVersion from Property : bcm4350_V0353.0727.hcd
07-27 08:53:44.084  6090  6128 E BluetoothAdapterState: stateChangeCallback : 1
,07-27 08:53:44.084  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.084  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.084  6090  6158 D bt_upio : BT_WAKE is asserted already
07-27 08:53:44.084  6090  6116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,07-27 08:53:44.084   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{beee1b5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.084  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.084  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.084  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.084  6090  6116 D BluetoothAdapterProperties: Setting state to 15
,07-27 08:53:44.084  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.084  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.084  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.084  6090  6116 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-27 08:53:44.094  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.094  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.094  6090  6158 D bt_upio : BT_WAKE is asserted already
07-27 08:53:44.094  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.094  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.094  6090  6158 D bt_upio : BT_WAKE is asserted already
07-27 08:53:44.094  6090  6158 I bt_vendor: low_power_mode_cb
07-27 08:53:44.094  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.094  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.094  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.104   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{479704a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.104  6090  6116 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-27 08:53:44.104  6090  6116 D BluetoothAdapterService: updateAdapterState state is 15
,07-27 08:53:44.104  6148  6148 I Fabric  : Initializing Crashlytics 2.3.2.56
,07-27 08:53:44.104  6090  6116 D BluetoothAdapterService: Autoconnection is available 
07-27 08:53:44.104  6090  6116 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-27 08:53:44.104  6090  6116 I BluetoothAdapterState: Entering BleOnState
,07-27 08:53:44.104   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{a0ba8d8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.104   749   873 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 08:53:44.104   749   873 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-27 08:53:44.104   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{378e431: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.104  6090  6116 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,07-27 08:53:44.104  6090  6116 D BluetoothAdapterProperties: Setting state to 11
,07-27 08:53:44.114  6090  6116 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-27 08:53:44.114  6090  6116 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-27 08:53:44.114  6090  6116 D BluetoothAdapterService: updateAdapterState state is 11
,07-27 08:53:44.114   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{ee64716: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.114  6090  6116 D BluetoothAdapterService: Autoconnection is available 
,07-27 08:53:44.114  6090  6116 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-27 08:53:44.114  6090  6116 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:53:44.114  6090  6116 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 08:53:44.114  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 08:53:44.114  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.114  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.114  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.114  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.114  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.114  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.114   749   873 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
,07-27 08:53:44.114  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.114  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.114  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.114  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.114  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.114  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.114  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.114  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.114  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.124   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{efe7a84: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.124   749   749 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:44.124   749   749 I InputMethodManagerService: [BT Setting State] State =11
,07-27 08:53:44.124  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 08:53:44.124  1773  1773 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:53:44.124   749   749 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,07-27 08:53:44.134   749   749 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:53:44.134   749   749 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-27 08:53:44.134  6090  6090 D HeadsetService: Received start request. Starting profile...
07-27 08:53:44.134  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
,07-27 08:53:44.134  6090  6090 D HeadsetProvider: make
07-27 08:53:44.134  6090  6090 D HeadsetProvider: HeadsetProvider
,07-27 08:53:44.134  6090  6090 I HeadsetProvider: clearAllHeadsetSettings(0)
,07-27 08:53:44.134   749  1567 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,07-27 08:53:44.134   749  1733 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 08:53:44.134  1379  1379 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:44.134  1379  1379 D BluetoothTile:  getBluetoothState : 11
07-27 08:53:44.134  1379  1379 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 )
,07-27 08:53:44.144  1969  1969 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 08:53:44.144  6090  6090 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 08:53:44.144  6090  6090 D HeadsetStateMachine: make
,07-27 08:53:44.144  6090  6090 E HeadsetStateMachine: # of Max HF connection is 2
,07-27 08:53:44.154   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{898961c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.154  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 08:53:44.154  1379  3017 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 08:53:44.154  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 08:53:44.154   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{a767ffa: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.164  1379  3017 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 08:53:44.164  1379  1379 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-27 08:53:44.164  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-27 08:53:44.194  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 08:53:44.194   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{b11452: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.194  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-27 08:53:44.194  6090  6090 I bt_bluedroid: get_profile_interface handsfree
,07-27 08:53:44.204   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{29ac020: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.214  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 08:53:44.214  6090  6116 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 08:53:44.214  6090  6116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:53:44.214  6090  6116 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:53:44.214  6090  6116 I BluetoothAdapterState: Entering PendingCommandState
,07-27 08:53:44.214   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{128239e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.224   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{3257e7f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.224  6090  6090 I DualScoManager: Instantiating Dual Sco Manager
,07-27 08:53:44.224  6090  6090 I DualScoManager: Set HeadsetServiceHelper
,07-27 08:53:44.234   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{8bbbe4c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:44.234  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:53:44.234  6090  6090 D BluetoothAtMessage: createCMTIContentObservers
,07-27 08:53:44.234   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{6b35e95: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:44.234  6148  6229 E Fabric  : Error performing auto configuration.
07-27 08:53:44.234  6148  6229 E Fabric  : java.util.concurrent.ExecutionException: java.lang.IllegalStateException: Invalid format of fabric file,.fabric/
07-27 08:53:44.234  6148  6229 E Fabric  : 	at java.util.concurrent.FutureTask.report(FutureTask.java:94)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at java.util.concurrent.FutureTask.get(FutureTask.java:164)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at a.a.a.a.u.c(Onboarding.java:105)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at a.a.a.a.u.f(Onboarding.java:45)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at a.a.a.a.p.a(InitializationTask.java:63)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at a.a.a.a.p.a(InitializationTask.java:28)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at a.a.a.a.a.c.c.call(AsyncTask.java:311)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:44.234  6148  6229 E Fabric  : Caused by: java.lang.IllegalStateException: Invalid format of fabric file,.fabric/
07-27 08:53:44.234  6148  6229 E Fabric  : 	at a.a.a.a.k.a(FabricKitsFinder.java:91)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at a.a.a.a.k.a(FabricKitsFinder.java:58)
07-27 08:53:44.234  6148  6229 E Fabric  : 	at a.a.a.a.k.call(FabricKitsFinder.java:35)
07-27 08:53:44.234  6148  6229 E Fabric  : 	... 4 more
,07-27 08:53:44.244   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{d6edbaa: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.244  6090  6090 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@a6522c4
,07-27 08:53:44.244  6090  6090 D HeadsetProvider: setHeadsetDB - Can't find 300 for B0:C5:59:3F:75:XX
,07-27 08:53:44.244   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{e9d839b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.254  6148  6148 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 6148
,07-27 08:53:44.254   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{2c6be77: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.254  6090  6090 I HeadsetProvider: setHeadsetDB - B0:C5:59:3F:75:XX, 300, 1, true
,07-27 08:53:44.254   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{3b18ae4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.264   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{b41cb4d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.264   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{1833602: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.264   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{6decb13: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.264  6090  6090 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@fc1ac73
,07-27 08:53:44.264   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{26e7150: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.274  6090  6090 D HeadsetProvider: setHeadsetDB - Can't find 400 for B0:C5:59:3F:75:XX
07-27 08:53:44.274   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{36ccf49: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.274   749  1733 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/6148 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:44.274   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{7f2b04e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.274  6090  6090 I HeadsetProvider: setHeadsetDB - B0:C5:59:3F:75:XX, 400, 1, true
,07-27 08:53:44.274  6090  6237 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-27 08:53:44.274   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{8cd835a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.274  6090  6090 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-27 08:53:44.274  6090  6090 E HeadsetService: notifyProfileServiceStateChanged
,07-27 08:53:44.284  6090  6237 D HeadsetStateMachine: Clear mHeadsetBrsf
,07-27 08:53:44.284  6090  6237 D HeadsetStateMachine: map size, before remove : 0
07-27 08:53:44.284   749   749 D BluetoothA2dp: Proxy object connected
07-27 08:53:44.284  2384  2384 D BluetoothA2dp: Proxy object connected
,07-27 08:53:44.284  6090  6237 D HeadsetStateMachine: map size, after remove: 0
,07-27 08:53:44.284  6090  6090 D A2dpService: Received start request. Starting profile...
07-27 08:53:44.284  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
,07-27 08:53:44.284  6090  6090 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-27 08:53:44.284  6090  6090 I bt_bluedroid: get_profile_interface avrcp
,07-27 08:53:44.294   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{f22898b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.304   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{d2e3367: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.304  6090  6090 I Avrcp   : No of Audio players :: 2
,07-27 08:53:44.304   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{8ff7514: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.304  6090  6090 I Avrcp   : App Package name is GM
,07-27 08:53:44.304   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{be921bd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.304  6090  6090 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:53:44.314  6090  6090 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,07-27 08:53:44.314  6090  6090 I Avrcp   : App Package name is SM
,07-27 08:53:44.314  6090  6090 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungMusic_20_M/SamsungMusic_20_M.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:53:44.324  6090  6090 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,07-27 08:53:44.324   749   762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90b1cb9 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
,07-27 08:53:44.324  4631  4631 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 08:53:44.324   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{c91c8fe: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.324  6090  6090 I Avrcp   : No of Video players :: 2
07-27 08:53:44.324  6090  6090 I Avrcp   : Video App Package name is others
,07-27 08:53:44.324  6090  6090 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:53:44.334  6090  6090 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,07-27 08:53:44.334  6090  6090 I Avrcp   : Video App Package name is others
07-27 08:53:44.334  4631  4631 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 08:53:44.334   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{7c4285f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.334  6090  6090 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:53:44.334   749  1415 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:44.334  4631  4631 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 08:53:44.334  6090  6090 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-27 08:53:44.334  6090  6090 I Avrcp   : Add tempPlayer
07-27 08:53:44.334  6090  6090 V Avrcp   : MediaPlayerInfo: mPlayerId=5
07-27 08:53:44.334  6090  6090 V Avrcp   : no_of_players : 5
07-27 08:53:44.334  6090  6090 I Avrcp   : Total no of players: 5
07-27 08:53:44.334  6090  6090 V Avrcp   : swapping the samsung player with 1st player
,07-27 08:53:44.334  6090  6090 D Avrcp   : Compose Browsing Service Candidate
,07-27 08:53:44.334  6090  6090 D Avrcp   : ResolveInfo info ResolveInfo{ca4065c com.google.android.music/.browse.MediaBrowserService m=0x108000}
07-27 08:53:44.334  6090  6090 D Avrcp   : Initialize Media Controller
,07-27 08:53:44.344  6090  6090 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-27 08:53:44.344   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{b4c52ac: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:44.344   749  1415 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:44.344  6090  6090 E Avrcp   : getActiveSessions
07-27 08:53:44.344  6090  6090 D Avrcp   : pick active media Controller
07-27 08:53:44.344  6090  6090 D Avrcp   : Get the active Media Controller 
,07-27 08:53:44.344  6090  6090 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:53:44.344  6090  6090 D A2dpStateMachine: make
,07-27 08:53:44.344  4631  4631 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-27 08:53:44.344  4631  4631 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 08:53:44.344  4631  4631 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-27 08:53:44.344  6090  6090 I bt_bluedroid: get_profile_interface a2dp
07-27 08:53:44.344  4631  4646 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 08:53:44.344  6090  6090 E bt_btif : warning : media task started media_task_refcnt 1 
07-27 08:53:44.344  6090  6090 E bt_btif : warning : no command pending, ignore ack
,07-27 08:53:44.344  6090  6248 D A2dpStateMachine: Enter Disconnected: -2
,07-27 08:53:44.354   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{db7cb75: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.354  6090  6090 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-27 08:53:44.354  6090  6090 E A2dpService: notifyProfileServiceStateChanged
,07-27 08:53:44.354  6090  6090 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 08:53:44.364   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90b1cb9 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{57edbad 5344:com.samsung.android.app.FileShareServer/5005}
,07-27 08:53:44.364  6090  6090 D HidService: Received start request. Starting profile...
07-27 08:53:44.364  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
07-27 08:53:44.364  6090  6090 I bt_bluedroid: get_profile_interface hidhost
07-27 08:53:44.364  6090  6090 D HidService: setHidService(): set to: null
07-27 08:53:44.364  6090  6090 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
07-27 08:53:44.364  6090  6090 E HidService: notifyProfileServiceStateChanged
,07-27 08:53:44.384  6090  6090 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 08:53:44.384   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{1dddd62: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.384  5344  5344 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-27 08:53:44.384  6090  6090 D HealthService: Received start request. Starting profile...
07-27 08:53:44.384  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
,07-27 08:53:44.384   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{b74ef3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.384  6090  6090 I bt_bluedroid: get_profile_interface health
,07-27 08:53:44.384  6090  6090 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
07-27 08:53:44.384  6090  6090 E HealthService: notifyProfileServiceStateChanged
,07-27 08:53:44.384  6090  6090 D HeadsetStateMachine: Try to query the phonestate on bind
,07-27 08:53:44.384   749  1747 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 08:53:44.384   749  1747 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,07-27 08:53:44.394  6090  6090 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,07-27 08:53:44.394   749   749 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 08:53:44.394  6090  6090 D PanService: Received start request. Starting profile...
07-27 08:53:44.394  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
07-27 08:53:44.394  6090  6090 D BluetoothPanServiceJni: initializeNative(L118): pan
07-27 08:53:44.394  6090  6090 I bt_bluedroid: get_profile_interface pan
,07-27 08:53:44.394  5344  5344 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
07-27 08:53:44.394  5344  5344 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
,07-27 08:53:44.394  5344  5344 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:53:44.394  6090  6090 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
07-27 08:53:44.394  6090  6090 E PanService: notifyProfileServiceStateChanged
07-27 08:53:44.394  5344  5344 W System.err: 	at com.samsung.android.app.FileShareServer.ServerBroadcastReceiver.onReceive(ServerBroadcastReceiver.java:34)
,07-27 08:53:44.394  5344  5344 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3634)
07-27 08:53:44.394  5344  5344 W System.err: 	at android.app.ActivityThread.access$2000(ActivityThread.java:221)
07-27 08:53:44.394  5344  5344 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1876)
07-27 08:53:44.394  5344  5344 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-27 08:53:44.394  5344  5344 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:53:44.394  5344  5344 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-27 08:53:44.394  6090  6090 D HeadsetStateMachine: Proxy object connected
07-27 08:53:44.394  5344  5344 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,07-27 08:53:44.394  5344  5344 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-27 08:53:44.394  5344  5344 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-27 08:53:44.394   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{b0cd7b0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.394  6111  6111 I wpa_supplicant: nl80211: Received scan results (12 BSSes)
,07-27 08:53:44.394  6111  6111 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-27 08:53:44.394  6111  6111 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-27 08:53:44.394  6111  6111 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-27 08:53:44.394  6111  6111 I wpa_supplicant:    allow  - level is under -85dBm [-43] or selected nid [-1] [0]
,07-27 08:53:44.404  6111  6111 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
07-27 08:53:44.404  6111  6111 I wpa_supplicant:    allow  - level is under -85dBm [-43] or selected nid [-1] [0]
,07-27 08:53:44.404  6111  6111 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz level=-43) 
,07-27 08:53:44.404  6090  6090 D BluetoothMapService: Received start request. Starting profile...
07-27 08:53:44.404  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
,07-27 08:53:44.404   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{f5fbedc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.404   305  1126 D Netd    : Iface wlan0 link up
,07-27 08:53:44.404  6090  6090 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
,07-27 08:53:44.404  6090  6090 E BluetoothMapService: notifyProfileServiceStateChanged
07-27 08:53:44.404   749   832 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:53:44.404   749   832 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:53:44.414  6090  6090 V SapService: SapBinder()
,07-27 08:53:44.414  6090  6090 D SapService: Received start request. Starting profile...
,07-27 08:53:44.414  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
07-27 08:53:44.414  6090  6090 V SapService: start()
,07-27 08:53:44.414  6090  6090 D SapService: Disable sap : false
,07-27 08:53:44.414  6090  6090 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
,07-27 08:53:44.414   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{184f161: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.414  6090  6090 E SapService: notifyProfileServiceStateChanged
,07-27 08:53:44.414  6090  6090 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,07-27 08:53:44.414  6090  6090 D HeadsetPhoneState: sendDeviceDataStateChanged
,07-27 08:53:44.414  6090  6090 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-27 08:53:44.414  6090  6090 E BluetoothAdapterService: handleMessage() - Message: 1
,07-27 08:53:44.414  6090  6090 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:53:44.424  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 08:53:44.424  6090  6090 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:53:44.424  6090  6090 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
,07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isTurningOn()=true
,07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:44.424  6090  6090 E BluetoothAdapterService: handleMessage() - Message: 1
,07-27 08:53:44.424  6090  6090 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-27 08:53:44.424  6090  6237 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:53:44.424  6090  6237 E HeadsetStateMachine: Unknown message: 11
07-27 08:53:44.424  6090  6237 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-27 08:53:44.424  6090  6237 E HeadsetStateMachine: Unknown message: 19
07-27 08:53:44.424  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 08:53:44.424  6090  6237 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:53:44.424  6090  6237 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:53:44.424  6090  6237 E HeadsetStateMachine: Unknown message: 11
,07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:44.424  6090  6090 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:44.424  6090  6090 D BluetoothAdapterService: HID Host service started
,07-27 08:53:44.424   749  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:53:44.434   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{92c8486: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.434   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{df97147: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.434  6090  6090 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,07-27 08:53:44.434  6090  6090 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:53:44.434  6090  6090 D HeadsetPhoneState: sendDeviceDataStateChanged
,07-27 08:53:44.434  6090  6237 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:53:44.434  6090  6237 E HeadsetStateMachine: Unknown message: 11
07-27 08:53:44.434  6090  6090 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-27 08:53:44.434  6090  6237 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-27 08:53:44.434  6090  6237 E HeadsetStateMachine: Unknown message: 19
07-27 08:53:44.434  6090  6090 E BluetoothAdapterService: handleMessage() - Message: 1
,07-27 08:53:44.444  6090  6090 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:44.444  6090  6090 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:53:44.444  6090  6090 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:44.444  6090  6090 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:53:44.444  6090  6090 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:53:44.444  6090  6090 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:53:44.444  6090  6090 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:44.444  6090  6090 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:44.444  6090  6116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-27 08:53:44.444  6090  6116 E BluetoothServiceJni: enableBrEdrNative:
07-27 08:53:44.444  6090  6116 I bt_bluedroid: enable_bredr
,07-27 08:53:44.454   749  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a30d74 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
,07-27 08:53:44.464  6256  6256 E Zygote  : v2
07-27 08:53:44.464  6256  6256 I libpersona: KNOX_SDCARD checking this for 5005
07-27 08:53:44.464  6256  6256 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:44.464  6256  6256 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:44.464  6256  6256 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:44.474   749   826 I ActivityManager: Start proc 6256:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,07-27 08:53:44.474  6256  6256 E Zygote  : accessInfo : 0
07-27 08:53:44.474  6256  6256 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,07-27 08:53:44.484  6111  6111 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,07-27 08:53:44.484   305  1126 D Netd    : Iface wlan0 link up
07-27 08:53:44.484   305  1126 D Netd    : Iface wlan0 link up
07-27 08:53:44.484   305  1126 D Netd    : Iface wlan0 link up
07-27 08:53:44.484   749   832 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:53:44.484   749   832 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:53:44.484   749   832 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:53:44.484   749   832 D Tethering: interfaceStatusChanged wlan0, true
07-27 08:53:44.484   749   832 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:53:44.484   749   832 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:53:44.484  6111  6111 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-27 08:53:44.494  6111  6111 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
07-27 08:53:44.494  6111  6111 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,07-27 08:53:44.494   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{4f99e5e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.494  6090  6128 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xb2a4d929
07-27 08:53:44.494  6090  6128 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
,07-27 08:53:44.494  6090  6222 D         : Codec ==> copy capability info [bta_av_co_audio_init:584]
07-27 08:53:44.494  6090  6128 D BluetoothAdapterProperties: Address is:B0:C5:59:3F:75:69
07-27 08:53:44.494  6090  6128 E BluetoothServiceJni: populateRssiValuesNative
07-27 08:53:44.494  6090  6128 I bt_bluedroid: getModelRssiValues
07-27 08:53:44.494  6090  6128 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-27 08:53:44.494  6090  6128 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 08:53:44.494  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.494  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.494  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.494   749  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:53:44.494  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.494  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.494  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.494  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.494  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.494  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.494  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.494  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.494  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.504  6111  6111 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
07-27 08:53:44.504  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.504  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.504  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.504  6111  6111 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,07-27 08:53:44.504  6090  6128 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy S5)
07-27 08:53:44.504   749   749 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,07-27 08:53:44.504  6111  6111 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 08:53:44.504  6111  6111 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 08:53:44.504  6111  6111 I wpa_supplicant: Blacklist: Clear (temp) 
07-27 08:53:44.504   305  1126 D Netd    : Iface wlan0 link up
,07-27 08:53:44.514   749   832 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:53:44.514   749   832 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:53:44.514  6090  6128 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-27 08:53:44.514  6090  6128 D BluetoothAdapterProperties: Scan Mode:20
07-27 08:53:44.514  6090  6128 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:53:44.514  6090  6128 E bt_btif : btif_handle_bluetooth_enable_evt
07-27 08:53:44.514  6090  6128 E bt_btif : ANT+ socket does not initialize.
,07-27 08:53:44.524  6090  6128 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-27 08:53:44.524  6090  6128 D IOP_DB_BT: db_open: db_open : handle 2996740112l, read 17911 bytes onto local cache
07-27 08:53:44.524  6090  6128 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-27 08:53:44.524  6090  6128 D IOP_DB_BT: db_query: result 1
07-27 08:53:44.524  6090  6128 I         : iop_db_open: iop_db_open status 0
07-27 08:53:44.524  6090  6128 E BluetoothAdapterState: stateChangeCallback : 17
07-27 08:53:44.524  6090  6116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,07-27 08:53:44.524  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.524  6090  6128 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 08:53:44.524  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.524  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.524  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.524  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.524  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.524  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.524  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.524  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.524  5802  5802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:53:44.524  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.524  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.524  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.524   749  1747 I ActivityManager: Killing 4478:com.android.providers.calendar/u0a46 (adj 15): DHA:empty #37
,07-27 08:53:44.524  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.524  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.524  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.534  6256  6256 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:44.534  6256  6256 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:44.534  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.534  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.534  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.534  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.534  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.534  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.534  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.534  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.534  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.534   749  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a30d74 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5b3690 2384:com.samsung.android.providers.context/u0a175}
,07-27 08:53:44.534  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.534  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.534  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.534  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.534  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.534  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.534  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.534  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.534  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.544  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.544  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.544  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.544   749  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:53:44.544   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{73d423f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.554  6090  6116 D BluetoothAdapterProperties: ScanMode =  20
07-27 08:53:44.554  6090  6116 D BluetoothAdapterProperties: State =  11
,07-27 08:53:44.554   749   759 I art     : Background partial concurrent mark sweep GC freed 64768(4MB) AllocSpace objects, 18(356KB) LOS objects, 27% free, 42MB/58MB, paused 11.152ms total 189.973ms
,07-27 08:53:44.554   749  1415 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{90b1cb9 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{afe970c 6256:com.samsung.android.app.FileShareClient/5005}
,07-27 08:53:44.564   749  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a30d74 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
,07-27 08:53:44.574  1632  1632 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,07-27 08:53:44.574   749  1567 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,07-27 08:53:44.574  6256  6256 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package null
,07-27 08:53:44.584   749  1325 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-27 08:53:44.594   749  2078 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-27 08:53:44.594   749   762 D SecContentProvider: insert(), uri = 2
,07-27 08:53:44.594  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.594  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.594  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.594  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.594  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.594  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.594  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.594  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.594  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.594   749  2079 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a30d74 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f630343 1887:com.sec.android.app.shealth:remote/u0a35}
,07-27 08:53:44.604   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{fb42855: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.604  6090  6128 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-27 08:53:44.604  6090  6128 D BluetoothAdapterProperties: Scan Mode:21
07-27 08:53:44.604  6090  6128 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 08:53:44.604  6090  6116 D BluetoothAdapterProperties: Setting state to 12
07-27 08:53:44.604  6090  6116 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-27 08:53:44.604  6090  6116 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:53:44.604  6090  6116 D BluetoothAdapterService: updateAdapterState state is 12
,07-27 08:53:44.614   749  1325 V AlarmManager:  remove PendingIntent] PendingIntent{95bf4d1: PendingIntentRecord{b651b36 android broadcastIntent}}
,07-27 08:53:44.614   749  1325 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,07-27 08:53:44.614  6256  6256 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm
,07-27 08:53:44.614  5802  5802 D BluetoothAdapter: STATE_ON
,07-27 08:53:44.614   749   749 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,07-27 08:53:44.624   749   749 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:53:44.624   749   749 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-27 08:53:44.624   749  1330 I WifiHs20Service: Message received 5007
07-27 08:53:44.624   749  1325 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:53:44.624   749  1332 D ConnectivityService: Got NetworkAgent Messenger
07-27 08:53:44.624   749  1332 E ConnectivityService: updateNetworkInfo()
07-27 08:53:44.624   749  1332 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:44.624   749  1332 D ConnectivityService: NetworkAgent connected
,07-27 08:53:44.624  5802  5802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-27 08:53:44.624   305  1133 D CommandListener: Setting iface cfg
,07-27 08:53:44.624  5802  5802 D BluetoothAdapter: STATE_ON
07-27 08:53:44.624  6256  6256 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 08:53:44.634  5802  5802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:53:44.634  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:44.634  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 08:53:44.634  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:53:44.634  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:53:44.634  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:44.634  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:44.634  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:53:44.634  5802  5802 D BluetoothAdapter: STATE_ON
,07-27 08:53:44.634   749  1625 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a30d74 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
,07-27 08:53:44.634  5802  5802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:53:44.634  4631  4631 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 08:53:44.644  6090  6116 V BluetoothAdapterService: start opp service
,07-27 08:53:44.644   749  1325 D WifiStateMachine: Start Dhcp Watchdog 1
,07-27 08:53:44.644   749  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:53:44.644   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{537a3be: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.654  6090  6090 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-27 08:53:44.654   749  1733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a30d74 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97a4d07 1379:com.android.systemui/u0a59}
,07-27 08:53:44.654  1379  1379 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:44.654  1379  1379 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-27 08:53:44.654  6090  6116 D BluetoothAdapterService: Autoconnection is available 
07-27 08:53:44.654  6090  6116 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-27 08:53:44.654  6090  6116 D BluetoothAdapterService: starting service from this receiver
07-27 08:53:44.654   749  1325 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,07-27 08:53:44.664  2384  2399 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 08:53:44.664   749   873 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 08:53:44.664  1632  4034 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.664  1632  4034 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:53:44.664  6148  6160 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.664  6148  6160 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:53:44.664   749  1332 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-27 08:53:44.664   749  1332 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:53:44.664  6256  6256 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,07-27 08:53:44.664  6090  6116 D BluetoothAdapterService: BT on, init HID DEV count : 0
07-27 08:53:44.664  6090  6116 I BluetoothAdapterState: Entering OnState
,07-27 08:53:44.674  6090  6090 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-27 08:53:44.674  6090  6090 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:53:44.674  6090  6090 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:53:44.674  6090  6090 W System.err: 	at com.android.bluetooth.opp.BluetoothOppService.onCreate(BluetoothOppService.java:195)
07-27 08:53:44.674  6090  6090 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3807)
07-27 08:53:44.674  6090  6090 W System.err: 	at android.app.ActivityThread.access$2100(ActivityThread.java:221)
07-27 08:53:44.674  6090  6090 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1882)
07-27 08:53:44.674  6090  6090 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:44.674  6090  6090 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:53:44.674  6090  6090 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-27 08:53:44.674  6090  6090 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:44.674  6090  6090 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-27 08:53:44.674  6090  6090 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,07-27 08:53:44.674  6090  6090 V BtOppService: isOwner == true
07-27 08:53:44.674   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{6780b3b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.674   749  1332 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:53:44.674  5802  5812 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.674  5802  5812 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:53:44.674   749   873 D BluetoothPan: onBluetoothStateChange on: true
,07-27 08:53:44.684   749   873 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.684   749   873 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:53:44.684  1682  2006 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.684  1682  2006 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:53:44.684   749  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a30d74 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a6f808 6090:com.android.bluetooth/1002}
,07-27 08:53:44.684  1675  1699 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.684  1675  1699 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:53:44.684   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{f2af258: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.694  1887  1898 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.694  1887  1898 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:53:44.694  5963  5973 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.694  5963  5973 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:53:44.694   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{3302fb1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:44.694  2384  2399 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.694  2384  2399 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:53:44.694  1379  3383 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.694  1379  3383 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:53:44.694  6090  6239 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:53:44.694  6090  6239 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:53:44.694   749   749 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:44.694   749   749 I InputMethodManagerService: [BT Setting State] State =12
07-27 08:53:44.694   749   749 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-27 08:53:44.694  1773  1773 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:53:44.704  1969  1969 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 08:53:44.704   749   749 I Telecom : BluetoothPhoneService: queryPhoneState
07-27 08:53:44.704   749   749 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,07-27 08:53:44.704   749   749 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-27 08:53:44.704   749   749 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:44.704   749   749 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-27 08:53:44.704   749  1625 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,07-27 08:53:44.704   749  1414 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-27 08:53:44.704  1379  1379 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:44.704  1379  1379 D BluetoothTile:  getBluetoothState : 12
07-27 08:53:44.704  1379  1379 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,07-27 08:53:44.714   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{6715ed: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.714   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{6e0bc22: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.714  1379  3017 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 08:53:44.714  6090  6090 I BluetoothPbapService: Handler(): got msg=1
,07-27 08:53:44.714   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{b4ea6b3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.714   749  1625 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 08:53:44.714   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{8b9b470: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.724   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{aac23e9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.724   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{d72786e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.724  6090  6278 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-27 08:53:44.724  6256  6256 D FileShare-Client: Outbound.stopDelayTimer - 
,07-27 08:53:44.734   749  1320 I ActivityManager: Killing 3744:com.google.android.talk/u0a117 (adj 15): DHA:empty #37
,07-27 08:53:44.734   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{95d4e34: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:44.734  6090  6278 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:53:44.734  6090  6278 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:53:44.734  6090  6278 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
07-27 08:53:44.734  6090  6158 D bt_vendor: op for 7
07-27 08:53:44.734  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:44.734  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:44.744   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{c9b19a0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.744   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{198d959: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.754  6281  6281 E Zygote  : v2
07-27 08:53:44.754  6281  6281 I libpersona: KNOX_SDCARD checking this for 10122
07-27 08:53:44.754  6281  6281 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:44.754   749  1746 I ActivityManager: Start proc 6281:com.google.android.apps.maps/u0a122 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
07-27 08:53:44.754  6281  6281 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:44.754  6281  6281 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:44.754  6281  6281 E Zygote  : accessInfo : 0
,07-27 08:53:44.754  6281  6281 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,07-27 08:53:44.754   749  1325 E WifiNative-wlan0: do suspend false
,07-27 08:53:44.764  6090  6280 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
07-27 08:53:44.764  6090  6280 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:53:44.764  6090  6280 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:53:44.764  6090  6280 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:250)
,07-27 08:53:44.764   749  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-27 08:53:44.764   749  1324 D WifiP2pService: InactiveState{ what=143375 }
,07-27 08:53:44.764   749  1324 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 08:53:44.774  1379  1379 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02061d/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f02017c/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:53:44.774  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:44.774  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:44.774  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:44.774  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:44.774   749   762 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,07-27 08:53:44.794  6292  6292 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 08:53:44.794  6281  6281 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:44.794  6281  6281 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:44.794   749   761 I ActivityManager: Start proc 6294:com.android.email/u0a163 for content provider com.android.email/.provider.EmailProvider
,07-27 08:53:44.794  6292  6292 I dhcpcd  : version 5.5.6 starting
07-27 08:53:44.794  6294  6294 E Zygote  : v2
07-27 08:53:44.794  6294  6294 I libpersona: KNOX_SDCARD checking this for 10163
07-27 08:53:44.794  6294  6294 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:44.794  6294  6294 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:44.794  6294  6294 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:44.794  6294  6294 E Zygote  : accessInfo : 0
,07-27 08:53:44.794  6294  6294 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.email 
,07-27 08:53:44.804   749  1323 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 08:53:44.804  6292  6292 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 08:53:44.814   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a30d74 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78e7cb8 6281:com.google.android.apps.maps/u0a122}
,07-27 08:53:44.814   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{ffb5a91: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:44.814   749  1323 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 08:53:44.814   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{83175f7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:44.814  6090  6239 D A2dpStateMachine: getConnectedDevices : size=0
07-27 08:53:44.814   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{30aac64: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.824   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{56a0ecd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.824   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{e38f382: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.824   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{fd7a93: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.834   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{7f82ad0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.834   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{e95cac9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:44.834   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{a06c5ce: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.844  6281  6281 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.google.android.apps.maps rsrc of package null
,07-27 08:53:44.844   749   749 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@7b2cef
,07-27 08:53:44.844   749   749 D BluetoothHeadset: registerMessageListener
,07-27 08:53:44.844  6090  6109 D HeadsetService: registerMessageListener
,07-27 08:53:44.844  6090  6109 D HeadsetService: registerMessageListener
07-27 08:53:44.844  6294  6294 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:44.844  6294  6294 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:44.844   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{bfd23fc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.844   749   749 I Telecom : BluetoothManager : register MessageListener
,07-27 08:53:44.844   749   749 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,07-27 08:53:44.844   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{ca74a85: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.844  6090  6237 D HeadsetStateMachine: Disconnected process message: 70, size: 0
,07-27 08:53:44.854  6090  6237 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2a368e
,07-27 08:53:44.854   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{3cd70da: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.864   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{977a90b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.864   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{6f683e8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.864   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{970a01: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.864   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{321c0a6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.864   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{475cae7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:44.864  6294  6294 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in com.android.email rsrc of package null
,07-27 08:53:44.874   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{fa3f694: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.874   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{869453d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.874   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{2194132: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.874   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{54a2e83: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.874   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{713e800: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.884   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{429f839: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.884  6090  6233 D bt_upio : ..proc_btwrite_timeout..
07-27 08:53:44.884  6090  6233 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-27 08:53:44.894   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{4963e7e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.894   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{e772fdf: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.904   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{ecf842c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.904  6281  6281 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-27 08:53:44.904   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{ea8def5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.904   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{853c48a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.914   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{e48eafb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.914  6292  6292 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:53:44.914  6292  6292 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,07-27 08:53:44.914   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{5c6b718: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.914  6292  6292 I dhcpcd  : bssid match
,07-27 08:53:44.914  6292  6292 I dhcpcd  : wlan0: rebinding lease of 192.168.1.124
,07-27 08:53:44.914   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{5f57571: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.914   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{9b19f56: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.924   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{1b13bd7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.924   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{7fc2cc4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.924   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{f9af7ad: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.924   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{9405ae2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.934   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{8e3be73: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.934   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{cf15130: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.934   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{49c61a9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.934   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{e0d432e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.934   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{9b1cecf: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.944   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{d2505c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.944   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{1306f65: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.944   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{ae643a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.944   749  2079 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:44.944   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{ba688eb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.954   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{4621648: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.954   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{43d9ce1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.954   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{b0e8a06: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.964   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{9e2c8c7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.964   749  1746 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:44.964   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{fa64ef4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.964  6292  6292 I dhcpcd  : wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,07-27 08:53:44.964   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{a96261d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.974   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{8f94092: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.974   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{6b92a63: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.974   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{3536660: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.984   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{1f40719: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.984   749  2079 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:44.984   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{fb4fbd5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.984   749  1713 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:44.984   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{884fea: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.994  6292  6292 I dhcpcd  : wlan0: leased 192.168.1.124 for 172800 seconds
07-27 08:53:44.994   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{b5f82db: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.994   749  1332 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:53:44.994   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{1eba178: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.994   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{7568051: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:44.994   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{a9380b6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.004   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{4c971b7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.004   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{4f55d24: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.004   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{cb1d08d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.014   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{f4ef242: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.014   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{3797253: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.024   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{abd2790: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.024   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{df7e889: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.054   749  1733 I ActivityManager: Start proc 6324:com.sec.android.provider.badge/u0a78 for content provider com.sec.android.provider.badge/.BadgeProvider
,07-27 08:53:45.054  6324  6324 E Zygote  : v2
07-27 08:53:45.054  6324  6324 I libpersona: KNOX_SDCARD checking this for 10078
07-27 08:53:45.054  6324  6324 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:45.054  6324  6324 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:45.054  6324  6324 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:45.054  6324  6324 E Zygote  : accessInfo : 0
,07-27 08:53:45.054  6324  6324 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,07-27 08:53:45.064   749   762 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 08:53:45.064   749   762 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:45.074   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{e5df08e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.084   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{91ee0af: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.084   749  1712 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:45.084   749  1567 I ActivityManager: Killing 5356:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): DHA:empty #37
,07-27 08:53:45.084  6324  6324 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:45.084  6324  6324 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:45.094   749  1320 I ActivityManager: Killing 5392:com.sec.android.app.camera/u0a154 (adj 15): DHA:empty #37
,07-27 08:53:45.114   749  1625 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,07-27 08:53:45.114  6090  6090 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,07-27 08:53:45.114  6090  6338 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:53:45.114  6090  6338 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:53:45.124  6090  6338 I BtOppRfcommListener: Accept thread started.
07-27 08:53:45.124  6090  6158 D bt_vendor: op for 7
07-27 08:53:45.124  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 08:53:45.124  6090  6158 D bt_upio : upio_start_stop_timer : timer_settime success
07-27 08:53:45.124  6090  6158 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-27 08:53:45.124   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{f52cbc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.124  6090  6340 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:53:45.124  6090  6340 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:53:45.124   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{16d8445: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.124  6090  6090 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:53:45.124  6090  6090 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:53:45.124  6090  6340 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,07-27 08:53:45.134  6090  6340 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-27 08:53:45.134  6090  6158 D bt_vendor: op for 7
07-27 08:53:45.134  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:45.134  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:45.134   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{c4c879a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.134  6090  6090 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:53:45.134  6090  6090 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:53:45.134  6090  6090 D ObexServerSockets: Succeed to create listening sockets 
07-27 08:53:45.134   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{902d8cb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.134  6090  6090 D ObexServerSockets: startAccept()
,07-27 08:53:45.134  6090  6344 D ObexServerSockets: Accepting socket connection for masId0
,07-27 08:53:45.134  6090  6345 D ObexServerSockets: Accepting socket connection for masId0
,07-27 08:53:45.144   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{c4658a8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.144  6090  6090 D BluetoothMapMasInstance: set MAP SDP message type : 1
07-27 08:53:45.144  6090  6090 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-27 08:53:45.144  6090  6158 D bt_vendor: op for 7
07-27 08:53:45.144  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:53:45.144  6090  6158 D bt_upio : BT_WAKE is asserted already
07-27 08:53:45.144  6090  6090 D BluetoothSdpJni: SDP Create record success - handle: 1
,07-27 08:53:45.144   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{2e71fc1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.154   749  1713 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
,07-27 08:53:45.154  6324  6324 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package null
,07-27 08:53:45.154   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{85b8366: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.164   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{7e436a7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.164   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{d04f6fd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.164   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{30c6ff2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.164   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{d939643: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.174   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{a7194c0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.174   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{a2f05f9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.174   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{16d993e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.174   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{44f539f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.174   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{d3b3cec: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.184   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{95108b5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.184   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{9260b4a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.184   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{1df8abb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.184   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{153bd8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.184   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{2567b31: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.194   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{1419216: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.194   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{6721797: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.194   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{78e3d84: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.194  6324  6324 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm
,07-27 08:53:45.194  6324  6324 D BadgeProvider: onCreate
,07-27 08:53:45.194  6324  6324 D BadgeProvider: DatabaseHelper
,07-27 08:53:45.204   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{666996d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.214  6324  6335 D BaseReflect: null getOwnClass TEST
,07-27 08:53:45.214  6324  6335 D MethodReflector: android.content.ContentResolver getClass TEST
07-27 08:53:45.214  6324  6335 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
,07-27 08:53:45.224  6324  6335 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,07-27 08:53:45.224   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{3bcb9a2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.224  6324  6335 D MethodReflector: notifyChange is called
07-27 08:53:45.224  1700  1700 D Launcher.Model: reloadBadges entered.
07-27 08:53:45.224  6324  6335 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-27 08:53:45.224  6324  6335 D BadgeProvider: sendNotify, [notify] : null
07-27 08:53:45.224  6324  6335 D BadgeProvider: update, getCallingPackage() : com.android.email
07-27 08:53:45.224  6324  6335 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-27 08:53:45.224  6324  6335 D BadgeProvider: update, [uri.query] : null
07-27 08:53:45.224  6324  6335 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-27 08:53:45.224  6324  6335 D BadgeProvider: update, [UpdateCount] : 1
07-27 08:53:45.224  1700  1700 D Launcher.Model: reloadBadges entered.
,07-27 08:53:45.244  6324  6335 D BadgeProvider: query, [selection] : null
,07-27 08:53:45.254   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{d369633: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.254   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{73adf0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.254   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{7e05f69: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.254   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{bd0cdee: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.264   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{aba628f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.264   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{6168925: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.274   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{cffdafa: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.274   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{50498ab: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.284   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{8bb4b08: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.284   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{8cb92a1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.284   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{ee0acc6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.284   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{1721487: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.294   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{73e0fb4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.294   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{76db7dd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.294   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{9aacf52: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.294   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{4517223: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.294   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{1867320: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.304   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{812f4d9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.304   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{f828e9e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.304   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{e3f0d7f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.304   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{62fa14c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.304   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{2350595: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.304   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e84f6aa: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.314   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{341029b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.314   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{5b8638: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.314   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{12d6611: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.314   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{793d376: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.314   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{7a32d77: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.324   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{95ecde4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.324  6324  6335 D BadgeProvider: query, [selection] : null
,07-27 08:53:45.324   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{271524d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.324   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{5e1b102: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.334  6294  6314 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:53:45.344   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{e932a13: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.344   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{92ce450: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.344  6294  6314 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:53:45.354   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{33ddb4e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.354   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{67c546f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.354   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{183f57c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.364   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{3e37e05: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.364   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{5205e5a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.364   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{f23c88b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.374   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{fd8ed68: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.374   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e22f581: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.374   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{e760626: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.374   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{5846267: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.374   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{2037814: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.384   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{d8868bd: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.384   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{22c5eb2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.384   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{9aa0180: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.384   749  1325 E WifiNative-wlan0: do suspend true
,07-27 08:53:45.394   749  1324 D WifiP2pService: InactiveState{ what=143375 }
,07-27 08:53:45.394   749  1324 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 08:53:45.394   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{2d7d3b9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.394   749  1332 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:53:45.394   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{27db3fe: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.394   749  1325 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 08:53:45.394   749  1325 D WifiStateMachine: VerifyingLinkState enter
,07-27 08:53:45.394   749  1332 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-27 08:53:45.404   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{d1375f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.404   749  1332 E ConnectivityService: updateNetworkInfo()
,07-27 08:53:45.404   749  1332 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,07-27 08:53:45.404   749  1332 D ConnectivityService: Adding iface wlan0 to network 502
,07-27 08:53:45.404  6281  6362 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
,07-27 08:53:45.414   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{a6db5ac: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.414  6281  6362 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,07-27 08:53:45.414   749   749 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-27 08:53:45.414   749   749 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:45.414   749   749 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-27 08:53:45.414   749  1330 I WifiHs20Service: Message received 5007
,07-27 08:53:45.414   749  1344 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-27 08:53:45.414   749  1344 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 08:53:45.424   749  1344 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:53:45.424   749  1344 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 08:53:45.424   749  1344 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 08:53:45.434  6281  6362 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
,07-27 08:53:45.434   749  1325 D WifiNative-wlan0: callSECApiInt - ID [210]
,07-27 08:53:45.444   749  1344 I WifiManager: isCaptivePortalException
,07-27 08:53:45.444   749  1344 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-27 08:53:45.444   749  1344 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,07-27 08:53:45.444   749  1344 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
,07-27 08:53:45.444   749  1344 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {d18f275}
07-27 08:53:45.444   749  1344 I WifiManager: isCaptivePortalException
,07-27 08:53:45.444   749  1344 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-27 08:53:45.444   749  1344 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,07-27 08:53:45.444   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{8fd120a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.444   749  1325 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,07-27 08:53:45.444   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{cfbea7b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.444   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{ed68098: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.454   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{a1340f1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.454   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{36244d6: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.454   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{554b357: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.454   749  1332 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,07-27 08:53:45.454   749  1332 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,07-27 08:53:45.454   749  1332 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,07-27 08:53:45.454   749  1332 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-27 08:53:45.454   749  1332 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
,07-27 08:53:45.464   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{fff0e44: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.464   749  1325 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 08:53:45.464   749   749 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-27 08:53:45.464   749   749 I WifiTrafficPoller: mBoosterFLAG : 0
07-27 08:53:45.464   749   749 I WifiTrafficPoller: current booster mode : FullMode
07-27 08:53:45.464   749   749 D WifiNative-wlan0: callSECApiVoid - ID [212]
,07-27 08:53:45.464  6111  6111 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-27 08:53:45.464  6111  6111 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 08:53:45.464   749   749 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-27 08:53:45.464   749   749 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:53:45.464   749   749 D HS20StateMachine: SSID : "NG700"
07-27 08:53:45.464   749   749 D HS20StateMachine: NetId : 0
07-27 08:53:45.464   749   749 D HS20StateMachine: checkifOSUAP  null
07-27 08:53:45.464   749   749 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-27 08:53:45.464   749  1330 I WifiHs20Service: Message received 5007
,07-27 08:53:45.464   749  1332 V NetworkStats: updateIfacesLocked()
07-27 08:53:45.464   749  1332 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:53:45.464   749  1332 V NetworkStats: performPollLocked() took 2ms
,07-27 08:53:45.474   749  1325 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 08:53:45.474  6111  6111 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 08:53:45.484   749  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.484   749  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-27 08:53:45.484   749  1323 D NtpTrustedTime: forceRefresh: no connectivity
07-27 08:53:45.484   749  1332 D ConnectivityService: Not required to send intent.
07-27 08:53:45.484   749  1332 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:53:45.484   749  1332 E ConnectivityService: updateNetworkInfo()
07-27 08:53:45.484   749  1332 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-27 08:53:45.484   749  1332 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-27 08:53:45.484   749  1332 V NetworkStats: updateIfacesLocked()
07-27 08:53:45.484   749  1332 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:53:45.484   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{115d862: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.484   749  1332 V NetworkStats: performPollLocked() took 3ms
,07-27 08:53:45.484   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{c072df3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.484   749  1323 D NtpTrustedTime: forceRefresh: no connectivity
07-27 08:53:45.484   749  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.484   749  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-27 08:53:45.484   749  6274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:53:45.484   749  6274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Connected
,07-27 08:53:45.484   749  6274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:53:45.484   749  1332 D ConnectivityService: scheduleUnvalidatedPrompt 502
,07-27 08:53:45.494   749  1332 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 502]
07-27 08:53:45.494   749  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-27 08:53:45.494   749  1325 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-27 08:53:45.494   749  1325 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-27 08:53:45.494   749  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:53:45.494   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,07-27 08:53:45.494   749  6274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Validated
07-27 08:53:45.494   749  1332 D ConnectivityService: currentScore = 0, newScore = 20
07-27 08:53:45.494   749  1332 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 502]
07-27 08:53:45.494   749  1332 D ConnectivityService:    accepting network in place of null
,07-27 08:53:45.494   749  1332 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.494   749  1324 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.494   749  1325 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.494   749  1325 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.494   749  1325 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:53:45.494   749  1325 D WIFI_UT : evalRequest
07-27 08:53:45.494   749  1325 D WIFI_UT :   done
07-27 08:53:45.494   749  1325 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.494   749  1325 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.494   749  1325 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:53:45.494   749  1325 D WIFI    : evalRequest
07-27 08:53:45.494   749  1325 D WIFI    :   done
,07-27 08:53:45.494   749  1324 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.494   749  1324 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:53:45.494   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{c00cab0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.494   749  1324 D WIFI_P2P: evalRequest
07-27 08:53:45.494   749  1324 D WIFI_P2P:   done
,07-27 08:53:45.494   749  1325 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.494   749  1325 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.494   749  1325 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:53:45.494   749  1325 D WIFI    : evalRequest
07-27 08:53:45.494   749  1325 D WIFI    :   done
07-27 08:53:45.494   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:45.494   749  1353 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.494   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:45.494   749  1353 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-27 08:53:45.494   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:45.494   749  1353 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:53:45.494   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-27 08:53:45.494   749  1353 D Ethernet: evalRequest
07-27 08:53:45.494   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:45.494   749  1353 D Ethernet:   done
07-27 08:53:45.494   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-27 08:53:45.494   749  1332 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 08:53:45.494   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{e381d29: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.504   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{d7d18ae: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.504   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{5cb64f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.524   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{71fe1dc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.524   305  1133 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 08:53:45.524   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{b8c62e5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.524   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{30611ba: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.534   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{2d8686b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.534   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{3b73fc8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.534   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{7254861: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.534   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{2f38f86: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.534   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{f132047: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.544   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{ce49074: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.544   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{f0d099d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.554   305  1133 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 08:53:45.554   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{de91e12: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.554   749  1332 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,07-27 08:53:45.554   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{75779e3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.554   749   873 D EntConnectivity: Not allowed due to - mEnabled false
,07-27 08:53:45.554   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{ff43fe0: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.564   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{db5a299: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.564   749  1332 D ConnectivityService: updateTcpDelayedAckSetting - WiFi setting
,07-27 08:53:45.564   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{937095e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.564   749  1332 D ConnectivityService: Setting TCP values: [1] which comes from [net.tcp.usercfg.wifi]
,07-27 08:53:45.564   749  1332 D ConnectivityService: Setting TCP values: [20] which comes from [net.tcp.delack.wifi]
,07-27 08:53:45.564   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{dfdd13f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.564   749  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.564   749  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.574   749  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.574   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{8d7a0c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.574   749  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.574   749  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:53:45.574  1379  1379 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:53:45.574  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:45.574   749  1332 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
07-27 08:53:45.574   749  1332 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,07-27 08:53:45.574   749  1332 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:53:45.574  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:45.574  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:45.574   749  2079 D ConnectivityService: getVpnConfig > userId : 0
,07-27 08:53:45.574  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:45.584   749  1332 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 08:53:45.584   749  1332 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/749 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.584   749  1332 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:53:45.584   749  1332 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,07-27 08:53:45.584   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.584   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.584   749  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.584   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:53:45.584   749  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:53:45.584   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.584   749  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.584   749   873 D EntConnectivity: Not allowed due to - mEnabled false
,07-27 08:53:45.584   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.584   749  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.584   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.584   749  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.584   749  1332 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-27 08:53:45.594   749  1332 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] validation  passed
,07-27 08:53:45.594   749  1332 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-27 08:53:45.594   749  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-27 08:53:45.594   749  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:53:45.594   749   749 D Tethering: Tethering got CONNECTIVITY_ACTION
,07-27 08:53:45.594   749   873 D Tethering: MasterInitialState.processMessage what=3
,07-27 08:53:45.594   749  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-27 08:53:45.594   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-27 08:53:45.594   749   749 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:45.594   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-27 08:53:45.594   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:45.594   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-27 08:53:45.594   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-27 08:53:45.594   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-27 08:53:45.594   749  1332 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:53:45.594   749  1332 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/749 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.594   749  1332 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:53:45.594   749  1332 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,07-27 08:53:45.594   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.594   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.594   749  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.594   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:53:45.594   749  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:53:45.594   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.594   749  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.604   749  1323 D NtpTrustedTime: forceRefresh() from cache miss
,07-27 08:53:45.604   305  1129 D EnterpriseController: netId is 0
07-27 08:53:45.604   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.604   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-27 08:53:45.604   749  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.604   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.604   749  1333 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-27 08:53:45.604   749  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.604   749  1332 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.604   749  1325 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.604   749  1325 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.604   749  1644 D NtpTrustedTime: forceRefresh() from cache miss
07-27 08:53:45.604   749  1325 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:53:45.604   749  1325 D WIFI_UT : evalRequest
07-27 08:53:45.604   749  1325 D WIFI_UT :   done
07-27 08:53:45.604  1682  1698 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-27 08:53:45.604  1682  1698 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-27 08:53:45.604   749  1325 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.604   749  1325 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.604   749  1325 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:53:45.604   749  1325 D WIFI    : evalRequest
07-27 08:53:45.604   749  1325 D WIFI    :   done
,07-27 08:53:45.604   749  1333 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-27 08:53:45.604   305  1129 D EnterpriseController: netId is 0
07-27 08:53:45.604   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-27 08:53:45.604   749  1324 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.604   749  1324 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.604   749  1324 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:53:45.604   749  1324 D WIFI_P2P: evalRequest
07-27 08:53:45.604   749  1324 D WIFI_P2P:   done
,07-27 08:53:45.604   749  1325 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.604   749  1325 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.604   749  1325 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:53:45.604   749  1325 D WIFI    : evalRequest
07-27 08:53:45.604   749  1325 D WIFI    :   done
,07-27 08:53:45.604   749   749 V MARsPolicyManager: DataConnection: true
,07-27 08:53:45.604   749  1353 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.604   749  1353 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-27 08:53:45.604   749  1353 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:53:45.604   749  1353 D Ethernet: evalRequest
07-27 08:53:45.614   749  1353 D Ethernet:   done
,07-27 08:53:45.614  1379  1379 D StatusBar.NetworkController: EthernetConnected: false
07-27 08:53:45.614  1379  1379 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 08:53:45.614  1379  1379 D StatusBar.NetworkController: updateDataNetType()
07-27 08:53:45.614  1379  1379 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,07-27 08:53:45.614   749  1332 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 08:53:45.614  2183  2183 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-27 08:53:45.614  4859  4859 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dd18689 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 (has extras) }
,07-27 08:53:45.624   749  1325 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
,07-27 08:53:45.624   749  1325 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,07-27 08:53:45.624  5802  5802 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-27 08:53:45.624   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{8b4cf55: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.624  6148  6148 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 08:53:45.624  1379  1379 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 08:53:45.624  1379  1379 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
,07-27 08:53:45.624  1379  1379 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-27 08:53:45.634  1379  1379 D StatusBar.NetworkController: EthernetConnected: false
07-27 08:53:45.634  1379  1379 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 08:53:45.634  1379  1379 D StatusBar.NetworkController: updateDataNetType()
07-27 08:53:45.634  1379  1379 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,07-27 08:53:45.634   749  1332 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,07-27 08:53:45.634   749  1332 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 08:53:45.634   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{ce65d6a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.634  1379  1379 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 08:53:45.634  1379  1379 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
07-27 08:53:45.634  1379  1379 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-27 08:53:45.634   749   749 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:45.634   749  1332 D ConnectivityService: identical MTU - not setting
,07-27 08:53:45.634   749  1332 V NetworkStats: updateIfacesLocked()
07-27 08:53:45.634   749  1332 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:53:45.634  4859  4859 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-27 08:53:45.634   749  1332 V NetworkStats: performPollLocked() took 2ms
,07-27 08:53:45.644   749  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-27 08:53:45.644  5802  5802 D BluetoothAdapter: STATE_ON
07-27 08:53:45.644   749  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-27 08:53:45.644   749  1332 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,07-27 08:53:45.644   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.644   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{888425b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.644   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.644  5802  5802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:53:45.644  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:45.644  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 08:53:45.644  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:53:45.644  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:53:45.644  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 08:53:45.644  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 08:53:45.644  5802  5802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 08:53:45.644   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.644   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:53:45.644   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:53:45.644  5802  5802 D BluetoothAdapter: STATE_ON
07-27 08:53:45.644   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.644   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.644   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.644   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.644   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.644  5802  5802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 08:53:45.644   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.644   749  1332 D ConnectivityService: Not required to send intent.
07-27 08:53:45.644   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{39e2af8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.644   749  1332 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:53:45.644   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.654   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.654   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.654   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:53:45.654   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{f400bd1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.654   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:53:45.654   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.654   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.654   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.654   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:45.654   749  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.654   749  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:45.654   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{684e636: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.654   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{87ea937: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.664   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{d06fea4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.664  1817  1817 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 08:53:45.664   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{468940d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.674   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{cb12fc2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.674   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{60aa1d3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.674   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{c076110: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.684   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{1176409: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.704   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{79a784b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.704  2335  2335 E audit   : type=1400 msg=audit(1469602425.704:289): avc:  denied  { ioctl } for  pid=3737 comm="ChromiumNet" path="socket:[35781]" dev="sockfs" ino=35781 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
07-27 08:53:45.704  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:45.714   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{f7958d4: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.724  2335  2335 E audit   : type=1300 msg=audit(1469602425.704:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=1b a1=8b1b a2=9a664468 a3=9a664460 items=0 ppid=349 ppcomm=main pid=3737 auid=4294967295 uid=10062 gid=10062 euid=10062 suid=10062 fsuid=10062 egid=10062 sgid=10062 fsgid=10062 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:53:45.724  2335  2335 E audit   : type=1327 msg=audit(1469602425.704:289): proctitle="com.google.android.googlequicksearchbox:search"
07-27 08:53:45.724  2335  2335 E audit   : type=1320 msg=audit(1469602425.704:289): 
,07-27 08:53:45.724   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{d7d2e40: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.724   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{7e46179: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.724   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e868ebe: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.734   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{3bcdb1f: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.734   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{b26ee6c: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.734  1379  1379 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-27 08:53:45.734  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:45.734  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:45.734  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:53:45.734  1379  1379 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:53:45.734   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{fc09c35: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.734   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{a98d8ca: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.744   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{b5e0a3b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.744   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{2ca8558: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.754   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{eebc6b1: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.754   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{ed3b796: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.754   749  1348 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,07-27 08:53:45.754   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{6190f17: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.764   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{e0e9f04: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.764   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{1c51ced: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.764   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{9d2236e: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.764  6090  6391 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
07-27 08:53:45.764  6090  6391 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:53:45.764  6090  6391 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:53:45.764  6090  6391 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:250)
,07-27 08:53:45.774   749  1414 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.MessageCompose newState = 1 callingPackage = 10163
,07-27 08:53:45.784   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a58ca0f u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97a4d07 1379:com.android.systemui/u0a59}
,07-27 08:53:45.784   749  2079 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.AccountShortcutPicker newState = 2 callingPackage = 10163
,07-27 08:53:45.794   749  1733 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.MailService newState = 2 callingPackage = 10163
,07-27 08:53:45.794   749  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.AttachmentDownloadService newState = 2 callingPackage = 10163
,07-27 08:53:45.794   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{751fca5: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.804   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{581087a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97a4d07 1379:com.android.systemui/u0a59}
,07-27 08:53:45.804   749  1712 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-27 08:53:45.804   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e1f82b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.814   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{a85ec07: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.824   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{581087a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
,07-27 08:53:45.834   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{d59d134: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
07-27 08:53:45.834  4631  4631 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 08:53:45.834  4631  4631 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 08:53:45.834   749   821 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:53:45.834   749   821 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:53:45.834   749  1740 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:53:45.834  4631  4631 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,07-27 08:53:45.834   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{742cd2: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.834   749   762 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:45.834  4631  4631 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,07-27 08:53:45.834  4631  4631 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
07-27 08:53:45.834  4631  4631 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 08:53:45.844   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{38b41a3: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.854   749  1323 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1469602425926 mCachedNtpElapsedRealtime : 93540 mCachedNtpCertainty : 53
,07-27 08:53:45.854   749  1644 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1469602425926 mCachedNtpElapsedRealtime : 93540 mCachedNtpCertainty : 53
07-27 08:53:45.854   749  1644 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:53:45.854   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{581087a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1bb3a0 6148:tv.peel.smartremote/u0a171}
,07-27 08:53:45.854   749  1644 D AlarmManager: setTime : 1469602425926 calling from uid: 1000 pid :749
,07-27 08:53:45.864   749  1348 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,07-27 08:53:45.874   749  1733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{75ccca0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
,07-27 08:53:45.874  1682  2472 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-27 08:53:45.874  1682  2472 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-27 08:53:45.874   749   821 D TelephonyManager: getDataEnabled: retVal=true
,07-27 08:53:45.884  6281  6359 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-27 08:53:45.884   749  1323 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:53:45.884   749  1323 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:45.884   749  1323 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
07-27 08:53:45.884   749  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:53:45.884   749  1323 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:53:45.884   749  1323 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:53:45.884   749  1323 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:53:45.884   749   826 I ActivityManager: Start proc 6399:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
07-27 08:53:45.884   749  1323 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:53:45.884   749  1323 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,07-27 08:53:45.884   749  1644 D AlarmManagerService: Setting time of day to sec=1469602425
,07-27 08:53:45.884  6399  6399 E Zygote  : v2
07-27 08:53:45.884  6399  6399 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:45.884  6399  6399 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:45.884   749  1644 D AlarmManagerService: Trying to open a file
,07-27 08:53:45.884   749  1644 E AlarmManagerService: File Open Failed
07-27 08:53:45.884   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{c9c1059: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.884  6399  6399 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:45.884  6399  6399 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:45.884  6399  6399 E Zygote  : accessInfo : 0
,07-27 08:53:45.926   749  1644 W AlarmManagerService: Unable to set rtc to 1469602425: Invalid argument
07-27 08:53:45.926   749  1235 V AlarmManager: Expired Alarm result :65536
,07-27 08:53:45.926   749  1644 V AlarmManager:  remove PendingIntent] PendingIntent{3e0e4: PendingIntentRecord{484694d android broadcastIntent}}
,07-27 08:53:45.936  1943  6396 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-27 08:53:45.936   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{c0654ff: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.936  1682  2006 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@93b3b77, selection=nullselectionArgs=null, sort=name ASC
,07-27 08:53:45.936  4631  4631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 08:53:45.936  1682  2006 D TelephonyProvider: query: match = 5
,07-27 08:53:45.936   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{8f45915: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.946   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{e6c842a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.956  6090  6233 D bt_upio : ..proc_btwrite_timeout..
07-27 08:53:45.956  6090  6233 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-27 08:53:45.956   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{75ccca0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5b3690 2384:com.samsung.android.providers.context/u0a175}
,07-27 08:53:45.956   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{6f5421b: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.966  6399  6399 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:45.966  6399  6399 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:45.966   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{c738fb8: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.966   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{75ccca0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
,07-27 08:53:45.966  1632  1632 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,07-27 08:53:45.976  4631  4631 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,07-27 08:53:45.976   749  1740 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{581087a u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cadef64 6399:com.sec.android.diagmonagent/1000}
,07-27 08:53:45.986  1682  2006 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,07-27 08:53:45.986   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{75ccca0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f630343 1887:com.sec.android.app.shealth:remote/u0a35}
,07-27 08:53:45.986   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{d9fd993: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:45.996  4631  4631 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-27 08:53:45.996  4631  4631 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,07-27 08:53:45.996  6399  6399 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package null
,07-27 08:53:45.996   749   821 E GpsLocationProvider: No APN found to select.
,07-27 08:53:45.996   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{e647bef: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.016   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{865c6fc: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.016   749  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{75ccca0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
,07-27 08:53:46.036  6399  6399 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm
,07-27 08:53:46.036   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:53:46.046   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{e59f9e7: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.046   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{61df994: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.046   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{9468c3d: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.066   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{5f27c32: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.066  4631  4631 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-27 08:53:46.066   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{ac24d83: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.076   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{314af39: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.076  6399  6399 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-27 08:53:46.086  4631  4631 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-27 08:53:46.086  4631  4631 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-27 08:53:46.086   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{cb14a18: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.086  4631  4631 E BluetoothHeadset: BTStateChangeCB is registed
,07-27 08:53:46.096  4631  4631 D BluetoothMap: Create BluetoothMap proxy object
,07-27 08:53:46.096   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{1d7fead: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.116   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{b22d8a9: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.116  4631  4631 D BluetoothSap: Create BluetoothSap proxy object
,07-27 08:53:46.146   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{f275665: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.156   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{ae147eb: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:46.156  1943  6395 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-27 08:53:46.156   749   821 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 37713, reason: UserStart, SyncResult: databaseError: true stats []
,07-27 08:53:46.166   749   821 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 124563, reason: UserStart
,07-27 08:53:46.176  4631  4631 D LocalBluetoothProfileManager: PANU : true
,07-27 08:53:46.176  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:53:46.176  4631  4631 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
07-27 08:53:46.176  4631  4631 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-27 08:53:46.176  4631  4631 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-27 08:53:46.186  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:53:46.186  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:53:46.186  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:53:46.186   749   762 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 08:53:46.196  4631  4631 D DockEventReceiver: finishStartingService: stopping service
,07-27 08:53:46.196  4631  4631 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 08:53:46.196  4631  4631 D BluetoothA2dp: Proxy object connected
,07-27 08:53:46.196  4631  4631 D A2dpProfile: Bluetooth service connected
,07-27 08:53:46.206   749  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{75ccca0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97a4d07 1379:com.android.systemui/u0a59}
,07-27 08:53:46.206  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 08:53:46.206  1379  1379 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:46.206  1379  1379 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-27 08:53:46.216  6090  6239 D A2dpStateMachine: getConnectedDevices : size=0
,07-27 08:53:46.216  4631  4631 D BluetoothMap: Proxy object connected
,07-27 08:53:46.216  4631  4631 D MapProfile: Bluetooth service connected
07-27 08:53:46.216  4631  4631 D BluetoothMap: getConnectedDevices()
,07-27 08:53:46.216   749  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{75ccca0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a6f808 6090:com.android.bluetooth/1002}
,07-27 08:53:46.216  6090  6090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc6893
,07-27 08:53:46.216  6090  6090 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 08:53:46.226  4631  4631 D BluetoothPbap: Proxy object connected
,07-27 08:53:46.236   749  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{75ccca0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78e7cb8 6281:com.google.android.apps.maps/u0a122}
,07-27 08:53:46.236  4631  4631 D PbapServerProfile: Bluetooth service connected
,07-27 08:53:46.236  4631  4631 D BluetoothSap: Proxy object connected
,07-27 08:53:46.236  4631  4631 D SapProfile: Bluetooth service connected
,07-27 08:53:46.236  4631  4631 D BluetoothInputDevice: Proxy object connected
,07-27 08:53:46.246  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:53:46.246  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:53:46.256  4631  4631 D HidProfile: Bluetooth service connected
,07-27 08:53:46.256  4631  4631 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 08:53:46.266  4631  4631 D PanProfile: Bluetooth service connected
,07-27 08:53:46.266  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 08:53:46.266  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:53:46.266  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 08:53:46.266  1632  4034 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:53:46.266  1632  4034 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:53:46.266  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:46.266  4631  4631 D HeadsetProfile: Bluetooth service connected
,07-27 08:53:46.296  6419  6419 E Zygote  : v2
07-27 08:53:46.296  6419  6419 I libpersona: KNOX_SDCARD checking this for 10164
07-27 08:53:46.296  6419  6419 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:46.296  6419  6419 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:46.296  6419  6419 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:46.296  6419  6419 E Zygote  : accessInfo : 0
07-27 08:53:46.296   749  1415 I ActivityManager: Start proc 6419:com.android.exchange/u0a164 for broadcast-3 com.android.exchange/.service.ExchangeBroadcastReceiver
07-27 08:53:46.296  6419  6419 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.exchange 
,07-27 08:53:46.306   749   759 I art     : Background partial concurrent mark sweep GC freed 78201(4MB) AllocSpace objects, 8(160KB) LOS objects, 27% free, 41MB/57MB, paused 3.507ms total 124.403ms
,07-27 08:53:46.326  6419  6419 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:46.326  6419  6419 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:46.336  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 08:53:46.336  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 08:53:46.336  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
07-27 08:53:46.336   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{912d153 u0 com.android.email.intent.action.CHANGE_LOGGING qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1fc9a90 6419:com.android.exchange/u0a164}
,07-27 08:53:46.336  6419  6419 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in com.android.exchange rsrc of package null
,07-27 08:53:46.346  6419  6419 W System  : ClassLoader referenced unknown path: /system/app/SecExchange/lib/arm
,07-27 08:53:46.356   749  1746 I ActivityManager: Killing 5413:com.sec.android.GeoLookout/u0a113 (adj 15): DHA:empty #37
,07-27 08:53:46.356  6399  6399 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,07-27 08:53:46.366  6399  6399 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
,07-27 08:53:46.366  6399  6399 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-27 08:53:46.366  6399  6399 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:53:46.366  6399  6399 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-27 08:53:46.366  6399  6399 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-27 08:53:46.376   749  2078 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
,07-27 08:53:46.386   749  1733 I ActivityManager: Start proc 6431:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,07-27 08:53:46.396  6431  6431 E Zygote  : v2
07-27 08:53:46.396  6431  6431 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:46.396  6431  6431 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:46.396  6431  6431 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:46.396  6431  6431 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:46.396  6431  6431 E Zygote  : accessInfo : 0
,07-27 08:53:46.416   749  1712 I ActivityManager: Killing 4974:com.google.android.gm/u0a114 (adj 15): DHA:empty #37
,07-27 08:53:46.416   749  1740 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:46.426  6431  6431 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:46.426  6431  6431 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:46.426   749  2079 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d18629a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cadef64 6399:com.sec.android.diagmonagent/1000}
,07-27 08:53:46.426  6399  6399 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-27 08:53:46.436  6399  6399 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:53:46.436  6399  6399 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-27 08:53:46.436  6399  6399 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-27 08:53:46.436   749  1567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{581087a u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98a0e66 6431:com.sec.knox.switcher/1000}
,07-27 08:53:46.446  6431  6431 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package null
,07-27 08:53:46.446   749  1746 I ActivityManager: Killing 4859:com.google.android.music:main/u0a126 (adj 15): DHA:empty #37
,07-27 08:53:46.446   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d18629a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97a4d07 1379:com.android.systemui/u0a59}
,07-27 08:53:46.456  6431  6431 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm
,07-27 08:53:46.466  6431  6431 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
,07-27 08:53:46.466  6431  6431 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,07-27 08:53:46.466  1943  6397 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10012, CallingPid : 1943
,07-27 08:53:46.466  4631  4631 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 08:53:46.466   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d18629a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
,07-27 08:53:46.466  4631  4631 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 08:53:46.466   749  1415 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/1943 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:46.466   749  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-27 08:53:46.466   749  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:53:46.466   749  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-27 08:53:46.466   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:46.466   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:46.466   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:46.466   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-27 08:53:46.476   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:46.476   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:53:46.476   749  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-27 08:53:46.476   749  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:46.476   749  1733 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,07-27 08:53:46.476  6431  6431 I usagelog: received in receiver
,07-27 08:53:46.476  6431  6431 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-27 08:53:46.486   749  1733 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,07-27 08:53:46.486  6431  6431 I KnoxUsageLogPro: premStatus:2
,07-27 08:53:46.496  6431  6431 I KnoxUsageLogPro: isEulaShown : false
07-27 08:53:46.496  6431  6431 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:53:46.496   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d18629a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98a0e66 6431:com.sec.knox.switcher/1000}
,07-27 08:53:46.496  6431  6431 I usagelog: received in receiver
07-27 08:53:46.496  6431  6431 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-27 08:53:46.496  6431  6431 I KnoxUsageLogPro: premStatus:2
,07-27 08:53:46.496  6431  6431 I KnoxUsageLogPro: isEulaShown : false
07-27 08:53:46.496  6431  6431 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:53:46.506  6446  6446 E Zygote  : v2
07-27 08:53:46.506  6446  6446 I libpersona: KNOX_SDCARD checking this for 10211
07-27 08:53:46.506  6446  6446 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:46.506  6446  6446 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:46.506  6446  6446 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:46.506   749   762 I ActivityManager: Start proc 6446:com.samsung.android.sm.policy/u0a211 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
07-27 08:53:46.506  6446  6446 E Zygote  : accessInfo : 0
,07-27 08:53:46.506  6446  6446 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-27 08:53:46.526   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d18629a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1bb3a0 6148:tv.peel.smartremote/u0a171}
,07-27 08:53:46.536   749  2078 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18aaf2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cadef64 6399:com.sec.android.diagmonagent/1000}
,07-27 08:53:46.536  6399  6399 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-27 08:53:46.536  6399  6399 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:53:46.536  6399  6399 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-27 08:53:46.536  6399  6399 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3634 
,07-27 08:53:46.536  6446  6446 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:46.536  6446  6446 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:46.546  6458  6458 E Zygote  : v2
07-27 08:53:46.546  6458  6458 I libpersona: KNOX_SDCARD checking this for 10082
07-27 08:53:46.546  6458  6458 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:46.556  6458  6458 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:46.556  6458  6458 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:46.556   749   821 I ActivityManager: Start proc 6458:com.google.android.apps.books/u0a82 for service com.google.android.apps.books/.service.SyncService
,07-27 08:53:46.556  6458  6458 E Zygote  : accessInfo : 0
07-27 08:53:46.556   749  1323 D NetworkPolicy: isUidForegroundLocked: 10082, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 08:53:46.556   749   762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18aaf2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97a4d07 1379:com.android.systemui/u0a59}
,07-27 08:53:46.566   749  1414 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{581087a u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{282843e 6446:com.samsung.android.sm.policy/u0a211}
,07-27 08:53:46.566  6458  6458 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.books 
,07-27 08:53:46.566   749  1567 I ActivityManager: Killing 5427:com.google.android.gms:car/u0a12 (adj 15): DHA:empty #37
,07-27 08:53:46.566  6446  6446 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package null
,07-27 08:53:46.576   749  1323 D NetworkPolicy: isUidForegroundLocked: 10082, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 08:53:46.576   749  2078 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-27 08:53:46.586   749  1740 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,07-27 08:53:46.586   749  1320 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,07-27 08:53:46.596   749  2079 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,07-27 08:53:46.596  6458  6458 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:46.596  6458  6458 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:46.606  6446  6446 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm
,07-27 08:53:46.606   749  2078 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
,07-27 08:53:46.606  1379  1379 D ViewRootImpl: #1 mView = android.widget.LinearLayout{9d46599 V.E...... ......I. 0,0-0,0 #10203a7 android:id/toast_layout_root}
,07-27 08:53:46.606   749  1733 D ISSUE_DEBUG: InputChannelName : a2d9fec Toast
,07-27 08:53:46.616   749  1733 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,07-27 08:53:46.616  4631  4631 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 08:53:46.616  4631  4631 I NearbySettings: MountReceiver.onReceive - Keep current state
07-27 08:53:46.616   749  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18aaf2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7519f30 4631:com.android.settings/1000}
,07-27 08:53:46.626   292   292 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,07-27 08:53:46.636  6458  6458 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in com.google.android.apps.books rsrc of package null
,07-27 08:53:46.636   749  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18aaf2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98a0e66 6431:com.sec.knox.switcher/1000}
,07-27 08:53:46.636  6431  6431 I usagelog: received in receiver
07-27 08:53:46.636  6431  6431 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-27 08:53:46.636  6431  6431 I KnoxUsageLogPro: premStatus:2
07-27 08:53:46.636  6431  6431 I KnoxUsageLogPro: isEulaShown : false
07-27 08:53:46.636  6431  6431 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:53:46.646  6458  6458 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,07-27 08:53:46.646   749  1740 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=749
,07-27 08:53:46.646   749  1713 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d18629a u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{282843e 6446:com.samsung.android.sm.policy/u0a211}
,07-27 08:53:46.656   749  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18aaf2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{282843e 6446:com.samsung.android.sm.policy/u0a211}
,07-27 08:53:46.666  1379  1379 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-27 08:53:46.676  6090  6158 D bt_vendor: op for 7
07-27 08:53:46.676  6090  6158 D bt_upio : upio_set : pio 0 action 1, polarity 1
07-27 08:53:46.676  6090  6158 D bt_upio : BT_WAKE is de-asserted already
,07-27 08:53:46.686  1379  1379 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-27 08:53:46.686   749  1712 V WindowStateAnimator: Finishing drawing window Window{a2d9fec u0 d0 Toast}: mDrawState=DRAW_PENDING
,07-27 08:53:46.696   749  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18aaf2 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1bb3a0 6148:tv.peel.smartremote/u0a171}
,07-27 08:53:46.696   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbea7a364
,07-27 08:53:46.716   749  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3415604 5802:com.test.thalitest/u0a4}
,07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:53:46.716   749  1320 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:46.726   749  2079 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{83a0580 749:system/1000}
,07-27 08:53:46.736   749  1415 I ActivityManager: Killing 5265:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): DHA:empty #37
,07-27 08:53:46.746   749   749 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2af4fb 1943:com.google.android.gms/u0a12}
,07-27 08:53:46.756   749  1740 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,07-27 08:53:46.776   749  1625 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.AccountsChangedReceiver newState = 2 callingPackage = 10012
,07-27 08:53:46.786   749  2078 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2af4fb 1943:com.google.android.gms/u0a12}
,07-27 08:53:46.796   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:53:46.796  1943  1943 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 08:53:46.806   749   762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2af4fb 1943:com.google.android.gms/u0a12}
,07-27 08:53:46.816  1943  2887 I iu.UploadsManager: num queued entries: 0
,07-27 08:53:46.816   749  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
,07-27 08:53:46.826  1943  2887 I iu.UploadsManager: num updated entries: 0
,07-27 08:53:46.826  1943  2887 I iu.SyncManager: NEXT; no task
,07-27 08:53:46.836   305  1129 D EnterpriseController: netId is 0
07-27 08:53:46.836   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,07-27 08:53:46.846   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{535d669 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cadef64 6399:com.sec.android.diagmonagent/1000}
,07-27 08:53:46.846  6399  6399 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,07-27 08:53:46.846  6399  6399 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:53:46.846  6399  6399 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-27 08:53:46.856  6399  6399 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(18/llllIIIllIlIIIIllllI)] timeToActivate is not set. Do not anything.
,07-27 08:53:46.856  6482  6482 E Zygote  : v2
,07-27 08:53:46.856  6482  6482 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:46.856   749   826 I ActivityManager: Start proc 6482:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
07-27 08:53:46.856  6482  6482 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:46.856  6482  6482 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:46.856  6482  6482 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:46.856  6482  6482 E Zygote  : accessInfo : 0
,07-27 08:53:46.866   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{d7678ee: PendingIntentRecord{c9a3355 com.google.android.gms broadcastIntent}}
,07-27 08:53:46.866   749  1323 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-27 08:53:46.866   749  1323 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-27 08:53:46.876  1943  6477 I MDM     : [232] SitrepService.onHandleIntent: sending sitrep: [0, 2, [tWT6n50_Aiv-zaAWuUFU2ysceqg], null]
07-27 08:53:46.876  1943  6477 W BaseAppContext: Using Auth Proxy for data requests.
07-27 08:53:46.876   749  2078 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:46.876  4902  6480 D PicasaService: start picasa sync
,07-27 08:53:46.886  6458  6458 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-27 08:53:46.886  4902  6480 D PicasaService: end picasa sync
,07-27 08:53:46.896  6458  6458 I BooksApp: Created application version: 3.7.75 (30775)
,07-27 08:53:46.906  6482  6482 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:46.906  6482  6482 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:46.916   749  1414 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cedc1c 6482:com.policydm/1000}
,07-27 08:53:46.916  6482  6482 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package null
,07-27 08:53:46.946   749  3343 D SSRM:n  : SIOP:: AP = 470, PST = 463, CUR = 300, LCD = 0
,07-27 08:53:46.956  6482  6482 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm
,07-27 08:53:46.956   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:47.036  1943  6397 W DriveInitializer: Awaiting to be initialized
,07-27 08:53:47.036  1943  6513 W DriveInitializer: Background init thread started
,07-27 08:53:47.056  1632  1646 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/android_device_manager
07-27 08:53:47.056  1632  1646 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:53:47.056  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:53:47.056  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:53:47.056  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:53:47.056  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:53:47.056  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:53:47.056  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:53:47.056  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:53:47.056  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:53:47.056  1632  1646 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:53:47.056  1632  1646 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:47.096  6482  6482 I FOTA    : [com.policydm.db.XDB(1493/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-27 08:53:47.106  6458  6512 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 08:53:47.136  1943  6477 E MDM     : [232] SitrepService.a: Error sending sitrep.
,07-27 08:53:47.166  1943  6513 W DriveInitializer: Background init thread ended
,07-27 08:53:47.236  6482  6482 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(54/<init>)] 
,07-27 08:53:47.236  6482  6482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:58 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:14 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:20 
,07-27 08:53:47.246  6529  6529 E Zygote  : v2
07-27 08:53:47.246  6529  6529 I libpersona: KNOX_SDCARD checking this for 10217
07-27 08:53:47.246  6529  6529 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:47.246   749  1746 I ActivityManager: Start proc 6529:com.samsung.aasaservice/u0a217 for service com.samsung.aasaservice/.AASAService
07-27 08:53:47.256  6529  6529 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:47.256  6529  6529 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:47.256  6529  6529 E Zygote  : accessInfo : 0
,07-27 08:53:47.256  6529  6529 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
07-27 08:53:47.256  6482  6482 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-27 08:53:47.276  6482  6482 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(236/llIIIIlllllIIllIIllI)] try read dbString
,07-27 08:53:47.286  6529  6529 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:47.286  6529  6529 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:47.286  6482  6482 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:53:47.296  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-27 08:53:47.296  6482  6482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.sec.android.policyagent.PolicyApplication.onCreate:61 android.app.Instrumentation.callApplicationOnCreate:1036 android.app.ActivityThread.handleBindApplication:6316 
,07-27 08:53:47.306  6529  6529 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,07-27 08:53:47.306  6482  6482 I DBG_POLICYDM: [com.sec.android.policyagent.PolicyApplication(64/onCreate)] PolicyApplication onCreated!
,07-27 08:53:47.306   749  1320 I ActivityManager: Killing 5726:com.google.android.partnersetup/u0a15 (adj 15): DHA:empty #37
,07-27 08:53:47.326  1632  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in com.google.android.gms rsrc of package null
,07-27 08:53:47.326  6482  6482 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:53:47.326  1632  6478 I GCM     : GCM config loaded
,07-27 08:53:47.336   749  1625 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,07-27 08:53:47.336  6529  6529 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,07-27 08:53:47.346  6482  6482 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:53:47.346  6529  6529 D AASAservice: onCreate()
,07-27 08:53:47.346  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-27 08:53:47.356  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(122/onCreate)] 
,07-27 08:53:47.356   749  1712 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:47.356  6482  6547 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-27 08:53:47.356   749  1713 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cedc1c 6482:com.policydm/1000}
,07-27 08:53:47.356  6482  6547 I DBG_POLICYDM: [com.policydm.XDMService(382/lllIlIlIIIllIIlIllIl)] a previous network is 0, current network is 2
,07-27 08:53:47.356  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(171/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,07-27 08:53:47.356  6482  6482 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-27 08:53:47.366  6482  6547 E DBG_POLICYDM: [com.policydm.XDMService(384/lllIlIlIIIllIIlIllIl)] network changed.... 
,07-27 08:53:47.366  6482  6547 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : true
,07-27 08:53:47.366  6482  6547 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(196/llIIIIlllllIIllIIllI)] DM Not Init
,07-27 08:53:47.376  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(515/IIIIllIlIIlIIIIlllIl)] 
,07-27 08:53:47.376  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(520/IIIIllIlIIlIIIIlllIl)] m_WakeLock is acquire!!
,07-27 08:53:47.376  6482  6547 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:53:47.376  6482  6482 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(126/IlIIIllllIIlIIIIIlII)] 
,07-27 08:53:47.376  6482  6549 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-27 08:53:47.386  6482  6549 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(191/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,07-27 08:53:47.386  6482  6549 I DBG_POLICYDM: [IIlIlIIIlIIlIlIIIIII(146/llIIIIlllllIIllIIllI)] nSync = 0
,07-27 08:53:47.386  6482  6547 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:53:47.386  6482  6547 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(316/llIIllllIIlllIIIIlll)] SPD SERVICE Stop!!
,07-27 08:53:47.386  6482  6547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1311 android.content.ContextWrapper.stopService:611 com.policydm.XDMBroadcastReceiver.llIIllllIIlllIIIIlll:317 com.policydm.XDMService.llllIIIllIlIIIIllllI:288 com.policydm.lllIlIlIIIllIIlIllIl.run:98 
,07-27 08:53:47.386  6482  6547 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : false
,07-27 08:53:47.386  6458  6543 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.google.android.apps.books/files/dictionaries/temp
,07-27 08:53:47.396  6482  6549 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-27 08:53:47.396  6482  6549 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(200/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,07-27 08:53:47.396   749  1746 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:47.396  6482  6549 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
07-27 08:53:47.396  6482  6549 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-27 08:53:47.396  6482  6482 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(160/IlIIIllllIIlIIIIIlII)] bExternalStorageAvailable [true]
,07-27 08:53:47.396  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(541/llllllIllIlIlllIIlIl)] 
,07-27 08:53:47.396  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(546/llllllIllIlIlllIIlIl)] m_WakeLock is release!!
,07-27 08:53:47.406  6482  6549 I DBG_POLICYDM: [com.policydm.ui.IllIIIIIIlIIlIIIlIII(49/llIIIIlllllIIllIIllI)] Indicator id : 7
,07-27 08:53:47.406  6482  6549 I DBG_POLICYDM: [com.policydm.XDMService(572/llllIIIllIlIIIIllllI)] set NotibarState : 7
,07-27 08:53:47.406  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
,07-27 08:53:47.406  6482  6549 I DBG_POLICYDM: [com.policydm.adapter.llllIIIllIlIIIIllllI(98/lllIlIlIIIllIIlIllIl)] 
,07-27 08:53:47.406  6482  6482 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,07-27 08:53:47.416  6482  6482 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:53:47.416  6482  6482 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
,07-27 08:53:47.436  6482  6482 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,07-27 08:53:47.436  6482  6482 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,07-27 08:53:47.436  6482  6482 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/08/03/11:26:08
,07-27 08:53:47.436  6482  6482 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-27 08:53:47.446  6482  6482 I DBG_POLICYDM: [com.policydm.XDMService(105/onDestroy)] 
,07-27 08:53:47.456  6553  6553 E Zygote  : v2
07-27 08:53:47.456  6553  6553 I libpersona: KNOX_SDCARD checking this for 10045
07-27 08:53:47.456  6553  6553 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:47.456  6553  6553 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:47.456  6553  6553 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:47.456  6553  6553 E Zygote  : accessInfo : 0
07-27 08:53:47.456  6553  6553 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
,07-27 08:53:47.456   749  1567 I ActivityManager: Start proc 6553:com.osp.app.signin/u0a45 for broadcast-5 com.osp.app.signin/.OspReceiver
,07-27 08:53:47.466   749  1567 I ActivityManager: Killing 5743:com.samsung.groupcast/u0a16 (adj 15): DHA:empty #37
,07-27 08:53:47.486  6553  6553 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:47.486  6482  6549 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
07-27 08:53:47.486  6553  6553 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:47.496   749  1415 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c9b9c77 6553:com.osp.app.signin/u0a45}
,07-27 08:53:47.506   749  1733 D ActivityManager: isAutoRunBlockedApp:: com.samsung.groupcast, Auto Run ON
,07-27 08:53:47.506  6553  6553 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in com.osp.app.signin rsrc of package null
,07-27 08:53:47.506  6482  6549 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:53:47.516  6482  6549 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(232/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,07-27 08:53:47.516  6482  6550 I DBG_POLICYDM: [llllIlIIIllllIIlIlll(208/llllIIIllIlIIIIllllI)] XUI_DM_IDLE_STATE :true
,07-27 08:53:47.516   749  1740 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:47.516  6482  6550 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-27 08:53:47.536  6482  6550 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-27 08:53:47.536  6482  6550 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/IIIlIIllIlIIllIlllII)] nSessionSaveState:0
,07-27 08:53:47.536  6482  6550 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/IIIlIIllIlIIllIlllII)] nNotiUiEvent:0
,07-27 08:53:47.536  6553  6553 W System  : ClassLoader referenced unknown path: /system/priv-app/Samsungservice2_xxhdpi/lib/arm
,07-27 08:53:47.536  6482  6550 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/IIIlIIllIlIIllIlllII)] nNotiRetryCount:0
,07-27 08:53:47.546  6482  6549 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(211/lllIlIlIIIllIIlIllIl)] 
,07-27 08:53:47.546  6482  6549 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/sepolicy
,07-27 08:53:47.546  6482  6549 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/seapp_contexts
07-27 08:53:47.546  6482  6550 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/IIIlIIllIlIIllIlllII)] Current NOTI NOT SAVED State. EXIT.
,07-27 08:53:47.556  6482  6550 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/IIIIlllIIIlIlIlllIII)] 
,07-27 08:53:47.556  1632  1645 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 08:53:47.556  1632  1645 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:53:47.556  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:53:47.556  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:53:47.556  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:53:47.556  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:53:47.556  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:53:47.556  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:53:47.556  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:53:47.556  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:53:47.556  1632  1645 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:53:47.556  1632  1645 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:47.556  6482  6549 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/property_contexts
,07-27 08:53:47.556  6482  6549 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/file_contexts
,07-27 08:53:47.556  6482  6549 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/service_contexts
,07-27 08:53:47.556  6482  6549 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/mac_permissions.xml
,07-27 08:53:47.566  6482  6550 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(39/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-27 08:53:47.566  6482  6550 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(453/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus : 0
,07-27 08:53:47.566   749  1415 I ActivityManager: Killing 5782:com.sec.android.app.myfiles/u0a51 (adj 15): DHA:empty #37
,07-27 08:53:47.576   749  2442 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-27 08:53:47.576   749  2442 V MARsPolicyManager: updateSMDBValues
,07-27 08:53:47.576   749   872 E MARsDBManager: updateDBAll : begin --size 1
,07-27 08:53:47.586  6482  6549 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(235/lllIlIlIIIllIIlIllIl)] Start resumecase for INIT
,07-27 08:53:47.586   749  1320 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.myfiles, Auto Run ON
,07-27 08:53:47.596  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 08:53:47.596  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:53:47.596  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:53:47.596  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:53:47.596  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:53:47.596  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:53:47.596  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:53:47.596  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:53:47.596  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:53:47.596  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:53:47.596  1632  4034 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:53:47.596  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:47.596   749  1625 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:47.606   749   872 E MARsDBManager: updateDBAll : end
07-27 08:53:47.606   749   872 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-27 08:53:47.606  6482  6549 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-27 08:53:47.606  6553  6553 I SA      : [SSP] onCreated
,07-27 08:53:47.616  6458  6568 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 08:53:47.616  6458  6512 E BooksSync: Soft error
07-27 08:53:47.616  6458  6512 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:53:47.616  6458  6512 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-27 08:53:47.616  6458  6512 E BooksSync: Sync error
07-27 08:53:47.616  6458  6512 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:53:47.616  6458  6512 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-27 08:53:47.616  6553  6553 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3e93891
,07-27 08:53:47.616  6482  6550 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(552/llllIIIllIlIIIIllllI)] Initiated Type: 0
,07-27 08:53:47.626  6458  6570 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-27 08:53:47.626  6458  6512 I BooksSync: Finished books sync
,07-27 08:53:47.636   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{2bf395a: PendingIntentRecord{5e964a3 com.android.bluetooth broadcastIntent}}
,07-27 08:53:47.646  6553  6553 I SA      : [TPM] There is no property file
,07-27 08:53:47.646  6553  6553 I SA      : [SCU] isHaveSA() - false
,07-27 08:53:47.656  6553  6553 I SA      : [TPM] getModelProperty : null
07-27 08:53:47.656  6553  6553 I SA      : [TPM] getCSCProperty : null
,07-27 08:53:47.656  6553  6553 I SA      : [DM] FLOATING AMOLED FEATURE: true
07-27 08:53:47.656  6553  6553 I SA      : [DM] PRODUCT AMOLED FEATURE: false
07-27 08:53:47.656  6553  6553 I SA      : [DM] TFT FEATURE: false
,07-27 08:53:47.656  6553  6553 I SA      : [DM] init START
,07-27 08:53:47.666  6458  6570 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-27 08:53:47.666  6482  6549 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:53:47.666  6482  6549 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:53:47.676  6482  6550 I DBG_POLICYDM: [com.policydm.db.XDB(1781/IIIlIIllIlIIllIlllII)] 
,07-27 08:53:47.686  6553  6553 I SA      : [DM] This device is not a Vodafone
,07-27 08:53:47.686  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-27 08:53:47.686  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:53:47.686  1632  4031 E Auth    : 	,at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:53:47.686  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:53:47.686  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:53:47.686  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:53:47.686  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:53:47.686  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:53:47.686  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:53:47.686  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:53:47.686  1632  4031 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:53:47.686  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:47.696   749   821 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37656, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:53:47.706  6458  6570 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: Failed to register token for device group
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:53:47.706  6458  6570 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:53:47.716   749   821 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 08:53:47.716   749   826 I ActivityManager: Start proc 6574:com.google.android.talk/u0a117 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,07-27 08:53:47.716  6574  6574 E Zygote  : v2
07-27 08:53:47.716  6574  6574 I libpersona: KNOX_SDCARD checking this for 10117
07-27 08:53:47.716  6574  6574 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:47.726  1632  6548 I GCM     : Ack for not saved message 32
,07-27 08:53:47.726  6574  6574 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 08:53:47.726  6574  6574 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:47.726  6574  6574 E Zygote  : accessInfo : 0
,07-27 08:53:47.726  6574  6574 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,07-27 08:53:47.726  6553  6553 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,07-27 08:53:47.726  6553  6553 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,07-27 08:53:47.726  6553  6553 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,07-27 08:53:47.726  6553  6553 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,07-27 08:53:47.736  6553  6553 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,07-27 08:53:47.736  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:53:47.736  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:53:47.736   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{1f37b14: PendingIntentRecord{bbec068 com.google.android.gms broadcastIntent}}
,07-27 08:53:47.746  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:53:47.746  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:53:47.746  6553  6553 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,07-27 08:53:47.746   749   761 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 08:53:47.756  6574  6574 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:47.756  6574  6574 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:47.766  6553  6553 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,07-27 08:53:47.766  6553  6553 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:53:47.766   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9a3afbd u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{36b99b2 6574:com.google.android.talk/u0a117}
,07-27 08:53:47.776  6553  6553 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:53:47.776  6553  6553 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
07-27 08:53:47.776  6553  6553 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,07-27 08:53:47.776  6553  6553 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
07-27 08:53:47.776  6553  6553 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
07-27 08:53:47.776  6553  6553 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,07-27 08:53:47.776  6553  6553 W ResourceType: Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
07-27 08:53:47.776  6553  6553 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,07-27 08:53:47.786  6574  6574 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-27 08:53:47.786  6553  6553 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:53:47.786  6553  6553 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,07-27 08:53:47.786  6553  6553 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
07-27 08:53:47.786  6553  6553 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
07-27 08:53:47.786  6553  6553 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,07-27 08:53:47.786  6553  6553 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,07-27 08:53:47.796  6553  6553 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,07-27 08:53:47.806  6553  6553 I SA      : [SCU] isHaveSA() - false
07-27 08:53:47.806  6553  6553 I SA      : support phone number id : false
07-27 08:53:47.806  6553  6553 I SA      : [DM] Supports Ref Jpn : true
07-27 08:53:47.806  6553  6553 I SA      : [DM] init END
,07-27 08:53:47.806  6553  6553 I SA      : [OR] onReceive log=[SA = 2.1.0300 V = 23 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = MMB29M M = SM-G900F OKLEFT false DIS MMB29M.G900FXXU1CPEM PSS = 5.219788042639568  ]
,07-27 08:53:47.806  6574  6574 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-27 08:53:47.806  6553  6553 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-27 08:53:47.806  6553  6553 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-27 08:53:47.806  6553  6553 I SA      : [SLFUCHKMGR] constructor called
,07-27 08:53:47.826  6553  6553 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-27 08:53:47.826  6553  6553 I SA      : [OR] == isSIMCardReady false ==
,07-27 08:53:47.826  6553  6553 I SA      : [SCU] == networkStateCheck == true
,07-27 08:53:47.826  6553  6553 I SA      : [DM] getCountryCodeFromCSC : DE
07-27 08:53:47.826  6553  6553 I SA      : isChinaCountryCode : false
07-27 08:53:47.826  6553  6553 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-27 08:53:47.826  6553  6553 I SA      : [OR] == networkStateCheck true ==
,07-27 08:53:47.846  6553  6553 I SA      : [OR] GetMyCountryZoneTask
,07-27 08:53:47.856  6553  6553 I SA      : [OR] onReceive END
,07-27 08:53:47.856   749  1713 I ActivityManager: Killing 5822:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): DHA:empty #37
,07-27 08:53:47.856   749  1713 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f50dd03 2183:com.sec.android.widgetapp.ap.hero.accuweather/u0a71}
,07-27 08:53:47.876  2183  2183 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-27 08:53:47.876  2183  2183 D accuweather: [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,07-27 08:53:47.886   749   761 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,07-27 08:53:47.886  2183  2183 D accuweather: [KK AccuPhone]>>> UIMEM:91 [0:0] getInstance
,07-27 08:53:47.886  2183  2183 D accuweather: [KK AccuPhone]>>> UIMEM:79 [0:0] UIManager : create ui manager
,07-27 08:53:47.886  6553  6588 I SA      : [SRS_HTTPURLCONNECTION] prepareGetMyCountryZone
,07-27 08:53:47.896  2183  2183 D accuweather: [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,07-27 08:53:47.896  2183  2183 D accuweather: [KK AccuPhone]>>> RM:136 [0:0]  V init 
,07-27 08:53:47.916  1516  1527 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 08:53:47.916  2183  2183 D accuweather: [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,07-27 08:53:47.926  6482  6550 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-27 08:53:47.926  1516  1530 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 08:53:47.936  2183  2183 D accuweather: [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,07-27 08:53:47.936  1516  1631 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 08:53:47.946  6553  6588 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-27 08:53:47.946  2183  2183 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,07-27 08:53:47.956  2183  2183 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,07-27 08:53:47.956  6553  6588 I SA      : [SSP] query invoked
,07-27 08:53:47.956  6553  6588 I SA      : [TPMU] GetMccFromDB : null
,07-27 08:53:47.956  6553  6588 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-27 08:53:47.966   749  1567 I ActivityManager: Start proc 6591:com.sec.android.cloudagent/u0a2 for broadcast-5 com.sec.android.cloudagent/.detector.DetectorReceiver
,07-27 08:53:47.966  6591  6591 E Zygote  : v2
07-27 08:53:47.966  6591  6591 I libpersona: KNOX_SDCARD checking this for 10002
07-27 08:53:47.966  6591  6591 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:47.966  6591  6591 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:47.966  6591  6591 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:47.966  6591  6591 E Zygote  : accessInfo : 0
,07-27 08:53:47.966  6591  6591 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.cloudagent 
,07-27 08:53:47.966  6553  6588 I SA      : [LBE] isSupportCheckDomainRegion : true
,07-27 08:53:47.966  6553  6588 I SA      : [TPM] isNoProxy(default) : true
,07-27 08:53:47.966  6574  6574 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-27 08:53:47.976  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 08:53:47.976  5802  5937 I jxcore-log: 
,07-27 08:53:47.996  6482  6550 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(37/llllIIIllIlIIIIllllI)] Noti Exist : false
,07-27 08:53:47.996  6553  6588 E File    : fail readDirectory() errno=2
,07-27 08:53:48.006  6591  6591 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:48.006  6591  6591 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:48.016   749  1713 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c173480 6591:com.sec.android.cloudagent/u0a2}
,07-27 08:53:48.016  6591  6591 W ResourcesManager: getTopLevelResources: /system/priv-app/CloudAgent/CloudAgent.apk / 1.0 running in com.sec.android.cloudagent rsrc of package null
,07-27 08:53:48.026  6591  6591 W System  : ClassLoader referenced unknown path: /system/priv-app/CloudAgent/lib/arm
,07-27 08:53:48.066  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:53:48.066  1632  2978 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: androidmarket
07-27 08:53:48.066  1632  2978 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:53:48.066  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 08:53:48.066  1632  2978 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:53:48.066  1632  2978 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:53:48.066  1632  2978 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:48.086   749   759 I art     : Background partial concurrent mark sweep GC freed 40715(2MB) AllocSpace objects, 13(260KB) LOS objects, 27% free, 41MB/57MB, paused 1.970ms total 142.976ms
,07-27 08:53:48.096  6458  6570 W InstanceID/Rpc: Found 10012
,07-27 08:53:48.106  6458  6458 W PlayCommon: [1] 2.onErrorResponse: Failed to read experiments from backend: User needs to (re)enter credentials. 
,07-27 08:53:48.106   749  1414 I ActivityManager: Killing 5853:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #37
,07-27 08:53:48.136  6605  6605 E Zygote  : v2
07-27 08:53:48.136  6605  6605 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:48.136  6605  6605 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:48.136  6605  6605 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:48.136  6605  6605 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:53:48.136   749  1625 I ActivityManager: Start proc 6605:com.wssyncmldm/1000 for broadcast-5 com.wssyncmldm/com.samsung.android.app.fotaclient.NetworkReceiver
,07-27 08:53:48.136  6605  6605 E Zygote  : accessInfo : 0
,07-27 08:53:48.136   749  1625 I ActivityManager: Killing 5007:com.android.mms/u0a50 (adj 15): DHA:empty #37
,07-27 08:53:48.146   749  1713 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,07-27 08:53:48.156   749  2079 D CountryDetector: No listener is left
,07-27 08:53:48.156   749  1712 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
,07-27 08:53:48.166  6605  6605 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:48.166  6605  6605 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:48.176   749  1625 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5571398 6605:com.wssyncmldm/1000}
,07-27 08:53:48.196  6605  6605 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package null
,07-27 08:53:48.206  6605  6605 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm
,07-27 08:53:48.216  6574  6618 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,07-27 08:53:48.216  6574  6618 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-27 08:53:48.246  6574  6574 I Babel_telephony: TeleModule.onApplicationCreate
,07-27 08:53:48.246  6605  6605 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,07-27 08:53:48.266  6574  6626 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-27 08:53:48.266  6574  6626 I Babel_SMS: MmsConfig.loadMmsSettings
,07-27 08:53:48.266  6574  6626 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
,07-27 08:53:48.266  6574  6626 I Babel_SMS: MmsConfig.loadFromDatabase
,07-27 08:53:48.286  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:53:48.296  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 08:53:48.296  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-27 08:53:48.296  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
07-27 08:53:48.296  1632  4034 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:53:48.296  1632  4034 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:53:48.296  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:48.326  1632  4034 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
07-27 08:53:48.326  1632  4034 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
07-27 08:53:48.326  1632  4034 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-27 08:53:48.326  1632  4034 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
07-27 08:53:48.326  1632  4034 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:53:48.326  1632  4034 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:53:48.326  1632  4034 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:48.326  6458  6589 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:53:48.326  6458  6589 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-27 08:53:48.326  6458  6589 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
07-27 08:53:48.326  6458  6589 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
07-27 08:53:48.326  6458  6589 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
07-27 08:53:48.326  6458  6589 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-27 08:53:48.326  6458  6589 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:48.326  6458  6589 W PlayEventLogger: deferring log upload because couldn't retrieve auth token
,07-27 08:53:48.336  6605  6605 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2021/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-27 08:53:48.356  6574  6574 I Babel_Crash: Startup - clean
,07-27 08:53:48.356  6574  6626 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-27 08:53:48.356  6574  6626 I Babel_SMS: MmsConfig.loadFromResources
,07-27 08:53:48.356  6574  6626 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-27 08:53:48.356  6574  6626 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
,07-27 08:53:48.366   749  1740 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10117
,07-27 08:53:48.366   749  1625 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10117
,07-27 08:53:48.376   749  1746 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10117
,07-27 08:53:48.376   749  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10117
,07-27 08:53:48.376   749  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10117
,07-27 08:53:48.426  6605  6605 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(271/llIlIIIIlIIIIIlIlIII)] Voice : true
,07-27 08:53:48.426  6605  6605 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(272/llIlIIIIlIIIIIlIlIII)] SMS : true
,07-27 08:53:48.426  6605  6605 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,07-27 08:53:48.436   749  2078 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a4c04dc u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
,07-27 08:53:48.446  6605  6605 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3216/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-27 08:53:48.446   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{a0149e5: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:53:48.456  6605  6605 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3268/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,07-27 08:53:48.476  6574  6574 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,07-27 08:53:48.476  6605  6605 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
,07-27 08:53:48.476  6574  6574 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-27 08:53:48.496   749  2079 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ffac95b 4313:com.sec.spp.push/u0a38}
,07-27 08:53:48.506  6605  6637 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:53:48.506  4313  4313 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
07-27 08:53:48.506  4313  4313 E SPPClientService: [SystemStateMoniter] Current Time : 96158
,07-27 08:53:48.516  6574  6574 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm
,07-27 08:53:48.516  4313  4313 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-27 08:53:48.526   749  1415 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31a0ddb 2585:android.process.media/u0a47}
,07-27 08:53:48.526  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 08:53:48.526  5802  5937 I jxcore-log: 
07-27 08:53:48.526  2585  2585 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:53:48.536   749  1713 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{684f26b 3085:com.android.contacts/u0a20}
,07-27 08:53:48.546   749  1747 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,07-27 08:53:48.546  6639  6639 E Zygote  : v2
07-27 08:53:48.546  6639  6639 I libpersona: KNOX_SDCARD checking this for 10207
07-27 08:53:48.546  6639  6639 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:48.546  6639  6639 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:48.546  6639  6639 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:48.546   749  2079 I ActivityManager: Start proc 6639:com.google.android.apps.photos/u0a207 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
07-27 08:53:48.556  6639  6639 E Zygote  : accessInfo : 0
07-27 08:53:48.556  6639  6639 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,07-27 08:53:48.556  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 08:53:48.556  5802  5937 I jxcore-log: 
,07-27 08:53:48.556  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 08:53:48.556  5802  5937 I jxcore-log: 
,07-27 08:53:48.586  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 08:53:48.586  5802  5937 I jxcore-log: 
,07-27 08:53:48.586  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 08:53:48.586  5802  5937 I jxcore-log: 
,07-27 08:53:48.586  6639  6639 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:48.586  6639  6639 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:48.596   749  1625 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d48cf47 6639:com.google.android.apps.photos/u0a207}
,07-27 08:53:48.606  6639  6639 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package null
,07-27 08:53:48.626  6639  6639 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-27 08:53:48.636  6574  6574 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-27 08:53:48.666  6574  6574 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:53:48.686   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{4b918e3: PendingIntentRecord{83343c2 com.google.android.talk startService}}
,07-27 08:53:48.696   749  1712 I ActivityManager: Killing 5887:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #37
,07-27 08:53:48.706   749  1320 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,07-27 08:53:48.706  6574  6651 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,07-27 08:53:48.876  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.talk, Service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
07-27 08:53:48.876  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:53:48.876  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:53:48.876  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:53:48.876  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:53:48.876  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:53:48.876  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:53:48.876  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:53:48.876  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:53:48.876  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:53:48.876  1632  4031 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:53:48.876  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:48.896  6574  6652 E Babel   : UserRecoverableAuthException.
,07-27 08:53:48.896  6574  6652 E Babel   : fgm: BadAuthentication
07-27 08:53:48.896  6574  6652 E Babel   : 	at fgk.b(Unknown Source)
07-27 08:53:48.896  6574  6652 E Babel   : 	at fgk.a(Unknown Source)
07-27 08:53:48.896  6574  6652 E Babel   : 	at fgk.b(Unknown Source)
07-27 08:53:48.896  6574  6652 E Babel   : 	at aal.a(SourceFile:53309)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cvn.a(SourceFile:3101)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cvn.a(SourceFile:1145)
07-27 08:53:48.896  6574  6652 E Babel   : 	at dth.a(SourceFile:4331)
07-27 08:53:48.896  6574  6652 E Babel   : 	at dth.a(SourceFile:1415)
07-27 08:53:48.896  6574  6652 E Babel   : 	at dpf.a(SourceFile:480)
07-27 08:53:48.896  6574  6652 E Babel   : 	at dpf.a(SourceFile:2453)
07-27 08:53:48.896  6574  6652 E Babel   : 	at doo.a(SourceFile:4068)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cwf.b(SourceFile:131)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cwb.f(SourceFile:328)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cwc.run(SourceFile:78)
,07-27 08:53:48.896  6574  6652 E Babel   : Error getting auth token
,07-27 08:53:48.896  6574  6652 E Babel   : ewy
07-27 08:53:48.896  6574  6652 E Babel   : 	at aal.a(SourceFile:53318)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cvn.a(SourceFile:3101)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cvn.a(SourceFile:1145)
07-27 08:53:48.896  6574  6652 E Babel   : 	at dth.a(SourceFile:4331)
07-27 08:53:48.896  6574  6652 E Babel   : 	at dth.a(SourceFile:1415)
07-27 08:53:48.896  6574  6652 E Babel   : 	at dpf.a(SourceFile:480)
07-27 08:53:48.896  6574  6652 E Babel   : 	at dpf.a(SourceFile:2453)
07-27 08:53:48.896  6574  6652 E Babel   : 	at doo.a(SourceFile:4068)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cwf.b(SourceFile:131)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cwb.f(SourceFile:328)
07-27 08:53:48.896  6574  6652 E Babel   : 	at cwc.run(SourceFile:78)
,07-27 08:53:48.916  6574  6658 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:53:48.916  6574  6658 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:53:48.916  6574  6652 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
07-27 08:53:48.916  6574  6652 I art     : Note: end time exceeds epoch: 
,07-27 08:53:48.916   305  1129 D EnterpriseController: netId is 0
07-27 08:53:48.916   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 10117
,07-27 08:53:48.936  1632  1646 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.talk, Service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
07-27 08:53:48.936  1632  1646 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:53:48.936  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:53:48.936  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:53:48.936  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:53:48.936  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:53:48.936  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:53:48.936  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:53:48.936  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:53:48.936  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:53:48.936  1632  1646 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:53:48.936  1632  1646 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:53:48.956  6574  6635 E Babel   : Unexpected exception while authenticating.
,07-27 08:53:48.956  6574  6635 E Babel   : fgj: User intervention required. Notification has been pushed.
07-27 08:53:48.956  6574  6635 E Babel   : 	at fgk.c(Unknown Source)
07-27 08:53:48.956  6574  6635 E Babel   : 	at fgk.c(Unknown Source)
07-27 08:53:48.956  6574  6635 E Babel   : 	at aal.a(SourceFile:53307)
07-27 08:53:48.956  6574  6635 E Babel   : 	at cvn.b(SourceFile:1160)
07-27 08:53:48.956  6574  6635 E Babel   : 	at dzi.run(SourceFile:5324)
07-27 08:53:48.956  6574  6635 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:53:48.956  6574  6635 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:53:48.956  6574  6635 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,07-27 08:53:48.985   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:49.096  6639  6639 W Primes  : Memory instrumentations are turned off.
,07-27 08:53:49.106  6639  6639 W Primes  : Timer instrumentations are turned off.
,07-27 08:53:49.106  6639  6639 W Primes  : Crash monitoring is turned off.
,07-27 08:53:49.106  6639  6639 W Primes  : Network monitoring is turned off.
07-27 08:53:49.106  6639  6639 W Primes  : Package metrics are turned off by default
,07-27 08:53:49.146   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fe0b10e u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d48cf47 6639:com.google.android.apps.photos/u0a207}
,07-27 08:53:49.156   749   761 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d48cf47 6639:com.google.android.apps.photos/u0a207}
,07-27 08:53:49.176   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{863213c u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d48cf47 6639:com.google.android.apps.photos/u0a207}
,07-27 08:53:49.206  6673  6673 E Zygote  : v2
07-27 08:53:49.206  6673  6673 I libpersona: KNOX_SDCARD checking this for 10128
07-27 08:53:49.206  6673  6673 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:49.206  6673  6673 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:49.206  6673  6673 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:49.206   749  2078 I ActivityManager: Start proc 6673:com.google.android.apps.magazines/u0a128 for broadcast-5 com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
07-27 08:53:49.216  6673  6673 E Zygote  : accessInfo : 0
07-27 08:53:49.216  6673  6673 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.magazines 
,07-27 08:53:49.246  6673  6673 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:49.246  6673  6673 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:49.246   749  1625 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1df1528 6673:com.google.android.apps.magazines/u0a128}
,07-27 08:53:49.256   749  1747 I ActivityManager: Killing 5903:com.google.android.apps.docs/u0a98 (adj 15): DHA:empty #37
,07-27 08:53:49.256  6673  6673 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.google.android.apps.magazines rsrc of package null
,07-27 08:53:49.276  6292  6292 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:53:49.286   749  1746 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,07-27 08:53:49.286  6673  6673 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-27 08:53:49.286   305  1126 D Netd    : Iface wlan0 link up
,07-27 08:53:49.296  6111  6111 I wpa_supplicant: nl80211: Received scan results (31 BSSes)
,07-27 08:53:49.296   749   832 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:53:49.296   749   832 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:53:49.296   749  1324 D WifiP2pService: InactiveState{ what=147461 }
,07-27 08:53:49.296   749  1324 D WifiP2pService: P2pEnabledState{ what=147461 }
07-27 08:53:49.296   749  1324 D WifiP2pService: DefaultState{ what=147461 }
,07-27 08:53:49.316   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95e6241 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97a4d07 1379:com.android.systemui/u0a59}
,07-27 08:53:49.356  6673  6673 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 08:53:49.356  6673  6673 I MultiDex: install
07-27 08:53:49.356  6673  6673 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:53:49.356  6574  6658 I Babel   : connection state changed from UNKNOWN to CONNECTED
,07-27 08:53:49.366  6553  6588 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-27 08:53:49.396  6553  6588 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-27 08:53:49.396  6553  6588 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:53:49.396  6553  6588 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:53:49.396   305  1129 D EnterpriseController: netId is 0
07-27 08:53:49.396   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 10045
,07-27 08:53:49.476  6673  6673 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-27 08:53:49.476  6673  6673 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 08:53:49.476  6673  6673 I GAv4    :   adb logcat -s GAv4
,07-27 08:53:49.486  6673  6673 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.google.android.apps.magazines rsrc of package null
,07-27 08:53:49.486   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{aab4872: PendingIntentRecord{52cc4c3 com.google.android.apps.magazines broadcastIntent}}
,07-27 08:53:49.486  6673  6673 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:53:49.486  6673  6673 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:53:49.496  6673  6697 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:53:49.646  6673  6673 I NSApplication: Starting up...
,07-27 08:53:49.666   749  1567 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2844273 5368:com.google.android.apps.plus/u0a135}
,07-27 08:53:49.756   749  1712 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{885e3a5 6294:com.android.email/u0a163}
,07-27 08:53:49.766   749   762 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:49.786   749  1320 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:49.786   749   761 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:49.796   749  1625 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1bb3a0 6148:tv.peel.smartremote/u0a171}
,07-27 08:53:49.826  6730  6730 E Zygote  : v2
07-27 08:53:49.826  6730  6730 I libpersona: KNOX_SDCARD checking this for 10178
07-27 08:53:49.826  6730  6730 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:53:49.826  6730  6730 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:49.826  6730  6730 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:53:49.826   749  1747 I ActivityManager: Start proc 6730:com.samsung.android.service.travel/u0a178 for broadcast-5 com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver
07-27 08:53:49.826  6730  6730 E Zygote  : accessInfo : 0
07-27 08:53:49.826   749  1747 I ActivityManager: Killing 5943:com.sec.android.automotive.drivelink/u0a99 (adj 15): DHA:empty #37
07-27 08:53:49.826  6730  6730 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.samsung.android.service.travel 
,07-27 08:53:49.836  6148  6165 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-27 08:53:49.836  6148  6165 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-27 08:53:49.846   749  1713 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.automotive.drivelink, Auto Run ON
,07-27 08:53:49.856  6148  6165 I System.out: Thread-856(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-27 08:53:49.856  6148  6165 I System.out: Thread-856(ApacheHTTPLog):isSBSettingEnabled false
,07-27 08:53:49.856  6148  6165 I System.out: Thread-856(ApacheHTTPLog):isShipBuild true
07-27 08:53:49.856  6148  6165 I System.out: Thread-856(ApacheHTTPLog):getDebugLevel 0x4f4c
07-27 08:53:49.856  6730  6730 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:49.856  6730  6730 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:49.856  6148  6165 I System.out: Thread-856(ApacheHTTPLog):Smart Bonding Setting is false
07-27 08:53:49.856  6148  6165 I System.out: Thread-856(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-27 08:53:49.856   305  1129 D EnterpriseController: netId is 0
07-27 08:53:49.856   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 10171
,07-27 08:53:49.866   749  2078 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2fc637a 6730:com.samsung.android.service.travel/u0a178}
,07-27 08:53:49.866  6730  6730 W ResourcesManager: getTopLevelResources: /system/app/TravelService_K/TravelService_K.apk / 1.0 running in com.samsung.android.service.travel rsrc of package null
,07-27 08:53:49.896  6730  6730 W System  : ClassLoader referenced unknown path: /system/app/TravelService_K/lib/arm
,07-27 08:53:49.896   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{621b72b: PendingIntentRecord{86c4788 com.samsung.android.service.travel broadcastIntent}}
,07-27 08:53:49.906   749  1625 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f389bb u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ecc57d 6045:com.sec.android.app.samsungapps/u0a40}
,07-27 08:53:49.926  6045  6045 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-27 08:53:50.056  6045  6045 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-27 08:53:50.056  6045  6045 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-27 08:53:50.056  6045  6045 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-27 08:53:50.056  6045  6045 D InitializeManagerStateMachine: exit::IDLE
07-27 08:53:50.056  6045  6045 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-27 08:53:50.056   749  1713 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:53:50.056   749  1625 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:50.056  6045  6045 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-27 08:53:50.056  6045  6045 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-27 08:53:50.056  6045  6045 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-27 08:53:50.056  6045  6045 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-27 08:53:50.056  6045  6045 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-27 08:53:50.056  6045  6045 D InitializeManagerStateMachine: entry::SUCCESS
07-27 08:53:50.056  6045  6045 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-27 08:53:50.066  6045  6045 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,07-27 08:53:50.066  6045  6045 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-27 08:53:50.066  6045  6045 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,07-27 08:53:50.066   749  1746 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:50.066  6045  6045 D InitializeManagerStateMachine: exit::SUCCESS
07-27 08:53:50.066  6045  6045 D InitializeManagerStateMachine: entry::IDLE
,07-27 08:53:50.066   749  2079 I ActivityManager: Killing 5963:com.vlingo.midas/u0a33 (adj 15): DHA:empty #37
,07-27 08:53:50.086   749  2078 D ActivityManager: isAutoRunBlockedApp:: com.vlingo.midas, Auto Run ON
,07-27 08:53:50.106  1379  1379 D ViewRootImpl: #3 mView = null
,07-27 08:53:50.116   292   361 I SurfaceFlinger: id=15 Removed Uoast (8/9)
,07-27 08:53:50.116   292  1295 I SurfaceFlinger: id=15 Removed Uoast (-2/9)
,07-27 08:53:50.116   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbea7a3a4
,07-27 08:53:50.116   749  1747 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 749) eventTime = 97774
,07-27 08:53:50.116   749  1747 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=749 (0x0)
,07-27 08:53:50.126   749  1747 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=749, ws=WorkSource{10059}) (elapsedTime=3472)
,07-27 08:53:50.256  6553  6588 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 866
,07-27 08:53:50.266  6553  6588 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,07-27 08:53:50.266  6553  6588 I SA      : [OCP] update openData : PL
,07-27 08:53:50.266  6553  6588 I SA      : [TPMU] getNetworkMcc : 
,07-27 08:53:50.276  6553  6588 I SA      : [SCU] saveMccToPreferece Start
,07-27 08:53:50.276  6553  6588 I SA      : [SCU] RegionMCC : 260
07-27 08:53:50.276  6553  6588 I SA      : [SSP] query invoked
,07-27 08:53:50.276  6553  6588 I SA      : [TPMU] GetMccFromDB : null
,07-27 08:53:50.276  6553  6588 I SA      : [SCU] getMccFromPreferece mcc = 260
07-27 08:53:50.276  6553  6588 I SA      : [SCU] saveMccToPreferece End
,07-27 08:53:50.276  6553  6588 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 909
07-27 08:53:50.276  6553  6588 I SA_HTTPURLCONNECTION: [RC New] Execute end
,07-27 08:53:50.276  6553  6553 I SA      : [OR] GetMyCountryZoneTask mcc = 260
07-27 08:53:50.276  6553  6553 I SA      : [OR] GetMyCountryZoneTask Success
,07-27 08:53:50.716  6148  6165 I System.out: tr calls detatch()
,07-27 08:53:50.906  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 08:53:50.906  5802  5937 I jxcore-log: 
,07-27 08:53:50.916  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 08:53:50.916  5802  5937 I jxcore-log: 
,07-27 08:53:50.926  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 08:53:50.926  5802  5937 I jxcore-log: 
,07-27 08:53:51.046   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:53:51.086  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 08:53:51.086  5802  5937 I jxcore-log: 
,07-27 08:53:51.905  6458  6492 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:53:51.925  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 08:53:51.925  5802  5937 I jxcore-log: 
,07-27 08:53:51.985  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 08:53:51.985  5802  5937 I jxcore-log: 
,07-27 08:53:51.995  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 08:53:51.995  5802  5937 I jxcore-log: 
,07-27 08:53:52.195  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 08:53:52.195  5802  5937 I jxcore-log: 
,07-27 08:53:52.215  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 08:53:52.215  5802  5937 I jxcore-log: 
,07-27 08:53:52.215  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 08:53:52.215  5802  5937 I jxcore-log: 
,07-27 08:53:52.225  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 08:53:52.225  5802  5937 I jxcore-log: 
,07-27 08:53:52.235  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 08:53:52.235  5802  5937 I jxcore-log: 
,07-27 08:53:52.255  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 08:53:52.255  5802  5937 I jxcore-log: 
,07-27 08:53:52.345  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 08:53:52.345  5802  5937 I jxcore-log: 
,07-27 08:53:52.355  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 08:53:52.355  5802  5937 I jxcore-log: 
,07-27 08:53:52.385  5802  5937 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 08:53:52.385  5802  5937 I jxcore-log: 
,07-27 08:53:52.395  5802  5937 D BluetoothAdapter: STATE_ON
,07-27 08:53:52.395  5802  5937 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-27 08:53:52.395  5802  5937 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-27 08:53:52.395  5802  5937 I jxcore-log: 
,07-27 08:53:52.445  5802  5937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 08:53:52.445  5802  5937 I jxcore-log: 
,07-27 08:53:52.445  5802  5937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 08:53:52.445  5802  5937 I jxcore-log: 
,07-27 08:53:52.445  5802  5937 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 08:53:52.445  5802  5937 I jxcore-log: 
,07-27 08:53:53.275  6292  6292 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:53:53.525   749  1332 D ConnectivityService: handlePromptUnvalidated 502
,07-27 08:53:53.615   749  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:53:53.615   749  1625 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4333, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:53:53.625   749  1625 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:53:53.625   749  1625 D BatteryService: stay LED for charging
,07-27 08:53:53.625   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:53:53.635   749   749 I MotionRecognitionService: Plugged
,07-27 08:53:53.635   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:53:53.635   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:53:53.635   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:53:53.645  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:53:53.645  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:53:53.645  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:53:53.685  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:53:53.685  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:53:53.685  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:53:53.695  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:53:53.695  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:53:53.955  6574  6574 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,07-27 08:53:53.985   749  1414 I ActivityManager: Killing 5977:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #37
,07-27 08:53:54.055   749  1320 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,07-27 08:53:54.535   749  3348 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-27 08:53:54.595   749  3348 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,07-27 08:53:54.595   749  3348 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-27 08:53:54.595   749  3348 I System.out: Thread-175(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-27 08:53:54.595   749  3348 I System.out: Thread-175(ApacheHTTPLog):isSBSettingEnabled false
,07-27 08:53:54.605   749  3348 I System.out: Thread-175(ApacheHTTPLog):isShipBuild true
,07-27 08:53:54.605   749  3348 I System.out: Thread-175(ApacheHTTPLog):getDebugLevel 0x4f4c
,07-27 08:53:54.605   749  3348 I System.out: Thread-175(ApacheHTTPLog):Smart Bonding Setting is false
07-27 08:53:54.605   749  3348 I System.out: Thread-175(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-27 08:53:54.605   305  1129 D EnterpriseController: netId is 0
07-27 08:53:54.605   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-27 08:53:55.065   749  3348 I System.out: Category Thread calls detatch()
,07-27 08:53:56.045   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:53:56.925   749  1323 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-27 08:53:56.935   749  1323 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-27 08:53:57.005   749  3343 D SSRM:n  : SIOP:: AP = 440, PST = 462, CUR = 300, LCD = 0
,07-27 08:53:57.015   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:57.275  6292  6292 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:53:57.275  6292  6292 I dhcpcd  : wlan0: no IPv6 Routers available
,07-27 08:53:57.715  3385  3385 D FactoryTest: User mode
,07-27 08:53:57.715  3385  3385 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,07-27 08:53:57.715  3385  3385 D MTPRx   : still no open session command from host, so toast
,07-27 08:53:57.725   749  1747 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,07-27 08:53:57.745   749  1747 D ActivityManager: mDVFSHelper.acquire()
,07-27 08:53:57.745   749  1747 V WindowManager: addAppToken: AppWindowToken{d6afa8a token=Token{5632cf5 ActivityRecord{9ea4a2c u0 com.samsung.android.MtpApplication/.USBConnection t103}}} to stack=1 task=103 at 0
,07-27 08:53:57.745   749  1747 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,07-27 08:53:57.765   749   826 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,07-27 08:53:57.785   749  1747 D InputDispatcher: Focused application set to: xxxx
,07-27 08:53:57.795   749  1747 D InputDispatcher: Focus left window: 5802
,07-27 08:53:57.795  3385  3385 E MTPRx   : started activity for popup
,07-27 08:53:57.795   749   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:749 uid:1000
07-27 08:53:57.795   749   874 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:53:57.795   749   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:749 uid:1000
07-27 08:53:57.795   749   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 08:53:57.805  3385  3385 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,07-27 08:53:57.805  3385  3385 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,07-27 08:53:57.815   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:53:57.825  3385  3385 D MTPUSBConnection: onCreate in USBConnection
,07-27 08:53:57.825  3385  3385 V MTPUSBConnection: Registering broadcast receiver.
,07-27 08:53:57.825  3385  3385 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,07-27 08:53:57.825   749  1733 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,07-27 08:53:57.875  3385  3385 D TAG     : dev.kiessupport is : TRUE
,07-27 08:53:57.905  3385  3385 D SecWifiDisplayUtil: Metadata value : none
,07-27 08:53:57.905  3385  3385 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d8f3552 V.E...... R.....I. 0,0-0,0}
,07-27 08:53:57.915  3385  6788 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-27 08:53:57.915   749  1320 D ISSUE_DEBUG: InputChannelName : 74850e2 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,07-27 08:53:57.915   749  1320 D InputDispatcher: Focus entered window: 3385
,07-27 08:53:57.915   749   828 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{74850e2 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,07-27 08:53:57.925   749   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:749 uid:1000
07-27 08:53:57.925   749   874 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:53:57.925   749   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:749 uid:1000
07-27 08:53:57.925   749   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 08:53:57.925  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,07-27 08:53:57.935  3385  3385 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1d01caa I.E...... R.....I. 0,0-0,0}
,07-27 08:53:57.935   749  1713 D ISSUE_DEBUG: InputChannelName : 4313730 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,07-27 08:53:57.935   749   762 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
07-27 08:53:57.935   749   762 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-27 08:53:57.935   749   749 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-27 08:53:57.935   749   749 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-27 08:53:57.935   749   749 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,07-27 08:53:57.975   292   292 I SurfaceFlinger: id=16 createSurf (145x145),1 flag=4, VSBConnecti
,07-27 08:53:57.985  3385  6788 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-27 08:53:57.985  3385  6788 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-27 08:53:57.985  3385  6788 I Adreno-EGL: Build Date: 01/28/16 Thu
07-27 08:53:57.985  3385  6788 I Adreno-EGL: Local Branch: ss
07-27 08:53:57.985  3385  6788 I Adreno-EGL: Remote Branch: 
07-27 08:53:57.985  3385  6788 I Adreno-EGL: Local Patches: 
07-27 08:53:57.985  3385  6788 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:53:57.995  3385  6788 D libEGL  : eglInitialize EGLDisplay = 0x9eeef7c4
07-27 08:53:57.995  3385  6788 I OpenGLRenderer: Initialized EGL, version 1.4
,07-27 08:53:58.065   292   292 I SurfaceFlinger: id=17 createSurf (193x193),1 flag=4, VSBConnecti
,07-27 08:53:58.095  3385  3385 V ActivityThread: updateVisibility : ActivityRecord{3374411 token=android.os.BinderProxy@7a4e023 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,07-27 08:53:58.105  3385  3385 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-27 08:53:58.205   749  1567 V WindowStateAnimator: Finishing drawing window Window{74850e2 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,07-27 08:53:58.205  3385  3385 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-27 08:53:58.215   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbea7a364
,07-27 08:53:58.215   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbea7a364
,07-27 08:53:58.215   749  1320 V WindowStateAnimator: Finishing drawing window Window{4313730 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,07-27 08:53:58.215  3385  3385 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-27 08:53:58.215  3385  3385 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-27 08:53:58.225   749   874 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-27 08:53:58.225   749  1747 V WindowStateAnimator: Finishing drawing window Window{74850e2 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
07-27 08:53:58.235   749   749 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-27 08:53:58.235   749   874 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +447ms (total +482ms)
,07-27 08:53:58.235   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbea7a364
,07-27 08:53:58.235   749  2078 V WindowStateAnimator: Finishing drawing window Window{4313730 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,07-27 08:53:58.235  3385  3385 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7a4e023 time:105895
,07-27 08:53:58.235   749   749 I KnoxTimeoutHandler: SD activityfalse
,07-27 08:53:58.235   749   874 D ActivityManager: mDVFSHelper.release()
07-27 08:53:58.235   749   874 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9ea4a2c u0 com.samsung.android.MtpApplication/.USBConnection t103} time:105899
,07-27 08:53:58.795   749  3344 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,07-27 08:53:58.965  1451  1451 D Recents : onTaskStackChanged
,07-27 08:53:58.995  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-27 08:54:00.015   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 08:54:00.115  6045  6045 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,07-27 08:54:00.125  6045  6045 D PreloadUpdateManagerStateMachine: exit::IDLE
,07-27 08:54:00.125  6045  6045 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-27 08:54:00.135  6045  6045 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,07-27 08:54:00.145  6045  6045 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-27 08:54:00.145  6045  6045 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-27 08:54:00.145  6045  6045 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,07-27 08:54:00.145  6045  6045 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-27 08:54:01.045   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:54:03.255  6574  6621 W Babel   : aye TOOK TOO LONG! (15003ms > 10000ms)
,07-27 08:54:03.295   749  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10117
,07-27 08:54:03.305  6574  6623 W Babel   : aye TOOK TOO LONG! (15048ms > 10000ms)
,07-27 08:54:03.345   749   761 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-27 08:54:03.355  6574  6574 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-27 08:54:03.355  6574  6574 W Babel   : BAM#gBA: invalid account id: -1
,07-27 08:54:03.365  6574  6574 W Babel   : BAM#gBA: invalid account id: -1
,07-27 08:54:03.365  6574  6574 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-27 08:54:03.375   749  1747 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-27 08:54:03.465  6574  6632 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,07-27 08:54:03.675   749  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:03.675   749  1713 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:54:03.675   749  1713 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-27 08:54:03.675   749  1713 D BatteryService: stay LED for charging
,07-27 08:54:03.675   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:03.685   749   749 I MotionRecognitionService: Plugged
,07-27 08:54:03.685   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:54:03.685   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:54:03.685   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:54:03.685  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:54:03.685  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:54:03.685  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:54:03.695  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:54:03.705  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:54:03.705  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:03.705  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:03.705  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:03.825   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:54:07.075   749  3343 D SSRM:n  : SIOP:: AP = 400, PST = 457, CUR = 300, LCD = 0
,07-27 08:54:13.175   749  1568 E Watchdog: !@Sync 3 [07-27 08:54:13.182]
,07-27 08:54:14.185   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:54:14.185   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:54:14.185   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:54:17.165   749  3343 D SSRM:n  : SIOP:: AP = 370, PST = 449, CUR = 300, LCD = 0
,07-27 08:54:17.205   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:54:17.835   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:54:17.875   749   749 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,07-27 08:54:17.885   749   749 V AlarmManagerEXT: <AppSync3 Whitelist>
,07-27 08:54:17.885   749   749 V AlarmManagerEXT: (AppSync) ### 0 added ###
,07-27 08:54:17.895  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 08:54:17.895  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 08:54:17.895  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:54:17.905   749  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:17.905   749  1320 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4375, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:54:17.905   749  1320 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:54:17.905   749  1320 D BatteryService: stay LED for charging
,07-27 08:54:17.935  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 08:54:17.935  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 08:54:17.945  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:54:17.955   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:17.965  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:54:17.965  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:54:17.965  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:54:17.975  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:54:17.975  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:54:17.985  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:54:17.995  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:54:17.995  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:54:17.995  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:54:17.995  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:54:17.995   749   749 I MotionRecognitionService: Plugged
07-27 08:54:17.995   749   749 D MotionRecognitionService:   cableConnection= 1
07-27 08:54:17.995   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:54:17.995   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:54:17.995  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-27 08:54:17.995  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-27 08:54:17.995  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:18.015  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:54:18.045  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:54:18.445   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:54:18.485   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cf64ae1 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
,07-27 08:54:18.495   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{ab4a006: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:54:18.565   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{154f4: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:54:18.695   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{d7c6863: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:54:18.725  1632  1632 D WearableService: callingUid 10012, callindPid: 1632
,07-27 08:54:18.725  1632  1632 I ConfigService: onCreate
,07-27 08:54:18.795  1632  6846 I CheckinRequestBuilder: Classify the device as Phone.
,07-27 08:54:18.845  1632  6846 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:18.845  1632  6846 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:18.855   305  1129 D EnterpriseController: netId is 0
07-27 08:54:18.855   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,07-27 08:54:18.855   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:54:18.855   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:54:18.855   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:54:18.895  1632  6846 I qtaguid : Tagging socket 57 with tag 1000040b00000000{268436491,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:18.925  1943  6849 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-27 08:54:18.935  6458  6850 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 08:54:18.935   749   821 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 124563, reason: UserStart, SyncResult: databaseError: true stats []
,07-27 08:54:18.935   749   821 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 188093, reason: UserStart
,07-27 08:54:18.935  1632  6846 I qtaguid : Tagging socket 61 with tag 1000040b00000000{268436491,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:18.945  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:54:18.955  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:54:18.965  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:54:18.965  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:54:18.965  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:54:18.965  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:54:18.965  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:54:18.965   749  1414 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 08:54:18.985  1632  2978 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 08:54:18.985  1632  2978 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:54:18.985  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 08:54:18.985  1632  2978 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:54:18.985  1632  2978 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:54:18.985  1632  2978 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:54:18.985  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 08:54:18.985  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:54:18.985  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:54:18.985  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:54:18.985  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:54:18.985  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:54:18.985  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:54:18.985  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:54:18.985  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:54:18.985  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:54:18.985  1632  4034 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:54:18.985  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:54:19.005  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 08:54:19.005  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 08:54:19.015  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-27 08:54:19.015  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 08:54:19.015  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:54:19.015  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:54:19.015  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:54:19.015  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:54:19.015  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:54:19.015  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:54:19.015  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:54:19.015  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:54:19.015  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:54:19.015  1632  4031 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:54:19.015  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:54:19.025  6458  6851 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 08:54:19.035  6458  6850 E BooksSync: Soft error
07-27 08:54:19.035  6458  6850 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:54:19.035  6458  6850 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-27 08:54:19.035  6458  6850 E BooksSync: Sync error
07-27 08:54:19.035  6458  6850 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:54:19.035  6458  6850 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-27 08:54:19.035  6458  6850 I BooksSync: Finished books sync
,07-27 08:54:19.035  6458  6852 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-27 08:54:19.035  6458  6852 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-27 08:54:19.035   749   821 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125446, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:54:19.045  1632  1646 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-27 08:54:19.045  1632  1646 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:54:19.045  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:54:19.045  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:54:19.045  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:54:19.045  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:54:19.045  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:54:19.045  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:54:19.045  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:54:19.045  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:54:19.045  1632  1646 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:54:19.045  1632  1646 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:54:19.045   749   821 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 08:54:19.065  6458  6852 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: Failed to register token for device group
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:54:19.065  6458  6852 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:54:19.065  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:54:19.075  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:54:19.075  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:54:19.075  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:54:19.075   749  1414 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 08:54:19.095   749   759 I art     : Background partial concurrent mark sweep GC freed 53506(3MB) AllocSpace objects, 33(844KB) LOS objects, 27% free, 42MB/58MB, paused 4.492ms total 157.340ms
,07-27 08:54:19.115  1632  6846 I qtaguid : Untagging socket 57
,07-27 08:54:19.135  1943  6837 D ChimeraConfigService: Fetched value, gms:chimera:module_overlay = 0|
,07-27 08:54:19.145  1943  6837 D ZappDownloader: Read 0 stored downloads
,07-27 08:54:19.155   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{145a931 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
,07-27 08:54:19.165   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{11c2816: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:54:19.225   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{3c74d69: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:54:19.235  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:54:19.245  1632  6859 I VacuumService: Vacuum at: now=1469602459253 tag=VacuumService
,07-27 08:54:19.255   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da823ee u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
,07-27 08:54:19.265   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{39e008f: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:54:19.345   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{967f108: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:54:19.655  1632  1632 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=5dc988a7-ab56-4e29-b66a-7ce47f794867
,07-27 08:54:19.735  1632  1639 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d7bb5bb)
,07-27 08:54:19.845  1943  6861 D UdcContextInitService: registered all accounts: true
,07-27 08:54:19.855  1632  2126 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 08:54:19.875  1632  6862 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-27 08:54:20.015   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{778314e: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:54:20.015  1632  6862 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10012, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,07-27 08:54:20.135  1632  1632 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,07-27 08:54:20.445  1632  6890 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 81 seconds from now (1469602460453)
,07-27 08:54:20.515   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7d09368 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7951cf3 1632:com.google.android.gms.persistent/u0a12}
,07-27 08:54:20.705  1632  6884 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,07-27 08:54:20.715  1632  6884 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:54:20.815   749  1740 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:20.985  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:20.985  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:20.995   305  1129 D EnterpriseController: netId is 0
07-27 08:54:20.995   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,07-27 08:54:21.045  1632  6884 I qtaguid : Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:21.055   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:54:21.085  1632  6884 I qtaguid : Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:21.765   749  1320 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:21.775  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:21.775  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:54:21.775  1632  6884 I qtaguid : Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:22.175   749  1733 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:22.195  1632  6884 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/cclog
07-27 08:54:22.195  1632  6884 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.q.a(:com.google.android.gms:146)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.auth.q.a(:com.google.android.gms:73)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:761)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:582)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:469)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:384)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.UploaderService.b(:com.google.android.gms:100)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.UploaderService.a(:com.google.android.gms:69)
07-27 08:54:22.195  1632  6884 E Auth    : 	at com.google.android.gms.gcm.aw.run(:com.google.android.gms:144)
,07-27 08:54:22.205  1632  6884 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:54:22.205  1632  6884 E Uploader: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.auth.q.a(:com.google.android.gms:146)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.auth.q.a(:com.google.android.gms:73)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:761)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:582)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:469)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:384)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(:com.google.android.gms:100)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(:com.google.android.gms:69)
07-27 08:54:22.205  1632  6884 E Uploader: 	at com.google.android.gms.gcm.aw.run(:com.google.android.gms:144)
,07-27 08:54:22.215  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:54:22.215  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.215  1632  6884 I qtaguid : Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:22.355   749  2078 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:22.365  1632  6884 W Uploader: UNKNOWN no longer exists, so no auth token.
,07-27 08:54:22.375  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.375  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.375  1632  6884 I qtaguid : Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:22.525   749  1747 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:22.545  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.545  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.545  1632  6884 I qtaguid : Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:22.685   749  1713 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:22.695  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.695  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.695  1632  6884 I qtaguid : Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:22.795   749  2079 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:22.845  1632  6884 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/cclog
07-27 08:54:22.845  1632  6884 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.q.a(:com.google.android.gms:146)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.auth.q.a(:com.google.android.gms:73)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:761)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:582)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:469)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:384)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.UploaderService.b(:com.google.android.gms:100)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.playlog.uploader.UploaderService.a(:com.google.android.gms:69)
07-27 08:54:22.845  1632  6884 E Auth    : 	at com.google.android.gms.gcm.aw.run(:com.google.android.gms:144)
,07-27 08:54:22.865  1632  6884 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:54:22.865  1632  6884 E Uploader: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.auth.q.a(:com.google.android.gms:146)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.auth.q.a(:com.google.android.gms:73)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:761)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:582)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:469)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:384)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(:com.google.android.gms:100)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(:com.google.android.gms:69)
07-27 08:54:22.865  1632  6884 E Uploader: 	at com.google.android.gms.gcm.aw.run(:com.google.android.gms:144)
,07-27 08:54:22.875  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.875  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.875  1632  6884 I qtaguid : Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:22.975   749  1414 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:22.995  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.995  1632  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:54:22.995  1632  6884 I qtaguid : Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1632, getuid(): 10012
,07-27 08:54:23.195   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{cf989fe: PendingIntentRecord{5d346d4 com.google.android.gms broadcastIntent}}
,07-27 08:54:24.155  1632  1632 I ConfigService: onDestroy
,07-27 08:54:27.275   749  3343 D SSRM:n  : SIOP:: AP = 360, PST = 437, CUR = 300, LCD = 0
,07-27 08:54:27.985   749   761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:27.995   749   761 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4380, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:54:27.995   749   761 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:54:28.005   749   761 D BatteryService: stay LED for charging
,07-27 08:54:28.005   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:28.015   749   749 I MotionRecognitionService: Plugged
,07-27 08:54:28.025   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:54:28.025   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:54:28.025   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:54:28.035  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:54:28.035  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:54:28.035  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:54:28.055  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:54:28.055  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:54:28.065  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:28.065  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:28.065  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:37.335   749  3343 D SSRM:n  : SIOP:: AP = 340, PST = 424, CUR = 300, LCD = 0
,07-27 08:54:37.335   749  3343 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,07-27 08:54:37.355  2585  2585 D ContentApp:  LEVEL : 0
,07-27 08:54:37.405  6921  6921 E Zygote  : v2
,07-27 08:54:37.415   749   826 I ActivityManager: Start proc 6921:com.sec.android.app.videoplayer/u0a54 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,07-27 08:54:37.415   749  1323 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 08:54:37.415  6921  6921 I libpersona: KNOX_SDCARD checking this for 10054
,07-27 08:54:37.415  6921  6921 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:37.425  6921  6921 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 08:54:37.425  6921  6921 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:54:37.425  6921  6921 E Zygote  : accessInfo : 0
,07-27 08:54:37.425  6921  6921 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,07-27 08:54:37.435   749  3343 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:54:37.525  6921  6921 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:37.525  6921  6921 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:37.545   749   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6bf555f u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f47bac 6921:com.sec.android.app.videoplayer/u0a54}
,07-27 08:54:37.545   749  1323 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,07-27 08:54:37.555  6921  6921 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,07-27 08:54:37.585  6921  6921 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,07-27 08:54:37.635  6921  6921 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,07-27 08:54:37.685  6921  6921 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,07-27 08:54:37.695  6921  6921 D videowall-Global: core_num = 4
,07-27 08:54:37.725  6921  6921 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
07-27 08:54:37.725  6921  6921 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,07-27 08:54:37.735  6921  6921 D TranscodeReceiver:  SIOP_LEVEL: 0
,07-27 08:54:37.745   749  1320 I ActivityManager: Killing 5993:com.samsung.helphub/1000 (adj 15): DHA:empty #37
,07-27 08:54:37.765   749  1740 D ActivityManager: isAutoRunBlockedApp:: com.samsung.helphub, Auto Run ON
,07-27 08:54:38.105   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:54:38.105   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:54:38.105   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:54:39.025   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:54:39.075   749  2078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:39.085   749  2078 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4382, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:54:39.085   749  2078 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-27 08:54:39.085   749  2078 D BatteryService: stay LED for charging
,07-27 08:54:39.085   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:39.085   749   749 I MotionRecognitionService: Plugged
,07-27 08:54:39.085   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:54:39.085   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:54:39.085   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:54:39.095  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:54:39.095  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:54:39.095  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:54:39.105  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:54:39.105  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:54:39.115  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:39.115  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:39.115  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-27 08:54:39.435  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:54:39.455  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:54:39.455  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:54:39.475  1632  1645 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 08:54:39.475  1632  1645 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:54:39.475  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 08:54:39.475  1632  1645 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:54:39.475  1632  1645 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:54:39.475  1632  1645 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:54:39.495  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 08:54:39.495  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 08:54:39.495  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-27 08:54:41.055   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:54:43.185   749  1568 E Watchdog: !@Sync 4 [07-27 08:54:43.190]
,07-27 08:54:44.355  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:54:47.505   749  3343 D SSRM:n  : SIOP:: AP = 330, PST = 410, CUR = 300, LCD = 0
,07-27 08:54:49.165   749  1414 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:51.465   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:54:51.465   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:54:51.465   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:54:57.565   749  3343 D SSRM:n  : SIOP:: AP = 320, PST = 395, CUR = 300, LCD = 0
,07-27 08:54:57.565   749  3343 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,07-27 08:54:57.595  2585  2585 D ContentApp:  LEVEL : -1
,07-27 08:54:57.635   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8e427dc u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f47bac 6921:com.sec.android.app.videoplayer/u0a54}
,07-27 08:54:57.635  6921  6921 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,07-27 08:54:57.645  6921  6921 D TranscodeReceiver:  SIOP_LEVEL: -1
,07-27 08:54:59.515   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:54:59.615   749  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:59.615   749  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:54:59.615   749  1747 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-27 08:54:59.615   749  1747 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 749) 
,07-27 08:54:59.615   749  1747 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,07-27 08:54:59.615   749  1747 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-27 08:54:59.625   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:59.625   749   749 I MotionRecognitionService: Plugged
,07-27 08:54:59.625   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:54:59.625   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:54:59.625   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:54:59.635  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:54:59.635  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:54:59.635  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:54:59.635  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:54:59.655   749  1747 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-27 08:54:59.655  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:54:59.655  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:54:59.655  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:59.655  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:59.655  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:59.675   749  1747 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-27 08:54:59.675   749  1747 D BatteryService: turn on LED for fully charged
,07-27 08:54:59.995   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 08:55:00.035   749   898 D LightsService: [SvcLED]  onSensorChanged::light value = 16
07-27 08:55:00.035   749   898 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-27 08:55:00.045   749   898 D SensorManager: unregisterListener ::   
,07-27 08:55:00.045   749   898 D lights  : led_pattern : 5 +
,07-27 08:55:00.045   749   898 D lights  : led_pattern : 5 -
,07-27 08:55:00.055   749   898 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-27 08:55:00.055   749   898 V AlarmManager:  remove PendingIntent] PendingIntent{209f16a: PendingIntentRecord{7c6465b android broadcastIntent}}
,07-27 08:55:00.245  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:55:00.265  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:55:00.265  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:55:00.285  1632  1645 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 08:55:00.285  1632  1645 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:55:00.285  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 08:55:00.285  1632  1645 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:55:00.285  1632  1645 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:55:00.285  1632  1645 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:55:00.305  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
07-27 08:55:00.315  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 08:55:00.315  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-27 08:55:01.065   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:55:07.705   749  3343 D SSRM:n  : SIOP:: AP = 320, PST = 381, CUR = 300, LCD = 0
,07-27 08:55:11.345   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:55:11.345   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:55:11.345   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:55:13.195   749  1568 E Watchdog: !@Sync 5 [07-27 08:55:13.198]
,07-27 08:55:13.605   749  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-27 08:55:13.615   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df9a20d u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e26a5aa 5648:com.samsung.android.sm.provider/1000}
,07-27 08:55:13.645   749  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,07-27 08:55:13.655   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f55fd3 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e26a5aa 5648:com.samsung.android.sm.provider/1000}
,07-27 08:55:14.355  1632  3199 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 08:55:17.775   749  3343 D SSRM:n  : SIOP:: AP = 310, PST = 366, CUR = 300, LCD = 0
,07-27 08:55:19.255   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:55:19.275  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 08:55:19.275  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 08:55:19.275  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:55:19.335   749  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:55:19.335  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 08:55:19.345  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 08:55:19.385  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:55:19.385  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:55:19.385  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:55:19.385  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 08:55:19.385  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:55:19.385  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:55:19.385  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:55:19.465  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:55:19.515  6458  7035 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 08:55:19.585  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:55:19.585  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:55:19.625  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 08:55:19.625  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:55:19.625  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:55:19.625  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:55:19.625  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:55:19.625  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:55:19.625  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:55:19.625  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:55:19.625  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:55:19.625  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:55:19.625  1632  4031 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:55:19.625  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:55:19.685  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 08:55:19.685  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:55:19.685  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:55:19.685  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:55:19.685  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:55:19.685  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:55:19.685  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:55:19.685  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:55:19.685  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:55:19.685  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:55:19.685  1632  4034 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:55:19.685  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:55:19.715  6458  7036 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:55:19.725  6458  7035 E BooksSync: Soft error
07-27 08:55:19.725  6458  7035 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:55:19.725  6458  7035 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-27 08:55:19.725  6458  7035 E BooksSync: Sync error
07-27 08:55:19.725  6458  7035 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:55:19.725  6458  7035 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-27 08:55:19.735  6458  7035 I BooksSync: Finished books sync
,07-27 08:55:19.745  6458  7038 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-27 08:55:19.755   749   821 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 186890, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:55:19.755  6458  7038 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-27 08:55:19.775   749   821 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 08:55:19.785  1632  1646 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-27 08:55:19.785  1632  1646 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:55:19.785  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:55:19.785  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:55:19.785  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:55:19.785  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:55:19.785  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:55:19.785  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:55:19.785  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:55:19.785  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:55:19.785  1632  1646 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:55:19.785  1632  1646 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:55:19.825  6458  7038 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: Failed to register token for device group
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:55:19.825  6458  7038 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:55:19.835  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-27 08:55:19.835  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-27 08:55:19.835  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-27 08:55:19.845  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-27 08:55:19.845   749  1567 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 08:55:20.315   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:55:20.525  1632  6862 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:-818113082>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-27 08:55:20.525  1632  6862 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.s.d(:com.google.android.gms:450)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.auth.q.c(:com.google.android.gms:586)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.common.server.a.a.a(:com.google.android.gms:82)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.common.server.c.a(:com.google.android.gms:59)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:61)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:140)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.contextmanager.l.a.a.a(:com.google.android.gms:130)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.contextmanager.g.a.a.run(:com.google.android.gms:52)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.contextmanager.g.i.a(:com.google.android.gms:263)
07-27 08:55:20.525  1632  6862 E Auth    : 	at com.google.android.contextmanager.g.i.handleMessage(:com.google.android.gms:254)
07-27 08:55:20.525  1632  6862 E Auth    : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:55:20.525  1632  6862 E Auth    : 	at android.os.Looper.loop(Looper.java:158)
07-27 08:55:20.525  1632  6862 E Auth    : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:55:20.565   749   759 I art     : Background partial concurrent mark sweep GC freed 48463(2MB) AllocSpace objects, 34(680KB) LOS objects, 27% free, 41MB/57MB, paused 2.510ms total 202.578ms
,07-27 08:55:20.565  1632  6862 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-27 08:55:20.635  1632  6862 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-27 08:55:20.635  1632  6862 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:55:20.635  1632  6862 E Auth    : ,	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.s.d(:com.google.android.gms:450)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.auth.q.c(:com.google.android.gms:586)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.common.server.a.a.a(:com.google.android.gms:82)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.common.server.c.a(:com.google.android.gms:59)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:61)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:140)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.contextmanager.l.a.a.a(:com.google.android.gms:130)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.contextmanager.g.a.a.run(:com.google.android.gms:52)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.contextmanager.g.i.a(:com.google.android.gms:263)
07-27 08:55:20.635  1632  6862 E Auth    : 	at com.google.android.contextmanager.g.i.handleMessage(:com.google.android.gms:254)
07-27 08:55:20.635  1632  6862 E Auth    : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:55:20.635  1632  6862 E Auth    : 	at android.os.Looper.loop(Looper.java:158)
07-27 08:55:20.635  1632  6862 E Auth    : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:55:20.655  1632  6862 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-27 08:55:20.685  1632  6862 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-27 08:55:20.685  1632  6862 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.s.d(:com.google.android.gms:450)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.auth.q.c(:com.google.android.gms:586)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.common.server.a.a.a(:com.google.android.gms:82)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.common.server.c.a(:com.google.android.gms:59)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:61)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:140)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.contextmanager.l.a.a.a(:com.google.android.gms:130)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.contextmanager.g.a.a.run(:com.google.android.gms:52)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.contextmanager.g.i.a(:com.google.android.gms:263)
07-27 08:55:20.685  1632  6862 E Auth    : 	at com.google.android.contextmanager.g.i.handleMessage(:com.google.android.gms:254)
07-27 08:55:20.685  1632  6862 E Auth    : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:55:20.685  1632  6862 E Auth    : 	at android.os.Looper.loop(Looper.java:158)
07-27 08:55:20.685  1632  6862 E Auth    : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:55:20.705  1632  6862 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-27 08:55:20.725  1632  6862 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=UNKNOWN).  Giving up.
07-27 08:55:20.725  1632  6862 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = -1
,07-27 08:55:20.765  1632  6862 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-27 08:55:20.915  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:55:20.935  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 08:55:20.935  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:55:20.935  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 08:55:20.935  1632  4031 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:55:20.935  1632  4031 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:55:20.935  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:55:20.955  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 08:55:20.955  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 08:55:20.955  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-27 08:55:21.065   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:55:27.835   749  3343 D SSRM:n  : SIOP:: AP = 310, PST = 350, CUR = 300, LCD = 0
,07-27 08:55:29.425   749  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:55:37.895   749  3343 D SSRM:n  : SIOP:: AP = 310, PST = 337, CUR = 300, LCD = 0
,07-27 08:55:40.975   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:55:41.045   749  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:55:41.045   749  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-27 08:55:41.045   749  1415 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:55:41.045   749  1415 D BatteryService: stay LED for fully charged
07-27 08:55:41.045   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:55:41.055  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:55:41.055  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:55:41.065  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:55:41.065   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:55:41.075  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:55:41.075  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:55:41.085   749   749 I MotionRecognitionService: Plugged
,07-27 08:55:41.085   749   749 D MotionRecognitionService:   cableConnection= 1
07-27 08:55:41.085   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:55:41.085   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:55:41.085  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:41.085  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:55:41.085  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:41.605  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:55:41.625  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:55:41.625  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:55:41.645  1632  2978 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 08:55:41.645  1632  2978 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:55:41.645  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 08:55:41.645  1632  2978 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:55:41.645  1632  2978 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:55:41.645  1632  2978 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:55:41.665  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 08:55:41.665  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 08:55:41.675  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-27 08:55:43.195   749  1568 E Watchdog: !@Sync 6 [07-27 08:55:43.204]
,07-27 08:55:44.465  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:55:47.955   749  3343 D SSRM:n  : SIOP:: AP = 310, PST = 328, CUR = 300, LCD = 0
,07-27 08:55:51.135   749  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:55:51.145   749  1733 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:55:51.145   749  1733 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:55:51.145   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:55:51.155   749   749 I MotionRecognitionService: Plugged
,07-27 08:55:51.165   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:55:51.165   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:55:51.165   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:55:51.175   749  1733 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 08:55:51.175   749  1733 D BatteryService: stay LED for fully charged
,07-27 08:55:51.175  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:55:51.185  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:55:51.185  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:55:51.205  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:55:51.215  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:55:51.215  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:51.215  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:51.215  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:58.025   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 321, CUR = 300, LCD = 0
,07-27 08:55:59.995   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 08:56:01.095   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:56:01.225   749  1567 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:01.225   749  1567 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:56:01.225   749  1567 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:56:01.235   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:01.245   749   749 I MotionRecognitionService: Plugged
,07-27 08:56:01.245   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:56:01.245   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:56:01.245   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:56:01.255   749  1567 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 08:56:01.255   749  1567 D BatteryService: stay LED for fully charged
,07-27 08:56:01.255  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:01.255  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:56:01.255  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:01.275  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:01.275  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:56:01.285  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:01.285  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:56:01.285  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:08.085   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 315, CUR = 300, LCD = 0
,07-27 08:56:11.315   749  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:11.315   749  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:56:11.325   749  1713 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:56:11.325   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:11.335   749   749 I MotionRecognitionService: Plugged
,07-27 08:56:11.335   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:56:11.345   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:56:11.345   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:56:11.345   749  1713 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 08:56:11.355   749  1713 D BatteryService: stay LED for fully charged
,07-27 08:56:11.355  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:11.355  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:56:11.355  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:11.375  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:11.375  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:56:11.385  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:11.385  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:56:11.385  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:13.205   749  1568 E Watchdog: !@Sync 7 [07-27 08:56:13.209]
,07-27 08:56:18.135   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 311, CUR = 300, LCD = 0
,07-27 08:56:21.095   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:56:21.405   749  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:21.405   749  1625 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:56:21.405   749  1625 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:56:21.415   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:21.425   749   749 I MotionRecognitionService: Plugged
,07-27 08:56:21.425   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:56:21.425   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:56:21.435   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:56:21.435   749  1625 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 08:56:21.435   749  1625 D BatteryService: stay LED for fully charged
,07-27 08:56:21.455  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:21.455  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:56:21.455  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:21.465  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:21.475  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:56:21.475  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:21.475  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:56:21.475  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:28.195   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 300, LCD = 0
,07-27 08:56:31.485   749  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:31.495   749  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:56:31.495   749  1320 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:56:31.495   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:31.515   749   749 I MotionRecognitionService: Plugged
,07-27 08:56:31.515   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:56:31.515   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:56:31.525   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:56:31.525   749  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 08:56:31.525   749  1320 D BatteryService: stay LED for fully charged
,07-27 08:56:31.545  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:31.545  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:31.545  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:31.565  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:31.565  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:56:31.575  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:31.575  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:31.575  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:38.255   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 300, LCD = 0
,07-27 08:56:41.105   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:56:41.585   749  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:41.595   749  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:56:41.595   749  1747 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:56:41.595   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:41.605   749   749 I MotionRecognitionService: Plugged
,07-27 08:56:41.605   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:56:41.615   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:56:41.615   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:56:41.615   749  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-27 08:56:41.625   749  1747 D BatteryService: stay LED for fully charged
,07-27 08:56:41.625  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:41.635  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:41.635  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:41.655  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:41.665  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:56:41.665  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:41.665  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:41.665  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:43.205   749  1568 E Watchdog: !@Sync 8 [07-27 08:56:43.213]
,07-27 08:56:44.475  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:56:48.315   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 300, LCD = 0
,07-27 08:56:51.675   749  1567 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:58.375   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,07-27 08:57:01.105   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:01.755   749  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:08.435   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 0
,07-27 08:57:13.215   749  1568 E Watchdog: !@Sync 9 [07-27 08:57:13.217]
,07-27 08:57:18.535   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-27 08:57:19.855  1632  3199 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 08:57:20.155   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:57:20.185  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 08:57:20.185  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 08:57:20.185  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:57:20.215  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 08:57:20.235   749   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:20.245  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 08:57:20.265  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:20.265  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:20.265  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:20.265  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 08:57:20.265  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:20.265  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:20.265  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:20.335  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:20.665  6458  7110 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 08:57:20.705  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:57:20.705  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:57:20.735  1632  2978 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 08:57:20.735  1632  2978 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:57:20.735  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:57:20.735  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:57:20.735  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:57:20.735  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:57:20.735  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:57:20.735  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:57:20.735  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:57:20.735  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:57:20.735  1632  2978 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:57:20.735  1632  2978 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:57:20.775  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 08:57:20.775  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:57:20.775  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:57:20.775  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:57:20.775  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:57:20.775  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:57:20.775  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:57:20.775  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:57:20.775  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:57:20.775  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:57:20.775  1632  4034 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:57:20.775  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:57:20.795  6458  7111 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 08:57:20.795  6458  7110 E BooksSync: Soft error
07-27 08:57:20.795  6458  7110 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:57:20.795  6458  7110 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-27 08:57:20.795  6458  7110 E BooksSync: Sync error
07-27 08:57:20.795  6458  7110 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:57:20.795  6458  7110 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-27 08:57:20.805  6458  7110 I BooksSync: Finished books sync
,07-27 08:57:20.815  6458  7112 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-27 08:57:20.815  6458  7112 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-27 08:57:20.825   749   821 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307798, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:57:20.835  1632  1645 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-27 08:57:20.835  1632  1645 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:57:20.835  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:57:20.835  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:57:20.835  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:57:20.835  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:57:20.835  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:57:20.835  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:57:20.835  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:57:20.835  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:57:20.835  1632  1645 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 08:57:20.835  1632  1645 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:57:20.845   749   821 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 08:57:20.895  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:20.895  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:20.895  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:20.895  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:20.895  6458  7112 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-27 08:57:20.895   749  1746 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: Failed to register token for device group
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:57:20.895  6458  7112 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:57:21.105   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:28.075   749  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 08:57:28.095   749  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 08:57:28.095   749  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 08:57:28.105   749  1229 I TLC_TIMA_PKM_initialize: initializing...
,07-27 08:57:28.115   749  1229 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-27 08:57:28.115   749  1229 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-27 08:57:28.115   749  1229 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-27 08:57:28.115   749  1229 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-27 08:57:28.115   749  1229 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-27 08:57:28.125   749  1229 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-27 08:57:28.125   749  1229 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-27 08:57:28.125   749  1229 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-27 08:57:28.135   749  1229 D QSEECOMAPI: : App is not loaded in QSEE
,07-27 08:57:28.185   749  1229 D QSEECOMAPI: : Loaded image: APP id = 3
,07-27 08:57:28.195   749  1229 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-27 08:57:28.215   749  1229 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-27 08:57:28.605   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-27 08:57:30.335   749  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:30.335   749  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:57:30.335   749  1713 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:57:30.335   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:57:30.345   749   749 I MotionRecognitionService: Plugged
,07-27 08:57:30.345   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:57:30.355   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:57:30.355   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:57:30.355   749  1713 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms
,07-27 08:57:30.365   749  1713 D BatteryService: stay LED for fully charged
,07-27 08:57:30.375  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:30.375  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:30.375  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:30.395  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:30.395  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:57:30.405  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:30.405  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:57:30.405  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:31.545   749  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 08:57:31.545   749  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 08:57:31.555   749  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 08:57:31.565   749  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 08:57:38.675   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-27 08:57:40.395   749  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:40.405   749  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:57:40.405   749  1415 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:57:40.405   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:57:40.425   749   749 I MotionRecognitionService: Plugged
,07-27 08:57:40.425   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:57:40.425   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:57:40.425   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:57:40.435   749  1415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 08:57:40.435   749  1415 D BatteryService: stay LED for fully charged
,07-27 08:57:40.435  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:40.435  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:57:40.435  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:40.455  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:40.455  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:57:40.465  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:40.465  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:40.465  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:41.115   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:43.215   749  1568 E Watchdog: !@Sync 10 [07-27 08:57:43.222]
,07-27 08:57:44.485  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:57:48.745   749  3343 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-27 08:57:49.435   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:57:49.435   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:57:49.435   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:57:50.475   749  2078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:58.805   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 300, LCD = 0
,07-27 08:57:59.995   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 08:58:00.565   749  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:01.115   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:04.505   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:58:04.505   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:04.505   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:08.895   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 300, LCD = 0
,07-27 08:58:12.285  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:12.305  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:12.305  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:12.335  1632  2978 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-27 08:58:12.335  1632  2978 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-27 08:58:12.335  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
07-27 08:58:12.335  1632  2978 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:58:12.335  1632  2978 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:58:12.335  1632  2978 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:58:12.355  1632  2978 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
07-27 08:58:12.355  1632  2978 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
07-27 08:58:12.355  1632  2978 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-27 08:58:12.355  1632  2978 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
07-27 08:58:12.355  1632  2978 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:58:12.355  1632  2978 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:58:12.355  1632  2978 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:58:12.365  5294  5336 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:58:12.365  5294  5336 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-27 08:58:12.365  5294  5336 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
07-27 08:58:12.365  5294  5336 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
07-27 08:58:12.365  5294  5336 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
07-27 08:58:12.365  5294  5336 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-27 08:58:12.365  5294  5336 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:58:12.425  5294  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:58:12.425  5294  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:58:12.445   305  1129 D EnterpriseController: netId is 0
07-27 08:58:12.445   305  1129 D Netd    : getNetworkForDns: using netid 502 for uid 10030
,07-27 08:58:12.445   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-27 08:58:12.445   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:12.445   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:13.225   749  1568 E Watchdog: !@Sync 11 [07-27 08:58:13.227]
,07-27 08:58:16.285   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 08:58:16.355   749  1235 I ActivityManager: Start proc 7147:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-27 08:58:16.365  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 08:58:16.375  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 08:58:16.375  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:58:16.375  7147  7147 E Zygote  : v2
,07-27 08:58:16.385  7147  7147 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:58:16.385  7147  7147 I libpersona: KNOX_SDCARD not a persona
,07-27 08:58:16.385  7147  7147 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:58:16.385  7147  7147 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:58:16.385  7147  7147 E Zygote  : accessInfo : 0
,07-27 08:58:16.385   749  1746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:16.385   749  1746 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-27 08:58:16.385   749  1746 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:58:16.385   749  1746 D BatteryService: stay LED for fully charged
,07-27 08:58:16.395  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 08:58:16.415  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 08:58:16.425  6111  6111 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-27 08:58:16.425  6111  6111 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-27 08:58:16.435  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:16.435  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:16.435   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 08:58:16.435  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:16.445   749   749 I MotionRecognitionService: Plugged
,07-27 08:58:16.445  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 08:58:16.445   749   749 D MotionRecognitionService:   cableConnection= 1
07-27 08:58:16.445   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:58:16.445   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:58:16.445  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:16.445  6111  6111 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 08:58:16.445  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:16.445  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:16.455  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:58:16.455  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:16.455  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 08:58:16.455  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:58:16.465  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:16.465  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:16.465  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:16.465  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:16.485  7147  7147 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:58:16.485  7147  7147 D ActivityThread: Added TimaKeyStore provider
,07-27 08:58:16.495  7147  7147 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,07-27 08:58:16.515  7147  7147 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-27 08:58:16.515  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:16.545   749  1740 I ActivityManager: Killing 6005:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #37
,07-27 08:58:16.565   749  1625 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
,07-27 08:58:18.965   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 300, LCD = 0
,07-27 08:58:20.235  6111  6111 I wpa_supplicant: nl80211: Received scan results (29 BSSes)
,07-27 08:58:20.235   305  1126 D Netd    : Iface wlan0 link up
,07-27 08:58:20.245  6111  6111 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-27 08:58:20.255   749   832 D Tethering: interfaceLinkStateChanged wlan0, true
,07-27 08:58:20.255   749   832 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:58:20.285   749  1324 D WifiP2pService: InactiveState{ what=147461 }
,07-27 08:58:20.285   749  1324 D WifiP2pService: P2pEnabledState{ what=147461 }
07-27 08:58:20.285   749  1324 D WifiP2pService: DefaultState{ what=147461 }
,07-27 08:58:20.335   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d307b1d u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97a4d07 1379:com.android.systemui/u0a59}
,07-27 08:58:21.115   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:26.445   749  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:26.455   749  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:58:26.455   749  1320 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:58:26.455   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:58:26.475   749   749 I MotionRecognitionService: Plugged
,07-27 08:58:26.475   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:58:26.475   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:58:26.475   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:58:26.485   749  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 08:58:26.485   749  1320 D BatteryService: stay LED for fully charged
,07-27 08:58:26.485  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:26.485  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:58:26.485  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:26.505  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:26.505  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:58:26.515  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:26.515  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:26.515  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:29.025   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 300, LCD = 0
,07-27 08:58:36.535   749  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:38.305   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:58:38.305   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:38.305   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:39.085   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 300, LCD = 0
,07-27 08:58:41.125   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:43.225   749  1568 E Watchdog: !@Sync 12 [07-27 08:58:43.233]
,07-27 08:58:44.505  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:58:46.625   749  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:46.625   749  1733 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:58:46.625   749  1733 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:58:46.635   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:58:46.645   749   749 I MotionRecognitionService: Plugged
,07-27 08:58:46.645   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:58:46.645   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:58:46.645   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:58:46.655   749  1733 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 08:58:46.655   749  1733 D BatteryService: stay LED for fully charged
,07-27 08:58:46.675  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:46.675  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:46.675  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:46.695  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:46.695  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:58:46.705  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:46.705  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:46.705  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:49.135   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 300, LCD = 0
,07-27 08:58:49.365   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:58:49.365   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:49.365   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:56.735   749  1567 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:56.735   749  1567 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:58:56.745   749  1567 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:58:56.745   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:58:56.755   749   749 I MotionRecognitionService: Plugged
,07-27 08:58:56.755   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:58:56.755   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:58:56.755   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:58:56.755   749  1567 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 20ms
,07-27 08:58:56.765   749  1567 D BatteryService: stay LED for fully charged
,07-27 08:58:56.775  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:56.775  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:56.775  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:56.805  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:56.805  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:56.805  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:56.815  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:56.815  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:58:59.205   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,07-27 08:58:59.995   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 08:59:01.125   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:05.305   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:59:05.305   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:59:05.305   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:59:09.295   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,07-27 08:59:13.235   749  1568 E Watchdog: !@Sync 13 [07-27 08:59:13.239]
,07-27 08:59:19.115   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:59:19.115   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:59:19.115   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:59:19.395   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,07-27 08:59:21.135   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:26.805   749  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:26.815   749  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:59:26.815   749  1713 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:59:26.815   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:59:26.825   749   749 I MotionRecognitionService: Plugged
,07-27 08:59:26.835   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:59:26.835   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:59:26.835   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:59:26.845   749  1713 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,07-27 08:59:26.855   749  1713 D BatteryService: stay LED for fully charged
,07-27 08:59:26.865  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:26.865  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:26.875  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:59:26.895  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:59:26.895  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:59:26.905  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:26.905  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:59:26.905  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:29.455   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 08:59:38.185   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:59:38.185   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:59:38.185   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:59:39.515   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 08:59:41.135   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:43.235   749  1568 E Watchdog: !@Sync 14 [07-27 08:59:43.243]
,07-27 08:59:44.575  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:59:44.835  1716  1803 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 260ms lastUpdatedAfter : 143916ms
,07-27 08:59:49.575   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 08:59:56.885   749   761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:56.895   749   761 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:59:56.895   749   761 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 08:59:56.895   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:59:56.915   749   749 I MotionRecognitionService: Plugged
,07-27 08:59:56.915   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 08:59:56.915   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:59:56.915   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:59:56.925   749   761 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 08:59:56.925   749   761 D BatteryService: stay LED for fully charged
,07-27 08:59:56.935  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:56.935  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:59:56.935  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:59:56.955  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:59:56.955  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:59:56.965  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:56.965  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:56.965  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:59.635   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:00:01.135   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:09.695   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:00:13.245   749  1568 E Watchdog: !@Sync 15 [07-27 09:00:13.248]
,07-27 09:00:17.805   358   358 I bootchecker: bootchecker wake up!!
,07-27 09:00:19.755   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:00:21.145   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:26.965   749  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:26.975   749  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:00:26.975   749  1320 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:00:26.975   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:00:26.995   749   749 I MotionRecognitionService: Plugged
,07-27 09:00:26.995   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:00:26.995   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:00:26.995   749  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-27 09:00:27.005   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:00:27.005   749  1320 D BatteryService: stay LED for fully charged
,07-27 09:00:27.025  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:27.025  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:27.025  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:00:27.045  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:00:27.045  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:00:27.055  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:27.055  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:00:27.055  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:29.805   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:00:39.885   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:00:41.145   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:43.245   749  1568 E Watchdog: !@Sync 16 [07-27 09:00:43.252]
,07-27 09:00:44.945  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:00:49.955   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:00:57.045   749  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:57.055   749  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:00:57.055   749  1415 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:00:57.055   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:00:57.065   749   749 I MotionRecognitionService: Plugged
,07-27 09:00:57.075   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:00:57.075   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:00:57.075   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:00:57.085   749  1415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:00:57.085   749  1415 D BatteryService: stay LED for fully charged
,07-27 09:00:57.095  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:57.095  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:57.105  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:00:57.135  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:57.135  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:57.135  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:57.135  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:00:57.145  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:01:00.025   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:01:01.145   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:10.075   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:01:13.255   749  1568 E Watchdog: !@Sync 17 [07-27 09:01:13.256]
,07-27 09:01:20.165   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:01:21.155   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:21.605   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:01:21.645  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:01:21.645  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 09:01:21.645  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:01:21.685  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:01:21.695  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:01:21.705  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:01:21.725  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:01:21.725  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:01:21.725  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:01:21.725  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:01:21.725  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:01:21.725  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:01:21.785  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:01:21.885  6458  7208 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 09:01:21.935  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:01:21.935  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:01:21.965  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 09:01:21.965  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:01:21.965  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:01:21.965  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:01:21.965  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:01:21.965  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:01:21.965  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:01:21.965  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:01:21.965  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:01:21.965  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:01:21.965  1632  4031 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 09:01:21.965  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:01:22.005  1632  1645 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 09:01:22.005  1632  1645 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:01:22.005  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:01:22.005  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:01:22.005  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:01:22.005  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:01:22.005  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:01:22.005  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:01:22.005  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:01:22.005  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:01:22.005  1632  1645 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 09:01:22.005  1632  1645 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:01:22.025  6458  7209 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:01:22.025  6458  7208 E BooksSync: Soft error
07-27 09:01:22.025  6458  7208 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:01:22.025  6458  7208 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-27 09:01:22.025  6458  7208 E BooksSync: Sync error
07-27 09:01:22.025  6458  7208 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:01:22.025  6458  7208 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-27 09:01:22.035  6458  7208 I BooksSync: Finished books sync
07-27 09:01:22.035  6458  7210 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-27 09:01:22.035  6458  7210 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-27 09:01:22.045   749   821 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 549264, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:01:22.055  1632  2978 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-27 09:01:22.055  1632  2978 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:01:22.055  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:01:22.055  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:01:22.055  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:01:22.055  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:01:22.055  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:01:22.055  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:01:22.055  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:01:22.055  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:01:22.055  1632  2978 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 09:01:22.055  1632  2978 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:01:22.065   749   821 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 09:01:22.085  6458  7210 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: Failed to register token for device group
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-27 09:01:22.085  6458  7210 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 09:01:22.105  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-27 09:01:22.105  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-27 09:01:22.105  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-27 09:01:22.115  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-27 09:01:22.115   749   762 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 09:01:27.125   749  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:30.235   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:01:40.335   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:01:41.155   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:43.255   749  1568 E Watchdog: !@Sync 18 [07-27 09:01:43.260]
,07-27 09:01:45.065  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:01:50.385   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:01:57.205   749  1746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:57.205   749  1746 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:01:57.215   749  1746 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:01:57.215   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:01:57.225   749   749 I MotionRecognitionService: Plugged
,07-27 09:01:57.235   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:01:57.235   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:01:57.235   749  1746 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 09:01:57.235   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:01:57.245   749  1746 D BatteryService: stay LED for fully charged
,07-27 09:01:57.265  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:01:57.265  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:01:57.265  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:01:57.275  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:01:57.275  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:01:57.285  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:57.285  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:01:57.285  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:59.995   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 09:02:00.445   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:02:01.165   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:10.505   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:02:13.265   749  1568 E Watchdog: !@Sync 19 [07-27 09:02:13.268]
,07-27 09:02:13.325   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:02:13.325   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:02:13.325   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:02:20.555   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:02:21.165   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:27.275   749  2079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:02:28.075   749  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:02:28.075   749  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:02:28.075   749  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:02:28.345   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:02:28.345   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:02:28.345   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:02:29.575   749  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:02:29.585   749  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:02:29.595   749  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:02:29.595   749  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:02:30.605   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:02:40.665   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:02:41.165   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:43.265   749  1568 E Watchdog: !@Sync 20 [07-27 09:02:43.272]
,07-27 09:02:45.145  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10016, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10020, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10028, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10030, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.415   749   821 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10038, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10051, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10058, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10062, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10071, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10076, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10082, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10084, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10088, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.425   749   821 D NetworkPolicy: isUidForegroundLocked: 10092, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10096, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10103, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10117, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10138, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10141, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10143, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.435   749   821 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10173, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10175, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10207, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.445   749   821 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.455   749   821 D NetworkPolicy: isUidForegroundLocked: 10211, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.455   749   821 D NetworkPolicy: isUidForegroundLocked: 10212, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.455   749   821 D NetworkPolicy: isUidForegroundLocked: 10213, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:47.455   749   821 D NetworkPolicy: isUidForegroundLocked: 10221, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:47.535   749   874 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-27 09:02:47.545   749   874 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-27 09:02:50.725   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:02:57.365   749  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:00.775   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:03:01.175   749  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:03:10.845   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:03:12.945   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:03:12.945   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:03:12.945   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:03:13.275   749  1568 E Watchdog: !@Sync 21 [07-27 09:03:13.276]
,07-27 09:03:16.705   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 09:03:20.965   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:03:27.445   749  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:27.445   749  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:03:27.445   749  1740 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:03:27.455   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:03:27.475   749   749 I MotionRecognitionService: Plugged
,07-27 09:03:27.475   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:03:27.475   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:03:27.485   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:03:27.485   749  1740 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 42ms
,07-27 09:03:27.485   749  1740 D BatteryService: stay LED for fully charged
,07-27 09:03:27.515  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:27.515  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:03:27.515  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:03:27.535  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:03:27.535  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:03:27.535  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:27.535  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:27.545  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:28.025   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:03:28.025   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:03:28.025   305  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:03:31.035   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:03:41.085   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:03:43.275   749  1568 E Watchdog: !@Sync 22 [07-27 09:03:43.280]
,07-27 09:03:45.225  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:03:45.415  1716  1803 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 179ms lastUpdatedAfter : 143288ms
,07-27 09:03:51.155   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:03:51.905   749  1740 I ActivityManager: Killing 4313:com.sec.spp.push/u0a38 (adj 5): SSR - service for lastStateTime 649s, lastActivityTime 600s
,07-27 09:03:51.915   749  1740 I ActivityManager: Killing 1516:com.sec.android.daemonapp/u0a182 (adj 5): SSR - service for lastStateTime 641s, lastActivityTime 603s
,07-27 09:03:51.925   749  1740 I ActivityManager: Killing 1887:com.sec.android.app.shealth:remote/u0a35 (adj 8): SSR - service for lastStateTime 666s, lastActivityTime 605s
,07-27 09:03:51.935   749  1740 I ActivityManager: Killing 5756:com.samsung.android.sdk.samsunglink/u0a42 (adj 8): SSR - service for lastStateTime 623s, lastActivityTime 623s
,07-27 09:03:51.935   749  1740 I ActivityManager: Killing 3944:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 652s, lastActivityTime 652s
,07-27 09:03:51.935   749  1740 I ActivityManager: Killing 3670:com.sec.android.pagebuddynotisvc/u0a27 (adj 8): SSR - service for lastStateTime 653s, lastActivityTime 653s
,07-27 09:03:52.025   291   291 I ServiceManager: service 'AtCmdFwd' died
,07-27 09:03:52.025   371  4857 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-27 09:03:52.035   371  4857 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:03:52.045   749  2079 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-27 09:03:52.045   749  2079 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-27 09:03:52.045   749  2079 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-27 09:03:52.075   749  1712 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
07-27 09:03:52.075   749  1712 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,07-27 09:03:52.085   749  1747 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,07-27 09:03:52.085   749  1747 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,07-27 09:03:52.095   749  1567 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,07-27 09:03:52.095   749  1567 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-27 09:03:52.105   749  1567 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10941ms
,07-27 09:03:52.105  5454  5454 D HealthConsole: Service for HealthDataStore is disconnected
,07-27 09:03:52.115   749  1320 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,07-27 09:03:52.115   749  1320 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-27 09:03:52.115   749  1320 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20928ms
,07-27 09:03:52.125   749  1414 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
07-27 09:03:52.125   749  1414 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-27 09:03:52.125   749  1414 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 30915ms
07-27 09:03:52.125   749  1414 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-27 09:03:52.125   749  1414 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 40915ms
,07-27 09:03:52.165  7242  7242 E Zygote  : v2
07-27 09:03:52.165  7242  7242 I libpersona: KNOX_SDCARD checking this for 10035
07-27 09:03:52.165  7242  7242 I libpersona: KNOX_SDCARD not a persona
,07-27 09:03:52.165  7242  7242 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 09:03:52.165   749  1740 I ActivityManager: Start proc 7242:com.sec.android.app.shealth:remote/u0a35 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
07-27 09:03:52.165  7242  7242 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:03:52.165  7242  7242 E Zygote  : accessInfo : 0
,07-27 09:03:52.165  7242  7242 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-27 09:03:52.205  7242  7242 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:03:52.205  7242  7242 D ActivityThread: Added TimaKeyStore provider
,07-27 09:03:52.245  7242  7242 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-27 09:03:52.295  7242  7242 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-27 09:03:52.305  7242  7242 I MultiDex: VM with version 2.1.0 has multidex support
07-27 09:03:52.305  7242  7242 I MultiDex: install
07-27 09:03:52.305  7242  7242 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-27 09:03:52.305  7242  7242 I MultiDex: install
07-27 09:03:52.305  7242  7242 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 09:03:52.545   749  1415 I ActivityManager: Start proc 7262:com.sec.android.service.health/u0a17 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,07-27 09:03:52.555  7262  7262 E Zygote  : v2
07-27 09:03:52.555  7262  7262 I libpersona: KNOX_SDCARD checking this for 10017
07-27 09:03:52.555  7262  7262 I libpersona: KNOX_SDCARD not a persona
,07-27 09:03:52.565  7262  7262 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:03:52.565  7262  7262 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:03:52.575  7262  7262 E Zygote  : accessInfo : 0
,07-27 09:03:52.575  7262  7262 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,07-27 09:03:52.645  7262  7262 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:03:52.645  7262  7262 D ActivityThread: Added TimaKeyStore provider
,07-27 09:03:52.695  7262  7262 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,07-27 09:03:52.765  7242  7242 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-27 09:03:52.765  7242  7242 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-27 09:03:52.825  1379  1379 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-27 09:03:52.825   749   761 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10035
,07-27 09:03:52.835   749  2079 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10035
,07-27 09:03:52.845  1379  1379 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{a12d46a VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,07-27 09:03:52.845  1379  1379 D AdaptiveEventManager: M updateContainers()
07-27 09:03:52.845  1379  1379 D AdaptiveEventContainerSmall: C updatePedoContainer()
,07-27 09:03:52.845  1379  1379 D AdaptiveEventContainerSmall: handlePedoUpdate()
,07-27 09:03:52.845   749  1733 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10035
,07-27 09:03:52.845  1379  1379 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-27 09:03:52.855   749  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10035
,07-27 09:03:52.905  7242  7242 I Health.HealthService: HealthService: onCreate() start (7242)
,07-27 09:03:53.035   371  4857 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:03:53.035  5454  5454 D HealthDataStore: Service for HealthDataStore is connected
,07-27 09:03:53.045  5454  5454 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-27 09:03:53.085  7280  7280 E Zygote  : v2
07-27 09:03:53.085  7280  7280 I libpersona: KNOX_SDCARD checking this for 1000
07-27 09:03:53.085  7280  7280 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 09:03:53.085  7280  7280 I libpersona: KNOX_SDCARD not a persona
07-27 09:03:53.085  7280  7280 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 09:03:53.085   749   826 I ActivityManager: Start proc 7280:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
07-27 09:03:53.085  7280  7280 E Zygote  : accessInfo : 0
,07-27 09:03:53.125  5454  5454 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-27 09:03:53.125  5454  5454 E HealthDataStore: disconnectService: Context instance is invalid
,07-27 09:03:53.135  7280  7280 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:03:53.135  7280  7280 D ActivityThread: Added TimaKeyStore provider
,07-27 09:03:53.155   749  1747 I ActivityManager: Killing 6019:com.sec.kidsplat.installer/u0a166 (adj 15): DHA:empty #37
,07-27 09:03:53.165  7280  7280 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-27 09:03:53.175   749  1320 D ActivityManager: isAutoRunBlockedApp:: com.sec.kidsplat.installer, Auto Run ON
,07-27 09:03:53.195  7280  7280 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-27 09:03:53.205  7280  7280 D AtFwdService: onCreate method
07-27 09:03:53.205  7280  7280 I AtFwdService: Instantiate AtCmdFwd Service
,07-27 09:03:53.215  7280  7310 D AtCkpdCmdHandler: De-queing command
,07-27 09:03:53.235  7242  7242 D HealthDataStore: Service for HealthDataStore is connected
,07-27 09:03:53.245  7242  7242 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-27 09:03:53.245  7242  7242 D HealthConsole: Service for HealthDataConsole is connected
,07-27 09:03:53.245  7242  7242 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-27 09:03:53.245  7242  7242 E HealthDataStore: disconnectService: Context instance is invalid
,07-27 09:03:53.385  7242  7279 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-27 09:03:53.415   749   759 I art     : Background partial concurrent mark sweep GC freed 70940(6MB) AllocSpace objects, 261(5MB) LOS objects, 27% free, 41MB/57MB, paused 2.465ms total 165.607ms
,07-27 09:03:53.435  7242  7313 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-27 09:03:53.445  7262  7274 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-27 09:03:53.455   388   388 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10017, gid 10017, pid 7262
07-27 09:03:53.455   388   388 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,07-27 09:03:53.725  7262  7274 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,07-27 09:03:53.755  7242  7313 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-27 09:03:54.055  7242  7313 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-27 09:03:54.055  7242  7313 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-27 09:03:54.455   388   388 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,07-27 09:03:54.515  7262  7274 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,07-27 09:03:54.515  7262  7274 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,07-27 09:03:54.525  7262  7274 D HSCheck : SS_G-2d de 1c 15 c8 bf 9d d9 69 c1 84 f0 50 9f a4 42 
,07-27 09:03:57.515   749  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:57.515   749  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:03:57.525   749  1740 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:03:57.525   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:03:57.545   749   749 I MotionRecognitionService: Plugged
,07-27 09:03:57.545   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:03:57.545   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:03:57.545   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:03:57.555   749  1740 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,07-27 09:03:57.555   749  1740 D BatteryService: stay LED for fully charged
,07-27 09:03:57.555  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:57.555  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:03:57.555  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:03:57.575  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:03:57.575  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:03:57.585  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:57.585  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:03:57.585  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:01.215   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:04:03.105   749   826 I ActivityManager: Start proc 7336:com.sec.android.pagebuddynotisvc/u0a27 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-27 09:04:03.125  7336  7336 E Zygote  : v2
,07-27 09:04:03.125  7336  7336 I libpersona: KNOX_SDCARD checking this for 10027
07-27 09:04:03.125  7336  7336 I libpersona: KNOX_SDCARD not a persona
,07-27 09:04:03.125  7336  7336 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:04:03.125  7336  7336 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:04:03.125  7336  7336 E Zygote  : accessInfo : 0
,07-27 09:04:03.125  7336  7336 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-27 09:04:03.175  7336  7336 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:04:03.175  7336  7336 D ActivityThread: Added TimaKeyStore provider
,07-27 09:04:03.195  7336  7336 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-27 09:04:03.215  7336  7336 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-27 09:04:03.235  7336  7336 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-27 09:04:03.235  7336  7336 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-27 09:04:11.315   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:04:13.105   749   826 I ActivityManager: Start proc 7357:com.sec.android.daemonapp/u0a182 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
07-27 09:04:13.105   749  1323 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 09:04:13.115  7357  7357 E Zygote  : v2
,07-27 09:04:13.115  7357  7357 I libpersona: KNOX_SDCARD checking this for 10182
07-27 09:04:13.115  7357  7357 I libpersona: KNOX_SDCARD not a persona
,07-27 09:04:13.115  7357  7357 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:04:13.115  7357  7357 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:04:13.125  7357  7357 E Zygote  : accessInfo : 0
,07-27 09:04:13.125  7357  7357 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-27 09:04:13.175  7357  7357 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:04:13.175  7357  7357 D ActivityThread: Added TimaKeyStore provider
,07-27 09:04:13.195   749  1323 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-27 09:04:13.205  7357  7357 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-27 09:04:13.225  7357  7357 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-27 09:04:13.255  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-27 09:04:13.265  7357  7357 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:04:13.275   749   826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{863ebfa u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cdd5ab 7357:com.sec.android.daemonapp/u0a182}
,07-27 09:04:13.275   749  1568 E Watchdog: !@Sync 23 [07-27 09:04:13.284]
,07-27 09:04:13.285  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-27 09:04:13.285  7357  7357 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:04:13.285  7357  7357 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,07-27 09:04:13.285  7357  7357 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:04:13.295  7357  7357 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-27 09:04:13.295  7357  7357 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:04:13.315  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:04:13.315  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-27 09:04:13.315  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-27 09:04:13.315  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:04:13.315  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:04:13.315  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-27 09:04:13.325  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-27 09:04:13.345  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-27 09:04:13.345  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:04:13.345  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:04:13.355  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-27 09:04:13.355  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-27 09:04:13.355  7357  7357 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:04:13.355  7357  7357 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:04:13.365  7357  7357 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-27 09:04:13.365  7357  7357 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:04:13.365  7357  7357 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:04:13.365  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-27 09:04:13.365  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-27 09:04:13.365  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-27 09:04:13.365  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:04:13.365  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-27 09:04:13.365  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:04:13.365  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:04:13.375   749  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e122187 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cdd5ab 7357:com.sec.android.daemonapp/u0a182}
,07-27 09:04:13.385  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:04:13.385  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:04:13.385  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:04:13.385  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:04:13.395  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:04:13.395  7357  7357 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:04:13.395  7357  7357 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-27 09:04:13.395  7357  7357 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:04:13.395  7357  7357 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:04:13.395  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-27 09:04:13.395  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-27 09:04:13.395  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-27 09:04:13.395  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:04:13.395  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-27 09:04:13.395  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:04:13.405  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:04:13.405   749  2078 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95998b4 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cdd5ab 7357:com.sec.android.daemonapp/u0a182}
,07-27 09:04:13.415  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:04:13.415  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:04:13.415  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:04:13.425  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:04:13.425  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:04:13.425  7357  7357 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:04:13.425  7357  7357 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-27 09:04:13.425  7357  7357 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:04:13.425  7357  7357 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:04:13.425  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-27 09:04:13.425  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-27 09:04:13.425  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-27 09:04:13.425  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:04:13.425  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-27 09:04:13.425  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:04:13.435  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:04:13.435   749  2079 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6e50cdd u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cdd5ab 7357:com.sec.android.daemonapp/u0a182}
,07-27 09:04:13.445  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:04:13.445  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-27 09:04:13.445  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:04:13.455  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:04:13.455  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:04:13.455  7357  7357 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:04:13.455  7357  7357 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-27 09:04:13.465  7357  7357 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:04:13.465  7357  7357 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-27 09:04:13.465  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-27 09:04:13.465  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-27 09:04:13.465  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-27 09:04:13.465  7357  7357 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:04:13.465  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-27 09:04:13.465  7357  7357 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:04:13.465  7357  7357 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:04:21.415   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:04:27.595   749  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:27.595   749  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:04:27.595   749  1713 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:04:27.605   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:04:27.615   749   749 I MotionRecognitionService: Plugged
,07-27 09:04:27.615   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:04:27.615   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:04:27.625   749  1713 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-27 09:04:27.625   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:04:27.625   749  1713 D BatteryService: stay LED for fully charged
,07-27 09:04:27.635  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:27.635  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:04:27.635  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:27.655  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:04:27.655  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:04:27.665  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:27.665  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:27.665  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:31.475   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:04:41.545   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:04:43.285   749  1568 E Watchdog: !@Sync 24 [07-27 09:04:43.286]
,07-27 09:04:45.505  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:04:51.645   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:04:57.655   749  2079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:57.665   749  2079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:04:57.665   749  2079 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:04:57.665   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:04:57.685   749   749 I MotionRecognitionService: Plugged
,07-27 09:04:57.685   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:04:57.685   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:04:57.695   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:04:57.695   749  2079 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:04:57.695   749  2079 D BatteryService: stay LED for fully charged
,07-27 09:04:57.705  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:57.705  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:57.705  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:57.745  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:57.745  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:57.745  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:57.745  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:04:57.745  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:05:01.705   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:05:11.815   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:05:13.285   749  1568 E Watchdog: !@Sync 25 [07-27 09:05:13.292]
,07-27 09:05:21.885   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:05:27.735   749   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:05:27.735   749   762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:05:27.735   749   762 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:05:27.745   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:05:27.755   749   749 I MotionRecognitionService: Plugged
,07-27 09:05:27.755   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:05:27.765   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:05:27.765   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:05:27.775   749   762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 39ms
,07-27 09:05:27.775   749   762 D BatteryService: stay LED for fully charged
,07-27 09:05:27.795  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:27.795  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:05:27.795  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:27.815  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:05:27.815  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:05:27.815  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:27.825  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:27.825  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:31.945   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:05:42.025   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:05:43.295   749  1568 E Watchdog: !@Sync 26 [07-27 09:05:43.299]
,07-27 09:05:45.635  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:05:47.575   749  2442 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-27 09:05:47.585   749  2442 V MARsPolicyManager: updateSMDBValues
,07-27 09:05:47.585   749   872 E MARsDBManager: updateDBAll : begin --size 0
,07-27 09:05:47.595   749   872 E MARsDBManager: updateDBAll : end
,07-27 09:05:52.095   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:05:57.805   749  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:05:57.815   749  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:05:57.815   749  1747 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:05:57.815   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:05:57.825   749   749 I MotionRecognitionService: Plugged
,07-27 09:05:57.835   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:05:57.835   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:05:57.835   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:05:57.835   749  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-27 09:05:57.845   749  1747 D BatteryService: stay LED for fully charged
,07-27 09:05:57.855  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:57.855  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:57.855  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:57.885  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:57.885  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:57.895  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:57.905  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:05:57.905  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:06:02.165   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:06:12.255   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:06:13.295   749  1568 E Watchdog: !@Sync 27 [07-27 09:06:13.303]
,07-27 09:06:22.355   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:06:27.875   749  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:06:27.875   749  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:06:27.885   749  1320 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:06:27.885   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:06:27.895   749   749 I MotionRecognitionService: Plugged
,07-27 09:06:27.895   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:06:27.905   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:06:27.905   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:06:27.905   749  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:06:27.915   749  1320 D BatteryService: stay LED for fully charged
,07-27 09:06:27.925  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:06:27.925  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:06:27.935  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:06:27.945  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:06:27.945  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:06:27.955  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:27.955  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:27.955  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:32.415   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:06:42.465   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:06:43.305   749  1568 E Watchdog: !@Sync 28 [07-27 09:06:43.309]
,07-27 09:06:45.735  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:06:45.905  1716  1803 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 161ms lastUpdatedAfter : 180488ms
,07-27 09:06:52.535   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:06:57.945   749  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:06:57.945   749  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:06:57.955   749  1740 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:06:57.955   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:06:57.965   749   749 I MotionRecognitionService: Plugged
,07-27 09:06:57.965   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:06:57.975   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:06:57.975   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:06:57.985   749  1740 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:06:57.985   749  1740 D BatteryService: stay LED for fully charged
,07-27 09:06:57.985  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:06:57.985  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:06:57.985  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:06:58.005  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:06:58.005  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:06:58.015  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:58.015  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:58.015  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:02.585   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:07:12.645   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:07:13.305   749  1568 E Watchdog: !@Sync 29 [07-27 09:07:13.314]
,07-27 09:07:22.695   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:07:28.015   749  1567 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:28.025   749  1567 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:07:28.025   749  1567 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:07:28.025   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:07:28.045   749   749 I MotionRecognitionService: Plugged
,07-27 09:07:28.045   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:07:28.045   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:07:28.055   749  1567 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-27 09:07:28.055   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:07:28.055   749  1567 D BatteryService: stay LED for fully charged
,07-27 09:07:28.075   749  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:07:28.075   749  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:07:28.075   749  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:07:28.085  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:07:28.085  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:07:28.085  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:07:28.105  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:07:28.105  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:07:28.115  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:28.115  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:28.115  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:31.405   749  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:07:31.405   749  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:07:31.415   749  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:07:31.415   749  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:07:32.745   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:07:42.855   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:07:43.315   749  1568 E Watchdog: !@Sync 30 [07-27 09:07:43.318]
,07-27 09:07:45.935  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:07:52.945   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:08:03.005   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:08:05.515   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:08:05.585   749  2079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:05.605  5294  5294 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-27 09:08:05.625  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:08:05.625  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 09:08:05.625  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:08:05.645  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:08:05.645   749   826 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-27 09:08:05.655  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:08:05.665   749   749 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-27 09:08:05.665  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:05.665  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:05.675  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:05.675  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:05.675   749   749 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-27 09:08:05.685  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:05.695   749   749 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-27 09:08:05.695  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:05.695  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:05.715   749   749 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-27 09:08:05.725  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:05.745  1817  7403 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,07-27 09:08:05.755  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:05.755  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:05.795  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:05.795  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-27 09:08:05.795  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:08:05.795  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:08:05.795  1632  4034 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:08:05.795  1632  4034 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:08:05.795  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:08:05.845  5294  5294 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-27 09:08:05.845  1817  7387 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-27 09:08:05.855  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:05.865  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-27 09:08:05.865  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:08:05.865  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:08:05.865  1632  4034 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:08:05.865  1632  4034 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:08:05.865  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:08:05.895  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:05.905  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-27 09:08:05.905  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:08:05.905  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:08:05.905  1632  4034 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:08:05.905  1632  4034 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:08:05.905  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:08:05.935  5294  5294 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-27 09:08:05.995  1817  7387 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
07-27 09:08:05.995  1817  7387 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-27 09:08:06.015  1817  7387 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
07-27 09:08:06.015  1817  7387 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-27 09:08:06.075   749   898 D LightsService: [SvcLED]  onSensorChanged::light value = 18
,07-27 09:08:06.075   749   898 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-27 09:08:06.085   749   898 D SensorManager: unregisterListener ::   
,07-27 09:08:06.085   749   898 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-27 09:08:06.085   749   898 V AlarmManager:  remove PendingIntent] PendingIntent{209f16a: PendingIntentRecord{7c6465b android broadcastIntent}}
,07-27 09:08:06.095  1817  7387 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
07-27 09:08:06.095  1817  7387 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-27 09:08:06.315  1943  5314 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,07-27 09:08:06.415  1817  7387 I ContextCompilationHandl: Recognition context unchanged for APP_NAMES en-US
07-27 09:08:06.415  1817  7387 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-27 09:08:06.475  1943  5308 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-27 09:08:06.535  1943  5315 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:08:06.585  1943  3911 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:08:06.615  1943  5314 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:08:06.635  1817  7387 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,07-27 09:08:06.645  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:06.655  1632  1646 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-27 09:08:06.655  1632  1646 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:08:06.655  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:08:06.655  1632  1646 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:08:06.655  1632  1646 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:08:06.655  1632  1646 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:08:06.675  5294  5294 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-27 09:08:06.685  5294  5294 D Finsky  : [1] WearSupportService.startHygiene: disabled
,07-27 09:08:06.685  5294  5294 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-27 09:08:06.685  5294  5294 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,07-27 09:08:06.695  1632  4031 D DeviceConnectionService: client connected with version: 8296000
,07-27 09:08:13.065   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:08:13.315   749  1568 E Watchdog: !@Sync 31 [07-27 09:08:13.322]
,07-27 09:08:20.945   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:08:21.355  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:21.365  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:21.375  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:21.395  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 09:08:21.395  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:08:21.395  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:08:21.395  1632  4031 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:08:21.395  1632  4031 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:08:21.395  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:08:21.415  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 09:08:21.415  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 09:08:21.415  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,07-27 09:08:23.135   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:08:33.205   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:08:41.425   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:08:41.495   749  1567 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:41.855  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:41.865  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:41.865  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:08:41.885  1632  1646 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 09:08:41.885  1632  1646 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:08:41.885  1632  1646 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:08:41.885  1632  1646 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:08:41.885  1632  1646 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:08:41.885  1632  1646 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:08:41.895  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 09:08:41.895  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 09:08:41.895  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-27 09:08:43.325   749  1568 E Watchdog: !@Sync 32 [07-27 09:08:43.327]
,07-27 09:08:43.335   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:08:44.115   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:08:44.175  6090  6124 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-27 09:08:44.175  6090  6158 D bt_vendor: op for 7
,07-27 09:08:44.175  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:08:44.185  6090  6124 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-27 09:08:44.195  6090  6158 D bt_upio : upio_start_stop_timer : timer_settime success
07-27 09:08:44.195  6090  6158 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-27 09:08:44.195  6090  6124 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
07-27 09:08:44.195  6090  6124 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-27 09:08:44.195  6090  6158 D bt_vendor: op for 7
,07-27 09:08:44.195  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.195  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.205  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.205  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.205  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.205  6090  6158 D bt_vendor: op for 7
,07-27 09:08:44.205  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.205  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.205  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.205  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.205  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.205  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.205  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:08:44.205  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.205  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.205  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.205  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.215  6090  6158 D bt_vendor: op for 7
,07-27 09:08:44.215  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.215  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.215  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.215  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.215  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.215  6090  6158 D bt_vendor: op for 7
,07-27 09:08:44.215  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.215  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.215  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.215  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.215  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.215  6090  6158 D bt_vendor: op for 7
,07-27 09:08:44.215  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.215  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.215  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.225  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:08:44.225  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.225  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.225  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.225  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.225  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.225  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:08:44.225  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.225  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.225  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.225  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.225  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.225  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:08:44.225  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.225  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.235  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.235  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.235  6090  6158 D bt_vendor: op for 7
,07-27 09:08:44.235  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.235  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.235  6090  6158 D bt_vendor: op for 7
07-27 09:08:44.235  6090  6158 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:08:44.235  6090  6158 D bt_upio : BT_WAKE is asserted already
,07-27 09:08:44.255   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{544bb28: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.255   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{83a1041: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.255   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{4f2e9e6: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.265   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{c95db27: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.265   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{bbe61d4: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.275   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{fd66f7d: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.275   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{bf3be72: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.285   749  1320 V AlarmManager:  remove PendingIntent] PendingIntent{8fb02c3: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.285   749  1625 V AlarmManager:  remove PendingIntent] PendingIntent{389c740: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.285   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{7df8679: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.295   749  1712 V AlarmManager:  remove PendingIntent] PendingIntent{fbb4fbe: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.295   749  1415 V AlarmManager:  remove PendingIntent] PendingIntent{1081f: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.305   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{7e4176c: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.305   749  1414 V AlarmManager:  remove PendingIntent] PendingIntent{4c91135: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.315   749  1733 V AlarmManager:  remove PendingIntent] PendingIntent{d8a9ca: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.315   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{c38073b: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.325   749  1740 V AlarmManager:  remove PendingIntent] PendingIntent{8b13e58: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.325   749  1713 V AlarmManager:  remove PendingIntent] PendingIntent{4868bb1: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.335   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{7bf9896: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.335   749  2078 V AlarmManager:  remove PendingIntent] PendingIntent{715dc17: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.345   749  1747 V AlarmManager:  remove PendingIntent] PendingIntent{e27e804: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.345   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{6c731ed: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.345   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{e54a822: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.355   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{19222b3: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.355   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{b3d8070: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.355   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{cf1ffe9: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.355   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{639246e: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.365   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{a82370f: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.365   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{ad2339c: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.365   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{de1b1a5: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.375   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{7d7197a: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.375   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{eb5352b: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.375   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{39ced88: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.385   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{960c321: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.385   749   762 V AlarmManager:  remove PendingIntent] PendingIntent{62d5346: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.385   749  1746 V AlarmManager:  remove PendingIntent] PendingIntent{ecff907: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.385   749  2079 V AlarmManager:  remove PendingIntent] PendingIntent{ed75a34: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.395   749  1567 V AlarmManager:  remove PendingIntent] PendingIntent{765705d: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.395   749   761 V AlarmManager:  remove PendingIntent] PendingIntent{35b5dd2: PendingIntentRecord{84b354b com.android.bluetooth broadcastIntent}}
,07-27 09:08:44.995  6090  6233 D bt_upio : ..proc_btwrite_timeout..
,07-27 09:08:44.995  6090  6233 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-27 09:08:46.045  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:08:53.435   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:08:59.995   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 09:09:01.895   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:09:01.975  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:09:01.975  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 09:09:01.975  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:09:01.995  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:09:01.995  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:09:02.005  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:09:02.005  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:09:02.015  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:09:02.015  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:09:02.015  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:09:02.025  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:09:02.025  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:09:02.085  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:09:02.665  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:09:02.675  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:09:02.675  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:09:02.705  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 09:09:02.705  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:09:02.705  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:09:02.705  1632  4031 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:09:02.705  1632  4031 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:09:02.705  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:09:02.735  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 09:09:02.735  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 09:09:02.735  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-27 09:09:03.495   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:09:11.585   749   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:09:13.325   749  1568 E Watchdog: !@Sync 33 [07-27 09:09:13.332]
,07-27 09:09:13.575   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:09:22.735   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:09:23.015   749   759 I art     : Background partial concurrent mark sweep GC freed 49004(4MB) AllocSpace objects, 160(3MB) LOS objects, 27% free, 42MB/58MB, paused 3.302ms total 176.654ms
,07-27 09:09:23.255  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:09:23.265  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:09:23.275  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:09:23.295  1632  2978 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 09:09:23.295  1632  2978 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:09:23.295  1632  2978 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:09:23.295  1632  2978 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:09:23.295  1632  2978 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:09:23.295  1632  2978 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:09:23.315  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 09:09:23.325  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 09:09:23.325  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-27 09:09:23.615   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:09:23.685   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:09:23.725  6458  7497 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 09:09:23.765  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 09:09:23.765  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:09:23.765  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:09:23.765  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:09:23.765  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:09:23.765  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:09:23.765  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:09:23.765  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:09:23.765  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:09:23.765  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:09:23.765  1632  4031 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 09:09:23.765  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:09:23.815  1632  4034 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-27 09:09:23.815  1632  4034 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:09:23.815  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:09:23.815  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:09:23.815  1632  4034 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:09:23.815  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:09:23.815  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:09:23.815  1632  4034 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:09:23.815  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:09:23.815  1632  4034 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:09:23.815  1632  4034 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 09:09:23.815  1632  4034 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:09:23.825  6458  7498 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 09:09:23.835  6458  7497 E BooksSync: Soft error
07-27 09:09:23.835  6458  7497 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:09:23.835  6458  7497 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-27 09:09:23.835  6458  7497 E BooksSync: Sync error
07-27 09:09:23.835  6458  7497 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:09:23.835  6458  7497 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-27 09:09:23.845  6458  7497 I BooksSync: Finished books sync
,07-27 09:09:23.845  6458  7500 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-27 09:09:23.845  6458  7500 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-27 09:09:23.855  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-27 09:09:23.855  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:09:23.855  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:09:23.855  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:09:23.855  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:09:23.855  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:09:23.855  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:09:23.855  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:09:23.855  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:09:23.855  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:09:23.855  1632  4031 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-27 09:09:23.855  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:09:23.875  6458  7500 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: Failed to register token for device group
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-27 09:09:23.875  6458  7500 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 09:09:23.895   749   821 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1031272, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:09:23.925   749   821 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 09:09:23.935  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 09:09:23.935  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 09:09:23.935  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 09:09:23.935  3085  3100 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 09:09:23.935   749  2078 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 09:09:33.735   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:09:43.335   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:09:43.345   749  1568 E Watchdog: !@Sync 34 [07-27 09:09:43.339]
,07-27 09:09:43.405   749  2079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:09:43.405   749  2079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:09:43.415   749  2079 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:09:43.415   749  2079 D BatteryService: stay LED for fully charged
,07-27 09:09:43.425   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:09:43.435   749   749 I MotionRecognitionService: Plugged
,07-27 09:09:43.435   749   749 D MotionRecognitionService:   cableConnection= 1
07-27 09:09:43.435   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:09:43.435   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:09:43.435  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:09:43.435  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:09:43.435  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:09:43.455  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:09:43.455  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:09:43.465  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:43.465  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:09:43.465  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:43.775   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:09:43.915  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:09:43.935  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:09:43.935  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:09:43.975  1632  1645 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 09:09:43.975  1632  1645 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:09:43.975  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:09:43.975  1632  1645 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:09:43.975  1632  1645 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:09:43.975  1632  1645 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:09:44.015  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 09:09:44.015  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 09:09:44.015  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-27 09:09:46.115  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:09:53.845   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:09:59.995   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 09:10:03.895   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:10:04.025   749  1235 V AlarmManager: Expired Alarm result :4
,07-27 09:10:04.105  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:10:04.105  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 09:10:04.105  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:10:04.115  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:10:04.115  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:10:04.135  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:10:04.135  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:10:04.135  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:10:04.135  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:10:04.135  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:10:04.145  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:10:04.145  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:10:04.205  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:10:04.815  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:10:04.835  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:10:04.835  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:10:04.875  1632  4031 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-27 09:10:04.875  1632  4031 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-27 09:10:04.875  1632  4031 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-27 09:10:04.875  1632  4031 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:10:04.875  1632  4031 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:10:04.875  1632  4031 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:10:04.925  5294  5294 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 09:10:04.925  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 09:10:04.925  5294  5294 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-27 09:10:13.345   749  1568 E Watchdog: !@Sync 35 [07-27 09:10:13.353]
,07-27 09:10:13.495   749  1746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:10:13.495   749  1746 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:10:13.495   749  1746 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:10:13.505   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:10:13.515   749   749 I MotionRecognitionService: Plugged
,07-27 09:10:13.515   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:10:13.515   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:10:13.515   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:10:13.525   749  1746 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:10:13.525   749  1746 D BatteryService: stay LED for fully charged
,07-27 09:10:13.535  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:10:13.535  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:10:13.535  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:10:13.555  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:10:13.555  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:10:13.565  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:13.565  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:10:13.565  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:13.955   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:10:24.005   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:10:34.065   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:10:43.355   749  1568 E Watchdog: !@Sync 36 [07-27 09:10:43.359]
,07-27 09:10:43.565   749  2078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:10:43.575   749  2078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:10:43.575   749  2078 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:10:43.575   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:10:43.585   749   749 I MotionRecognitionService: Plugged
,07-27 09:10:43.595   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:10:43.595   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:10:43.595   749  2078 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,07-27 09:10:43.595   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:10:43.605   749  2078 D BatteryService: stay LED for fully charged
,07-27 09:10:43.625  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:10:43.625  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:10:43.625  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:10:43.645  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:10:43.645  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:10:43.655  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:43.655  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:43.655  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:44.125   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:10:46.185  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:10:54.215   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:10:59.995   749  1235 V AlarmManager: Expired Alarm result :8
,07-27 09:11:04.295   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:11:13.355   749  1568 E Watchdog: !@Sync 37 [07-27 09:11:13.363]
,07-27 09:11:13.645   749   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:11:13.655   749   762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:11:13.655   749   762 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:11:13.655   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:11:13.665   749   749 I MotionRecognitionService: Plugged
,07-27 09:11:13.675   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:11:13.675   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:11:13.685   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:11:13.685   749   762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-27 09:11:13.685   749   762 D BatteryService: stay LED for fully charged
,07-27 09:11:13.685  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:11:13.685  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:11:13.685  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:11:13.705  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:11:13.705  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:11:13.715  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:13.715  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:11:13.715  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:14.345   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:11:24.445   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:11:34.505   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:11:43.365   749  1568 E Watchdog: !@Sync 38 [07-27 09:11:43.368]
,07-27 09:11:43.725   749  1414 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:11:43.725   749  1414 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:11:43.735   749  1414 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:11:43.745   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:11:43.765   749   749 I MotionRecognitionService: Plugged
,07-27 09:11:43.765   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:11:43.765   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:11:43.765   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:11:43.775   749  1414 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 46ms
,07-27 09:11:43.775   749  1414 D BatteryService: stay LED for fully charged
,07-27 09:11:43.785  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:11:43.785  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:11:43.785  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:11:43.805  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:11:43.805  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:11:43.805  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:43.805  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:11:43.805  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:44.565   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:11:46.305  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:11:46.485  1716  1803 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 2Kb duration : 153ms lastUpdatedAfter : 142523ms
,07-27 09:11:54.665   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:12:04.755   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:12:04.925  1632  3199 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:12:13.365   749  1568 E Watchdog: !@Sync 39 [07-27 09:12:13.372]
,07-27 09:12:13.805   749  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:12:13.815   749  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:12:13.815   749  1747 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:12:13.815   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:12:13.825   749   749 I MotionRecognitionService: Plugged
,07-27 09:12:13.835   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:12:13.835   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:12:13.835   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:12:13.845   749  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-27 09:12:13.845   749  1747 D BatteryService: stay LED for fully charged
,07-27 09:12:13.855  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:12:13.855  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:12:13.855  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:12:13.885  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:12:13.885  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:12:13.885  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:12:13.895  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:12:13.895  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:12:14.805   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:12:24.865   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:12:28.075   749  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:12:28.075   749  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:12:28.075   749  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:12:29.575   749  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:12:29.575   749  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:12:29.585   749  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:12:29.585   749  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:12:34.955   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:12:40.125   749   821 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:12:43.375   749  1568 E Watchdog: !@Sync 40 [07-27 09:12:43.377]
,07-27 09:12:43.895   749  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:12:45.035   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:12:46.555  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:12:55.085   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:13:05.175   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:13:13.375   749  1568 E Watchdog: !@Sync 41 [07-27 09:13:13.381]
,07-27 09:13:13.975   749  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:13:13.975   749  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:13:13.985   749  1713 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:13:13.985   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:13:14.005   749   749 I MotionRecognitionService: Plugged
,07-27 09:13:14.005   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:13:14.005   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:13:14.005   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:13:14.015   749  1713 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-27 09:13:14.015   749  1713 D BatteryService: stay LED for fully charged
,07-27 09:13:14.035  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:13:14.035  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:13:14.035  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:13:14.045  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:13:14.045  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:13:14.055  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:14.055  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:14.055  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:15.225   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:13:25.305   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:13:35.395   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:13:43.385   749  1568 E Watchdog: !@Sync 42 [07-27 09:13:43.385]
,07-27 09:13:44.065   749  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:13:44.065   749  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:13:44.065   749  1415 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:13:44.075   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:13:44.085   749   749 I MotionRecognitionService: Plugged
,07-27 09:13:44.085   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:13:44.095   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:13:44.095   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:13:44.095   749  1415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:13:44.095   749  1415 D BatteryService: stay LED for fully charged
,07-27 09:13:44.105  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:13:44.115  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:13:44.115  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:13:44.145  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:44.145  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:44.145  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:44.155  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:13:44.155  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:13:45.445   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:13:46.645  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:13:55.555   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:14:05.605   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:14:13.385   749  1568 E Watchdog: !@Sync 43 [07-27 09:14:13.391]
,07-27 09:14:14.135   749  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:14:15.695   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:14:25.785   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:14:35.865   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:14:43.395   749  1568 E Watchdog: !@Sync 44 [07-27 09:14:43.395]
,07-27 09:14:44.215   749  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:14:45.955   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:14:46.685  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:14:46.825  1716  1803 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 130ms lastUpdatedAfter : 180348ms
,07-27 09:14:56.025   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:15:06.105   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:15:13.395   749  1568 E Watchdog: !@Sync 45 [07-27 09:15:13.401]
,07-27 09:15:14.295   749  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:15:14.305   749  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:15:14.305   749  1747 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:15:14.305   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:15:14.325   749   749 I MotionRecognitionService: Plugged
,07-27 09:15:14.325   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:15:14.325   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:15:14.335   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:15:14.335   749  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:15:14.335   749  1747 D BatteryService: stay LED for fully charged
,07-27 09:15:14.335  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:15:14.335  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:15:14.335  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:15:14.355  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:15:14.355  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:15:14.365  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:14.365  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:14.365  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:16.155   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:15:26.215   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:15:36.265   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:15:43.405   749  1568 E Watchdog: !@Sync 46 [07-27 09:15:43.406]
,07-27 09:15:44.375   749  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:15:44.385   749  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:15:44.385   749  1740 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:15:44.385   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:15:44.395   749   749 I MotionRecognitionService: Plugged
,07-27 09:15:44.405   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:15:44.405   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:15:44.405   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:15:44.415   749  1740 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-27 09:15:44.415   749  1740 D BatteryService: stay LED for fully charged
,07-27 09:15:44.435  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:15:44.435  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:15:44.435  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:15:44.445  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:15:44.455  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:15:44.455  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:44.455  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:44.455  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:46.325   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:15:46.885  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:15:56.385   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:16:06.475   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:16:13.415   749  1568 E Watchdog: !@Sync 47 [07-27 09:16:13.416]
,07-27 09:16:14.455   749  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:16:14.465   749  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:16:14.465   749  1415 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-27 09:16:14.465   749   749 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:16:14.485   749   749 I MotionRecognitionService: Plugged
,07-27 09:16:14.485   749   749 D MotionRecognitionService:   cableConnection= 1
,07-27 09:16:14.485   749   749 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:16:14.485   749   749 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:16:14.495   749  1415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 09:16:14.495   749  1415 D BatteryService: stay LED for fully charged
,07-27 09:16:14.505  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:16:14.505  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:16:14.515  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:16:14.535  6090  6090 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:16:14.535  6090  6237 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:16:14.545  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:16:14.545  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:16:14.545  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:16:16.525   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:16:26.585   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:16:36.645   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:16:43.415   749  1568 E Watchdog: !@Sync 48 [07-27 09:16:43.421]
,07-27 09:16:44.535   749  1746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:16:46.705   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-27 09:16:46.995  1716  1803 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:16:56.765   749  3343 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,TIME-OUT KILL (timeout was 1400000ms)
```
