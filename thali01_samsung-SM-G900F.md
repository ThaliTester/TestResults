#### Test 85019474526c333_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
09-13 12:25:37.463   774  3409 D SSRM:n  : SIOP:: AP = 480, PST = 453, CUR = 300, LCD = 0
,--------- beginning of main
09-13 12:25:37.863  5321  5321 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
09-13 12:25:37.863  5321  5321 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
09-13 12:25:37.863  5321  5321 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
09-13 12:25:37.873  5321  5321 I art     : System.exit called, status: 0
09-13 12:25:37.873  5321  5321 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 12:25:37.903   774  1726 I ActivityManager: Process com.samsung.aasaservice (pid 5321)(adj 0) has died(148,720)
09-13 12:25:37.913   774  1726 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
09-13 12:25:37.913   774  1726 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
09-13 12:25:37.913   774  1726 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
09-13 12:25:37.933  6248  6248 E Zygote  : v2
09-13 12:25:37.933  6248  6248 I libpersona: KNOX_SDCARD checking this for 10014
09-13 12:25:37.933  6248  6248 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:37.933  6248  6248 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:37.933  6248  6248 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:37.933   774   849 I ActivityManager: Start proc 6248:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
09-13 12:25:37.933  6248  6248 E Zygote  : accessInfo : 0
09-13 12:25:37.933   774  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 12:25:37.933  5293  5293 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
09-13 12:25:37.933  6248  6248 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
09-13 12:25:37.963  6248  6248 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:37.963  6248  6248 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:37.963   774  2422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3f49482 6248:com.google.android.partnersetup/u0a14}
09-13 12:25:37.973   774  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
09-13 12:25:37.973  6248  6248 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
09-13 12:25:37.983  6248  6248 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
09-13 12:25:38.013   774  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3f49482 6248:com.google.android.partnersetup/u0a14}
09-13 12:25:38.033  6267  6267 E Zygote  : v2
09-13 12:25:38.033  6267  6267 I libpersona: KNOX_SDCARD checking this for 10015
09-13 12:25:38.033  6267  6267 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:38.033  6267  6267 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:38.033  6267  6267 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:38.033  6267  6267 E Zygote  : accessInfo : 0
09-13 12:25:38.033  6267  6267 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
09-13 12:25:38.033   774  2422 I ActivityManager: Start proc 6267:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
09-13 12:25:38.053  6267  6267 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:38.053  6267  6267 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:38.063   774  2439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{37a9fc9 6267:com.samsung.groupcast/u0a15}
09-13 12:25:38.063  6267  6267 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
09-13 12:25:38.073   774  1415 I ActivityManager: Killing 5265:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #37
09-13 12:25:38.093   774  1501 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
09-13 12:25:38.093  6267  6267 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
09-13 12:25:38.113  6267  6267 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
09-13 12:25:38.113  6267  6267 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
09-13 12:25:38.113  6267  6267 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-13 12:25:38.113  6267  6267 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
09-13 12:25:38.113  6267  6267 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
09-13 12:25:38.113  6267  6267 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
09-13 12:25:38.113  6267  6267 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
09-13 12:25:38.113  6267  6267 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
09-13 12:25:38.113  6267  6267 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
09-13 12:25:38.113  6267  6267 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:25:38.113  6267  6267 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-13 12:25:38.113  6267  6267 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
09-13 12:25:38.113  6267  6267 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:25:38.113  6267  6267 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-13 12:25:38.113  6267  6267 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-13 12:25:38.123   774  1320 I ActivityManager: Killing 5408:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
09-13 12:25:38.123   774  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bffcba0 1882:com.sec.android.app.shealth:remote/u0a34}
09-13 12:25:38.133   774  1415 I ActivityManager: Start proc 6281:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
09-13 12:25:38.133  6281  6281 E Zygote  : v2
09-13 12:25:38.133  6281  6281 I libpersona: KNOX_SDCARD checking this for 10041
09-13 12:25:38.133  6281  6281 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:38.133  6281  6281 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:38.133  6281  6281 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:38.143  6281  6281 E Zygote  : accessInfo : 0
09-13 12:25:38.143  6281  6281 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
09-13 12:25:38.153   774  1726 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
09-13 12:25:38.173  6281  6281 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:38.173  6281  6281 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:38.183   774  1501 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{65b76ce 6281:com.samsung.android.sdk.samsunglink/u0a41}
09-13 12:25:38.183  6281  6281 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
09-13 12:25:38.263  6281  6281 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
09-13 12:25:38.273  6281  6281 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
09-13 12:25:38.323  6281  6281 I SL_DEBUG: isLoggable:: isProductShip = 1
09-13 12:25:38.323  6281  6281 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
09-13 12:25:38.333   774  1501 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
09-13 12:25:38.343   774   787 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
09-13 12:25:38.343   774  1646 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
09-13 12:25:38.343  2320  2320 E audit   : type=1400 msg=audit(1473762338.343:284): avc:  denied  { execmod } for  pid=6241 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 12:25:38.343   774  2422 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
09-13 12:25:38.343  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:38.343  2320  2320 E audit   : type=1300 msg=audit(1473762338.343:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fbb000 a1=51000 a2=5 a3=4 items=0 ppid=3545 ppcomm=adbd pid=6241 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 12:25:38.343  2320  2320 E audit   : type=1327 msg=audit(1473762338.343:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
09-13 12:25:38.343  2320  2320 E audit   : type=1320 msg=audit(1473762338.343:284): 
09-13 12:25:38.343   774  3741 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
09-13 12:25:38.353   774  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
09-13 12:25:38.353   774   788 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
09-13 12:25:38.353   774  1415 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
09-13 12:25:38.353   774  1742 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
09-13 12:25:38.363   774  2439 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
09-13 12:25:38.403  2320  2320 E audit   : type=1400 msg=audit(1473762338.403:285): avc:  denied  { execmod } for  pid=6241 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 12:25:38.403  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:38.403  2320  2320 E audit   : type=1300 msg=audit(1473762338.403:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7b000 a1=51000 a2=5 a3=4 items=0 ppid=3545 ppcomm=adbd pid=6241 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 12:25:38.403  2320  2320 E audit   : type=1327 msg=audit(1473762338.403:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
09-13 12:25:38.403  2320  2320 E audit   : type=1320 msg=audit(1473762338.403:285): 
09-13 12:25:38.443  2320  2320 E audit   : type=1400 msg=audit(1473762338.443:286): avc:  denied  { execmod } for  pid=6241 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 12:25:38.443  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:38.443  2320  2320 E audit   : type=1300 msg=audit(1473762338.443:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7b000 a1=51000 a2=5 a3=4 items=0 ppid=3545 ppcomm=adbd pid=6241 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 12:25:38.443  2320  2320 E audit   : type=1327 msg=audit(1473762338.443:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
09-13 12:25:38.443  2320  2320 E audit   : type=1320 msg=audit(1473762338.443:286): 
09-13 12:25:38.443  6241  6241 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 12:25:38.453  6241  6241 D AndroidRuntime: CheckJNI is OFF
09-13 12:25:38.453  6241  6241 D AndroidRuntime: readGMSProperty: start
09-13 12:25:38.453  6241  6241 D AndroidRuntime: readGMSProperty: already setted!!
09-13 12:25:38.453  6241  6241 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 12:25:38.453  6241  6241 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 12:25:38.453  6241  6241 D AndroidRuntime: readGMSProperty: end
09-13 12:25:38.453  6241  6241 D AndroidRuntime: addProductProperty: start
09-13 12:25:38.453  6241  6241 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
09-13 12:25:38.453  6241  6241 W art     : aede2000-b1d08000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
09-13 12:25:38.453  6241  6241 W art     : b1d08000-b3f77000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
09-13 12:25:38.453  6241  6241 W art     : b3f77000-b3f78000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
09-13 12:25:38.453  6241  6241 W art     : b3f78000-b3f79000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.453  6241  6241 W art     : b42bb000-b42e4000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
09-13 12:25:38.453  6241  6241 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 946        /system/lib/libart.so
09-13 12:25:38.453  6241  6241 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b4733000-b473d000 r--p 0044e000 b3:17 946        /system/lib/libart.so
09-13 12:25:38.453  6241  6241 W art     : b473d000-b473e000 rw-p 00458000 b3:17 946        /system/lib/libart.so
09-13 12:25:38.453  6241  6241 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
09-13 12:25:38.453  6241  6241 W art     : b484b000-b484e000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
09-13 12:25:38.453  6241  6241 W art     : b484e000-b484f000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
09-13 12:25:38.453  6241  6241 W art     : b484f000-b4850000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
09-13 12:25:38.453  6241  6241 W art     : b4850000-b4851000 r--p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b4851000-b4871000 r--s 00000000 00:0b 7201       /dev/__properties__
09-13 12:25:38.453  6241  6241 W art     : b4871000-b5282000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
09-13 12:25:38.453  6241  6241 W art     : b5282000-b5283000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b5283000-b52cc000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
09-13 12:25:38.453  6241  6241 W art     : b52cc000-b52cd000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
09-13 12:25:38.453  6241  6241 W art     : b52cd000-b52d5000 rw-p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b52d5000-b530a000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
09-13 12:25:38.453  6241  6241 W art     : b530a000-b530b000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b530b000-b530c000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
09-13 12:25:38.453  6241  6241 W art     : b530c000-b530d000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
09-13 12:25:38.453  6241  6241 W art     : b530d000-b5365000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
09-13 12:25:38.453  6241  6241 W art     : b5365000-b5366000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b5366000-b5367000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
09-13 12:25:38.453  6241  6241 W art     : b5367000-b5368000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
09-13 12:25:38.453  6241  6241 W art     : b5369000-b536f000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungV
09-13 12:25:38.453  6241  6241 W art     : AD_v01009.so
09-13 12:25:38.453  6241  6241 W art     : b536f000-b5370000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 12:25:38.453  6241  6241 W art     : b5370000-b5371000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 12:25:38.453  6241  6241 W art     : b5371000-b5373000 rw-p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b5374000-b537e000 r-xp 00000000 b3:17 1088 
09-13 12:25:38.453  6241  6241 W art     :       /system/lib/libcommon_time_client.so
09-13 12:25:38.453  6241  6241 W art     : b537e000-b5381000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
09-13 12:25:38.453  6241  6241 W art     : b5381000-b5382000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
09-13 12:25:38.453  6241  6241 W art     : b5383000-b539a000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 12:25:38.453  6241  6241 W art     : b539a000-b539b000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b539b000-b539c000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 12:25:38.453  6241  6241 W art     : b539c000-b539d000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 12:25:38.453  6241  6241 W art     : b539e000-b53a8000 r-xp 00000000 b3:17 2671   
09-13 12:25:38.453  6241  6241 W art     :     /system/lib/libsec_km.so
09-13 12:25:38.453  6241  6241 W art     : b53a8000-b53a9000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
09-13 12:25:38.453  6241  6241 W art     : b53a9000-b53aa000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
09-13 12:25:38.453  6241  6241 W art     : b53aa000-b53ae000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
09-13 12:25:38.453  6241  6241 W art     : b53ae000-b53af000 r--p 00003000 b
09-13 12:25:38.453  6241  6241 W art     : 3:17 2888       /system/lib/libSEF4MP4.so
09-13 12:25:38.453  6241  6241 W art     : b53af000-b53b0000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
09-13 12:25:38.453  6241  6241 W art     : b53b0000-b53c6000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
09-13 12:25:38.453  6241  6241 W art     : b53c6000-b53c7000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
09-13 12:25:38.453  6241  6241 W art     : b53c7000-b53c8000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
09-13 12:25:38.453  6241  6241 W art     : b53c8000-b53d5000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
09-13 12:25:38.453  6241  6241 W art     : b53d5000-b53d6000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
09-13 12:25:38.453  6241  6241 W art     : b53d6000-b53d7000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
09-13 12:25:38.453  6241  6241 W art     : b53d7000-b5437000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
09-13 12:25:38.453  6241  6241 W art     : b5437000-b543a000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
09-13 12:25:38.453  6241  6241 W art     : b543a000-b543e000 rw-p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b543e000-b549f000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
09-13 12:25:38.453  6241  6241 W art     : b549f000-b54a0000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
09-13 12:25:38.453  6241  6241 W art     : b54a0000-b54ef000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
09-13 12:25:38.453  6241  6241 W art     : b54ef000-b54f1000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
09-13 12:25:38.453  6241  6241 W art     : b54f1000-b54f2000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
09-13 12:25:38.453  6241  6241 W art     : b54f2000-b54f3000 rw-p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b54f3000-b54fa000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
09-13 12:25:38.453  6241  6241 W art     : b54fa000-b54fb000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
09-13 12:25:38.453  6241  6241 W art     : b54fb000-b54fc000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
09-13 12:25:38.453  6241  6241 W art     : avc_common.so
09-13 12:25:38.453  6241  6241 W art     : b54fd000-b5500000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
09-13 12:25:38.453  6241  6241 W art     : b5500000-b5501000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
09-13 12:25:38.453  6241  6241 W art     : b5501000-b5502000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
09-13 12:25:38.453  6241  6241 W art     : enc_common.so
09-13 12:25:38.453  6241  6241 W art     : b5503000-b5507000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
09-13 12:25:38.453  6241  6241 W art     : b5507000-b5508000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b5508000-b5509000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
09-13 12:25:38.453  6241  6241 W art     : b5509000-b550a000 rw-p 00005000 b3:17 2510       /syste
09-13 12:25:38.453  6241  6241 W art     : m/lib/libpowermanager.so
09-13 12:25:38.453  6241  6241 W art     : b550b000-b5528000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 12:25:38.453  6241  6241 W art     : b5528000-b5529000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 12:25:38.453  6241  6241 W art     : b5529000-b552a000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 12:25:38.453  6241  6241 W art     : b552b000-b5530000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 12:25:38.453  6241  6241 W art     : b5530000-b5531000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 12:25:38.453  6241  6241 W art     : b5531000-b5532000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 12:25:38.453  6241  6241 W art     : b5533000-b5564000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 12:25:38.453  6241  6241 W art     : b5564000-b5565000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b5565000-b5568000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 12:25:38.453  6241  6241 W art     : b5568000-b5569000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 12:25:38.453  6241  6241 W art     : b556a000-b55a5000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
09-13 12:25:38.453  6241  6241 W art     : b55a5000-b55a6000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
09-13 12:25:38.453  6241  6241 W art     : b55a6000-b55a7000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
09-13 12:25:38.453  6241  6241 W art     : b55a8000-b55af000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
09-13 12:25:38.453  6241  6241 W art     : b55af000-b55b0000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b55b0000-b55b1000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
09-13 12:25:38.453  6241  6241 W art     : b55b1000-b55b2000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
09-13 12:25:38.453  6241  6241 W art     : b55b2000-b55b3000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.453  6241  6241 W art     : b55b3000-b55ca000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
09-13 12:25:38.453  6241  6241 W art     : b55ca000-b55cb000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b55cb000-b55ce000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
09-13 12:25:38.453  6241  6241 W art     : b55ce000-b55cf000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
09-13 12:25:38.453  6241  6241 W art     : b55cf000-b55ee000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
09-13 12:25:38.453  6241  6241 W art     : b55ee000-b55ef000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
09-13 12:25:38.453  6241  6241 W art     : b55ef000-b55f0000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
09-13 12:25:38.453  6241  6241 W art     : b55f0000-b562e000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
09-13 12:25:38.453  6241  6241 W art     : b562e000-b562f000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b562f000-b5631000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
09-13 12:25:38.453  6241  6241 W art     : b5631000-b5632000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
09-13 12:25:38.453  6241  6241 W art     : b5633000-b563a000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 12:25:38.453  6241  6241 W art     : b563a000-b563b000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 12:25:38.453  6281  6281 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
09-13 12:25:38.453  6241  6241 W art     : b563b000-b563c000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 12:25:38.453  6241  6241 W art     : b563d000-b5640000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 12:25:38.453  6241  6241 W art     : b5640000-b5641000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 12:25:38.453  6241  6241 W art     : b5641000-b5642000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 12:25:38.453  6241  6241 W art     : b5642000-b5648000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 12:25:38.453  6241  6241 W art     : b5648000-b5649000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b5649000-b564a000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 12:25:38.453  6241  6241 W art     : b564a000-b564b000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 12:25:38.453  6241  6241 W art     : b564b000-b5654000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
09-13 12:25:38.453  6241  6241 W art     : b5654000-b5655000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
09-13 12:25:38.453  6241  6241 W art     : b5655000-b5656000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
09-13 12:25:38.453  6241  6241 W art     : b5656000-b56e7000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 12:25:38.453  6241  6241 W art     : b56e7000-b56e8000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b56e8000-b56f3000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 12:25:38.453  6241  6241 W art     : b56f3000-b56f4000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 12:25:38.453  6241  6241 W art     : b56f5000-b5707000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
09-13 12:25:38.453  6241  6241 W art     : b5707000-b5708000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
09-13 12:25:38.453  6241  6241 W art     : b5708000-b5709000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
09-13 12:25:38.453  6241  6241 W art     : b570a000-b570f000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
09-13 12:25:38.453  6241  6241 W art     : b570f000-b5710000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
09-13 12:25:38.453  6241  6241 W art     : b5710000-b5711000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
09-13 12:25:38.453  6241  6241 W art     : b5712000-b577f000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
09-13 12:25:38.453  6241  6241 W art     : b577f000-b5780000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b5780000-b5782000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
09-13 12:25:38.453  6241  6241 W art     : b5782000-b5783000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
09-13 12:25:38.453  6241  6241 W art     : b5783000-b5784000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.453  6241  6241 W art     : b5784000-b578b000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 12:25:38.453  6241  6241 W art     : b578b000-b578c000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 12:25:38.453  6241  6241 W art     : b578c000-b578d000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 12:25:38.453  6241  6241 W art     : b578e000-b580e000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 12:25:38.453  6241  6241 W art     : b580e000-b580f000 ---p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b580f000-b5810000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 12:25:38.453  6241  6241 W art     : b5810000-b5811000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 12:25:38.453  6241  6241 W art     : b5811000-b5828000 rw-p 00000000 00:00 0 
09-13 12:25:38.453  6241  6241 W art     : b5828000-b585f000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 12:25:38.453  6241  6241 W art     : b585f000-b5860000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 12:25:38.463  6241  6241 W art     : b5860000-b5861000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 12:25:38.463  6241  6241 W art     : b5861000-b587d000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 12:25:38.463  6241  6241 W art     : b587d000-b587e000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 12:25:38.463  6241  6241 W art     : b587e000-b587f000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 12:25:38.463  6241  6241 W art     : b5880000-b58e1000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
09-13 12:25:38.463  6241  6241 W art     : b58e1000-b58e3000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
09-13 12:25:38.463  6241  6241 W art     : b58e3000-b58e4000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
09-13 12:25:38.463  6241  6241 W art     : b58e5000-b590a000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
09-13 12:25:38.463  6241  6241 W art     : b590a000-b590b000 r--p 00024000 b3:17 126        /system/lib/libpng.so
09-13 12:25:38.463  6241  6241 W art     : b590b000-b590c000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
09-13 12:25:38.463  6241  6241 W art     : b590d000-b5915000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 12:25:38.463  6241  6241 W art     : b5915000-b5917000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 12:25:38.463  6241  6241 W art     : b5917000-b5918000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 12:25:38.463  6241  6241 W art     : b5919000-b591c000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
09-13 12:25:38.463  6241  6241 W art     : b591c000-b591d000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
09-13 12:25:38.463  6241  6241 W art     : b591d000-b591e000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
09-13 12:25:38.473   774  2439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{95ef0d 1747:android.process.acore/u0a19}
09-13 12:25:38.463  6241  6241 W art     : b591e000-b5922000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
09-13 12:25:38.463  6241  6241 W art     : b5922000-b5923000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5923000-b5924000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
09-13 12:25:38.463  6241  6241 W art     : b5924000-b5925000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
09-13 12:25:38.463  6241  6241 W art     : b5925000-b5935000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
09-13 12:25:38.463  6241  6241 W art     : b5935000-b5936000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
09-13 12:25:38.463  6241  6241 W art     : b5936000-b5937000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
09-13 12:25:38.463  6241  6241 W art     : b5937000-b597d000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b597d000-b5986000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
09-13 12:25:38.463  6241  6241 W art     : b5986000-b5987000 r--p 00008000 b3:17 982        /system/lib/libbase.so
09-13 12:25:38.463  6241  6241 W art     : b5987000-b5988000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
09-13 12:25:38.463  6241  6241 W art     : b5989000-b598e000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
09-13 12:25:38.463  6241  6241 W art     : b598e000-b598f000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
09-13 12:25:38.463  6241  6241 W art     : b598f000-b5990000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
09-13 12:25:38.463  6241  6241 W art     : b5990000-b5993000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 12:25:38.463  6241  6241 W art     : b5993000-b5994000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5994000-b5995000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 12:25:38.463  6241  6241 W art     : b5995000-b5996000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 12:25:38.463  6241  6241 W art     : b5997000-b59af000 r-xp 00000000 b3:17 2789       /system/lib/libstagefri
09-13 12:25:38.463  6241  6241 W art     : ght_foundation.so
09-13 12:25:38.463  6241  6241 W art     : b59af000-b59b0000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b59b0000-b59b1000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 12:25:38.463  6241  6241 W art     : b59b1000-b59b2000 rw-p 00019000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 12:25:38.463  6241  6241 W art     : b59b2000-b59b3000 rw-p 00000000 00:
09-13 12:25:38.463  6241  6241 W art     : 00 0          [anon:linker_alloc_vector]
09-13 12:25:38.463  6241  6241 W art     : b59b3000-b5b4d000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
09-13 12:25:38.463  6241  6241 W art     : b5b4d000-b5b4e000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5b4e000-b5b5b000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
09-13 12:25:38.463  6241  6241 W art     : b5b5b000-b5b5c000 rw-p 001a7000 b3:17 604        /system/
09-13 12:25:38.463  6241  6241 W art     : lib/libstagefright.so
09-13 12:25:38.463  6241  6241 W art     : b5b5c000-b5b60000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
09-13 12:25:38.463  6241  6241 W art     : b5b60000-b5b61000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5b61000-b5b62000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
09-13 12:25:38.463  6241  6241 W art     : b5b62000-b5b63000 rw-p 00005000 b3:17 2676       /system/lib/libp
09-13 12:25:38.463  6241  6241 W art     : ersona.so
09-13 12:25:38.463  6241  6241 W art     : b5b63000-b5b76000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
09-13 12:25:38.463  6241  6241 W art     : b5b76000-b5b77000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
09-13 12:25:38.463  6241  6241 W art     : b5b77000-b5b78000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
09-13 12:25:38.463  6241  6241 W art     : b5b79000-b5bc4000 r
09-13 12:25:38.463  6241  6241 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
09-13 12:25:38.463  6241  6241 W art     : b5bc4000-b5bc5000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
09-13 12:25:38.463  6241  6241 W art     : b5bc5000-b5bc6000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
09-13 12:25:38.463  6241  6241 W art     : b5bc6000-b5bc8000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5bc9000-b5bda000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 12:25:38.463  6241  6241 W art     : b5bda000-b5bdb000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5bdb000-b5bdc000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 12:25:38.463  6241  6241 W art     : b5bdc000-b5bdd000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 12:25:38.463  6241  6241 W art     : b5bdd000-b5bde000 r--p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5bde000-b5be8000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
09-13 12:25:38.463  6241  6241 W art     : b5be8000-b5bea000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
09-13 12:25:38.463  6241  6241 W art     : b5bea000-b5beb000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
09-13 12:25:38.463  6241  6241 W art     : b5beb000-b5c04000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
09-13 12:25:38.463  6241  6241 W art     : b5c04000-b5c05000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
09-13 12:25:38.463  6241  6241 W art     : b5c05000-b5c08000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
09-13 12:25:38.463  6241  6241 W art     : b5c08000-b5c0c000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5c0c000-b5c80000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
09-13 12:25:38.463  6241  6241 W art     : b5c80000-b5c81000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5c81000-b5c84000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
09-13 12:25:38.463  6241  6241 W art     : b5c84000-b5c85000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
09-13 12:25:38.463  6241  6241 W art     : b5c85000-b5c86000 r--p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b5c86000-b5c89000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
09-13 12:25:38.463  6241  6241 W art     : b5c89000-b5c8a000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
09-13 12:25:38.463  6241  6241 W art     : b5c8a000-b5c8b000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
09-13 12:25:38.463  6241  6241 W art     : b5c8b000-b5c8c000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b5c8c000-b5c91000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 12:25:38.463  6241  6241 W art     : b5c91000-b5c92000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 12:25:38.463  6241  6241 W art     : b5c92000-b5c93000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 12:25:38.463  6241  6241 W art     : b5c93000-b5c94000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b5c94000-b5c97000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 12:25:38.463  6281  6281 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
09-13 12:25:38.463  6241  6241 W art     : b5c97000-b5c98000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 12:25:38.463  6281  6281 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
09-13 12:25:38.463  6241  6241 W art     : b5c98000-b5c99000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 12:25:38.463  6281  6281 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
09-13 12:25:38.463  6241  6241 W art     : b5c99000-b5c9a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 12:25:38.463  6241  6241 W art     : b5c9a000-b5c9e000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
09-13 12:25:38.463  6241  6241 W art     : b5c9e000-b5c9f000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
09-13 12:25:38.463  6281  6281 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
09-13 12:25:38.463  6241  6241 W art     : b5c9f000-b5ca0000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
09-13 12:25:38.463  6281  6281 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
09-13 12:25:38.463  6241  6241 W art     : b5ca0000-b5ca1000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b5ca1000-b5ca5000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 12:25:38.463  6241  6241 W art     : b5ca5000-b5ca6000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 12:25:38.463  6281  6281 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
09-13 12:25:38.463  6241  6241 W art     : b5ca6000-b5ca7000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 12:25:38.463  6281  6281 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
09-13 12:25:38.463  6241  6241 W art     : b5ca7000-b5ca8000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b5ca8000-b5cb6000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
09-13 12:25:38.463  6241  6241 W art     : b5cb6000-b5cb7000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6281  6281 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
09-13 12:25:38.463  6281  6281 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
09-13 12:25:38.463  6241  6241 W art     : b5cb7000-b5cb8000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
09-13 12:25:38.463  6281  6281 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:25:38.463  6241  6241 W art     : b5cb8000-b5cb9000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
09-13 12:25:38.463  6241  6241 W art     : b5cb9000-b5cc3000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 12:25:38.463  6241  6241 W art     : b5cc3000-b5cc6000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 12:25:38.463  6281  6281 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-13 12:25:38.463  6241  6241 W art     : b5cc6000-b5cc7000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 12:25:38.463  6241  6241 W art     : b5cc7000-b5cc8000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b5cc8000-b5cd2000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
09-13 12:25:38.463  6241  6241 W art     : b5cd2000-b5cd5000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
09-13 12:25:38.463  6241  6241 W art     : b5cd5000-b5cd6000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
09-13 12:25:38.463  6241  6241 W art     : b5cd6000-b5cda000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
09-13 12:25:38.463  6241  6241 W art     : b5cda000-b5cdb000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
09-13 12:25:38.463  6241  6241 W art     : b5cdb000-b5cdc000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
09-13 12:25:38.463  6241  6241 W art     : b5cdc000-b5cdd000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b5cdd000-b5cea000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
09-13 12:25:38.463  6241  6241 W art     : b5cea000-b5cec000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
09-13 12:25:38.463  6241  6241 W art     : b5cec000-b5ced000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
09-13 12:25:38.463  6281  6281 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
09-13 12:25:38.463  6241  6241 W art     : b5ced000-b60ff000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
09-13 12:25:38.463  6281  6281 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:25:38.463  6241  6241 W art     : b60ff000-b6100000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6100000-b6109000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
09-13 12:25:38.463  6241  6241 W art     : b6109000-b610d000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
09-13 12:25:38.463  6281  6281 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-13 12:25:38.463  6241  6241 W art     : b610d000-b610e000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b610e000-b6115000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
09-13 12:25:38.463  6281  6281 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-13 12:25:38.463  6241  6241 W art     : b6115000-b6116000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
09-13 12:25:38.463  6241  6241 W art     : b6116000-b6117000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
09-13 12:25:38.463  6241  6241 W art     : b6117000-b6118000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b6118000-b6133000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
09-13 12:25:38.463  6241  6241 W art     : b6133000-b6134000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
09-13 12:25:38.463  6241  6241 W art     : b6134000-b6135000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
09-13 12:25:38.463  6241  6241 W art     : b6135000-b6136000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b6136000-b6182000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 12:25:38.463  6241  6241 W art     : b6182000-b6183000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6183000-b6184000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 12:25:38.463  6241  6241 W art     : b6184000-b6185000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 12:25:38.463  6241  6241 W art     : b6185000-b6186000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b6186000-b618a000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
09-13 12:25:38.463  6241  6241 W art     : b618a000-b618b000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b618b000-b618c000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
09-13 12:25:38.463  6241  6241 W art     : b618c000-b618d000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
09-13 12:25:38.463  6241  6241 W art     : b618d000-b61c5000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
09-13 12:25:38.463  6241  6241 W art     : b61c5000-b61c6000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
09-13 12:25:38.463  6241  6241 W art     : b61c6000-b61c7000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
09-13 12:25:38.463  6241  6241 W art     : b61c7000-b61c8000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b61c8000-b6267000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
09-13 12:25:38.463  6241  6241 W art     : b6267000-b6285000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
09-13 12:25:38.463  6241  6241 W art     : b6285000-b6286000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
09-13 12:25:38.463  6241  6241 W art     : b6286000-b63f9000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
09-13 12:25:38.463  6241  6241 W art     : b63f9000-b6404000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
09-13 12:25:38.463  6241  6241 W art     : b6404000-b6405000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
09-13 12:25:38.463  6241  6241 W art     : b6405000-b651c000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
09-13 12:25:38.463  6241  6241 W art     : b651c000-b6527000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
09-13 12:25:38.463  6241  6241 W art     : b6527000-b6528000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
09-13 12:25:38.463  6241  6241 W art     : b6528000-b652c000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b652c000-b6550000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
09-13 12:25:38.463  6241  6241 W art     : b6550000-b6552000 r--p 00023000 b3:17 400        /system/lib/libssl.so
09-13 12:25:38.463  6241  6241 W art     : b6552000-b6553000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
09-13 12:25:38.463  6241  6241 W art     : b6553000-b65f9000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
09-13 12:25:38.463  6241  6241 W art     : b65f9000-b6606000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
09-13 12:25:38.463  6241  6241 W art     : b6606000-b6607000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
09-13 12:25:38.463  6241  6241 W art     : b6607000-b6608000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6608000-b665b000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
09-13 12:25:38.463  6241  6241 W art     : b665b000-b665c000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b665c000-b665d000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
09-13 12:25:38.463  6241  6241 W art     : b665d000-b665e000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
09-13 12:25:38.463  6241  6241 W art     : b665e000-b6663000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6663000-b6675000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
09-13 12:25:38.463  6241  6241 W art     : b6675000-b6676000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6676000-b6677000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
09-13 12:25:38.463  6241  6241 W art     : b6677000-b6678000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
09-13 12:25:38.463  6241  6241 W art     : b6678000-b667f000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 12:25:38.463  6241  6241 W art     : b667f000-b6680000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 12:25:38.463  6241  6241 W art     : b6680000-b6681000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 12:25:38.463  6241  6241 W art     : b6681000-b6682000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6682000-b6685000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
09-13 12:25:38.463  6241  6241 W art     : b6685000-b6686000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
09-13 12:25:38.463  6241  6241 W art     : b6686000-b6687000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
09-13 12:25:38.463  6241  6241 W art     : b6687000-b668b000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
09-13 12:25:38.463  6241  6241 W art     : b668b000-b668c000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
09-13 12:25:38.463  6241  6241 W art     : b668c000-b668d000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
09-13 12:25:38.463  6241  6241 W art     : b668d000-b669b000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
09-13 12:25:38.463  6241  6241 W art     : b669b000-b669c000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b669c000-b669d000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
09-13 12:25:38.463  6241  6241 W art     : b669d000-b669e000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
09-13 12:25:38.463  6241  6241 W art     : b669e000-b66a7000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 12:25:38.463  6241  6241 W art     : b66a7000-b66a8000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 12:25:38.463  6241  6241 W art     : b66a8000-b66a9000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 12:25:38.463  6241  6241 W art     : b66a9000-b670f000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
09-13 12:25:38.463  6241  6241 W art     : b670f000-b6710000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6710000-b6712000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
09-13 12:25:38.463  6241  6241 W art     : b6712000-b671b000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
09-13 12:25:38.463  6241  6241 W art     : b671b000-b671e000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b671e000-b67b5000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
09-13 12:25:38.463  6241  6241 W art     : b67b5000-b67b7000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
09-13 12:25:38.463  6241  6241 W art     : b67b7000-b67b8000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
09-13 12:25:38.463  6241  6241 W art     : b67b8000-b67b9000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b67b9000-b6ad7000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
09-13 12:25:38.463  6241  6241 W art     : b6ad7000-b6ad8000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6ad8000-b6af3000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
09-13 12:25:38.463  6241  6241 W art     : b6af3000-b6af7000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
09-13 12:25:38.463  6241  6241 W art     : b6af7000-b6afc000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6afc000-b6b04000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 12:25:38.463  6241  6241 W art     : b6b04000-b6b05000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 12:25:38.463  6241  6241 W art     : b6b05000-b6b06000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 12:25:38.463  6241  6241 W art     : b6b06000-b6b34000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
09-13 12:25:38.463  6241  6241 W art     : b6b34000-b6b35000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6b35000-b6b3c000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
09-13 12:25:38.463  6241  6241 W art     : b6b3c000-b6b3d000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
09-13 12:25:38.463  6241  6241 W art     : b6b3d000-b6b83000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
09-13 12:25:38.463  6241  6241 W art     : b6b83000-b6b84000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6b84000-b6b87000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
09-13 12:25:38.463  6241  6241 W art     : b6b87000-b6b88000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
09-13 12:25:38.463  6241  6241 W art     : b6b88000-b6ba3000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
09-13 12:25:38.463  6241  6241 W art     : b6ba3000-b6ba7000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
09-13 12:25:38.463  6241  6241 W art     : b6ba7000-b6ba8000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
09-13 12:25:38.463  6241  6241 W art     : b6ba8000-b6bf5000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
09-13 12:25:38.463  6241  6241 W art     : b6bf5000-b6bf6000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6bf6000-b6c02000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
09-13 12:25:38.463  6241  6241 W art     : b6c02000-b6c03000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
09-13 12:25:38.463  6241  6241 W art     : b6c03000-b6c10000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
09-13 12:25:38.463  6241  6241 W art     : b6c10000-b6c11000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6c11000-b6c12000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
09-13 12:25:38.463  6241  6241 W art     : b6c12000-b6c13000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
09-13 12:25:38.463  6241  6241 W art     : b6c13000-b6c1b000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
09-13 12:25:38.463  6241  6241 W art     : b6c1b000-b6c1c000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6c1c000-b6c1d000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
09-13 12:25:38.463  6241  6241 W art     : b6c1d000-b6c1e000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
09-13 12:25:38.463  6241  6241 W art     : b6c1e000-b6c25000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
09-13 12:25:38.463  6241  6241 W art     : b6c25000-b6c26000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
09-13 12:25:38.463  6241  6241 W art     : b6c26000-b6c27000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
09-13 12:25:38.463  6241  6241 W art     : b6c27000-b6c3b000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
09-13 12:25:38.463  6241  6241 W art     : b6c3b000-b6c3d000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
09-13 12:25:38.463  6241  6241 W art     : b6c3d000-b6c3e000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
09-13 12:25:38.463  6241  6241 W art     : b6c3e000-b6c66000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
09-13 12:25:38.463  6241  6241 W art     : b6c66000-b6c68000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
09-13 12:25:38.463  6241  6241 W art     : b6c68000-b6c69000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
09-13 12:25:38.463  6241  6241 W art     : b6c69000-b6c6c000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
09-13 12:25:38.463  6241  6241 W art     : b6c6c000-b6c6d000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
09-13 12:25:38.493   774  1725 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e816ba4 5064:com.sec.android.gallery3d/u0a47}
09-13 12:25:38.463  6241  6241 W art     : b6c6d000-b6c6e000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
09-13 12:25:38.463  6241  6241 W art     : b6c6e000-b6c77000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
09-13 12:25:38.463  6241  6241 W art     : b6c77000-b6c78000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
09-13 12:25:38.463  6241  6241 W art     : b6c78000-b6c79000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
09-13 12:25:38.463  6241  6241 W art     : b6c79000-b6c99000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
09-13 12:25:38.463  6241  6241 W art     : b6c99000-b6c9a000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
09-13 12:25:38.463  6241  6241 W art     : b6c9a000-b6c9b000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
09-13 12:25:38.463  6241  6241 W art     : b6c9b000-b6d0e000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
09-13 12:25:38.463  6241  6241 W art     : b6d0e000-b6d12000 r--p 00072000 b3:17 1016       /system/lib/libc.so
09-13 12:25:38.463  6241  6241 W art     : b6d12000-b6d15000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
09-13 12:25:38.463  6241  6241 W art     : b6d15000-b6d1f000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6d1f000-b6da7000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
09-13 12:25:38.463  6241  6241 W art     : b6da7000-b6da8000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6da8000-b6dac000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
09-13 12:25:38.463  6241  6241 W art     : b6dac000-b6dad000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
09-13 12:25:38.463  6241  6241 W art     : b6dad000-b6dae000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6dae000-b6dd7000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
09-13 12:25:38.463  6241  6241 W art     : b6dd7000-b6dd8000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6dd8000-b6ddb000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
09-13 12:25:38.463  6241  6241 W art     : b6ddb000-b6ddc000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
09-13 12:25:38.463  6241  6241 W art     : b6ddc000-b6eb6000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 12:25:38.463  6241  6241 W art     : b6eb6000-b6ebd000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 12:25:38.463  6241  6241 W art     : b6ebd000-b6ec5000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 12:25:38.463  6241  6241 W art     : b6ec5000-b6ec6000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6ec6000-b6ec7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 12:25:38.463  6241  6241 W art     : b6ec7000-b6ec8000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
09-13 12:25:38.463  6241  6241 W art     : b6ec8000-b6ec9000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b6ec9000-b6ecc000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b6ecc000-b6ef1000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
09-13 12:25:38.463  6241  6241 W art     : b6ef1000-b6ef2000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6ef2000-b6ef9000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
09-13 12:25:38.463  6241  6241 W art     : b6ef9000-b6efa000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
09-13 12:25:38.463  6241  6241 W art     : b6efa000-b6f01000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
09-13 12:25:38.463  6241  6241 W art     : b6f01000-b6f02000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
09-13 12:25:38.463  6241  6241 W art     : b6f02000-b6f03000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
09-13 12:25:38.463  6241  6241 W art     : b6f03000-b6f04000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b6f04000-b6f1c000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
09-13 12:25:38.463  6241  6241 W art     : b6f1c000-b6f1d000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6f1d000-b6f1e000 r--p 00018000 b3:17 918        /system/lib/libutils.so
09-13 12:25:38.463  6241  6241 W art     : b6f1e000-b6f1f000 ,rw-p 00019000 b3:17 918        /system/lib/libutils.so
09-13 12:25:38.463  6241  6241 W art     : b6f1f000-b6f2d000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
09-13 12:25:38.463  6241  6241 W art     : b6f2d000-b6f2e000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6f2e000-b6f2f000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
09-13 12:25:38.463  6241  6241 W art     : b6f2f000-b6f30000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
09-13 12:25:38.463  6241  6241 W art     : b6f30000-b6f31000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 12:25:38.463  6241  6241 W art     : b6f31000-b6f33000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b6f33000-b6f34000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b6f34000-b6f35000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 12:25:38.463  6241  6241 W art     : b6f35000-b6f36000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
09-13 12:25:38.463  6241  6241 W art     : b6f36000-b6f37000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 12:25:38.463  6241  6241 W art     : b6f37000-b6f57000 r--s 00000000 00:0b 7201       /dev/__properties__
09-13 12:25:38.463  6241  6241 W art     : b6f57000-b6f58000 r--p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6f58000-b6f59000 ---p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6f59000-b6f5b000 rw-p 00000000 00:00 0          [anon:thread signal stack]
09-13 12:25:38.463  6241  6241 W art     : b6f5b000-b6f5c000 r-xp 00000000 00:00 0          [sigpage]
09-13 12:25:38.463  6241  6241 W art     : b6f5c000-b6f77000 r-xp 00000000 b3:17 341        /system/bin/linker
09-13 12:25:38.463  6241  6241 W art     : b6f77000-b6f78000 r--p 0001a000 b3:17 341        /system/bin/linker
09-13 12:25:38.463  6241  6241 W art     : b6f78000-b6f7a000 rw-p 0001b000 b3:17 341        /system/bin/linker
09-13 12:25:38.463  6241  6241 W art     : b6f7a000-b6f7c000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : b6f7c000-b6f81000 r-xp 00000000 b3:17 978        /system/bin/app_process32
09-13 12:25:38.463  6241  6241 W art     : b6f81000-b6f82000 r--p 00004000 b3:17 978        /system/bin/app_process32
09-13 12:25:38.463  6241  6241 W art     : b6f82000-b6f83000 rw-p 00000000 00:00 0 
09-13 12:25:38.463  6241  6241 W art     : beeb9000-beeda000 rw-p 00000000 00:00 0          [stack]
09-13 12:25:38.463  6241  6241 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
09-13 12:25:38.503  6241  6241 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 12:25:38.503  5064  5064 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
09-13 12:25:38.503   774  2422 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-13 12:25:38.523   774  3741 I ActivityManager: Start proc 6309:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
09-13 12:25:38.523   774  1323 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 12:25:38.523  6309  6309 E Zygote  : v2
09-13 12:25:38.523  6309  6309 I libpersona: KNOX_SDCARD checking this for 10050
09-13 12:25:38.523  6309  6309 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:38.523  6309  6309 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:38.523  6309  6309 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:38.533  6309  6309 E Zygote  : accessInfo : 0
09-13 12:25:38.533  6309  6309 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
09-13 12:25:38.533   774  1323 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:25:38.543  6241  6241 I Radio-JNI: register_android_hardware_Radio DONE
09-13 12:25:38.553  6309  6309 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:38.553  6309  6309 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:38.553  6241  6241 E AffinityControl: AffinityControl: registerfunction enter
09-13 12:25:38.563   774  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf92f7e 6309:com.sec.android.app.myfiles/u0a50}
09-13 12:25:38.573  6309  6309 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
09-13 12:25:38.573  6241  6241 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 12:25:38.583   774  1742 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
09-13 12:25:38.583  6309  6309 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
09-13 12:25:38.603   774  1742 D ActivityManager: mDVFSHelper.acquire()
09-13 12:25:38.603   774  1742 V WindowManager: addAppToken: AppWindowToken{d9943f5 token=Token{d5e5d2c ActivityRecord{f05ccdf u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
09-13 12:25:38.623  6324  6324 E Zygote  : v2
09-13 12:25:38.623  6324  6324 I libpersona: KNOX_SDCARD checking this for 10004
09-13 12:25:38.623  6324  6324 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:38.623  6324  6324 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:38.623  6324  6324 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:38.623  6324  6324 E Zygote  : accessInfo : 0
09-13 12:25:38.623  6324  6324 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-13 12:25:38.623   774  1742 I ActivityManager: Start proc 6324:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
09-13 12:25:38.623   774  1742 D InputDispatcher: Focused application set to: xxxx
09-13 12:25:38.623   774  1742 D InputDispatcher: Focus left window: 4399
09-13 12:25:38.623   774   901 D SecWifiDisplayUtil: Metadata value : none
09-13 12:25:38.623   774   854 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{14f3575 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
09-13 12:25:38.623   774  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 12:25:38.623   774   901 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{592fcad V.E...... R.....ID 0,0-0,0}
09-13 12:25:38.623  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
09-13 12:25:38.623   774   901 D ISSUE_DEBUG: InputChannelName : 89fcb73 Starting com.test.thalitest
09-13 12:25:38.623  6241  6241 D AndroidRuntime: Shutting down VM
09-13 12:25:38.633   774   901 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:774 uid:1000
09-13 12:25:38.633   774   901 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 12:25:38.633   774   901 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:774 uid:1000
09-13 12:25:38.633   774   901 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
09-13 12:25:38.643   293   293 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, uhalitest
09-13 12:25:38.643  6309  6309 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
09-13 12:25:38.653  6324  6324 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:38.653  6324  6324 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:38.663   774  1726 V WindowOrientationListener: setCurrentAppOrientation :-1
09-13 12:25:38.663   774   901 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
09-13 12:25:38.663   774  1726 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
09-13 12:25:38.673   774   854 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{89fcb73 u0 d0 Starting com.test.thalitest}
09-13 12:25:38.673  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
09-13 12:25:38.693   774  1726 D ActivityManager:  Launching com.test.thalitest, updated priority
09-13 12:25:38.713  1694  1855 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
09-13 12:25:38.713  1694  1694 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
,09-13 12:25:38.713  4399  4399 V ActivityThread: updateVisibility : ActivityRecord{d876bb5 token=android.os.BinderProxy@694138d {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
09-13 12:25:38.723   774   901 V WindowStateAnimator: Finishing drawing window Window{89fcb73 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-13 12:25:38.723   293   330 D libEGL  : eglTerminate EGLDisplay = 0xb677f64c
09-13 12:25:38.723   293   330 D libEGL  : eglTerminate EGLDisplay = 0xb677f64c
09-13 12:25:38.733   293  1296 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
09-13 12:25:38.733   293  1295 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
09-13 12:25:38.733   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef3d3a4
09-13 12:25:38.733   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef3d364
09-13 12:25:38.733   293  1295 I SurfaceFlinger: id=14 Removed YUIInstallC (5/9)
09-13 12:25:38.733   293   324 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/9)
09-13 12:25:38.743  1694  1694 V ActivityThread: updateVisibility : ActivityRecord{57580f4 token=android.os.BinderProxy@1aff877 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-13 12:25:38.743  2123  2137 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
09-13 12:25:38.743  1694  1694 D Launcher: onTrimMemory. Level: 20
09-13 12:25:38.783   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-13 12:25:39.003   774  1726 I WindowManager: Screenshot max retries 4 of Token{d5e5d2c ActivityRecord{f05ccdf u0 com.test.thalitest/.MainActivity t168}} appWin=Window{89fcb73 u0 d0 Starting com.test.thalitest} drawState=4
09-13 12:25:39.033   774   787 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ea5298f 2830:com.android.settings/1000}
09-13 12:25:39.033  6324  6324 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
09-13 12:25:39.033   774   849 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-13 12:25:39.043  6342  6342 E Zygote  : v2
09-13 12:25:39.043  6342  6342 I libpersona: KNOX_SDCARD checking this for 10210
09-13 12:25:39.043  6342  6342 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:39.043  6342  6342 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:39.043  6342  6342 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:39.053  6342  6342 E Zygote  : accessInfo : 0
09-13 12:25:39.053  6342  6342 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
09-13 12:25:39.053   774   849 I ActivityManager: Start proc 6342:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
09-13 12:25:39.053   774  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-13 12:25:39.063   774  3409 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-13 12:25:39.073  6324  6324 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
09-13 12:25:39.073  6324  6324 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
09-13 12:25:39.073   337   337 E installd: system dir 0 : /system/app/
09-13 12:25:39.073   337   337 E installd: system dir 1 : /system/priv-app/
09-13 12:25:39.073   337   337 E installd: system dir 2 : /vendor/app/
09-13 12:25:39.073   337   337 E installd: system dir 3 : /oem/app/
09-13 12:25:39.083   774   788 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ea5298f 2830:com.android.settings/1000}
09-13 12:25:39.093  6324  6324 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
09-13 12:25:39.113  6354  6354 E Zygote  : v2
09-13 12:25:39.113  6354  6354 I libpersona: KNOX_SDCARD checking this for 10169
09-13 12:25:39.113  6354  6354 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:39.113  6354  6354 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:39.113   774  1415 I ActivityManager: Start proc 6354:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
09-13 12:25:39.113  6354  6354 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:39.113  6354  6354 E Zygote  : accessInfo : 0
09-13 12:25:39.123  6342  6342 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:39.123  6342  6342 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:39.123  6354  6354 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
09-13 12:25:39.133  6324  6324 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
09-13 12:25:39.143  6342  6342 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
09-13 12:25:39.143  6324  6324 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 12:25:39.153  6354  6354 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:39.153  6354  6354 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:39.153  6324  6324 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 872-876)
09-13 12:25:39.153  6324  6324 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
09-13 12:25:39.163  6342  6342 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
09-13 12:25:39.163   774  1646 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{da1abcf 6354:com.samsung.android.provider.shootingmodeprovider/u0a169}
09-13 12:25:39.163  6342  6342 D AASAservice: onCreate()
09-13 12:25:39.173   774  3741 I ActivityManager: Killing 5435:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
09-13 12:25:39.173   774   924 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
09-13 12:25:39.173  6324  6372 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-13 12:25:39.173  5293  5293 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
09-13 12:25:39.183  6354  6354 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
09-13 12:25:39.183  6324  6324 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {843c59d}
09-13 12:25:39.183  6324  6324 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
09-13 12:25:39.183  6324  6324 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 12:25:39.193  6354  6354 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
09-13 12:25:39.193  6324  6324 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-13 12:25:39.193   774   788 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
09-13 12:25:39.213   774  1726 I ActivityManager: Killing 4048:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
09-13 12:25:39.213   774  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{748cd57 1680:com.android.phone/1001}
09-13 12:25:39.223  6324  6324 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 12:25:39.223  6324  6324 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 12:25:39.223  6324  6324 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 12:25:39.223  6324  6324 I Adreno-EGL: Local Branch: ss
09-13 12:25:39.223  6324  6324 I Adreno-EGL: Remote Branch: 
09-13 12:25:39.223  6324  6324 I Adreno-EGL: Local Patches: 
09-13 12:25:39.223  6324  6324 I Adreno-EGL: Reconstruct Branch: 
09-13 12:25:39.223   774   788 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b51b70d 1824:com.google.android.googlequicksearchbox:search/u0a61}
09-13 12:25:39.223  6324  6324 D libEGL  : eglInitialize EGLDisplay = 0xbeca1dac
09-13 12:25:39.233   774  1742 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
09-13 12:25:39.243   774  3741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b51b70d 1824:com.google.android.googlequicksearchbox:search/u0a61}
09-13 12:25:39.253   774  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{891a53a 6176:com.samsung.android.sm.provider/1000}
09-13 12:25:39.273  6390  6390 E Zygote  : v2
09-13 12:25:39.273  6390  6390 I libpersona: KNOX_SDCARD checking this for 5012
09-13 12:25:39.273  6390  6390 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:39.273   774  2439 I ActivityManager: Start proc 6390:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
09-13 12:25:39.273  6390  6390 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:39.273  6390  6390 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:39.273  6390  6390 E Zygote  : accessInfo : 0
09-13 12:25:39.273  6390  6390 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
09-13 12:25:39.273   774  2422 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
09-13 12:25:39.273   774  2422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29689 com.android.server.am.ActivityManagerService.registerReceiver:22554 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
09-13 12:25:39.313  6390  6390 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:39.313  6390  6390 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:39.323  6324  6324 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-13 12:25:39.333   774   787 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{356d624 6390:com.samsung.android.sm.devicesecurity/5012}
09-13 12:25:39.333  6324  6324 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 12:25:39.333  6324  6324 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
09-13 12:25:39.333  6324  6324 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
09-13 12:25:39.333  6324  6324 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-13 12:25:39.333  1824  6379 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-13 12:25:39.333  6390  6390 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
09-13 12:25:39.353  6324  6324 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
09-13 12:25:39.353  6390  6390 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
09-13 12:25:39.353  6324  6324 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-13 12:25:39.403   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b001987 3182:com.android.contacts/u0a19}
09-13 12:25:39.413  6411  6411 E Zygote  : v2
09-13 12:25:39.413  6411  6411 I libpersona: KNOX_SDCARD checking this for 10049
09-13 12:25:39.413  6411  6411 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:39.423  6411  6411 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:39.423   774  1742 I ActivityManager: Start proc 6411:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
09-13 12:25:39.423  6411  6411 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:39.423  1824  6379 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
09-13 12:25:39.423   774  1323 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 12:25:39.423  6411  6411 E Zygote  : accessInfo : 0
09-13 12:25:39.423  6411  6411 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
09-13 12:25:39.423   774  1323 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:25:39.443  1824  6379 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
09-13 12:25:39.443  6324  6324 D SecWifiDisplayUtil: Metadata value : none
09-13 12:25:39.453  6324  6324 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7c51972 I.E...... R.....ID 0,0-0,0}
09-13 12:25:39.453  6324  6425 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-13 12:25:39.453  6411  6411 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:39.453  6411  6411 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:39.463   774  1320 D ISSUE_DEBUG: InputChannelName : 8413daf com.test.thalitest/com.test.thalitest.MainActivity
09-13 12:25:39.463   774  1612 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-13 12:25:39.463   774  1612 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 12:25:39.463   774   774 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 12:25:39.463   774   774 I KnoxTimeoutHandler: Shared devices show user statefalse
09-13 12:25:39.473   774  3741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ecc5bc 6411:com.android.mms/u0a49}
09-13 12:25:39.493  6411  6411 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
09-13 12:25:39.503   774  2439 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
09-13 12:25:39.503  6324  6324 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6324
09-13 12:25:39.503   774   788 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6324 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:25:39.503   774  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-13 12:25:39.503   774  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 12:25:39.503   774  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-13 12:25:39.503   774  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 12:25:39.513   774  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 12:25:39.513   774  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 12:25:39.513   774  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-13 12:25:39.513   774  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 12:25:39.513   774  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-13 12:25:39.513   774  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:25:39.523  6324  6324 D SecWifiDisplayUtil: Metadata value : none
09-13 12:25:39.523  6324  6372 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-13 12:25:39.533   293   293 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
09-13 12:25:39.533  6411  6411 W System  : ClassLoader referenced unknown path: imsmanager.jar
09-13 12:25:39.543   774   787 D InputDispatcher: Focus entered window: 6324
09-13 12:25:39.543  6411  6411 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
09-13 12:25:39.553  6324  6425 D libEGL  : eglInitialize EGLDisplay = 0x9caad7c4
09-13 12:25:39.553  6324  6425 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 12:25:39.553   774   901 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:774 uid:1000
09-13 12:25:39.553   774   901 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 12:25:39.553   774   901 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:774 uid:1000
09-13 12:25:39.553   774   901 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
09-13 12:25:39.563  2800  6429 W IcingInternalCorpora: getNumBytesRead when not calculated.
09-13 12:25:39.613  6324  6324 V ActivityThread: updateVisibility : ActivityRecord{760d835 token=android.os.BinderProxy@af8567d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-13 12:25:39.613  6324  6324 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
09-13 12:25:39.613  6324  6324 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-13 12:25:39.623  1824  6379 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 290 ms] updated apps [took 290 ms] 
09-13 12:25:39.633  6411  6411 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
09-13 12:25:39.633   774  1415 V WindowStateAnimator: Finishing drawing window Window{8413daf u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-13 12:25:39.643  6324  6324 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
09-13 12:25:39.643   774  1646 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-13 12:25:39.643  6411  6433 D Mms/ArtClassLoader: init before art second
09-13 12:25:39.643   774   901 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 12:25:39.643  6411  6432 D Mms/ArtClassLoader: init before art first
09-13 12:25:39.643   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef3d364
09-13 12:25:39.643   774   774 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 12:25:39.653  6324  6324 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
09-13 12:25:39.653   774   774 I KnoxTimeoutHandler: SD activityfalse
09-13 12:25:39.653  6411  6411 D Mms/TelephonyPermission: start operation mode monitor
09-13 12:25:39.653  6411  6411 D Mms/TelephonyPermission: User ID is null set current User Id
09-13 12:25:39.653   774   901 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +650ms (total +1s46ms)
09-13 12:25:39.653   774   901 D ActivityManager: mDVFSHelper.release()
09-13 12:25:39.653   774   901 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f05ccdf u0 com.test.thalitest/.MainActivity t168} time:101378
09-13 12:25:39.653   774   901 D ViewRootImpl: #3 mView = null
09-13 12:25:39.663  6411  6434 D Mms/ArtClassLoader: init before art third
09-13 12:25:39.663   293   330 I SurfaceFlinger: id=16 Removed uhalitest (7/9)
09-13 12:25:39.663  6324  6324 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@af8567d time:101383
09-13 12:25:39.663   293   324 I SurfaceFlinger: id=16 Removed uhalitest (-2/9)
09-13 12:25:39.663  6411  6411 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
09-13 12:25:39.663  6411  6411 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
09-13 12:25:39.673   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef3d3a4
09-13 12:25:39.683  6411  6434 D Mms/ArtClassLoader: init [DONE] art
09-13 12:25:39.693  6324  6437 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 12:25:39.693  6324  6437 D libEGL  : eglInitialize EGLDisplay = 0x9b46a3ec
09-13 12:25:39.703  6411  6411 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-13 12:25:39.703  6411  6411 D Mms/TelephonyPermission: isDefault true
09-13 12:25:39.703  6411  6411 D Mms/MmsApp: onCreate() com.android.mms
09-13 12:25:39.743  6324  6324 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6324
09-13 12:25:39.813  6411  6411 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
09-13 12:25:39.813  6411  6432 D Mms/ArtClassLoader: init [DONE] art
09-13 12:25:39.813  6411  6433 D Mms/ArtClassLoader: init [DONE] art
09-13 12:25:39.813  6411  6411 D Mms/MmsApp: [start]    initCountryIso consume time = 181.228645
09-13 12:25:39.813   774  1612 D CountryDetector: The first listener is added
09-13 12:25:39.823  6411  6411 D Mms/MmsApp: [end]    initCountryIso consume time = 5.442188
09-13 12:25:39.823  6411  6411 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.105104
09-13 12:25:39.823  6411  6411 D Mms/MmsConfig: before partial update
09-13 12:25:39.853  6411  6411 D Mms/MmsConfig: Load Resize quality : 80
09-13 12:25:39.863  6411  6411 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
09-13 12:25:39.863  6411  6411 D EasySignUpManager_1.0.5: isAuth is false
09-13 12:25:39.863  6411  6411 I EasySignUpManager_1.0.5: auth : false, join : 2
09-13 12:25:39.863  6411  6411 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
09-13 12:25:39.863  6411  6411 D EasySignUpManager_1.0.5: userSerialNumber = 0
09-13 12:25:39.863  6411  6411 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
09-13 12:25:39.863  6411  6411 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
09-13 12:25:39.863  6411  6411 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
09-13 12:25:39.863  6411  6411 D EasySignUpManager_1.0.5: isAuth is false
09-13 12:25:39.863  6411  6411 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
09-13 12:25:39.863  6411  6411 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
09-13 12:25:39.873  1680  1691 D TP/MmsSmsProvider: query, match:2117, calling pid = 6411, accessRestricted = false
09-13 12:25:39.873  1680  1691 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.255 ms
09-13 12:25:39.883  6411  6411 E CscParser: mps_code.dat does not exist
09-13 12:25:39.883  6411  6411 E CscParser: customer_path =/system/csc/customer.xml
09-13 12:25:39.883  6411  6411 E CscParser: fileName + /system/csc/customer.xml
09-13 12:25:39.893  6411  6411 E CscParser: mps_code.dat does not exist
09-13 12:25:39.893  6411  6411 E CscParser: customer_path =/system/csc/customer.xml
09-13 12:25:39.893  6411  6411 E CscParser: fileName + /system/csc/customer.xml
09-13 12:25:39.903  6411  6411 D CscParser: getInstance fileName =/system/csc/customer.xml
09-13 12:25:39.903  6411  6411 D Mms/MmsConfig:  enable multiwindow = true
09-13 12:25:39.903  6411  6411 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
09-13 12:25:39.903  6411  6411 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
09-13 12:25:39.903  6411  6411 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
09-13 12:25:39.903  6411  6411 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
09-13 12:25:39.903  6411  6411 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
09-13 12:25:39.903  6411  6411 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-13 12:25:39.903  6411  6411 E Mms/MessageUtils: updateCountryIso : update country iso info 
09-13 12:25:39.903  6411  6411 D Mms/MmsConfig: [end]    init() consume time = 85.5825
09-13 12:25:39.913  6324  6324 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 12:25:39.923  6411  6411 D Mms/Contact: [start]    init() consume time = 14.077136
,09-13 12:25:39.943  1680  1937 D TP/MmsSmsProvider: query, match:13, calling pid = 6411, accessRestricted = false
,09-13 12:25:39.943  1680  1937 D TP/MmsSmsProvider: query, match 13:Elapsed time : 3.036 ms
,09-13 12:25:39.943  6411  6411 D Mms/Contact: [end]    init consume time = 22.487447
,09-13 12:25:39.953  6411  6411 D Mms:transaction: roaming -> false (slotId = 0)
09-13 12:25:39.953  6411  6411 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 12:25:39.953  6411  6411 D Mms:transaction: auto download without roaming -> true
09-13 12:25:39.953  6411  6411 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
09-13 12:25:39.953  6411  6411 D Mms:transaction: roaming -> false (slotId = 1)
09-13 12:25:39.953  6411  6411 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-13 12:25:39.953  6411  6411 D Mms:transaction: auto download without roaming -> true
09-13 12:25:39.953  6411  6411 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 12:25:39.953  6411  6411 D Mms:transaction: auto download during roaming secondary -> false
09-13 12:25:39.953  6411  6411 D Mms:transaction: mAutoDownload ------> true
,09-13 12:25:39.953  6411  6449 D Mms/DraftCache: [start]    rebuildCache consume time = 10.07302
,09-13 12:25:39.963  1680  2781 D TP/MmsSmsProvider: query, match:12, calling pid = 6411, accessRestricted = false
,09-13 12:25:39.963  1680  2781 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.090 ms
,09-13 12:25:39.963  6411  6449 D Mms/DraftCache: [end]    rebuildCache consume time = 9.441094
,09-13 12:25:39.983  6411  6411 D ComposerPerformance: 1473762339988 ms / [DONE] Composer constructor
,09-13 12:25:39.983  6411  6411 D CII     : Log Level [5]
09-13 12:25:39.983  6411  6411 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,09-13 12:25:39.983  6411  6450 D Mms/Conversation: [start]    init() consume time = 22.778332
,09-13 12:25:39.983  6411  6411 I Mms/ReservationManager: ReservationManager()
,09-13 12:25:39.983  6411  6411 I Mms/ReservationManager: resetAfterConnected()
09-13 12:25:39.983  1680  1692 D TP/MmsSmsProvider: delete, match:1, calling pid = 6411
09-13 12:25:39.983  1680  1692 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-13 12:25:39.983  1680  1692 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,09-13 12:25:39.993  1680  1692 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,09-13 12:25:39.993  1680  1692 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-13 12:25:39.993  1680  1692 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,09-13 12:25:39.993  1680  1937 D TP/MmsSmsProvider: query, match:7, calling pid = 6411, accessRestricted = false
,09-13 12:25:39.993  1680  1692 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,09-13 12:25:39.993  1680  1937 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.057 ms
,09-13 12:25:40.003  6411  6411 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,09-13 12:25:40.003  6411  6411 D Mms/MmsApp: [end]    onCreate() consume time = 16.773335
09-13 12:25:40.003  6411  6411 D Mms/MmsApp: [end]    onCreate() consume time = 0.081197
,09-13 12:25:40.003  6411  6411 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,09-13 12:25:40.003  6411  6411 D Mms:transaction: roaming ------> false, mSimSlot = 0
09-13 12:25:40.003  6411  6411 D Mms:transaction: roaming -> false (slotId = 0)
09-13 12:25:40.003  6411  6411 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 12:25:40.003  6411  6411 D Mms:transaction: auto download without roaming -> true
09-13 12:25:40.003  6411  6411 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
09-13 12:25:40.003  6411  6411 D Mms:transaction: mAutoDownload ------> true
,09-13 12:25:40.013  1680  1692 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
09-13 12:25:40.013  1680  1692 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
09-13 12:25:40.013  1680  1692 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-13 12:25:40.013  1680  1692 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 14.785 ms
09-13 12:25:40.013  1680  1692 D TP/MmsSmsProvider: need read changed broadcast:false
,09-13 12:25:40.013  6452  6452 E Zygote  : v2
09-13 12:25:40.013   774  1415 I ActivityManager: Start proc 6452:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
09-13 12:25:40.013  6452  6452 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:40.013  6452  6452 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:40.013  6452  6452 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:25:40.013  6452  6452 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:40.013  6452  6452 E Zygote  : accessInfo : 0
,09-13 12:25:40.013   774  1415 I ActivityManager: Killing 4913:com.samsung.android.sm/1000 (adj 15): DHA:empty #37
,09-13 12:25:40.023  6411  6450 D Mms/Conversation: [end]    init consume time = 18.641668
,09-13 12:25:40.023  6411  6450 D Mms/MessagingNotification: [start]    init() consume time = 2.09
,09-13 12:25:40.023  6411  6450 D Mms/MessagingNotification: [end]    init consume time = 4.232864
,09-13 12:25:40.033  1680  2781 D TP/MmsSmsProvider: query, match:0, calling pid = 6411, accessRestricted = false
09-13 12:25:40.033  1680  2781 V TP/MmsSmsProvider: getSimpleConversations entered.
,09-13 12:25:40.033  1680  2781 D TP/MmsSmsProvider: query, match 0:Elapsed time : 0.860 ms
,09-13 12:25:40.043  6324  6451 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1696859856
,09-13 12:25:40.043  6452  6452 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:40.043  6452  6452 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:40.043  6324  6451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 12:25:40.043  6324  6451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 12:25:40.043  6324  6451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 12:25:40.043  6324  6451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 12:25:40.043  6324  6451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 12:25:40.053  6324  6451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dda1b3 added. We now have 1 listener(s)
,09-13 12:25:40.053  6411  6464 D Mms/Synchronizer: [start]    doSync consume time = 23.897344
,09-13 12:25:40.053  6411  6463 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.252656
,09-13 12:25:40.053   774  3410 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,09-13 12:25:40.053   774  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8c1bfa 6452:com.samsung.android.bbc.bbcagent/1000}
,09-13 12:25:40.063  6324  6451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,09-13 12:25:40.063  6324  6451 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 12:25:40.063  6324  6451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 12:25:40.063  6324  6451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:25:40.063   774  1742 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
,09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 12:25:40.063  6324  6451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ddef6e added. We now have 1 listener(s)
09-13 12:25:40.063  6324  6451 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 12:25:40.073  6324  6451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:25:40.073  6324  6451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 12:25:40.073  6324  6451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-13 12:25:40.073  6324  6451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 12:25:40.073  6324  6451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 12:25:40.073  6452  6452 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,09-13 12:25:40.083  6037  6051 D BadgeProvider: query, [selection] : package=?
09-13 12:25:40.083  1680  1937 D TP/MmsSmsProvider: update, match:300, calling pid = 6411
,09-13 12:25:40.083  1680  1937 V TP/MmsSmsProvider: syncDBData start
,09-13 12:25:40.083  1680  1937 V TP/MmsSmsProvider: syncDBData sms end
,09-13 12:25:40.083  1680  1937 V TP/MmsSmsProvider: syncDBData mms end
,09-13 12:25:40.083  6324  6451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:25:40.083  6324  6451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,09-13 12:25:40.083  1680  1937 V TP/MmsSmsProvider: syncDBData end
,09-13 12:25:40.093  1680  1937 D TP/MmsSmsProvider: update, match 300:Elapsed time : 6.503 ms
,09-13 12:25:40.093  6411  6450 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-13 12:25:40.093  6411  6464 D Mms/Synchronizer: [end]    doSync consume time = 39.572709
,09-13 12:25:40.093  6324  6451 D BluetoothAdapter: STATE_ON
,09-13 12:25:40.093  6324  6451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 12:25:40.093  6324  6451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:40.093  6324  6451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:40.093  6324  6451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:40.093  6324  6451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:40.093  6324  6451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:40.093  6324  6451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:40.093  6324  6451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:40.093  6324  6451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:25:40.103  6324  6451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 12:25:40.103  6324  6451 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:25:40.103  6324  6451 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 12:25:40.103  1680  1691 D TP/MmsSmsProvider: query, match:400, calling pid = 6411, accessRestricted = false
,09-13 12:25:40.133  6324  6324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:40.143  1680  1692 D TP/SmsProvider: query,matched:26, calling pid = 6411
,09-13 12:25:40.143  6324  6324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:40.143  1680  1692 D TP/SmsProvider: query, match 26:Elapsed time : 1.774 ms
,09-13 12:25:40.143  6324  6324 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 12:25:40.153  6452  6452 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,09-13 12:25:40.153  6411  6463 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 61.862031
,09-13 12:25:40.183  1680  2781 D TP/MmsSmsProvider: query, match:6, calling pid = 6411, accessRestricted = false
,09-13 12:25:40.183  1680  2781 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.729 ms
,09-13 12:25:40.193   774   784 I art     : Background partial concurrent mark sweep GC freed 57131(3MB) AllocSpace objects, 9(320KB) LOS objects, 27% free, 42MB/58MB, paused 1.565ms total 114.039ms
,09-13 12:25:40.213  6467  6467 E Zygote  : v2
,09-13 12:25:40.213  6467  6467 I libpersona: KNOX_SDCARD checking this for 10097
09-13 12:25:40.213  6467  6467 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:40.213  6467  6467 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:25:40.213  6467  6467 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:25:40.223  6467  6467 E Zygote  : accessInfo : 0
,09-13 12:25:40.223  6467  6467 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,09-13 12:25:40.223   774  2422 I ActivityManager: Start proc 6467:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,09-13 12:25:40.233   774  2422 I ActivityManager: Killing 5101:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,09-13 12:25:40.253  6467  6467 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:40.253  6467  6467 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:40.253  6479  6479 E Zygote  : v2
09-13 12:25:40.253  6479  6479 I libpersona: KNOX_SDCARD checking this for 10024
09-13 12:25:40.253  6479  6479 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:40.253  6479  6479 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:40.253  6479  6479 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:25:40.253  6479  6479 E Zygote  : accessInfo : 0
,09-13 12:25:40.253  6479  6479 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,09-13 12:25:40.253   774   788 I ActivityManager: Start proc 6479:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,09-13 12:25:40.263   774  1612 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,09-13 12:25:40.273  6324  6333 I art     : Background sticky concurrent mark sweep GC freed 51382(3MB) AllocSpace objects, 9(180KB) LOS objects, 31% free, 17MB/25MB, paused 992us total 100.076ms
,09-13 12:25:40.273   774  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{93dfcdd 6467:com.google.android.apps.docs/u0a97}
,09-13 12:25:40.283  6479  6479 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:40.283  6479  6479 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:40.283   774  2422 I ActivityManager: Killing 5087:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,09-13 12:25:40.293  6467  6467 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,09-13 12:25:40.303  6479  6479 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,09-13 12:25:40.313   774  1501 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,09-13 12:25:40.313  6479  6479 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,09-13 12:25:40.323  6467  6467 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,09-13 12:25:40.363  6479  6479 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,09-13 12:25:40.373  6411  6450 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,09-13 12:25:40.403  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,09-13 12:25:40.403  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,09-13 12:25:40.403  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,09-13 12:25:40.403  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,09-13 12:25:40.403  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-13 12:25:40.413  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-13 12:25:40.413  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-13 12:25:40.413  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-13 12:25:40.413  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-13 12:25:40.413  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-13 12:25:40.423  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,09-13 12:25:40.423  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,09-13 12:25:40.423  6479  6479 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,09-13 12:25:40.473  1456  1456 D Recents : onTaskStackChanged
,09-13 12:25:40.483  1456  1456 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,09-13 12:25:40.613  6467  6493 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
09-13 12:25:40.613  6467  6493 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 12:25:40.613  6467  6493 I GAv4    :   adb logcat -s GAv4
,09-13 12:25:40.623  2800  4982 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,09-13 12:25:40.633  6467  6493 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,09-13 12:25:40.633   774  2439 V AlarmManager:  remove PendingIntent] PendingIntent{72289d9: PendingIntentRecord{68aff9e com.google.android.apps.docs broadcastIntent}}
,09-13 12:25:40.633  6467  6493 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 12:25:40.643  6467  6493 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 12:25:40.683  6467  6499 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 12:25:40.713  2800  4982 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,09-13 12:25:40.753  6467  6467 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,09-13 12:25:40.763  6467  6467 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,09-13 12:25:40.783  2800  4982 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,09-13 12:25:40.843  6467  6493 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
09-13 12:25:40.843  6467  6493 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
09-13 12:25:40.843  6467  6493 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,09-13 12:25:40.853   774  6154 I HarmonyEASService: Updating for all 1
,09-13 12:25:40.853  6467  6493 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,09-13 12:25:40.883  6505  6505 E Zygote  : v2
09-13 12:25:40.883  6505  6505 I libpersona: KNOX_SDCARD checking this for 10098
09-13 12:25:40.883  6505  6505 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:40.883  6505  6505 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:40.883  6505  6505 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:40.883  6505  6505 E Zygote  : accessInfo : 0
09-13 12:25:40.883  6505  6505 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,09-13 12:25:40.883   774  1320 I ActivityManager: Start proc 6505:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,09-13 12:25:40.883   774  1320 I ActivityManager: Killing 5133:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,09-13 12:25:40.903   774  1415 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,09-13 12:25:40.913  6505  6505 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:40.913  6505  6505 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:40.923   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c2377aa 6505:com.sec.android.automotive.drivelink/u0a98}
,09-13 12:25:40.933  6505  6505 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,09-13 12:25:40.953  6505  6505 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,09-13 12:25:40.963  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:40.963  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:41.003  6505  6505 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,09-13 12:25:41.003  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:41.013   774  2439 V AlarmManager:  remove PendingIntent] PendingIntent{6af5202: PendingIntentRecord{32eb713 com.sec.android.automotive.drivelink broadcastIntent}}
,09-13 12:25:41.013  6505  6521 I GMPM    : App measurement is starting up
,09-13 12:25:41.023  6505  6505 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,09-13 12:25:41.023  6324  6466 W jxcore-log: Initializing JXcore engine
,09-13 12:25:41.023  6324  6466 W jxcore-log: JXcore engine is ready
,09-13 12:25:41.023  6505  6521 E GMPM    : getGoogleAppId failed with status: 10
,09-13 12:25:41.023  6505  6521 E GMPM    : Uploading is not possible. App measurement disabled
,09-13 12:25:41.023   774  1415 V AlarmManager:  remove PendingIntent] PendingIntent{25ded50: PendingIntentRecord{32eb713 com.sec.android.automotive.drivelink broadcastIntent}}
,09-13 12:25:41.043  6505  6505 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,09-13 12:25:41.053  6505  6505 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,09-13 12:25:41.063  6467  6494 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,09-13 12:25:41.063  2320  2320 E audit   : type=1400 msg=audit(1473762341.063:287): avc:  denied  { ioctl } for  pid=6466 comm="Thread-875" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 12:25:41.063  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:41.063  2320  2320 E audit   : type=1300 msg=audit(1473762341.063:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9acba3c8 items=0 ppid=355 ppcomm=main pid=6466 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-875" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 12:25:41.063  2320  2320 E audit   : type=1327 msg=audit(1473762341.063:287): proctitle="com.test.thalitest"
09-13 12:25:41.063  2320  2320 E audit   : type=1320 msg=audit(1473762341.063:287): 
,09-13 12:25:41.063  2320  2320 E audit   : type=1400 msg=audit(1473762341.063:288): avc:  denied  { ioctl } for  pid=6466 comm="Thread-875" path="socket:[40109]" dev="sockfs" ino=40109 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 12:25:41.063  2320  2320 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:41.063  2320  2320 E audit   : type=1300 msg=audit(1473762341.063:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9acba3c8 items=0 ppid=355 ppcomm=main pid=6466 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-875" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 12:25:41.063  2320  2320 E audit   : type=1327 msg=audit(1473762341.063:288): proctitle="com.test.thalitest"
09-13 12:25:41.063  2320  2320 E audit   : type=1320 msg=audit(1473762341.063:288): 
,09-13 12:25:41.073  6324  6466 W jxcore-log: Starting JXcore engine
,09-13 12:25:41.103  6527  6527 E Zygote  : v2
09-13 12:25:41.103  6527  6527 I libpersona: KNOX_SDCARD checking this for 10032
09-13 12:25:41.103  6527  6527 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:41.103  6527  6527 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:41.103  6527  6527 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 12:25:41.103   774   788 I ActivityManager: Start proc 6527:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,09-13 12:25:41.103  6527  6527 E Zygote  : accessInfo : 0
,09-13 12:25:41.103   774  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 12:25:41.103  6527  6527 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,09-13 12:25:41.133  6527  6527 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:41.133  6527  6527 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:41.143   774  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,09-13 12:25:41.143  6467  6494 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,09-13 12:25:41.143  6527  6527 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,09-13 12:25:41.153  6527  6527 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,09-13 12:25:41.163  6467  6494 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
09-13 12:25:41.163  6467  6494 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,09-13 12:25:41.163  6467  6494 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-13 12:25:41.163  6324  6466 W jxcore-log: Platform android
09-13 12:25:41.163  6324  6466 W jxcore-log: 
,09-13 12:25:41.173  6324  6466 W jxcore-log: Process ARCH arm
09-13 12:25:41.173  6324  6466 W jxcore-log: 
,09-13 12:25:41.213  6467  6494 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 12:25:41.233  6505  6505 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,09-13 12:25:41.233  6505  6505 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,09-13 12:25:41.233  6505  6505 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,09-13 12:25:41.263  6505  6505 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Sep 13 12:25:41 GMT+02:00 2016
,09-13 12:25:41.273  6527  6527 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,09-13 12:25:41.273  6541  6541 E Zygote  : v2
09-13 12:25:41.273  6541  6541 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:41.273  6541  6541 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:41.273  6541  6541 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:41.273  6541  6541 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:25:41.273  6541  6541 E Zygote  : accessInfo : 0
,09-13 12:25:41.273  6505  6505 D DialogFlow: initQueue()
,09-13 12:25:41.273   774  1415 I ActivityManager: Start proc 6541:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,09-13 12:25:41.283   774  1415 I ActivityManager: Killing 5422:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,09-13 12:25:41.283   774  1415 I ActivityManager: Killing 4660:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,09-13 12:25:41.303  6541  6541 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:41.303  6541  6541 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:41.313   774  1415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3f58b 6541:com.samsung.android.app.filterinstaller/1000}
,09-13 12:25:41.313   774  1717 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,09-13 12:25:41.323  6541  6541 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,09-13 12:25:41.323   774   787 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,09-13 12:25:41.333  6541  6541 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,09-13 12:25:41.333  6527  6527 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,09-13 12:25:41.343  6541  6541 E FilterPackageIntentReceiver: This package is not a effect filter
,09-13 12:25:41.363   774  2439 I ActivityManager: Start proc 6558:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,09-13 12:25:41.363   774  2439 I ActivityManager: Killing 5031:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,09-13 12:25:41.363  6558  6558 E Zygote  : v2
09-13 12:25:41.363  6558  6558 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:41.363  6558  6558 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:41.363  6558  6558 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:41.363  6558  6558 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:25:41.363  6558  6558 E Zygote  : accessInfo : 0
,09-13 12:25:41.383  6324  6466 I jxcore-log: JXcore Cordova bridge is ready!
09-13 12:25:41.383  6324  6466 I jxcore-log: 
,09-13 12:25:41.383  6324  6466 W jxcore-log: JXcore engine is started
,09-13 12:25:41.393  6558  6558 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:41.393  6558  6558 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:41.393   774  1742 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,09-13 12:25:41.393  6324  6451 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 12:25:41.393  6324  6324 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 12:25:41.403   774  1726 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b021668 6558:com.samsung.helphub/1000}
,09-13 12:25:41.403   774  1646 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,09-13 12:25:41.403  6558  6558 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,09-13 12:25:41.423  6558  6558 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,09-13 12:25:41.443  6527  6527 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,09-13 12:25:41.443  6527  6527 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,09-13 12:25:41.443  6527  6527 D DialogFlow: initQueue()
,09-13 12:25:41.463  6570  6570 E Zygote  : v2
09-13 12:25:41.463  6570  6570 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:41.463  6570  6570 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:41.463   774  1612 I ActivityManager: Start proc 6570:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,09-13 12:25:41.463  6570  6570 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:41.463  6570  6570 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:25:41.473   774  1612 I ActivityManager: Killing 5277:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,09-13 12:25:41.473  6570  6570 E Zygote  : accessInfo : 0
,09-13 12:25:41.493  6570  6570 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:41.493  6570  6570 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:41.493   774  1726 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,09-13 12:25:41.503   774  2422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e838b03 6570:com.samsung.android.app.mirrorlink/1000}
,09-13 12:25:41.513  6570  6570 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,09-13 12:25:41.523  6570  6570 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,09-13 12:25:41.553  6570  6570 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,09-13 12:25:41.553  6570  6570 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,09-13 12:25:41.553   774  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3bf4b8e 5681:com.google.android.apps.plus/u0a134}
,09-13 12:25:41.573   774   787 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3bf4b8e 5681:com.google.android.apps.plus/u0a134}
,09-13 12:25:41.583   774  3741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3bf4b8e 5681:com.google.android.apps.plus/u0a134}
,09-13 12:25:41.623   774   788 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,09-13 12:25:41.633   774  2422 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,09-13 12:25:41.633   774  1415 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,09-13 12:25:41.633   774  3741 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,09-13 12:25:41.633   774  1717 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,09-13 12:25:41.643   774  1725 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,09-13 12:25:41.643   774  2439 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,09-13 12:25:41.653   774   788 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,09-13 12:25:41.653   774  1367 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,09-13 12:25:41.663  6584  6584 E Zygote  : v2
09-13 12:25:41.663  6584  6584 I libpersona: KNOX_SDCARD checking this for 10165
09-13 12:25:41.663  6584  6584 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:41.663   774  1612 I ActivityManager: Start proc 6584:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,09-13 12:25:41.663  6584  6584 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:41.663  6584  6584 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:25:41.663  6584  6584 E Zygote  : accessInfo : 0
,09-13 12:25:41.663  6584  6584 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,09-13 12:25:41.663   774  3741 I ActivityManager: Killing 5544:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,09-13 12:25:41.683  6584  6584 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:41.683  6584  6584 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:41.693   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{492a4fe 6584:com.sec.kidsplat.installer/u0a165}
,09-13 12:25:41.703   774   787 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,09-13 12:25:41.703  6584  6584 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,09-13 12:25:41.713  6584  6584 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,09-13 12:25:41.723   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{492a4fe 6584:com.sec.kidsplat.installer/u0a165}
,09-13 12:25:41.723  6584  6584 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,09-13 12:25:41.733  6596  6596 E Zygote  : v2
,09-13 12:25:41.733  6596  6596 I libpersona: KNOX_SDCARD checking this for 10142
09-13 12:25:41.733  6596  6596 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:41.733  6596  6596 E Zygote  : isSdpEnabledProcess - SDP enabled
,09-13 12:25:41.733  6596  6596 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:25:41.733  6596  6596 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:25:41.733  6596  6596 E Zygote  : accessInfo : 64
,09-13 12:25:41.733  6596  6596 E Zygote  : isSdpEnabledProcess - SDP enabled
09-13 12:25:41.733  6596  6596 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,09-13 12:25:41.743  6596  6596 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,09-13 12:25:41.743   774  1320 I ActivityManager: Start proc 6596:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,09-13 12:25:41.743   774  1320 I ActivityManager: Killing 5524:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,09-13 12:25:41.753   774  1612 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,09-13 12:25:41.773  6596  6596 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:41.773  6596  6596 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:41.783   774  3741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b29d45f 6596:com.sec.android.app.sbrowser/u0a142}
,09-13 12:25:41.793  6596  6596 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,09-13 12:25:41.803  6596  6596 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,09-13 12:25:41.813  6596  6596 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,09-13 12:25:41.823  6596  6596 D ManifestProvider: onCreate()
,09-13 12:25:41.833  6596  6596 I SBrowserUtils: getSystemProperty of sales_code : XEO
,09-13 12:25:41.833  6596  6596 I SBrowserUtils: getSystemProperty of country_code : Poland
09-13 12:25:41.833  6596  6596 I SBrowserUtils: getSystemProperty of country_code : Poland
09-13 12:25:41.833  6596  6596 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,09-13 12:25:41.843  6596  6596 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,09-13 12:25:41.843  6596  6596 D [MM]MHDataBaseProvider: onCreate()
,09-13 12:25:41.853  6596  6596 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@c21d55e)
,09-13 12:25:41.893   774  1742 I ActivityManager: Killing 5668:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,09-13 12:25:41.903   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{705b1c8 2043:com.google.android.gms.persistent/u0a11}
,09-13 12:25:41.913  2800  6611 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 12:25:41.913   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a87831 2800:com.google.android.gms/u0a11}
,09-13 12:25:41.923  2800  6610 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,09-13 12:25:41.923  2800  6611 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 12:25:41.923   774  1725 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,09-13 12:25:41.933  2800  2800 D AsyncTaskServiceImpl: Submit a task: nzm
,09-13 12:25:41.943  2800  4982 D nzm     : Processing package: com.test.thalitest
,09-13 12:25:41.953   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{705b1c8 2043:com.google.android.gms.persistent/u0a11}
,09-13 12:25:41.953  2800  6611 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 12:25:41.963  2800  6611 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 12:25:41.973   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a87831 2800:com.google.android.gms/u0a11}
,09-13 12:25:41.973  2800  2800 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,09-13 12:25:41.983  2800  4982 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-13 12:25:41.983  2800  4982 D nzm     : Found info for package com.test.thalitest in db.
,09-13 12:25:42.043  6411  6411 I Mms/MmsApp:  start initViewCache mms
,09-13 12:25:42.053   774  2422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41cb3f6 6065:com.sec.android.app.samsungapps/u0a39}
,09-13 12:25:42.063   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9655c38 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73e9c0f 4804:com.android.vending/u0a29}
,09-13 12:25:42.123   774  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{496934f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f2364e 5710:com.sec.android.app.shealth/u0a34}
,09-13 12:25:42.133  4804  4804 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,09-13 12:25:42.143  2043  2043 D WearableService: callingUid 10011, callindPid: 2043
,09-13 12:25:42.143  4804  4804 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,09-13 12:25:42.153   774  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{496934f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bffcba0 1882:com.sec.android.app.shealth:remote/u0a34}
,09-13 12:25:42.153  4804  4804 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-13 12:25:42.153  4804  4804 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-13 12:25:42.203   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{496934f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bffcba0 1882:com.sec.android.app.shealth:remote/u0a34}
,09-13 12:25:42.213   774  3741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d53156b u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{705b1c8 2043:com.google.android.gms.persistent/u0a11}
,09-13 12:25:42.323  6527  6557 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
09-13 12:25:42.323  6527  6557 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,09-13 12:25:42.333  6411  6411 D Mms/BubbleViewCache: fillCache bubble = 4
,09-13 12:25:42.343  6527  6557 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
09-13 12:25:42.343  6527  6557 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
09-13 12:25:42.343  6527  6557 I System.out: INFO:Resource not found:/Common.properties Using default values
,09-13 12:25:42.353  6527  6557 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
09-13 12:25:42.353  6527  6557 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,09-13 12:25:43.133  2800  5030 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,09-13 12:25:43.183  2800  5030 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,09-13 12:25:43.193  2800  5030 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,09-13 12:25:43.203  2800  5030 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,09-13 12:25:44.033   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:25:45.093   774  3409 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:25:45.413  3465  3465 D FactoryTest: User mode
,09-13 12:25:45.413  3465  3465 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-13 12:25:45.413  3465  3465 D MTPRx   : still no open session command from host, so toast
,09-13 12:25:45.413   774   787 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,09-13 12:25:45.423   774   787 D ActivityManager: mDVFSHelper.acquire()
,09-13 12:25:45.423   774   787 V WindowManager: addAppToken: AppWindowToken{bbbe086 token=Token{9883d61 ActivityRecord{8a8e8c8 u0 com.samsung.android.MtpApplication/.USBConnection t169}}} to stack=1 task=169 at 0
,09-13 12:25:45.423   774   787 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,09-13 12:25:45.433   774   849 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-13 12:25:45.443   774   787 D InputDispatcher: Focused application set to: xxxx
,09-13 12:25:45.443   774   787 D InputDispatcher: Focus left window: 6324
,09-13 12:25:45.453   774   901 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:774 uid:1000
09-13 12:25:45.453   774   901 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 12:25:45.453   774   901 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:774 uid:1000
09-13 12:25:45.453   774   901 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
09-13 12:25:45.453  3465  3465 E MTPRx   : started activity for popup
,09-13 12:25:45.453  3465  3465 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,09-13 12:25:45.463  3465  3465 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,09-13 12:25:45.473  3465  3465 D MTPUSBConnection: onCreate in USBConnection
09-13 12:25:45.473  3465  3465 V MTPUSBConnection: Registering broadcast receiver.
,09-13 12:25:45.473  3465  3465 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,09-13 12:25:45.473   774  1320 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,09-13 12:25:45.483   774  3409 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:25:45.523  3465  3465 D TAG     : dev.kiessupport is : TRUE
,09-13 12:25:45.553  3465  3465 D SecWifiDisplayUtil: Metadata value : none
,09-13 12:25:45.553  3465  3465 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1f161e2 V.E...... R.....I. 0,0-0,0}
,09-13 12:25:45.553  3465  6643 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 12:25:45.563   774  2422 D ISSUE_DEBUG: InputChannelName : 6987a5e com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,09-13 12:25:45.563   774  2422 D InputDispatcher: Focus entered window: 3465
,09-13 12:25:45.563   774   854 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6987a5e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-13 12:25:45.563  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
09-13 12:25:45.563   774   901 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:774 uid:1000
09-13 12:25:45.563   774   901 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 12:25:45.563   774   901 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:774 uid:1000
09-13 12:25:45.563   774   901 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,09-13 12:25:45.573  3465  3465 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f994b3a I.E...... R.....I. 0,0-0,0}
,09-13 12:25:45.573   774  3741 D ISSUE_DEBUG: InputChannelName : d7ed30c com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,09-13 12:25:45.573   774  2422 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-13 12:25:45.573   774  2422 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 12:25:45.573   774   774 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 12:25:45.573   774   774 I KnoxTimeoutHandler: Shared devices show user statefalse
09-13 12:25:45.573   774   774 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-13 12:25:45.613   293   293 I SurfaceFlinger: id=18 createSurf (145x145),1 flag=4, VSBConnecti
,09-13 12:25:45.623  3465  6643 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 12:25:45.623  3465  6643 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 12:25:45.623  3465  6643 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 12:25:45.623  3465  6643 I Adreno-EGL: Local Branch: ss
09-13 12:25:45.623  3465  6643 I Adreno-EGL: Remote Branch: 
09-13 12:25:45.623  3465  6643 I Adreno-EGL: Local Patches: 
09-13 12:25:45.623  3465  6643 I Adreno-EGL: Reconstruct Branch: 
,09-13 12:25:45.623  3465  6643 D libEGL  : eglInitialize EGLDisplay = 0x9f0927c4
,09-13 12:25:45.623  3465  6643 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 12:25:45.663   293   293 I SurfaceFlinger: id=19 createSurf (193x193),1 flag=4, VSBConnecti
,09-13 12:25:45.683  3465  3465 V ActivityThread: updateVisibility : ActivityRecord{cf6efe1 token=android.os.BinderProxy@665b973 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-13 12:25:45.693  3465  3465 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-13 12:25:45.803   774  1612 V WindowStateAnimator: Finishing drawing window Window{6987a5e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-13 12:25:45.803  3465  3465 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-13 12:25:45.803   774  2439 V WindowStateAnimator: Finishing drawing window Window{d7ed30c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-13 12:25:45.803  3465  3465 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 12:25:45.803  3465  3465 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-13 12:25:45.813   774   787 V WindowStateAnimator: Finishing drawing window Window{6987a5e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,09-13 12:25:45.813   774   788 V WindowStateAnimator: Finishing drawing window Window{d7ed30c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
09-13 12:25:45.813  3465  3465 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@665b973 time:107534
,09-13 12:25:45.813   774   901 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 12:25:45.813   774   774 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 12:25:45.813   774   901 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +372ms (total +392ms)
09-13 12:25:45.813   774   774 I KnoxTimeoutHandler: SD activityfalse
09-13 12:25:45.813   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef3d364
09-13 12:25:45.813   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef3d364
,09-13 12:25:45.823   774   901 D ActivityManager: mDVFSHelper.release()
09-13 12:25:45.823   774   901 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8a8e8c8 u0 com.samsung.android.MtpApplication/.USBConnection t169} time:107542
,09-13 12:25:45.833   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef3d364
,09-13 12:25:46.453   774  3410 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,09-13 12:25:46.583  1456  1456 D Recents : onTaskStackChanged
,09-13 12:25:46.583  1456  1456 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,09-13 12:25:47.343   774  1236 V AlarmManager: Expired Alarm result :4
,09-13 12:25:47.363   774  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,09-13 12:25:47.363   774  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,09-13 12:25:47.373   774  2439 V AlarmManager:  remove PendingIntent] PendingIntent{d6dde6a: PendingIntentRecord{42f472f com.google.android.gms broadcastIntent}}
,09-13 12:25:47.403   774  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:25:47.403   774  1742 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4313, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
09-13 12:25:47.403   774  1742 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 12:25:47.403   774  1742 D BatteryService: stay LED for charging
,09-13 12:25:47.403   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:25:47.403   774   774 I MotionRecognitionService: Plugged
,09-13 12:25:47.403   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:25:47.403   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:25:47.403   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:25:47.403  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:25:47.403  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:25:47.403  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:25:47.413  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 12:25:47.413  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:25:47.423  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:25:47.423  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:25:47.433  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:25:47.503   774  3409 D SSRM:n  : SIOP:: AP = 480, PST = 455, CUR = 300, LCD = 0
,09-13 12:25:48.653   774   924 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-13 12:25:48.673   774   924 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-13 12:25:49.033   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:25:49.183   774   924 D PackageManager: [MSG] MCS_UNBIND
,09-13 12:25:49.193   774  1415 I ActivityManager: Killing 5293:com.policydm/1000 (adj 15): DHA:empty #37
,09-13 12:25:49.203   774  1415 I ActivityManager: Killing 4744:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,09-13 12:25:49.253   774   787 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,09-13 12:25:49.263  6342  6342 D AASAservice: onDestroy()
,09-13 12:25:49.263  6342  6342 I art     : System.exit called, status: 80
09-13 12:25:49.263  6342  6342 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,09-13 12:25:49.273   774  2422 I ActivityManager: Process com.samsung.aasaservice (pid 6342)(adj 0) has died(85,719)
,09-13 12:25:49.273   774  2422 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,09-13 12:25:49.283   774   788 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,09-13 12:25:49.303   355   355 I Zygote  : Process 6342 exited cleanly (80)
,09-13 12:25:51.523   774  3409 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:25:53.453   774   849 I ActivityManager: Waited long enough for: ServiceRecord{d3b91a6 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,09-13 12:25:56.423  6324  6466 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 12:25:56.423  6324  6466 I jxcore-log: 
,09-13 12:25:56.423  6324  6466 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 12:25:56.423  6324  6466 I jxcore-log: 
,09-13 12:25:56.433  6324  6466 D BluetoothAdapter: STATE_ON
,09-13 12:25:56.433  6324  6466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:56.433  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:56.433  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:56.433  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:56.433  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:56.433  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:56.433  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:56.433  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:56.433  6324  6466 D BluetoothAdapter: STATE_ON
,09-13 12:25:56.433  6324  6466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:25:56.443  6324  6466 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 12:25:56.443  6324  6466 I jxcore-log: 
,09-13 12:25:56.443  6324  6466 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 12:25:56.443  6324  6466 I jxcore-log: 
,09-13 12:25:56.833  6324  6466 I jxcore-log: Running unit tests
09-13 12:25:56.833  6324  6466 I jxcore-log: 
,09-13 12:25:56.833  6324  6466 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:25:56.833  6324  6466 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cd2fa2 added. We now have 2 listener(s)
,09-13 12:25:56.833  6324  6466 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 12:25:56.833  6324  6466 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:25:56.833  6324  6466 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:25:56.833  6324  6466 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:25:56.833  6324  6466 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92cd433 added. We now have 2 listener(s)
09-13 12:25:56.833  6324  6466 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:25:56.833  6324  6466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 12:25:56.843  6324  6466 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:25:56.843  6324  6466 D BluetoothAdapter: STATE_ON
,09-13 12:25:56.843  6324  6466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:56.843  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:56.843  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:56.843  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:56.843  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:56.843  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:56.843  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:56.843  6324  6466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:56.843  6324  6466 D BluetoothAdapter: STATE_ON
,09-13 12:25:56.843  6324  6466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:25:56.853  6324  6466 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:25:56.853  6324  6466 D executeNativeTests: Running unit tests
,09-13 12:25:56.853  6324  6324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:56.853  6324  6324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:56.883  6324  6466 I jxcore-log: Total number of executed tests:  1
09-13 12:25:56.883  6324  6466 I jxcore-log: 
,09-13 12:25:56.883  6324  6466 I jxcore-log: Number of passed tests:  1
09-13 12:25:56.883  6324  6466 I jxcore-log: 
09-13 12:25:56.883  6324  6466 I jxcore-log: Number of failed tests:  0
09-13 12:25:56.883  6324  6466 I jxcore-log: 
09-13 12:25:56.883  6324  6466 I jxcore-log: Number of ignored tests:  0
09-13 12:25:56.883  6324  6466 I jxcore-log: 
,09-13 12:25:56.883  6324  6466 I jxcore-log: Total duration:  3
09-13 12:25:56.883  6324  6466 I jxcore-log: 
,09-13 12:25:56.883  6324  6466 I jxcore-log: Unit Test app is loaded
09-13 12:25:56.883  6324  6466 I jxcore-log: 
,09-13 12:25:56.893  6324  6466 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:25:56.893  6324  6466 I jxcore-log: 
,09-13 12:25:56.893  6324  6324 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 12:25:56.893  6324  6466 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:25:56.893  6324  6466 I jxcore-log: 
,09-13 12:25:56.893  6324  6466 I jxcore-log: My device name is: samsung-SM-G900F
09-13 12:25:56.893  6324  6466 I jxcore-log: 
,09-13 12:25:56.903  6324  6466 I jxcore-log: Running for WIFI network type
09-13 12:25:56.903  6324  6466 I jxcore-log: 
,09-13 12:25:57.403   774  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
09-13 12:25:57.403   774  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,09-13 12:25:57.553   774  3409 D SSRM:n  : SIOP:: AP = 450, PST = 454, CUR = 300, LCD = 0
,09-13 12:25:59.263   774  1568 E Watchdog: !@Sync 3 [09-13 12:25:59.267]
,09-13 12:25:59.523  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-13 12:25:59.523  6324  6466 I jxcore-log: 
,09-13 12:25:59.993   774  1236 V AlarmManager: Expired Alarm result :8
,09-13 12:26:00.033  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-13 12:26:00.033  6324  6466 I jxcore-log: 
,09-13 12:26:00.063  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-13 12:26:00.063  6324  6466 I jxcore-log: 
,09-13 12:26:01.573  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-13 12:26:01.573  6324  6466 I jxcore-log: 
,09-13 12:26:01.843  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-13 12:26:01.843  6324  6466 I jxcore-log: 
,09-13 12:26:01.843  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-13 12:26:01.843  6324  6466 I jxcore-log: 
,09-13 12:26:01.853  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-13 12:26:01.853  6324  6466 I jxcore-log: 
,09-13 12:26:01.943  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-13 12:26:01.943  6324  6466 I jxcore-log: 
,09-13 12:26:02.153  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-13 12:26:02.153  6324  6466 I jxcore-log: 
,09-13 12:26:02.153  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-13 12:26:02.153  6324  6466 I jxcore-log: 
,09-13 12:26:02.273   774  1236 V AlarmManager: Expired Alarm result :4
,09-13 12:26:02.313   774   849 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{77b2ed3 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{705b1c8 2043:com.google.android.gms.persistent/u0a11}
,09-13 12:26:02.323  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-13 12:26:02.323  1381  1381 I PERF    : received broadcast android.intent.action.TIME_TICK
09-13 12:26:02.323  1381  1381 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:26:02.323   774  1725 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:26:02.323   774  1725 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
09-13 12:26:02.323   774  1725 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:26:02.333   774  1725 D BatteryService: stay LED for charging
,09-13 12:26:02.343   774  2439 V AlarmManager:  remove PendingIntent] PendingIntent{1e96a10: PendingIntentRecord{470c959 com.google.android.gms broadcastIntent}}
,09-13 12:26:02.343   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:26:02.343   774   774 I MotionRecognitionService: Plugged
,09-13 12:26:02.343   774   774 D MotionRecognitionService:   cableConnection= 1
09-13 12:26:02.343   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:26:02.343   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:26:02.353  1381  1381 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 12:26:02.353  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:26:02.353  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:26:02.353  1381  1381 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 12:26:02.363  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:26:02.363  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:26:02.373  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:26:02.373  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
09-13 12:26:02.373  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:26:02.373  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:26:02.373  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:26:02.373  4804  4886 I Finsky  : [672] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,09-13 12:26:02.373  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:26:02.373  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:02.373  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 12:26:02.373  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:02.373  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 12:26:02.373  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:26:02.443  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:26:02.493   774  3741 V AlarmManager:  remove PendingIntent] PendingIntent{486370e: PendingIntentRecord{470c959 com.google.android.gms broadcastIntent}}
,09-13 12:26:02.523   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:26:02.523   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:26:02.523   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:26:02.563  2800  6694 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-13 12:26:02.563  2800  6694 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-13 12:26:02.593  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:26:02.593   774  1415 V AlarmManager:  remove PendingIntent] PendingIntent{90c0041: PendingIntentRecord{470c959 com.google.android.gms broadcastIntent}}
,09-13 12:26:02.613   774   849 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{57619e6 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{705b1c8 2043:com.google.android.gms.persistent/u0a11}
,09-13 12:26:02.643   774  1501 V AlarmManager:  remove PendingIntent] PendingIntent{d114b27: PendingIntentRecord{470c959 com.google.android.gms broadcastIntent}}
,09-13 12:26:02.683   774  2422 V AlarmManager:  remove PendingIntent] PendingIntent{c6d11d4: PendingIntentRecord{470c959 com.google.android.gms broadcastIntent}}
,09-13 12:26:02.823  4804  4886 I Finsky  : [672] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,09-13 12:26:02.833  4804  4804 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,09-13 12:26:02.883   774   784 I art     : Background partial concurrent mark sweep GC freed 43714(2MB) AllocSpace objects, 17(340KB) LOS objects, 27% free, 42MB/58MB, paused 1.743ms total 119.473ms
,09-13 12:26:02.903  6699  6699 E Zygote  : v2
09-13 12:26:02.903  6699  6699 I libpersona: KNOX_SDCARD checking this for 10011
09-13 12:26:02.903  6699  6699 I libpersona: KNOX_SDCARD not a persona
,09-13 12:26:02.903   774   787 I ActivityManager: Start proc 6699:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
09-13 12:26:02.903  6699  6699 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:26:02.903  6699  6699 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:26:02.903  6699  6699 E Zygote  : accessInfo : 0
,09-13 12:26:02.903  6699  6699 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,09-13 12:26:02.923  6699  6699 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:26:02.923  6699  6699 D ActivityThread: Added TimaKeyStore provider
,09-13 12:26:02.943  6699  6699 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,09-13 12:26:02.973  6699  6699 I MultiDex: VM with version 2.1.0 has multidex support
,09-13 12:26:02.973  6699  6699 I MultiDex: install
09-13 12:26:02.973  6699  6699 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 12:26:02.993  6699  6699 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,09-13 12:26:03.003  6699  6699 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,09-13 12:26:03.013  6699  6699 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,09-13 12:26:03.013  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-13 12:26:03.013  6324  6466 I jxcore-log: 
,09-13 12:26:03.013  6699  6699 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 12:26:03.043  6699  6699 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 12:26:03.053  6699  6699 D ChimeraCfgMgr: Reading stored module config
,09-13 12:26:03.143   334   970 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6699)
,09-13 12:26:03.143  6699  6713 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-13 12:26:03.223  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-13 12:26:03.223  6324  6466 I jxcore-log: 
,09-13 12:26:03.223   334   970 D WVCdm   : Instantiating CDM.
,09-13 12:26:03.223   334   978 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6699)
09-13 12:26:03.223   334   978 I WVCdm   : CdmEngine::OpenSession
09-13 12:26:03.223   334   978 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-13 12:26:03.233   334   978 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-13 12:26:03.233  6699  6710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:03.233  6699  6710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:03.243   334   978 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
09-13 12:26:03.243   334   978 D DrmWidevineDash: Service_Initialize: starts!
09-13 12:26:03.243   334   978 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-13 12:26:03.243   334   978 D QSEECOMAPI: : App is not loaded in QSEE
09-13 12:26:03.243   334   978 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-13 12:26:03.243   334   978 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-13 12:26:03.243   334   978 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-13 12:26:03.243   334   978 D QSEECOMAPI: : App is not loaded in QSEE
09-13 12:26:03.243   334   978 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-13 12:26:03.243   334   978 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-13 12:26:03.243   334   978 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-13 12:26:03.243   334   978 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 12:26:03.243   319  1104 D EnterpriseController: netId is 0
09-13 12:26:03.243   319  1104 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 12:26:03.243   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:26:03.243   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:26:03.243   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:26:03.263   334   978 D QSEECOMAPI: : Loaded image: APP id = 3
,09-13 12:26:03.263   334   978 D DrmWidevineDash: Service_Initialize: ends! returns 0
09-13 12:26:03.263   334   978 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef56000
09-13 12:26:03.263   334   978 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef56000
,09-13 12:26:03.273  2043  2043 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=de4db6b8-2c4f-48aa-ac43-cf27f29f39f3
,09-13 12:26:03.273  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:26:03.273  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:26:03.283   334   978 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-13 12:26:03.283   334   978 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-13 12:26:03.283   334   978 D DrmWidevineDash: hlos api version =  10
09-13 12:26:03.283   334   978 D DrmWidevineDash: tz api version =  10
,09-13 12:26:03.283   334   978 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-13 12:26:03.283   334   978 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-13 12:26:03.293  6699  6710 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6699, getuid(): 10011
,09-13 12:26:03.303   334   978 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-13 12:26:03.303   334   978 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-13 12:26:03.303   334   978 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf07e924
09-13 12:26:03.303   334   978 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-13 12:26:03.303   334   978 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-13 12:26:03.303   334   978 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1e1d828, dataLength=8
,09-13 12:26:03.303   334   978 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-13 12:26:03.323   334   978 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1d8d800, wrapped_rsa_key_length=1280
,09-13 12:26:03.323   334   978 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,09-13 12:26:03.323   334   978 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-13 12:26:03.323   334   970 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-13 12:26:03.323   334   970 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-13 12:26:03.323   334   970 I WVCdm   : CdmEngine::GenerateKeyRequest
09-13 12:26:03.323   334   970 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xae58ade0, idLength=0xaf180f2c
,09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-13 12:26:03.343   334   970 D DrmWidevineDash: hlos api version =  10
09-13 12:26:03.343   334   970 D DrmWidevineDash: tz api version =  10
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-13 12:26:03.343   334   970 D WVCdm   : PrepareKeyRequest: nonce=3729865822
09-13 12:26:03.343   334   970 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xae54f400
09-13 12:26:03.343   334   970 D DrmWidevineDash: message_length=1631, signature=0xae225c80, signature_length=2937589764
,09-13 12:26:03.423   334   970 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-13 12:26:03.433   334   334 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6699)
09-13 12:26:03.433   334   334 I WVCdm   : CdmEngine::CloseSession
09-13 12:26:03.433   334   334 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,09-13 12:26:03.433   334   334 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-13 12:26:03.433   334   334 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-13 12:26:03.433   334   334 D DrmWidevineDash: Service_Uninitialize: starts!
09-13 12:26:03.433   334   334 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-13 12:26:03.433   334   334 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
09-13 12:26:03.433   334   334 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-13 12:26:03.433   334   334 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-13 12:26:03.453  2043  2214 W GCoreFlp: No location to return for getLastLocation()
,09-13 12:26:03.463  6699  6710 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6699, getuid(): 10011
,09-13 12:26:03.503  2800  6695 D UdcContextInitService: registered all accounts: true
,09-13 12:26:03.513  2043  2260 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 12:26:03.533  2043  2575 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-13 12:26:03.643  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-13 12:26:03.643  6324  6466 I jxcore-log: 
,09-13 12:26:03.653  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-13 12:26:03.653  6324  6466 I jxcore-log: 
,09-13 12:26:03.653  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-13 12:26:03.653  6324  6466 I jxcore-log: 
,09-13 12:26:03.663  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-13 12:26:03.663  6324  6466 I jxcore-log: 
,09-13 12:26:03.673  6699  6710 I qtaguid : Untagging socket 21
,09-13 12:26:03.703  6699  6710 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
09-13 12:26:03.703  6699  6710 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,09-13 12:26:03.713  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-13 12:26:03.713  6324  6466 I jxcore-log: 
,09-13 12:26:03.763  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-13 12:26:03.763  6324  6466 I jxcore-log: 
,09-13 12:26:03.763  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-13 12:26:03.763  6324  6466 I jxcore-log: 
,09-13 12:26:03.773  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-13 12:26:03.773  6324  6466 I jxcore-log: 
,09-13 12:26:03.793  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-13 12:26:03.793  6324  6466 I jxcore-log: 
,09-13 12:26:03.803  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-13 12:26:03.803  6324  6466 I jxcore-log: 
,09-13 12:26:03.803  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-13 12:26:03.803  6324  6466 I jxcore-log: 
,09-13 12:26:03.823  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-13 12:26:03.823  6324  6466 I jxcore-log: 
,09-13 12:26:03.853  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-13 12:26:03.853  6324  6466 I jxcore-log: 
,09-13 12:26:03.863  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-13 12:26:03.863  6324  6466 I jxcore-log: 
,09-13 12:26:03.873  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-13 12:26:03.873  6324  6466 I jxcore-log: 
,09-13 12:26:03.893  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-13 12:26:03.893  6324  6466 I jxcore-log: 
,09-13 12:26:03.903  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-13 12:26:03.903  6324  6466 I jxcore-log: 
,09-13 12:26:03.913  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-13 12:26:03.913  6324  6466 I jxcore-log: 
,09-13 12:26:03.923  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-13 12:26:03.923  6324  6466 I jxcore-log: 
,09-13 12:26:03.953  6324  6466 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-13 12:26:03.953  6324  6466 I jxcore-log: 
,09-13 12:26:03.983  6324  6466 D BluetoothAdapter: STATE_ON
,09-13 12:26:03.983  6324  6466 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-13 12:26:03.983  6324  6466 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-13 12:26:03.983  6324  6466 I jxcore-log: 
,09-13 12:26:03.993  6324  6466 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-13 12:26:03.993  6324  6466 I jxcore-log: 
,09-13 12:26:03.993  6324  6466 I jxcore-log: ThaliTape :: Started ThaliTape
09-13 12:26:03.993  6324  6466 I jxcore-log: 
,09-13 12:26:03.993  6324  6466 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-13 12:26:03.993  6324  6466 I jxcore-log: 
,09-13 12:26:04.053  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:04.053  6324  6466 I jxcore-log: 
09-13 12:26:04.053  6324  6466 I jxcore-log: websocket error
09-13 12:26:04.053  6324  6466 I jxcore-log: 
09-13 12:26:04.053  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:04.053  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:04.053  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:04.053  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:04.053  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:04.053  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:04.053  6324  6466 I jxcore-log: 
,09-13 12:26:04.143  6731  6731 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,09-13 12:26:04.243  6731  6731 I dex2oat : ----------------------------------------------------
09-13 12:26:04.243  6731  6731 I dex2oat : <SS>: S T A R T I N G . . .
09-13 12:26:04.243  6731  6731 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
09-13 12:26:04.243  6731  6731 I dex2oat : dex2oat took 95.401ms (threads: 4) arena alloc=103KB java alloc=43KB native alloc=1666KB free=1661KB
,09-13 12:26:04.243  6699  6710 W System  : ClassLoader referenced unknown path: 
,09-13 12:26:04.253  6699  6710 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,09-13 12:26:04.253  6699  6710 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 12:26:04.253  6699  6710 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 12:26:04.253  6699  6710 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 12:26:04.253  6699  6710 I Adreno-EGL: Local Branch: ss
09-13 12:26:04.253  6699  6710 I Adreno-EGL: Remote Branch: 
09-13 12:26:04.253  6699  6710 I Adreno-EGL: Local Patches: 
09-13 12:26:04.253  6699  6710 I Adreno-EGL: Reconstruct Branch: 
,09-13 12:26:04.253  6699  6710 D libEGL  : eglInitialize EGLDisplay = 0xb2f4e174
,09-13 12:26:04.323  6699  6710 D libEGL  : eglTerminate EGLDisplay = 0xb2f4e1cc
,09-13 12:26:04.323  6699  6710 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 12:26:04.323  6699  6710 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 12:26:04.323  6699  6710 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 12:26:04.323  6699  6710 I Adreno-EGL: Local Branch: ss
09-13 12:26:04.323  6699  6710 I Adreno-EGL: Remote Branch: 
09-13 12:26:04.323  6699  6710 I Adreno-EGL: Local Patches: 
09-13 12:26:04.323  6699  6710 I Adreno-EGL: Reconstruct Branch: 
09-13 12:26:04.323  6699  6710 D libEGL  : eglInitialize EGLDisplay = 0xb2f4e174
,09-13 12:26:04.363  6699  6710 D libEGL  : eglTerminate EGLDisplay = 0xb2f4e1cc
,09-13 12:26:04.523  6699  6710 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 12:26:04.523  6699  6710 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 12:26:04.523  6699  6710 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 12:26:04.523  6699  6710 I Adreno-EGL: Local Branch: ss
09-13 12:26:04.523  6699  6710 I Adreno-EGL: Remote Branch: 
09-13 12:26:04.523  6699  6710 I Adreno-EGL: Local Patches: 
09-13 12:26:04.523  6699  6710 I Adreno-EGL: Reconstruct Branch: 
,09-13 12:26:04.523  6699  6710 D libEGL  : eglInitialize EGLDisplay = 0xb2f4e174
,09-13 12:26:04.563  6699  6710 D libEGL  : eglTerminate EGLDisplay = 0xb2f4e1cc
,09-13 12:26:04.663  2043  6697 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:26:04.663  2043  6697 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:04.663   319  1104 D EnterpriseController: netId is 0
09-13 12:26:04.663   319  1104 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 12:26:04.663  2043  6697 I qtaguid : Tagging socket 47 with tag 1000040100000000{268436481,0} uid 10011, pid: 2043, getuid(): 10011
,09-13 12:26:04.703  2043  6697 I qtaguid : Tagging socket 50 with tag 1000040100000000{268436481,0} uid 10011, pid: 2043, getuid(): 10011
,09-13 12:26:04.933   774  1501 V AlarmManager:  remove PendingIntent] PendingIntent{34b1ca6: PendingIntentRecord{470c959 com.google.android.gms broadcastIntent}}
,09-13 12:26:04.933  2043  2575 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 12:26:04.933  2043  2575 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-13 12:26:04.943  2043  2575 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-13 12:26:03.597+0200, stopTime=2016-09-13 12:26:04.950+0200, duration=1353ms
,09-13 12:26:04.963  2043  6743 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:04.963  2043  6743 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:04.963   319  1104 D EnterpriseController: netId is 0
09-13 12:26:04.963   319  1104 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 12:26:04.963  2043  6743 I qtaguid : Tagging socket 52 with tag 1000310500000000{268448005,0} uid 10011, pid: 2043, getuid(): 10011
,09-13 12:26:05.013  2043  6743 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} uid 10011, pid: 2043, getuid(): 10011
,09-13 12:26:05.243  2043  6743 I qtaguid : Untagging socket 52
,09-13 12:26:05.253   774   788 V AlarmManager:  remove PendingIntent] PendingIntent{9f2b294: PendingIntentRecord{470c959 com.google.android.gms broadcastIntent}}
,09-13 12:26:05.313  2043  2575 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-13 12:26:05.433  2043  6757 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 12:26:05.433  2043  6755 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 12:26:05.453  2043  6757 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 12:26:05.453  2043  6755 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 12:26:05.463  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:05.463  6324  6466 I jxcore-log: 
09-13 12:26:05.463  6324  6466 I jxcore-log: websocket error
09-13 12:26:05.463  6324  6466 I jxcore-log: 
09-13 12:26:05.463  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:05.463  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:05.463  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:05.463  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:05.463  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:05.463  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:05.463  6324  6466 I jxcore-log: 
,09-13 12:26:05.463  2043  6757 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 12:26:05.463  2043  6755 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 12:26:05.463  2043  6755 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-13 12:26:05.473  2043  6755 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 12:26:05.523   774  1717 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:05.543  2043  6755 W Uploader: UNKNOWN no longer exists, so no auth token.
,09-13 12:26:05.573  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:05.573  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:05.573   319  1104 D EnterpriseController: netId is 0
09-13 12:26:05.573   319  1104 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 12:26:05.573  2043  6755 I qtaguid : Tagging socket 63 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2043, getuid(): 10011
,09-13 12:26:05.613  2043  6755 I qtaguid : Tagging socket 66 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2043, getuid(): 10011
,09-13 12:26:05.803   774  1501 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:05.813  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:05.813  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:26:05.813  2043  6755 I qtaguid : Tagging socket 63 with tag 11065c0800000000{285629448,0} uid -1, pid: 2043, getuid(): 10011
,09-13 12:26:05.923   774  1725 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:05.933  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:05.933  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:26:05.933  2043  6755 I qtaguid : Tagging socket 63 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2043, getuid(): 10011
,09-13 12:26:06.073   774  3741 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:06.083  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:06.083  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:26:06.083  2043  6755 I qtaguid : Tagging socket 63 with tag 11065fff00000000{285630463,0} uid -1, pid: 2043, getuid(): 10011
,09-13 12:26:06.223   774   788 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:06.233  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:06.233  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:06.233  2043  6755 I qtaguid : Tagging socket 63 with tag 11065c9100000000{285629585,0} uid -1, pid: 2043, getuid(): 10011
,09-13 12:26:06.403   774  1717 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:06.553  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:06.553  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:06.553  2043  6755 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} uid 10011, pid: 2043, getuid(): 10011
,09-13 12:26:06.593  2043  6755 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} uid 10011, pid: 2043, getuid(): 10011
,09-13 12:26:06.983  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:06.983  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:06.983  2043  6755 I qtaguid : Tagging socket 63 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2043, getuid(): 10011
,09-13 12:26:07.043  2043  6744 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:26:07.043  2043  6744 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:26:07.043  2043  6744 I qtaguid : Tagging socket 52 with tag 1000310200000000{268448002,0} uid 10011, pid: 2043, getuid(): 10011
,09-13 12:26:07.143   774   788 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:07.143  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:26:07.143  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:07.143  2043  6755 I qtaguid : Tagging socket 63 with tag 11065b5800000000{285629272,0} uid -1, pid: 2043, getuid(): 10011
,09-13 12:26:07.273   774  1717 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:26:07.293  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:26:07.293  2043  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:26:07.293  2043  6755 I qtaguid : Tagging socket 63 with tag fffffca200000000{4294966434,0} uid -1, pid: 2043, getuid(): 10011
,09-13 12:26:07.333  2043  6744 I qtaguid : Untagging socket 52
,09-13 12:26:07.353  2043  2575 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-13 12:26:07.503   774  2439 V AlarmManager:  remove PendingIntent] PendingIntent{4f4dbdf: PendingIntentRecord{470c959 com.google.android.gms broadcastIntent}}
,09-13 12:26:07.613   774  3409 D SSRM:n  : SIOP:: AP = 450, PST = 453, CUR = 300, LCD = 0
,09-13 12:26:08.333  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:08.333  6324  6466 I jxcore-log: 
,09-13 12:26:08.333  6324  6466 I jxcore-log: websocket error
09-13 12:26:08.333  6324  6466 I jxcore-log: 
,09-13 12:26:08.343  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:08.343  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:08.343  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:08.343  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:08.343  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:08.343  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:08.343  6324  6466 I jxcore-log: 
,09-13 12:26:09.043   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:26:10.783  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:10.783  6324  6466 I jxcore-log: 
,09-13 12:26:10.783  6324  6466 I jxcore-log: websocket error
09-13 12:26:10.783  6324  6466 I jxcore-log: 
,09-13 12:26:10.783  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:10.783  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:10.783  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:10.783  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:10.783  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:10.783  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:10.783  6324  6466 I jxcore-log: 
,09-13 12:26:12.423   774  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:26:12.423   774  1501 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4351, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:26:12.433   774  1501 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:26:12.443   774  1501 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
,09-13 12:26:12.443   774  1501 D BatteryService: stay LED for charging
,09-13 12:26:12.453   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:26:12.463   774   774 I MotionRecognitionService: Plugged
,09-13 12:26:12.463   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:26:12.473   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:26:12.473   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:26:12.483  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:12.483  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:12.483  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:26:12.503  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:26:12.503  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:26:12.513  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:12.513  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:12.513  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:15.853  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:15.853  6324  6466 I jxcore-log: 
,09-13 12:26:15.853  6324  6466 I jxcore-log: websocket error
09-13 12:26:15.853  6324  6466 I jxcore-log: 
,09-13 12:26:15.853  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:15.853  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:15.853  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:15.853  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:15.853  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:15.853  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:15.853  6324  6466 I jxcore-log: 
,09-13 12:26:17.673   774  3409 D SSRM:n  : SIOP:: AP = 410, PST = 445, CUR = 300, LCD = 0
,09-13 12:26:17.713   774  3409 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:26:20.953  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:20.953  6324  6466 I jxcore-log: 
,09-13 12:26:20.963  6324  6466 I jxcore-log: websocket error
09-13 12:26:20.963  6324  6466 I jxcore-log: 
,09-13 12:26:20.963  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:20.963  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:20.963  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:20.963  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:20.963  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:20.963  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:20.963  6324  6466 I jxcore-log: 
,09-13 12:26:22.503   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:26:22.513   774   787 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4376, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:26:22.513   774   787 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:26:22.513   774   787 D BatteryService: stay LED for charging
,09-13 12:26:22.523   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:26:22.533  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:22.533  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:22.533  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:26:22.543   774   774 I MotionRecognitionService: Plugged
,09-13 12:26:22.543   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:26:22.543   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:26:22.543   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:26:22.563  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:26:22.563  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:26:22.563  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:22.573  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:22.573  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:26.033  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:26.033  6324  6466 I jxcore-log: 
,09-13 12:26:26.033  6324  6466 I jxcore-log: websocket error
09-13 12:26:26.033  6324  6466 I jxcore-log: 
,09-13 12:26:26.043  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:26.043  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:26.043  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:26.043  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:26.043  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:26.043  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:26.043  6324  6466 I jxcore-log: 
,09-13 12:26:27.793   774  3409 D SSRM:n  : SIOP:: AP = 390, PST = 437, CUR = 300, LCD = 0
,09-13 12:26:29.043   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:26:29.263   774  1568 E Watchdog: !@Sync 4 [09-13 12:26:29.270]
,09-13 12:26:30.743  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:26:31.123  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:31.123  6324  6466 I jxcore-log: 
,09-13 12:26:31.133  6324  6466 I jxcore-log: websocket error
09-13 12:26:31.133  6324  6466 I jxcore-log: 
,09-13 12:26:31.133  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:31.133  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:31.133  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:31.133  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:31.133  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:31.133  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:31.133  6324  6466 I jxcore-log: 
,09-13 12:26:32.583   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:26:32.583   774   787 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4383, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:26:32.583   774   787 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:26:32.593   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:26:32.603   774   774 I MotionRecognitionService: Plugged
,09-13 12:26:32.603   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:26:32.613   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:26:32.613   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:26:32.623   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,09-13 12:26:32.623   774   787 D BatteryService: stay LED for charging
,09-13 12:26:32.633  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:32.633  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:32.633  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:26:32.643  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:26:32.643  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:26:32.653  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:32.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:32.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:36.203  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error,
09-13 12:26:36.203  6324  6466 I jxcore-log: 
,09-13 12:26:36.213  6324  6466 I jxcore-log: websocket error
09-13 12:26:36.213  6324  6466 I jxcore-log: 
,09-13 12:26:36.213  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:36.213  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:36.213  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:36.213  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:36.213  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:36.213  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:36.213  6324  6466 I jxcore-log: 
,09-13 12:26:37.853   774  3409 D SSRM:n  : SIOP:: AP = 360, PST = 430, CUR = 300, LCD = 0
,09-13 12:26:41.303  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:41.303  6324  6466 I jxcore-log: 
,09-13 12:26:41.313  6324  6466 I jxcore-log: websocket error
09-13 12:26:41.313  6324  6466 I jxcore-log: 
,09-13 12:26:41.313  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:41.313  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:41.313  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:41.313  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:41.313  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:41.313  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:41.313  6324  6466 I jxcore-log: 
,09-13 12:26:44.283   774  1236 V AlarmManager: Expired Alarm result :4
,09-13 12:26:44.363   774  1646 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:26:44.363   774  1646 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4373, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:26:44.363   774  1646 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 12:26:44.363   774  1646 D BatteryService: stay LED for charging
,09-13 12:26:44.363   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:26:44.373  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:44.373  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:44.373  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:26:44.383  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:26:44.383  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:26:44.403  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:44.403  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:44.403  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:44.423   774  1236 I ActivityManager: Start proc 6802:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,09-13 12:26:44.433   774   774 I MotionRecognitionService: Plugged
09-13 12:26:44.433   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:26:44.433   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:26:44.433   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:26:44.433  6802  6802 E Zygote  : v2
09-13 12:26:44.433  6802  6802 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:26:44.433  6802  6802 I libpersona: KNOX_SDCARD not a persona
,09-13 12:26:44.443  6802  6802 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:26:44.443  6802  6802 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:26:44.443  6802  6802 E Zygote  : accessInfo : 0
,09-13 12:26:44.473  6802  6802 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:26:44.473  6802  6802 D ActivityThread: Added TimaKeyStore provider
,09-13 12:26:44.483  6802  6802 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,09-13 12:26:44.503  6802  6802 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,09-13 12:26:44.533   774  2439 I ActivityManager: Killing 5790:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,09-13 12:26:44.553   774  1726 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,09-13 12:26:46.463  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:46.463  6324  6466 I jxcore-log: 
,09-13 12:26:46.463  6324  6466 I jxcore-log: websocket error
09-13 12:26:46.463  6324  6466 I jxcore-log: 
,09-13 12:26:46.463  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:46.463  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:46.463  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:46.463  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:46.463  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:46.463  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:46.463  6324  6466 I jxcore-log: 
,09-13 12:26:47.923   774  3409 D SSRM:n  : SIOP:: AP = 350, PST = 423, CUR = 300, LCD = 0
,09-13 12:26:47.923   774  3409 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,09-13 12:26:48.003  6841  6841 E Zygote  : v2
,09-13 12:26:48.003  6841  6841 I libpersona: KNOX_SDCARD checking this for 10053
,09-13 12:26:48.013  6841  6841 I libpersona: KNOX_SDCARD not a persona
,09-13 12:26:48.013  6841  6841 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:26:48.013  6841  6841 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:26:48.023   774   849 I ActivityManager: Start proc 6841:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,09-13 12:26:48.023  6841  6841 E Zygote  : accessInfo : 0
,09-13 12:26:48.023   774  1323 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-13 12:26:48.023  6841  6841 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,09-13 12:26:48.033   774  3409 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 12:26:48.073  6841  6841 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:26:48.073  6841  6841 D ActivityThread: Added TimaKeyStore provider
,09-13 12:26:48.083  2770  2770 D ContentApp:  LEVEL : 0
,09-13 12:26:48.113   774  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{618b318 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5c171 6841:com.sec.android.app.videoplayer/u0a53}
,09-13 12:26:48.113   774  1323 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,09-13 12:26:48.123  6841  6841 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,09-13 12:26:48.163  6841  6841 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,09-13 12:26:48.193  6841  6841 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,09-13 12:26:48.223  6841  6841 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,09-13 12:26:48.223  6841  6841 D videowall-Global: core_num = 4
,09-13 12:26:48.233  6841  6841 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
09-13 12:26:48.233  6841  6841 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,09-13 12:26:48.243  6841  6841 D TranscodeReceiver:  SIOP_LEVEL: 0
,09-13 12:26:48.243   774  1646 I ActivityManager: Killing 5903:com.google.android.apps.photos/u0a199 (adj 15): DHA:empty #37
,09-13 12:26:48.263   774  3741 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,09-13 12:26:49.053   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:26:51.523  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:51.523  6324  6466 I jxcore-log: 
,09-13 12:26:51.523  6324  6466 I jxcore-log: websocket error
09-13 12:26:51.523  6324  6466 I jxcore-log: 
,09-13 12:26:51.523  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:51.523  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:51.523  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:51.523  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:51.523  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:51.523  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:51.523  6324  6466 I jxcore-log: 
,09-13 12:26:54.373  2800  5020 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 12:26:54.453   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:26:54.463   774   787 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:26:54.463   774   787 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:26:54.463   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:26:54.483   774   774 I MotionRecognitionService: Plugged
,09-13 12:26:54.483   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:26:54.483   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:26:54.493   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:26:54.493   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,09-13 12:26:54.503   774   787 D BatteryService: stay LED for charging
,09-13 12:26:54.513  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:54.513  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:26:54.513  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:26:54.523  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:26:54.523  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:26:54.533  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,09-13 12:26:54.533  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:54.543  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:26:56.623  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:26:56.623  6324  6466 I jxcore-log: 
,09-13 12:26:56.623  6324  6466 I jxcore-log: websocket error
09-13 12:26:56.623  6324  6466 I jxcore-log: 
,09-13 12:26:56.623  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:26:56.623  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:26:56.623  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:26:56.623  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:56.623  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:26:56.623  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:26:56.623  6324  6466 I jxcore-log: 
,09-13 12:26:58.103   774  3409 D SSRM:n  : SIOP:: AP = 340, PST = 415, CUR = 300, LCD = 0
,09-13 12:26:59.273   774  1568 E Watchdog: !@Sync 5 [09-13 12:26:59.278]
,09-13 12:26:59.413   774  3410 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,09-13 12:26:59.423   774   849 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f27acf u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{891a53a 6176:com.samsung.android.sm.provider/1000}
,09-13 12:26:59.553   774  3410 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,09-13 12:26:59.573   774   849 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2efb65 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{891a53a 6176:com.samsung.android.sm.provider/1000}
,09-13 12:26:59.993   774  1236 V AlarmManager: Expired Alarm result :8
,09-13 12:27:01.703  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:01.703  6324  6466 I jxcore-log: 
,09-13 12:27:01.723  6324  6466 I jxcore-log: websocket error
09-13 12:27:01.723  6324  6466 I jxcore-log: 
,09-13 12:27:01.723  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:01.723  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:01.723  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:01.723  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:01.723  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:01.723  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:01.723  6324  6466 I jxcore-log: 
,09-13 12:27:04.523   774  1726 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:27:04.533   774  1726 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4390, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:27:04.533   774  1726 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:27:04.533   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:27:04.553   774   774 I MotionRecognitionService: Plugged
,09-13 12:27:04.553   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:27:04.553   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:27:04.553   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:27:04.563   774  1726 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,09-13 12:27:04.563   774  1726 D BatteryService: stay LED for charging
,09-13 12:27:04.573  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:04.573  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:04.573  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:27:04.603  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:27:04.603  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:27:04.613  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:27:04.613  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:27:04.613  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:27:06.783  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:06.783  6324  6466 I jxcore-log: 
,09-13 12:27:06.783  6324  6466 I jxcore-log: websocket error
09-13 12:27:06.783  6324  6466 I jxcore-log: 
,09-13 12:27:06.783  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:06.783  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:06.783  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:06.783  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:06.783  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:06.783  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:06.783  6324  6466 I jxcore-log: 
,09-13 12:27:08.173   774  3409 D SSRM:n  : SIOP:: AP = 340, PST = 405, CUR = 300, LCD = 0
,09-13 12:27:08.173   774  3409 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,09-13 12:27:08.233   774   849 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{445f4eb u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba5c171 6841:com.sec.android.app.videoplayer/u0a53}
,09-13 12:27:08.243  2770  2770 D ContentApp:  LEVEL : -1
,09-13 12:27:08.243  6841  6841 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,09-13 12:27:08.243  6841  6841 D TranscodeReceiver:  SIOP_LEVEL: -1
,09-13 12:27:09.053   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:27:11.863  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:11.863  6324  6466 I jxcore-log: 
,09-13 12:27:11.863  6324  6466 I jxcore-log: websocket error
09-13 12:27:11.863  6324  6466 I jxcore-log: 
,09-13 12:27:11.863  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:11.863  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:11.863  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:11.863  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:11.863  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:11.863  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:11.863  6324  6466 I jxcore-log: 
,09-13 12:27:14.603   774   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:27:14.613   774   788 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:27:14.613   774   788 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:27:14.623   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:27:14.633   774   774 I MotionRecognitionService: Plugged
,09-13 12:27:14.633   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:27:14.633   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:27:14.643   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:27:14.643   774   788 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,09-13 12:27:14.643   774   788 D BatteryService: stay LED for charging
,09-13 12:27:14.653  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:14.653  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:27:14.653  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:27:14.673  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:27:14.673  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:27:14.673  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:27:14.683  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:27:14.683  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 12:27:16.933  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:16.933  6324  6466 I jxcore-log: 
,09-13 12:27:16.933  6324  6466 I jxcore-log: websocket error
09-13 12:27:16.933  6324  6466 I jxcore-log: ,
,09-13 12:27:16.943  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:16.943  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:16.943  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:16.943  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:16.943  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:16.943  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:16.943  6324  6466 I jxcore-log: 
,09-13 12:27:18.293   774  3409 D SSRM:n  : SIOP:: AP = 330, PST = 390, CUR = 300, LCD = 0
,09-13 12:27:21.993  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:21.993  6324  6466 I jxcore-log: 
,09-13 12:27:22.003  6324  6466 I jxcore-log: websocket error
09-13 12:27:22.003  6324  6466 I jxcore-log: 
,09-13 12:27:22.003  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:22.003  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:22.003  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:22.003  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:22.003  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:22.003  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:22.003  6324  6466 I jxcore-log: 
,09-13 12:27:24.723   774  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:27:24.733   774  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:27:24.733   774  1415 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:27:24.733   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:27:24.743   774   774 I MotionRecognitionService: Plugged
,09-13 12:27:24.743   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:27:24.753   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:27:24.753   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:27:24.753  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:24.753  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:27:24.753  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:27:24.753  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:27:24.763   774  1415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,09-13 12:27:24.763   774  1415 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 774) 
,09-13 12:27:24.773   774  1415 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,09-13 12:27:24.773   774  1415 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,09-13 12:27:24.773  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:27:24.773  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:27:24.783  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:24.783  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:24.783  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:24.793   774  1415 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,09-13 12:27:24.803   774  1415 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,09-13 12:27:24.803   774  1415 D BatteryService: turn on LED for fully charged
,09-13 12:27:25.003   774  1218 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,09-13 12:27:25.013   774   915 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,09-13 12:27:25.013   774   915 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,09-13 12:27:25.023   774   915 D SensorManager: unregisterListener ::   
,09-13 12:27:25.023   774   915 D lights  : led_pattern : 5 +
,09-13 12:27:25.043   774   915 D lights  : led_pattern : 5 -,
09-13 12:27:25.053   774   915 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,09-13 12:27:25.053   774   915 V AlarmManager:  remove PendingIntent] PendingIntent{d2bd13c: PendingIntentRecord{5d08ec5 android broadcastIntent}}
,09-13 12:27:27.103  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:27.103  6324  6466 I jxcore-log: 
,09-13 12:27:27.103  6324  6466 I jxcore-log: websocket error
09-13 12:27:27.103  6324  6466 I jxcore-log: 
,09-13 12:27:27.103  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:27.103  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:27.103  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:27.103  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:27.103  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:27.103  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:27.103  6324  6466 I jxcore-log: 
,09-13 12:27:28.353   774  3409 D SSRM:n  : SIOP:: AP = 330, PST = 375, CUR = 300, LCD = 0
,09-13 12:27:28.413  2043  3287 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 12:27:29.083   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:27:29.283   774  1568 E Watchdog: !@Sync 6 [09-13 12:27:29.286]
,09-13 12:27:30.763  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:27:32.173  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:32.173  6324  6466 I jxcore-log: 
,09-13 12:27:32.173  6324  6466 I jxcore-log: websocket error
09-13 12:27:32.173  6324  6466 I jxcore-log: 
,09-13 12:27:32.183  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:32.183  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:32.183  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:32.183  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:32.183  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:32.183  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:32.183  6324  6466 I jxcore-log: 
,09-13 12:27:34.793   774  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:27:34.803   774  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:27:34.803   774  1415 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:27:34.813   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:27:34.823   774   774 I MotionRecognitionService: Plugged
,09-13 12:27:34.823   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:27:34.823   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:27:34.833   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:27:34.833   774  1415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,09-13 12:27:34.843   774  1415 D BatteryService: stay LED for fully charged
,09-13 12:27:34.853  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:34.853  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:27:34.853  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:27:34.863  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:27:34.863  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:27:34.873  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:34.873  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:34.883  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:37.273  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:37.273  6324  6466 I jxcore-log: 
,09-13 12:27:37.273  6324  6466 I jxcore-log: websocket error
09-13 12:27:37.273  6324  6466 I jxcore-log: 
,09-13 12:27:37.273  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:37.273  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:37.273  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:37.273  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:37.273  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:37.273  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:37.273  6324  6466 I jxcore-log: 
,09-13 12:27:38.423   774  3409 D SSRM:n  : SIOP:: AP = 330, PST = 363, CUR = 300, LCD = 0
,09-13 12:27:42.353  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:42.353  6324  6466 I jxcore-log: 
,09-13 12:27:42.363  6324  6466 I jxcore-log: websocket error
09-13 12:27:42.363  6324  6466 I jxcore-log: 
,09-13 12:27:42.363  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:42.363  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:42.363  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:42.363  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:42.363  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:42.363  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:42.363  6324  6466 I jxcore-log: 
,09-13 12:27:44.883   774  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:27:44.893   774  2422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:27:44.893   774  2422 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:27:44.893   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:27:44.913   774   774 I MotionRecognitionService: Plugged
,09-13 12:27:44.913   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:27:44.913   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:27:44.913   774  2422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,09-13 12:27:44.923   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:27:44.923   774  2422 D BatteryService: stay LED for fully charged
,09-13 12:27:44.943  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:44.943  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:44.943  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:27:44.963  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:27:44.963  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:27:44.973  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:44.973  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:27:44.973  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:47.443  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:47.443  6324  6466 I jxcore-log: 
,09-13 12:27:47.443  6324  6466 I jxcore-log: websocket error
09-13 12:27:47.443  6324  6466 I jxcore-log: 
,09-13 12:27:47.443  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:47.443  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:47.443  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:47.443  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:47.443  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:47.443  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:47.443  6324  6466 I jxcore-log: 
,09-13 12:27:48.493   774  3409 D SSRM:n  : SIOP:: AP = 320, PST = 350, CUR = 300, LCD = 0
,09-13 12:27:49.083   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:27:52.513  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:52.513  6324  6466 I jxcore-log: 
,09-13 12:27:52.513  6324  6466 I jxcore-log: websocket error
09-13 12:27:52.513  6324  6466 I jxcore-log: 
,09-13 12:27:52.513  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:52.513  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:52.513  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:52.513  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:52.513  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:52.513  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:52.513  6324  6466 I jxcore-log: 
,09-13 12:27:54.973   774  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:27:54.973   774  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:27:54.973   774  1501 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:27:54.983   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:27:54.993   774   774 I MotionRecognitionService: Plugged
,09-13 12:27:54.993   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:27:55.003   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:27:55.003   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:27:55.003   774  1501 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,09-13 12:27:55.003   774  1501 D BatteryService: stay LED for fully charged
,09-13 12:27:55.003  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:27:55.003  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:27:55.013  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:27:55.023  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:27:55.023  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:27:55.033  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:55.033  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:55.033  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:57.603  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:27:57.603  6324  6466 I jxcore-log: 
,09-13 12:27:57.603  6324  6466 I jxcore-log: websocket error
09-13 12:27:57.603  6324  6466 I jxcore-log: 
09-13 12:27:57.603  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:27:57.603  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:27:57.603  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:27:57.603  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:57.603  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:27:57.603  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:27:57.603  6324  6466 I jxcore-log: 
,09-13 12:27:58.553   774  3409 D SSRM:n  : SIOP:: AP = 320, PST = 341, CUR = 300, LCD = 0
,09-13 12:27:59.283   774  1568 E Watchdog: !@Sync 7 [09-13 12:27:59.291]
,09-13 12:28:02.673  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:02.673  6324  6466 I jxcore-log: 
,09-13 12:28:02.673  6324  6466 I jxcore-log: websocket error
09-13 12:28:02.673  6324  6466 I jxcore-log: 
,09-13 12:28:02.673  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:02.673  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:02.673  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:02.673  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:02.673  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:02.673  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:02.673  6324  6466 I jxcore-log: 
,09-13 12:28:05.053   774  1726 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:28:07.743  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:07.743  6324  6466 I jxcore-log: 
,09-13 12:28:07.743  6324  6466 I jxcore-log: websocket error
09-13 12:28:07.743  6324  6466 I jxcore-log: 
,09-13 12:28:07.753  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:07.753  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:07.753  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:07.753  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:07.753  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:07.753  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:07.753  6324  6466 I jxcore-log: 
,09-13 12:28:08.613   774  3409 D SSRM:n  : SIOP:: AP = 320, PST = 334, CUR = 300, LCD = 0
,09-13 12:28:09.083   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:28:15.133   774  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:28:18.673   774  3409 D SSRM:n  : SIOP:: AP = 320, PST = 330, CUR = 300, LCD = 0
,09-13 12:28:19.833  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:19.833  6324  6466 I jxcore-log: 
,09-13 12:28:19.833  6324  6466 I jxcore-log: websocket error
09-13 12:28:19.833  6324  6466 I jxcore-log: 
,09-13 12:28:19.843  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:19.843  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:19.843  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:19.843  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:19.843  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:19.843  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:19.843  6324  6466 I jxcore-log: 
,09-13 12:28:24.923  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:24.923  6324  6466 I jxcore-log: 
,09-13 12:28:24.923  6324  6466 I jxcore-log: websocket error
09-13 12:28:24.923  6324  6466 I jxcore-log: 
,09-13 12:28:24.933  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:24.933  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:24.933  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:24.933  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:24.933  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:24.933  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:24.933  6324  6466 I jxcore-log: 
,09-13 12:28:25.223   774  1646 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:28:25.233   774  1646 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:28:25.233   774  1646 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:28:25.233   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:28:25.243   774   774 I MotionRecognitionService: Plugged
,09-13 12:28:25.253   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:28:25.253   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:28:25.253   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:28:25.253   774  1646 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,09-13 12:28:25.263   774  1646 D BatteryService: stay LED for fully charged
,09-13 12:28:25.263  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:28:25.263  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:28:25.263  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:28:25.273  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:28:25.273  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:28:25.283  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:28:25.283  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:28:25.283  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:28:28.733   774  3409 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 300, LCD = 0
,09-13 12:28:29.093   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:28:29.293   774  1568 E Watchdog: !@Sync 8 [09-13 12:28:29.295]
,09-13 12:28:30.003  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:30.003  6324  6466 I jxcore-log: 
,09-13 12:28:30.013  6324  6466 I jxcore-log: websocket error
09-13 12:28:30.013  6324  6466 I jxcore-log: 
,09-13 12:28:30.013  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:30.013  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:30.013  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:30.013  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:30.013  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:30.013  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:30.013  6324  6466 I jxcore-log: 
,09-13 12:28:30.773  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:28:31.073  1747  1815 E ContactsProvider_EventLog: Flush buffer to file cnt : 8 size : 2Kb duration : 288ms lastUpdatedAfter : 171511ms
,09-13 12:28:35.093  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:35.093  6324  6466 I jxcore-log: 
,09-13 12:28:35.093  6324  6466 I jxcore-log: websocket error
09-13 12:28:35.093  6324  6466 I jxcore-log: 
,09-13 12:28:35.103  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:35.103  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:35.103  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:35.103  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:35.103  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:35.103  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:35.103  6324  6466 I jxcore-log: 
,09-13 12:28:35.323   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:28:35.333   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:28:35.333   774   787 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:28:35.333   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:28:35.353   774   774 I MotionRecognitionService: Plugged
,09-13 12:28:35.353   774   774 D MotionRecognitionService:   cableConnection= 1
09-13 12:28:35.353   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:28:35.353   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:28:35.353  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:28:35.353  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:28:35.353  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:28:35.353   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,09-13 12:28:35.363   774   787 D BatteryService: stay LED for fully charged
,09-13 12:28:35.373  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:28:35.373  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:28:35.383  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:28:35.383  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:28:35.383  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:28:38.793   774  3409 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 300, LCD = 0
,09-13 12:28:40.153  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:40.153  6324  6466 I jxcore-log: 
,09-13 12:28:40.153  6324  6466 I jxcore-log: websocket error
09-13 12:28:40.153  6324  6466 I jxcore-log: 
,09-13 12:28:40.153  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:40.153  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:40.153  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:40.153  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:40.153  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:40.153  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:40.153  6324  6466 I jxcore-log: 
,09-13 12:28:45.233  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:45.233  6324  6466 I jxcore-log: 
,09-13 12:28:45.233  6324  6466 I jxcore-log: websocket error
09-13 12:28:45.233  6324  6466 I jxcore-log: 
,09-13 12:28:45.233  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:45.233  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:45.233  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:45.233  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:45.233  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:45.233  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:45.233  6324  6466 I jxcore-log: 
,09-13 12:28:45.373   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:28:48.853   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 300, LCD = 0
,09-13 12:28:49.093   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:28:50.313  6324  6466 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 12:28:50.313  6324  6466 I jxcore-log: 
,09-13 12:28:50.313  6324  6466 I jxcore-log: websocket error
09-13 12:28:50.313  6324  6466 I jxcore-log: 
,09-13 12:28:50.313  6324  6466 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 12:28:50.313  6324  6466 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 12:28:50.313  6324  6466 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 12:28:50.313  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:50.313  6324  6466 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 12:28:50.313  6324  6466 I jxcore-log: emit@events.js:82:1
09-13 12:28:50.313  6324  6466 I jxcore-log: 
,09-13 12:28:55.463   774  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:28:55.493   774  1742 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:28:55.493   774  1742 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:28:55.493   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:28:55.503   774   774 I MotionRecognitionService: Plugged
,09-13 12:28:55.503   774   774 D MotionRecognitionService:   cableConnection= 1
09-13 12:28:55.503   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:28:55.503   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:28:55.503  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:28:55.503  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:28:55.503  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:28:55.513   774  1742 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 43ms
,09-13 12:28:55.513   774  1742 D BatteryService: stay LED for fully charged
,09-13 12:28:55.533  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:28:55.533  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:28:55.533  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:28:55.533  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:28:55.533  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:28:55.623  6324  6466 I jxcore-log: ThaliTape :: Reconnected to the test server
09-13 12:28:55.623  6324  6466 I jxcore-log: 
,09-13 12:28:55.663  6324  6466 I jxcore-log: ThaliTape :: Connected to the test server
09-13 12:28:55.663  6324  6466 I jxcore-log: 
,09-13 12:28:58.913   774  3409 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 300, LCD = 0
,09-13 12:28:59.293   774  1568 E Watchdog: !@Sync 9 [09-13 12:28:59.302]
,09-13 12:29:05.543   774  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:29:08.973   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 300, LCD = 0
,09-13 12:29:09.093   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:29:12.443   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:29:12.443   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:29:12.443   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:29:14.193   774  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,09-13 12:29:14.203   774  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:29:14.213   774  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,09-13 12:29:14.223   774  1230 I TLC_TIMA_PKM_initialize: initializing...
,09-13 12:29:14.223   774  1230 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,09-13 12:29:14.233   774  1230 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,09-13 12:29:14.233   774  1230 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,09-13 12:29:14.233   774  1230 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,09-13 12:29:14.233   774  1230 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,09-13 12:29:14.233   774  1230 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,09-13 12:29:14.243   774  1230 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,09-13 12:29:14.243   774  1230 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,09-13 12:29:14.243   774  1230 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 12:29:14.313   774  1230 D QSEECOMAPI: : Loaded image: APP id = 3
,09-13 12:29:14.323   774  1230 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,09-13 12:29:14.343   774  1230 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,09-13 12:29:15.643   774  1646 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:29:15.653   774  1646 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:29:15.653   774  1646 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:29:15.653   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:15.673   774   774 I MotionRecognitionService: Plugged
,09-13 12:29:15.673   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:29:15.673   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:29:15.673   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:29:15.683   774  1646 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,09-13 12:29:15.683   774  1646 D BatteryService: stay LED for fully charged
,09-13 12:29:15.683  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:15.683  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:29:15.683  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:29:15.703  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:29:15.703  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:29:15.703  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:15.713  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:15.713  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:17.613   774  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:29:17.613   774  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:29:17.623   774  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:29:17.623   774  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:29:19.033   774  3409 D SSRM:n  : SIOP:: AP = 320, PST = 318, CUR = 300, LCD = 0
,09-13 12:29:20.663   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:29:20.663   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:29:20.663   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:29:29.083   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 300, LCD = 0
,09-13 12:29:29.103   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:29:29.303   774  1568 E Watchdog: !@Sync 10 [09-13 12:29:29.306]
,09-13 12:29:30.423   774  1236 V AlarmManager: Expired Alarm result :4
,09-13 12:29:30.453  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-13 12:29:30.453  1381  1381 I PERF    : received broadcast android.intent.action.TIME_TICK
,09-13 12:29:30.453  1381  1381 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:29:30.503   774  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:29:30.503   774  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:29:30.503   774  1320 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 12:29:30.503   774  1320 D BatteryService: stay LED for fully charged
,09-13 12:29:30.503  1381  1381 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 12:29:30.513  1381  1381 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 12:29:30.533  1554  1554 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-13 12:29:30.543  1554  1554 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-13 12:29:30.553  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:29:30.553  1554  1554 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-13 12:29:30.563  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:29:30.563  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:29:30.563  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:29:30.573   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:30.573  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:29:30.583  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
09-13 12:29:30.583  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:29:30.583   774   774 I MotionRecognitionService: Plugged
09-13 12:29:30.583   774   774 D MotionRecognitionService:   cableConnection= 1
09-13 12:29:30.583   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:29:30.583   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:29:30.593  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:29:30.593  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:29:30.603  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:30.603  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:30.603  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:29:30.603  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:29:30.603  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:29:30.603  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:29:30.643  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:29:31.173  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:29:34.393   319  1101 D Netd    : Iface wlan0 link up
,09-13 12:29:34.393  1554  1554 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
,09-13 12:29:34.413   774   858 D Tethering: interfaceLinkStateChanged wlan0, true
,09-13 12:29:34.413   774   858 D Tethering: interfaceStatusChanged wlan0, true
,09-13 12:29:34.413  1554  1554 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,09-13 12:29:34.443   774  1324 D WifiP2pService: InactiveState{ what=147461 }
,09-13 12:29:34.443   774  1324 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-13 12:29:34.443   774  1324 D WifiP2pService: DefaultState{ what=147461 }
,09-13 12:29:34.493   774   849 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{315e606 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2988b77 1381:com.android.systemui/u0a58}
,09-13 12:29:39.173   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 300, LCD = 0
,09-13 12:29:40.593   774  1646 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:29:40.593   774  1646 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:29:40.593   774  1646 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:29:40.603   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:40.613   774   774 I MotionRecognitionService: Plugged
,09-13 12:29:40.613   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:29:40.613   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:29:40.623   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:29:40.623   774  1646 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,09-13 12:29:40.633   774  1646 D BatteryService: stay LED for fully charged
,09-13 12:29:40.643  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:40.643  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:29:40.643  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:29:40.653  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:29:40.653  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:29:40.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:40.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:40.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:49.113   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:29:49.233   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 300, LCD = 0
,09-13 12:29:50.663   774  3741 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:29:50.673   774  3741 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:29:50.673   774  3741 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:29:50.673   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:50.693   774   774 I MotionRecognitionService: Plugged
,09-13 12:29:50.693   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:29:50.693   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:29:50.693   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:29:50.703   774  3741 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,09-13 12:29:50.703   774  3741 D BatteryService: stay LED for fully charged
,09-13 12:29:50.713  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:50.713  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:50.713  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:29:50.743  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:29:50.743  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:29:50.743  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:50.743  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:29:50.743  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:52.903  4804  4883 I PlayCommon: [669] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:29:52.963  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:29:53.003  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:29:53.003  2043  2043 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:29:53.073  4804  4883 I PlayCommon: [669] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,09-13 12:29:53.073  4804  4883 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:29:53.073  4804  4883 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:29:53.073   319  1104 D EnterpriseController: netId is 0
09-13 12:29:53.073   319  1104 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,09-13 12:29:53.233  4804  4883 I PlayCommon: [669] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,09-13 12:29:59.293   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 300, LCD = 0
,09-13 12:29:59.303   774  1568 E Watchdog: !@Sync 11 [09-13 12:29:59.310]
,09-13 12:29:59.993   774  1236 V AlarmManager: Expired Alarm result :8
,09-13 12:30:00.763   774  3741 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:30:00.763   774  3741 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:30:00.763   774  3741 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:30:00.763   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:30:00.783   774   774 I MotionRecognitionService: Plugged
,09-13 12:30:00.783   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:30:00.783   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:30:00.783   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:30:00.793   774  3741 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,09-13 12:30:00.793   774  3741 D BatteryService: stay LED for fully charged
,09-13 12:30:00.793  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:30:00.793  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:30:00.793  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:30:00.813  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:30:00.813  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:30:00.823  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:00.823  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:00.823  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:09.113   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:30:09.353   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 300, LCD = 0
,09-13 12:30:10.863   774  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:30:10.863   774  2422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:30:10.873   774  2422 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:30:10.883   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:30:10.893   774   774 I MotionRecognitionService: Plugged
,09-13 12:30:10.893   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:30:10.893   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:30:10.893   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:30:10.893  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:30:10.903  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:30:10.903  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:30:10.903   774  2422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 41ms
,09-13 12:30:10.903   774  2422 D BatteryService: stay LED for fully charged
,09-13 12:30:10.913  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:30:10.913  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:30:10.923  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:10.923  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:30:10.923  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:19.413   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300, LCD = 0
,09-13 12:30:20.923   774  1725 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:30:20.933   774  1725 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:30:20.933   774  1725 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:30:20.933   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:30:20.953   774   774 I MotionRecognitionService: Plugged
,09-13 12:30:20.953   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:30:20.953   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:30:20.953   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:30:20.963   774  1725 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
09-13 12:30:20.963   774  1725 D BatteryService: stay LED for fully charged
,09-13 12:30:20.983  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:30:20.983  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:30:20.983  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:30:21.003  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:30:21.003  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:30:21.013  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:21.013  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:21.013  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:25.883   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:30:25.883   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:30:25.883   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:30:29.123   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:30:29.313   774  1568 E Watchdog: !@Sync 12 [09-13 12:30:29.316]
,09-13 12:30:29.463   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300, LCD = 0
,09-13 12:30:31.013   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:30:31.013   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:30:31.013   774   787 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:30:31.023   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:30:31.033   774   774 I MotionRecognitionService: Plugged
,09-13 12:30:31.033   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:30:31.033   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:30:31.043   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:30:31.043   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,09-13 12:30:31.043   774   787 D BatteryService: stay LED for fully charged
,09-13 12:30:31.043  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:30:31.043  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:30:31.043  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:30:31.063  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:30:31.063  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:30:31.073  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:31.073  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:31.073  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:31.283  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:30:32.483  4804  6144 I PlayCommon: [690] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:30:32.493  4804  6144 I PlayCommon: [690] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:30:35.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:30:35.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:30:35.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:30:39.533   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300, LCD = 0
,09-13 12:30:41.093   774  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:30:41.103   774  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:30:41.103   774  1415 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:30:41.103   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:30:41.123   774   774 I MotionRecognitionService: Plugged
,09-13 12:30:41.123   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:30:41.123   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:30:41.133   774  1415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,09-13 12:30:41.133   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:30:41.143   774  1415 D BatteryService: stay LED for fully charged
,09-13 12:30:41.143  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:30:41.143  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:30:41.143  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:30:41.153  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:30:41.163  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:30:41.173  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:41.173  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:30:41.173  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:49.123   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:30:49.603   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300, LCD = 0
,09-13 12:30:51.003   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:30:51.003   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:30:51.003   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:30:51.173   774  1612 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:30:51.183   774  1612 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:30:51.183   774  1612 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:30:51.193   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:30:51.203   774   774 I MotionRecognitionService: Plugged
,09-13 12:30:51.203   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:30:51.213   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:30:51.213   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:30:51.213   774  1612 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 38ms
,09-13 12:30:51.223   774  1612 D BatteryService: stay LED for fully charged
,09-13 12:30:51.233  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:30:51.233  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:30:51.243  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:30:51.253  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:30:51.253  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:30:51.263  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:51.263  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:51.263  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:59.313   774  1568 E Watchdog: !@Sync 13 [09-13 12:30:59.320]
,09-13 12:30:59.653   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,09-13 12:31:01.013   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:31:01.013   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:31:01.013   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:31:01.263   774  2439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:01.263   774  2439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:31:01.263   774  2439 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:31:01.273   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:31:01.283   774   774 I MotionRecognitionService: Plugged
,09-13 12:31:01.293   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:31:01.293   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:31:01.293   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:31:01.293  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:01.293  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:31:01.293  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:31:01.303   774  2439 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,09-13 12:31:01.303   774  2439 D BatteryService: stay LED for fully charged
,09-13 12:31:01.313  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:31:01.313  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:31:01.323  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:01.323  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:01.323  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:09.123   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:31:09.713   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,09-13 12:31:11.353   774  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:11.353   774  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:31:11.363   774  1320 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:31:11.363   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:31:11.373   774   774 I MotionRecognitionService: Plugged
,09-13 12:31:11.383   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:31:11.383   774  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,09-13 12:31:11.383   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:31:11.393   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:31:11.383   774  1320 D BatteryService: stay LED for fully charged
,09-13 12:31:11.393  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:11.393  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:31:11.393  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:31:11.403  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:31:11.413  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:31:11.423  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:11.423  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:31:11.423  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:19.773   774  3409 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,09-13 12:31:21.433   774  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:21.433   774  1742 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:31:21.433   774  1742 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:31:21.443   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:31:21.453   774   774 I MotionRecognitionService: Plugged
,09-13 12:31:21.453   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:31:21.453   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:31:21.463   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:31:21.463   774  1742 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,09-13 12:31:21.463   774  1742 D BatteryService: stay LED for fully charged
,09-13 12:31:21.483  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:21.493  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:31:21.493  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:31:21.503  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:31:21.503  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:31:21.513  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:21.513  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:21.513  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:22.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:31:22.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:31:22.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:31:26.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:31:26.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:31:26.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:31:29.133   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:31:29.323   774  1568 E Watchdog: !@Sync 14 [09-13 12:31:29.324]
,09-13 12:31:29.833   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 300, LCD = 0
,09-13 12:31:31.343  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:31:31.493   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:31.493   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:31:31.493   774   787 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:31:31.503   774   787 D BatteryService: stay LED for fully charged
09-13 12:31:31.503   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:31:31.503   774   774 I MotionRecognitionService: Plugged
,09-13 12:31:31.503   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:31:31.503   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:31:31.503   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:31:31.513  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:31.513  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:31:31.513  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:31:31.543  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:31:31.543  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:31:31.543  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:31.543  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:31:31.543  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:31.613  1747  1815 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 247ms lastUpdatedAfter : 180542ms
,09-13 12:31:39.893   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 300, LCD = 0
,09-13 12:31:41.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:31:41.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:31:41.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:31:41.583   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:41.593   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:31:41.593   774   787 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:31:41.603   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
,09-13 12:31:41.603   774   787 D BatteryService: stay LED for fully charged
,09-13 12:31:41.603   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:31:41.623   774   774 I MotionRecognitionService: Plugged
,09-13 12:31:41.633   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:31:41.633   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:31:41.633   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:31:41.643  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:41.643  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:31:41.643  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:31:41.653  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:31:41.653  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:31:41.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:41.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:41.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:49.133   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:31:49.953   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 300, LCD = 0
,09-13 12:31:51.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:31:51.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:31:51.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:31:51.673   774  1646 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:51.673   774  1646 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:31:51.683   774  1646 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:31:51.683   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:31:51.693   774   774 I MotionRecognitionService: Plugged
,09-13 12:31:51.693   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:31:51.693   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:31:51.703   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:31:51.703   774  1646 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,09-13 12:31:51.703   774  1646 D BatteryService: stay LED for fully charged
,09-13 12:31:51.713  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:51.713  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:51.723  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:31:51.743  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:31:51.753  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:31:51.753  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:51.753  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:51.753  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:59.323   774  1568 E Watchdog: !@Sync 15 [09-13 12:31:59.331]
,09-13 12:32:00.013   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 300, LCD = 0
,09-13 12:32:01.763   774  1726 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:32:01.773   774  1726 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:32:01.773   774  1726 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:32:01.773   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:32:01.793   774   774 I MotionRecognitionService: Plugged
,09-13 12:32:01.793   774   774 D MotionRecognitionService:   cableConnection= 1
09-13 12:32:01.793   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:32:01.793   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:32:01.793   774  1726 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms
,09-13 12:32:01.793   774  1726 D BatteryService: stay LED for fully charged
,09-13 12:32:01.793  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:32:01.793  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:32:01.793  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:32:01.813  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:32:01.813  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:32:01.823  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:32:01.823  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:32:01.823  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:32:03.703   365   365 I bootchecker: bootchecker wake up!!
,09-13 12:32:06.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:32:06.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:32:06.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:32:09.143   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:32:10.073   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300, LCD = 0
,09-13 12:32:16.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:32:16.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:32:16.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:32:20.133   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 300, LCD = 0
,09-13 12:32:29.143   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:32:29.333   774  1568 E Watchdog: !@Sync 16 [09-13 12:32:29.337]
,09-13 12:32:30.193   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,09-13 12:32:31.363   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:32:31.363   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:32:31.363   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:32:31.623  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:32:31.833   774   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:32:31.833   774   788 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:32:31.833   774   788 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:32:31.833   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:32:31.843   774   774 I MotionRecognitionService: Plugged
,09-13 12:32:31.843   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:32:31.843   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:32:31.853   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:32:31.853   774   788 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 22ms
,09-13 12:32:31.853   774   788 D BatteryService: stay LED for fully charged
,09-13 12:32:31.863  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:32:31.873  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:32:31.873  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:32:31.893  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:32:31.893  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:32:31.903  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:32:31.903  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:32:31.903  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:32:40.243   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 0
,09-13 12:32:41.393   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:32:41.393   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:32:41.393   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:32:49.143   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:32:50.303   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,09-13 12:32:56.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:32:56.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:32:56.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:32:59.333   774  1568 E Watchdog: !@Sync 17 [09-13 12:32:59.340]
,09-13 12:32:59.993   774  1236 V AlarmManager: Expired Alarm result :8
,09-13 12:32:59.993   774  1236 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=541716 batch.start=679021
,09-13 12:33:00.023  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-13 12:33:00.023  1381  1381 I PERF    : received broadcast android.intent.action.TIME_TICK
,09-13 12:33:00.023  1381  1381 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:33:00.063  1381  1381 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 12:33:00.093  1381  1381 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 12:33:00.103  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:33:00.103  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:33:00.103  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:33:00.103  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:33:00.103  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:33:00.113  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:33:00.123  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:33:00.183  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:33:00.363   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:33:01.913   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:33:01.923   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:33:01.923   774   787 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:33:01.923   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:33:01.933   774   774 I MotionRecognitionService: Plugged
,09-13 12:33:01.943   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:33:01.943   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:33:01.943   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:33:01.943   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,09-13 12:33:01.953   774   787 D BatteryService: stay LED for fully charged
,09-13 12:33:01.963  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:33:01.963  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:33:01.963  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:33:01.993  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:33:01.993  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:33:01.993  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:01.993  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:33:01.993  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:06.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:33:06.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:33:06.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:33:09.153   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:33:10.423   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:33:20.473   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:33:21.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:33:21.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:33:21.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:33:29.153   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:33:29.343   774  1568 E Watchdog: !@Sync 18 [09-13 12:33:29.344]
,09-13 12:33:30.533   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:33:31.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:33:31.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:33:31.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:33:31.743  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:33:31.983   774  2439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:33:31.983   774  2439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:33:31.993   774  2439 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:33:31.993   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:33:32.003   774   774 I MotionRecognitionService: Plugged
,09-13 12:33:32.003   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:33:32.013   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:33:32.013   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:33:32.023   774  2439 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,09-13 12:33:32.023   774  2439 D BatteryService: stay LED for fully charged
,09-13 12:33:32.033  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:33:32.033  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:33:32.043  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:33:32.053  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:33:32.053  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:33:32.063  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:32.063  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:32.063  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:40.593   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:33:46.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:33:46.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:33:46.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:33:49.163   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:33:50.643   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:33:54.093   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:33:54.093   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:33:54.093   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:33:59.343   774  1568 E Watchdog: !@Sync 19 [09-13 12:33:59.349]
,09-13 12:33:59.993   774  1236 V AlarmManager: Expired Alarm result :8
,09-13 12:34:00.693   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:34:02.053   774  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:34:09.163   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:34:10.753   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:34:11.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:34:11.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:34:11.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:34:14.193   774  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,09-13 12:34:14.193   774  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,09-13 12:34:14.193   774  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:34:15.643   774  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:34:15.653   774  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:34:15.663   774  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:34:15.663   774  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:34:20.803   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:34:21.703   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:34:21.703   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:34:21.703   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:34:29.163   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:34:29.343   774  1568 E Watchdog: !@Sync 20 [09-13 12:34:29.353]
,09-13 12:34:30.863   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:34:31.773  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:34:31.983  1747  1815 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 189ms lastUpdatedAfter : 180368ms
,09-13 12:34:32.123   774  3741 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:34:32.123   774  3741 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:34:32.133   774  3741 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:34:32.133   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:34:32.143   774   774 I MotionRecognitionService: Plugged
,09-13 12:34:32.143   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:34:32.153   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:34:32.153   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:34:32.153   774  3741 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,09-13 12:34:32.163   774  3741 D BatteryService: stay LED for fully charged
,09-13 12:34:32.183  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:34:32.183  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:34:32.193  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:34:32.203  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:34:32.203  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:34:32.213  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:34:32.213  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:34:32.213  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.813   774   842 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.823   774   842 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.833   774   842 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
09-13 12:34:33.843   774   842 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-13 12:34:33.883   774   901 I ActivityManager: setMaxStartingBackgroundTimer onfinish
09-13 12:34:33.893   774   901 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,09-13 12:34:40.913   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:34:49.173   774  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:34:50.973   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:34:59.353   774  1568 E Watchdog: !@Sync 21 [09-13 12:34:59.357]
,09-13 12:35:01.023   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:35:02.193   774  1646 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:35:02.203   774  1646 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:35:02.203   774  1646 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:35:02.203   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:35:02.223   774  1646 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 20ms
,09-13 12:35:02.223   774  1646 D BatteryService: stay LED for fully charged
,09-13 12:35:02.233   774   774 I MotionRecognitionService: Plugged
,09-13 12:35:02.233   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:35:02.233   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:35:02.243   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:35:02.253  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:35:02.253  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:35:02.253  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:35:02.263  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:35:02.263  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:35:02.273  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:02.273  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:35:02.273  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:08.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:35:08.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:35:08.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:35:08.303   774  2422 I ActivityManager: Killing 4535:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 618s, lastActivityTime 618s
,09-13 12:35:08.303   774  2422 I ActivityManager: Killing 3827:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 622s, lastActivityTime 622s
,09-13 12:35:08.363   292   292 I ServiceManager: service 'AtCmdFwd' died
,09-13 12:35:08.373   376  4820 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,09-13 12:35:08.373   376  4820 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:35:08.383   774  1726 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,09-13 12:35:08.383   774  1726 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
,09-13 12:35:08.383   774  1726 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,09-13 12:35:08.413   774  1501 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,09-13 12:35:08.413   774  1501 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
09-13 12:35:08.413   774  1501 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10970ms
,09-13 12:35:09.373   376  4820 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:35:09.453   774   849 I ActivityManager: Start proc 6983:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,09-13 12:35:09.463  6983  6983 E Zygote  : v2
,09-13 12:35:09.463  6983  6983 I libpersona: KNOX_SDCARD checking this for 1000
,09-13 12:35:09.463  6983  6983 I libpersona: KNOX_SDCARD not a persona
,09-13 12:35:09.473  6983  6983 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:35:09.473  6983  6983 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:35:09.473  6983  6983 E Zygote  : accessInfo : 0
,09-13 12:35:09.513  6983  6983 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:35:09.513  6983  6983 D ActivityThread: Added TimaKeyStore provider
,09-13 12:35:09.543  6983  6983 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,09-13 12:35:09.563  6983  6983 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,09-13 12:35:09.573  6983  6983 D AtFwdService: onCreate method
,09-13 12:35:09.573  6983  6983 I AtFwdService: Instantiate AtCmdFwd Service
,09-13 12:35:09.583  6983  6995 D AtCkpdCmdHandler: De-queing command
,09-13 12:35:11.083   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:35:11.853   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:35:11.853   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:35:11.853   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:35:17.303   774  1236 V AlarmManager: Expired Alarm result :8
,09-13 12:35:19.453   774   849 I ActivityManager: Start proc 6997:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,09-13 12:35:19.463  6997  6997 E Zygote  : v2
,09-13 12:35:19.463  6997  6997 I libpersona: KNOX_SDCARD checking this for 10026
09-13 12:35:19.463  6997  6997 I libpersona: KNOX_SDCARD not a persona
,09-13 12:35:19.463  6997  6997 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:35:19.463  6997  6997 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:35:19.473  6997  6997 E Zygote  : accessInfo : 0
,09-13 12:35:19.473  6997  6997 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,09-13 12:35:19.513  6997  6997 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:35:19.513  6997  6997 D ActivityThread: Added TimaKeyStore provider
,09-13 12:35:19.523   774  1415 I ActivityManager: Killing 1521:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 637s, lastActivityTime 602s
,09-13 12:35:19.523   774  1415 I ActivityManager: Killing 3779:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 633s, lastActivityTime 606s
,09-13 12:35:19.563  6997  6997 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,09-13 12:35:19.563   774  1742 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
09-13 12:35:19.563   774  1742 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,09-13 12:35:19.583   774  1501 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
09-13 12:35:19.583   774  1501 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
09-13 12:35:19.583   774  1501 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,09-13 12:35:19.593  6997  6997 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,09-13 12:35:19.603  6997  6997 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,09-13 12:35:19.603  6997  6997 D ContextualPageNotification: resetAllNotification : all clear!!!
,09-13 12:35:20.653   774   849 I ActivityManager: Start proc 7019:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
09-13 12:35:20.653   774  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-13 12:35:20.663  7019  7019 E Zygote  : v2
,09-13 12:35:20.663  7019  7019 I libpersona: KNOX_SDCARD checking this for 10181
09-13 12:35:20.663  7019  7019 I libpersona: KNOX_SDCARD not a persona
,09-13 12:35:20.663  7019  7019 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:35:20.663  7019  7019 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:35:20.663  7019  7019 E Zygote  : accessInfo : 0
,09-13 12:35:20.673  7019  7019 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,09-13 12:35:20.713  7019  7019 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:35:20.713  7019  7019 D ActivityThread: Added TimaKeyStore provider
,09-13 12:35:20.733   774  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,09-13 12:35:20.743  7019  7019 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,09-13 12:35:20.773  7019  7019 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,09-13 12:35:20.803  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,09-13 12:35:20.813  7019  7019 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,09-13 12:35:20.823   774   849 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{31ccc51 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{129dcb6 7019:com.sec.android.daemonapp/u0a181}
,09-13 12:35:20.833  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,09-13 12:35:20.833  7019  7019 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,09-13 12:35:20.833  7019  7019 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,09-13 12:35:20.833  7019  7019 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,09-13 12:35:20.833  7019  7019 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,09-13 12:35:20.833  7019  7019 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,09-13 12:35:20.853  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:35:20.853  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,09-13 12:35:20.863  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,09-13 12:35:20.863  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:35:20.863  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
09-13 12:35:20.863  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,09-13 12:35:20.873  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,09-13 12:35:20.893  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,09-13 12:35:20.903  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:35:20.903  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,09-13 12:35:20.903  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,09-13 12:35:20.913  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,09-13 12:35:20.913  7019  7019 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,09-13 12:35:20.913  7019  7019 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,09-13 12:35:20.913  7019  7019 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,09-13 12:35:20.913  7019  7019 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 12:35:20.913  7019  7019 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,09-13 12:35:20.923  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,09-13 12:35:20.923  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,09-13 12:35:20.923  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
09-13 12:35:20.923  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,09-13 12:35:20.923  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
09-13 12:35:20.923  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:35:20.923  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,09-13 12:35:20.933   774  3741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eef0e42 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{129dcb6 7019:com.sec.android.daemonapp/u0a181}
,09-13 12:35:20.943  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:35:20.943  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
09-13 12:35:20.943  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 12:35:20.943  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:35:20.953  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,09-13 12:35:20.953  7019  7019 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:35:20.953  7019  7019 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,09-13 12:35:20.953  7019  7019 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 12:35:20.953  7019  7019 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:35:20.953  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,09-13 12:35:20.953  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
09-13 12:35:20.953  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
09-13 12:35:20.953  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,09-13 12:35:20.953  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
09-13 12:35:20.953  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:35:20.953  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,09-13 12:35:20.963   774  1415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2d5e53 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{129dcb6 7019:com.sec.android.daemonapp/u0a181}
,09-13 12:35:20.973  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:35:20.973  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
09-13 12:35:20.973  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 12:35:20.973  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:35:20.973  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,09-13 12:35:20.973  7019  7019 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:35:20.973  7019  7019 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,09-13 12:35:20.983  7019  7019 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 12:35:20.983  7019  7019 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,09-13 12:35:20.983  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
09-13 12:35:20.983  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
09-13 12:35:20.983  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,09-13 12:35:20.983  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
09-13 12:35:20.983  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,09-13 12:35:20.983  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:35:20.983  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,09-13 12:35:20.993   774  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c40a390 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{129dcb6 7019:com.sec.android.daemonapp/u0a181}
,09-13 12:35:20.993  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:35:20.993  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,09-13 12:35:20.993  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 12:35:21.003  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:35:21.003  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,09-13 12:35:21.003  7019  7019 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:35:21.003  7019  7019 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,09-13 12:35:21.003  7019  7019 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 12:35:21.003  7019  7019 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:35:21.003  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,09-13 12:35:21.003  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
09-13 12:35:21.003  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
09-13 12:35:21.003  7019  7019 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,09-13 12:35:21.013  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
09-13 12:35:21.013  7019  7019 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:35:21.013  7019  7019 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,09-13 12:35:21.153   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:35:26.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:35:26.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:35:26.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:35:29.353   774  1568 E Watchdog: !@Sync 22 [09-13 12:35:29.361]
,09-13 12:35:31.203   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:35:32.033  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:35:32.283   774  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:35:32.283   774  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:35:32.283   774  1320 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:35:32.293   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:35:32.303   774   774 I MotionRecognitionService: Plugged
,09-13 12:35:32.303   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:35:32.303   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:35:32.303   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:35:32.313   774  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,09-13 12:35:32.313   774  1320 D BatteryService: stay LED for fully charged
,09-13 12:35:32.323  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:35:32.323  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:35:32.323  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:35:32.353  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:35:32.353  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:35:32.363  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:32.363  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:35:32.363  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:32.493  4804  6144 I PlayCommon: [690] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:35:32.503  4804  6144 I PlayCommon: [690] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:35:36.943   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:35:36.943   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:35:36.943   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:35:41.263   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:35:51.313   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:35:52.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:35:52.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:35:52.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:35:52.063   774  2422 I ActivityManager: Killing 1882:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 680s, lastActivityTime 609s
,09-13 12:35:52.063   774  2422 I ActivityManager: Killing 6281:com.samsung.android.sdk.samsunglink/u0a41 (adj 8): SSR - service for lastStateTime 613s, lastActivityTime 613s
,09-13 12:35:52.153   774  1612 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,09-13 12:35:52.163   774  1612 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,09-13 12:35:52.163  5710  5710 D HealthConsole: Service for HealthDataStore is disconnected
,09-13 12:35:52.173   774  1725 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,09-13 12:35:52.173   774  1725 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
09-13 12:35:52.173   774  1725 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 1000ms
09-13 12:35:52.173   774  1725 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
,09-13 12:35:52.173   774  1725 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 11000ms
,09-13 12:35:52.223  7047  7047 E Zygote  : v2
09-13 12:35:52.223  7047  7047 I libpersona: KNOX_SDCARD checking this for 10034
09-13 12:35:52.223  7047  7047 I libpersona: KNOX_SDCARD not a persona
,09-13 12:35:52.223  7047  7047 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:35:52.223  7047  7047 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:35:52.223  7047  7047 E Zygote  : accessInfo : 0
,09-13 12:35:52.223  7047  7047 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,09-13 12:35:52.223   774  3741 I ActivityManager: Start proc 7047:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,09-13 12:35:52.263  7047  7047 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:35:52.263  7047  7047 D ActivityThread: Added TimaKeyStore provider
,09-13 12:35:52.283  7047  7047 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,09-13 12:35:52.303  7047  7047 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,09-13 12:35:52.313  7047  7047 I MultiDex: VM with version 2.1.0 has multidex support
09-13 12:35:52.313  7047  7047 I MultiDex: install
09-13 12:35:52.313  7047  7047 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-13 12:35:52.313  7047  7047 I MultiDex: install
09-13 12:35:52.313  7047  7047 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 12:35:52.333   774   784 I art     : Background partial concurrent mark sweep GC freed 92129(8MB) AllocSpace objects, 302(5MB) LOS objects, 27% free, 42MB/58MB, paused 1.543ms total 133.029ms
,09-13 12:35:52.433  7063  7063 E Zygote  : v2
09-13 12:35:52.433  7063  7063 I libpersona: KNOX_SDCARD checking this for 10016
09-13 12:35:52.433  7063  7063 I libpersona: KNOX_SDCARD not a persona
,09-13 12:35:52.433  7063  7063 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 12:35:52.433  7063  7063 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:35:52.433   774  1717 I ActivityManager: Start proc 7063:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
09-13 12:35:52.433  7063  7063 E Zygote  : accessInfo : 0
,09-13 12:35:52.433  7063  7063 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,09-13 12:35:52.453  7063  7063 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:35:52.453  7063  7063 D ActivityThread: Added TimaKeyStore provider
,09-13 12:35:52.473  7063  7063 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,09-13 12:35:52.513  7047  7047 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
09-13 12:35:52.513  7047  7047 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,09-13 12:35:52.553  1381  1381 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,09-13 12:35:52.583  1381  1381 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{daa2c87 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
09-13 12:35:52.583  1381  1381 D AdaptiveEventManager: M updateContainers()
09-13 12:35:52.583  1381  1381 D AdaptiveEventContainerSmall: C updatePedoContainer()
09-13 12:35:52.583  1381  1381 D AdaptiveEventContainerSmall: handlePedoUpdate()
,09-13 12:35:52.583   774  1415 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,09-13 12:35:52.583  1381  1381 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,09-13 12:35:52.593   774  1725 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,09-13 12:35:52.603   774  1717 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,09-13 12:35:52.603   774  1742 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,09-13 12:35:52.663  7047  7047 I Health.HealthService: HealthService: onCreate() start (7047)
,09-13 12:35:52.803  5710  5710 D HealthDataStore: Service for HealthDataStore is connected
,09-13 12:35:52.813  5710  5710 D HealthDataStore: HealthConnectionErrorResult code : 9
,09-13 12:35:52.823   774  1725 I ActivityManager: Killing 5945:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,09-13 12:35:52.853  5710  5710 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,09-13 12:35:52.853  5710  5710 E HealthDataStore: disconnectService: Context instance is invalid
,09-13 12:35:52.863   774  2439 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,09-13 12:35:52.923  7047  7047 D HealthDataStore: Service for HealthDataStore is connected
,09-13 12:35:52.923  7047  7047 D HealthDataStore: HealthConnectionErrorResult code : 9
,09-13 12:35:52.923  7047  7047 D HealthConsole: Service for HealthDataConsole is connected
,09-13 12:35:52.923  7047  7047 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,09-13 12:35:52.933  7047  7047 E HealthDataStore: disconnectService: Context instance is invalid
,09-13 12:35:53.103  7047  7084 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,09-13 12:35:53.183  7047  7100 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,09-13 12:35:53.233  7063  7073 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-13 12:35:53.243   446   446 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7063
09-13 12:35:53.243   446   446 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,09-13 12:35:53.493  7063  7073 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,09-13 12:35:53.503  7047  7100 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,09-13 12:35:53.713  7047  7100 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,09-13 12:35:53.713  7047  7100 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,09-13 12:35:53.843   446   446 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,09-13 12:35:53.883  7063  7073 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,09-13 12:35:53.883  7063  7073 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,09-13 12:35:53.893  7063  7073 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,09-13 12:35:59.363   774  1568 E Watchdog: !@Sync 23 [09-13 12:35:59.365]
,09-13 12:36:01.373   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:36:02.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:36:02.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:36:02.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:36:02.353   774   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:36:02.363   774   788 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:36:02.373   774   788 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:36:02.373   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:36:02.383   774   774 I MotionRecognitionService: Plugged
,09-13 12:36:02.393   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:36:02.393   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:36:02.393   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:36:02.393   774   788 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,09-13 12:36:02.393   774   788 D BatteryService: stay LED for fully charged
,09-13 12:36:02.403  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:36:02.403  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:36:02.403  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:36:02.413  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:36:02.413  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:36:02.423  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:36:02.423  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:36:02.423  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:36:11.423   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:36:17.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:36:17.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:36:17.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:36:21.473   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:36:27.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:36:27.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:36:27.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:36:29.363   774  1568 E Watchdog: !@Sync 24 [09-13 12:36:29.372]
,09-13 12:36:31.533   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:36:32.173  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:36:32.433   774  3741 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:36:32.433   774  3741 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:36:32.443   774  3741 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:36:32.443   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:36:32.453   774   774 I MotionRecognitionService: Plugged
,09-13 12:36:32.453   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:36:32.463   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:36:32.463   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:36:32.473   774  3741 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,09-13 12:36:32.473   774  3741 D BatteryService: stay LED for fully charged
,09-13 12:36:32.493  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:36:32.493  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:36:32.493  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:36:32.503  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:36:32.503  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:36:32.513  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:36:32.523  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:36:32.523  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:36:41.583   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:36:42.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:36:42.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:36:42.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:36:51.643   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:36:52.213   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:36:52.213   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:36:52.213   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:36:59.373   774  1568 E Watchdog: !@Sync 25 [09-13 12:36:59.378]
,09-13 12:37:01.693   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:37:02.513   774   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:37:07.323   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:37:07.323   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:37:07.323   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:37:11.753   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:37:17.303   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:37:17.303   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:37:17.303   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:37:21.803   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:37:25.063   774  1236 V AlarmManager: Expired Alarm result :8
,09-13 12:37:29.373   774  1568 E Watchdog: !@Sync 26 [09-13 12:37:29.382]
,09-13 12:37:31.863   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:37:32.263  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:37:32.403   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:37:32.403   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:37:32.403   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:37:32.493  1747  1815 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 217ms lastUpdatedAfter : 180511ms
,09-13 12:37:32.583   774  1717 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:37:32.583   774  1717 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:37:32.583   774  1717 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:37:32.593   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:37:32.603   774   774 I MotionRecognitionService: Plugged
,09-13 12:37:32.603   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:37:32.613   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:37:32.613   774  1717 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,09-13 12:37:32.613   774  1717 D BatteryService: stay LED for fully charged
,09-13 12:37:32.613   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:37:32.633  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:37:32.633  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:37:32.643  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:37:32.653  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:37:32.653  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:37:32.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:37:32.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:37:32.663  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:37:33.933   774  2442 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,09-13 12:37:33.943   774  2442 V MARsPolicyManager: updateSMDBValues
,09-13 12:37:33.943   774   896 E MARsDBManager: updateDBAll : begin --size 1
,09-13 12:37:34.013   774   896 E MARsDBManager: updateDBAll : end
,09-13 12:37:34.013   774   896 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,09-13 12:37:41.913   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:37:42.393   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:37:42.393   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:37:42.393   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:37:51.973   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:37:57.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:37:57.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:37:57.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:37:59.383   774  1568 E Watchdog: !@Sync 27 [09-13 12:37:59.388]
,09-13 12:38:02.053   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:38:02.663   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:38:02.673   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:38:02.673   774   787 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:38:02.673   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:38:02.683   774   774 I MotionRecognitionService: Plugged
,09-13 12:38:02.693   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:38:02.693   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:38:02.693   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:38:02.693   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,09-13 12:38:02.703   774   787 D BatteryService: stay LED for fully charged
,09-13 12:38:02.713  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:38:02.713  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:38:02.713  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:38:02.743  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:38:02.743  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:38:02.743  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:02.743  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:38:02.743  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:07.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:38:07.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:38:07.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:38:12.113   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:38:22.163   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:38:22.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:38:22.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:38:22.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:38:29.383   774  1568 E Watchdog: !@Sync 28 [09-13 12:38:29.392]
,09-13 12:38:32.223   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:38:32.543  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:38:32.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:38:32.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:38:32.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:38:32.713   774  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:38:32.713   774  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:38:32.713   774  1415 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 12:38:32.713   774  1415 D BatteryService: stay LED for fully charged
09-13 12:38:32.713   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:38:32.723   774   774 I MotionRecognitionService: Plugged
,09-13 12:38:32.723   774   774 D MotionRecognitionService:   cableConnection= 1
09-13 12:38:32.723   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:38:32.723   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:38:32.733  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:38:32.733  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:38:32.733  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:38:32.743  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:38:32.743  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:38:32.753  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:32.753  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:32.753  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:42.293   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:38:47.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:38:47.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:38:47.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:38:52.343   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:38:57.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:38:57.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:38:57.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:38:59.393   774  1568 E Watchdog: !@Sync 29 [09-13 12:38:59.398]
,09-13 12:39:02.403   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:39:02.803   774  3741 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:39:02.803   774  3741 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:39:02.803   774  3741 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:39:02.813   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:39:02.823   774   774 I MotionRecognitionService: Plugged
,09-13 12:39:02.823   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:39:02.823   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:39:02.833   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:39:02.833   774  3741 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,09-13 12:39:02.833   774  3741 D BatteryService: stay LED for fully charged
,09-13 12:39:02.843  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:39:02.843  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:39:02.843  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:39:02.853  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:39:02.853  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:39:02.863  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:39:02.873  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:39:02.873  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:39:12.453   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:39:12.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:39:12.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:39:12.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:39:14.193   774  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,09-13 12:39:14.193   774  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,09-13 12:39:14.193   774  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:39:17.513   774  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:39:17.513   774  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:39:17.523   774  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:39:17.533   774  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:39:22.513   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:39:22.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:39:22.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:39:22.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:39:29.393   774  1568 E Watchdog: !@Sync 30 [09-13 12:39:29.402]
,09-13 12:39:32.563   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:39:32.663  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:39:36.013   774  1236 V AlarmManager: Expired Alarm result :4
,09-13 12:39:36.053  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-13 12:39:36.053  1381  1381 I PERF    : received broadcast android.intent.action.TIME_TICK
,09-13 12:39:36.063  1381  1381 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:39:36.113  1381  1381 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 12:39:36.113   774   849 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,09-13 12:39:36.123   774  3741 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:39:36.123   774  3741 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:39:36.123   774  3741 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 12:39:36.123   774  3741 D BatteryService: stay LED for fully charged
,09-13 12:39:36.123  1381  1381 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 12:39:36.143  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:39:36.143  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:39:36.143  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:39:36.143   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 12:39:36.143  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:39:36.153  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:39:36.163  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:39:36.163  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:39:36.163   774   774 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,09-13 12:39:36.163   774   774 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,09-13 12:39:36.163  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:39:36.173  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:39:36.173   774   774 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,09-13 12:39:36.193  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:39:36.193  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:39:36.193  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:39:36.193  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:39:36.193  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:39:36.193   774   774 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,09-13 12:39:36.203  2310  2498 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
09-13 12:39:36.203  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:39:36.203  2310  2498 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
09-13 12:39:36.203  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.203  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.203  2310  2498 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
09-13 12:39:36.203  2310  2498 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,09-13 12:39:36.213   774   774 I MotionRecognitionService: Plugged
09-13 12:39:36.213   774   774 D MotionRecognitionService:   cableConnection= 1
09-13 12:39:36.213   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:39:36.213   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:39:36.213  2310  2546 D bt_upio : upio_start_stop_timer : timer_settime success
09-13 12:39:36.213  2310  2546 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 12:39:36.213  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.213  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.213  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.213  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.213  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.213  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.223  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.223  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.223  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.223  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.223  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.223  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.223  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.223  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.223  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.223  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.223  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.223  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.223  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.223  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.223  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.223  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.223  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.223  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.223   774  1501 V AlarmManager:  remove PendingIntent] PendingIntent{90576fa: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
09-13 12:39:36.223  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.223  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.223  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.223  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.223  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.223  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.233  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.233  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.233  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.233  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.233  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.233  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.233  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.233  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.233  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.233  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.233  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.233  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.233  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.233  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.233  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.233  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.233  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.233  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.233   774  1415 V AlarmManager:  remove PendingIntent] PendingIntent{f004ab: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
09-13 12:39:36.233  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.233  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.233  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.233  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.233  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.233  2310  2546 D bt_upio : BT_WAKE is asserted already
,09-13 12:39:36.243  2310  2546 D bt_vendor: op for 7
09-13 12:39:36.243  2310  2546 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 12:39:36.243  2310  2546 D bt_upio : BT_WAKE is asserted already
09-13 12:39:36.243  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 12:39:36.253   774   787 V AlarmManager:  remove PendingIntent] PendingIntent{ee04708: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.263   774  1742 V AlarmManager:  remove PendingIntent] PendingIntent{352dea1: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.273   774   788 V AlarmManager:  remove PendingIntent] PendingIntent{ba408c6: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.273   774  1612 V AlarmManager:  remove PendingIntent] PendingIntent{ea84087: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.273   774  1717 V AlarmManager:  remove PendingIntent] PendingIntent{b6cbb4: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.283   774  1501 V AlarmManager:  remove PendingIntent] PendingIntent{11dc3dd: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.283   774   787 V AlarmManager:  remove PendingIntent] PendingIntent{547eb52: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.283   774  2439 V AlarmManager:  remove PendingIntent] PendingIntent{cbe5e23: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.293   774  1320 V AlarmManager:  remove PendingIntent] PendingIntent{fceef20: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.293   774   788 V AlarmManager:  remove PendingIntent] PendingIntent{ab7c0d9: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.293   774  1612 V AlarmManager:  remove PendingIntent] PendingIntent{dd56a9e: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.293   774  1717 V AlarmManager:  remove PendingIntent] PendingIntent{e8eb97f: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.303   774  1501 V AlarmManager:  remove PendingIntent] PendingIntent{683dd4c: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.303   774   787 V AlarmManager:  remove PendingIntent] PendingIntent{85a9195: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.303   774  2439 V AlarmManager:  remove PendingIntent] PendingIntent{52992aa: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.303   774  1320 V AlarmManager:  remove PendingIntent] PendingIntent{6df6e9b: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.313   774   788 V AlarmManager:  remove PendingIntent] PendingIntent{7b78238: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.313   774  1612 V AlarmManager:  remove PendingIntent] PendingIntent{21fb211: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.313   774  1717 V AlarmManager:  remove PendingIntent] PendingIntent{9e62f76: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.323   774  1501 V AlarmManager:  remove PendingIntent] PendingIntent{4bc5977: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.323   774   787 V AlarmManager:  remove PendingIntent] PendingIntent{7e89e4: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.323   774  3741 V AlarmManager:  remove PendingIntent] PendingIntent{e3c5e4d: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.323   774  1742 V AlarmManager:  remove PendingIntent] PendingIntent{fdcd02: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.333   774  2422 V AlarmManager:  remove PendingIntent] PendingIntent{2131613: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.333   774   788 V AlarmManager:  remove PendingIntent] PendingIntent{88c6050: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.333   774  1415 V AlarmManager:  remove PendingIntent] PendingIntent{6fd9249: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.333   774  2439 V AlarmManager:  remove PendingIntent] PendingIntent{9ffb74e: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.333   774  1717 V AlarmManager:  remove PendingIntent] PendingIntent{f006f: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.343   774  1501 V AlarmManager:  remove PendingIntent] PendingIntent{d5f317c: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.343   774  1726 V AlarmManager:  remove PendingIntent] PendingIntent{4840a05: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.343   774  1612 V AlarmManager:  remove PendingIntent] PendingIntent{c23fa5a: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.343   774  1646 V AlarmManager:  remove PendingIntent] PendingIntent{d35348b: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.353   774  1320 V AlarmManager:  remove PendingIntent] PendingIntent{42be968: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.353   774  1725 V AlarmManager:  remove PendingIntent] PendingIntent{6404181: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.353   774   787 V AlarmManager:  remove PendingIntent] PendingIntent{8176226: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.353   774  3741 V AlarmManager:  remove PendingIntent] PendingIntent{1408e67: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.353   774  1742 V AlarmManager:  remove PendingIntent] PendingIntent{e8a3414: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.363   774  2422 V AlarmManager:  remove PendingIntent] PendingIntent{82e74bd: PendingIntentRecord{6811525 com.android.bluetooth broadcastIntent}}
,09-13 12:39:36.553   774  1218 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,09-13 12:39:36.563   774   915 D LightsService: [SvcLED]  onSensorChanged::light value = 0
09-13 12:39:36.563   774   915 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,09-13 12:39:36.563   774   915 D SensorManager: unregisterListener ::   
09-13 12:39:36.563   774   915 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,09-13 12:39:36.563   774   915 V AlarmManager:  remove PendingIntent] PendingIntent{d2bd13c: PendingIntentRecord{5d08ec5 android broadcastIntent}}
,09-13 12:39:37.013  2310  2735 D bt_upio : ..proc_btwrite_timeout..
,09-13 12:39:37.013  2310  2735 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 12:39:37.803   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:39:37.803   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:39:37.803   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:39:42.623   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:39:47.813   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:39:47.813   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:39:47.813   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:39:52.683   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:39:59.403   774  1568 E Watchdog: !@Sync 31 [09-13 12:39:59.408]
,09-13 12:39:59.993   774  1236 V AlarmManager: Expired Alarm result :8
,09-13 12:40:02.733   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:40:02.883   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:40:02.883   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:40:02.883   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:40:06.153   774  2439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:40:06.163   774  2439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:40:06.163   774  2439 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:40:06.163   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:40:06.183   774   774 I MotionRecognitionService: Plugged
,09-13 12:40:06.183   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:40:06.183   774  2439 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,09-13 12:40:06.193   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:40:06.193   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:40:06.193   774  2439 D BatteryService: stay LED for fully charged
,09-13 12:40:06.213  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:40:06.213  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:40:06.223  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:40:06.233  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:40:06.233  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:40:06.243  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:40:06.243  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:40:06.243  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:40:12.793   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:40:12.883   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:40:12.883   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:40:12.883   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:40:22.843   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0,
,09-13 12:40:27.963   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:40:27.963   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:40:27.963   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:40:29.413   774  1568 E Watchdog: !@Sync 32 [09-13 12:40:29.414]
,09-13 12:40:32.513  4804  6144 I PlayCommon: [690] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:40:32.513  4804  6144 I PlayCommon: [690] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:40:32.683  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:40:32.923   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:40:32.933  1747  1815 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 230ms lastUpdatedAfter : 180439ms
,09-13 12:40:36.233   774  1725 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:40:36.243   774  1725 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:40:36.243   774  1725 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:40:36.243   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:40:36.253   774   774 I MotionRecognitionService: Plugged
,09-13 12:40:36.263   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:40:36.263   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:40:36.263   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:40:36.273   774  1725 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,09-13 12:40:36.273   774  1725 D BatteryService: stay LED for fully charged
,09-13 12:40:36.273  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:40:36.273  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:40:36.273  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:40:36.293  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:40:36.293  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:40:36.303  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:40:36.303  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:40:36.303  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:40:37.963   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:40:37.963   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:40:37.963   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:40:42.973   774  3409 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,09-13 12:40:53.023   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 300, LCD = 0
,09-13 12:40:53.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:40:53.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:40:53.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:40:59.413   774  1568 E Watchdog: !@Sync 33 [09-13 12:40:59.419]
,09-13 12:41:03.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:41:03.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:41:03.043   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:41:03.123   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 300, LCD = 0
,09-13 12:41:06.293   774  2439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:41:06.303   774  2439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:41:06.303   774  2439 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:41:06.313   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:41:06.323   774   774 I MotionRecognitionService: Plugged
,09-13 12:41:06.323   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:41:06.323   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:41:06.323   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:41:06.333   774  2439 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,09-13 12:41:06.333   774  2439 D BatteryService: stay LED for fully charged
,09-13 12:41:06.343  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:41:06.343  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:41:06.353  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:41:06.373  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:41:06.373  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:41:06.383  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:41:06.383  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:41:06.383  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:41:13.183   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 300, LCD = 0
,09-13 12:41:18.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:41:18.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:41:18.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:41:23.243   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 300, LCD = 0
,09-13 12:41:28.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:41:28.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:41:28.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:41:29.413   774  1568 E Watchdog: !@Sync 34 [09-13 12:41:29.423]
,09-13 12:41:32.943  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:41:33.303   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 300, LCD = 0
,09-13 12:41:36.363   774  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:41:36.373   774  2422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:41:36.373   774  2422 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:41:36.373   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:41:36.393   774   774 I MotionRecognitionService: Plugged
,09-13 12:41:36.393   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:41:36.393   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:41:36.403   774  2422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,09-13 12:41:36.403   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:41:36.403   774  2422 D BatteryService: stay LED for fully charged
,09-13 12:41:36.423  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:41:36.423  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:41:36.423  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:41:36.443  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:41:36.443  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:41:36.453  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:41:36.453  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:41:36.453  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:41:43.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:41:43.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:41:43.203   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:41:43.373   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 300, LCD = 0
,09-13 12:41:53.253   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:41:53.253   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:41:53.253   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:41:53.443   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,09-13 12:41:59.423   774  1568 E Watchdog: !@Sync 35 [09-13 12:41:59.428]
,09-13 12:42:03.493   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,09-13 12:42:06.433   774  2439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:42:08.323   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:42:08.323   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:42:08.323   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:42:13.553   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,09-13 12:42:18.323   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-13 12:42:18.323   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:42:18.323   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:42:23.613   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:42:29.423   774  1568 E Watchdog: !@Sync 36 [09-13 12:42:29.432]
,09-13 12:42:33.043  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:42:33.403   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:42:33.403   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:42:33.403   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:42:33.683   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:42:36.503   774  3741 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:42:36.513   774  3741 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:42:36.513   774  3741 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:42:36.513   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:42:36.523   774   774 I MotionRecognitionService: Plugged
,09-13 12:42:36.533   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:42:36.533   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:42:36.533   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:42:36.543   774  3741 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,09-13 12:42:36.543   774  3741 D BatteryService: stay LED for fully charged
,09-13 12:42:36.563  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:42:36.563  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:42:36.563  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:42:36.583  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:42:36.583  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:42:36.593  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:42:36.593  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:42:36.593  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:42:43.393   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:42:43.393   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:42:43.393   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:42:43.743   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:42:53.793   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:42:58.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:42:58.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:42:58.483   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:42:59.433   774  1568 E Watchdog: !@Sync 37 [09-13 12:42:59.437]
,09-13 12:43:03.843   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:43:06.573   774  1725 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:43:08.473   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:43:08.473   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:43:08.473   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:43:13.903   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:43:23.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:43:23.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:43:23.563   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:43:23.953   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:43:29.433   774  1568 E Watchdog: !@Sync 38 [09-13 12:43:29.441]
,09-13 12:43:33.093  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:43:33.323  1747  1815 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 208ms lastUpdatedAfter : 180386ms
,09-13 12:43:33.573   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:43:33.573   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:43:33.573   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:43:34.013   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:43:36.643   774  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:43:36.643   774  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:43:36.653   774  1320 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:43:36.653   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:43:36.663   774   774 I MotionRecognitionService: Plugged
,09-13 12:43:36.663   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:43:36.673   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:43:36.673   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:43:36.673   774  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,09-13 12:43:36.683   774  1320 D BatteryService: stay LED for fully charged
,09-13 12:43:36.693  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:43:36.693  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:43:36.693  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:43:36.723  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:43:36.723  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:43:36.723  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:43:36.723  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:43:36.723  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:43:44.063   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:43:48.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:43:48.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:43:48.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:43:54.113   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:43:58.653   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:43:58.653   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:43:58.653   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:43:59.453   774  1568 E Watchdog: !@Sync 39 [09-13 12:43:59.445]
,09-13 12:44:04.193   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:44:06.713   774  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:44:06.713   774  1415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:44:06.723   774  1415 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:44:06.723   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:44:06.733   774   774 I MotionRecognitionService: Plugged
,09-13 12:44:06.733   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:44:06.743   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:44:06.743   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:44:06.743   774  1415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,09-13 12:44:06.753   774  1415 D BatteryService: stay LED for fully charged
,09-13 12:44:06.763  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:44:06.773  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:44:06.773  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:44:06.783  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:44:06.783  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:44:06.793  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:44:06.793  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:44:06.793  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:44:13.763   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:44:13.763   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:44:13.763   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:44:14.193   774  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,09-13 12:44:14.193   774  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,09-13 12:44:14.193   774  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:44:14.253   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:44:15.683   774  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:44:15.683   774  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:44:15.693   774  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:44:15.693   774  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:44:23.763   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:44:23.763   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:44:23.763   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:44:24.343   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:44:26.183   774   842 I UsageStatsService: User[0] Flushing usage stats to disk
,09-13 12:44:29.463   774  1568 E Watchdog: !@Sync 40 [09-13 12:44:29.465]
,09-13 12:44:33.383  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:44:34.423   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:44:36.783   774  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:44:36.783   774  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:44:36.793   774  1320 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:44:36.793   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:44:36.803   774   774 I MotionRecognitionService: Plugged
,09-13 12:44:36.803   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:44:36.813   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:44:36.813   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:44:36.813   774  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,09-13 12:44:36.823   774  1320 D BatteryService: stay LED for fully charged
,09-13 12:44:36.823  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:44:36.823  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:44:36.823  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:44:36.833  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:44:36.843  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:44:36.853  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:44:36.853  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:44:36.853  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:44:38.843   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:44:38.843   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:44:38.843   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:44:44.493   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:44:48.843   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:44:48.843   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:44:48.843   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:44:53.233  4804  4883 I PlayCommon: [669] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:44:53.233  4804  4883 I PlayCommon: [669] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:44:54.543   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:44:59.463   774  1568 E Watchdog: !@Sync 41 [09-13 12:44:59.470]
,09-13 12:45:03.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:45:03.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:45:03.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:45:04.593   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:45:06.853   774  2439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:45:06.863   774  2439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:45:06.863   774  2439 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:45:06.863   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:45:06.873   774   774 I MotionRecognitionService: Plugged
,09-13 12:45:06.883   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:45:06.883   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:45:06.883   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:45:06.893   774  2439 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,09-13 12:45:06.893   774  2439 D BatteryService: stay LED for fully charged
,09-13 12:45:06.913  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:45:06.913  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:45:06.913  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:45:06.933  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:45:06.933  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:45:06.943  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:45:06.943  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:45:06.943  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:45:13.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:45:13.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:45:13.923   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:45:13.943   774  1320 I ActivityManager: Killing 6983:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 604s, lastActivityTime 604s
,09-13 12:45:14.033   292   292 I ServiceManager: service 'AtCmdFwd' died
,09-13 12:45:14.033   376  4821 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,09-13 12:45:14.033   376  4821 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:45:14.043   774  1501 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,09-13 12:45:14.043   774  1501 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
09-13 12:45:14.043   774  1501 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,09-13 12:45:14.653   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:45:15.033   376  4821 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:45:15.123   774   849 I ActivityManager: Start proc 7187:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,09-13 12:45:15.133  7187  7187 E Zygote  : v2
,09-13 12:45:15.133  7187  7187 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:45:15.133  7187  7187 I libpersona: KNOX_SDCARD not a persona
,09-13 12:45:15.143  7187  7187 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:45:15.143  7187  7187 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:45:15.143  7187  7187 E Zygote  : accessInfo : 0
,09-13 12:45:15.193  7187  7187 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:45:15.193  7187  7187 D ActivityThread: Added TimaKeyStore provider
,09-13 12:45:15.213  7187  7187 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,09-13 12:45:15.233  7187  7187 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,09-13 12:45:15.233  7187  7187 D AtFwdService: onCreate method
,09-13 12:45:15.233  7187  7187 I AtFwdService: Instantiate AtCmdFwd Service
,09-13 12:45:15.253  7187  7199 D AtCkpdCmdHandler: De-queing command
,09-13 12:45:24.703   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:45:29.003   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:45:29.003   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:45:29.003   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:45:29.023   774  1415 I ActivityManager: Killing 7019:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 608s, lastActivityTime 608s
,09-13 12:45:29.033   774  1415 I ActivityManager: Killing 6997:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 609s, lastActivityTime 609s
,09-13 12:45:29.113   774  2422 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,09-13 12:45:29.113   774  2422 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
09-13 12:45:29.113   774  2422 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
,09-13 12:45:29.123   774  2439 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,09-13 12:45:29.123   774  2439 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
09-13 12:45:29.123   774  2439 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 10986ms
,09-13 12:45:29.473   774  1568 E Watchdog: !@Sync 42 [09-13 12:45:29.474]
,09-13 12:45:30.173   774   849 I ActivityManager: Start proc 7201:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,09-13 12:45:30.183  7201  7201 E Zygote  : v2
,09-13 12:45:30.183  7201  7201 I libpersona: KNOX_SDCARD checking this for 10026
09-13 12:45:30.183  7201  7201 I libpersona: KNOX_SDCARD not a persona
,09-13 12:45:30.183  7201  7201 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:45:30.193  7201  7201 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:45:30.193  7201  7201 E Zygote  : accessInfo : 0
,09-13 12:45:30.193  7201  7201 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,09-13 12:45:30.233  7201  7201 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:45:30.233  7201  7201 D ActivityThread: Added TimaKeyStore provider
,09-13 12:45:30.263  7201  7201 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,09-13 12:45:30.273  7201  7201 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,09-13 12:45:30.283  7201  7201 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,09-13 12:45:30.283  7201  7201 D ContextualPageNotification: resetAllNotification : all clear!!!
,09-13 12:45:32.513  4804  6144 I PlayCommon: [690] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:45:32.523  4804  6144 I PlayCommon: [690] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:45:33.493  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:45:34.763   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:45:36.923   774  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:45:36.933   774  2422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:45:36.933   774  2422 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:45:36.933   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:45:36.953   774  2422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,09-13 12:45:36.963   774  2422 D BatteryService: stay LED for fully charged
,09-13 12:45:36.973  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:45:36.973  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:45:36.973  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:45:36.973   774   774 I MotionRecognitionService: Plugged
,09-13 12:45:36.973   774   774 D MotionRecognitionService:   cableConnection= 1
09-13 12:45:36.973   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 12:45:36.973   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:45:36.983  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:45:36.983  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:45:36.993  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:45:37.003  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:45:37.003  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:45:39.023   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:45:39.023   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:45:39.023   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:45:40.173   774   849 I ActivityManager: Start proc 7215:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
09-13 12:45:40.173   774  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-13 12:45:40.193  7215  7215 E Zygote  : v2
,09-13 12:45:40.193  7215  7215 I libpersona: KNOX_SDCARD checking this for 10181
09-13 12:45:40.193  7215  7215 I libpersona: KNOX_SDCARD not a persona
,09-13 12:45:40.193  7215  7215 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:45:40.193  7215  7215 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:45:40.193  7215  7215 E Zygote  : accessInfo : 0
,09-13 12:45:40.193  7215  7215 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,09-13 12:45:40.243  7215  7215 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:45:40.243  7215  7215 D ActivityThread: Added TimaKeyStore provider
,09-13 12:45:40.263   774  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,09-13 12:45:40.273  7215  7215 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,09-13 12:45:40.283  7215  7215 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,09-13 12:45:40.313  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,09-13 12:45:40.313  7215  7215 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,09-13 12:45:40.323   774   849 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fd29fb9 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b6e8ffe 7215:com.sec.android.daemonapp/u0a181}
,09-13 12:45:40.333  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,09-13 12:45:40.333  7215  7215 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,09-13 12:45:40.333  7215  7215 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,09-13 12:45:40.333  7215  7215 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,09-13 12:45:40.333  7215  7215 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,09-13 12:45:40.343  7215  7215 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,09-13 12:45:40.353  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:45:40.353  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,09-13 12:45:40.353  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,09-13 12:45:40.363  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:45:40.363  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
09-13 12:45:40.363  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,09-13 12:45:40.363  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,09-13 12:45:40.383  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,09-13 12:45:40.393  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:45:40.393  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
09-13 12:45:40.393  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,09-13 12:45:40.393  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,09-13 12:45:40.393  7215  7215 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,09-13 12:45:40.403  7215  7215 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,09-13 12:45:40.403  7215  7215 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
09-13 12:45:40.403  7215  7215 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 12:45:40.403  7215  7215 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,09-13 12:45:40.403  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,09-13 12:45:40.403  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,09-13 12:45:40.403  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
09-13 12:45:40.403  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
09-13 12:45:40.403  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,09-13 12:45:40.403  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:45:40.413  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,09-13 12:45:40.413   774  3741 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61fae0a u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b6e8ffe 7215:com.sec.android.daemonapp/u0a181}
,09-13 12:45:40.423  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:45:40.423  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
09-13 12:45:40.423  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 12:45:40.423  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:45:40.433  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,09-13 12:45:40.433  7215  7215 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:45:40.433  7215  7215 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,09-13 12:45:40.433  7215  7215 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 12:45:40.433  7215  7215 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:45:40.433  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,09-13 12:45:40.433  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
09-13 12:45:40.433  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
09-13 12:45:40.433  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
09-13 12:45:40.433  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,09-13 12:45:40.433  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:45:40.433  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,09-13 12:45:40.443   774  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{840567b u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b6e8ffe 7215:com.sec.android.daemonapp/u0a181}
,09-13 12:45:40.443  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:45:40.443  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
09-13 12:45:40.443  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 12:45:40.453  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:45:40.453  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,09-13 12:45:40.453  7215  7215 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:45:40.453  7215  7215 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,09-13 12:45:40.453  7215  7215 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 12:45:40.453  7215  7215 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:45:40.453  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
09-13 12:45:40.453  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,09-13 12:45:40.453  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
09-13 12:45:40.453  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
09-13 12:45:40.453  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,09-13 12:45:40.453  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:45:40.463  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,09-13 12:45:40.463   774  1501 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{be07c98 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b6e8ffe 7215:com.sec.android.daemonapp/u0a181}
,09-13 12:45:40.473  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,09-13 12:45:40.473  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
09-13 12:45:40.473  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 12:45:40.483  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:45:40.483  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,09-13 12:45:40.483  7215  7215 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:45:40.483  7215  7215 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,09-13 12:45:40.483  7215  7215 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 12:45:40.483  7215  7215 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:45:40.483  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
09-13 12:45:40.483  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,09-13 12:45:40.483  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
09-13 12:45:40.483  7215  7215 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
09-13 12:45:40.483  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,09-13 12:45:40.483  7215  7215 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 12:45:40.493  7215  7215 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,09-13 12:45:44.823   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:45:54.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:45:54.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:45:54.123   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:45:54.133   774  1612 I ActivityManager: Killing 7047:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 601s, lastActivityTime 601s
,09-13 12:45:54.203   774  1726 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,09-13 12:45:54.203   774  1726 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
09-13 12:45:54.203   774  1726 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 1000ms
,09-13 12:45:54.873   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:45:55.273   774   849 I ActivityManager: Start proc 7236:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService
,09-13 12:45:55.283  7236  7236 E Zygote  : v2
,09-13 12:45:55.283  7236  7236 I libpersona: KNOX_SDCARD checking this for 10034
09-13 12:45:55.283  7236  7236 I libpersona: KNOX_SDCARD not a persona
,09-13 12:45:55.283  7236  7236 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 12:45:55.283  7236  7236 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 12:45:55.293  7236  7236 E Zygote  : accessInfo : 0
,09-13 12:45:55.293  7236  7236 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,09-13 12:45:55.333  7236  7236 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:45:55.333  7236  7236 D ActivityThread: Added TimaKeyStore provider
,09-13 12:45:55.363  7236  7236 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,09-13 12:45:55.383  7236  7236 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,09-13 12:45:55.393  7236  7236 I MultiDex: VM with version 2.1.0 has multidex support
,09-13 12:45:55.393  7236  7236 I MultiDex: install
09-13 12:45:55.393  7236  7236 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-13 12:45:55.393  7236  7236 I MultiDex: install
09-13 12:45:55.393  7236  7236 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 12:45:55.463  7236  7236 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,09-13 12:45:55.463  7236  7236 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,09-13 12:45:55.483  1381  1381 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,09-13 12:45:55.493  1381  1381 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{27047b4 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,09-13 12:45:55.493  1381  1381 D AdaptiveEventManager: M updateContainers()
09-13 12:45:55.493  1381  1381 D AdaptiveEventContainerSmall: C updatePedoContainer()
09-13 12:45:55.493  1381  1381 D AdaptiveEventContainerSmall: handlePedoUpdate()
,09-13 12:45:55.493  1381  1381 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,09-13 12:45:55.493   774  1612 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,09-13 12:45:55.503   774  1501 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,09-13 12:45:55.503   774  1726 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,09-13 12:45:55.513   774  2422 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,09-13 12:45:55.533  7236  7236 I Health.HealthService: HealthService: onCreate() start (7236)
,09-13 12:45:55.663  7236  7236 D HealthDataStore: Service for HealthDataStore is connected
,09-13 12:45:55.663  7236  7236 D HealthDataStore: HealthConnectionErrorResult code : 9
,09-13 12:45:55.663  7236  7236 D HealthConsole: Service for HealthDataConsole is connected
,09-13 12:45:55.663  7236  7236 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,09-13 12:45:55.663  7236  7236 E HealthDataStore: disconnectService: Context instance is invalid
,09-13 12:45:55.823  7236  7257 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,09-13 12:45:55.863  7236  7261 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,09-13 12:45:55.873  7063  7074 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,09-13 12:45:56.053  7236  7261 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,09-13 12:45:56.163  7236  7261 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
09-13 12:45:56.163  7236  7261 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,09-13 12:45:59.473   774  1568 E Watchdog: !@Sync 43 [09-13 12:45:59.482]
,09-13 12:46:04.103   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:46:04.103   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:46:04.103   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:46:04.933   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:46:06.993   774  1726 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:46:06.993   774  1726 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:46:07.003   774  1726 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:46:07.003   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:46:07.013   774   774 I MotionRecognitionService: Plugged
,09-13 12:46:07.013   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:46:07.023   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:46:07.023   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:46:07.023   774  1726 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,09-13 12:46:07.033   774  1726 D BatteryService: stay LED for fully charged
,09-13 12:46:07.043  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:46:07.043  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:46:07.043  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:46:07.073  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:46:07.073  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:46:07.073  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:46:07.083  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:46:07.083  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:46:14.983   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:46:19.163   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:46:19.163   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:46:19.163   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:46:25.043   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:46:29.193   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:46:29.193   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:46:29.193   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:46:29.483   774  1568 E Watchdog: !@Sync 44 [09-13 12:46:29.487]
,09-13 12:46:33.523  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:46:33.723  1747  1815 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 184ms lastUpdatedAfter : 180398ms
,09-13 12:46:35.093   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:46:37.063   774  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:46:37.073   774  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:46:37.073   774  1320 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:46:37.073   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:46:37.083   774   774 I MotionRecognitionService: Plugged
,09-13 12:46:37.093   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:46:37.093   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:46:37.093   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:46:37.103   774  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,09-13 12:46:37.103   774  1320 D BatteryService: stay LED for fully charged
,09-13 12:46:37.123  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:46:37.123  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:46:37.123  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:46:37.133  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:46:37.133  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:46:37.143  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:46:37.143  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:46:37.143  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:46:44.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:46:44.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:46:44.283   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:46:45.143   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:46:54.273   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:46:54.273   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:46:54.273   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:46:55.203   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:46:59.483   774  1568 E Watchdog: !@Sync 45 [09-13 12:46:59.491]
,09-13 12:47:05.263   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:47:07.143   774  1726 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:47:09.363   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:47:09.363   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:47:09.363   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:47:15.323   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:47:19.353   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:47:19.353   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:47:19.353   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:47:25.383   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:47:29.493   774  1568 E Watchdog: !@Sync 46 [09-13 12:47:29.495]
,09-13 12:47:33.773  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:47:34.443   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:47:34.443   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:47:34.443   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:47:35.433   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:47:37.213   774   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:47:44.443   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:47:44.443   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:47:44.443   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:47:45.493   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:47:55.553   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:47:59.493   774  1568 E Watchdog: !@Sync 47 [09-13 12:47:59.500]
,09-13 12:47:59.523   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:47:59.523   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:47:59.523   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:48:05.623   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:48:07.273   774  1646 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:48:07.283   774  1646 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:48:07.283   774  1646 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:48:07.283   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:48:07.303   774   774 I MotionRecognitionService: Plugged
,09-13 12:48:07.303   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:48:07.303   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:48:07.303   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:48:07.313   774  1646 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,09-13 12:48:07.313   774  1646 D BatteryService: stay LED for fully charged
,09-13 12:48:07.323  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:48:07.323  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:48:07.323  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:48:07.333  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:48:07.333  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:48:07.343  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:48:07.343  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:48:07.353  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:48:09.523   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:48:09.523   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:48:09.523   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:48:15.673   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:48:24.603   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:48:24.603   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:48:24.603   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:48:25.773   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:48:25.863   774   784 I art     : Background sticky concurrent mark sweep GC freed 62759(7MB) AllocSpace objects, 379(7MB) LOS objects, 26% free, 42MB/58MB, paused 2.584ms total 134.861ms
,09-13 12:48:29.493   774  1568 E Watchdog: !@Sync 48 [09-13 12:48:29.504]
,09-13 12:48:33.843  1747  1815 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 12:48:34.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:48:34.643   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:48:34.653   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:48:35.853   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:48:37.343   774  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:48:37.353   774  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:48:37.353   774  1320 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:48:37.353   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:48:37.363   774   774 I MotionRecognitionService: Plugged
,09-13 12:48:37.373   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:48:37.373   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:48:37.373   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:48:37.383   774  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,09-13 12:48:37.383   774  1320 D BatteryService: stay LED for fully charged
,09-13 12:48:37.393  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:48:37.393  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:48:37.393  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:48:37.423  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:48:37.423  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:48:37.423  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:48:37.423  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:48:37.423  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:48:45.913   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:48:49.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:48:49.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:48:49.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:48:55.993   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:48:59.503   774  1568 E Watchdog: !@Sync 49 [09-13 12:48:59.508]
,09-13 12:48:59.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 12:48:59.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 12:48:59.723   319  1100 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 12:49:06.053   774  3409 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,09-13 12:49:07.413   774  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:49:07.413   774  2422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 12:49:07.423   774  2422 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 12:49:07.423   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:49:07.433   774   774 I MotionRecognitionService: Plugged
,09-13 12:49:07.443   774   774 D MotionRecognitionService:   cableConnection= 1
,09-13 12:49:07.443   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 12:49:07.443   774   774 D MotionRecognitionService: skip setTransmitPower. 
,09-13 12:49:07.453   774  2422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,09-13 12:49:07.453   774  2422 D BatteryService: stay LED for fully charged
,09-13 12:49:07.473  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:49:07.473  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:49:07.473  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:49:07.483  2310  2310 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:49:07.483  2310  2752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 12:49:07.493  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:49:07.493  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:49:07.493  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1400000ms)
```
