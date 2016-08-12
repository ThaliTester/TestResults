#### Test 79751015007586f_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-12 22:27:17.030  4903  4903 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
,08-12 22:27:17.030  4903  4903 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-12 22:27:17.030  4903  4903 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-12 22:27:17.040  4903  4903 I art     : System.exit called, status: 0
08-12 22:27:17.040  4903  4903 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
--------- beginning of system
08-12 22:27:17.090   775  2268 I ActivityManager: Process com.samsung.aasaservice (pid 4903)(adj 0) has died(133,728)
08-12 22:27:17.090   775  2268 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-12 22:27:17.090   775  2268 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-12 22:27:17.090   775  2268 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-12 22:27:17.110   775   856 I ActivityManager: Start proc 6403:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-12 22:27:17.110   775  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 22:27:17.120  6403  6403 E Zygote  : v2
08-12 22:27:17.120  6403  6403 I libpersona: KNOX_SDCARD checking this for 10014
08-12 22:27:17.120  6403  6403 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:17.120  6403  6403 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:17.120  6403  6403 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:17.120  6403  6403 E Zygote  : accessInfo : 0
08-12 22:27:17.120  6403  6403 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-12 22:27:17.130  4861  4861 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-12 22:27:17.190  6403  6403 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:17.190  6403  6403 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:17.200   775  2100 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a473aa2 6403:com.google.android.partnersetup/u0a14}
08-12 22:27:17.200   775  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-12 22:27:17.200  6403  6403 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-12 22:27:17.210  6403  6403 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-12 22:27:17.240   775  2269 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a473aa2 6403:com.google.android.partnersetup/u0a14}
08-12 22:27:17.260   775   788 I ActivityManager: Start proc 6428:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-12 22:27:17.260  6428  6428 E Zygote  : v2
08-12 22:27:17.260  6428  6428 I libpersona: KNOX_SDCARD checking this for 10015
08-12 22:27:17.260  6428  6428 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:17.260  6428  6428 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:17.260  6428  6428 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:17.260  6428  6428 E Zygote  : accessInfo : 0
08-12 22:27:17.270  6428  6428 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-12 22:27:17.310  6428  6428 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:17.310  6428  6428 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:17.320   775  1694 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b899469 6428:com.samsung.groupcast/u0a15}
08-12 22:27:17.320  6428  6428 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-12 22:27:17.340  6428  6428 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-12 22:27:17.360  6428  6428 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-12 22:27:17.360  6428  6428 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-12 22:27:17.370  6428  6428 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-12 22:27:17.370  6428  6428 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-12 22:27:17.370  6428  6428 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-12 22:27:17.370  6428  6428 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 22:27:17.370  6428  6428 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 22:27:17.370  6428  6428 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 22:27:17.370  6428  6428 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 22:27:17.370  6428  6428 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:27:17.370  6428  6428 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 22:27:17.370  6428  6428 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 22:27:17.370  6428  6428 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:27:17.370  6428  6428 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 22:27:17.370  6428  6428 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 22:27:17.370   775  1217 I ActivityManager: Killing 4980:com.samsung.android.sm/1000 (adj 15): DHA:empty #37
08-12 22:27:17.380   775  1217 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ca8274 1940:com.sec.android.app.shealth:remote/u0a34}
08-12 22:27:17.390  6442  6442 E Zygote  : v2
08-12 22:27:17.390   775  1669 I ActivityManager: Start proc 6442:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-12 22:27:17.390  6442  6442 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:17.390  6442  6442 I libpersona: KNOX_SDCARD checking this for 10041
08-12 22:27:17.390  6442  6442 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:17.390  6442  6442 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:17.400  6442  6442 E Zygote  : accessInfo : 0
08-12 22:27:17.400  6442  6442 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-12 22:27:17.400   775  1694 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
08-12 22:27:17.420  6442  6442 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:17.420  6442  6442 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:17.430   775   788 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7025eee 6442:com.samsung.android.sdk.samsunglink/u0a41}
08-12 22:27:17.430  6442  6442 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-12 22:27:17.510  6442  6442 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 22:27:17.510  6442  6442 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 22:27:17.570  6442  6442 I SL_DEBUG: isLoggable:: isProductShip = 1
08-12 22:27:17.570  6442  6442 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
08-12 22:27:17.580   775  2273 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
08-12 22:27:17.580   775  2104 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
08-12 22:27:17.580   775   788 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
08-12 22:27:17.590   775   789 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
08-12 22:27:17.590   775  2270 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
08-12 22:27:17.590   775  1217 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
08-12 22:27:17.590   775  1411 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
08-12 22:27:17.590   775  2269 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
08-12 22:27:17.600   775  1677 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
08-12 22:27:17.600   775  2268 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
08-12 22:27:17.690  6442  6442 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
08-12 22:27:17.690  6442  6442 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-12 22:27:17.690  6442  6442 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-12 22:27:17.690  6442  6442 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-12 22:27:17.690  6442  6442 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-12 22:27:17.690  6442  6442 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-12 22:27:17.690  6442  6442 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 22:27:17.690  6442  6442 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 22:27:17.690  6442  6442 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 22:27:17.690  6442  6442 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 22:27:17.690  6442  6442 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:27:17.690  6442  6442 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 22:27:17.690  6442  6442 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 22:27:17.690  6442  6442 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:27:17.690  6442  6442 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 22:27:17.690  6442  6442 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 22:27:17.700   775  1411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{efcaa55 1740:android.process.acore/u0a19}
08-12 22:27:17.710   775  1411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1923f65 5027:com.sec.android.gallery3d/u0a47}
08-12 22:27:17.710  5027  5027 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-12 22:27:17.710   775  1669 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 22:27:17.730   775  1237 V AlarmManager: Expired Alarm result :4
08-12 22:27:17.730   775  1694 I ActivityManager: Start proc 6465:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-12 22:27:17.740  6465  6465 E Zygote  : v2
08-12 22:27:17.740  6465  6465 I libpersona: KNOX_SDCARD checking this for 10050
08-12 22:27:17.740  6465  6465 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:17.740  6465  6465 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:17.740  6465  6465 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:17.750  6465  6465 E Zygote  : accessInfo : 0
08-12 22:27:17.750  6465  6465 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
08-12 22:27:17.750  5804  5845 I Finsky  : [825] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
08-12 22:27:17.780  6465  6465 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:17.780  6465  6465 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:17.790   775  2103 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-12 22:27:17.790   775  2103 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 22:27:17.790   775  2103 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-12 22:27:17.790   775  2103 D BatteryService: stay LED for charging
08-12 22:27:17.790   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-12 22:27:17.790   775  1411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{727ca95 6465:com.sec.android.app.myfiles/u0a50}
08-12 22:27:17.800   775   775 I MotionRecognitionService: Plugged
08-12 22:27:17.800   775   775 D MotionRecognitionService:   cableConnection= 1
08-12 22:27:17.800   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 22:27:17.800   775   775 D MotionRecognitionService: skip setTransmitPower. 
08-12 22:27:17.800  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:27:17.800  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:27:17.800  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
08-12 22:27:17.800  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 22:27:17.800  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 22:27:17.810  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-12 22:27:17.810  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 22:27:17.810  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 22:27:17.810   775  2273 I ActivityManager: Killing 5605:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
08-12 22:27:17.820  6465  6465 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-12 22:27:17.830   775  1677 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
08-12 22:27:17.840  6465  6465 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
08-12 22:27:17.880  6465  6465 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-12 22:27:17.890   775  2270 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1d0aa1a 5182:com.android.settings/1000}
08-12 22:27:17.890   330   330 E installd: system dir 0 : /system/app/
08-12 22:27:17.890   330   330 E installd: system dir 1 : /system/priv-app/
08-12 22:27:17.890   330   330 E installd: system dir 2 : /vendor/app/
08-12 22:27:17.890   330   330 E installd: system dir 3 : /oem/app/
08-12 22:27:17.900   775   937 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-12 22:27:17.910   775  2271 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1d0aa1a 5182:com.android.settings/1000}
08-12 22:27:17.930  6480  6480 E Zygote  : v2
08-12 22:27:17.930  6480  6480 I libpersona: KNOX_SDCARD checking this for 10169
08-12 22:27:17.930  6480  6480 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:17.930   775  2271 I ActivityManager: Start proc 6480:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-12 22:27:17.930  6480  6480 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:17.930  6480  6480 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:17.930  6480  6480 E Zygote  : accessInfo : 0
08-12 22:27:17.930  6480  6480 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
08-12 22:27:17.950  2185  2185 E audit   : type=1400 msg=audit(1471033637.950:284): avc:  denied  { execmod } for  pid=6401 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 22:27:17.950  2185  2185 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:17.950  2185  2185 E audit   : type=1300 msg=audit(1471033637.950:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb2000 a1=51000 a2=5 a3=4 items=0 ppid=3505 ppcomm=adbd pid=6401 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 22:27:17.950  2185  2185 E audit   : type=1327 msg=audit(1471033637.950:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 22:27:17.950  2185  2185 E audit   : type=1320 msg=audit(1471033637.950:284): 
08-12 22:27:17.960  6480  6480 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:17.960  6480  6480 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:17.970   775  2269 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3077b11 6480:com.samsung.android.provider.shootingmodeprovider/u0a169}
08-12 22:27:17.970  6480  6480 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
08-12 22:27:17.980  6480  6480 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
08-12 22:27:18.000   775  2100 I ActivityManager: Killing 4994:com.android.mms/u0a49 (adj 15): DHA:empty #37
08-12 22:27:18.000  2185  2185 E audit   : type=1400 msg=audit(1471033638.000:285): avc:  denied  { execmod } for  pid=6401 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 22:27:18.000  2185  2185 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:18.000  2185  2185 E audit   : type=1300 msg=audit(1471033638.000:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f75000 a1=51000 a2=5 a3=4 items=0 ppid=3505 ppcomm=adbd pid=6401 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 22:27:18.000  2185  2185 E audit   : type=1327 msg=audit(1471033638.000:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 22:27:18.000  2185  2185 E audit   : type=1320 msg=audit(1471033638.000:285): 
08-12 22:27:18.010   775  2100 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12826 1650:com.android.phone/1001}
08-12 22:27:18.020   775  1694 D CountryDetector: No listener is left
08-12 22:27:18.020   775  2271 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f1461cc 1792:com.google.android.googlequicksearchbox:search/u0a61}
08-12 22:27:18.020   775  1638 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
08-12 22:27:18.040   775  2268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f1461cc 1792:com.google.android.googlequicksearchbox:search/u0a61}
08-12 22:27:18.050   775  1638 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b7ca77 6342:com.samsung.android.sm.provider/1000}
08-12 22:27:18.050  2185  2185 E audit   : type=1400 msg=audit(1471033638.050:286): avc:  denied  { execmod } for  pid=6401 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 22:27:18.050  2185  2185 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:18.050  2185  2185 E audit   : type=1300 msg=audit(1471033638.050:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f75000 a1=51000 a2=5 a3=4 items=0 ppid=3505 ppcomm=adbd pid=6401 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 22:27:18.050  2185  2185 E audit   : type=1327 msg=audit(1471033638.050:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 22:27:18.050  2185  2185 E audit   : type=1320 msg=audit(1471033638.050:286): 
08-12 22:27:18.050  6401  6401 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 22:27:18.060  6401  6401 D AndroidRuntime: CheckJNI is OFF
08-12 22:27:18.060  6401  6401 D AndroidRuntime: readGMSProperty: start
08-12 22:27:18.060  6401  6401 D AndroidRuntime: readGMSProperty: already setted!!
08-12 22:27:18.060  6401  6401 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 22:27:18.060  6401  6401 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 22:27:18.060  6401  6401 D AndroidRuntime: readGMSProperty: end
08-12 22:27:18.060  6401  6401 D AndroidRuntime: addProductProperty: start
08-12 22:27:18.060  1792  6492 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 22:27:18.060  6401  6401 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 22:27:18.060  6401  6401 W art     : aedd9000-b1cff000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 22:27:18.060  6401  6401 W art     : b1cff000-b3f6e000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 22:27:18.060  6401  6401 W art     : b3f6e000-b3f6f000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 22:27:18.060  6401  6401 W art     : b3f6f000-b3f70000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.060  6401  6401 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 22:27:18.060  6401  6401 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 22:27:18.060  6401  6401 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 22:27:18.060  6401  6401 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 22:27:18.060  6401  6401 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 22:27:18.060  6401  6401 W art     : b4842000-b4845000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 22:27:18.060  6401  6401 W art     : b4845000-b4846000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 22:27:18.060  6401  6401 W art     : b4846000-b4847000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 22:27:18.060  6401  6401 W art     : b4847000-b4848000 r--p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b4848000-b4868000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 22:27:18.060  6401  6401 W art     : b4868000-b5279000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 22:27:18.060  6401  6401 W art     : b5279000-b527a000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b527a000-b52c3000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 22:27:18.060  6401  6401 W art     : b52c3000-b52c4000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 22:27:18.060  6401  6401 W art     : b52c4000-b52cc000 rw-p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b52cc000-b52cd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.060  6401  6401 W art     : b52cd000-b5302000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 22:27:18.060  6401  6401 W art     : b5302000-b5303000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5303000-b5304000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 22:27:18.060  6401  6401 W art     : b5304000-b5305000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 22:27:18.060  6401  6401 W art     : b5305000-b535d000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 22:27:18.060  6401  6401 W art     : b535d000-b535e000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b535e000-b535f000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 22:27:18.060  6401  6401 W art     : b535f000-b5360000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 22:27:18.060  6401  6401 W art     : b5361000-b5367000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 22:27:18.060  6401  6401 W art     : b5367000-b5368000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 22:27:18.060  6401  6401 W art     : b5368000-b5369000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 22:27:18.060  6401  6401 W art     : b5369000-b536b000 rw-p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b536c000-b5376000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 22:27:18.060  6401  6401 W art     : b5376000-b5379000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 22:27:18.060  6401  6401 W art     : b5379000-b537a000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 22:27:18.060  6401  6401 W art     : b537b000-b5392000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 22:27:18.060  6401  6401 W art     : b5392000-b5393000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5393000-b5394000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 22:27:18.060  6401  6401 W art     : b5394000-b5395000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 22:27:18.060  6401  6401 W art     : b5396000-b53a0000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 22:27:18.060  6401  6401 W art     : b53a0000-b53a1000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 22:27:18.060  6401  6401 W art     : b53a1000-b53a2000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 22:27:18.060  6401  6401 W art     : b53a2000-b53a6000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 22:27:18.060  6401  6401 W art     : b53a6000-b53a7000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 22:27:18.060  6401  6401 W art     : b53a7000-b53a8000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 22:27:18.060  6401  6401 W art     : b53a8000-b53be000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-12 22:27:18.060  6401  6401 W art     : b53be000-b53bf000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 22:27:18.060  6401  6401 W art     : b53bf000-b53c0000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 22:27:18.060  6401  6401 W art     : b53c0000-b53cd000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 22:27:18.060  6401  6401 W art     : b53cd000-b53ce000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 22:27:18.060  6401  6401 W art     : b53ce000-b53cf000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 22:27:18.060  6401  6401 W art     : b53cf000-b542f000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 22:27:18.060  6401  6401 W art     : b542f000-b5432000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 22:27:18.060  6401  6401 W art     : b5432000-b5436000 rw-p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5436000-b5497000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 22:27:18.060  6401  6401 W art     : b5497000-b5498000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 22:27:18.060  6401  6401 W art     : b5498000-b54e7000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 22:27:18.060  6401  6401 W art     : b54e7000-b54e9000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 22:27:18.060  6401  6401 W art     : b54e9000-b54ea000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 22:27:18.060  6401  6401 W art     : b54ea000-b54eb000 rw-p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b54eb000-b54f2000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 22:27:18.060  6401  6401 W art     : b54f2000-b54f3000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 22:27:18.060  6401  6401 W art     : b54f3000-b54f4000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 22:27:18.060  6401  6401 W art     : b54f5000-b54f8000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 22:27:18.060  6401  6401 W art     : b54f8000-b54f9000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 22:27:18.060  6401  6401 W art     : b54f9000-b54fa000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 22:27:18.060  6401  6401 W art     : b54fb000-b54ff000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 22:27:18.060  6401  6401 W art     : b54ff000-b5500000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5500000-b5501000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 22:27:18.060  6401  6401 W art     : b5501000-b5502000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-12 22:27:18.060  6401  6401 W art     : b5503000-b5520000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 22:27:18.060  6401  6401 W art     : b5520000-b5521000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 22:27:18.060  6401  6401 W art     : b5521000-b5522000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 22:27:18.060  6401  6401 W art     : b5523000-b5528000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 22:27:18.060  6401  6401 W art     : b5528000-b5529000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 22:27:18.060  6401  6401 W art     : b5529000-b552a000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 22:27:18.060  6401  6401 W art     : b552b000-b555c000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 22:27:18.060  6401  6401 W art     : b555c000-b555f000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 22:27:18.060  6401  6401 W art     : b555f000-b5560000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 22:27:18.060  6401  6401 W art     : b5561000-b559c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 22:27:18.060  6401  6401 W art     : b559c000-b559d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 22:27:18.060  6401  6401 W art     : b559d000-b559e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 22:27:18.060  6401  6401 W art     : b559f000-b55a6000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 22:27:18.060  6401  6401 W art     : b55a6000-b55a7000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b55a7000-b55a8000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 22:27:18.060  6401  6401 W art     : b55a8000-b55a9000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 22:27:18.060  6401  6401 W art     : b55a9000-b55aa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.060  6401  6401 W art     : b55aa000-b55c1000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 22:27:18.060  6401  6401 W art     : b55c1000-b55c2000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b55c2000-b55c5000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 22:27:18.060  6401  6401 W art     : b55c5000-b55c6000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 22:27:18.060  6401  6401 W art     : b55c6000-b55e5000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 22:27:18.060  6401  6401 W art     : b55e5000-b55e6000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 22:27:18.060  6401  6401 W art     : b55e6000-b55e7000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-12 22:27:18.060  6401  6401 W art     : b55e7000-b5625000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 22:27:18.060  6401  6401 W art     : b5625000-b5626000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5626000-b5628000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 22:27:18.060  6401  6401 W art     : b5628000-b5629000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 22:27:18.060  6401  6401 W art     : b562a000-b5631000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 22:27:18.060  6401  6401 W art     : b5631000-b5632000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 22:27:18.060  6401  6401 W art     : b5632000-b5633000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 22:27:18.060  6401  6401 W art     : b5634000-b5637000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 22:27:18.060  6401  6401 W art     : b5637000-b5638000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 22:27:18.060  6401  6401 W art     : b5638000-b5639000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 22:27:18.060  6401  6401 W art     : b5639000-b563f000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 22:27:18.060  6401  6401 W art     : b563f000-b5640000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5640000-b5641000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 22:27:18.060  6401  6401 W art     : b5641000-b5642000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 22:27:18.060  6401  6401 W art     : b5642000-b564b000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 22:27:18.060  6401  6401 W art     : b564b000-b564c000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 22:27:18.060  6401  6401 W art     : b564c000-b564d000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 22:27:18.060  6401  6401 W art     : b564d000-b56de000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 22:27:18.060  6401  6401 W art     : b56de000-b56df000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b56df000-b56ea000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 22:27:18.060  6401  6401 W art     : b56ea000-b56eb000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 22:27:18.060  6401  6401 W art     : b56ec000-b56fe000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 22:27:18.060  6401  6401 W art     : b56fe000-b56ff000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 22:27:18.060  6401  6401 W art     : b56ff000-b5700000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 22:27:18.060  6401  6401 W art     : b5701000-b5706000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 22:27:18.060  6401  6401 W art     : b5706000-b5707000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 22:27:18.060  6401  6401 W art     : b5707000-b5708000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 22:27:18.060  6401  6401 W art     : b5709000-b5776000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 22:27:18.060  6401  6401 W art     : b5776000-b5777000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5777000-b5779000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 22:27:18.090  6494  6494 I libpersona: KNOX_SDCARD checking this for 5012
08-12 22:27:18.060  6401  6401 W art     : b5779000-b577a000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 22:27:18.090  6494  6494 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:18.060  6401  6401 W art     : b577a000-b577b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.060  6401  6401 W art     : b577b000-b5782000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 22:27:18.060  6401  6401 W art     : b5782000-b5783000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 22:27:18.060  6401  6401 W art     : b5783000-b5784000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 22:27:18.090   775  1411 I ActivityManager: Start proc 6494:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-12 22:27:18.060  6401  6401 W art     : b5785000-b5805000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 22:27:18.060  6401  6401 W art     : b5805000-b5806000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5806000-b5807000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 22:27:18.060  6401  6401 W art     : b5807000-b5808000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 22:27:18.060  6401  6401 W art     : b5808000-b581f000 rw-p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b581f000-b5856000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 22:27:18.060  6401  6401 W art     : ib/libqc-opt.so
08-12 22:27:18.060  6401  6401 W art     : b5856000-b5857000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 22:27:18.060  6401  6401 W art     : b5857000-b5858000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 22:27:18.060  6401  6401 W art     : b5858000-b5874000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 22:27:18.060  6401  6401 W art     : b5874000-b5875000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 22:27:18.060  6401  6401 W art     : b5875000-b5876000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 22:27:18.060  6401  6401 W art     : b5877000-b58d8000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 22:27:18.060  6401  6401 W art     : b58d8000-b58da000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 22:27:18.060  6401  6401 W art     : b58da000-b58db000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 22:27:18.060  6401  6401 W art     : b58dc000-b5903000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 22:27:18.060  6401  6401 W art     : b5903000-b5904000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5904000-b5905000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 22:27:18.060  6401  6401 W art     : b5905000-b5906000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 22:27:18.060  6401  6401 W art     : b5907000-b590f000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 22:27:18.060  6401  6401 W art     : b590f000-b5911000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 22:27:18.060  6401  6401 W art     : b5911000-b5912000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 22:27:18.060  6401  6401 W art     : b5913000-b5916000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 22:27:18.060  6401  6401 W art     : b5916000-b5917000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 22:27:18.060  6401  6401 W art     : b5917000-b5918000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 22:27:18.060  6401  6401 W art     : b5918000-b591c000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 22:27:18.060  6401  6401 W art     : b591c000-b591d000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b591d000-b591e000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 22:27:18.060  6401  6401 W art     : b591e000-b591f000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 22:27:18.060  6401  6401 W art     : b591f000-b592f000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 22:27:18.060  6401  6401 W art     : b592f000-b5930000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 22:27:18.060  6401  6401 W art     : b5930000-b5931000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 22:27:18.060  6401  6401 W art     : b5931000-b5977000 rw-p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5977000-b5980000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 22:27:18.060  6401  6401 W art     : b5980000-b5981000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 22:27:18.060  6401  6401 W art     : b5981000-b5982000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 22:27:18.060  6401  6401 W art     : b5983000-b5988000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 22:27:18.060  6401  6401 W art     : b5988000-b5989000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 22:27:18.060  6401  6401 W art     : b5989000-b598a000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 22:27:18.060  6401  6401 W art     : b598a000-b598d000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 22:27:18.060  6401  6401 W art     : b598d000-b598e000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b598e000-b598f000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 22:27:18.060  6401  6401 W art     : b598f000-b5990000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 22:27:18.060  6401  6401 W art     : b5991000-b59a9000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 22:27:18.060  6401  6401 W art     : b59a9000-b59aa000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b59aa000-b59ab000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 22:27:18.060  6401  6401 W art     : b59ab000-b59ac000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 22:27:18.060  6401  6401 W art     : b59ad000-b5b47000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 22:27:18.060  6401  6401 W art     : b5b47000-b5b48000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5b48000-b5b55000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 22:27:18.060  6401  6401 W art     : b5b55000-b5b56000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 22:27:18.060  6401  6401 W art     : b5b56000-b5b5a000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 22:27:18.060  6401  6401 W art     : b5b5a000-b5b5b000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5b5b000-b5b5c000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 22:27:18.060  6401  6401 W art     : b5b5c000-b5b5d000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 22:27:18.060  6401  6401 W art     : b5b5d000-b5b70000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 22:27:18.060  6401  6401 W art     : b5b70000-b5b71000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 22:27:18.060  6401  6401 W art     : b5b71000-b5b72000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 22:27:18.060  6401  6401 W art     : b5b73000-b5bbe000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 22:27:18.060  6401  6401 W art     : b5bbe000-b5bbf000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 22:27:18.060  6401  6401 W art     : b5bbf000-b5bc0000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 22:27:18.060  6401  6401 W art     : b5bc0000-b5bc2000 rw-p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5bc2000-b5bc3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:27:18.060  6401  6401 W art     : b5bc3000-b5bd4000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 22:27:18.060  6401  6401 W art     : b5bd4000-b5bd5000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5bd5000-b5bd6000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 22:27:18.060  6401  6401 W art     : b5bd6000-b5bd7000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 22:27:18.060  6401  6401 W art     : b5bd8000-b5be2000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 22:27:18.060  6401  6401 W art     : b5be2000-b5be4000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 22:27:18.060  6401  6401 W art     : b5be4000-b5be5000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 22:27:18.060  6401  6401 W art     : b5be5000-b5bfe000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 22:27:18.060  6401  6401 W art     : b5bfe000-b5bff000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 22:27:18.060  6401  6401 W art     : b5bff000-b5c02000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 22:27:18.060  6401  6401 W art     : b5c02000-b5c06000 rw-p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5c06000-b5c7a000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 22:27:18.060  6401  6401 W art     : b5c7a000-b5c7b000 ---p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5c7b000-b5c7e000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 22:27:18.060  6401  6401 W art     : b5c7e000-b5c7f000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 22:27:18.060  6401  6401 W art     : b5c80000-b5c83000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 22:27:18.060  6401  6401 W art     : b5c83000-b5c84000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 22:27:18.060  6401  6401 W art     : b5c84000-b5c85000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 22:27:18.060  6401  6401 W art     : b5c85000-b5c86000 r--p 00000000 00:00 0 
08-12 22:27:18.060  6401  6401 W art     : b5c86000-b5c8b000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 22:27:18.060  6401  6401 W art     : b5c8b000-b5c8c000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 22:27:18.060  6401  6401 W art     : b5c8c000-b5c8d000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 22:27:18.060  6401  6401 W art     : b5c8d000-b5c8e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b5c8e000-b5c91000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 22:27:18.070  6401  6401 W art     : b5c91000-b5c92000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 22:27:18.070  6401  6401 W art     : b5c92000-b5c93000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 22:27:18.070  6401  6401 W art     : b5c93000-b5c94000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b5c94000-b5c98000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 22:27:18.070  6401  6401 W art     : b5c98000-b5c99000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 22:27:18.070  6401  6401 W art     : b5c99000-b5c9a000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 22:27:18.070  6401  6401 W art     : b5c9a000-b5c9b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:27:18.070  6401  6401 W art     : b5c9b000-b5c9f000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 22:27:18.070  6401  6401 W art     : b5c9f000-b5ca0000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 22:27:18.070  6401  6401 W art     : b5ca0000-b5ca1000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 22:27:18.070  6401  6401 W art     : b5ca1000-b5ca2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b5ca2000-b5cb0000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 22:27:18.070  6401  6401 W art     : b5cb0000-b5cb1000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b5cb1000-b5cb2000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 22:27:18.070  6401  6401 W art     : b5cb2000-b5cb3000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 22:27:18.070  6401  6401 W art     : b5cb3000-b5cbd000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 22:27:18.070  6401  6401 W art     : b5cbd000-b5cc0000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 22:27:18.070  6401  6401 W art     : b5cc0000-b5cc1000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 22:27:18.070  6401  6401 W art     : b5cc1000-b5cc2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b5cc2000-b5ccc000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 22:27:18.070  6401  6401 W art     : b5ccc000-b5ccf000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 22:27:18.070  6401  6401 W art     : b5ccf000-b5cd0000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 22:27:18.070  6401  6401 W art     : b5cd0000-b5cd4000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 22:27:18.070  6401  6401 W art     : b5cd4000-b5cd5000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 22:27:18.070  6401  6401 W art     : b5cd5000-b5cd6000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 22:27:18.070  6401  6401 W art     : b5cd6000-b5cd7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b5cd7000-b5ce4000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 22:27:18.070  6401  6401 W art     : b5ce4000-b5ce6000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 22:27:18.070  6401  6401 W art     : b5ce6000-b5ce7000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 22:27:18.070  6401  6401 W art     : b5ce7000-b60f9000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 22:27:18.070  6401  6401 W art     : b60f9000-b60fa000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b60fa000-b6103000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 22:27:18.070  6401  6401 W art     : b6103000-b6107000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 22:27:18.070  6401  6401 W art     : b6107000-b6108000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6108000-b610f000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-12 22:27:18.070  6401  6401 W art     : ioutils.so
08-12 22:27:18.070  6401  6401 W art     : b610f000-b6110000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 22:27:18.070  6401  6401 W art     : b6110000-b6111000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 22:27:18.070  6401  6401 W art     : b6111000-b6112000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b6112000-b612d000 r-xp 00000000
08-12 22:27:18.070  6401  6401 W art     :  b3:17 1184       /system/lib/libz.so
08-12 22:27:18.070  6401  6401 W art     : b612d000-b612e000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 22:27:18.070  6401  6401 W art     : b612e000-b612f000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 22:27:18.070  6401  6401 W art     : b612f000-b6130000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b6130000-b617c000 r-xp 00000000 b3:17 994        
08-12 22:27:18.070  6401  6401 W art     : /system/lib/libharfbuzz_ng.so
08-12 22:27:18.070  6401  6401 W art     : b617c000-b617d000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b617d000-b617e000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 22:27:18.070  6401  6401 W art     : b617e000-b617f000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 22:27:18.070  6401  6401 W art     : b617f000-b6180000 r--p 00000000 00:00 0          [anon:li
08-12 22:27:18.070  6401  6401 W art     : nker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b6180000-b6184000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 22:27:18.070  6401  6401 W art     : b6184000-b6185000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6185000-b6186000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 22:27:18.070  6401  6401 W art     : b6186000-b6187000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-12 22:27:18.070  6401  6401 W art     : sbhost.so
08-12 22:27:18.070  6401  6401 W art     : b6187000-b61bf000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 22:27:18.070  6401  6401 W art     : b61bf000-b61c0000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 22:27:18.070  6401  6401 W art     : b61c0000-b61c1000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 22:27:18.070  6401  6401 W art     : b61c1000-b61c2000 r--p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     :          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b61c2000-b6260000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 22:27:18.070  6401  6401 W art     : b6260000-b6261000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6261000-b627f000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 22:27:18.070  6401  6401 W art     : b627f000-b6280000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
08-12 22:27:18.070  6401  6401 W art     : .so
08-12 22:27:18.070  6401  6401 W art     : b6280000-b63f3000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 22:27:18.070  6401  6401 W art     : b63f3000-b63fe000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 22:27:18.070  6401  6401 W art     : b63fe000-b63ff000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 22:27:18.070  6401  6401 W art     : b63ff000-b6516000 r-xp 00000000
08-12 22:27:18.070  6401  6401 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-12 22:27:18.070  6401  6401 W art     : b6516000-b6521000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 22:27:18.070  6401  6401 W art     : b6521000-b6522000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 22:27:18.070  6401  6401 W art     : b6522000-b6526000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6526000-b654a000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
08-12 22:27:18.070  6401  6401 W art     : o
08-12 22:27:18.070  6401  6401 W art     : b654a000-b654c000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 22:27:18.070  6401  6401 W art     : b654c000-b654d000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 22:27:18.070  6401  6401 W art     : b654d000-b65f3000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 22:27:18.070  6401  6401 W art     : b65f3000-b6600000 r--p 000a5000 b3:17 13
08-12 22:27:18.070  6401  6401 W art     : 2        /system/lib/libcrypto.so
08-12 22:27:18.070  6401  6401 W art     : b6600000-b6601000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 22:27:18.070  6401  6401 W art     : b6601000-b6602000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6602000-b6655000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 22:27:18.070  6401  6401 W art     : b6655000-b6656000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6656000-b6657000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 22:27:18.070  6401  6401 W art     : b6657000-b6658000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 22:27:18.070  6401  6401 W art     : b6658000-b665d000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b665d000-b666f000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 22:27:18.070  6401  6401 W art     : b666f000-b6670000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6670000-b6671000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 22:27:18.070  6401  6401 W art     : b6671000-b6672000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 22:27:18.070  6401  6401 W art     : b6672000-b6679000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 22:27:18.070  6401  6401 W art     : b6679000-b667a000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 22:27:18.070  6401  6401 W art     : b667a000-b667b000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 22:27:18.070  6401  6401 W art     : b667b000-b667c000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b667c000-b667f000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 22:27:18.070  6401  6401 W art     : b667f000-b6680000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 22:27:18.070  6401  6401 W art     : b6680000-b6681000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 22:27:18.070  6401  6401 W art     : b6681000-b6685000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 22:27:18.070  6401  6401 W art     : b6685000-b6686000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 22:27:18.070  6401  6401 W art     : b6686000-b6687000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 22:27:18.070  6401  6401 W art     : b6687000-b6695000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 22:27:18.070  6401  6401 W art     : b6695000-b6696000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6696000-b6697000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 22:27:18.070  6401  6401 W art     : b6697000-b6698000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 22:27:18.070  6401  6401 W art     : b6698000-b66a1000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 22:27:18.070  6401  6401 W art     : b66a1000-b66a2000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 22:27:18.070  6401  6401 W art     : b66a2000-b66a3000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 22:27:18.070  6401  6401 W art     : b66a3000-b6709000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 22:27:18.070  6401  6401 W art     : b6709000-b670a000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b670a000-b670c000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 22:27:18.070  6401  6401 W art     : b670c000-b6715000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 22:27:18.070  6401  6401 W art     : b6715000-b6718000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6718000-b67af000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 22:27:18.070  6401  6401 W art     : b67af000-b67b1000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 22:27:18.070  6401  6401 W art     : b67b1000-b67b2000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 22:27:18.070  6401  6401 W art     : b67b2000-b67b3000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b67b3000-b6ad4000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 22:27:18.070  6401  6401 W art     : b6ad4000-b6ad5000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6ad5000-b6af0000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 22:27:18.070  6401  6401 W art     : b6af0000-b6af4000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 22:27:18.070  6401  6401 W art     : b6af4000-b6af9000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6af9000-b6b01000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 22:27:18.070  6401  6401 W art     : b6b01000-b6b02000 r--p 00007000 b3:,17 2591       /system/lib/libcamera_metadata.so
08-12 22:27:18.070  6401  6401 W art     : b6b02000-b6b03000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 22:27:18.070  6401  6401 W art     : b6b03000-b6b31000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 22:27:18.070  6401  6401 W art     : b6b31000-b6b32000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6b32000-b6b39000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 22:27:18.070  6401  6401 W art     : b6b39000-b6b3a000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 22:27:18.070  6401  6401 W art     : b6b3a000-b6b80000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 22:27:18.070  6401  6401 W art     : b6b80000-b6b81000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6b81000-b6b84000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 22:27:18.070  6401  6401 W art     : b6b84000-b6b85000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 22:27:18.070  6401  6401 W art     : b6b85000-b6ba0000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 22:27:18.070  6401  6401 W art     : b6ba0000-b6ba4000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 22:27:18.070  6401  6401 W art     : b6ba4000-b6ba5000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 22:27:18.070  6401  6401 W art     : b6ba5000-b6bf2000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 22:27:18.070  6401  6401 W art     : b6bf2000-b6bf3000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6bf3000-b6bff000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 22:27:18.070  6401  6401 W art     : b6bff000-b6c00000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 22:27:18.070  6401  6401 W art     : b6c00000-b6c0d000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 22:27:18.070  6401  6401 W art     : b6c0d000-b6c0e000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6c0e000-b6c0f000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 22:27:18.070  6401  6401 W art     : b6c0f000-b6c10000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 22:27:18.070  6401  6401 W art     : b6c10000-b6c18000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 22:27:18.070  6401  6401 W art     : b6c18000-b6c19000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6c19000-b6c1a000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 22:27:18.070  6401  6401 W art     : b6c1a000-b6c1b000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 22:27:18.070  6401  6401 W art     : b6c1b000-b6c22000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 22:27:18.070  6401  6401 W art     : b6c22000-b6c23000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 22:27:18.070  6401  6401 W art     : b6c23000-b6c24000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 22:27:18.070  6401  6401 W art     : b6c24000-b6c38000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 22:27:18.070  6401  6401 W art     : b6c38000-b6c3a000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 22:27:18.070  6401  6401 W art     : b6c3a000-b6c3b000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 22:27:18.070  6401  6401 W art     : b6c3b000-b6c63000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 22:27:18.070  6401  6401 W art     : b6c63000-b6c65000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 22:27:18.070  6401  6401 W art     : b6c65000-b6c66000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 22:27:18.070  6401  6401 W art     : b6c66000-b6c69000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 22:27:18.070  6401  6401 W art     : b6c69000-b6c6a000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 22:27:18.070  6401  6401 W art     : b6c6a000-b6c6b000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 22:27:18.070  6401  6401 W art     : b6c6b000-b6c74000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 22:27:18.070  6401  6401 W art     : b6c74000-b6c75000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 22:27:18.070  6401  6401 W art     : b6c75000-b6c76000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 22:27:18.070  6401  6401 W art     : b6c76000-b6c96000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 22:27:18.070  6401  6401 W art     : b6c96000-b6c97000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 22:27:18.070  6401  6401 W art     : b6c97000-b6c98000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 22:27:18.070  6401  6401 W art     : b6c98000-b6d0b000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 22:27:18.070  6401  6401 W art     : b6d0b000-b6d0f000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 22:27:18.070  6401  6401 W art     : b6d0f000-b6d12000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 22:27:18.070  6401  6401 W art     : b6d12000-b6d1c000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6d1c000-b6da4000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 22:27:18.070  6401  6401 W art     : b6da4000-b6da5000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6da5000-b6da9000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 22:27:18.070  6401  6401 W art     : b6da9000-b6daa000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 22:27:18.070  6401  6401 W art     : b6daa000-b6dab000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6dab000-b6dd4000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 22:27:18.070  6401  6401 W art     : b6dd4000-b6dd5000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6dd5000-b6dd8000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 22:27:18.070  6401  6401 W art     : b6dd8000-b6dd9000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 22:27:18.070  6401  6401 W art     : b6dd9000-b6eb3000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 22:27:18.070  6401  6401 W art     : b6eb3000-b6eba000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 22:27:18.070  6401  6401 W art     : b6eba000-b6ec2000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 22:27:18.070  6401  6401 W art     : b6ec2000-b6ec3000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6ec3000-b6ec4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:27:18.070  6401  6401 W art     : b6ec4000-b6ec5000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 22:27:18.070  6401  6401 W art     : b6ec5000-b6ec6000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b6ec6000-b6ec9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b6ec9000-b6eee000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 22:27:18.070  6401  6401 W art     : b6eee000-b6eef000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6eef000-b6ef6000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 22:27:18.070  6401  6401 W art     : b6ef6000-b6ef7000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 22:27:18.070  6401  6401 W art     : b6ef7000-b6efe000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 22:27:18.120  6505  6505 I libpersona: KNOX_SDCARD checking this for 10210
08-12 22:27:18.070  6401  6401 W art     : b6efe000-b6eff000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 22:27:18.120  6505  6505 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:18.070  6401  6401 W art     : b6eff000-b6f00000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 22:27:18.070  6401  6401 W art     : b6f00000-b6f01000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b6f01000-b6f19000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 22:27:18.070  6401  6401 W art     : b6f19000-b6f1a000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6f1a000-b6f1b000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 22:27:18.070  6401  6401 W art     : b6f1b000-b6f1c000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 22:27:18.070  6401  6401 W art     : b6f1c000-b6f2a000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 22:27:18.070  6401  6401 W art     : b6f2a000-b6f2b000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6f2b000-b6f2c000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 22:27:18.070  6401  6401 W art     : b6f2c000-b6f2d000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 22:27:18.070  6401  6401 W art     : b6f2d000-b6f2e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:27:18.070  6401  6401 W art     : b6f2e000-b6f30000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b6f30000-b6f31000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b6f31000-b6f32000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:27:18.070  6401  6401 W art     : b6f32000-b6f33000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 22:27:18.070  6401  6401 W art     : b6f33000-b6f34000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:27:18.070  6401  6401 W art     : b6f34000-b6f54000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 22:27:18.070  6401  6401 W art     : b6f54000-b6f55000 r--p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6f55000-b6f56000 ---p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6f56000-b6f58000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 22:27:18.070  6401  6401 W art     : b6f58000-b6f59000 r-xp 00000000 00:00 0          [sigpage]
08-12 22:27:18.070  6401  6401 W art     : b6f59000-b6f74000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 22:27:18.070  6401  6401 W art     : b6f74000-b6f75000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 22:27:18.070  6401  6401 W art     : b6f75000-b6f77000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 22:27:18.070  6401  6401 W art     : b6f77000-b6f79000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : b6f79000-b6f7e000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 22:27:18.070  6401  6401 W art     : b6f7e000-b6f7f000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 22:27:18.070  6401  6401 W art     : b6f7f000-b6f80000 rw-p 00000000 00:00 0 
08-12 22:27:18.070  6401  6401 W art     : bea45000-bea66000 rw-p 00000000 00:00 0          [stack]
08-12 22:27:18.070  6401  6401 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 22:27:18.090  6494  6494 E Zygote  : v2
08-12 22:27:18.090  6494  6494 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:18.090  6494  6494 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:18.090  6494  6494 E Zygote  : accessInfo : 0
08-12 22:27:18.130   775   856 I ActivityManager: Start proc 6505:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-12 22:27:18.090  6494  6494 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
08-12 22:27:18.110  6401  6401 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 22:27:18.120  6505  6505 E Zygote  : v2
08-12 22:27:18.120  6505  6505 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:18.120  6505  6505 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:18.120  6505  6505 E Zygote  : accessInfo : 0
08-12 22:27:18.120  6505  6505 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-12 22:27:18.140  6494  6494 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:18.140  6494  6494 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:18.160   775  2100 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fba6e4 6494:com.samsung.android.sm.devicesecurity/5012}
08-12 22:27:18.170  6401  6401 I Radio-JNI: register_android_hardware_Radio DONE
08-12 22:27:18.170  6494  6494 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-12 22:27:18.180  6401  6401 E AffinityControl: AffinityControl: registerfunction enter
08-12 22:27:18.180  6505  6505 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:18.180  6505  6505 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:18.180  6494  6494 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-12 22:27:18.190  6505  6505 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-12 22:27:18.200  6401  6401 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 22:27:18.200  1792  6492 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-12 22:27:18.210   775  2100 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-12 22:27:18.210  6505  6505 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-12 22:27:18.210  1792  6492 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-12 22:27:18.210  6505  6505 D AASAservice: onCreate()
08-12 22:27:18.220   775  2100 D ActivityManager: mDVFSHelper.acquire()
08-12 22:27:18.230   775  2100 D FocusedStackFrame: Set to : 0
08-12 22:27:18.230   775  2100 V WindowManager: addAppToken: AppWindowToken{4d49713 token=Token{1c0b202 ActivityRecord{57b74d u0 com.test.thalitest/.MainActivity t167}}} to stack=1 task=167 at 0
08-12 22:27:18.240  6525  6525 E Zygote  : v2
08-12 22:27:18.240  6525  6525 I libpersona: KNOX_SDCARD checking this for 10004
08-12 22:27:18.240  6525  6525 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:18.240  6525  6525 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:18.240  6525  6525 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:18.240   775  2100 I ActivityManager: Start proc 6525:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-12 22:27:18.240   775  2100 D InputDispatcher: Focused application set to: xxxx
08-12 22:27:18.240  6525  6525 E Zygote  : accessInfo : 0
08-12 22:27:18.240  6525  6525 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-12 22:27:18.240   775  2100 D InputDispatcher: Focus left window: 1663
08-12 22:27:18.240   775   907 D SecWifiDisplayUtil: Metadata value : none
08-12 22:27:18.250  4861  4861 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-12 22:27:18.250   775   907 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{485d58b V.E...... R.....ID 0,0-0,0}
08-12 22:27:18.250   775   907 D ISSUE_DEBUG: InputChannelName : 92c4a81 Starting com.test.thalitest
08-12 22:27:18.250   775  1669 I ActivityManager: Killing 5621:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
08-12 22:27:18.250  6401  6401 D AndroidRuntime: Shutting down VM
08-12 22:27:18.260   775  2103 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-12 22:27:18.270   775   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:775 uid:1000
08-12 22:27:18.270   775   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 22:27:18.270   775   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:775 uid:1000
08-12 22:27:18.270   775   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 22:27:18.270   293   293 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
08-12 22:27:18.290  6525  6525 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:18.290  6525  6525 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:18.290   775  1694 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
08-12 22:27:18.300   775   907 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-12 22:27:18.310   775  1669 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a8a723 3178:com.android.contacts/u0a19}
08-12 22:27:18.320   775  1677 V WindowOrientationListener: setCurrentAppOrientation :-1
08-12 22:27:18.320   775  1677 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-12 22:27:18.330   775  1677 D ActivityManager:  Launching com.test.thalitest, updated priority
08-12 22:27:18.330   775   907 V WindowStateAnimator: Finishing drawing window Window{92c4a81 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-12 22:27:18.330  1663  1852 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-12 22:27:18.330   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef79364
08-12 22:27:18.340  1663  1663 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-12 22:27:18.360   293   351 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
08-12 22:27:18.360   293   351 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
08-12 22:27:18.370   293  1506 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-12 22:27:18.370   293   351 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-12 22:27:18.380  2116  2131 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-12 22:27:18.380   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef793a4
08-12 22:27:18.380  1663  1663 V ActivityThread: updateVisibility : ActivityRecord{69f7ebc token=android.os.BinderProxy@825657b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-12 22:27:18.380  1663  1663 D Launcher: onTrimMemory. Level: 20
08-12 22:27:18.390   775   856 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-12 22:27:18.400   775   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{92c4a81 u0 d0 Starting com.test.thalitest}
08-12 22:27:18.400  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-12 22:27:18.400  6525  6525 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-12 22:27:18.420   775  1217 I ActivityManager: Start proc 6538:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-12 22:27:18.420  6538  6538 E Zygote  : v2
08-12 22:27:18.420  6538  6538 I libpersona: KNOX_SDCARD checking this for 10049
08-12 22:27:18.420  6538  6538 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:18.420  6538  6538 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:18.420  6538  6538 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:18.420  6538  6538 E Zygote  : accessInfo : 0
08-12 22:27:18.420  6538  6538 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-12 22:27:18.440  6525  6525 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-12 22:27:18.450   775  3391 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 22:27:18.450  6525  6525 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-12 22:27:18.460  6538  6538 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:18.460  6538  6538 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:18.470  4051  6537 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-12 22:27:18.480   775  1669 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{205b45f 6538:com.android.mms/u0a49}
,08-12 22:27:18.480  6525  6525 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-12 22:27:18.500  6538  6538 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 22:27:18.500  6525  6525 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 22:27:18.510  6525  6525 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-12 22:27:18.520  6525  6525 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 4958-4962)
,08-12 22:27:18.520  6525  6525 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-12 22:27:18.520  1792  6492 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 461 ms] updated apps [took 461 ms] 
,08-12 22:27:18.530  6538  6538 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-12 22:27:18.540  6525  6525 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {badf44b}
08-12 22:27:18.540  6525  6525 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 22:27:18.540  6525  6525 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 22:27:18.540  6538  6538 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-12 22:27:18.540  6525  6552 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-12 22:27:18.550  6525  6525 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-12 22:27:18.550  6538  6538 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-12 22:27:18.550   775   786 I art     : Background partial concurrent mark sweep GC freed 161276(9MB) AllocSpace objects, 10(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.924ms total 183.911ms
,08-12 22:27:18.560  6538  6559 D Mms/ArtClassLoader: init before art third
,08-12 22:27:18.570  6538  6558 D Mms/ArtClassLoader: init before art second
,08-12 22:27:18.570  6525  6525 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 22:27:18.570  6525  6525 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 22:27:18.570  6525  6525 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 22:27:18.570  6525  6525 I Adreno-EGL: Local Branch: ss
08-12 22:27:18.570  6525  6525 I Adreno-EGL: Remote Branch: 
08-12 22:27:18.570  6525  6525 I Adreno-EGL: Local Patches: 
08-12 22:27:18.570  6525  6525 I Adreno-EGL: Reconstruct Branch: 
,08-12 22:27:18.570  6538  6557 D Mms/ArtClassLoader: init before art first
,08-12 22:27:18.580  6538  6538 D Mms/TelephonyPermission: start operation mode monitor
,08-12 22:27:18.580  6538  6538 D Mms/TelephonyPermission: User ID is null set current User Id
08-12 22:27:18.580  6525  6525 D libEGL  : eglInitialize EGLDisplay = 0xbeb03dac
,08-12 22:27:18.600  6538  6538 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 22:27:18.600  6538  6559 D Mms/ArtClassLoader: init [DONE] art
,08-12 22:27:18.600  6538  6538 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 22:27:18.610   775  2269 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-12 22:27:18.610   775  2269 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-12 22:27:18.620  6538  6538 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-12 22:27:18.620  6538  6538 D Mms/TelephonyPermission: isDefault true
,08-12 22:27:18.620  6538  6538 D Mms/MmsApp: onCreate() com.android.mms
,08-12 22:27:18.660  6525  6525 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-12 22:27:18.670  6525  6525 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 22:27:18.670  6525  6525 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-12 22:27:18.670  6525  6525 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-12 22:27:18.680  6525  6525 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-12 22:27:18.690  6538  6538 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-12 22:27:18.690  6538  6538 D Mms/MmsApp: [start]    initCountryIso consume time = 139.009688
,08-12 22:27:18.690  6525  6525 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-12 22:27:18.690  5804  5845 I Finsky  : [825] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-12 22:27:18.700  5804  5804 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-12 22:27:18.700   775  2269 D CountryDetector: The first listener is added
,08-12 22:27:18.700  6525  6525 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-12 22:27:18.710  6538  6538 D Mms/MmsApp: [end]    initCountryIso consume time = 16.211614
08-12 22:27:18.710  6538  6538 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.097761
,08-12 22:27:18.710  6538  6538 D Mms/MmsConfig: before partial update
,08-12 22:27:18.730  6538  6557 D Mms/ArtClassLoader: init [DONE] art
,08-12 22:27:18.740  6538  6538 D Mms/MmsConfig: Load Resize quality : 80
,08-12 22:27:18.750  6538  6538 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 22:27:18.750  6538  6538 D EasySignUpManager_1.0.5: isAuth is false
08-12 22:27:18.750  6538  6538 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-12 22:27:18.750  6538  6538 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-12 22:27:18.750  6538  6538 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-12 22:27:18.750  6538  6538 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 22:27:18.750  6538  6538 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-12 22:27:18.750  6538  6538 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 22:27:18.750  6538  6538 D EasySignUpManager_1.0.5: isAuth is false
08-12 22:27:18.750  6538  6538 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-12 22:27:18.750  6538  6538 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-12 22:27:18.760  1650  1662 D TP/MmsSmsProvider: query, match:2117, calling pid = 6538, accessRestricted = false
,08-12 22:27:18.760  1650  1662 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 0.971 ms
,08-12 22:27:18.770  6538  6538 E CscParser: mps_code.dat does not exist
08-12 22:27:18.770  6538  6538 E CscParser: customer_path =/system/csc/customer.xml
08-12 22:27:18.770  6538  6538 E CscParser: fileName + /system/csc/customer.xml
,08-12 22:27:18.770  6525  6525 D SecWifiDisplayUtil: Metadata value : none
,08-12 22:27:18.770  6525  6525 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5be9a21 I.E...... R.....ID 0,0-0,0}
,08-12 22:27:18.780  6525  6582 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 22:27:18.780  6538  6558 D Mms/ArtClassLoader: init [DONE] art
08-12 22:27:18.780   775  2270 D ISSUE_DEBUG: InputChannelName : 60d330c com.test.thalitest/com.test.thalitest.MainActivity
,08-12 22:27:18.780   775  2104 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-12 22:27:18.780   775  2104 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-12 22:27:18.780   775   775 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 22:27:18.780   775   775 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-12 22:27:18.790  6538  6538 E CscParser: mps_code.dat does not exist
08-12 22:27:18.790  6538  6538 E CscParser: customer_path =/system/csc/customer.xml
08-12 22:27:18.790  6538  6538 E CscParser: fileName + /system/csc/customer.xml
,08-12 22:27:18.800  6525  6525 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6525
,08-12 22:27:18.800   775  2100 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6525 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 22:27:18.800   775  1331 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-12 22:27:18.800   775  1331 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-12 22:27:18.800   775  1331 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-12 22:27:18.800   775  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 22:27:18.800   775  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 22:27:18.800   775  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 22:27:18.800   775  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-12 22:27:18.800   775  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 22:27:18.800   775  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-12 22:27:18.800   775  1331 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 22:27:18.800  6538  6538 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-12 22:27:18.800  6538  6538 D Mms/MmsConfig:  enable multiwindow = true
,08-12 22:27:18.810  6538  6538 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-12 22:27:18.810  6538  6538 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-12 22:27:18.810  6538  6538 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-12 22:27:18.810  6538  6538 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-12 22:27:18.810   775  1694 I ActivityManager: Killing 5269:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-12 22:27:18.810  6538  6538 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-12 22:27:18.810  6538  6538 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-12 22:27:18.810  6538  6538 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-12 22:27:18.810  6538  6538 D Mms/MmsConfig: [end]    init() consume time = 106.047447
,08-12 22:27:18.810  6525  6525 D SecWifiDisplayUtil: Metadata value : none
,08-12 22:27:18.820  6525  6552 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-12 22:27:18.830   775  2103 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-12 22:27:18.830   293   293 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
08-12 22:27:18.830  6538  6538 D Mms/Contact: [start]    init() consume time = 20.374427
,08-12 22:27:18.840  6538  6538 D Mms/Contact: [end]    init consume time = 6.96698
,08-12 22:27:18.840  6538  6587 D Mms/DraftCache: [start]    rebuildCache consume time = 1.713802
,08-12 22:27:18.850   775   789 D InputDispatcher: Focus entered window: 6525
,08-12 22:27:18.850  1650  1866 D TP/MmsSmsProvider: query, match:13, calling pid = 6538, accessRestricted = false
,08-12 22:27:18.850  1650  1866 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.155 ms
,08-12 22:27:18.850   775   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:775 uid:1000
08-12 22:27:18.850  6525  6582 D libEGL  : eglInitialize EGLDisplay = 0x9cb397c4
08-12 22:27:18.850  6525  6582 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 22:27:18.850   775   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 22:27:18.850   775   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:775 uid:1000
08-12 22:27:18.850   775   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 22:27:18.850  6538  6538 D Mms:transaction: roaming -> false (slotId = 0)
08-12 22:27:18.850  6538  6538 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 22:27:18.850  6538  6538 D Mms:transaction: auto download without roaming -> true
08-12 22:27:18.850  6538  6538 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-12 22:27:18.850  6538  6538 D Mms:transaction: roaming -> false (slotId = 1)
08-12 22:27:18.850  6538  6538 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-12 22:27:18.850  6538  6538 D Mms:transaction: auto download without roaming -> true
08-12 22:27:18.850  6538  6538 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-12 22:27:18.850  6538  6538 D Mms:transaction: auto download during roaming secondary -> false
08-12 22:27:18.850  6538  6538 D Mms:transaction: mAutoDownload ------> true
,08-12 22:27:18.860  1650  1662 D TP/MmsSmsProvider: query, match:12, calling pid = 6538, accessRestricted = false
,08-12 22:27:18.860  1650  1662 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.056 ms
,08-12 22:27:18.870   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:27:18.870  6538  6587 D Mms/DraftCache: [end]    rebuildCache consume time = 27.709687
,08-12 22:27:18.870  6538  6538 D ComposerPerformance: 1471033638890 ms / [DONE] Composer constructor
,08-12 22:27:18.880  6538  6538 D CII     : Log Level [5]
,08-12 22:27:18.880  6538  6538 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
08-12 22:27:18.880  6538  6591 D Mms/Conversation: [start]    init() consume time = 6.153803
,08-12 22:27:18.880  6538  6538 I Mms/ReservationManager: ReservationManager()
,08-12 22:27:18.880  6538  6538 I Mms/ReservationManager: resetAfterConnected()
,08-12 22:27:18.880  1650  1903 D TP/MmsSmsProvider: delete, match:1, calling pid = 6538
,08-12 22:27:18.880  1650  1903 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-12 22:27:18.880  1650  1903 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-12 22:27:18.880  1650  1903 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-12 22:27:18.880  1650  1903 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,08-12 22:27:18.880  1650  1903 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-12 22:27:18.890  1650  1866 D TP/MmsSmsProvider: query, match:7, calling pid = 6538, accessRestricted = false
,08-12 22:27:18.890  1650  1866 D TP/MmsSmsProvider: query, match 7:Elapsed time : 1.460 ms
,08-12 22:27:18.890  1650  1903 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-12 22:27:18.890  6538  6538 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-12 22:27:18.890  6538  6538 D Mms/MmsApp: [end]    onCreate() consume time = 17.102968
08-12 22:27:18.890  6538  6538 D Mms/MmsApp: [end]    onCreate() consume time = 0.077344
,08-12 22:27:18.900  1650  1903 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-12 22:27:18.900  1650  1903 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,08-12 22:27:18.900  1650  1903 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-12 22:27:18.900  1650  1903 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 11.727 ms
08-12 22:27:18.900  1650  1903 D TP/MmsSmsProvider: need read changed broadcast:false
,08-12 22:27:18.900  6538  6591 D Mms/Conversation: [end]    init consume time = 5.905156
,08-12 22:27:18.900  6525  6525 V ActivityThread: updateVisibility : ActivityRecord{b3418a0 token=android.os.BinderProxy@7ffc088 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-12 22:27:18.910  6538  6591 D Mms/MessagingNotification: [start]    init() consume time = 6.067344
,08-12 22:27:18.910  6538  6538 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-12 22:27:18.910  6538  6538 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-12 22:27:18.910  6538  6538 D Mms:transaction: roaming -> false (slotId = 0)
08-12 22:27:18.910  6538  6538 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 22:27:18.910  6538  6538 D Mms:transaction: auto download without roaming -> true
08-12 22:27:18.910  6538  6538 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-12 22:27:18.910  6538  6538 D Mms:transaction: mAutoDownload ------> true
,08-12 22:27:18.910  6592  6592 E Zygote  : v2
,08-12 22:27:18.910  6592  6592 I libpersona: KNOX_SDCARD checking this for 1000
08-12 22:27:18.910  6592  6592 I libpersona: KNOX_SDCARD not a persona
,08-12 22:27:18.920   775  1669 I ActivityManager: Start proc 6592:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
08-12 22:27:18.920  6592  6592 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:18.920  6592  6592 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:18.920  6592  6592 E Zygote  : accessInfo : 0
,08-12 22:27:18.920   775  1669 I ActivityManager: Killing 5134:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-12 22:27:18.930  6538  6591 D Mms/MessagingNotification: [end]    init consume time = 19.237813
,08-12 22:27:18.930  6525  6525 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 22:27:18.930  6538  6600 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 4.231041
,08-12 22:27:18.940  1650  2656 D TP/MmsSmsProvider: query, match:0, calling pid = 6538, accessRestricted = false
08-12 22:27:18.940  1650  2656 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-12 22:27:18.940  1650  1662 D TP/MmsSmsProvider: query, match:400, calling pid = 6538, accessRestricted = false
08-12 22:27:18.940  1650  2656 D TP/MmsSmsProvider: query, match 0:Elapsed time : 0.165 ms
,08-12 22:27:18.950   775  2273 V WindowStateAnimator: Finishing drawing window Window{60d330c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-12 22:27:18.950  6525  6525 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-12 22:27:18.950  6538  6604 D Mms/Synchronizer: [start]    doSync consume time = 16.88073
,08-12 22:27:18.950  6525  6525 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 22:27:18.960   775  2103 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-12 22:27:18.960  1650  1665 D TP/MmsSmsProvider: update, match:300, calling pid = 6538
,08-12 22:27:18.960  1650  1665 V TP/MmsSmsProvider: syncDBData start
,08-12 22:27:18.960  1650  1665 V TP/MmsSmsProvider: syncDBData sms end
,08-12 22:27:18.960  1650  1665 V TP/MmsSmsProvider: syncDBData mms end
08-12 22:27:18.960  1650  1665 V TP/MmsSmsProvider: syncDBData end
,08-12 22:27:18.960  1650  1665 D TP/MmsSmsProvider: update, match 300:Elapsed time : 2.572 ms
,08-12 22:27:18.960   775   907 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 22:27:18.960   775   775 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-12 22:27:18.960  6538  6600 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 15.232343
08-12 22:27:18.960   775   907 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +576ms (total +734ms)
08-12 22:27:18.960   775   907 D ActivityManager: mDVFSHelper.release()
08-12 22:27:18.960   775   907 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{57b74d u0 com.test.thalitest/.MainActivity t167} time:105409
08-12 22:27:18.960   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef79364
08-12 22:27:18.970  6124  6142 D BadgeProvider: query, [selection] : package=?
08-12 22:27:18.970   775   775 I KnoxTimeoutHandler: SD activityfalse
08-12 22:27:18.970   775   907 D ViewRootImpl: #3 mView = null
,08-12 22:27:18.970   293   351 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
,08-12 22:27:18.970  6592  6592 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 22:27:18.970   293   359 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
08-12 22:27:18.970  6592  6592 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:18.980   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef793a4
,08-12 22:27:18.990  6538  6604 D Mms/Synchronizer: [end]    doSync consume time = 24.737084
,08-12 22:27:18.990   775  2103 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7843cc5 6592:com.samsung.android.bbc.bbcagent/1000}
,08-12 22:27:18.990   775  2100 V WindowStateAnimator: Finishing drawing window Window{60d330c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-12 22:27:18.990  6525  6525 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-12 22:27:18.990  6525  6525 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7ffc088 time:105436
,08-12 22:27:18.990   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef79364
,08-12 22:27:19.000   775  1694 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-12 22:27:19.010  6592  6592 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-12 22:27:19.010  6525  6609 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-12 22:27:19.010  6525  6609 D libEGL  : eglInitialize EGLDisplay = 0x9ab7f3ec
,08-12 22:27:19.020  6538  6591 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-12 22:27:19.030  1650  1903 D TP/SmsProvider: query,matched:26, calling pid = 6538
,08-12 22:27:19.030  1650  1903 D TP/SmsProvider: query, match 26:Elapsed time : 1.163 ms
,08-12 22:27:19.040  6592  6592 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-12 22:27:19.040  1650  1662 D TP/MmsSmsProvider: query, match:6, calling pid = 6538, accessRestricted = false
,08-12 22:27:19.050  1650  1662 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.479 ms
,08-12 22:27:19.060  6525  6525 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6525
,08-12 22:27:19.070  6612  6612 E Zygote  : v2
,08-12 22:27:19.070  6612  6612 I libpersona: KNOX_SDCARD checking this for 10024
08-12 22:27:19.070  6612  6612 I libpersona: KNOX_SDCARD not a persona
,08-12 22:27:19.070  6612  6612 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 22:27:19.070  6612  6612 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:19.070  6612  6612 E Zygote  : accessInfo : 0
,08-12 22:27:19.080  6612  6612 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-12 22:27:19.080   775  1694 I ActivityManager: Start proc 6612:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-12 22:27:19.090  6624  6624 E Zygote  : v2
08-12 22:27:19.090  6624  6624 I libpersona: KNOX_SDCARD checking this for 10097
08-12 22:27:19.090  6624  6624 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:19.090   775  2104 I ActivityManager: Start proc 6624:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-12 22:27:19.090  6624  6624 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 22:27:19.090  6624  6624 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:19.090  6624  6624 E Zygote  : accessInfo : 0
08-12 22:27:19.090  6624  6624 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-12 22:27:19.090   775  2104 I ActivityManager: Killing 5293:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-12 22:27:19.120  6612  6612 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:19.120  6612  6612 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:19.120  6624  6624 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 22:27:19.120  6624  6624 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:19.120   775  1411 I ActivityManager: Killing 5505:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-12 22:27:19.130   775  1217 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{330161a 6624:com.google.android.apps.docs/u0a97}
,08-12 22:27:19.130  6612  6612 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-12 22:27:19.140   775   789 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-12 22:27:19.140  6624  6624 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 22:27:19.150   775  2103 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-12 22:27:19.150  6612  6612 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-12 22:27:19.160  6624  6624 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-12 22:27:19.190  6525  6525 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 22:27:19.210  6612  6612 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-12 22:27:19.220  6538  6591 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-12 22:27:19.240  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-12 22:27:19.240  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-12 22:27:19.240  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-12 22:27:19.240  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-12 22:27:19.240  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-12 22:27:19.240  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-12 22:27:19.250  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-12 22:27:19.250  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-12 22:27:19.250  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-12 22:27:19.250  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-12 22:27:19.250  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-12 22:27:19.250  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-12 22:27:19.260  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-12 22:27:19.360  6525  6639 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1705772752
,08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24664f6 added. We now have 1 listener(s)
,08-12 22:27:19.370  6525  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-12 22:27:19.370  6525  6639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-12 22:27:19.370  6525  6639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 22:27:19.370  6525  6639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 22:27:19.370  6525  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10c31cd added. We now have 1 listener(s)
08-12 22:27:19.380  6525  6639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 22:27:19.380  6525  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 22:27:19.380  6525  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 22:27:19.380  6525  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-12 22:27:19.380  6525  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 22:27:19.380  6525  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 22:27:19.380  6525  6639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 22:27:19.380  6525  6639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-12 22:27:19.390  6525  6639 D BluetoothAdapter: STATE_ON
,08-12 22:27:19.390  6525  6639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 22:27:19.390  6525  6639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:27:19.390  6525  6639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:27:19.390  6525  6639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 22:27:19.390  6525  6639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:27:19.390  6525  6639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:27:19.390  6525  6639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:27:19.390  6525  6639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:27:19.390  6525  6639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 22:27:19.390  6525  6639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-12 22:27:19.390  6525  6639 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 22:27:19.390  6525  6639 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 22:27:19.390   775  3396 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-12 22:27:19.390  6525  6525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 22:27:19.390  6525  6525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 22:27:19.420  6525  6525 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 22:27:19.470  6624  6643 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-12 22:27:19.470  6624  6643 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-12 22:27:19.470  6624  6643 I GAv4    :   adb logcat -s GAv4
,08-12 22:27:19.500  6624  6643 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 22:27:19.500   775  1669 V AlarmManager:  remove PendingIntent] PendingIntent{e8bd740: PendingIntentRecord{8a05679 com.google.android.apps.docs broadcastIntent}}
,08-12 22:27:19.500  6624  6643 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-12 22:27:19.510  6624  6643 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-12 22:27:19.540  4051  4902 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-12 22:27:19.550  6624  6648 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-12 22:27:19.590  4051  4902 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-12 22:27:19.630  6624  6624 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-12 22:27:19.630  6624  6624 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-12 22:27:19.670  6624  6643 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-12 22:27:19.670  6624  6643 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-12 22:27:19.670  6624  6643 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,08-12 22:27:19.670  6624  6643 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-12 22:27:19.700  4051  4902 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-12 22:27:19.730  6658  6658 E Zygote  : v2
,08-12 22:27:19.730  6658  6658 I libpersona: KNOX_SDCARD checking this for 10098
08-12 22:27:19.730  6658  6658 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:19.730   775  2273 I ActivityManager: Start proc 6658:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-12 22:27:19.740  6658  6658 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 22:27:19.740  6658  6658 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:19.740  6658  6658 E Zygote  : accessInfo : 0
,08-12 22:27:19.740  6658  6658 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-12 22:27:19.740   775  2273 I ActivityManager: Killing 5243:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-12 22:27:19.770  6658  6658 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 22:27:19.770  6658  6658 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:19.780   775  2271 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c6e135 6658:com.sec.android.automotive.drivelink/u0a98}
,08-12 22:27:19.790  1453  1453 D Recents : onTaskStackChanged
,08-12 22:27:19.790  6658  6658 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 22:27:19.790  1453  1453 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 22:27:19.810   775  1217 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-12 22:27:19.830  6658  6658 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-12 22:27:19.860  6658  6658 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 22:27:19.870  1922  1922 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 22:27:19.870  1922  1922 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 22:27:19.880   775  1694 V AlarmManager:  remove PendingIntent] PendingIntent{2915bb1: PendingIntentRecord{dba2896 com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 22:27:19.890  6658  6671 I GMPM    : App measurement is starting up
,08-12 22:27:19.890  6658  6658 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-12 22:27:19.890  6658  6671 E GMPM    : getGoogleAppId failed with status: 10
,08-12 22:27:19.890  6658  6671 E GMPM    : Uploading is not possible. App measurement disabled
,08-12 22:27:19.890   775  2104 V AlarmManager:  remove PendingIntent] PendingIntent{aa52c17: PendingIntentRecord{dba2896 com.sec.android.automotive.drivelink broadcastIntent}}
,08-12 22:27:19.900  1922  1922 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 22:27:19.930  6658  6658 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-12 22:27:19.930  6658  6658 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-12 22:27:19.980  6624  6644 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 22:27:19.990  6678  6678 E Zygote  : v2
08-12 22:27:19.990  6678  6678 I libpersona: KNOX_SDCARD checking this for 10032
08-12 22:27:19.990  6678  6678 I libpersona: KNOX_SDCARD not a persona
,08-12 22:27:19.990   775  1694 I ActivityManager: Start proc 6678:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-12 22:27:19.990  6678  6678 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:19.990   775  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 22:27:19.990  6678  6678 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:19.990  6678  6678 E Zygote  : accessInfo : 0
,08-12 22:27:19.990  6678  6678 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-12 22:27:20.010  6678  6678 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:20.010  6678  6678 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:20.020   775  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 22:27:20.030  6678  6678 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-12 22:27:20.040  6678  6678 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-12 22:27:20.090  6624  6644 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-12 22:27:20.100  6624  6644 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-12 22:27:20.100  6624  6644 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-12 22:27:20.110  6624  6644 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 22:27:20.170  6624  6644 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 22:27:20.190  6658  6658 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-12 22:27:20.200  6678  6678 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-12 22:27:20.210  6658  6658 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-12 22:27:20.210  6658  6658 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-12 22:27:20.220  6678  6678 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-12 22:27:20.230  6658  6658 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDFri Aug 12 22:27:20 GMT+02:00 2016
,08-12 22:27:20.240  6658  6658 D DialogFlow: initQueue()
,08-12 22:27:20.240   775  2268 I ActivityManager: Start proc 6693:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-12 22:27:20.240  6693  6693 E Zygote  : v2
,08-12 22:27:20.240  6693  6693 I libpersona: KNOX_SDCARD checking this for 1000
08-12 22:27:20.240  6693  6693 I libpersona: KNOX_SDCARD not a persona
,08-12 22:27:20.240  6693  6693 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 22:27:20.240  6693  6693 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:20.250  6693  6693 E Zygote  : accessInfo : 0
,08-12 22:27:20.250   775  2268 I ActivityManager: Killing 4671:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-12 22:27:20.250   775  2268 I ActivityManager: Killing 5738:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-12 22:27:20.270  6693  6693 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:20.270  6693  6693 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:20.280   775  1638 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7cca97a 6693:com.samsung.android.app.filterinstaller/1000}
,08-12 22:27:20.300   775   788 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-12 22:27:20.310   775  2100 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-12 22:27:20.320  6693  6693 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-12 22:27:20.330  6693  6693 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-12 22:27:20.330  6693  6693 E FilterPackageIntentReceiver: This package is not a effect filter
,08-12 22:27:20.340  3613  3613 D FactoryTest: User mode
,08-12 22:27:20.340  3613  3613 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-12 22:27:20.340  3613  3613 D MTPRx   : still no open session command from host, so toast
,08-12 22:27:20.350  6708  6708 E Zygote  : v2
08-12 22:27:20.350  6708  6708 I libpersona: KNOX_SDCARD checking this for 1000
08-12 22:27:20.350   775  2270 I ActivityManager: Start proc 6708:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-12 22:27:20.350  6708  6708 I libpersona: KNOX_SDCARD not a persona
,08-12 22:27:20.350  6708  6708 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:20.350  6708  6708 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:20.350  6708  6708 E Zygote  : accessInfo : 0
,08-12 22:27:20.350   775  2270 I ActivityManager: Killing 5788:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-12 22:27:20.360   775  1694 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-12 22:27:20.360   775  1694 D ActivityManager: mDVFSHelper.acquire()
,08-12 22:27:20.360   775  1694 V WindowManager: addAppToken: AppWindowToken{7bf9321 token=Token{7f4fd88 ActivityRecord{c23852b u0 com.samsung.android.MtpApplication/.USBConnection t168}}} to stack=1 task=168 at 0
,08-12 22:27:20.360   775  1694 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-12 22:27:20.370  6708  6708 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:20.370  6708  6708 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:20.370   775   856 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-12 22:27:20.390   775  1694 D InputDispatcher: Focused application set to: xxxx
,08-12 22:27:20.390   775  1694 D InputDispatcher: Focus left window: 6525
,08-12 22:27:20.390  3613  3613 E MTPRx   : started activity for popup
,08-12 22:27:20.390   775   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:775 uid:1000
08-12 22:27:20.390  3613  3613 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-12 22:27:20.390   775   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 22:27:20.390   775   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:775 uid:1000
08-12 22:27:20.390   775   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 22:27:20.390  3613  3613 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-12 22:27:20.410   775  2273 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-12 22:27:20.410  3613  3613 D MTPUSBConnection: onCreate in USBConnection
,08-12 22:27:20.410  3613  3613 V MTPUSBConnection: Registering broadcast receiver.
,08-12 22:27:20.420   775  2268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7ebe346 6708:com.samsung.helphub/1000}
,08-12 22:27:20.420  3613  3613 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-12 22:27:20.430   775  1217 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-12 22:27:20.430  6708  6708 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-12 22:27:20.470   775  2104 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-12 22:27:20.490  3613  3613 D TAG     : dev.kiessupport is : TRUE
,08-12 22:27:20.490  6708  6708 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-12 22:27:20.520  6525  6640 W jxcore-log: Initializing JXcore engine
,08-12 22:27:20.520  6525  6640 W jxcore-log: JXcore engine is ready
08-12 22:27:20.520  3613  3613 D SecWifiDisplayUtil: Metadata value : none
,08-12 22:27:20.520  3613  3613 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{93c8078 V.E...... R.....I. 0,0-0,0}
,08-12 22:27:20.530  3613  6721 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 22:27:20.530   775  2269 D ISSUE_DEBUG: InputChannelName : ca6d8b8 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-12 22:27:20.530   775   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ca6d8b8 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-12 22:27:20.530   775  2269 D InputDispatcher: Focus entered window: 3613
,08-12 22:27:20.530   775   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:775 uid:1000
08-12 22:27:20.530   775   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 22:27:20.530   775   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:775 uid:1000
08-12 22:27:20.530   775   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 22:27:20.530  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-12 22:27:20.540  3613  3613 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{16ae690 I.E...... R.....I. 0,0-0,0}
,08-12 22:27:20.540   775  2103 D ISSUE_DEBUG: InputChannelName : 719a9f6 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-12 22:27:20.540   775  2269 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-12 22:27:20.540   775  2269 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 22:27:20.540   775   775 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 22:27:20.540   775   775 I KnoxTimeoutHandler: Shared devices show user statefalse
08-12 22:27:20.540   775   775 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-12 22:27:20.560  6678  6678 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-12 22:27:20.560  6678  6678 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-12 22:27:20.570  6722  6722 E Zygote  : v2
08-12 22:27:20.570  6722  6722 I libpersona: KNOX_SDCARD checking this for 1000
08-12 22:27:20.570  6722  6722 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:20.570  6722  6722 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:20.570  6722  6722 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:20.570  6722  6722 E Zygote  : accessInfo : 0
08-12 22:27:20.570  2185  2185 E audit   : type=1400 msg=audit(1471033640.570:287): avc:  denied  { ioctl } for  pid=6640 comm="Thread-915" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 22:27:20.570  2185  2185 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:20.570  2185  2185 E audit   : type=1300 msg=audit(1471033640.570:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a2ff3c8 items=0 ppid=360 ppcomm=main pid=6640 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-915" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 22:27:20.570  2185  2185 E audit   : type=1327 msg=audit(1471033640.570:287): proctitle="com.test.thalitest"
08-12 22:27:20.570  2185  2185 E audit   : type=1320 msg=audit(1471033640.570:287): 
08-12 22:27:20.570   775  1217 I ActivityManager: Start proc 6722:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-12 22:27:20.570  2185  2185 E audit   : type=1400 msg=audit(1471033640.570:288): avc:  denied  { ioctl } for  pid=6640 comm="Thread-915" path="socket:[38648]" dev="sockfs" ino=38648 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 22:27:20.570  2185  2185 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:20.570  2185  2185 E audit   : type=1300 msg=audit(1471033640.570:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9a2ff3c8 items=0 ppid=360 ppcomm=main pid=6640 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-915" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 22:27:20.580  2185  2185 E audit   : type=1327 msg=audit(1471033640.570:288): proctitle="com.test.thalitest"
08-12 22:27:20.580  2185  2185 E audit   : type=1320 msg=audit(1471033640.570:288): 
08-12 22:27:20.580   775  1217 I ActivityManager: Killing 5852:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-12 22:27:20.590   293   293 I SurfaceFlinger: id=16 createSurf (145x145),1 flag=4, VSBConnecti
,08-12 22:27:20.600  6525  6640 W jxcore-log: Starting JXcore engine
08-12 22:27:20.600  6722  6722 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:20.600  6722  6722 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:20.610  3613  6721 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 22:27:20.610  3613  6721 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 22:27:20.610  3613  6721 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 22:27:20.610  3613  6721 I Adreno-EGL: Local Branch: ss
08-12 22:27:20.610  3613  6721 I Adreno-EGL: Remote Branch: 
08-12 22:27:20.610  3613  6721 I Adreno-EGL: Local Patches: 
08-12 22:27:20.610  3613  6721 I Adreno-EGL: Reconstruct Branch: 
08-12 22:27:20.610  3613  6721 D libEGL  : eglInitialize EGLDisplay = 0x9ef7b7c4
08-12 22:27:20.610  3613  6721 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 22:27:20.630   775  1694 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1fa81f7 6722:com.samsung.android.app.mirrorlink/1000}
,08-12 22:27:20.650  6722  6722 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-12 22:27:20.660   293   293 I SurfaceFlinger: id=17 createSurf (193x193),1 flag=4, VSBConnecti
,08-12 22:27:20.660  6678  6678 D DialogFlow: initQueue()
,08-12 22:27:20.670   775   789 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-12 22:27:20.680  3613  3613 V ActivityThread: updateVisibility : ActivityRecord{d3aebaf token=android.os.BinderProxy@2b77351 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-12 22:27:20.690  3613  3613 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 22:27:20.730  6525  6640 W jxcore-log: Platform android
08-12 22:27:20.730  6525  6640 W jxcore-log: 
,08-12 22:27:20.730  6525  6640 W jxcore-log: Process ARCH arm
08-12 22:27:20.730  6525  6640 W jxcore-log: 
,08-12 22:27:20.750   775  6321 I HarmonyEASService: Updating for all 1
,08-12 22:27:20.770  6722  6722 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-12 22:27:20.810   775  1694 V WindowStateAnimator: Finishing drawing window Window{ca6d8b8 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 22:27:20.810  3613  3613 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 22:27:20.820   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef79364
,08-12 22:27:20.820   775  2100 V WindowStateAnimator: Finishing drawing window Window{719a9f6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 22:27:20.820  3613  3613 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-12 22:27:20.820  3613  3613 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-12 22:27:20.820  6722  6722 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-12 22:27:20.820  6722  6722 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-12 22:27:20.830   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef79364
,08-12 22:27:20.830   775  1638 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7253ae 5079:com.google.android.apps.plus/u0a134}
,08-12 22:27:20.830   775   907 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 22:27:20.830   775   789 V WindowStateAnimator: Finishing drawing window Window{ca6d8b8 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-12 22:27:20.840   775  1669 V WindowStateAnimator: Finishing drawing window Window{719a9f6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-12 22:27:20.840   775   775 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 22:27:20.840   775   907 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +453ms (total +472ms)
,08-12 22:27:20.840  3613  3613 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b77351 time:107281
08-12 22:27:20.840   775   775 I KnoxTimeoutHandler: SD activityfalse
,08-12 22:27:20.840   775   907 D ActivityManager: mDVFSHelper.release()
,08-12 22:27:20.840   775   907 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c23852b u0 com.samsung.android.MtpApplication/.USBConnection t168} time:107283
,08-12 22:27:20.850   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef79364
,08-12 22:27:20.860   775  2273 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7253ae 5079:com.google.android.apps.plus/u0a134}
,08-12 22:27:20.870   775  2104 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7253ae 5079:com.google.android.apps.plus/u0a134}
,08-12 22:27:20.930  6538  6538 I Mms/MmsApp:  start initViewCache mms
,08-12 22:27:20.950  6741  6741 E Zygote  : v2
08-12 22:27:20.950  6741  6741 I libpersona: KNOX_SDCARD checking this for 10165
08-12 22:27:20.950  6741  6741 I libpersona: KNOX_SDCARD not a persona
,08-12 22:27:20.950  6741  6741 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:20.950  6741  6741 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:20.960  6741  6741 E Zygote  : accessInfo : 0
08-12 22:27:20.960   775  1677 I ActivityManager: Start proc 6741:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-12 22:27:20.960  6741  6741 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-12 22:27:20.980   775  2100 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-12 22:27:20.980   775  2270 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-12 22:27:20.980  6741  6741 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:20.980  6741  6741 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:20.980   775  1217 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-12 22:27:20.990   775   788 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-12 22:27:20.990   775   789 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-12 22:27:20.990   775  2273 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-12 22:27:20.990   775  1411 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-12 22:27:20.990   775  1669 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4b4693 6741:com.sec.kidsplat.installer/u0a165}
,08-12 22:27:21.000   775  1694 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-12 22:27:21.000  6741  6741 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-12 22:27:21.010   775  1217 I ActivityManager: Killing 5536:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-12 22:27:21.020  6525  6640 I jxcore-log: JXcore Cordova bridge is ready!
08-12 22:27:21.020  6525  6640 I jxcore-log: 
,08-12 22:27:21.020  6525  6640 W jxcore-log: JXcore engine is started
,08-12 22:27:21.020  6741  6741 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-12 22:27:21.030   775  1411 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-12 22:27:21.030  6525  6639 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 22:27:21.030  6525  6525 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 22:27:21.050   775  2269 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4b4693 6741:com.sec.kidsplat.installer/u0a165}
,08-12 22:27:21.070   775   786 I art     : Background partial concurrent mark sweep GC freed 25550(1678KB) AllocSpace objects, 2(40KB) LOS objects, 27% free, 41MB/57MB, paused 1.680ms total 133.956ms
,08-12 22:27:21.070  6741  6741 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-12 22:27:21.090  6754  6754 E Zygote  : v2
08-12 22:27:21.090  6754  6754 I libpersona: KNOX_SDCARD checking this for 10142
08-12 22:27:21.090  6754  6754 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 22:27:21.090  6754  6754 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:21.090  6754  6754 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:21.090  6754  6754 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:21.090  6754  6754 E Zygote  : accessInfo : 64
08-12 22:27:21.090  6754  6754 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 22:27:21.090  6754  6754 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-12 22:27:21.090  6754  6754 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-12 22:27:21.090   775  2104 I ActivityManager: Start proc 6754:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-12 22:27:21.090   775  2104 I ActivityManager: Killing 5775:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-12 22:27:21.120   775  2270 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-12 22:27:21.120  6754  6754 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 22:27:21.120  6754  6754 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:21.130   775  2273 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44006d0 6754:com.sec.android.app.sbrowser/u0a142}
,08-12 22:27:21.130  6754  6754 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 22:27:21.150  6754  6754 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-12 22:27:21.170  6754  6754 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 22:27:21.170  6754  6754 D ManifestProvider: onCreate()
,08-12 22:27:21.180  6754  6754 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-12 22:27:21.180  6754  6754 I SBrowserUtils: getSystemProperty of country_code : Poland
08-12 22:27:21.180  6754  6754 I SBrowserUtils: getSystemProperty of country_code : Poland
08-12 22:27:21.180  6754  6754 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-12 22:27:21.190  6754  6754 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-12 22:27:21.190  6754  6754 D [MM]MHDataBaseProvider: onCreate()
,08-12 22:27:21.210  6754  6754 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@efde4d4)
,08-12 22:27:21.210  6538  6538 D Mms/BubbleViewCache: fillCache bubble = 4
,08-12 22:27:21.250   775  1638 I ActivityManager: Killing 5414:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-12 22:27:21.260   775  1638 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c339ed9 1922:com.google.android.gms.persistent/u0a11}
,08-12 22:27:21.270   775  2104 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-12 22:27:21.280   775   788 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f68117 4051:com.google.android.gms/u0a11}
,08-12 22:27:21.290   775  1364 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/167_task.xml.bak
,08-12 22:27:21.310  4051  6769 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 22:27:21.310  4051  6768 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-12 22:27:21.310  4051  6769 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 22:27:21.320  4051  4051 D AsyncTaskServiceImpl: Submit a task: nzm
,08-12 22:27:21.330  4051  6769 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 22:27:21.340   775  2271 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c339ed9 1922:com.google.android.gms.persistent/u0a11}
,08-12 22:27:21.340  4051  6769 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 22:27:21.350  4051  4902 D nzm     : Processing package: com.test.thalitest
,08-12 22:27:21.350   775  2271 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f68117 4051:com.google.android.gms/u0a11}
,08-12 22:27:21.360  4051  4051 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 22:27:21.390  4051  4902 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-12 22:27:21.390  4051  4902 D nzm     : Found info for package com.test.thalitest in db.
,08-12 22:27:21.390   775  3396 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-12 22:27:21.470   775  1669 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3102e0 5804:com.android.vending/u0a29}
08-12 22:27:21.520   775  2104 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61c4b1 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{94fa3f0 6164:com.sec.android.app.samsungapps/u0a39}
08-12 22:27:21.530  5804  5804 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
08-12 22:27:21.530  1922  1922 D WearableService: callingUid 10011, callindPid: 1922
08-12 22:27:21.530  5804  5804 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
08-12 22:27:21.540   775  2271 I ActivityManager: Start proc 6775:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-12 22:27:21.550  6775  6775 E Zygote  : v2
08-12 22:27:21.550  6775  6775 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:21.550  6775  6775 I libpersona: KNOX_SDCARD checking this for 10034
08-12 22:27:21.550  6775  6775 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 22:27:21.550  6775  6775 I libpersona: KNOX_SDCARD not a persona
08-12 22:27:21.550  6775  6775 E Zygote  : accessInfo : 0
08-12 22:27:21.550  6775  6775 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
08-12 22:27:21.550  1453  1453 D Recents : onTaskStackChanged
08-12 22:27:21.570  1453  1453 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
08-12 22:27:21.580  5804  5804 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
08-12 22:27:21.580  5804  5804 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
08-12 22:27:21.590  6775  6775 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:21.590  6775  6775 D ActivityThread: Added TimaKeyStore provider
08-12 22:27:21.600  6678  6706 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 22:27:21.600  6678  6706 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 22:27:21.600   775  2268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{52e7a7e u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{990bbdf 6775:com.sec.android.app.shealth/u0a34}
08-12 22:27:21.630  6775  6775 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
08-12 22:27:21.650  6775  6775 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
08-12 22:27:21.650  6678  6706 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 22:27:21.650  6678  6706 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 22:27:21.650  6678  6706 I System.out: INFO:Resource not found:/Common.properties Using default values
08-12 22:27:21.650  6775  6775 I MultiDex: VM with version 2.1.0 has multidex support
08-12 22:27:21.650  6775  6775 I MultiDex: install
08-12 22:27:21.650  6775  6775 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-12 22:27:21.650  6775  6775 I MultiDex: install
08-12 22:27:21.650  6775  6775 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-12 22:27:21.660  6678  6706 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 22:27:21.660  6678  6706 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 22:27:21.730   775  2268 I ActivityManager: Killing 5965:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
08-12 22:27:21.740   775  2268 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{52e7a7e u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ca8274 1940:com.sec.android.app.shealth:remote/u0a34}
08-12 22:27:21.740  6775  6775 D HealthDataStore: Service for HealthDataStore is connected
08-12 22:27:21.750  6775  6775 D HealthDataStore: HealthConnectionErrorResult code : 9
08-12 22:27:21.750  6775  6775 D HealthConsole: Service for HealthDataConsole is connected
08-12 22:27:21.750   775   789 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
08-12 22:27:21.760  6775  6775 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
08-12 22:27:21.760  6775  6775 E HealthDataStore: disconnectService: Context instance is invalid
08-12 22:27:21.760   775  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{52e7a7e u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ca8274 1940:com.sec.android.app.shealth:remote/u0a34}
08-12 22:27:21.780   775   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1aee3ad u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c339ed9 1922:com.google.android.gms.persistent/u0a11}
08-12 22:27:21.800   775   775 I BackgroundCompactionService: onStart. jobID=801
08-12 22:27:21.800   775   775 I BackgroundCompactionService: onStart done. jobID=801
08-12 22:27:21.800   775  6792 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-12 22:27:21.800   775  6792 I BackgroundCompactionService: compact_memory command done
08-12 22:27:22.070  4051  6773 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 22:27:22.540  4051  4919 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-12 22:27:22.590  4051  4919 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 22:27:22.610  4051  4919 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 22:27:22.610  4051  4919 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-12 22:27:22.930   775  1237 V AlarmManager: Expired Alarm result :4
,08-12 22:27:22.940   775  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-12 22:27:22.940   775  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-12 22:27:22.940   775  2270 V AlarmManager:  remove PendingIntent] PendingIntent{cb9ec5c: PendingIntentRecord{4251ae1 com.google.android.gms broadcastIntent}}
,08-12 22:27:23.100   775  3391 D SSRM:n  : SIOP:: AP = 480, PST = 448, CUR = 350, LCD = 0
,08-12 22:27:23.870   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:27:26.440   775  3391 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 22:27:27.960   775   937 D PackageManager: [MSG] MCS_UNBIND
,08-12 22:27:27.980   775  2270 I ActivityManager: Killing 4861:com.policydm/1000 (adj 15): DHA:empty #37
,08-12 22:27:28.020   775  2269 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-12 22:27:28.020  6505  6505 D AASAservice: onDestroy()
,08-12 22:27:28.030  6505  6505 I art     : System.exit called, status: 80
,08-12 22:27:28.030  6505  6505 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-12 22:27:28.040   775  1677 I ActivityManager: Process com.samsung.aasaservice (pid 6505)(adj 0) has died(90,718)
,08-12 22:27:28.040   775  1677 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-12 22:27:28.090   360   360 I Zygote  : Process 6505 exited cleanly (80)
,08-12 22:27:28.270   775   937 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-12 22:27:28.290   775   937 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 22:27:32.980   775  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-12 22:27:32.980   775  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-12 22:27:33.150   775  3391 D SSRM:n  : SIOP:: AP = 450, PST = 448, CUR = 350, LCD = 0
,08-12 22:27:34.460   775  1550 E Watchdog: !@Sync 3 [08-12 22:27:34.471]
,08-12 22:27:36.490   775  1237 V AlarmManager: Expired Alarm result :4
,08-12 22:27:36.510   775   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f7d4eb u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c339ed9 1922:com.google.android.gms.persistent/u0a11}
,08-12 22:27:36.530   775   788 V AlarmManager:  remove PendingIntent] PendingIntent{5594606: PendingIntentRecord{7ff5ef4 com.google.android.gms broadcastIntent}}
,08-12 22:27:36.550  5804  5845 I Finsky  : [825] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,08-12 22:27:36.560   775  1677 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:27:36.560   775  1677 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4338, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 22:27:36.560   775  1677 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-12 22:27:36.560   775  1677 D BatteryService: stay LED for charging
08-12 22:27:36.560   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:27:36.560   775   775 I MotionRecognitionService: Plugged
08-12 22:27:36.560   775   775 D MotionRecognitionService:   cableConnection= 1
08-12 22:27:36.560   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 22:27:36.560   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:27:36.560  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:27:36.560  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:27:36.560  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:27:36.570  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:27:36.570  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:27:36.590  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:27:36.590  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 22:27:36.590  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:27:36.660   775   789 V AlarmManager:  remove PendingIntent] PendingIntent{5656af4: PendingIntentRecord{7ff5ef4 com.google.android.gms broadcastIntent}}
,08-12 22:27:36.740  4051  6831 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-12 22:27:36.740  4051  6831 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-12 22:27:36.760  1922  1922 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 22:27:36.780   775  1694 V AlarmManager:  remove PendingIntent] PendingIntent{bd995bf: PendingIntentRecord{7ff5ef4 com.google.android.gms broadcastIntent}}
,08-12 22:27:36.780   775   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ff248c u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c339ed9 1922:com.google.android.gms.persistent/u0a11}
,08-12 22:27:36.830   775  2103 V AlarmManager:  remove PendingIntent] PendingIntent{50d67d5: PendingIntentRecord{7ff5ef4 com.google.android.gms broadcastIntent}}
,08-12 22:27:36.860   775   789 V AlarmManager:  remove PendingIntent] PendingIntent{164bea: PendingIntentRecord{7ff5ef4 com.google.android.gms broadcastIntent}}
,08-12 22:27:36.990  5804  5845 I Finsky  : [825] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,08-12 22:27:36.990  5804  5804 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-12 22:27:37.060  6836  6836 E Zygote  : v2
08-12 22:27:37.060  6836  6836 I libpersona: KNOX_SDCARD checking this for 10011
08-12 22:27:37.060  6836  6836 I libpersona: KNOX_SDCARD not a persona
,08-12 22:27:37.060   775   789 I ActivityManager: Start proc 6836:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-12 22:27:37.060  6836  6836 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 22:27:37.060  6836  6836 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:27:37.060  6836  6836 E Zygote  : accessInfo : 0
,08-12 22:27:37.060  6836  6836 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-12 22:27:37.090  6836  6836 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:27:37.090  6836  6836 D ActivityThread: Added TimaKeyStore provider
,08-12 22:27:37.100  6836  6836 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 22:27:37.140  6836  6836 I MultiDex: VM with version 2.1.0 has multidex support
08-12 22:27:37.140  6836  6836 I MultiDex: install
08-12 22:27:37.140  6836  6836 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 22:27:37.180  6836  6836 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-12 22:27:37.190  6836  6836 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-12 22:27:37.190  6836  6836 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-12 22:27:37.190  6836  6836 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 22:27:37.220  6836  6836 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 22:27:37.240  6836  6836 D ChimeraCfgMgr: Reading stored module config
,08-12 22:27:37.340  1922  1922 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=5b7f0e38-5680-4645-baaf-32184e4b203d
,08-12 22:27:37.350  1922  1922 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 22:27:37.350  1922  1922 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 22:27:37.360  6836  6850 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-12 22:27:37.390   326   988 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6836)
,08-12 22:27:37.430   326   326 D WVCdm   : Instantiating CDM.
,08-12 22:27:37.430   326   956 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6836)
08-12 22:27:37.430   326   956 I WVCdm   : CdmEngine::OpenSession
08-12 22:27:37.430   326   956 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-12 22:27:37.440   326   956 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-12 22:27:37.450   326   956 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-12 22:27:37.450   326   956 D DrmWidevineDash: Service_Initialize: starts!
08-12 22:27:37.450   326   956 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-12 22:27:37.450   326   956 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 22:27:37.450   326   956 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-12 22:27:37.450   326   956 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-12 22:27:37.450   326   956 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-12 22:27:37.450   326   956 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 22:27:37.450   326   956 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-12 22:27:37.450   326   956 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-12 22:27:37.450   326   956 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-12 22:27:37.450   326   956 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 22:27:37.490   326   956 D QSEECOMAPI: : Loaded image: APP id = 3
,08-12 22:27:37.490   326   956 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-12 22:27:37.490   326   956 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef15000
08-12 22:27:37.490   326   956 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef15000
,08-12 22:27:37.500  6836  6847 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 22:27:37.500  6836  6847 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:37.500   306  1131 D EnterpriseController: netId is 0
08-12 22:27:37.500   306  1131 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 22:27:37.510   326   956 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-12 22:27:37.510   326   956 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-12 22:27:37.510   326   956 D DrmWidevineDash: hlos api version =  10
08-12 22:27:37.510   326   956 D DrmWidevineDash: tz api version =  10
08-12 22:27:37.510   326   956 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-12 22:27:37.510   326   956 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-12 22:27:37.520   326   956 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-12 22:27:37.520   326   956 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-12 22:27:37.520   326   956 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf1c0924
,08-12 22:27:37.520   326   956 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-12 22:27:37.520   326   956 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-12 22:27:37.520   326   956 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1e1deb8, dataLength=8
,08-12 22:27:37.520   326   956 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-12 22:27:37.520   326   956 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xae764800, wrapped_rsa_key_length=1280
,08-12 22:27:37.530   326   956 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,08-12 22:27:37.530   326   956 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-12 22:27:37.530   326   979 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-12 22:27:37.530   326   979 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-12 22:27:37.530   326   979 I WVCdm   : CdmEngine::GenerateKeyRequest
08-12 22:27:37.530   326   979 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xaf533cc0, idLength=0xaf0bef2c
,08-12 22:27:37.530  1922  2280 W GCoreFlp: No location to return for getLastLocation()
,08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-12 22:27:37.540   326   979 D DrmWidevineDash: hlos api version =  10
,08-12 22:27:37.540   326   979 D DrmWidevineDash: tz api version =  10
08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-12 22:27:37.540   326   979 D WVCdm   : PrepareKeyRequest: nonce=2433976980
08-12 22:27:37.540   326   979 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xad44b300
08-12 22:27:37.540   326   979 D DrmWidevineDash: message_length=1631, signature=0xaf514a00, signature_length=2936795140
,08-12 22:27:37.550  6836  6847 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6836, getuid(): 10011
,08-12 22:27:37.610  4051  6832 D UdcContextInitService: registered all accounts: true
,08-12 22:27:37.610  1922  2399 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 22:27:37.620  1922  2503 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-12 22:27:37.630   326   979 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-12 22:27:37.630   326   326 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6836)
,08-12 22:27:37.630   326   326 I WVCdm   : CdmEngine::CloseSession
08-12 22:27:37.630   326   326 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-12 22:27:37.630   326   326 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-12 22:27:37.630   326   326 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-12 22:27:37.630   326   326 D DrmWidevineDash: Service_Uninitialize: starts!
08-12 22:27:37.630   326   326 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-12 22:27:37.630   326   326 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
08-12 22:27:37.630   326   326 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-12 22:27:37.640   326   326 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-12 22:27:37.700  6836  6847 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6836, getuid(): 10011
,08-12 22:27:37.820  6836  6847 I qtaguid : Untagging socket 21
,08-12 22:27:37.850  6836  6847 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-12 22:27:37.850  6836  6847 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 22:27:38.190  6525  6640 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 22:27:38.190  6525  6640 I jxcore-log: 
,08-12 22:27:38.200  6525  6640 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 22:27:38.200  6525  6640 I jxcore-log: 
,08-12 22:27:38.200  6525  6640 D BluetoothAdapter: STATE_ON
,08-12 22:27:38.200  6525  6640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:27:38.200  6525  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:27:38.200  6525  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 22:27:38.200  6525  6640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:27:38.200  6525  6640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:27:38.200  6525  6640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:27:38.200  6525  6640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:27:38.200  6525  6640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 22:27:38.200  6525  6640 D BluetoothAdapter: STATE_ON
,08-12 22:27:38.200  6525  6640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 22:27:38.210  6525  6640 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 22:27:38.210  6525  6640 I jxcore-log: 
,08-12 22:27:38.210  6525  6640 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 22:27:38.210  6525  6640 I jxcore-log: 
,08-12 22:27:38.310  6865  6865 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-12 22:27:38.420  6865  6865 I dex2oat : ----------------------------------------------------
08-12 22:27:38.420  6865  6865 I dex2oat : <SS>: S T A R T I N G . . .
08-12 22:27:38.420  6865  6865 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
08-12 22:27:38.420  6865  6865 I dex2oat : dex2oat took 109.836ms (threads: 4) arena alloc=180KB java alloc=39KB native alloc=1414KB free=1401KB
,08-12 22:27:38.430  6836  6847 W System  : ClassLoader referenced unknown path: 
,08-12 22:27:38.430  6836  6847 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-12 22:27:38.430  6836  6847 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 22:27:38.430  6836  6847 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 22:27:38.430  6836  6847 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 22:27:38.430  6836  6847 I Adreno-EGL: Local Branch: ss
08-12 22:27:38.430  6836  6847 I Adreno-EGL: Remote Branch: 
08-12 22:27:38.430  6836  6847 I Adreno-EGL: Local Patches: 
08-12 22:27:38.430  6836  6847 I Adreno-EGL: Reconstruct Branch: 
,08-12 22:27:38.440  6836  6847 D libEGL  : eglInitialize EGLDisplay = 0xb2f4e264
,08-12 22:27:38.490  6836  6847 D libEGL  : eglTerminate EGLDisplay = 0xb2f4e2bc
,08-12 22:27:38.500  6836  6847 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 22:27:38.500  6836  6847 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 22:27:38.500  6836  6847 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 22:27:38.500  6836  6847 I Adreno-EGL: Local Branch: ss
08-12 22:27:38.500  6836  6847 I Adreno-EGL: Remote Branch: 
08-12 22:27:38.500  6836  6847 I Adreno-EGL: Local Patches: 
08-12 22:27:38.500  6836  6847 I Adreno-EGL: Reconstruct Branch: 
,08-12 22:27:38.500  6836  6847 D libEGL  : eglInitialize EGLDisplay = 0xb2f4e264
,08-12 22:27:38.540  6836  6847 D libEGL  : eglTerminate EGLDisplay = 0xb2f4e2bc
,08-12 22:27:38.570  6525  6640 I jxcore-log: Unit Test app is loaded
08-12 22:27:38.570  6525  6640 I jxcore-log: 
,08-12 22:27:38.580  6525  6640 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 22:27:38.580  6525  6640 I jxcore-log: 
,08-12 22:27:38.580  6525  6640 I jxcore-log: My device name is: samsung-SM-G900F
08-12 22:27:38.580  6525  6640 I jxcore-log: 
,08-12 22:27:38.580  6525  6525 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 22:27:38.580  6525  6640 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 22:27:38.580  6525  6640 I jxcore-log: 
,08-12 22:27:38.600  6836  6847 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 22:27:38.600  6836  6847 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 22:27:38.600  6836  6847 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 22:27:38.600  6836  6847 I Adreno-EGL: Local Branch: ss
08-12 22:27:38.600  6836  6847 I Adreno-EGL: Remote Branch: 
08-12 22:27:38.600  6836  6847 I Adreno-EGL: Local Patches: 
08-12 22:27:38.600  6836  6847 I Adreno-EGL: Reconstruct Branch: 
,08-12 22:27:38.600  6836  6847 D libEGL  : eglInitialize EGLDisplay = 0xb2f4e264
,08-12 22:27:38.650  6836  6847 D libEGL  : eglTerminate EGLDisplay = 0xb2f4e2bc
,08-12 22:27:38.780  1922  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:38.780  1922  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:38.780   306  1131 D EnterpriseController: netId is 0
08-12 22:27:38.780   306  1131 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 22:27:38.780  1922  6834 I qtaguid : Tagging socket 46 with tag 1000040100000000{268436481,0} uid 10011, pid: 1922, getuid(): 10011
,08-12 22:27:38.830  1922  6834 I qtaguid : Tagging socket 50 with tag 1000040100000000{268436481,0} uid 10011, pid: 1922, getuid(): 10011
,08-12 22:27:39.030  1922  2503 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 22:27:39.040  1922  2503 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-12 22:27:39.050  1922  2503 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-12 22:27:37.701+0200, stopTime=2016-08-12 22:27:39.061+0200, duration=1360ms
,08-12 22:27:39.050   775  1411 V AlarmManager:  remove PendingIntent] PendingIntent{f323d4c: PendingIntentRecord{7ff5ef4 com.google.android.gms broadcastIntent}}
,08-12 22:27:39.070  1922  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 22:27:39.070  1922  6884 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:39.070   306  1131 D EnterpriseController: netId is 0
08-12 22:27:39.070   306  1131 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 22:27:39.070  1922  6884 I qtaguid : Tagging socket 52 with tag 1000310500000000{268448005,0} uid 10011, pid: 1922, getuid(): 10011
,08-12 22:27:39.120  1922  6884 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} uid 10011, pid: 1922, getuid(): 10011
,08-12 22:27:39.370   775  1411 V AlarmManager:  remove PendingIntent] PendingIntent{a6ef2aa: PendingIntentRecord{7ff5ef4 com.google.android.gms broadcastIntent}}
,08-12 22:27:39.370  1922  6884 I qtaguid : Untagging socket 52
,08-12 22:27:39.430  1922  2503 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-12 22:27:39.570  1922  6906 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 22:27:39.570  1922  6899 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-12 22:27:39.580  1922  6906 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-12 22:27:39.580  1922  6899 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-12 22:27:39.600  1922  6906 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-12 22:27:39.600  1922  6899 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-12 22:27:39.600  1922  6899 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-12 22:27:39.600  1922  6899 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 22:27:39.660   775  2104 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 22:27:39.710  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 22:27:39.710  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:39.710   306  1131 D EnterpriseController: netId is 0
08-12 22:27:39.710   306  1131 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-12 22:27:39.710  1922  6899 I qtaguid : Tagging socket 63 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 1922, getuid(): 10011
,08-12 22:27:39.760  1922  6899 I qtaguid : Tagging socket 66 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 1922, getuid(): 10011
,08-12 22:27:40.000   775  1217 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 22:27:40.010  1922  6899 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-12 22:27:40.010  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:40.010  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:40.010  1922  6899 I qtaguid : Tagging socket 63 with tag fffff65b00000000{4294964827,0} uid -1, pid: 1922, getuid(): 10011
,08-12 22:27:40.330   775  2100 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 22:27:40.340  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:40.340  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 22:27:40.340  1922  6899 I qtaguid : Tagging socket 63 with tag 11065c0800000000{285629448,0} uid -1, pid: 1922, getuid(): 10011
,08-12 22:27:40.450   775  2268 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 22:27:40.460  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:40.460  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 22:27:40.460  1922  6899 I qtaguid : Tagging socket 63 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 1922, getuid(): 10011
,08-12 22:27:40.560   775  1638 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 22:27:40.570  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 22:27:40.570  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:40.570  1922  6899 I qtaguid : Tagging socket 63 with tag 11065fff00000000{285630463,0} uid -1, pid: 1922, getuid(): 10011
,08-12 22:27:40.680   775  2269 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 22:27:40.690  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:40.690  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 22:27:40.690  1922  6899 I qtaguid : Tagging socket 63 with tag 11065c9100000000{285629585,0} uid -1, pid: 1922, getuid(): 10011
,08-12 22:27:40.790   775  1411 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 22:27:40.800  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:40.800  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 22:27:40.800  1922  6899 I qtaguid : Tagging socket 63 with tag 11065b5800000000{285629272,0} uid -1, pid: 1922, getuid(): 10011
,08-12 22:27:40.910   775   789 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 22:27:40.930  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:40.930  1922  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-12 22:27:40.930  1922  6899 I qtaguid : Tagging socket 63 with tag fffffca200000000{4294966434,0} uid -1, pid: 1922, getuid(): 10011
,08-12 22:27:41.100  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 22:27:41.100  6525  6640 I jxcore-log: 
,08-12 22:27:41.100   775   788 V AlarmManager:  remove PendingIntent] PendingIntent{498e9e4: PendingIntentRecord{7ff5ef4 com.google.android.gms broadcastIntent}}
,08-12 22:27:41.170  1922  6883 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:41.180  1922  6883 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-12 22:27:41.180  1922  6883 I qtaguid : Tagging socket 52 with tag 1000310200000000{268448002,0} uid 10011, pid: 1922, getuid(): 10011
,08-12 22:27:41.480  1922  6883 I qtaguid : Untagging socket 52
,08-12 22:27:41.480  1922  2503 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-12 22:27:41.740  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 22:27:41.740  6525  6640 I jxcore-log: 
,08-12 22:27:41.760  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 22:27:41.760  6525  6640 I jxcore-log: 
,08-12 22:27:43.180  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 22:27:43.180  6525  6640 I jxcore-log: 
,08-12 22:27:43.190   775  3391 D SSRM:n  : SIOP:: AP = 450, PST = 448, CUR = 350, LCD = 0
,08-12 22:27:43.420  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 22:27:43.420  6525  6640 I jxcore-log: 
,08-12 22:27:43.430  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 22:27:43.430  6525  6640 I jxcore-log: 
,08-12 22:27:43.440  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 22:27:43.440  6525  6640 I jxcore-log: 
,08-12 22:27:43.450  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 22:27:43.450  6525  6640 I jxcore-log: 
,08-12 22:27:43.460  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
08-12 22:27:43.460  6525  6640 I jxcore-log: 
,08-12 22:27:43.680   775  1669 I ActivityManager: Killing 5981:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-12 22:27:43.710   775  1411 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-12 22:27:43.870   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:27:44.160  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 22:27:44.160  6525  6640 I jxcore-log: 
,08-12 22:27:44.180  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 22:27:44.180  6525  6640 I jxcore-log: 
,08-12 22:27:44.190  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 22:27:44.190  6525  6640 I jxcore-log: 
,08-12 22:27:44.200  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 22:27:44.200  6525  6640 I jxcore-log: 
,08-12 22:27:44.250  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 22:27:44.250  6525  6640 I jxcore-log: 
,08-12 22:27:44.300  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 22:27:44.300  6525  6640 I jxcore-log: 
,08-12 22:27:44.310  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 22:27:44.310  6525  6640 I jxcore-log: 
,08-12 22:27:44.490  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 22:27:44.490  6525  6640 I jxcore-log: 
,08-12 22:27:44.520  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 22:27:44.520  6525  6640 I jxcore-log: 
,08-12 22:27:44.520  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 22:27:44.520  6525  6640 I jxcore-log: 
,08-12 22:27:44.530  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 22:27:44.530  6525  6640 I jxcore-log: 
,08-12 22:27:44.550  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 22:27:44.550  6525  6640 I jxcore-log: 
,08-12 22:27:44.640  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 22:27:44.640  6525  6640 I jxcore-log: 
,08-12 22:27:44.650  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 22:27:44.650  6525  6640 I jxcore-log: 
,08-12 22:27:44.680  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 22:27:44.680  6525  6640 I jxcore-log: 
,08-12 22:27:44.690  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 22:27:44.690  6525  6640 I jxcore-log: 
,08-12 22:27:44.710  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 22:27:44.710  6525  6640 I jxcore-log: 
,08-12 22:27:44.750  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 22:27:44.750  6525  6640 I jxcore-log: 
,08-12 22:27:44.760  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 22:27:44.760  6525  6640 I jxcore-log: 
,08-12 22:27:44.970  6525  6640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 22:27:44.970  6525  6640 I jxcore-log: 
,08-12 22:27:44.980  6525  6640 D BluetoothAdapter: STATE_ON
,08-12 22:27:44.990  6525  6640 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 22:27:44.990  6525  6640 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 22:27:44.990  6525  6640 I jxcore-log: 
,08-12 22:27:46.630   775   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:27:46.630   775   788 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4385, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:27:46.630   775   788 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350,
08-12 22:27:46.640   775   788 D BatteryService: stay LED for charging
,08-12 22:27:46.640   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,08-12 22:27:46.640   775   775 I MotionRecognitionService: Plugged
,08-12 22:27:46.640   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:27:46.640   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:27:46.640   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:27:46.650  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:27:46.650  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:27:46.650  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:27:46.660  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:27:46.660  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:27:46.670  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:27:46.670  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:27:46.670  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:27:52.330   775   786 I art     : Background partial concurrent mark sweep GC freed 35057(1893KB) AllocSpace objects, 20(400KB) LOS objects, 27% free, 42MB/58MB, paused 2.454ms total 226.440ms
,08-12 22:27:53.240   775  3391 D SSRM:n  : SIOP:: AP = 410, PST = 441, CUR = 350, LCD = 0
,08-12 22:27:56.720   775  2104 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:27:56.720   775  2104 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:27:56.730   775  2104 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:27:56.730   775  2104 D BatteryService: stay LED for charging
,08-12 22:27:56.730   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:27:56.750   775   775 I MotionRecognitionService: Plugged
,08-12 22:27:56.750   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:27:56.750   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:27:56.760   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:27:56.770  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:27:56.770  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:27:56.780  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:27:56.790  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:27:56.790  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:27:56.800  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:27:56.800  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:27:56.800  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:27:59.990   775  1237 V AlarmManager: Expired Alarm result :8
,08-12 22:28:03.310   775  3391 D SSRM:n  : SIOP:: AP = 380, PST = 432, CUR = 350, LCD = 0
,08-12 22:28:03.870   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:28:04.470   775  1550 E Watchdog: !@Sync 4 [08-12 22:28:04.472]
,08-12 22:28:06.020  1740  1810 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 22:28:06.810   775  1677 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:28:06.810   775  1677 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:28:06.820   775  1677 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:28:06.820   775  1677 D BatteryService: stay LED for charging
,08-12 22:28:06.820   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:28:06.830   775   775 I MotionRecognitionService: Plugged
,08-12 22:28:06.840   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:28:06.840   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:28:06.840   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:28:06.850  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:28:06.850  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:28:06.850  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:28:06.880  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:28:06.880  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:28:06.880  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:28:06.890  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:28:06.890  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:28:13.370   775  3391 D SSRM:n  : SIOP:: AP = 350, PST = 425, CUR = 350, LCD = 0
,08-12 22:28:13.380   775  3391 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,08-12 22:28:13.440  2733  2733 D ContentApp:  LEVEL : 0
,08-12 22:28:13.450   775   856 I ActivityManager: Start proc 6942:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,08-12 22:28:13.450   775  1322 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-12 22:28:13.460  6942  6942 E Zygote  : v2
,08-12 22:28:13.470  6942  6942 I libpersona: KNOX_SDCARD checking this for 10053
,08-12 22:28:13.470  6942  6942 I libpersona: KNOX_SDCARD not a persona
,08-12 22:28:13.470  6942  6942 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 22:28:13.470  6942  6942 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:28:13.470  6942  6942 E Zygote  : accessInfo : 0
,08-12 22:28:13.480   775  3391 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 22:28:13.480  6942  6942 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-12 22:28:13.570  6942  6942 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 22:28:13.570  6942  6942 D ActivityThread: Added TimaKeyStore provider
,08-12 22:28:13.590   775  1669 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8f2d02 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{738f613 6942:com.sec.android.app.videoplayer/u0a53}
,08-12 22:28:13.590   775  1322 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 22:28:13.600  6942  6942 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-12 22:28:13.630  6942  6942 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-12 22:28:13.670  6942  6942 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-12 22:28:13.700  6942  6942 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-12 22:28:13.700  6942  6942 D videowall-Global: core_num = 4
,08-12 22:28:13.710  6942  6942 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
08-12 22:28:13.710  6942  6942 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-12 22:28:13.720  6942  6942 D TranscodeReceiver:  SIOP_LEVEL: 0
08-12 22:28:13.730   775  2100 I ActivityManager: Killing 6008:com.google.android.apps.photos/u0a199 (adj 15): DHA:empty #37
,08-12 22:28:13.750   775  2269 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-12 22:28:19.440   775  1237 V AlarmManager: Expired Alarm result :4
,08-12 22:28:19.510   775  1677 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:28:19.560  6982  6982 E Zygote  : v2
,08-12 22:28:19.560  6982  6982 I libpersona: KNOX_SDCARD checking this for 1000
,08-12 22:28:19.560   775  1237 I ActivityManager: Start proc 6982:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-12 22:28:19.570  6982  6982 I libpersona: KNOX_SDCARD not a persona
,08-12 22:28:19.570  6982  6982 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 22:28:19.570  6982  6982 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 22:28:19.570  6982  6982 E Zygote  : accessInfo : 0
,08-12 22:28:19.580  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-12 22:28:19.580  1381  1381 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-12 22:28:19.580  1381  1381 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 22:28:19.590  1381  1381 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-12 22:28:19.590  1381  1381 D SecKeyguardClockView: HomeTimezone(): 1
,08-12 22:28:19.600  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:28:19.600  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:28:19.600  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:28:19.600  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 22:28:19.600  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:28:19.600  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:28:19.610  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:28:19.650  6982  6982 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 22:28:19.650  6982  6982 D ActivityThread: Added TimaKeyStore provider
,08-12 22:28:19.660  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:28:19.670  6982  6982 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-12 22:28:19.690  6982  6982 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-12 22:28:19.740   775  2103 I ActivityManager: Killing 6037:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-12 22:28:19.770   775   788 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,08-12 22:28:23.540   775  3391 D SSRM:n  : SIOP:: AP = 340, PST = 417, CUR = 350, LCD = 0
,08-12 22:28:23.880   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:28:29.190  4051  4960 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 22:28:29.590   775   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:28:29.590   775   789 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4385, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:28:29.590   775   789 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:28:29.590   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:28:29.600   775   775 I MotionRecognitionService: Plugged
,08-12 22:28:29.600   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:28:29.600   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:28:29.600   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:28:29.600   775   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
,08-12 22:28:29.600   775   789 D BatteryService: stay LED for charging
,08-12 22:28:29.610  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:28:29.610  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:28:29.610  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:28:29.630  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:28:29.630  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:28:29.630  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:28:29.630  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:28:29.630  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 22:28:33.450  1922  3277 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 22:28:33.610   775  3391 D SSRM:n  : SIOP:: AP = 330, PST = 408, CUR = 350, LCD = 0
,08-12 22:28:33.620   775  3391 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-12 22:28:33.630  2733  2733 D ContentApp:  LEVEL : -1
,08-12 22:28:33.670   775   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{57aea05 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{738f613 6942:com.sec.android.app.videoplayer/u0a53}
,08-12 22:28:33.670  6942  6942 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-12 22:28:33.670  6942  6942 D TranscodeReceiver:  SIOP_LEVEL: -1
,08-12 22:28:34.470   775  1550 E Watchdog: !@Sync 5 [08-12 22:28:34.480]
,08-12 22:28:34.760   775  3396 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-12 22:28:34.770   775   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{51b8a03 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b7ca77 6342:com.samsung.android.sm.provider/1000}
,08-12 22:28:34.910   775  3396 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,08-12 22:28:34.930   775   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9137fb9 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b7ca77 6342:com.samsung.android.sm.provider/1000}
,08-12 22:28:39.700   775  1677 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:28:39.710   775  1677 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:28:39.710   775  1677 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:28:39.710   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:28:39.720   775   775 I MotionRecognitionService: Plugged
,08-12 22:28:39.720   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:28:39.720   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:28:39.720   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:28:39.730   775  1677 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms
,08-12 22:28:39.730   775  1677 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 775) 
,08-12 22:28:39.740  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:28:39.740  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:28:39.740  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:28:39.740  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:28:39.740   775  1677 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,08-12 22:28:39.760   775  1677 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-12 22:28:39.770  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:28:39.770  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:28:39.780  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:28:39.780   775  1677 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-12 22:28:39.780  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:28:39.780  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:28:39.800   775  1677 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-12 22:28:39.800   775  1677 D BatteryService: turn on LED for fully charged
,08-12 22:28:40.170   775  1219 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,08-12 22:28:40.170   775   918 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,08-12 22:28:40.170   775   918 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-12 22:28:40.180   775   918 D SensorManager: unregisterListener ::   
,08-12 22:28:40.190   775   918 D lights  : led_pattern : 5 +
,08-12 22:28:40.200   775   918 D lights  : led_pattern : 5 -
,08-12 22:28:40.210   775   918 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-12 22:28:40.210   775   918 V AlarmManager:  remove PendingIntent] PendingIntent{484aa3a: PendingIntentRecord{960cc48 android broadcastIntent}}
,08-12 22:28:43.720   775  3391 D SSRM:n  : SIOP:: AP = 330, PST = 399, CUR = 350, LCD = 0
,08-12 22:28:43.880   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:28:49.790   775  1694 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:28:49.790   775  1694 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:28:49.800   775  1694 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:28:49.800   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:28:49.800   775   775 I MotionRecognitionService: Plugged
,08-12 22:28:49.810   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:28:49.810   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:28:49.810   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:28:49.810   775  1694 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 20ms
,08-12 22:28:49.820   775  1694 D BatteryService: stay LED for fully charged
,08-12 22:28:49.820  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:28:49.820  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:28:49.820  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:28:49.840  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:28:49.840  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:28:49.850  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:28:49.850  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:28:49.850  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:28:53.780   775  3391 D SSRM:n  : SIOP:: AP = 320, PST = 384, CUR = 350, LCD = 0
,08-12 22:29:00.000   775  1237 V AlarmManager: Expired Alarm result :8
,08-12 22:29:00.070   775  2270 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:29:00.080   775  2270 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:29:00.080   775  2270 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:29:00.080   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:29:00.100   775   775 I MotionRecognitionService: Plugged
,08-12 22:29:00.100   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:29:00.100   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:29:00.110   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:29:00.110   775  2270 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-12 22:29:00.110   775  2270 D BatteryService: stay LED for fully charged
,08-12 22:29:00.120  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:29:00.120  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:29:00.120  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:29:00.130  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:29:00.140  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:29:00.150  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:00.150  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:00.150  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:03.840   775  3391 D SSRM:n  : SIOP:: AP = 320, PST = 368, CUR = 350, LCD = 0
,08-12 22:29:03.890   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:29:04.470   775  1550 E Watchdog: !@Sync 6 [08-12 22:29:04.487]
,08-12 22:29:06.130  1740  1810 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 22:29:10.160   775  2268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:29:13.900   775  3391 D SSRM:n  : SIOP:: AP = 320, PST = 355, CUR = 350, LCD = 0
,08-12 22:29:20.240   775  2271 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:29:23.890   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:29:23.960   775  3391 D SSRM:n  : SIOP:: AP = 310, PST = 341, CUR = 350, LCD = 0
,08-12 22:29:30.330   775  1638 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:29:30.330   775  1638 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:29:30.330   775  1638 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:29:30.340   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:29:30.350   775   775 I MotionRecognitionService: Plugged
,08-12 22:29:30.350   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:29:30.350   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:29:30.360   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:29:30.360   775  1638 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-12 22:29:30.360   775  1638 D BatteryService: stay LED for fully charged
,08-12 22:29:30.370  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:29:30.370  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:29:30.370  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:29:30.390  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:29:30.390  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:29:30.400  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:30.400  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 22:29:30.400  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:34.020   775  3391 D SSRM:n  : SIOP:: AP = 310, PST = 331, CUR = 350, LCD = 0
,08-12 22:29:34.480   775  1550 E Watchdog: !@Sync 7 [08-12 22:29:34.493]
,08-12 22:29:40.410   775  1677 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:29:40.410   775  1677 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:29:40.410   775  1677 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:29:40.420   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:29:40.430   775   775 I MotionRecognitionService: Plugged
,08-12 22:29:40.430   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:29:40.430   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:29:40.440   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:29:40.440   775  1677 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-12 22:29:40.440   775  1677 D BatteryService: stay LED for fully charged
,08-12 22:29:40.460  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:29:40.460  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:29:40.470  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:29:40.480  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:29:40.480  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:29:40.490  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:40.490  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:40.490  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:43.900   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:29:44.080   775  3391 D SSRM:n  : SIOP:: AP = 310, PST = 324, CUR = 350, LCD = 0
,08-12 22:29:50.490   775  2103 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:29:50.500   775  2103 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:29:50.500   775  2103 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:29:50.500   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:29:50.520   775   775 I MotionRecognitionService: Plugged
,08-12 22:29:50.520   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:29:50.520   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:29:50.520   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:29:50.530   775  2103 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-12 22:29:50.530   775  2103 D BatteryService: stay LED for fully charged
,08-12 22:29:50.540  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:29:50.540  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:29:50.540  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:29:50.570  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:50.580  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:29:50.580  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:29:50.580  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:50.580  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:29:54.140   775  3391 D SSRM:n  : SIOP:: AP = 310, PST = 320, CUR = 350, LCD = 0
,08-12 22:30:00.570   775  1217 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:30:00.580   775  1217 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:30:00.580   775  1217 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:30:00.590   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:30:00.600   775   775 I MotionRecognitionService: Plugged
,08-12 22:30:00.600   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:30:00.600   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:30:00.600   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:30:00.610   775  1217 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-12 22:30:00.610   775  1217 D BatteryService: stay LED for fully charged
,08-12 22:30:00.620  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:30:00.620  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:30:00.620  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:30:00.630  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:30:00.630  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:30:00.650  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:30:00.650  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 22:30:00.650  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:30:03.900   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:30:04.200   775  3391 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 350, LCD = 0
,08-12 22:30:04.480   775  1550 E Watchdog: !@Sync 8 [08-12 22:30:04.497]
,08-12 22:30:06.150  1740  1810 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 22:30:06.400  1740  1810 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 245ms lastUpdatedAfter : 167944ms
,08-12 22:30:10.660   775  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:30:14.260   775  3391 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 350, LCD = 0
,08-12 22:30:20.750   775   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:30:23.910   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:30:24.320   775  3391 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 350, LCD = 0
,08-12 22:30:30.830   775  1694 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:30:30.830   775  1694 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 22:30:30.830   775  1694 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:30:30.830   775  1694 D BatteryService: stay LED for fully charged
08-12 22:30:30.830   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:30:30.840   775   775 I MotionRecognitionService: Plugged
,08-12 22:30:30.840   775   775 D MotionRecognitionService:   cableConnection= 1
08-12 22:30:30.840   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 22:30:30.840   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:30:30.840  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:30:30.840  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:30:30.840  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:30:30.850  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:30:30.860  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:30:30.870  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:30:30.870  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 22:30:30.870  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:30:34.380   775  3391 D SSRM:n  : SIOP:: AP = 300, PST = 311, CUR = 350, LCD = 0
,08-12 22:30:34.490   775  1550 E Watchdog: !@Sync 9 [08-12 22:30:34.502]
,08-12 22:30:40.940   775  1677 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:30:40.940   775  1677 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-12 22:30:40.940   775  1677 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-12 22:30:40.940   775  1677 D BatteryService: stay LED for fully charged
,08-12 22:30:40.940   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:30:40.950   775   775 I MotionRecognitionService: Plugged
,08-12 22:30:40.950   775   775 D MotionRecognitionService:   cableConnection= 1
08-12 22:30:40.950   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 22:30:40.950   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:30:40.950  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:30:40.950  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 22:30:40.950  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:30:40.960  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:30:40.960  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:30:40.980  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:30:40.980  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 22:30:40.980  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:30:43.920   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:30:44.440   775  3391 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 350, LCD = 0
,08-12 22:30:49.280   775  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-12 22:30:49.290   775  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-12 22:30:49.300   775  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,08-12 22:30:49.310   775  1231 I TLC_TIMA_PKM_initialize: initializing...
,08-12 22:30:49.310   775  1231 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,08-12 22:30:49.310   775  1231 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-12 22:30:49.320   775  1231 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,08-12 22:30:49.320   775  1231 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-12 22:30:49.320   775  1231 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-12 22:30:49.320   775  1231 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,08-12 22:30:49.320   775  1231 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,08-12 22:30:49.330   775  1231 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-12 22:30:49.330   775  1231 D QSEECOMAPI: : App is not loaded in QSEE
,08-12 22:30:49.380   775  1231 D QSEECOMAPI: : Loaded image: APP id = 3
,08-12 22:30:49.390   775  1231 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-12 22:30:49.400   775  1231 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-12 22:30:51.030   775  2271 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:30:52.680   775  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-12 22:30:52.680   775  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-12 22:30:52.700   775  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-12 22:30:52.700   775  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-12 22:30:54.500   775  3391 D SSRM:n  : SIOP:: AP = 310, PST = 308, CUR = 350, LCD = 0
,08-12 22:31:02.600   306  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 22:31:02.600   306  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 22:31:02.600   306  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 22:31:03.780   306  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 22:31:03.780   306  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 22:31:03.790   306  1125 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 22:31:03.910   775  3425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 22:31:04.490   775  1550 E Watchdog: !@Sync 10 [08-12 22:31:04.506]
,08-12 22:31:04.560   775  3391 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 350, LCD = 0
,08-12 22:31:04.690   775  1237 V AlarmManager: Expired Alarm result :4
,08-12 22:31:04.710  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-12 22:31:04.710  1381  1381 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-12 22:31:04.720  1381  1381 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 22:31:04.770   775  2268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:31:04.770   775  2268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:31:04.770   775  2268 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-12 22:31:04.770   775  2268 D BatteryService: stay LED for fully charged
,08-12 22:31:04.770  1381  1381 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-12 22:31:04.780  1381  1381 D SecKeyguardClockView: HomeTimezone(): 1
,08-12 22:31:04.800  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:31:04.800  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:31:04.810  1539  1539 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-12 22:31:04.810  1539  1539 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-12 22:31:04.820   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:31:04.830  1539  1539 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-12 22:31:04.840  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:31:04.840  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:31:04.850   775   775 I MotionRecognitionService: Plugged
,08-12 22:31:04.850  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:31:04.850   775   775 D MotionRecognitionService:   cableConnection= 1
08-12 22:31:04.850   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 22:31:04.850   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:31:04.860  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:31:04.860  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:31:04.860  1381  1381 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:31:04.860  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:31:04.870  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:31:04.870  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:31:04.870  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:31:04.870  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 22:31:04.870  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:31:04.880  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:31:04.920  1381  1381 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 22:31:06.410  1740  1810 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-12 22:31:08.620   306  1126 D Netd    : Iface wlan0 link up
,08-12 22:31:08.620  1539  1539 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
,08-12 22:31:08.640   775   861 D Tethering: interfaceLinkStateChanged wlan0, true
,08-12 22:31:08.640   775   861 D Tethering: interfaceStatusChanged wlan0, true
,08-12 22:31:08.640  1539  1539 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,08-12 22:31:08.670   775  1323 D WifiP2pService: InactiveState{ what=147461 }
,08-12 22:31:08.670   775  1323 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-12 22:31:08.680   775  1323 D WifiP2pService: DefaultState{ what=147461 }
,08-12 22:31:08.740   775   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9635e75 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{acaa075 1381:com.android.systemui/u0a58}
,08-12 22:31:14.610   775  3391 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 350, LCD = 0
,08-12 22:31:14.850   775  1638 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 22:31:14.860   775  1638 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 22:31:14.860   775  1638 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-12 22:31:14.860   775   775 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 22:31:14.880   775   775 I MotionRecognitionService: Plugged
,08-12 22:31:14.880   775   775 D MotionRecognitionService:   cableConnection= 1
,08-12 22:31:14.880   775   775 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-12 22:31:14.880   775   775 D MotionRecognitionService: skip setTransmitPower. 
,08-12 22:31:14.890   775  1638 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-12 22:31:14.890   775  1638 D BatteryService: stay LED for fully charged
,08-12 22:31:14.900  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:31:14.900  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 22:31:14.900  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 22:31:14.930  2178  2178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 22:31:14.930  2178  2697 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 22:31:14.930  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:31:14.930  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 22:31:14.930  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 22:31:17.310  6525  6640 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 22:31:17.310  6525  6640 I jxcore-log: 
,08-12 22:31:18.520  2185  2185 E audit   : type=1400 msg=audit(1471033878.520:289): avc:  denied  { execmod } for  pid=7088 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 22:31:18.530  2185  2185 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 22:31:18.530  2185  2185 E audit   : type=1300 msg=audit(1471033878.520:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f83000 a1=51000 a2=5 a3=4 items=0 ppid=3505 ppcomm=adbd pid=7088 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 22:31:18.530  2185  2185 E audit   : type=1327 msg=audit(1471033878.520:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 22:31:18.530  2185  2185 E audit   : type=1320 msg=audit(1471033878.520:289): 
,08-12 22:31:18.580  2185  2185 E audit   : type=1400 msg=audit(1471033878.580:290): avc:  denied  { execmod } for  pid=7088 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 22:31:18.580  2185  2185 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 22:31:18.580  2185  2185 E audit   : type=1300 msg=audit(1471033878.580:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f42000 a1=51000 a2=5 a3=4 items=0 ppid=3505 ppcomm=adbd pid=7088 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 22:31:18.580  2185  2185 E audit   : type=1327 msg=audit(1471033878.580:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 22:31:18.580  2185  2185 E audit   : type=1320 msg=audit(1471033878.580:290): 
,08-12 22:31:18.630  2185  2185 E audit   : type=1400 msg=audit(1471033878.630:291): avc:  denied  { execmod } for  pid=7088 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 22:31:18.630  2185  2185 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 22:31:18.630  7088  7088 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 22:31:18.630  2185  2185 E audit   : type=1300 msg=audit(1471033878.630:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f43000 a1=51000 a2=5 a3=4 items=0 ppid=3505 ppcomm=adbd pid=7088 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 22:31:18.630  2185  2185 E audit   : type=1327 msg=audit(1471033878.630:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 22:31:18.630  2185  2185 E audit   : type=1320 msg=audit(1471033878.630:291): 
,08-12 22:31:18.630  7088  7088 D AndroidRuntime: CheckJNI is OFF
,08-12 22:31:18.640  7088  7088 D AndroidRuntime: readGMSProperty: start
08-12 22:31:18.640  7088  7088 D AndroidRuntime: readGMSProperty: already setted!!
08-12 22:31:18.640  7088  7088 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 22:31:18.640  7088  7088 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 22:31:18.640  7088  7088 D AndroidRuntime: readGMSProperty: end
08-12 22:31:18.640  7088  7088 D AndroidRuntime: addProductProperty: start
,08-12 22:31:18.640  7088  7088 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 22:31:18.640  7088  7088 W art     : af0e4000-b200a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
,08-12 22:31:18.640  7088  7088 W art     : b200a000-b4279000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 22:31:18.640  7088  7088 W art     : b4279000-b427a000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 22:31:18.640  7088  7088 W art     : b427a000-b42a3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 22:31:18.640  7088  7088 W art     : b42a3000-b46f1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 22:31:18.640  7088  7088 W art     : b46f1000-b46f2000 ---p 00000000 00:00 0 
08-12 22:31:18.640  7088  7088 W art     : b46f2000-b46fc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 22:31:18.640  7088  7088 W art     : b46fc000-b46fd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 22:31:18.640  7088  7088 W art     : b46fd000-b46ff000 rw-p 00000000 00:00 0 
08-12 22:31:18.640  7088  7088 W art     : b46ff000-b4700000 r--p 00000000 00:00 0 
08-12 22:31:18.640  7088  7088 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 22:31:18.640  7088  7088 W art     : b4814000-b4817000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 22:31:18.640  7088  7088 W art     : b4817000-b4818000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 22:31:18.650  7088  7088 W art     : b4818000-b4819000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 22:31:18.650  7088  7088 W art     : b4819000-b481a000 r--p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b481a000-b483a000 r--s 00000000 00:0b 6702       /dev/__properties__
,08-12 22:31:18.650  7088  7088 W art     : b483a000-b524b000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 22:31:18.650  7088  7088 W art     : b524b000-b524c000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b524c000-b5295000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 22:31:18.650  7088  7088 W art     : b5295000-b5296000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 22:31:18.650  7088  7088 W art     : b5296000-b529e000 rw-p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b529e000-b529f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.650  7088  7088 W art     : b529f000-b52d4000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 22:31:18.650  7088  7088 W art     : b52d4000-b52d5000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b52d5000-b52d6000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
,08-12 22:31:18.650  7088  7088 W art     : b52d6000-b52d7000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 22:31:18.650  7088  7088 W art     : b52d7000-b532f000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 22:31:18.650  7088  7088 W art     : b532f000-b5330000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5330000-b5331000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 22:31:18.650  7088  7088 W art     : b5331000-b5332000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 22:31:18.650  7088  7088 W art     : b5333000-b5339000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 22:31:18.650  7088  7088 W art     : b5339000-b533a000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 22:31:18.650  7088  7088 W art     : b533a000-b533b000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-12 22:31:18.650  7088  7088 W art     : b533b000-b533d000 rw-p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b533e000-b5348000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 22:31:18.650  7088  7088 W art     : b5348000-b534b000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 22:31:18.650  7088  7088 W art     : b534b000-b534c000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 22:31:18.650  7088  7088 W art     : b534d000-b5364000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 22:31:18.650  7088  7088 W art     : b5364000-b5365000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5365000-b5366000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 22:31:18.650  7088  7088 W art     : b5366000-b5367000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-12 22:31:18.650  7088  7088 W art     : b5368000-b5372000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 22:31:18.650  7088  7088 W art     : b5372000-b5373000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 22:31:18.650  7088  7088 W art     : b5373000-b5374000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 22:31:18.650  7088  7088 W art     : b5374000-b5378000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 22:31:18.650  7088  7088 W art     : b5378000-b5379000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 22:31:18.650  7088  7088 W art     : b5379000-b537a000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 22:31:18.650  7088  7088 W art     : b537a000-b5390000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
,08-12 22:31:18.650  7088  7088 W art     : b5390000-b5391000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 22:31:18.650  7088  7088 W art     : b5391000-b5392000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 22:31:18.650  7088  7088 W art     : b5392000-b539f000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 22:31:18.650  7088  7088 W art     : b539f000-b53a0000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 22:31:18.650  7088  7088 W art     : b53a0000-b53a1000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 22:31:18.650  7088  7088 W art     : b53a1000-b5401000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 22:31:18.650  7088  7088 W art     : b5401000-b5404000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
,08-12 22:31:18.650  7088  7088 W art     : b5404000-b5408000 rw-p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5408000-b5469000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 22:31:18.650  7088  7088 W art     : b5469000-b546a000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 22:31:18.650  7088  7088 W art     : b546a000-b54b9000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
,08-12 22:31:18.650  7088  7088 W art     : b54b9000-b54bb000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so,
08-12 22:31:18.650  7088  7088 W art     : b54bb000-b54bc000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 22:31:18.650  7088  7088 W art     : b54bc000-b54bd000 rw-p 00000000 00:00 0 
,08-12 22:31:18.650  7088  7088 W art     : b54bd000-b54c4000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 22:31:18.650  7088  7088 W art     : b54c4000-b54c5000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-12 22:31:18.650  7088  7088 W art     : b54c5000-b54c6000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-12 22:31:18.650  7088  7088 W art     : avc_common.so
,08-12 22:31:18.650  7088  7088 W art     : b54c7000-b54ca000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 22:31:18.650  7088  7088 W art     : b54ca000-b54cb000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-12 22:31:18.650  7088  7088 W art     : b54cb000-b54cc000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-12 22:31:18.650  7088  7088 W art     : enc_common.so
,08-12 22:31:18.650  7088  7088 W art     : b54cd000-b54d1000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 22:31:18.650  7088  7088 W art     : b54d1000-b54d2000 ---p 00000000 00:00 0 ,
08-12 22:31:18.650  7088  7088 W art     : b54d2000-b54d3000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
,08-12 22:31:18.650  7088  7088 W art     : b54d3000-b54d4000 rw-p 00005000 b3:17 2510       /syste
,08-12 22:31:18.650  7088  7088 W art     : m/lib/libpowermanager.so
08-12 22:31:18.650  7088  7088 W art     : b54d5000-b54f2000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so,
08-12 22:31:18.650  7088  7088 W art     : b54f2000-b54f3000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 22:31:18.650  7088  7088 W art     : b54f3000-b54f4000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so,
08-12 22:31:18.650  7088  7088 W art     : b54f5000-b54fa000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 22:31:18.650  7088  7088 W art     : b54fa000-b54fb000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-12 22:31:18.650  7088  7088 W art     : b54fb000-b54fc000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 22:31:18.650  7088  7088 W art     : b54fd000-b552e000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-12 22:31:18.650  7088  7088 W art     : b552e000-b5531000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 22:31:18.650  7088  7088 W art     : b5531000-b5532000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 22:31:18.650  7088  7088 W art     : b5533000-b556e000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 22:31:18.650  7088  7088 W art     : b556e000-b556f000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
,08-12 22:31:18.650  7088  7088 W art     : b556f000-b5570000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 22:31:18.650  7088  7088 W art     : b5571000-b5578000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 22:31:18.650  7088  7088 W art     : b5578000-b5579000 ---p 00000000 00:00 0 ,
08-12 22:31:18.650  7088  7088 W art     : b5579000-b557a000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so,
08-12 22:31:18.650  7088  7088 W art     : b557a000-b557b000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 22:31:18.650  7088  7088 W art     : b557b000-b557c000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 22:31:18.650  7088  7088 W art     : b557c000-b5593000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 22:31:18.650  7088  7088 W art     : b5593000-b5594000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5594000-b5597000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
,08-12 22:31:18.650  7088  7088 W art     : b5597000-b5598000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 22:31:18.650  7088  7088 W art     : b5598000-b55b7000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so,
08-12 22:31:18.650  7088  7088 W art     : b55b7000-b55b8000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 22:31:18.650  7088  7088 W art     : b55b8000-b55b9000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so,
08-12 22:31:18.650  7088  7088 W art     : b55b9000-b55f7000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 22:31:18.650  7088  7088 W art     : b55f7000-b55f8000 ---p 00000000 00:00 0 
,08-12 22:31:18.650  7088  7088 W art     : b55f8000-b55fa000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
,08-12 22:31:18.650  7088  7088 W art     : b55fa000-b55fb000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 22:31:18.650  7088  7088 W art     : b55fc000-b5603000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 22:31:18.650  7088  7088 W art     : b5603000-b5604000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
,08-12 22:31:18.650  7088  7088 W art     : b5604000-b5605000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 22:31:18.650  7088  7088 W art     : b5606000-b5609000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 22:31:18.650  7088  7088 W art     : b5609000-b560a000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
,08-12 22:31:18.650  7088  7088 W art     : b560a000-b560b000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 22:31:18.650  7088  7088 W art     : b560b000-b5611000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 22:31:18.650  7088  7088 W art     : b5611000-b5612000 ---p 00000000 00:00 0 
,08-12 22:31:18.650  7088  7088 W art     : b5612000-b5613000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 22:31:18.650  7088  7088 W art     : b5613000-b5614000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 22:31:18.650  7088  7088 W art     : b5614000-b561d000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
,08-12 22:31:18.650  7088  7088 W art     : b561d000-b561e000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 22:31:18.650  7088  7088 W art     : b561e000-b561f000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 22:31:18.650  7088  7088 W art     : b561f000-b56b0000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
,08-12 22:31:18.650  7088  7088 W art     : b56b0000-b56b1000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b56b1000-b56bc000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 22:31:18.650  7088  7088 W art     : b56bc000-b56bd000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
,08-12 22:31:18.650  7088  7088 W art     : b56be000-b56d0000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 22:31:18.650  7088  7088 W art     : b56d0000-b56d1000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 22:31:18.650  7088  7088 W art     : b56d1000-b56d2000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
,08-12 22:31:18.650  7088  7088 W art     : b56d3000-b56d8000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 22:31:18.650  7088  7088 W art     : b56d8000-b56d9000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 22:31:18.650  7088  7088 W art     : b56d9000-b56da000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
,08-12 22:31:18.650  7088  7088 W art     : b56db000-b5748000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 22:31:18.650  7088  7088 W art     : b5748000-b5749000 ---p 00000000 00:00 0 
,08-12 22:31:18.650  7088  7088 W art     : b5749000-b574b000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 22:31:18.650  7088  7088 W art     : b574b000-b574c000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 22:31:18.650  7088  7088 W art     : b574c000-b574d000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 22:31:18.650  7088  7088 W art     : b574d000-b5754000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 22:31:18.650  7088  7088 W art     : b5754000-b5755000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 22:31:18.650  7088  7088 W art     : b5755000-b5756000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-12 22:31:18.650  7088  7088 W art     : b5757000-b57d7000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 22:31:18.650  7088  7088 W art     : b57d7000-b57d8000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b57d8000-b57d9000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 22:31:18.650  7088  7088 W art     : b57d9000-b57da000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
,08-12 22:31:18.650  7088  7088 W art     : b57da000-b57f1000 rw-p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b57f1000-b5828000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 22:31:18.650  7088  7088 W art     : ib/libqc-opt.so
08-12 22:31:18.650  7088  7088 W art     : b5828000-b5829000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
,08-12 22:31:18.650  7088  7088 W art     : b5829000-b582a000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 22:31:18.650  7088  7088 W art     : b582a000-b5846000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 22:31:18.650  7088  7088 W art     : b5846000-b5847000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 22:31:18.650  7088  7088 W art     : b5847000-b5848000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 22:31:18.650  7088  7088 W art     : b5849000-b58aa000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
,08-12 22:31:18.650  7088  7088 W art     : b58aa000-b58ac000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 22:31:18.650  7088  7088 W art     : b58ac000-b58ad000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 22:31:18.650  7088  7088 W art     : b58ae000-b58d5000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 22:31:18.650  7088  7088 W art     : b58d5000-b58d6000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b58d6000-b58d7000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
,08-12 22:31:18.650  7088  7088 W art     : b58d7000-b58d8000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 22:31:18.650  7088  7088 W art     : b58d9000-b58e1000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 22:31:18.650  7088  7088 W art     : b58e1000-b58e3000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 22:31:18.650  7088  7088 W art     : b58e3000-b58e4000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-12 22:31:18.650  7088  7088 W art     : b58e5000-b58e8000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 22:31:18.650  7088  7088 W art     : b58e8000-b58e9000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 22:31:18.650  7088  7088 W art     : b58e9000-b58ea000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 22:31:18.650  7088  7088 W art     : b58ea000-b58ee000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 22:31:18.650  7088  7088 W art     : b58ee000-b58ef000 ---p 00000000 00:00 0 
,08-12 22:31:18.650  7088  7088 W art     : b58ef000-b58f0000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 22:31:18.650  7088  7088 W art     : b58f0000-b58f1000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 22:31:18.650  7088  7088 W art     : b58f1000-b5901000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 22:31:18.650  7088  7088 W art     : b5901000-b5902000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
,08-12 22:31:18.650  7088  7088 W art     : b5902000-b5903000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 22:31:18.650  7088  7088 W art     : b5903000-b5949000 rw-p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5949000-b5952000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 22:31:18.650  7088  7088 W art     : b5952000-b5953000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 22:31:18.650  7088  7088 W art     : b5953000-b5954000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so,
08-12 22:31:18.650  7088  7088 W art     : b5955000-b595a000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 22:31:18.650  7088  7088 W art     : b595a000-b595b000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 22:31:18.650  7088  7088 W art     : b595b000-b595c000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 22:31:18.650  7088  7088 W art     : b595c000-b595f000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so,
08-12 22:31:18.650  7088  7088 W art     : b595f000-b5960000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5960000-b5961000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 22:31:18.650  7088  7088 W art     : b5961000-b5962000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 22:31:18.650  7088  7088 W art     : b5963000-b597b000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
,08-12 22:31:18.650  7088  7088 W art     : b597b000-b597c000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b597c000-b597d000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 22:31:18.650  7088  7088 W art     : b597d000-b597e000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 22:31:18.650  7088  7088 W art     : b597f000-b5b19000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 22:31:18.650  7088  7088 W art     : b5b19000-b5b1a000 ---p 00000000 00:00 0 
,08-12 22:31:18.650  7088  7088 W art     : b5b1a000-b5b27000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 22:31:18.650  7088  7088 W art     : b5b27000-b5b28000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 22:31:18.650  7088  7088 W art     : b5b28000-b5b2c000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
,08-12 22:31:18.650  7088  7088 W art     : b5b2c000-b5b2d000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5b2d000-b5b2e000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 22:31:18.650  7088  7088 W art     : b5b2e000-b5b2f000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 22:31:18.650  7088  7088 W art     : b5b2f000-b5b42000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 22:31:18.650  7088  7088 W art     : b5b42000-b5b43000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
,08-12 22:31:18.650  7088  7088 W art     : b5b43000-b5b44000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 22:31:18.650  7088  7088 W art     : b5b44000-b5b45000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:31:18.650  7088  7088 W art     : b5b45000-b5b90000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 22:31:18.650  7088  7088 W art     : b5b90000-b5b91000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
,08-12 22:31:18.650  7088  7088 W art     : b5b91000-b5b92000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 22:31:18.650  7088  7088 W art     : b5b92000-b5b94000 rw-p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5b95000-b5ba6000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 22:31:18.650  7088  7088 W art     : b5ba6000-b5ba7000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5ba7000-b5ba8000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
,08-12 22:31:18.650  7088  7088 W art     : b5ba8000-b5ba9000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 22:31:18.650  7088  7088 W art     : b5baa000-b5bb4000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 22:31:18.650  7088  7088 W art     : b5bb4000-b5bb6000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 22:31:18.650  7088  7088 W art     : b5bb6000-b5bb7000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
,08-12 22:31:18.650  7088  7088 W art     : b5bb7000-b5bd0000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 22:31:18.650  7088  7088 W art     : b5bd0000-b5bd1000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 22:31:18.650  7088  7088 W art     : b5bd1000-b5bd4000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 22:31:18.650  7088  7088 W art     : b5bd4000-b5bd8000 rw-p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5bd8000-b5c4c000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so,
08-12 22:31:18.650  7088  7088 W art     : b5c4c000-b5c4d000 ---p 00000000 00:00 0 
,08-12 22:31:18.650  7088  7088 W art     : b5c4d000-b5c50000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 22:31:18.650  7088  7088 W art     : b5c50000-b5c51000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 22:31:18.650  7088  7088 W art     : b5c51000-b5c52000 r--p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b5c52000-b5c55000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
,08-12 22:31:18.650  7088  7088 W art     : b5c55000-b5c56000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 22:31:18.650  7088  7088 W art     : b5c56000-b5c57000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 22:31:18.650  7088  7088 W art     : b5c57000-b5c58000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.650  7088  7088 W art     : b5c58000-b5c5d000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
,08-12 22:31:18.650  7088  7088 W art     : b5c5d000-b5c5e000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 22:31:18.650  7088  7088 W art     : b5c5e000-b5c5f000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 22:31:18.650  7088  7088 W art     : b5c5f000-b5c60000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.650  7088  7088 W art     : b5c60000-b5c63000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 22:31:18.650  7088  7088 W art     : b5c63000-b5c64000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
,08-12 22:31:18.650  7088  7088 W art     : b5c64000-b5c65000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 22:31:18.650  7088  7088 W art     : b5c65000-b5c66000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.650  7088  7088 W art     : b5c66000-b5c6a000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 22:31:18.650  7088  7088 W art     : b5c6a000-b5c6b000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 22:31:18.650  7088  7088 W art     : b5c6b000-b5c6c000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so,
08-12 22:31:18.650  7088  7088 W art     : b5c6c000-b5c6d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:31:18.650  7088  7088 W art     : b5c6d000-b5c71000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 22:31:18.650  7088  7088 W art     : b5c71000-b5c72000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 22:31:18.650  7088  7088 W art     : b5c72000-b5c73000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 22:31:18.650  7088  7088 W art     : b5c73000-b5c74000 r--p 00000000 00:00 0          [anon:linker_alloc],
08-12 22:31:18.650  7088  7088 W art     : b5c74000-b5c82000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 22:31:18.650  7088  7088 W art     : b5c82000-b5c83000 ---p 00000000 00:00 0 
,08-12 22:31:18.650  7088  7088 W art     : b5c83000-b5c84000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 22:31:18.650  7088  7088 W art     : b5c84000-b5c85000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 22:31:18.650  7088  7088 W art     : b5c85000-b5c8f000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 22:31:18.650  7088  7088 W art     : b5c8f000-b5c92000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 22:31:18.650  7088  7088 W art     : b5c92000-b5c93000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 22:31:18.650  7088  7088 W art     : b5c93000-b5c94000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 22:31:18.650  7088  7088 W art     : b5c94000-b5c9e000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 22:31:18.650  7088  7088 W art     : b5c9e000-b5ca1000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 22:31:18.650  7088  7088 W art     : b5ca1000-b5ca2000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 22:31:18.650  7088  7088 W art     : b5ca2000-b5ca6000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 22:31:18.650  7088  7088 W art     : b5ca6000-b5ca7000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 22:31:18.650  7088  7088 W art     : b5ca7000-b5ca8000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 22:31:18.650  7088  7088 W art     : b5ca8000-b5ca9000 r--p 00000000 00:00 0          [anon:linker_alloc],
08-12 22:31:18.650  7088  7088 W art     : b5ca9000-b5cb6000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 22:31:18.650  7088  7088 W art     : b5cb6000-b5cb8000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 22:31:18.650  7088  7088 W art     : b5cb8000-b5cb9000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 22:31:18.650  7088  7088 W art     : b5cb9000-b60cb000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 22:31:18.650  7088  7088 W art     : b60cb000-b60cc000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b60cc000-b60d5000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so,
08-12 22:31:18.650  7088  7088 W art     : b60d5000-b60d9000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 22:31:18.650  7088  7088 W art     : b60d9000-b60da000 rw-p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b60da000-b60e1000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-12 22:31:18.650  7088  7088 W art     : b60e1000-b60e2000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 22:31:18.650  7088  7088 W art     : b60e2000-b60e3000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 22:31:18.650  7088  7088 W art     : b60e3000-b60e4000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 22:31:18.650  7088  7088 W art     : b60e4000-b60ff000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-12 22:31:18.650  7088  7088 W art     : b60ff000-b6100000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 22:31:18.650  7088  7088 W art     : b6100000-b6101000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 22:31:18.650  7088  7088 W art     : b6101000-b6102000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.650  7088  7088 W art     : b6102000-b614e000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 22:31:18.650  7088  7088 W art     : b614e000-b614f000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b614f000-b6150000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 22:31:18.650  7088  7088 W art     : b6150000-b6151000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 22:31:18.650  7088  7088 W art     : b6151000-b6152000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.650  7088  7088 W art     : b6152000-b6156000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 22:31:18.650  7088  7088 W art     : b6156000-b6157000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b6157000-b6158000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 22:31:18.650  7088  7088 W art     : b6158000-b6159000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-12 22:31:18.650  7088  7088 W art     : b6159000-b6191000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 22:31:18.650  7088  7088 W art     : b6191000-b6192000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 22:31:18.650  7088  7088 W art     : b6192000-b6193000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 22:31:18.650  7088  7088 W art     : b6193000-b6194000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.650  7088  7088 W art     : b6194000-b6232000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 22:31:18.650  7088  7088 W art     : b6232000-b6233000 ---p 00000000 00:00 0 
08-12 22:31:18.650  7088  7088 W art     : b6233000-b6251000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 22:31:18.660  7088  7088 W art     : b6251000-b6252000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-12 22:31:18.660  7088  7088 W art     : b6252000-b63c5000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 22:31:18.660  7088  7088 W art     : b63c5000-b63d0000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 22:31:18.660  7088  7088 W art     : b63d0000-b63d1000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 22:31:18.660  7088  7088 W art     : b63d1000-b64e8000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-12 22:31:18.660  7088  7088 W art     : b64e8000-b64f3000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 22:31:18.660  7088  7088 W art     : b64f3000-b64f4000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 22:31:18.660  7088  7088 W art     : b64f4000-b64f8000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b64f8000-b651c000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-12 22:31:18.660  7088  7088 W art     : b651c000-b651e000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 22:31:18.660  7088  7088 W art     : b651e000-b651f000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 22:31:18.660  7088  7088 W art     : b651f000-b65c5000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 22:31:18.660  7088  7088 W art     : b65c5000-b65d2000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-12 22:31:18.660  7088  7088 W art     : b65d2000-b65d3000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 22:31:18.660  7088  7088 W art     : b65d3000-b65d4000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b65d4000-b6627000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 22:31:18.660  7088  7088 W art     : b6627000-b6628000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6628000-b6629000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 22:31:18.660  7088  7088 W art     : b6629000-b662a000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 22:31:18.660  7088  7088 W art     : b662a000-b662f000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b662f000-b6641000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 22:31:18.660  7088  7088 W art     : b6641000-b6642000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6642000-b6643000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 22:31:18.660  7088  7088 W art     : b6643000-b6644000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 22:31:18.660  7088  7088 W art     : b6644000-b664b000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 22:31:18.660  7088  7088 W art     : b664b000-b664c000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 22:31:18.660  7088  7088 W art     : b664c000-b664d000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 22:31:18.660  7088  7088 W art     : b664d000-b664e000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b664e000-b6651000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 22:31:18.660  7088  7088 W art     : b6651000-b6652000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 22:31:18.660  7088  7088 W art     : b6652000-b6653000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 22:31:18.660  7088  7088 W art     : b6653000-b6657000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 22:31:18.660  7088  7088 W art     : b6657000-b6658000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 22:31:18.660  7088  7088 W art     : b6658000-b6659000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 22:31:18.660  7088  7088 W art     : b6659000-b6667000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 22:31:18.660  7088  7088 W art     : b6667000-b6668000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6668000-b6669000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 22:31:18.660  7088  7088 W art     : b6669000-b666a000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 22:31:18.660  7088  7088 W art     : b666a000-b6673000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 22:31:18.660  7088  7088 W art     : b6673000-b6674000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 22:31:18.660  7088  7088 W art     : b6674000-b6675000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 22:31:18.660  7088  7088 W art     : b6675000-b66db000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 22:31:18.660  7088  7088 W art     : b66db000-b66dc000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b66dc000-b66de000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 22:31:18.660  7088  7088 W art     : b66de000-b66e7000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 22:31:18.660  7088  7088 W art     : b66e7000-b66ea000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b66ea000-b6781000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 22:31:18.660  7088  7088 W art     : b6781000-b6783000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 22:31:18.660  7088  7088 W art     : b6783000-b6784000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 22:31:18.660  7088  7088 W art     : b6784000-b6785000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6785000-b6aa6000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 22:31:18.660  7088  7088 W art     : b6aa6000-b6aa7000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6aa7000-b6ac2000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 22:31:18.660  7088  7088 W art     : b6ac2000-b6ac6000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 22:31:18.660  7088  7088 W art     : b6ac6000-b6acb000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6acb000-b6ad3000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 22:31:18.660  7088  7088 W art     : b6ad3000-b6ad4000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 22:31:18.660  7088  7088 W art     : b6ad4000-b6ad5000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 22:31:18.660  7088  7088 W art     : b6ad5000-b6b03000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 22:31:18.660  7088  7088 W art     : b6b03000-b6b04000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6b04000-b6b0b000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 22:31:18.660  7088  7088 W art     : b6b0b000-b6b0c000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 22:31:18.660  7088  7088 W art     : b6b0c000-b6b52000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 22:31:18.660  7088  7088 W art     : b6b52000-b6b53000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6b53000-b6b56000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 22:31:18.660  7088  7088 W art     : b6b56000-b6b57000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 22:31:18.660  7088  7088 W art     : b6b57000-b6b72000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 22:31:18.660  7088  7088 W art     : b6b72000-b6b76000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 22:31:18.660  7088  7088 W art     : b6b76000-b6b77000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 22:31:18.660  7088  7088 W art     : b6b77000-b6bc4000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 22:31:18.660  7088  7088 W art     : b6bc4000-b6bc5000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6bc5000-b6bd1000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 22:31:18.660  7088  7088 W art     : b6bd1000-b6bd2000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 22:31:18.660  7088  7088 W art     : b6bd2000-b6bdf000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 22:31:18.660  7088  7088 W art     : b6bdf000-b6be0000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6be0000-b6be1000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 22:31:18.660  7088  7088 W art     : b6be1000-b6be2000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 22:31:18.660  7088  7088 W art     : b6be2000-b6bea000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 22:31:18.660  7088  7088 W art     : b6bea000-b6beb000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6beb000-b6bec000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 22:31:18.660  7088  7088 W art     : b6bec000-b6bed000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 22:31:18.660  7088  7088 W art     : b6bed000-b6bf4000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 22:31:18.660  7088  7088 W art     : b6bf4000-b6bf5000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 22:31:18.660  7088  7088 W art     : b6bf5000-b6bf6000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 22:31:18.660  7088  7088 W art     : b6bf6000-b6c0a000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 22:31:18.660  7088  7088 W art     : b6c0a000-b6c0c000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 22:31:18.660  7088  7088 W art     : b6c0c000-b6c0d000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 22:31:18.660  7088  7088 W art     : b6c0d000-b6c35000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 22:31:18.660  7088  7088 W art     : b6c35000-b6c37000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 22:31:18.660  7088  7088 W art     : b6c37000-b6c38000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 22:31:18.660  7088  7088 W art     : b6c38000-b6c3b000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 22:31:18.660  7088  7088 W art     : b6c3b000-b6c3c000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 22:31:18.660  7088  7088 W art     : b6c3c000-b6c3d000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 22:31:18.660  7088  7088 W art     : b6c3d000-b6c46000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 22:31:18.660  7088  7088 W art     : b6c46000-b6c47000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 22:31:18.660  7088  7088 W art     : b6c47000-b6c48000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 22:31:18.660  7088  7088 W art     : b6c48000-b6c68000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 22:31:18.660  7088  7088 W art     : b6c68000-b6c69000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 22:31:18.660  7088  7088 W art     : b6c69000-b6c6a000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 22:31:18.660  7088  7088 W art     : b6c6a000-b6cdd000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 22:31:18.660  7088  7088 W art     : b6cdd000-b6ce1000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 22:31:18.660  7088  7088 W art     : b6ce1000-b6ce4000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 22:31:18.660  7088  7088 W art     : b6ce4000-b6cee000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6cee000-b6d76000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 22:31:18.660  7088  7088 W art     : b6d76000-b6d77000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6d77000-b6d7b000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 22:31:18.660  7088  7088 W art     : b6d7b000-b6d7c000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 22:31:18.660  7088  7088 W art     : b6d7c000-b6d7d000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6d7d000-b6da6000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 22:31:18.660  7088  7088 W art     : b6da6000-b6da7000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6da7000-b6daa000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 22:31:18.660  7088  7088 W art     : b6daa000-b6dab000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 22:31:18.660  7088  7088 W art     : b6dab000-b6e85000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 22:31:18.660  7088  7088 W art     : b6e85000-b6e8c000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 22:31:18.660  7088  7088 W art     : b6e8c000-b6e94000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 22:31:18.660  7088  7088 W art     : b6e94000-b6e95000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6e95000-b6e96000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:31:18.660  7088  7088 W art     : b6e96000-b6e97000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 22:31:18.660  7088  7088 W art     : b6e97000-b6e98000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.660  7088  7088 W art     : b6e98000-b6e9b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.660  7088  7088 W art     : b6e9b000-b6ec0000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 22:31:18.660  7088  7088 W art     : b6ec0000-b6ec1000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6ec1000-b6ec8000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 22:31:18.660  7088  7088 W art     : b6ec8000-b6ec9000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 22:31:18.660  7088  7088 W art     : b6ec9000-b6ed0000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 22:31:18.660  7088  7088 W art     : b6ed0000-b6ed1000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 22:31:18.660  7088  7088 W art     : b6ed1000-b6ed2000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 22:31:18.660  7088  7088 W art     : b6ed2000-b6ed3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.660  7088  7088 W art     : b6ed3000-b6eeb000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 22:31:18.660  7088  7088 W art     : b6eeb000-b6eec000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6eec000-b6eed000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 22:31:18.660  7088  7088 W art     : b6eed000-b6eee000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 22:31:18.660  7088  7088 W art     : b6eee000-b6efc000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 22:31:18.660  7088  7088 W art     : b6efc000-b6efd000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6efd000-b6efe000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 22:31:18.660  7088  7088 W art     : b6efe000-b6eff000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 22:31:18.660  7088  7088 W art     : b6eff000-b6f00000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:31:18.660  7088  7088 W art     : b6f00000-b6f02000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.660  7088  7088 W art     : b6f02000-b6f03000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.660  7088  7088 W art     : b6f03000-b6f04000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 22:31:18.660  7088  7088 W art     : b6f04000-b6f05000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 22:31:18.660  7088  7088 W art     : b6f05000-b6f06000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 22:31:18.660  7088  7088 W art     : b6f06000-b6f26000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 22:31:18.660  7088  7088 W art     : b6f26000-b6f27000 r--p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6f27000-b6f28000 ---p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6f28000-b6f2a000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 22:31:18.660  7088  7088 W art     : b6f2a000-b6f2b000 r-xp 00000000 00:00 0          [sigpage]
08-12 22:31:18.660  7088  7088 W art     : b6f2b000-b6f46000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 22:31:18.660  7088  7088 W art     : b6f46000-b6f47000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 22:31:18.660  7088  7088 W art     : b6f47000-b6f49000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 22:31:18.660  7088  7088 W art     : b6f49000-b6f4b000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : b6f4b000-b6f50000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 22:31:18.660  7088  7088 W art     : b6f50000-b6f51000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 22:31:18.660  7088  7088 W art     : b6f51000-b6f52000 rw-p 00000000 00:00 0 
08-12 22:31:18.660  7088  7088 W art     : bef5f000-bef80000 rw-p 00000000 00:00 0          [stack]
08-12 22:31:18.660  7088  7088 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 22:31:18.700  7088  7088 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 22:31:18.750  7088  7088 I Radio-JNI: register_android_hardware_Radio DONE
08-12 22:31:18.760  7088  7088 E AffinityControl: AffinityControl: registerfunction enter
08-12 22:31:18.770  7088  7088 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-12 22:31:18.790   775  2103 D PackageManager: START PACKAGE DELETE: observer{160763402}
08-12 22:31:18.790   775  2103 D PackageManager: pkg{<packageName>}
08-12 22:31:18.790   775  2103 D PackageManager: user{0}
08-12 22:31:18.790   775  2103 D PackageManager: caller{2000}
08-12 22:31:18.790   775  2103 D PackageManager: flags{2}
,08-12 22:31:18.790   775  2103 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-12 22:31:18.790   775  2103 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-12 22:31:18.790   775  2103 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-12 22:31:18.790   775   856 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-12 22:31:18.790   775  2103 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-12 22:31:18.790   775  2103 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-12 22:31:18.790   775   937 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-12 22:31:18.790   775   937 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-12 22:31:18.790   775   856 I ActivityManager: Killing 6525:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
08-12 22:31:18.790   775   937 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-12 22:31:18.790   775   937 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-12 22:31:18.790   775   937 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-12 22:31:18.790   775   937 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS,
08-12 22:31:18.790   775   937 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 22:31:18.790   775   937 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-12 22:31:18.790   775   937 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS,
,08-12 22:31:18.790   775   937 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest,
08-12 22:31:18.800   775   856 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 22:31:18.800   775   856 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-12 22:31:18.810   775   937 D AASAinstall: there is not AASApackages.xml file
,08-12 22:31:18.860   775  2273 D GraphicsStats: Buffer count: 4
,08-12 22:31:18.860   775  1217 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@47a367b)
,08-12 22:31:18.860   293  1506 D libEGL  : eglTerminate EGLDisplay = 0xb1e486fc
08-12 22:31:18.870   775  1331 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 22:31:18.870   775  1331 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 22:31:18.870   775  2273 I WindowState: WIN DEATH: Window{60d330c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:31:18.870   293  1299 I SurfaceFlinger: id=15 Removed NainActivit (4/10)
,08-12 22:31:18.870   775  1331 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 22:31:18.870   293   351 I SurfaceFlinger: id=15 Removed NainActivit (-2/10)
08-12 22:31:18.870   293   359 I SurfaceFlinger: id=15 Removed NainActivit (-2/10)
,08-12 22:31:18.870   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef793a4
,08-12 22:31:19.110   775   937 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-12 22:31:19.200   775   937 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 22:31:19.200   775   856 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 22:31:19.210   775   856 E ActivityManager: Failure starting process com.test.thalitest
08-12 22:31:19.210   775   856 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5273)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5190)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5028)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2338)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2215)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:6684)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7381)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9142)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8765)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8920)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
08-12 22:31:19.210   775   856 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:19.210   775   856 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-12 22:31:19.210   775   856 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:31:19.210   775   856 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 22:31:19.210   775   856 I ActivityManager:   Force finishing activity ActivityRecord{57b74d u0 com.test.thalitest/.MainActivity t167}
,08-12 22:31:19.210   334   334 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-12 22:31:19.220   775   937 I art     : Starting a blocking GC Explicit
,08-12 22:31:19.330   775   937 I art     : Explicit concurrent mark sweep GC freed 112869(7MB) AllocSpace objects, 114(2MB) LOS objects, 27% free, 41MB/57MB, paused 1.342ms total 107.446ms
,08-12 22:31:19.350   775   937 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 22:31:19.350   775   937 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-12 22:31:19.350   775   937 D AASAinstall: there is not AASApackages.xml file
08-12 22:31:19.350   775   937 D PackageManager: result of delete: 1{160763402}
,08-12 22:31:19.360  7088  7088 I art     : System.exit called, status: 0
08-12 22:31:19.360  7088  7088 I AndroidRuntime: VM exiting with result code 0.
,08-12 22:31:19.370   775   937 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-12 22:31:19.370   775   937 D PackageManager: userId{-1}
08-12 22:31:19.370   775   937 D PackageManager: andCode{true}
,08-12 22:31:19.380   775   937 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-12 22:31:19.390  6197  7114 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-12 22:31:19.390  6197  7114 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-12 22:31:19.390  6197  7114 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-12 22:31:19.460   775   856 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 22:31:19.460   775   856 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 22:31:19.460   775   856 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 22:31:19.470   775   775 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.470   775   775 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.470   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.470   775   849 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.480  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,08-12 22:31:19.480  1381  1381 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
08-12 22:31:19.480   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.480   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.480   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.480   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.480   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.480   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.480   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.480   775   907 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.490   775   907 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.490   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.490   775  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 22:31:19.490   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.490   775   775 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.500   775   775 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.500   775   775 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.500   775   775 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.500   775   775 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.500   775   775 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.500   775   775 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.500  1957  1957 E SamsungIME: mOCRHelper is null
,08-12 22:31:19.510  1922  2399 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 22:31:19.510   775   775 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.510   775   775 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.510   775   775 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.510   775   775 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.510   775   775 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.510   775   775 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.520   775   775 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.520   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.520   775   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4d7461 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2d1810 4240:com.samsung.klmsagent/u0a18}
,08-12 22:31:19.530   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.530   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.530  1650  1650 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 22:31:19.530  4240  4240 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Fri Aug 12 22:31:19 GMT+02:00 2016
,08-12 22:31:19.530   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.530   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.530   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.530   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   849 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540  1640  1640 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2c08454 in tid 1640 (com.android.nfc)
08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.540   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.550  2185  2185 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:31:19.550   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.550   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.550   775  1364 E File    : fail readDirectory() errno=2
08-12 22:31:19.550   775  1364 E File    : fail readDirectory() errno=2
08-12 22:31:19.550   775  1364 E TaskPersister: File error accessing recents directory (too many files open?).
08-12 22:31:19.550  4240  4240 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
08-12 22:31:19.550   775  1364 E TaskPersister: File error accessing recents directory (too many files open?).
,08-12 22:31:19.550   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.550   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.550  2185  2185 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:31:19.550   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.550  3178  3193 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 22:31:19.550   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.550   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.550   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.550   775  2273 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4d7461 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{31d63db 775:system/1000}
,08-12 22:31:19.550  3178  3193 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 22:31:19.550   775   775 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.560  3178  3193 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 22:31:19.560   775   775 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.560  3178  3193 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-12 22:31:19.560   775  2268 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-12 22:31:19.560  4240  4240 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-12 22:31:19.560  4240  4240 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-12 22:31:19.560   775   849 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.560   775  1297 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-12 22:31:19.560  4240  4240 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2d822af in tid 4240 (msung.klmsagent)
,08-12 22:31:19.560  4240  4240 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 22:31:19.560  2185  2185 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:31:19.560   775   775 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.560   775   775 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.570   775   775 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.570   775   775 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.570   775   775 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.570   775   775 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.570   775   775 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-12 22:31:19.570   775   775 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-12 22:31:19.580   292   292 I ServiceManager: service 'nfc' died
08-12 22:31:19.580   292   292 I ServiceManager: service 'nfccontroller' died
08-12 22:31:19.580   292   292 I ServiceManager: service 'secontroller' died
,08-12 22:31:19.580   775  2103 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e30ad84 in tid 2103 (Binder_A)
08-12 22:31:19.580   775  2103 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 22:31:19.580   775  1411 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e30ad84 in tid 1411 (Binder_4)
08-12 22:31:19.580   775  1411 I libc    : Another thread contacted debuggerd first; not contacting debuggerd.
,08-12 22:31:19.580  2185  2185 E audit_log: File locking failed. error= Bad file descriptor
08-12 22:31:19.580   775  1321 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-12 22:31:19.580   775  1321 D NtpTrustedTime: currentTimeMillis() cache hit
08-12 22:31:19.580   775  1321 V NetworkStats: performPollLocked(flags=0x3)
,08-12 22:31:19.610   360   360 I Zygote  : Process 1640 exited due to signal (7)
,08-12 22:31:19.620   360   360 I Zygote  : Process 4240 exited due to signal (7)
,08-12 22:31:19.660  1381  1394 W Sensors : sensorservice died [0xb3f4e040]
,08-12 22:31:19.660   326   979 W AudioFlinger: power manager service died !!!
08-12 22:31:19.660   326   979 W AudioFlinger: power manager service died !!!
,08-12 22:31:19.660  1922  1933 W Sensors : sensorservice died [0xb3f5aac0]
,08-12 22:31:19.660  1940  1953 W Sensors : sensorservice died [0xada34c40]
,08-12 22:31:19.660   293   351 I SurfaceFlinger: id=2 Removed GocusedStac (4/9)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=9 Removed EimLayer(Di (3/6)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=10 Removed EimLayer(An (0/5)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=5 Removed TtatusBar (3/4)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=6 Removed JmageWallpa (0/3)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/3)
,08-12 22:31:19.660   293   351 I SurfaceFlinger: id=13 Removed DolorFade (2/2)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=13 Removed DolorFade (-2/2)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=9 Removed EimLayer(Di (-2/2)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=10 Removed EimLayer(An (-2/2)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=16 Removed VSBConnecti (1/1)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=17 Removed VSBConnecti (0/0)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/0)
08-12 22:31:19.660   293   351 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/0)
,08-12 22:31:19.670   330   330 E installd: eof
08-12 22:31:19.670   330   330 E installd: failed to read size
08-12 22:31:19.670   330   330 I installd: closing connection
,08-12 22:31:19.670  1663  1676 W Sensors : sensorservice died [0xada2a380]
08-12 22:31:19.670  1650  2416 E WifiManager: Channel connection lost
,08-12 22:31:19.670  2178  2178 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ed67894 in tid 2178 (droid.bluetooth)
08-12 22:31:19.670  1792  1921 E WifiManager: Channel connection lost
,08-12 22:31:19.670  1922  2397 E WifiManager: Channel connection lost
08-12 22:31:19.670  2178  2178 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 22:31:19.670   292   292 I ServiceManager: service 'notification' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'location' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'country_detector' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'sec_location' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'search' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'execute' died
08-12 22:31:19.670  2185  2185 E audit_log: File locking failed. error= Bad file descriptor
08-12 22:31:19.670   292   292 I ServiceManager: service 'dropbox' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'wallpaper' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'audio' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'DockObserver' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'midi' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'usb' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'serial' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'kiesusb' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'jobscheduler' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'backup' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'appwidget' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'voiceinteraction' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'diskstats' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'mDNIe' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'AAS' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'MSCS' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'spengestureservice' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'quickconnect' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'samplingprofiler' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'commontime_management' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'dreams' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'graphicsstats' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'print' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'restrictions' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'media_session' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'media_router' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'trust' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'fingerprint' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'launcherapps' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'voip' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'media_projection' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'lpnet' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'imms' died
08-12 22:31:19.670  1650  1650 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-12 22:31:19.670   292   292 I ServiceManager: service 'sec_analytics' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'user' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'procstats' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'meminfo' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'gfxinfo' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'dbinfo' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'cpuinfo' died
08-12 2,2:31:19.670   292   292 I ServiceManager: service 'permission' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'processinfo' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'sensorservice' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'battery' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'usagestats' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'webviewupdate' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'scheduling_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'telephony.registry' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'persona' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'context_aware' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'scontext' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'barbeam' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'multiwindow_facade' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'window' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'input' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'bluetooth_manager' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'rcp' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'input_method' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'accessibility' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'cover' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'mount' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'lock_settings' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'deviceidle' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'device_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'harmony_eas_service' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'sdp' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'sdp_log' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'dlp' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'log_manager_service' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'telecom' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'application_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'wifi_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'remoteinjection' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'edm_proxy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'mum_container_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'otp_service' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
,08-12 22:31:19.670   292   292 I ServiceManager: service 'enterprise_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'statusbar' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'clipboard' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'persona_policy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'edmnativehelper' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'clipboardEx' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'network_management' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'textservices' died
,08-12 22:31:19.670   292   292 I ServiceManager: service 'network_score' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'netstats' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'netpolicy' died
08-12 22:31:19.680  2185  2185 E audit_log: File locking failed. error= Bad file descriptor
08-12 22:31:19.670   292   292 I ServiceManager: service 'wifip2p' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'wifi' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'wifihs20' died
,08-12 22:31:19.670   292   292 I ServiceManager: service 'wifiscanner' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'rttmanager' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'ethernet' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'connectivity' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'sb_service' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'servicediscovery' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'updatelock' died
,08-12 22:31:19.670   292   292 I ServiceManager: service 'SEAMService' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'media.camera.proxy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'account' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'content' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'DirEncryptService' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'LSManager' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'ReactiveService' died
,08-12 22:31:19.670   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'EngineeringModeService' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'SatsService' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'sedenial' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'vibrator' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'tw_toolbox' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'tima' died
,08-12 22:31:19.670   292   292 I ServiceManager: service 'iccc' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'cepproxyks' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'emailksproxy' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'consumer_ir' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'alarm' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'activity' died
,08-12 22:31:19.670   292   292 I ServiceManager: service 'package' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'batterystats' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'appops' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'power' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'display' died
08-12 22:31:19.670   292   292 I ServiceManager: service 'uimode' died
08-12 22:31:19.670  2237  2259 W Sensors : sensorservice died [0xad87cc00]
,08-12 22:31:19.670  1381  1625 E WifiManager: Channel connection lost
08-12 22:31:19.670  3178  3193 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e650b55 in tid 3193 (AccountChangeLi)
08-12 22:31:19.670  3178  3193 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 22:31:19.680   293   359 D libEGL  : eglTerminate EGLDisplay = 0xb667f6fc
,08-12 22:31:19.680   293  1299 I SurfaceFlinger: restart the boot-animation @ binderDied
,08-12 22:31:19.680   293   359 D libEGL  : eglTerminate EGLDisplay = 0xb667f6fc
,08-12 22:31:19.690  5681  5751 E WifiManager: Channel connection lost
,08-12 22:31:19.690   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
08-12 22:31:19.690   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-12 22:31:19.700  2224  2224 D BluetoothA2dp: Proxy object disconnected
,08-12 22:31:19.700  5182  5182 D BluetoothMap: Proxy object disconnected
08-12 22:31:19.700  5182  5182 D MapProfile: Bluetooth service disconnected
,08-12 22:31:19.700  5182  5182 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9882bd in tid 5182 (ndroid.settings)
,08-12 22:31:19.700  5182  5182 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 22:31:19.700  2185  2185 E audit_log: File locking failed. error= Bad file descriptor
,08-12 22:31:19.730   360   360 I Zygote  : Process 3178 exited due to signal (7)
,08-12 22:31:19.750   360   360 I Zygote  : Process 5182 exited due to signal (7)
08-12 22:31:19.750   360  6983 I Zygote  : Process 2178 exited due to signal (7)
,08-12 22:31:19.810   291   291 I lowmemorykiller: ActivityManager disconnected
08-12 22:31:19.810   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-12 22:31:19.930   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
08-12 22:31:19.930   293   553 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-12 22:31:20.180   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-12 22:31:20.180   293   553 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 22:31:20.180   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef793a4
,08-12 22:31:20.180   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef7938c
,08-12 22:31:20.190   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef7938c
,08-12 22:31:20.190   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef7938c
,08-12 22:31:20.190   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef793a4
08-12 22:31:20.190   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef793a4
,08-12 22:31:20.190   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef7938c
08-12 22:31:20.190   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef7938c
,08-12 22:31:20.190   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef7938c

```
