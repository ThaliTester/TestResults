#### Test 830701771a7aee8_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
09-08 18:23:27.363  1470  1470 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
--------- beginning of system
09-08 18:23:27.363  1018  3274 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 2 receivers.size=42
09-08 18:23:27.363  1018  3274 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
09-08 18:23:27.363  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
09-08 18:23:27.363  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.363  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.363  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.363  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.383  6623  6623 E Zygote  : MountEmulatedStorage()
09-08 18:23:27.383  6623  6623 E Zygote  : v2
09-08 18:23:27.383  6623  6623 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:27.383  6623  6623 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:27.383  6623  6623 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:27.383  6623  6623 I libpersona: KNOX_SDCARD checking this for 10029
09-08 18:23:27.383  6623  6623 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:27.403  1018  1043 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6623 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-08 18:23:27.413  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
09-08 18:23:27.413  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.413  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.413  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.413  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.423  1018  1327 I TactileAssist: enable value -1
09-08 18:23:27.423  1018  1327 I TactileAssist: internal enable value -1
09-08 18:23:27.423  1018  1327 I TactileAssist: intensity value -1
09-08 18:23:27.423  1018  1327 I TactileAssist: saveAppList value true
09-08 18:23:27.423  1018  1327 I TactileAssist: List of disabled apps :
,09-08 18:23:27.443  6640  6640 E Zygote  : MountEmulatedStorage()
09-08 18:23:27.443  6640  6640 I libpersona: KNOX_SDCARD checking this for 10098
09-08 18:23:27.443  6640  6640 E Zygote  : v2
09-08 18:23:27.443  6640  6640 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:27.443  6640  6640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:27.443  6623  6623 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:27.443  6623  6623 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:27.443  1018  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6640 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-08 18:23:27.443  6640  6640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:27.443  6640  6640 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:27.453  2775  2775 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
09-08 18:23:27.463  2775  2775 I AASAservice-TokenRule: parseToken()
09-08 18:23:27.463  2775  2775 W System.err: java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
09-08 18:23:27.463  2775  2775 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 18:23:27.463  2775  2775 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:23:27.463  2775  2775 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-08 18:23:27.463  2775  2775 W System.err: 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:86)
09-08 18:23:27.463  2775  2775 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:55)
09-08 18:23:27.463  2775  2775 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-08 18:23:27.463  2775  2775 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-08 18:23:27.463  2775  2775 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-08 18:23:27.463  2775  2775 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:27.463  2775  2775 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:27.463  2775  2775 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:27.463  2775  2775 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:27.463  2775  2775 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:27.463  2775  2775 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:27.463  2775  2775 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:27.463  2775  2775 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
09-08 18:23:27.463  2775  2775 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 18:23:27.463  2775  2775 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:23:27.463  2775  2775 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 18:23:27.463  2775  2775 W System.err: 	... 14 more
09-08 18:23:27.463  2775  2775 E AASAservice-TokenRule: parseToken() : TokenFile is null
09-08 18:23:27.463  2775  2775 E AASAservice-UpdateReceiver: AASARuleUpdateResult() : Rule file is not exist.
09-08 18:23:27.463  2775  2775 I art     : System.exit called, status: 0
09-08 18:23:27.463  2775  2775 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-08 18:23:27.473  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
09-08 18:23:27.473  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.473  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.473  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.473  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.473  6640  6640 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:27.483  6640  6640 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:27.493  6656  6656 E Zygote  : MountEmulatedStorage()
09-08 18:23:27.493  6656  6656 E Zygote  : v2
09-08 18:23:27.493  6656  6656 I libpersona: KNOX_SDCARD checking this for 10048
09-08 18:23:27.493  6656  6656 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:27.493  6656  6656 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:27.493  1018  1505 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6656 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
09-08 18:23:27.503  6656  6656 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:27.503  6656  6656 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-08 18:23:27.513  1018  1238 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
09-08 18:23:27.523  1018  1493 I ActivityManager: Killing 6305:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
09-08 18:23:27.523   318   318 I art     : Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 783us total 28.197ms
09-08 18:23:27.533  2742  2742 I DBG_POLICYDM: [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
09-08 18:23:27.533  6656  6656 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:27.533  6656  6656 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:27.543  6623  6668 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
09-08 18:23:27.543  1018  3836 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-08 18:23:27.553  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.553  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.553  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.553  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.553   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 714us total 27.867ms
09-08 18:23:27.563  2742  2742 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(79/onServiceDisconnected)] AASA: onServiceDisconnected
09-08 18:23:27.563  6640  6640 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
09-08 18:23:27.563  6640  6640 D PackageIntentReceiver: Not GearManger package! 
09-08 18:23:27.573  6623  6668 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-08 18:23:27.573  6623  6668 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:27.573  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.573  6623  6668 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-08 18:23:27.573  6623  6668 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-08 18:23:27.573   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 18.651ms
09-08 18:23:27.583  6656  6656 D Compatibility: onReceive() it will make start service
09-08 18:23:27.583  6623  6668 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-08 18:23:27.583   301   301 E SMD     : DCD OFF
09-08 18:23:27.593  6623  6668 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-08 18:23:27.593  6623  6668 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 18:23:27.593  6623  6668 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:27.593  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.593  6623  6668 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-08 18:23:27.593  6675  6675 E Zygote  : MountEmulatedStorage()
09-08 18:23:27.593  6675  6675 I libpersona: KNOX_SDCARD checking this for 10032
09-08 18:23:27.593  6675  6675 E Zygote  : v2
09-08 18:23:27.593  6675  6675 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:27.593  6675  6675 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:27.593  1018  3836 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6675 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:27.593  1018  1522 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-08 18:23:27.593  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
09-08 18:23:27.593  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:27.593  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:27.593  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
09-08 18:23:27.593  6675  6675 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:27.603  1018  3274 I ActivityManager: Process com.samsung.aasaservice (pid 2775)(adj 0) has died(103,712)
09-08 18:23:27.603  1018  3274 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
09-08 18:23:27.603  6675  6675 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-08 18:23:27.603  6656  6681 D Compatibility: onHandleIntent()
09-08 18:23:27.603  1018  3836 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
09-08 18:23:27.603  6656  6681 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10170, android.intent.extra.user_handle=0}]
09-08 18:23:27.603  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.603  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.603  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.603  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.613  6656  6681 D Compatibility: found: 2
09-08 18:23:27.613  6623  6668 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 18:23:27.613  6623  6668 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:27.613  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.613  6623  6668 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-08 18:23:27.613  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.613  6623  6668 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-08 18:23:27.623  6690  6690 E Zygote  : MountEmulatedStorage()
09-08 18:23:27.623  6690  6690 E Zygote  : v2
09-08 18:23:27.623  6690  6690 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:27.623  6690  6690 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:27.623  6690  6690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:27.633  6656  6681 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-08 18:23:27.633  1018  3836 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 18:23:27.633  6690  6690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:27.633  1018  3836 I ActivityManager: Killing 5901:com.google.android.gm/u0a99 (adj 15): empty #21
09-08 18:23:27.633  6690  6690 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:27.633  1018  1493 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
09-08 18:23:27.633  6656  6681 D Compatibility: skipping ResolveInfo{f9c50a1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-08 18:23:27.633  6656  6681 D Compatibility: considering ResolveInfo{3a592c6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-08 18:23:27.633  6656  6681 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
09-08 18:23:27.643  6656  6681 D Compatibility: enabling receiver ResolveInfo{b5c0287 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-08 18:23:27.643  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.643  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.643  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.643  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.643  6623  6668 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 18:23:27.643  6623  6668 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:27.643  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.643  6623  6668 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-08 18:23:27.643  6623  6668 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 18:23:27.643  6623  6668 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 18:23:27.643  6623  6668 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-08 18:23:27.653  6656  6681 D Compatibility: enabling receiver ResolveInfo{1a5c65b4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-08 18:23:27.653  6675  6675 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:27.653  6675  6675 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:27.663  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.663  6623  6668 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 18:23:27.663  6623  6668 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-08 18:23:27.663  6706  6706 E Zygote  : MountEmulatedStorage()
09-08 18:23:27.663  6706  6706 E Zygote  : v2
09-08 18:23:27.663  6706  6706 I libpersona: KNOX_SDCARD checking this for 10052
09-08 18:23:27.663  6706  6706 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:27.663  6706  6706 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:27.663  1018  1493 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6706 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-08 18:23:27.663  6706  6706 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:27.663  6706  6706 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-08 18:23:27.673  6656  6681 D Compatibility: enabling receiver ResolveInfo{3d8c55dd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-08 18:23:27.683  6690  6690 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:27.683  6690  6690 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:27.693  6623  6668 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-08 18:23:27.693  6623  6668 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 18:23:27.693  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.693  6623  6668 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 18:23:27.693  6656  6681 D Compatibility: enabling receiver ResolveInfo{3cd81552 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-08 18:23:27.693  1018  1542 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-08 18:23:27.693  1018  1542 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
09-08 18:23:27.693  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:27.693  1018  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:27.693  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
09-08 18:23:27.703  6623  6668 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-08 18:23:27.703  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.703  6623  6668 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 18:23:27.703  6623  6668 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-08 18:23:27.703  6656  6681 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
09-08 18:23:27.713  1018  4614 I ActivityManager: Killing 4997:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
09-08 18:23:27.713  6706  6706 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:27.713  6706  6706 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:27.733  1879  1879 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-08 18:23:27.733  1879  1879 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
09-08 18:23:27.733  1879  6719 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
09-08 18:23:27.743  6662  6662 D AndroidRuntime: 
09-08 18:23:27.743  6662  6662 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-08 18:23:27.743  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:27.743  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
09-08 18:23:27.743  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:27.743  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:27.743  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:27.743  6662  6662 D AndroidRuntime: CheckJNI is OFF
09-08 18:23:27.743  6662  6662 D AndroidRuntime: readGMSProperty: start
09-08 18:23:27.743  6662  6662 D AndroidRuntime: readGMSProperty: already setted!!
09-08 18:23:27.743  6662  6662 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-08 18:23:27.743  6662  6662 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-08 18:23:27.743  6662  6662 D AndroidRuntime: readGMSProperty: end
09-08 18:23:27.743  6662  6662 D AndroidRuntime: addProductProperty: start
09-08 18:23:27.743  6623  6668 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-08 18:23:27.743  6623  6668 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:27.743  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.743  6623  6668 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-08 18:23:27.743  1018  4614 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:27.743  1018  4614 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
09-08 18:23:27.743  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:27.743  1018  4614 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:27.743  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:27.753  1018  3836 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
09-08 18:23:27.753  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.753  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.753  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.753  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.763  6623  6668 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-08 18:23:27.783  6724  6724 E Zygote  : MountEmulatedStorage()
09-08 18:23:27.783  6724  6724 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:27.783  6724  6724 E Zygote  : v2
09-08 18:23:27.783  6724  6724 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:27.783  6724  6724 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:27.783  1018  3836 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6724 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 18:23:27.783  1018  3836 I ActivityManager: Killing 6171:com.google.android.music:main/u0a108 (adj 15): empty #21
09-08 18:23:27.783  6724  6724 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:27.783  1018  1141 I ActivityManager: Killing 5986:com.android.vending/u0a26 (adj 15): empty #21
09-08 18:23:27.783  6724  6724 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:27.793  6675  6723 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-08 18:23:27.793  6675  6723 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
09-08 18:23:27.793  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:27.793  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
09-08 18:23:27.793  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:27.793  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:27.793  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:27.803  6675  6723 D SPPClientService: PushLog.txt file is not deleted.
09-08 18:23:27.803  6675  6723 D SPPClientService: PushLog.txt file is not deleted.
09-08 18:23:27.803  6675  6723 D SPPClientService: ============PushLog. stop!
09-08 18:23:27.813  1018  1327 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:27.813  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-08 18:23:27.813  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:27.813  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:27.813  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:27.823  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
09-08 18:23:27.823  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.823  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.823  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.823  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.833  6724  6724 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:27.833  6724  6724 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:27.833  6623  6668 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-08 18:23:27.833  6623  6668 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-08 18:23:27.833  6623  6668 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 18:23:27.833  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.833  6623  6668 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 18:23:27.843  6746  6746 E Zygote  : MountEmulatedStorage()
09-08 18:23:27.843  6746  6746 I libpersona: KNOX_SDCARD checking this for 10039
09-08 18:23:27.843  6746  6746 E Zygote  : v2
09-08 18:23:27.843  6746  6746 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:27.843  6746  6746 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:27.843  1018  1030 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6746 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-08 18:23:27.843  6746  6746 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:27.843  6746  6746 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:27.853  1018  3836 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.wearable.service.WearableControlService in 10745ms
09-08 18:23:27.853  1018  1042 E libprocessgroup: failed to kill 1 processes for processgroup 5901
09-08 18:23:27.863  6623  6668 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-08 18:23:27.863  6623  6668 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.883  6746  6746 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:27.883  6746  6746 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:27.883  6662  6662 E AffinityControl: AffinityControl: registerfunction enter
09-08 18:23:27.893  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-08 18:23:27.893  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-08 18:23:27.893  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:27.893  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:27.893  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-08 18:23:27.893  6623  6668 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
09-08 18:23:27.903  1018  1141 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-08 18:23:27.903  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-08 18:23:27.903  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:27.903  1018  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:27.903  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-08 18:23:27.903  6746  6746 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 18:23:27.903  6746  6746 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:27.903  6746  6746 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:27.903  6746  6746 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-08 18:23:27.903  6746  6746 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 18:23:27.903  6746  6746 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 18:23:27.903  6746  6746 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-08 18:23:27.913  1018  1506 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
09-08 18:23:27.913  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.913  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.913  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.913  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:27.913  6724  6763 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
09-08 18:23:27.913  6662  6662 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-08 18:23:27.923  6724  6763 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-08 18:23:27.933  6766  6766 E Zygote  : MountEmulatedStorage()
09-08 18:23:27.933  6766  6766 I libpersona: KNOX_SDCARD checking this for 10117
09-08 18:23:27.933  6766  6766 E Zygote  : v2
09-08 18:23:27.933  6766  6766 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:27.933  6766  6766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:27.933  1018  1506 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6766 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-08 18:23:27.933  1018  1506 I ActivityManager: Killing 6392:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
09-08 18:23:27.933  6766  6766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:27.933  6766  6766 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-08 18:23:27.943  1018  3274 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-08 18:23:27.943  1018  3274 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
09-08 18:23:27.943  1018  3274 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:27.943  1018  3274 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:27.943  1018  3274 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-08 18:23:27.943  6724  6724 D AcmsService: Enter Oncreate
09-08 18:23:27.953  6724  6724 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-08 18:23:27.953  6724  6724 D AcmsService: creating AcmsCore
09-08 18:23:27.953  6724  6724 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-08 18:23:27.953  6724  6724 D AcmsCore: AcmsCore
09-08 18:23:27.953  6724  6724 D AcmsCore: init
09-08 18:23:27.953  6724  6724 D AcmsCore: Looper handler is not null
09-08 18:23:27.953  6724  6724 D AcmsCore: Post to AcmsCoreHandler
09-08 18:23:27.953  6724  6724 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-08 18:23:27.953  6724  6724 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-08 18:23:27.953  6724  6724 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-08 18:23:27.953  6724  6724 D AcmsService: onStartCommand
09-08 18:23:27.953  6724  6724 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-08 18:23:27.953  6724  6724 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-08 18:23:27.953  6724  6724 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-08 18:23:27.953  6724  6724 D AcmsService: Incremented Counter Value : onStartCommand
09-08 18:23:27.963  1018  1522 E PersonaManagerService: inState():  stateMachine is null !!
09-08 18:23:27.963  6724  6775 D AcmsCertificateMngr: AcmsCertificateMngr
09-08 18:23:27.963  1018  1522 I PersonaManagerService: PersonaId don't exist
09-08 18:23:27.963  1018  1522 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-08 18:23:27.973  1018  1542 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-08 18:23:27.973  6766  6766 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:27.973  6766  6766 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:27.973  6724  6724 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-08 18:23:27.973  1018  1522 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 18:23:27.983  6724  6775 D AcmsRevocationMngr: AcmsRevocationMngr
09-08 18:23:27.993  1018  1522 W ActivityManager: mDVFSHelper.acquire()
09-08 18:23:28.003  1018  1522 D FocusedStackFrame: Set to : 0
09-08 18:23:28.023  6724  6724 D AcmsService: Inside handle Intent
09-08 18:23:28.023  6724  6724 D AcmsService: App added - package name: com.test.thalitest
09-08 18:23:28.023  6724  6724 D AcmsCore: Post to AcmsCoreHandler
09-08 18:23:28.023  6724  6724 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-08 18:23:28.023  6724  6724 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-08 18:23:28.023  6724  6724 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-08 18:23:28.023  6724  6724 D AcmsService: Decremented Counter Value : handleStartIntent
09-08 18:23:28.023  6724  6724 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-08 18:23:28.043  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.043  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.043  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.043  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.043  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-08 18:23:28.043  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-08 18:23:28.063  6785  6785 E Zygote  : MountEmulatedStorage()
09-08 18:23:28.063  6785  6785 E Zygote  : v2
09-08 18:23:28.063  6785  6785 I libpersona: KNOX_SDCARD checking this for 10170
09-08 18:23:28.063  6785  6785 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:28.063  6785  6785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:28.063  1018  1522 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-08 18:23:28.063  1018  1522 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6785 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-08 18:23:28.063  1018  1522 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 18:23:28.063  6785  6785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:28.063  1018  1522 D InputDispatcher: Focused application set to: xxxx
09-08 18:23:28.063  6785  6785 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-08 18:23:28.063  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-08 18:23:28.063  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-08 18:23:28.063  1018  1522 D InputDispatcher: Focus left window: 1507
09-08 18:23:28.063   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-08 18:23:28.073  6662  6662 D AndroidRuntime: Shutting down VM
09-08 18:23:28.083  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 18:23:28.083  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-08 18:23:28.093  6785  6785 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:28.093  1018  1238 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-08 18:23:28.093  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
09-08 18:23:28.093  6785  6785 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:28.093  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:28.093  1018  1238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:28.093  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-08 18:23:28.103  1018  3836 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-08 18:23:28.103  1018  1018 V ActivityManager: Display changed displayId=0
09-08 18:23:28.123  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-08 18:23:28.133  6766  6766 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:28.143  1018  3836 D PersonaManager: isKioskContainerExistOnDevice
09-08 18:23:28.163  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-08 18:23:28.183  1018  3836 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
09-08 18:23:28.183  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.183  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.183  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.183  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.193  6805  6805 E Zygote  : MountEmulatedStorage()
09-08 18:23:28.193  6805  6805 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:28.193  6805  6805 E Zygote  : v2
09-08 18:23:28.193  6805  6805 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:28.193   258   438 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-08 18:23:28.193  6805  6805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:28.203   258   443 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-08 18:23:28.203  6805  6805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:28.203  6805  6805 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:28.203  1018  3836 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6805 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 18:23:28.213  1018  4614 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-08 18:23:28.223  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:28.223  1507  1507 V ActivityThread: updateVisibility : ActivityRecord{22fe356b token=android.os.BinderProxy@795dd89 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-08 18:23:28.223  1507  1507 D Launcher: onTrimMemory. Level: 20
09-08 18:23:28.223  1018  4614 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:28.223  6805  6805 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:28.223  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:28.223  6805  6805 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:28.233  1879  1879 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-08 18:23:28.233  6746  6746 D NearbySource: Nearby Source Create!
09-08 18:23:28.243  1879  1879 I ConfigFetchService: launchTask
09-08 18:23:28.253  6562  6562 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
09-08 18:23:28.263  6746  6746 D NearbyContext: Nearby Context Create!
09-08 18:23:28.273  6662  6662 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-08 18:23:28.293  1879  6823 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1W4AdurZWD_7o89eB6hzBNj1bkOEb-jTAdd6KcKSzTDT9k6eg2te3iler0Kvzn-I3OA22oBLQZ2ROgnUkhs9eJyxbIjJkjssYtHsFLbt-gjWHbC5tOUkKXSpevWeRHl0AK1qJlxYyMR2lFdgVG8i9hYI8tBDJdqsLuw9A_2TvMRgMmmBJ-gjwz62cvDDnbrIKdo8DyMSo85JWof0AtMwMzFmDCOErKPY1vYSnTHMEdJhmyGCOs
09-08 18:23:28.323   257   538 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-08 18:23:28.323   257   538 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 18:23:28.323  6746  6746 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
09-08 18:23:28.323  6746  6746 D SLinkSource: Samsung link source created
09-08 18:23:28.333  6785  6785 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-08 18:23:28.343  6436  6436 I Mms/MmsApp:  start initViewCache mms
09-08 18:23:28.343  6436  6436 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1936.614218
09-08 18:23:28.343  6436  6436 D Mms/ComposeMessageFragment: fillCache, easy = false
09-08 18:23:28.383  6785  6785 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5752-5754)
09-08 18:23:28.383  6785  6785 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-08 18:23:28.453  1018  1238 I art     : Explicit concurrent mark sweep GC freed 141453(7MB) AllocSpace objects, 2(1824KB) LOS objects, 33% free, 22MB/34MB, paused 9.793ms total 203.584ms
09-08 18:23:28.453  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:28.453  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-08 18:23:28.463  6785  6785 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dec4023}
09-08 18:23:28.463  6785  6785 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-08 18:23:28.463  6785  6785 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 18:23:28.473  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:28.473  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:28.473  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:28.483  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
09-08 18:23:28.493  1879  6823 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
09-08 18:23:28.493  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:28.493  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:28.493  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
09-08 18:23:28.503  1879  1879 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-08 18:23:28.503  1879  1879 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-08 18:23:28.513  1879  6824 I PeopleContactsSync: CP2 sync disabled
09-08 18:23:28.513  1018  4614 D LocationManagerService: getProviders()=[passive, gps]
09-08 18:23:28.513  1018  3274 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-08 18:23:28.513  1018  3274 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4195, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-08 18:23:28.513  1018  3274 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-08 18:23:28.513  1018  3274 D BatteryService: stay LED for charging
09-08 18:23:28.513  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-08 18:23:28.523  1018  1018 I MotionRecognitionService: Plugged
09-08 18:23:28.523  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
09-08 18:23:28.523  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-08 18:23:28.533  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
09-08 18:23:28.533  1879  1879 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
09-08 18:23:28.543  6785  6785 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-08 18:23:28.543  1440  1440 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-08 18:23:28.543  1440  1440 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-08 18:23:28.553  6785  6785 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 18:23:28.553  3209  3209 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-08 18:23:28.553  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-08 18:23:28.553  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:28.553  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:28.553  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:28.553  3209  3339 D HeadsetStateMachine: Disconnected process message: 10
09-08 18:23:28.553  1018  1721 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
09-08 18:23:28.563  1018  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.563  1018  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.563  1018  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.563  1018  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.563  6785  6785 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 18:23:28.573  1018  1721 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6842 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
09-08 18:23:28.573  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:23:28.573  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:23:28.573  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:23:28.573  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-08 18:23:28.573  1182  1182 D SViewCoverView: level :100 plugged : 2
09-08 18:23:28.583  1018  1238 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-08 18:23:28.583  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
09-08 18:23:28.583  1664  4298 I art     : Explicit concurrent mark sweep GC freed 12658(586KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.115ms total 61.836ms
09-08 18:23:28.593  6842  6842 E Zygote  : MountEmulatedStorage()
09-08 18:23:28.593  6842  6842 I libpersona: KNOX_SDCARD checking this for 10014
09-08 18:23:28.593  6842  6842 E Zygote  : v2
09-08 18:23:28.593  6842  6842 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:28.593  6842  6842 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:28.593  6842  6842 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:28.593  6842  6842 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-08 18:23:28.603  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:28.603  1018  1238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:28.603  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:28.613  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.613  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.613  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.613  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.613  1018  1505 E EdmStorageProvider: Admin not in database, something went wrong
09-08 18:23:28.623  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
09-08 18:23:28.633  1018  1542 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:23:28.633  6859  6859 E Zygote  : MountEmulatedStorage()
09-08 18:23:28.633  6859  6859 E Zygote  : v2
09-08 18:23:28.633  6859  6859 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:28.633  6859  6859 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:28.633  6859  6859 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:28.633  6859  6859 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:28.633  6859  6859 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:28.643  1018  1043 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=6859 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 18:23:28.653  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{153e0ad9 u0 com.test.thalitest/.MainActivity t163}
09-08 18:23:28.653  6842  6842 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:28.653  6842  6842 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:28.663  1018  3274 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-08 18:23:28.663  1018  3274 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
09-08 18:23:28.673  1018  3274 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:28.673  1018  3274 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:28.673  1018  3274 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
09-08 18:23:28.683  6859  6859 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:28.683  6859  6859 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:28.683  6785  6785 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 18:23:28.683  6785  6785 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 18:23:28.683  6785  6785 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 18:23:28.683  6785  6785 I Adreno-EGL: Local Branch: 
09-08 18:23:28.683  6785  6785 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 18:23:28.683  6785  6785 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 18:23:28.683  6785  6785 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-08 18:23:28.693  1018  1141 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
09-08 18:23:28.703  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.703  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.703  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.703  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.703  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:23:28.703  6746  6746 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
09-08 18:23:28.723  1018  1141 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6879 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
09-08 18:23:28.733  6879  6879 E Zygote  : MountEmulatedStorage()
09-08 18:23:28.733  6879  6879 I libpersona: KNOX_SDCARD checking this for 10087
09-08 18:23:28.733  6879  6879 E Zygote  : v2
09-08 18:23:28.733  6879  6879 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:28.733  6879  6879 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:28.733  6746  6841 D ContactProvider: getAllContactInfoList Start
09-08 18:23:28.743  1018  6835 I ActivityManager: Killing 6412:com.osp.app.signin/u0a36 (adj 15): empty #21
09-08 18:23:28.743  6879  6879 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:28.743  6879  6879 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-08 18:23:28.753   318   318 I art     : Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 644us total 28.587ms
09-08 18:23:28.763  6706  6762 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-08 18:23:28.773   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 705us total 19.643ms
09-08 18:23:28.773  6879  6879 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:28.773  6879  6879 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:28.783  1018  1522 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-08 18:23:28.783  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
09-08 18:23:28.793   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 18.267ms
09-08 18:23:28.793  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:28.793  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:28.793  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
09-08 18:23:28.823  6436  6436 D AbsListView: Get MotionRecognitionManager
09-08 18:23:28.823  1018  1721 D MotionRecognitionService:  ssp status : false
09-08 18:23:28.833  6746  6841 D ContactProvider: getAllContactInfoList End
09-08 18:23:28.833  6746  6841 I syncContacts: thread: 1243, sync time = 265
09-08 18:23:28.833  6436  6436 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 498.498958
09-08 18:23:28.843  1018  6835 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-08 18:23:28.843  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
09-08 18:23:28.843  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:28.843  1018  6835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:28.843  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
09-08 18:23:28.843  1018  1506 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
09-08 18:23:28.853  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.853  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.853  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.853  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.863  6859  6859 D AASAservice: onCreate()
09-08 18:23:28.863  6859  6859 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
09-08 18:23:28.873  6909  6909 E Zygote  : MountEmulatedStorage()
09-08 18:23:28.873  6909  6909 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:28.873  6909  6909 E Zygote  : v2
09-08 18:23:28.873  6909  6909 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:28.873  6909  6909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:28.873  6909  6909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:28.873  6909  6909 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:28.873  1018  1506 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6909 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 18:23:28.883  6785  6785 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 18:23:28.883  2742  2742 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
09-08 18:23:28.893  1879  6823 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-08 18:23:28.893  1879  6823 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 18:23:28.893  1879  6823 I System.out: (HTTPLog)-Static: isShipBuild true
09-08 18:23:28.893  1879  6823 I System.out: (HTTPLog)-Thread-241-691634310: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-08 18:23:28.893  1879  6823 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 18:23:28.893   282   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 18:23:28.893   282   988 D Netd    : getNetworkForDns: using netid 502 for uid 10011
09-08 18:23:28.893  6785  6785 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-08 18:23:28.893  6785  6785 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-08 18:23:28.903  6785  6785 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-08 18:23:28.903  6785  6785 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-08 18:23:28.913  6909  6909 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:28.913  6909  6909 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:28.933  1018  4614 I ActivityManager: Killing 6354:com.android.defcontainer/u0a3 (adj 15): empty #21
09-08 18:23:28.953  1879  6823 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-08 18:23:28.963  1879  6823 I qtaguid : Tagging socket 96 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1879, getuid(): 10011
09-08 18:23:28.973  6909  6909 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-08 18:23:28.973  6909  6909 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-08 18:23:28.973  6909  6909 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
09-08 18:23:28.993  6909  6909 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-08 18:23:28.993  6909  6909 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 18:23:28.993  6909  6909 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 18:23:28.993  6909  6909 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
09-08 18:23:29.003  1018  4614 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
09-08 18:23:29.003  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.003  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.003  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.003  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.013  6930  6930 E Zygote  : MountEmulatedStorage()
09-08 18:23:29.013  6930  6930 E Zygote  : v2
09-08 18:23:29.013  6930  6930 I libpersona: KNOX_SDCARD checking this for 10026
09-08 18:23:29.013  6930  6930 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:29.023  1018  4614 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6930 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:29.023  1018  4614 I ActivityManager: Killing 6463:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
09-08 18:23:29.023  6930  6930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:29.033  6930  6930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:29.033  6930  6930 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-08 18:23:29.033  1018  1522 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-08 18:23:29.043  1018  1327 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-08 18:23:29.053  6930  6930 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:29.053  6930  6930 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:29.063  1879  6823 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1879, getuid(): 10011
,09-08 18:23:29.083  6436  6436 D Mms/BubbleViewCache: fillCache bubble = 1
,09-08 18:23:29.083  1879  6839 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:23:29.083  1879  6839 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:23:29.143  1879  6839 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:23:29.153  1018  1141 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:29.153  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:29.153  1018  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.153  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,09-08 18:23:29.163  6436  6436 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,09-08 18:23:29.163  1018  6835 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-08 18:23:29.163  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.163  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:29.163  1018  6835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:29.163  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-08 18:23:29.173  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,09-08 18:23:29.183  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-08 18:23:29.183  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.183  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.183  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-08 18:23:29.193  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.203  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.,
09-08 18:23:29.203  1018  1031 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6954 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,09-08 18:23:29.203  1018  1542 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:29.213  1018  1542 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.213  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:29.213  1018  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.213  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:29.213  6954  6954 E Zygote  : MountEmulatedStorage()
09-08 18:23:29.213  6954  6954 E Zygote  : v2
09-08 18:23:29.213  6954  6954 I libpersona: KNOX_SDCARD checking this for 10042
,09-08 18:23:29.213  6954  6954 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:29.213  6954  6954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:29.213  6954  6954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:29.213  6954  6954 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
09-08 18:23:29.213  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.223  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:29.223  1018  1238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.223  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:29.243  6954  6954 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:29.243  6954  6954 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:29.263  1018  3274 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:29.263  1018  3274 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.263  1018  3274 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:29.263  1018  3274 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.263  1018  3274 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:29.273  6436  6975 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,09-08 18:23:29.273  6436  6975 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,09-08 18:23:29.273  6954  6954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:29.273  6954  6954 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 18:23:29.273  6954  6954 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-08 18:23:29.273  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,09-08 18:23:29.273  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.273  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:29.273  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.273  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-08 18:23:29.283  6785  6785 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 18:23:29.283  1018  1031 I ActivityManager: Killing 6480:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-08 18:23:29.293  6930  6930 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-08 18:23:29.303  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-08 18:23:29.303  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.303  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:29.303  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.303  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-08 18:23:29.313  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:29.313  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:29.313  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.313  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-08 18:23:29.313  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.333  6785  6785 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 18:23:29.353  6785  6785 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-08 18:23:29.353  6785  6785 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-08 18:23:29.353  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.353  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:29.353  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:29.353  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:29.353  6785  6785 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-08 18:23:29.363  1018  4614 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:29.363  1018  4614 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.363  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:29.363  1018  4614 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.363  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:29.373  6785  6785 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 18:23:29.373  6785  6785 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 18:23:29.373  1879  6839 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:23:29.383  1879  6839 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:23:29.433  1018  1327 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-08 18:23:29.433  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.433  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.433  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.433  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:29.433  6954  6954 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,09-08 18:23:29.443  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.443  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.,
,09-08 18:23:29.443  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.453  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.453  6993  6993 E Zygote  : MountEmulatedStorage(),
,09-08 18:23:29.453  6993  6993 E Zygote  : v2
09-08 18:23:29.453  6993  6993 I libpersona: KNOX_SDCARD checking this for 10148
09-08 18:23:29.453  6993  6993 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:29.453  6993  6993 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:29.453  6993  6993 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:29.453  1018  1327 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6993 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,09-08 18:23:29.463  6993  6993 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:29.463  1018  1030 I ActivityManager: Killing 6502:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
09-08 18:23:29.463  1879  6839 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:23:29.463  1018  1056 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-08 18:23:29.463  1018  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.463  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:29.463  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.463  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.463  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:29.483  6993  6993 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:29.493  6993  6993 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:29.503  7009  7009 E Zygote  : MountEmulatedStorage()
09-08 18:23:29.503  7009  7009 E Zygote  : v2
09-08 18:23:29.503  7009  7009 I libpersona: KNOX_SDCARD checking this for 10003
09-08 18:23:29.503  7009  7009 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:29.503  6706  6762 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 733 ms] updated apps [took 733 ms] 
09-08 18:23:29.503  7009  7009 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:29.503  7009  7009 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:29.503  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-08 18:23:29.503  1018  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7009 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-08 18:23:29.503  7009  7009 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:29.503  1018  1238 I ActivityManager: Killing 6517:com.wsomacp/u0a23 (adj 15): empty #21
,09-08 18:23:29.513  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.513  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.513  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.513  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.523  1018  1031 I ActivityManager: Killing 6534:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-08 18:23:29.523  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.533  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.533  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.533  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.533  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.533  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.543  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.543  7009  7009 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:29.543  7009  7009 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:29.543  6930  6930 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-08 18:23:29.553  1018  1327 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6502, ws=null) (elapsedTime=2882)
,09-08 18:23:29.553  6993  6993 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-08 18:23:29.573  6930  6930 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-08 18:23:29.573  6930  6930 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-08 18:23:29.573  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,09-08 18:23:29.573  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:29.573  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:29.573  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.573  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:29.593  7030  7030 E Zygote  : MountEmulatedStorage(),
09-08 18:23:29.593  7030  7030 E Zygote  : v2
09-08 18:23:29.593  7030  7030 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:29.593  7030  7030 I libpersona: KNOX_SDCARD not a persona,
09-08 18:23:29.593  7030  7030 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:29.593  7030  7030 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 18:23:29.593  7030  7030 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:29.593  1018  1031 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7030 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 18:23:29.593  1018  1031 I ActivityManager: Killing 6262:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-08 18:23:29.603  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.603  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.603  6930  6930 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-08 18:23:29.603   297   297 E installd: system dir 0 : /system/app/
09-08 18:23:29.603   297   297 E installd: system dir 1 : /system/priv-app/
09-08 18:23:29.603   297   297 E installd: system dir 2 : /vendor/app/
09-08 18:23:29.603   297   297 E installd: system dir 3 : /oem/app/
,09-08 18:23:29.623  7030  7030 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-08 18:23:29.623  7030  7030 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:29.643  1018  1238 I ActivityManager: Killing 6281:com.android.calendar/u0a131 (adj 15): empty #21
,09-08 18:23:29.643  1018  1056 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-08 18:23:29.653  7030  7030 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,09-08 18:23:29.663  1879  6839 W art     : Verification of long com.google.android.gms.games.broker.AchievementAgent.forceResolveInstanceId(com.google.android.gms.games.broker.GamesClientContext, java.lang.String) took 178.057ms
,09-08 18:23:29.673  6785  7046 D OpenGLRenderer: Render dirty regions requested: true
,09-08 18:23:29.683  1018  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-08 18:23:29.683  1018  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 18:23:29.683  1018  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-08 18:23:29.683  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-08 18:23:29.683  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,09-08 18:23:29.683  1018  1043 W ProcessCpuTracker: Skipping unknown process pid 6534
,09-08 18:23:29.683  6785  6785 V ActivityThread: updateVisibility : ActivityRecord{974a4b2 token=android.os.BinderProxy@2704ce14 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-08 18:23:29.693  6785  6901 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-08 18:23:29.703  6785  6785 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-08 18:23:29.703  6785  6785 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-08 18:23:29.723   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-08 18:23:29.723  1018  1506 D InputDispatcher: Focus entered window: 6785
,09-08 18:23:29.733  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 18:23:29.733  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 18:23:29.733  6785  6785 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-08 18:23:29.733  6785  7046 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 18:23:29.743  6785  7046 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-08 18:23:29.743  6785  7046 D OpenGLRenderer: Enabling debug mode 0
,09-08 18:23:29.743  6930  6930 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-08 18:23:29.743  1018  1327 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-08 18:23:29.743  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,09-08 18:23:29.743  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:29.743  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.743  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-08 18:23:29.763  1018  1493 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-08 18:23:29.763  6930  7050 D Ads     : Skipping gmscore version check
,09-08 18:23:29.773  6930  6930 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-08 18:23:29.773  1018  7053 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 18:23:29.773  1182  1182 D PanelView: There is/are notification(s) 
,09-08 18:23:29.793  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-08 18:23:29.793  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:29.793  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.793  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.793  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:29.793  6785  6785 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-08 18:23:29.803  6785  6785 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2704ce14 time:97170
,09-08 18:23:29.813  7056  7056 E Zygote  : MountEmulatedStorage(),
09-08 18:23:29.813  7056  7056 E Zygote  : v2
09-08 18:23:29.813  7056  7056 I libpersona: KNOX_SDCARD checking this for 10152
09-08 18:23:29.813  7056  7056 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:29.813  1018  1505 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7056 uid=10152 gids={50152, 9997} abi=armeabi-v7a,
09-08 18:23:29.813  1018  1505 I ActivityManager: Killing 6553:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-08 18:23:29.823  1018  1048 I ActivityManager: Displayed Component not be shown by security: +1s672ms (total +1s779ms),
09-08 18:23:29.823  1018  1048 W ActivityManager: mDVFSHelper.release()
09-08 18:23:29.823  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{153e0ad9 u0 com.test.thalitest/.MainActivity t163} time:97191
09-08 18:23:29.823  1018  6835 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:29.823  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:29.823  1018  6835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:29.823  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-08 18:23:29.833   258   438 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-08 18:23:29.833   258   443 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-08 18:23:29.843   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7bf37c8
09-08 18:23:29.843   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-08 18:23:29.843   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
09-08 18:23:29.843   273   292 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1212204920)
,09-08 18:23:29.853  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-08 18:23:29.873  7056  7056 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:29.873  7056  7056 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:29.873  7056  7056 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-08 18:23:29.883  1879  6823 I qtaguid : Untagging socket 96
,09-08 18:23:29.893  7056  7056 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:29.903  7056  7056 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:29.903   273   292 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-08 18:23:29.903   273   292 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-08 18:23:29.903   273   292 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1212204920) wakelock released: 1, error no: 0
09-08 18:23:29.903   273   292 I rmt_storage: 
,09-08 18:23:29.903   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7bf37c8
,09-08 18:23:29.913  1879  1879 I ConfigFetchService: fetch service done; releasing wakelock
,09-08 18:23:29.913  1879  1879 I ConfigFetchService: stopping self
,09-08 18:23:29.923  7056  7056 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-08 18:23:29.923  7056  7056 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,09-08 18:23:29.933  7056  7056 I TapandpayWidget:Utils: Clear T&P info.
,09-08 18:23:29.933  1889  1889 I SamsungIME: getCurrentCandidateView
,09-08 18:23:29.963  7056  7056 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-08 18:23:29.963  1018  6835 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-08 18:23:29.963  1018  6835 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.963  1018  6835 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.963  1018  6835 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:29.963  1018  6835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:29.983  7074  7074 E Zygote  : MountEmulatedStorage()
09-08 18:23:29.983  7074  7074 E Zygote  : v2
09-08 18:23:29.983  7074  7074 I libpersona: KNOX_SDCARD checking this for 10009
09-08 18:23:29.983  7074  7074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:29.983  7074  7074 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:29.983  7074  7074 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:29.983  1018  6835 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7074 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-08 18:23:29.983  7074  7074 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-08 18:23:29.983  1018  6835 I ActivityManager: Killing 6584:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-08 18:23:30.023  6785  6785 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6785
,09-08 18:23:30.033  7074  7074 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:30.033  7074  7074 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:30.103  1879  6839 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 100.084ms
,09-08 18:23:30.143  1018  1493 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-08 18:23:30.243  1018  3836 I ActivityManager: Killing 6600:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-08 18:23:30.263  1889  1889 D SamsungIME: Dismiss ExpandCandiate
,09-08 18:23:30.323  6785  6785 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 18:23:30.333  1018  1506 I art     : Explicit concurrent mark sweep GC freed 17614(987KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 22MB/34MB, paused 2.473ms total 156.166ms
,09-08 18:23:30.413  6785  7055 D jxcore_app_log: JniHelper::setJavaVM(0xb78a12b0), pthread_self() = -1209899640
,09-08 18:23:30.423  6785  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 18:23:30.423  6785  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 18:23:30.423  6785  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 18:23:30.423  6785  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 18:23:30.423  6785  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 18:23:30.433  6785  7055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34867ef1 added. We now have 1 listener(s)
,09-08 18:23:30.433  6785  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-08 18:23:30.433  6785  7055 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-08 18:23:30.433  6785  7055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:23:30.443  6785  7055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 18:23:30.443  6785  7055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b01e444 added. We now have 1 listener(s)
09-08 18:23:30.443  6785  7055 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:30.453  6785  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:23:30.453  6785  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 18:23:30.453  6785  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-08 18:23:30.453  6785  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-08 18:23:30.453  6785  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 18:23:30.463  6785  7055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:30.463  6785  7055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-08 18:23:30.473  6785  7055 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 18:23:30.473  6785  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:30.473  6785  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:30.473  6785  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:30.473  6785  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:30.473  6785  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:30.473  6785  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:30.473  6785  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:30.473  6785  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:30.473  6785  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-08 18:23:30.473  6785  7055 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:30.483  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:30.483  6879  6946 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-08 18:23:30.483  6879  6946 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 18:23:30.483  6879  6946 I GAv4    :   adb logcat -s GAv4
,09-08 18:23:30.483  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:30.483  6785  7055 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 18:23:30.513  6785  6785 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 18:23:30.533  1879  4189 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,09-08 18:23:30.543  1889  1889 I SamsungIME: getDebugLevel  : 0x4f4c
,09-08 18:23:30.593   301   301 E SMD     : DCD OFF,
,09-08 18:23:30.603  6879  6946 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:23:30.603  1018  1141 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-08 18:23:30.633  6879  6946 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:23:30.673  6879  6893 W art     : Suspending all threads took: 15.760ms
,09-08 18:23:30.673  1889  1889 I SamsungIME: getDebugLevel  : 0x4f4c
,09-08 18:23:30.683  6879  6946 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,09-08 18:23:30.693  6879  7100 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:23:30.713  1889  1889 I SamsungIME: KeybaordView init() : load resources
,09-08 18:23:30.723  1879  4189 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,09-08 18:23:30.783  1889  1889 I SamsungIME: getCurrentKeyboard
09-08 18:23:30.783  1889  1889 I SamsungIME: getTextKeyboard
,09-08 18:23:30.813  1879  4189 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,09-08 18:23:30.813  1889  1889 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-08 18:23:30.833  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-08 18:23:30.843  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:30.843  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:30.843  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:30.893  1018  1141 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,09-08 18:23:30.893  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:30.893  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:30.893  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:30.893  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:30.903  7105  7105 E Zygote  : MountEmulatedStorage(),
09-08 18:23:30.903  7105  7105 E Zygote  : v2
09-08 18:23:30.903  7105  7105 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:30.903  7105  7105 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:30.903  7105  7105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:30.913  7105  7105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:30.913  7105  7105 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:30.913  1018  1141 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7105 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 18:23:30.913  1018  1141 I ActivityManager: Killing 6562:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-08 18:23:30.933  7105  7105 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:30.933  7105  7105 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:30.983  7105  7105 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,09-08 18:23:30.983  7105  7105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-08 18:23:30.983  1018  1522 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,09-08 18:23:30.993  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,09-08 18:23:30.993  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:30.993  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:30.993  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-08 18:23:30.993  1018  4614 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-08 18:23:31.003  6879  7104 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 18:23:31.003  6879  7104 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 18:23:31.003  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,09-08 18:23:31.003  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:31.003  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-08 18:23:31.003  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:31.003  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:31.013  7105  7105 I FilterInstaller: FilterPackageService : ACTION_CHANGED,
09-08 18:23:31.013  7123  7123 I libpersona: KNOX_SDCARD checking this for 10130
09-08 18:23:31.013  7123  7123 E Zygote  : MountEmulatedStorage()
09-08 18:23:31.013  7123  7123 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:31.013  7123  7123 E Zygote  : v2
09-08 18:23:31.013  7123  7123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:31.023  7123  7123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:31.023  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7123 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,09-08 18:23:31.023  7123  7123 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-08 18:23:31.023  7105  7122 E FilterInstaller: installFilters
,09-08 18:23:31.023  7105  7122 E FilterInstaller: There is no requred permission
,09-08 18:23:31.033  1018  1327 I ActivityManager: Killing 6623:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,09-08 18:23:31.053  7123  7123 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:31.063  7123  7123 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:31.083  7123  7123 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:31.083  7123  7123 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-08 18:23:31.093  1018  3836 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,09-08 18:23:31.103  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:31.103  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:31.103  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:31.103  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:31.123  1018  3836 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7138 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
09-08 18:23:31.123  1018  3836 I ActivityManager: Killing 6640:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-08 18:23:31.123  7138  7138 E Zygote  : MountEmulatedStorage()
09-08 18:23:31.123  7138  7138 E Zygote  : v2
,09-08 18:23:31.123  7138  7138 I libpersona: KNOX_SDCARD checking this for 10131
09-08 18:23:31.123  7138  7138 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:31.123  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:31.133  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 18:23:31.133  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:31.143   318   318 I art     : Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 634us total 31.643ms
,09-08 18:23:31.153  6879  7104 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-08 18:23:31.163  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:31.163  7138  7138 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:31.163   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.528ms
,09-08 18:23:31.183   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 17.257ms
,09-08 18:23:31.193  7138  7138 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-08 18:23:31.193  7138  7138 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 18:23:31.193  7138  7138 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 18:23:31.213  6879  7104 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-08 18:23:31.213  6879  7104 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dcd04b1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-08 18:23:31.213  6879  7104 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-08 18:23:31.243  6785  7097 W jxcore-log: Initializing JXcore engine
09-08 18:23:31.243  6785  7097 W jxcore-log: JXcore engine is ready
,09-08 18:23:31.253  2544  2553 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-08 18:23:31.253  1018  3274 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-08 18:23:31.253  1018  3274 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-08 18:23:31.253  1018  3274 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:31.253  1018  3274 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:31.253  1018  3274 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-08 18:23:31.273  1018  3836 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-08 18:23:31.273  1018  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-08 18:23:31.273  1018  3836 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:31.273  1018  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:31.273  1018  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-08 18:23:31.273  1018  1522 I ActivityManager: Killing 6656:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-08 18:23:31.293  1018  1141 I ActivityManager: Killing 6675:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-08 18:23:31.303  2018  2018 E audit   : type=1400 msg=audit(1473351811.303:205): avc:  denied  { ioctl } for  pid=7097 comm="Thread-1275" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 18:23:31.303  2018  2018 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:31.303  2018  2018 E audit   : type=1300 msg=audit(1473351811.303:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f7018f8 items=0 ppid=318 ppcomm=main pid=7097 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1275" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-08 18:23:31.303  2018  2018 E audit   : type=1320 msg=audit(1473351811.303:205): 
,09-08 18:23:31.313  1018  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 18:23:31.313  6785  7097 W jxcore-log: Starting JXcore engine
,09-08 18:23:31.423  6785  7097 W jxcore-log: Platform android
09-08 18:23:31.423  6785  7097 W jxcore-log: 
09-08 18:23:31.423  6785  7097 W jxcore-log: Process ARCH arm
09-08 18:23:31.423  6785  7097 W jxcore-log: 
,09-08 18:23:31.623  6785  7097 I jxcore-log: JXcore Cordova bridge is ready!
09-08 18:23:31.623  6785  7097 I jxcore-log: 
,09-08 18:23:31.623  6785  7097 W jxcore-log: JXcore engine is started
,09-08 18:23:31.633  6785  7055 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 18:23:31.633  6785  6785 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,09-08 18:23:33.593   301   301 E SMD     : DCD OFF
,09-08 18:23:34.713  1018  3354 D SSRM:n  : SIOP:: AP = 420
,09-08 18:23:34.923  1664  1664 I ConfigService: onDestroy
,09-08 18:23:35.253  6724  6775 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-08 18:23:35.263  6724  6775 I AcmsKeyStoreHelper: Key Store exist
,09-08 18:23:35.263  6724  6775 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-08 18:23:35.323  6724  6775 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit,
09-08 18:23:35.323  6724  6775 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-08 18:23:35.323  6724  6775 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-08 18:23:35.323  6724  6775 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-08 18:23:35.323  6724  6775 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-08 18:23:35.323  6724  6775 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-08 18:23:35.323  6724  6775 D AcmsCore: This is NOT a valid MirrorLink app
09-08 18:23:35.323  6724  6775 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-08 18:23:35.323  6724  6775 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-08 18:23:35.323  6724  6775 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-08 18:23:35.323  6724  6775 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-08 18:23:35.323  6724  6724 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-08 18:23:35.323  6724  6724 D AcmsService: Enter onDestroy
09-08 18:23:35.323  6724  6724 I AcmsService: cleanUp(): inside service clean up
09-08 18:23:35.323  6724  6724 D AcmsCore: AcmsCore: inside DeInit
09-08 18:23:35.323  6724  6724 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,09-08 18:23:35.323  6724  6724 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-08 18:23:35.333  6724  6724 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-08 18:23:35.333  6724  6724 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-08 18:23:35.333  6724  6724 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-08 18:23:35.333  6724  6724 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-08 18:23:35.333  6724  6724 D AcmsService: killing acms process
,09-08 18:23:35.333  6724  6724 I Process : Sending signal. PID: 6724 SIG: 9
,09-08 18:23:35.463  1018  1238 I ActivityManager: Process ACMS.Process (pid 6724)(adj 0) has died(22,741)
,09-08 18:23:36.313  1018  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 18:23:36.593   301   301 E SMD     : DCD OFF,
,09-08 18:23:38.083  1018  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-08 18:23:38.563  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-08 18:23:38.563  1018  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4248, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-08 18:23:38.563  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-08 18:23:38.563  1018  1031 D BatteryService: stay LED for charging
09-08 18:23:38.563  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 18:23:38.573  1018  1018 I MotionRecognitionService: Plugged
09-08 18:23:38.573  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 18:23:38.573  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-08 18:23:38.573  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 18:23:38.573  1440  1440 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-08 18:23:38.573  1440  1440 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-08 18:23:38.583  3209  3209 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 18:23:38.583  3209  3339 D HeadsetStateMachine: Disconnected process message: 10
,09-08 18:23:38.593  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-08 18:23:38.593  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:23:38.593  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:23:38.593  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-08 18:23:38.593  1182  1182 D SViewCoverView: level :100 plugged : 2
,09-08 18:23:38.603  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:38.603  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:38.603  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:38.603  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:38.613  1018  1043 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7161 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-08 18:23:38.623  7161  7161 E Zygote  : MountEmulatedStorage()
09-08 18:23:38.623  7161  7161 E Zygote  : v2
09-08 18:23:38.623  7161  7161 I libpersona: KNOX_SDCARD checking this for 10011
09-08 18:23:38.623  7161  7161 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:38.623  7161  7161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:38.623  7161  7161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:38.623  7161  7161 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 18:23:38.643  7161  7161 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:38.643  7161  7161 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:38.673  7161  7161 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-08 18:23:38.673  7161  7161 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 18:23:38.703  7161  7161 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>,
09-08 18:23:38.703  7161  7161 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-08 18:23:38.703  7161  7161 I MultiDex: VM with version 2.1.0 has multidex support
09-08 18:23:38.703  7161  7161 I MultiDex: install
09-08 18:23:38.703  7161  7161 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-08 18:23:38.743  7161  7161 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...,
,09-08 18:23:38.803  7161  7161 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-08 18:23:38.803  7161  7161 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@cce44f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-08 18:23:38.803  7161  7161 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-08 18:23:38.803  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:38.803  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.803  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.813  1018  1493 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-08 18:23:38.813  1018  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-08 18:23:38.813  1018  1493 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.813  1018  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.813  1018  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.813  1018  4614 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,09-08 18:23:38.813  1664  4994 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-08 18:23:38.813  1018  4614 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
09-08 18:23:38.813  1018  4614 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,09-08 18:23:38.813  1018  4614 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,09-08 18:23:38.813  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.823  1018  4614 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.823  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.823  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.823  1018  6835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.823  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.833  1664  1664 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-08 18:23:38.833  1018  3836 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.833  1018  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.833  1018  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.843  1018  1542 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-08 18:23:38.843  1018  1542 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,09-08 18:23:38.843  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.843  1018  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.843  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.853  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.853  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.853  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.853  1664  1664 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:23:38.853  1664  1664 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:23:38.863  1018  1493 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:38.863  1018  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.863  1018  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.863  7161  7180 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,09-08 18:23:38.863  1879  1879 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-08 18:23:38.863  1018  1493 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:38.863  1018  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
09-08 18:23:38.863  1018  1493 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.863  1018  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.863  1018  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.873  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.873  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.873  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.873  1018  1030 I ActivityManager: Killing 6690:com.samsung.helphub/1000 (adj 15): empty #21
,09-08 18:23:38.883  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:38.883  1018  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.883  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.883  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.883  1018  4614 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.883  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.893  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.893  1018  4614 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.893  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.893  1018  1721 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:38.893  1018  1721 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.893  1018  1721 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.893  1018  1721 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.903  7161  7161 D WearableService: callingUid 10011, callindPid: 7161
,09-08 18:23:38.913  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.913  1018  4614 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.913  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.943  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.943  1018  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.943  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.943  1018  3836 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.943  1018  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.943  1018  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.953  1018  3274 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:38.953  1018  3274 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.953  1018  3274 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.953  1018  3274 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.963  1018  3836 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:38.963  1018  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.963  1018  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.963  1735  3095 E MDM     : [175] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-08 18:23:38.963  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:38.963  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,09-08 18:23:38.963  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:38.963  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.973  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.973  1879  7183 D LocationInitializer: Restart initialization of location
,09-08 18:23:38.973  1018  6835 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:38.973  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,09-08 18:23:38.973  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.973  1018  6835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.973  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.983  1018  1542 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:38.983  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.983  1018  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:38.983  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.593   301   301 E SMD     : DCD OFF
,09-08 18:23:39.653  1018  1056 D PackageManager: [MSG] MCS_UNBIND
,09-08 18:23:41.083  1018  1323 E Watchdog: !@Sync 3,
,09-08 18:23:41.613   330   330 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-08 18:23:41.613   330   330 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-08 18:23:42.593   301   301 E SMD     : DCD OFF
,09-08 18:23:43.893  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-08 18:23:43.893  6785  7097 I jxcore-log: 
,09-08 18:23:43.893  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-08 18:23:43.893  6785  7097 I jxcore-log: 
,09-08 18:23:43.893  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-08 18:23:43.893  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:43.893  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:43.893  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:43.893  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:43.893  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:43.893  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:43.893  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:43.893  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-08 18:23:43.903  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 18:23:43.903  6785  7097 I jxcore-log: 
,09-08 18:23:43.903  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 18:23:43.903  6785  7097 I jxcore-log: 
,09-08 18:23:44.003  1018  3836 I ActivityManager: Killing 6746:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-08 18:23:44.573  6785  7097 D executeNativeTests: Running unit tests,
,09-08 18:23:44.613  1018  1096 V AlarmManager: waitForAlarm result :4,
09-08 18:23:44.613  1018  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-08 18:23:44.663  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:23:44.663  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 added. We now have 2 listener(s)
,09-08 18:23:44.673  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-08 18:23:44.673  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:23:44.673  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:23:44.673  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:44.673  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 added. We now have 2 listener(s)
09-08 18:23:44.673  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:44.673  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:23:44.673  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:44.683  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:44.683  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.683  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:44.683  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.683  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:44.683  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.683  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.683  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:44.683  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:44.683  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:44.683  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:44.683  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 18:23:44.683  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:44.683  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 18:23:44.683  6785  7097 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 18:23:44.683  6785  7097 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:44.693  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:44.693  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:44.693  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.693  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:23:44.693  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.693  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.693  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.693  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:23:44.693  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 removed from the list
09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.693  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 removed from the list
09-08 18:23:44.693  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.693  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.693  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.693  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.693  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:44.693  6785  7097 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-08 18:23:44.693  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.693  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.693  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.693  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.693  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.693  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.693  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:44.693  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.693  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.693  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.693  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.693  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.693  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.693  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:23:44.703  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.703  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.703  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.703  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.703  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.703  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.703  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:44.703  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.703  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:44.703  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.703  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.703  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.703  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.703  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.703  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.703  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.703  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.703  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:44.703  6785  7097 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 18:23:44.703  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:44.713  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:44.713  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.713  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:44.713  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.713  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:44.713  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.713  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.713  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:44.713  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.713  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:44.713  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:44.713  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:44.713  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:44.713  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:44.713  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:23:44.713  1018  1050 I PowerManagerService: [PWL] Off : 50s ago
09-08 18:23:44.713  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:44.713  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:23:44.723  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:44.723  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:23:44.733  1018  3354 D SSRM:n  : SIOP:: AP = 400
09-08 18:23:44.733  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:23:44.733  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-08 18:23:44.743  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-08 18:23:44.743  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:23:44.743  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:23:44.743  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 18:23:44.753  3209  3328 D BtGatt.GattService: registerClient() - UUID=7f9657c9-50e5-4d62-ad95-67b0f4f4b504
,09-08 18:23:44.793  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=7f9657c9-50e5-4d62-ad95-67b0f4f4b504, clientIf=6
,09-08 18:23:44.803  6785  6794 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 18:23:44.803  3209  3358 D BtGatt.GattService: start scan with filters
,09-08 18:23:44.803  3209  3329 D BtGatt.ScanManager: handling starting scan
,09-08 18:23:44.803  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:23:44.803  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:23:44.803  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:23:44.803  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:23:44.803  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.803  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 18:23:44.803  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.813  3209  3329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:44.813  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:23:44.823  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-08 18:23:44.823  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.823  3209  3329 D BtGatt.ScanManager: allow scan with filters
,09-08 18:23:44.823  3209  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-08 18:23:44.823  3209  3329 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-08 18:23:44.823  6785  7097 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 18:23:44.833  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-08 18:23:44.833  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.833  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.833  6785  7097 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:23:44.833  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.833  3209  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:23:44.833  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:23:44.833  3209  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-08 18:23:44.833  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.833  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:23:44.833  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:44.833  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:44.833  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:44.833  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:23:44.833  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:23:44.833  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:23:44.833  3209  3226 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:23:44.833  3209  3328 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 18:23:44.833  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-08 18:23:44.833  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.843  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:44.843  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:23:44.843  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:23:44.843  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:23:44.843  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:23:44.843  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:44.843  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:23:44.843  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:23:44.843  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:23:44.843  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:23:44.843  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-08 18:23:44.843  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.843  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.843  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.843  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:44.843  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:44.843  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:44.843  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:44.843  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.843  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:44.843  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:44.843  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.843  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:44.843  6785  7097 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 18:23:44.853  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:44.853  3209  3329 D BtGatt.ScanManager: filter size is 1
09-08 18:23:44.853  3209  3329 D BtGatt.ScanManager: delete FilterIndex - 3
,09-08 18:23:44.853  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-08 18:23:44.853  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.853  3209  3329 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:23:44.863  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:44.863  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.863  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:44.863  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.863  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:44.863  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.863  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.863  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:44.863  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:44.863  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-08 18:23:44.863  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:44.863  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:44.863  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:44.863  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:44.863  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:44.863  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:23:44.863  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.863  3209  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:23:44.873  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:23:44.873  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-08 18:23:44.873  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.873  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.873  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.883  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:23:44.883  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:23:44.883  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 18:23:44.883  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:23:44.883  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:23:44.883  3209  3328 D BtGatt.GattService: registerClient() - UUID=674f1da6-a7ff-4cf0-824c-c5c99c3adafa
,09-08 18:23:44.933  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=674f1da6-a7ff-4cf0-824c-c5c99c3adafa, clientIf=6
,09-08 18:23:44.933  6785  6797 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 18:23:44.933  3209  3222 D BtGatt.GattService: start scan with filters
,09-08 18:23:44.933  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:23:44.933  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 18:23:44.933  3209  3329 D BtGatt.ScanManager: handling starting scan
,09-08 18:23:44.933  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 18:23:44.933  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:23:44.943  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.943  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 18:23:44.943  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.943  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-08 18:23:44.943  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.943  3209  3329 D BtGatt.ScanManager: allow scan with filters
09-08 18:23:44.943  3209  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-08 18:23:44.943  3209  3329 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-08 18:23:44.943  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:23:44.943  6785  7097 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 18:23:44.953  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-08 18:23:44.953  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.953  3209  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:23:44.953  3209  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:23:44.953  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:23:44.953  6785  7097 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 18:23:44.953  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:44.953  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 18:23:44.953  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:44.953  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:23:44.953  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 18:23:44.953  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:44.953  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 18:23:44.953  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:23:44.953  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:23:44.953  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:23:44.953  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-08 18:23:44.963  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.963  3209  3358 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:23:44.963  3209  3328 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 18:23:44.963  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:44.963  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:23:44.963  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:23:44.963  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:23:44.963  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:23:44.963  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-08 18:23:44.963  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.963  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:44.963  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:23:44.963  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:23:44.973  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:23:44.973  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:23:44.973  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:44.973  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.973  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.973  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:44.973  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:44.973  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.973  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:44.973  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.973  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:44.973  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:23:44.973  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:44.973  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.973  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:44.973  3209  3329 D BtGatt.ScanManager: filter size is 1
09-08 18:23:44.973  3209  3329 D BtGatt.ScanManager: delete FilterIndex - 4
,09-08 18:23:44.973  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.973  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.973  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.973  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:44.973  6785  7097 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 18:23:44.983  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:44.983  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-08 18:23:44.983  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.983  3209  3329 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:23:44.983  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:44.983  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.983  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:44.983  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.983  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:44.983  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.983  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.983  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:44.983  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:44.983  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:44.983  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:44.983  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:44.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:44.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:44.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:23:44.993  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-08 18:23:44.993  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.993  3209  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:23:44.993  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.993  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-08 18:23:45.003  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:45.003  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:23:45.003  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.003  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-08 18:23:45.003  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:23:45.013  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:23:45.013  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:23:45.013  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:23:45.013  3209  3222 D BtGatt.GattService: registerClient() - UUID=8478a5c2-40f2-4d44-87d0-c7c751c47152
,09-08 18:23:45.013  6930  7027 D Finsky  : [1299] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-08 18:23:45.023  6930  6930 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-08 18:23:45.053  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=8478a5c2-40f2-4d44-87d0-c7c751c47152, clientIf=6
,09-08 18:23:45.053  6785  6794 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-08 18:23:45.053  3209  3328 D BtGatt.GattService: start scan with filters
,09-08 18:23:45.053  3209  3329 D BtGatt.ScanManager: handling starting scan
,09-08 18:23:45.063  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:23:45.063  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 18:23:45.063  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 18:23:45.063  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:23:45.063  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:45.063  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:45.063  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:23:45.063  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-08 18:23:45.063  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:45.073  3209  3329 D BtGatt.ScanManager: allow scan with filters
09-08 18:23:45.073  3209  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-08 18:23:45.073  3209  3329 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-08 18:23:45.073  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:23:45.073  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-08 18:23:45.073  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:45.073  3209  3329 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 18:23:45.073  3209  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:23:45.073  6785  7097 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 18:23:45.073  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.073  6785  7097 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:23:45.073  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.073  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 18:23:45.083  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.083  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:23:45.083  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:45.083  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:45.083  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:45.083  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:23:45.083  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:23:45.083  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:23:45.083  3209  3222 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:23:45.083  3209  3328 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 18:23:45.083  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-08 18:23:45.083  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:45.083  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:45.083  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:23:45.083  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:23:45.083  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:23:45.083  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:23:45.083  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:45.083  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 18:23:45.083  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:23:45.093  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:23:45.093  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:23:45.093  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-08 18:23:45.093  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:45.093  3209  3329 D BtGatt.ScanManager: filter size is 1
,09-08 18:23:45.093  3209  3329 D BtGatt.ScanManager: delete FilterIndex - 5
,09-08 18:23:45.093  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-08 18:23:45.093  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:45.093  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:45.103  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.103  6785  7097 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 18:23:45.103  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.103  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.103  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-08 18:23:45.103  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:45.103  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.103  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.103  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:23:45.103  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.103  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.103  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.103  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.103  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.103  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:45.103  3209  3329 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:23:45.103  6785  7097 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 18:23:45.103  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.103  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.103  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.103  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.103  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.103  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.103  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.103  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.103  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.103  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.103  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.103  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.103  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.103  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 18:23:45.103  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.103  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.103  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.103  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.103  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.103  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.103  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.103  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.103  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.103  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.103  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.103  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.103  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:45.113  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.113  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-08 18:23:45.113  6785  7097 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-08 18:23:45.113  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.113  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.113  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.113  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.113  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.113  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.113  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.113  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.113  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.113  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.113  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.113  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.113  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:45.113  3209  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.113  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.113  6785  7097 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 18:23:45.113  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.113  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.113  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.113  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.113  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.113  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.113  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.113  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.113  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.113  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.113  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.113  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.113  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:45.113  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:45.113  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:45.113  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:45.113  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.113  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.113  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.113  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.113  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.113  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.113  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.113  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.113  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.113  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.113  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.113  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.113  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.123  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-08 18:23:45.123  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:45.123  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:23:45.123  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.123  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.123  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.123  6785  7097 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:45.123  6785  7097 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
,09-08 18:23:45.123  6785  7097 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:45.123  6785  7097 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 18:23:45.123  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:23:45.123  6785  7097 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 18:23:45.123  6785  7097 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:45.123  6785  7097 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 18:23:45.123  6785  7097 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:45.123  6785  7097 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:45.123  6785  7097 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 18:23:45.123  6785  7097 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:45.123  6785  7097 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:45.123  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 18:23:45.133  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 18:23:45.133  6785  7097 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 18:23:45.133  6785  7097 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:45.133  6785  7097 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 18:23:45.133  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.133  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.133  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.133  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.133  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.133  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 18:23:45.133  6785  7190 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1339)
09-08 18:23:45.133  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.133  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.133  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.133  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.133  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.133  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:45.133  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.133  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.133  6785  7097 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-08 18:23:45.133  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.133  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.133  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.133  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.133  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.133  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.133  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.133  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.133  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.133  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.133  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.133  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.133  6785  7191 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1339
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.133  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.133  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.143  6785  7097 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-08 18:23:45.143  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.143  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.143  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 18:23:45.143  6785  7097 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:45.143  6785  7097 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:23:45.143  6785  7097 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:45.143  6785  7097 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:23:45.143  6785  7097 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:45.143  6785  7097 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 18:23:45.143  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.143  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.143  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,1 listener(s) left
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.143  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.143  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.143  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.143  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.143  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.143  6785  7190 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.143  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.143  6785  7190 D BluetoothSocket: connect(): myUserId = 0
,09-08 18:23:45.143  6785  7190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:23:45.143  6785  7097 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 18:23:45.143  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:45.153  3209  3222 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 18:23:45.153  6785  7190 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 18:23:45.153  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:23:45.153  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.153  6785  7192 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 18:23:45.153  6785  7192 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 18:23:45.153  6785  6785 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 18:23:45.153  6785  6785 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:45.153  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.153  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:45.153  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.153  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:45.153  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:45.153  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.153  6785  6785 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.153  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.153  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:45.153  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.153  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.153  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.153  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:45.153  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:45.153  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.153  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.153  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.163  6785  7097 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-08 18:23:45.163  6785  7097 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:45.163  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:45.163  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.163  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.163  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.163  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.163  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.163  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.163  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.163  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.163  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.163  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.163  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.163  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.163  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.163  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:45.163  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.163  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.163  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.163  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.163  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.163  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.163  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.163  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.163  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.163  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.163  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.163  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.163  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:23:45.163  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:45.163  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:45.163  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.163  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.163  6785  7097 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3781 not in the list
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.163  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
09-08 18:23:45.163  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:45.163  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.163  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:45.163  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:45.163  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:45.163  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:45.163  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c692026 not in the list
,09-08 18:23:45.173  6785  7097 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:45.173  6785  7097 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:45.173  6785  7097 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-08 18:23:45.173  6785  7097 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 18:23:45.173  6785  7097 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 18:23:45.173  6785  7097 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 18:23:45.173  6785  7097 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-08 18:23:45.173  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:45.173  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27e00a98 added. We now have 2 listener(s)
09-08 18:23:45.173  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:45.173  6785  7097 D BluetoothAdapter: enable()
,09-08 18:23:45.173  6785  7097 D BluetoothAdapter: enable(): BT is already enabled..!,
,09-08 18:23:45.183  1018  1238 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-08 18:23:45.183  1018  1238 D WifiService: setWifiEnabled: true pid=6785, uid=10170
09-08 18:23:45.183  1018  1238 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 18:23:45.183  1018  1238 W ActivityManager: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:23:45.183  1018  1238 D SecContentProvider2: mCursor = null
,09-08 18:23:45.183  1018  1238 W WifiService: Failed getting userId using ActivityManagerNative
09-08 18:23:45.183  1018  1238 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:23:45.183  1018  1238 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-08 18:23:45.183  1018  1238 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-08 18:23:45.183  1018  1238 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-08 18:23:45.183  1018  1238 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-08 18:23:45.183  1018  1238 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:23:45.183  1018  1238 D SettingsProvider: name = wifi_on
,09-08 18:23:45.183  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-08 18:23:45.183  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@72f02f1 added. We now have 3 listener(s)
09-08 18:23:45.183  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:45.193  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:23:45.193  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@194fded6 added. We now have 4 listener(s)
09-08 18:23:45.193  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:45.193  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-08 18:23:45.193  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c6b4557 added. We now have 5 listener(s)
09-08 18:23:45.193  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:45.193  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 18:23:45.193  1018  1030 D WifiService: setWifiEnabled: false pid=6785, uid=10170
09-08 18:23:45.193  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 18:23:45.193  1018  1030 D SecContentProvider2: mCursor = null
09-08 18:23:45.193  1018  1030 D SettingsProvider: name = wifi_on
,09-08 18:23:45.203  1018  1129 E WifiStateMachine: WifiStateMachine: Leaving Connected state,
,09-08 18:23:45.203  1387  1387 I wpa_supplicant: reset timer : RESET_TIMER 0
09-08 18:23:45.203  1387  1387 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-08 18:23:45.203  1387  1387 I wpa_supplicant: P2P: Current p2p state = IDLE
09-08 18:23:45.203  1387  1387 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-08 18:23:45.203  6785  7097 D BluetoothAdapter: disable()
,09-08 18:23:45.203  1018  4614 D SettingsProvider: name = bluetooth_on
,09-08 18:23:45.213  1018  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:45.223  3209  3285 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-08 18:23:45.223  3209  3285 D BluetoothAdapterProperties: Setting state to 13
09-08 18:23:45.223  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 18:23:45.223  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:45.223  3209  3285 D BluetoothAdapterService: updateAdapterState state is 13
,09-08 18:23:45.223  1018  1141 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:45.223  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 18:23:45.223  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:45.223  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.223  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:45.233  3209  3209 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-08 18:23:45.233  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cc6412, channel: 19, state: LISTENING
,09-08 18:23:45.233  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2cc6412, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a1e97ba, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f7047e3mSocket: android.net.LocalSocket@2547f5e0 impl:android.net.LocalSocketImpl@17ce2099 fd:FileDescriptor[80]
09-08 18:23:45.233  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2547f5e0 impl:android.net.LocalSocketImpl@17ce2099 fd:FileDescriptor[80]
,09-08 18:23:45.233  1018  1129 E WifiNative-wlan0: do suspend true
,09-08 18:23:45.233  3209  3285 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:45.233  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-08 18:23:45.233  3209  3285 D BluetoothAdapterService: terminating service from this receiver
,09-08 18:23:45.233  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-08 18:23:45.233  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.233  1018  1238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.233  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:45.233  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:45.233  3209  3285 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 18:23:45.243  3209  3285 D BluetoothAdapterProperties: mDiscovering is false
09-08 18:23:45.243  4726  4726 D BluetoothPbap: Proxy object disconnected
,09-08 18:23:45.243  4726  4726 D PbapServerProfile: Bluetooth service disconnected
,09-08 18:23:45.243  1018  1327 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-08 18:23:45.243  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:45.243  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,09-08 18:23:45.243  3209  3285 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-08 18:23:45.243  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:45.243  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:45.243  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:45.243  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:45.243  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:45.243  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:45.243  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:45.243  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:45.243  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:45.243  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:45.243  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:45.243  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:45.253  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.253  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.253  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-08 18:23:45.263  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null,
,09-08 18:23:45.263  1889  1889 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:45.263  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-08 18:23:45.263  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:45.263  1182  1182 D BluetoothTile:  getBluetoothState : 13
,09-08 18:23:45.263  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:45.263  1018  1506 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:45.263  1018  3836 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 18:23:45.263  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:45.263  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-08 18:23:45.273  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 18:23:45.273  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:45.273  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:45.273  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:45.273  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:45.273  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:45.273  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:45.273  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:45.273  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:45.273  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:45.273  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.273  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:45.273  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.283  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 18:23:45.283  3209  3288 D BluetoothAdapterProperties: Scan Mode:20
,09-08 18:23:45.283  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@29d57f3f, channel: 5, state: LISTENING
09-08 18:23:45.283  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@29d57f3f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@151d766b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@666900cmSocket: android.net.LocalSocket@2ed72d55 impl:android.net.LocalSocketImpl@262c636a fd:FileDescriptor[82]
09-08 18:23:45.283  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ed72d55 impl:android.net.LocalSocketImpl@262c636a fd:FileDescriptor[82]
,09-08 18:23:45.283  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-08 18:23:45.283  3209  3285 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-08 18:23:45.283  3209  3285 E bt-btif : cmd socket is not created
09-08 18:23:45.283  3209  5208 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:45.283  6785  7190 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@29fdd2d, channel: -1, state: INIT
09-08 18:23:45.283  6785  7190 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@29fdd2d, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11431262, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22f4dff3mSocket: android.net.LocalSocket@277194b0 impl:android.net.LocalSocketImpl@16ca1f29 fd:FileDescriptor[106]
09-08 18:23:45.283  6785  7190 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@277194b0 impl:android.net.LocalSocketImpl@16ca1f29 fd:FileDescriptor[106]
09-08 18:23:45.283  6785  7190 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1339)
,09-08 18:23:45.283  3209  3289 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-08 18:23:45.283  3209  3209 I BtOppRfcommListener: stopping Accept Thread
09-08 18:23:45.283  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@152cd05b, channel: 12, state: LISTENING
09-08 18:23:45.283  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@152cd05b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f9a79d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2cf2a0f8mSocket: android.net.LocalSocket@82a49d1 impl:android.net.LocalSocketImpl@5254c36 fd:FileDescriptor[86]
09-08 18:23:45.283  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@82a49d1 impl:android.net.LocalSocketImpl@5254c36 fd:FileDescriptor[86]
09-08 18:23:45.283  3209  3285 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 18:23:45.283  3209  5208 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-08 18:23:45.293  3209  3209 V BluetoothOppManager: cleanUp...
09-08 18:23:45.293  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.293  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:23:45.293  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.293  1018  1141 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-08 18:23:45.293  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:23:45.293  3209  3289 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,09-08 18:23:45.293  3209  3289 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
,09-08 18:23:45.293  3209  3289 W bt-btif : invalid rfc slot id: 4
09-08 18:23:45.293  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.293  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.293  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:45.303  3209  3289 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:45.303  3209  3289 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:45.303  3209  3289 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:45.303  3209  3289 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:45.303  3209  3289 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:45.303  3209  3289 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-08 18:23:45.303  1664  1664 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:45.313  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:45.313  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:45.313  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:45.313  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-08 18:23:45.313  1387  1387 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
,09-08 18:23:45.313  1018  3274 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-08 18:23:45.323  1018  1128 D WifiP2pService: InactiveState{ what=147461 }
,09-08 18:23:45.323  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.323  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.323  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.323  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.323  1018  1128 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-08 18:23:45.323  1018  1128 D WifiP2pService: DefaultState{ what=147461 }
,09-08 18:23:45.333  1018  1128 D WifiP2pService: InactiveState{ what=143375 },
09-08 18:23:45.333  1018  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 18:23:45.333  7197  7197 E Zygote  : MountEmulatedStorage(),
09-08 18:23:45.333  7197  7197 E Zygote  : v2
09-08 18:23:45.333  7197  7197 I libpersona: KNOX_SDCARD checking this for 10055
09-08 18:23:45.333  7197  7197 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:45.333  7197  7197 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:45.343  1018  3274 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7197 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-08 18:23:45.343   282   992 D CommandListener: Clearing all IP addresses on wlan0,
09-08 18:23:45.343  7197  7197 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:45.343  7197  7197 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:45.343  1664  2527 V NativeCrypto: Read error: ssl=0xb7e0f688: I/O error during system call, Connection timed out,
,09-08 18:23:45.353  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-08 18:23:45.353  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 18:23:45.353  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-08 18:23:45.353  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.353  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.353  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.353  1664  2527 V NativeCrypto: SSL shutdown failed: ssl=0xb7e0f688: I/O error during system call, Broken pipe
09-08 18:23:45.353  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:23:45.353  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:45.353  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:23:45.353  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-08 18:23:45.353  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-08 18:23:45.353  1018  1238 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-08 18:23:45.353  1018  1733 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:45.353  1018  1733 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:45.353  1018  1733 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-08 18:23:45.353  1018  1733 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:45.353  1018  1733 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-08 18:23:45.353  1018  1733 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,09-08 18:23:45.363  1018  1733 I qtaguid : Tagging socket 349 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,09-08 18:23:45.363  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
,09-08 18:23:45.363  1018  1128 D WifiP2pService: InactiveState{ what=131204 }
09-08 18:23:45.363  1018  1152 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:45.363  1018  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
09-08 18:23:45.363  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-08 18:23:45.373  1018  1018 D RttService: SCAN_AVAILABLE : 1
09-08 18:23:45.373  1018  1733 I qtaguid : Untagging socket 349
09-08 18:23:45.373  1018  1733 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:45.373  1018  1153 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:45.373  1018  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 18:23:45.373  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:23:45.383  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.383  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 18:23:45.383  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.383  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.383  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.383  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:45.383  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-08 18:23:45.383  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:45.383  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-08 18:23:45.383  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-08 18:23:45.383  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 18:23:45.383  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 18:23:45.383  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-08 18:23:45.383  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:45.383  1018  1048 D WifiDisplayController: disconnect
09-08 18:23:45.383  1018  1048 D WifiDisplayController: updateConnection
09-08 18:23:45.383  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:45.383  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:23:45.383  1018  1128 D WifiP2pService: P2pDisablingState
09-08 18:23:45.383  1018  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
09-08 18:23:45.383  1018  1128 D WifiP2pService: p2p socket connection lost
,09-08 18:23:45.393  1018  1128 D WifiP2pService: P2pDisabledState
09-08 18:23:45.393  1018  1129 E WifiNative-wlan0: do suspend true
,09-08 18:23:45.393  7197  7197 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:45.393  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 18:23:45.393  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-08 18:23:45.393  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer,
,09-08 18:23:45.393  7197  7197 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:45.393  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-08 18:23:45.403  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-08 18:23:45.403  1018  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:23:45.403  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 18:23:45.423  1018  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-08 18:23:45.423  1018  1128 D WifiP2pService: DefaultState{ what=143375 }
,09-08 18:23:45.423  7197  7197 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
,09-08 18:23:45.423   282   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
,09-08 18:23:45.423   282   988 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-08 18:23:45.423  1018  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-08 18:23:45.423   282   992 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:45.423  1018  1131 V NetworkStats: updateIfacesLocked()
09-08 18:23:45.423  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:23:45.423  1018  1131 V NetworkStats: performPollLocked(flags=0x1),
09-08 18:23:45.423  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:23:45.423  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,09-08 18:23:45.423  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.433  1018  1131 V NetworkStats: performPollLocked() took 7ms
09-08 18:23:45.423  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.423  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.423  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.423  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.433  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:45.433  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:23:45.433  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-08 18:23:45.433  1387  1387 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-08 18:23:45.433  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.433  1018  1733 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-08 18:23:45.433  1018  1733 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-08 18:23:45.443  1182  1707 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 18:23:45.443  1018  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-08 18:23:45.443  1018  1733 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:45.443  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:45.443  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:23:45.443  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-08 18:23:45.443  1018  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:45.443  1018  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-08 18:23:45.443  1482  1482 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-08 18:23:45.443  1482  1482 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:45.443  1018  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-08 18:23:45.443  1018  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-08 18:23:45.443  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-08 18:23:45.443  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:23:45.443  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.443  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:45.443  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.443  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.443  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.443  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:45.453  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:23:45.453  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:23:45.453  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:23:45.453  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:45.453  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:45.453  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.453  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.453  7197  7197 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-08 18:23:45.453  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.453  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.453  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.453  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-08 18:23:45.453  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.453  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.453  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 18:23:45.453  7197  7197 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-08 18:23:45.453  7197  7197 D UserAnalysis: Create SecureDbHelper
,09-08 18:23:45.463  1018  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-08 18:23:45.463  1182  1182 D HotspotTile: onReceive : 0, 0
09-08 18:23:45.463  1018  1131 D ConnectivityService: nai.networkMonitor.doQuit()
,09-08 18:23:45.463  1018  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-08 18:23:45.463  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:23:45.463  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:45.463  1018  1131 E ConnectivityService: updateNetworkInfo()
,09-08 18:23:45.463  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-08 18:23:45.463  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-08 18:23:45.463  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,09-08 18:23:45.463  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.463  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:45.463  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:45.463  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:45.463  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:45.463  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:45.463  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:45.463  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:45.463  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:45.463  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.463  1018  1126 V NetworkStats: updateIfacesLocked()
09-08 18:23:45.463  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:23:45.463  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:45.463  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.463  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:45.463  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:23:45.473  1018  1126 V NetworkStats: performPollLocked() took 4ms
09-08 18:23:45.473  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:45.473  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.473  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:45.473  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:45.473  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:45.473  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:45.473  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:45.473  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:45.473  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:45.473  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:45.473  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
09-08 18:23:45.473  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 18:23:45.473  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 18:23:45.473  1182  1182 D StatusBar.NetworkController: updateDataNetType()
,09-08 18:23:45.473  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.473  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:45.473  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.473  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:45.473  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.473  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:23:45.473  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-08 18:23:45.473  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.473  1018  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-08 18:23:45.473  7197  7197 D IntelligenceServiceApplication: onCreate()
,09-08 18:23:45.473  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-08 18:23:45.473  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-08 18:23:45.473  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-08 18:23:45.473  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-08 18:23:45.483  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.483  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:45.483  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:23:45.483  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.483  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:23:45.483  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.483  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.483  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.483  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:45.483  1018  3274 I ActivityManager: Killing 6706:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-08 18:23:45.493  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-08 18:23:45.493  3209  3285 D BtConfig.SecureMode: isSecureModeOn:false
09-08 18:23:45.493  3209  3285 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-08 18:23:45.493  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-08 18:23:45.493  3209  3285 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-08 18:23:45.493  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-08 18:23:45.493  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 18:23:45.493  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-08 18:23:45.493  7197  7197 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-08 18:23:45.493  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 18:23:45.493  1018  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.493  1018  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-08 18:23:45.493  1018  1493 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.493  1018  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.493  1018  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:45.493  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-08 18:23:45.493  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-08 18:23:45.493  1018  1721 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-08 18:23:45.493  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-08 18:23:45.493  3209  3209 D HeadsetService: Received stop request...Stopping profile...
,09-08 18:23:45.493  1018  3274 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
09-08 18:23:45.493  7197  7197 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-08 18:23:45.503  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.503  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.503  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.503  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.503  7197  7197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-08 18:23:45.513  7219  7219 E Zygote  : MountEmulatedStorage(),
,09-08 18:23:45.513  7219  7219 I libpersona: KNOX_SDCARD checking this for 10105
09-08 18:23:45.513  7219  7219 E Zygote  : v2
09-08 18:23:45.513  7219  7219 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:45.513  7219  7219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-08 18:23:45.513  1018  3274 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7219 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-08 18:23:45.513  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.513  1018  6835 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.513  1018  6835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.513  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-08 18:23:45.513  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:45.513  7219  7219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:45.513  7219  7219 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-08 18:23:45.523  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-08 18:23:45.523  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-08 18:23:45.523  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:45.523  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-08 18:23:45.523  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-08 18:23:45.523  3209  3209 D A2dpService: Received stop request...Stopping profile...
09-08 18:23:45.523  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.523  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-08 18:23:45.523  3209  3349 D A2dpStateMachine: Exit Disconnected: -1
,09-08 18:23:45.523  4726  4726 D HeadsetProfile: Bluetooth service disconnected
09-08 18:23:45.523  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.523  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.523  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:45.533  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-08 18:23:45.533  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 18:23:45.533  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-08 18:23:45.533  1018  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.533  1018  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-08 18:23:45.533  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:45.533  1018  1493 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.533  1018  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.533  1018  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:45.533  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-08 18:23:45.533  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:23:45.533  1018  1018 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:45.533  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-08 18:23:45.533  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-08 18:23:45.533  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.533  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-08 18:23:45.533  4726  4726 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:45.533  4726  4726 D A2dpProfile: Bluetooth service disconnected
,09-08 18:23:45.533  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.533  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-08 18:23:45.533  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:45.543  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.543  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:45.543  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService,
,09-08 18:23:45.543  1018  1522 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.543  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:23:45.543  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.543  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.543  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-08 18:23:45.543  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-08 18:23:45.543  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-08 18:23:45.543  3209  3285 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-08 18:23:45.543  1018  3836 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.543  1018  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:23:45.553  1018  3836 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.553  1018  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.553  1018  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:45.553  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:45.553  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:23:45.553  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:45.553  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:45.553  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-08 18:23:45.553  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:45.553  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-08 18:23:45.553  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 18:23:45.553  7219  7219 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:45.553  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 18:23:45.553  7219  7219 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:45.553  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-08 18:23:45.553  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-08 18:23:45.553  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-08 18:23:45.553  3209  3285 D BluetoothAdapterState: Stopping profile services that were post enabled
09-08 18:23:45.553  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-08 18:23:45.553  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:45.553  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-08 18:23:45.573  3209  3209 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 18:23:45.573  3209  3209 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 18:23:45.573  3209  3209 D HidService: Received stop request...Stopping profile...
09-08 18:23:45.573  3209  3209 D HidService: Stopping Bluetooth HidService
09-08 18:23:45.573  3209  3209 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 18:23:45.573  3209  3209 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-08 18:23:45.573  3209  3209 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 18:23:45.573  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:45.573  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-08 18:23:45.573  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:45.573  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-08 18:23:45.573  3209  3209 D HealthService: Received stop request...Stopping profile...
,09-08 18:23:45.573  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:45.583  4726  4726 D BluetoothInputDevice: Proxy object disconnected
,09-08 18:23:45.583  4726  4726 D HidProfile: Bluetooth service disconnected
09-08 18:23:45.583  3209  3209 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:45.583  3209  3209 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-08 18:23:45.583  1387  1387 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-08 18:23:45.583  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:45.583  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:45.583  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:23:45.583  3209  3350 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-08 18:23:45.583  3209  3209 I GKI_LINUX: GKI_exit_task 2 done
09-08 18:23:45.583  3209  3209 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-08 18:23:45.583  3209  3209 D PanService: Received stop request...Stopping profile...
09-08 18:23:45.583  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:45.583  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:23:45.583  4726  4726 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:23:45.583  4726  4726 D PanProfile: Bluetooth service disconnected
09-08 18:23:45.583  3209  3209 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:45.593  3209  3209 D SapService: Received stop request...Stopping profile...
09-08 18:23:45.593  3209  3209 D SapService: Stopping Bluetooth SapService
09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:45.593  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-08 18:23:45.593  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:45.593  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true,
09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. ,
09-08 18:23:45.593  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.593  3209  3209 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 18:23:45.593  3209  3209 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 18:23:45.593  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-08 18:23:45.593  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.593   301   301 E SMD     : DCD OFF
09-08 18:23:45.593  3209  3209 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 18:23:45.593  3209  3209 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 18:23:45.593  4726  4726 D BluetoothMap: Proxy object disconnected
,09-08 18:23:45.593  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-08 18:23:45.593  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:23:45.593  3209  3209 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService,
09-08 18:23:45.603  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-08 18:23:45.603  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-08 18:23:45.603  3209  3209 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-08 18:23:45.603  3209  3209 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-08 18:23:45.603  4726  4726 D MapProfile: Bluetooth service disconnected
09-08 18:23:45.603  4726  4726 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-08 18:23:45.603  4726  4726 D SapProfile: Bluetooth service disconnected
09-08 18:23:45.603  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-08 18:23:45.603  3209  3285 D BluetoothAdapterProperties: Setting state to 10
,09-08 18:23:45.603  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-08 18:23:45.603  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:45.603  3209  3285 D BluetoothAdapterService: updateAdapterState state is 10
09-08 18:23:45.603  3209  3285 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:45.603  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-08 18:23:45.603  3209  3285 I BluetoothAdapterState: Entering OffState
,09-08 18:23:45.603  1182  1209 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:45.603  1182  1209 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:45.603  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.603  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.603  1387  1387 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-08 18:23:45.603  1387  1387 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,09-08 18:23:45.603  1387  1387 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-08 18:23:45.613  1387  1387 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-08 18:23:45.613  1387  1387 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-08 18:23:45.613  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-08 18:23:45.613  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:45.613  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.613  1018  1132 D Tethering: InitialState.processMessage what=4
,09-08 18:23:45.613  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.613  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:45.613  1018  1132 E Tethering: No numeric data
,09-08 18:23:45.613  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 18:23:45.613  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.613  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:45.613  4726  4734 D Bluetoothsap: onBluetoothStateChange: up=false
09-08 18:23:45.613  4726  4734 D Bluetoothsap: Unbinding service...
,09-08 18:23:45.613  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:45.613  1018  1132 D Tethering: clearTetheredNotification()
,09-08 18:23:45.613  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 18:23:45.623  1735  1915 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.623  1735  1915 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:45.623  4726  4739 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 18:23:45.623  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.623  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:45.623  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 18:23:45.623  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:23:45.623  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:45.623  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:45.623  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:23:45.623  1018  1126 V NetworkStats: performPollLocked() took 3ms
09-08 18:23:45.623  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:45.623  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:45.623  1182  1182 D HotspotTile: updateTetherState():false, false
,09-08 18:23:45.623  3209  3226 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.623  3209  3226 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:45.633  1664  2207 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.633  1664  2207 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:45.633  4726  4734 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:45.633  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 18:23:45.633  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.633  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:45.633  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.633  3209  3358 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:45.633  4726  4739 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.633  4726  4739 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.633  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 18:23:45.633  4726  4734 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 18:23:45.633  6785  6797 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.633  6785  6797 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.633  6785  6797 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-08 18:23:45.633  6785  6797 D BluetoothLeAdvertiser: Exit stop advertising
09-08 18:23:45.633  6785  6797 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-08 18:23:45.633  6785  6797 D BluetoothLeScanner: Exiting stopAllScan
,09-08 18:23:45.633  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.643  1482  1661 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:45.643  1482  1661 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.643  4726  4734 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 18:23:45.643  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.643  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:23:45.643  1459  1478 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.643  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.643  1459  1478 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:45.643  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.643  1470  1486 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.643  1470  1486 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:45.643  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.643  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 18:23:45.643  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:45.643  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
09-08 18:23:45.643  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.643  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 18:23:45.653  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 18:23:45.653  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:45.653  1182  1182 D BluetoothTile:  getBluetoothState : 10
,09-08 18:23:45.653  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 18:23:45.653  1889  1889 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:45.653  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.653  1018  1493 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-08 18:23:45.653  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.653  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:45.653  1018  1238 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 18:23:45.653  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.653  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 18:23:45.663  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:23:45.663  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.663  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.663  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.663  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:45.663  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.663  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.663  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:45.663  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.663  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.663  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.673  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.673  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.673  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.673  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.673  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.673  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.673  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.703   257   538 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-08 18:23:45.703   257   538 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:45.703  7219  7253 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-08 18:23:45.713   257   538 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-08 18:23:45.713   257   538 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:45.713  7219  7253 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-08 18:23:45.753  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 18:23:45.843  7219  7219 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-08 18:23:45.843  7219  7219 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.843  7219  7219 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.843  7219  7219 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.e.b(PG:170)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.843  7219  7219 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.k.d(PG:583)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.e.b(PG:170)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.843  7219  7219 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.843  7219  7219 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.843  7219  7219 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.843  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.853  1018  1505 I ActivityManager: Killing 6151:com.samsung.android.sm/1000 (adj 15): empty #21
09-08 18:23:45.853  1018  4614 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:45.853  1018  4614 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:23:45.853  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.853  1018  4614 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.853  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 18:23:45.853  1631  1631 I Hs20UtilService: Starting #8
09-08 18:23:45.853  1631  1674 I Hs20UtilService: Message received 5007
09-08 18:23:45.863  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-08 18:23:45.863  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 18:23:45.863  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 18:23:45.863  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:23:45.863  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:45.863  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:45.873  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 18:23:45.873  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-08 18:23:45.873  1387  1387 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-08 18:23:45.873  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 18:23:45.883  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 18:23:45.883  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:23:45.883  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:45.883  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-08 18:23:45.883  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-08 18:23:45.883  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.883  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:23:45.883  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.883  1018  1542 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-08 18:23:45.883  1018  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.883  1018  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.883  1018  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.883  1018  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.893  7264  7264 E Zygote  : MountEmulatedStorage()
09-08 18:23:45.893  7264  7264 I libpersona: KNOX_SDCARD checking this for 10064
09-08 18:23:45.893  7264  7264 E Zygote  : v2
09-08 18:23:45.893  7264  7264 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:45.893  7264  7264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:45.903  7264  7264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:45.903  7264  7264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:45.903  1018  1542 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7264 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:45.903  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-08 18:23:45.903  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-08 18:23:45.913  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:23:45.913  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.913  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.913  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:23:45.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.913  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.913  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.913  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-08 18:23:45.923  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 18:23:45.923  1182  1182 D HotspotTile: onReceive : 1, 0
09-08 18:23:45.923  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:45.923  7219  7260 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 18:23:45.923  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.933  1735  2188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:45.933  7264  7264 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:45.933  7264  7264 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:45.943  7264  7264 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 18:23:45.953  1018  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:45.953  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:45.953  1018  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:45.953  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-08 18:23:45.963  7264  7264 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:45.963  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:45.963  7264  7264 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-08 18:23:45.963  1018  1018 I ApplicationPolicy: updateDataUsageMap
,09-08 18:23:45.983  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:45.983  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.983  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.993  7264  7264 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 18:23:45.993  1018  3836 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-08 18:23:45.993  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.993  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.993  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.993  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.013  7281  7281 E Zygote  : MountEmulatedStorage(),
09-08 18:23:46.013  7281  7281 E Zygote  : v2
09-08 18:23:46.013  7281  7281 I libpersona: KNOX_SDCARD checking this for 10065
09-08 18:23:46.013  7281  7281 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.013  7281  7281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:46.013  1018  3836 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7281 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:46.013  1018  3836 I ActivityManager: Killing 6805:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-08 18:23:46.013  7281  7281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:46.013  7281  7281 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.033  7281  7281 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.033  7281  7281 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.053  7281  7281 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:46.063  1018  1493 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.063  1018  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:46.063  1018  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-08 18:23:46.063  1018  1493 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-08 18:23:46.063  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.063  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-08 18:23:46.063  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.063  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.083  7296  7296 E Zygote  : MountEmulatedStorage()
,09-08 18:23:46.083  7296  7296 E Zygote  : v2
09-08 18:23:46.083  7296  7296 I libpersona: KNOX_SDCARD checking this for 10102
09-08 18:23:46.083  7296  7296 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.083  7296  7296 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:46.083  7296  7296 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:46.083  1018  1493 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7296 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-08 18:23:46.083  7296  7296 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-08 18:23:46.083  1018  1238 I ActivityManager: Killing 6879:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-08 18:23:46.103  7296  7296 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.103  7296  7296 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.113  7296  7296 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-08 18:23:46.293  7296  7316 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-08 18:23:46.293  7296  7316 I Babel_SMS: MmsConfig.loadMmsSettings
,09-08 18:23:46.293  7296  7316 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-08 18:23:46.293  7296  7316 I Babel_SMS: MmsConfig.loadFromDatabase
,09-08 18:23:46.313  7296  7316 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-08 18:23:46.313  7296  7316 I Babel_SMS: MmsConfig.loadFromResources
,09-08 18:23:46.313  7296  7316 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-08 18:23:46.313  7296  7316 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-08 18:23:46.333  1018  4614 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-08 18:23:46.333  1018  4614 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-08 18:23:46.333  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.333  1018  4614 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:46.333  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 18:23:46.363  7296  7296 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:46.363  7296  7296 I Babel_Crash: startup - clean
,09-08 18:23:46.393  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:46.393  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:46.393  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.393  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.393  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:46.393  1631  1631 I Hs20UtilService: Starting #9
,09-08 18:23:46.393  1631  1674 I Hs20UtilService: Message received 5007
,09-08 18:23:46.403  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:23:46.403  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:46.403  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:23:46.403  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:23:46.403  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:46.403  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:46.403  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:46.413  7296  7296 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 18:23:46.413  1018  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:46.413  7296  7296 W AudioCapabilities: Unsupported mime audio/evrc
09-08 18:23:46.413  1018  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:46.413  1018  1493 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.413  1018  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.413  1018  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:46.413  7296  7296 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 18:23:46.413  7296  7296 W AudioCapabilities: Unsupported mime audio/mpeg-L1
09-08 18:23:46.423  1631  1631 I Hs20UtilService: Starting #10
,09-08 18:23:46.423  1631  1674 I Hs20UtilService: Message received 5011
,09-08 18:23:46.423  1018  1721 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
09-08 18:23:46.423  7296  7296 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-08 18:23:46.423  1018  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.423  1018  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.423  1018  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.423  1018  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.423  7296  7296 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-08 18:23:46.423  7296  7296 W AudioCapabilities: Unsupported mime audio/x-ima
09-08 18:23:46.423  7296  7296 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 18:23:46.423  7296  7296 W AudioCapabilities: Unsupported mime audio/evrc
,09-08 18:23:46.433  7319  7319 E Zygote  : MountEmulatedStorage()
,09-08 18:23:46.433  7319  7319 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:46.433  7319  7319 E Zygote  : v2
09-08 18:23:46.433  7319  7319 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:46.433  1018  1721 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7319 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-08 18:23:46.433  7296  7296 W VideoCapabilities: Unsupported mime video/wvc1
,09-08 18:23:46.443  7319  7319 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:46.443  7296  7296 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-08 18:23:46.443  7319  7319 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:46.443  7319  7319 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.453  7296  7296 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
09-08 18:23:46.453  7296  7296 W VideoCapabilities: Unsupported mime video/wvc1
09-08 18:23:46.453  7296  7296 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-08 18:23:46.453  7296  7296 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-08 18:23:46.463  7296  7296 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-08 18:23:46.463  7296  7296 W VideoCapabilities: Unsupported mime video/mp43,
,09-08 18:23:46.473  7319  7319 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.473  7319  7319 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.473  7296  7296 W VideoCapabilities: Unsupported mime video/sorenson
,09-08 18:23:46.483  7296  7296 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-08 18:23:46.493  1018  1045 D Tethering: interfaceRemoved wlan0
09-08 18:23:46.493  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-08 18:23:46.503  7296  7296 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 18:23:46.513  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 18:23:46.513  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-08 18:23:46.513  7319  7319 D SecurityLogAgent: StateMachine : Current State = 1
,09-08 18:23:46.513  7319  7319 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:46.513  1018  1030 I ActivityManager: Killing 6842:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-08 18:23:46.523  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.523  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.523  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.523  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.523  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.523  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.533  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.533  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:46.533  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.533  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.533  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:46.533  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.543  7296  7296 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 18:23:46.543  7296  7296 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 18:23:46.543  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.543  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:46.543  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-08 18:23:46.543  7296  7296 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 18:23:46.543  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.543  7296  7296 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 18:23:46.543  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:46.543  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.553  1018  1522 I ActivityManager: Killing 6909:com.sec.pcw.device/1000 (adj 15): empty #21
,09-08 18:23:46.553  7296  7296 I vclib   : onServiceConnected
,09-08 18:23:46.553  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.553  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.553  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.553  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.553  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.553  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.563  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.563  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.563  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.563  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.563  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.563  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.563  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.563  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.563  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.563  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.563  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.563  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.573  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.573  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.573  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.573  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.573  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.573  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.573  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.573  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.573  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.583  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:23:46.583  1018  1141 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 18:23:46.583  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:23:46.583  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.583  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.583  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:46.583  1664  1664 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:46.593  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:46.593  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:46.593  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:46.593  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-08 18:23:46.613   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:46.613  1018  1141 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:46.613  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:46.613  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.613  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:46.623  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:46.623  1018  1045 D Tethering: interfaceRemoved p2p0
09-08 18:23:46.623  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
09-08 18:23:46.623  1631  1631 I Hs20UtilService: Starting #11
,09-08 18:23:46.623  1631  1674 I Hs20UtilService: Message received 5011
,09-08 18:23:46.623  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:23:46.623  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:46.623  7319  7319 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:23:46.623  7319  7319 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:46.633  1018  3836 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-08 18:23:46.633  1018  3836 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.pcw.device/com.sec.pcw.device.receiver.SYSTEMReceiver}
09-08 18:23:46.633  1018  3836 W BroadcastQueue: android.os.TransactionTooLargeException
09-08 18:23:46.633  1018  3836 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 18:23:46.633  1018  3836 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 18:23:46.633  1018  3836 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-08 18:23:46.633  1018  3836 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-08 18:23:46.633  1018  3836 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-08 18:23:46.633  1018  3836 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-08 18:23:46.633  1018  3836 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-08 18:23:46.633  1018  3836 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-08 18:23:46.633  1018  3836 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-08 18:23:46.633  1018  3836 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-08 18:23:46.633  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.633  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.633  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.633  1018  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.653  7337  7337 E Zygote  : MountEmulatedStorage()
,09-08 18:23:46.653  7337  7337 E Zygote  : v2
09-08 18:23:46.653  7337  7337 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:46.653  7337  7337 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.653  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_6909/cgroup.procs: No such file or directory
,09-08 18:23:46.653  7337  7337 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-08 18:23:46.653  1018  3836 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7337 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-08 18:23:46.653  7337  7337 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 18:23:46.653  7337  7337 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.673  7337  7337 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.673  7337  7337 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.693  7337  7337 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-08 18:23:46.693  7337  7337 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-08 18:23:46.693  7337  7337 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-08 18:23:46.703  7337  7337 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-08 18:23:46.703  7337  7337 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 18:23:46.703  7337  7337 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 18:23:46.703  7337  7337 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:46.713  1018  1031 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-08 18:23:46.713  1018  1031 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-08 18:23:46.713  1018  1031 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-08 18:23:46.713  7337  7352 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-08 18:23:46.713  1018  1031 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-08 18:23:46.713  1018  1031 I ActivityManager: Killing 6436:com.android.mms/u0a41 (adj 15): empty #21
,09-08 18:23:46.713  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-08 18:23:46.713  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.713  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.713  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.713  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.733  7354  7354 E Zygote  : MountEmulatedStorage(),
09-08 18:23:46.733  7354  7354 E Zygote  : v2
,09-08 18:23:46.733  7354  7354 I libpersona: KNOX_SDCARD checking this for 10001,
09-08 18:23:46.733  7354  7354 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:46.733  7354  7354 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:46.743  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7354 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:46.743  7354  7354 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:46.743  7354  7354 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.753  7354  7354 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.763  7354  7354 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.833  1018  1238 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-08 18:23:46.833  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.833  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.833  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.833  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.853  7371  7371 E Zygote  : MountEmulatedStorage()
,09-08 18:23:46.853  7371  7371 E Zygote  : v2
09-08 18:23:46.853  7371  7371 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:46.853  7371  7371 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.853  1018  1505 D CountryDetector: No listener is left
,09-08 18:23:46.853  7371  7371 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-08 18:23:46.853  1018  1238 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7371 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-08 18:23:46.853  1018  1238 I ActivityManager: Killing 6954:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21,
,09-08 18:23:46.863  7371  7371 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:46.863  7371  7371 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.883  7371  7371 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.883  7371  7371 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.923  7371  7371 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-08 18:23:47.063  7371  7371 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-08 18:23:47.073  7371  7371 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-08 18:23:47.083  7371  7371 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:47.083  7371  7371 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-08 18:23:47.083  7371  7371 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-08 18:23:47.083  7371  7371 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-08 18:23:47.083  1018  1493 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-08 18:23:47.083  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-08 18:23:47.083  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.083  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.083  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.093  1018  1493 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7386 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-08 18:23:47.103  1018  1493 I ActivityManager: Killing 6766:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-08 18:23:47.103  7386  7386 E Zygote  : MountEmulatedStorage()
09-08 18:23:47.103  7386  7386 I libpersona: KNOX_SDCARD checking this for 10008
09-08 18:23:47.103  7386  7386 E Zygote  : v2
09-08 18:23:47.103  7386  7386 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:47.103  7386  7386 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:47.103  7386  7386 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:47.103  7386  7386 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,09-08 18:23:47.123   318   318 I art     : Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 637us total 24.549ms
,09-08 18:23:47.123  7386  7386 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-08 18:23:47.123  7386  7386 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.143   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 632us total 16.587ms
,09-08 18:23:47.153   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.538ms
,09-08 18:23:47.183  1018  4614 I ActivityManager: Killing 6993:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-08 18:23:47.193  1018  1327 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-08 18:23:47.193  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.193  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.193  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.193  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-08 18:23:47.213  1879  1879 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 18:23:47.213  1879  2801 I iu.UploadsManager: num queued entries: 0
,09-08 18:23:47.213  1018  1522 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:47.213  1879  2801 I iu.UploadsManager: num updated entries: 0
,09-08 18:23:47.213  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
09-08 18:23:47.213  1879  2801 I iu.SyncManager: NEXT; no task
,09-08 18:23:47.213  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:47.213  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.213  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:47.223  1879  1879 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 18:23:47.223  1879  1879 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-08 18:23:47.233  2805  2805 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 18:23:47 GMT+02:00 2016
,09-08 18:23:47.233  1018  1721 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-08 18:23:47.233  1018  1721 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.233  1018  1721 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:47.233  1018  1721 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:47.233  1018  1721 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 18:23:47.233  2805  2805 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-08 18:23:47.243  1018  1327 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-08 18:23:47.243  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.243  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.243  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.243  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.243  2805  2805 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-08 18:23:47.243  2805  2805 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 18:23:47.243  2805  2805 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-08 18:23:47.253  7403  7403 E Zygote  : MountEmulatedStorage()
09-08 18:23:47.253  7403  7403 E Zygote  : v2
09-08 18:23:47.253  7403  7403 I libpersona: KNOX_SDCARD checking this for 10031
09-08 18:23:47.253  7403  7403 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:47.253  7403  7403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:47.253  1018  1327 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7403 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-08 18:23:47.253  7403  7403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:47.253  7403  7403 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:47.263  2805  7402 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
09-08 18:23:47.263  2805  7402 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-08 18:23:47.263  2805  7402 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-08 18:23:47.263  2805  7402 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-08 18:23:47.263  2805  2805 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-08 18:23:47.273  7403  7403 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:47.273  7403  7403 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.303  7403  7403 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-08 18:23:47.303  1018  4614 I ActivityManager: Killing 7030:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-08 18:23:47.323  1018  3274 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-08 18:23:47.323  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.323  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.323  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.323  1018  3274 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.333  2742  7418 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-08 18:23:47.333  2742  7418 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-08 18:23:47.333  7419  7419 E Zygote  : MountEmulatedStorage()
09-08 18:23:47.333  7419  7419 E Zygote  : v2
09-08 18:23:47.333  7419  7419 I libpersona: KNOX_SDCARD checking this for 10032
09-08 18:23:47.333  7419  7419 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:47.333  7419  7419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:47.333  1018  3274 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7419 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:47.343  7419  7419 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:47.343  2742  7418 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-08 18:23:47.343  7419  7419 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-08 18:23:47.343  2742  7418 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-08 18:23:47.343  2742  7418 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
,09-08 18:23:47.363  7419  7419 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:47.363  7419  7419 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.413  7419  7434 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-08 18:23:47.413  7419  7434 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-08 18:23:47.413  7419  7434 D SPPClientService: PushLog.txt file is not deleted.
,09-08 18:23:47.413  7419  7434 D SPPClientService: PushLog.txt file is not deleted.
,09-08 18:23:47.413  7419  7434 D SPPClientService: ============PushLog. stop!
,09-08 18:23:47.423  7419  7419 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-08 18:23:47.423  1018  1493 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-08 18:23:47.423  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.423  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.423  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.423  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.443  7436  7436 E Zygote  : MountEmulatedStorage()
,09-08 18:23:47.443  7436  7436 E Zygote  : v2
09-08 18:23:47.443  7436  7436 I libpersona: KNOX_SDCARD checking this for 10036
09-08 18:23:47.443  7436  7436 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:47.443  7436  7436 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 18:23:47.443  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-08 18:23:47.443  1018  1493 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7436 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:47.443  7436  7436 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:47.443  1018  1493 I ActivityManager: Killing 7056:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21,
,09-08 18:23:47.443  1018  1505 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-08 18:23:47.443  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-08 18:23:47.453  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:47.453  1018  1505 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-08 18:23:47.453  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-08 18:23:47.453  7436  7436 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-08 18:23:47.473  7436  7436 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:47.473  7436  7436 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.483  7419  7443 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-08 18:23:47.513  7436  7436 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@228ba6ab
,09-08 18:23:47.533  7436  7436 I SA      : [SSP] onCreated
,09-08 18:23:47.543  7436  7436 I SA      : [TPM] There is no property file
,09-08 18:23:47.543  7436  7436 I SA      : [SCU] isHaveSA() - false
,09-08 18:23:47.543  7436  7436 I SA      : [TPM] getModelProperty : null
,09-08 18:23:47.553  7436  7436 I SA      : [TPM] getCSCProperty : null
,09-08 18:23:47.553  7436  7436 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-08 18:23:47.553  7436  7436 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,09-08 18:23:47.553  7436  7436 I SA      : [DM] TFT FEATURE: false
,09-08 18:23:47.553  7436  7436 I SA      : [DM] init START
,09-08 18:23:47.563  7436  7436 I SA      : [DM] This device is not a Vodafone
,09-08 18:23:47.563  7436  7436 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-08 18:23:47.563  7436  7436 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-08 18:23:47.563  7436  7436 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-08 18:23:47.573  7436  7436 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-08 18:23:47.573  7436  7436 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-08 18:23:47.573  7436  7436 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-08 18:23:47.573  7436  7436 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-08 18:23:47.573  7436  7436 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-08 18:23:47.573  7436  7436 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-08 18:23:47.573  7436  7436 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-08 18:23:47.583  7436  7436 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-08 18:23:47.583  7436  7436 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-08 18:23:47.583  7436  7436 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-08 18:23:47.583  7436  7436 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-08 18:23:47.583  7436  7436 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-08 18:23:47.583  7436  7436 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-08 18:23:47.583  7436  7436 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-08 18:23:47.583  7436  7436 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-08 18:23:47.593  7436  7436 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-08 18:23:47.593  7436  7436 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-08 18:23:47.593  7436  7436 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-08 18:23:47.593  7436  7436 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-08 18:23:47.593  7436  7436 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-08 18:23:47.593  7436  7436 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-08 18:23:47.593  7436  7436 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-08 18:23:47.593  7436  7436 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-08 18:23:47.593  7436  7436 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-08 18:23:47.603  7436  7436 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-08 18:23:47.603  7436  7436 I SA      : [SCU] isHaveSA() - false
,09-08 18:23:47.603  7436  7436 I SA      : support phone number id : false
,09-08 18:23:47.603  7436  7436 I SA      : [DM] Supports Ref Jpn : true
,09-08 18:23:47.603  7436  7436 I SA      : [DM] init END
,09-08 18:23:47.603  7436  7436 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-08 18:23:47.613  7436  7436 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,09-08 18:23:47.613  7436  7436 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==,
09-08 18:23:47.613   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:23:47.623  7436  7436 I SA      : [SLFUCHKMGR] constructor called
,09-08 18:23:47.623  7436  7436 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-08 18:23:47.623  7436  7436 I SA      : [OR] == isSIMCardReady false ==
,09-08 18:23:47.633  7436  7436 I SA      : [SCU] == networkStateCheck == false
,09-08 18:23:47.633  7436  7436 I SA      : [OR] onReceive END
,09-08 18:23:47.633  1018  1542 I ActivityManager: Killing 7074:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-08 18:23:47.633  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:47.643  1797  1797 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 18:23:47.653  2544  6325 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-08 18:23:47.653  1797  1797 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-08 18:23:47.653  1797  1797 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-08 18:23:47.653  1797  1797 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-08 18:23:47.663  1797  1797 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-08 18:23:47.663  1797  1797 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 18:23:47.663  1797  1797 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-08 18:23:47.663  1018  1238 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast,
,09-08 18:23:47.673  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-08 18:23:47.673  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.673  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.673  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.683  7458  7458 E Zygote  : MountEmulatedStorage()
09-08 18:23:47.683  7458  7458 E Zygote  : v2
,09-08 18:23:47.683  7458  7458 I libpersona: KNOX_SDCARD checking this for 10077
09-08 18:23:47.683  7458  7458 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:47.683  1018  1238 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7458 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:47.683  7458  7458 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:47.683  7458  7458 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 18:23:47.693  7458  7458 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-08 18:23:47.713  7458  7458 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:47.713  7458  7458 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.893  1018  1141 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-08 18:23:47.893  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.893  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.893  1018  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.893  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 18:23:47.903  1018  1493 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-08 18:23:47.903  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.903  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.903  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.903  1018  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.913  1018  1493 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7476 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:47.913  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-08 18:23:47.913  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.913  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.913  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.913  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 18:23:47.913  7476  7476 E Zygote  : MountEmulatedStorage()
09-08 18:23:47.913  7476  7476 I libpersona: KNOX_SDCARD checking this for 10110
09-08 18:23:47.913  7476  7476 E Zygote  : v2
09-08 18:23:47.913  7476  7476 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:47.913  7476  7476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:47.923  7296  7475 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 18:23:47.923  7476  7476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 18:23:47.923  7476  7476 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 18:23:47.923  1018  4614 I ActivityManager: Killing 7105:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-08 18:23:47.943  7476  7476 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:47.943  7476  7476 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:48.093  1018  1522 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-08 18:23:48.213   257   538 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-08 18:23:48.213   257   538 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:48.213  7476  7494 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-08 18:23:48.213   257   538 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-08 18:23:48.213   257   538 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:48.213  7476  7494 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-08 18:23:48.233   257   538 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-08 18:23:48.233   257   538 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:48.233  7476  7495 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-08 18:23:48.233   257   538 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-08 18:23:48.233   257   538 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:48.243  7476  7495 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-08 18:23:48.253  1018  3274 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 18:23:48.253  1018  3274 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 18:23:48.253  1018  3274 D SecContentProvider2: mCursor = null
,09-08 18:23:48.253  1018  3274 D WifiService: setWifiEnabled: true pid=6785, uid=10170
,09-08 18:23:48.253  1018  3274 W ActivityManager: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-08 18:23:48.253  1018  3274 W WifiService: Failed getting userId using ActivityManagerNative
09-08 18:23:48.253  1018  3274 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:23:48.253  1018  3274 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-08 18:23:48.253  1018  3274 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-08 18:23:48.253  1018  3274 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-08 18:23:48.253  1018  3274 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-08 18:23:48.253  1018  3274 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:23:48.253  1018  3274 D SettingsProvider: name = wifi_on
,09-08 18:23:48.263  1018  1129 E WifiHW  : ##################### set firmware type 0 #####################
,09-08 18:23:48.263  7476  7476 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 18:23:48.263  7476  7476 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 18:23:48.263  7476  7476 I GAv4    :   adb logcat -s GAv4
,09-08 18:23:48.333  7476  7476 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:23:48.333  1018  1238 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-08 18:23:48.343  7476  7476 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:23:48.343  7476  7498 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:23:48.583  1018  1721 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:48.583  1018  1721 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:48.583  1018  1721 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:48.583  1018  1721 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-08 18:23:48.593   301   301 E SMD     : DCD OFF
,09-08 18:23:48.613  1018  3274 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-08 18:23:48.613  1018  3274 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4253, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-08 18:23:48.613   330   330 I ServiceManager: Waiting for service AtCmdFwd...
09-08 18:23:48.613  1018  3274 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-08 18:23:48.613  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 18:23:48.613  1018  3274 D BatteryService: stay LED for charging
,09-08 18:23:48.613  1018  1045 D Tethering: interfaceAdded wlan0
,09-08 18:23:48.623  7476  7476 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-08 18:23:48.623  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-08 18:23:48.623  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:48.623  1018  1018 I MotionRecognitionService: Plugged
,09-08 18:23:48.623  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 18:23:48.623  1018  1132 E Tethering: No numeric data
,09-08 18:23:48.623  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 18:23:48.633  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-08 18:23:48.633  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:48.633  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
09-08 18:23:48.633  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:48.633  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:23:48.633  1440  1440 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-08 18:23:48.633  1440  1440 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-08 18:23:48.633   282   992 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-08 18:23:48.633   282   992 D SoftapController: Softap fwReload - Ok
,09-08 18:23:48.643  1018  1045 D Tethering: interfaceAdded p2p0
,09-08 18:23:48.643  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-08 18:23:48.643   282   992 D CommandListener: Setting iface cfg,
09-08 18:23:48.643   282   992 D CommandListener: Trying to bring down wlan0
09-08 18:23:48.643  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:23:48.643   282   992 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:23:48.653  1018  1129 E WifiHW  : supplicant_name : p2p_supplicant
,09-08 18:23:48.653  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 18:23:48.653  1018  1132 D Tethering: clearTetheredNotification()
09-08 18:23:48.653  1018  1132 D Tethering: InitialState.processMessage what=4
,09-08 18:23:48.663  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:48.663  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-08 18:23:48.663  1018  1132 E Tethering: No numeric data
09-08 18:23:48.663  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-08 18:23:48.663  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:23:48.663  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:48.663  1018  1132 D Tethering: clearTetheredNotification()
,09-08 18:23:48.663  1018  1126 V NetworkStats: performPollLocked() took 4ms
,09-08 18:23:48.663  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:48.663  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-08 18:23:48.663  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:23:48.663  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-08 18:23:48.663  1182  1182 D SViewCoverView: level :100 plugged : 2
,09-08 18:23:48.673  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-08 18:23:48.673  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:48.673  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-08 18:23:48.673  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
09-08 18:23:48.673  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:48.673  7476  7476 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6040-6043)
09-08 18:23:48.673  1182  1182 D HotspotTile: updateTetherState():false, false,
09-08 18:23:48.673  7476  7476 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-08 18:23:48.673  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:48.673  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
09-08 18:23:48.673  1182  1182 D HotspotTile: updateTetherState():false, false
09-08 18:23:48.673  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:48.673  1018  1126 V NetworkStats: performPollLocked() took 7ms
09-08 18:23:48.673  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:48.673  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:48.673  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:48.693  7476  7476 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cc6412}
09-08 18:23:48.693  7476  7476 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-08 18:23:48.693  7476  7476 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 18:23:48.703  7522  7522 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-08 18:23:48.703  7522  7522 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 18:23:48.703  7522  7522 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-08 18:23:48.713  7476  7476 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-08 18:23:48.713  7476  7476 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-08 18:23:48.723  7522  7522 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-08 18:23:48.723   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7522
09-08 18:23:48.723   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-08 18:23:48.723  7522  7522 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-08 18:23:48.723  7522  7522 I wpa_supplicant: ssSupport state is = 1
09-08 18:23:48.723  7522  7522 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-08 18:23:48.723  7522  7522 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-08 18:23:48.723  7476  7476 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 18:23:48.723   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7522
09-08 18:23:48.723   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-08 18:23:48.733  7476  7476 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-08 18:23:48.733  7476  7476 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 18:23:48.733  7476  7476 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 18:23:48.733  7476  7476 I Adreno-EGL: Local Branch: 
09-08 18:23:48.733  7476  7476 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 18:23:48.733  7476  7476 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 18:23:48.733  7476  7476 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 18:23:48.753  1018  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-08 18:23:48.763  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:23:48.763  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:48.763  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:23:48.763  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:48.763  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:48.763  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:48.763  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:48.763  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:48.763  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:48.763  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-08 18:23:48.763  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 18:23:48.763  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-08 18:23:48.763  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.763  1182  1182 D HotspotTile: onReceive : 2, 0
09-08 18:23:48.763  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:48.813  7476  7476 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 18:23:48.813  7476  7537 W cr.media: Requires BLUETOOTH permission
,09-08 18:23:48.823  7476  7476 I NSApplication: Starting up...
,09-08 18:23:48.833  1018  1327 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-08 18:23:48.833  1018  1721 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-08 18:23:48.833  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-08 18:23:48.843  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-08 18:23:48.843  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:48.843  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:48.843  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:48.853  1018  1505 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7542 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:48.853  1018  1505 I ActivityManager: Killing 7123:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-08 18:23:48.853  7542  7542 E Zygote  : MountEmulatedStorage(),
09-08 18:23:48.863  7542  7542 E Zygote  : v2
09-08 18:23:48.863  7542  7542 I libpersona: KNOX_SDCARD checking this for 10117
09-08 18:23:48.863  7542  7542 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:48.863  7542  7542 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:48.863  7542  7542 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:48.863  7542  7542 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 18:23:48.883  7542  7542 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:48.883  7542  7542 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:48.903  7542  7542 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 18:23:48.923   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-08 18:23:48.923  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-08 18:23:48.983  7522  7522 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-08 18:23:48.983  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-08 18:23:48.993  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-08 18:23:48.993   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7522
09-08 18:23:48.993   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
09-08 18:23:48.993  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-08 18:23:48.993  7522  7522 I wpa_supplicant: ssSupport state is = 1
09-08 18:23:48.993  7522  7522 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-08 18:23:48.993  7522  7522 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:23:48.993  7522  7522 E wpa_supplicant: SIM READ ERROR,
09-08 18:23:48.993  7522  7522 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:48.993  7522  7522 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:23:48.993  7522  7522 E wpa_supplicant: SIM READ ERROR
09-08 18:23:48.993  7522  7522 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 18:23:48.993  7522  7522 I wpa_supplicant: wpa_default_ap_write_once
09-08 18:23:48.993  7522  7522 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-08 18:23:48.993  7522  7522 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:48.993  7522  7522 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-08 18:23:48.993  7522  7522 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:48.993  7522  7522 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-08 18:23:49.003  7522  7522 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 18:23:49.003  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:49.003  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:49.003  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:49.143  7522  7522 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-08 18:23:49.283  1018  1238 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-08 18:23:49.283  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:49.283  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:49.283  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:49.283  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:49.303  7564  7564 E Zygote  : MountEmulatedStorage(),
09-08 18:23:49.303  7564  7564 E Zygote  : v2
09-08 18:23:49.303  7564  7564 I libpersona: KNOX_SDCARD checking this for 10121
09-08 18:23:49.303  7564  7564 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:49.303  7564  7564 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-08 18:23:49.303  7564  7564 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-08 18:23:49.303  1018  1238 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7564 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-08 18:23:49.303  1018  1238 I ActivityManager: Killing 7138:com.android.calendar/u0a131 (adj 15): empty #21
,09-08 18:23:49.313  7564  7564 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:49.333  7564  7564 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:49.333  7564  7564 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:49.353  7564  7564 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 18:23:49.353  7564  7564 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 18:23:49.353  7564  7564 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 18:23:49.363  7564  7564 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:49.373  7564  7564 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-08 18:23:49.373  7564  7564 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-08 18:23:49.373  1018  1327 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-08 18:23:49.373  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:49.373  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:49.373  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:49.373  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:49.393  1018  1327 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7581 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-08 18:23:49.393  1018  1327 I ActivityManager: Killing 7009:com.android.defcontainer/u0a3 (adj 15): empty #21
09-08 18:23:49.393  7581  7581 E Zygote  : MountEmulatedStorage()
09-08 18:23:49.393  7581  7581 I libpersona: KNOX_SDCARD checking this for 10141
09-08 18:23:49.393  7581  7581 E Zygote  : v2
09-08 18:23:49.393  7581  7581 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:49.393  7581  7581 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:49.393  7581  7581 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:49.393  7581  7581 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:49.413  7581  7581 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:49.413  7581  7581 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:49.433  7581  7581 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-08 18:23:49.433  7581  7581 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:49.433  7581  7581 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:49.433  7581  7581 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-08 18:23:49.463  7522  7522 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-08 18:23:49.463  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-08 18:23:49.483  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-08 18:23:49.483   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7522
09-08 18:23:49.483   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-08 18:23:49.483  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-08 18:23:49.483  7522  7522 I wpa_supplicant: ssSupport state is = 1
,09-08 18:23:49.483  7522  7522 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-08 18:23:49.483  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-08 18:23:49.483  1018  1327 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:49.493  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-08 18:23:49.493   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7522,
09-08 18:23:49.493   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-08 18:23:49.493  7522  7522 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-08 18:23:49.493  7522  7522 I wpa_supplicant: ssSupport state is = 1
09-08 18:23:49.493  7522  7522 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:49.493  7522  7522 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-08 18:23:49.493  7522  7522 E wpa_supplicant: SIM READ ERROR
09-08 18:23:49.493  7522  7522 I wpa_supplicant: wpa_default_ap_write_once
09-08 18:23:49.493  7522  7522 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-08 18:23:49.493  7522  7522 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 18:23:49.493  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,09-08 18:23:49.493  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:23:49.503  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 18:23:49.503  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:49.503  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:49.503  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:23:49.503  1018  3274 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:49.533  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:49.543  1018  4614 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:49.573  7522  7522 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-08 18:23:49.573  7522  7522 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-08 18:23:49.573  1018  1141 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-08 18:23:49.583  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:49.583  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:49.583  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:49.583  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:49.593  1018  1505 D RCPManagerService: exchangeData() failure , invalid userId,
,09-08 18:23:49.593  7605  7605 E Zygote  : MountEmulatedStorage()
09-08 18:23:49.593  7605  7605 E Zygote  : v2,
09-08 18:23:49.593  7605  7605 I libpersona: KNOX_SDCARD checking this for 10068
09-08 18:23:49.593  7605  7605 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:49.593  7605  7605 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:49.593  7605  7605 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:49.593  7605  7605 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-08 18:23:49.603  1018  1141 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7605 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,09-08 18:23:49.603  1018  1522 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:49.613   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:23:49.623  7605  7605 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:49.623  7605  7605 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:49.623  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:49.623  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:49.623  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:23:49.633  7522  7522 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-08 18:23:49.633  7522  7522 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-08 18:23:49.633  7522  7522 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 18:23:49.643  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-08 18:23:49.643  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-08 18:23:49.643  7522  7522 I wpa_supplicant: HOTSPOT20_ENABLE called
09-08 18:23:49.643  7522  7522 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:49.643  7522  7522 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:23:49.643  7522  7522 E wpa_supplicant: SIM READ ERROR
09-08 18:23:49.643  7522  7522 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 18:23:49.653  1018  1506 D RCPManagerService: exchangeData() failure , invalid userId
09-08 18:23:49.653  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-08 18:23:49.653  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:49.653  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:49.653  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:49.653  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:49.663  7623  7623 E Zygote  : MountEmulatedStorage()
09-08 18:23:49.663  7623  7623 E Zygote  : v2
09-08 18:23:49.663  7623  7623 I libpersona: KNOX_SDCARD checking this for 10009
09-08 18:23:49.663  7623  7623 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:49.663  7623  7623 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-08 18:23:49.673  1018  1030 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7623 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-08 18:23:49.673  1018  1030 I ActivityManager: Killing 6930:com.android.vending/u0a26 (adj 15): empty #21
09-08 18:23:49.673  1018  1030 I ActivityManager: Killing 7161:com.google.android.gms.wearable/u0a11 (adj 15): empty #22
,09-08 18:23:49.673  7605  7605 D BadgeProvider: onCreate
09-08 18:23:49.673  7623  7623 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:49.673  7605  7605 D BadgeProvider: DatabaseHelper
,09-08 18:23:49.673  7623  7623 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,09-08 18:23:49.713  7522  7522 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-08 18:23:49.723  7623  7623 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:49.723  7623  7623 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:49.743  7522  7522 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 18:23:49.743  1018  1129 D WifiConfigStore: Loading config and enabling all networks 
,09-08 18:23:49.763  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:23:49.763  1018  1129 E WifiConfigStore: Not a HS20
,09-08 18:23:49.763  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:49.773  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:49.773  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:49.773  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:49.773  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:49.773  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:49.773  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:49.773  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:49.773  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:49.773  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:49.773  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:49.773  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:49.773  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:49.773  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:49.773  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:49.773  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:49.773  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:49.773  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:49.773  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:49.773  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-08 18:23:49.773  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:49.773  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 18:23:49.783  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:49.783  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:49.783  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:49.783  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:49.783  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:49.783  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:49.783  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:49.783  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:49.783  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:49.783  1018  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-08 18:23:49.783  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:49.783  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:49.783  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-08 18:23:49.783  7522  7522 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-08 18:23:49.783  7522  7522 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-08 18:23:49.783  7522  7522 I wpa_supplicant: reset timer : RESET_TIMER 0
09-08 18:23:49.783  7522  7522 I wpa_supplicant: P2P: Current p2p state = IDLE
09-08 18:23:49.783  7522  7522 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-08 18:23:49.783  7522  7522 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-08 18:23:49.783  7522  7522 I wpa_supplicant: First Scan Start
09-08 18:23:49.783  7522  7522 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-08 18:23:49.783  1182  1182 D HotspotTile: onReceive : 3, 0
,09-08 18:23:49.793  1018  1129 D WifiNative-wlan0: Setting external_sim to 1
,09-08 18:23:49.793  1018  1129 D WifiStateMachine: Setting OUI to DA-A1-19
,09-08 18:23:49.793  1018  1129 I WifiNative-HAL: startHal
09-08 18:23:49.793  1018  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f12b88c
09-08 18:23:49.793  1018  1129 I WifiNative-HAL: Could not start hal
09-08 18:23:49.793  7296  7296 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:49.793  1018  1129 E WifiNative-wlan0: do suspend true
,09-08 18:23:49.793  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-08 18:23:49.793  1018  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-08 18:23:49.793  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,09-08 18:23:49.793   282   992 D CommandListener: Setting iface cfg
09-08 18:23:49.793   282   992 D CommandListener: Trying to bring up p2p0
09-08 18:23:49.793  1018  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 18:23:49.793  1018  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 18:23:49.793  1018  1129 E WifiNative-wlan0: invaild command id : 215
,09-08 18:23:49.793  1018  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 18:23:49.793  1018  1018 D RttService: SCAN_AVAILABLE : 3
,09-08 18:23:49.793  1018  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:49.803  1018  1128 D WifiP2pService: P2pEnablingState
09-08 18:23:49.803  1018  1152 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:49.803  1018  1152 I WifiNative-HAL: startHal
09-08 18:23:49.803  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9dfed9bc
09-08 18:23:49.803  1018  1152 I WifiNative-HAL: Could not start hal
09-08 18:23:49.803  1018  1152 E WifiScanningService: could not start HAL
,09-08 18:23:49.803  1018  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-08 18:23:49.803  1018  1128 D WifiP2pService: P2p socket connection successful
09-08 18:23:49.803  7522  7522 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-08 18:23:49.803  1018  1128 D WifiP2pService: P2pEnabledState
,09-08 18:23:49.803  7522  7522 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 18:23:49.803  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-08 18:23:49.803  7522  7522 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-08 18:23:49.803  1018  1129 E WifiStateMachine: Failed to set frequency band 0
09-08 18:23:49.803  1018  1131 E ConnectivityService: updateNetworkInfo()
,09-08 18:23:49.803  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:49.803  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:23:49.803  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:49.803  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:23:49.803  1018  1128 D WifiNative-p2p0: p2pGetDeviceAddress
,09-08 18:23:49.803  1018  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-08 18:23:49.813  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-08 18:23:49.813  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-08 18:23:49.813  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:49.813  1018  1048 D WifiDisplayController: disconnect
09-08 18:23:49.813  1018  1048 D WifiDisplayController: updateConnection
09-08 18:23:49.813  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:49.813  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:23:49.813  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:49.813  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-08 18:23:49.813  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 18:23:49.813  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-08 18:23:49.813  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-08 18:23:49.813  1018  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:23:49.813  1018  1128 D WifiP2pService: DeviceAddress: 0a:75:42
,09-08 18:23:49.813  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 18:23:49.823  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  secondary type: null
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  wps: 0
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  grpcapab: 0
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  devcapab: 0
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  status: 3
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  wfdInfo: null
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  groupownerAddress: null
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  GOdeviceName: null
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  interfaceAddress: 
09-08 18:23:49.823  1018  1048 D WifiDisplayController:  SConnectInfo : null
,09-08 18:23:49.843  1018  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-08 18:23:49.843  1018  1128 D WifiP2pService: InactiveState
,09-08 18:23:49.843  1018  1128 D WifiP2pService: InactiveState{ what=143376 }
,09-08 18:23:49.843  1018  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 18:23:49.843  7522  7522 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 18:23:49.843  1018  1128 D WifiP2pService: InactiveState{ what=143376 }
,09-08 18:23:49.843  1018  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 18:23:49.893  1018  6835 I art     : Explicit concurrent mark sweep GC freed 72759(4MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.454ms total 221.898ms
,09-08 18:23:49.913  7605  7622 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-08 18:23:49.933  7605  7614 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-08 18:23:49.933  7605  7614 D BadgeProvider: sendNotify, [notify] : null
09-08 18:23:49.933  7605  7614 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-08 18:23:49.933  7605  7614 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-08 18:23:49.933  7605  7614 D BadgeProvider: update, [UpdateCount] : 1
,09-08 18:23:49.933  1507  1507 D Launcher.Model: reloadBadges entered.
,09-08 18:23:49.953  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-08 18:23:49.953  1018  1030 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-08 18:23:49.953  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-08 18:23:49.953  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-08 18:23:49.983  1018  1542 I ActivityManager: Killing 7264:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-08 18:23:49.993  1018  4614 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:49.993  1018  4614 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:49.993  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:49.993  1018  4614 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:49.993  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:49.993  1631  1631 I Hs20UtilService: Starting #12
,09-08 18:23:49.993  1631  1674 I Hs20UtilService: Message received 5011
,09-08 18:23:49.993  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 18:23:49.993  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:49.993  7319  7319 D SecurityLogAgent: StateMachine : Current State = 1
,09-08 18:23:49.993  7319  7319 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:50.003  1018  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:50.003  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:50.003  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:50.003  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:50.003  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:50.013  1631  1631 I Hs20UtilService: Starting #13
,09-08 18:23:50.013  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:23:50.013  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:50.013  7319  7319 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:23:50.013  7319  7319 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:50.013  1631  1674 I Hs20UtilService: Message received 5011
,09-08 18:23:50.013  1018  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 18:23:50.013  1018  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 18:23:50.013  1018  1129 E WifiNative-wlan0: invaild command id : 215
,09-08 18:23:50.023  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-08 18:23:50.023  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:50.023  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:23:50.023  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:23:50.023  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:50.023  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:50.023  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:50.033  1018  1327 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-08 18:23:50.033  1018  1327 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
09-08 18:23:50.033  1018  1327 W BroadcastQueue: android.os.TransactionTooLargeException
09-08 18:23:50.033  1018  1327 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 18:23:50.033  1018  1327 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 18:23:50.033  1018  1327 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-08 18:23:50.033  1018  1327 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-08 18:23:50.033  1018  1327 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-08 18:23:50.033  1018  1327 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-08 18:23:50.033  1018  1327 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-08 18:23:50.033  1018  1327 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-08 18:23:50.033  1018  1327 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:23:50.033  1018  1327 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-08 18:23:50.033  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:50.033  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:50.033  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:50.033  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:50.043  1018  1327 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7643 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-08 18:23:50.043  7643  7643 E Zygote  : MountEmulatedStorage()
09-08 18:23:50.043  7643  7643 I libpersona: KNOX_SDCARD checking this for 10064
09-08 18:23:50.043  7643  7643 E Zygote  : v2
,09-08 18:23:50.043  7643  7643 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:50.053  7643  7643 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:50.053  7643  7643 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:23:50.053  7643  7643 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-08 18:23:50.073   318   318 I art     : Explicit concurrent mark sweep GC freed 8680(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 27.728ms
,09-08 18:23:50.073  7643  7643 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:50.073  7643  7643 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:50.083  7643  7643 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 18:23:50.093   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.927ms
,09-08 18:23:50.093  1018  1042 W libprocessgroup: failed to open /acct/uid_10064/pid_7264/cgroup.procs: No such file or directory
,09-08 18:23:50.093  7643  7643 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:50.103  7643  7643 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-08 18:23:50.113   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 789us total 16.644ms
,09-08 18:23:50.133  7643  7643 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 18:23:50.143  7281  7281 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:50.143  1018  1522 I ActivityManager: Killing 7197:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-08 18:23:50.613   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:50.923  7522  7522 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
,09-08 18:23:50.923  7522  7522 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-08 18:23:50.923  7522  7522 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-08 18:23:50.923  7522  7522 I wpa_supplicant: Trying to associate with  'G700'
09-08 18:23:50.923  7522  7522 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-08 18:23:50.923  7522  7522 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-08 18:23:50.933  1018  7621 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-08 18:23:50.953  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:50.953  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:23:51.043  7522  7522 E wpa_supplicant: Cmd 35605 not handled
09-08 18:23:51.043  7522  7522 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-08 18:23:51.043  7522  7522 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-08 18:23:51.043  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-08 18:23:51.053  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.043  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:23:51.053  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.043  7522  7522 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-08 18:23:51.053  7522  7522 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-08 18:23:51.053  7522  7522 I wpa_supplicant: Associated with F4.99.3E
09-08 18:23:51.053  7522  7522 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-08 18:23:51.053  7522  7522 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,09-08 18:23:51.053  7522  7522 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-08 18:23:51.053  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-08 18:23:51.053  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:23:51.053  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-08 18:23:51.053  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.053  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
09-08 18:23:51.053  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
,09-08 18:23:51.053  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-08 18:23:51.063  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
09-08 18:23:51.063  7522  7522 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-08 18:23:51.063  7522  7522 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-08 18:23:51.063  7522  7522 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-08 18:23:51.063  7522  7522 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
09-08 18:23:51.063  7522  7522 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:23:51.063  7522  7522 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-08 18:23:51.063  7522  7522 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-08 18:23:51.063  7522  7522 I wpa_supplicant: Blacklist: Clear (temp) 
09-08 18:23:51.063  7522  7522 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-08 18:23:51.063  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:51.063  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:23:51.073  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-08 18:23:51.073  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-08 18:23:51.073  1018  1132 E Tethering: No numeric data
09-08 18:23:51.073  1018  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-08 18:23:51.073  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 18:23:51.073  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-08 18:23:51.073  1018  1132 D Tethering: clearTetheredNotification()
09-08 18:23:51.073  1018  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,09-08 18:23:51.073  1018  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-08 18:23:51.073  1018  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-08 18:23:51.073  1018  1131 E ConnectivityService: updateNetworkInfo()
,09-08 18:23:51.083  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-08 18:23:51.083  5861  5861 D FactoryTest: Not factory mode
09-08 18:23:51.083  5861  5861 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-08 18:23:51.083  5861  5861 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-08 18:23:51.083  5861  5861 D MTPRx   : still no open session command from host, so toast
,09-08 18:23:51.083  5861  5861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-08 18:23:51.083  5861  5861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-08 18:23:51.093  5861  5861 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118461
09-08 18:23:51.093  1018  1141 E PersonaManagerService: inState():  stateMachine is null !!
09-08 18:23:51.093  1018  1141 I PersonaManagerService: PersonaId don't exist
09-08 18:23:51.093  1018  1141 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-08 18:23:51.093  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
09-08 18:23:51.093  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-08 18:23:51.093  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:51.093  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:23:51.093  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:23:51.093  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:51.093  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:51.093  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.093  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.093  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.093  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:51.093  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.093  1182  1182 D HotspotTile: updateTetherState():false, false
,09-08 18:23:51.093  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:51.093  1018  1126 V NetworkStats: performPollLocked() took 4ms
,09-08 18:23:51.103  1018  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:51.103  1018  1141 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-08 18:23:51.103  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:51.103  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:51.103  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-08 18:23:51.113  1018  1141 W ActivityManager: mDVFSHelper.acquire()
,09-08 18:23:51.133  1018  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:51.133  1018  1141 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:23:51.143   282   992 D CommandListener: Setting iface cfg
,09-08 18:23:51.143  1018  1141 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 18:23:51.143  1018  1141 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-08 18:23:51.143  1018  1141 D InputDispatcher: Focused application set to: xxxx
09-08 18:23:51.143  1018  1141 D InputDispatcher: Focus left window: 6785
,09-08 18:23:51.153  5861  5861 E MTPRx   : started activity for popup
,09-08 18:23:51.153  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-08 18:23:51.153  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101,
,09-08 18:23:51.153  1018  1129 E WifiStateMachine: Start Dhcp Watchdog 2
,09-08 18:23:51.153  1018  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-08 18:23:51.153  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
09-08 18:23:51.153  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:23:51.153  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:51.163  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:51.163  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:51.163  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 18:23:51.163  1631  1631 I Hs20UtilService: Starting #14
09-08 18:23:51.163  1631  1674 I Hs20UtilService: Message received 5007
,09-08 18:23:51.163  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:51.163  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:23:51.163  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:23:51.163  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:51.163  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:51.163  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:23:51.173  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:23:51.173  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:23:51.173  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:51.173  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:51.173  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:51.183  5861  5861 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-08 18:23:51.183  5861  5861 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-08 18:23:51.183  5861  5861 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-08 18:23:51.183  5861  5861 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:51.183  5861  5861 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:51.183  5861  5861 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 18:23:51.183  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:23:51.183  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:51.183  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 18:23:51.183  1018  1129 E WifiNative-wlan0: do suspend false
,09-08 18:23:51.183  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.183  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:51.183  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:23:51.183  1018  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-08 18:23:51.183  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.183  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.183  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.193  1018  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 18:23:51.213  5861  5861 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-08 18:23:51.223  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-08 18:23:51.223  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-08 18:23:51.223  1018  1031 D InputDispatcher: Focused application set to: xxxx
,09-08 18:23:51.223  1018  1031 D InputDispatcher: Focus entered window: 6785
,09-08 18:23:51.223  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-08 18:23:51.223  1018  6835 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-08 18:23:51.223  1018  6835 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@15ad579e attribute=null, token = android.os.BinderProxy@1f3f0e2f
,09-08 18:23:51.223  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 18:23:51.263  5861  5861 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-08 18:23:51.263  1018  4614 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 18:23:51.263  1018  4614 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 18:23:51.263  1018  4614 D SecContentProvider2: mCursor = null
,09-08 18:23:51.263  1018  4614 D WifiService: setWifiEnabled: false pid=6785, uid=10170
,09-08 18:23:51.263  1018  4614 D SettingsProvider: name = wifi_on
,09-08 18:23:51.273  5861  5861 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-08 18:23:51.273  5861  5861 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-08 18:23:51.273  1018  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:51.283  1018  1129 E WifiNative-wlan0: do suspend true
,09-08 18:23:51.293  6785  6785 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 18:23:51.293  6785  6785 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-08 18:23:51.293  6785  6785 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-08 18:23:51.293  6785  6785 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-08 18:23:51.303  1018  1238 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-08 18:23:51.303  1018  1238 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 18:23:51.303  1018  1238 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-08 18:23:51.303  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-08 18:23:51.303  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,09-08 18:23:51.303   282   992 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:23:51.303  1018  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-08 18:23:51.303  1018  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 18:23:51.313  1018  1131 E ConnectivityService: updateNetworkInfo()
,09-08 18:23:51.313  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:51.313  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:23:51.313  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,09-08 18:23:51.313   282   992 E Netd    : no such netId 503
,09-08 18:23:51.313  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:23:51.313  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:51.313  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:51.313  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.313  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.313  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.313  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.313  1018  1131 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-08 18:23:51.313  1018  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-08 18:23:51.313  1018  1131 V NetworkStats: updateIfacesLocked()
09-08 18:23:51.313  6785  6785 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-08 18:23:51.313  6785  6785 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-08 18:23:51.313  1018  1131 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:23:51.313  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:51.323  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:51.323  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:23:51.323  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 18:23:51.333  1018  1128 D WifiP2pService: InactiveState{ what=131204 }
,09-08 18:23:51.333  1018  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
09-08 18:23:51.333  1018  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 18:23:51.333  6785  6785 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2704ce14 time:118701
,09-08 18:23:51.333  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-08 18:23:51.333  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:51.333  1018  1131 V NetworkStats: performPollLocked() took 13ms
,09-08 18:23:51.333  6785  6785 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@18b41a50 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c43f2ae, 16908290=android.view.AbsSavedState$1@c43f2ae}, android:focusedViewId=100}]}]
09-08 18:23:51.333  6785  6785 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-08 18:23:51.333  6785  6785 V ActivityThread: updateVisibility : ActivityRecord{974a4b2 token=android.os.BinderProxy@2704ce14 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-08 18:23:51.333  6785  6785 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 18:23:51.333  6785  6785 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-08 18:23:51.333  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:23:51.333  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:51.333  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:51.333  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.333  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.333  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.333  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.333  1018  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-08 18:23:51.343  1018  7658 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:51.343  1018  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-08 18:23:51.343  1018  1131 D ConnectivityService: nai.networkMonitor.doQuit()
,09-08 18:23:51.343  1018  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-08 18:23:51.343  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:23:51.343  1018  7658 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-08 18:23:51.343  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-08 18:23:51.343  1018  1131 E ConnectivityService: updateNetworkInfo()
,09-08 18:23:51.343  1018  1327 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:51.343  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:23:51.343  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:51.343  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:51.343  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:51.343  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
,09-08 18:23:51.343  1018  1128 D WifiP2pService: P2pDisablingState
09-08 18:23:51.343  1018  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-08 18:23:51.343  1018  1152 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:51.343  1018  1128 D WifiP2pService: p2p socket connection lost
09-08 18:23:51.343  1018  1129 E WifiNative-wlan0: do suspend true
,09-08 18:23:51.343  1018  1128 D WifiP2pService: P2pDisabledState
,09-08 18:23:51.343  1018  1018 D RttService: SCAN_AVAILABLE : 1
09-08 18:23:51.343  1018  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:51.353  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 18:23:51.353  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-08 18:23:51.353  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 18:23:51.353  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 18:23:51.353  1631  1631 I Hs20UtilService: Starting #15
09-08 18:23:51.353  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:51.353  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:51.353  1631  1674 I Hs20UtilService: Message received 5007
,09-08 18:23:51.353  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-08 18:23:51.353  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false,
09-08 18:23:51.353  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:51.353  1018  1048 D WifiDisplayController: disconnect
09-08 18:23:51.353  1018  1048 D WifiDisplayController: updateConnection
09-08 18:23:51.353  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:51.353  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:23:51.353  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-08 18:23:51.353  1018  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:23:51.353  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 18:23:51.363  1018  3836 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:23:51.373  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:23:51.373  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:51.373  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 18:23:51.373  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:23:51.373  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:51.373  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-08 18:23:51.373  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:51.373  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-08 18:23:51.373  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:51.373  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 18:23:51.373  1018  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
09-08 18:23:51.373  1018  1128 D WifiP2pService: DefaultState{ what=143375 }
,09-08 18:23:51.383   282   992 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:23:51.383  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:23:51.383  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:51.383  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:51.383  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:51.383  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:23:51.383  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:51.383  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:51.383  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.383  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.383  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.383  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.383  7643  7643 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-08 18:23:51.383  7643  7643 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-08 18:23:51.383  7643  7643 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 18:23:51.393  7281  7281 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:51.393  7522  7522 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-08 18:23:51.393  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 18:23:51.403  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:23:51.403  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:51.403  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:51.403  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.403  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.403  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.403  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.403  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:51.403  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:23:51.413  7663  7663 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-08 18:23:51.413  7663  7663 I dhcpcd  : version 5.5.6 starting
,09-08 18:23:51.413  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:23:51.413  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:51.413  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:51.413  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
09-08 18:23:51.413  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:23:51.413  1182  1182 D HotspotTile: onReceive : 0, 0
09-08 18:23:51.413  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.413  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.413  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.413  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.413  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:51.413  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0),
09-08 18:23:51.413  7663  7663 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-08 18:23:51.413  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:51.423  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:51.423  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.423  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:51.423  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:51.423  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:51.423  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.423  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:51.433  1018  1522 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:51.433  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,09-08 18:23:51.443  1018  1522 W ActivityManager: userId = 0, bbcId = -10000,
09-08 18:23:51.443  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:51.443  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 18:23:51.443  1631  1631 I Hs20UtilService: Starting #16
09-08 18:23:51.443  1631  1674 I Hs20UtilService: Message received 5007
09-08 18:23:51.443  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:23:51.443  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:51.443  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:23:51.443  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:23:51.443  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:51.443  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:51.443  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:51.453  1018  6835 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:51.463  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:51.463  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:51.463  1018  6835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:51.463  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 18:23:51.463  1631  1631 I Hs20UtilService: Starting #17
,09-08 18:23:51.463  1631  1674 I Hs20UtilService: Message received 5011
,09-08 18:23:51.463  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 18:23:51.463  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:51.463  7319  7319 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:23:51.463  7319  7319 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:51.483  7663  7663 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-08 18:23:51.483  7663  7663 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-08 18:23:51.483  7663  7663 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-08 18:23:51.483  7663  7663 I dhcpcd  : bssid match
,09-08 18:23:51.483  7663  7663 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-08 18:23:51.543  7522  7522 I wpa_supplicant: Blacklist: Clear (all) ,
,09-08 18:23:51.593  7663  7663 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-08 18:23:51.603   301   301 E SMD     : DCD OFF,
,09-08 18:23:51.623   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-08 18:23:51.653  7522  7522 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-08 18:23:51.653  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:51.653  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:51.653  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:23:51.673  7522  7522 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-08 18:23:51.673  7522  7522 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-08 18:23:51.673  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.673  7522  7522 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-08 18:23:51.673  7522  7522 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-08 18:23:51.673  7522  7522 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-08 18:23:51.673  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.673  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:23:51.673  1018  1132 D Tethering: InitialState.processMessage what=4
09-08 18:23:51.683  1018  1132 E Tethering: No numeric data
09-08 18:23:51.683  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:51.683  1018  1132 D Tethering: clearTetheredNotification()
09-08 18:23:51.683  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.683  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:51.683  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 18:23:51.683  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.683  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:51.683  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:23:51.683  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:51.683  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:51.683  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.683  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:51.683  1182  1182 D HotspotTile: updateTetherState():false, false
,09-08 18:23:51.683  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:23:51.683  1018  1126 V NetworkStats: performPollLocked() took 4ms
,09-08 18:23:51.683  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:51.683  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:51.683  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:51.743  7663  7663 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-08 18:23:52.043  7522  7522 I wpa_supplicant: Blacklist: Clear (all) 
09-08 18:23:52.043  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:52.043  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:52.043  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 18:23:52.093  7522  7522 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-08 18:23:52.093  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:52.093  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:23:52.103  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 18:23:52.203  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-08 18:23:52.203  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-08 18:23:52.203  7296  7296 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:52.203  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-08 18:23:52.203  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:52.203  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-08 18:23:52.203  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:52.213  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:52.213  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:52.213  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:52.213  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:52.213  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-08 18:23:52.213  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:52.213  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 18:23:52.213  1182  1182 D HotspotTile: onReceive : 1, 0
09-08 18:23:52.213  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:52.223  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:52.223  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:52.223  1018  1141 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:52.223  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:52.223  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:52.223  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:52.223  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:52.233  1735  2188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:52.233  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:23:52.233  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:52.233  7319  7319 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:23:52.233  7319  7319 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-08 18:23:52.233  1631  1631 I Hs20UtilService: Starting #18
09-08 18:23:52.233  1631  1674 I Hs20UtilService: Message received 5011
,09-08 18:23:52.893   282   986 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-08 18:23:52.893  1018  1045 D Tethering: interfaceRemoved wlan0
,09-08 18:23:52.893  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-08 18:23:53.063  1018  1045 D Tethering: interfaceRemoved p2p0
09-08 18:23:53.063  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-08 18:23:53.403  1018  1096 V AlarmManager: waitForAlarm result :4
,09-08 18:23:53.413   282   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 18:23:53.413   282   988 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-08 18:23:53.433  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:53.433  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:53.433  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-08 18:23:53.803  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-08 18:23:54.113  1018  1043 W ActivityManager: mDVFSHelper.release()
,09-08 18:23:54.273  6785  7097 D BluetoothAdapter: enable(),
,09-08 18:23:54.273  1018  1493 W ActivityManager: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-08 18:23:54.283  1018  1493 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-08 18:23:54.283  1018  1493 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:23:54.283  1018  1493 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-08 18:23:54.283  1018  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256),
09-08 18:23:54.283  1018  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-08 18:23:54.283  1018  1493 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-08 18:23:54.283  1018  1493 W BluetoothManagerService: 	,at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:23:54.283  1018  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-08 18:23:54.283  1018  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:23:54.293  1018  1493 D SettingsProvider: name = bluetooth_on
,09-08 18:23:54.313  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-08 18:23:54.313  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:23:54.313  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
09-08 18:23:54.313  3209  3285 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-08 18:23:54.313  3209  3285 D BluetoothAdapterProperties: Setting state to 11
09-08 18:23:54.313  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-08 18:23:54.313  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:54.313  3209  3285 D BluetoothAdapterService: updateAdapterState state is 11
09-08 18:23:54.313  3209  3285 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:54.313  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-08 18:23:54.313  3209  3285 D BtConfig.SecureMode: isSecureModeOn:false
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-08 18:23:54.313  1018  6835 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
09-08 18:23:54.313  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10,
09-08 18:23:54.323  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:23:54.323  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-08 18:23:54.313  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 18:23:54.313  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-08 18:23:54.323  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.323  1018  6835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.323  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:54.323  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-08 18:23:54.323  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-08 18:23:54.323  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-08 18:23:54.323  3209  3209 D HeadsetService: Received start request. Starting profile...
09-08 18:23:54.323  3209  3209 D HeadsetService: start()
09-08 18:23:54.323  3209  3209 D HeadsetStateMachine: make
09-08 18:23:54.333  3209  3209 E HeadsetStateMachine: # of Max HF connection is 2
,09-08 18:23:54.343  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-08 18:23:54.343  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:54.343  1182  1182 D BluetoothTile:  getBluetoothState : 11
,09-08 18:23:54.343  1889  1889 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:54.343  1018  6835 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:54.343  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 18:23:54.343  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:54.343  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:54.343  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.353  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:54.353  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-08 18:23:54.353  1018  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.353  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.353  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.353  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.353  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.353  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.363  1018  1238 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-08 18:23:54.363  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.363  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-08 18:23:54.363  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:54.363  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-08 18:23:54.363  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.363  1018  1238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.363  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-08 18:23:54.363  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 18:23:54.363  1664  1664 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:54.363  1018  1141 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:54.363  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.363  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.363  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.363  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.373  1018  4614 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-08 18:23:54.373  1018  4614 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.373  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-08 18:23:54.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-08 18:23:54.373  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-08 18:23:54.373  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.373  1018  4614 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.373  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-08 18:23:54.373  3209  3209 I bluedroid: get_profile_interface handsfree
09-08 18:23:54.373  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.373  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.373  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.373  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.373  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.373  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-08 18:23:54.373  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:23:54.373  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-08 18:23:54.373  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-08 18:23:54.383  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.383  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.383  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.383  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 18:23:54.383  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:54.383  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:54.383  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
09-08 18:23:54.383  1018  1721 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.383  1018  1721 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.383  1018  1721 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.383  1018  1721 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.383  1018  1721 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.393  3209  3209 E DualScoManager: Dual Sco Manager already instantiated
09-08 18:23:54.393  3209  3209 I DualScoManager: Set HeadsetServiceHelper
09-08 18:23:54.393  3209  3209 D BluetoothAtMessage: createCMTIContentObservers
,09-08 18:23:54.393  1018  1030 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-08 18:23:54.393  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:54.393  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:54.393  1018  1030 D SettingsProvider: selectionArgs: false
09-08 18:23:54.393  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-08 18:23:54.393  1018  1030 D SettingsProvider: selectionArgs: 1002
09-08 18:23:54.393  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:23:54.393  3209  3285 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-08 18:23:54.393  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:54.393  1018  1030 D SettingsProvider: ret = -1
,09-08 18:23:54.393  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:54.393  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-08 18:23:54.393  3209  7696 D HeadsetStateMachine: Enter Disconnected: -2
09-08 18:23:54.393  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.393  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.393  3209  3209 D HeadsetService: mStartError = false
09-08 18:23:54.393  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:54.403  3209  3209 D A2dpService: Received start request. Starting profile...
09-08 18:23:54.403  3209  3209 D A2dpService: start()
09-08 18:23:54.403  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.403  3209  3209 I bluedroid: get_profile_interface avrcp
09-08 18:23:54.403  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.403  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.403  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:54.403  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:54.403  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:54.403  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:54.403  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:54.403  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:54.403  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-08 18:23:54.403  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 18:23:54.403  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 18:23:54.403  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-08 18:23:54.403  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 18:23:54.403  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-08 18:23:54.403  3209  3285 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-08 18:23:54.403  3209  3209 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 18:23:54.403  3209  3209 D Avrcp   : Initialize Media Controller
09-08 18:23:54.403  3209  3209 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-08 18:23:54.403  3209  3209 E Avrcp   : getActiveSessions
09-08 18:23:54.403  3209  3209 D Avrcp   : pick active media Controller
09-08 18:23:54.403  3209  3209 D Avrcp   : Get the active Media Controller 
09-08 18:23:54.403  1018  4614 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-08 18:23:54.403  3209  7696 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-08 18:23:54.403  3209  7696 D HeadsetStateMachine: map size, before remove : 0
09-08 18:23:54.403  3209  7696 D HeadsetStateMachine: map size, after remove: 0
,09-08 18:23:54.403  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:54.403  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:54.403  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:54.403  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:54.423  7698  7698 E Zygote  : MountEmulatedStorage()
09-08 18:23:54.423  7698  7698 E Zygote  : v2
09-08 18:23:54.423  7698  7698 I libpersona: KNOX_SDCARD checking this for 10055
09-08 18:23:54.423  7698  7698 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:54.423  7698  7698 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:54.423  1018  4614 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7698 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-08 18:23:54.423  7698  7698 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 18:23:54.423  7698  7698 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:54.433  3209  3209 I Avrcp   :  Updating now playing list upon AVRCP Start
09-08 18:23:54.433  3209  7697 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-08 18:23:54.433  3209  3209 D A2dpStateMachine: make
,09-08 18:23:54.433  3209  3209 I bluedroid: get_profile_interface a2dp
,09-08 18:23:54.433  3209  7707 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-08 18:23:54.433  3209  3209 E bt-btif : warning : media task started media_task_refcnt 1 
09-08 18:23:54.433  3209  3209 D A2dpService: mStartError = false
09-08 18:23:54.433  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:23:54.433  3209  3209 D HeadsetStateMachine: Try to query the phonestate on bind
,09-08 18:23:54.443  3209  7706 D A2dpStateMachine: Enter Disconnected: -2
,09-08 18:23:54.443  1459  1478 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 18:23:54.443  1459  1459 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-08 18:23:54.443  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-08 18:23:54.443  1459  1478 I Telecom : BluetoothPhoneService: Result of Message : true
,09-08 18:23:54.443  3209  3209 D HeadsetStateMachine: Proxy object connected
,09-08 18:23:54.443  3209  3209 D HidService: Received start request. Starting profile...
09-08 18:23:54.443  3209  3209 D HidService: start()
09-08 18:23:54.443  3209  3209 I bluedroid: get_profile_interface hidhost
09-08 18:23:54.443  3209  3209 D HidService: setHidService(): set to: null
09-08 18:23:54.443  3209  3209 D HidService: mStartError = false
09-08 18:23:54.443  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:23:54.443  3209  3209 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-08 18:23:54.443  3209  7696 D HeadsetStateMachine: Disconnected process message: 11
,09-08 18:23:54.443  3209  3209 D HealthService: Received start request. Starting profile...
09-08 18:23:54.443  3209  3209 D HealthService: start()
09-08 18:23:54.443  3209  7697 D BluetoothMediaBrowser: no now playing list
09-08 18:23:54.443  3209  7697 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-08 18:23:54.453  3209  3209 I bluedroid: get_profile_interface health
09-08 18:23:54.453  3209  3209 D HealthService: mStartError = false
09-08 18:23:54.453  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:23:54.453  3209  3209 D PanService: Received start request. Starting profile...
,09-08 18:23:54.453  3209  3209 D PanService: start()
09-08 18:23:54.453  3209  3209 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 18:23:54.453  3209  3209 I bluedroid: get_profile_interface pan
09-08 18:23:54.453  3209  3209 D PanService: mStartError = false
09-08 18:23:54.453  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:23:54.453  3209  3209 D HeadsetPhoneState: sendDeviceDataStateChanged
09-08 18:23:54.453  3209  3209 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-08 18:23:54.453  3209  7696 D HeadsetStateMachine: Disconnected process message: 18
,09-08 18:23:54.453  3209  3209 D BluetoothMapService: Received start request. Starting profile...
09-08 18:23:54.453  3209  3209 D BluetoothMapService: start()
,09-08 18:23:54.453  3209  3209 D BluetoothMapService: mStartError = false
09-08 18:23:54.453  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:23:54.453  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-08 18:23:54.453  3209  3209 D SapService: Received start request. Starting profile...
,09-08 18:23:54.453  3209  3209 D SapService: start()
09-08 18:23:54.453  3209  3209 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-08 18:23:54.453  3209  3209 I bluedroid: get_profile_interface sap
09-08 18:23:54.453  3209  3209 D SapService: mStartError = false
09-08 18:23:54.453  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:23:54.453  3209  3209 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-08 18:23:54.453  3209  7696 D HeadsetStateMachine: Disconnected process message: 10
09-08 18:23:54.453  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-08 18:23:54.453  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-08 18:23:54.453  3209  7696 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 18:23:54.453  3209  7696 D HeadsetStateMachine: Disconnected process message: 11
09-08 18:23:54.463  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-08 18:23:54.463  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-08 18:23:54.463  7698  7698 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:54.463  7698  7698 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:54.473  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-08 18:23:54.473  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-08 18:23:54.483  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-08 18:23:54.483  3209  3285 I bluedroid: enable
09-08 18:23:54.483  3209  3288 E bt-btif : Calling BTA_HhEnable
09-08 18:23:54.483  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-08 18:23:54.483  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-08 18:23:54.483  3209  3288 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
09-08 18:23:54.483  3209  3288 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-08 18:23:54.483  3209  3288 E BluetoothServiceJni: populateRssiValuesNative
,09-08 18:23:54.483  3209  3288 I bluedroid: getModelRssiValues
09-08 18:23:54.483  3209  3288 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-08 18:23:54.483  3209  3288 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-08 18:23:54.493  3209  3288 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-08 18:23:54.493  1018  1018 D SettingsProvider: name = bluetooth_name
,09-08 18:23:54.493  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 18:23:54.493  3209  3288 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:23:54.493  3209  3288 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:23:54.493  3209  3288 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-08 18:23:54.493  3209  3288 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-08 18:23:54.493  3209  3288 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-08 18:23:54.493  3209  3288 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-08 18:23:54.493  3209  3288 E bt-btif : JVenable fails
09-08 18:23:54.493  3209  3288 D bte_conf: Device ID record 1 : primary
09-08 18:23:54.493  3209  3288 D bte_conf:   vendorId            = 0075
09-08 18:23:54.493  3209  3288 D bte_conf:   vendorIdSource      = 0001
09-08 18:23:54.493  3209  3288 D bte_conf:   product             = 0100
09-08 18:23:54.493  3209  3288 D bte_conf:   version             = 0200
09-08 18:23:54.493  3209  3288 D bte_conf:   clientExecutableURL = 
09-08 18:23:54.493  3209  3288 D bte_conf:   serviceDescription  = 
09-08 18:23:54.493  3209  3288 D bte_conf:   documentationURL    = 
09-08 18:23:54.493  3209  3288 D bte_conf: bte_load_did_conf no section named DID2.
09-08 18:23:54.493  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-08 18:23:54.493  3209  3288 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 18:23:54.493  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-08 18:23:54.493  3209  3285 D BluetoothAdapterProperties: ScanMode =  20
09-08 18:23:54.493  3209  3285 D BluetoothAdapterProperties: State =  11
,09-08 18:23:54.493  1018  1721 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-08 18:23:54.493  3209  3285 D BluetoothAdapterProperties: Setting state to 12
09-08 18:23:54.493  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 18:23:54.503  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.503  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-08 18:23:54.503  3209  3288 D BluetoothAdapterProperties: Scan Mode:21
,09-08 18:23:54.503  1018  6835 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-08 18:23:54.503  1018  6835 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:54.503  1018  6835 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:54.503  1018  6835 D SettingsProvider: selectionArgs: false
09-08 18:23:54.503  1018  6835 D SettingsProvider: selectionArgs: 1002
09-08 18:23:54.503  1018  6835 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:54.503  1018  6835 D SettingsProvider: ret = -1
,09-08 18:23:54.503  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:54.503  3209  3285 D BluetoothAdapterService: updateAdapterState state is 12
,09-08 18:23:54.503  3209  3288 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:23:54.503  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:54.503  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:54.503  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:54.503  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:54.503  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:54.503  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:54.503  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:54.503  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:54.503  1018  6835 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.503  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.513  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.513  1018  6835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:54.513  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:54.513  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.513  7698  7698 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-08 18:23:54.523  3209  3209 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-08 18:23:54.523  3209  3209 I BluetoothPbapService: Handler(): got msg=1
09-08 18:23:54.523  1018  1141 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-08 18:23:54.523  3209  3285 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:54.523  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-08 18:23:54.523  3209  3285 D BluetoothAdapterService: starting service from this receiver
09-08 18:23:54.523  1018  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.523  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.523  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.523  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.523  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.533  1459  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.533  3209  3285 I BluetoothAdapterState: Entering On State from state = 11
,09-08 18:23:54.533  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.533  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:23:54.533  3209  7719 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-08 18:23:54.533  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.533  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:54.533  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:54.533  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:54.533  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:54.533  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:54.533  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:54.533  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:54.533  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:54.533  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.533  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.533  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:54.533  1459  1476 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:23:54.543  4726  4734 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.543  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.543  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.543  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-08 18:23:54.543  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.543  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.543  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-08 18:23:54.543  3209  7719 D BluetoothSocket: bindListen(): myUserId = 0
,09-08 18:23:54.543  4726  4734 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:23:54.543  4726  4726 D HeadsetProfile: Bluetooth service connected
09-08 18:23:54.543  1182  3516 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.543  1182  3516 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.543  3209  7719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:23:54.543  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.543  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.553  1459  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
09-08 18:23:54.553  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.553  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:23:54.553  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.553  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.553  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.553  1459  1476 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:23:54.553  7698  7698 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-08 18:23:54.553  3209  7719 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-08 18:23:54.553  3209  7719 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:23:54.553  3209  7719 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:23:54.553  3209  7719 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@da6f80f
,09-08 18:23:54.553  1459  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-08 18:23:54.553  7698  7698 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-08 18:23:54.553  7698  7698 D UserAnalysis: Create SecureDbHelper
,09-08 18:23:54.553  3209  7719 D BluetoothSocket: channel: 19
09-08 18:23:54.553  3209  7719 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-08 18:23:54.553  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.553  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:23:54.553  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.553  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.553  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.553  1459  1476 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:23:54.553  4726  4739 D Bluetoothsap: onBluetoothStateChange: up=true
09-08 18:23:54.553  4726  4739 D Bluetoothsap: Binding service...
,09-08 18:23:54.563  4726  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-08 18:23:54.563  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-08 18:23:54.563  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.563  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.563  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.563  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.563  4726  4739 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-08 18:23:54.563  4726  4726 D Bluetoothsap: BluetoothSAP Proxy object connected
09-08 18:23:54.563  4726  4726 D SapProfile: Bluetooth service connected
09-08 18:23:54.563  4726  4726 D Bluetoothsap: getConnectedDevices()
,09-08 18:23:54.563  1482  1492 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.563  7698  7698 D IntelligenceServiceApplication: onCreate()
,09-08 18:23:54.563  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.563  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:23:54.563  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.563  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.563  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.563  1482  1492 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:23:54.573  1735  1743 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.573  1735  1743 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:23:54.573  1018  1141 I ActivityManager: Killing 7219:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-08 18:23:54.573  4726  7720 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 18:23:54.573  7698  7698 D IntelligenceServiceApplication: no applications having user consent for prediction
09-08 18:23:54.573  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-08 18:23:54.573  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.573  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.573  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.573  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.573  3209  3226 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:23:54.573  3209  3226 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:23:54.573  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-08 18:23:54.583  4726  4726 D BluetoothPbap: Proxy object connected
09-08 18:23:54.583  4726  4726 D PbapServerProfile: Bluetooth service connected
,09-08 18:23:54.583  7698  7698 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-08 18:23:54.593  7698  7698 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-08 18:23:54.603   301   301 E SMD     : DCD OFF,
,09-08 18:23:54.673  1018  1047 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #11
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: android.os.DeadObjectException
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:23:54.673  1018  1047 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 18:23:54.673  1664  4296 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.673  1664  4296 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:23:54.673  4726  4734 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:23:54.683  4726  4734 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.683  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:23:54.683  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.683  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.683  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.683  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.683  3209  3358 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:23:54.683  4726  4726 D BluetoothA2dp: Proxy object connected
09-08 18:23:54.683  4726  4726 D A2dpProfile: Bluetooth service connected
,09-08 18:23:54.683  3209  3358 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.683  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:23:54.683  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.683  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.683  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.683  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.693  4726  4739 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.693  4726  4739 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.693  3209  3209 D BluetoothA2dp: Proxy object connected
09-08 18:23:54.693  3209  3209 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-08 18:23:54.693  4726  4734 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 18:23:54.693  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-08 18:23:54.693  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.693  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.693  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.693  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.693  6785  6794 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:23:54.693  6785  6794 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.693  4726  4739 D BluetoothPan: Binding service...
,09-08 18:23:54.703  4726  4726 D BluetoothMap: Proxy object connected
,09-08 18:23:54.703  4726  4726 D MapProfile: Bluetooth service connected
09-08 18:23:54.703  4726  4726 D BluetoothMap: getConnectedDevices()
,09-08 18:23:54.703  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-08 18:23:54.703  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.703  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.703  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.703  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.703  4726  4726 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:23:54.703  4726  4726 D PanProfile: Bluetooth service connected
,09-08 18:23:54.713  1482  1661 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.713  1482  1661 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.713  4726  4734 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 18:23:54.713  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-08 18:23:54.713  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.713  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.713  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:54.713  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.723  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:23:54.723  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-08 18:23:54.723  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:23:54.723  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.723  1018  1047 D BluetoothPan: Binding service...
09-08 18:23:54.723  1018  1018 D BluetoothA2dp: Proxy object connected
09-08 18:23:54.723  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-08 18:23:54.723  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-08 18:23:54.723  1459  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.723  1459  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.723  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 18:23:54.723  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-08 18:23:54.723  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.723  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-08 18:23:54.723  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:23:54.723  4726  4726 D BluetoothInputDevice: Proxy object connected
09-08 18:23:54.723  4726  4726 D HidProfile: Bluetooth service connected
,09-08 18:23:54.723  1470  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.723  1470  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.723  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-08 18:23:54.723  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-08 18:23:54.733  1459  1459 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@34867ef1, true
,09-08 18:23:54.733  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:54.733  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
09-08 18:23:54.733  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 18:23:54.733  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-08 18:23:54.733  1459  1459 D BluetoothHeadset: registerMessageListener
,09-08 18:23:54.743  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-08 18:23:54.743  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:54.743  1182  1182 D BluetoothTile:  getBluetoothState : 12
,09-08 18:23:54.743  1889  1889 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:54.743  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:54.743  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.753  3209  3226 D HeadsetService: registerMessageListener
,09-08 18:23:54.753  1018  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:54.753  3209  3226 D HeadsetService: registerMessageListener
,09-08 18:23:54.753  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:54.753  1459  1459 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-08 18:23:54.753  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-08 18:23:54.753  1018  1327 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-08 18:23:54.753  1018  3354 D SSRM:n  : SIOP:: AP = 380
09-08 18:23:54.753  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:54.753  3209  7696 D HeadsetStateMachine: Disconnected process message: 70
09-08 18:23:54.753  3209  7696 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1a46609c
,09-08 18:23:54.753  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.753  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:54.763  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-08 18:23:54.763  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-08 18:23:54.763  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-08 18:23:54.763  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:54.763  3209  7725 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-08 18:23:54.763  3209  7696 D HeadsetStateMachine: Disconnected process message: 9
09-08 18:23:54.763  3209  7696 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-08 18:23:54.763  4726  4726 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-08 18:23:54.763  4726  4726 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-08 18:23:54.763  4726  4726 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,09-08 18:23:54.763  4726  4726 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-08 18:23:54.763   296   690 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-08 18:23:54.763   296   690 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-08 18:23:54.763   296   690 V voice   : voice_set_parameters: exit with code(-2)
09-08 18:23:54.763   296   690 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-08 18:23:54.763   296   690 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-08 18:23:54.763   296   690 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-08 18:23:54.763   296   690 V audio_hw_primary: adev_set_parameters: exit
09-08 18:23:54.773  3209  7696 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-08 18:23:54.773  3209  7725 D BluetoothSocket: bindListen(): myUserId = 0
,09-08 18:23:54.773  3209  7725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:23:54.773  3209  7725 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-08 18:23:54.773  3209  7725 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:23:54.773  3209  7725 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:23:54.773  3209  7725 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@360edaa5
,09-08 18:23:54.773  3209  7725 D BluetoothSocket: channel: 5
,09-08 18:23:54.773  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:23:54.773  1018  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 18:23:54.773  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.773  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.773  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.773  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:54.783  1664  1664 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:54.793  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:54.793  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:54.793  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:54.793  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-08 18:23:54.803  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:54.803  3209  3209 D BtConfig.SecureMode: isSecureModeOn:false
,09-08 18:23:54.813  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:54.813  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.813  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.813  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.813  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.823  1018  6835 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-08 18:23:54.823  1018  6835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:54.823  1018  6835 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:54.823  1018  6835 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:54.823  1018  6835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:54.823  1018  1721 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-08 18:23:54.833  7730  7730 E Zygote  : MountEmulatedStorage()
09-08 18:23:54.833  7730  7730 E Zygote  : v2
09-08 18:23:54.833  7730  7730 I libpersona: KNOX_SDCARD checking this for 10105
09-08 18:23:54.833  7730  7730 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:54.843  7730  7730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:23:54.843  7730  7730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:23:54.843  7730  7730 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-08 18:23:54.843  1018  6835 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7730 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,09-08 18:23:54.843  3209  7733 D BluetoothSocket: bindListen(): myUserId = 0
09-08 18:23:54.853  3209  7733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:23:54.853  3209  7733 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
09-08 18:23:54.853  3209  7733 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:23:54.853  3209  7733 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:23:54.853  3209  7733 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11b77c21
,09-08 18:23:54.853  3209  7733 D BluetoothSocket: channel: 12
09-08 18:23:54.853  3209  7733 I BtOppRfcommListener: Accept thread started.
,09-08 18:23:54.873  7730  7730 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:54.873  7730  7730 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:54.993   257   538 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-08 18:23:54.993   257   538 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:54.993  7730  7749 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-08 18:23:54.993   257   538 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-08 18:23:54.993   257   538 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:55.003  7730  7749 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-08 18:23:55.133  7730  7730 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-08 18:23:55.133  7730  7730 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:55.133  7730  7730 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:55.133  7730  7730 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.e.b(PG:170)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:55.133  7730  7730 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.k.d(PG:583)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.e.b(PG:170)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:55.133  7730  7730 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:55.133  7730  7730 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:55.133  1018  1238 I ActivityManager: Killing 7337:com.sec.pcw.device/1000 (adj 15): empty #21
09-08 18:23:55.133  7730  7730 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:55.133  7730  7730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-08 18:23:55.193  7730  7760 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 18:23:55.223  1018  1542 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:55.223  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:55.223  1018  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:55.223  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-08 18:23:56.313  1018  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 18:23:56.623   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:57.313  6785  7097 D BluetoothAdapter: disable()
,09-08 18:23:57.313  1018  1506 D SettingsProvider: name = bluetooth_on
,09-08 18:23:57.323  3209  3285 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-08 18:23:57.323  3209  3285 D BluetoothAdapterProperties: Setting state to 13
09-08 18:23:57.323  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 18:23:57.323  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:57.323  1018  3274 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.323  3209  3285 D BluetoothAdapterService: updateAdapterState state is 13
09-08 18:23:57.323  1018  3274 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-08 18:23:57.323  1018  3274 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.323  1018  3274 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.323  1018  3274 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.323  3209  3209 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-08 18:23:57.323  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15781846, channel: 19, state: LISTENING
09-08 18:23:57.323  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15781846, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@da6f80f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7abda07mSocket: android.net.LocalSocket@9042734 impl:android.net.LocalSocketImpl@20eeb95d fd:FileDescriptor[80]
09-08 18:23:57.323  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@9042734 impl:android.net.LocalSocketImpl@20eeb95d fd:FileDescriptor[80]
,09-08 18:23:57.333  3209  3285 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:57.333  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-08 18:23:57.333  3209  3285 D BluetoothAdapterService: terminating service from this receiver
,09-08 18:23:57.333  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-08 18:23:57.333  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,09-08 18:23:57.333  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-08 18:23:57.343  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 18:23:57.343  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:57.343  1182  1182 D BluetoothTile:  getBluetoothState : 13
,09-08 18:23:57.343  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:57.343  1889  1889 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:57.343  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:57.353  1018  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:57.353  1018  1505 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false,
,09-08 18:23:57.353  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-08 18:23:57.353  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:57.353  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:57.353  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:57.353  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:57.353  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:57.353  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:57.353  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:57.353  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:57.353  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:57.353  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:57.353  1018  4614 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.353  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d0d72d2, channel: 5, state: LISTENING
09-08 18:23:57.353  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d0d72d2, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@360edaa5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@38220fa3mSocket: android.net.LocalSocket@25682a0 impl:android.net.LocalSocketImpl@2628e59 fd:FileDescriptor[82]
09-08 18:23:57.353  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25682a0 impl:android.net.LocalSocketImpl@2628e59 fd:FileDescriptor[82]
,09-08 18:23:57.353  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-08 18:23:57.363  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:57.363  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:57.363  3209  3209 I BtOppRfcommListener: stopping Accept Thread
09-08 18:23:57.363  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d2bea1e, channel: 12, state: LISTENING
09-08 18:23:57.363  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d2bea1e, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11b77c21, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e3c02ffmSocket: android.net.LocalSocket@38b128cc impl:android.net.LocalSocketImpl@37a4b715 fd:FileDescriptor[87]
09-08 18:23:57.363  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@38b128cc impl:android.net.LocalSocketImpl@37a4b715 fd:FileDescriptor[87]
09-08 18:23:57.363  3209  7733 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:57.363  3209  7733 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-08 18:23:57.363  1018  4614 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:57.363  1018  4614 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.363  1018  4614 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.363  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:23:57.363  3209  3285 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 18:23:57.363  3209  3285 D BluetoothAdapterProperties: mDiscovering is false
09-08 18:23:57.363  1018  1327 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-08 18:23:57.363  1018  1238 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-08 18:23:57.363  3209  3285 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-08 18:23:57.363  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-08 18:23:57.363  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.363  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.363  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:57.373  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:57.373  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:57.373  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:57.373  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:57.373  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:57.373  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:57.373  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:57.373  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:57.373  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:57.373  6785  6785 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:57.373  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:57.383  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 18:23:57.383  3209  3288 D BluetoothAdapterProperties: Scan Mode:20
,09-08 18:23:57.383  4726  4726 D BluetoothPbap: Proxy object disconnected
,09-08 18:23:57.383  4726  4726 D PbapServerProfile: Bluetooth service disconnected
09-08 18:23:57.383  1664  1664 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:57.383  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-08 18:23:57.383  3209  3285 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-08 18:23:57.383  3209  3285 E bt-btif : cmd socket is not created
09-08 18:23:57.383  3209  3285 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 18:23:57.383  3209  3289 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-08 18:23:57.393  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:57.403  3209  3209 V BluetoothOppManager: cleanUp...
09-08 18:23:57.403  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:57.403  3209  3289 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:57.403  3209  3289 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:57.403  3209  3289 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:57.403  3209  3289 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:57.403  3209  3289 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:57.403  3209  3289 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-08 18:23:57.403  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:57.403  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:57.403  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:57.403  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-08 18:23:57.593  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-08 18:23:57.593  3209  3285 D BtConfig.SecureMode: isSecureModeOn:false
09-08 18:23:57.593  3209  3285 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-08 18:23:57.593  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-08 18:23:57.593  3209  3285 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-08 18:23:57.593  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-08 18:23:57.593  1018  1238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.593  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 18:23:57.593  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-08 18:23:57.593  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-08 18:23:57.593  1018  1238 W ActivityManager: userId = 0, bbcId = -10000,
09-08 18:23:57.593  1018  1238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:57.593  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.593  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-08 18:23:57.593  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-08 18:23:57.593  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-08 18:23:57.593  1018  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:57.593  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.603  3209  3209 D HeadsetService: Received stop request...Stopping profile...
,09-08 18:23:57.603  1018  1327 W ActivityManager: userId = 0, bbcId = -10000,
09-08 18:23:57.603  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:57.603  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.603   301   301 E SMD     : DCD OFF
,09-08 18:23:57.603  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:23:57.603  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-08 18:23:57.603  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:57.603  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-08 18:23:57.603  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1,
09-08 18:23:57.603  1018  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.603  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.613  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.613  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.613  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:57.613  4726  4726 D HeadsetProfile: Bluetooth service disconnected
09-08 18:23:57.613  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-08 18:23:57.613  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 18:23:57.613  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-08 18:23:57.613  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.613  3209  3209 D A2dpService: Received stop request...Stopping profile...
09-08 18:23:57.613  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.613  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.613  3209  7706 D A2dpStateMachine: Exit Disconnected: -1
09-08 18:23:57.613  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.613  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.613  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-08 18:23:57.613  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:23:57.613  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-08 18:23:57.613  1018  6835 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.613  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.613  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:23:57.613  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.613  1018  6835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:57.613  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.613  1018  1018 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:57.613  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-08 18:23:57.623  4726  4726 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:57.623  4726  4726 D A2dpProfile: Bluetooth service disconnected
,09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:57.623  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:57.623   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:57.623  1018  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:57.623  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.623  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.623  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.623  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-08 18:23:57.623  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-08 18:23:57.623  1018  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:57.623  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-08 18:23:57.623  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.623  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.623  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:57.623  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:57.623  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-08 18:23:57.623  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-08 18:23:57.623  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 18:23:57.623  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-08 18:23:57.623  3209  3285 D BluetoothAdapterState: Stopping profile services that were post enabled
09-08 18:23:57.623  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-08 18:23:57.623  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:57.623  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-08 18:23:57.633  3209  3209 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 18:23:57.633  3209  3209 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 18:23:57.633  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-08 18:23:57.633  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:57.633  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-08 18:23:57.633  3209  3209 D HidService: Received stop request...Stopping profile...
,09-08 18:23:57.633  3209  3209 D HidService: Stopping Bluetooth HidService
09-08 18:23:57.633  3209  3209 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 18:23:57.633  3209  3209 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-08 18:23:57.633  3209  3209 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 18:23:57.633  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:57.633  3209  3209 D HealthService: Received stop request...Stopping profile...
,09-08 18:23:57.633  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:57.633  4726  4726 D BluetoothInputDevice: Proxy object disconnected
09-08 18:23:57.633  4726  4726 D HidProfile: Bluetooth service disconnected
,09-08 18:23:57.633  3209  3209 D PanService: Received stop request...Stopping profile...
,09-08 18:23:57.633  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:57.633  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-08 18:23:57.633  3209  3209 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:57.633  3209  3209 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-08 18:23:57.633  3209  7707 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-08 18:23:57.633  3209  3209 I GKI_LINUX: GKI_exit_task 2 done
09-08 18:23:57.633  3209  3209 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-08 18:23:57.633  4726  4726 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-08 18:23:57.633  4726  4726 D PanProfile: Bluetooth service disconnected
09-08 18:23:57.643  3209  3209 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 18:23:57.643  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:57.643  3209  3209 D SapService: Received stop request...Stopping profile...
09-08 18:23:57.643  3209  3209 D SapService: Stopping Bluetooth SapService
09-08 18:23:57.643  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:23:57.643  4726  4726 D BluetoothMap: Proxy object disconnected
09-08 18:23:57.643  4726  4726 D MapProfile: Bluetooth service disconnected
,09-08 18:23:57.643  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-08 18:23:57.643  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-08 18:23:57.643  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.643  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.643  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-08 18:23:57.643  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-08 18:23:57.643  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.643  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.643  3209  3209 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 18:23:57.643  3209  3209 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-08 18:23:57.643  4726  4726 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-08 18:23:57.643  4726  4726 D SapProfile: Bluetooth service disconnected
09-08 18:23:57.643  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-08 18:23:57.643  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-08 18:23:57.643  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.643  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:57.643  3209  3209 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 18:23:57.643  3209  3209 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 18:23:57.653  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-08 18:23:57.653  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-08 18:23:57.653  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-08 18:23:57.653  3209  3209 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-08 18:23:57.653  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-08 18:23:57.653  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-08 18:23:57.653  3209  3209 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-08 18:23:57.653  3209  3209 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-08 18:23:57.653  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-08 18:23:57.653  3209  3285 D BluetoothAdapterProperties: Setting state to 10
09-08 18:23:57.653  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-08 18:23:57.653  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:57.653  3209  3285 D BluetoothAdapterService: updateAdapterState state is 10
,09-08 18:23:57.653  3209  3285 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:57.653  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-08 18:23:57.653  3209  3285 I BluetoothAdapterState: Entering OffState
,09-08 18:23:57.663  1182  1209 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:57.663  1182  1209 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.663  7730  7742 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:57.663  7730  7742 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.663  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:57.663  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.663  4726  4734 D Bluetoothsap: onBluetoothStateChange: up=false
,09-08 18:23:57.663  4726  4734 D Bluetoothsap: Unbinding service...
,09-08 18:23:57.663  1735  1750 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.663  1735  1750 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.663  4726  4739 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 18:23:57.663  3209  7723 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:57.663  3209  7723 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.673  1664  2207 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.673  1664  2207 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.673  4726  7720 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:57.673  3209  3222 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:57.673  4726  4734 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:57.673  4726  4734 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.673  4726  4739 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 18:23:57.673  6785  6794 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:57.673  6785  6794 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.673  6785  6794 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-08 18:23:57.673  6785  6794 D BluetoothLeAdvertiser: Exit stop advertising
,09-08 18:23:57.673  6785  6794 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-08 18:23:57.673  6785  6794 D BluetoothLeScanner: Exiting stopAllScan
,09-08 18:23:57.673  1482  2482 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:57.673  1482  2482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.673  4726  4734 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 18:23:57.673  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:57.683  1459  7766 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:57.683  1459  7766 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.683  1470  1486 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.683  1470  1486 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.683  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:57.683  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
09-08 18:23:57.683  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 18:23:57.693  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:57.693  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-08 18:23:57.693  1889  1889 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-08 18:23:57.693  1182  1182 D BluetoothTile:  getBluetoothState : 10
,09-08 18:23:57.693  1018  1493 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:57.693  1018  3836 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 18:23:57.693  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:57.693  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:57.703  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:57.703  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:57.703  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:23:57.703  1018  1238 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-08 18:23:57.703  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.703  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.703  1018  1238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.703  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:57.713  1664  1664 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:57.713  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 18:23:57.713  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:57.723  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:57.733  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:57.733  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-08 18:23:58.623   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:58.673  1018  1493 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-08 18:23:58.673  1018  1493 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-08 18:23:58.673  1018  1493 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-08 18:23:58.673  1018  1493 D BatteryService: stay LED for charging
09-08 18:23:58.673  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-08 18:23:58.673  1018  1018 I MotionRecognitionService: Plugged
09-08 18:23:58.673  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 18:23:58.683  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-08 18:23:58.683  1440  1440 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,09-08 18:23:58.683  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
09-08 18:23:58.683  1440  1440 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-08 18:23:58.703  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-08 18:23:58.703  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:23:58.703  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:23:58.703  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-08 18:23:58.703  1182  1182 D SViewCoverView: level :100 plugged : 2
,09-08 18:23:59.623   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:59.993  1018  1096 V AlarmManager: waitForAlarm result :8
,09-08 18:24:00.323  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop,
09-08 18:24:00.323  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:00.603   301   301 E SMD     : DCD OFF,
,09-08 18:24:00.623   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:24:01.623   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-08 18:24:03.333  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:03.333  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d73884f added. We now have 6 listener(s)
09-08 18:24:03.333  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:03.333  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:03.333  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29d34bdc added. We now have 7 listener(s)
,09-08 18:24:03.333  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:03.333  6785  7097 I System.out: IsBluetoothEnabled
,09-08 18:24:03.333  6785  7097 D BluetoothAdapter: disable()
,09-08 18:24:03.343  1018  1505 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-08 18:24:03.343  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:03.343  6785  7097 D BluetoothAdapter: enable()
,09-08 18:24:03.353  1018  3836 W ActivityManager: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-08 18:24:03.353  1018  3836 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-08 18:24:03.353  1018  3836 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:24:03.353  1018  3836 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-08 18:24:03.353  1018  3836 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-08 18:24:03.353  1018  3836 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-08 18:24:03.353  1018  3836 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-08 18:24:03.353  1018  3836 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:24:03.353  1018  3836 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-08 18:24:03.353  1018  3836 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:24:03.353  1018  3836 D SettingsProvider: name = bluetooth_on
,09-08 18:24:03.363  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:24:03.363  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:24:03.363  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-08 18:24:03.373  3209  3285 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-08 18:24:03.373  3209  3285 D BluetoothAdapterProperties: Setting state to 11
09-08 18:24:03.373  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-08 18:24:03.373  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:24:03.373  3209  3285 D BluetoothAdapterService: updateAdapterState state is 11
,09-08 18:24:03.373  3209  3285 D BluetoothAdapterService: Autoconnection is available 
09-08 18:24:03.373  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-08 18:24:03.373  3209  3285 D BtConfig.SecureMode: isSecureModeOn:false
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.373  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.373  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-08 18:24:03.373  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp,.HeadsetService
09-08 18:24:03.373  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-08 18:24:03.373  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 18:24:03.373  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:03.373  1182  1182 D BluetoothTile:  getBluetoothState : 11
,09-08 18:24:03.383  1889  1889 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:24:03.383  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
09-08 18:24:03.383  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-08 18:24:03.383  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:03.383  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:03.393  1018  1141 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:24:03.393  1018  3836 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-08 18:24:03.393  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-08 18:24:03.393  1018  1238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.393  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.393  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.393  1018  1238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.393  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.393  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-08 18:24:03.393  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-08 18:24:03.393  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-08 18:24:03.393  1018  1542 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:24:03.393  1018  1542 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.403  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.403  1018  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.403  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.403  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-08 18:24:03.403  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
09-08 18:24:03.403  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-08 18:24:03.403  3209  3209 D HeadsetService: Received start request. Starting profile...
09-08 18:24:03.403  3209  3209 D HeadsetService: start(),
09-08 18:24:03.403  3209  3209 D HeadsetStateMachine: make
09-08 18:24:03.403  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.403  3209  3209 E HeadsetStateMachine: # of Max HF connection is 2
,09-08 18:24:03.403  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-08 18:24:03.403  1664  1664 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:24:03.413  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.413  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.413  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:24:03.413  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-08 18:24:03.413  1018  1505 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-08 18:24:03.413  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 18:24:03.413  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-08 18:24:03.413  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-08 18:24:03.413  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.413  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.413  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-08 18:24:03.423  1018  1522 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-08 18:24:03.423  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.423  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.423  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.423  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-08 18:24:03.423  3209  3209 I bluedroid: get_profile_interface handsfree
,09-08 18:24:03.423  1018  3274 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.423  1018  3274 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.423  1018  3274 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.423  1018  3274 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.423  1018  3274 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.423  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-08 18:24:03.423  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:24:03.423  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-08 18:24:03.433  3209  3209 E DualScoManager: Dual Sco Manager already instantiated
,09-08 18:24:03.433  3209  3209 I DualScoManager: Set HeadsetServiceHelper
09-08 18:24:03.433  3209  3209 D BluetoothAtMessage: createCMTIContentObservers
09-08 18:24:03.433  1018  3836 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-08 18:24:03.433  1018  3836 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.433  1018  3836 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.433  1018  3836 D SettingsProvider: selectionArgs: false
09-08 18:24:03.433  1018  3836 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.433  1018  3836 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.433  1018  3836 D SettingsProvider: ret = -1
09-08 18:24:03.433  3209  7774 D HeadsetStateMachine: Enter Disconnected: -2
09-08 18:24:03.443  3209  3209 D HeadsetService: mStartError = false
09-08 18:24:03.443  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:24:03.443  3209  3209 D A2dpService: Received start request. Starting profile...
09-08 18:24:03.443  1018  1141 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.443  3209  3209 D A2dpService: start()
09-08 18:24:03.443  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-08 18:24:03.443  3209  3209 I bluedroid: get_profile_interface avrcp
09-08 18:24:03.443  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:24:03.443  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.443  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.443  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.443  3209  3209 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 18:24:03.443  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 18:24:03.443  3209  3209 D Avrcp   : Initialize Media Controller
09-08 18:24:03.443  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:24:03.443  3209  3209 D Avrcp   : Get the Context Package Name: com.android.bluetooth
09-08 18:24:03.443  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-08 18:24:03.443  1018  1721 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.443  1018  1721 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-08 18:24:03.443  3209  3209 E Avrcp   : getActiveSessions
09-08 18:24:03.443  3209  3209 D Avrcp   : pick active media Controller
09-08 18:24:03.443  3209  3209 D Avrcp   : Get the active Media Controller 
,09-08 18:24:03.453  1018  1721 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.453  1018  1721 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.453  1018  1721 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:24:03.453  3209  7774 D HeadsetStateMachine: Clear mHeadsetBrsf,
09-08 18:24:03.453  3209  7774 D HeadsetStateMachine: map size, before remove : 0
09-08 18:24:03.453  3209  7774 D HeadsetStateMachine: map size, after remove: 0
,09-08 18:24:03.453  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-08 18:24:03.453  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:24:03.453  3209  3285 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-08 18:24:03.453  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:03.453  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-08 18:24:03.463  3209  3209 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-08 18:24:03.463  3209  7775 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-08 18:24:03.463  3209  3209 D A2dpStateMachine: make
,09-08 18:24:03.463  3209  3209 I bluedroid: get_profile_interface a2dp
,09-08 18:24:03.463  3209  7777 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-08 18:24:03.463  3209  3209 E bt-btif : warning : media task started media_task_refcnt 1 
,09-08 18:24:03.463  3209  3209 D A2dpService: mStartError = false
09-08 18:24:03.463  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:24:03.463  3209  7776 D A2dpStateMachine: Enter Disconnected: -2
,09-08 18:24:03.463  3209  3209 D HidService: Received start request. Starting profile...
09-08 18:24:03.463  3209  3209 D HidService: start()
09-08 18:24:03.463  3209  3209 I bluedroid: get_profile_interface hidhost
09-08 18:24:03.463  3209  3209 D HidService: setHidService(): set to: null
09-08 18:24:03.463  3209  3209 D HidService: mStartError = false
09-08 18:24:03.463  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:24:03.463  3209  3209 D HeadsetStateMachine: Try to query the phonestate on bind
09-08 18:24:03.463  1018  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.463  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.463  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.463  1459  7721 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 18:24:03.463  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.463  1459  1459 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-08 18:24:03.463  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-08 18:24:03.463  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-08 18:24:03.463  3209  3209 D HeadsetStateMachine: Proxy object connected
09-08 18:24:03.463  1459  7721 I Telecom : BluetoothPhoneService: Result of Message : true
09-08 18:24:03.463  3209  3209 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-08 18:24:03.473  3209  7774 D HeadsetStateMachine: Disconnected process message: 11
09-08 18:24:03.473  3209  3209 D HealthService: Received start request. Starting profile...
09-08 18:24:03.473  3209  3209 D HealthService: start()
09-08 18:24:03.473  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:24:03.473  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:24:03.473  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:24:03.473  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.473  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.473  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.473  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.473  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.473  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.473  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,09-08 18:24:03.473  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 18:24:03.473  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-08 18:24:03.473  3209  3285 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-08 18:24:03.473  3209  3209 I bluedroid: get_profile_interface health
09-08 18:24:03.473  3209  3209 D HealthService: mStartError = false
09-08 18:24:03.473  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:24:03.473  3209  3209 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-08 18:24:03.473  3209  3209 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-08 18:24:03.473  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-08 18:24:03.473  3209  3209 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 18:24:03.473  3209  7774 D HeadsetStateMachine: Disconnected process message: 18
09-08 18:24:03.473  3209  7774 D HeadsetStateMachine: Disconnected process message: 10
09-08 18:24:03.473  3209  7774 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 18:24:03.473  3209  7774 D HeadsetStateMachine: Disconnected process message: 11
09-08 18:24:03.483  3209  3209 D PanService: Received start request. Starting profile...
09-08 18:24:03.483  3209  3209 D PanService: start()
,09-08 18:24:03.483  3209  3209 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 18:24:03.483  3209  3209 I bluedroid: get_profile_interface pan
09-08 18:24:03.483  3209  3209 D PanService: mStartError = false
09-08 18:24:03.483  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:24:03.483  3209  3209 D BluetoothMapService: Received start request. Starting profile...
09-08 18:24:03.483  3209  3209 D BluetoothMapService: start()
09-08 18:24:03.483  3209  3209 D BluetoothMapService: mStartError = false
09-08 18:24:03.483  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:24:03.483  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-08 18:24:03.483  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-08 18:24:03.493  3209  7775 D BluetoothMediaBrowser: no now playing list
09-08 18:24:03.493  3209  7775 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-08 18:24:03.493  3209  3209 D SapService: Received start request. Starting profile...
09-08 18:24:03.493  3209  3209 D SapService: start()
09-08 18:24:03.493  3209  3209 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-08 18:24:03.493  3209  3209 I bluedroid: get_profile_interface sap
09-08 18:24:03.493  3209  3209 D SapService: mStartError = false
09-08 18:24:03.493  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
,09-08 18:24:03.493  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-08 18:24:03.493  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-08 18:24:03.513  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-08 18:24:03.513  3209  3209 E BluetoothAdapterService(1020794194): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-08 18:24:03.523  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-08 18:24:03.523  3209  3285 I bluedroid: enable
,09-08 18:24:03.523  3209  3288 E bt-btif : Calling BTA_HhEnable
,09-08 18:24:03.523  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-08 18:24:03.523  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-08 18:24:03.523  3209  3288 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-08 18:24:03.523  3209  3288 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-08 18:24:03.523  3209  3288 E BluetoothServiceJni: populateRssiValuesNative
09-08 18:24:03.523  3209  3288 I bluedroid: getModelRssiValues
09-08 18:24:03.523  3209  3288 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-08 18:24:03.523  3209  3288 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-08 18:24:03.533  3209  3288 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-08 18:24:03.533  1018  1018 D SettingsProvider: name = bluetooth_name
,09-08 18:24:03.533  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:03.533  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 18:24:03.533  3209  3288 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:24:03.533  3209  3288 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:24:03.533  3209  3288 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-08 18:24:03.533  3209  3288 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-08 18:24:03.533  3209  3288 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-08 18:24:03.533  3209  3288 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-08 18:24:03.533  3209  3288 E bt-btif : JVenable fails
,09-08 18:24:03.533  3209  3288 D bte_conf: Device ID record 1 : primary
09-08 18:24:03.533  3209  3288 D bte_conf:   vendorId            = 0075
09-08 18:24:03.533  3209  3288 D bte_conf:   vendorIdSource      = 0001
09-08 18:24:03.533  3209  3288 D bte_conf:   product             = 0100
09-08 18:24:03.533  3209  3288 D bte_conf:   version             = 0200
09-08 18:24:03.533  3209  3288 D bte_conf:   clientExecutableURL = 
09-08 18:24:03.533  3209  3288 D bte_conf:   serviceDescription  = 
09-08 18:24:03.533  3209  3288 D bte_conf:   documentationURL    = 
09-08 18:24:03.533  3209  3288 D bte_conf: bte_load_did_conf no section named DID2.
,09-08 18:24:03.543  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-08 18:24:03.543  3209  3285 D BluetoothAdapterProperties: ScanMode =  20
09-08 18:24:03.543  3209  3285 D BluetoothAdapterProperties: State =  11
,09-08 18:24:03.543  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-08 18:24:03.543  3209  3288 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 18:24:03.543  1018  1031 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-08 18:24:03.543  3209  3285 D BluetoothAdapterProperties: Setting state to 12
09-08 18:24:03.543  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 18:24:03.543  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 18:24:03.543  3209  3288 D BluetoothAdapterProperties: Scan Mode:21
09-08 18:24:03.543  3209  3288 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 18:24:03.543  1018  1141 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-08 18:24:03.543  1018  1141 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.543  1018  1141 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.543  1018  1141 D SettingsProvider: selectionArgs: false
09-08 18:24:03.543  1018  1141 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.543  1018  1141 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.543  1018  1141 D SettingsProvider: ret = -1
,09-08 18:24:03.543  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:24:03.543  3209  3285 D BluetoothAdapterService: updateAdapterState state is 12
,09-08 18:24:03.543  1018  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.543  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.543  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.543  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.543  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.553  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:03.553  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:03.553  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:03.553  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:03.553  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:03.553  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:03.553  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:03.553  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:03.553  3209  3285 D BluetoothAdapterService: Autoconnection is available 
09-08 18:24:03.553  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-08 18:24:03.553  3209  3285 D BluetoothAdapterService: starting service from this receiver
,09-08 18:24:03.553  1018  1141 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.553  1018  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.553  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.553  1018  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.553  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.553  1459  1478 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-08 18:24:03.553  3209  3285 I BluetoothAdapterState: Entering On State from state = 11
,09-08 18:24:03.553  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:03.553  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:03.563  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.563  3209  3209 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-08 18:24:03.563  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:24:03.563  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.563  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:03.563  1459  1478 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:24:03.563  4726  4739 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:03.573  3209  3209 I BluetoothPbapService: Handler(): got msg=1
,09-08 18:24:03.603   301   301 E SMD     : DCD OFF,
,09-08 18:24:03.713  1018  1047 I art     : Explicit concurrent mark sweep GC freed 56523(3MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 22MB/34MB, paused 2.342ms total 145.108ms
09-08 18:24:03.713  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:03.713  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:03.713  1018  1522 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-08 18:24:03.713  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.713  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.713  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.713  4726  4739 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:24:03.713  1182  1547 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:03.713  1182  1547 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:24:03.713  7730  7745 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:03.713  7730  7745 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:03.723  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:03.723  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:03.723  1459  7766 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:03.723  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:03.723  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-08 18:24:03.723  3209  7782 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-08 18:24:03.723  4726  4726 D HeadsetProfile: Bluetooth service connected
09-08 18:24:03.723  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.723  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.723  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.723  1459  7766 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:24:03.723  3209  7782 D BluetoothSocket: bindListen(): myUserId = 0
09-08 18:24:03.723  3209  7782 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:03.723  3209  7782 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-08 18:24:03.723  3209  7782 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:24:03.723  3209  7782 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:24:03.723  3209  7782 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26b01be2
09-08 18:24:03.723  3209  7782 D BluetoothSocket: channel: 19
09-08 18:24:03.723  3209  7782 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-08 18:24:03.733  1459  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:03.733  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-08 18:24:03.733  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:03.733  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.733  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.733  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.733  1459  1476 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:24:03.733  4726  7720 D Bluetoothsap: onBluetoothStateChange: up=true
09-08 18:24:03.733  4726  7720 D Bluetoothsap: Binding service...
,09-08 18:24:03.733  4726  7720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-08 18:24:03.733  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-08 18:24:03.733  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.733  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.733  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.733  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.733  4726  7720 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-08 18:24:03.733  1482  1500 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-08 18:24:03.743  4726  4726 D Bluetoothsap: BluetoothSAP Proxy object connected
09-08 18:24:03.743  4726  4726 D SapProfile: Bluetooth service connected
09-08 18:24:03.743  4726  4726 D Bluetoothsap: getConnectedDevices()
,09-08 18:24:03.743  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:03.743  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:03.743  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.743  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.743  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-08 18:24:03.743  1482  1500 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:24:03.743  1735  1750 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:03.743  1735  1750 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:24:03.743  4726  4739 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 18:24:03.743  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-08 18:24:03.743  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.743  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.743  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.743  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.743  4726  4726 D BluetoothPbap: Proxy object connected
,09-08 18:24:03.743  4726  4726 D PbapServerProfile: Bluetooth service connected
,09-08 18:24:03.753  3209  3226 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:03.753  3209  3226 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:03.753  1664  4240 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:03.753  1664  4240 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:24:03.753  4726  4734 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:24:03.753  4726  4734 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:03.753  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-08 18:24:03.753  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.753  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.753  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.753  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.753  4726  4726 D BluetoothA2dp: Proxy object connected
,09-08 18:24:03.753  4726  4726 D A2dpProfile: Bluetooth service connected
,09-08 18:24:03.753  3209  3328 D BluetoothA2dp: onBluetoothStateChange: up=true,
,09-08 18:24:03.753  3209  3328 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:03.763  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:24:03.763  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-08 18:24:03.763  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.763  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.763  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.763  4726  4739 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:03.763  4726  4739 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:24:03.763  3209  3209 D BluetoothA2dp: Proxy object connected
09-08 18:24:03.763  4726  7720 D BluetoothMap: onBluetoothStateChange: up=true
09-08 18:24:03.763  3209  3209 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-08 18:24:03.763  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-08 18:24:03.763  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.763  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.763  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.763  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.763  6785  6797 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:03.763  6785  6797 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:24:03.773  4726  4726 D BluetoothMap: Proxy object connected
09-08 18:24:03.773  4726  4726 D MapProfile: Bluetooth service connected
09-08 18:24:03.773  4726  4739 D BluetoothPan: Binding service...
09-08 18:24:03.773  4726  4726 D BluetoothMap: getConnectedDevices()
,09-08 18:24:03.773  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-08 18:24:03.773  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.773  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.773  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.773  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.773  1482  1661 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:03.773  1482  1661 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:03.773  4726  4726 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 18:24:03.773  4726  7720 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 18:24:03.773  4726  4726 D PanProfile: Bluetooth service connected
,09-08 18:24:03.773  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-08 18:24:03.773  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.773  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.773  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.773  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.773  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:24:03.773  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-08 18:24:03.773  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:24:03.773  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.783  1018  1047 D BluetoothPan: Binding service...
09-08 18:24:03.783  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-08 18:24:03.783  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.783  1018  1018 D BluetoothA2dp: Proxy object connected
09-08 18:24:03.783  1459  1478 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:03.783  1459  1478 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:03.783  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:03.783  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:03.783  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:24:03.783  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:03.783  1470  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:03.783  1470  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:03.783  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-08 18:24:03.783  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-08 18:24:03.783  4726  4726 D BluetoothInputDevice: Proxy object connected
09-08 18:24:03.783  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:24:03.783  4726  4726 D HidProfile: Bluetooth service connected
,09-08 18:24:03.783  1459  1459 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3757aad6, true
,09-08 18:24:03.793  1459  1459 D BluetoothHeadset: registerMessageListener
,09-08 18:24:03.793  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-08 18:24:03.793  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 18:24:03.793  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:03.793  1182  1182 D BluetoothTile:  getBluetoothState : 12
,09-08 18:24:03.793  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:24:03.793  1889  1889 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:24:03.803  1018  1141 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:24:03.803  1018  3836 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-08 18:24:03.803  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:24:03.803  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:24:03.803  1182  1725 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:24:03.803  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:03.813  3209  3226 D HeadsetService: registerMessageListener
,09-08 18:24:03.813  3209  3226 D HeadsetService: registerMessageListener
09-08 18:24:03.813  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:03.813  3209  7774 D HeadsetStateMachine: Disconnected process message: 70
09-08 18:24:03.813  3209  7774 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1446eb73
,09-08 18:24:03.813  1459  1459 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-08 18:24:03.813  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-08 18:24:03.813  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:03.813  3209  7784 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-08 18:24:03.813  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
09-08 18:24:03.813  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 18:24:03.823  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-08 18:24:03.823  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-08 18:24:03.823  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-08 18:24:03.823  3209  7774 D HeadsetStateMachine: Disconnected process message: 9
,09-08 18:24:03.823  3209  7774 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-08 18:24:03.823  4726  4726 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-08 18:24:03.823  3209  7784 D BluetoothSocket: bindListen(): myUserId = 0
09-08 18:24:03.823  4726  4726 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-08 18:24:03.823  4726  4726 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-08 18:24:03.823  4726  4726 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-08 18:24:03.823  3209  7784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:03.823  3209  7784 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-08 18:24:03.823  3209  7784 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:24:03.823  3209  7784 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:24:03.823  3209  7784 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@be17a30
,09-08 18:24:03.823  3209  7784 D BluetoothSocket: channel: 5
,09-08 18:24:03.833   296   296 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-08 18:24:03.833   296   296 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-08 18:24:03.833   296   296 V voice   : voice_set_parameters: exit with code(-2)
,09-08 18:24:03.833   296   296 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,09-08 18:24:03.833   296   296 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-08 18:24:03.833   296   296 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,09-08 18:24:03.833   296   296 V audio_hw_primary: adev_set_parameters: exit
,09-08 18:24:03.833  3209  7774 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-08 18:24:03.833  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:24:03.833  1018  3836 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-08 18:24:03.833  1018  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.843  1018  3836 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.843  1018  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.843  1018  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:24:03.843  1664  1664 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,09-08 18:24:03.853  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:24:03.853  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:24:03.863  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
,09-08 18:24:03.863  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-08 18:24:03.873  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd81552
09-08 18:24:03.873  3209  3209 D BtConfig.SecureMode: isSecureModeOn:false
,09-08 18:24:03.873  1018  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:24:03.873  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.873  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.873  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:24:03.873  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.883  1018  1522 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-08 18:24:03.883  3209  7789 D BluetoothSocket: bindListen(): myUserId = 0
09-08 18:24:03.883  3209  7789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:03.893  3209  7789 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
,09-08 18:24:03.893  3209  7789 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:24:03.893  3209  7789 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:24:03.893  3209  7789 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@391c095c
09-08 18:24:03.893  3209  7789 D BluetoothSocket: channel: 12
09-08 18:24:03.893  3209  7789 I BtOppRfcommListener: Accept thread started.
,09-08 18:24:04.383  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:04.383  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:04.383  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:04.383  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:04.383  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:04.383  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:04.383  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:04.383  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:04.383  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:04.383  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:04.383  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@383c84e5 added. We now have 8 listener(s)
09-08 18:24:04.383  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:04.393  1018  1505 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-08 18:24:04.393  1018  1505 D WifiService: setWifiEnabled: false pid=6785, uid=10170
09-08 18:24:04.393  1018  1505 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 18:24:04.393  1018  1505 D SecContentProvider2: mCursor = null
09-08 18:24:04.393  1018  1505 D SettingsProvider: name = wifi_on
,09-08 18:24:04.393  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:04.393  1018  1493 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 18:24:04.403  1018  1493 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-08 18:24:04.403  1018  1493 D SecContentProvider2: mCursor = null
,09-08 18:24:04.403  1018  1493 D WifiService: setWifiEnabled: true pid=6785, uid=10170
,09-08 18:24:04.403  1018  1493 W ActivityManager: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-08 18:24:04.403  1018  1493 W WifiService: Failed getting userId using ActivityManagerNative
09-08 18:24:04.403  1018  1493 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6785, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:24:04.403  1018  1493 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-08 18:24:04.403  1018  1493 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-08 18:24:04.403  1018  1493 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-08 18:24:04.403  1018  1493 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-08 18:24:04.403  1018  1493 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:24:04.403  1018  1493 D SettingsProvider: name = wifi_on
,09-08 18:24:04.413  1018  1129 E WifiHW  : ##################### set firmware type 0 #####################
,09-08 18:24:04.753  1018  1045 D Tethering: interfaceAdded wlan0
,09-08 18:24:04.763  1018  1132 E Tethering: No numeric data
,09-08 18:24:04.763  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-08 18:24:04.763  1018  1132 D Tethering: clearTetheredNotification()
,09-08 18:24:04.763  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-08 18:24:04.763  1018  1126 V NetworkStats: performPollLocked(flags=0x1),
09-08 18:24:04.773  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:24:04.773  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-08 18:24:04.773  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:24:04.773  1182  1182 D HotspotTile: updateTetherState():false, false
09-08 18:24:04.773  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-08 18:24:04.773  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:24:04.773  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:24:04.773  1018  1126 V NetworkStats: performPollLocked() took 9ms
,09-08 18:24:04.773  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:04.783  1018  1132 D Tethering: InitialState.processMessage what=4
,09-08 18:24:04.783  1018  1045 D Tethering: interfaceAdded p2p0
09-08 18:24:04.783  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:04.783  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:04.783  1018  1132 E Tethering: No numeric data
,09-08 18:24:04.793  1018  3354 D SSRM:n  : SIOP:: AP = 340
,09-08 18:24:04.793  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:24:04.793  1018  1132 D Tethering: clearTetheredNotification()
09-08 18:24:04.793  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
09-08 18:24:04.793   282   992 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-08 18:24:04.793   282   992 D SoftapController: Softap fwReload - Ok
,09-08 18:24:04.793  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:24:04.793  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
09-08 18:24:04.793  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 18:24:04.793  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:24:04.793  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:04.793   282   992 D CommandListener: Setting iface cfg
09-08 18:24:04.803   282   992 D CommandListener: Trying to bring down wlan0
09-08 18:24:04.803  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:24:04.803  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-08 18:24:04.803  1182  1182 D HotspotTile: updateTetherState():false, false
09-08 18:24:04.803  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:24:04.803   282   992 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:24:04.803  1018  1129 E WifiHW  : supplicant_name : p2p_supplicant
09-08 18:24:04.803  1018  1126 V NetworkStats: performPollLocked() took 9ms
09-08 18:24:04.803  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:04.813  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:04.813  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:04.813  1018  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-08 18:24:04.823  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:24:04.823  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:24:04.823  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-08 18:24:04.823  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:04.823  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:04.823  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:24:04.823  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:04.823  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 18:24:04.823  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:04.823  1182  1182 D HotspotTile: onReceive : 2, 0
09-08 18:24:04.823  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:24:04.823  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-08 18:24:04.833  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
09-08 18:24:04.833  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:04.833  1018  3836 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:24:04.833  1018  3836 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.833  1018  3836 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:24:04.833  1018  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.833  1018  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 18:24:04.833  1631  1631 I Hs20UtilService: Starting #19
09-08 18:24:04.833  1631  1674 I Hs20UtilService: Message received 5011
09-08 18:24:04.843  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:24:04.843  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:24:04.843  7319  7319 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:24:04.843  7319  7319 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:24:04.853  7802  7802 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-08 18:24:04.853  7802  7802 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 18:24:04.853  7802  7802 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-08 18:24:04.863  7802  7802 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-08 18:24:04.873   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7802
,09-08 18:24:04.873   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-08 18:24:04.873  7802  7802 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-08 18:24:04.873  7802  7802 I wpa_supplicant: ssSupport state is = 1
09-08 18:24:04.873  7802  7802 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,09-08 18:24:04.873  7802  7802 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-08 18:24:04.873   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7802
09-08 18:24:04.873   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-08 18:24:05.013   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-08 18:24:05.013  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-08 18:24:05.053  7802  7802 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-08 18:24:05.053  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-08 18:24:05.073  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-08 18:24:05.073   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7802
09-08 18:24:05.073   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-08 18:24:05.073  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-08 18:24:05.073  7802  7802 I wpa_supplicant: ssSupport state is = 1
09-08 18:24:05.073  7802  7802 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-08 18:24:05.073  7802  7802 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:24:05.073  7802  7802 E wpa_supplicant: SIM READ ERROR,
09-08 18:24:05.073  7802  7802 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:24:05.073  7802  7802 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-08 18:24:05.073  7802  7802 E wpa_supplicant: SIM READ ERROR
09-08 18:24:05.073  7802  7802 I wpa_supplicant: Blacklist: Clear (all) ,
09-08 18:24:05.073  7802  7802 I wpa_supplicant: wpa_default_ap_write_once
09-08 18:24:05.073  7802  7802 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-08 18:24:05.073  7802  7802 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:24:05.073  7802  7802 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-08 18:24:05.073  7802  7802 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-08 18:24:05.073  7802  7802 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-08 18:24:05.073  7802  7802 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
09-08 18:24:05.073  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-08 18:24:05.073  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:24:05.073  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:24:05.113  7802  7802 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-08 18:24:05.223  7802  7802 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-08 18:24:05.223  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-08 18:24:05.233  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-08 18:24:05.233   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7802
,09-08 18:24:05.233   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-08 18:24:05.233  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-08 18:24:05.233  7802  7802 I wpa_supplicant: ssSupport state is = 1
09-08 18:24:05.233  7802  7802 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-08 18:24:05.233  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-08 18:24:05.253  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-08 18:24:05.253   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7802
09-08 18:24:05.253   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-08 18:24:05.253  7802  7802 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-08 18:24:05.253  7802  7802 I wpa_supplicant: ssSupport state is = 1
09-08 18:24:05.253  7802  7802 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:24:05.253  7802  7802 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:24:05.253  7802  7802 E wpa_supplicant: SIM READ ERROR
09-08 18:24:05.253  7802  7802 I wpa_supplicant: wpa_default_ap_write_once
09-08 18:24:05.253  7802  7802 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-08 18:24:05.253  7802  7802 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 18:24:05.253  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:24:05.253  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 18:24:05.253  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:24:05.263  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:24:05.263  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:24:05.263  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 18:24:05.383  7802  7802 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-08 18:24:05.383  7802  7802 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-08 18:24:05.423  7802  7802 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-08 18:24:05.423  7802  7802 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-08 18:24:05.423  7802  7802 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 18:24:05.433  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-08 18:24:05.433  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-08 18:24:05.433  7802  7802 I wpa_supplicant: HOTSPOT20_ENABLE called
09-08 18:24:05.433  7802  7802 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:24:05.433  7802  7802 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:24:05.433  7802  7802 E wpa_supplicant: SIM READ ERROR
09-08 18:24:05.433  7802  7802 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 18:24:05.453  7802  7802 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-08 18:24:05.463  7802  7802 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 18:24:05.463  1018  1129 D WifiConfigStore: Loading config and enabling all networks 
,09-08 18:24:05.473  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:24:05.473  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:05.473  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:24:05.473  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:05.473  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:05.473  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-08 18:24:05.473  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:05.473  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:05.473  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:24:05.473  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-08 18:24:05.473  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:24:05.473  1182  1725 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 18:24:05.483  1182  1182 D HotspotTile: onReceive : 3, 0
,09-08 18:24:05.483  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:05.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:05.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:05.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:05.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:05.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:05.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:05.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:05.493  1018  1129 E WifiConfigStore: Not a HS20
,09-08 18:24:05.493  1018  1522 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:24:05.493  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:24:05.493  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:05.493  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:05.493  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,09-08 18:24:05.493  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:05.493  1018  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-08 18:24:05.493  1631  1631 I Hs20UtilService: Starting #20
,09-08 18:24:05.493  1631  1674 I Hs20UtilService: Message received 5011
,09-08 18:24:05.503  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-08 18:24:05.503  7802  7802 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-08 18:24:05.503  7802  7802 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-08 18:24:05.503  7802  7802 I wpa_supplicant: reset timer : RESET_TIMER 0
09-08 18:24:05.503  7802  7802 I wpa_supplicant: P2P: Current p2p state = IDLE
09-08 18:24:05.503  7802  7802 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-08 18:24:05.503  7802  7802 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-08 18:24:05.503  7802  7802 I wpa_supplicant: First Scan Start
,09-08 18:24:05.503  7802  7802 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-08 18:24:05.503  1018  1129 D WifiNative-wlan0: Setting external_sim to 1
,09-08 18:24:05.503  1018  1129 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 18:24:05.503  1018  1129 I WifiNative-HAL: startHal
09-08 18:24:05.503  1018  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f12b88c
09-08 18:24:05.503  1018  1129 I WifiNative-HAL: Could not start hal
,09-08 18:24:05.513  7296  7296 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:24:05.513  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:24:05.513  7319  7319 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:24:05.513  7319  7319 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:24:05.513  7319  7319 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:24:05.513  1018  1129 E WifiNative-wlan0: do suspend true
,09-08 18:24:05.513  1018  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-08 18:24:05.513   282   992 D CommandListener: Setting iface cfg
,09-08 18:24:05.513   282   992 D CommandListener: Trying to bring up p2p0
,09-08 18:24:05.513  1018  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 18:24:05.513  1018  1128 D WifiP2pService: P2pEnablingState
,09-08 18:24:05.513  1018  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
09-08 18:24:05.513  1018  1128 D WifiP2pService: P2p socket connection successful
,09-08 18:24:05.513  1018  1128 D WifiP2pService: P2pEnabledState
,09-08 18:24:05.523  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-08 18:24:05.523  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-08 18:24:05.523  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:24:05.523  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 18:24:05.523  1018  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 18:24:05.523  1018  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 18:24:05.523  1018  1129 E WifiNative-wlan0: invaild command id : 215
09-08 18:24:05.523  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:05.523  1018  1152 I WifiNative-HAL: startHal
09-08 18:24:05.523  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9dfed9bc
09-08 18:24:05.523  1018  1152 I WifiNative-HAL: Could not start hal
09-08 18:24:05.523  1018  1152 E WifiScanningService: could not start HAL
09-08 18:24:05.523  1018  1018 D RttService: SCAN_AVAILABLE : 3
09-08 18:24:05.523  1018  1153 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:24:05.523  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-08 18:24:05.523  1018  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 18:24:05.523  1018  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 18:24:05.523  1018  1129 E WifiNative-wlan0: invaild command id : 215
,09-08 18:24:05.523  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-08 18:24:05.523  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:24:05.523  1018  1048 D WifiDisplayController: disconnect
09-08 18:24:05.523  1018  1048 D WifiDisplayController: updateConnection
09-08 18:24:05.523  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:24:05.523  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:24:05.533  7802  7802 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 18:24:05.533  7802  7802 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 18:24:05.533  7802  7802 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-08 18:24:05.533  1018  1129 E WifiStateMachine: Failed to set frequency band 0
,09-08 18:24:05.533  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:24:05.533  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:24:05.533  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:24:05.533  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:24:05.533  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-08 18:24:05.543  1018  1238 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:24:05.543  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 18:24:05.543  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 18:24:05.543  1018  1128 D WifiNative-p2p0: p2pGetDeviceAddress
09-08 18:24:05.543  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-08 18:24:05.543  1018  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-08 18:24:05.543  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 18:24:05.543  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-08 18:24:05.543  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  secondary type: null
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  wps: 0
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  grpcapab: 0
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  devcapab: 0
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  status: 3
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  wfdInfo: null
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  groupownerAddress: null
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  GOdeviceName: null
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  interfaceAddress: 
09-08 18:24:05.543  1018  1048 D WifiDisplayController:  SConnectInfo : null
,09-08 18:24:05.543  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 18:24:05.543  1018  1128 D WifiP2pService: DeviceAddress: 0a:75:42
09-08 18:24:05.543  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:24:05.543  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:24:05.553  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:24:05.553  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:24:05.553  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-08 18:24:05.553  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:24:05.553  7643  7643 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:24:05.553  7643  7643 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-08 18:24:05.553  7643  7643 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 18:24:05.563  7281  7281 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:24:05.573  1018  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-08 18:24:05.573  1018  1128 D WifiP2pService: InactiveState
,09-08 18:24:05.573  1018  1128 D WifiP2pService: InactiveState{ what=143376 }
,09-08 18:24:05.573  1018  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 18:24:05.573  7802  7802 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 18:24:05.573  1018  1128 D WifiP2pService: InactiveState{ what=143376 }
,09-08 18:24:05.573  1018  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 18:24:05.773  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,09-08 18:24:05.773  1018  1045 D Tethering: interfaceStatusChanged p2p0, false,
,09-08 18:24:05.773  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,09-08 18:24:06.423  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:06.423  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:06.423  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:06.423  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:06.423  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:06.423  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:06.423  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:06.423  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:06.433  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:06.433  6785  7097 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 18:24:06.433  6785  7097 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 18:24:06.433  6785  7097 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@18b41a50 Bundle[{}]
,09-08 18:24:06.443  6785  7097 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 18:24:06.443  6785  7097 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 18:24:06.443  6785  7097 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 18:24:06.443  6785  7097 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 18:24:06.443  6785  7097 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-08 18:24:06.443  6785  7097 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 18:24:06.443  6785  7097 I System.out: Running OutgoingSocketThread
,09-08 18:24:06.443  6785  7811 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1369)
09-08 18:24:06.453  6785  7811 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42083
09-08 18:24:06.453  6785  7811 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 18:24:06.603   301   301 E SMD     : DCD OFF,
,09-08 18:24:06.763  7802  7802 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
,09-08 18:24:06.763  7802  7802 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-08 18:24:06.773  1018  7808 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
09-08 18:24:06.773  7802  7802 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-08 18:24:06.773  7802  7802 I wpa_supplicant: Trying to associate with  'G700'
09-08 18:24:06.773  7802  7802 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-08 18:24:06.773  7802  7802 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-08 18:24:06.793  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:24:06.793  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:24:06.883  7802  7802 E wpa_supplicant: Cmd 35605 not handled
,09-08 18:24:06.883  7802  7802 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-08 18:24:06.883  7802  7802 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-08 18:24:06.883  7802  7802 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-08 18:24:06.883  7802  7802 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-08 18:24:06.883  7802  7802 I wpa_supplicant: Associated with F4.99.3E
09-08 18:24:06.883  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:24:06.883  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:24:06.883  7802  7802 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-08 18:24:06.883  7802  7802 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-08 18:24:06.883  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:24:06.883  7802  7802 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-08 18:24:06.893  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:24:06.893  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:24:06.893  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 18:24:06.893  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-08 18:24:06.893  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-08 18:24:06.893  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:24:06.893  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-08 18:24:06.893  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-08 18:24:06.893  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
09-08 18:24:06.893  7802  7802 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-08 18:24:06.893  7802  7802 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-08 18:24:06.893  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:24:06.893  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:24:06.903  7802  7802 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-08 18:24:06.903  1018  1132 E Tethering: No numeric data
,09-08 18:24:06.903  7802  7802 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
09-08 18:24:06.903  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 18:24:06.903  1018  1132 D Tethering: clearTetheredNotification()
,09-08 18:24:06.903  7802  7802 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:24:06.903  7802  7802 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-08 18:24:06.903  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-08 18:24:06.903  7802  7802 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-08 18:24:06.903  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:24:06.903  7802  7802 I wpa_supplicant: Blacklist: Clear (temp) 
09-08 18:24:06.903  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-08 18:24:06.903  7802  7802 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-08 18:24:06.913  1182  1182 D HotspotTile: updateTetherState():false, false
09-08 18:24:06.903  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-08 18:24:06.903  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
09-08 18:24:06.903  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:24:06.903  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:24:06.903  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:06.913  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-08 18:24:06.913  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:24:06.913  1018  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
09-08 18:24:06.913  1018  1126 V NetworkStats: performPollLocked() took 8ms
09-08 18:24:06.913  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:06.913  1018  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,09-08 18:24:06.923  1018  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-08 18:24:06.923  1018  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-08 18:24:06.923  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:24:06.923  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-08 18:24:06.923  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:24:06.923  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:24:06.923  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 18:24:06.923  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:06.933  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:06.933  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:06.933  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:06.933  1018  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-08 18:24:06.933  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:06.933  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:06.933  1018  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-08 18:24:06.933  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:06.933  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:24:06.933  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:24:06.933  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 18:24:06.933  1631  1631 I Hs20UtilService: Starting #21
09-08 18:24:06.933  1631  1674 I Hs20UtilService: Message received 5007,
,09-08 18:24:06.943  1018  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:24:06.943  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:24:06.943  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:24:06.943  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:24:06.943  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:24:06.943  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-08 18:24:06.943  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:24:06.953   282   992 D CommandListener: Setting iface cfg,
,09-08 18:24:06.953  4726  4780 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:24:06.953  1018  1129 E WifiStateMachine: Start Dhcp Watchdog 3
,09-08 18:24:06.963  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 18:24:06.963  1018  1129 D SecContentProvider2: mCursor = null
,09-08 18:24:06.973  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:24:06.973  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:24:06.973  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 18:24:06.973  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:06.973  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:06.973  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:06.973  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:06.983  1018  1129 E WifiNative-wlan0: do suspend false
,09-08 18:24:06.983  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-08 18:24:06.983  1018  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-08 18:24:06.983  1018  1129 D SecContentProvider2: mCursor = null
09-08 18:24:06.983  1018  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 18:24:07.203  7814  7814 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-08 18:24:07.203  7814  7814 I dhcpcd  : version 5.5.6 starting,
,09-08 18:24:07.203  7814  7814 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-08 18:24:07.253  7814  7814 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-08 18:24:07.253  7814  7814 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-08 18:24:07.253  7814  7814 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-08 18:24:07.253  7814  7814 I dhcpcd  : bssid match
09-08 18:24:07.253  7814  7814 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116,
,09-08 18:24:07.313  7814  7814 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-08 18:24:07.393  7814  7814 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-08 18:24:07.443  6785  7097 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1370),
09-08 18:24:07.443  6785  7097 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1370)
,09-08 18:24:07.453  6785  7097 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1375),
09-08 18:24:07.453  6785  7097 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
09-08 18:24:07.453  6785  7097 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1376)
,09-08 18:24:07.453  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,09-08 18:24:07.453  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10608bba added. We now have 2 listener(s),
09-08 18:24:07.463  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-08 18:24:07.463  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:07.463  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:07.463  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-08 18:24:07.463  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8a5a6b added. We now have 9 listener(s)
09-08 18:24:07.463  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,09-08 18:24:07.463  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,09-08 18:24:07.473  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:07.473  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:07.473  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:07.473  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:07.473  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:07.473  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:07.473  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:07.473  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:07.473  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:07.473  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:07.473  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:07.473  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,09-08 18:24:07.473  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb58a61 added. We now have 3 listener(s),
,09-08 18:24:07.483  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:07.483  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:07.483  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-08 18:24:07.483  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:07.483  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:07.483  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:07.483  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47ba986 added. We now have 10 listener(s)
09-08 18:24:07.483  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:07.483  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:07.483  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:07.483  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:07.483  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.483  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:07.483  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10608bba removed from the list
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.483  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8a5a6b removed from the list
09-08 18:24:07.483  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:07.483  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:07.483  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:07.483  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:07.483  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8a5a6b not in the list
09-08 18:24:07.483  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.483  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.483  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47ba986 removed from the list
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:07.483  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.483  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:07.483  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:07.483  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb58a61 removed from the list
,09-08 18:24:07.483  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:07.483  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f23247 added. We now have 2 listener(s)
,09-08 18:24:07.493  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-08 18:24:07.493  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:24:07.493  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:07.493  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:07.493  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215b3a74 added. We now have 9 listener(s)
09-08 18:24:07.493  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:07.493  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:07.493  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:07.493  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,09-08 18:24:07.493  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:07.493  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:07.493  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:07.493  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:07.493  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:07.493  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:07.493  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:07.493  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:07.493  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:07.493  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:07.503  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d8d812 added. We now have 3 listener(s)
,09-08 18:24:07.503  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:07.503  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-08 18:24:07.503  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-08 18:24:07.503  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:07.503  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:07.503  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:07.503  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@615abe3 added. We now have 10 listener(s)
09-08 18:24:07.503  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:07.503  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:07.503  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:07.503  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:07.503  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:07.503  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:24:07.503  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:24:07.513  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:24:07.513  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-08 18:24:07.523  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-08 18:24:07.523  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:24:07.523  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:24:07.523  3209  7783 D BtGatt.GattService: registerClient() - UUID=cd4e268a-a3e2-467a-9c5b-dbb678343313
,09-08 18:24:07.563  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=cd4e268a-a3e2-467a-9c5b-dbb678343313, clientIf=6,
09-08 18:24:07.563  6785  6794 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-08 18:24:07.563  3209  3222 D BtGatt.GattService: start scan with filters,
09-08 18:24:07.563  3209  3329 D BtGatt.ScanManager: handling starting scan
09-08 18:24:07.563  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:24:07.563  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:24:07.563  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:24:07.563  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:24:07.573  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-08 18:24:07.573  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:07.573  3209  3329 D BtGatt.ScanManager: allow scan with filters
,09-08 18:24:07.573  3209  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-08 18:24:07.573  3209  3329 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,09-08 18:24:07.573  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:24:07.573  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:24:07.573  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:07.573  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:24:07.573  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-08 18:24:07.573  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:07.573  3209  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:24:07.573  3209  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:24:07.583  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-08 18:24:07.583  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:07.583  6785  7097 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:24:07.583  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:24:07.583  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:24:07.583  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.583  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-08 18:24:07.583  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:24:07.583  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:24:07.583  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-08 18:24:07.583  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:24:07.593  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
09-08 18:24:07.593  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 18:24:07.593  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-08 18:24:07.593  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.593  3209  3222 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:24:07.593  3209  3329 D BtGatt.ScanManager: filter size is 1
,09-08 18:24:07.593  3209  3329 D BtGatt.ScanManager: delete FilterIndex - 6
,09-08 18:24:07.593  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-08 18:24:07.593  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.593  3209  3329 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:24:07.603  3209  3328 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 18:24:07.603  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:07.603  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:24:07.603  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:24:07.603  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:24:07.603  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:24:07.603  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-08 18:24:07.603  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:07.603  3209  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:24:07.603  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:07.603  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-08 18:24:07.603  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:24:07.603  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:24:07.603  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-08 18:24:07.603  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.603  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:07.613  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:07.613  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:07.613  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:07.613  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:24:07.613  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:07.613  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:07.613  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:07.613  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:07.613  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:07.613  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:07.613  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f23247 removed from the list
09-08 18:24:07.613  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:07.613  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215b3a74 removed from the list
09-08 18:24:07.613  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:07.613  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:07.613  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-08 18:24:07.613  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:07.623  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-08 18:24:07.623  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:07.623  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.623  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215b3a74 not in the list
09-08 18:24:07.623  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.623  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:07.623  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-08 18:24:07.623  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:07.623  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.623  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@615abe3 removed from the list
09-08 18:24:07.623  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:24:07.623  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.623  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:07.623  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:07.623  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d8d812 removed from the list
09-08 18:24:07.623  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:07.623  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6d233f added. We now have 2 listener(s)
,09-08 18:24:07.633  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-08 18:24:07.633  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:07.633  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:07.633  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:07.633  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13ef640c added. We now have 9 listener(s)
09-08 18:24:07.633  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:07.633  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:07.643  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:07.643  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:07.643  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:07.643  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:07.643  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:07.643  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:07.643  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:07.643  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:07.643  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:07.643  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:07.643  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:24:07.653  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:07.653  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ad3576a added. We now have 3 listener(s)
,09-08 18:24:07.653  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:07.653  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:07.653  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-08 18:24:07.653  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:24:07.653  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:24:07.653  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:07.653  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@269ab45b added. We now have 10 listener(s)
,09-08 18:24:07.653  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:07.653  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:24:07.653  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:07.653  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:07.653  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 18:24:07.653  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:07.653  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:24:07.663  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:24:07.663  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:24:07.663  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:24:07.673  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 18:24:07.673  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:24:07.673  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:24:07.673  3209  7724 D BtGatt.GattService: registerClient() - UUID=ec5df5af-e97e-4fa4-bde3-53d070a806be
,09-08 18:24:07.713  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=ec5df5af-e97e-4fa4-bde3-53d070a806be, clientIf=6
,09-08 18:24:07.713  6785  6797 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 18:24:07.713  3209  7723 D BtGatt.GattService: start scan with filters
,09-08 18:24:07.723  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:24:07.723  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:24:07.723  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:24:07.723  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:24:07.723  3209  3329 D BtGatt.ScanManager: handling starting scan
,09-08 18:24:07.723  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-08 18:24:07.723  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.723  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:24:07.723  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:24:07.723  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:07.723  3209  3329 D BtGatt.ScanManager: allow scan with filters
09-08 18:24:07.723  3209  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-08 18:24:07.723  3209  3329 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-08 18:24:07.723  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-08 18:24:07.723  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:07.723  3209  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:24:07.723  3209  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:24:07.733  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-08 18:24:07.733  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.733  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:24:07.733  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-08 18:24:07.733  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.743  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:24:07.743  6785  7097 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 18:24:07.743  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:24:07.743  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:24:07.743  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:24:07.743  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:24:07.743  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:07.743  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:24:07.743  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 18:24:07.753  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6d233f removed from the list
,09-08 18:24:07.753  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:07.753  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13ef640c removed from the list
,09-08 18:24:07.753  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:24:07.753  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:07.753  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:07.753  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-08 18:24:07.753  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:07.753  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:07.753  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:24:07.753  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:24:07.753  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:07.753  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13ef640c not in the list
,09-08 18:24:07.753  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 18:24:07.753  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 18:24:07.753  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-08 18:24:07.763  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 18:24:07.763  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:24:07.763  3209  3358 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:24:07.763  3209  3329 D BtGatt.ScanManager: filter size is 1
,09-08 18:24:07.763  3209  3329 D BtGatt.ScanManager: delete FilterIndex - 7
,09-08 18:24:07.763  3209  7783 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 18:24:07.763  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-08 18:24:07.763  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.763  3209  3329 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:24:07.763  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:07.763  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:24:07.763  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:24:07.763  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:24:07.763  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:24:07.773  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-08 18:24:07.773  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:07.773  3209  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-08 18:24:07.773  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:07.773  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:24:07.773  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:24:07.773  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:24:07.773  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-08 18:24:07.773  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:07.773  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.773  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:24:07.773  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:24:07.773  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:07.773  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:24:07.773  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:24:07.773  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.773  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@269ab45b removed from the list
,09-08 18:24:07.783  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:07.783  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.783  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:07.783  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:07.783  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ad3576a removed from the list
,09-08 18:24:07.783  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:24:07.783  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a463b37 added. We now have 2 listener(s)
,09-08 18:24:07.783  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-08 18:24:07.783  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:24:07.783  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:24:07.783  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:07.783  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@397c28a4 added. We now have 9 listener(s)
,09-08 18:24:07.783  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:07.783  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:07.793  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:07.793  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:07.793  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:07.793  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:07.793  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:07.793  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:07.793  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:07.793  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:07.793  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:07.793  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:07.793  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:24:07.803  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:07.803  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180369c2 added. We now have 3 listener(s)
,09-08 18:24:07.803  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:07.803  1018  1129 E WifiNative-wlan0: do suspend true
,09-08 18:24:07.803  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-08 18:24:07.803  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:07.803  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:07.803  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:07.803  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b953d3 added. We now have 10 listener(s)
09-08 18:24:07.803  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:07.803  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:07.803  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:07.803  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:07.803  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:07.803  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:24:07.803  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:07.803  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:24:07.813  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:24:07.813  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:24:07.813  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 18:24:07.813  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 18:24:07.813  6785  7097 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:24:07.823  3209  7724 D BtGatt.GattService: registerClient() - UUID=a7b68c4e-be99-47e9-b46b-c1d6da06b45f
,09-08 18:24:07.823  1018  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-08 18:24:07.833  1018  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 18:24:07.833  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:24:07.833  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:07.833  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:24:07.833  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.833  1018  1129 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 18:24:07.833  1018  1129 E WifiStateMachine: VerifyingLinkState enter
,09-08 18:24:07.833  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.833  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-08 18:24:07.833  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.843  1018  1131 D ConnectivityService: Adding iface wlan0 to network 504
09-08 18:24:07.833  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:24:07.843  1018  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-08 18:24:07.843  1018  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-08 18:24:07.843  1018  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-08 18:24:07.843  1018  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-08 18:24:07.843  1018  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-08 18:24:07.853  1018  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-08 18:24:07.863  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=a7b68c4e-be99-47e9-b46b-c1d6da06b45f, clientIf=6,
09-08 18:24:07.863  6785  6794 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 18:24:07.863  1018  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-08 18:24:07.863  3209  7723 D BtGatt.GattService: start scan with filters
09-08 18:24:07.863  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:24:07.863  1018  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504,
,09-08 18:24:07.863  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:24:07.863  1018  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504,
,09-08 18:24:07.863  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:24:07.863  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:24:07.863  3209  3329 D BtGatt.ScanManager: handling starting scan
09-08 18:24:07.863  1018  1129 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-08 18:24:07.873  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:24:07.873  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:07.873  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:24:07.873  1018  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:24:07.873  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.873  1018  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 18:24:07.873  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.873  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:24:07.873  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.873  1018  1131 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-08 18:24:07.873  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.873  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:07.873  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:24:07.873  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 18:24:07.873  1631  1631 I Hs20UtilService: Starting #22
,09-08 18:24:07.873  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:24:07.873  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 18:24:07.873  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:07.873  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-08 18:24:07.873  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.873  3209  3329 D BtGatt.ScanManager: allow scan with filters
,09-08 18:24:07.873  3209  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-08 18:24:07.873  3209  3329 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,09-08 18:24:07.873  1631  1674 I Hs20UtilService: Message received 5007
09-08 18:24:07.873  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:24:07.883  4726  4726 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-08 18:24:07.883  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:24:07.883  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-08 18:24:07.883  1018  1131 D ConnectivityService: LTETest block dns file not exists
,09-08 18:24:07.883  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:07.883  3209  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:24:07.883  3209  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:24:07.883  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-08 18:24:07.883  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.893  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.893  1018  1131 V NetworkStats: updateIfacesLocked()
09-08 18:24:07.893  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:24:07.893  1018  1131 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:24:07.893  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:24:07.893  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-08 18:24:07.893  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.903  1018  1131 V NetworkStats: performPollLocked() took 8ms
09-08 18:24:07.903  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 18:24:07.903  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:07.903  1018  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 18:24:07.903  1018  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 18:24:07.903  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:07.903  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:07.903  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:07.903  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:07.903  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.903  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:24:07.903  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:07.903  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-08 18:24:07.903  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
09-08 18:24:07.913  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
09-08 18:24:07.913  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a463b37 removed from the list
09-08 18:24:07.913  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.913  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@397c28a4 removed from the list
09-08 18:24:07.913  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:07.913  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:07.913  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-08 18:24:07.913  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:07.913  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:24:07.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.913  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:07.913  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.913  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:07.913  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-08 18:24:07.913  1018  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-08 18:24:07.923  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:24:07.923  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:07.923  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 18:24:07.923  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:24:07.923  1018  1131 E ConnectivityService: updateNetworkInfo()
09-08 18:24:07.923  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.923  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.923  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.923  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:07.923  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:07.923  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.923  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.923  1018  1131 V NetworkStats: updateIfacesLocked()
09-08 18:24:07.923  1018  1131 V NetworkStats: performPollLocked(flags=0x1)
,09-08 18:24:07.923  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:24:07.923  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:07.923  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:07.923  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@397c28a4 not in the list
09-08 18:24:07.923  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 18:24:07.923  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:24:07.923  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:24:07.923  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 18:24:07.923  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:24:07.923  3209  3358 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:24:07.923  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:24:07.923  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:24:07.933  3209  3329 D BtGatt.ScanManager: filter size is 1
,09-08 18:24:07.933  3209  7723 D BtGatt.GattService: unregisterClient() - clientIf=6
09-08 18:24:07.933  3209  3329 D BtGatt.ScanManager: delete FilterIndex - 8
,09-08 18:24:07.933  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-08 18:24:07.933  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.933  3209  3329 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:24:07.933  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:07.933  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:24:07.933  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:24:07.933  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:24:07.933  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:24:07.933  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:07.933  1018  1131 V NetworkStats: performPollLocked() took 13ms
09-08 18:24:07.933  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:07.933  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:24:07.933  6785  7097 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:24:07.933  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:24:07.933  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-08 18:24:07.933  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.933  3209  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:24:07.933  1018  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,09-08 18:24:07.933  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.933  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.933  1018  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-08 18:24:07.933  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:07.933  1018  7812 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:07.933  1018  7812 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-08 18:24:07.933  1018  7812 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:07.933  1018  7812 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-08 18:24:07.933  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-08 18:24:07.933  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:07.943  1018  7812 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 18:24:07.943  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:07.943  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:07.943  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.943  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b953d3 removed from the list
09-08 18:24:07.943  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:07.943  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.943  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:07.943  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:07.943  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180369c2 removed from the list
09-08 18:24:07.943  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:07.943  6785  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:07.943  6785  6785 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:24:07.943  1018  1542 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:24:07.943  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:07.943  1018  1542 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:24:07.943  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@153b5a2f added. We now have 2 listener(s)
,09-08 18:24:07.943  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:07.943  1018  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:07.943  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:24:07.943   282   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 18:24:07.943   282   988 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-08 18:24:07.943  1018  1131 D ConnectivityService:    accepting network in place of null
,09-08 18:24:07.943  1018  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-08 18:24:07.943  1482  1482 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-08 18:24:07.943  1482  1482 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-08 18:24:07.943  1018  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-08 18:24:07.943  1631  1631 I Hs20UtilService: Starting #23
,09-08 18:24:07.943  1018  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 18:24:07.943  1018  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-08 18:24:07.943  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-08 18:24:07.953  1631  1674 I Hs20UtilService: Message received 5007
,09-08 18:24:07.953  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-08 18:24:07.953  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:07.953  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:07.953  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:07.953  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f19e83c added. We now have 9 listener(s)
09-08 18:24:07.953  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:07.953  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:07.953  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-08 18:24:07.953  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,09-08 18:24:07.953  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:24:07.953  1018  1126 V NetworkStats: updateIfacesLocked()
09-08 18:24:07.953  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.953  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-08 18:24:07.953  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:24:07.953  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:24:07.953  1018  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-08 18:24:07.953  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:24:07.963  1018  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-08 18:24:07.963  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: updateDataNetType()
09-08 18:24:07.963  1018  1126 V NetworkStats: performPollLocked() took 4ms
09-08 18:24:07.963  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.963  1182  1707 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 18:24:07.963  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-08 18:24:07.963  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:24:07.963  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-08 18:24:07.963  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-08 18:24:07.963  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-08 18:24:07.963  4726  4726 I NearbySettings: MountReceiver.onReceive - Keep current state
09-08 18:24:07.963  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:07.963  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.963  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.973  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.973  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:07.973  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.973  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.973  1018  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-08 18:24:07.973  6785  7097 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:07.973  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:07.973  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:07.973  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:07.973  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:07.973  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:07.973  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:07.973  6785  7097 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:07.973  6785  7097 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:24:07.973  6785  7097 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:07.973  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:07.973  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9286f1a added. We now have 3 listener(s)
,09-08 18:24:07.983  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:07.983  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-08 18:24:07.983  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:24:07.983  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:07.983  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:24:07.983  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:07.983  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d6a4b added. We now have 10 listener(s)
09-08 18:24:07.983  6785  7097 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:07.983  6785  7097 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:24:07.983  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:07.983  6785  7097 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:07.983  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:07.983  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.983  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:07.983  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:07.983  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@153b5a2f removed from the list
09-08 18:24:07.983  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.983  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f19e83c removed from the list
09-08 18:24:07.983  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:24:07.983  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:07.983  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:07.983  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:07.983  6785  7097 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:07.983  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:07.983  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:24:07.983  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.983  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:07.983  1631  1631 I Hs20UtilService: Starting #24
,09-08 18:24:07.983  1631  1674 I Hs20UtilService: Message received 5007
,09-08 18:24:07.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:07.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:07.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.993  6785  7097 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f19e83c not in the list
09-08 18:24:07.993  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.993  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:07.993  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:24:07.993  4726  4726 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-08 18:24:07.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:24:07.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:07.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:07.993  6785  7097 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d6a4b removed from the list
09-08 18:24:07.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:07.993  6785  7097 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:07.993  6785  7097 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:07.993  6785  7097 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:07.993  6785  7097 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9286f1a removed from the list
,09-08 18:24:07.993  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 18:24:07.993  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 18:24:07.993  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 18:24:07.993  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:07.993  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 18:24:07.993  6785  7097 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:24:08.003  1018  1327 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-08 18:24:08.003  6785  7850 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1383, name: My test thread name)
,09-08 18:24:08.003  6785  7850 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1383, thread name: My test thread name)
09-08 18:24:08.003  6785  7850 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1383, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-08 18:24:08.003  1018  1030 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-08 18:24:08.003  1018  1030 D SecContentProvider2: mCursor = null
09-08 18:24:08.003  6785  7851 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1385, name: My test thread name)
09-08 18:24:08.003  6785  7851 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1385, thread name: My test thread name)
09-08 18:24:08.003  6785  7851 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1385, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-08 18:24:08.003  1018  3836 D SecContentProvider2: uri = 15 selection = getToastGravity
09-08 18:24:08.003  1018  3836 D SecContentProvider2: mCursor = null,
,09-08 18:24:08.003  6785  7097 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-08 18:24:08.003  6785  7097 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80,
09-08 18:24:08.003  6785  7097 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-08 18:24:08.003  6785  7097 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-08 18:24:08.003  6785  7097 D com.test.thalitest.ThaliTestRunner: Total duration: 23343 ms
,09-08 18:24:08.003  1018  4614 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-08 18:24:08.003  1018  4614 D SecContentProvider2: mCursor = null
09-08 18:24:08.003  6785  7097 I jxcore-log: *Native tests were executed*
09-08 18:24:08.003  6785  7097 I jxcore-log: 
09-08 18:24:08.003  6785  7097 I jxcore-log: Total number of executed tests:  80
09-08 18:24:08.003  6785  7097 I jxcore-log: 
,09-08 18:24:08.003  6785  7097 I jxcore-log: Number of passed tests:  80
09-08 18:24:08.003  6785  7097 I jxcore-log: 
09-08 18:24:08.003  6785  7097 I jxcore-log: Number of failed tests:  0
09-08 18:24:08.003  6785  7097 I jxcore-log: 
,09-08 18:24:08.003  6785  7097 I jxcore-log: Number of ignored tests:  0,
09-08 18:24:08.003  6785  7097 I jxcore-log: 
09-08 18:24:08.013  6785  7097 I jxcore-log: Total duration:  23343
09-08 18:24:08.013  6785  7097 I jxcore-log: 
,09-08 18:24:08.013  6785  7097 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-08 18:24:08.013  6785  7097 I jxcore-log: 
09-08 18:24:08.013  1018  1493 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-08 18:24:08.013  1018  1493 D SecContentProvider2: mCursor = null
,09-08 18:24:08.013  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.013  6785  7097 I jxcore-log: 
09-08 18:24:08.013  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.013  6785  7097 I jxcore-log: 
09-08 18:24:08.013  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.013  6785  7097 I jxcore-log: 
09-08 18:24:08.023  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.023  6785  7097 I jxcore-log: 
09-08 18:24:08.023  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.023  6785  7097 I jxcore-log: 
09-08 18:24:08.023  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.023  6785  7097 I jxcore-log: 
09-08 18:24:08.023  6785  6785 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-08 18:24:08.023  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.023  6785  7097 I jxcore-log: 
09-08 18:24:08.023  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.023  6785  7097 I jxcore-log: 
09-08 18:24:08.033  1018  1141 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-08 18:24:08.033  1018  1141 D SecContentProvider2: mCursor = null
09-08 18:24:08.033  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.033  6785  7097 I jxcore-log: 
09-08 18:24:08.033  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:08.033  6785  7097 I jxcore-log: 
09-08 18:24:08.033  1018  1542 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-08 18:24:08.033  1018  1542 D SecContentProvider2: mCursor = null
09-08 18:24:08.033  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.033  6785  7097 I jxcore-log: 
09-08 18:24:08.033  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.033  6785  7097 I jxcore-log: 
09-08 18:24:08.033  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.033  6785  7097 I jxcore-log: 
09-08 18:24:08.033  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.033  6785  7097 I jxcore-log: 
09-08 18:24:08.033  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.033  6785  7097 I jxcore-log: 
09-08 18:24:08.033  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.033  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
,09-08 18:24:08.043  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.043  6785  7097 I jxcore-log: 
,09-08 18:24:08.063   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-08 18:24:08.063  1018  1238 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,09-08 18:24:08.073  1182  1182 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-08 18:24:08.113  6785  6785 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:24:08.113  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:08.113  6785  7097 I jxcore-log: 
,09-08 18:24:08.233  1018  7812 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,09-08 18:24:08.273  6785  6785 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-08 18:24:08.283  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:08.283  6785  7097 I jxcore-log: 
,09-08 18:24:08.293  7853  7853 D AndroidRuntime: ,
09-08 18:24:08.293  7853  7853 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-08 18:24:08.293  7853  7853 D AndroidRuntime: CheckJNI is OFF,
09-08 18:24:08.293  7853  7853 D AndroidRuntime: readGMSProperty: start,
09-08 18:24:08.293  7853  7853 D AndroidRuntime: readGMSProperty: already setted!!
09-08 18:24:08.293  7853  7853 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-08 18:24:08.293  7853  7853 D AndroidRuntime: readGMSProperty: could not set the property(default)!!,
09-08 18:24:08.293  7853  7853 D AndroidRuntime: readGMSProperty: end
09-08 18:24:08.293  7853  7853 D AndroidRuntime: addProductProperty: start
,09-08 18:24:08.313  1018  7812 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 16:24:08 GMT], X-Android-Received-Millis=[1473351848322], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473351848299]},
09-08 18:24:08.313  1018  7812 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 18:24:08.313  1018  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-08 18:24:08.313  1018  7812 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-08 18:24:08.313  1018  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-08 18:24:08.313  1018  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-08 18:24:08.313  1018  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-08 18:24:08.313  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 18:24:08.313  1182  1707 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 18:24:08.323  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
,09-08 18:24:08.323  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-08 18:24:08.323  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,09-08 18:24:08.323  1182  1182 D StatusBar.NetworkController: updateDataNetType()
,09-08 18:24:08.323  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-08 18:24:08.323  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-08 18:24:08.323  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
09-08 18:24:08.323  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-08 18:24:08.323  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-08 18:24:08.323  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-08 18:24:08.333  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:08.333  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 18:24:08.333  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.333  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.333  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.333  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:08.433  7853  7853 E AffinityControl: AffinityControl: registerfunction enter,
,09-08 18:24:08.443  6785  6785 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-08 18:24:08.443  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:08.443  6785  7097 I jxcore-log: 
,09-08 18:24:08.453  7853  7853 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
09-08 18:24:08.453  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:08.463  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,09-08 18:24:08.473  1018  6835 D PackageManager: START PACKAGE DELETE: observer{772590773}
09-08 18:24:08.473  1018  6835 D PackageManager: pkg{<packageName>}
09-08 18:24:08.473  1018  6835 D PackageManager: user{0}
09-08 18:24:08.473  1018  6835 D PackageManager: caller{2000}
09-08 18:24:08.473  1018  6835 D PackageManager: flags{2}
,09-08 18:24:08.473  1018  6835 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-08 18:24:08.473  1018  6835 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-08 18:24:08.473  1018  6835 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-08 18:24:08.473  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-08 18:24:08.473  1018  6835 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-08 18:24:08.473  1018  6835 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-08 18:24:08.473  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:08.473  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:08.473  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:08.473  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:08.483  1018  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-08 18:24:08.483  1018  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-08 18:24:08.483  1018  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-08 18:24:08.483  6785  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:08.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:08.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:08.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:08.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:08.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:08.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:08.483  6785  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:08.483  1018  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
09-08 18:24:08.483  1018  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-08 18:24:08.483  6785  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:08.483  6785  7097 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.483  6785  7097 I jxcore-log: 
,09-08 18:24:08.493  1018  1056 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
09-08 18:24:08.493  7863  7863 E Zygote  : MountEmulatedStorage(),
09-08 18:24:08.493  7863  7863 E Zygote  : v2
09-08 18:24:08.493  7863  7863 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:24:08.493  7863  7863 I libpersona: KNOX_SDCARD not a persona
,09-08 18:24:08.493  1018  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7863 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-08 18:24:08.503  7863  7863 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-08 18:24:08.503  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-08 18:24:08.503  1018  1043 I ActivityManager: Killing 6785:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-08 18:24:08.503  7863  7863 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:24:08.503  7863  7863 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:24:08.503  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{153e0ad9 u0 com.test.thalitest/.MainActivity t163}
,09-08 18:24:08.513  1018  1043 D InputDispatcher: Focus left window: 6785
09-08 18:24:08.513   258  1164 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-08 18:24:08.513   258   438 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-08 18:24:08.553  1018  1043 D InputDispatcher: Focused application released
09-08 18:24:08.553  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 18:24:08.553  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 18:24:08.563  7863  7863 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:24:08.573  7863  7863 D ActivityThread: Added TimaKeyStore provider
,09-08 18:24:08.663  1018  1056 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-08 18:24:08.673  1018  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-08 18:24:08.683  7863  7863 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-08 18:24:08.683  7863  7863 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-08 18:24:08.683  7863  7863 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-08 18:24:08.703  2821  2821 I art     : Explicit concurrent mark sweep GC freed 16593(990KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 809us total 35.369ms
,09-08 18:24:08.723  1018  1141 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-08 18:24:08.723  1018  1141 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-08 18:24:08.723  1018  1141 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-08 18:24:08.723  1018  1141 D BatteryService: stay LED for charging
,09-08 18:24:08.723  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,09-08 18:24:08.723  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-08 18:24:08.723  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-08 18:24:08.723  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-08 18:24:08.723  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-08 18:24:08.733  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 18:24:08.743  1735  1930 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-08 18:24:08.743  1889  1889 E SamsungIME: mOCRHelper is null
,09-08 18:24:08.743  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,09-08 18:24:08.743  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-08 18:24:08.763  1470  1470 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:24:08.773  1018  1126 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-08 18:24:08.773  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:08.773  1018  1126 V NetworkStats: performPollLocked(flags=0x3)
,09-08 18:24:08.773  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:24:08.773  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:24:08.773  1018  1126 V NetworkStats: performPollLocked() took 4ms
,09-08 18:24:08.783  1470  1470 D RegisteredServicesCache: empty dynamic service
,09-08 18:24:08.783  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:08.793  7863  7863 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-08 18:24:08.793  7863  7863 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 18:24:08.793  7863  7863 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 18:24:08.793  7863  7863 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:08.803  1018  1542 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-08 18:24:08.803  1018  1542 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-08 18:24:08.803  1018  1542 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-08 18:24:08.803  1018  1542 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-08 18:24:08.803  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:08.803  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:08.803  1018  1542 I ActivityManager: Killing 7354:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-08 18:24:08.813  1470  1470 D RegisteredComponentCache: Collect Tech packages for Knox
,09-08 18:24:08.813  1470  1470 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:24:08.823  1018  1522 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-08 18:24:08.823  1018  1522 D SecContentProvider2: mCursor = null
,09-08 18:24:08.833  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
09-08 18:24:08.833  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-08 18:24:08.843  1018  1042 W TextServicesManagerService: no available spell checker services found
,09-08 18:24:08.873  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-08 18:24:08.873  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-08 18:24:08.873  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:08.873  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-08 18:24:08.873  1018  1018 V EnterpriseBillingPolicy: uID is 10170
09-08 18:24:08.873  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
09-08 18:24:08.873  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-08 18:24:08.873  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-08 18:24:08.873  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-08 18:24:08.873  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-08 18:24:08.873  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-08 18:24:08.873  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-08 18:24:08.873  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:08.873  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 18:24:08.873  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-08 18:24:08.883  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:08.883  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:08.883  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-08 18:24:08.883  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 18:24:08.893  1440  1440 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-08 18:24:08.893  1440  1440 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-08 18:24:08.903  3209  3209 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 18:24:08.903  3209  7774 D HeadsetStateMachine: Disconnected process message: 10
,09-08 18:24:08.913  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:24:08.913  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-08 18:24:08.913  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-08 18:24:08.913  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-08 18:24:08.913  1182  1182 D SViewCoverView: level :100 plugged : 2
,09-08 18:24:08.923  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-08 18:24:08.923  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,09-08 18:24:08.923  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-08 18:24:08.923  1018  3354 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-08 18:24:08.923  1018  1018 V EnterpriseBillingPolicy: uID is 10170
,09-08 18:24:08.923  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
,09-08 18:24:08.923  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-08 18:24:08.933  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-08 18:24:08.933  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-08 18:24:08.933  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-08 18:24:08.933  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-08 18:24:08.933  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-08 18:24:08.943  1018  1018 I MotionRecognitionService: Plugged
09-08 18:24:08.943  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 18:24:08.963  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast,
,09-08 18:24:08.973  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:08.973  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:08.973  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:08.973  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:08.973  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
09-08 18:24:08.973  1018  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-08 18:24:08.973  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:08.983  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:08.983  7882  7882 E Zygote  : MountEmulatedStorage(),
09-08 18:24:08.983  7882  7882 E Zygote  : v2
,09-08 18:24:08.983  7882  7882 I libpersona: KNOX_SDCARD checking this for 10001
09-08 18:24:08.983  7882  7882 I libpersona: KNOX_SDCARD not a persona
,09-08 18:24:08.983  7882  7882 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-08 18:24:08.983  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7882 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:24:08.983  7882  7882 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 18:24:08.993  7882  7882 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:24:08.993  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.003  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 18:24:09.003  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:24:09.003  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 18:24:09.003  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.003  1018  1056 I art     : Explicit concurrent mark sweep GC freed 72808(4MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/35MB, paused 13.796ms total 258.675ms
,09-08 18:24:09.013  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.023  7882  7882 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:24:09.023  7882  7882 D ActivityThread: Added TimaKeyStore provider
09-08 18:24:09.023  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.023  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 18:24:09.023  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-08 18:24:09.023  1018  1056 D PackageManager: delete codoeFile: 
,09-08 18:24:09.033  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.033  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 18:24:09.033  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-08 18:24:09.033  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 18:24:09.033  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-08 18:24:09.043  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.043  1018  1056 I AASA_removePackage: UID=10170 Target=com.test.thalitest
09-08 18:24:09.043  1018  1056 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest,
,09-08 18:24:09.043  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-08 18:24:09.043  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-08 18:24:09.043  1018  1056 D PackageManager: result of delete: 1{772590773},
,09-08 18:24:09.053  7853  7853 D AndroidRuntime: Shutting down VM
,09-08 18:24:09.083  7371  7371 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:09.083  7371  7371 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-08 18:24:09.083  7371  7371 I DIAGMON_AGENT: ./extraInfo: "NG700"
,09-08 18:24:09.093  7371  7371 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-08 18:24:09.223  7386  7386 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-08 18:24:09.223  7386  7386 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-08 18:24:09.223  7386  7386 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-08 18:24:09.233  7386  7386 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-08 18:24:09.243  1018  1238 I ActivityManager: Killing 7403:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-08 18:24:09.253  1018  1522 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-08 18:24:09.253  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-08 18:24:09.253  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:09.253  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:24:09.253  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-08 18:24:09.263  7853  7853 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-08 18:24:09.273   282   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 18:24:09.273   282   988 D Netd    : getNetworkForDns: using netid 504 for uid 10011
09-08 18:24:09.273  1879  1879 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,09-08 18:24:09.323  1879  1879 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 18:24:09.333  1879  2801 I iu.UploadsManager: num queued entries: 0
,09-08 18:24:09.333  1879  2801 I iu.UploadsManager: num updated entries: 0
,09-08 18:24:09.333  1879  2801 I iu.SyncManager: NEXT; no task
,09-08 18:24:09.343  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:24:09.343  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-08 18:24:09.343  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:09.343  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:24:09.343  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:24:09.343  1018  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-08 18:24:09.343  1018  1056 D PackageManager: userId{-1}
09-08 18:24:09.343  1018  1056 D PackageManager: andCode{true}
09-08 18:24:09.343  1018  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-08 18:24:09.343  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:09.343  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:09.343  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:09.343  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:09.353  7906  7906 E Zygote  : MountEmulatedStorage()
,09-08 18:24:09.353  7906  7906 E Zygote  : v2
,09-08 18:24:09.363  7906  7906 I libpersona: KNOX_SDCARD checking this for 10003
09-08 18:24:09.363  7906  7906 I libpersona: KNOX_SDCARD not a persona
,09-08 18:24:09.363  7906  7906 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-08 18:24:09.363  1018  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7906 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-08 18:24:09.363  7906  7906 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:24:09.363  1879  1879 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 18:24:09.373  1879  1879 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-08 18:24:09.373  7906  7906 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:24:09.373  2805  2805 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 18:24:09 GMT+02:00 2016
,09-08 18:24:09.373  1018  3836 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-08 18:24:09.373  1018  3836 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-08 18:24:09.373  1018  3836 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:09.373  1018  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:09.373  1018  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 18:24:09.383  2805  2805 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-08 18:24:09.383  7906  7906 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:24:09.393  7906  7906 D ActivityThread: Added TimaKeyStore provider
09-08 18:24:09.393  2805  2805 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-08 18:24:09.393  1018  4614 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-08 18:24:09.393  2805  2805 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 18:24:09.393  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:09.393  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:09.393  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:09.393  1018  4614 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:09.403  2805  2805 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,09-08 18:24:09.403  2805  7917 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-08 18:24:09.403  2805  7917 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-08 18:24:09.403  7923  7923 E Zygote  : MountEmulatedStorage()
,09-08 18:24:09.403  7923  7923 E Zygote  : v2
,09-08 18:24:09.413  7923  7923 I libpersona: KNOX_SDCARD checking this for 10031
09-08 18:24:09.413  7923  7923 I libpersona: KNOX_SDCARD not a persona
,09-08 18:24:09.413  7923  7923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 18:24:09.413  2805  7917 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-08 18:24:09.413  1018  4614 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7923 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-08 18:24:09.413  7923  7923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 18:24:09.413  7923  7923 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:24:09.413  1018  6835 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-08 18:24:09.413  1018  6835 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-08 18:24:09.423  1018  6835 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:09.423  1018  6835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:09.423  1018  6835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-08 18:24:09.423  2805  7917 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,09-08 18:24:09.423  2805  7917 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,09-08 18:24:09.423  2805  7917 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,09-08 18:24:09.433  2805  7917 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:171)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.uploadRequestLog(NetworkChangeOperations.java:81)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.doNetworkJob(NetworkChangeOperations.java:57)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.StateImplV2.networkChangeListener(StateImplV2.java:240)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:222)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:24:09.433  2805  7917 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:171)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.uploadRequestLog(NetworkChangeOperations.java:81)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.doNetworkJob(NetworkChangeOperations.java:57)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.StateImplV2.networkChangeListener(StateImplV2.java:240)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:222)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:24:09.433  2805  7917 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 18:24:09.433  2805  7917 W SQLiteOpenHelper: Opened klms.db in read-only mode

```
