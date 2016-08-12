#### Test 79751015f24a8ad_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
08-12 17:14:30.883   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
08-12 17:14:31.963  5365  5365 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-12 17:14:31.963  5365  5365 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-12 17:14:31.963  5365  5365 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-12 17:14:31.963  5365  5365 I art     : System.exit called, status: 0
08-12 17:14:31.963  5365  5365 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-12 17:14:31.993   773  1648 I ActivityManager: Process com.samsung.aasaservice (pid 5365)(adj 0) has died(121,730)
08-12 17:14:31.993   773  1648 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-12 17:14:31.993   773  1648 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-12 17:14:31.993  5307  5307 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-12 17:14:31.993   773  1648 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-12 17:14:32.013  6397  6397 E Zygote  : v2
08-12 17:14:32.013  6397  6397 I libpersona: KNOX_SDCARD checking this for 10014
08-12 17:14:32.013  6397  6397 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:32.023  6397  6397 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:32.023  6397  6397 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:32.023  6397  6397 E Zygote  : accessInfo : 0
08-12 17:14:32.023  6397  6397 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-12 17:14:32.043  6397  6397 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:32.043  6397  6397 D ActivityThread: Added TimaKeyStore provider
08-12 17:14:32.043   773   861 I ActivityManager: Start proc 6397:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-12 17:14:32.043   773  1327 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 17:14:32.053   773  1550 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{21f5668 6397:com.google.android.partnersetup/u0a14}
08-12 17:14:32.053   773  1327 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-12 17:14:32.063  6397  6397 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-12 17:14:32.093  6397  6397 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-12 17:14:32.123   773  1780 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{21f5668 6397:com.google.android.partnersetup/u0a14}
08-12 17:14:32.153  6415  6415 E Zygote  : v2
08-12 17:14:32.153  6415  6415 I libpersona: KNOX_SDCARD checking this for 10015
08-12 17:14:32.153  6415  6415 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:32.153   773  1298 I ActivityManager: Start proc 6415:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-12 17:14:32.153  6415  6415 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:32.153  6415  6415 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:32.153  6415  6415 E Zygote  : accessInfo : 0
08-12 17:14:32.153  6415  6415 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-12 17:14:32.173   773   788 I ActivityManager: Killing 5491:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
08-12 17:14:32.183  6415  6415 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:32.183  6415  6415 D ActivityThread: Added TimaKeyStore provider
08-12 17:14:32.193   773  1324 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b689f67 6415:com.samsung.groupcast/u0a15}
08-12 17:14:32.193   773  1748 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
08-12 17:14:32.193  6415  6415 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-12 17:14:32.213  6415  6415 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-12 17:14:32.233  6415  6415 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-12 17:14:32.243  6415  6415 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-12 17:14:32.243  6415  6415 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-12 17:14:32.243  6415  6415 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-12 17:14:32.243  6415  6415 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-12 17:14:32.243  6415  6415 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 17:14:32.243  6415  6415 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 17:14:32.243  6415  6415 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 17:14:32.243  6415  6415 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 17:14:32.243  6415  6415 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:14:32.243  6415  6415 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 17:14:32.243  6415  6415 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 17:14:32.243  6415  6415 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:14:32.243  6415  6415 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 17:14:32.243  6415  6415 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 17:14:32.243   773  1780 I ActivityManager: Killing 5181:com.android.mms/u0a49 (adj 15): DHA:empty #37
08-12 17:14:32.253   773  1780 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d1fca51 1887:com.sec.android.app.shealth:remote/u0a34}
08-12 17:14:32.263   773  1648 D CountryDetector: No listener is left
08-12 17:14:32.263   773  1550 I ActivityManager: Start proc 6430:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-12 17:14:32.263  6430  6430 E Zygote  : v2
08-12 17:14:32.263  6430  6430 I libpersona: KNOX_SDCARD checking this for 10041
08-12 17:14:32.263  6430  6430 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:32.263  6430  6430 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:32.263  6430  6430 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:32.273  6430  6430 E Zygote  : accessInfo : 0
08-12 17:14:32.273  6430  6430 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-12 17:14:32.273   773  1298 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
08-12 17:14:32.293  6430  6430 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:32.293  6430  6430 D ActivityThread: Added TimaKeyStore provider
08-12 17:14:32.293   773   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc77114 6430:com.samsung.android.sdk.samsunglink/u0a41}
08-12 17:14:32.303  6430  6430 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-12 17:14:32.373  2206  2206 E audit   : type=1400 msg=audit(1471014872.373:284): avc:  denied  { execmod } for  pid=6394 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 17:14:32.373  2206  2206 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:32.373  2206  2206 E audit   : type=1300 msg=audit(1471014872.373:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b400b000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=6394 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 17:14:32.373  2206  2206 E audit   : type=1327 msg=audit(1471014872.373:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 17:14:32.373  2206  2206 E audit   : type=1320 msg=audit(1471014872.373:284): 
08-12 17:14:32.383  6430  6430 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 17:14:32.383  6430  6430 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 17:14:32.423  2206  2206 E audit   : type=1400 msg=audit(1471014872.423:285): avc:  denied  { execmod } for  pid=6394 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 17:14:32.423  2206  2206 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:32.423  2206  2206 E audit   : type=1300 msg=audit(1471014872.423:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcb000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=6394 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 17:14:32.423  2206  2206 E audit   : type=1327 msg=audit(1471014872.423:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 17:14:32.423  2206  2206 E audit   : type=1320 msg=audit(1471014872.423:285): 
08-12 17:14:32.443  6430  6430 I SL_DEBUG: isLoggable:: isProductShip = 1
08-12 17:14:32.443  6430  6430 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-12 17:14:32.453   773  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-12 17:14:32.453   773  3915 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-12 17:14:32.453   773  3916 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-12 17:14:32.463   773   789 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-12 17:14:32.463   773  1749 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-12 17:14:32.463   773   788 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-12 17:14:32.463   773  1730 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-12 17:14:32.473   773  1324 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-12 17:14:32.473   773  1594 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-12 17:14:32.473  2206  2206 E audit   : type=1400 msg=audit(1471014872.473:286): avc:  denied  { execmod } for  pid=6394 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 17:14:32.473  2206  2206 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:32.473  2206  2206 E audit   : type=1300 msg=audit(1471014872.473:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcb000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=6394 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 17:14:32.473  2206  2206 E audit   : type=1327 msg=audit(1471014872.473:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 17:14:32.473   773  1731 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-12 17:14:32.473  2206  2206 E audit   : type=1320 msg=audit(1471014872.473:286): 
08-12 17:14:32.473  6394  6394 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 17:14:32.473  6394  6394 D AndroidRuntime: CheckJNI is OFF
08-12 17:14:32.483  6394  6394 D AndroidRuntime: readGMSProperty: start
08-12 17:14:32.483  6394  6394 D AndroidRuntime: readGMSProperty: already setted!!
08-12 17:14:32.483  6394  6394 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 17:14:32.483  6394  6394 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 17:14:32.483  6394  6394 D AndroidRuntime: readGMSProperty: end
08-12 17:14:32.483  6394  6394 D AndroidRuntime: addProductProperty: start
08-12 17:14:32.483  6394  6394 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 17:14:32.483  6394  6394 W art     : aee32000-b1d58000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 17:14:32.483  6394  6394 W art     : b1d58000-b3fc7000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 17:14:32.483  6394  6394 W art     : b3fc7000-b3fc8000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 17:14:32.483  6394  6394 W art     : b3fc8000-b3fc9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.483  6394  6394 W art     : b42fb000-b4324000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 17:14:32.483  6394  6394 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 17:14:32.483  6394  6394 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 17:14:32.483  6394  6394 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 17:14:32.483  6394  6394 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 17:14:32.483  6394  6394 W art     : b489b000-b489e000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 17:14:32.483  6394  6394 W art     : b489e000-b489f000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 17:14:32.483  6394  6394 W art     : b489f000-b48a0000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 17:14:32.483  6394  6394 W art     : b48a0000-b48a1000 r--p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b48a1000-b48c1000 r--s 00000000 00:0b 6572       /dev/__properties__
08-12 17:14:32.483  6394  6394 W art     : b48c1000-b52d2000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 17:14:32.483  6394  6394 W art     : b52d2000-b52d3000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b52d3000-b531c000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 17:14:32.483  6394  6394 W art     : b531c000-b531d000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 17:14:32.483  6394  6394 W art     : b531d000-b5325000 rw-p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5325000-b5326000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.483  6394  6394 W art     : b5326000-b535b000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 17:14:32.483  6394  6394 W art     : b535b000-b535c000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b535c000-b535d000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 17:14:32.483  6394  6394 W art     : b535d000-b535e000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 17:14:32.483  6394  6394 W art     : b535e000-b53b6000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 17:14:32.483  6394  6394 W art     : b53b6000-b53b7000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b53b7000-b53b8000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 17:14:32.483  6394  6394 W art     : b53b8000-b53b9000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 17:14:32.483  6394  6394 W art     : b53ba000-b53c0000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 17:14:32.483  6394  6394 W art     : b53c0000-b53c1000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 17:14:32.483  6394  6394 W art     : b53c1000-b53c2000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 17:14:32.483  6394  6394 W art     : b53c2000-b53c4000 rw-p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b53c5000-b53cf000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 17:14:32.483  6394  6394 W art     : b53cf000-b53d2000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 17:14:32.483  6394  6394 W art     : b53d2000-b53d3000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 17:14:32.483  6394  6394 W art     : b53d4000-b53eb000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 17:14:32.483  6394  6394 W art     : b53eb000-b53ec000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b53ec000-b53ed000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 17:14:32.483  6394  6394 W art     : b53ed000-b53ee000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 17:14:32.483  6394  6394 W art     : b53ef000-b53f9000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 17:14:32.483  6394  6394 W art     : b53f9000-b53fa000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 17:14:32.483  6394  6394 W art     : b53fa000-b53fb000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 17:14:32.483  6394  6394 W art     : b53fb000-b53ff000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 17:14:32.483  6394  6394 W art     : b53ff000-b5400000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 17:14:32.483  6394  6394 W art     : b5400000-b5401000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 17:14:32.483  6394  6394 W art     : b5401000-b5417000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-12 17:14:32.483  6394  6394 W art     : b5417000-b5418000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 17:14:32.483  6394  6394 W art     : b5418000-b5419000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 17:14:32.483  6394  6394 W art     : b5419000-b5426000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 17:14:32.483  6394  6394 W art     : b5426000-b5427000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 17:14:32.483  6394  6394 W art     : b5427000-b5428000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 17:14:32.483  6394  6394 W art     : b5428000-b5488000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 17:14:32.483  6394  6394 W art     : b5488000-b548b000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 17:14:32.483  6394  6394 W art     : b548b000-b548f000 rw-p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b548f000-b54f0000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 17:14:32.483  6394  6394 W art     : b54f0000-b54f1000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 17:14:32.483  6394  6394 W art     : b54f1000-b5540000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 17:14:32.483  6394  6394 W art     : b5540000-b5542000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 17:14:32.483  6394  6394 W art     : b5542000-b5543000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 17:14:32.483  6394  6394 W art     : b5543000-b5544000 rw-p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5544000-b554b000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 17:14:32.483  6394  6394 W art     : b554b000-b554c000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 17:14:32.483  6394  6394 W art     : b554c000-b554d000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-12 17:14:32.483  6394  6394 W art     : avc_common.so
08-12 17:14:32.483  6394  6394 W art     : b554e000-b5551000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 17:14:32.483  6394  6394 W art     : b5551000-b5552000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 17:14:32.483  6394  6394 W art     : b5552000-b5553000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-12 17:14:32.483  6394  6394 W art     : enc_common.so
08-12 17:14:32.483  6394  6394 W art     : b5554000-b5558000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 17:14:32.483  6394  6394 W art     : b5558000-b5559000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5559000-b555a000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 17:14:32.483  6394  6394 W art     : b555a000-b555b000 rw-p 00005000 b3:17 2510       /syste
08-12 17:14:32.483  6394  6394 W art     : m/lib/libpowermanager.so
08-12 17:14:32.483  6394  6394 W art     : b555c000-b5579000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 17:14:32.483  6394  6394 W art     : b5579000-b557a000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 17:14:32.483  6394  6394 W art     : b557a000-b557b000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 17:14:32.483  6394  6394 W art     : b557c000-b5581000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 17:14:32.483  6394  6394 W art     : b5581000-b5582000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 17:14:32.483  6394  6394 W art     : b5582000-b5583000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 17:14:32.483  6394  6394 W art     : b5584000-b55b5000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 17:14:32.483  6394  6394 W art     : b55b5000-b55b8000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 17:14:32.483  6394  6394 W art     : b55b8000-b55b9000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 17:14:32.483  6394  6394 W art     : b55ba000-b55f5000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 17:14:32.483  6394  6394 W art     : b55f5000-b55f6000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 17:14:32.483  6394  6394 W art     : b55f6000-b55f7000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 17:14:32.483  6394  6394 W art     : b55f8000-b55ff000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 17:14:32.483  6394  6394 W art     : b55ff000-b5600000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5600000-b5601000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 17:14:32.483  6394  6394 W art     : b5601000-b5602000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 17:14:32.483  6394  6394 W art     : b5602000-b5603000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.483  6394  6394 W art     : b5603000-b561a000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 17:14:32.483  6394  6394 W art     : b561a000-b561b000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b561b000-b561e000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 17:14:32.483  6394  6394 W art     : b561e000-b561f000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 17:14:32.483  6394  6394 W art     : b561f000-b563e000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 17:14:32.483  6394  6394 W art     : b563e000-b563f000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 17:14:32.483  6394  6394 W art     : b563f000-b5640000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-12 17:14:32.483  6394  6394 W art     : b5640000-b567e000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 17:14:32.483  6394  6394 W art     : b567e000-b567f000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b567f000-b5681000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 17:14:32.483  6394  6394 W art     : b5681000-b5682000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 17:14:32.483  6394  6394 W art     : b5683000-b568a000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 17:14:32.483  6394  6394 W art     : b568a000-b568b000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 17:14:32.483  6394  6394 W art     : b568b000-b568c000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 17:14:32.483  6394  6394 W art     : b568d000-b5690000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 17:14:32.483  6394  6394 W art     : b5690000-b5691000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 17:14:32.483  6394  6394 W art     : b5691000-b5692000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 17:14:32.483  6394  6394 W art     : b5692000-b5698000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 17:14:32.483  6394  6394 W art     : b5698000-b5699000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5699000-b569a000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 17:14:32.483  6394  6394 W art     : b569a000-b569b000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 17:14:32.483  6394  6394 W art     : b569b000-b56a4000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 17:14:32.483  6394  6394 W art     : b56a4000-b56a5000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 17:14:32.483  6394  6394 W art     : b56a5000-b56a6000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 17:14:32.483  6394  6394 W art     : b56a6000-b5737000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 17:14:32.483  6394  6394 W art     : b5737000-b5738000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5738000-b5743000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 17:14:32.483  6394  6394 W art     : b5743000-b5744000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 17:14:32.483  6394  6394 W art     : b5745000-b5757000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 17:14:32.483  6394  6394 W art     : b5757000-b5758000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 17:14:32.483  6394  6394 W art     : b5758000-b5759000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 17:14:32.483  6394  6394 W art     : b575a000-b575f000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 17:14:32.483  6394  6394 W art     : b575f000-b5760000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 17:14:32.483  6394  6394 W art     : b5760000-b5761000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 17:14:32.483  6394  6394 W art     : b5762000-b57cf000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 17:14:32.483  6394  6394 W art     : b57cf000-b57d0000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b57d0000-b57d2000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 17:14:32.483  6394  6394 W art     : b57d2000-b57d3000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 17:14:32.483  6394  6394 W art     : b57d3000-b57d4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.483  6394  6394 W art     : b57d4000-b57db000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 17:14:32.483  6394  6394 W art     : b57db000-b57dc000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 17:14:32.483  6394  6394 W art     : b57dc000-b57dd000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 17:14:32.483  6394  6394 W art     : b57de000-b585e000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 17:14:32.483  6394  6394 W art     : b585e000-b585f000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b585f000-b5860000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 17:14:32.483  6394  6394 W art     : b5860000-b5861000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 17:14:32.483  6394  6394 W art     : b5861000-b5878000 rw-p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5878000-b58af000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 17:14:32.483  6394  6394 W art     : ib/libqc-opt.so
08-12 17:14:32.483  6394  6394 W art     : b58af000-b58b0000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 17:14:32.483  6394  6394 W art     : b58b0000-b58b1000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 17:14:32.483  6394  6394 W art     : b58b1000-b58cd000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 17:14:32.483  6394  6394 W art     : b58cd000-b58ce000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 17:14:32.483  6394  6394 W art     : b58ce000-b58cf000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 17:14:32.483  6394  6394 W art     : b58d0000-b5931000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 17:14:32.483  6394  6394 W art     : b5931000-b5933000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 17:14:32.483  6394  6394 W art     : b5933000-b5934000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 17:14:32.483  6394  6394 W art     : b5935000-b595c000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 17:14:32.483  6394  6394 W art     : b595c000-b595d000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b595d000-b595e000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 17:14:32.483  6394  6394 W art     : b595e000-b595f000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 17:14:32.483  6394  6394 W art     : b5960000-b5968000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 17:14:32.483  6394  6394 W art     : b5968000-b596a000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 17:14:32.483  6394  6394 W art     : b596a000-b596b000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 17:14:32.483  6394  6394 W art     : b596c000-b596f000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 17:14:32.483  6394  6394 W art     : b596f000-b5970000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 17:14:32.483  6394  6394 W art     : b5970000-b5971000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 17:14:32.483  6394  6394 W art     : b5971000-b5975000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 17:14:32.483  6394  6394 W art     : b5975000-b5976000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5976000-b5977000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 17:14:32.483  6394  6394 W art     : b5977000-b5978000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 17:14:32.483  6394  6394 W art     : b5978000-b5988000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 17:14:32.483  6394  6394 W art     : b5988000-b5989000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 17:14:32.483  6394  6394 W art     : b5989000-b598a000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 17:14:32.483  6394  6394 W art     : b598a000-b59d0000 rw-p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b59d0000-b59d9000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 17:14:32.483  6394  6394 W art     : b59d9000-b59da000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 17:14:32.483  6394  6394 W art     : b59da000-b59db000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 17:14:32.483  6394  6394 W art     : b59dc000-b59e1000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 17:14:32.483  6394  6394 W art     : b59e1000-b59e2000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 17:14:32.483  6394  6394 W art     : b59e2000-b59e3000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 17:14:32.483  6394  6394 W art     : b59e3000-b59e6000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 17:14:32.483  6394  6394 W art     : b59e6000-b59e7000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b59e7000-b59e8000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 17:14:32.483  6394  6394 W art     : b59e8000-b59e9000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 17:14:32.483  6394  6394 W art     : b59ea000-b5a02000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 17:14:32.483  6394  6394 W art     : b5a02000-b5a03000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5a03000-b5a04000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 17:14:32.483  6394  6394 W art     : b5a04000-b5a05000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 17:14:32.483  6394  6394 W art     : b5a06000-b5ba0000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 17:14:32.483  6394  6394 W art     : b5ba0000-b5ba1000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5ba1000-b5bae000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 17:14:32.483  6394  6394 W art     : b5bae000-b5baf000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 17:14:32.483  6394  6394 W art     : b5baf000-b5bb3000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 17:14:32.483  6394  6394 W art     : b5bb3000-b5bb4000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5bb4000-b5bb5000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 17:14:32.483  6394  6394 W art     : b5bb5000-b5bb6000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 17:14:32.483  6394  6394 W art     : b5bb6000-b5bc9000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 17:14:32.483  6394  6394 W art     : b5bc9000-b5bca000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 17:14:32.483  6394  6394 W art     : b5bca000-b5bcb000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 17:14:32.483  6394  6394 W art     : b5bcb000-b5bcc000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:14:32.483  6394  6394 W art     : b5bcc000-b5c17000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 17:14:32.483  6394  6394 W art     : b5c17000-b5c18000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 17:14:32.483  6394  6394 W art     : b5c18000-b5c19000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 17:14:32.483  6394  6394 W art     : b5c19000-b5c1b000 rw-p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5c1c000-b5c2d000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 17:14:32.483  6394  6394 W art     : b5c2d000-b5c2e000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5c2e000-b5c2f000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 17:14:32.483  6394  6394 W art     : b5c2f000-b5c30000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 17:14:32.483  6394  6394 W art     : b5c31000-b5c3b000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 17:14:32.483  6394  6394 W art     : b5c3b000-b5c3d000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 17:14:32.483  6394  6394 W art     : b5c3d000-b5c3e000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 17:14:32.483  6394  6394 W art     : b5c3e000-b5c57000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 17:14:32.483  6394  6394 W art     : b5c57000-b5c58000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 17:14:32.483  6394  6394 W art     : b5c58000-b5c5b000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 17:14:32.483  6394  6394 W art     : b5c5b000-b5c5f000 rw-p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5c5f000-b5cd3000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 17:14:32.483  6394  6394 W art     : b5cd3000-b5cd4000 ---p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5cd4000-b5cd7000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 17:14:32.483  6394  6394 W art     : b5cd7000-b5cd8000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 17:14:32.483  6394  6394 W art     : b5cd8000-b5cd9000 r--p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5cd9000-b5cdc000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 17:14:32.483  6394  6394 W art     : b5cdc000-b5cdd000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 17:14:32.483  6394  6394 W art     : b5cdd000-b5cde000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 17:14:32.483  6394  6394 W art     : b5cde000-b5cdf000 r--p 00000000 00:00 0 
08-12 17:14:32.483  6394  6394 W art     : b5cdf000-b5ce4000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 17:14:32.483  6394  6394 W art     : b5ce4000-b5ce5000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 17:14:32.483  6394  6394 W art     : b5ce5000-b5ce6000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 17:14:32.483  6394  6394 W art     : b5ce6000-b5ce7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.483  6394  6394 W art     : b5ce7000-b5cea000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 17:14:32.483  6394  6394 W art     : b5cea000-b5ceb000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 17:14:32.483  6394  6394 W art     : b5ceb000-b5cec000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 17:14:32.483  6394  6394 W art     : b5cec000-b5ced000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.483  6394  6394 W art     : b5ced000-b5cf1000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 17:14:32.483  6394  6394 W art     : b5cf1000-b5cf2000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 17:14:32.483  6394  6394 W art     : b5cf2000-b5cf3000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 17:14:32.483  6394  6394 W art     : b5cf3000-b5cf4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:14:32.483  6394  6394 W art     : b5cf4000-b5cf8000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 17:14:32.483  6394  6394 W art     : b5cf8000-b5cf9000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 17:14:32.483  6394  6394 W art     : b5cf9000-b5cfa000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 17:14:32.493  6394  6394 W art     : b5cfa000-b5cfb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b5cfb000-b5d09000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 17:14:32.493  6394  6394 W art     : b5d09000-b5d0a000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b5d0a000-b5d0b000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 17:14:32.493  6394  6394 W art     : b5d0b000-b5d0c000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 17:14:32.493  6394  6394 W art     : b5d0c000-b5d16000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 17:14:32.493  6394  6394 W art     : b5d16000-b5d19000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 17:14:32.493  6394  6394 W art     : b5d19000-b5d1a000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 17:14:32.493  6394  6394 W art     : b5d1a000-b5d1b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b5d1b000-b5d25000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 17:14:32.493  6394  6394 W art     : b5d25000-b5d28000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 17:14:32.493  6394  6394 W art     : b5d28000-b5d29000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 17:14:32.493  6394  6394 W art     : b5d29000-b5d2d000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 17:14:32.493  6394  6394 W art     : b5d2d000-b5d2e000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 17:14:32.493  6394  6394 W art     : b5d2e000-b5d2f000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 17:14:32.493  6394  6394 W art     : b5d2f000-b5d30000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b5d30000-b5d3d000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 17:14:32.493  6394  6394 W art     : b5d3d000-b5d3f000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 17:14:32.493  6394  6394 W art     : b5d3f000-b5d40000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 17:14:32.493  6394  6394 W art     : b5d40000-b6152000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 17:14:32.493  6394  6394 W art     : b6152000-b6153000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6153000-b615c000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 17:14:32.493  6394  6394 W art     : b615c000-b6160000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 17:14:32.493  6394  6394 W art     : b6160000-b6161000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6161000-b6168000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-12 17:14:32.493  6394  6394 W art     : b6168000-b6169000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 17:14:32.493  6394  6394 W art     : b6169000-b616a000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 17:14:32.493  6394  6394 W art     : b616a000-b616b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b616b000-b6186000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-12 17:14:32.493  6394  6394 W art     : b6186000-b6187000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 17:14:32.493  6394  6394 W art     : b6187000-b6188000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 17:14:32.493  6394  6394 W art     : b6188000-b6189000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b6189000-b61d5000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 17:14:32.493  6394  6394 W art     : b61d5000-b61d6000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b61d6000-b61d7000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 17:14:32.493  6394  6394 W art     : b61d7000-b61d8000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 17:14:32.493  6394  6394 W art     : b61d8000-b61d9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b61d9000-b61dd000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 17:14:32.493  6394  6394 W art     : b61dd000-b61de000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b61de000-b61df000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 17:14:32.493  6394  6394 W art     : b61df000-b61e0000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-12 17:14:32.493  6394  6394 W art     : b61e0000-b6218000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 17:14:32.493  6394  6394 W art     : b6218000-b6219000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 17:14:32.493  6394  6394 W art     : b6219000-b621a000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 17:14:32.493  6394  6394 W art     : b621a000-b621b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b621b000-b62b9000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 17:14:32.493  6394  6394 W art     : b62b9000-b62ba000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b62ba000-b62d8000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 17:14:32.493  6394  6394 W art     : b62d8000-b62d9000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-12 17:14:32.493  6394  6394 W art     : b62d9000-b644c000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 17:14:32.493  6394  6394 W art     : b644c000-b6457000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 17:14:32.493  6394  6394 W art     : b6457000-b6458000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 17:14:32.493  6394  6394 W art     : b6458000-b656f000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-12 17:14:32.493  6394  6394 W art     : b656f000-b657a000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 17:14:32.493  6394  6394 W art     : b657a000-b657b000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 17:14:32.493  6394  6394 W art     : b657b000-b657f000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b657f000-b65a3000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-12 17:14:32.493  6394  6394 W art     : b65a3000-b65a5000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 17:14:32.493  6394  6394 W art     : b65a5000-b65a6000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 17:14:32.493  6394  6394 W art     : b65a6000-b664c000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 17:14:32.493  6394  6394 W art     : b664c000-b6659000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-12 17:14:32.493  6394  6394 W art     : b6659000-b665a000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 17:14:32.493  6394  6394 W art     : b665a000-b665b000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b665b000-b66ae000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 17:14:32.493  6394  6394 W art     : b66ae000-b66af000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b66af000-b66b0000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 17:14:32.493  6394  6394 W art     : b66b0000-b66b1000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 17:14:32.493  6394  6394 W art     : b66b1000-b66b6000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b66b6000-b66c8000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 17:14:32.493  6394  6394 W art     : b66c8000-b66c9000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b66c9000-b66ca000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 17:14:32.493  6394  6394 W art     : b66ca000-b66cb000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 17:14:32.493  6394  6394 W art     : b66cb000-b66d2000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 17:14:32.493  6394  6394 W art     : b66d2000-b66d3000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 17:14:32.493  6394  6394 W art     : b66d3000-b66d4000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 17:14:32.493  6394  6394 W art     : b66d4000-b66d5000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b66d5000-b66d8000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 17:14:32.493  6394  6394 W art     : b66d8000-b66d9000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 17:14:32.493  6394  6394 W art     : b66d9000-b66da000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 17:14:32.493  6394  6394 W art     : b66da000-b66de000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 17:14:32.493  6394  6394 W art     : b66de000-b66df000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 17:14:32.493  6394  6394 W art     : b66df000-b66e0000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 17:14:32.493  6394  6394 W art     : b66e0000-b66ee000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 17:14:32.493  6394  6394 W art     : b66ee000-b66ef000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b66ef000-b66f0000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 17:14:32.493  6394  6394 W art     : b66f0000-b66f1000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 17:14:32.493  6394  6394 W art     : b66f1000-b66fa000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 17:14:32.493  6394  6394 W art     : b66fa000-b66fb000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 17:14:32.493  6394  6394 W art     : b66fb000-b66fc000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 17:14:32.493  6394  6394 W art     : b66fc000-b6762000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 17:14:32.493  6394  6394 W art     : b6762000-b6763000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6763000-b6765000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 17:14:32.493  6394  6394 W art     : b6765000-b676e000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 17:14:32.493  6394  6394 W art     : b676e000-b6771000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6771000-b6808000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 17:14:32.493  6394  6394 W art     : b6808000-b680a000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 17:14:32.493  6394  6394 W art     : b680a000-b680b000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 17:14:32.493  6394  6394 W art     : b680b000-b680c000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b680c000-b6b2d000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 17:14:32.493  6394  6394 W art     : b6b2d000-b6b2e000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6b2e000-b6b49000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 17:14:32.493  6394  6394 W art     : b6b49000-b6b4d000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 17:14:32.493  6394  6394 W art     : b6b4d000-b6b52000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6b52000-b6b5a000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 17:14:32.493  6394  6394 W art     : b6b5a000-b6b5b000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 17:14:32.493  6394  6394 W art     : b6b5b000-b6b5c000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 17:14:32.493  6394  6394 W art     : b6b5c000-b6b8a000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 17:14:32.493  6394  6394 W art     : b6b8a000-b6b8b000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6b8b000-b6b92000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 17:14:32.493  6394  6394 W art     : b6b92000-b6b93000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 17:14:32.493  6394  6394 W art     : b6b93000-b6bd9000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 17:14:32.493  6394  6394 W art     : b6bd9000-b6bda000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6bda000-b6bdd000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 17:14:32.493  6394  6394 W art     : b6bdd000-b6bde000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 17:14:32.493  6394  6394 W art     : b6bde000-b6bf9000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 17:14:32.493  6394  6394 W art     : b6bf9000-b6bfd000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 17:14:32.493  6394  6394 W art     : b6bfd000-b6bfe000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 17:14:32.493  6394  6394 W art     : b6bfe000-b6c4b000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 17:14:32.493  6394  6394 W art     : b6c4b000-b6c4c000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6c4c000-b6c58000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 17:14:32.493  6394  6394 W art     : b6c58000-b6c59000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 17:14:32.493  6394  6394 W art     : b6c59000-b6c66000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 17:14:32.493  6394  6394 W art     : b6c66000-b6c67000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6c67000-b6c68000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 17:14:32.493  6394  6394 W art     : b6c68000-b6c69000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 17:14:32.493  6394  6394 W art     : b6c69000-b6c71000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 17:14:32.493  6394  6394 W art     : b6c71000-b6c72000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6c72000-b6c73000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 17:14:32.493  6394  6394 W art     : b6c73000-b6c74000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 17:14:32.493  6394  6394 W art     : b6c74000-b6c7b000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 17:14:32.493  6394  6394 W art     : b6c7b000-b6c7c000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 17:14:32.493  6394  6394 W art     : b6c7c000-b6c7d000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 17:14:32.493  6394  6394 W art     : b6c7d000-b6c91000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 17:14:32.493  6394  6394 W art     : b6c91000-b6c93000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 17:14:32.493  6394  6394 W art     : b6c93000-b6c94000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 17:14:32.493  6394  6394 W art     : b6c94000-b6cbc000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 17:14:32.493  6394  6394 W art     : b6cbc000-b6cbe000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 17:14:32.493  6394  6394 W art     : b6cbe000-b6cbf000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 17:14:32.493  6394  6394 W art     : b6cbf000-b6cc2000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 17:14:32.493  6394  6394 W art     : b6cc2000-b6cc3000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 17:14:32.493  6394  6394 W art     : b6cc3000-b6cc4000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 17:14:32.493  6394  6394 W art     : b6cc4000-b6ccd000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 17:14:32.493  6394  6394 W art     : b6ccd000-b6cce000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 17:14:32.493  6394  6394 W art     : b6cce000-b6ccf000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 17:14:32.493  6394  6394 W art     : b6ccf000-b6cef000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 17:14:32.493  6394  6394 W art     : b6cef000-b6cf0000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 17:14:32.493  6394  6394 W art     : b6cf0000-b6cf1000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 17:14:32.493  6394  6394 W art     : b6cf1000-b6d64000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 17:14:32.493  6394  6394 W art     : b6d64000-b6d68000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 17:14:32.493  6394  6394 W art     : b6d68000-b6d6b000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 17:14:32.493  6394  6394 W art     : b6d6b000-b6d75000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6d75000-b6dfd000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 17:14:32.493  6394  6394 W art     : b6dfd000-b6dfe000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6dfe000-b6e02000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 17:14:32.493  6394  6394 W art     : b6e02000-b6e03000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 17:14:32.493  6394  6394 W art     : b6e03000-b6e04000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6e04000-b6e2d000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 17:14:32.493  6394  6394 W art     : b6e2d000-b6e2e000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6e2e000-b6e31000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 17:14:32.493  6394  6394 W art     : b6e31000-b6e32000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 17:14:32.493  6394  6394 W art     : b6e32000-b6f0c000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 17:14:32.493  6394  6394 W art     : b6f0c000-b6f13000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 17:14:32.493  6394  6394 W art     : b6f13000-b6f1b000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 17:14:32.493  6394  6394 W art     : b6f1b000-b6f1c000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6f1c000-b6f1d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:14:32.493  6394  6394 W art     : b6f1d000-b6f1e000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 17:14:32.493  6394  6394 W art     : b6f1e000-b6f1f000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b6f1f000-b6f22000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b6f22000-b6f47000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 17:14:32.493  6394  6394 W art     : b6f47000-b6f48000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6f48000-b6f4f000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 17:14:32.493  6394  6394 W art     : b6f4f000-b6f50000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 17:14:32.493  6394  6394 W art     : b6f50000-b6f57000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 17:14:32.493  6394  6394 W art     : b6f57000-b6f58000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 17:14:32.493  6394  6394 W art     : b6f58000-b6f59000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 17:14:32.493  6394  6394 W art     : b6f59000-b6f5a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b6f5a000-b6f72000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 17:14:32.493  6394  6394 W art     : b6f72000-b6f73000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6f73000-b6f74000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 17:14:32.493  6394  6394 W art     : b6f74000-b6f75000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 17:14:32.493  6394  6394 W art     : b6f75000-b6f83000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 17:14:32.493  6394  6394 W art     : b6f83000-b6f84000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6f84000-b6f85000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 17:14:32.493  6394  6394 W art     : b6f85000-b6f86000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 17:14:32.493  6394  6394 W art     : b6f86000-b6f87000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:14:32.493  6394  6394 W art     : b6f87000-b6f89000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b6f89000-b6f8a000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b6f8a000-b6f8b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:14:32.493  6394  6394 W art     : b6f8b000-b6f8c000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 17:14:32.493  6394  6394 W art     : b6f8c000-b6f8d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:14:32.493  6394  6394 W art     : b6f8d000-b6fad000 r--s 00000000 00:0b 6572       /dev/__properties__
08-12 17:14:32.493  6394  6394 W art     : b6fad000-b6fae000 r--p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6fae000-b6faf000 ---p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6faf000-b6fb1000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 17:14:32.493  6394  6394 W art     : b6fb1000-b6fb2000 r-xp 00000000 00:00 0          [sigpage]
08-12 17:14:32.493  6394  6394 W art     : b6fb2000-b6fcd000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 17:14:32.493  6394  6394 W art     : b6fcd000-b6fce000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 17:14:32.493  6394  6394 W art     : b6fce000-b6fd0000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 17:14:32.493  6394  6394 W art     : b6fd0000-b6fd2000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : b6fd2000-b6fd7000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 17:14:32.493  6394  6394 W art     : b6fd7000-b6fd8000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 17:14:32.493  6394  6394 W art     : b6fd8000-b6fd9000 rw-p 00000000 00:00 0 
08-12 17:14:32.493  6394  6394 W art     : bec39000-bec5a000 rw-p 00000000 00:00 0          [stack]
08-12 17:14:32.493  63,94  6394 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 17:14:32.533  6394  6394 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 17:14:32.573  6394  6394 I Radio-JNI: register_android_hardware_Radio DONE
08-12 17:14:32.573  6430  6430 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-12 17:14:32.573  6430  6430 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-12 17:14:32.573  6430  6430 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-12 17:14:32.573  6430  6430 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-12 17:14:32.573  6430  6430 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-12 17:14:32.573  6430  6430 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-12 17:14:32.573  6430  6430 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 17:14:32.573  6430  6430 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 17:14:32.573  6430  6430 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 17:14:32.573  6430  6430 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 17:14:32.573  6430  6430 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:14:32.573  6430  6430 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 17:14:32.573  6430  6430 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 17:14:32.573  6430  6430 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:14:32.573  6430  6430 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 17:14:32.573  6430  6430 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 17:14:32.583  6394  6394 E AffinityControl: AffinityControl: registerfunction enter
08-12 17:14:32.583   773  1594 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec1d165 1680:android.process.acore/u0a19}
08-12 17:14:32.593   773  1748 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{488f69 5028:com.sec.android.gallery3d/u0a47}
08-12 17:14:32.593  5028  5028 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-12 17:14:32.603  6394  6394 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 17:14:32.603  3507  3507 D FactoryTest: User mode
08-12 17:14:32.603  3507  3507 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-12 17:14:32.603  3507  3507 D MTPRx   : still no open session command from host, so toast
08-12 17:14:32.613   773  1731 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 17:14:32.623  6461  6461 E Zygote  : v2
08-12 17:14:32.623  6461  6461 I libpersona: KNOX_SDCARD checking this for 10050
08-12 17:14:32.623  6461  6461 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:32.623  6461  6461 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:32.623  6461  6461 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:32.623  6461  6461 E Zygote  : accessInfo : 0
08-12 17:14:32.623  6461  6461 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-12 17:14:32.623   773  1594 I ActivityManager: Start proc 6461:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-12 17:14:32.633   773  1780 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
08-12 17:14:32.643   773  1780 D ActivityManager: mDVFSHelper.acquire()
08-12 17:14:32.643   773  1780 D FocusedStackFrame: Set to : 0
08-12 17:14:32.643   773  1780 V WindowManager: addAppToken: AppWindowToken{6cb3962 token=Token{c24402d ActivityRecord{4334744 u0 com.samsung.android.MtpApplication/.USBConnection t167}}} to stack=1 task=167 at 0
08-12 17:14:32.653   773  1780 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
08-12 17:14:32.663  6461  6461 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:32.663  6461  6461 D ActivityThread: Added TimaKeyStore provider
08-12 17:14:32.673   773  1780 D InputDispatcher: Focused application set to: xxxx
08-12 17:14:32.673   773  1780 D InputDispatcher: Focus left window: 1733
08-12 17:14:32.683  3507  3507 E MTPRx   : started activity for popup
08-12 17:14:32.683   773   904 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:773 uid:1000
08-12 17:14:32.683   773   904 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 17:14:32.683   773   904 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:773 uid:1000
08-12 17:14:32.683   773   904 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 17:14:32.683  3507  3507 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-12 17:14:32.683   773  1648 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-12 17:14:32.683  3507  3507 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-12 17:14:32.693   773  1648 D ActivityManager: mDVFSHelper.acquire()
08-12 17:14:32.693   773  1648 V WindowManager: addAppToken: AppWindowToken{7b1b229 token=Token{1bf93b0 ActivityRecord{3cf7af3 u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-12 17:14:32.703   773  1648 D InputDispatcher: Focused application set to: xxxx
08-12 17:14:32.703  6394  6394 D AndroidRuntime: Shutting down VM
08-12 17:14:32.713   773  1550 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99c7d61 6461:com.sec.android.app.myfiles/u0a50}
08-12 17:14:32.713   773   904 D SecWifiDisplayUtil: Metadata value : none
08-12 17:14:32.713   773   904 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{fdb2086 V.E...... R.....ID 0,0-0,0}
08-12 17:14:32.713   773   904 D ISSUE_DEBUG: InputChannelName : 7190974 Starting com.test.thalitest
08-12 17:14:32.713  3507  3507 D MTPUSBConnection: onCreate in USBConnection
08-12 17:14:32.713  3507  3507 V MTPUSBConnection: Registering broadcast receiver.
08-12 17:14:32.713   773   861 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
08-12 17:14:32.723  3507  3507 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
08-12 17:14:32.723   773   789 D SecContentProvider2: query(), uri = 14 selection = getSealedState
08-12 17:14:32.723   773  1550 I ActivityManager: Killing 5504:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
08-12 17:14:32.723  6461  6461 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-12 17:14:32.733   295   295 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-12 17:14:32.743   773  1550 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
08-12 17:14:32.753   773   904 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-12 17:14:32.753  6461  6461 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-12 17:14:32.783   773   904 V WindowStateAnimator: Finishing drawing window Window{7190974 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-12 17:14:32.783   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbecd7364
08-12 17:14:32.783  3507  3507 D TAG     : dev.kiessupport is : TRUE
08-12 17:14:32.803  6461  6461 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-12 17:14:32.813  3507  3507 D SecWifiDisplayUtil: Metadata value : none
08-12 17:14:32.813  3507  3507 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5702e8 V.E...... R.....I. 0,0-0,0}
08-12 17:14:32.823  3507  6476 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 17:14:32.823   773  1780 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd1a0fb 2851:com.android.settings/1000}
08-12 17:14:32.823   773  1748 D ISSUE_DEBUG: InputChannelName : b026f5b com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
08-12 17:14:32.823   322   322 E installd: system dir 0 : /system/app/
08-12 17:14:32.823   322   322 E installd: system dir 1 : /system/priv-app/
08-12 17:14:32.823   322   322 E installd: system dir 2 : /vendor/app/
08-12 17:14:32.823   322   322 E installd: system dir 3 : /oem/app/
08-12 17:14:32.833  3507  3507 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e254700 I.E...... R.....I. 0,0-0,0}
08-12 17:14:32.833   773  1324 D ISSUE_DEBUG: InputChannelName : c6e80d1 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
08-12 17:14:32.843   773   942 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-12 17:14:32.843   773  1594 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-12 17:14:32.843   773  1594 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 17:14:32.843   773   773 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 17:14:32.843   773   773 I KnoxTimeoutHandler: Shared devices show user statefalse
08-12 17:14:32.843   773   773 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
08-12 17:14:32.853  6479  6479 E Zygote  : v2
08-12 17:14:32.853  6479  6479 I libpersona: KNOX_SDCARD checking this for 10004
08-12 17:14:32.853  6479  6479 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:32.853  6479  6479 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:32.853   773   789 I ActivityManager: Start proc 6479:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-12 17:14:32.853  6479  6479 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:32.853  6479  6479 E Zygote  : accessInfo : 0
08-12 17:14:32.853  6479  6479 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-12 17:14:32.863   773  1748 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd1a0fb 2851:com.android.settings/1000}
08-12 17:14:32.883  6491  6491 E Zygote  : v2
08-12 17:14:32.883  6491  6491 I libpersona: KNOX_SDCARD checking this for 10169
08-12 17:14:32.883  6491  6491 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:32.883  6491  6491 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:32.883  6491  6491 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:32.883  6491  6491 E Zygote  : accessInfo : 0
08-12 17:14:32.883  6491  6491 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-12 17:14:32.883   773  1747 I ActivityManager: Start proc 6491:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-12 17:14:32.893   295   295 I SurfaceFlinger: id=20 createSurf (145x145),1 flag=4, VSBConnecti
08-12 17:14:32.893  6479  6479 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:32.893  6479  6479 D ActivityThread: Added TimaKeyStore provider
08-12 17:14:32.903   773  1730 V WindowOrientationListener: setCurrentAppOrientation :-1
08-12 17:14:32.903   773  1730 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-12 17:14:32.903   773   863 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{7190974 u0 d0 Starting com.test.thalitest}
08-12 17:14:32.903  3507  6476 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 17:14:32.903  3507  6476 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 17:14:32.903  3507  6476 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 17:14:32.903  3507  6476 I Adreno-EGL: Local Branch: ss
08-12 17:14:32.903  3507  6476 I Adreno-EGL: Remote Branch: 
08-12 17:14:32.903  3507  6476 I Adreno-EGL: Local Patches: 
08-12 17:14:32.903  3507  6476 I Adreno-EGL: Reconstruct Branch: 
08-12 17:14:32.903  1385  1385 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-12 17:14:32.913  3507  6476 D libEGL  : eglInitialize EGLDisplay = 0x9f04d7c4
08-12 17:14:32.913  3507  6476 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 17:14:32.923   773  1730 D ActivityManager:  Launching com.test.thalitest, updated priority
,08-12 17:14:32.933  6491  6491 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 17:14:32.933  6491  6491 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:32.933   773   861 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-12 17:14:32.943  1733  1886 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
,08-12 17:14:32.943  1733  1733 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
,08-12 17:14:32.953   295   365 D libEGL  : eglTerminate EGLDisplay = 0xb65ff64c
,08-12 17:14:32.963   295   365 D libEGL  : eglTerminate EGLDisplay = 0xb65ff64c
,08-12 17:14:32.973  3507  3507 V ActivityThread: updateVisibility : ActivityRecord{2835adf token=android.os.BinderProxy@f5f1d01 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-12 17:14:32.983   295   357 I SurfaceFlinger: id=8 Removed Mauncher (5/10)
,08-12 17:14:32.983   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd73a4
,08-12 17:14:32.983  3507  3507 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-12 17:14:32.983   773  1748 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8f2b736 6491:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-12 17:14:32.983  6479  6479 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 17:14:33.003   773  3415 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 17:14:33.013   773   861 I ActivityManager: Start proc 6507:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-12 17:14:33.013  6507  6507 E Zygote  : v2
,08-12 17:14:33.013  6507  6507 I libpersona: KNOX_SDCARD checking this for 10210
08-12 17:14:33.013  6507  6507 I libpersona: KNOX_SDCARD not a persona
,08-12 17:14:33.013  6507  6507 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:33.013  6507  6507 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:14:33.013  6507  6507 E Zygote  : accessInfo : 0
,08-12 17:14:33.013  6507  6507 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-12 17:14:33.033  6479  6479 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 17:14:33.033  1733  1733 V ActivityThread: updateVisibility : ActivityRecord{f825ebc token=android.os.BinderProxy@ee833ab {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,08-12 17:14:33.033  2377  2392 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
,08-12 17:14:33.033  6479  6479 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 17:14:33.033  1733  1733 D Launcher: onTrimMemory. Level: 20
,08-12 17:14:33.043  6491  6491 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-12 17:14:33.053  6479  6479 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-12 17:14:33.063  6491  6491 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-12 17:14:33.083  6479  6479 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 17:14:33.093  6507  6507 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:33.093  6507  6507 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:33.093  6479  6479 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-12 17:14:33.103   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbecd7364
,08-12 17:14:33.103   773   789 V WindowStateAnimator: Finishing drawing window Window{b026f5b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 17:14:33.103  3507  3507 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-12 17:14:33.103  3507  3507 V ActivityThread: updateVisibility : ActivityRecord{2835adf token=android.os.BinderProxy@f5f1d01 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,08-12 17:14:33.113  6479  6479 I cr_LibraryLoader: Time to load native libraries: 14 ms (timestamps 8000-8014)
,08-12 17:14:33.113  6479  6479 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 17:14:33.113   295  6504 I SurfaceFlinger: id=20 Removed VSBConnecti (5/9)
,08-12 17:14:33.113   295  4688 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/9)
,08-12 17:14:33.123   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd73a4
,08-12 17:14:33.123   773  1730 I ActivityManager: Killing 5523:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-12 17:14:33.123  3507  3507 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f5f1d01 time:108025
,08-12 17:14:33.143   773  1730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3af322b 1714:com.android.phone/1001}
,08-12 17:14:33.153  6479  6479 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {62ac67b}
08-12 17:14:33.153  6479  6479 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 17:14:33.153  6479  6523 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-12 17:14:33.153   773  1550 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
08-12 17:14:33.153  6479  6479 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 17:14:33.163   773  1780 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f36292 1838:com.google.android.googlequicksearchbox:search/u0a61}
,08-12 17:14:33.163  6479  6479 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-12 17:14:33.173  6507  6507 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-12 17:14:33.173   773   783 I art     : Background partial concurrent mark sweep GC freed 159037(9MB) AllocSpace objects, 7(2MB) LOS objects, 27% free, 42MB/58MB, paused 12.154ms total 222.247ms
,08-12 17:14:33.183   773   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f36292 1838:com.google.android.googlequicksearchbox:search/u0a61}
,08-12 17:14:33.193  6479  6479 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 17:14:33.193  6479  6479 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 17:14:33.193  6479  6479 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 17:14:33.193  6479  6479 I Adreno-EGL: Local Branch: ss
08-12 17:14:33.193  6479  6479 I Adreno-EGL: Remote Branch: 
08-12 17:14:33.193  6479  6479 I Adreno-EGL: Local Patches: 
08-12 17:14:33.193  6479  6479 I Adreno-EGL: Reconstruct Branch: 
,08-12 17:14:33.193  6479  6479 D libEGL  : eglInitialize EGLDisplay = 0xbed88dac
,08-12 17:14:33.203   773  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e89590d 6340:com.samsung.android.sm.provider/1000}
,08-12 17:14:33.203  6507  6507 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-12 17:14:33.213  6507  6507 D AASAservice: onCreate()
,08-12 17:14:33.223  6530  6530 E Zygote  : v2
08-12 17:14:33.223  6530  6530 I libpersona: KNOX_SDCARD checking this for 5012
08-12 17:14:33.223  6530  6530 I libpersona: KNOX_SDCARD not a persona
,08-12 17:14:33.223  6530  6530 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:33.223  6530  6530 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:14:33.223   773  1648 I ActivityManager: Start proc 6530:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-12 17:14:33.223  6530  6530 E Zygote  : accessInfo : 0
,08-12 17:14:33.223  6530  6530 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-12 17:14:33.233   773  1780 I ActivityManager: Killing 5097:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-12 17:14:33.243  5307  5307 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-12 17:14:33.253   773  3916 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-12 17:14:33.253  6530  6530 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:33.253  6530  6530 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:33.253   773  1730 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
08-12 17:14:33.253   773  1730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-12 17:14:33.263  1838  6528 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 17:14:33.263   773  1594 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dec573c 6530:com.samsung.android.sm.devicesecurity/5012}
,08-12 17:14:33.283  6530  6530 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,08-12 17:14:33.303  6479  6479 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
08-12 17:14:33.303  6530  6530 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,08-12 17:14:33.323  6479  6479 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 17:14:33.323  6479  6479 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-12 17:14:33.323  6479  6479 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-12 17:14:33.323  6479  6479 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-12 17:14:33.333  1838  6528 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-12 17:14:33.343  6479  6479 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-12 17:14:33.343  6479  6479 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-12 17:14:33.353   773  1594 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ac29ed 3184:com.android.contacts/u0a19}
,08-12 17:14:33.363  1838  6528 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-12 17:14:33.363  6558  6558 E Zygote  : v2
08-12 17:14:33.363  6558  6558 I libpersona: KNOX_SDCARD checking this for 10049
08-12 17:14:33.363  6558  6558 I libpersona: KNOX_SDCARD not a persona
,08-12 17:14:33.363  6558  6558 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:33.363  6558  6558 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:14:33.373   773  1747 I ActivityManager: Start proc 6558:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
,08-12 17:14:33.373  6558  6558 E Zygote  : accessInfo : 0
,08-12 17:14:33.373  6558  6558 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,08-12 17:14:33.393  6558  6558 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 17:14:33.393  6558  6558 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:33.403   773  1749 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c72b73b 6558:com.android.mms/u0a49}
,08-12 17:14:33.413  6558  6558 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 17:14:33.433  6558  6558 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-12 17:14:33.433   773  1780 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,08-12 17:14:33.443  6558  6558 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-12 17:14:33.453  6479  6479 D SecWifiDisplayUtil: Metadata value : none
,08-12 17:14:33.463  6479  6479 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9e47d1 I.E...... R.....ID 0,0-0,0}
,08-12 17:14:33.463  6479  6574 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 17:14:33.463  6558  6558 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-12 17:14:33.463   773   861 W ActivityManager: Activity pause timeout for ActivityRecord{3cf7af3 u0 com.test.thalitest/.MainActivity t168}
,08-12 17:14:33.473   773   789 D ISSUE_DEBUG: InputChannelName : fdc239c com.test.thalitest/com.test.thalitest.MainActivity
,08-12 17:14:33.473  6558  6577 D Mms/ArtClassLoader: init before art third
,08-12 17:14:33.473  6558  6575 D Mms/ArtClassLoader: init before art first
,08-12 17:14:33.473  6558  6558 D Mms/TelephonyPermission: start operation mode monitor
,08-12 17:14:33.483   773  1780 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-12 17:14:33.483   773  1780 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-12 17:14:33.483   773   773 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 17:14:33.483   773   773 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-12 17:14:33.483  6558  6576 D Mms/ArtClassLoader: init before art second
,08-12 17:14:33.483  6558  6558 D Mms/TelephonyPermission: User ID is null set current User Id
,08-12 17:14:33.533  6479  6479 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6479
,08-12 17:14:33.533   773  1748 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6479 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 17:14:33.533   773  1336 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-12 17:14:33.533   773  1336 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-12 17:14:33.533   773  1336 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,08-12 17:14:33.543   773  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-12 17:14:33.543   773  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 17:14:33.543   773  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-12 17:14:33.543   773  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-12 17:14:33.543   773  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-12 17:14:33.543   773  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-12 17:14:33.543   773  1336 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 17:14:33.543  6479  6523 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-12 17:14:33.543  6479  6479 V ActivityThread: updateVisibility : ActivityRecord{116fdd3 token=android.os.BinderProxy@adfd6f8 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-12 17:14:33.553  6479  6479 D SecWifiDisplayUtil: Metadata value : none
,08-12 17:14:33.553  6558  6577 D Mms/ArtClassLoader: init [DONE] art
,08-12 17:14:33.563   295   295 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,08-12 17:14:33.573  2806  6573 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-12 17:14:33.573  6558  6558 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-12 17:14:33.573  6558  6558 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
08-12 17:14:33.583   773   788 D InputDispatcher: Focus entered window: 6479
,08-12 17:14:33.583   773   904 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:773 uid:1000
08-12 17:14:33.583   773   904 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 17:14:33.583   773   904 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:773 uid:1000
08-12 17:14:33.583   773   904 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 17:14:33.583  6479  6574 D libEGL  : eglInitialize EGLDisplay = 0x9c97f7c4
08-12 17:14:33.583  6479  6574 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 17:14:33.603  6558  6558 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-12 17:14:33.603  6558  6558 D Mms/TelephonyPermission: isDefault true
,08-12 17:14:33.603  6558  6558 D Mms/MmsApp: onCreate() com.android.mms
,08-12 17:14:33.623  1838  6528 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 360 ms] updated apps [took 360 ms] 
,08-12 17:14:33.653  6479  6479 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 17:14:33.653   773  1748 V WindowStateAnimator: Finishing drawing window Window{fdc239c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-12 17:14:33.653  6479  6479 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-12 17:14:33.653  6479  6479 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 17:14:33.653   773  1780 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-12 17:14:33.653  6558  6558 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-12 17:14:33.653   773  1238 V AlarmManager: Expired Alarm result :4
,08-12 17:14:33.673   773   904 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 17:14:33.673   773   773 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 17:14:33.673   773   904 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +712ms (total +1s34ms)
,08-12 17:14:33.683   773   904 D ActivityManager: mDVFSHelper.release()
,08-12 17:14:33.683   773   773 I KnoxTimeoutHandler: SD activityfalse
08-12 17:14:33.683   773   904 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3cf7af3 u0 com.test.thalitest/.MainActivity t168} time:108580
,08-12 17:14:33.683   773   904 D ViewRootImpl: #3 mView = null
,08-12 17:14:33.683   295  6504 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
,08-12 17:14:33.693   295  4688 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
,08-12 17:14:33.693   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd73a4
,08-12 17:14:33.703  6479  6584 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 17:14:33.703  6479  6584 D libEGL  : eglInitialize EGLDisplay = 0x9be803ec
08-12 17:14:33.703   773  3419 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome/TouchWizHome.apk / 1.0 running in null rsrc of package null
,08-12 17:14:33.703  5777  5823 I Finsky  : [825] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-12 17:14:33.723   773  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-12 17:14:33.723   773  1747 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 17:14:33.723   773  1747 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-12 17:14:33.723   773  1747 D BatteryService: stay LED for charging
08-12 17:14:33.723   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:14:33.723   773   773 I MotionRecognitionService: Plugged
08-12 17:14:33.723   773   773 D MotionRecognitionService:   cableConnection= 1
08-12 17:14:33.723   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 17:14:33.723   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:14:33.723  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 17:14:33.723  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:14:33.723  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:14:33.733   773  1648 V WindowStateAnimator: Finishing drawing window Window{fdc239c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-12 17:14:33.733  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:14:33.733  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 17:14:33.733  6558  6558 D Mms/MmsApp: [start]    initCountryIso consume time = 273.011093
,08-12 17:14:33.743  6479  6479 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 17:14:33.743  6479  6479 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@adfd6f8 time:108641
,08-12 17:14:33.743   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbecd7364
,08-12 17:14:33.743   773  1749 D CountryDetector: The first listener is added
,08-12 17:14:33.753  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 17:14:33.753  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:14:33.753  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:14:33.753  6558  6558 D Mms/MmsApp: [end]    initCountryIso consume time = 17.761615
08-12 17:14:33.753  6558  6558 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.102812
,08-12 17:14:33.763  6558  6575 D Mms/ArtClassLoader: init [DONE] art
,08-12 17:14:33.763  6558  6558 D Mms/MmsConfig: before partial update
,08-12 17:14:33.773  6479  6479 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6479
,08-12 17:14:33.783  6558  6558 D Mms/MmsConfig: Load Resize quality : 80
,08-12 17:14:33.803  6558  6558 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-12 17:14:33.803  6558  6558 D EasySignUpManager_1.0.5: isAuth is false
08-12 17:14:33.803  6558  6558 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-12 17:14:33.803  6558  6558 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-12 17:14:33.803  6558  6558 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-12 17:14:33.803  6558  6558 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-12 17:14:33.803  6558  6558 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-12 17:14:33.803  6558  6558 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 17:14:33.803  6558  6558 D EasySignUpManager_1.0.5: isAuth is false
,08-12 17:14:33.803  6558  6558 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-12 17:14:33.803  6558  6558 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-12 17:14:33.813  1714  1732 D TP/MmsSmsProvider: query, match:2117, calling pid = 6558, accessRestricted = false
,08-12 17:14:33.813  1714  1732 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.482 ms
,08-12 17:14:33.823  6558  6558 E CscParser: mps_code.dat does not exist
08-12 17:14:33.823  6558  6558 E CscParser: customer_path =/system/csc/customer.xml
08-12 17:14:33.823  6558  6558 E CscParser: fileName + /system/csc/customer.xml
,08-12 17:14:33.833  6558  6558 E CscParser: mps_code.dat does not exist
,08-12 17:14:33.833  6558  6558 E CscParser: customer_path =/system/csc/customer.xml
08-12 17:14:33.833  6558  6558 E CscParser: fileName + /system/csc/customer.xml
,08-12 17:14:33.843  6558  6558 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-12 17:14:33.843  6558  6576 D Mms/ArtClassLoader: init [DONE] art
,08-12 17:14:33.853  6558  6558 D Mms/MmsConfig:  enable multiwindow = true
,08-12 17:14:33.853  6558  6558 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-12 17:14:33.853  6558  6558 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-12 17:14:33.853  6558  6558 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-12 17:14:33.853  6558  6558 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-12 17:14:33.853  6558  6558 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-12 17:14:33.853  6558  6558 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-12 17:14:33.853  6558  6558 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-12 17:14:33.873  6558  6558 D Mms/MmsConfig: [end]    init() consume time = 114.476043
,08-12 17:14:33.873  6558  6558 D Mms/Contact: [start]    init() consume time = 4.32453
,08-12 17:14:33.883  1714  1935 D TP/MmsSmsProvider: query, match:13, calling pid = 6558, accessRestricted = false
,08-12 17:14:33.893  1714  1935 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.502 ms
,08-12 17:14:33.893  6558  6558 D Mms/Contact: [end]    init consume time = 16.395313
,08-12 17:14:33.893  6558  6597 D Mms/DraftCache: [start]    rebuildCache consume time = 2.222448
,08-12 17:14:33.893  6558  6558 D Mms:transaction: roaming -> false (slotId = 0)
08-12 17:14:33.893  6558  6558 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 17:14:33.893  6558  6558 D Mms:transaction: auto download without roaming -> true
08-12 17:14:33.893  6558  6558 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-12 17:14:33.893  6558  6558 D Mms:transaction: roaming -> false (slotId = 1)
08-12 17:14:33.893  6558  6558 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-12 17:14:33.893  6558  6558 D Mms:transaction: auto download without roaming -> true
08-12 17:14:33.893  6558  6558 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-12 17:14:33.893  6558  6558 D Mms:transaction: auto download during roaming secondary -> false
08-12 17:14:33.893  6558  6558 D Mms:transaction: mAutoDownload ------> true
,08-12 17:14:33.903  1714  1729 D TP/MmsSmsProvider: query, match:12, calling pid = 6558, accessRestricted = false
,08-12 17:14:33.903  1714  1729 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.408 ms
,08-12 17:14:33.913  6558  6597 D Mms/DraftCache: [end]    rebuildCache consume time = 16.877865
,08-12 17:14:33.923  6558  6558 D ComposerPerformance: 1471014873924 ms / [DONE] Composer constructor
,08-12 17:14:33.923  6558  6558 D CII     : Log Level [5]
08-12 17:14:33.923  6558  6558 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-12 17:14:33.923  6558  6558 I Mms/ReservationManager: ReservationManager()
08-12 17:14:33.923  6558  6558 I Mms/ReservationManager: resetAfterConnected()
,08-12 17:14:33.923  6558  6599 D Mms/Conversation: [start]    init() consume time = 16.429635
,08-12 17:14:33.923  1714  1732 D TP/MmsSmsProvider: delete, match:1, calling pid = 6558
08-12 17:14:33.923  1714  1732 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-12 17:14:33.923  1714  1732 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-12 17:14:33.923  1714  1729 D TP/MmsSmsProvider: query, match:7, calling pid = 6558, accessRestricted = false
,08-12 17:14:33.933  1714  1729 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.103 ms
,08-12 17:14:33.933  1714  1732 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-12 17:14:33.933  1714  1732 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-12 17:14:33.933  1714  1732 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-12 17:14:33.933  6558  6558 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-12 17:14:33.933  1714  1732 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-12 17:14:33.933  6479  6479 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 17:14:33.933  6558  6558 D Mms/MmsApp: [end]    onCreate() consume time = 13.123072
,08-12 17:14:33.943  6558  6558 D Mms/MmsApp: [end]    onCreate() consume time = 1.153647
,08-12 17:14:33.953  1714  1732 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-12 17:14:33.953  1714  1732 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-12 17:14:33.953  1714  1732 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-12 17:14:33.953  1714  1732 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 20.640 ms
08-12 17:14:33.953  1714  1732 D TP/MmsSmsProvider: need read changed broadcast:false
,08-12 17:14:33.953  6558  6599 D Mms/Conversation: [end]    init consume time = 9.78901
,08-12 17:14:33.953  6558  6558 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-12 17:14:33.963   773  1298 I ActivityManager: Start proc 6600:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-12 17:14:33.963  6600  6600 E Zygote  : v2
08-12 17:14:33.963  6600  6600 I libpersona: KNOX_SDCARD checking this for 1000
08-12 17:14:33.963  6600  6600 I libpersona: KNOX_SDCARD not a persona
,08-12 17:14:33.963  6600  6600 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:33.963  6600  6600 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:14:33.963  6600  6600 E Zygote  : accessInfo : 0
,08-12 17:14:33.963  6558  6558 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-12 17:14:33.963  6558  6558 D Mms:transaction: roaming -> false (slotId = 0)
08-12 17:14:33.963  6558  6558 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 17:14:33.963  6558  6558 D Mms:transaction: auto download without roaming -> true
08-12 17:14:33.963  6558  6558 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-12 17:14:33.963  6558  6558 D Mms:transaction: mAutoDownload ------> true
,08-12 17:14:33.973   773  3419 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-12 17:14:33.983  6558  6599 D Mms/MessagingNotification: [start]    init() consume time = 30.148959
,08-12 17:14:33.983  6558  6599 D Mms/MessagingNotification: [end]    init consume time = 5.119218
,08-12 17:14:33.993  6558  6613 D Mms/Synchronizer: [start]    doSync consume time = 1.366199
,08-12 17:14:33.993  6558  6612 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 2.634166
,08-12 17:14:34.003  1714  1935 D TP/MmsSmsProvider: query, match:0, calling pid = 6558, accessRestricted = false
,08-12 17:14:34.003  1714  1935 V TP/MmsSmsProvider: getSimpleConversations entered.
08-12 17:14:34.003  1714  1729 D TP/MmsSmsProvider: query, match:400, calling pid = 6558, accessRestricted = false
,08-12 17:14:34.003  1714  2026 D TP/MmsSmsProvider: update, match:300, calling pid = 6558
08-12 17:14:34.003  1714  2026 V TP/MmsSmsProvider: syncDBData start
,08-12 17:14:34.003  1714  1935 D TP/MmsSmsProvider: query, match 0:Elapsed time : 0.788 ms
08-12 17:14:34.003  1714  2026 V TP/MmsSmsProvider: syncDBData sms end
,08-12 17:14:34.003  1714  2026 V TP/MmsSmsProvider: syncDBData mms end
,08-12 17:14:34.003  1714  2026 V TP/MmsSmsProvider: syncDBData end
08-12 17:14:34.003  1714  2026 D TP/MmsSmsProvider: update, match 300:Elapsed time : 1.958 ms
,08-12 17:14:34.003  6558  6613 D Mms/Synchronizer: [end]    doSync consume time = 18.307499
,08-12 17:14:34.013  6600  6600 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:34.013  6600  6600 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:34.033  6558  6612 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 22.227761
,08-12 17:14:34.043   773  1648 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba7a693 6600:com.samsung.android.bbc.bbcagent/1000}
,08-12 17:14:34.043  6085  6102 D BadgeProvider: query, [selection] : package=?
,08-12 17:14:34.053  6558  6599 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-12 17:14:34.063  1714  2026 D TP/SmsProvider: query,matched:26, calling pid = 6558
,08-12 17:14:34.063  1714  2026 D TP/SmsProvider: query, match 26:Elapsed time : 1.246 ms
,08-12 17:14:34.063  6600  6600 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-12 17:14:34.083  1714  1729 D TP/MmsSmsProvider: query, match:6, calling pid = 6558, accessRestricted = false
,08-12 17:14:34.083  1714  1729 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.186 ms
,08-12 17:14:34.103  6600  6600 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-12 17:14:34.113  6615  6615 E Zygote  : v2
08-12 17:14:34.113  6615  6615 I libpersona: KNOX_SDCARD checking this for 10024
08-12 17:14:34.113  6615  6615 I libpersona: KNOX_SDCARD not a persona
,08-12 17:14:34.113  6615  6615 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:34.113  6615  6615 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:34.113  6615  6615 E Zygote  : accessInfo : 0
08-12 17:14:34.113  6615  6615 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
08-12 17:14:34.113  6479  6614 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1718224592
,08-12 17:14:34.113   773  1731 I ActivityManager: Start proc 6615:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-12 17:14:34.113  6479  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 17:14:34.113  6479  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 17:14:34.113  6479  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 17:14:34.113  6479  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 17:14:34.113  6479  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 17:14:34.123  6479  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@693d4e6 added. We now have 1 listener(s)
,08-12 17:14:34.133  6479  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-12 17:14:34.133  6479  6614 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-12 17:14:34.133  6479  6614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 17:14:34.133  6479  6614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 17:14:34.133  6479  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@230967d added. We now have 1 listener(s)
08-12 17:14:34.133  6479  6614 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 17:14:34.133  6479  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 17:14:34.143  6615  6615 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:34.143  6615  6615 D ActivityThread: Added TimaKeyStore provider
08-12 17:14:34.143  6479  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 17:14:34.143  6479  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-12 17:14:34.143  6479  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-12 17:14:34.143  6479  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 17:14:34.143  6627  6627 E Zygote  : v2
08-12 17:14:34.153   773  1550 I ActivityManager: Start proc 6627:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-12 17:14:34.153  6627  6627 I libpersona: KNOX_SDCARD checking this for 10097
08-12 17:14:34.153  6627  6627 I libpersona: KNOX_SDCARD not a persona
,08-12 17:14:34.153  6627  6627 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:34.153  6627  6627 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:14:34.153   773  1550 I ActivityManager: Killing 5075:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
08-12 17:14:34.153  6627  6627 E Zygote  : accessInfo : 0
,08-12 17:14:34.153  6627  6627 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-12 17:14:34.153   773  1730 I ActivityManager: Killing 5138:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-12 17:14:34.163  6479  6614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 17:14:34.163  6479  6614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-12 17:14:34.163  6479  6614 D BluetoothAdapter: STATE_ON
,08-12 17:14:34.163  6479  6614 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 17:14:34.173  6479  6614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:14:34.173  6479  6614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:14:34.173  6479  6614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 17:14:34.173  6479  6614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:14:34.173  6479  6614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:14:34.173  6479  6614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:14:34.173  6479  6614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:14:34.173  6479  6614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 17:14:34.173  6479  6614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 17:14:34.173  6479  6614 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 17:14:34.173  6479  6614 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 17:14:34.173  6479  6479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 17:14:34.173  6479  6479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 17:14:34.183  6615  6615 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-12 17:14:34.183   773  1648 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-12 17:14:34.193  6615  6615 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-12 17:14:34.203  6479  6479 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 17:14:34.213  6627  6627 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:34.213  6627  6627 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:34.223   773  1324 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1644cda 6627:com.google.android.apps.docs/u0a97}
,08-12 17:14:34.233  6627  6627 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 17:14:34.243   773  1324 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-12 17:14:34.283  6627  6627 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-12 17:14:34.283  6558  6599 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-12 17:14:34.293  6615  6615 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-12 17:14:34.323  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-12 17:14:34.323  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-12 17:14:34.323  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-12 17:14:34.323  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-12 17:14:34.333  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-12 17:14:34.333  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-12 17:14:34.333  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-12 17:14:34.333  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-12 17:14:34.333  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-12 17:14:34.333  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-12 17:14:34.343  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-12 17:14:34.343  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-12 17:14:34.343  6615  6615 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-12 17:14:34.393   773  1238 V AlarmManager: Expired Alarm result :4
,08-12 17:14:34.463  1456  1456 D Recents : onTaskStackChanged
,08-12 17:14:34.473  1456  1456 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 17:14:34.523  5777  5823 I Finsky  : [825] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-12 17:14:34.523  5777  5777 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-12 17:14:34.543   773  1324 I ActivityManager: Killing 4676:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-12 17:14:34.563   773  3916 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-12 17:14:34.613  2806  5004 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-12 17:14:34.633   773  3415 D SSRM:n  : SIOP:: AP = 480, PST = 450, CUR = 350, LCD = 0
,08-12 17:14:34.633   773  3415 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 17:14:34.643  6627  6642 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-12 17:14:34.643  6627  6642 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-12 17:14:34.643  6627  6642 I GAv4    :   adb logcat -s GAv4
,08-12 17:14:34.713  2806  5004 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-12 17:14:34.713  6627  6642 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 17:14:34.723   773  1731 V AlarmManager:  remove PendingIntent] PendingIntent{b4836e7: PendingIntentRecord{c23f294 com.google.android.apps.docs broadcastIntent}}
,08-12 17:14:34.723  6627  6642 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-12 17:14:34.723  6627  6642 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-12 17:14:34.743  6627  6650 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-12 17:14:34.813  2806  5004 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-12 17:14:34.933  6627  6627 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-12 17:14:34.943  6627  6627 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-12 17:14:34.953  6627  6642 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-12 17:14:34.953  6627  6642 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-12 17:14:34.953  6627  6642 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-12 17:14:34.953  6627  6642 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-12 17:14:35.063  6656  6656 E Zygote  : v2
08-12 17:14:35.063  6656  6656 I libpersona: KNOX_SDCARD checking this for 10098
08-12 17:14:35.063  6656  6656 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:35.063  6656  6656 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:35.063  6656  6656 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:35.063  6656  6656 E Zygote  : accessInfo : 0
08-12 17:14:35.063  6656  6656 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-12 17:14:35.073   773  1298 I ActivityManager: Start proc 6656:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-12 17:14:35.073   773  1298 I ActivityManager: Killing 5005:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-12 17:14:35.103  6656  6656 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:35.103  6656  6656 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:35.113   773  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{197a400 6656:com.sec.android.automotive.drivelink/u0a98}
,08-12 17:14:35.123   773  3916 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-12 17:14:35.133  6656  6656 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 17:14:35.153  6656  6656 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-12 17:14:35.203  6656  6656 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 17:14:35.213  1981  1981 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 17:14:35.213  1981  1981 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 17:14:35.213   773  1648 V AlarmManager:  remove PendingIntent] PendingIntent{3d3002c: PendingIntentRecord{8ecaaf5 com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 17:14:35.233  6656  6656 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-12 17:14:35.233  6656  6672 I GMPM    : App measurement is starting up
,08-12 17:14:35.243  6656  6672 E GMPM    : getGoogleAppId failed with status: 10
,08-12 17:14:35.253  1981  1981 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 17:14:35.253  6656  6672 E GMPM    : Uploading is not possible. App measurement disabled
,08-12 17:14:35.253   773  1748 V AlarmManager:  remove PendingIntent] PendingIntent{9393b56: PendingIntentRecord{8ecaaf5 com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 17:14:35.263  6656  6656 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-12 17:14:35.273  6656  6656 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-12 17:14:35.313  6479  6639 W jxcore-log: Initializing JXcore engine
08-12 17:14:35.313  6479  6639 W jxcore-log: JXcore engine is ready
,08-12 17:14:35.333  6627  6644 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 17:14:35.343  6678  6678 E Zygote  : v2
,08-12 17:14:35.343   773  1780 I ActivityManager: Start proc 6678:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
08-12 17:14:35.343  6678  6678 I libpersona: KNOX_SDCARD checking this for 10032
08-12 17:14:35.343  6678  6678 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:35.343   773  1327 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 17:14:35.343  6678  6678 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 17:14:35.343  6678  6678 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:14:35.343  6678  6678 E Zygote  : accessInfo : 0
,08-12 17:14:35.343  6678  6678 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-12 17:14:35.363  2206  2206 E audit   : type=1400 msg=audit(1471014875.363:287): avc:  denied  { ioctl } for  pid=6639 comm="Thread-900" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 17:14:35.363  2206  2206 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:35.363  2206  2206 E audit   : type=1300 msg=audit(1471014875.363:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=98d5f3c8 items=0 ppid=351 ppcomm=main pid=6639 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-900" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 17:14:35.363  2206  2206 E audit   : type=1327 msg=audit(1471014875.363:287): proctitle="com.test.thalitest"
08-12 17:14:35.363  2206  2206 E audit   : type=1320 msg=audit(1471014875.363:287): 
,08-12 17:14:35.363  2206  2206 E audit   : type=1400 msg=audit(1471014875.363:288): avc:  denied  { ioctl } for  pid=6639 comm="Thread-900" path="socket:[37583]" dev="sockfs" ino=37583 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 17:14:35.363  2206  2206 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:35.363  2206  2206 E audit   : type=1300 msg=audit(1471014875.363:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3c a1=5451 a2=3 a3=98d5f3c8 items=0 ppid=351 ppcomm=main pid=6639 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-900" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 17:14:35.363  2206  2206 E audit   : type=1327 msg=audit(1471014875.363:288): proctitle="com.test.thalitest"
08-12 17:14:35.363  2206  2206 E audit   : type=1320 msg=audit(1471014875.363:288): 
,08-12 17:14:35.373  6678  6678 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:35.373  6678  6678 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:35.373  6479  6639 W jxcore-log: Starting JXcore engine
,08-12 17:14:35.383   773  1327 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 17:14:35.383  6678  6678 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-12 17:14:35.413  6678  6678 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-12 17:14:35.433   773  6319 I HarmonyEASService: Updating for all 1
,08-12 17:14:35.473  6627  6644 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-12 17:14:35.493  6627  6644 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-12 17:14:35.493  6627  6644 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-12 17:14:35.493  6479  6639 W jxcore-log: Platform android
08-12 17:14:35.493  6479  6639 W jxcore-log: 
08-12 17:14:35.493  6479  6639 W jxcore-log: Process ARCH arm
08-12 17:14:35.493  6479  6639 W jxcore-log: 
,08-12 17:14:35.493  6656  6656 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-12 17:14:35.503  6627  6644 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 17:14:35.513  6656  6656 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-12 17:14:35.513  6656  6656 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-12 17:14:35.513  6656  6656 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDFri Aug 12 17:14:35 GMT+02:00 2016
,08-12 17:14:35.523  6656  6656 D DialogFlow: initQueue()
,08-12 17:14:35.523  6678  6678 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-12 17:14:35.523  6692  6692 E Zygote  : v2
08-12 17:14:35.523  6692  6692 I libpersona: KNOX_SDCARD checking this for 1000
08-12 17:14:35.523  6692  6692 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:35.523  6692  6692 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:35.533  6692  6692 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:35.533   773   789 I ActivityManager: Start proc 6692:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-12 17:14:35.533  6692  6692 E Zygote  : accessInfo : 0
08-12 17:14:35.533   773   789 I ActivityManager: Killing 5295:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-12 17:14:35.533   773   789 I ActivityManager: Killing 5574:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-12 17:14:35.553   773  1730 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-12 17:14:35.563  6627  6644 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 17:14:35.563   773  3916 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-12 17:14:35.573  6692  6692 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 17:14:35.573  6692  6692 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:35.583  6678  6678 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-12 17:14:35.583   773   788 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d66da9 6692:com.samsung.android.app.filterinstaller/1000}
,08-12 17:14:35.593  6692  6692 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-12 17:14:35.613  6692  6692 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-12 17:14:35.623  6692  6692 E FilterPackageIntentReceiver: This package is not a effect filter
,08-12 17:14:35.633  6708  6708 E Zygote  : v2
08-12 17:14:35.633  6708  6708 I libpersona: KNOX_SDCARD checking this for 1000
08-12 17:14:35.633  6708  6708 I libpersona: KNOX_SDCARD not a persona
,08-12 17:14:35.633  6708  6708 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:35.633  6708  6708 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:14:35.643   773  1594 I ActivityManager: Start proc 6708:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-12 17:14:35.643   773  1594 I ActivityManager: Killing 5607:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-12 17:14:35.663   773  1550 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-12 17:14:35.663  6708  6708 E Zygote  : accessInfo : 0
,08-12 17:14:35.663   773  1780 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-12 17:14:35.693   773   783 I art     : Background partial concurrent mark sweep GC freed 24111(1492KB) AllocSpace objects, 6(120KB) LOS objects, 27% free, 41MB/57MB, paused 4.608ms total 120.032ms
,08-12 17:14:35.693  6708  6708 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:35.693  6708  6708 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:35.703   773  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ff3b65 6708:com.samsung.helphub/1000}
,08-12 17:14:35.703  6708  6708 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-12 17:14:35.713  6678  6678 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-12 17:14:35.713  6678  6678 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-12 17:14:35.723  6708  6708 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-12 17:14:35.723  6678  6678 D DialogFlow: initQueue()
,08-12 17:14:35.743  6479  6639 I jxcore-log: JXcore Cordova bridge is ready!
08-12 17:14:35.743  6479  6639 I jxcore-log: 
,08-12 17:14:35.743  6479  6639 W jxcore-log: JXcore engine is started
,08-12 17:14:35.743   773  1371 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-12 17:14:35.743  6479  6614 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 17:14:35.753  6479  6479 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 17:14:35.783   773  1747 I ActivityManager: Start proc 6720:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-12 17:14:35.783  6720  6720 E Zygote  : v2
08-12 17:14:35.783  6720  6720 I libpersona: KNOX_SDCARD checking this for 1000
08-12 17:14:35.783  6720  6720 I libpersona: KNOX_SDCARD not a persona
,08-12 17:14:35.783  6720  6720 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:35.783  6720  6720 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:14:35.783   773  1747 I ActivityManager: Killing 5590:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-12 17:14:35.783  6720  6720 E Zygote  : accessInfo : 0
,08-12 17:14:35.803   773   788 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-12 17:14:35.813  6720  6720 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 17:14:35.813  6720  6720 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:35.823   773  1780 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{92d28e1 6720:com.samsung.android.app.mirrorlink/1000}
,08-12 17:14:35.823  6720  6720 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-12 17:14:35.843  6720  6720 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-12 17:14:35.873  6720  6720 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-12 17:14:35.873  6720  6720 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-12 17:14:35.883   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:14:35.883   773  1749 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e316fa0 5755:com.google.android.apps.plus/u0a134}
,08-12 17:14:35.893   773   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e316fa0 5755:com.google.android.apps.plus/u0a134}
,08-12 17:14:35.913   773  1550 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e316fa0 5755:com.google.android.apps.plus/u0a134}
,08-12 17:14:35.953   773  1731 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-12 17:14:35.953   773  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-12 17:14:35.963   773  1748 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-12 17:14:35.963   773  1550 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-12 17:14:35.963   773  3915 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-12 17:14:35.973  6558  6558 I Mms/MmsApp:  start initViewCache mms
,08-12 17:14:35.983   773  1324 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-12 17:14:35.983   773  1748 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-12 17:14:35.983   773  1780 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-12 17:14:36.013  6734  6734 E Zygote  : v2
08-12 17:14:36.013   773  1648 I ActivityManager: Start proc 6734:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-12 17:14:36.013  6734  6734 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:36.013  6734  6734 I libpersona: KNOX_SDCARD checking this for 10165
08-12 17:14:36.013  6734  6734 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:36.013  6734  6734 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:36.013  6734  6734 E Zygote  : accessInfo : 0
08-12 17:14:36.013   773  1648 I ActivityManager: Killing 5743:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
08-12 17:14:36.013  6734  6734 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-12 17:14:36.043   773  1749 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-12 17:14:36.043  6734  6734 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 17:14:36.043  6734  6734 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:36.053   773   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf2721d 6734:com.sec.kidsplat.installer/u0a165}
,08-12 17:14:36.053  6734  6734 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-12 17:14:36.063  6734  6734 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-12 17:14:36.073   773  1648 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cf2721d 6734:com.sec.kidsplat.installer/u0a165}
,08-12 17:14:36.073  6734  6734 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-12 17:14:36.093  6747  6747 E Zygote  : v2
08-12 17:14:36.093  6747  6747 I libpersona: KNOX_SDCARD checking this for 10142
08-12 17:14:36.093  6747  6747 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 17:14:36.093  6747  6747 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:36.093  6747  6747 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:36.093  6747  6747 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:36.093  6747  6747 E Zygote  : accessInfo : 64
08-12 17:14:36.093  6747  6747 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 17:14:36.093  6747  6747 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-12 17:14:36.093  6747  6747 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-12 17:14:36.103   773  1749 I ActivityManager: Start proc 6747:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-12 17:14:36.103   773  1749 I ActivityManager: Killing 5832:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-12 17:14:36.133  6747  6747 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:36.133  6747  6747 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:36.133   773  1780 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-12 17:14:36.143   773  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{16d9c92 6747:com.sec.android.app.sbrowser/u0a142}
,08-12 17:14:36.153  6747  6747 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 17:14:36.193  6747  6747 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-12 17:14:36.213  6747  6747 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 17:14:36.213  6747  6747 D ManifestProvider: onCreate()
,08-12 17:14:36.233  6747  6747 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-12 17:14:36.233  6747  6747 I SBrowserUtils: getSystemProperty of country_code : Poland
08-12 17:14:36.233  6747  6747 I SBrowserUtils: getSystemProperty of country_code : Poland
08-12 17:14:36.233  6747  6747 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-12 17:14:36.243  6747  6747 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-12 17:14:36.243  6747  6747 D [MM]MHDataBaseProvider: onCreate()
,08-12 17:14:36.253  6558  6558 D Mms/BubbleViewCache: fillCache bubble = 4
,08-12 17:14:36.263  6747  6747 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@a097a44)
,08-12 17:14:36.323   773  1731 I ActivityManager: Killing 5705:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-12 17:14:36.323   773  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8b405a 1981:com.google.android.gms.persistent/u0a11}
,08-12 17:14:36.333  2806  6763 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 17:14:36.343   773  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b6bac3 2806:com.google.android.gms/u0a11}
,08-12 17:14:36.343  2806  6762 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-12 17:14:36.343  2806  6763 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 17:14:36.353  2806  2806 D AsyncTaskServiceImpl: Submit a task: nzm
,08-12 17:14:36.363  2806  6763 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 17:14:36.363  2806  6763 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 17:14:36.373   773  3916 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8b405a 1981:com.google.android.gms.persistent/u0a11}
,08-12 17:14:36.383   773  1648 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-12 17:14:36.393  2806  4918 D nzm     : Processing package: com.test.thalitest
,08-12 17:14:36.393   773  3916 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b6bac3 2806:com.google.android.gms/u0a11}
,08-12 17:14:36.393  2806  2806 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 17:14:36.443  2806  4918 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-12 17:14:36.443  2806  4918 D nzm     : Found info for package com.test.thalitest in db.
,08-12 17:14:36.493   773  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ed000d0 5777:com.android.vending/u0a29}
,08-12 17:14:36.543   773  1594 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ec9ef u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e3aa26f 6127:com.sec.android.app.samsungapps/u0a39}
,08-12 17:14:36.563  6769  6769 E Zygote  : v2
08-12 17:14:36.563  6769  6769 I libpersona: KNOX_SDCARD checking this for 10034
08-12 17:14:36.563  6769  6769 I libpersona: KNOX_SDCARD not a persona
08-12 17:14:36.563   773   789 I ActivityManager: Start proc 6769:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-12 17:14:36.563  6769  6769 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:36.563  6769  6769 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 17:14:36.563  6769  6769 E Zygote  : accessInfo : 0
08-12 17:14:36.563  6769  6769 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-12 17:14:36.573  5777  5777 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-12 17:14:36.583  1981  1981 D WearableService: callingUid 10011, callindPid: 1981
,08-12 17:14:36.593  6769  6769 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:36.593  6769  6769 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:36.593  5777  5777 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-12 17:14:36.603   773   788 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fb5e390 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d27f489 6769:com.sec.android.app.shealth/u0a34}
,08-12 17:14:36.603  6769  6769 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-12 17:14:36.613  5777  5777 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-12 17:14:36.613  5777  5777 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-12 17:14:36.633  6769  6769 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-12 17:14:36.643  6769  6769 I MultiDex: VM with version 2.1.0 has multidex support
08-12 17:14:36.643  6769  6769 I MultiDex: install
08-12 17:14:36.643  6769  6769 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-12 17:14:36.643  6769  6769 I MultiDex: install
08-12 17:14:36.643  6769  6769 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 17:14:36.713  6769  6769 D HealthDataStore: Service for HealthDataStore is connected
,08-12 17:14:36.723   773  1324 I ActivityManager: Killing 5307:com.policydm/1000 (adj 15): DHA:empty #37
,08-12 17:14:36.723  6769  6769 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-12 17:14:36.723   773  1324 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fb5e390 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d1fca51 1887:com.sec.android.app.shealth:remote/u0a34}
,08-12 17:14:36.733  6769  6769 D HealthConsole: Service for HealthDataConsole is connected
,08-12 17:14:36.753   773  1550 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-12 17:14:36.753  6507  6507 D AASAservice: onDestroy()
,08-12 17:14:36.753  6678  6706 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-12 17:14:36.753  6678  6706 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 17:14:36.763  6769  6769 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-12 17:14:36.763  6769  6769 E HealthDataStore: disconnectService: Context instance is invalid
,08-12 17:14:36.763   773  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fb5e390 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d1fca51 1887:com.sec.android.app.shealth:remote/u0a34}
,08-12 17:14:36.763  6507  6507 I art     : System.exit called, status: 80
08-12 17:14:36.763  6507  6507 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-12 17:14:36.783   773  1298 I ActivityManager: Process com.samsung.aasaservice (pid 6507)(adj 0) has died(44,765)
,08-12 17:14:36.783   773  1298 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-12 17:14:36.803   351   351 I Zygote  : Process 6507 exited cleanly (80)
,08-12 17:14:36.803   773  1747 V AlarmManager:  remove PendingIntent] PendingIntent{bd85354: PendingIntentRecord{b7e38bb com.google.android.gms broadcastIntent}}
,08-12 17:14:36.803  6678  6706 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 17:14:36.803  6678  6706 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 17:14:36.803  6678  6706 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-12 17:14:36.813   773  1327 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 17:14:36.813   773  1327 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-12 17:14:36.813   773  1730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7742fd u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8b405a 1981:com.google.android.gms.persistent/u0a11}
,08-12 17:14:36.823  6678  6706 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-12 17:14:36.823  6678  6706 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 17:14:37.043  2806  6767 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 17:14:37.623  2806  4918 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-12 17:14:37.683  2806  4918 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 17:14:37.693  2806  4918 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 17:14:37.693  2806  4918 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-12 17:14:39.033   773  3415 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 17:14:42.903   773   942 D PackageManager: [MSG] MCS_UNBIND
,08-12 17:14:42.903   773   942 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-12 17:14:42.913   773   942 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 17:14:44.683   773  3415 D SSRM:n  : SIOP:: AP = 460, PST = 450, CUR = 350, LCD = 0
,08-12 17:14:46.043   773  1592 E Watchdog: !@Sync 3 [08-12 17:14:46.051]
,08-12 17:14:46.843   773  1327 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-12 17:14:46.843   773  1327 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 17:14:48.663   773  1730 I ActivityManager: Killing 5884:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-12 17:14:48.713   773  1648 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-12 17:14:51.503   773  1238 V AlarmManager: Expired Alarm result :4
,08-12 17:14:51.533   773   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1150c0 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8b405a 1981:com.google.android.gms.persistent/u0a11}
,08-12 17:14:51.543  5777  5823 I Finsky  : [825] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-12 17:14:51.553   773   789 V AlarmManager:  remove PendingIntent] PendingIntent{409b53e: PendingIntentRecord{9c2a1 com.google.android.gms broadcastIntent}}
,08-12 17:14:51.583   773  1780 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:14:51.583   773  1780 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4341, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 17:14:51.583   773  1780 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:14:51.583   773  1780 D BatteryService: stay LED for charging
08-12 17:14:51.583   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:14:51.583   773   773 I MotionRecognitionService: Plugged
,08-12 17:14:51.583   773   773 D MotionRecognitionService:   cableConnection= 1
08-12 17:14:51.583   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 17:14:51.583   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:14:51.583  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:14:51.583  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 17:14:51.583  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:14:51.603  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:14:51.613  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:14:51.613  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:14:51.613  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 17:14:51.613  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:14:51.683   773  1730 V AlarmManager:  remove PendingIntent] PendingIntent{1ab8ec: PendingIntentRecord{9c2a1 com.google.android.gms broadcastIntent}}
,08-12 17:14:51.753  2806  6815 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.,
08-12 17:14:51.753  2806  6815 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-12 17:14:51.783  1981  1981 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 17:14:51.793   773  1324 V AlarmManager:  remove PendingIntent] PendingIntent{6038397: PendingIntentRecord{9c2a1 com.google.android.gms broadcastIntent}}
,08-12 17:14:51.803   773   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f613984 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8b405a 1981:com.google.android.gms.persistent/u0a11}
,08-12 17:14:51.843   773  3916 V AlarmManager:  remove PendingIntent] PendingIntent{c03e56d: PendingIntentRecord{9c2a1 com.google.android.gms broadcastIntent}}
,08-12 17:14:51.843  6479  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 17:14:51.843  6479  6639 I jxcore-log: 
,08-12 17:14:51.853  6479  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 17:14:51.853  6479  6639 I jxcore-log: 
,08-12 17:14:51.853  6479  6639 D BluetoothAdapter: STATE_ON
,08-12 17:14:51.853  6479  6639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:14:51.853  6479  6639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:14:51.853  6479  6639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 17:14:51.853  6479  6639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:14:51.853  6479  6639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:14:51.853  6479  6639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:14:51.853  6479  6639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:14:51.853  6479  6639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 17:14:51.853  6479  6639 D BluetoothAdapter: STATE_ON
08-12 17:14:51.863  6479  6639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 17:14:51.863  6479  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 17:14:51.863  6479  6639 I jxcore-log: 
08-12 17:14:51.863  6479  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 17:14:51.863  6479  6639 I jxcore-log: 
,08-12 17:14:51.963   773  1747 V AlarmManager:  remove PendingIntent] PendingIntent{87a69f0: PendingIntentRecord{9c2a1 com.google.android.gms broadcastIntent}}
,08-12 17:14:52.063  5777  5823 I Finsky  : [825] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-12 17:14:52.063  5777  5777 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-12 17:14:52.093  6824  6824 E Zygote  : v2
08-12 17:14:52.093  6824  6824 I libpersona: KNOX_SDCARD checking this for 10011
08-12 17:14:52.093  6824  6824 I libpersona: KNOX_SDCARD not a persona
,08-12 17:14:52.103  6824  6824 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 17:14:52.103  6824  6824 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:14:52.103   773  1298 I ActivityManager: Start proc 6824:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
08-12 17:14:52.103  6824  6824 E Zygote  : accessInfo : 0
,08-12 17:14:52.103  6824  6824 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-12 17:14:52.133  6824  6824 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:14:52.133  6824  6824 D ActivityThread: Added TimaKeyStore provider
,08-12 17:14:52.153  6824  6824 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 17:14:52.183  6824  6824 I MultiDex: VM with version 2.1.0 has multidex support
08-12 17:14:52.183  6824  6824 I MultiDex: install
08-12 17:14:52.183  6824  6824 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 17:14:52.203  6824  6824 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-12 17:14:52.213  6824  6824 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-12 17:14:52.213  6824  6824 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-12 17:14:52.223  6824  6824 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 17:14:52.243  6824  6824 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 17:14:52.263  6824  6824 D ChimeraCfgMgr: Reading stored module config
,08-12 17:14:52.283  6479  6639 I jxcore-log: Unit Test app is loaded
08-12 17:14:52.283  6479  6639 I jxcore-log: 
,08-12 17:14:52.283  6479  6479 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 17:14:52.283  6479  6639 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 17:14:52.283  6479  6639 I jxcore-log: 
,08-12 17:14:52.293  6479  6639 I jxcore-log: My device name is: samsung-SM-G900F
08-12 17:14:52.293  6479  6639 I jxcore-log: 
,08-12 17:14:52.363  6824  6839 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-12 17:14:52.373  1981  1981 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=edf48aa9-8dd3-4cee-b62c-cda72f1e16fe
,08-12 17:14:52.383  1981  1981 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 17:14:52.383  1981  1981 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 17:14:52.413   319   319 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6824)
,08-12 17:14:52.463   319   972 D WVCdm   : Instantiating CDM.
,08-12 17:14:52.463   319   941 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6824)
08-12 17:14:52.463   319   941 I WVCdm   : CdmEngine::OpenSession
08-12 17:14:52.463   319   941 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-12 17:14:52.473   319   941 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-12 17:14:52.483   319   941 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-12 17:14:52.483   319   941 D DrmWidevineDash: Service_Initialize: starts!
,08-12 17:14:52.483   319   941 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-12 17:14:52.483   319   941 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 17:14:52.483   319   941 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-12 17:14:52.483   319   941 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-12 17:14:52.483   319   941 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-12 17:14:52.483   319   941 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 17:14:52.483   319   941 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-12 17:14:52.483   319   941 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-12 17:14:52.483   319   941 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-12 17:14:52.483   319   941 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 17:14:52.513   319   941 D QSEECOMAPI: : Loaded image: APP id = 3
,08-12 17:14:52.513   319   941 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-12 17:14:52.513   319   941 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef57000
08-12 17:14:52.513   319   941 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef57000
,08-12 17:14:52.513  6824  6835 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:52.513  6824  6835 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:52.523   307  1156 D EnterpriseController: netId is 0
08-12 17:14:52.523   307  1156 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 17:14:52.533   319   941 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-12 17:14:52.533   319   941 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-12 17:14:52.533   319   941 D DrmWidevineDash: hlos api version =  10
08-12 17:14:52.533   319   941 D DrmWidevineDash: tz api version =  10
08-12 17:14:52.533   319   941 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-12 17:14:52.533   319   941 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-12 17:14:52.543   319   941 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-12 17:14:52.543   319   941 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-12 17:14:52.543   319   941 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf17e924
,08-12 17:14:52.543   319   941 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-12 17:14:52.543   319   941 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-12 17:14:52.543   319   941 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xae23da48, dataLength=8
08-12 17:14:52.543   319   941 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-12 17:14:52.553   319   941 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xae257800, wrapped_rsa_key_length=1280
,08-12 17:14:52.553   319   941 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-12 17:14:52.553   319   941 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-12 17:14:52.553   319   962 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-12 17:14:52.553   319   962 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-12 17:14:52.553   319   962 I WVCdm   : CdmEngine::GenerateKeyRequest
08-12 17:14:52.553   319   962 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xad410380, idLength=0xaf07ff2c
,08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-12 17:14:52.563   319   962 D DrmWidevineDash: hlos api version =  10
08-12 17:14:52.563   319   962 D DrmWidevineDash: tz api version =  10
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-12 17:14:52.563   319   962 D WVCdm   : PrepareKeyRequest: nonce=2668824479
08-12 17:14:52.563   319   962 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d85f00
08-12 17:14:52.563   319   962 D DrmWidevineDash: message_length=1631, signature=0xaec49500, signature_length=2936537092
,08-12 17:14:52.573  6824  6835 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6824, getuid(): 10011
,08-12 17:14:52.583  1981  2344 W GCoreFlp: No location to return for getLastLocation()
,08-12 17:14:52.643  2806  6819 D UdcContextInitService: registered all accounts: true
,08-12 17:14:52.693  1981  2408 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 17:14:52.703   319   962 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-12 17:14:52.703  1981  2621 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-12 17:14:52.713  6824  6835 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6824, getuid(): 10011
,08-12 17:14:52.713   319   972 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6824)
08-12 17:14:52.713   319   972 I WVCdm   : CdmEngine::CloseSession
08-12 17:14:52.713   319   972 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-12 17:14:52.713   319   972 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-12 17:14:52.713   319   972 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-12 17:14:52.713   319   972 D DrmWidevineDash: Service_Uninitialize: starts!
08-12 17:14:52.713   319   972 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-12 17:14:52.713   319   972 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,08-12 17:14:52.713   319   972 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-12 17:14:52.713   319   972 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-12 17:14:52.773   773   783 I art     : Background partial concurrent mark sweep GC freed 28941(1582KB) AllocSpace objects, 11(220KB) LOS objects, 27% free, 42MB/58MB, paused 1.679ms total 125.198ms
,08-12 17:14:52.803   773   788 V AlarmManager:  remove PendingIntent] PendingIntent{89a967b: PendingIntentRecord{9c2a1 com.google.android.gms broadcastIntent}}
,08-12 17:14:52.833  6824  6835 I qtaguid : Untagging socket 21
,08-12 17:14:52.873  6824  6835 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 17:14:52.873  6824  6835 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 17:14:53.063  1981  6853 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 17:14:53.063  1981  6851 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-12 17:14:53.073  1981  6853 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 17:14:53.073  1981  6851 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-12 17:14:53.093  1981  6853 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 17:14:53.093  1981  6851 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-12 17:14:53.093  1981  6851 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-12 17:14:53.103  1981  6851 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 17:14:53.173   773  3915 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 17:14:53.243  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:53.243  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:53.243   307  1156 D EnterpriseController: netId is 0
08-12 17:14:53.243   307  1156 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 17:14:53.243  1981  6851 I qtaguid : Tagging socket 55 with tag 11065c0800000000{285629448,0} uid -1, pid: 1981, getuid(): 10011
,08-12 17:14:53.283  1981  6851 I qtaguid : Tagging socket 58 with tag 11065c0800000000{285629448,0} uid -1, pid: 1981, getuid(): 10011
,08-12 17:14:53.423  6856  6856 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-12 17:14:53.513  6856  6856 I dex2oat : ----------------------------------------------------
08-12 17:14:53.513  6856  6856 I dex2oat : <SS>: S T A R T I N G . . .
08-12 17:14:53.513  6856  6856 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,08-12 17:14:53.513  6856  6856 I dex2oat : dex2oat took 88.238ms (threads: 4) arena alloc=200KB java alloc=43KB native alloc=1667KB free=1404KB
08-12 17:14:53.513   773  1324 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 17:14:53.523  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:53.523  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:53.523  1981  6851 I qtaguid : Tagging socket 55 with tag 11065b5800000000{285629272,0} uid -1, pid: 1981, getuid(): 10011
,08-12 17:14:53.523  6824  6835 W System  : ClassLoader referenced unknown path: 
,08-12 17:14:53.523  6824  6835 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-12 17:14:53.533  6824  6835 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 17:14:53.533  6824  6835 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 17:14:53.533  6824  6835 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 17:14:53.533  6824  6835 I Adreno-EGL: Local Branch: ss
08-12 17:14:53.533  6824  6835 I Adreno-EGL: Remote Branch: 
08-12 17:14:53.533  6824  6835 I Adreno-EGL: Local Patches: 
08-12 17:14:53.533  6824  6835 I Adreno-EGL: Reconstruct Branch: 
,08-12 17:14:53.533  6824  6835 D libEGL  : eglInitialize EGLDisplay = 0xb2ff6264
,08-12 17:14:53.583  6824  6835 D libEGL  : eglTerminate EGLDisplay = 0xb2ff62bc
,08-12 17:14:53.593  6824  6835 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 17:14:53.593  6824  6835 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 17:14:53.593  6824  6835 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 17:14:53.593  6824  6835 I Adreno-EGL: Local Branch: ss
08-12 17:14:53.593  6824  6835 I Adreno-EGL: Remote Branch: 
08-12 17:14:53.593  6824  6835 I Adreno-EGL: Local Patches: 
08-12 17:14:53.593  6824  6835 I Adreno-EGL: Reconstruct Branch: 
,08-12 17:14:53.593  6824  6835 D libEGL  : eglInitialize EGLDisplay = 0xb2ff6264
,08-12 17:14:53.613   773  1780 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 17:14:53.633  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:53.633  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:53.633  1981  6851 I qtaguid : Tagging socket 55 with tag fffffca200000000{4294966434,0} uid -1, pid: 1981, getuid(): 10011
,08-12 17:14:53.643  6824  6835 D libEGL  : eglTerminate EGLDisplay = 0xb2ff62bc
,08-12 17:14:53.643  6824  6835 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 17:14:53.643  6824  6835 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 17:14:53.643  6824  6835 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 17:14:53.643  6824  6835 I Adreno-EGL: Local Branch: ss
08-12 17:14:53.643  6824  6835 I Adreno-EGL: Remote Branch: 
08-12 17:14:53.643  6824  6835 I Adreno-EGL: Local Patches: 
08-12 17:14:53.643  6824  6835 I Adreno-EGL: Reconstruct Branch: 
08-12 17:14:53.643  6824  6835 D libEGL  : eglInitialize EGLDisplay = 0xb2ff6264
,08-12 17:14:53.683  6824  6835 D libEGL  : eglTerminate EGLDisplay = 0xb2ff62bc
,08-12 17:14:53.703  1981  6821 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:53.703  1981  6821 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:53.703   307  1156 D EnterpriseController: netId is 0
08-12 17:14:53.703   307  1156 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 17:14:53.703  1981  6821 I qtaguid : Tagging socket 52 with tag 1000040100000000{268436481,0} uid 10011, pid: 1981, getuid(): 10011
,08-12 17:14:53.733  1981  6821 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} uid 10011, pid: 1981, getuid(): 10011
,08-12 17:14:53.753   773  1747 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 17:14:53.783  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:53.783  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:53.783  1981  6851 I qtaguid : Tagging socket 55 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 1981, getuid(): 10011
,08-12 17:14:53.913   773  3915 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 17:14:53.913  1981  6851 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-12 17:14:53.923   773  3915 V AlarmManager:  remove PendingIntent] PendingIntent{bd434ae: PendingIntentRecord{9c2a1 com.google.android.gms broadcastIntent}}
,08-12 17:14:53.933  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:53.933  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:53.933  1981  6851 I qtaguid : Tagging socket 55 with tag fffff65b00000000{4294964827,0} uid -1, pid: 1981, getuid(): 10011
,08-12 17:14:53.933  1981  2621 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 17:14:53.943  1981  2621 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-12 17:14:53.963  1981  6869 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:53.963  1981  6869 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:53.963   307  1156 D EnterpriseController: netId is 0
08-12 17:14:53.963   307  1156 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 17:14:53.963  1981  6869 I qtaguid : Tagging socket 62 with tag 1000310500000000{268448005,0} uid 10011, pid: 1981, getuid(): 10011
,08-12 17:14:53.963  1981  2621 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-12 17:14:52.809+0200, stopTime=2016-08-12 17:14:53.961+0200, duration=1152ms
,08-12 17:14:53.993  1981  6869 I qtaguid : Tagging socket 65 with tag 1000310500000000{268448005,0} uid 10011, pid: 1981, getuid(): 10011
,08-12 17:14:54.033   773  1747 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 17:14:54.043  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:54.043  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:54.043  1981  6851 I qtaguid : Tagging socket 55 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 1981, getuid(): 10011
,08-12 17:14:54.133   773  1298 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 17:14:54.133  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:54.133  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:54.133  1981  6851 I qtaguid : Tagging socket 55 with tag 11065fff00000000{285630463,0} uid -1, pid: 1981, getuid(): 10011
,08-12 17:14:54.223  1981  6869 I qtaguid : Untagging socket 62
,08-12 17:14:54.223  1981  2621 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-12 17:14:54.223   773  1749 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 17:14:54.233  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 17:14:54.233  1981  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:54.233  1981  6851 I qtaguid : Tagging socket 55 with tag 11065c9100000000{285629585,0} uid -1, pid: 1981, getuid(): 10011
,08-12 17:14:54.373   773  1550 V AlarmManager:  remove PendingIntent] PendingIntent{7b25ddc: PendingIntentRecord{9c2a1 com.google.android.gms broadcastIntent}}
,08-12 17:14:54.713   773  3415 D SSRM:n  : SIOP:: AP = 460, PST = 450, CUR = 350, LCD = 0
,08-12 17:14:54.813  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 17:14:54.813  6479  6639 I jxcore-log: 
,08-12 17:14:55.433  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 17:14:55.433  6479  6639 I jxcore-log: 
,08-12 17:14:55.453  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 17:14:55.453  6479  6639 I jxcore-log: 
,08-12 17:14:55.883   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:14:56.053  1981  6868 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:56.053  1981  6868 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 17:14:56.053  1981  6868 I qtaguid : Tagging socket 62 with tag 1000310200000000{268448002,0} uid 10011, pid: 1981, getuid(): 10011
,08-12 17:14:56.293  1981  6868 I qtaguid : Untagging socket 62
,08-12 17:14:56.293  1981  2621 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-12 17:14:56.813  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 17:14:56.813  6479  6639 I jxcore-log: 
,08-12 17:14:57.033  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 17:14:57.033  6479  6639 I jxcore-log: 
,08-12 17:14:57.043  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 17:14:57.043  6479  6639 I jxcore-log: 
,08-12 17:14:57.043  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 17:14:57.043  6479  6639 I jxcore-log: 
,08-12 17:14:57.063  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 17:14:57.063  6479  6639 I jxcore-log: 
,08-12 17:14:57.063  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
08-12 17:14:57.063  6479  6639 I jxcore-log: 
,08-12 17:14:57.733  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 17:14:57.733  6479  6639 I jxcore-log: 
,08-12 17:14:57.743  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 17:14:57.743  6479  6639 I jxcore-log: 
,08-12 17:14:57.753  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 17:14:57.753  6479  6639 I jxcore-log: 
,08-12 17:14:57.763  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 17:14:57.763  6479  6639 I jxcore-log: 
,08-12 17:14:57.823  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 17:14:57.823  6479  6639 I jxcore-log: 
,08-12 17:14:57.883  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 17:14:57.883  6479  6639 I jxcore-log: 
,08-12 17:14:57.893  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 17:14:57.893  6479  6639 I jxcore-log: 
,08-12 17:14:58.053  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 17:14:58.053  6479  6639 I jxcore-log: 
,08-12 17:14:58.083  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 17:14:58.083  6479  6639 I jxcore-log: 
,08-12 17:14:58.093  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 17:14:58.093  6479  6639 I jxcore-log: 
,08-12 17:14:58.103  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 17:14:58.103  6479  6639 I jxcore-log: 
,08-12 17:14:58.123  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 17:14:58.123  6479  6639 I jxcore-log: 
,08-12 17:14:58.203  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 17:14:58.203  6479  6639 I jxcore-log: 
,08-12 17:14:58.213  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 17:14:58.213  6479  6639 I jxcore-log: 
,08-12 17:14:58.243  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 17:14:58.243  6479  6639 I jxcore-log: 
,08-12 17:14:58.263  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 17:14:58.263  6479  6639 I jxcore-log: 
,08-12 17:14:58.283  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 17:14:58.283  6479  6639 I jxcore-log: 
,08-12 17:14:58.313  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 17:14:58.313  6479  6639 I jxcore-log: 
,08-12 17:14:58.323  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 17:14:58.323  6479  6639 I jxcore-log: 
,08-12 17:14:58.523  6479  6639 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 17:14:58.523  6479  6639 I jxcore-log: 
,08-12 17:14:58.533  6479  6639 D BluetoothAdapter: STATE_ON
,08-12 17:14:58.533  6479  6639 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 17:14:58.533  6479  6639 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 17:14:58.533  6479  6639 I jxcore-log: 
,08-12 17:14:58.693   773  1594 I ActivityManager: Killing 5429:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-12 17:14:58.703   773   789 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-12 17:14:59.993   773  1238 V AlarmManager: Expired Alarm result :8,
,08-12 17:15:01.663   773   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:15:01.673   773   789 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:15:01.673   773   789 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:15:01.673   773   789 D BatteryService: stay LED for charging
,08-12 17:15:01.673   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:15:01.693   773   773 I MotionRecognitionService: Plugged
,08-12 17:15:01.693   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:15:01.703   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:15:01.703   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:15:01.713  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:15:01.713  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:15:01.713  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:15:01.733  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:15:01.733  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:15:01.743  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:01.743  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:01.743  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:04.773   773  3415 D SSRM:n  : SIOP:: AP = 420, PST = 443, CUR = 350, LCD = 0
,08-12 17:15:04.813   773  3415 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 17:15:11.743   773  1298 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:15:11.753   773  1298 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:15:11.753   773  1298 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:15:11.763   773  1298 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
,08-12 17:15:11.763   773  1298 D BatteryService: stay LED for charging
,08-12 17:15:11.763   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:15:11.773   773   773 I MotionRecognitionService: Plugged
,08-12 17:15:11.783   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:15:11.783   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:15:11.783   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:15:11.793  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:15:11.793  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:15:11.803  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:15:11.823  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:15:11.823  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:15:11.833  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:11.833  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:11.833  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:14.883   773  3415 D SSRM:n  : SIOP:: AP = 400, PST = 436, CUR = 350, LCD = 0
,08-12 17:15:15.893   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:15:16.053   773  1592 E Watchdog: !@Sync 4 [08-12 17:15:16.055]
,08-12 17:15:16.893  1680  1751 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 17:15:24.943   773  3415 D SSRM:n  : SIOP:: AP = 370, PST = 430, CUR = 350, LCD = 0
,08-12 17:15:31.393   773  1238 V AlarmManager: Expired Alarm result :4
,08-12 17:15:31.463   773  1298 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:15:31.463   773  1298 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:15:31.463   773  1298 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-12 17:15:31.463   773  1298 D BatteryService: stay LED for charging
,08-12 17:15:31.523  6894  6894 E Zygote  : v2
,08-12 17:15:31.523  6894  6894 I libpersona: KNOX_SDCARD checking this for 1000
08-12 17:15:31.523  6894  6894 I libpersona: KNOX_SDCARD not a persona
,08-12 17:15:31.523  6894  6894 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 17:15:31.523  6894  6894 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:15:31.523  6894  6894 E Zygote  : accessInfo : 0
,08-12 17:15:31.543   773  1238 I ActivityManager: Start proc 6894:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-12 17:15:31.553   773   773 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-12 17:15:31.553   773   773 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-12 17:15:31.553   773   773 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-12 17:15:31.563  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-12 17:15:31.563  1385  1385 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-12 17:15:31.563  1385  1385 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 17:15:31.573   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:15:31.593   773   773 I MotionRecognitionService: Plugged
08-12 17:15:31.593   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:15:31.593   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 17:15:31.593   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:15:31.593  1385  1385 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-12 17:15:31.593  1385  1385 D SecKeyguardClockView: HomeTimezone(): 1
,08-12 17:15:31.603  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:15:31.603  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 17:15:31.603  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:15:31.603  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:15:31.603  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:15:31.603  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:15:31.613  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 17:15:31.613  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:15:31.613  1385  1385 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:15:31.613  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 17:15:31.613  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:15:31.613  6894  6894 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 17:15:31.613  6894  6894 D ActivityThread: Added TimaKeyStore provider
,08-12 17:15:31.613  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:31.613  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 17:15:31.613  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:31.633  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:15:31.633  6894  6894 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-12 17:15:31.653  6894  6894 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-12 17:15:31.673  1385  1385 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:15:31.683   773  1324 I ActivityManager: Killing 5980:com.google.android.apps.photos/u0a199 (adj 15): DHA:empty #37
,08-12 17:15:31.703   773   789 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-12 17:15:35.013   773  3415 D SSRM:n  : SIOP:: AP = 350, PST = 423, CUR = 350, LCD = 0
,08-12 17:15:35.013   773  3415 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,08-12 17:15:35.093   773   861 I ActivityManager: Start proc 6935:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,08-12 17:15:35.103   773  1327 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 17:15:35.103  6935  6935 E Zygote  : v2
,08-12 17:15:35.103  6935  6935 I libpersona: KNOX_SDCARD checking this for 10053
08-12 17:15:35.103  6935  6935 I libpersona: KNOX_SDCARD not a persona
,08-12 17:15:35.103  6935  6935 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 17:15:35.113  6935  6935 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 17:15:35.113  6935  6935 E Zygote  : accessInfo : 0
,08-12 17:15:35.113   773  3415 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 17:15:35.123  2778  2778 D ContentApp:  LEVEL : 0
,08-12 17:15:35.123  6935  6935 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-12 17:15:35.223  6935  6935 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 17:15:35.223  6935  6935 D ActivityThread: Added TimaKeyStore provider
,08-12 17:15:35.243   773  1298 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ca8c74 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c1559d 6935:com.sec.android.app.videoplayer/u0a53}
,08-12 17:15:35.243   773  1327 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 17:15:35.243  6935  6935 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-12 17:15:35.273  6935  6935 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-12 17:15:35.303  6935  6935 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-12 17:15:35.333  6935  6935 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-12 17:15:35.333  6935  6935 D videowall-Global: core_num = 4
,08-12 17:15:35.343  6935  6935 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
08-12 17:15:35.343  6935  6935 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-12 17:15:35.353  6935  6935 D TranscodeReceiver:  SIOP_LEVEL: 0
,08-12 17:15:35.353   773  1730 I ActivityManager: Killing 6016:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-12 17:15:35.383   773  1780 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,08-12 17:15:35.893   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-12 17:15:40.843  2806  4978 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 17:15:41.553   773  1749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:15:41.563   773  1749 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:15:41.563   773  1749 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:15:41.573   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:15:41.583   773   773 I MotionRecognitionService: Plugged
,08-12 17:15:41.583   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:15:41.593   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:15:41.593   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:15:41.593   773  1749 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,08-12 17:15:41.603   773  1749 D BatteryService: stay LED for charging
,08-12 17:15:41.603  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:15:41.603  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:15:41.603  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:15:41.623  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:15:41.623  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:15:41.633  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:41.633  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:41.633  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 17:15:43.403  1981  3288 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 17:15:45.183   773  3415 D SSRM:n  : SIOP:: AP = 340, PST = 415, CUR = 350, LCD = 0
,08-12 17:15:46.063   773  1592 E Watchdog: !@Sync 5 [08-12 17:15:46.063]
,08-12 17:15:46.253   773  3419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-12 17:15:46.263   773   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae366f8 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e89590d 6340:com.samsung.android.sm.provider/1000}
,08-12 17:15:46.363   773  3419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,08-12 17:15:46.373   773   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{28236 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e89590d 6340:com.samsung.android.sm.provider/1000}
,08-12 17:15:51.663   773   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:15:51.673   773   789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:15:51.673   773   789 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:15:51.673   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:15:51.693   773   773 I MotionRecognitionService: Plugged
,08-12 17:15:51.693   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:15:51.693   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:15:51.693   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:15:51.703  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:15:51.703  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:15:51.703  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:15:51.703  1385  1385 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:15:51.713   773   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 39ms
,08-12 17:15:51.713   773   789 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 773) 
,08-12 17:15:51.713   773   789 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,08-12 17:15:51.723   773   789 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-12 17:15:51.723  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:15:51.733  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:15:51.733  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:15:51.733  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:15:51.733  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:15:51.733   773   789 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-12 17:15:51.753   773   789 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-12 17:15:51.753   773   789 D BatteryService: turn on LED for fully charged
,08-12 17:15:52.123   773  1221 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
08-12 17:15:52.123   773   919 D LightsService: [SvcLED]  onSensorChanged::light value = 0
08-12 17:15:52.123   773   919 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-12 17:15:52.133   773   919 D SensorManager: unregisterListener ::   
,08-12 17:15:52.133   773   919 D lights  : led_pattern : 5 +
,08-12 17:15:52.143   773   919 D lights  : led_pattern : 5 -
,08-12 17:15:52.143   773   919 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-12 17:15:52.143   773   919 V AlarmManager:  remove PendingIntent] PendingIntent{bbf219f: PendingIntentRecord{c99f2ec android broadcastIntent}}
,08-12 17:15:55.253   773  3415 D SSRM:n  : SIOP:: AP = 340, PST = 408, CUR = 350, LCD = 0
,08-12 17:15:55.253   773  3415 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-12 17:15:55.273  2778  2778 D ContentApp:  LEVEL : -1
,08-12 17:15:55.303   773   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{963faa4 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c1559d 6935:com.sec.android.app.videoplayer/u0a53}
,08-12 17:15:55.303  6935  6935 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-12 17:15:55.313  6935  6935 D TranscodeReceiver:  SIOP_LEVEL: -1
,08-12 17:15:55.903   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:15:59.993   773  1238 V AlarmManager: Expired Alarm result :8
,08-12 17:16:01.733   773  1594 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:16:05.353   773  3415 D SSRM:n  : SIOP:: AP = 330, PST = 395, CUR = 350, LCD = 0
,08-12 17:16:11.823   773  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:16:15.413   773  3415 D SSRM:n  : SIOP:: AP = 330, PST = 380, CUR = 350, LCD = 0
,08-12 17:16:15.913   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:16:16.063   773  1592 E Watchdog: !@Sync 6 [08-12 17:16:16.070]
,08-12 17:16:16.913  1680  1751 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 17:16:21.913   773  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:16:21.913   773  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:16:21.923   773  1648 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:16:21.923   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:16:21.933   773   773 I MotionRecognitionService: Plugged
,08-12 17:16:21.933   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:16:21.943   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:16:21.943   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:16:21.953   773  1648 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-12 17:16:21.953   773  1648 D BatteryService: stay LED for fully charged
,08-12 17:16:21.953  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:16:21.953  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:16:21.953  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:16:21.973  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:16:21.973  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:16:21.983  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:16:21.983  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:16:21.983  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:16:25.473   773  3415 D SSRM:n  : SIOP:: AP = 320, PST = 366, CUR = 350, LCD = 0
,08-12 17:16:32.003   773  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:16:32.003   773  1731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:16:32.013   773  1731 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:16:32.023   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:16:32.033   773   773 I MotionRecognitionService: Plugged
,08-12 17:16:32.033   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:16:32.033   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:16:32.033   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:16:32.043   773  1731 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,08-12 17:16:32.043   773  1731 D BatteryService: stay LED for fully charged
,08-12 17:16:32.053  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:16:32.053  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:16:32.053  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:16:32.063  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:16:32.073  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:16:32.073  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:16:32.083  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:16:32.083  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:16:35.533   773  3415 D SSRM:n  : SIOP:: AP = 320, PST = 352, CUR = 350, LCD = 0
,08-12 17:16:35.913   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:16:42.093   773  1594 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:16:45.593   773  3415 D SSRM:n  : SIOP:: AP = 320, PST = 342, CUR = 350, LCD = 0
,08-12 17:16:46.073   773  1592 E Watchdog: !@Sync 7 [08-12 17:16:46.075]
,08-12 17:16:52.173   773  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:16:52.183   773  1731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:16:52.183   773  1731 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:16:52.183   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:16:52.203   773   773 I MotionRecognitionService: Plugged
,08-12 17:16:52.203   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:16:52.203   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:16:52.203   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:16:52.213   773  1731 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-12 17:16:52.213   773  1731 D BatteryService: stay LED for fully charged
,08-12 17:16:52.223  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:16:52.223  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:16:52.223  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:16:52.253  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:16:52.253  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:16:52.253  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:16:52.263  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:16:52.263  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:16:55.653   773  3415 D SSRM:n  : SIOP:: AP = 320, PST = 334, CUR = 350, LCD = 0
,08-12 17:16:55.913   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:17:02.253   773  1594 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:17:02.263   773  1594 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:17:02.263   773  1594 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:17:02.273   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:17:02.283   773   773 I MotionRecognitionService: Plugged
,08-12 17:17:02.283   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:17:02.283   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:17:02.293   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:17:02.293   773  1594 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-12 17:17:02.293   773  1594 D BatteryService: stay LED for fully charged
,08-12 17:17:02.303  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:17:02.303  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:17:02.303  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:17:02.313  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:17:02.323  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:17:02.323  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:02.333  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:02.333  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:05.713   773  3415 D SSRM:n  : SIOP:: AP = 320, PST = 329, CUR = 350, LCD = 0
,08-12 17:17:12.353   773  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:17:12.353   773  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:17:12.363   773  1648 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:17:12.363   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:17:12.373   773   773 I MotionRecognitionService: Plugged
,08-12 17:17:12.373   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:17:12.383   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:17:12.383   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:17:12.383   773  1648 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-12 17:17:12.393   773  1648 D BatteryService: stay LED for fully charged
,08-12 17:17:12.403  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:17:12.403  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 17:17:12.403  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:17:12.413  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:17:12.413  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:17:12.423  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:12.423  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:12.423  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:15.773   773  3415 D SSRM:n  : SIOP:: AP = 310, PST = 325, CUR = 350, LCD = 0
,08-12 17:17:15.923   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:17:16.073   773  1592 E Watchdog: !@Sync 8 [08-12 17:17:16.079]
,08-12 17:17:16.923  1680  1751 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 17:17:17.093  1680  1751 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 166ms lastUpdatedAfter : 163539ms
,08-12 17:17:22.443   773  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:17:25.833   773  3415 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 350, LCD = 0
,08-12 17:17:32.533   773  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:17:32.533   773  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:17:32.533   773  1648 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:17:32.543   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:17:32.553   773   773 I MotionRecognitionService: Plugged
,08-12 17:17:32.553   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:17:32.553   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:17:32.553   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:17:32.563   773  1648 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-12 17:17:32.563   773  1648 D BatteryService: stay LED for fully charged
,08-12 17:17:32.573  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:17:32.573  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:17:32.573  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:17:32.603  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:17:32.603  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:17:32.613  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:32.613  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 17:17:32.613  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:35.903   773  3415 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 350, LCD = 0
,08-12 17:17:35.923   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:17:42.603   773  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:17:45.963   773  3415 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 350, LCD = 0
,08-12 17:17:46.083   773  1592 E Watchdog: !@Sync 9 [08-12 17:17:46.083]
,08-12 17:17:52.693   773  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:17:52.703   773  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:17:52.713   773  1730 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 17:17:52.713   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:17:52.723   773   773 I MotionRecognitionService: Plugged
,08-12 17:17:52.723   773   773 D MotionRecognitionService:   cableConnection= 1
,08-12 17:17:52.733   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 17:17:52.733   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:17:52.733   773  1730 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-12 17:17:52.743   773  1730 D BatteryService: stay LED for fully charged
,08-12 17:17:52.753  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:17:52.753  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 17:17:52.753  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:17:52.763  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:17:52.763  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:17:52.773  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:52.773  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:52.783  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:17:55.933   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:17:56.023   773  3415 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 350, LCD = 0
,08-12 17:18:00.793   773  1232 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-12 17:18:00.803   773  1231 D TimaService: TimaServiceHandler.handleMessage what =1
,08-12 17:18:00.803   773  1232 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-12 17:18:00.823   773  1232 I TLC_TIMA_PKM_initialize: initializing...
,08-12 17:18:00.823   773  1232 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,08-12 17:18:00.823   773  1232 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-12 17:18:00.833   773  1232 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,08-12 17:18:00.833   773  1232 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-12 17:18:00.833   773  1232 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-12 17:18:00.833   773  1232 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,08-12 17:18:00.833   773  1232 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,08-12 17:18:00.843   773  1232 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-12 17:18:00.843   773  1232 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 17:18:00.873   773  1232 D QSEECOMAPI: : Loaded image: APP id = 3
,08-12 17:18:00.883   773  1232 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-12 17:18:00.893   773  1232 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-12 17:18:02.783   773  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:18:04.213   773  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-12 17:18:04.213   773  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-12 17:18:04.223   773  1232 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-12 17:18:04.233   773  1232 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-12 17:18:06.093   773  3415 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 350, LCD = 0
,08-12 17:18:06.303   307  1152 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 17:18:06.303   307  1152 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 17:18:06.303   307  1152 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 17:18:15.053   307  1152 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 17:18:15.053   307  1152 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 17:18:15.053   307  1152 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 17:18:15.933   773  3459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 17:18:16.083   773  1592 E Watchdog: !@Sync 10 [08-12 17:18:16.088]
,08-12 17:18:16.143   773  3415 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 350, LCD = 0
,08-12 17:18:16.793   773  1238 V AlarmManager: Expired Alarm result :4
,08-12 17:18:16.813  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-12 17:18:16.823  1385  1385 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-12 17:18:16.823  1385  1385 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 17:18:16.873   773  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 17:18:16.873   773  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 17:18:16.873   773  1747 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-12 17:18:16.873   773  1747 D BatteryService: stay LED for fully charged
,08-12 17:18:16.893  1385  1385 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-12 17:18:16.893  1565  1565 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-12 17:18:16.893  1565  1565 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-12 17:18:16.913  1385  1385 D SecKeyguardClockView: HomeTimezone(): 1
,08-12 17:18:16.913  1565  1565 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-12 17:18:16.933  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:18:16.933  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:18:16.933   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 17:18:16.933  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:18:16.943  2201  2201 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 17:18:16.943  2201  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 17:18:16.953   773   773 I MotionRecognitionService: Plugged
,08-12 17:18:16.953   773   773 D MotionRecognitionService:   cableConnection= 1
08-12 17:18:16.953   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 17:18:16.953   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-12 17:18:16.953  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:18:16.953  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:18:16.963  1385  1385 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:18:16.963  1385  1385 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:18:16.963  1385  1385 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:18:16.963  1385  1385 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 17:18:16.973  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:18:16.973  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 17:18:16.973  1385  1385 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 17:18:16.983  1385  1385 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 17:18:17.013  1385  1385 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 17:18:17.193  1680  1751 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 17:18:20.713  1565  1565 I wpa_supplicant: nl80211: Received scan results (41 BSSes)
,08-12 17:18:20.723   307  1153 D Netd    : Iface wlan0 link up
,08-12 17:18:20.743   773   867 D Tethering: interfaceLinkStateChanged wlan0, true
,08-12 17:18:20.743   773   867 D Tethering: interfaceStatusChanged wlan0, true
,08-12 17:18:20.743  1565  1565 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,08-12 17:18:20.773   773  1328 D WifiP2pService: InactiveState{ what=147461 }
,08-12 17:18:20.773   773  1328 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-12 17:18:20.783   773  1328 D WifiP2pService: DefaultState{ what=147461 }
,08-12 17:18:20.853   773   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8d8cdd3 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5bb108 1385:com.android.systemui/u0a58}
,08-12 17:18:23.463  6479  6639 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 17:18:23.463  6479  6639 I jxcore-log: 
,08-12 17:18:24.203  6479  6639 I jxcore-log: TAP version 13
08-12 17:18:24.203  6479  6639 I jxcore-log: 
,08-12 17:18:24.213  6479  6639 I jxcore-log: # setup
08-12 17:18:24.213  6479  6639 I jxcore-log: 
,08-12 17:18:24.283  6479  6639 I jxcore-log: # 1. calling createNativeListener directly rejects
08-12 17:18:24.283  6479  6639 I jxcore-log: 
,08-12 17:18:24.513  2206  2206 E audit   : type=1400 msg=audit(1471015104.513:289): avc:  denied  { execmod } for  pid=7025 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 17:18:24.523  2206  2206 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 17:18:24.523  2206  2206 E audit   : type=1300 msg=audit(1471015104.513:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f95000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=7025 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 17:18:24.523  2206  2206 E audit   : type=1327 msg=audit(1471015104.513:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 17:18:24.523  2206  2206 E audit   : type=1320 msg=audit(1471015104.513:289): 
,08-12 17:18:24.573  2206  2206 E audit   : type=1400 msg=audit(1471015104.573:290): avc:  denied  { execmod } for  pid=7025 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-12 17:18:24.573  2206  2206 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 17:18:24.573  2206  2206 E audit   : type=1300 msg=audit(1471015104.573:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f55000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=7025 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 17:18:24.573  2206  2206 E audit   : type=1327 msg=audit(1471015104.573:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-12 17:18:24.573  2206  2206 E audit   : type=1320 msg=audit(1471015104.573:290): 
,08-12 17:18:24.623  2206  2206 E audit   : type=1400 msg=audit(1471015104.623:291): avc:  denied  { execmod } for  pid=7025 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-12 17:18:24.623  7025  7025 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 17:18:24.623  2206  2206 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 17:18:24.623  2206  2206 E audit   : type=1300 msg=audit(1471015104.623:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f55000 a1=51000 a2=5 a3=4 items=0 ppid=3593 ppcomm=adbd pid=7025 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 17:18:24.623  2206  2206 E audit   : type=1327 msg=audit(1471015104.623:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 17:18:24.623  2206  2206 E audit   : type=1320 msg=audit(1471015104.623:291): 
,08-12 17:18:24.623  7025  7025 D AndroidRuntime: CheckJNI is OFF
,08-12 17:18:24.623  7025  7025 D AndroidRuntime: readGMSProperty: start
,08-12 17:18:24.623  7025  7025 D AndroidRuntime: readGMSProperty: already setted!!
08-12 17:18:24.623  7025  7025 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 17:18:24.623  7025  7025 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 17:18:24.623  7025  7025 D AndroidRuntime: readGMSProperty: end
08-12 17:18:24.633  7025  7025 D AndroidRuntime: addProductProperty: start
,08-12 17:18:24.633  7025  7025 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-12 17:18:24.633  7025  7025 W art     : aedbc000-b1ce2000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 17:18:24.633  7025  7025 W art     : b1ce2000-b3f51000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 17:18:24.633  7025  7025 W art     : b3f51000-b3f52000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 17:18:24.633  7025  7025 W art     : b3f52000-b3f53000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.633  7025  7025 W art     : b427b000-b42a4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 17:18:24.633  7025  7025 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
,08-12 17:18:24.633  7025  7025 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-12 17:18:24.633  7025  7025 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 17:18:24.633  7025  7025 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 17:18:24.633  7025  7025 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
08-12 17:18:24.633  7025  7025 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 17:18:24.633  7025  7025 W art     : b4826000-b4829000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 17:18:24.633  7025  7025 W art     : b4829000-b482a000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 17:18:24.633  7025  7025 W art     : b482a000-b482b000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
,08-12 17:18:24.633  7025  7025 W art     : b482b000-b482c000 r--p 00000000 00:00 0 
08-12 17:18:24.633  7025  7025 W art     : b482c000-b484c000 r--s 00000000 00:0b 6572       /dev/__properties__
08-12 17:18:24.633  7025  7025 W art     : b484c000-b525d000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 17:18:24.633  7025  7025 W art     : b525d000-b525e000 ---p 00000000 00:00 0 
08-12 17:18:24.633  7025  7025 W art     : b525e000-b52a7000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 17:18:24.633  7025  7025 W art     : b52a7000-b52a8000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 17:18:24.633  7025  7025 W art     : b52a8000-b52b0000 rw-p 00000000 00:00 0 
,08-12 17:18:24.633  7025  7025 W art     : b52b0000-b52b1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.633  7025  7025 W art     : b52b1000-b52e6000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 17:18:24.643  7025  7025 W art     : b52e6000-b52e7000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b52e7000-b52e8000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 17:18:24.643  7025  7025 W art     : b52e8000-b52e9000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 17:18:24.643  7025  7025 W art     : b52e9000-b5341000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
,08-12 17:18:24.643  7025  7025 W art     : b5341000-b5342000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b5342000-b5343000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 17:18:24.643  7025  7025 W art     : b5343000-b5344000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 17:18:24.643  7025  7025 W art     : b5345000-b534b000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 17:18:24.643  7025  7025 W art     : b534b000-b534c000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 17:18:24.643  7025  7025 W art     : b534c000-b534d000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 17:18:24.643  7025  7025 W art     : b534d000-b534f000 rw-p 00000000 00:00 0 
,08-12 17:18:24.643  7025  7025 W art     : b5350000-b535a000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 17:18:24.643  7025  7025 W art     : b535a000-b535d000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 17:18:24.643  7025  7025 W art     : b535d000-b535e000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 17:18:24.643  7025  7025 W art     : b535f000-b5376000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 17:18:24.643  7025  7025 W art     : b5376000-b5377000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b5377000-b5378000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 17:18:24.643  7025  7025 W art     : b5378000-b5379000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-12 17:18:24.643  7025  7025 W art     : b537a000-b5384000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 17:18:24.643  7025  7025 W art     : b5384000-b5385000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 17:18:24.643  7025  7025 W art     : b5385000-b5386000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 17:18:24.643  7025  7025 W art     : b5386000-b538a000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 17:18:24.643  7025  7025 W art     : b538a000-b538b000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 17:18:24.643  7025  7025 W art     : b538b000-b538c000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 17:18:24.643  7025  7025 W art     : b538c000-b53a2000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
,08-12 17:18:24.643  7025  7025 W art     : b53a2000-b53a3000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 17:18:24.643  7025  7025 W art     : b53a3000-b53a4000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 17:18:24.643  7025  7025 W art     : b53a4000-b53b1000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 17:18:24.643  7025  7025 W art     : b53b1000-b53b2000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 17:18:24.643  7025  7025 W art     : b53b2000-b53b3000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 17:18:24.643  7025  7025 W art     : b53b3000-b5413000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
,08-12 17:18:24.643  7025  7025 W art     : b5413000-b5416000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 17:18:24.643  7025  7025 W art     : b5416000-b541a000 rw-p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b541a000-b547b000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 17:18:24.643  7025  7025 W art     : b547b000-b547c000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 17:18:24.643  7025  7025 W art     : b547c000-b54cb000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 17:18:24.643  7025  7025 W art     : b54cb000-b54cd000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
,08-12 17:18:24.643  7025  7025 W art     : b54cd000-b54ce000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 17:18:24.643  7025  7025 W art     : b54ce000-b54cf000 rw-p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b54cf000-b54d6000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 17:18:24.643  7025  7025 W art     : b54d6000-b54d7000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 17:18:24.643  7025  7025 W art     : b54d7000-b54d8000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-12 17:18:24.643  7025  7025 W art     : avc_common.so
08-12 17:18:24.643  7025  7025 W art     : b54d9000-b54dc000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-12 17:18:24.643  7025  7025 W art     : b54dc000-b54dd000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 17:18:24.643  7025  7025 W art     : b54dd000-b54de000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-12 17:18:24.643  7025  7025 W art     : enc_common.so
,08-12 17:18:24.643  7025  7025 W art     : b54df000-b54e3000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 17:18:24.643  7025  7025 W art     : b54e3000-b54e4000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b54e4000-b54e5000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 17:18:24.643  7025  7025 W art     : b54e5000-b54e6000 rw-p 00005000 b3:17 2510       /syste
08-12 17:18:24.643  7025  7025 W art     : m/lib/libpowermanager.so
08-12 17:18:24.643  7025  7025 W art     : b54e7000-b5504000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 17:18:24.643  7025  7025 W art     : b5504000-b5505000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 17:18:24.643  7025  7025 W art     : b5505000-b5506000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 17:18:24.643  7025  7025 W art     : b5507000-b550c000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 17:18:24.643  7025  7025 W art     : b550c000-b550d000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 17:18:24.643  7025  7025 W art     : b550d000-b550e000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 17:18:24.643  7025  7025 W art     : b550f000-b5540000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 17:18:24.643  7025  7025 W art     : b5540000-b5543000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-12 17:18:24.643  7025  7025 W art     : b5543000-b5544000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 17:18:24.643  7025  7025 W art     : b5545000-b5580000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 17:18:24.643  7025  7025 W art     : b5580000-b5581000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 17:18:24.643  7025  7025 W art     : b5581000-b5582000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 17:18:24.643  7025  7025 W art     : b5583000-b558a000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 17:18:24.643  7025  7025 W art     : b558a000-b558b000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b558b000-b558c000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 17:18:24.643  7025  7025 W art     : b558c000-b558d000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 17:18:24.643  7025  7025 W art     : b558d000-b558e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.643  7025  7025 W art     : b558e000-b55a5000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 17:18:24.643  7025  7025 W art     : b55a5000-b55a6000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b55a6000-b55a9000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 17:18:24.643  7025  7025 W art     : b55a9000-b55aa000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 17:18:24.643  7025  7025 W art     : b55aa000-b55c9000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 17:18:24.643  7025  7025 W art     : b55c9000-b55ca000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 17:18:24.643  7025  7025 W art     : b55ca000-b55cb000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
,08-12 17:18:24.643  7025  7025 W art     : b55cb000-b5609000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 17:18:24.643  7025  7025 W art     : b5609000-b560a000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b560a000-b560c000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 17:18:24.643  7025  7025 W art     : b560c000-b560d000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 17:18:24.643  7025  7025 W art     : b560e000-b5615000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 17:18:24.643  7025  7025 W art     : b5615000-b5616000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 17:18:24.643  7025  7025 W art     : b5616000-b5617000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 17:18:24.643  7025  7025 W art     : b5618000-b561b000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 17:18:24.643  7025  7025 W art     : b561b000-b561c000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 17:18:24.643  7025  7025 W art     : b561c000-b561d000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 17:18:24.643  7025  7025 W art     : b561d000-b5623000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 17:18:24.643  7025  7025 W art     : b5623000-b5624000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b5624000-b5625000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-12 17:18:24.643  7025  7025 W art     : b5625000-b5626000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 17:18:24.643  7025  7025 W art     : b5626000-b562f000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 17:18:24.643  7025  7025 W art     : b562f000-b5630000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 17:18:24.643  7025  7025 W art     : b5630000-b5631000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 17:18:24.643  7025  7025 W art     : b5631000-b56c2000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 17:18:24.643  7025  7025 W art     : b56c2000-b56c3000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b56c3000-b56ce000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 17:18:24.643  7025  7025 W art     : b56ce000-b56cf000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 17:18:24.643  7025  7025 W art     : b56d0000-b56e2000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 17:18:24.643  7025  7025 W art     : b56e2000-b56e3000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 17:18:24.643  7025  7025 W art     : b56e3000-b56e4000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
,08-12 17:18:24.643  7025  7025 W art     : b56e5000-b56ea000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 17:18:24.643  7025  7025 W art     : b56ea000-b56eb000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 17:18:24.643  7025  7025 W art     : b56eb000-b56ec000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 17:18:24.643  7025  7025 W art     : b56ed000-b575a000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 17:18:24.643  7025  7025 W art     : b575a000-b575b000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b575b000-b575d000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 17:18:24.643  7025  7025 W art     : b575d000-b575e000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 17:18:24.643  7025  7025 W art     : b575e000-b575f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.643  7025  7025 W art     : b575f000-b5766000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 17:18:24.643  7025  7025 W art     : b5766000-b5767000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 17:18:24.643  7025  7025 W art     : b5767000-b5768000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-12 17:18:24.643  7025  7025 W art     : b5769000-b57e9000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 17:18:24.643  7025  7025 W art     : b57e9000-b57ea000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b57ea000-b57eb000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 17:18:24.643  7025  7025 W art     : b57eb000-b57ec000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 17:18:24.643  7025  7025 W art     : b57ec000-b5803000 rw-p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b5803000-b583a000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 17:18:24.643  7025  7025 W art     : ib/libqc-opt.so
08-12 17:18:24.643  7025  7025 W art     : b583a000-b583b000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 17:18:24.643  7025  7025 W art     : b583b000-b583c000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 17:18:24.643  7025  7025 W art     : b583c000-b5858000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 17:18:24.643  7025  7025 W art     : b5858000-b5859000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
,08-12 17:18:24.643  7025  7025 W art     : b5859000-b585a000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 17:18:24.643  7025  7025 W art     : b585b000-b58bc000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 17:18:24.643  7025  7025 W art     : b58bc000-b58be000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 17:18:24.643  7025  7025 W art     : b58be000-b58bf000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 17:18:24.643  7025  7025 W art     : b58c0000-b58e7000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 17:18:24.643  7025  7025 W art     : b58e7000-b58e8000 ---p 00000000 00:00 0 
08-12 17:18:24.643  7025  7025 W art     : b58e8000-b58e9000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 17:18:24.643  7025  7025 W art     : b58e9000-b58ea000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 17:18:24.643  7025  7025 W art     : b58eb000-b58f3000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 17:18:24.643  7025  7025 W art     : b58f3000-b58f5000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-12 17:18:24.653  7025  7025 W art     : b58f5000-b58f6000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 17:18:24.653  7025  7025 W art     : b58f7000-b58fa000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 17:18:24.653  7025  7025 W art     : b58fa000-b58fb000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 17:18:24.653  7025  7025 W art     : b58fb000-b58fc000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 17:18:24.653  7025  7025 W art     : b58fc000-b5900000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 17:18:24.653  7025  7025 W art     : b5900000-b5901000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5901000-b5902000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 17:18:24.653  7025  7025 W art     : b5902000-b5903000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 17:18:24.653  7025  7025 W art     : b5903000-b5913000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 17:18:24.653  7025  7025 W art     : b5913000-b5914000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 17:18:24.653  7025  7025 W art     : b5914000-b5915000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 17:18:24.653  7025  7025 W art     : b5915000-b595b000 rw-p 00000000 00:00 0 
,08-12 17:18:24.653  7025  7025 W art     : b595b000-b5964000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 17:18:24.653  7025  7025 W art     : b5964000-b5965000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 17:18:24.653  7025  7025 W art     : b5965000-b5966000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 17:18:24.653  7025  7025 W art     : b5967000-b596c000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 17:18:24.653  7025  7025 W art     : b596c000-b596d000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 17:18:24.653  7025  7025 W art     : b596d000-b596e000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 17:18:24.653  7025  7025 W art     : b596e000-b5971000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 17:18:24.653  7025  7025 W art     : b5971000-b5972000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5972000-b5973000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 17:18:24.653  7025  7025 W art     : b5973000-b5974000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 17:18:24.653  7025  7025 W art     : b5975000-b598d000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
,08-12 17:18:24.653  7025  7025 W art     : b598d000-b598e000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b598e000-b598f000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 17:18:24.653  7025  7025 W art     : b598f000-b5990000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 17:18:24.653  7025  7025 W art     : b5991000-b5b2b000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 17:18:24.653  7025  7025 W art     : b5b2b000-b5b2c000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5b2c000-b5b39000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 17:18:24.653  7025  7025 W art     : b5b39000-b5b3a000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 17:18:24.653  7025  7025 W art     : b5b3a000-b5b3e000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 17:18:24.653  7025  7025 W art     : b5b3e000-b5b3f000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5b3f000-b5b40000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 17:18:24.653  7025  7025 W art     : b5b40000-b5b41000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
,08-12 17:18:24.653  7025  7025 W art     : b5b41000-b5b54000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 17:18:24.653  7025  7025 W art     : b5b54000-b5b55000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 17:18:24.653  7025  7025 W art     : b5b55000-b5b56000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 17:18:24.653  7025  7025 W art     : b5b56000-b5b57000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:18:24.653  7025  7025 W art     : b5b57000-b5ba2000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 17:18:24.653  7025  7025 W art     : b5ba2000-b5ba3000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 17:18:24.653  7025  7025 W art     : b5ba3000-b5ba4000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 17:18:24.653  7025  7025 W art     : b5ba4000-b5ba6000 rw-p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5ba7000-b5bb8000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 17:18:24.653  7025  7025 W art     : b5bb8000-b5bb9000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5bb9000-b5bba000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
,08-12 17:18:24.653  7025  7025 W art     : b5bba000-b5bbb000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 17:18:24.653  7025  7025 W art     : b5bbc000-b5bc6000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 17:18:24.653  7025  7025 W art     : b5bc6000-b5bc8000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 17:18:24.653  7025  7025 W art     : b5bc8000-b5bc9000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 17:18:24.653  7025  7025 W art     : b5bc9000-b5be2000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 17:18:24.653  7025  7025 W art     : b5be2000-b5be3000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 17:18:24.653  7025  7025 W art     : b5be3000-b5be6000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 17:18:24.653  7025  7025 W art     : b5be6000-b5bea000 rw-p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5bea000-b5c5e000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 17:18:24.653  7025  7025 W art     : b5c5e000-b5c5f000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5c5f000-b5c62000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
,08-12 17:18:24.653  7025  7025 W art     : b5c62000-b5c63000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 17:18:24.653  7025  7025 W art     : b5c63000-b5c64000 r--p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5c64000-b5c67000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 17:18:24.653  7025  7025 W art     : b5c67000-b5c68000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 17:18:24.653  7025  7025 W art     : b5c68000-b5c69000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 17:18:24.653  7025  7025 W art     : b5c69000-b5c6a000 r--p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5c6a000-b5c6f000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 17:18:24.653  7025  7025 W art     : b5c6f000-b5c70000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 17:18:24.653  7025  7025 W art     : b5c70000-b5c71000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 17:18:24.653  7025  7025 W art     : b5c71000-b5c72000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.653  7025  7025 W art     : b5c72000-b5c75000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
,08-12 17:18:24.653  7025  7025 W art     : b5c75000-b5c76000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 17:18:24.653  7025  7025 W art     : b5c76000-b5c77000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 17:18:24.653  7025  7025 W art     : b5c77000-b5c78000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.653  7025  7025 W art     : b5c78000-b5c7c000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 17:18:24.653  7025  7025 W art     : b5c7c000-b5c7d000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 17:18:24.653  7025  7025 W art     : b5c7d000-b5c7e000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 17:18:24.653  7025  7025 W art     : b5c7e000-b5c7f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:18:24.653  7025  7025 W art     : b5c7f000-b5c83000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 17:18:24.653  7025  7025 W art     : b5c83000-b5c84000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 17:18:24.653  7025  7025 W art     : b5c84000-b5c85000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 17:18:24.653  7025  7025 W art     : b5c85000-b5c86000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 17:18:24.653  7025  7025 W art     : b5c86000-b5c94000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 17:18:24.653  7025  7025 W art     : b5c94000-b5c95000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b5c95000-b5c96000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 17:18:24.653  7025  7025 W art     : b5c96000-b5c97000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 17:18:24.653  7025  7025 W art     : b5c97000-b5ca1000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 17:18:24.653  7025  7025 W art     : b5ca1000-b5ca4000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 17:18:24.653  7025  7025 W art     : b5ca4000-b5ca5000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 17:18:24.653  7025  7025 W art     : b5ca5000-b5ca6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.653  7025  7025 W art     : b5ca6000-b5cb0000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 17:18:24.653  7025  7025 W art     : b5cb0000-b5cb3000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 17:18:24.653  7025  7025 W art     : b5cb3000-b5cb4000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
,08-12 17:18:24.653  7025  7025 W art     : b5cb4000-b5cb8000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 17:18:24.653  7025  7025 W art     : b5cb8000-b5cb9000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 17:18:24.653  7025  7025 W art     : b5cb9000-b5cba000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 17:18:24.653  7025  7025 W art     : b5cba000-b5cbb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.653  7025  7025 W art     : b5cbb000-b5cc8000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 17:18:24.653  7025  7025 W art     : b5cc8000-b5cca000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 17:18:24.653  7025  7025 W art     : b5cca000-b5ccb000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 17:18:24.653  7025  7025 W art     : b5ccb000-b60dd000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 17:18:24.653  7025  7025 W art     : b60dd000-b60de000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b60de000-b60e7000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 17:18:24.653  7025  7025 W art     : b60e7000-b60eb000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 17:18:24.653  7025  7025 W art     : b60eb000-b60ec000 rw-p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b60ec000-b60f3000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
,08-12 17:18:24.653  7025  7025 W art     : b60f3000-b60f4000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 17:18:24.653  7025  7025 W art     : b60f4000-b60f5000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 17:18:24.653  7025  7025 W art     : b60f5000-b60f6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.653  7025  7025 W art     : b60f6000-b6111000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-12 17:18:24.653  7025  7025 W art     : b6111000-b6112000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 17:18:24.653  7025  7025 W art     : b6112000-b6113000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 17:18:24.653  7025  7025 W art     : b6113000-b6114000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.653  7025  7025 W art     : b6114000-b6160000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 17:18:24.653  7025  7025 W art     : b6160000-b6161000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b6161000-b6162000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 17:18:24.653  7025  7025 W art     : b6162000-b6163000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 17:18:24.653  7025  7025 W art     : b6163000-b6164000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.653  7025  7025 W art     : b6164000-b6168000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 17:18:24.653  7025  7025 W art     : b6168000-b6169000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b6169000-b616a000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
,08-12 17:18:24.653  7025  7025 W art     : b616a000-b616b000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-12 17:18:24.653  7025  7025 W art     : b616b000-b61a3000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 17:18:24.653  7025  7025 W art     : b61a3000-b61a4000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 17:18:24.653  7025  7025 W art     : b61a4000-b61a5000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 17:18:24.653  7025  7025 W art     : b61a5000-b61a6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.653  7025  7025 W art     : b61a6000-b6244000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 17:18:24.653  7025  7025 W art     : b6244000-b6245000 ---p 00000000 00:00 0 
08-12 17:18:24.653  7025  7025 W art     : b6245000-b6263000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 17:18:24.663  7025  7025 W art     : b6263000-b6264000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-12 17:18:24.663  7025  7025 W art     : b6264000-b63d7000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 17:18:24.663  7025  7025 W art     : b63d7000-b63e2000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 17:18:24.663  7025  7025 W art     : b63e2000-b63e3000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 17:18:24.663  7025  7025 W art     : b63e3000-b64fa000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
,08-12 17:18:24.663  7025  7025 W art     : b64fa000-b6505000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 17:18:24.663  7025  7025 W art     : b6505000-b6506000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 17:18:24.663  7025  7025 W art     : b6506000-b650a000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b650a000-b652e000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-12 17:18:24.663  7025  7025 W art     : b652e000-b6530000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 17:18:24.663  7025  7025 W art     : b6530000-b6531000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 17:18:24.663  7025  7025 W art     : b6531000-b65d7000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 17:18:24.663  7025  7025 W art     : b65d7000-b65e4000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-12 17:18:24.663  7025  7025 W art     : b65e4000-b65e5000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 17:18:24.663  7025  7025 W art     : b65e5000-b65e6000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b65e6000-b6639000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 17:18:24.663  7025  7025 W art     : b6639000-b663a000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b663a000-b663b000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 17:18:24.663  7025  7025 W art     : b663b000-b663c000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 17:18:24.663  7025  7025 W art     : b663c000-b6641000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6641000-b6653000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 17:18:24.663  7025  7025 W art     : b6653000-b6654000 ---p 00000000 00:00 0 
,08-12 17:18:24.663  7025  7025 W art     : b6654000-b6655000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 17:18:24.663  7025  7025 W art     : b6655000-b6656000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 17:18:24.663  7025  7025 W art     : b6656000-b665d000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 17:18:24.663  7025  7025 W art     : b665d000-b665e000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 17:18:24.663  7025  7025 W art     : b665e000-b665f000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 17:18:24.663  7025  7025 W art     : b665f000-b6660000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6660000-b6663000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 17:18:24.663  7025  7025 W art     : b6663000-b6664000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 17:18:24.663  7025  7025 W art     : b6664000-b6665000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 17:18:24.663  7025  7025 W art     : b6665000-b6669000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 17:18:24.663  7025  7025 W art     : b6669000-b666a000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 17:18:24.663  7025  7025 W art     : b666a000-b666b000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
,08-12 17:18:24.663  7025  7025 W art     : b666b000-b6679000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 17:18:24.663  7025  7025 W art     : b6679000-b667a000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b667a000-b667b000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 17:18:24.663  7025  7025 W art     : b667b000-b667c000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 17:18:24.663  7025  7025 W art     : b667c000-b6685000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 17:18:24.663  7025  7025 W art     : b6685000-b6686000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 17:18:24.663  7025  7025 W art     : b6686000-b6687000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 17:18:24.663  7025  7025 W art     : b6687000-b66ed000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 17:18:24.663  7025  7025 W art     : b66ed000-b66ee000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b66ee000-b66f0000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 17:18:24.663  7025  7025 W art     : b66f0000-b66f9000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 17:18:24.663  7025  7025 W art     : b66f9000-b66fc000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b66fc000-b6793000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 17:18:24.663  7025  7025 W art     : b6793000-b6795000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
,08-12 17:18:24.663  7025  7025 W art     : b6795000-b6796000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 17:18:24.663  7025  7025 W art     : b6796000-b6797000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6797000-b6ab8000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 17:18:24.663  7025  7025 W art     : b6ab8000-b6ab9000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6ab9000-b6ad4000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 17:18:24.663  7025  7025 W art     : b6ad4000-b6ad8000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 17:18:24.663  7025  7025 W art     : b6ad8000-b6add000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6add000-b6ae5000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 17:18:24.663  7025  7025 W art     : b6ae5000-b6ae6000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 17:18:24.663  7025  7025 W art     : b6ae6000-b6ae7000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 17:18:24.663  7025  7025 W art     : b6ae7000-b6b15000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 17:18:24.663  7025  7025 W art     : b6b15000-b6b16000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6b16000-b6b1d000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 17:18:24.663  7025  7025 W art     : b6b1d000-b6b1e000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so,
08-12 17:18:24.663  7025  7025 W art     : b6b1e000-b6b64000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 17:18:24.663  7025  7025 W art     : b6b64000-b6b65000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6b65000-b6b68000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 17:18:24.663  7025  7025 W art     : b6b68000-b6b69000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 17:18:24.663  7025  7025 W art     : b6b69000-b6b84000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 17:18:24.663  7025  7025 W art     : b6b84000-b6b88000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 17:18:24.663  7025  7025 W art     : b6b88000-b6b89000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 17:18:24.663  7025  7025 W art     : b6b89000-b6bd6000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 17:18:24.663  7025  7025 W art     : b6bd6000-b6bd7000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6bd7000-b6be3000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
,08-12 17:18:24.663  7025  7025 W art     : b6be3000-b6be4000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 17:18:24.663  7025  7025 W art     : b6be4000-b6bf1000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 17:18:24.663  7025  7025 W art     : b6bf1000-b6bf2000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6bf2000-b6bf3000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 17:18:24.663  7025  7025 W art     : b6bf3000-b6bf4000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 17:18:24.663  7025  7025 W art     : b6bf4000-b6bfc000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 17:18:24.663  7025  7025 W art     : b6bfc000-b6bfd000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6bfd000-b6bfe000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 17:18:24.663  7025  7025 W art     : b6bfe000-b6bff000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 17:18:24.663  7025  7025 W art     : b6bff000-b6c06000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 17:18:24.663  7025  7025 W art     : b6c06000-b6c07000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 17:18:24.663  7025  7025 W art     : b6c07000-b6c08000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
,08-12 17:18:24.663  7025  7025 W art     : b6c08000-b6c1c000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 17:18:24.663  7025  7025 W art     : b6c1c000-b6c1e000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 17:18:24.663  7025  7025 W art     : b6c1e000-b6c1f000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 17:18:24.663  7025  7025 W art     : b6c1f000-b6c47000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 17:18:24.663  7025  7025 W art     : b6c47000-b6c49000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 17:18:24.663  7025  7025 W art     : b6c49000-b6c4a000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 17:18:24.663  7025  7025 W art     : b6c4a000-b6c4d000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 17:18:24.663  7025  7025 W art     : b6c4d000-b6c4e000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 17:18:24.663  7025  7025 W art     : b6c4e000-b6c4f000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
,08-12 17:18:24.663  7025  7025 W art     : b6c4f000-b6c58000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 17:18:24.663  7025  7025 W art     : b6c58000-b6c59000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 17:18:24.663  7025  7025 W art     : b6c59000-b6c5a000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 17:18:24.663  7025  7025 W art     : b6c5a000-b6c7a000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 17:18:24.663  7025  7025 W art     : b6c7a000-b6c7b000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 17:18:24.663  7025  7025 W art     : b6c7b000-b6c7c000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 17:18:24.663  7025  7025 W art     : b6c7c000-b6cef000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 17:18:24.663  7025  7025 W art     : b6cef000-b6cf3000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 17:18:24.663  7025  7025 W art     : b6cf3000-b6cf6000 rw-p 00076000 b3:17 860        /system/lib/libc.so
,08-12 17:18:24.663  7025  7025 W art     : b6cf6000-b6d00000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6d00000-b6d88000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 17:18:24.663  7025  7025 W art     : b6d88000-b6d89000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6d89000-b6d8d000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 17:18:24.663  7025  7025 W art     : b6d8d000-b6d8e000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 17:18:24.663  7025  7025 W art     : b6d8e000-b6d8f000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6d8f000-b6db8000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 17:18:24.663  7025  7025 W art     : b6db8000-b6db9000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6db9000-b6dbc000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
,08-12 17:18:24.663  7025  7025 W art     : b6dbc000-b6dbd000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 17:18:24.663  7025  7025 W art     : b6dbd000-b6e97000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 17:18:24.663  7025  7025 W art     : b6e97000-b6e9e000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 17:18:24.663  7025  7025 W art     : b6e9e000-b6ea6000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 17:18:24.663  7025  7025 W art     : b6ea6000-b6ea7000 rw-p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6ea7000-b6ea8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:18:24.663  7025  7025 W art     : b6ea8000-b6ea9000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 17:18:24.663  7025  7025 W art     : b6ea9000-b6eaa000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.663  7025  7025 W art     : b6eaa000-b6ead000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 17:18:24.663  7025  7025 W art     : b6ead000-b6ed2000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 17:18:24.663  7025  7025 W art     : b6ed2000-b6ed3000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6ed3000-b6eda000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 17:18:24.663  7025  7025 W art     : b6eda000-b6edb000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 17:18:24.663  7025  7025 W art     : b6edb000-b6ee2000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 17:18:24.663  7025  7025 W art     : b6ee2000-b6ee3000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 17:18:24.663  7025  7025 W art     : b6ee3000-b6ee4000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 17:18:24.663  7025  7025 W art     : b6ee4000-b6ee5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.663  7025  7025 W art     : b6ee5000-b6efd000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 17:18:24.663  7025  7025 W art     : b6efd000-b6efe000 ---p 00000000 00:00 0 
,08-12 17:18:24.663  7025  7025 W art     : b6efe000-b6eff000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 17:18:24.663  7025  7025 W art     : b6eff000-b6f00000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 17:18:24.663  7025  7025 W art     : b6f00000-b6f0e000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 17:18:24.663  7025  7025 W art     : b6f0e000-b6f0f000 ---p 00000000 00:00 0 
08-12 17:18:24.663  7025  7025 W art     : b6f0f000-b6f10000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 17:18:24.663  7025  7025 W art     : b6f10000-b6f11000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 17:18:24.663  7025  7025 W art     : b6f11000-b6f12000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:18:24.663  7025  7025 W art     : b6f12000-b6f14000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 17:18:24.663  7025  7025 W art     : b6f14000-b6f15000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.663  7025  7025 W art     : b6f15000-b6f16000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 17:18:24.663  7025  7025 W art     : b6f16000-b6f17000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 17:18:24.663  7025  7025 W art     : b6f17000-b6f18000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 17:18:24.673  7025  7025 W art     : b6f18000-b6f38000 r--s 00000000 00:0b 6572       /dev/__properties__
,08-12 17:18:24.673  7025  7025 W art     : b6f38000-b6f39000 r--p 00000000 00:00 0 
08-12 17:18:24.673  7025  7025 W art     : b6f39000-b6f3a000 ---p 00000000 00:00 0 
08-12 17:18:24.673  7025  7025 W art     : b6f3a000-b6f3c000 rw-p 00000000 00:00 0          [anon:thread signal stack]
,08-12 17:18:24.673  7025  7025 W art     : b6f3c000-b6f3d000 r-xp 00000000 00:00 0          [sigpage]
08-12 17:18:24.673  7025  7025 W art     : b6f3d000-b6f58000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 17:18:24.673  7025  7025 W art     : b6f58000-b6f59000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 17:18:24.673  7025  7025 W art     : b6f59000-b6f5b000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 17:18:24.673  7025  7025 W art     : b6f5b000-b6f5d000 rw-p 00000000 00:00 0 
08-12 17:18:24.673  7025  7025 W art     : b6f5d000-b6f62000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 17:18:24.673  7025  7025 W art     : b6f62000-b6f63000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 17:18:24.673  7025  7025 W art     : b6f63000-b6f64000 rw-p 00000000 00:00 0 
08-12 17:18:24.673  7025  7025 W art     : bee7c000-bee9d000 rw-p 00000000 00:00 0          [stack]
,08-12 17:18:24.673  7025  7025 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-12 17:18:24.723  7025  7025 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 17:18:24.783  7025  7025 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 17:18:24.793  7025  7025 E AffinityControl: AffinityControl: registerfunction enter
,08-12 17:18:24.813  7025  7025 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 17:18:24.823   773  1298 D PackageManager: START PACKAGE DELETE: observer{121117968}
08-12 17:18:24.823   773  1298 D PackageManager: pkg{<packageName>}
08-12 17:18:24.823   773  1298 D PackageManager: user{0}
08-12 17:18:24.823   773  1298 D PackageManager: caller{2000}
08-12 17:18:24.823   773  1298 D PackageManager: flags{2}
08-12 17:18:24.823   773  1298 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-12 17:18:24.823   773  1298 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-12 17:18:24.823   773  1298 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-12 17:18:24.823   773  1298 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-12 17:18:24.823   773  1298 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-12 17:18:24.823   773   942 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-12 17:18:24.823   773   942 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-12 17:18:24.823   773   942 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-12 17:18:24.823   773   942 D ApplicationPolicy: getApplicationUninstallationEnabled
08-12 17:18:24.823   773   942 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-12 17:18:24.833   773   942 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-12 17:18:24.833   773   942 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 17:18:24.833   773   942 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-12 17:18:24.833   773   861 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-12 17:18:24.833   773   942 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-12 17:18:24.833   773   942 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 17:18:24.833   773   861 I ActivityManager: Killing 6479:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-12 17:18:24.843   773   861 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 17:18:24.843   773   861 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 17:18:24.853   773   861 D ActivityManager: mDVFSHelper.acquire()
,08-12 17:18:24.873   773   942 D AASAinstall: there is not AASApackages.xml file
,08-12 17:18:24.883   773  1747 D GraphicsStats: Buffer count: 4
,08-12 17:18:24.893   773  1747 I WindowState: WIN DEATH: Window{fdc239c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 17:18:24.893   773  3915 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@5e9fa3c)
,08-12 17:18:24.893   295   357 I SurfaceFlinger: id=21 Removed NainActivit (6/8)
,08-12 17:18:24.893   773  1336 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 17:18:24.893   773  1336 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 17:18:24.893   773  1336 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 17:18:24.893   295  1303 I SurfaceFlinger: id=21 Removed NainActivit (-2/8)
,08-12 17:18:24.903   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd73a4
,08-12 17:18:24.903   773  1747 D InputDispatcher: Focus left window: 6479
,08-12 17:18:25.153   773   942 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-12 17:18:25.243   773   942 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 17:18:25.243   773   861 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-12 17:18:25.243   773   904 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 17:18:25.253   773   861 E ActivityManager: Failure starting process com.test.thalitest
08-12 17:18:25.253   773   861 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5273)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5190)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5028)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4999)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4960)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7375)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9142)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8765)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8920)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
08-12 17:18:25.253   773   861 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:18:25.253   773   861 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-12 17:18:25.253   773   861 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:18:25.253   773   861 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 17:18:25.253   773   861 I ActivityManager:   Force finishing activity ActivityRecord{3cf7af3 u0 com.test.thalitest/.MainActivity t168}
,08-12 17:18:25.253   324   324 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-12 17:18:25.263   773   942 I art     : Starting a blocking GC Explicit
,08-12 17:18:25.263   773   904 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
,08-12 17:18:25.263   773   904 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-12 17:18:25.263   773   904 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-12 17:18:25.263   773   904 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4342)
08-12 17:18:25.263   773   904 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
08-12 17:18:25.263   773   904 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-12 17:18:25.263   773   904 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 17:18:25.263   773   904 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:18:25.263   773   904 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 17:18:25.263   773   904 D SecWifiDisplayUtil: Metadata value : none
,08-12 17:18:25.263   773   904 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{64de4e6 V.E...... R.....ID 0,0-0,0}
,08-12 17:18:25.273   773   904 D ISSUE_DEBUG: InputChannelName : b0d54d4 Starting com.test.thalitest
,08-12 17:18:25.283   295   295 I SurfaceFlinger: id=22 createSurf (1146x1876),1 flag=4, VSBConnecti
,08-12 17:18:25.313  1733  1733 D Launcher: onRestart, Launcher: 140780961
,08-12 17:18:25.403   773   942 I art     : Explicit concurrent mark sweep GC freed 125415(7MB) AllocSpace objects, 119(2MB) LOS objects, 27% free, 41MB/57MB, paused 1.472ms total 145.517ms
,08-12 17:18:25.433   773   942 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 17:18:25.433   773   942 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-12 17:18:25.433   773   942 D AASAinstall: there is not AASApackages.xml file
,08-12 17:18:25.433   773   942 D PackageManager: result of delete: 1{121117968}
,08-12 17:18:25.433  7025  7025 I art     : System.exit called, status: 0
08-12 17:18:25.433  7025  7025 I AndroidRuntime: VM exiting with result code 0.
,08-12 17:18:25.443   773   942 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-12 17:18:25.443   773   942 D PackageManager: userId{-1}
08-12 17:18:25.443   773   942 D PackageManager: andCode{true}
,08-12 17:18:25.593   773   861 I WindowManager: Screenshot max retries 4 of Token{c24402d ActivityRecord{4334744 u0 com.samsung.android.MtpApplication/.USBConnection t167}} appWin=Window{b026f5b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=1
,08-12 17:18:25.603   773   904 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:773 uid:1000
,08-12 17:18:25.603   773   904 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 17:18:25.603   773   904 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:773 uid:1000
08-12 17:18:25.603   773   904 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 17:18:25.603  1733  1733 D Launcher: onStart, Launcher: 140780961
,08-12 17:18:25.603   295   295 I SurfaceFlinger: id=23 createSurf (1080x1920),1 flag=404, uhalitest
,08-12 17:18:25.613  1733  1733 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,08-12 17:18:25.613   773   904 D ViewRootImpl: #3 mView = null
08-12 17:18:25.613  1733  1733 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-12 17:18:25.613  1733  1733 D Launcher.HomeView: onStart
,08-12 17:18:25.613   295  1303 I SurfaceFlinger: id=23 Removed uhalitest (7/9)
,08-12 17:18:25.613   295   365 I SurfaceFlinger: id=23 Removed uhalitest (-2/9)
,08-12 17:18:25.613  1733  1733 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
,08-12 17:18:25.623  1733  1733 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,08-12 17:18:25.623  1733  1733 V ActivityThread: updateVisibility : ActivityRecord{f825ebc token=android.os.BinderProxy@ee833ab {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-12 17:18:25.623  2377  2398 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
,08-12 17:18:25.623  1733  1733 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2ddd930 in tid 1733 (id.app.launcher)
,08-12 17:18:25.623  2206  2206 E audit_log: File locking failed. error= Bad file descriptor
08-12 17:18:25.623  2206  2206 E audit_log: File locking failed. error= Bad file descriptor
,08-12 17:18:25.643   773  1301 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-12 17:18:25.643  6182  7048 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2df3070 in tid 7048 (IntentService[D)
,08-12 17:18:25.643  6182  7048 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 17:18:25.653  2206  2206 E audit_log: File locking failed. error= Bad file descriptor
,08-12 17:18:25.653   773   861 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
08-12 17:18:25.653   773  1747 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-12 17:18:25.653   773  1747 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 17:18:25.653   773   773 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 17:18:25.653   773   861 D InputDispatcher: Focus entered window: 3507
08-12 17:18:25.653   773   773 I KnoxTimeoutHandler: Shared devices show user statefalse
08-12 17:18:25.653   773   773 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-12 17:18:25.653   773   861 D InputDispatcher: Focused application released
,08-12 17:18:25.653   773   904 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:773 uid:1000
08-12 17:18:25.653   773   904 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 17:18:25.653   773   904 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:773 uid:1000
,08-12 17:18:25.663   773   904 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 17:18:25.663   293   293 E lowmemorykiller: Error writing /proc/6182/oom_score_adj; errno=22
,08-12 17:18:25.663   773   863 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{b026f5b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-12 17:18:25.663  1385  1385 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-12 17:18:25.673   773  1301 I EventHub: Removing device '/dev/input/event5' due to inotify event
,08-12 17:18:25.673   773  1731 V WindowStateAnimator: Finishing drawing window Window{b026f5b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 17:18:25.683   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbecd7364
,08-12 17:18:25.683   295   295 I SurfaceFlinger: id=24 createSurf (1194x288),1 flag=4, VSBConnecti
,08-12 17:18:25.683   773  1550 V WindowOrientationListener: setCurrentAppOrientation :1
08-12 17:18:25.683   773  1550 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-12 17:18:25.693   773  3915 I ActivityManager: Process com.android.defcontainer (pid 6182)(adj 5) has died(221,715)
,08-12 17:18:25.693  3507  3507 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x746351c4 in tid 3507 (.MtpApplication)
,08-12 17:18:25.693  3507  3507 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 17:18:25.693  2206  2206 E audit_log: File locking failed. error= Bad file descriptor
,08-12 17:18:25.693   773  3915 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
08-12 17:18:25.693   773  3915 I ActivityManager: isWidgetUsingPkg : com.android.defcontainer no widget is using.
,08-12 17:18:25.703   773   904 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 17:18:25.703   773   904 D ActivityManager: mDVFSHelper.release()
08-12 17:18:25.703   773   773 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 17:18:25.713   773   773 I KnoxTimeoutHandler: SD activityfalse
08-12 17:18:25.713   773  1301 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-12 17:18:25.713   773   904 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4334744 u0 com.samsung.android.MtpApplication/.USBConnection t167} time:340611
,08-12 17:18:25.713   773   942 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-12 17:18:25.723   773   942 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ce3a940 in tid 942 (PackageManager)
,08-12 17:18:25.723   773   942 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 17:18:25.723   351   351 I Zygote  : Process 6182 exited due to signal (7)
08-12 17:18:25.723  2206  2206 E audit_log: File locking failed. error= Bad file descriptor
,08-12 17:18:25.743  2377  2377 E Surface : queueBuffer: error queuing buffer to SurfaceTexture, -32
,08-12 17:18:25.743  2377  2377 E Surface : queueBuffer (handle=0xad6d8ce0) failed (Broken pipe)
,08-12 17:18:25.743  2377  2377 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x73396607 in tid 2377 (ero.accuweather)
,08-12 17:18:25.753  2377  2377 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 17:18:25.753  2206  2206 E audit_log: File locking failed. error= Bad file descriptor
,08-12 17:18:25.783   351   351 I Zygote  : Process 1733 exited due to signal (7)
,08-12 17:18:25.803   351   351 I Zygote  : Process 2377 exited due to signal (7)
,08-12 17:18:25.803   351   351 I Zygote  : Process 3507 exited due to signal (7)
,08-12 17:18:25.813   322   322 E installd: eof
08-12 17:18:25.813   322   322 E installd: failed to read size
08-12 17:18:25.813   322   322 I installd: closing connection
,08-12 17:18:25.813   294   294 I ServiceManager: service 'telecom' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'connectivity' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'sb_service' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'servicediscovery' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'updatelock' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'notification' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'devicestoragemonitor' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'location' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'country_detector' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'sec_location' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'search' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'execute' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'dropbox' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'wallpaper' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'audio' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'DockObserver' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'midi' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'usb' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'serial' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'kiesusb' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'jobscheduler' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'backup' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'appwidget' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'voiceinteraction' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'SecExternalDisplayService' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'diskstats' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'mDNIe' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'AAS' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'MSCS' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'dreams' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'graphicsstats' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'print' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'restrictions' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'media_session' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'media_router' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'trust' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'fingerprint' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'launcherapps' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'voip' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'media_projection' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'lpnet' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'imms' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'sec_analytics' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'application_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'wifi_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'phone_restriction_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'remoteinjection' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'knox_ucsm_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'edm_proxy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'mum_container_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'enterprise_billing_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'otp_service' died
08-12 17:18:25,.813   294   294 I ServiceManager: service 'enterprise_shared_device_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'knox_timakeystore_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'enterprise_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'statusbar' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'clipboard' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'clipboardEx' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'network_management' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'spengestureservice' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'quickconnect' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'ABTPersistenceService' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'textservices' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'network_score' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'netstats' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'netpolicy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'wifip2p' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'wifi' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'wifihs20' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'wifiscanner' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'rttmanager' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'ethernet' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'knox_ccm_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'enterprise_license_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'rcp' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'input_method' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'accessibility' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'cover' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'mount' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'lock_settings' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'deviceidle' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'device_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'harmony_eas_service' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'sdp' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'sdp_log' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'dlp' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'log_manager_service' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'edmnativehelper' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'activity' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'user' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'procstats' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'meminfo' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'gfxinfo' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'dbinfo' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'cpuinfo' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'permission' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'processinfo' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'sensorservice' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'mdm.remotedesktop' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'battery' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'usagestats' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'webviewupdate' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'scheduling_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'telephony.registry' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'persona' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'SEAMService' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'media.camera.proxy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'account' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'content' died
08-12 17:18:25.813   319   972 W AudioFlinger: power manager service died !!!
08-12 17:18:25.813   294   294 I ServiceManager: service 'DirEncryptService' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'LSManager' died
08-12 17:18:25.813   319   972 W AudioFlinger: power manager service died !!!
08-12 17:18:25.813   294   294 I ServiceManager: service 'ReactiveService' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'DeviceRootKeyService' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'EngineeringModeService' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'SatsService' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'sedenial' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'vibrator' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'tw_toolbox' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'tima' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'iccc' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'cepproxyks' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'emailksproxy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'CustomFrequencyManagerService' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'consumer_ir' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'persona_policy' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'package' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'alarm' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'context_aware' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'scontext' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'barbeam' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'multiwindow_facade' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'window' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'input' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'samplingprofiler' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'bluetooth_manager' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'commontime_management' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'uimode' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'batterystats' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'appops' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'power' died
08-12 17:18:25.813   294   294 I ServiceManager: service 'display' died
08-12 17:18:25.813  2851  2862 W Sensors : sensorservice died [0xad83abc0]
08-12 17:18:25.813   295  4688 D libEGL  : eglTerminate EGLDisplay = 0xb46ba6fc
08-12 17:18:25.823   295   295 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a64000
08-12 17:18:25.823   295   295 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-12 17:18:25.823  1385  1400 W Sensors : sensorservice died [0xad39cd80]
08-12 17:18:25.823  2262  2285 W Sensors : sensorservice died [0xb3effcc0]
08-12 17:18:25.823  1838  2021 E WifiManager: Channel connection lost
08-12 17:18:25.823  1385  1632 E WifiManager: Channel connection lost
08-12 17:18:25.823  1981  2404 E WifiManager: Channel connection lost
08-12 17:18:25.823   295  1303 I SurfaceFlinger: restart the boot-animation @ binderDied
08-12 17:18:25.833  1714  1714 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-12 17:18:25.833   295   357 I SurfaceFlinger: id=2 Removed GocusedStac (7/9)
08-12 17:18:25.833   295   357 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
08-12 17:18:25.833   295   357 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-12 17:18:25.833   295   357 I SurfaceFlinger: id=15 Removed EimLayer(An (1/6)
08-12 17:18:25.833   295   357 I SurfaceFlinger: id=14 Removed EimLayer(Di (0/5)
08-12 17:18:25.833   295   357 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-12 17:18:25.833   295   357 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-12 17:18:25.833   295   357 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-12 17:18:25.833   295  4688 D libEGL  : eglTerminate EGLDisplay = 0xb46ba6fc
08-12 17:18:25.833  2201  2201 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ece6894 in tid 2201 (droid.bluetooth)
08-12 17:18:25.833  2201  2201 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 17:18:25.833  2206  2206 E audit_log: File locking failed. error= Bad file descriptor
08-12 17:18:25.833  2851  3171 E WifiManager: Channel connection lost
08-12 17:18:25.833   295  6504 I SurfaceFlinger: id=24 Removed VSBConnecti (1/4)
08-12 17:18:25.833   295  6504 I SurfaceFlinger: id=5 Removed TtatusBar (2/3)
08-12 17:18:25.833   295  6504 I SurfaceFlinger: id=5 Removed TtatusBar (-2/3)
08-12 17:18:25.843   295  6504 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/3)
08-12 17:18:25.843   295  6504 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/3)
08-12 17:18:25.843   295  6504 I SurfaceFlinger: id=7 Removed JmageWallpa (0/2)
08-12 17:18:25.843   295  6504 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/2)
08-12 17:18:25.843   295  6504 I SurfaceFlinger: id=18 Removed DolorFade (1/1)
08-12 17:18:25.843   295  6504 I SurfaceFlinger: id=18 Removed DolorFade (-2/1)
08-12 17:18:25.843   295   365 I SurfaceFlinger: id=22 Removed VSBConnecti (0/0)
08-12 17:18:25.843   295   365 I SurfaceFlinger: id=22 Removed VSBConnecti (-2/0)
08-12 17:18:25.843   295   365 I SurfaceFlinger: id=24 Removed VSBConnecti (-2/0)
08-12 17:18:25.843  5625  5688 E WifiManager: Channel connection lost
08-12 17:18:25.843  1887  1899 W Sensors : sensorservice died [0xb4758f40]
08-12 17:18:25.843  1981  1992 W Sensors : sensorservice died [0xb4751980]
08-12 17:18:25.853  1714  2409 E WifiManager: Channel connection lost
,08-12 17:18:25.863  2247  2247 D BluetoothA2dp: Proxy object disconnected
08-12 17:18:25.863  2851  2851 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-12 17:18:25.863  2851  2851 D PanProfile: Bluetooth service disconnected
08-12 17:18:25.863  2851  2851 D BluetoothMap: Proxy object disconnected
08-12 17:18:25.863  2851  2851 D MapProfile: Bluetooth service disconnected
08-12 17:18:25.873  2851  2851 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9072bd in tid 2851 (ndroid.settings)
08-12 17:18:25.873  2851  2851 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 17:18:25.873  2206  2206 E audit_log: File locking failed. error= Bad file descriptor
,08-12 17:18:25.913   351   351 I Zygote  : Process 2851 exited due to signal (7)
,08-12 17:18:25.913   351   351 I Zygote  : Process 2201 exited due to signal (7)
,08-12 17:18:26.073   295   553 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-12 17:18:26.073   295   295 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-12 17:18:26.073   295   577 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
08-12 17:18:26.073   295   577 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,08-12 17:18:26.083   293   293 I lowmemorykiller: ActivityManager disconnected
08-12 17:18:26.083   293   293 I lowmemorykiller: Closing Activity Manager data connection
,08-12 17:18:26.293   295   553 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 17:18:26.323   295   295 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-12 17:18:26.323   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd73a4
,08-12 17:18:26.323   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd738c
,08-12 17:18:26.323   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd738c
08-12 17:18:26.323   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd738c
,08-12 17:18:26.323   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd738c
08-12 17:18:26.323   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd73a4
,08-12 17:18:26.323   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbecd73a4

```
