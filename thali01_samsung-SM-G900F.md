#### Test 82337235d68dad2_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
08-23 13:27:12.022   763  3742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
08-23 13:27:12.402  5659  5659 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-23 13:27:12.402  5659  5659 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-23 13:27:12.402  5659  5659 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-23 13:27:12.412  5659  5659 I art     : System.exit called, status: 0
08-23 13:27:12.412  5659  5659 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-23 13:27:12.442   763  2450 I ActivityManager: Process com.samsung.aasaservice (pid 5659)(adj 0) has died(98,732)
08-23 13:27:12.442   763  2450 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-23 13:27:12.442   763  2450 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-23 13:27:12.442   763  2450 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-23 13:27:12.452  5626  5626 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-23 13:27:12.462   763   862 I ActivityManager: Start proc 6549:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-23 13:27:12.462   763  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 13:27:12.462  6549  6549 E Zygote  : v2
08-23 13:27:12.462  6549  6549 I libpersona: KNOX_SDCARD checking this for 10014
08-23 13:27:12.462  6549  6549 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:12.472  6549  6549 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:12.472  6549  6549 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:12.472  6549  6549 E Zygote  : accessInfo : 0
08-23 13:27:12.472  6549  6549 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-23 13:27:12.492  6549  6549 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:12.492  6549  6549 D ActivityThread: Added TimaKeyStore provider
08-23 13:27:12.502   763  1624 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a8a36d 6549:com.google.android.partnersetup/u0a14}
08-23 13:27:12.502   763  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-23 13:27:12.512  6549  6549 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-23 13:27:12.522  6549  6549 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-23 13:27:12.542   763  1621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a8a36d 6549:com.google.android.partnersetup/u0a14}
08-23 13:27:12.562  6566  6566 E Zygote  : v2
08-23 13:27:12.562   763  2450 I ActivityManager: Start proc 6566:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-23 13:27:12.562  6566  6566 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:12.562  6566  6566 I libpersona: KNOX_SDCARD checking this for 10015
08-23 13:27:12.562  6566  6566 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:12.562  6566  6566 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:12.562  6566  6566 E Zygote  : accessInfo : 0
08-23 13:27:12.562  6566  6566 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-23 13:27:12.582   763  2472 I ActivityManager: Killing 5694:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
08-23 13:27:12.592   763  1730 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
08-23 13:27:12.592  6566  6566 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:12.592  6566  6566 D ActivityThread: Added TimaKeyStore provider
08-23 13:27:12.602   763  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77cbff0 6566:com.samsung.groupcast/u0a15}
08-23 13:27:12.612  6566  6566 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-23 13:27:12.632  6566  6566 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-23 13:27:12.652  6566  6566 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-23 13:27:12.652  6566  6566 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-23 13:27:12.652  6566  6566 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-23 13:27:12.652  6566  6566 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-23 13:27:12.652  6566  6566 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-23 13:27:12.652  6566  6566 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 13:27:12.652  6566  6566 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 13:27:12.652  6566  6566 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 13:27:12.652  6566  6566 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 13:27:12.652  6566  6566 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:27:12.652  6566  6566 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 13:27:12.652  6566  6566 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 13:27:12.652  6566  6566 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:27:12.652  6566  6566 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 13:27:12.652  6566  6566 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 13:27:12.662   763  1638 I ActivityManager: Killing 5613:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #37
08-23 13:27:12.662   763  1638 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{93f5495 1999:com.sec.android.app.shealth:remote/u0a34}
08-23 13:27:12.672  6578  6578 E Zygote  : v2
08-23 13:27:12.672  6578  6578 I libpersona: KNOX_SDCARD checking this for 10041
08-23 13:27:12.672  6578  6578 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:12.672  6578  6578 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:12.672  6578  6578 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:12.672   763  1730 I ActivityManager: Start proc 6578:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-23 13:27:12.682  6578  6578 E Zygote  : accessInfo : 0
08-23 13:27:12.682  6578  6578 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-23 13:27:12.682   763  1731 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
08-23 13:27:12.712  6578  6578 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:12.712  6578  6578 D ActivityThread: Added TimaKeyStore provider
08-23 13:27:12.722   763   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6390969 6578:com.samsung.android.sdk.samsunglink/u0a41}
08-23 13:27:12.722  6578  6578 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-23 13:27:12.802  6578  6578 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 13:27:12.802  6578  6578 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-23 13:27:12.852  6578  6578 I SL_DEBUG: isLoggable:: isProductShip = 1
08-23 13:27:12.862  6578  6578 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-23 13:27:12.872   763  1730 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-23 13:27:12.872   763  2450 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-23 13:27:12.872   763  2147 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-23 13:27:12.872   763  1252 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-23 13:27:12.872   763  2501 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-23 13:27:12.882   763  2146 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-23 13:27:12.882   763  2472 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-23 13:27:12.882   763  1731 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-23 13:27:12.882   763  2526 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-23 13:27:12.882   763  2448 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-23 13:27:12.962  2424  2424 E audit   : type=1400 msg=audit(1471951632.962:285): avc:  denied  { execmod } for  pid=6545 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:27:12.962  2424  2424 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:12.962  2424  2424 E audit   : type=1300 msg=audit(1471951632.962:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4023000 a1=51000 a2=5 a3=4 items=0 ppid=3851 ppcomm=adbd pid=6545 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:27:12.962  2424  2424 E audit   : type=1327 msg=audit(1471951632.962:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 13:27:12.962  2424  2424 E audit   : type=1320 msg=audit(1471951632.962:285): 
08-23 13:27:12.982  6578  6578 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-23 13:27:12.992  6578  6578 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-23 13:27:12.992  6578  6578 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-23 13:27:12.992  6578  6578 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-23 13:27:12.992  6578  6578 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-23 13:27:12.992  6578  6578 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-23 13:27:12.992  6578  6578 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-23 13:27:12.992  6578  6578 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-23 13:27:12.992  6578  6578 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-23 13:27:12.992  6578  6578 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-23 13:27:12.992  6578  6578 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:27:12.992  6578  6578 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 13:27:12.992  6578  6578 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 13:27:12.992  6578  6578 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:27:12.992  6578  6578 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 13:27:12.992  6578  6578 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 13:27:12.992   763  2146 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ac9b019 1629:android.process.acore/u0a19}
08-23 13:27:13.002   763  2472 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cccdf60 5341:com.sec.android.gallery3d/u0a47}
08-23 13:27:13.012  5341  5341 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-23 13:27:13.012  2424  2424 E audit   : type=1400 msg=audit(1471951633.012:286): avc:  denied  { execmod } for  pid=6545 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:27:13.012  2424  2424 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:13.012  2424  2424 E audit   : type=1300 msg=audit(1471951633.012:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe3000 a1=51000 a2=5 a3=4 items=0 ppid=3851 ppcomm=adbd pid=6545 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:27:13.022  2424  2424 E audit   : type=1327 msg=audit(1471951633.012:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 13:27:13.022  2424  2424 E audit   : type=1320 msg=audit(1471951633.012:286): 
08-23 13:27:13.022   763  1621 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-23 13:27:13.042   763  1624 I ActivityManager: Start proc 6601:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-23 13:27:13.042  6601  6601 E Zygote  : v2
08-23 13:27:13.042  6601  6601 I libpersona: KNOX_SDCARD checking this for 10050
08-23 13:27:13.042  6601  6601 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:13.042  6601  6601 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:13.042  6601  6601 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:13.042  6601  6601 E Zygote  : accessInfo : 0
08-23 13:27:13.042  6601  6601 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-23 13:27:13.072  2424  2424 E audit   : type=1400 msg=audit(1471951633.072:287): avc:  denied  { execmod } for  pid=6545 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:27:13.072  2424  2424 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:13.072  2424  2424 E audit   : type=1300 msg=audit(1471951633.072:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe3000 a1=51000 a2=5 a3=4 items=0 ppid=3851 ppcomm=adbd pid=6545 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:27:13.072  2424  2424 E audit   : type=1327 msg=audit(1471951633.072:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 13:27:13.072  2424  2424 E audit   : type=1320 msg=audit(1471951633.072:287): 
08-23 13:27:13.072  6545  6545 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 13:27:13.072  6545  6545 D AndroidRuntime: CheckJNI is OFF
08-23 13:27:13.072  6545  6545 D AndroidRuntime: readGMSProperty: start
08-23 13:27:13.072  6545  6545 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:27:13.072  6545  6545 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:27:13.072  6545  6545 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:27:13.072  6545  6545 D AndroidRuntime: readGMSProperty: end
08-23 13:27:13.072  6545  6545 D AndroidRuntime: addProductProperty: start
08-23 13:27:13.082  6601  6601 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:13.082  6601  6601 D ActivityThread: Added TimaKeyStore provider
08-23 13:27:13.082  6545  6545 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:27:13.082  6545  6545 W art     : aee4a000-b1d70000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:27:13.082  6545  6545 W art     : b1d70000-b3fdf000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:27:13.082  6545  6545 W art     : b3fdf000-b3fe0000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:27:13.082  6545  6545 W art     : b3fe0000-b3fe1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 13:27:13.082  6545  6545 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 13:27:13.082  6545  6545 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 13:27:13.082  6545  6545 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 13:27:13.082  6545  6545 W art     : b4889000-b48b2000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:27:13.082  6545  6545 W art     : b48b2000-b48b5000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:27:13.082  6545  6545 W art     : b48b5000-b48b6000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:27:13.082  6545  6545 W art     : b48b6000-b48b7000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:27:13.082  6545  6545 W art     : b48b7000-b48b8000 r--p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b48b8000-b48d8000 r--s 00000000 00:0b 6700       /dev/__properties__
08-23 13:27:13.082  6545  6545 W art     : b48d8000-b52e9000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:27:13.082  6545  6545 W art     : b52e9000-b52ea000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b52ea000-b5333000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:27:13.082  6545  6545 W art     : b5333000-b5334000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:27:13.082  6545  6545 W art     : b5334000-b533c000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b533c000-b533d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b533d000-b5372000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:27:13.082  6545  6545 W art     : b5372000-b5373000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5373000-b5374000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:27:13.082  6545  6545 W art     : b5374000-b5375000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:27:13.082  6545  6545 W art     : b5375000-b53cd000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 13:27:13.082  6545  6545 W art     : b53cd000-b53ce000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b53ce000-b53cf000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 13:27:13.082  6545  6545 W art     : b53cf000-b53d0000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 13:27:13.082  6545  6545 W art     : b53d1000-b53d7000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:27:13.082  6545  6545 W art     : b53d7000-b53d8000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:27:13.082  6545  6545 W art     : b53d8000-b53d9000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:27:13.082  6545  6545 W art     : b53d9000-b53db000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b53dc000-b53e6000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:27:13.082  6545  6545 W art     : b53e6000-b53e9000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:27:13.082  6545  6545 W art     : b53e9000-b53ea000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:27:13.082  6545  6545 W art     : b53eb000-b5402000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:27:13.082  6545  6545 W art     : b5402000-b5403000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5403000-b5404000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:27:13.082  6545  6545 W art     : b5404000-b5405000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:27:13.082  6545  6545 W art     : b5406000-b5410000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:27:13.082  6545  6545 W art     : b5410000-b5411000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:27:13.082  6545  6545 W art     : b5411000-b5412000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:27:13.082  6545  6545 W art     : b5412000-b5416000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:27:13.082  6545  6545 W art     : b5416000-b5417000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:27:13.082  6545  6545 W art     : b5417000-b5418000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:27:13.082  6545  6545 W art     : b5418000-b542e000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 13:27:13.082  6545  6545 W art     : b542e000-b542f000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 13:27:13.082  6545  6545 W art     : b542f000-b5430000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 13:27:13.082  6545  6545 W art     : b5430000-b543d000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:27:13.082  6545  6545 W art     : b543d000-b543e000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:27:13.082  6545  6545 W art     : b543e000-b543f000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:27:13.082  6545  6545 W art     : b543f000-b549f000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 13:27:13.082  6545  6545 W art     : b549f000-b54a2000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 13:27:13.082  6545  6545 W art     : b54a2000-b54a6000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b54a6000-b5507000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:27:13.082  6545  6545 W art     : b5507000-b5508000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:27:13.082  6545  6545 W art     : b5508000-b5557000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:27:13.082  6545  6545 W art     : b5557000-b5559000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:27:13.082  6545  6545 W art     : b5559000-b555a000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:27:13.082  6545  6545 W art     : b555a000-b555b000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b555b000-b5562000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:27:13.082  6545  6545 W art     : b5562000-b5563000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:27:13.082  6545  6545 W art     : b5563000-b5564000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-23 13:27:13.082  6545  6545 W art     : avc_common.so
08-23 13:27:13.082  6545  6545 W art     : b5565000-b5568000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:27:13.082  6545  6545 W art     : b5568000-b5569000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:27:13.082  6545  6545 W art     : b5569000-b556a000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-23 13:27:13.082  6545  6545 W art     : enc_common.so
08-23 13:27:13.082  6545  6545 W art     : b556b000-b556f000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:27:13.082  6545  6545 W art     : b556f000-b5570000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5570000-b5571000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:27:13.082  6545  6545 W art     : b5571000-b5572000 rw-p 00005000 b3:17 2510       /syste
08-23 13:27:13.082  6545  6545 W art     : m/lib/libpowermanager.so
08-23 13:27:13.082  6545  6545 W art     : b5573000-b5590000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:27:13.082  6545  6545 W art     : b5590000-b5591000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:27:13.082  6545  6545 W art     : b5591000-b5592000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:27:13.082  6545  6545 W art     : b5593000-b5598000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:27:13.082  6545  6545 W art     : b5598000-b5599000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:27:13.082  6545  6545 W art     : b5599000-b559a000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:27:13.082  6545  6545 W art     : b559b000-b55cc000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:27:13.082  6545  6545 W art     : b55cc000-b55cf000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:27:13.082  6545  6545 W art     : b55cf000-b55d0000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:27:13.082  6545  6545 W art     : b55d1000-b560c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 13:27:13.082  6545  6545 W art     : b560c000-b560d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 13:27:13.082  6545  6545 W art     : b560d000-b560e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 13:27:13.082  6545  6545 W art     : b560f000-b5616000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:27:13.082  6545  6545 W art     : b5616000-b5617000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5617000-b5618000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:27:13.082  6545  6545 W art     : b5618000-b5619000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:27:13.082  6545  6545 W art     : b5619000-b561a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b561a000-b5631000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:27:13.082  6545  6545 W art     : b5631000-b5632000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5632000-b5635000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:27:13.082  6545  6545 W art     : b5635000-b5636000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:27:13.082  6545  6545 W art     : b5636000-b5655000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:27:13.082  6545  6545 W art     : b5655000-b5656000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:27:13.082  6545  6545 W art     : b5656000-b5657000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:27:13.082  6545  6545 W art     : b5657000-b5695000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 13:27:13.082  6545  6545 W art     : b5695000-b5696000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5696000-b5698000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 13:27:13.082  6545  6545 W art     : b5698000-b5699000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 13:27:13.082  6545  6545 W art     : b569a000-b56a1000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:27:13.082  6545  6545 W art     : b56a1000-b56a2000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:27:13.082  6545  6545 W art     : b56a2000-b56a3000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:27:13.082  6545  6545 W art     : b56a4000-b56a7000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:27:13.082  6545  6545 W art     : b56a7000-b56a8000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:27:13.082  6545  6545 W art     : b56a8000-b56a9000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:27:13.082  6545  6545 W art     : b56a9000-b56af000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:27:13.082  6545  6545 W art     : b56af000-b56b0000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b56b0000-b56b1000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:27:13.082  6545  6545 W art     : b56b1000-b56b2000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:27:13.082  6545  6545 W art     : b56b2000-b56bb000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:27:13.082  6545  6545 W art     : b56bb000-b56bc000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:27:13.082  6545  6545 W art     : b56bc000-b56bd000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:27:13.082  6545  6545 W art     : b56bd000-b574e000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:27:13.082  6545  6545 W art     : b574e000-b574f000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b574f000-b575a000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:27:13.082  6545  6545 W art     : b575a000-b575b000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:27:13.082  6545  6545 W art     : b575c000-b576e000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 13:27:13.082  6545  6545 W art     : b576e000-b576f000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 13:27:13.082  6545  6545 W art     : b576f000-b5770000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 13:27:13.082  6545  6545 W art     : b5771000-b5776000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:27:13.082  6545  6545 W art     : b5776000-b5777000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:27:13.082  6545  6545 W art     : b5777000-b5778000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:27:13.082  6545  6545 W art     : b5779000-b57e6000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:27:13.082  6545  6545 W art     : b57e6000-b57e7000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b57e7000-b57e9000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:27:13.082  6545  6545 W art     : b57e9000-b57ea000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:27:13.082  6545  6545 W art     : b57ea000-b57eb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b57eb000-b57f2000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:27:13.082  6545  6545 W art     : b57f2000-b57f3000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:27:13.082  6545  6545 W art     : b57f3000-b57f4000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:27:13.082  6545  6545 W art     : b57f5000-b5875000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:27:13.082  6545  6545 W art     : b5875000-b5876000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5876000-b5877000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:27:13.082  6545  6545 W art     : b5877000-b5878000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:27:13.082  6545  6545 W art     : b5878000-b588f000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b588f000-b58c6000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 13:27:13.082  6545  6545 W art     : ib/libqc-opt.so
08-23 13:27:13.082  6545  6545 W art     : b58c6000-b58c7000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:27:13.082  6545  6545 W art     : b58c7000-b58c8000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:27:13.082  6545  6545 W art     : b58c8000-b58e4000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:27:13.082  6545  6545 W art     : b58e4000-b58e5000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:27:13.082  6545  6545 W art     : b58e5000-b58e6000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:27:13.082  6545  6545 W art     : b58e7000-b5948000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 13:27:13.082  6545  6545 W art     : b5948000-b594a000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 13:27:13.082  6545  6545 W art     : b594a000-b594b000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 13:27:13.082  6545  6545 W art     : b594c000-b5973000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 13:27:13.082  6545  6545 W art     : b5973000-b5974000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5974000-b5975000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 13:27:13.082  6545  6545 W art     : b5975000-b5976000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 13:27:13.082  6545  6545 W art     : b5977000-b597f000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:27:13.082  6545  6545 W art     : b597f000-b5981000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:27:13.082  6545  6545 W art     : b5981000-b5982000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:27:13.082  6545  6545 W art     : b5983000-b5986000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 13:27:13.082  6545  6545 W art     : b5986000-b5987000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 13:27:13.082  6545  6545 W art     : b5987000-b5988000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 13:27:13.082  6545  6545 W art     : b5988000-b598c000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:27:13.082  6545  6545 W art     : b598c000-b598d000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b598d000-b598e000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:27:13.082  6545  6545 W art     : b598e000-b598f000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:27:13.082  6545  6545 W art     : b598f000-b599f000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 13:27:13.082  6545  6545 W art     : b599f000-b59a0000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 13:27:13.082  6545  6545 W art     : b59a0000-b59a1000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 13:27:13.082  6545  6545 W art     : b59a1000-b59e7000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b59e7000-b59f0000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 13:27:13.082  6545  6545 W art     : b59f0000-b59f1000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 13:27:13.082  6545  6545 W art     : b59f1000-b59f2000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 13:27:13.082  6545  6545 W art     : b59f3000-b59f8000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 13:27:13.082  6545  6545 W art     : b59f8000-b59f9000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 13:27:13.082  6545  6545 W art     : b59f9000-b59fa000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 13:27:13.082  6545  6545 W art     : b59fa000-b59fd000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:27:13.082  6545  6545 W art     : b59fd000-b59fe000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b59fe000-b59ff000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:27:13.082  6545  6545 W art     : b59ff000-b5a00000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:27:13.082  6545  6545 W art     : b5a01000-b5a19000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:27:13.082  6545  6545 W art     : b5a19000-b5a1a000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5a1a000-b5a1b000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:27:13.082  6545  6545 W art     : b5a1b000-b5a1c000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:27:13.082  6545  6545 W art     : b5a1d000-b5bb7000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:27:13.082  6545  6545 W art     : b5bb7000-b5bb8000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5bb8000-b5bc5000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:27:13.082  6545  6545 W art     : b5bc5000-b5bc6000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:27:13.082  6545  6545 W art     : b5bc6000-b5bca000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 13:27:13.082  6545  6545 W art     : b5bca000-b5bcb000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5bcb000-b5bcc000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 13:27:13.082  6545  6545 W art     : b5bcc000-b5bcd000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 13:27:13.082  6545  6545 W art     : b5bcd000-b5be0000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:27:13.082  6545  6545 W art     : b5be0000-b5be1000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:27:13.082  6545  6545 W art     : b5be1000-b5be2000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:27:13.082  6545  6545 W art     : b5be2000-b5be3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:13.082  6545  6545 W art     : b5be3000-b5c2e000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:27:13.082  6545  6545 W art     : b5c2e000-b5c2f000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:27:13.082  6545  6545 W art     : b5c2f000-b5c30000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:27:13.082  6545  6545 W art     : b5c30000-b5c32000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5c33000-b5c44000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:27:13.082  6545  6545 W art     : b5c44000-b5c45000 ---p 00000000 00:00 0 
08-23 13:27:13.102   763  2448 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{aea1ed9 6601:com.sec.android.app.myfiles/u0a50}
08-23 13:27:13.082  6545  6545 W art     : b5c45000-b5c46000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:27:13.082  6545  6545 W art     : b5c46000-b5c47000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:27:13.082  6545  6545 W art     : b5c48000-b5c52000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:27:13.082  6545  6545 W art     : b5c52000-b5c54000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:27:13.082  6545  6545 W art     : b5c54000-b5c55000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:27:13.082  6545  6545 W art     : b5c55000-b5c6e000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:27:13.082  6545  6545 W art     : b5c6e000-b5c6f000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:27:13.082  6545  6545 W art     : b5c6f000-b5c72000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:27:13.082  6545  6545 W art     : b5c72000-b5c76000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5c76000-b5cea000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 13:27:13.082  6545  6545 W art     : b5cea000-b5ceb000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5ceb000-b5cee000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 13:27:13.082  6545  6545 W art     : b5cee000-b5cef000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 13:27:13.082  6545  6545 W art     : b5cef000-b5cf0000 r--p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5cf0000-b5cf3000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:27:13.082  6545  6545 W art     : b5cf3000-b5cf4000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:27:13.082  6545  6545 W art     : b5cf4000-b5cf5000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:27:13.082  6545  6545 W art     : b5cf5000-b5cf6000 r--p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5cf6000-b5cfb000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:27:13.082  6545  6545 W art     : b5cfb000-b5cfc000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:27:13.082  6545  6545 W art     : b5cfc000-b5cfd000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:27:13.082  6545  6545 W art     : b5cfd000-b5cfe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b5cfe000-b5d01000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:27:13.082  6545  6545 W art     : b5d01000-b5d02000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:27:13.082  6545  6545 W art     : b5d02000-b5d03000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:27:13.082  6545  6545 W art     : b5d03000-b5d04000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b5d04000-b5d08000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:27:13.082  6545  6545 W art     : b5d08000-b5d09000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:27:13.082  6545  6545 W art     : b5d09000-b5d0a000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:27:13.082  6545  6545 W art     : b5d0a000-b5d0b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:13.082  6545  6545 W art     : b5d0b000-b5d0f000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:27:13.082  6545  6545 W art     : b5d0f000-b5d10000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:27:13.082  6545  6545 W art     : b5d10000-b5d11000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:27:13.082  6545  6545 W art     : b5d11000-b5d12000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b5d12000-b5d20000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 13:27:13.082  6545  6545 W art     : b5d20000-b5d21000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b5d21000-b5d22000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 13:27:13.082  6545  6545 W art     : b5d22000-b5d23000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 13:27:13.082  6545  6545 W art     : b5d23000-b5d2d000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:27:13.082  6545  6545 W art     : b5d2d000-b5d30000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:27:13.082  6545  6545 W art     : b5d30000-b5d31000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:27:13.082  6545  6545 W art     : b5d31000-b5d32000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b5d32000-b5d3c000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 13:27:13.082  6545  6545 W art     : b5d3c000-b5d3f000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 13:27:13.082  6545  6545 W art     : b5d3f000-b5d40000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 13:27:13.082  6545  6545 W art     : b5d40000-b5d44000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:27:13.082  6545  6545 W art     : b5d44000-b5d45000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:27:13.082  6545  6545 W art     : b5d45000-b5d46000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:27:13.082  6545  6545 W art     : b5d46000-b5d47000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b5d47000-b5d54000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:27:13.082  6545  6545 W art     : b5d54000-b5d56000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:27:13.082  6545  6545 W art     : b5d56000-b5d57000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:27:13.082  6545  6545 W art     : b5d57000-b6169000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 13:27:13.082  6545  6545 W art     : b6169000-b616a000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b616a000-b6173000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 13:27:13.082  6545  6545 W art     : b6173000-b6177000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 13:27:13.082  6545  6545 W art     : b6177000-b6178000 rw-p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b6178000-b617f000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:27:13.082  6545  6545 W art     : b617f000-b6180000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:27:13.082  6545  6545 W art     : b6180000-b6181000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:27:13.082  6545  6545 W art     : b6181000-b6182000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.102  6601  6601 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-23 13:27:13.082  6545  6545 W art     : b6182000-b619d000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-23 13:27:13.082  6545  6545 W art     : b619d000-b619e000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 13:27:13.082  6545  6545 W art     : b619e000-b619f000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 13:27:13.082  6545  6545 W art     : b619f000-b61a0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b61a0000-b61ec000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:27:13.082  6545  6545 W art     : b61ec000-b61ed000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b61ed000-b61ee000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:27:13.082  6545  6545 W art     : b61ee000-b61ef000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:27:13.082  6545  6545 W art     : b61ef000-b61f0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b61f0000-b61f4000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:27:13.082  6545  6545 W art     : b61f4000-b61f5000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b61f5000-b61f6000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:27:13.082  6545  6545 W art     : b61f6000-b61f7000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:27:13.082  6545  6545 W art     : b61f7000-b622f000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:27:13.082  6545  6545 W art     : b622f000-b6230000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:27:13.082  6545  6545 W art     : b6230000-b6231000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:27:13.082  6545  6545 W art     : b6231000-b6232000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.082  6545  6545 W art     : b6232000-b62d0000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 13:27:13.082  6545  6545 W art     : b62d0000-b62d1000 ---p 00000000 00:00 0 
08-23 13:27:13.082  6545  6545 W art     : b62d1000-b62ef000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 13:27:13.082  6545  6545 W art     : b62ef000-b62f0000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-23 13:27:13.082  6545  6545 W art     : b62f0000-b6463000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:27:13.082  6545  6545 W art     : b6463000-b646e000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:27:13.082  6545  6545 W art     : b646e000-b646f000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:27:13.082  6545  6545 W art     : b646f000-b6586000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:27:13.082  6545  6545 W art     : b6586000-b6591000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:27:13.082  6545  6545 W art     : b6591000-b6592000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:27:13.082  6545  6545 W art     : b6592000-b6596000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6596000-b65ba000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-23 13:27:13.092  6545  6545 W art     : b65ba000-b65bc000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 13:27:13.092  6545  6545 W art     : b65bc000-b65bd000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 13:27:13.092  6545  6545 W art     : b65bd000-b6663000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 13:27:13.092  6545  6545 W art     : b6663000-b6670000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-23 13:27:13.092  6545  6545 W art     : b6670000-b6671000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 13:27:13.092  6545  6545 W art     : b6671000-b6672000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6672000-b66c5000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:27:13.092  6545  6545 W art     : b66c5000-b66c6000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b66c6000-b66c7000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:27:13.092  6545  6545 W art     : b66c7000-b66c8000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:27:13.092  6545  6545 W art     : b66c8000-b66cd000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b66cd000-b66df000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 13:27:13.092  6545  6545 W art     : b66df000-b66e0000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b66e0000-b66e1000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 13:27:13.092  6545  6545 W art     : b66e1000-b66e2000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 13:27:13.092  6545  6545 W art     : b66e2000-b66e9000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:27:13.092  6545  6545 W art     : b66e9000-b66ea000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:27:13.092  6545  6545 W art     : b66ea000-b66eb000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:27:13.092  6545  6545 W art     : b66eb000-b66ec000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b66ec000-b66ef000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 13:27:13.092  6545  6545 W art     : b66ef000-b66f0000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 13:27:13.092  6545  6545 W art     : b66f0000-b66f1000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 13:27:13.092  6545  6545 W art     : b66f1000-b66f5000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 13:27:13.092  6545  6545 W art     : b66f5000-b66f6000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 13:27:13.092  6545  6545 W art     : b66f6000-b66f7000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 13:27:13.092  6545  6545 W art     : b66f7000-b6705000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:27:13.092  6545  6545 W art     : b6705000-b6706000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6706000-b6707000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:27:13.092  6545  6545 W art     : b6707000-b6708000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:27:13.092  6545  6545 W art     : b6708000-b6711000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:27:13.092  6545  6545 W art     : b6711000-b6712000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:27:13.092  6545  6545 W art     : b6712000-b6713000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:27:13.092  6545  6545 W art     : b6713000-b6779000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 13:27:13.092  6545  6545 W art     : b6779000-b677a000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b677a000-b677c000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 13:27:13.092  6545  6545 W art     : b677c000-b6785000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 13:27:13.092  6545  6545 W art     : b6785000-b6788000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6788000-b681f000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 13:27:13.092  6545  6545 W art     : b681f000-b6821000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 13:27:13.092  6545  6545 W art     : b6821000-b6822000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 13:27:13.092  6545  6545 W art     : b6822000-b6823000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6823000-b6b44000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 13:27:13.092  6545  6545 W art     : b6b44000-b6b45000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6b45000-b6b60000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 13:27:13.092  6545  6545 W art     : b6b60000-b6b64000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 13:27:13.092  6545  6545 W art     : b6b64000-b6b69000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6b69000-b6b71000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:27:13.092  6545  6545 W art     : b6b71000-b6b72000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:27:13.092  6545  6545 W art     : b6b72000-b6b73000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:27:13.092  6545  6545 W art     : b6b73000-b6ba1000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:27:13.092  6545  6545 W art     : b6ba1000-b6ba2000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6ba2000-b6ba9000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:27:13.092  6545  6545 W art     : b6ba9000-b6baa000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:27:13.092  6545  6545 W art     : b6baa000-b6bf0000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:27:13.092  6545  6545 W art     : b6bf0000-b6bf1000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6bf1000-b6bf4000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:27:13.092  6545  6545 W art     : b6bf4000-b6bf5000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:27:13.092  6545  6545 W art     : b6bf5000-b6c10000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 13:27:13.092  6545  6545 W art     : b6c10000-b6c14000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 13:27:13.092  6545  6545 W art     : b6c14000-b6c15000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 13:27:13.092  6545  6545 W art     : b6c15000-b6c62000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 13:27:13.092  6545  6545 W art     : b6c62000-b6c63000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6c63000-b6c6f000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 13:27:13.092  6545  6545 W art     : b6c6f000-b6c70000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 13:27:13.092  6545  6545 W art     : b6c70000-b6c7d000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 13:27:13.092  6545  6545 W art     : b6c7d000-b6c7e000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6c7e000-b6c7f000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 13:27:13.092  6545  6545 W art     : b6c7f000-b6c80000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 13:27:13.092  6545  6545 W art     : b6c80000-b6c88000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:27:13.092  6545  6545 W art     : b6c88000-b6c89000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6c89000-b6c8a000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:27:13.092  6545  6545 W art     : b6c8a000-b6c8b000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:27:13.092  6545  6545 W art     : b6c8b000-b6c92000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:27:13.092  6545  6545 W art     : b6c92000-b6c93000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:27:13.092  6545  6545 W art     : b6c93000-b6c94000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:27:13.092  6545  6545 W art     : b6c94000-b6ca8000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 13:27:13.092  6545  6545 W art     : b6ca8000-b6caa000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 13:27:13.092  6545  6545 W art     : b6caa000-b6cab000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 13:27:13.092  6545  6545 W art     : b6cab000-b6cd3000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:27:13.092  6545  6545 W art     : b6cd3000-b6cd5000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:27:13.092  6545  6545 W art     : b6cd5000-b6cd6000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:27:13.092  6545  6545 W art     : b6cd6000-b6cd9000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:27:13.092  6545  6545 W art     : b6cd9000-b6cda000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:27:13.092  6545  6545 W art     : b6cda000-b6cdb000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:27:13.092  6545  6545 W art     : b6cdb000-b6ce4000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:27:13.092  6545  6545 W art     : b6ce4000-b6ce5000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:27:13.092  6545  6545 W art     : b6ce5000-b6ce6000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:27:13.092  6545  6545 W art     : b6ce6000-b6d06000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 13:27:13.092  6545  6545 W art     : b6d06000-b6d07000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 13:27:13.092  6545  6545 W art     : b6d07000-b6d08000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 13:27:13.092  6545  6545 W art     : b6d08000-b6d7b000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 13:27:13.092  6545  6545 W art     : b6d7b000-b6d7f000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 13:27:13.092  6545  6545 W art     : b6d7f000-b6d82000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 13:27:13.092  6545  6545 W art     : b6d82000-b6d8c000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6d8c000-b6e14000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 13:27:13.092  6545  6545 W art     : b6e14000-b6e15000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6e15000-b6e19000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 13:27:13.092  6545  6545 W art     : b6e19000-b6e1a000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 13:27:13.092  6545  6545 W art     : b6e1a000-b6e1b000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6e1b000-b6e44000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:27:13.092  6545  6545 W art     : b6e44000-b6e45000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6e45000-b6e48000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:27:13.092  6545  6545 W art     : b6e48000-b6e49000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:27:13.092  6545  6545 W art     : b6e49000-b6f23000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:27:13.092  6545  6545 W art     : b6f23000-b6f2a000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:27:13.092  6545  6545 W art     : b6f2a000-b6f32000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:27:13.092  6545  6545 W art     : b6f32000-b6f33000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6f33000-b6f34000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:13.092  6545  6545 W art     : b6f34000-b6f35000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 13,:27:13.092  6545  6545 W art     : b6f35000-b6f36000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.092  6545  6545 W art     : b6f36000-b6f39000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.092  6545  6545 W art     : b6f39000-b6f5e000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 13:27:13.092  6545  6545 W art     : b6f5e000-b6f5f000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6f5f000-b6f66000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 13:27:13.092  6545  6545 W art     : b6f66000-b6f67000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 13:27:13.092  6545  6545 W art     : b6f67000-b6f6e000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 13:27:13.092  6545  6545 W art     : b6f6e000-b6f6f000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 13:27:13.092  6545  6545 W art     : b6f6f000-b6f70000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 13:27:13.092  6545  6545 W art     : b6f70000-b6f71000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.092  6545  6545 W art     : b6f71000-b6f89000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 13:27:13.092  6545  6545 W art     : b6f89000-b6f8a000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6f8a000-b6f8b000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 13:27:13.092  6545  6545 W art     : b6f8b000-b6f8c000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 13:27:13.092  6545  6545 W art     : b6f8c000-b6f9a000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 13:27:13.092  6545  6545 W art     : b6f9a000-b6f9b000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6f9b000-b6f9c000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 13:27:13.092  6545  6545 W art     : b6f9c000-b6f9d000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 13:27:13.092  6545  6545 W art     : b6f9d000-b6f9e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:13.092  6545  6545 W art     : b6f9e000-b6fa0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.092  6545  6545 W art     : b6fa0000-b6fa1000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.092  6545  6545 W art     : b6fa1000-b6fa2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:13.092  6545  6545 W art     : b6fa2000-b6fa3000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 13:27:13.092  6545  6545 W art     : b6fa3000-b6fa4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:13.092  6545  6545 W art     : b6fa4000-b6fc4000 r--s 00000000 00:0b 6700       /dev/__properties__
08-23 13:27:13.092  6545  6545 W art     : b6fc4000-b6fc5000 r--p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6fc5000-b6fc6000 ---p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6fc6000-b6fc8000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 13:27:13.092  6545  6545 W art     : b6fc8000-b6fc9000 r-xp 00000000 00:00 0          [sigpage]
08-23 13:27:13.092  6545  6545 W art     : b6fc9000-b6fe4000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 13:27:13.092  6545  6545 W art     : b6fe4000-b6fe5000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 13:27:13.092  6545  6545 W art     : b6fe5000-b6fe7000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 13:27:13.092  6545  6545 W art     : b6fe7000-b6fe9000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : b6fe9000-b6fee000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 13:27:13.092  6545  6545 W art     : b6fee000-b6fef000 r--p 00004000 b3:17 978        /system/bin/app_process32
,08-23 13:27:13.092  6545  6545 W art     : b6fef000-b6ff0000 rw-p 00000000 00:00 0 
08-23 13:27:13.092  6545  6545 W art     : bee13000-bee34000 rw-p 00000000 00:00 0          [stack]
08-23 13:27:13.092  6545  6545 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 13:27:13.122  6601  6601 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,08-23 13:27:13.142  6545  6545 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 13:27:13.162  6601  6601 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-23 13:27:13.172   763  2472 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5f268b 5200:com.android.settings/1000}
08-23 13:27:13.182   326   326 E installd: system dir 0 : /system/app/
08-23 13:27:13.182   326   326 E installd: system dir 1 : /system/priv-app/
08-23 13:27:13.182   326   326 E installd: system dir 2 : /vendor/app/
08-23 13:27:13.182   326   326 E installd: system dir 3 : /oem/app/
08-23 13:27:13.192  6545  6545 I Radio-JNI: register_android_hardware_Radio DONE
08-23 13:27:13.192   763  1411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5f268b 5200:com.android.settings/1000}
08-23 13:27:13.202   763   944 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-23 13:27:13.202  6545  6545 E AffinityControl: AffinityControl: registerfunction enter
08-23 13:27:13.212   763  2448 I ActivityManager: Start proc 6621:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-23 13:27:13.212  6621  6621 E Zygote  : v2
08-23 13:27:13.212  6621  6621 I libpersona: KNOX_SDCARD checking this for 10169
08-23 13:27:13.212  6621  6621 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:13.212  6621  6621 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:13.212  6621  6621 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:13.212  6621  6621 E Zygote  : accessInfo : 0
08-23 13:27:13.212  6621  6621 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-23 13:27:13.222  6545  6545 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 13:27:13.232   763  1638 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-23 13:27:13.242  6621  6621 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:13.242  6621  6621 D ActivityThread: Added TimaKeyStore provider
08-23 13:27:13.252   763  1638 D ActivityManager: mDVFSHelper.acquire()
08-23 13:27:13.252   763  1638 V WindowManager: addAppToken: AppWindowToken{dcedc9b token=Token{999f8aa ActivityRecord{c54cf95 u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-23 13:27:13.262   763   906 D SecWifiDisplayUtil: Metadata value : none
08-23 13:27:13.262   763   906 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{dc24413 V.E...... R.....ID 0,0-0,0}
08-23 13:27:13.262   763   906 D ISSUE_DEBUG: InputChannelName : f837049 Starting com.test.thalitest
08-23 13:27:13.262   763  1638 I ActivityManager: Start proc 6635:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-23 13:27:13.262  6635  6635 E Zygote  : v2
08-23 13:27:13.262  6635  6635 I libpersona: KNOX_SDCARD checking this for 10004
08-23 13:27:13.262  6635  6635 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:13.262  6635  6635 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:13.262  6635  6635 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:13.262  6635  6635 E Zygote  : accessInfo : 0
08-23 13:27:13.262  6635  6635 W SELinux : SELinux: seapp_context_lookup: seinfo=default, lev,el=s0:c512,c768, pkgname=com.test.thalitest 
08-23 13:27:13.262   763  1638 D InputDispatcher: Focused application set to: xxxx
08-23 13:27:13.272   763  1638 D InputDispatcher: Focus left window: 4707
08-23 13:27:13.272  6545  6545 D AndroidRuntime: Shutting down VM
08-23 13:27:13.272  6423  6423 D CAR.SERVICE: onUnbind
08-23 13:27:13.272  6423  6423 D CAR.SERVICE: CSB onClientsDisconnected
08-23 13:27:13.272  6423  6423 D CAR.SERVICE: tearDown
08-23 13:27:13.272  6423  6423 D CAR.SERVICE: tearDownCarState
08-23 13:27:13.272  6423  6423 D CAR.SERVICE: Skip, car not connected.
08-23 13:27:13.272  6423  6423 D CAR.SERVICE: tearDownClientState
08-23 13:27:13.272  6423  6423 D CAR.SERVICE: requestStop
08-23 13:27:13.282   293   293 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-23 13:27:13.282   763  1252 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8a33d4e 6621:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-23 13:27:13.282   763   867 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ee837c4 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-23 13:27:13.282  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-23 13:27:13.282  6423  6423 D CAR.SERVICE: onDestroy
08-23 13:27:13.282  6423  6423 D CAR.SERVICE: tearDown
08-23 13:27:13.282  6423  6423 D CAR.SERVICE: tearDownCarState
08-23 13:27:13.292  6423  6423 D CAR.SERVICE: Skip, car not connected.
08-23 13:27:13.292  6423  6423 D CAR.SERVICE: tearDownClientState
08-23 13:27:13.292  6423  6423 D CAR.SERVICE: requestStop
08-23 13:27:13.292   763   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:763 uid:1000
08-23 13:27:13.292   763   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:27:13.292   763   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:763 uid:1000
08-23 13:27:13.292   763   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 13:27:13.292   763   906 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-23 13:27:13.292  6423  6423 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@90d3f54 that was originally bound here
08-23 13:27:13.292  6423  6423 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@90d3f54 that was originally bound here
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBi,nd(:com.google.android.gms:165)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-23 13:27:13.292  6423  6423 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-23 13:27:13.302   763  1638 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@2830e6f
08-23 13:27:13.302  6635  6635 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:13.302  6635  6635 D ActivityThread: Added TimaKeyStore provider
08-23 13:27:13.302  6621  6621 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-23 13:27:13.302   763  2146 V WindowOrientationListener: setCurrentAppOrientation :-1
08-23 13:27:13.302   763  2146 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-23 13:27:13.312   763   867 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{f837049 u0 d0 Starting com.test.thalitest}
08-23 13:27:13.322  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-23 13:27:13.332  6621  6621 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-23 13:27:13.332   763  2146 D ActivityManager:  Launching com.test.thalitest, updated priority
08-23 13:27:13.342   293  2041 I SurfaceFlinger: id=19 Removed YUIInstallC (6/10)
08-23 13:27:13.342   763   906 V WindowStateAnimator: Finishing drawing window Window{f837049 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-23 13:27:13.342  1717  1894 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-23 13:27:13.342  1717  1717 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-23 13:27:13.352  4707  4707 V ActivityThread: updateVisibility : ActivityRecord{1778293 token=android.os.BinderProxy@b8d412b {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-23 13:27:13.352   293  1295 D libEGL  : eglTerminate EGLDisplay = 0xb47bd64c
08-23 13:27:13.352   293  1295 D libEGL  : eglTerminate EGLDisplay = 0xb47bd64c
08-23 13:27:13.352   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbec69364
08-23 13:27:13.352   293   424 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
08-23 13:27:13.362   293  2041 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-23 13:27:13.362  2107  2120 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-23 13:27:13.362  1717  1717 V ActivityThread: updateVisibility : ActivityRecord{66cb2d7 token=android.os.BinderProxy@13fe4e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 13:27:13.362  1717  1717 D Launcher: onTrimMemory. Level: 20
08-23 13:27:13.372   293   293 D libEGL  : eglTermin,ate EGLDisplay = 0xbec693a4
08-23 13:27:13.452   763  3707 D SSRM:n  : SIOP:: AP = 480, PST = 448, CUR = 350, LCD = 0
,08-23 13:27:13.652   763  2146 I WindowManager: Screenshot max retries 4 of Token{999f8aa ActivityRecord{c54cf95 u0 com.test.thalitest/.MainActivity t168}} appWin=Window{f837049 u0 d0 Starting com.test.thalitest} drawState=4
,08-23 13:27:13.662   763   862 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-23 13:27:13.672  6635  6635 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 13:27:13.672   763   862 I ActivityManager: Start proc 6650:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-23 13:27:13.682  6650  6650 E Zygote  : v2
08-23 13:27:13.682  6650  6650 I libpersona: KNOX_SDCARD checking this for 10210
08-23 13:27:13.682  6650  6650 I libpersona: KNOX_SDCARD not a persona
,08-23 13:27:13.682  6650  6650 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:13.682  6650  6650 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:13.682  6650  6650 E Zygote  : accessInfo : 0
,08-23 13:27:13.682  6650  6650 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-23 13:27:13.702   763  3707 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 13:27:13.702   763  1638 I ActivityManager: Killing 5707:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,08-23 13:27:13.712   763  1638 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73e1ec1 1702:com.android.phone/1001}
,08-23 13:27:13.722   763  1624 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{832f88e 1828:com.google.android.googlequicksearchbox:search/u0a61}
,08-23 13:27:13.732  6635  6635 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 13:27:13.732   763  1252 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,08-23 13:27:13.742  6635  6635 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 13:27:13.742   763  1638 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{832f88e 1828:com.google.android.googlequicksearchbox:search/u0a61}
,08-23 13:27:13.752  6650  6650 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:27:13.752  6650  6650 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:13.752  6635  6635 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-23 13:27:13.762  1828  6666 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-23 13:27:13.772   763   778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{289c805 6465:com.samsung.android.sm.provider/1000}
,08-23 13:27:13.772  6635  6635 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 13:27:13.782  6635  6635 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 13:27:13.792   763  2146 I ActivityManager: Start proc 6671:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
,08-23 13:27:13.792  6671  6671 E Zygote  : v2
08-23 13:27:13.792  6671  6671 I libpersona: KNOX_SDCARD checking this for 5012
08-23 13:27:13.792  6671  6671 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:13.792  6671  6671 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:13.792  6671  6671 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:13.792  6671  6671 E Zygote  : accessInfo : 0
08-23 13:27:13.792  6671  6671 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-23 13:27:13.802  6650  6650 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-23 13:27:13.822  6635  6635 I cr_LibraryLoader: Time to load native libraries: 33 ms (timestamps 458-491)
08-23 13:27:13.822  6635  6635 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 13:27:13.822  6671  6671 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:27:13.822  6671  6671 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:13.832   763  1624 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ddc228b 6671:com.samsung.android.sm.devicesecurity/5012}
,08-23 13:27:13.842  6635  6635 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5d493bb}
08-23 13:27:13.842  6635  6635 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 13:27:13.842  6635  6635 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 13:27:13.842  6635  6684 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-23 13:27:13.852  6635  6635 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 13:27:13.852  6650  6650 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-23 13:27:13.852  6671  6671 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,08-23 13:27:13.852  1828  6666 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-23 13:27:13.852  6650  6650 D AASAservice: onCreate()
,08-23 13:27:13.862  5626  5626 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-23 13:27:13.862   763  1730 I ActivityManager: Killing 5033:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
,08-23 13:27:13.862  1828  6666 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-23 13:27:13.872  6671  6671 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,08-23 13:27:13.872  6635  6635 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 13:27:13.872  6635  6635 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 13:27:13.872  6635  6635 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 13:27:13.872  6635  6635 I Adreno-EGL: Local Branch: ss
08-23 13:27:13.872  6635  6635 I Adreno-EGL: Remote Branch: 
08-23 13:27:13.872  6635  6635 I Adreno-EGL: Local Patches: 
08-23 13:27:13.872  6635  6635 I Adreno-EGL: Reconstruct Branch: 
,08-23 13:27:13.882  6635  6635 D libEGL  : eglInitialize EGLDisplay = 0xbeb51dac
,08-23 13:27:13.882   763  2147 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-23 13:27:13.912   763  1624 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,08-23 13:27:13.922   763  1638 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-23 13:27:13.922   763  1638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-23 13:27:13.932   763   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{adf9d1f 3299:com.android.contacts/u0a19}
,08-23 13:27:13.952  6702  6702 E Zygote  : v2
,08-23 13:27:13.952   763  1252 I ActivityManager: Start proc 6702:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-23 13:27:13.952  6702  6702 I libpersona: KNOX_SDCARD checking this for 10049
08-23 13:27:13.952  6702  6702 I libpersona: KNOX_SDCARD not a persona
,08-23 13:27:13.952  6702  6702 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:13.952  6702  6702 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:13.952  6702  6702 E Zygote  : accessInfo : 0
,08-23 13:27:13.952  6702  6702 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,08-23 13:27:13.992  6702  6702 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:13.992  6702  6702 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:13.992  6635  6635 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-23 13:27:14.002   763   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{248704f 6702:com.android.mms/u0a49}
,08-23 13:27:14.002  6635  6635 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 13:27:14.002  6635  6635 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-23 13:27:14.002  6635  6635 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-23 13:27:14.002  6635  6635 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-23 13:27:14.002  6702  6702 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 13:27:14.022  6635  6635 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-23 13:27:14.032  6635  6635 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 13:27:14.032  6702  6702 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-23 13:27:14.042  4645  6700 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-23 13:27:14.042  6702  6702 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-23 13:27:14.072  6702  6702 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-23 13:27:14.082  1828  6666 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 322 ms] updated apps [took 322 ms] 
,08-23 13:27:14.082  6635  6635 D SecWifiDisplayUtil: Metadata value : none
,08-23 13:27:14.082  6635  6635 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3449711 I.E...... R.....ID 0,0-0,0}
,08-23 13:27:14.092  6702  6722 D Mms/ArtClassLoader: init before art first
,08-23 13:27:14.092  6635  6721 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 13:27:14.092   763  1624 D ISSUE_DEBUG: InputChannelName : 8882c0c com.test.thalitest/com.test.thalitest.MainActivity
,08-23 13:27:14.092  6702  6702 D Mms/TelephonyPermission: start operation mode monitor
08-23 13:27:14.092  6702  6702 D Mms/TelephonyPermission: User ID is null set current User Id
,08-23 13:27:14.112   763   779 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-23 13:27:14.112   763   779 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 13:27:14.112   763   763 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-23 13:27:14.112   763   763 I KnoxTimeoutHandler: Shared devices show user statefalse
08-23 13:27:14.112  6702  6724 D Mms/ArtClassLoader: init before art third
,08-23 13:27:14.122  6702  6723 D Mms/ArtClassLoader: init before art second
,08-23 13:27:14.132  6635  6635 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6635
,08-23 13:27:14.132   763   779 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6635 for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:27:14.132   763  1330 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-23 13:27:14.132   763  1330 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-23 13:27:14.132   763  1330 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-23 13:27:14.132   763  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:27:14.132   763  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:27:14.132   763  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:27:14.132   763  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-23 13:27:14.132   763  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:27:14.132   763  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 13:27:14.132   763  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-23 13:27:14.132   763  1330 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:27:14.142  6635  6684 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-23 13:27:14.152  6635  6635 D SecWifiDisplayUtil: Metadata value : none
,08-23 13:27:14.152  6702  6702 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 13:27:14.152  6702  6702 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-23 13:27:14.152  6702  6724 D Mms/ArtClassLoader: init [DONE] art
,08-23 13:27:14.162   293   293 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-23 13:27:14.172   763  2472 D InputDispatcher: Focus entered window: 6635
,08-23 13:27:14.172   763   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:763 uid:1000
08-23 13:27:14.172   763   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:27:14.172   763   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:763 uid:1000
08-23 13:27:14.172   763   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 13:27:14.172  6635  6721 D libEGL  : eglInitialize EGLDisplay = 0x9c9fe7c4
08-23 13:27:14.172  6635  6721 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 13:27:14.182  6702  6702 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-23 13:27:14.182  6702  6702 D Mms/TelephonyPermission: isDefault true
,08-23 13:27:14.182  6702  6702 D Mms/MmsApp: onCreate() com.android.mms
,08-23 13:27:14.232  6635  6635 V ActivityThread: updateVisibility : ActivityRecord{d83d950 token=android.os.BinderProxy@67cdb38 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 13:27:14.242  6702  6702 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-23 13:27:14.242  6635  6635 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-23 13:27:14.242  6635  6635 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-23 13:27:14.242   763  2147 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 13:27:14.242  6702  6702 D Mms/MmsApp: [start]    initCountryIso consume time = 168.332864
,08-23 13:27:14.252  6635  6635 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-23 13:27:14.262   763  2448 D CountryDetector: The first listener is added
,08-23 13:27:14.262  6702  6702 D Mms/MmsApp: [end]    initCountryIso consume time = 18.86375
08-23 13:27:14.262  6702  6702 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.110625
,08-23 13:27:14.282  6702  6702 D Mms/MmsConfig: before partial update
,08-23 13:27:14.282   763   778 V WindowStateAnimator: Finishing drawing window Window{8882c0c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-23 13:27:14.282  6635  6635 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-23 13:27:14.282  6635  6635 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@67cdb38 time:100957
,08-23 13:27:14.282   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbec69364
,08-23 13:27:14.292   763   906 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 13:27:14.292   763   906 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +639ms (total +1s44ms)
,08-23 13:27:14.302   763   906 D ActivityManager: mDVFSHelper.release()
08-23 13:27:14.302   763   906 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c54cf95 u0 com.test.thalitest/.MainActivity t168} time:100970
,08-23 13:27:14.302   763   763 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 13:27:14.302   763   763 I KnoxTimeoutHandler: SD activityfalse
08-23 13:27:14.302   763   906 D ViewRootImpl: #3 mView = null
,08-23 13:27:14.302   293  2041 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
,08-23 13:27:14.302   293   420 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,08-23 13:27:14.302   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbec693a4
,08-23 13:27:14.322  6635  6734 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:27:14.322  6635  6734 D libEGL  : eglInitialize EGLDisplay = 0x9b49a3ec
,08-23 13:27:14.332  6702  6722 D Mms/ArtClassLoader: init [DONE] art
,08-23 13:27:14.352  6635  6635 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6635
,08-23 13:27:14.352  6702  6723 D Mms/ArtClassLoader: init [DONE] art
,08-23 13:27:14.362  6702  6702 D Mms/MmsConfig: Load Resize quality : 80
,08-23 13:27:14.362  6702  6702 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 13:27:14.362  6702  6702 D EasySignUpManager_1.0.5: isAuth is false
08-23 13:27:14.362  6702  6702 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-23 13:27:14.362  6702  6702 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-23 13:27:14.362  6702  6702 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-23 13:27:14.362  6702  6702 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 13:27:14.362  6702  6702 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
08-23 13:27:14.362  6702  6702 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-23 13:27:14.362  6702  6702 D EasySignUpManager_1.0.5: isAuth is false
08-23 13:27:14.362  6702  6702 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-23 13:27:14.362  6702  6702 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-23 13:27:14.372  1702  1716 D TP/MmsSmsProvider: query, match:2117, calling pid = 6702, accessRestricted = false
,08-23 13:27:14.372  1702  1716 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 2.090 ms
,08-23 13:27:14.382  6702  6702 E CscParser: mps_code.dat does not exist
08-23 13:27:14.382  6702  6702 E CscParser: customer_path =/system/csc/customer.xml
08-23 13:27:14.382  6702  6702 E CscParser: fileName + /system/csc/customer.xml
,08-23 13:27:14.392  6702  6702 E CscParser: mps_code.dat does not exist
08-23 13:27:14.392  6702  6702 E CscParser: customer_path =/system/csc/customer.xml
08-23 13:27:14.392  6702  6702 E CscParser: fileName + /system/csc/customer.xml
,08-23 13:27:14.402  6702  6702 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-23 13:27:14.402  6702  6702 D Mms/MmsConfig:  enable multiwindow = true
,08-23 13:27:14.402  6702  6702 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-23 13:27:14.402  6702  6702 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-23 13:27:14.402  6702  6702 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-23 13:27:14.402  6702  6702 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-23 13:27:14.402  6702  6702 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-23 13:27:14.402  6702  6702 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-23 13:27:14.402  6702  6702 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-23 13:27:14.402  6702  6702 D Mms/MmsConfig: [end]    init() consume time = 142.542083
,08-23 13:27:14.412  6702  6702 D Mms/Contact: [start]    init() consume time = 3.383178
,08-23 13:27:14.422  6702  6702 D Mms/Contact: [end]    init consume time = 10.272083
,08-23 13:27:14.422  1702  1922 D TP/MmsSmsProvider: query, match:13, calling pid = 6702, accessRestricted = false
,08-23 13:27:14.422  1702  1922 D TP/MmsSmsProvider: query, match 13:Elapsed time : 0.974 ms
,08-23 13:27:14.422  6702  6702 D Mms:transaction: roaming -> false (slotId = 0)
08-23 13:27:14.422  6702  6702 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 13:27:14.422  6702  6702 D Mms:transaction: auto download without roaming -> true
08-23 13:27:14.422  6702  6702 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-23 13:27:14.422  6702  6702 D Mms:transaction: roaming -> false (slotId = 1)
08-23 13:27:14.422  6702  6702 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-23 13:27:14.422  6702  6702 D Mms:transaction: auto download without roaming -> true
08-23 13:27:14.422  6702  6702 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-23 13:27:14.422  6702  6702 D Mms:transaction: auto download during roaming secondary -> false
08-23 13:27:14.422  6702  6702 D Mms:transaction: mAutoDownload ------> true
,08-23 13:27:14.442  6702  6741 D Mms/DraftCache: [start]    rebuildCache consume time = 17.561875
,08-23 13:27:14.452  1702  1715 D TP/MmsSmsProvider: query, match:12, calling pid = 6702, accessRestricted = false
,08-23 13:27:14.452  1702  1715 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.202 ms
,08-23 13:27:14.452  6702  6702 D ComposerPerformance: 1471951634468 ms / [DONE] Composer constructor
,08-23 13:27:14.462  6702  6741 D Mms/DraftCache: [end]    rebuildCache consume time = 20.748125
,08-23 13:27:14.462  6702  6702 D CII     : Log Level [5]
08-23 13:27:14.462  6702  6702 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-23 13:27:14.462  6702  6702 I Mms/ReservationManager: ReservationManager()
,08-23 13:27:14.462  6702  6702 I Mms/ReservationManager: resetAfterConnected()
,08-23 13:27:14.462  6702  6743 D Mms/Conversation: [start]    init() consume time = 5.496406
,08-23 13:27:14.462  1702  2044 D TP/MmsSmsProvider: delete, match:1, calling pid = 6702
08-23 13:27:14.462  1702  2044 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-23 13:27:14.462  1702  2044 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-23 13:27:14.472  1702  2044 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-23 13:27:14.472  1702  2044 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-23 13:27:14.472  1702  2044 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-23 13:27:14.472  1702  1922 D TP/MmsSmsProvider: query, match:7, calling pid = 6702, accessRestricted = false
,08-23 13:27:14.472  1702  1922 D TP/MmsSmsProvider: query, match 7:Elapsed time : 1.392 ms
,08-23 13:27:14.472  1702  2044 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-23 13:27:14.472  6702  6702 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-23 13:27:14.482  1702  2044 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-23 13:27:14.482  1702  2044 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-23 13:27:14.482  1702  2044 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-23 13:27:14.482  1702  2044 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 10.951 ms
08-23 13:27:14.482  1702  2044 D TP/MmsSmsProvider: need read changed broadcast:false
,08-23 13:27:14.482  6702  6743 D Mms/Conversation: [end]    init consume time = 20.660573
,08-23 13:27:14.482  6702  6743 D Mms/MessagingNotification: [start]    init() consume time = 2.537864
,08-23 13:27:14.492  6702  6743 D Mms/MessagingNotification: [end]    init consume time = 2.712188
,08-23 13:27:14.492  6702  6702 D Mms/MmsApp: [end]    onCreate() consume time = 0.501927
08-23 13:27:14.492  6702  6702 D Mms/MmsApp: [end]    onCreate() consume time = 0.065261
,08-23 13:27:14.492  6702  6745 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 2.392135
,08-23 13:27:14.492  6702  6702 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-23 13:27:14.492  6702  6702 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-23 13:27:14.492  6702  6702 D Mms:transaction: roaming -> false (slotId = 0)
08-23 13:27:14.492  6702  6702 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 13:27:14.492  6702  6702 D Mms:transaction: auto download without roaming -> true
08-23 13:27:14.492  6702  6702 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-23 13:27:14.492  6702  6702 D Mms:transaction: mAutoDownload ------> true
,08-23 13:27:14.502  1702  1716 D TP/MmsSmsProvider: query, match:0, calling pid = 6702, accessRestricted = false
08-23 13:27:14.502  1702  1716 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-23 13:27:14.502  1702  1716 D TP/MmsSmsProvider: query, match 0:Elapsed time : 0.923 ms
,08-23 13:27:14.502  1702  1922 D TP/MmsSmsProvider: query, match:400, calling pid = 6702, accessRestricted = false
,08-23 13:27:14.502  6747  6747 E Zygote  : v2
,08-23 13:27:14.512  6747  6747 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:27:14.512  6747  6747 I libpersona: KNOX_SDCARD not a persona
,08-23 13:27:14.512  6747  6747 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:14.512  6747  6747 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:14.512  6747  6747 E Zygote  : accessInfo : 0
,08-23 13:27:14.512   763  1411 I ActivityManager: Start proc 6747:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-23 13:27:14.512   763  1411 I ActivityManager: Killing 5723:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-23 13:27:14.522  6702  6746 D Mms/Synchronizer: [start]    doSync consume time = 26.934479
,08-23 13:27:14.522  1702  2044 D TP/MmsSmsProvider: update, match:300, calling pid = 6702
08-23 13:27:14.522  1702  2044 V TP/MmsSmsProvider: syncDBData start
,08-23 13:27:14.522  1702  2044 V TP/MmsSmsProvider: syncDBData sms end
,08-23 13:27:14.522  1702  2044 V TP/MmsSmsProvider: syncDBData mms end
,08-23 13:27:14.522  1702  2044 V TP/MmsSmsProvider: syncDBData end
08-23 13:27:14.522  1702  2044 D TP/MmsSmsProvider: update, match 300:Elapsed time : 1.747 ms
,08-23 13:27:14.522  6702  6746 D Mms/Synchronizer: [end]    doSync consume time = 4.849375
,08-23 13:27:14.532  6257  6269 D BadgeProvider: query, [selection] : package=?
,08-23 13:27:14.532  6702  6743 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-23 13:27:14.562  1702  1716 D TP/SmsProvider: query,matched:26, calling pid = 6702
,08-23 13:27:14.562  1702  1716 D TP/SmsProvider: query, match 26:Elapsed time : 1.924 ms
,08-23 13:27:14.562   763  2146 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-23 13:27:14.562  6747  6747 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:14.562  6747  6747 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:14.562  6635  6635 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:27:14.572   763  2501 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ab4771a 6747:com.samsung.android.bbc.bbcagent/1000}
,08-23 13:27:14.582  6702  6745 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 53.686875
,08-23 13:27:14.612  1702  2044 D TP/MmsSmsProvider: query, match:6, calling pid = 6702, accessRestricted = false
,08-23 13:27:14.612  1702  2044 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.263 ms
,08-23 13:27:14.622  6747  6747 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-23 13:27:14.642  6761  6761 E Zygote  : v2
08-23 13:27:14.642  6761  6761 I libpersona: KNOX_SDCARD checking this for 10024
08-23 13:27:14.642  6761  6761 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:14.642  6761  6761 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:14.642  6761  6761 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:14.642   763  1731 I ActivityManager: Start proc 6761:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-23 13:27:14.642  6761  6761 E Zygote  : accessInfo : 0
08-23 13:27:14.642  6761  6761 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-23 13:27:14.662  6747  6747 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-23 13:27:14.672  6761  6761 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:14.672  6761  6761 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:14.672   763  2526 I ActivityManager: Killing 5740:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-23 13:27:14.682   763  3710 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-23 13:27:14.692   763   774 I art     : Background partial concurrent mark sweep GC freed 152916(9MB) AllocSpace objects, 11(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.835ms total 163.604ms
,08-23 13:27:14.692   763  1621 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-23 13:27:14.692  6761  6761 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-23 13:27:14.712  6761  6761 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-23 13:27:14.712  6635  6772 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1715865296
,08-23 13:27:14.722  6635  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:27:14.722  6635  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:27:14.722  6635  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:27:14.722  6635  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:27:14.722  6635  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 13:27:14.722  6635  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af52326 added. We now have 1 listener(s)
,08-23 13:27:14.722  6635  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-23 13:27:14.722  6635  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-23 13:27:14.732  6635  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 13:27:14.732  6635  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 13:27:14.732  6635  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b3e9bd added. We now have 1 listener(s)
08-23 13:27:14.732  6635  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 13:27:14.732  6635  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 13:27:14.732  6635  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 13:27:14.732  6635  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 13:27:14.732  6635  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-23 13:27:14.732  6635  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 13:27:14.752  6774  6774 E Zygote  : v2
08-23 13:27:14.752  6774  6774 I libpersona: KNOX_SDCARD checking this for 10097
08-23 13:27:14.752  6774  6774 I libpersona: KNOX_SDCARD not a persona
,08-23 13:27:14.752  6774  6774 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:14.752  6774  6774 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:14.752   763   779 I ActivityManager: Start proc 6774:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-23 13:27:14.752   763  1321 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-23 13:27:14.752  6774  6774 E Zygote  : accessInfo : 0
08-23 13:27:14.752  6774  6774 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-23 13:27:14.752  6761  6761 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-23 13:27:14.752   763   779 I ActivityManager: Killing 4459:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-23 13:27:14.752  6702  6743 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-23 13:27:14.752  6635  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 13:27:14.752  6635  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-23 13:27:14.762   763  1321 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 13:27:14.772  6635  6772 D BluetoothAdapter: STATE_ON
,08-23 13:27:14.772  6635  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 13:27:14.772  6635  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:27:14.772  6635  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:27:14.772  6635  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 13:27:14.772  6635  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:27:14.772  6635  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:27:14.772  6635  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:27:14.772  6635  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:27:14.772  6635  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:27:14.772  6635  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:27:14.772  6635  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 13:27:14.772  6635  6772 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 13:27:14.772  6635  6635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:27:14.772  6635  6635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:27:14.782   763  1411 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-23 13:27:14.782  6774  6774 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:27:14.782  6774  6774 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:14.792   763   779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d33247d 6774:com.google.android.apps.docs/u0a97}
,08-23 13:27:14.792  6635  6635 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:27:14.802  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-23 13:27:14.802  6774  6774 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 13:27:14.812  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-23 13:27:14.812  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-23 13:27:14.812  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-23 13:27:14.812  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-23 13:27:14.812  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-23 13:27:14.812  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-23 13:27:14.812  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-23 13:27:14.812  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-23 13:27:14.812  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-23 13:27:14.822  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-23 13:27:14.822  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-23 13:27:14.822  6761  6761 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-23 13:27:14.822  6774  6774 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-23 13:27:15.082  4645  5311 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-23 13:27:15.112  6774  6789 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-23 13:27:15.112  6774  6789 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 13:27:15.112  6774  6789 I GAv4    :   adb logcat -s GAv4
,08-23 13:27:15.112  1441  1441 D Recents : onTaskStackChanged
,08-23 13:27:15.122  1441  1441 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 13:27:15.182  6774  6789 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 13:27:15.182   763  2526 V AlarmManager:  remove PendingIntent] PendingIntent{6d28b79: PendingIntentRecord{6ba70be com.google.android.apps.docs broadcastIntent}}
,08-23 13:27:15.182  6774  6789 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 13:27:15.182  6774  6789 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 13:27:15.212  6774  6794 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 13:27:15.322  4645  5311 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-23 13:27:15.392   763  6420 I HarmonyEASService: Updating for all 1
,08-23 13:27:15.402  6774  6774 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-23 13:27:15.402  6774  6774 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-23 13:27:15.442  6774  6789 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-23 13:27:15.442  6774  6789 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-23 13:27:15.442  6774  6789 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-23 13:27:15.442  6774  6789 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-23 13:27:15.502   763  2526 I ActivityManager: Start proc 6801:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-23 13:27:15.502  6801  6801 E Zygote  : v2
08-23 13:27:15.502  6801  6801 I libpersona: KNOX_SDCARD checking this for 10098
08-23 13:27:15.502  6801  6801 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:15.502  6801  6801 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:15.502  6801  6801 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:15.502  6801  6801 E Zygote  : accessInfo : 0
,08-23 13:27:15.502  6801  6801 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-23 13:27:15.502   763  2526 I ActivityManager: Killing 5383:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-23 13:27:15.522  6801  6801 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:27:15.522  6801  6801 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:15.542   763  1730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f28daca 6801:com.sec.android.automotive.drivelink/u0a98}
,08-23 13:27:15.542  6801  6801 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 13:27:15.552   763  1411 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-23 13:27:15.562  6801  6801 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-23 13:27:15.562  4645  5311 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-23 13:27:15.592  6801  6801 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-23 13:27:15.622   763  1252 V AlarmManager:  remove PendingIntent] PendingIntent{94ae43b: PendingIntentRecord{70f5758 com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 13:27:15.622  6801  6817 I GMPM    : App measurement is starting up
,08-23 13:27:15.632  6801  6817 E GMPM    : getGoogleAppId failed with status: 10
,08-23 13:27:15.632  2060  2060 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:27:15.632  6801  6817 E GMPM    : Uploading is not possible. App measurement disabled
08-23 13:27:15.632  2060  2060 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:27:15.632  6801  6801 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-23 13:27:15.642   763  1621 V AlarmManager:  remove PendingIntent] PendingIntent{6ce9104: PendingIntentRecord{70f5758 com.sec.android.automotive.drivelink broadcastIntent}}
,08-23 13:27:15.672  2060  2060 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:27:15.672  6801  6801 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-23 13:27:15.672  6801  6801 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-23 13:27:15.712  6635  6786 W jxcore-log: Initializing JXcore engine
08-23 13:27:15.712  6635  6786 W jxcore-log: JXcore engine is ready
,08-23 13:27:15.732   763  2472 I ActivityManager: Start proc 6823:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-23 13:27:15.732  6823  6823 E Zygote  : v2
08-23 13:27:15.732  6823  6823 I libpersona: KNOX_SDCARD checking this for 10032
08-23 13:27:15.732  6823  6823 I libpersona: KNOX_SDCARD not a persona
,08-23 13:27:15.732   763  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 13:27:15.732  6823  6823 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:15.732  6823  6823 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:15.732  6823  6823 E Zygote  : accessInfo : 0
,08-23 13:27:15.732  6823  6823 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-23 13:27:15.742  6774  6790 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-23 13:27:15.752  6823  6823 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:15.752  6823  6823 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:15.762  2424  2424 E audit   : type=1400 msg=audit(1471951635.762:288): avc:  denied  { ioctl } for  pid=6786 comm="Thread-920" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 13:27:15.762  2424  2424 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:15.762  2424  2424 E audit   : type=1300 msg=audit(1471951635.762:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=98f9f3c8 items=0 ppid=350 ppcomm=main pid=6786 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-920" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 13:27:15.762  2424  2424 E audit   : type=1327 msg=audit(1471951635.762:288): proctitle="com.test.thalitest"
08-23 13:27:15.762  2424  2424 E audit   : type=1320 msg=audit(1471951635.762:288): 
,08-23 13:27:15.762  2424  2424 E audit   : type=1400 msg=audit(1471951635.762:289): avc:  denied  { ioctl } for  pid=6786 comm="Thread-920" path="socket:[41802]" dev="sockfs" ino=41802 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-23 13:27:15.762  2424  2424 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:15.762  2424  2424 E audit   : type=1300 msg=audit(1471951635.762:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=98f9f3c8 items=0 ppid=350 ppcomm=main pid=6786 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-920" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 13:27:15.762  2424  2424 E audit   : type=1327 msg=audit(1471951635.762:289): proctitle="com.test.thalitest"
08-23 13:27:15.762  2424  2424 E audit   : type=1320 msg=audit(1471951635.762:289): 
,08-23 13:27:15.772   763  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-23 13:27:15.772  6823  6823 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-23 13:27:15.782  6635  6786 W jxcore-log: Starting JXcore engine
,08-23 13:27:15.792  6823  6823 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-23 13:27:15.802  6774  6790 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-23 13:27:15.822  6774  6790 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-23 13:27:15.822  6774  6790 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-23 13:27:15.832  6774  6790 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 13:27:15.862  6774  6790 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 13:27:15.872  6635  6786 W jxcore-log: Platform android
08-23 13:27:15.872  6635  6786 W jxcore-log: 
,08-23 13:27:15.882  6635  6786 W jxcore-log: Process ARCH arm
08-23 13:27:15.882  6635  6786 W jxcore-log: 
,08-23 13:27:15.912  6801  6801 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-23 13:27:15.922  6823  6823 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-23 13:27:15.942  6801  6801 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-23 13:27:15.942  6801  6801 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-23 13:27:15.952  6823  6823 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-23 13:27:15.962  6801  6801 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Aug 23 13:27:15 GMT+02:00 2016
,08-23 13:27:15.972  6801  6801 D DialogFlow: initQueue()
,08-23 13:27:15.972   763  2448 I ActivityManager: Start proc 6837:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-23 13:27:15.972  6837  6837 E Zygote  : v2
,08-23 13:27:15.972  6837  6837 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:27:15.972   763  2448 I ActivityManager: Killing 5424:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
08-23 13:27:15.972  6837  6837 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:15.972   763  2448 I ActivityManager: Killing 5363:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-23 13:27:15.972  6837  6837 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:15.972  6837  6837 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:15.972  6837  6837 E Zygote  : accessInfo : 0
,08-23 13:27:16.002   763  2526 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-23 13:27:16.002  6837  6837 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:27:16.002  6837  6837 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:16.012   763  2450 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b9522b 6837:com.samsung.android.app.filterinstaller/1000}
,08-23 13:27:16.012   763   779 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-23 13:27:16.012  6837  6837 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-23 13:27:16.032  6837  6837 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-23 13:27:16.032  6837  6837 E FilterPackageIntentReceiver: This package is not a effect filter
,08-23 13:27:16.042  6853  6853 E Zygote  : v2
08-23 13:27:16.042  6853  6853 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:27:16.042  6853  6853 I libpersona: KNOX_SDCARD not a persona
,08-23 13:27:16.042  6853  6853 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:16.042  6853  6853 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:16.042   763  1621 I ActivityManager: Start proc 6853:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-23 13:27:16.052  6853  6853 E Zygote  : accessInfo : 0
,08-23 13:27:16.052   763  1621 I ActivityManager: Killing 4896:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-23 13:27:16.062   763  2526 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-23 13:27:16.072  6853  6853 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:27:16.072  6853  6853 D ActivityThread: Added TimaKeyStore provider
08-23 13:27:16.072   763  2448 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-23 13:27:16.082   763  1252 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{178e607 6853:com.samsung.helphub/1000}
,08-23 13:27:16.092  6853  6853 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-23 13:27:16.112  6853  6853 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-23 13:27:16.122  6823  6823 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-23 13:27:16.122  6823  6823 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-23 13:27:16.122  6823  6823 D DialogFlow: initQueue()
,08-23 13:27:16.142  6635  6786 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:27:16.142  6635  6786 I jxcore-log: 
,08-23 13:27:16.142  6635  6786 W jxcore-log: JXcore engine is started
,08-23 13:27:16.152  6635  6772 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 13:27:16.152  6635  6635 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-23 13:27:16.152  6865  6865 E Zygote  : v2
08-23 13:27:16.152  6865  6865 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:27:16.152  6865  6865 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:16.162  6865  6865 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:16.162  6865  6865 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:16.162   763   779 I ActivityManager: Start proc 6865:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-23 13:27:16.162  6865  6865 E Zygote  : accessInfo : 0
08-23 13:27:16.162   763   779 I ActivityManager: Killing 5313:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
08-23 13:27:16.182  6635  6786 E jxcore  : Error!: missing name after . operator
08-23 13:27:16.182  6635  6786 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:27:16.182  6865  6865 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:16.182  6865  6865 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:16.182   763  2501 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-23 13:27:16.182  6635  6635 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
08-23 13:27:16.182  6635  6635 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:27:16.192   763  2450 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb3dba3 6865:com.samsung.android.app.mirrorlink/1000}
08-23 13:27:16.192   763  1411 D InputDispatcher: Focused application set to: xxxx
08-23 13:27:16.202  6865  6865 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
08-23 13:27:16.202   763  1411 I ActivityManager: Killing 5813:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-23 13:27:16.212  6635  6772 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 13:27:16.212  6865  6865 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
08-23 13:27:16.212  6635  6635 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 13:27:16.212   763  1730 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
08-23 13:27:16.212  6635  6635 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-23 13:27:16.222  6635  6635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:27:16.222  6635  6635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:27:16.222  6635  6635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:27:16.222  6635  6635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:27:16.222  6635  6635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af52326 removed from the list
,08-23 13:27:16.222  6635  6635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:27:16.222  6635  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b3e9bd removed from the list
08-23 13:27:16.222  6635  6635 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:27:16.222  6635  6635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 13:27:16.222  6635  6635 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 13:27:16.222  6635  6635 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,08-23 13:27:16.232  6635  6635 D ViewRootImpl: #3 mView = null
,08-23 13:27:16.242   293  1295 I SurfaceFlinger: id=22 Removed NainActivit (6/8)
,08-23 13:27:16.242   293   420 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
,08-23 13:27:16.242   763   779 D InputDispatcher: Focus left window: 6635
,08-23 13:27:16.242   763   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:763 uid:1000
,08-23 13:27:16.242   763   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:27:16.242   763   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:763 uid:1000
08-23 13:27:16.242   763   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 13:27:16.242   763  1624 D ActivityManager: mDVFSHelper.acquire()
,08-23 13:27:16.242   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbec693a4
,08-23 13:27:16.252  6635  6635 D cr_Ime  : [ImeAdapter.java:587] detach
,08-23 13:27:16.252   763  1624 V WindowOrientationListener: setCurrentAppOrientation :1
08-23 13:27:16.252   763  1624 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-23 13:27:16.262  6635  6635 E ViewRootImpl: sendUserActionEvent() mView == null
,08-23 13:27:16.262   763   862 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.wssyncmldm
,08-23 13:27:16.272  4707  4707 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(754/onResume)] 
,08-23 13:27:16.282  6865  6865 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
08-23 13:27:16.282  6865  6865 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-23 13:27:16.282  1717  1717 D Launcher: onRestart, Launcher: 158658077
,08-23 13:27:16.292   763  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b662d80 5924:com.google.android.apps.plus/u0a134}
,08-23 13:27:16.302  1717  1717 D Launcher: onStart, Launcher: 158658077
,08-23 13:27:16.302  1717  1717 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,08-23 13:27:16.302  1717  1717 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-23 13:27:16.302  1717  1717 D Launcher.HomeView: onStart
,08-23 13:27:16.302   763  2147 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-23 13:27:16.302   763  2147 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 13:27:16.302   763   763 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 13:27:16.302   763   763 I KnoxTimeoutHandler: Shared devices show user statefalse
08-23 13:27:16.302   763   763 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-23 13:27:16.312  4707  4707 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(747/onPause)] 
,08-23 13:27:16.312  1717  1717 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
08-23 13:27:16.312  1717  1717 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,08-23 13:27:16.312  2107  2120 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
08-23 13:27:16.312   763  2146 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b662d80 5924:com.google.android.apps.plus/u0a134}
,08-23 13:27:16.312  1717  1717 V ActivityThread: updateVisibility : ActivityRecord{66cb2d7 token=android.os.BinderProxy@13fe4e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-23 13:27:16.312   293   293 I SurfaceFlinger: id=23 createSurf (1080x1920),1 flag=4, Mauncher
,08-23 13:27:16.322   763   867 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ee837c4 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
,08-23 13:27:16.322   293   293 I SurfaceFlinger: id=24 createSurf (1146x1992),1 flag=4, YUIInstallC
,08-23 13:27:16.332   763   867 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{b6f22c6 u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}
,08-23 13:27:16.332  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-23 13:27:16.332   763  2147 D InputDispatcher: Focus entered window: 4707
,08-23 13:27:16.332   763   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:763 uid:1000
08-23 13:27:16.332   763   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:27:16.332   763   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:763 uid:1000
08-23 13:27:16.332   763   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 13:27:16.342   293   293 I SurfaceFlinger: id=25 createSurf (145x145),1 flag=4, YUIInstallC
,08-23 13:27:16.352   763  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-23 13:27:16.352   763  2448 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b662d80 5924:com.google.android.apps.plus/u0a134}
,08-23 13:27:16.352  4707  4707 V ActivityThread: updateVisibility : ActivityRecord{1778293 token=android.os.BinderProxy@b8d412b {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-23 13:27:16.362   293   420 I SurfaceFlinger: id=24 Removed YUIInstallC (8/10)
,08-23 13:27:16.372   763   867 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ca875b4 u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}
,08-23 13:27:16.372   293   424 I SurfaceFlinger: id=24 Removed YUIInstallC (-2/10)
,08-23 13:27:16.372   763  2146 D InputDispatcher: Focus left window: 4707
08-23 13:27:16.372   763  2146 D InputDispatcher: Focus entered window: 4707
,08-23 13:27:16.372   763   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:763 uid:1000
,08-23 13:27:16.372   763   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:27:16.372   763   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:763 uid:1000
08-23 13:27:16.372   763   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 13:27:16.382  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
,08-23 13:27:16.402   763  1252 V WindowStateAnimator: Finishing drawing window Window{ca875b4 u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: mDrawState=DRAW_PENDING
,08-23 13:27:16.402   763  2448 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 13:27:16.412   763   906 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 13:27:16.412   763   763 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-23 13:27:16.412   763   906 D ActivityManager: mDVFSHelper.release()
,08-23 13:27:16.412   763   906 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7a68816 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity t167} time:103084
,08-23 13:27:16.412   763   763 I KnoxTimeoutHandler: SD activityfalse
,08-23 13:27:16.412  4707  4707 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b8d412b time:103085
,08-23 13:27:16.422  2149  2149 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-23 13:27:16.462   763  2448 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-23 13:27:16.462   763  1731 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-23 13:27:16.462   763  2147 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-23 13:27:16.472   763  1638 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-23 13:27:16.472   763  1730 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-23 13:27:16.472   763  2472 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-23 13:27:16.472   763  2501 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-23 13:27:16.482   763  1624 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-23 13:27:16.512   763  2501 V WindowStateAnimator: Finishing drawing window Window{ee837c4 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-23 13:27:16.522  1717  1717 D Launcher.HomeView: onStop
,08-23 13:27:16.522  6889  6889 E Zygote  : v2
08-23 13:27:16.522  6889  6889 I libpersona: KNOX_SDCARD checking this for 10165
08-23 13:27:16.522  6889  6889 I libpersona: KNOX_SDCARD not a persona
,08-23 13:27:16.522  6889  6889 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:16.522  6889  6889 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:16.522   763  1730 I ActivityManager: Start proc 6889:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-23 13:27:16.522  6889  6889 E Zygote  : accessInfo : 0
,08-23 13:27:16.522  6889  6889 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-23 13:27:16.522   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbec69364
,08-23 13:27:16.532  6702  6702 I Mms/MmsApp:  start initViewCache mms
,08-23 13:27:16.532   763  1730 I ActivityManager: Killing 5626:com.policydm/1000 (adj 15): DHA:empty #37
,08-23 13:27:16.532   763   906 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 13:27:16.532   763   763 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 13:27:16.532   763   906 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{111913a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t165} time:103208
,08-23 13:27:16.532   763   763 I KnoxTimeoutHandler: SD activityfalse
,08-23 13:27:16.552  6889  6889 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:16.552  6889  6889 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:16.562   763  2146 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1e8eff 6889:com.sec.kidsplat.installer/u0a165}
,08-23 13:27:16.572   763  1730 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
08-23 13:27:16.572  6889  6889 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
08-23 13:27:16.572  6650  6650 D AASAservice: onDestroy()
,08-23 13:27:16.592  6650  6650 I art     : System.exit called, status: 80
08-23 13:27:16.592  6650  6650 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-23 13:27:16.592  6889  6889 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-23 13:27:16.602   763  2146 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1e8eff 6889:com.sec.kidsplat.installer/u0a165}
,08-23 13:27:16.612   763  1252 I ActivityManager: Process com.samsung.aasaservice (pid 6650)(adj 0) has died(77,726)
,08-23 13:27:16.612   763  1252 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-23 13:27:16.612  6889  6889 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-23 13:27:16.632   763  2147 I ActivityManager: Start proc 6903:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-23 13:27:16.632  6903  6903 E Zygote  : v2
08-23 13:27:16.632  6903  6903 I libpersona: KNOX_SDCARD checking this for 10142
08-23 13:27:16.632  6903  6903 I libpersona: KNOX_SDCARD not a persona
08-23 13:27:16.632  6903  6903 E Zygote  : isSdpEnabledProcess - SDP enabled
,08-23 13:27:16.632  6903  6903 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 13:27:16.632  6903  6903 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:16.632  6903  6903 E Zygote  : accessInfo : 64
08-23 13:27:16.632  6903  6903 E Zygote  : isSdpEnabledProcess - SDP enabled
08-23 13:27:16.632  6903  6903 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-23 13:27:16.632  6903  6903 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-23 13:27:16.652  6903  6903 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:27:16.652  6903  6903 D ActivityThread: Added TimaKeyStore provider
,08-23 13:27:16.662   350   350 I Zygote  : Process 6650 exited cleanly (80)
,08-23 13:27:16.662   763  2526 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c82315 6903:com.sec.android.app.sbrowser/u0a142}
,08-23 13:27:16.662  6903  6903 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 13:27:16.702  6903  6903 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-23 13:27:16.732  6903  6903 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-23 13:27:16.732  6903  6903 D ManifestProvider: onCreate()
,08-23 13:27:16.742  6903  6903 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-23 13:27:16.742  6903  6903 I SBrowserUtils: getSystemProperty of country_code : Poland
08-23 13:27:16.742  6903  6903 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-23 13:27:16.742  6903  6903 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-23 13:27:16.752  6903  6903 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-23 13:27:16.762  6903  6903 D [MM]MHDataBaseProvider: onCreate()
,08-23 13:27:16.782  6903  6903 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@c796284)
,08-23 13:27:16.812   763  1624 I ActivityManager: Killing 5841:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-23 13:27:16.812   763  1624 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7d9926 2060:com.google.android.gms.persistent/u0a11}
,08-23 13:27:16.832  4645  6918 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:27:16.832   763  2450 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ebbbd54 4645:com.google.android.gms/u0a11}
,08-23 13:27:16.832  4645  6917 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-23 13:27:16.852  4645  6918 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:27:16.852   763  1624 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-23 13:27:16.852  4645  4645 D AsyncTaskServiceImpl: Submit a task: nzm
,08-23 13:27:16.872   763  2448 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7d9926 2060:com.google.android.gms.persistent/u0a11}
,08-23 13:27:16.882  4645  6918 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:27:16.882  4645  5311 D nzm     : Processing package: com.test.thalitest
,08-23 13:27:16.892   763  2146 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ebbbd54 4645:com.google.android.gms/u0a11}
,08-23 13:27:16.892  4645  6918 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-23 13:27:16.902  4645  4645 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-23 13:27:16.922  6702  6702 D Mms/BubbleViewCache: fillCache bubble = 4
,08-23 13:27:16.932  4645  5311 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-23 13:27:16.932  4645  5311 D nzm     : Found info for package com.test.thalitest in db.
,08-23 13:27:16.992   763  2472 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f98544b 5949:com.android.vending/u0a29}
,08-23 13:27:17.022   763  3742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 13:27:17.032  5949  5949 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-23 13:27:17.032   763  2448 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5469c1a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c9059e 6351:com.sec.android.app.samsungapps/u0a39}
,08-23 13:27:17.042  2060  2060 D WearableService: callingUid 10011, callindPid: 2060
,08-23 13:27:17.052  5949  5949 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-23 13:27:17.052   763  1621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4c3cdda u0 com.google.android.vending.verifier.intent.action.VERIFY_INSTALLED_PACKAGES qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f98544b 5949:com.android.vending/u0a29}
,08-23 13:27:17.062  5949  5949 I Finsky  : [1] com.google.android.vending.verifier.VerifyInstalledPackagesReceiver.onReceive(42): Verify installed apps requested
,08-23 13:27:17.072  5949  5949 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-23 13:27:17.072   763  2526 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{412cb01 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7d9926 2060:com.google.android.gms.persistent/u0a11}
,08-23 13:27:17.082  5949  5949 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-23 13:27:17.082  5949  6924 I Finsky  : [860] com.google.android.vending.verifier.ac.a(103): Verifying installed packages
,08-23 13:27:17.092   763  1252 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9a0eda6 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f98544b 5949:com.android.vending/u0a29}
,08-23 13:27:17.092   763  1411 V AlarmManager:  remove PendingIntent] PendingIntent{651f3e7: PendingIntentRecord{da0ec20 com.google.android.gms broadcastIntent}}
,08-23 13:27:17.102   763  1624 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e60163d u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f9f0b04 5996:com.sec.android.app.shealth/u0a34}
,08-23 13:27:17.122  5949  6926 I Finsky  : [861] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-23 13:27:17.122  5949  5973 I PlayCommon: [829] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-23 13:27:17.122   763  2501 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e60163d u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{93f5495 1999:com.sec.android.app.shealth:remote/u0a34}
,08-23 13:27:17.142  5949  6927 I PlayCommon: [862] com.google.android.play.a.w.a(27553): Starting to flush logs
,08-23 13:27:17.142  5949  6927 I PlayCommon: [862] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,08-23 13:27:17.152   763  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e60163d u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{93f5495 1999:com.sec.android.app.shealth:remote/u0a34}
,08-23 13:27:17.172   763  2472 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c2e0b7e u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7d9926 2060:com.google.android.gms.persistent/u0a11}
,08-23 13:27:17.212  2060  2060 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 13:27:17.222  6823  6851 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-23 13:27:17.222  6823  6851 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 13:27:17.242  5949  5973 I PlayCommon: [829] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-23 13:27:17.242  5949  5973 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 13:27:17.242  5949  5973 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 13:27:17.252   306  1180 D EnterpriseController: netId is 0
08-23 13:27:17.252   306  1180 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-23 13:27:17.262  5949  5949 I Finsky  : [1] com.google.android.vending.verifier.ac.b(136): Done verifying installed packages
,08-23 13:27:17.272  6823  6851 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 13:27:17.272  6823  6851 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-23 13:27:17.272  6823  6851 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-23 13:27:17.272  6823  6851 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 13:27:17.272  6823  6851 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 13:27:17.322  1441  1441 D Recents : onTaskStackChanged
,08-23 13:27:17.332  2424  2424 E audit   : type=1400 msg=audit(1471951637.332:290): avc:  denied  { execmod } for  pid=6877 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-23 13:27:17.332  2424  2424 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 13:27:17.332  1441  1441 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
08-23 13:27:17.332  2424  2424 E audit   : type=1300 msg=audit(1471951637.332:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f45000 a1=51000 a2=5 a3=4 items=0 ppid=3851 ppcomm=adbd pid=6877 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:27:17.332  2424  2424 E audit   : type=1327 msg=audit(1471951637.332:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-23 13:27:17.332  2424  2424 E audit   : type=1320 msg=audit(1471951637.332:290): 
,08-23 13:27:17.392  2424  2424 E audit   : type=1400 msg=audit(1471951637.392:291): avc:  denied  { execmod } for  pid=6877 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:27:17.392  2424  2424 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:17.392  2424  2424 E audit   : type=1300 msg=audit(1471951637.392:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f08000 a1=51000 a2=5 a3=4 items=0 ppid=3851 ppcomm=adbd pid=6877 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:27:17.392  2424  2424 E audit   : type=1327 msg=audit(1471951637.392:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 13:27:17.392  2424  2424 E audit   : type=1320 msg=audit(1471951637.392:291): 
,08-23 13:27:17.442  2424  2424 E audit   : type=1400 msg=audit(1471951637.442:292): avc:  denied  { execmod } for  pid=6877 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 13:27:17.442  2424  2424 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-23 13:27:17.442  2424  2424 E audit   : type=1300 msg=audit(1471951637.442:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f08000 a1=51000 a2=5 a3=4 items=0 ppid=3851 ppcomm=adbd pid=6877 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 13:27:17.442  2424  2424 E audit   : type=1327 msg=audit(1471951637.442:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 13:27:17.442  2424  2424 E audit   : type=1320 msg=audit(1471951637.442:292): 
,08-23 13:27:17.442  6877  6877 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 13:27:17.452  6877  6877 D AndroidRuntime: CheckJNI is OFF
,08-23 13:27:17.452  6877  6877 D AndroidRuntime: readGMSProperty: start
08-23 13:27:17.452  6877  6877 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:27:17.452  6877  6877 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:27:17.452  6877  6877 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:27:17.452  6877  6877 D AndroidRuntime: readGMSProperty: end
08-23 13:27:17.452  6877  6877 D AndroidRuntime: addProductProperty: start
,08-23 13:27:17.462  6877  6877 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:27:17.462  6877  6877 W art     : aed6c000-b1c92000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:27:17.462  6877  6877 W art     : b1c92000-b3f01000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:27:17.462  6877  6877 W art     : b3f01000-b3f02000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 13:27:17.462  6877  6877 W art     : b3f02000-b3f03000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b423a000-b4263000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 13:27:17.462  6877  6877 W art     : b4263000-b46b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 13:27:17.462  6877  6877 W art     : b46b1000-b46b2000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b46b2000-b46bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 13:27:17.462  6877  6877 W art     : b46bc000-b46bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 13:27:17.462  6877  6877 W art     : b46bd000-b46bf000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b46bf000-b46c0000 r--p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 13:27:17.462  6877  6877 W art     : b47d6000-b47d9000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:27:17.462  6877  6877 W art     : b47d9000-b47da000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:27:17.462  6877  6877 W art     : b47da000-b47db000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 13:27:17.462  6877  6877 W art     : b47db000-b47dc000 r--p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b47dc000-b47fc000 r--s 00000000 00:0b 6700       /dev/__properties__
08-23 13:27:17.462  6877  6877 W art     : b47fc000-b520d000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:27:17.462  6877  6877 W art     : b520d000-b520e000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b520e000-b5257000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:27:17.462  6877  6877 W art     : b5257000-b5258000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 13:27:17.462  6877  6877 W art     : b5258000-b5260000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5260000-b5261000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b5261000-b5296000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:27:17.462  6877  6877 W art     : b5296000-b5297000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5297000-b5298000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:27:17.462  6877  6877 W art     : b5298000-b5299000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 13:27:17.462  6877  6877 W art     : b5299000-b52f1000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 13:27:17.462  6877  6877 W art     : b52f1000-b52f2000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b52f2000-b52f3000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 13:27:17.462  6877  6877 W art     : b52f3000-b52f4000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 13:27:17.462  6877  6877 W art     : b52f5000-b52fb000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:27:17.462  6877  6877 W art     : b52fb000-b52fc000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:27:17.462  6877  6877 W art     : b52fc000-b52fd000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 13:27:17.462  6877  6877 W art     : b52fd000-b52ff000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5300000-b530a000 r-xp 00000000 b3:17 1,088       /system/lib/libcommon_time_client.so
08-23 13:27:17.462  6877  6877 W art     : b530a000-b530d000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:27:17.462  6877  6877 W art     : b530d000-b530e000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 13:27:17.462  6877  6877 W art     : b530f000-b5326000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:27:17.462  6877  6877 W art     : b5326000-b5327000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5327000-b5328000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:27:17.462  6877  6877 W art     : b5328000-b5329000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 13:27:17.462  6877  6877 W art     : b532a000-b5334000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:27:17.462  6877  6877 W art     : b5334000-b5335000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:27:17.462  6877  6877 W art     : b5335000-b5336000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 13:27:17.462  6877  6877 W art     : b5336000-b533a000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:27:17.462  6877  6877 W art     : b533a000-b533b000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:27:17.462  6877  6877 W art     : b533b000-b533c000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 13:27:17.462  6877  6877 W art     : b533c000-b5352000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 13:27:17.462  6877  6877 W art     : b5352000-b5353000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 13:27:17.462  6877  6877 W art     : b5353000-b5354000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 13:27:17.462  6877  6877 W art     : b5354000-b5361000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:27:17.462  6877  6877 W art     : b5361000-b5362000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:27:17.462  6877  6877 W art     : b5362000-b5363000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 13:27:17.462  6877  6877 W art     : b5363000-b53c3000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 13:27:17.462  6877  6877 W art     : b53c3000-b53c6000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 13:27:17.462  6877  6877 W art     : b53c6000-b53ca000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b53ca000-b542b000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:27:17.462  6877  6877 W art     : b542b000-b542c000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 13:27:17.462  6877  6877 W art     : b542c000-b547b000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
,08-23 13:27:17.462  6877  6877 W art     : b547b000-b547d000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:27:17.462  6877  6877 W art     : b547d000-b547e000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 13:27:17.462  6877  6877 W art     : b547e000-b547f000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b547f000-b5486000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:27:17.462  6877  6877 W art     : b5486000-b5487000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 13:27:17.462  6877  6877 W art     : b5487000-b5488000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-23 13:27:17.462  6877  6877 W art     : b5489000-b548c000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:27:17.462  6877  6877 W art     : b548c000-b548d000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:27:17.462  6877  6877 W art     : b548d000-b548e000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 13:27:17.462  6877  6877 W art     : b548f000-b5493000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:27:17.462  6877  6877 W art     : b5493000-b5494000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5494000-b5495000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
,08-23 13:27:17.462  6877  6877 W art     : b5495000-b5496000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-23 13:27:17.462  6877  6877 W art     : b5497000-b54b4000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:27:17.462  6877  6877 W art     : b54b4000-b54b5000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:27:17.462  6877  6877 W art     : b54b5000-b54b6000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 13:27:17.462  6877  6877 W art     : b54b7000-b54bc000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-23 13:27:17.462  6877  6877 W art     : b54bc000-b54bd000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-23 13:27:17.462  6877  6877 W art     : b54bd000-b54be000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 13:27:17.462  6877  6877 W art     : b54bf000-b54f0000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:27:17.462  6877  6877 W art     : b54f0000-b54f3000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 13:27:17.462  6877  6877 W art     : b54f3000-b54f4000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-23 13:27:17.462  6877  6877 W art     : b54f5000-b5530000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 13:27:17.462  6877  6877 W art     : b5530000-b5531000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 13:27:17.462  6877  6877 W art     : b5531000-b5532000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 13:27:17.462  6877  6877 W art     : b5533000-b553a000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:27:17.462  6877  6877 W art     : b553a000-b553b000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b553b000-b553c000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
,08-23 13:27:17.462  6877  6877 W art     : b553c000-b553d000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 13:27:17.462  6877  6877 W art     : b553d000-b553e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b553e000-b5555000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:27:17.462  6877  6877 W art     : b5555000-b5556000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5556000-b5559000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:27:17.462  6877  6877 W art     : b5559000-b555a000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 13:27:17.462  6877  6877 W art     : b555a000-b5579000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:27:17.462  6877  6877 W art     : b5579000-b557a000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:27:17.462  6877  6877 W art     : b557a000-b557b000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 13:27:17.462  6877  6877 W art     : b557b000-b55b9000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 13:27:17.462  6877  6877 W art     : b55b9000-b55ba000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b55ba000-b55bc000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 13:27:17.462  6877  6877 W art     : b55bc000-b55bd000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 13:27:17.462  6877  6877 W art     : b55be000-b55c5000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:27:17.462  6877  6877 W art     : b55c5000-b55c6000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:27:17.462  6877  6877 W art     : b55c6000-b55c7000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 13:27:17.462  6877  6877 W art     : b55c8000-b55cb000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:27:17.462  6877  6877 W art     : b55cb000-b55cc000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:27:17.462  6877  6877 W art     : b55cc000-b55cd000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 13:27:17.462  6877  6877 W art     : b55cd000-b55d3000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:27:17.462  6877  6877 W art     : b55d3000-b55d4000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b55d4000-b55d5000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:27:17.462  6877  6877 W art     : b55d5000-b55d6000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 13:27:17.462  6877  6877 W art     : b55d6000-b55df000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:27:17.462  6877  6877 W art     : b55df000-b55e0000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:27:17.462  6877  6877 W art     : b55e0000-b55e1000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 13:27:17.462  6877  6877 W art     : b55e1000-b5672000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:27:17.462  6877  6877 W art     : b5672000-b5673000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5673000-b567e000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:27:17.462  6877  6877 W art     : b567e000-b567f000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 13:27:17.462  6877  6877 W art     : b5680000-b5692000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 13:27:17.462  6877  6877 W art     : b5692000-b5693000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 13:27:17.462  6877  6877 W art     : b5693000-b5694000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 13:27:17.462  6877  6877 W art     : b5695000-b569a000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:27:17.462  6877  6877 W art     : b569a000-b569b000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:27:1,7.462  6877  6877 W art     : b569b000-b569c000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 13:27:17.462  6877  6877 W art     : b569d000-b570a000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:27:17.462  6877  6877 W art     : b570a000-b570b000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b570b000-b570d000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:27:17.462  6877  6877 W art     : b570d000-b570e000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 13:27:17.462  6877  6877 W art     : b570e000-b570f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b570f000-b5716000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:27:17.462  6877  6877 W art     : b5716000-b5717000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:27:17.462  6877  6877 W art     : b5717000-b5718000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 13:27:17.462  6877  6877 W art     : b5719000-b5799000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:27:17.462  6877  6877 W art     : b5799000-b579a000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b579a000-b579b000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:27:17.462  6877  6877 W art     : b579b000-b579c000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 13:27:17.462  6877  6877 W art     : b579c000-b57b3000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b57b3000-b57ea000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 13:27:17.462  6877  6877 W art     : ib/libqc-opt.so
08-23 13:27:17.462  6877  6877 W art     : b57ea000-b57eb000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:27:17.462  6877  6877 W art     : b57eb000-b57ec000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 13:27:17.462  6877  6877 W art     : b57ec000-b5808000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:27:17.462  6877  6877 W art     : b5808000-b5809000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:27:17.462  6877  6877 W art     : b5809000-b580a000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 13:27:17.462  6877  6877 W art     : b580b000-b586c000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 13:27:17.462  6877  6877 W art     : b586c000-b586e000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 13:27:17.462  6877  6877 W art     : b586e000-b586f000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 13:27:17.462  6877  6877 W art     : b5870000-b5897000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 13:27:17.462  6877  6877 W art     : b5897000-b5898000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5898000-b5899000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 13:27:17.462  6877  6877 W art     : b5899000-b589a000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 13:27:17.462  6877  6877 W art     : b589b000-b58a3000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:27:17.462  6877  6877 W art     : b58a3000-b58a5000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:27:17.462  6877  6877 W art     : b58a5000-b58a6000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 13:27:17.462  6877  6877 W art     : b58a7000-b58aa000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 13:27:17.462  6877  6877 W art     : b58aa000-b58ab000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 13:27:17.462  6877  6877 W art     : b58ab000-b58ac000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 13:27:17.462  6877  6877 W art     : b58ac000-b58b0000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
,08-23 13:27:17.462  6877  6877 W art     : b58b0000-b58b1000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b58b1000-b58b2000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:27:17.462  6877  6877 W art     : b58b2000-b58b3000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 13:27:17.462  6877  6877 W art     : b58b3000-b58c3000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 13:27:17.462  6877  6877 W art     : b58c3000-b58c4000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 13:27:17.462  6877  6877 W art     : b58c4000-b58c5000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 13:27:17.462  6877  6877 W art     : b58c5000-b590b000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b590b000-b5914000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
,08-23 13:27:17.462  6877  6877 W art     : b5914000-b5915000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 13:27:17.462  6877  6877 W art     : b5915000-b5916000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 13:27:17.462  6877  6877 W art     : b5917000-b591c000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 13:27:17.462  6877  6877 W art     : b591c000-b591d000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so,
,08-23 13:27:17.462  6877  6877 W art     : b591d000-b591e000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 13:27:17.462  6877  6877 W art     : b591e000-b5921000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:27:17.462  6877  6877 W art     : b5921000-b5922000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5922000-b5923000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:27:17.462  6877  6877 W art     : b5923000-b5924000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 13:27:17.462  6877  6877 W art     : b5925000-b593d000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:27:17.462  6877  6877 W art     : b593d000-b593e000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b593e000-b593f000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:27:17.462  6877  6877 W art     : b593f000-b5940000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 13:27:17.462  6877  6877 W art     : b5941000-b5adb000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:27:17.462  6877  6877 W art     : b5adb000-b5adc000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5adc000-b5ae9000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:27:17.462  6877  6877 W art     : b5ae9000-b5aea000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 13:27:17.462  6877  6877 W art     : b5aea000-b5aee000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 13:27:17.462  6877  6877 W art     : b5aee000-b5aef000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5aef000-b5af0000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 13:27:17.462  6877  6877 W art     : b5af0000-b5af1000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 13:27:17.462  6877  6877 W art     : b5af1000-b5b04000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:27:17.462  6877  6877 W art     : b5b04000-b5b05000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:27:17.462  6877  6877 W art     : b5b05000-b5b06000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 13:27:17.462  6877  6877 W art     : b5b07000-b5b52000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:27:17.462  6877  6877 W art     : b5b52000-b5b53000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:27:17.462  6877  6877 W art     : b5b53000-b5b54000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 13:27:17.462  6877  6877 W art     : b5b54000-b5b56000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5b56000-b5b57000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:17.462  6877  6877 W art     : b5b57000-b5b68000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:27:17.462  6877  6877 W art     : b5b68000-b5b69000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5b69000-b5b6a000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:27:17.462  6877  6877 W art     : b5b6a000-b5b6b000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 13:27:17.462  6877  6877 W art     : b5b6c000-b5b76000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:27:17.462  6877  6877 W art     : b5b76000-b5b78000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:27:17.462  6877  6877 W art     : b5b78000-b5b79000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 13:27:17.462  6877  6877 W art     : b5b79000-b5b92000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:27:17.462  6877  6877 W art     : b5b92000-b5b93000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:27:17.462  6877  6877 W art     : b5b93000-b5b96000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 13:27:17.462  6877  6877 W art     : b5b96000-b5b9a000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5b9a000-b5c0e000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 13:27:17.462  6877  6877 W art     : b5c0e000-b5c0f000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5c0f000-b5c12000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 13:27:17.462  6877  6877 W art     : b5c12000-b5c13000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 13:27:17.462  6877  6877 W art     : b5c14000-b5c17000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:27:17.462  6877  6877 W art     : b5c17000-b5c18000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:27:17.462  6877  6877 W art     : b5c18000-b5c19000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 13:27:17.462  6877  6877 W art     : b5c19000-b5c1a000 r--p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5c1a000-b5c1f000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:27:17.462  6877  6877 W art     : b5c1f000-b5c20000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:27:17.462  6877  6877 W art     : b5c20000-b5c21000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 13:27:17.462  6877  6877 W art     : b5c21000-b5c22000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b5c22000-b5c25000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:27:17.462  6877  6877 W art     : b5c25000-b5c26000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:27:17.462  6877  6877 W art     : b5c26000-b5c27000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 13:27:17.462  6877  6877 W art     : b5c27000-b5c28000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b5c28000-b5c2c000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:27:17.462  6877  6877 W art     : b5c2c000-b5c2d000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:27:17.462  6877  6877 W art     : b5c2d000-b5c2e000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 13:27:17.462  6877  6877 W art     : b5c2e000-b5c2f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:17.462  6877  6877 W art     : b5c2f000-b5c33000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:27:17.462  6877  6877 W art     : b5c33000-b5c34000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:27:17.462  6877  6877 W art     : b5c34000-b5c35000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 13:27:17.462  6877  6877 W art     : b5c35000-b5c36000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b5c36000-b5c44000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 13:27:17.462  6877  6877 W art     : b5c44000-b5c45000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b5c45000-b5c46000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 13:27:17.462  6877  6877 W art     : b5c46000-b5c47000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 13:27:17.462  6877  6877 W art     : b5c47000-b5c51000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:27:17.462  6877  6877 W art     : b5c51000-b5c54000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:27:17.462  6877  6877 W art     : b5c54000-b5c55000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 13:27:17.462  6877  6877 W art     : b5c55000-b5c56000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b5c56000-b5c60000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 13:27:17.462  6877  6877 W art     : b5c60000-b5c63000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 13:27:17.462  6877  6877 W art     : b5c63000-b5c64000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 13:27:17.462  6877  6877 W art     : b5c64000-b5c68000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:27:17.462  6877  6877 W art     : b5c68000-b5c69000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:27:17.462  6877  6877 W art     : b5c69000-b5c6a000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 13:27:17.462  6877  6877 W art     : b5c6a000-b5c6b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b5c6b000-b5c78000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:27:17.462  6877  6877 W art     : b5c78000-b5c7a000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:27:17.462  6877  6877 W art     : b5c7a000-b5c7b000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 13:27:17.462  6877  6877 W art     : b5c7b000-b608d000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 13:27:17.462  6877  6877 W art     : b608d000-b608e000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b608e000-b6097000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 13:27:17.462  6877  6877 W art     : b6097000-b609b000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 13:27:17.462  6877  6877 W art     : b609b000-b609c000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b609c000-b60a3000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-23 13:27:17.462  6877  6877 W art     : ioutils.so
08-23 13:27:17.462  6877  6877 W art     : b60a3000-b60a4000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:27:17.462  6877  6877 W art     : b60a4000-b60a5000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 13:27:17.462  6877  6877 W art     : b60a5000-b60a6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b60a6000-b60c1000 r-xp 00000000
08-23 13:27:17.462  6877  6877 W art     :  b3:17 1184       /system/lib/libz.so
08-23 13:27:17.462  6877  6877 W art     : b60c1000-b60c2000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 13:27:17.462  6877  6877 W art     : b60c2000-b60c3000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
,08-23 13:27:17.462  6877  6877 W art     : b60c3000-b60c4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b60c4000-b6110000 r-xp 00000000 b3:17 994        
08-23 13:27:17.462  6877  6877 W art     : /system/lib/libharfbuzz_ng.so
08-23 13:27:17.462  6877  6877 W art     : b6110000-b6111000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6111000-b6112000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:27:17.462  6877  6877 W art     : b6112000-b6113000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 13:27:17.462  6877  6877 W art     : b6113000-b6114000 r--p 00000000 00:00 0          [anon:li
08-23 13:27:17.462  6877  6877 W art     : nker_alloc]
,08-23 13:27:17.462  6877  6877 W art     : b6114000-b6118000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:27:17.462  6877  6877 W art     : b6118000-b6119000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6119000-b611a000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 13:27:17.462  6877  6877 W art     : b611a000-b611b000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-23 13:27:17.462  6877  6877 W art     : sbhost.so
08-23 13:27:17.462  6877  6877 W art     : b611b000-b6153000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:27:17.462  6877  6877 W art     : b6153000-b6154000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
,08-23 13:27:17.462  6877  6877 W art     : b6154000-b6155000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 13:27:17.462  6877  6877 W art     : b6155000-b6156000 r--p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     :          [anon:linker_alloc]
08-23 13:27:17.462  6877  6877 W art     : b6156000-b61f4000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 13:27:17.462  6877  6877 W art     : b61f4000-b61f5000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b61f5000-b6213000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 13:27:17.462  6877  6877 W art     : b6213000-b6214000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
,08-23 13:27:17.462  6877  6877 W art     : .so
08-23 13:27:17.462  6877  6877 W art     : b6214000-b6387000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:27:17.462  6877  6877 W art     : b6387000-b6392000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:27:17.462  6877  6877 W art     : b6392000-b6393000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 13:27:17.462  6877  6877 W art     : b6393000-b64aa000 r-xp 00000000
08-23 13:27:17.462  6877  6877 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-23 13:27:17.462  6877  6877 W art     : b64aa000-b64b5000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 13:27:17.462  6877  6877 W art     : b64b5000-b64b6000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
,08-23 13:27:17.462  6877  6877 W art     : b64b6000-b64ba000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b64ba000-b64de000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
08-23 13:27:17.462  6877  6877 W art     : o
08-23 13:27:17.462  6877  6877 W art     : b64de000-b64e0000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 13:27:17.462  6877  6877 W art     : b64e0000-b64e1000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 13:27:17.462  6877  6877 W art     : b64e1000-b6587000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
,08-23 13:27:17.462  6877  6877 W art     : b6587000-b6594000 r--p 000a5000 b3:17 13
08-23 13:27:17.462  6877  6877 W art     : 2        /system/lib/libcrypto.so
08-23 13:27:17.462  6877  6877 W art     : b6594000-b6595000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 13:27:17.462  6877  6877 W art     : b6595000-b6596000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6596000-b65e9000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:27:17.462  6877  6877 W art     : b65e9000-b65ea000 ---p 00000000 00:00 0 
,08-23 13:27:17.462  6877  6877 W art     : b65ea000-b65eb000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:27:17.462  6877  6877 W art     : b65eb000-b65ec000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 13:27:17.462  6877  6877 W art     : b65ec000-b65f1000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b65f1000-b6603000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 13:27:17.462  6877  6877 W art     : b6603000-b6604000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6604000-b6605000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
,08-23 13:27:17.462  6877  6877 W art     : b6605000-b6606000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 13:27:17.462  6877  6877 W art     : b6606000-b660d000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:27:17.462  6877  6877 W art     : b660d000-b660e000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:27:17.462  6877  6877 W art     : b660e000-b660f000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 13:27:17.462  6877  6877 W art     : b660f000-b6610000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6610000-b6613000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
,08-23 13:27:17.462  6877  6877 W art     : b6613000-b6614000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 13:27:17.462  6877  6877 W art     : b6614000-b6615000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 13:27:17.462  6877  6877 W art     : b6615000-b6619000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 13:27:17.462  6877  6877 W art     : b6619000-b661a000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 13:27:17.462  6877  6877 W art     : b661a000-b661b000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 13:27:17.462  6877  6877 W art     : b661b000-b6629000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
,08-23 13:27:17.462  6877  6877 W art     : b6629000-b662a000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b662a000-b662b000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:27:17.462  6877  6877 W art     : b662b000-b662c000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 13:27:17.462  6877  6877 W art     : b662c000-b6635000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:27:17.462  6877  6877 W art     : b6635000-b6636000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:27:17.462  6877  6877 W art     : b6636000-b6637000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 13:27:17.462  6877  6877 W art     : b6637000-b669d000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
,08-23 13:27:17.462  6877  6877 W art     : b669d000-b669e000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b669e000-b66a0000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 13:27:17.462  6877  6877 W art     : b66a0000-b66a9000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 13:27:17.462  6877  6877 W art     : b66a9000-b66ac000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b66ac000-b6743000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 13:27:17.462  6877  6877 W art     : b6743000-b6745000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
,08-23 13:27:17.462  6877  6877 W art     : b6745000-b6746000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 13:27:17.462  6877  6877 W art     : b6746000-b6747000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6747000-b6a68000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 13:27:17.462  6877  6877 W art     : b6a68000-b6a69000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6a69000-b6a84000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 13:27:17.462  6877  6877 W art     : b6a84000-b6a88000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
,08-23 13:27:17.462  6877  6877 W art     : b6a88000-b6a8d000 rw-p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6a8d000-b6a95000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:27:17.462  6877  6877 W art     : b6a95000-b6a96000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:27:17.462  6877  6877 W art     : b6a96000-b6a97000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 13:27:17.462  6877  6877 W art     : b6a97000-b6ac5000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:27:17.462  6877  6877 W art     : b6ac5000-b6ac6000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6ac6000-b6acd000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:27:17.462  6877  6877 W art     : b6acd000-b6ace000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 13:27:17.462  6877  6877 W art     : b6ace000-b6b14000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:27:17.462  6877  6877 W art     : b6b14000-b6b15000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6b15000-b6b18000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:27:17.462  6877  6877 W art     : b6b18000-b6b19000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 13:27:17.462  6877  6877 W art     : b6b19000-b6b34000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 13:27:17.462  6877  6877 W art     : b6b34000-b6b38000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 13:27:17.462  6877  6877 W art     : b6b38000-b6b39000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 13:27:17.462  6877  6877 W art     : b6b39000-b6b86000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 13:27:17.462  6877  6877 W art     : b6b86000-b6b87000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6b87000-b6b93000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 13:27:17.462  6877  6877 W art     : b6b93000-b6b94000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 13:27:17.462  6877  6877 W art     : b6b94000-b6ba1000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 13:27:17.462  6877  6877 W art     : b6ba1000-b6ba2000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6ba2000-b6ba3000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 13:27:17.462  6877  6877 W art     : b6ba3000-b6ba4000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 13:27:17.462  6877  6877 W art     : b6ba4000-b6bac000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:27:17.462  6877  6877 W art     : b6bac000-b6bad000 ---p 00000000 00:00 0 
08-23 13:27:17.462  6877  6877 W art     : b6bad000-b6bae000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:27:17.462  6877  6877 W art     : b6bae000-b6baf000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 13:27:17.462  6877  6877 W art     : b6baf000-b6bb6000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:27:17.462  6877  6877 W art     : b6bb6000-b6bb7000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:27:17.462  6877  6877 W art     : b6bb7000-b6bb8000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 13:27:17.462  6877  6877 W art     : b6bb8000-b6bcc000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 13:27:17.462  6877  6877 W art     : b6bcc000-b6bce000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 13:27:17.462  6877  6877 W art     : b6bce000-b6bcf000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 13:27:17.472  6877  6877 W art     : b6bcf000-b6bf7000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:27:17.472  6877  6877 W art     : b6bf7000-b6bf9000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:27:17.472  6877  6877 W art     : b6bf9000-b6bfa000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 13:27:17.472  6877  6877 W art     : b6bfa000-b6bfd000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:27:17.472  6877  6877 W art     : b6bfd000-b6bfe000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:27:17.472  6877  6877 W art     : b6bfe000-b6bff000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 13:27:17.472  6877  6877 W art     : b6bff000-b6c08000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:27:17.472  6877  6877 W art     : b6c08000-b6c09000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:27:17.472  6877  6877 W art     : b6c09000-b6c0a000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 13:27:17.472  6877  6877 W art     : b6c0a000-b6c2a000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 13:27:17.472  6877  6877 W art     : b6c2a000-b6c2b000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 13:27:17.472  6877  6877 W art     : b6c2b000-b6c2c000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 13:27:17.472  6877  6877 W art     : b6c2c000-b6c9f000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 13:27:17.472  6877  6877 W art     : b6c9f000-b6ca3000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 13:27:17.472  6877  6877 W art     : b6ca3000-b6ca6000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 13:27:17.472  6877  6877 W art     : b6ca6000-b6cb0000 rw-p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6cb0000-b6d38000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 13:27:17.472  6877  6877 W art     : b6d38000-b6d39000 ---p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6d39000-b6d3d000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 13:27:17.472  6877  6877 W art     : b6d3d000-b6d3e000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 13:27:17.472  6877  6877 W art     : b6d3e000-b6d3f000 rw-p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6d3f000-b6d68000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:27:17.472  6877  6877 W art     : b6d68000-b6d69000 ---p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6d69000-b6d6c000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:27:17.472  6877  6877 W art     : b6d6c000-b6d6d000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 13:27:17.472  6877  6877 W art     : b6d6d000-b6e47000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:27:17.472  6877  6877 W art     : b6e47000-b6e4e000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:27:17.472  6877  6877 W art     : b6e4e000-b6e56000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 13:27:17.472  6877  6877 W art     : b6e56000-b6e57000 rw-p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6e57000-b6e58000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:17.472  6877  6877 W art     : b6e58000-b6e59000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 13:27:17.472  6877  6877 W art     : b6e59000-b6e5a000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.472  6877  6877 W art     : b6e5a000-b6e5d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.472  6877  6877 W art     : b6e5d000-b6e82000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 13:27:17.472  6877  6877 W art     : b6e82000-b6e83000 ---p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6e83000-b6e8a000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 13:27:17.472  6877  6877 W art     : b6e8a000-b6e8b000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 13:27:17.472  6877  6877 W art     : b6e8b000-b6e92000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 13:27:17.472  6877  6877 W art     : b6e92000-b6e93000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 13:27:17.472  6877  6877 W art     : b6e93000-b6e94000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 13:27:17.472  6877  6877 W art     : b6e94000-b6e95000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.472  6877  6877 W art     : b6e95000-b6ead000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 13:27:17.472  6877  6877 W art     : b6ead000-b6eae000 ---p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6eae000-b6eaf000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 13:27:17.472  6877  6877 W art     : b6eaf000-b6eb0000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 13:27:17.472  6877  6877 W art     : b6eb0000-b6ebe000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 13:27:17.472  6877  6877 W art     : b6ebe000-b6ebf000 ---p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6ebf000-b6ec0000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 13:27:17.472  6877  6877 W art     : b6ec0000-b6ec1000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 13:27:17.472  6877  6877 W art     : b6ec1000-b6ec2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:17.472  6877  6877 W art     : b6ec2000-b6ec4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.472  6877  6877 W art     : b6ec4000-b6ec5000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.472  6877  6877 W art     : b6ec5000-b6ec6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 13:27:17.472  6877  6877 W art     : b6ec6000-b6ec7000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 13:27:17.472  6877  6877 W art     : b6ec7000-b6ec8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 13:27:17.472  6877  6877 W art     : b6ec8000-b6ee8000 r--s 00000000 00:0b 6700       /dev/__properties__
08-23 13:27:17.472  6877  6877 W art     : b6ee8000-b6ee9000 r--p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6ee9000-b6eea000 ---p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6eea000-b6eec000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 13:27:17.472  6877  6877 W art     : b6eec000-b6eed000 r-xp 00000000 00:00 0          [sigpage]
08-23 13:27:17.472  6877  6877 W art     : b6eed000-b6f08000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 13:27:17.472  6877  6877 W art     : b6f08000-b6f09000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 13:27:17.472  6877  6877 W art     : b6f09000-b6f0b000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 13:27:17.472  6877  6877 W art     : b6f0b000-b6f0d000 rw-p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : b6f0d000-b6f12000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 13:27:17.472  6877  6877 W art     : b6f12000-b6f13000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 13:27:17.472  6877  6877 W art     : b6f13000-b6f14000 rw-p 00000000 00:00 0 
08-23 13:27:17.472  6877  6877 W art     : bef97000-befb8000 rw-p 00000000 00:00 0          [stack]
08-23 13:27:17.472  6877  6877 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-23 13:27:17.532  5949  5973 I PlayCommon: [829] com.google.android.play.a.al.a(945): Successfully uploaded logs.
08-23 13:27:17.532  6877  6877 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 13:27:17.532  5949  5973 I PlayCommon: [829] com.google.android.play.a.al.e(730): Preparing logs for uploading
08-23 13:27:17.532  5949  5973 I PlayCommon: [829] com.google.android.play.a.al.e(732): No file ready to send
,08-23 13:27:17.592  6877  6877 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 13:27:17.602  6877  6877 E AffinityControl: AffinityControl: registerfunction enter
,08-23 13:27:17.622  6877  6877 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:27:17.632   763  2472 D PackageManager: START PACKAGE DELETE: observer{186129432}
08-23 13:27:17.632   763  2472 D PackageManager: pkg{<packageName>}
08-23 13:27:17.632   763  2472 D PackageManager: user{0}
08-23 13:27:17.632   763  2472 D PackageManager: caller{2000}
08-23 13:27:17.632   763  2472 D PackageManager: flags{2}
08-23 13:27:17.632   763  2472 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 13:27:17.632   763  2472 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 13:27:17.632   763  2472 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 13:27:17.632   763  2472 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 13:27:17.632   763  2472 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 13:27:17.632   763   944 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 13:27:17.632   763   944 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 13:27:17.632   763   944 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 13:27:17.632   763   944 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 13:27:17.632   763   944 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 13:27:17.632   763   944 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-23 13:27:17.632   763   944 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-23 13:27:17.632   763   944 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-23 13:27:17.632   763   944 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-23 13:27:17.632   763   862 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-23 13:27:17.632   763   944 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-23 13:27:17.632   763   862 I ActivityManager: Killing 6635:com.test.thalitest/u0a4 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-23 13:27:17.642   763   862 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 13:27:17.642   763   862 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-23 13:27:17.662   763   944 D AASAinstall: there is not AASApackages.xml file
,08-23 13:27:17.672   763  2526 D GraphicsStats: Buffer count: 4
,08-23 13:27:17.672   763   779 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@4637671)
,08-23 13:27:17.672   763  1330 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:27:17.672   763  1330 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:27:17.672   763  1330 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 13:27:17.952   763   944 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-23 13:27:18.052   763   944 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-23 13:27:18.062   329   329 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-23 13:27:18.062   763   944 I art     : Starting a blocking GC Explicit
,08-23 13:27:18.082  4645  5257 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-23 13:27:18.092  4645  5257 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-23 13:27:18.172   763   944 I art     : Explicit concurrent mark sweep GC freed 105071(5MB) AllocSpace objects, 7(140KB) LOS objects, 27% free, 42MB/58MB, paused 1.445ms total 111.851ms
,08-23 13:27:18.202   763   944 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 13:27:18.202   763   944 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-23 13:27:18.202   763   944 D AASAinstall: there is not AASApackages.xml file
,08-23 13:27:18.202   763   944 D PackageManager: result of delete: 1{186129432}
,08-23 13:27:18.202  6877  6877 I art     : System.exit called, status: 0
08-23 13:27:18.202  6877  6877 I AndroidRuntime: VM exiting with result code 0.
,08-23 13:27:18.212   763   944 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 13:27:18.212   763   944 D PackageManager: userId{-1}
08-23 13:27:18.212   763   944 D PackageManager: andCode{true}
,08-23 13:27:18.222   763   944 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-23 13:27:18.232  6210  6619 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-23 13:27:18.242  6210  6619 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-23 13:27:18.242  6210  6619 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-23 13:27:18.312   763   851 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
,08-23 13:27:18.312   763   851 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-23 13:27:18.322   763   763 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.322  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-23 13:27:18.322  1382  1382 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-23 13:27:18.322   763   763 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.322   763   906 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.322   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.332   763   906 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.342   763  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 13:27:18.342   763   862 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{abe97e2 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{700d882 3385:com.samsung.klmsagent/u0a18}
,08-23 13:27:18.342  2149  2149 E SamsungIME: mOCRHelper is null
,08-23 13:27:18.342   763  1365 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/168_task.xml
,08-23 13:27:18.342  2060  2370 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.352   763   763 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.362   763   763 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.362   763   763 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.362   763  1320 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-23 13:27:18.362   763  1320 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 13:27:18.362   763  1320 V NetworkStats: performPollLocked(flags=0x3)
,08-23 13:27:18.362   763  1321 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-23 13:27:18.362   763  1321 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-23 13:27:18.362  3385  3385 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Aug 23 13:27:18 GMT+02:00 2016
,08-23 13:27:18.372   763   763 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.372  1702  1702 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 13:27:18.372   763   763 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.372   763   763 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.372   763   763 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.382   763  1320 V NetworkStats: performPollLocked() took 15ms
,08-23 13:27:18.382  3299  3317 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 13:27:18.382  3385  3385 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-23 13:27:18.382   763   763 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.382   763   763 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.382   763   763 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.382   763   763 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.382   763   763 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.382   763   763 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.382  3299  3317 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 13:27:18.382   763  2147 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{abe97e2 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{42fa74b 763:system/1000}
,08-23 13:27:18.392  3299  3317 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 13:27:18.392   763   763 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.392  3299  3317 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-23 13:27:18.392  1691  6964 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-23 13:27:18.392  1691  6964 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-23 13:27:18.392   763  2472 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
08-23 13:27:18.392  1691  6964 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
,08-23 13:27:18.392  1691  6964 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-23 13:27:18.392  1691  6964 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 13:27:18.392   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.392  3385  3385 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-23 13:27:18.392  3385  3385 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 13:27:18.392  3385  3385 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 13:27:18.392  3385  6966 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-23 13:27:18.392  3385  6966 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
08-23 13:27:18.392  3385  6966 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-23 13:27:18.392  3385  6966 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
,08-23 13:27:18.402  3385  6966 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-23 13:27:18.402  3385  6966 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-23 13:27:18.402  3385  6966 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 13:27:18.402  3385  6966 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 13:27:18.402   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.402   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763  1297 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.412   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.422  3385  6966 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x727febe6 in tid 6966 (IntentService[K)
,08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
08-23 13:27:18.422  2424  2424 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.422   763   763 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.432   763   763 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.432   763   763 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.432   763   851 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x99ab778c in tid 851 (android.bg)
,08-23 13:27:18.432  2424  2424 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:27:18.442   763   763 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.442   763   763 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-23 13:27:18.442   763   851 F libc    : Unable to open connection to debuggerd: Connection refused
,08-23 13:27:18.442  2424  2424 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:27:18.482   350   350 I Zygote  : Process 3385 exited due to signal (7)
,08-23 13:27:18.522   326   326 E installd: eof
08-23 13:27:18.522   326   326 E installd: failed to read size
08-23 13:27:18.522   326   326 I installd: closing connection
,08-23 13:27:18.522  2060  2514 W Sensors : sensorservice died [0xb4751780]
,08-23 13:27:18.522  2479  2493 W Sensors : sensorservice died [0xb3a72bc0]
,08-23 13:27:18.522  1382  2382 W Sensors : sensorservice died [0xad703c00]
,08-23 13:27:18.522  1702  1702 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
,08-23 13:27:18.522   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6b24000
08-23 13:27:18.522   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-23 13:27:18.522  2060  2369 E WifiManager: Channel connection lost
,08-23 13:27:18.532   293  2041 I SurfaceFlinger: restart the boot-animation @ binderDied
,08-23 13:27:18.532  1691  1691 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7168ab05 in tid 1691 (com.android.nfc)
,08-23 13:27:18.532  1691  1691 F libc    : Unable to open connection to debuggerd: Connection refused
,08-23 13:27:18.532  2424  2424 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:27:18.532  1382  1569 E WifiManager: Channel connection lost
,08-23 13:27:18.532  2418  2418 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ec77894 in tid 2418 (droid.bluetooth)
,08-23 13:27:18.542   292   292 I ServiceManager: service 'sec_analytics' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'telecom' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'application_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'wifi_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'remoteinjection' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'edm_proxy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'mum_container_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'otp_service' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'enterprise_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'statusbar' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'clipboard' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'clipboardEx' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'network_management' died
08-23 13:27:18.542  1717  2122 W Sensors : sensorservice died [0xad703240]
08-23 13:27:18.542   292   292 I ServiceManager: service 'jobscheduler' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'backup' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'textservices' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'network_score' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'netstats' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'netpolicy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'wifip2p' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'wifi' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'wifihs20' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'wifiscanner' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'rttmanager' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'ethernet' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'connectivity' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'sb_service' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'servicediscovery' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'updatelock' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'notification' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'location' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'country_detector' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'sec_location' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'search' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'execute' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'dropbox' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'wallpaper' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'audio' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'DockObserver' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'midi' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'usb' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'serial' died
08-23 13:27:18.542   2,92   292 I ServiceManager: service 'kiesusb' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'appwidget' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'voiceinteraction' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'diskstats' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'mDNIe' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'AAS' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'MSCS' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'spengestureservice' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'quickconnect' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'samplingprofiler' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'commontime_management' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'dreams' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'graphicsstats' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'print' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'restrictions' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'media_session' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'media_router' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'trust' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'fingerprint' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'launcherapps' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'voip' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'media_projection' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'lpnet' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'user' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'procstats' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'meminfo' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'gfxinfo' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'dbinfo' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'cpuinfo' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'permission' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'imms' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'processinfo' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'sensorservice' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'battery' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'usagestats' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'webviewupdate' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'scheduling_policy' died
08-23 13:27:18.542  2424  2424 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:27:18.542   292   292 I ServiceManager: service 'telephony.registry' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'persona' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'SEAMService' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'media.camera.proxy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'account' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'content' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'DirEncryptService' died
,08-23 13:27:18.542   292   292 I ServiceManager: service 'LSManager' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'ReactiveService' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'EngineeringModeService' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'SatsService' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'sedenial' died
,08-23 13:27:18.542   292   292 I ServiceManager: service 'vibrator' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'tw_toolbox' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'tima' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'iccc' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'cepproxyks' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'emailksproxy' died
,08-23 13:27:18.542   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'consumer_ir' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'alarm' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'persona_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'package' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'context_aware' died
,08-23 13:27:18.542   292   292 I ServiceManager: service 'scontext' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'barbeam' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'multiwindow_facade' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'window' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'input' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'bluetooth_manager' died
,08-23 13:27:18.542   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'rcp' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'input_method' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'accessibility' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'cover' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'mount' died
,08-23 13:27:18.542   292   292 I ServiceManager: service 'uimode' died
,08-23 13:27:18.542   292   292 I ServiceManager: service 'lock_settings' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'deviceidle' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'device_policy' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'harmony_eas_service' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'sdp' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'sdp_log' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'dlp' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'log_manager_service' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'edmnativehelper' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'activity' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'batterystats' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'appops' died
08-23 13:27:18.542   292   292 I ServiceManager: service 'power' died
,08-23 13:27:18.542   292   292 I ServiceManager: service 'display' died
08-23 13:27:18.542  1999  2010 W Sensors : sensorservice died [0xb3a72d00]
08-23 13:27:18.542  1702  2209 E WifiManager: Channel connection lost
08-23 13:27:18.542   320   940 W AudioFlinger: power manager service died !!!
08-23 13:27:18.542   320   940 W AudioFlinger: power manager service died !!!
08-23 13:27:18.542  1828  1944 E WifiManager: Channel connection lost
,08-23 13:27:18.542  2418  2418 F libc    : Unable to open connection to debuggerd: Connection refused
08-23 13:27:18.542   293   424 I SurfaceFlinger: id=2 Removed GocusedStac (5/9)
,08-23 13:27:18.562  6271  6329 E WifiManager: Channel connection lost
,08-23 13:27:18.562   293   424 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
08-23 13:27:18.562   293   424 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-23 13:27:18.562   293   424 I SurfaceFlinger: id=15 Removed EimLayer(An (0/6)
08-23 13:27:18.562   293   424 I SurfaceFlinger: id=14 Removed EimLayer(Di (2/5)
08-23 13:27:18.562   293   424 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-23 13:27:18.562   293   424 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-23 13:27:18.562   293   424 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-23 13:27:18.562   293   424 I SurfaceFlinger: id=23 Removed Mauncher (1/4)
08-23 13:27:18.562   293   424 I SurfaceFlinger: id=25 Removed YUIInstallC (1/3)
08-23 13:27:18.562   293  1295 I SurfaceFlinger: id=5 Removed TtatusBar (1/2)
08-23 13:27:18.562   293  1295 I SurfaceFlinger: id=5 Removed TtatusBar (-2/2)
08-23 13:27:18.562   293  1295 I SurfaceFlinger: id=7 Removed JmageWallpa (0/1)
08-23 13:27:18.562   293  1295 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/1)
08-23 13:27:18.562   293  6971 I SurfaceFlinger: id=20 Removed DolorFade (0/0)
08-23 13:27:18.562   293  6971 I SurfaceFlinger: id=23 Removed Mauncher (-2/0)
08-23 13:27:18.562   293  6971 I SurfaceFlinger: id=20 Removed DolorFade (-2/0)
08-23 13:27:18.562   293  6971 I SurfaceFlinger: id=25 Removed YUIInstallC (-2/0)
08-23 13:27:18.562   293  6971 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/0)
08-23 13:27:18.562   293  6971 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/0)
,08-23 13:27:18.562   293   420 D libEGL  : eglTerminate EGLDisplay = 0xb6a016fc
,08-23 13:27:18.562   293   420 D libEGL  : eglTerminate EGLDisplay = 0xb6a016fc
,08-23 13:27:18.572  2467  2467 D BluetoothA2dp: Proxy object disconnected
,08-23 13:27:18.572   292   292 I ServiceManager: service 'nfc' died
08-23 13:27:18.572   292   292 I ServiceManager: service 'nfccontroller' died
08-23 13:27:18.572   292   292 I ServiceManager: service 'secontroller' died
,08-23 13:27:18.582  5200  5200 D BluetoothA2dp: Proxy object disconnected
,08-23 13:27:18.582  5200  5200 D A2dpProfile: Bluetooth service disconnected
,08-23 13:27:18.582  5200  5200 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 13:27:18.582  5200  5200 D PanProfile: Bluetooth service disconnected
08-23 13:27:18.582  5200  5200 D BluetoothPbap: Proxy object disconnected
,08-23 13:27:18.582  5200  5200 D PbapServerProfile: Bluetooth service disconnected
08-23 13:27:18.582  5200  5200 D BluetoothSap: Proxy object disconnected
08-23 13:27:18.582  5200  5200 D SapProfile: Bluetooth service disconnected
,08-23 13:27:18.582  5200  5200 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b898e7c in tid 5200 (ndroid.settings)
,08-23 13:27:18.582  5200  5200 F libc    : Unable to open connection to debuggerd: Connection refused
,08-23 13:27:18.582  2424  2424 E audit_log: File locking failed. error= Bad file descriptor
,08-23 13:27:18.602   350   350 I Zygote  : Process 1691 exited due to signal (7)
,08-23 13:27:18.612   350   350 I Zygote  : Process 2418 exited due to signal (7)
,08-23 13:27:18.612   350   350 I Zygote  : Process 5200 exited due to signal (7)
,08-23 13:27:18.662   291   291 I lowmemorykiller: ActivityManager disconnected
08-23 13:27:18.662   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-23 13:27:18.782   293   543 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-23 13:27:18.782   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-23 13:27:19.032   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-23 13:27:19.032   293   543 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-23 13:27:19.032   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbec693a4
,08-23 13:27:19.042   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbec6938c
,08-23 13:27:19.042   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbec6938c
,08-23 13:27:19.042   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbec6938c
,08-23 13:27:19.042   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbec6938c
,08-23 13:27:19.042   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbec6938c
,08-23 13:27:19.042   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbec693a4

```
