#### Test 72145431744cc2c_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
07-12 11:36:55.577   777  3288 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
--------- beginning of main
07-12 11:36:55.697   777   939 D PackageManager: [MSG] MCS_UNBIND
07-12 11:36:55.697  1462  1462 D Recents : onTaskStackChanged
07-12 11:36:55.717   777   790 I ActivityManager: Killing 5010:com.android.exchange/u0a163 (adj 15): DHA:empty #37
07-12 11:36:55.737   777  1421 D ActivityManager: isAutoRunBlockedApp:: com.android.exchange, Auto Run ON
,07-12 11:36:56.597  5138  5138 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
07-12 11:36:56.607  5138  5138 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
07-12 11:36:56.607  5138  5138 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
07-12 11:36:56.607  5138  5138 I art     : System.exit called, status: 0
07-12 11:36:56.607  5138  5138 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-12 11:36:56.657   777  2235 I ActivityManager: Process com.samsung.aasaservice (pid 5138)(adj 0) has died(66,778)
07-12 11:36:56.657   777  2235 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
07-12 11:36:56.657   777  2235 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
07-12 11:36:56.657   777  2235 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
07-12 11:36:56.657  5108  5108 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
07-12 11:36:56.677  5810  5810 E Zygote  : v2
07-12 11:36:56.677  5810  5810 I libpersona: KNOX_SDCARD checking this for 10014
07-12 11:36:56.677  5810  5810 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:56.677  5810  5810 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:56.677  5810  5810 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:56.677  5810  5810 E Zygote  : accessInfo : 0
07-12 11:36:56.677  5810  5810 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
07-12 11:36:56.677   777   861 I ActivityManager: Start proc 5810:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
07-12 11:36:56.677   777  1327 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-12 11:36:56.707  5810  5810 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:56.707  5810  5810 D ActivityThread: Added TimaKeyStore provider
07-12 11:36:56.707   777  2231 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d3ac8f 5810:com.google.android.partnersetup/u0a14}
07-12 11:36:56.707   777  1327 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
07-12 11:36:56.717  5810  5810 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
07-12 11:36:56.727  5810  5810 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
07-12 11:36:56.747   777  1300 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d3ac8f 5810:com.google.android.partnersetup/u0a14}
07-12 11:36:56.767  5825  5825 E Zygote  : v2
07-12 11:36:56.767  5825  5825 I libpersona: KNOX_SDCARD checking this for 10015
07-12 11:36:56.767  5825  5825 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:56.767  5825  5825 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:56.767  5825  5825 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:56.767  5825  5825 E Zygote  : accessInfo : 0
07-12 11:36:56.767  5825  5825 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
07-12 11:36:56.767   777  2231 I ActivityManager: Start proc 5825:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
07-12 11:36:56.787  5825  5825 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:56.787  5825  5825 D ActivityThread: Added TimaKeyStore provider
07-12 11:36:56.797   777   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b392cfa 5825:com.samsung.groupcast/u0a15}
07-12 11:36:56.807  5825  5825 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
07-12 11:36:56.817   777  1678 I ActivityManager: Killing 4762:com.samsung.android.sm/1000 (adj 15): DHA:empty #37
07-12 11:36:56.827  5825  5825 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
07-12 11:36:56.837   777  1588 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
07-12 11:36:56.837   777  1240 V AlarmManager: Expired Alarm result :4
07-12 11:36:56.847  5422  5470 I Finsky  : [794] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
07-12 11:36:56.857  5825  5825 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
07-12 11:36:56.867  5825  5825 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
07-12 11:36:56.867  5825  5825 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-12 11:36:56.867  5825  5825 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
07-12 11:36:56.867  5825  5825 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
07-12 11:36:56.867  5825  5825 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
07-12 11:36:56.867  5825  5825 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
07-12 11:36:56.867  5825  5825 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
07-12 11:36:56.867  5825  5825 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
07-12 11:36:56.867  5825  5825 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:56.867  5825  5825 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-12 11:36:56.867  5825  5825 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-12 11:36:56.867  5825  5825 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:56.867  5825  5825 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-12 11:36:56.867  5825  5825 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-12 11:36:56.877   777  1588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74eac8c 1852:com.sec.android.app.shealth:remote/u0a34}
07-12 11:36:56.897  5837  5837 E Zygote  : v2
07-12 11:36:56.897  5837  5837 I libpersona: KNOX_SDCARD checking this for 10041
07-12 11:36:56.897  5837  5837 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:56.897  5837  5837 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:56.897  5837  5837 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:56.897  5837  5837 E Zygote  : accessInfo : 0
07-12 11:36:56.897  5837  5837 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
07-12 11:36:56.897   777  1719 I ActivityManager: Start proc 5837:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
07-12 11:36:56.907   777  1718 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:36:56.907   777  1718 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4306, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-12 11:36:56.907   777  1718 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-12 11:36:56.907   777  1718 D BatteryService: stay LED for charging
07-12 11:36:56.907   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:36:56.907   777   777 I MotionRecognitionService: Plugged
07-12 11:36:56.907   777   777 D MotionRecognitionService:   cableConnection= 1
07-12 11:36:56.907   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:36:56.907   777   777 D MotionRecognitionService: skip setTransmitPower. 
07-12 11:36:56.907  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:36:56.907  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:36:56.907  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
07-12 11:36:56.927  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-12 11:36:56.927  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-12 11:36:56.927  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-12 11:36:56.937  5837  5837 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:56.937  5837  5837 D ActivityThread: Added TimaKeyStore provider
07-12 11:36:56.947   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98a8ca1 5837:com.samsung.android.sdk.samsunglink/u0a41}
07-12 11:36:56.947  5837  5837 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
07-12 11:36:57.037  5837  5837 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-12 11:36:57.037  5837  5837 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
07-12 11:36:57.107  5837  5837 I SL_DEBUG: isLoggable:: isProductShip = 1
07-12 11:36:57.107  5837  5837 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
07-12 11:36:57.117   777  2235 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
07-12 11:36:57.117   777  1718 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
07-12 11:36:57.117   777  2231 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
07-12 11:36:57.127   777  2212 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
07-12 11:36:57.127   777  1588 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
07-12 11:36:57.127   777  1589 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
07-12 11:36:57.127   777   790 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
07-12 11:36:57.127   777  2212 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
07-12 11:36:57.137   777  2235 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
07-12 11:36:57.137   777  2231 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
07-12 11:36:57.187  5422  5470 I Finsky  : [794] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
07-12 11:36:57.187  5422  5422 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
07-12 11:36:57.187   777   789 I ActivityManager: Killing 5122:com.sec.android.soagent/1000 (adj 15): DHA:empty #37
07-12 11:36:57.207   777  2235 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.soagent, Auto Run ON
07-12 11:36:57.287  5837  5837 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
07-12 11:36:57.287  5837  5837 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
07-12 11:36:57.287  5837  5837 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
07-12 11:36:57.287  5837  5837 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
07-12 11:36:57.287  5837  5837 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
07-12 11:36:57.287  5837  5837 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
07-12 11:36:57.287  5837  5837 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
07-12 11:36:57.287  5837  5837 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
07-12 11:36:57.287  5837  5837 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
07-12 11:36:57.287  5837  5837 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
07-12 11:36:57.287  5837  5837 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:57.287  5837  5837 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-12 11:36:57.287  5837  5837 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-12 11:36:57.287  5837  5837 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:57.287  5837  5837 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-12 11:36:57.287  5837  5837 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-12 11:36:57.287   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee10521 1734:android.process.acore/u0a19}
07-12 11:36:57.297   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d31ee3f 4881:com.sec.android.gallery3d/u0a47}
07-12 11:36:57.307  4881  4881 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
07-12 11:36:57.307   777  1727 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:36:57.317  5860  5860 E Zygote  : v2
07-12 11:36:57.317   777  2235 I ActivityManager: Start proc 5860:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
07-12 11:36:57.317  5860  5860 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:57.317  5860  5860 I libpersona: KNOX_SDCARD checking this for 10050
07-12 11:36:57.317  5860  5860 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:57.317  5860  5860 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:57.327  5860  5860 E Zygote  : accessInfo : 0
07-12 11:36:57.327  5860  5860 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
07-12 11:36:57.347  5860  5860 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:57.347  5860  5860 D ActivityThread: Added TimaKeyStore provider
07-12 11:36:57.357   777  1719 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{49ee011 5860:com.sec.android.app.myfiles/u0a50}
07-12 11:36:57.357  5860  5860 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
07-12 11:36:57.367   777  2231 I ActivityManager: Killing 5108:com.policydm/1000 (adj 15): DHA:empty #37
07-12 11:36:57.387   777  1678 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
07-12 11:36:57.387  5860  5860 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
07-12 11:36:57.427  5860  5860 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
07-12 11:36:57.447   777  1588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
07-12 11:36:57.447   323   323 E installd: system dir 0 : /system/app/
07-12 11:36:57.447   323   323 E installd: system dir 1 : /system/priv-app/
07-12 11:36:57.447   323   323 E installd: system dir 2 : /vendor/app/
07-12 11:36:57.447   323   323 E installd: system dir 3 : /oem/app/
07-12 11:36:57.457   777   939 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
07-12 11:36:57.467   777  2231 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
07-12 11:36:57.467  2151  2151 E audit   : type=1400 msg=audit(1468316217.467:278): avc:  denied  { execmod } for  pid=5805 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-12 11:36:57.477  2151  2151 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:57.477  2151  2151 E audit   : type=1300 msg=audit(1468316217.467:278): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4025000 a1=51000 a2=5 a3=4 items=0 ppid=3446 ppcomm=adbd pid=5805 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-12 11:36:57.477  2151  2151 E audit   : type=1327 msg=audit(1468316217.467:278): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-12 11:36:57.477  2151  2151 E audit   : type=1320 msg=audit(1468316217.467:278): 
07-12 11:36:57.487  5875  5875 E Zygote  : v2
07-12 11:36:57.487  5875  5875 I libpersona: KNOX_SDCARD checking this for 10169
07-12 11:36:57.487  5875  5875 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:57.487  5875  5875 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:57.487  5875  5875 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:57.497  5875  5875 E Zygote  : accessInfo : 0
07-12 11:36:57.497  5875  5875 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
07-12 11:36:57.497   777  1421 I ActivityManager: Start proc 5875:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
07-12 11:36:57.517  5875  5875 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:57.517  5875  5875 D ActivityThread: Added TimaKeyStore provider
07-12 11:36:57.527   777  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4806c4d 5875:com.samsung.android.provider.shootingmodeprovider/u0a169}
07-12 11:36:57.527  2151  2151 E audit   : type=1400 msg=audit(1468316217.527:279): avc:  denied  { execmod } for  pid=5805 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-12 11:36:57.527  2151  2151 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:57.527  2151  2151 E audit   : type=1300 msg=audit(1468316217.527:279): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe5000 a1=51000 a2=5 a3=4 items=0 ppid=3446 ppcomm=adbd pid=5805 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-12 11:36:57.527  2151  2151 E audit   : type=1327 msg=audit(1468316217.527:279): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-12 11:36:57.527  2151  2151 E audit   : type=1320 msg=audit(1468316217.527:279): 
07-12 11:36:57.527  5875  5875 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
07-12 11:36:57.537  5875  5875 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
07-12 11:36:57.557   777  2231 I ActivityManager: Killing 5156:com.sec.android.app.sns3/u0a35 (adj 15): DHA:empty #37
07-12 11:36:57.567   777  2231 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{af435a3 1706:com.android.phone/1001}
07-12 11:36:57.567   777  2231 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b6f6db 1810:com.google.android.googlequicksearchbox:search/u0a61}
07-12 11:36:57.577  2151  2151 E audit   : type=1400 msg=audit(1468316217.577:280): avc:  denied  { execmod } for  pid=5805 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-12 11:36:57.577  2151  2151 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:57.577  2151  2151 E audit   : type=1300 msg=audit(1468316217.577:280): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe5000 a1=51000 a2=5 a3=4 items=0 ppid=3446 ppcomm=adbd pid=5805 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-12 11:36:57.577  2151  2151 E audit   : type=1327 msg=audit(1468316217.577:280): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-12 11:36:57.577  5805  5805 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 11:36:57.577  2151  2151 E audit   : type=1320 msg=audit(1468316217.577:280): 
07-12 11:36:57.577   777  1300 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sns3, Auto Run ON
07-12 11:36:57.577  5805  5805 D AndroidRuntime: CheckJNI is OFF
07-12 11:36:57.577  5805  5805 D AndroidRuntime: readGMSProperty: start
07-12 11:36:57.577  5805  5805 D AndroidRuntime: readGMSProperty: already setted!!
07-12 11:36:57.577  5805  5805 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-12 11:36:57.577  5805  5805 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-12 11:36:57.577  5805  5805 D AndroidRuntime: readGMSProperty: end
07-12 11:36:57.577  5805  5805 D AndroidRuntime: addProductProperty: start
07-12 11:36:57.587  5805  5805 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-12 11:36:57.587  5805  5805 W art     : aee4c000-b1d72000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-12 11:36:57.587  5805  5805 W art     : b1d72000-b3fe1000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-12 11:36:57.587  5805  5805 W art     : b3fe1000-b3fe2000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-12 11:36:57.587  5805  5805 W art     : b3fe2000-b3fe3000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-12 11:36:57.587  5805  5805 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-12 11:36:57.587  5805  5805 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-12 11:36:57.587  5805  5805 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-12 11:36:57.587  5805  5805 W art     : b488e000-b48b7000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-12 11:36:57.587  5805  5805 W art     : b48b7000-b48ba000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-12 11:36:57.587  5805  5805 W art     : b48ba000-b48bb000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-12 11:36:57.587  5805  5805 W art     : b48bb000-b48bc000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-12 11:36:57.587  5805  5805 W art     : b48bc000-b48bd000 r--p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b48bd000-b48dd000 r--s 00000000 00:0b 6706       /dev/__properties__
07-12 11:36:57.587  5805  5805 W art     : b48dd000-b52ee000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-12 11:36:57.587  5805  5805 W art     : b52ee000-b52ef000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b52ef000-b5338000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-12 11:36:57.587  5805  5805 W art     : b5338000-b5339000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-12 11:36:57.587  5805  5805 W art     : b5339000-b5341000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5341000-b5342000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b5342000-b5377000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-12 11:36:57.587  5805  5805 W art     : b5377000-b5378000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5378000-b5379000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-12 11:36:57.587  5805  5805 W art     : b5379000-b537a000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-12 11:36:57.587  5805  5805 W art     : b537a000-b53d2000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-12 11:36:57.587  5805  5805 W art     : b53d2000-b53d3000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b53d3000-b53d4000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-12 11:36:57.587  5805  5805 W art     : b53d4000-b53d5000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-12 11:36:57.587  5805  5805 W art     : b53d6000-b53dc000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-12 11:36:57.587  5805  5805 W art     : b53dc000-b53dd000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-12 11:36:57.587  5805  5805 W art     : b53dd000-b53de000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-12 11:36:57.587  5805  5805 W art     : b53de000-b53e0000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b53e1000-b53eb000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-12 11:36:57.587  5805  5805 W art     : b53eb000-b53ee000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-12 11:36:57.587  5805  5805 W art     : b53ee000-b53ef000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-12 11:36:57.587  5805  5805 W art     : b53f0000-b5407000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-12 11:36:57.587  5805  5805 W art     : b5407000-b5408000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5408000-b5409000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-12 11:36:57.587  5805  5805 W art     : b5409000-b540a000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-12 11:36:57.587  5805  5805 W art     : b540b000-b5415000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-12 11:36:57.587  5805  5805 W art     : b5415000-b5416000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-12 11:36:57.587  5805  5805 W art     : b5416000-b5417000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-12 11:36:57.587  5805  5805 W art     : b5417000-b541b000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-12 11:36:57.587  5805  5805 W art     : b541b000-b541c000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-12 11:36:57.587  5805  5805 W art     : b541c000-b541d000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-12 11:36:57.587  5805  5805 W art     : b541d000-b5433000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-12 11:36:57.587  5805  5805 W art     : b5433000-b5434000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-12 11:36:57.587  5805  5805 W art     : b5434000-b5435000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-12 11:36:57.587  5805  5805 W art     : b5435000-b5442000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-12 11:36:57.587  5805  5805 W art     : b5442000-b5443000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-12 11:36:57.587  5805  5805 W art     : b5443000-b5444000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-12 11:36:57.587  5805  5805 W art     : b5444000-b54a4000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-12 11:36:57.587  5805  5805 W art     : b54a4000-b54a7000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-12 11:36:57.587  5805  5805 W art     : b54a7000-b54ab000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b54ab000-b550c000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-12 11:36:57.587  5805  5805 W art     : b550c000-b550d000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-12 11:36:57.587  5805  5805 W art     : b550d000-b555c000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-12 11:36:57.587  5805  5805 W art     : b555c000-b555e000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-12 11:36:57.587  5805  5805 W art     : b555e000-b555f000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-12 11:36:57.587  5805  5805 W art     : b555f000-b5560000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5560000-b5567000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-12 11:36:57.587  5805  5805 W art     : b5567000-b5568000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-12 11:36:57.587  5805  5805 W art     : b5568000-b5569000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
07-12 11:36:57.587  5805  5805 W art     : avc_common.so
07-12 11:36:57.587  5805  5805 W art     : b556a000-b556d000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-12 11:36:57.587  5805  5805 W art     : b556d000-b556e000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-12 11:36:57.587  5805  5805 W art     : b556e000-b556f000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
07-12 11:36:57.587  5805  5805 W art     : enc_common.so
07-12 11:36:57.587  5805  5805 W art     : b5570000-b5574000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-12 11:36:57.587  5805  5805 W art     : b5574000-b5575000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5575000-b5576000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-12 11:36:57.587  5805  5805 W art     : b5576000-b5577000 rw-p 00005000 b3:17 2510       /syste
07-12 11:36:57.587  5805  5805 W art     : m/lib/libpowermanager.so
07-12 11:36:57.587  5805  5805 W art     : b5578000-b5595000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-12 11:36:57.587  5805  5805 W art     : b5595000-b5596000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-12 11:36:57.587  5805  5805 W art     : b5596000-b5597000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-12 11:36:57.587  5805  5805 W art     : b5598000-b559d000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-12 11:36:57.587  5805  5805 W art     : b559d000-b559e000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-12 11:36:57.587  5805  5805 W art     : b559e000-b559f000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-12 11:36:57.587  5805  5805 W art     : b55a0000-b55d1000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-12 11:36:57.587  5805  5805 W art     : b55d1000-b55d4000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-12 11:36:57.587  5805  5805 W art     : b55d4000-b55d5000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-12 11:36:57.587  5805  5805 W art     : b55d6000-b5611000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-12 11:36:57.587  5805  5805 W art     : b5611000-b5612000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-12 11:36:57.587  5805  5805 W art     : b5612000-b5613000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-12 11:36:57.587  5805  5805 W art     : b5614000-b561b000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-12 11:36:57.587  5805  5805 W art     : b561b000-b561c000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b561c000-b561d000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-12 11:36:57.587  5805  5805 W art     : b561d000-b561e000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-12 11:36:57.587  5805  5805 W art     : b561e000-b561f000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b561f000-b5636000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-12 11:36:57.587  5805  5805 W art     : b5636000-b5637000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5637000-b563a000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-12 11:36:57.587  5805  5805 W art     : b563a000-b563b000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-12 11:36:57.587  5805  5805 W art     : b563b000-b565a000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-12 11:36:57.587  5805  5805 W art     : b565a000-b565b000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-12 11:36:57.587  5805  5805 W art     : b565b000-b565c000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-12 11:36:57.587  5805  5805 W art     : b565c000-b569a000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-12 11:36:57.587  5805  5805 W art     : b569a000-b569b000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b569b000-b569d000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-12 11:36:57.587  5805  5805 W art     : b569d000-b569e000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-12 11:36:57.587  5805  5805 W art     : b569f000-b56a6000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-12 11:36:57.587  5805  5805 W art     : b56a6000-b56a7000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-12 11:36:57.587  5805  5805 W art     : b56a7000-b56a8000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-12 11:36:57.587  5805  5805 W art     : b56a9000-b56ac000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-12 11:36:57.587  5805  5805 W art     : b56ac000-b56ad000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-12 11:36:57.587  5805  5805 W art     : b56ad000-b56ae000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-12 11:36:57.587  5805  5805 W art     : b56ae000-b56b4000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-12 11:36:57.587  5805  5805 W art     : b56b4000-b56b5000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b56b5000-b56b6000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-12 11:36:57.587  5805  5805 W art     : b56b6000-b56b7000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-12 11:36:57.587  5805  5805 W art     : b56b7000-b56c0000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-12 11:36:57.587  5805  5805 W art     : b56c0000-b56c1000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-12 11:36:57.587  5805  5805 W art     : b56c1000-b56c2000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-12 11:36:57.587  5805  5805 W art     : b56c2000-b5753000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-12 11:36:57.587  5805  5805 W art     : b5753000-b5754000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5754000-b575f000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-12 11:36:57.587  5805  5805 W art     : b575f000-b5760000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-12 11:36:57.587  5805  5805 W art     : b5761000-b5773000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-12 11:36:57.587  5805  5805 W art     : b5773000-b5774000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-12 11:36:57.587  5805  5805 W art     : b5774000-b5775000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-12 11:36:57.587  5805  5805 W art     : b5776000-b577b000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-12 11:36:57.587  5805  5805 W art     : b577b000-b577c000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-12 11:36:57.587  5805  5805 W art     : b577c000-b577d000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-12 11:36:57.587  5805  5805 W art     : b577e000-b57eb000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-12 11:36:57.587  5805  5805 W art     : b57eb000-b57ec000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b57ec000-b57ee000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-12 11:36:57.587  5805  5805 W art     : b57ee000-b57ef000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-12 11:36:57.587  5805  5805 W art     : b57ef000-b57f0000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b57f0000-b57f7000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-12 11:36:57.587  5805  5805 W art     : b57f7000-b57f8000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-12 11:36:57.587  5805  5805 W art     : b57f8000-b57f9000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-12 11:36:57.587  5805  5805 W art     : b57fa000-b587a000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-12 11:36:57.587  5805  5805 W art     : b587a000-b587b000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b587b000-b587c000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-12 11:36:57.587  5805  5805 W art     : b587c000-b587d000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-12 11:36:57.587  5805  5805 W art     : b587d000-b5894000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5894000-b58cb000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-12 11:36:57.587  5805  5805 W art     : ib/libqc-opt.so
07-12 11:36:57.587  5805  5805 W art     : b58cb000-b58cc000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-12 11:36:57.587  5805  5805 W art     : b58cc000-b58cd000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-12 11:36:57.587  5805  5805 W art     : b58cd000-b58e9000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-12 11:36:57.587  5805  5805 W art     : b58e9000-b58ea000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-12 11:36:57.587  5805  5805 W art     : b58ea000-b58eb000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-12 11:36:57.587  5805  5805 W art     : b58ec000-b594d000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-12 11:36:57.587  5805  5805 W art     : b594d000-b594f000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-12 11:36:57.587  5805  5805 W art     : b594f000-b5950000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-12 11:36:57.587  5805  5805 W art     : b5951000-b5978000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-12 11:36:57.587  5805  5805 W art     : b5978000-b5979000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5979000-b597a000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-12 11:36:57.587  5805  5805 W art     : b597a000-b597b000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-12 11:36:57.587  5805  5805 W art     : b597c000-b5984000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-12 11:36:57.587  5805  5805 W art     : b5984000-b5986000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-12 11:36:57.587  5805  5805 W art     : b5986000-b5987000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-12 11:36:57.587  5805  5805 W art     : b5988000-b598b000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-12 11:36:57.587  5805  5805 W art     : b598b000-b598c000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-12 11:36:57.587  5805  5805 W art     : b598c000-b598d000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-12 11:36:57.587  5805  5805 W art     : b598d000-b5991000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-12 11:36:57.587  5805  5805 W art     : b5991000-b5992000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5992000-b5993000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-12 11:36:57.587  5805  5805 W art     : b5993000-b5994000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-12 11:36:57.587  5805  5805 W art     : b5994000-b59a4000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-12 11:36:57.597   777  1420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b6f6db 1810:com.google.android.googlequicksearchbox:search/u0a61}
07-12 11:36:57.587  5805  5805 W art     : b59a4000-b59a5000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-12 11:36:57.587  5805  5805 W art     : b59a5000-b59a6000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-12 11:36:57.587  5805  5805 W art     : b59a6000-b59ec000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b59ec000-b59f5000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-12 11:36:57.587  5805  5805 W art     : b59f5000-b59f6000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-12 11:36:57.587  5805  5805 W art     : b59f6000-b59f7000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-12 11:36:57.587  5805  5805 W art     : b59f8000-b59fd000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-12 11:36:57.587  5805  5805 W art     : b59fd000-b59fe000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-12 11:36:57.587  5805  5805 W art     : b59fe000-b59ff000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-12 11:36:57.587  5805  5805 W art     : b59ff000-b5a02000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-12 11:36:57.587  5805  5805 W art     : b5a02000-b5a03000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5a03000-b5a04000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-12 11:36:57.587  5805  5805 W art     : b5a04000-b5a05000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-12 11:36:57.587  5805  5805 W art     : b5a06000-b5a1e000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-12 11:36:57.587  5805  5805 W art     : b5a1e000-b5a1f000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5a1f000-b5a20000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-12 11:36:57.587  5805  5805 W art     : b5a20000-b5a21000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-12 11:36:57.587  5805  5805 W art     : b5a22000-b5bbc000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-12 11:36:57.587  5805  5805 W art     : b5bbc000-b5bbd000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5bbd000-b5bca000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-12 11:36:57.587  5805  5805 W art     : b5bca000-b5bcb000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-12 11:36:57.587  5805  5805 W art     : b5bcb000-b5bcf000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-12 11:36:57.587  5805  5805 W art     : b5bcf000-b5bd0000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5bd0000-b5bd1000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-12 11:36:57.587  5805  5805 W art     : b5bd1000-b5bd2000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-12 11:36:57.587  5805  5805 W art     : b5bd2000-b5be5000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-12 11:36:57.587  5805  5805 W art     : b5be5000-b5be6000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-12 11:36:57.587  5805  5805 W art     : b5be6000-b5be7000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-12 11:36:57.587  5805  5805 W art     : b5be7000-b5be8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 11:36:57.587  5805  5805 W art     : b5be8000-b5c33000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-12 11:36:57.587  5805  5805 W art     : b5c33000-b5c34000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-12 11:36:57.587  5805  5805 W art     : b5c34000-b5c35000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-12 11:36:57.587  5805  5805 W art     : b5c35000-b5c37000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5c38000-b5c49000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-12 11:36:57.587  5805  5805 W art     : b5c49000-b5c4a000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5c4a000-b5c4b000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-12 11:36:57.587  5805  5805 W art     : b5c4b000-b5c4c000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-12 11:36:57.587  5805  5805 W art     : b5c4d000-b5c57000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-12 11:36:57.587  5805  5805 W art     : b5c57000-b5c59000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-12 11:36:57.587  5805  5805 W art     : b5c59000-b5c5a000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-12 11:36:57.587  5805  5805 W art     : b5c5a000-b5c73000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-12 11:36:57.587  5805  5805 W art     : b5c73000-b5c74000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-12 11:36:57.587  5805  5805 W art     : b5c74000-b5c77000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-12 11:36:57.587  5805  5805 W art     : b5c77000-b5c7b000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5c7b000-b5cef000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-12 11:36:57.587  5805  5805 W art     : b5cef000-b5cf0000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5cf0000-b5cf3000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-12 11:36:57.587  5805  5805 W art     : b5cf3000-b5cf4000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-12 11:36:57.587  5805  5805 W art     : b5cf4000-b5cf5000 r--p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5cf5000-b5cf8000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-12 11:36:57.587  5805  5805 W art     : b5cf8000-b5cf9000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-12 11:36:57.587  5805  5805 W art     : b5cf9000-b5cfa000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-12 11:36:57.587  5805  5805 W art     : b5cfa000-b5cfb000 r--p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5cfb000-b5d00000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-12 11:36:57.587  5805  5805 W art     : b5d00000-b5d01000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-12 11:36:57.587  5805  5805 W art     : b5d01000-b5d02000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-12 11:36:57.587  5805  5805 W art     : b5d02000-b5d03000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b5d03000-b5d06000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-12 11:36:57.587  5805  5805 W art     : b5d06000-b5d07000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-12 11:36:57.587  5805  5805 W art     : b5d07000-b5d08000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-12 11:36:57.587  5805  5805 W art     : b5d08000-b5d09000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b5d09000-b5d0d000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-12 11:36:57.587  5805  5805 W art     : b5d0d000-b5d0e000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-12 11:36:57.587  5805  5805 W art     : b5d0e000-b5d0f000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-12 11:36:57.587  5805  5805 W art     : b5d0f000-b5d10000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 11:36:57.587  5805  5805 W art     : b5d10000-b5d14000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-12 11:36:57.587  5805  5805 W art     : b5d14000-b5d15000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-12 11:36:57.587  5805  5805 W art     : b5d15000-b5d16000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-12 11:36:57.587  5805  5805 W art     : b5d16000-b5d17000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b5d17000-b5d25000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-12 11:36:57.587  5805  5805 W art     : b5d25000-b5d26000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b5d26000-b5d27000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-12 11:36:57.587  5805  5805 W art     : b5d27000-b5d28000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-12 11:36:57.587  5805  5805 W art     : b5d28000-b5d32000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-12 11:36:57.587  5805  5805 W art     : b5d32000-b5d35000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-12 11:36:57.587  5805  5805 W art     : b5d35000-b5d36000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-12 11:36:57.587  5805  5805 W art     : b5d36000-b5d37000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b5d37000-b5d41000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-12 11:36:57.587  5805  5805 W art     : b5d41000-b5d44000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-12 11:36:57.587  5805  5805 W art     : b5d44000-b5d45000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-12 11:36:57.587  5805  5805 W art     : b5d45000-b5d49000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-12 11:36:57.587  5805  5805 W art     : b5d49000-b5d4a000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-12 11:36:57.587  5805  5805 W art     : b5d4a000-b5d4b000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-12 11:36:57.587  5805  5805 W art     : b5d4b000-b5d4c000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b5d4c000-b5d59000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-12 11:36:57.587  5805  5805 W art     : b5d59000-b5d5b000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-12 11:36:57.587  5805  5805 W art     : b5d5b000-b5d5c000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-12 11:36:57.587  5805  5805 W art     : b5d5c000-b616e000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-12 11:36:57.587  5805  5805 W art     : b616e000-b616f000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b616f000-b6178000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-12 11:36:57.587  5805  5805 W art     : b6178000-b617c000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-12 11:36:57.587  5805  5805 W art     : b617c000-b617d000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b617d000-b6184000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-12 11:36:57.587  5805  5805 W art     : b6184000-b6185000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-12 11:36:57.587  5805  5805 W art     : b6185000-b6186000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-12 11:36:57.587  5805  5805 W art     : b6186000-b6187000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b6187000-b61a2000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-12 11:36:57.587  5805  5805 W art     : b61a2000-b61a3000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-12 11:36:57.587  5805  5805 W art     : b61a3000-b61a4000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-12 11:36:57.587  5805  5805 W art     : b61a4000-b61a5000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b61a5000-b61f1000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-12 11:36:57.587  5805  5805 W art     : b61f1000-b61f2000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b61f2000-b61f3000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-12 11:36:57.587  5805  5805 W art     : b61f3000-b61f4000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-12 11:36:57.587  5805  5805 W art     : b61f4000-b61f5000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b61f5000-b61f9000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-12 11:36:57.587  5805  5805 W art     : b61f9000-b61fa000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b61fa000-b61fb000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-12 11:36:57.587  5805  5805 W art     : b61fb000-b61fc000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-12 11:36:57.587  5805  5805 W art     : b61fc000-b6234000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-12 11:36:57.587  5805  5805 W art     : b6234000-b6235000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-12 11:36:57.587  5805  5805 W art     : b6235000-b6236000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-12 11:36:57.587  5805  5805 W art     : b6236000-b6237000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b6237000-b62d5000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-12 11:36:57.587  5805  5805 W art     : b62d5000-b62d6000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b62d6000-b62f4000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-12 11:36:57.587  5805  5805 W art     : b62f4000-b62f5000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-12 11:36:57.587  5805  5805 W art     : b62f5000-b6468000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-12 11:36:57.587  5805  5805 W art     : b6468000-b6473000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-12 11:36:57.587  5805  5805 W art     : b6473000-b6474000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-12 11:36:57.587  5805  5805 W art     : b6474000-b658b000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-12 11:36:57.587  5805  5805 W art     : b658b000-b6596000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-12 11:36:57.587  5805  5805 W art     : b6596000-b6597000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-12 11:36:57.587  5805  5805 W art     : b6597000-b659b000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b659b000-b65bf000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-12 11:36:57.587  5805  5805 W art     : b65bf000-b65c1000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-12 11:36:57.587  5805  5805 W art     : b65c1000-b65c2000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-12 11:36:57.587  5805  5805 W art     : b65c2000-b6668000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-12 11:36:57.587  5805  5805 W art     : b6668000-b6675000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-12 11:36:57.587  5805  5805 W art     : b6675000-b6676000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-12 11:36:57.587  5805  5805 W art     : b6676000-b6677000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6677000-b66ca000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-12 11:36:57.587  5805  5805 W art     : b66ca000-b66cb000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b66cb000-b66cc000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-12 11:36:57.587  5805  5805 W art     : b66cc000-b66cd000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-12 11:36:57.587  5805  5805 W art     : b66cd000-b66d2000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b66d2000-b66e4000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-12 11:36:57.587  5805  5805 W art     : b66e4000-b66e5000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b66e5000-b66e6000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-12 11:36:57.587  5805  5805 W art     : b66e6000-b66e7000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-12 11:36:57.587  5805  5805 W art     : b66e7000-b66ee000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-12 11:36:57.587  5805  5805 W art     : b66ee000-b66ef000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-12 11:36:57.587  5805  5805 W art     : b66ef000-b66f0000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-12 11:36:57.587  5805  5805 W art     : b66f0000-b66f1000 rw-p 00000000 00:00 0 
,07-12 11:36:57.587  5805  5805 W art     : b66f1000-b66f4000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-12 11:36:57.607   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68d413 5733:com.samsung.android.sm.provider/1000}
07-12 11:36:57.587  5805  5805 W art     : b66f4000-b66f5000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-12 11:36:57.587  5805  5805 W art     : b66f5000-b66f6000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-12 11:36:57.587  5805  5805 W art     : b66f6000-b66fa000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-12 11:36:57.587  5805  5805 W art     : b66fa000-b66fb000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-12 11:36:57.587  5805  5805 W art     : b66fb000-b66fc000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-12 11:36:57.587  5805  5805 W art     : b66fc000-b670a000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-12 11:36:57.587  5805  5805 W art     : b670a000-b670b000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b670b000-b670c000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-12 11:36:57.587  5805  5805 W art     : b670c000-b670d000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-12 11:36:57.587  5805  5805 W art     : b670d000-b6716000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-12 11:36:57.587  5805  5805 W art     : b6716000-b6717000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-12 11:36:57.587  5805  5805 W art     : b6717000-b6718000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-12 11:36:57.587  5805  5805 W art     : b6718000-b677e000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-12 11:36:57.587  5805  5805 W art     : b677e000-b677f000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b677f000-b6781000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-12 11:36:57.587  5805  5805 W art     : b6781000-b678a000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-12 11:36:57.587  5805  5805 W art     : b678a000-b678d000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b678d000-b6824000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-12 11:36:57.587  5805  5805 W art     : b6824000-b6826000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-12 11:36:57.587  5805  5805 W art     : b6826000-b6827000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-12 11:36:57.587  5805  5805 W art     : b6827000-b6828000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6828000-b6b49000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-12 11:36:57.587  5805  5805 W art     : b6b49000-b6b4a000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6b4a000-b6b65000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-12 11:36:57.587  5805  5805 W art     : b6b65000-b6b69000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-12 11:36:57.587  5805  5805 W art     : b6b69000-b6b6e000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6b6e000-b6b76000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-12 11:36:57.587  5805  5805 W art     : b6b76000-b6b77000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-12 11:36:57.587  5805  5805 W art     : b6b77000-b6b78000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-12 11:36:57.587  5805  5805 W art     : b6b78000-b6ba6000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-12 11:36:57.587  5805  5805 W art     : b6ba6000-b6ba7000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6ba7000-b6bae000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-12 11:36:57.587  5805  5805 W art     : b6bae000-b6baf000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-12 11:36:57.587  5805  5805 W art     : b6baf000-b6bf5000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-12 11:36:57.587  5805  5805 W art     : b6bf5000-b6bf6000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6bf6000-b6bf9000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-12 11:36:57.587  5805  5805 W art     : b6bf9000-b6bfa000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-12 11:36:57.587  5805  5805 W art     : b6bfa000-b6c15000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-12 11:36:57.587  5805  5805 W art     : b6c15000-b6c19000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-12 11:36:57.587  5805  5805 W art     : b6c19000-b6c1a000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-12 11:36:57.587  5805  5805 W art     : b6c1a000-b6c67000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-12 11:36:57.587  5805  5805 W art     : b6c67000-b6c68000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6c68000-b6c74000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-12 11:36:57.587  5805  5805 W art     : b6c74000-b6c75000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-12 11:36:57.587  5805  5805 W art     : b6c75000-b6c82000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-12 11:36:57.587  5805  5805 W art     : b6c82000-b6c83000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6c83000-b6c84000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-12 11:36:57.587  5805  5805 W art     : b6c84000-b6c85000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-12 11:36:57.587  5805  5805 W art     : b6c85000-b6c8d000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-12 11:36:57.587  5805  5805 W art     : b6c8d000-b6c8e000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6c8e000-b6c8f000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-12 11:36:57.587  5805  5805 W art     : b6c8f000-b6c90000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-12 11:36:57.587  5805  5805 W art     : b6c90000-b6c97000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-12 11:36:57.587  5805  5805 W art     : b6c97000-b6c98000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-12 11:36:57.587  5805  5805 W art     : b6c98000-b6c99000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-12 11:36:57.587  5805  5805 W art     : b6c99000-b6cad000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-12 11:36:57.587  5805  5805 W art     : b6cad000-b6caf000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-12 11:36:57.587  5805  5805 W art     : b6caf000-b6cb0000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-12 11:36:57.587  5805  5805 W art     : b6cb0000-b6cd8000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-12 11:36:57.587  5805  5805 W art     : b6cd8000-b6cda000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-12 11:36:57.587  5805  5805 W art     : b6cda000-b6cdb000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-12 11:36:57.587  5805  5805 W art     : b6cdb000-b6cde000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-12 11:36:57.587  5805  5805 W art     : b6cde000-b6cdf000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-12 11:36:57.587  5805  5805 W art     : b6cdf000-b6ce0000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-12 11:36:57.587  5805  5805 W art     : b6ce0000-b6ce9000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-12 11:36:57.587  5805  5805 W art     : b6ce9000-b6cea000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-12 11:36:57.587  5805  5805 W art     : b6cea000-b6ceb000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-12 11:36:57.587  5805  5805 W art     : b6ceb000-b6d0b000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-12 11:36:57.587  5805  5805 W art     : b6d0b000-b6d0c000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-12 11:36:57.587  5805  5805 W art     : b6d0c000-b6d0d000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-12 11:36:57.587  5805  5805 W art     : b6d0d000-b6d80000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-12 11:36:57.587  5805  5805 W art     : b6d80000-b6d84000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-12 11:36:57.587  5805  5805 W art     : b6d84000-b6d87000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-12 11:36:57.587  5805  5805 W art     : b6d87000-b6d91000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6d91000-b6e19000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-12 11:36:57.587  5805  5805 W art     : b6e19000-b6e1a000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6e1a000-b6e1e000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-12 11:36:57.587  5805  5805 W art     : b6e1e000-b6e1f000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-12 11:36:57.587  5805  5805 W art     : b6e1f000-b6e20000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6e20000-b6e49000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-12 11:36:57.587  5805  5805 W art     : b6e49000-b6e4a000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6e4a000-b6e4d000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-12 11:36:57.587  5805  5805 W art     : b6e4d000-b6e4e000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-12 11:36:57.587  5805  5805 W art     : b6e4e000-b6f28000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-12 11:36:57.587  5805  5805 W art     : b6f28000-b6f2f000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-12 11:36:57.587  5805  5805 W art     : b6f2f000-b6f37000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-12 11:36:57.587  5805  5805 W art     : b6f37000-b6f38000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6f38000-b6f39000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 11:36:57.587  5805  5805 W art     : b6f39000-b6f3a000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-12 11:36:57.587  5805  5805 W art     : b6f3a000-b6f3b000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b6f3b000-b6f3e000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b6f3e000-b6f63000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-12 11:36:57.587  5805  5805 W art     : b6f63000-b6f64000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6f64000-b6f6b000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-12 11:36:57.587  5805  5805 W art     : b6f6b000-b6f6c000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-12 11:36:57.587  5805  5805 W art     : b6f6c000-b6f73000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-12 11:36:57.587  5805  5805 W art     : b6f73000-b6f74000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-12 11:36:57.587  5805  5805 W art     : b6f74000-b6f75000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-12 11:36:57.587  5805  5805 W art     : b6f75000-b6f76000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b6f76000-b6f8e000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-12 11:36:57.587  5805  5805 W art     : b6f8e000-b6f8f000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6f8f000-b6f90000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-12 11:36:57.587  5805  5805 W art     : b6f90000-b6f91000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-12 11:36:57.587  5805  5805 W art     : b6f91000-b6f9f000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-12 11:36:57.587  5805  5805 W art     : b6f9f000-b6fa0000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6fa0000-b6fa1000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-12 11:36:57.587  5805  5805 W art     : b6fa1000-b6fa2000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-12 11:36:57.587  5805  5805 W art     : b6fa2000-b6fa3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 11:36:57.587  5805  5805 W art     : b6fa3000-b6fa5000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b6fa5000-b6fa6000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b6fa6000-b6fa7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 11:36:57.587  5805  5805 W art     : b6fa7000-b6fa8000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-12 11:36:57.587  5805  5805 W art     : b6fa8000-b6fa9000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 11:36:57.587  5805  5805 W art     : b6fa9000-b6fc9000 r--s 00000000 00:0b 6706       /dev/__properties__
07-12 11:36:57.587  5805  5805 W art     : b6fc9000-b6fca000 r--p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6fca000-b6fcb000 ---p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6fcb000-b6fcd000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-12 11:36:57.587  5805  5805 W art     : b6fcd000-b6fce000 r-xp 00000000 00:00 0          [sigpage]
07-12 11:36:57.587  5805  5805 W art     : b6fce000-b6fe9000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-12 11:36:57.587  5805  5805 W art     : b6fe9000-b6fea000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-12 11:36:57.587  5805  5805 W art     : b6fea000-b6fec000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-12 11:36:57.587  5805  5805 W art     : b6fec000-b6fee000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : b6fee000-b6ff3000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-12 11:36:57.587  5805  5805 W art     : b6ff3000-b6ff4000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-12 11:36:57.587  5805  5805 W art     : b6ff4000-b6ff5000 rw-p 00000000 00:00 0 
07-12 11:36:57.587  5805  5805 W art     : bec3b000-bec5c000 rw-p 00000000 00:00 0          [stack]
07-12 11:36:57.587  5805  5805 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-12 11:36:57.627  5805  5805 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 11:36:57.637   777  1718 I ActivityManager: Start proc 5889:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
07-12 11:36:57.637  5889  5889 E Zygote  : v2
07-12 11:36:57.637  5889  5889 I libpersona: KNOX_SDCARD checking this for 5012
07-12 11:36:57.637  5889  5889 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:57.637  5889  5889 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:57.637  5889  5889 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:57.637  5889  5889 E Zygote  : accessInfo : 0
07-12 11:36:57.637  5889  5889 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
07-12 11:36:57.657  1810  5887 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-12 11:36:57.667  5889  5889 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:57.667  5889  5889 D ActivityThread: Added TimaKeyStore provider
07-12 11:36:57.667   777  2235 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f24650 5889:com.samsung.android.sm.devicesecurity/5012}
07-12 11:36:57.677  5889  5889 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
07-12 11:36:57.687  5805  5805 I Radio-JNI: register_android_hardware_Radio DONE
07-12 11:36:57.687  5889  5889 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
07-12 11:36:57.687   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-12 11:36:57.697  5805  5805 E AffinityControl: AffinityControl: registerfunction enter
07-12 11:36:57.707  5805  5805 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 11:36:57.727   777  2231 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-12 11:36:57.737  1810  5887 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
07-12 11:36:57.737   777  2231 D ActivityManager: mDVFSHelper.acquire()
07-12 11:36:57.737   777  2231 V WindowManager: addAppToken: AppWindowToken{1029e6f token=Token{a270d4e ActivityRecord{8748049 u0 com.test.thalitest/.MainActivity t104}}} to stack=1 task=104 at 0
07-12 11:36:57.747  1810  5887 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
07-12 11:36:57.747   777   912 D SecWifiDisplayUtil: Metadata value : none
07-12 11:36:57.747   777   912 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d49ec67 V.E...... R.....ID 0,0-0,0}
07-12 11:36:57.747   777   912 D ISSUE_DEBUG: InputChannelName : 69202bd Starting com.test.thalitest
07-12 11:36:57.757  5909  5909 E Zygote  : v2
07-12 11:36:57.757  5909  5909 I libpersona: KNOX_SDCARD checking this for 10004
07-12 11:36:57.757  5909  5909 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:57.757  5909  5909 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:57.757  5909  5909 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:57.757   777  2231 I ActivityManager: Start proc 5909:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-12 11:36:57.757   777  2231 D InputDispatcher: Focused application set to: xxxx
07-12 11:36:57.757  5909  5909 E Zygote  : accessInfo : 0
07-12 11:36:57.767   777  2231 D InputDispatcher: Focus left window: 3366
07-12 11:36:57.767  5805  5805 D AndroidRuntime: Shutting down VM
07-12 11:36:57.767   294   294 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
07-12 11:36:57.767   777  1589 I ActivityManager: Killing 5190:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): DHA:empty #37
07-12 11:36:57.787   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd2e4d1 3068:com.android.contacts/u0a19}
07-12 11:36:57.787  5909  5909 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-12 11:36:57.787   777   912 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:777 uid:1000
07-12 11:36:57.787   777   912 D PointerIcon: setMouseCustomIcon IconType is same.101
07-12 11:36:57.787   777   912 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:777 uid:1000
07-12 11:36:57.787   777   912 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-12 11:36:57.787   777   912 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-12 11:36:57.797   777   862 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{8c20971 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-12 11:36:57.797  1386  1386 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-12 11:36:57.807   777  2222 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.SPlannerAppWidget, Auto Run ON
07-12 11:36:57.817   777   912 V WindowStateAnimator: Finishing drawing window Window{69202bd u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-12 11:36:57.827  5909  5909 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:57.827  5909  5909 D ActivityThread: Added TimaKeyStore provider
07-12 11:36:57.827   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbea01364
07-12 11:36:57.827   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b130a34 4976:com.android.mms/u0a49}
07-12 11:36:57.837   777  1718 V WindowOrientationListener: setCurrentAppOrientation :-1
07-12 11:36:57.837   777  1718 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-12 11:36:57.837   777   789 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
07-12 11:36:57.847   777  1718 D ActivityManager:  Launching com.test.thalitest, updated priority
07-12 11:36:57.857   777   861 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-12 11:36:57.867  1721  1870 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
07-12 11:36:57.867  1721  1721 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
07-12 11:36:57.867   294   384 D libEGL  : eglTerminate EGLDisplay = 0xb66bf64c
07-12 11:36:57.877   294  4590 D libEGL  : eglTerminate EGLDisplay = 0xb1f0064c
07-12 11:36:57.877   294   854 I SurfaceFlinger: id=13 Removed VSBConnecti (7/11)
07-12 11:36:57.877   294  4590 D libEGL  : eglTerminate EGLDisplay = 0xb1f0064c
07-12 11:36:57.877   294   379 I SurfaceFlinger: id=13 Removed VSBConnecti (-2/11)
07-12 11:36:57.877   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbea013a4
07-12 11:36:57.877   294   854 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
07-12 11:36:57.877   294   379 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
07-12 11:36:57.887   294  4590 I SurfaceFlinger: id=14 Removed VSBConnecti (4/9)
07-12 11:36:57.887   294   379 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/9)
07-12 11:36:57.887  1721  1721 V ActivityThread: updateVisibility : ActivityRecord{d0a2d5e token=android.os.BinderProxy@43a80ef {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-12 11:36:57.887  1721  1721 D Launcher: onTrimMemory. Level: 20
07-12 11:36:57.887  3366  3366 V ActivityThread: updateVisibility : ActivityRecord{1fb10e0 token=android.os.BinderProxy@31a1aba {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-12 11:36:57.887  2095  2107 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
07-12 11:36:57.897   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbea013a4
07-12 11:36:57.897   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbea013a4
,07-12 11:36:58.007  5909  5909 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-12 11:36:58.017   777   862 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{69202bd u0 d0 Starting com.test.thalitest}
,07-12 11:36:58.017  1386  1386 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
,07-12 11:36:58.027   777  1589 I ActivityManager: Start proc 5922:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,07-12 11:36:58.027  5922  5922 E Zygote  : v2
07-12 11:36:58.027  5922  5922 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:36:58.027  5922  5922 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:58.027  5922  5922 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:58.027  5922  5922 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:36:58.037  5922  5922 E Zygote  : accessInfo : 0
,07-12 11:36:58.047   777   908 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-12 11:36:58.057  5909  5909 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-12 11:36:58.057  5909  5909 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-12 11:36:58.077  5909  5909 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-12 11:36:58.087  5922  5922 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:58.087  5922  5922 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:58.097   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68bb7ac 5922:com.samsung.android.bbc.bbcagent/1000}
,07-12 11:36:58.107  3983  5921 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-12 11:36:58.117  5909  5909 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-12 11:36:58.127  5909  5909 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-12 11:36:58.137  5909  5909 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 8794-8798)
07-12 11:36:58.137  5909  5909 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-12 11:36:58.147   777   787 I art     : Background partial concurrent mark sweep GC freed 135260(8MB) AllocSpace objects, 8(1896KB) LOS objects, 27% free, 41MB/57MB, paused 1.738ms total 176.814ms
,07-12 11:36:58.157  5922  5922 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,07-12 11:36:58.167  5909  5909 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {589698c}
07-12 11:36:58.167  5909  5909 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-12 11:36:58.167  5909  5909 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:36:58.177  5909  5936 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-12 11:36:58.177  1810  5887 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 523 ms] updated apps [took 523 ms] 
,07-12 11:36:58.177  5922  5922 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,07-12 11:36:58.187  5909  5909 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-12 11:36:58.197  5909  5937 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,07-12 11:36:58.207  5909  5909 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-12 11:36:58.207  5909  5909 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-12 11:36:58.207  5909  5909 I Adreno-EGL: Build Date: 01/28/16 Thu
07-12 11:36:58.207  5909  5909 I Adreno-EGL: Local Branch: ss
07-12 11:36:58.207  5909  5909 I Adreno-EGL: Remote Branch: 
07-12 11:36:58.207  5909  5909 I Adreno-EGL: Local Patches: 
07-12 11:36:58.207  5909  5909 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:36:58.207   777  2212 I ActivityManager: Start proc 5941:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
07-12 11:36:58.207  5941  5941 E Zygote  : v2
07-12 11:36:58.207  5941  5941 I libpersona: KNOX_SDCARD checking this for 10097
07-12 11:36:58.207  5941  5941 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:58.207  5941  5941 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:58.207  5941  5941 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:36:58.217  5941  5941 E Zygote  : accessInfo : 0
,07-12 11:36:58.217  5941  5941 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,07-12 11:36:58.217  5909  5909 D libEGL  : eglInitialize EGLDisplay = 0xbebcddac
,07-12 11:36:58.237  5941  5941 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:58.237  5941  5941 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:58.237   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74036d6 5941:com.google.android.apps.docs/u0a97}
,07-12 11:36:58.247   777  1300 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,07-12 11:36:58.247   777  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-12 11:36:58.257  5941  5941 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,07-12 11:36:58.277  5941  5941 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,07-12 11:36:58.327  5909  5909 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-12 11:36:58.337  5909  5909 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 11:36:58.337  5909  5909 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-12 11:36:58.337  5909  5909 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-12 11:36:58.337  5909  5909 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-12 11:36:58.357  5909  5909 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-12 11:36:58.357  5909  5909 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-12 11:36:58.457  5909  5909 D SecWifiDisplayUtil: Metadata value : none
,07-12 11:36:58.457  5909  5909 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{cc4d44a I.E...... R.....ID 0,0-0,0}
,07-12 11:36:58.457  5909  5972 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-12 11:36:58.457   777   789 D ISSUE_DEBUG: InputChannelName : c3a2f6a com.test.thalitest/com.test.thalitest.MainActivity
,07-12 11:36:58.467   777  1421 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-12 11:36:58.467   777  1421 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-12 11:36:58.467   777   777 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-12 11:36:58.467   777   777 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-12 11:36:58.477  5909  5909 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 5909
,07-12 11:36:58.477   777  2235 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/5909 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:36:58.497  5909  5909 D SecWifiDisplayUtil: Metadata value : none
,07-12 11:36:58.497  5909  5936 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,07-12 11:36:58.497   294   294 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-12 11:36:58.507   777  1719 D InputDispatcher: Focus entered window: 5909
,07-12 11:36:58.507   777   912 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:777 uid:1000
07-12 11:36:58.507   777   912 D PointerIcon: setMouseCustomIcon IconType is same.101
07-12 11:36:58.507   777   912 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:777 uid:1000
07-12 11:36:58.507   777   912 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-12 11:36:58.507  5909  5972 D libEGL  : eglInitialize EGLDisplay = 0x9d7bf7c4
07-12 11:36:58.507  5909  5972 I OpenGLRenderer: Initialized EGL, version 1.4
,07-12 11:36:58.567  5909  5909 V ActivityThread: updateVisibility : ActivityRecord{4cffc97 token=android.os.BinderProxy@a7955b5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-12 11:36:58.567  5909  5909 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-12 11:36:58.567  5909  5909 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-12 11:36:58.567   777  1727 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-12 11:36:58.577  5909  5909 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-12 11:36:58.597   777  1588 V WindowStateAnimator: Finishing drawing window Window{c3a2f6a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,07-12 11:36:58.597  5909  5909 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-12 11:36:58.597  5909  5909 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a7955b5 time:109256
,07-12 11:36:58.607   777   912 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-12 11:36:58.607   777   912 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +608ms (total +855ms)
,07-12 11:36:58.607   777   912 D ActivityManager: mDVFSHelper.release()
07-12 11:36:58.607   777   912 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8748049 u0 com.test.thalitest/.MainActivity t104} time:109263
,07-12 11:36:58.607   777   777 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-12 11:36:58.607   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbea01364
,07-12 11:36:58.607   777   777 I KnoxTimeoutHandler: SD activityfalse
,07-12 11:36:58.607   777   912 D ViewRootImpl: #3 mView = null
,07-12 11:36:58.607   294   854 I SurfaceFlinger: id=15 Removed uhalitest (7/9)
,07-12 11:36:58.607   294   379 I SurfaceFlinger: id=15 Removed uhalitest (-2/9)
,07-12 11:36:58.627   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbea013a4
,07-12 11:36:58.657  5909  5980 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:36:58.657  5909  5980 D libEGL  : eglInitialize EGLDisplay = 0x9bf5f3ec
,07-12 11:36:58.687  5909  5909 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5909
,07-12 11:36:58.707  5941  5985 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
07-12 11:36:58.707  5941  5985 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:36:58.707  5941  5985 I GAv4    :   adb logcat -s GAv4
,07-12 11:36:58.717  5941  5985 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,07-12 11:36:58.727   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{481e09: PendingIntentRecord{bd1b80e com.google.android.apps.docs broadcastIntent}}
,07-12 11:36:58.727  5941  5985 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:58.737  5941  5985 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:58.737  5941  5991 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:58.857  5941  5941 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,07-12 11:36:58.857  5941  5941 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,07-12 11:36:58.857  5909  5909 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 11:36:58.877  5941  5985 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
07-12 11:36:58.877  5941  5985 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,07-12 11:36:58.877  5941  5985 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
07-12 11:36:58.877  5941  5985 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,07-12 11:36:58.917   777  1727 I ActivityManager: Start proc 6000:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,07-12 11:36:58.917  6000  6000 E Zygote  : v2
07-12 11:36:58.917  6000  6000 I libpersona: KNOX_SDCARD checking this for 10098
07-12 11:36:58.917  6000  6000 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:58.917  6000  6000 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:58.917  6000  6000 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:58.917  6000  6000 E Zygote  : accessInfo : 0
07-12 11:36:58.917  6000  6000 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
07-12 11:36:58.917   777  1727 I ActivityManager: Killing 4608:com.android.calendar/u0a149 (adj 15): DHA:empty #37
,07-12 11:36:58.937  6000  6000 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:58.937  6000  6000 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:58.947   777  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{df5471a 6000:com.sec.android.automotive.drivelink/u0a98}
,07-12 11:36:58.967   777  1727 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
,07-12 11:36:58.967  6000  6000 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,07-12 11:36:58.977  6000  6000 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,07-12 11:36:58.997  5909  6012 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1686111952
,07-12 11:36:58.997  5909  6012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:36:58.997  5909  6012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:36:58.997  5909  6012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:36:58.997  5909  6012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:36:58.997  5909  6012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 11:36:58.997  5909  6012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6c1625 added. We now have 1 listener(s)
,07-12 11:36:58.997  6000  6000 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
07-12 11:36:59.007  5909  6012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,07-12 11:36:59.007  5909  6012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,07-12 11:36:59.007  5909  6012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 11:36:59.007  5909  6012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 11:36:59.007  5909  6012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc3fc08 added. We now have 1 listener(s)
07-12 11:36:59.007  5909  6012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 11:36:59.007  5909  6012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:59.007  5909  6012 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-12 11:36:59.007   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{535624b: PendingIntentRecord{cafe428 com.sec.android.automotive.drivelink broadcastIntent}}
,07-12 11:36:59.017  5909  6012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 11:36:59.017  5909  6012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:36:59.017  5909  6012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:36:59.017  5909  6012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 11:36:59.017   777  3288 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,07-12 11:36:59.017  5909  6012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 11:36:59.017  5909  6012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,07-12 11:36:59.017  5909  6012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:59.017  5909  6012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:59.017  5909  6012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:59.017  5909  6012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:59.017  5909  6012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:59.017  5909  6012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:59.017  5909  6012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:59.017  5909  6012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:59.017  5909  6012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:36:59.017  5909  6012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 11:36:59.017  5909  6012 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 11:36:59.017  6000  6014 I GMPM    : App measurement is starting up
,07-12 11:36:59.017  5909  6012 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 11:36:59.027  6000  6014 E GMPM    : getGoogleAppId failed with status: 10
,07-12 11:36:59.027  6000  6014 E GMPM    : Uploading is not possible. App measurement disabled
,07-12 11:36:59.027   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{95dcfc3: PendingIntentRecord{cafe428 com.sec.android.automotive.drivelink broadcastIntent}}
,07-12 11:36:59.027  6000  6000 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,07-12 11:36:59.047  2119  2119 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:59.047  2119  2119 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:59.057  5909  5909 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:36:59.077  6000  6000 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,07-12 11:36:59.077  2119  2119 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:59.087  6000  6000 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,07-12 11:36:59.157  6021  6021 E Zygote  : v2
07-12 11:36:59.157  6021  6021 I libpersona: KNOX_SDCARD checking this for 10032
07-12 11:36:59.157  6021  6021 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:59.157  6021  6021 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:59.157  6021  6021 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:36:59.157  6021  6021 E Zygote  : accessInfo : 0
07-12 11:36:59.157   777  2231 I ActivityManager: Start proc 6021:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,07-12 11:36:59.157   777  1327 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-12 11:36:59.157  6021  6021 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,07-12 11:36:59.177  5941  5988 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,07-12 11:36:59.187  6021  6021 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:59.187  6021  6021 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:59.197   777  1327 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,07-12 11:36:59.197   777  5715 I HarmonyEASService: Updating for all 1
,07-12 11:36:59.197  6021  6021 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,07-12 11:36:59.217  5941  5988 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-12 11:36:59.227  6021  6021 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,07-12 11:36:59.237  3983  4860 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,07-12 11:36:59.257  5941  5988 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-12 11:36:59.257  5941  5988 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-12 11:36:59.257  5941  5988 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:36:59.287  3983  4860 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,07-12 11:36:59.297  5941  5988 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:36:59.327  6000  6000 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,07-12 11:36:59.337  6000  6000 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,07-12 11:36:59.347  6000  6000 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,07-12 11:36:59.347  6021  6021 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,07-12 11:36:59.357  3983  4860 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,07-12 11:36:59.367  6000  6000 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Jul 12 11:36:59 GMT+02:00 2016
,07-12 11:36:59.367  6000  6000 D DialogFlow: initQueue()
,07-12 11:36:59.377  6021  6021 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,07-12 11:36:59.377  6035  6035 E Zygote  : v2
07-12 11:36:59.377  6035  6035 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:36:59.377  6035  6035 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:59.377  6035  6035 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:59.377  6035  6035 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:36:59.377  6035  6035 E Zygote  : accessInfo : 0
,07-12 11:36:59.377   777  1718 I ActivityManager: Start proc 6035:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,07-12 11:36:59.377   777  1718 I ActivityManager: Killing 5080:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #37
,07-12 11:36:59.387   777  1718 I ActivityManager: Killing 5207:com.sec.esdk.elm/u0a103 (adj 15): DHA:empty #37
,07-12 11:36:59.397  6035  6035 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:59.397  6035  6035 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:59.407   777  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41336ed 6035:com.samsung.android.app.filterinstaller/1000}
,07-12 11:36:59.417   777  1420 D ActivityManager: isAutoRunBlockedApp:: com.sec.esdk.elm, Auto Run ON
,07-12 11:36:59.417  6035  6035 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,07-12 11:36:59.417   777  1719 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
,07-12 11:36:59.437  6035  6035 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,07-12 11:36:59.437   777  2231 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,07-12 11:36:59.447  6035  6035 E FilterPackageIntentReceiver: This package is not a effect filter
,07-12 11:36:59.457  6051  6051 E Zygote  : v2
07-12 11:36:59.457  6051  6051 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:36:59.457  6051  6051 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:59.457   777   789 I ActivityManager: Start proc 6051:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,07-12 11:36:59.457  6051  6051 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:59.457  6051  6051 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:36:59.457   777   789 I ActivityManager: Killing 5241:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,07-12 11:36:59.467  6051  6051 E Zygote  : accessInfo : 0
,07-12 11:36:59.467  1462  1462 D Recents : onTaskStackChanged
,07-12 11:36:59.477   777  2212 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,07-12 11:36:59.477  1462  1462 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-12 11:36:59.487  6051  6051 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:59.487  6051  6051 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:59.497   777  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bed4c9c 6051:com.samsung.helphub/1000}
,07-12 11:36:59.507  6021  6021 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,07-12 11:36:59.507  6021  6021 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,07-12 11:36:59.507  6051  6051 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,07-12 11:36:59.517  6021  6021 D DialogFlow: initQueue()
,07-12 11:36:59.537  6051  6051 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,07-12 11:36:59.577  6063  6063 E Zygote  : v2
07-12 11:36:59.577  6063  6063 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:36:59.577  6063  6063 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:59.577  6063  6063 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:59.577  6063  6063 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:59.577   777  1678 I ActivityManager: Start proc 6063:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,07-12 11:36:59.577  6063  6063 E Zygote  : accessInfo : 0
,07-12 11:36:59.577   777  1678 I ActivityManager: Killing 5256:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
,07-12 11:36:59.607   777  1727 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
,07-12 11:36:59.607  6063  6063 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:59.607  6063  6063 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:59.617   777  1420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0956a5 6063:com.samsung.android.app.mirrorlink/1000}
,07-12 11:36:59.617  6063  6063 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,07-12 11:36:59.637  6063  6063 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,07-12 11:36:59.667  6063  6063 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,07-12 11:36:59.667  6063  6063 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,07-12 11:36:59.667   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ce8a82 5394:com.google.android.apps.plus/u0a134}
,07-12 11:36:59.677   777  1421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ce8a82 5394:com.google.android.apps.plus/u0a134}
,07-12 11:36:59.697   777   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ce8a82 5394:com.google.android.apps.plus/u0a134}
,07-12 11:36:59.737   777  1420 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,07-12 11:36:59.747   777   789 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,07-12 11:36:59.747   777  1727 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,07-12 11:36:59.747   777   790 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,07-12 11:36:59.747   777  2222 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,07-12 11:36:59.747   777  1718 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,07-12 11:36:59.747   777  1589 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,07-12 11:36:59.757   777  1678 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,07-12 11:36:59.767  6077  6077 E Zygote  : v2
07-12 11:36:59.767  6077  6077 I libpersona: KNOX_SDCARD checking this for 10165
07-12 11:36:59.767  6077  6077 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:59.767  6077  6077 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:59.767  6077  6077 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:59.767   777  1421 I ActivityManager: Start proc 6077:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,07-12 11:36:59.777  6077  6077 E Zygote  : accessInfo : 0
07-12 11:36:59.777  6077  6077 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,07-12 11:36:59.787   777  2222 I ActivityManager: Killing 5092:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,07-12 11:36:59.797   777  1718 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,07-12 11:36:59.827  6077  6077 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:59.827  6077  6077 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:59.837   777  1588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd09688 6077:com.sec.kidsplat.installer/u0a165}
,07-12 11:36:59.837  6077  6077 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,07-12 11:36:59.847  6077  6077 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,07-12 11:36:59.857   777  2222 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd09688 6077:com.sec.kidsplat.installer/u0a165}
,07-12 11:36:59.867  6077  6077 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,07-12 11:36:59.877   777  1300 I ActivityManager: Start proc 6089:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,07-12 11:36:59.877  6089  6089 E Zygote  : v2
07-12 11:36:59.877  6089  6089 I libpersona: KNOX_SDCARD checking this for 10142
07-12 11:36:59.877  6089  6089 E Zygote  : isSdpEnabledProcess - SDP enabled
07-12 11:36:59.877  6089  6089 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:59.877  6089  6089 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:36:59.877   777  1300 I ActivityManager: Killing 4278:com.wssyncmldm/1000 (adj 15): DHA:empty #37
07-12 11:36:59.877  6089  6089 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:59.877  6089  6089 E Zygote  : accessInfo : 64
07-12 11:36:59.877  6089  6089 E Zygote  : isSdpEnabledProcess - SDP enabled
07-12 11:36:59.877  6089  6089 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
07-12 11:36:59.877  6089  6089 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,07-12 11:36:59.897   777  1678 D ActivityManager: isAutoRunBlockedApp:: com.wssyncmldm, Auto Run ON
,07-12 11:36:59.897  6089  6089 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:59.897  6089  6089 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:59.907   777   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ddb821 6089:com.sec.android.app.sbrowser/u0a142}
,07-12 11:36:59.917  6089  6089 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,07-12 11:36:59.937  6089  6089 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,07-12 11:36:59.967  6089  6089 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,07-12 11:36:59.977  6089  6089 D ManifestProvider: onCreate()
,07-12 11:36:59.987  6089  6089 I SBrowserUtils: getSystemProperty of sales_code : XEO
,07-12 11:36:59.987  6089  6089 I SBrowserUtils: getSystemProperty of country_code : Poland
07-12 11:36:59.987  6089  6089 I SBrowserUtils: getSystemProperty of country_code : Poland
07-12 11:36:59.987  6089  6089 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,07-12 11:36:59.987  5909  6016 W jxcore-log: Initializing JXcore engine
07-12 11:36:59.987  5909  6016 W jxcore-log: JXcore engine is ready
,07-12 11:36:59.987   777  1240 V AlarmManager: Expired Alarm result :8
,07-12 11:37:00.007  6089  6089 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,07-12 11:37:00.007  6089  6089 D [MM]MHDataBaseProvider: onCreate()
,07-12 11:37:00.027  6089  6089 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@a241d51)
,07-12 11:37:00.027  2151  2151 E audit   : type=1400 msg=audit(1468316220.027:281): avc:  denied  { ioctl } for  pid=6016 comm="Thread-847" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-12 11:37:00.027  2151  2151 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:00.027  2151  2151 E audit   : type=1300 msg=audit(1468316220.027:281): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9b6f73c8 items=0 ppid=349 ppcomm=main pid=6016 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-847" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-12 11:37:00.027  2151  2151 E audit   : type=1327 msg=audit(1468316220.027:281): proctitle="com.test.thalitest"
07-12 11:37:00.027  2151  2151 E audit   : type=1320 msg=audit(1468316220.027:281): 
,07-12 11:37:00.027  2151  2151 E audit   : type=1400 msg=audit(1468316220.027:282): avc:  denied  { ioctl } for  pid=6016 comm="Thread-847" path="socket:[38119]" dev="sockfs" ino=38119 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-12 11:37:00.027  2151  2151 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:00.027  2151  2151 E audit   : type=1300 msg=audit(1468316220.027:282): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9b6f73c8 items=0 ppid=349 ppcomm=main pid=6016 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-847" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-12 11:37:00.027  2151  2151 E audit   : type=1327 msg=audit(1468316220.027:282): proctitle="com.test.thalitest"
07-12 11:37:00.027  2151  2151 E audit   : type=1320 msg=audit(1468316220.027:282): 
,07-12 11:37:00.047  5909  6016 W jxcore-log: Starting JXcore engine
,07-12 11:37:00.047   777   790 I ActivityManager: Killing 3871:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
,07-12 11:37:00.057   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:00.077   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{25db01b 3983:com.google.android.gms/u0a11}
,07-12 11:37:00.077  3983  6105 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-12 11:37:00.077  3983  6104 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-12 11:37:00.077   777  1727 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,07-12 11:37:00.077  3983  6105 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-12 11:37:00.087  3983  3983 D AsyncTaskServiceImpl: Submit a task: nwp
,07-12 11:37:00.107  3983  6105 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-12 11:37:00.107   777  1718 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:00.117   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{25db01b 3983:com.google.android.gms/u0a11}
,07-12 11:37:00.127  3983  4860 D nwp     : Processing package: com.test.thalitest
,07-12 11:37:00.127  3983  3983 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,07-12 11:37:00.147  5909  6016 W jxcore-log: Platform android
07-12 11:37:00.147  5909  6016 W jxcore-log: 
07-12 11:37:00.147  5909  6016 W jxcore-log: Process ARCH arm
07-12 11:37:00.147  5909  6016 W jxcore-log: 
,07-12 11:37:00.157  3983  4860 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,07-12 11:37:00.157  3983  4860 D nwp     : Found info for package com.test.thalitest in db.
,07-12 11:37:00.237  3983  3983 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,07-12 11:37:00.237   777  1718 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8a36ddb 5422:com.android.vending/u0a29}
,07-12 11:37:00.267  5422  5422 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,07-12 11:37:00.277   777  1420 I ActivityManager: Start proc 6110:com.sec.android.app.samsungapps/u0a39 for broadcast-3 com.sec.android.app.samsungapps/.MyPackageReplacedReceiver
,07-12 11:37:00.277  6110  6110 E Zygote  : v2
07-12 11:37:00.277  6110  6110 I libpersona: KNOX_SDCARD checking this for 10039
07-12 11:37:00.277  6110  6110 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:00.277  6110  6110 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:00.277  6110  6110 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:00.277  6110  6110 E Zygote  : accessInfo : 0
,07-12 11:37:00.277  6110  6110 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,07-12 11:37:00.277  5422  5422 I Finsky  : [1] com.google.android.finsky.utils.bh.run(2302): Package state data is missing for com.test.thalitest
,07-12 11:37:00.317  6110  6110 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:00.317  6110  6110 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:00.327   777  2231 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81e3b2a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1bac1b 6110:com.sec.android.app.samsungapps/u0a39}
,07-12 11:37:00.337  6110  6110 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.sec.android.app.samsungapps rsrc of package null
,07-12 11:37:00.357  6021  6049 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-12 11:37:00.357  6021  6049 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-12 11:37:00.357  6110  6110 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-2/lib/arm
,07-12 11:37:00.377  5909  6016 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:37:00.377  5909  6016 I jxcore-log: 
,07-12 11:37:00.377  5909  6016 W jxcore-log: JXcore engine is started
,07-12 11:37:00.387  5909  6012 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 11:37:00.387  5909  5909 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:37:00.437  6021  6049 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,07-12 11:37:00.437  6021  6049 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
07-12 11:37:00.437  6021  6049 I System.out: INFO:Resource not found:/Common.properties Using default values
,07-12 11:37:00.447  6021  6049 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,07-12 11:37:00.447  6021  6049 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-12 11:37:00.467   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{11ab1b8 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b2a143 5474:com.sec.android.app.shealth/u0a34}
,07-12 11:37:00.477   777  2212 I ActivityManager: Killing 5286:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
,07-12 11:37:00.477   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{11ab1b8 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74eac8c 1852:com.sec.android.app.shealth:remote/u0a34}
,07-12 11:37:00.487   777  2222 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
,07-12 11:37:00.507   777  1420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{11ab1b8 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74eac8c 1852:com.sec.android.app.shealth:remote/u0a34}
,07-12 11:37:00.527   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d3eb91 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:00.777   777  1371 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/104_task.xml.bak
,07-12 11:37:00.827  3983  6109 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,07-12 11:37:01.387  3983  4860 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
07-12 11:37:01.437  3983  4860 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
07-12 11:37:01.437  3983  4860 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
07-12 11:37:01.447  3983  4860 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,07-12 11:37:04.027   777  3287 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:04.807   777  3287 D SSRM:n  : SIOP:: AP = 430, PST = 420, CUR = 450, LCD = 0
,07-12 11:37:07.177   777  1421 I ActivityManager: Killing 5301:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
,07-12 11:37:07.207   777   789 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
,07-12 11:37:07.507   777   939 D PackageManager: [MSG] MCS_UNBIND
,07-12 11:37:07.507   777  1300 I ActivityManager: Killing 4862:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,07-12 11:37:07.527   777  2212 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,07-12 11:37:07.787   777   939 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-12 11:37:07.797   777   939 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-12 11:37:10.207   777  1594 E Watchdog: !@Sync 3 [07-12 11:37:10.214]
,07-12 11:37:10.617  5909  6016 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 11:37:10.617  5909  6016 I jxcore-log: 
,07-12 11:37:10.617  5909  6016 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 11:37:10.617  5909  6016 I jxcore-log: 
,07-12 11:37:10.617  5909  6016 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:10.617  5909  6016 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:37:10.617  5909  6016 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:10.617  5909  6016 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:37:10.617  5909  6016 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:37:10.617  5909  6016 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:37:10.617  5909  6016 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:10.617  5909  6016 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:10.617  5909  6016 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:37:10.617  5909  6016 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:10.617  5909  6016 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:37:10.627  5909  6016 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 11:37:10.627  5909  6016 I jxcore-log: 
,07-12 11:37:10.627  5909  6016 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
07-12 11:37:10.627  5909  6016 I jxcore-log: 
,07-12 11:37:10.967  5909  6016 I jxcore-log: Unit Test app is loaded
07-12 11:37:10.967  5909  6016 I jxcore-log: 
,07-12 11:37:10.967  5909  6016 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 11:37:10.967  5909  6016 I jxcore-log: 
,07-12 11:37:10.977  5909  6016 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-12 11:37:10.987   777   790 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-12 11:37:10.987   777   790 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-12 11:37:10.987  5909  5909 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 11:37:10.997   777   790 E SContext.CaeProvider: setAttribute() : attribute is null!
,07-12 11:37:10.997   777   790 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,07-12 11:37:11.007   777   790 V CAE     : start(ContextProvider.java:128)
,07-12 11:37:11.007   777   790 V CAE     : clear(ActivityTrackerRunner.java:108)
,07-12 11:37:11.007   777   790 V CAE     : enable(ActivityTrackerRunner.java:84)
07-12 11:37:11.007   777   790 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 9, 37, 11,
07-12 11:37:11.007   777   790 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 9, 37, 11
,07-12 11:37:11.007   326  1245 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 9, 37, 11
,07-12 11:37:11.017   777   790 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-12 11:37:11.017   777   790 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-12 11:37:11.027   777   790 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-12 11:37:11.027   777   790 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-12 11:37:11.027   777   790 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-12 11:37:11.027   777   790 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@d27aaf6, Service : ACTIVITY_TRACKER(1)
,07-12 11:37:11.027   777   790 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-12 11:37:11.027   777   790 D SContextService: 	.registerCallback : 1, client=
07-12 11:37:11.027   777   790 D SContextService: ===== SContext Service List =====
07-12 11:37:11.027   777   790 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@1a53164, Service : Activity Tracker
07-12 11:37:11.027   777   790 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@3eeef7, service=Activity Tracker
,07-12 11:37:11.027   777   790 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
,07-12 11:37:11.027   777   790 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
,07-12 11:37:11.027   777   790 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
07-12 11:37:11.027   777   790 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
07-12 11:37:11.027   777   790 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
,07-12 11:37:11.027   326   326 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-12 11:37:11.037   777   790 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,07-12 11:37:11.037   777   790 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-12 11:37:11.047   777   790 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
07-12 11:37:11.047   777   790 D SContextService: requestToUpdate() : service = Activity Tracker
07-12 11:37:11.047   777   790 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@3eeef7, service=Activity Tracker
07-12 11:37:11.047   777   790 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
07-12 11:37:11.047   777   790 D WifiService: setWifiEnabled: true pid=5909, uid=10004
,07-12 11:37:11.047   777   790 W ActivityManager: Permission Denial: getCurrentUser() from pid=5909, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
,07-12 11:37:11.047   777   790 W WifiService: Failed getting userId using ActivityManagerNative
07-12 11:37:11.047   777   790 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5909, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
07-12 11:37:11.047   777   790 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28165)
07-12 11:37:11.047   777   790 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2437)
07-12 11:37:11.047   777   790 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2425)
07-12 11:37:11.047   777   790 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-12 11:37:11.047   777   790 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 11:37:11.047   777   790 D SettingsProvider: isChangeAllowed() : name = wifi_on
07-12 11:37:11.047   777  1329 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,07-12 11:37:11.057   777  1330 D WifiController: [FCC]setFccChannel() is called !!!
07-12 11:37:11.057   777  1330 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,07-12 11:37:11.057   777  1678 I WifiService: disconnect: pid=5909, uid=10004
,07-12 11:37:11.057   777  1330 D WifiStateMachine: setFccChannel: channel = 0
,07-12 11:37:11.057  5909  6016 D BluetoothAdapter: enable()
,07-12 11:37:11.057   777  1329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18701 com.android.server.wifi.WifiStateMachine.access$3900:292 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8638 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,07-12 11:37:11.057   777  1330 D SecContentProvider: insert(), uri = 2
,07-12 11:37:11.057   777  1329 D WifiBigDataLog: init : 
,07-12 11:37:11.067   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fbaafcd u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d29fce 2183:com.samsung.android.providers.context/u0a174}
,07-12 11:37:11.067   777  1300 W ActivityManager: Permission Denial: getCurrentUser() from pid=5909, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
,07-12 11:37:11.067   777  1329 E WifiHW  : ##################### set firmware type 0 #####################
,07-12 11:37:11.067   777  1300 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-12 11:37:11.067   777  1300 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5909, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
07-12 11:37:11.067   777  1300 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28165)
07-12 11:37:11.067   777  1300 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2848)
07-12 11:37:11.067   777  1300 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2838)
07-12 11:37:11.067   777  1300 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1218)
07-12 11:37:11.067   777  1300 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
07-12 11:37:11.067   777  1300 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
07-12 11:37:11.067   777  1300 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-12 11:37:11.067   777  1300 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-12 11:37:11.077   306  1138 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-12 11:37:11.077   306  1138 I WifiHW  : module is semco 3RD
07-12 11:37:11.077   306  1138 E WifiHW  : ==========[WIFI] SEMCO 3RD MODULE ===========
07-12 11:37:11.077   306  1138 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_semco3rd
07-12 11:37:11.077   306  1138 E WifiHW  : TEMP_FAILURE_RETRY complete
07-12 11:37:11.077   306  1138 D SoftapController: Softap fwReload - Ok
,07-12 11:37:11.077   777  1300 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,07-12 11:37:11.077   326   574 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 2, 16, 109, -109, 0, 0
,07-12 11:37:11.087   777  1243 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 2, 16, 109, -109, 0, 0
,07-12 11:37:11.087  5909  6016 I jxcore-log: My device name is: samsung-SM-G900F
07-12 11:37:11.087  5909  6016 I jxcore-log: 
,07-12 11:37:11.087  5909  6016 I jxcore-log: WARN testUtils: myNameCallback not set!
07-12 11:37:11.087  5909  6016 I jxcore-log: 
,07-12 11:37:11.097   777   909 I ActivityManager: Start proc 6150:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
07-12 11:37:11.097  6150  6150 E Zygote  : v2
07-12 11:37:11.097  6150  6150 I libpersona: KNOX_SDCARD checking this for 1002
07-12 11:37:11.097  6150  6150 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:11.097  6150  6150 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:11.097  6150  6150 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:11.097   777  1242 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 9, 37, 11,
,07-12 11:37:11.097  6150  6150 E Zygote  : accessInfo : 0
,07-12 11:37:11.097   777  1242 D SensorHubManager: SendSensorHubData: send data = -63, 14, 9, 37, 11
07-12 11:37:11.097   326  1244 D Sensorhubs: sendContextData: -63, 14, 9, 37, 11
,07-12 11:37:11.107   777  1242 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_SLEEP
,07-12 11:37:11.107   777  1242 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
,07-12 11:37:11.107   777  1242 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 2, 16, 109, -109, 0, 0,
,07-12 11:37:11.117   777  1242 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,07-12 11:37:11.117   777  1242 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1468316231059]
,07-12 11:37:11.117   777  1247 D SContextService: updateSContext() : event = Activity Tracker
,07-12 11:37:11.127   777   777 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,07-12 11:37:11.127   777   777 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,07-12 11:37:11.127   777   777 D WifiService: setWifiScanWithSensor bMove = 0
07-12 11:37:11.127   777   777 D WifiStateMachine: setWifiScanMove bMove = 0
07-12 11:37:11.127   777   777 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
,07-12 11:37:11.127   306  1138 D CommandListener: Setting iface cfg
,07-12 11:37:11.127   306  1138 D CommandListener: Trying to bring down wlan0
,07-12 11:37:11.137   306  1138 D CommandListener: Clearing all IP addresses on wlan0
,07-12 11:37:11.137   777  1329 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 11:37:11.157  6150  6150 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.157  6150  6150 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.167  6150  6150 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-12 11:37:11.207  6150  6150 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-12 11:37:11.237  6150  6150 D BtSettings.ProfileConfig: Adding GattService
,07-12 11:37:11.237  6150  6150 D BtSettings.ProfileConfig: Adding HeadsetService
,07-12 11:37:11.237  6150  6150 D BtSettings.ProfileConfig: Adding A2dpService
07-12 11:37:11.237  6150  6150 D BtSettings.ProfileConfig: Adding HidService
,07-12 11:37:11.237  6150  6150 D BtSettings.ProfileConfig: Adding HealthService
07-12 11:37:11.237  6150  6150 D BtSettings.ProfileConfig: Adding PanService
07-12 11:37:11.237   777  1329 D wifi    : Can not initialize the vendor function pointer table
07-12 11:37:11.237   777  1329 E WifiNative-HAL: Could not start hal
07-12 11:37:11.237   777  1329 E WifiStateMachine: Failed to start HAL
07-12 11:37:11.247  6150  6150 D BtSettings.ProfileConfig: Adding BluetoothMapService
,07-12 11:37:11.247  6150  6150 D BtSettings.ProfileConfig: Adding SapService
07-12 11:37:11.247  6150  6150 D BtSettings.ProfileConfig: Adding HeadsetClientService
,07-12 11:37:11.247  6150  6150 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-12 11:37:11.247  6150  6150 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-12 11:37:11.247   777  1329 E WifiHW  : supplicant_name : p2p_supplicant
,07-12 11:37:11.247   777  2212 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
07-12 11:37:11.247   777  2212 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.247   777  2212 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-12 11:37:11.247   777  2212 D SettingsProvider: selectionArgs: false
07-12 11:37:11.247   777  2212 D SettingsProvider: selectionArgs: 1002
07-12 11:37:11.247   777  2212 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-12 11:37:11.247   777  2212 D SettingsProvider: ret = -1
,07-12 11:37:11.247   777  1588 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-12 11:37:11.247   777  1588 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.247   777  1588 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:11.247   777  1588 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:11.247   777  1588 D SettingsProvider: selectionArgs: false
07-12 11:37:11.247   777  1588 D SettingsProvider: selectionArgs: 1002
,07-12 11:37:11.247   777  1588 D SettingsProvider: ret = -1
,07-12 11:37:11.247   777  2235 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-12 11:37:11.247   777  2235 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.247   777  2235 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:11.247   777  2235 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:11.247   777  2235 D SettingsProvider: selectionArgs: false
07-12 11:37:11.247   777  2235 D SettingsProvider: selectionArgs: 1002
,07-12 11:37:11.247   777  2235 D SettingsProvider: ret = -1
,07-12 11:37:11.247   777  1727 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
07-12 11:37:11.247   777  1727 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.247   777  1727 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:11.247   777  1727 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:11.247   777  1727 D SettingsProvider: selectionArgs: false
07-12 11:37:11.247   777  1727 D SettingsProvider: selectionArgs: 1002
07-12 11:37:11.247   777  1727 D SettingsProvider: ret = -1
,07-12 11:37:11.247   777  1420 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-12 11:37:11.247   777  1420 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.247   777  1420 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:11.247   777  1420 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:11.247   777  1420 D SettingsProvider: selectionArgs: false
07-12 11:37:11.247   777  1420 D SettingsProvider: selectionArgs: 1002
,07-12 11:37:11.247   777  1420 D SettingsProvider: ret = -1
07-12 11:37:11.247   777  1719 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
07-12 11:37:11.247   777  1719 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.247   777  1719 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:11.247   777  1719 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:11.247   777  1719 D SettingsProvider: selectionArgs: false
07-12 11:37:11.247   777  1719 D SettingsProvider: selectionArgs: 1002
,07-12 11:37:11.257   777  1719 D SettingsProvider: ret = -1
07-12 11:37:11.257   777  1421 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-12 11:37:11.257   777  1421 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.257   777  1421 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:11.257   777  1421 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:11.257   777  1421 D SettingsProvider: selectionArgs: false
07-12 11:37:11.257   777  1421 D SettingsProvider: selectionArgs: 1002
07-12 11:37:11.257   777  1421 D SettingsProvider: ret = -1
,07-12 11:37:11.257   777   790 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
07-12 11:37:11.257   777   790 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.257   777   790 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:11.257   777   790 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:11.257   777   790 D SettingsProvider: selectionArgs: false
07-12 11:37:11.257   777   790 D SettingsProvider: selectionArgs: 1002
07-12 11:37:11.257   777   790 D SettingsProvider: ret = -1
,07-12 11:37:11.257   777  1678 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:11.257   777  1678 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.257   777  1678 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:11.257   777  1678 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:11.257   777  1678 D SettingsProvider: selectionArgs: false
07-12 11:37:11.257   777  1678 D SettingsProvider: selectionArgs: 1002
07-12 11:37:11.257   777  1678 D SettingsProvider: ret = -1
,07-12 11:37:11.257   777   789 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:37:11.257   777   789 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:11.257   777   789 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:11.257   777   789 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:11.257   777   789 D SettingsProvider: selectionArgs: false
07-12 11:37:11.257   777   789 D SettingsProvider: selectionArgs: 1002
07-12 11:37:11.257   777   789 D SettingsProvider: ret = -1
,07-12 11:37:11.297  6150  6150 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 11:37:11.297  6150  6150 I bt_bluedroid: init
,07-12 11:37:11.297  6150  6175 I BluetoothAdapterState: Entering OffState
,07-12 11:37:11.307  6150  6176 E bt_core_counter: counter_init unable to open counter port
07-12 11:37:11.307  6150  6176 E bt_core_module: module_init failed to initialize "counter_module"
07-12 11:37:11.307  6150  6176 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-12 11:37:11.307  6150  6176 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 11:37:11.307  6150  6176 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 11:37:11.307  6150  6176 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 11:37:11.307  6150  6150 I bt_bluedroid: get_profile_interface socket
,07-12 11:37:11.307  6150  6150 W bt_btif : btif_get_adapter_property 2
07-12 11:37:11.307  6150  6150 W bt_btif : btif_get_adapter_property 1
,07-12 11:37:11.307  6150  6179 D BluetoothAdapterProperties: Address is:7C:F9:0E:34:8A:A0
07-12 11:37:11.307  6150  6179 E BluetoothServiceJni: populateRssiValuesNative
07-12 11:37:11.307  6150  6179 I bt_bluedroid: getModelRssiValues
07-12 11:37:11.307  6150  6179 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-12 11:37:11.307  6150  6179 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-12 11:37:11.307  6150  6150 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-12 11:37:11.307   777   777 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,07-12 11:37:11.307  6150  6179 D BluetoothAdapterProperties: Name is: S5-1
,07-12 11:37:11.317  6150  6150 I bt_bluedroid: get_profile_interface sdp
,07-12 11:37:11.317  6150  6169 I bt_bluedroid: config_hci_snoop_log
,07-12 11:37:11.317   777   909 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-12 11:37:11.327  6150  6175 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-12 11:37:11.327  6150  6175 D BluetoothAdapterProperties: Setting state to 14
07-12 11:37:11.327  6150  6175 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-12 11:37:11.327  6150  6175 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-12 11:37:11.327  6150  6175 D BluetoothAdapterService: updateAdapterState state is 14
,07-12 11:37:11.327  6150  6175 D BluetoothAdapterService: Autoconnection is available 
07-12 11:37:11.327  6150  6175 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
07-12 11:37:11.327   777   909 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
,07-12 11:37:11.327  6150  6175 D BluetoothSecureManager: getInstant: null
07-12 11:37:11.327  6150  6175 D BluetoothSecureManager: calling getMethod for getService
07-12 11:37:11.327  6150  6175 D BluetoothSecureManager: calling getService
,07-12 11:37:11.327  6150  6175 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@590d6b7
,07-12 11:37:11.337   777   789 D BluetoothSecureManagerService: isSecureModeEnabled
07-12 11:37:11.337   777   789 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
07-12 11:37:11.337  6150  6175 D BtConfig.SecureMode: isSecureModeOn:false
07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-12 11:37:11.337  6172  6172 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-12 11:37:11.337  6172  6172 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-12 11:37:11.337  6172  6172 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-12 11:37:11.337  6172  6172 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:11.337  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:37:11.337  6150  6175 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-12 11:37:11.337  6150  6175 D BluetoothBondStateMachine: make
,07-12 11:37:11.337  6150  6182 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 11:37:11.347  6150  6175 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:37:11.347  6150  6150 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,07-12 11:37:11.347   777  1329 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-12 11:37:11.357   777   777 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:37:11.357   777   777 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:37:11.357   777  1334 I WifiHs20Service: Message received 5011
,07-12 11:37:11.357  1386  1386 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:11.357  1386  1386 D STATUSBAR-WifiTile: Wifi onReceive(2)
,07-12 11:37:11.357   777  1337 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-12 11:37:11.357  5909  5909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:37:11.367  1706  1717 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-12 11:37:11.367  1386  1386 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=2
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:11.367  1386  1386 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:11.367  1706  1717 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:11.367   777  1337 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:11.367  1386  1386 D HotspotTile: onReceive : 2, 0
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:11.367   777  1718 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:11.367   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef0fd00 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b1e939 5909:com.test.thalitest/u0a4}
,07-12 11:37:11.367  6172  6172 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-12 11:37:11.367   391   391 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6172
07-12 11:37:11.367   391   391 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
07-12 11:37:11.367  6172  6172 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-12 11:37:11.367  6172  6172 I wpa_supplicant: ssSupport state is = 1
07-12 11:37:11.367  6172  6172 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-12 11:37:11.367  6172  6172 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-12 11:37:11.367   391   391 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6172
07-12 11:37:11.367   391   391 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
,07-12 11:37:11.377  6150  6150 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 11:37:11.377  6150  6150 D BtGatt.GattService: Received start request. Starting profile...
07-12 11:37:11.377  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
07-12 11:37:11.377  6150  6150 D BtGatt.GattService: start()
07-12 11:37:11.377  6150  6150 I bt_bluedroid: get_profile_interface gatt
,07-12 11:37:11.377  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
07-12 11:37:11.377  6150  6150 D BtGatt.AdvertiseManager: advertise manager created
07-12 11:37:11.377  6150  6150 D BtGatt.AdvertiseManager: start
,07-12 11:37:11.377  1386  2960 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-12 11:37:11.377  1386  1386 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-12 11:37:11.387  6172  6172 I SecureStorage: [INFO]: SPID(0x00000007)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,07-12 11:37:11.387  6184  6184 E Zygote  : v2
,07-12 11:37:11.387  6184  6184 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:11.387   777   861 I ActivityManager: Start proc 6184:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
07-12 11:37:11.387  6184  6184 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:11.387  6184  6184 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:37:11.387  6150  6150 D BtGatt.ScanManager: start
,07-12 11:37:11.387  6184  6184 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:11.387  6150  6150 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,07-12 11:37:11.397  6184  6184 E Zygote  : accessInfo : 0
,07-12 11:37:11.427  6184  6184 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:11.427  6184  6184 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:11.427  6150  6150 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,07-12 11:37:11.437   777  1719 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ef0fd00 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13edff5 6184:com.samsung.android.securitylogagent/1000}
,07-12 11:37:11.437  6150  6150 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
,07-12 11:37:11.437  6150  6150 E BtGatt.GattService: notifyProfileServiceStateChanged
07-12 11:37:11.437  6150  6150 E BluetoothAdapterService: handleMessage() - Message: 1
,07-12 11:37:11.437  6150  6150 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,07-12 11:37:11.437  6150  6150 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:11.437  6150  6150 V BluetoothAdapterState: isTurningOn()=false
,07-12 11:37:11.437  6150  6150 V BluetoothAdapterState: isBleTurningOn()=true
07-12 11:37:11.437  6150  6150 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:11.437  6150  6175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-12 11:37:11.437  6150  6175 I bt_bluedroid: enable
,07-12 11:37:11.437  6150  6176 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-12 11:37:11.437  6150  6176 I bt_hci  : start_up
,07-12 11:37:11.447  6184  6184 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package null
,07-12 11:37:11.447  6150  6176 I bt_vendor: alloc value 0xb2b65979
,07-12 11:37:11.447  6150  6176 I bt_vendor: init
07-12 11:37:11.447  6150  6176 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 11:37:11.447  6150  6176 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-12 11:37:11.447  6150  6176 D bt_vendor: op for 5
07-12 11:37:11.447  6150  6176 D bt_vendor: op for 0
,07-12 11:37:11.447  6150  6176 I bt_upio : upio_set_bluetooth_power(on: 0)
,07-12 11:37:11.447  6150  6176 D bt_upio : is_emulator_context : 0
07-12 11:37:11.447  6150  6176 D bt_upio : is_rfkill_disabled ? [0]
07-12 11:37:11.447  6150  6176 D bt_upio : is_rfkill_disabled ? [0]
,07-12 11:37:11.457  6150  6176 D bt_vendor: op for 0
,07-12 11:37:11.457  6150  6176 I bt_upio : upio_set_bluetooth_power(on: 1)
07-12 11:37:11.457  6150  6176 D bt_upio : is_emulator_context : 0
07-12 11:37:11.457  6150  6176 D bt_upio : is_rfkill_disabled ? [0]
07-12 11:37:11.457  1386  1386 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-12 11:37:11.457  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:11.457  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:11.457  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:11.457  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:11.457  6150  6176 D bt_hci  : start_up starting async portion
,07-12 11:37:11.457  6150  6208 I bt_hci  : event_finish_startup
07-12 11:37:11.457  6150  6208 I bt_hci_h4: hal_open
07-12 11:37:11.457  6150  6208 D bt_vendor: op for 3
07-12 11:37:11.457  6150  6208 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-12 11:37:11.457  6184  6184 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm
,07-12 11:37:11.457  6150  6208 I bt_userial_vendor: userial_vendor_open():UART is setup
07-12 11:37:11.457  6150  6208 I bt_userial_vendor: device fd = 60 open
,07-12 11:37:11.467  6150  6208 D bt_vendor: op for 1
07-12 11:37:11.467  6150  6208 E bt_hwcfg: Start CFG HW, HCI reset
,07-12 11:37:11.467   777   790 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:11.467  6184  6184 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-12 11:37:11.467  6184  6184 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-12 11:37:11.467  6184  6184 D SecurityLogAgent: StateMachine : Current State = 1
,07-12 11:37:11.477  6184  6184 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-12 11:37:11.487  6211  6211 E Zygote  : v2
,07-12 11:37:11.487  6211  6211 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:11.487   777  1589 I ActivityManager: Start proc 6211:tv.peel.smartremote/u0a170 for broadcast-5 tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver
07-12 11:37:11.487  6211  6211 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:11.487  6211  6211 I libpersona: KNOX_SDCARD checking this for 10170
07-12 11:37:11.487  6211  6211 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:11.487   777  1589 I ActivityManager: Killing 4900:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
07-12 11:37:11.487  6211  6211 E Zygote  : accessInfo : 0
07-12 11:37:11.487  6211  6211 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=tv.peel.smartremote 
,07-12 11:37:11.507   777  2222 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,07-12 11:37:11.517  6211  6211 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.517  6211  6211 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.517   777  1420 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ef0fd00 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b7dc56 6211:tv.peel.smartremote/u0a170}
,07-12 11:37:11.527  6211  6211 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,07-12 11:37:11.537  6150  6208 E bt_hwcfg: Read Local Name after HCI reset
,07-12 11:37:11.537   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{bef34d7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.567  6211  6211 W System  : ClassLoader referenced unknown path: /system/app/SmartRemote_KL/lib/arm
,07-12 11:37:11.567  6150  6208 D bt_hwcfg: Chipset BCM4350C0
07-12 11:37:11.567  6150  6208 D bt_hwcfg: Target name = [BCM4350C0]
,07-12 11:37:11.567  6150  6208 I bt_hwcfg: module_type[semco3rd].
07-12 11:37:11.567  6150  6208 I bt_hwcfg: module_type[semco3rd] is invalid.
07-12 11:37:11.567  6150  6208 E bt_hwcfg: patchram path ORG . BCM4350C0
07-12 11:37:11.567  6150  6208 E bt_hwcfg: patchram path ORG .. BCM4350C0
07-12 11:37:11.567  6150  6208 E bt_hwcfg: patchram path ORG libpn547_fw.so BCM4350C0
07-12 11:37:11.567  6150  6208 E bt_hwcfg: patchram path ORG bcm4350_V0353.0733_wisol.hcd BCM4350C0
07-12 11:37:11.567  6150  6208 E bt_hwcfg: patchram path ORG bcm4350_V0353.0727.hcd BCM4350C0
07-12 11:37:11.567  6150  6208 E bt_hwcfg: fw ver (org)0.0
,07-12 11:37:11.577  6150  6208 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-12 11:37:11.577  6150  6208 E bt_hwcfg: Remove module rev, try again BCM4350
07-12 11:37:11.577  6150  6208 D bt_hwcfg: Target name = [BCM4350]
07-12 11:37:11.577  6150  6208 I bt_hwcfg: module_type[semco3rd].
07-12 11:37:11.577  6150  6208 I bt_hwcfg: module_type[semco3rd] is invalid.
07-12 11:37:11.577  6150  6208 E bt_hwcfg: patchram path ORG . BCM4350
07-12 11:37:11.577  6150  6208 E bt_hwcfg: patchram path ORG .. BCM4350
07-12 11:37:11.577  6150  6208 E bt_hwcfg: patchram path ORG libpn547_fw.so BCM4350
07-12 11:37:11.577  6150  6208 E bt_hwcfg: patchram path ORG bcm4350_V0353.0733_wisol.hcd BCM4350
07-12 11:37:11.577  6150  6208 I bt_hwcfg: patch(org) : bcm4350_V0353.0733_wisol.hcd
07-12 11:37:11.577  6150  6208 E bt_hwcfg: Module type exists. Skip
07-12 11:37:11.577  6150  6208 E bt_hwcfg: patchram path ORG bcm4350_V0353.0727.hcd BCM4350
07-12 11:37:11.577  6150  6208 I bt_hwcfg: patch(org) : bcm4350_V0353.0727.hcd
07-12 11:37:11.577  6150  6208 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4350_V0353.0727.hcd
07-12 11:37:11.577  6150  6208 E bt_hwcfg: ORG patchram base 0353
07-12 11:37:11.577  6150  6208 E bt_hwcfg: ORG patchram minor 0727
07-12 11:37:11.577  6150  6208 E bt_hwcfg: fw ver (org)353.727
07-12 11:37:11.577  6150  6208 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4350_V0353.0727.hcd
,07-12 11:37:11.587  6150  6208 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-12 11:37:11.587   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{c3d31c4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.587   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{cd018ad: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.597  6150  6208 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-12 11:37:11.617  6211  6211 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:37:11.617  6211  6211 I MultiDex: install
07-12 11:37:11.617  6211  6211 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:37:11.657   391   391 I SecureStorage: [INFO]: SPID(0x00000007)Secure Storage Daemon finished processing with result: 0
,07-12 11:37:11.667  6172  6172 I SecureStorage: [INFO]: SPID(0x00000007)Processing data has been completed
,07-12 11:37:11.687  6172  6172 I wpa_supplicant: Ctrl_iface: loading system cred
,07-12 11:37:11.687  6172  6172 I SecureStorage: [INFO]: SPID(0x00000007)Checking if this device supports Secure Storage
,07-12 11:37:11.697   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{eed67e2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.697   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{b884773: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.707  6172  6172 I SecureStorage: [INFO]: SPID(0x00000007)This device supports Secure Storage
,07-12 11:37:11.707   391   391 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 1010, gid 1010, pid 6172
07-12 11:37:11.707   391   391 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x0000010C
07-12 11:37:11.707  6172  6172 I SecureStorage: [INFO]: SPID(0x00000007)SS Daemon is running
07-12 11:37:11.707  6172  6172 I wpa_supplicant: ssSupport state is = 1
,07-12 11:37:11.717  6172  6172 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-12 11:37:11.717  6172  6172 E wpa_supplicant: SIM READ ERROR
07-12 11:37:11.717  6172  6172 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-12 11:37:11.717  6172  6172 E wpa_supplicant: SIM READ ERROR
07-12 11:37:11.717  6172  6172 I wpa_supplicant: Blacklist: Clear (all) 
,07-12 11:37:11.717  6172  6172 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-12 11:37:11.717  6172  6172 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-12 11:37:11.717  6172  6172 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:37:11.747   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{4bda630: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.747   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{68292a9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.747   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{5fe202e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.747   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{c95e7cf: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.757   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{18ef55c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.757   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{9c8b065: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.757   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{350113a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.757   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{b3331eb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.757   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{4c40b48: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.767  6211  6211 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-12 11:37:11.767   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{498ede1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.767   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{a9e0706: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.767   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{1101c7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.767   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{cb293f4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.767   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{3d5871d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.777   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{e838d92: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.777   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{411f363: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.777   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{55efb60: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.777   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{6487819: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.787   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{dc8f0de: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.787   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{1a662bf: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.787   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{4a86d8c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.787   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{35f7cd5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.787   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{96f3cea: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.797   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{fe86bdb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.797   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{d34d678: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.797   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{1a81151: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.797   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{f7c3db6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.807  6211  6211 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,07-12 11:37:11.807   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{377eab7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.807   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{41ce224: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.807   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{90b718d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.807  6211  6211 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-12 11:37:11.807   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{6867f42: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.817   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{1167b53: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.817   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{557fc90: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.817   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{cca9989: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.817   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{6014d8e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.817  6211  6211 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 2474-2477)
07-12 11:37:11.817  6211  6211 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-12 11:37:11.827   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{e0379af: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.827   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{2e851bc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.827   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{93a4545: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.827   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{748b49a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.837   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{a1801cb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.837   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{ac6cda8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.837   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{b6d8066: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.837  6211  6211 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a7955b5}
07-12 11:37:11.837   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{fa2efa7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:11.837  6211  6211 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-12 11:37:11.837  6211  6211 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:37:11.847   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{f8f1c54: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.847   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{788d7fd: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.847   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{1c13cf2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.847   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{504df43: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:11.847  6211  6211 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-12 11:37:11.847   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{feba9c0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.857  6211  6211 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in tv.peel.smartremote rsrc of package null
07-12 11:37:11.857   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{f8ff6f9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.857   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{b22363e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.857   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{c0c2c9f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.857   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{8c1a1ec: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.867   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{25009b5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.867   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{607784a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.867   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{b10f3bb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.867   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{e1cf0d8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.877   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{2c48c31: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.877   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{f4ccf16: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.877   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{bd11097: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.877   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{6dc4284: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.877   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{e24ba6d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.887   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{3bec6a2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.887   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{c0c1f33: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.887   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{71d02f0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.887   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{3df9069: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.887   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{e66aaee: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.897   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{bdf7b8f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.897   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{5675e1c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.897   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{157ca25: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.897   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{f9687fa: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.897   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{5e241ab: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.907   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{69a4008: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.907   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{d5fe3a1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.907   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{8b529c6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.907   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{d014d87: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.907   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{c9754b4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.917   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{f7618dd: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.917   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{8ca1c52: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.917   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{c1b3b23: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.917   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{3af0820: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.917   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{ec065d9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.917   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{5c9ab9e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.927   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{35c667f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.927   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{acc864c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.927   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{4c88695: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.927   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{ea0e3aa: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.937   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{f5aeb9b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.937   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{261bb38: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.937   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{ff7f711: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.937   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{2019076: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.937   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{5f2a677: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.937   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{e1352e4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.947   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{1d3f34d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.947   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{5ee3e02: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.947   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{4e13313: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.947   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{524b950: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.957   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{4f97749: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.957   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{c06384e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.967   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{e21ed6f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.967   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{da41a7c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.967   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{6d93f05: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.967   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{e918b5a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.977   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{e09f18b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.977   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{e566268: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.977   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{133c681: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.977   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{24d0326: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.977   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{7241b67: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.987   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{3633d14: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.987   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{f5549bd: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.987   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{8f62bb2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.987   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{fcd0703: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.987   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{1c11680: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.997   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{b11c4b9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.997   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{9750fe: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.997   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{d8f105f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:11.997   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{5611aac: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.007   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{d80f375: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.007   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{b937f0a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.007   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{a3e537b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.007   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{61b3598: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.007   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{f7a51f1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.017   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{d7281d6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.017   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{ed4ac57: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.017   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{f5a1344: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.017   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{5d11c2d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.017   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{86ce562: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.027   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{db6f3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.027   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{6871fb0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.027   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{5504e29: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.027   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{7b7f5ae: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.027   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{8c2cf4f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.037   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{c3686dc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.037   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{a76a3e5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.037   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{291beba: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.037   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{e07116b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.037   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{41334c8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.047   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{f29961: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.047   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{40d0c86: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.047   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{9035947: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.047   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{f8ad574: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.047   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{6de6a9d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.057   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{39d6b12: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.057   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{29242e3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.057   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{739d4e0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.057   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{7bc1399: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.057   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{a63265e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.067   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{c9c2a3f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.067   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{f175f0c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.067   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{b315055: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.067   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{1374a6a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.067   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{5332b5b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.067   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{1615ff8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.077   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{3839cd1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.077   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{377a336: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.077   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{f6f2237: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.077   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{c4883a4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.077   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{7d4350d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.087   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{292bcc2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.087   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{e09aad3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.087   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{e5c3610: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.087   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{61c1509: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.087   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{653e30e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.087   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{bba212f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.097   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{db6a33c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.097   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{8e7f8c5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.097   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{5ef221a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.097   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{d51a14b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.097   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{5e8b728: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.107   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{cd45c41: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.107   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{5cd45e6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.107   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{9970727: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.107   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{8a61dd4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.107   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{1c97b7d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.117   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{617da72: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.117   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{2e2eec3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.117   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{d314340: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.117   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{3f75279: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.117   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{e052bbe: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.127   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{e7bb41f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.127   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{a87536c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.127   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{8919d35: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.127   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{fe445ca: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.127   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{5b1733b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.127   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{84c3a58: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.137   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{a4bd7b1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.137   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{1e8f496: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.137   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{cba0817: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.137   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{276a404: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.137   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{1953ded: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.147   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{7b7c422: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.147   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{b4d0eb3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.147   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{bbbfc70: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.147   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{494cbe9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.147   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{8b2006e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.157   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{2ffe30f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.157   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{abc6f9c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.157   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{ae53da5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.157   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{f01b57a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.157   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{f61a12b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.167   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{deee988: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.167   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{1110f21: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.167   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{b65af46: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.167   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{bd72507: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.167   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{24d1634: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.177   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{7ce7c5d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.177   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{9bd79d2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.177   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{b370aa3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.177   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{8bf61a0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.177   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{afb8159: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.177   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{255611e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.187   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{d25adff: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.187   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{648f7cc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.187   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{c59da15: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.187   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{3f2712a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.187   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{d312b1b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.197   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{af3c4b8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.197   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{e0b0291: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.197   777  3287 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,07-12 11:37:12.197  2664  2664 D ContentApp:  LEVEL : -1
,07-12 11:37:12.197   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{29e75f6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.207   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ad5df7 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ef1e04 5672:com.sec.android.app.videoplayer/u0a53}
,07-12 11:37:12.207  5672  5672 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,07-12 11:37:12.207  5672  5672 D TranscodeReceiver:  SIOP_LEVEL: -1
,07-12 11:37:12.207   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{b7c7464: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.217   777  3287 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.217   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{8cc36cd: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.217   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{733fb82: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.217   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{4fe293: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.217   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{9be72d0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.227   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{9f272c9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.227   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{baa4dce: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.227   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{68c14ef: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.227   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{7dfebfc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.227   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{5267285: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.227   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{2178da: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.237   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{3af110b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.237   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{23dcbe8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.237   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{5e0b201: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.237   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{4ae48a6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.247   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{ebbb2e7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.247   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{c17be94: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.247   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{ca56d3d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.247   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{3e64932: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.247   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{2069683: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.247   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{afc3000: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.257   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{400a039: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.257   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{a2bc67e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.257   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{e9217df: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.257   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{cf44c2c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.267   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{94206f5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.267   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{5b9cc8a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.267  6150  6208 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 11:37:12.267  6150  6208 I bt_hwcfg: FW Download delta = 726023
07-12 11:37:12.267  6150  6208 D bt_hwcfg: Settlement delay -- 100 ms
07-12 11:37:12.267  6150  6208 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 11:37:12.267   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{92a52fb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.267   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{56fff18: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.267   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{4f91d71: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.267   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{b702756: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.277   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{d4123d7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.277   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{cf1f4c4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.277   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{f311fad: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.277   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{c5f62e2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.277   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{18a2673: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.277   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{f7b9930: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.277   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{b6d09a9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.287   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{814cb2e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.287   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{a56b6cf: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.287   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{5b9185c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.287   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{8639765: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.287   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{7a66c3a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.297   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{5b1f0eb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.297   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{4ed5e48: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.297   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{f7b44e1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.297   306  1131 D Netd    : Iface wlan0 link up
,07-12 11:37:12.297   777   866 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:12.297   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{d7f1206: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.297   777   866 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:12.297   306  1131 D Netd    : Iface wlan0 link up
,07-12 11:37:12.307   777   909 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
,07-12 11:37:12.307   777   909 D Tethering: NAP Supported and not Wifi Model
,07-12 11:37:12.307   777   866 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:12.307   777   866 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:12.307   777   909 E Tethering: No numeric data
,07-12 11:37:12.307  6211  6234 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,07-12 11:37:12.307   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{23eaf19: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.307   777   909 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-12 11:37:12.307   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{4605bde: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.307  1386  1386 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-12 11:37:12.307  1386  1386 D HotspotTile: updateTetherState():false, false
,07-12 11:37:12.317   777  1326 D NtpTrustedTime: forceRefresh: no connectivity
,07-12 11:37:12.317   777  1326 V NetworkStats: performPollLocked(flags=0x1)
,07-12 11:37:12.317   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4b8f1bf u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{69758ba 777:system/1000}
,07-12 11:37:12.317  6211  6211 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-12 11:37:12.317  6211  6211 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-12 11:37:12.317  6211  6211 I Adreno-EGL: Build Date: 01/28/16 Thu
07-12 11:37:12.317  6211  6211 I Adreno-EGL: Local Branch: ss
07-12 11:37:12.317  6211  6211 I Adreno-EGL: Remote Branch: 
07-12 11:37:12.317  6211  6211 I Adreno-EGL: Local Patches: 
07-12 11:37:12.317  6211  6211 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:37:12.317   777  1326 V NetworkStats: performPollLocked() took 6ms
,07-12 11:37:12.317   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{521508c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.327   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{e0223d5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.327   777  1327 D NtpTrustedTime: forceRefresh: no connectivity
,07-12 11:37:12.327   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{99257ea: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.327   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{314eadb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.327   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{fd8e978: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.327   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{14e2851: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.327  6211  6211 D libEGL  : eglInitialize EGLDisplay = 0xbebce23c
,07-12 11:37:12.337   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{e3608b6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.337   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{66d59b7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.337   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{86f2524: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.337   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{27bf88d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.337   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{e91fa42: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.337   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{f73da53: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.347   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{b6f90: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.347   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{a3c9089: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.347   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{2c9788e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.347   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{e57c8af: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.347   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{dff4bc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.357   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{154ac45: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.357   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{fe88f9a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.357   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{ce240cb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.357   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{415a0a8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.357   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{e18c7c1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.367   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{db00b66: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.367   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{e521ea7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.367   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{a781f54: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.367   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{da91efd: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.367   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{d2177f2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.367  6150  6208 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-12 11:37:12.367   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{f7fe43: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.377   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{3e1dcc0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.377   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{4edadf9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.377   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{bcb213e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.377   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{d923b9f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.377   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{16804ec: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.377   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{55230b5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.387   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{fd4134a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.387   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{8c81a16: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.387   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{829ff97: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.387   777  1589 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10170
,07-12 11:37:12.387   777  1589 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
07-12 11:37:12.387   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{684fe33: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.387   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{a85f5f0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.397   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{3990769: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.397   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{ca055ee: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.397   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{e874a8f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.397   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{1ec811c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.397   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{8b1b125: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.407   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{f3fe2fa: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.407   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{cb800ab: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.417   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{9ce9308: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.417   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{df13aa1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.417   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{91934c6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.417   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{2e3d752: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.417   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{209da23: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.427   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{8babb20: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.427  6172  6172 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-12 11:37:12.427  6172  6172 I SecureStorage: [INFO]: SPID(0x00000007)Checking if this device supports Secure Storage
,07-12 11:37:12.437   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{60694c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.447   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{5ea2d95: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.447   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{4d6feaa: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.447  6172  6172 I SecureStorage: [INFO]: SPID(0x00000007)This device supports Secure Storage
,07-12 11:37:12.447   391   391 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 1010, gid 1010, pid 6172
07-12 11:37:12.447   391   391 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x0000010C
07-12 11:37:12.447  6172  6172 I SecureStorage: [INFO]: SPID(0x00000007)SS Daemon is running
07-12 11:37:12.447  6172  6172 I wpa_supplicant: ssSupport state is = 1
,07-12 11:37:12.447   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{a032c50: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.447  6172  6172 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-12 11:37:12.447   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{ba6e49: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.457   306  1131 D Netd    : Iface p2p0 link up
,07-12 11:37:12.457   777   866 D Tethering: interfaceLinkStateChanged p2p0, true
07-12 11:37:12.457   777   866 D Tethering: interfaceStatusChanged p2p0, true
,07-12 11:37:12.457   306  1131 D Netd    : Iface p2p0 link up
,07-12 11:37:12.457   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{271634e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.457   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{2dd3c6f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.457   777   866 D Tethering: interfaceLinkStateChanged p2p0, true
07-12 11:37:12.457   777   866 D Tethering: interfaceStatusChanged p2p0, true
,07-12 11:37:12.457   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{d76bd7c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.457   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{332a605: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.467  6211  6211 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-12 11:37:12.467   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{804665a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.467   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{4ab308b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.467   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{c303568: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.467   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{73c9d81: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.467   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{f928e26: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.467  6150  6208 I bt_hwcfg: vendor lib fwcfg completed
07-12 11:37:12.467  6150  6208 I bt_vendor: firmware callback
07-12 11:37:12.467  6150  6208 I bt_hci  : firmware_config_callback
,07-12 11:37:12.477   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{1a4a67: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.477  6150  6256 I bt_btu_task: Bluetooth chip preload is complete
,07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_HCI
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_BNEP
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_BTIF
07-12 11:37:12.477  6150  6256 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-12 11:37:12.477   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{874014: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.477   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{29490bd: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.477  6211  6211 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 11:37:12.477  6211  6211 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
07-12 11:37:12.477  6211  6211 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-12 11:37:12.477   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{c8966b2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.477  6211  6211 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-12 11:37:12.477   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{3772603: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.487   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{a24980: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.487   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{7e7bb9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.487   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{9a33bfe: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.487  6211  6211 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-12 11:37:12.487   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{b3c1f5f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.487  6211  6211 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 11:37:12.487  6211  6211 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-12 11:37:12.487  6211  6211 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
07-12 11:37:12.487   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{ca27dac: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.487  6211  6211 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-12 11:37:12.487   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{2821a75: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.497   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{f31a0a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.497   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{72d527b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.497   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{38fc898: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.497   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{e6e8f1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.497   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{8b0ccd6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.507   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{5349b57: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.507   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{b04d644: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.507   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{6f0232d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.507   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{c4e062: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.507   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{dfd95f3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.507   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{59b12b0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.517   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{6d8c529: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.517  6211  6211 I ClientConfig: Set OkHttp cache (max size: 52MB) to /data/user/0/tv.peel.smartremote/cache/peel-cache
,07-12 11:37:12.517   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{d14a0ae: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.517   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{f519e4f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.517   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{416a9dc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.517   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{18f8ae5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.527   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{88e19ba: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.527  6172  6172 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
07-12 11:37:12.527   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{33d06b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.527   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{d5287c8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.527   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{e32f061: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.527   777  1329 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-12 11:37:12.527   777  1329 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,07-12 11:37:12.527   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{cf41786: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.537   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{abd0847: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.537   777  1329 D WifiNative-wlan0: callSECApiBoolean - ID [301]
07-12 11:37:12.537  6172  6172 I wpa_supplicant: HOTSPOT20_ENABLE called ON
07-12 11:37:12.537  6172  6172 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-12 11:37:12.537  6172  6172 E wpa_supplicant: SIM READ ERROR
07-12 11:37:12.537  6172  6172 I wpa_supplicant: Blacklist: Clear (all) 
,07-12 11:37:12.537   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{8ec5874: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.537   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{d4d319d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.537   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{b6a2612: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.537   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{7b7e1e3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.547   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{8b087e0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.547  6172  6172 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-12 11:37:12.547   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{3d04a99: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.547  6172  6172 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,07-12 11:37:12.547   777  1329 D WifiNative-wlan0: callSECApiInt - ID [210]
,07-12 11:37:12.547   777   777 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:37:12.547   777   777 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:12.547   777  1334 I WifiHs20Service: Message received 5011
07-12 11:37:12.557  1386  1386 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:37:12.557   777  1331 D HS20StateMachine: WIFI_STATE_ENABLED
07-12 11:37:12.557  1386  1386 D STATUSBAR-WifiTile: Wifi onReceive(3)
07-12 11:37:12.557  1386  1386 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:12.557  1386  1386 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=3
07-12 11:37:12.557  1386  2960 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-12 11:37:12.557   777  1331 D HS20StateMachine: reloadCredentialsToSupplicant
07-12 11:37:12.557  1386  1386 D HotspotTile: onReceive : 3, 0
,07-12 11:37:12.557  1386  1386 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-12 11:37:12.557   777  1331 D HotspotDBHandler: getCredentialIds
,07-12 11:37:12.557   777  1337 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-12 11:37:12.557   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1c0915e u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b1e939 5909:com.test.thalitest/u0a4}
,07-12 11:37:12.557  1706  1948 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-12 11:37:12.557   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{7fcb93f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.557  1706  1948 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-12 11:37:12.557   777  1337 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-12 11:37:12.567  5909  5909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:12.567  5909  5909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:12.567  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:12.567  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:37:12.567  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:12.567  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:37:12.567  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:12.567  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:12.567  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:37:12.567   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{cc6420c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.567  5909  5909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:12.567  5909  5909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:37:12.567   777  1718 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.567   777  1718 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.567   777  1718 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.577   777  1718 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.577  6265  6265 E Zygote  : v2
07-12 11:37:12.577  6265  6265 I libpersona: KNOX_SDCARD checking this for 10202
07-12 11:37:12.577  6265  6265 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:12.577  6265  6265 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:12.577  6265  6265 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:12.577   777  1718 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:12.577  6265  6265 E Zygote  : accessInfo : 0
07-12 11:37:12.577  6172  6172 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
07-12 11:37:12.577  6265  6265 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
07-12 11:37:12.577   777  1329 D WifiConfigStore: Loading config and enabling all networks 
,07-12 11:37:12.577   777  1331 I ActivityManager: Start proc 6265:com.samsung.hs20provider/u0a202 for content provider com.samsung.hs20provider/.Hs20Provider
,07-12 11:37:12.577   777  1718 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:12.577   777  1718 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:12.577   777  1718 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:12.577   777  1718 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.577   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{9d1f755: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.587   777  1718 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:12.587   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{880656a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.587   777  1718 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:12.587   777  1718 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:12.587   777  1718 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.587   777  1718 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.587   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{78daa5b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.587   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1c0915e u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13edff5 6184:com.samsung.android.securitylogagent/1000}
,07-12 11:37:12.597   777  1329 I WifiConfigStore: "NG700" is a verified password AP: true
07-12 11:37:12.597   777  1329 E WifiConfigStore: Not a HS20
,07-12 11:37:12.597   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{e9b72f8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.597   777  1727 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.597  6184  6184 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-12 11:37:12.597  6184  6184 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-12 11:37:12.597  6184  6184 D SecurityLogAgent: StateMachine : Current State = 1
07-12 11:37:12.597  6184  6184 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-12 11:37:12.597   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{907b3d1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.597   777  1329 D WifiConfigStore: loaded 0 passpoint configs
07-12 11:37:12.607   777  1329 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-12 11:37:12.607   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{5b76e36: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.607   777  1329 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-12 11:37:12.607   777  1329 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-12 11:37:12.607   777  1329 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-12 11:37:12.607   777   777 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,07-12 11:37:12.607   777   777 D WifiHs20Service: reason: 2
07-12 11:37:12.607   777  1334 I WifiHs20Service: Message received 5014
07-12 11:37:12.607   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{6729137: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.607   777  1334 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,07-12 11:37:12.607   777  1334 E WifiHs20Service: The changed config is NULL
,07-12 11:37:12.607   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{e90c6a4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.617   777  1329 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,07-12 11:37:12.617   777  1329 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-12 11:37:12.617  6265  6265 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:12.617  6265  6265 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:12.617   777  1329 D WifiNative-wlan0: callSECApiBoolean - ID [13]
07-12 11:37:12.617  6172  6172 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-12 11:37:12.617  6172  6172 I wpa_supplicant: resume autoscan
07-12 11:37:12.617  6172  6172 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-12 11:37:12.617  6172  6172 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-12 11:37:12.617  6172  6172 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-12 11:37:12.617  6172  6172 I wpa_supplicant: reset timer : RESET_TIMER 0
07-12 11:37:12.617  6172  6172 I wpa_supplicant: P2P: Current p2p state = IDLE
07-12 11:37:12.617  6172  6172 I wpa_supplicant: First Scan Start
,07-12 11:37:12.627   777  2235 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1c0915e u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b7dc56 6211:tv.peel.smartremote/u0a170}
,07-12 11:37:12.627  6172  6172 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-12 11:37:12.627   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{702bc0d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.637  6265  6265 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package null
,07-12 11:37:12.637   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{8437c2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.637   777  1329 D WifiNative-wlan0: Setting external_sim to 1
07-12 11:37:12.637   777  1329 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
07-12 11:37:12.637   777  1329 D WifiStateMachine: Setting OUI to DA-A1-19
,07-12 11:37:12.637  6172  6172 I wpa_supplicant: bt_status is set be DISCONNECTED
,07-12 11:37:12.647   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{35509d3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.647   777  1329 E WifiNative-wlan0: do suspend true
,07-12 11:37:12.647   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{65a910: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.647  6265  6265 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm
,07-12 11:37:12.647  1386  1386 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02061d/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f02017c/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-12 11:37:12.647   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{72c0c09: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.647  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:12.657  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:12.657  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:12.657  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:12.657   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{1620e0e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.657   777  1329 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
07-12 11:37:12.657   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{3dc702f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.657   777  1328 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-12 11:37:12.657   306  1138 D CommandListener: Setting iface cfg
07-12 11:37:12.657   306  1138 D CommandListener: Trying to bring up p2p0
,07-12 11:37:12.657   777  1328 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-12 11:37:12.657   777  1328 D SecContentProvider: insert(), uri = 2
,07-12 11:37:12.657   777   777 D RttService: SCAN_AVAILABLE : 3
07-12 11:37:12.657   777  1357 E WifiScanningService: could not start HAL
,07-12 11:37:12.667   777  1328 D WifiP2pService: P2pEnablingState
,07-12 11:37:12.667   777  1358 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-12 11:37:12.667   777  1328 D WifiP2pService: P2pEnablingState{ what=147457 }
,07-12 11:37:12.667   777  1328 D WifiP2pService: P2p socket connection successful
,07-12 11:37:12.667   777  1328 D WifiP2pService: P2pEnabledState
07-12 11:37:12.667   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{805fc5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.667   777  1328 D SecContentProvider: insert(), uri = 2
,07-12 11:37:12.667   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{b34fd1a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.667   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{6c9e04b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.667   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{b4d8a28: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.677   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{30c3341: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.677   777  1329 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-12 11:37:12.677   777  1329 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
07-12 11:37:12.677   777  1329 D WifiStateMachine: setFccChannelNative: channel = 0
07-12 11:37:12.677   777  1329 D WifiNative-wlan0: callSECApiInt - ID [230]
,07-12 11:37:12.677   777  1328 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,07-12 11:37:12.677   777   777 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-12 11:37:12.677   777   912 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-12 11:37:12.677  6265  6277 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:12.677  6265  6277 D HotspotProvider: CREDENTIAL
,07-12 11:37:12.677  6265  6277 D HotspotProvider: No prepend tags
,07-12 11:37:12.677   777   912 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-12 11:37:12.677   777   912 D WifiDisplayController: disconnect
07-12 11:37:12.677   777   912 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-12 11:37:12.677  1386  1386 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-12 11:37:12.687   777  1328 D WifiP2pService: create mNetworkAgent
,07-12 11:37:12.687   777  1420 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-12 11:37:12.687   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{bd43627: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.687  1386  1386 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-12 11:37:12.687   777  1331 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
07-12 11:37:12.687   777  1331 D HS20StateMachine: enter : DiscoveringState
,07-12 11:37:12.687   777  1328 D P2pNetworkAgent: NetworkAgent: Registering NetworkAgent
,07-12 11:37:12.697   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{b0520d4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.697   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{927c27d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.697   777  1329 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-12 11:37:12.697   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{9fd7640: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.697  6150  6256 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
07-12 11:37:12.697  6150  6256 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb2ab9269
07-12 11:37:12.697  6150  6256 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb2ab9269 
07-12 11:37:12.697  6150  6256 E bt_btm  : btm_ble_set_search_if search_if=4
,07-12 11:37:12.697   777  1329 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-12 11:37:12.697   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{937723b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.697   777  1328 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:12.707   777  1336 D ConnectivityService: Got NetworkAgent Messenger
,07-12 11:37:12.707   777  1336 E ConnectivityService: updateNetworkInfo()
,07-12 11:37:12.707   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{5a76eb1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.707   777  1336 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-12 11:37:12.707   777  1336 D ConnectivityService: NetworkAgent connected
,07-12 11:37:12.707   777   912 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:12.707   777  1336 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 13
,07-12 11:37:12.707  6172  6172 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,07-12 11:37:12.707  6150  6179 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 28928 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 1024 mIsExtendedScanSupported = false mIsDebugLogSupported = false mAobleSupported = 0
07-12 11:37:12.707  6172  6172 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,07-12 11:37:12.707   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{9ea3f96: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.707   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{c20f717: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.717  1706  2486 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-12 11:37:12.717   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{81c6704: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.717  6150  6179 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,07-12 11:37:12.717  6150  6179 D bt_hci  : do_postload posting postload work item
,07-12 11:37:12.717  6150  6208 I bt_hci  : event_postload
07-12 11:37:12.717  6150  6208 D bt_vendor: op for 2
07-12 11:37:12.717  6150  6208 D bt_hwcfg: hw_sco_config
07-12 11:37:12.717  6150  6208 I bt_vendor: sco_config_cb
07-12 11:37:12.717  6150  6208 I bt_hci  : sco_config_callback postload finished.
07-12 11:37:12.717  6150  6208 D bt_vendor: op for 6
07-12 11:37:12.717  6150  6208 D bt_upio : upio_set : pio 2 action 2, polarity 0
07-12 11:37:12.717  6150  6179 E bt_btif_sock: btif_sock_init: !vhci_init
,07-12 11:37:12.717  6150  6179 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
07-12 11:37:12.717  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.717  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.717  6150  6208 D bt_upio : upio_start_stop_timer : timer_settime success
07-12 11:37:12.717  6150  6208 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-12 11:37:12.717  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.717  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.717  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.717  6211  6211 I Fabric  : Initializing Crashlytics 2.3.2.56
07-12 11:37:12.717   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{c9344ed: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.717  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.717  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.717  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.717  6150  6179 D bt_bte_conf: Device ID record 1 : primary
07-12 11:37:12.717  6150  6179 D bt_bte_conf:   vendorId            = 0075
,07-12 11:37:12.717  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.717  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.717  6150  6208 D bt_upio : BT_WAKE is asserted already
07-12 11:37:12.717  6150  6179 D bt_bte_conf:   vendorIdSource      = 0001
,07-12 11:37:12.717  6150  6179 D bt_bte_conf:   product             = 0100
07-12 11:37:12.717  6150  6179 D bt_bte_conf:   version             = 0200
07-12 11:37:12.717  6150  6179 D bt_bte_conf:   clientExecutableURL = 
07-12 11:37:12.717  6150  6179 D bt_bte_conf:   serviceDescription  = 
,07-12 11:37:12.727  6150  6179 D bt_bte_conf:   documentationURL    = 
07-12 11:37:12.727  6150  6179 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 11:37:12.727  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.727  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.727  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.727  6150  6176 D bt_stack_manager: event_start_up_stack finished
07-12 11:37:12.727  6150  6179 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
,07-12 11:37:12.727  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.727  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.727  6150  6208 D bt_upio : BT_WAKE is asserted already
07-12 11:37:12.727  6150  6179 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 7
,07-12 11:37:12.727  6150  6179 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24844
07-12 11:37:12.727  6150  6179 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4354 37.4MHz SEMCO-B80 K-LTE-0353
07-12 11:37:12.727  6150  6179 D BluetoothDataManager: firmwareVersion from Property : bcm4350_V0353.0727.hcd
07-12 11:37:12.727  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.727  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.727  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.727  6150  6179 E BluetoothAdapterState: stateChangeCallback : 1
07-12 11:37:12.727  6150  6175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,07-12 11:37:12.727  6150  6208 I bt_vendor: low_power_mode_cb
07-12 11:37:12.727  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.727  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.727  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.727  6150  6175 D BluetoothAdapterProperties: Setting state to 15
07-12 11:37:12.727  6150  6175 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-12 11:37:12.727  6150  6175 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-12 11:37:12.727  6150  6175 D BluetoothAdapterService: updateAdapterState state is 15
,07-12 11:37:12.727  6150  6175 D BluetoothAdapterService: Autoconnection is available 
07-12 11:37:12.727  6150  6175 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-12 11:37:12.727  6150  6175 I BluetoothAdapterState: Entering BleOnState
,07-12 11:37:12.727   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{97aef70: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.737   777   909 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-12 11:37:12.737   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{eec42e9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.737   777   909 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-12 11:37:12.737  6150  6175 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,07-12 11:37:12.737  6150  6175 D BluetoothAdapterProperties: Setting state to 11
07-12 11:37:12.737  6150  6175 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 11:37:12.737  6150  6175 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-12 11:37:12.737  6150  6175 D BluetoothAdapterService: updateAdapterState state is 11
,07-12 11:37:12.737   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{31ab6e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.737  6150  6175 D BluetoothAdapterService: Autoconnection is available 
07-12 11:37:12.737  6150  6175 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-12 11:37:12.737  6150  6175 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:12.737  6150  6175 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-12 11:37:12.737  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-12 11:37:12.747   777   909 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
,07-12 11:37:12.747  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-12 11:37:12.747  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.747  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.747  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.747  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.747  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.747  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.747  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.747  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.747  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.747  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.747  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.747  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.747   777   777 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:12.747   777   777 I InputMethodManagerService: [BT Setting State] State =11
,07-12 11:37:12.747  6150  6208 D bt_vendor: op for 7
07-12 11:37:12.747  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:12.747  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:12.747  6150  6150 D HeadsetService: Received start request. Starting profile...
07-12 11:37:12.747  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
,07-12 11:37:12.747  6150  6150 D HeadsetProvider: make
07-12 11:37:12.747  6150  6150 D HeadsetProvider: HeadsetProvider
,07-12 11:37:12.747  6150  6150 I HeadsetProvider: clearAllHeadsetSettings(0)
,07-12 11:37:12.757  1761  1761 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:37:12.757   777   777 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,07-12 11:37:12.757   777   777 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:37:12.757   777   777 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-12 11:37:12.757  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-12 11:37:12.757   777  1328 E WifiP2pService: Failed to set my phone number info into probe response
,07-12 11:37:12.767   777  2222 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,07-12 11:37:12.767   777   789 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-12 11:37:12.767  1386  1386 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:37:12.767  1386  1386 D BluetoothTile:  getBluetoothState : 11
,07-12 11:37:12.767  1386  1386 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 )
,07-12 11:37:12.777   777  1328 D WifiNative-p2p0: p2pGetDeviceAddress
,07-12 11:37:12.777   777  1328 D WifiNative-p2p0: p2pGetDeviceAddress returning ee:1f:72:63:11:86
,07-12 11:37:12.777  6150  6150 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 11:37:12.777  6150  6150 D HeadsetStateMachine: make
,07-12 11:37:12.777  6150  6150 E HeadsetStateMachine: # of Max HF connection is 2
,07-12 11:37:12.777  1934  1934 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-12 11:37:12.777  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-12 11:37:12.777   777  1328 D WifiP2pService: DeviceAddress: ee:11:86
,07-12 11:37:12.787   777   912 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] S5-1
07-12 11:37:12.787   777   912 D WifiDisplayController:  deviceAddress: ee:1f:72:63:11:86
07-12 11:37:12.787   777   912 D WifiDisplayController:  primary type: 10-0050F204-5
07-12 11:37:12.787   777   912 D WifiDisplayController:  secondary type: null
07-12 11:37:12.787   777   912 D WifiDisplayController:  wps: 0
07-12 11:37:12.787   777   912 D WifiDisplayController:  grpcapab: 0
07-12 11:37:12.787   777   912 D WifiDisplayController:  devcapab: 0
07-12 11:37:12.787   777   912 D WifiDisplayController:  status: 3
07-12 11:37:12.787   777   912 D WifiDisplayController:  wfdInfo: null
07-12 11:37:12.787   777   912 D WifiDisplayController:  groupownerAddress: null
07-12 11:37:12.787   777   912 D WifiDisplayController:  GOdeviceName: null
07-12 11:37:12.787   777   912 D WifiDisplayController:  interfaceAddress: 
07-12 11:37:12.787   777   912 D WifiDisplayController:  SConnectInfo : null
07-12 11:37:12.787   777   912 D WifiDisplayController:  contactInfoHash : null
07-12 11:37:12.787   777   912 D WifiDisplayController:  ssDevInfo : 0
07-12 11:37:12.787   777   912 D WifiDisplayController:  iconIdx : 0
,07-12 11:37:12.787  1386  2960 D BluetoothTile:  handleUpdatestate:false name:null
,07-12 11:37:12.787   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{a3d34d2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.787  1386  2960 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-12 11:37:12.787  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-12 11:37:12.797  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-12 11:37:12.797  1386  1386 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-12 11:37:12.807  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-12 11:37:12.807   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{f12dacc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.807   777  1328 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-12 11:37:12.807  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:12.807  6150  6175 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:12.807  6150  6175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:37:12.807  6150  6175 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:37:12.807  6150  6175 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:37:12.807  6150  6150 I bt_bluedroid: get_profile_interface handsfree
07-12 11:37:12.807   777  1328 D WifiP2pService: InactiveState
07-12 11:37:12.807   777  1328 D P2pNetworkAgent: NetworkAgent: NetworkAgent fully connected
,07-12 11:37:12.807   777  1336 E ConnectivityService: updateNetworkInfo()
,07-12 11:37:12.817   777  1328 D WifiP2pService: InactiveState{ what=143376 }
07-12 11:37:12.817   777  1336 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
07-12 11:37:12.817   777  1328 D WifiP2pService: P2pEnabledState{ what=143376 }
07-12 11:37:12.817   777  1328 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,07-12 11:37:12.817   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{9f8d7b8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.817   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{fe1991: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.817   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{f2140f6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.827   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{737ccf7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.827  6150  6150 I DualScoManager: Instantiating Dual Sco Manager
07-12 11:37:12.827  6150  6150 I DualScoManager: Set HeadsetServiceHelper
,07-12 11:37:12.827  6150  6150 D BluetoothAtMessage: createCMTIContentObservers
,07-12 11:37:12.827   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{13fb764: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.837   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{d59bdcd: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.837   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{987682: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.847   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{f924193: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.847  6150  6150 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@49989f
,07-12 11:37:12.847  6150  6150 D HeadsetProvider: setHeadsetDB - Can't find 300 for 7C:F9:0E:34:8A:XX
,07-12 11:37:12.847   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{bf2e5d0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.857  6211  6211 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10170, CallingPid : 6211
,07-12 11:37:12.857   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{4688efc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.857   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{efdd985: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.857   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{c3a53da: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.857   777  1727 D ConnectivityService: listenForNetwork for Listen from uid/pid:10170/6211 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:12.867  6150  6150 I HeadsetProvider: setHeadsetDB - 7C:F9:0E:34:8A:XX, 300, 1, true
,07-12 11:37:12.867   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{efe500b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.867   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{22d9ee8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.867   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{3478901: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.877   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{8f9d3a6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.877  6211  6260 E Fabric  : Error performing auto configuration.
07-12 11:37:12.877  6211  6260 E Fabric  : java.util.concurrent.ExecutionException: java.lang.IllegalStateException: Invalid format of fabric file,.fabric/
07-12 11:37:12.877  6211  6260 E Fabric  : 	at java.util.concurrent.FutureTask.report(FutureTask.java:94)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at java.util.concurrent.FutureTask.get(FutureTask.java:164)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at a.a.a.a.u.c(Onboarding.java:105)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at a.a.a.a.u.f(Onboarding.java:45)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at a.a.a.a.p.a(InitializationTask.java:63)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at a.a.a.a.p.a(InitializationTask.java:28)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at a.a.a.a.a.c.c.call(AsyncTask.java:311)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at java.lang.Thread.run(Thread.java:818)
07-12 11:37:12.877  6211  6260 E Fabric  : Caused by: java.lang.IllegalStateException: Invalid format of fabric file,.fabric/
07-12 11:37:12.877  6211  6260 E Fabric  : 	at a.a.a.a.k.a(FabricKitsFinder.java:91)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at a.a.a.a.k.a(FabricKitsFinder.java:58)
07-12 11:37:12.877  6211  6260 E Fabric  : 	at a.a.a.a.k.call(FabricKitsFinder.java:35)
07-12 11:37:12.877  6211  6260 E Fabric  : 	... 4 more
,07-12 11:37:12.877   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{93fe1e7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.887   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{6b1c194: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.887   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{f22b43d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.887  6150  6150 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@cc4d44a
,07-12 11:37:12.887  6150  6150 D HeadsetProvider: setHeadsetDB - Can't find 400 for 7C:F9:0E:34:8A:XX
,07-12 11:37:12.887   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{8df8432: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.887   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{21eb583: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.897   777  2235 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8b36300 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
,07-12 11:37:12.897  4959  4959 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
,07-12 11:37:12.897  4959  4959 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
07-12 11:37:12.897   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{e8b5739: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.907  6150  6150 I HeadsetProvider: setHeadsetDB - 7C:F9:0E:34:8A:XX, 400, 1, true
,07-12 11:37:12.907   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{4fdb17e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.907  6150  6285 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-12 11:37:12.907  6150  6150 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-12 11:37:12.907  6150  6150 E HeadsetService: notifyProfileServiceStateChanged
,07-12 11:37:12.907   777   777 D BluetoothA2dp: Proxy object connected
,07-12 11:37:12.907  2183  2183 D BluetoothA2dp: Proxy object connected
,07-12 11:37:12.907  4959  4959 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,07-12 11:37:12.907  6150  6150 D A2dpService: Received start request. Starting profile...
07-12 11:37:12.907   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{33f678a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.907  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
07-12 11:37:12.907  6150  6285 D HeadsetStateMachine: Clear mHeadsetBrsf
,07-12 11:37:12.907  6150  6285 D HeadsetStateMachine: map size, before remove : 0
07-12 11:37:12.907  6150  6285 D HeadsetStateMachine: map size, after remove: 0
,07-12 11:37:12.917  6150  6150 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-12 11:37:12.917  4959  4959 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-12 11:37:12.917  6150  6150 I bt_bluedroid: get_profile_interface avrcp
,07-12 11:37:12.917   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{b347256: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.927  6150  6150 I Avrcp   : No of Audio players :: 2
,07-12 11:37:12.927  6150  6150 I Avrcp   : App Package name is GM
,07-12 11:37:12.927   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{4af12d7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.927  6150  6150 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-12 11:37:12.927   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{f92b7c4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.927  4959  4959 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-12 11:37:12.927   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{b0e26ad: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.927   777  1718 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.937   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{b9d5de2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.937  4959  4959 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-12 11:37:12.937  6150  6150 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-12 11:37:12.937  6150  6150 I Avrcp   : App Package name is SM
,07-12 11:37:12.937  6150  6150 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungMusic_20_M/SamsungMusic_20_M.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-12 11:37:12.937   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{3680573: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.937  6150  6150 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,07-12 11:37:12.937   777  1589 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.937   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{ee58c30: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.937  4959  4959 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-12 11:37:12.937  4959  4959 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-12 11:37:12.937  4959  4959 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-12 11:37:12.937  6150  6150 I Avrcp   : No of Video players :: 2
07-12 11:37:12.937  6150  6150 I Avrcp   : Video App Package name is others
,07-12 11:37:12.937  6150  6150 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-12 11:37:12.947  6150  6150 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,07-12 11:37:12.947  6150  6150 I Avrcp   : Video App Package name is others
,07-12 11:37:12.957  6150  6150 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-12 11:37:12.957  6150  6150 V Avrcp   : MediaPlayerInfo: mPlayerId=4
,07-12 11:37:12.957  6150  6150 I Avrcp   : Add tempPlayer
07-12 11:37:12.957  6150  6150 V Avrcp   : MediaPlayerInfo: mPlayerId=5
07-12 11:37:12.957  6150  6150 V Avrcp   : no_of_players : 5
07-12 11:37:12.957  6150  6150 I Avrcp   : Total no of players: 5
07-12 11:37:12.957  6150  6150 V Avrcp   : swapping the samsung player with 1st player
,07-12 11:37:12.957  6150  6150 D Avrcp   : Compose Browsing Service Candidate
,07-12 11:37:12.957  6150  6150 D Avrcp   : ResolveInfo info ResolveInfo{4cffc97 com.google.android.music/.browse.MediaBrowserService m=0x108000}
,07-12 11:37:12.957  6150  6150 D Avrcp   : Initialize Media Controller
,07-12 11:37:12.957  4959  6294 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-12 11:37:12.957  6150  6150 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-12 11:37:12.967   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{d4f3b5c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.967  6150  6150 E Avrcp   : getActiveSessions
,07-12 11:37:12.967  6150  6150 D Avrcp   : pick active media Controller
,07-12 11:37:12.967  6150  6150 D Avrcp   : Get the active Media Controller 
,07-12 11:37:12.967  6150  6150 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 11:37:12.967  6150  6150 D A2dpStateMachine: make
,07-12 11:37:12.967  6150  6150 I bt_bluedroid: get_profile_interface a2dp
,07-12 11:37:12.967  6150  6150 E bt_btif : warning : media task started media_task_refcnt 1 
07-12 11:37:12.967  6150  6150 E bt_btif : warning : no command pending, ignore ack
,07-12 11:37:12.977  6150  6299 D A2dpStateMachine: Enter Disconnected: -2
,07-12 11:37:12.977  6211  6220 W art     : Suspending all threads took: 21.526ms
,07-12 11:37:12.977   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8b36300 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2dc201e 5364:com.samsung.android.app.FileShareServer/5005}
,07-12 11:37:12.977  5364  5364 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-12 11:37:12.977   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{342b148: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.977  6150  6150 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-12 11:37:12.977  6150  6150 E A2dpService: notifyProfileServiceStateChanged
07-12 11:37:12.977  6150  6150 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 11:37:12.987  6150  6150 D HidService: Received start request. Starting profile...
,07-12 11:37:12.987  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
07-12 11:37:12.987  6150  6150 I bt_bluedroid: get_profile_interface hidhost
07-12 11:37:12.987  6150  6150 D HidService: setHidService(): set to: null
07-12 11:37:12.987  6150  6150 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
,07-12 11:37:12.987  6150  6150 E HidService: notifyProfileServiceStateChanged
07-12 11:37:12.987   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{b199be1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:12.987  6150  6150 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-12 11:37:12.987  6150  6150 D HealthService: Received start request. Starting profile...
,07-12 11:37:12.987  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
07-12 11:37:12.987   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{86c1d06: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.987  5364  5364 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-12 11:37:12.987  5364  5364 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-12 11:37:12.987  5364  5364 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-12 11:37:12.987  5364  5364 W System.err: 	at com.samsung.android.app.FileShareServer.ServerBroadcastReceiver.onReceive(ServerBroadcastReceiver.java:34)
07-12 11:37:12.987  5364  5364 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3634)
07-12 11:37:12.987  5364  5364 W System.err: 	at android.app.ActivityThread.access$2000(ActivityThread.java:221)
07-12 11:37:12.987  5364  5364 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1876)
07-12 11:37:12.987  5364  5364 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:12.987  5364  5364 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-12 11:37:12.987  5364  5364 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-12 11:37:12.987  5364  5364 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:12.987  5364  5364 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-12 11:37:12.987  5364  5364 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-12 11:37:12.987   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{f845fc7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.987  6150  6150 I bt_bluedroid: get_profile_interface health
,07-12 11:37:12.987  6150  6150 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
07-12 11:37:12.987  6150  6150 E HealthService: notifyProfileServiceStateChanged
,07-12 11:37:12.987  6150  6150 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,07-12 11:37:12.987   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{b7599f4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:12.987   777   777 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:37:12.997   777  2231 I ActivityManager: Killing 4923:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,07-12 11:37:12.997  6150  6150 D PanService: Received start request. Starting profile...
07-12 11:37:12.997  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
,07-12 11:37:12.997  6150  6150 D BluetoothPanServiceJni: initializeNative(L118): pan
07-12 11:37:12.997  6150  6150 I bt_bluedroid: get_profile_interface pan
,07-12 11:37:12.997  6150  6150 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
,07-12 11:37:12.997  6150  6150 E PanService: notifyProfileServiceStateChanged
,07-12 11:37:13.017   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{a5d3163: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.017   777  2222 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44c6160 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
,07-12 11:37:13.027   777  1589 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,07-12 11:37:13.047   777   861 I ActivityManager: Start proc 6308:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,07-12 11:37:13.047  6308  6308 E Zygote  : v2
07-12 11:37:13.047  6308  6308 I libpersona: KNOX_SDCARD checking this for 5005
07-12 11:37:13.047  6308  6308 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:13.047  6308  6308 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:13.047  6308  6308 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:13.047  6308  6308 E Zygote  : accessInfo : 0
,07-12 11:37:13.047  6308  6308 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
07-12 11:37:13.047   777  1420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44c6160 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d29fce 2183:com.samsung.android.providers.context/u0a174}
,07-12 11:37:13.057   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{c06338c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.067   777  1300 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44c6160 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74eac8c 1852:com.sec.android.app.shealth:remote/u0a34}
,07-12 11:37:13.077   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{8b03f51: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.077  6150  6150 D BluetoothMapService: Received start request. Starting profile...
,07-12 11:37:13.077  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
,07-12 11:37:13.087  6308  6308 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:13.087  6308  6308 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:13.087   777  2231 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44c6160 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
,07-12 11:37:13.087  6150  6150 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
07-12 11:37:13.087  6150  6150 E BluetoothMapService: notifyProfileServiceStateChanged
,07-12 11:37:13.087  6150  6150 D HeadsetStateMachine: Try to query the phonestate on bind
,07-12 11:37:13.097  4959  4959 D BluetoothNotiBroadcastReceiver: onReceive
,07-12 11:37:13.097   777  1718 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 11:37:13.097   777  1718 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,07-12 11:37:13.097  6150  6150 V SapService: SapBinder()
,07-12 11:37:13.097   777  1421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44c6160 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a073ef 1386:com.android.systemui/u0a58}
,07-12 11:37:13.107  6150  6150 D SapService: Received start request. Starting profile...
07-12 11:37:13.107  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
07-12 11:37:13.107  6150  6150 V SapService: start()
,07-12 11:37:13.107  6150  6150 D SapService: Disable sap : false
,07-12 11:37:13.107  1386  1386 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:13.107  1386  1386 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-12 11:37:13.107   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{56ae290: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.107  6150  6150 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
07-12 11:37:13.107   777  2222 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8b36300 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84397bc 6308:com.samsung.android.app.FileShareClient/5005}
,07-12 11:37:13.107  6150  6150 E SapService: notifyProfileServiceStateChanged
,07-12 11:37:13.107  6150  6150 D HeadsetStateMachine: Proxy object connected
,07-12 11:37:13.117   777  1718 I ActivityManager: Killing 4486:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,07-12 11:37:13.117  6150  6150 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,07-12 11:37:13.117  6150  6150 D HeadsetPhoneState: sendDeviceDataStateChanged
07-12 11:37:13.117  6150  6285 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-12 11:37:13.117  6150  6285 E HeadsetStateMachine: Unknown message: 11
07-12 11:37:13.117  6150  6285 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-12 11:37:13.117  6150  6285 E HeadsetStateMachine: Unknown message: 19
,07-12 11:37:13.117  6150  6150 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-12 11:37:13.117  6150  6150 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:13.117  6150  6150 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,07-12 11:37:13.117  6150  6150 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:13.117  6150  6150 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:13.117  6150  6150 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:13.117  6150  6150 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:37:13.117  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:37:13.117  6150  6150 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:13.117  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-12 11:37:13.117  6150  6285 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 11:37:13.117  6150  6285 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-12 11:37:13.117  6150  6285 E HeadsetStateMachine: Unknown message: 11
,07-12 11:37:13.117  6150  6150 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
,07-12 11:37:13.117  6308  6308 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package null
,07-12 11:37:13.127  6150  6150 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:37:13.127  6150  6150 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:13.127  6150  6150 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:13.127  6150  6150 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:13.127  6150  6150 E BluetoothAdapterService: handleMessage() - Message: 1
,07-12 11:37:13.127  6150  6150 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
,07-12 11:37:13.127  6150  6150 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:13.127   777  1421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44c6160 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{19eb859 6150:com.android.bluetooth/1002}
,07-12 11:37:13.127  6150  6150 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:13.127  6150  6150 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:13.127  6150  6150 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:13.127  6150  6150 D BluetoothAdapterService: HID Host service started
,07-12 11:37:13.137   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{46b1345: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.137  6150  6150 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,07-12 11:37:13.137  6150  6150 E BluetoothAdapterService: handleMessage() - Message: 1
,07-12 11:37:13.137  6150  6150 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:13.137  6150  6150 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:13.137  6150  6150 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:37:13.137  6150  6150 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 11:37:13.137  6150  6150 D HeadsetPhoneState: sendDeviceDataStateChanged
07-12 11:37:13.137  6150  6285 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-12 11:37:13.137  6150  6285 E HeadsetStateMachine: Unknown message: 11
07-12 11:37:13.137  6150  6285 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-12 11:37:13.137  6150  6285 E HeadsetStateMachine: Unknown message: 19
,07-12 11:37:13.137  6150  6150 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-12 11:37:13.137  6150  6150 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:13.137  6150  6150 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:37:13.137  6150  6150 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:13.137  6150  6150 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:13.137  6150  6150 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:37:13.147  6150  6175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-12 11:37:13.147   777   790 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,07-12 11:37:13.147  6308  6308 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm
,07-12 11:37:13.147  6308  6308 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-12 11:37:13.157  6150  6175 E BluetoothServiceJni: enableBrEdrNative:
07-12 11:37:13.157  6150  6175 I bt_bluedroid: enable_bredr
,07-12 11:37:13.157   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{dd46a9a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.157  6308  6308 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,07-12 11:37:13.167  6321  6321 E Zygote  : v2
07-12 11:37:13.167  6321  6321 I libpersona: KNOX_SDCARD checking this for 10121
07-12 11:37:13.167  6321  6321 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:13.167   777  1588 I ActivityManager: Start proc 6321:com.google.android.apps.maps/u0a121 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
07-12 11:37:13.167  6321  6321 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:13.167  6321  6321 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:13.167  6321  6321 E Zygote  : accessInfo : 0
,07-12 11:37:13.167  6321  6321 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,07-12 11:37:13.177  6150  6179 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xb2a8e929
07-12 11:37:13.177  6150  6179 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
,07-12 11:37:13.177  6150  6179 D BluetoothAdapterProperties: Address is:7C:F9:0E:34:8A:A0
07-12 11:37:13.177  6150  6179 E BluetoothServiceJni: populateRssiValuesNative
07-12 11:37:13.177  6150  6179 I bt_bluedroid: getModelRssiValues
07-12 11:37:13.177  6150  6179 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-12 11:37:13.177  6150  6179 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-12 11:37:13.177  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.177  6150  6179 D BluetoothAdapterProperties: Name is: S5-1
07-12 11:37:13.177  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.177  6150  6208 D bt_upio : BT_WAKE is asserted already
07-12 11:37:13.177   777   777 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,07-12 11:37:13.177  6150  6256 D         : Codec ==> copy capability info [bta_av_co_audio_init:584]
07-12 11:37:13.177  6150  6179 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-12 11:37:13.177  6150  6179 D BluetoothAdapterProperties: Scan Mode:20
07-12 11:37:13.177  6150  6179 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:37:13.177  6150  6179 E bt_btif : btif_handle_bluetooth_enable_evt
07-12 11:37:13.177  6150  6179 E bt_btif : ANT+ socket does not initialize.
,07-12 11:37:13.177  6150  6208 D bt_vendor: op for 7
,07-12 11:37:13.177  5909  5909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 11:37:13.177  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.177  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.177  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.177  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.177  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.177  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.177  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.177  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.177   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{9087fcb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.177  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.177  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.177  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.177  6150  6179 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-12 11:37:13.187  6150  6179 D IOP_DB_BT: db_open: db_open : handle 2997002256l, read 17911 bytes onto local cache
07-12 11:37:13.187  6150  6179 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
07-12 11:37:13.187  6150  6179 D IOP_DB_BT: db_query: result 1
,07-12 11:37:13.187  6150  6179 I         : iop_db_open: iop_db_open status 0
07-12 11:37:13.187  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.187  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.187   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{19073a8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.187  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.187  6150  6179 E BluetoothAdapterState: stateChangeCallback : 17
07-12 11:37:13.187  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.187  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.187  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.187  6150  6179 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 11:37:13.187  6150  6175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,07-12 11:37:13.187   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{9ae9ec1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.187  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.187  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.187  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.187  6150  6175 D BluetoothAdapterProperties: ScanMode =  20
07-12 11:37:13.187  6150  6175 D BluetoothAdapterProperties: State =  11
,07-12 11:37:13.187  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.187  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.187  6150  6208 D bt_upio : BT_WAKE is asserted already
07-12 11:37:13.187   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{dfe9666: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.187  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.187  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.187  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.187   777  1727 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-12 11:37:13.187   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{1d4da7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.187   777  1718 D SecContentProvider: insert(), uri = 2
,07-12 11:37:13.187  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.187  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.187  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.197  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.197   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{4d2254: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.197  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.197  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.197  6172  6172 I wpa_supplicant: nl80211: Received scan results (3 BSSes)
07-12 11:37:13.197  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.197  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.197  6150  6208 D bt_upio : BT_WAKE is asserted already
07-12 11:37:13.197  6172  6172 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-12 11:37:13.197  6172  6172 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-12 11:37:13.197  6172  6172 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-12 11:37:13.197  6172  6172 I wpa_supplicant:    allow  - level is under -85dBm [-44] or selected nid [-1] [0]
,07-12 11:37:13.197  6172  6172 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
07-12 11:37:13.197  6172  6172 I wpa_supplicant:    allow  - level is under -85dBm [-44] or selected nid [-1] [0]
07-12 11:37:13.197  6172  6172 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz level=-44) 
,07-12 11:37:13.197  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.197  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.197  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.197  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.197  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.197  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.197  6150  6175 D BluetoothAdapterProperties: Setting state to 12
07-12 11:37:13.197  6150  6175 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-12 11:37:13.197  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.197  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.197  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.197   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{24565fd: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.197  6150  6179 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-12 11:37:13.197  6150  6179 D BluetoothAdapterProperties: Scan Mode:21
07-12 11:37:13.197   306  1131 D Netd    : Iface wlan0 link up
07-12 11:37:13.197  6150  6179 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:37:13.197   777   866 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:13.197   777   866 D Tethering: interfaceStatusChanged wlan0, true
07-12 11:37:13.207  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.207  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.207  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.207   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{b4db2f2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.207  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.207  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.207  6150  6208 D bt_upio : BT_WAKE is asserted already
07-12 11:37:13.207  5909  5909 D BluetoothAdapter: STATE_ON
,07-12 11:37:13.207  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.207  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.207  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.207  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.207  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.207  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.207  5909  5909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-12 11:37:13.207   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{5c71d43: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.207   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{5840fc0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.207  5909  5909 D BluetoothAdapter: STATE_ON
,07-12 11:37:13.217   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{48764f9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.217  5909  5909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:13.217  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:13.217  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 11:37:13.217  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:13.217  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:37:13.217  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:13.217  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:13.217  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:37:13.217   777  1329 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-12 11:37:13.217  6150  6175 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-12 11:37:13.217   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{c3e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.217  6150  6175 D BluetoothAdapterService: updateAdapterState state is 12
,07-12 11:37:13.217  5909  5909 D BluetoothAdapter: STATE_ON
,07-12 11:37:13.217  5909  5909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:37:13.227   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{67a67ec: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.227  6150  6175 V BluetoothAdapterService: start opp service
,07-12 11:37:13.227   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{a5057b5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.227  6308  6308 D FileShare-Client: Outbound.stopDelayTimer - 
,07-12 11:37:13.237  6150  6150 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-12 11:37:13.237  6150  6150 I BluetoothPbapService: Handler(): got msg=1
,07-12 11:37:13.237   777  2235 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-12 11:37:13.237  6321  6321 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:13.237  6321  6321 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:13.237  6150  6175 D BluetoothAdapterService: Autoconnection is available 
,07-12 11:37:13.237   777   909 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.237  6150  6175 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-12 11:37:13.237   777   909 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:13.237  6150  6175 D BluetoothAdapterService: starting service from this receiver
,07-12 11:37:13.237   777  2222 I ActivityManager: Killing 4779:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,07-12 11:37:13.247  6150  6336 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-12 11:37:13.247   777  1719 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44c6160 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{59c16d8 6321:com.google.android.apps.maps/u0a121}
,07-12 11:37:13.247   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{b4f6516: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.257  6150  6175 D BluetoothAdapterService: BT on, init HID DEV count : 0
,07-12 11:37:13.257  6150  6175 I BluetoothAdapterState: Entering OnState
,07-12 11:37:13.257   777   909 D BluetoothPan: onBluetoothStateChange on: true
,07-12 11:37:13.257  2183  2200 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-12 11:37:13.257  2183  2200 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:13.257   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{20c86d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.257  2183  2214 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-12 11:37:13.257  2119  2133 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.257  2119  2133 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:13.257  6150  6336 D BluetoothSocket: bindListen(): myUserId = 0
,07-12 11:37:13.257  6211  6222 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.257  6211  6222 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:13.257  6150  6336 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:13.257  6021  6032 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.257  6021  6032 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:13.257   777   909 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-12 11:37:13.257  6150  6170 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.257  6150  6170 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-12 11:37:13.257  6150  6336 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
07-12 11:37:13.257  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.257  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.257  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.257   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{c54bca2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.257  6150  6150 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-12 11:37:13.257  6150  6150 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-12 11:37:13.257  1695  1709 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.257  1695  1709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:13.257  6150  6150 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-12 11:37:13.257  6150  6150 W System.err: 	at com.android.bluetooth.opp.BluetoothOppService.onCreate(BluetoothOppService.java:195)
07-12 11:37:13.257  6150  6150 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3807)
07-12 11:37:13.257  6150  6150 W System.err: 	at android.app.ActivityThread.access$2100(ActivityThread.java:221)
07-12 11:37:13.257  6150  6150 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1882)
07-12 11:37:13.257  6150  6150 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:13.257  6150  6150 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-12 11:37:13.257  6150  6150 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-12 11:37:13.257  6150  6150 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:13.257  6150  6150 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-12 11:37:13.257  6150  6150 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,07-12 11:37:13.267  6150  6150 V BtOppService: isOwner == true
,07-12 11:37:13.267  1852  1862 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.267  1852  1862 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-12 11:37:13.267  1386  2060 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.267  1386  2060 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-12 11:37:13.267  5909  5920 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.267  5909  5920 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-12 11:37:13.267  1706  2486 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:13.267  1706  2486 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-12 11:37:13.267   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{8d9dd33: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.267   777   777 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:13.267   777   777 I InputMethodManagerService: [BT Setting State] State =12
07-12 11:37:13.267   777   777 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-12 11:37:13.267  6321  6321 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.google.android.apps.maps rsrc of package null
,07-12 11:37:13.267  1934  1934 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-12 11:37:13.267  1761  1761 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:37:13.277   777   777 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 11:37:13.277   777   777 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,07-12 11:37:13.277   777   777 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-12 11:37:13.277   777   777 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:13.277   777   777 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-12 11:37:13.277   777  1727 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,07-12 11:37:13.277   777  2235 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
07-12 11:37:13.277  1386  1386 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:13.277  1386  1386 D BluetoothTile:  getBluetoothState : 12
,07-12 11:37:13.277  1386  1386 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,07-12 11:37:13.287   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{ddda41c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.287   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{9079825: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.287   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{b3e91a1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.297  1386  2960 D BluetoothTile:  handleUpdatestate:false name:null
,07-12 11:37:13.297  6172  6172 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
07-12 11:37:13.297   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{b6b847f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.297   306  1131 D Netd    : Iface wlan0 link up
07-12 11:37:13.297   306  1131 D Netd    : Iface wlan0 link up
07-12 11:37:13.297   306  1131 D Netd    : Iface wlan0 link up
,07-12 11:37:13.297   777   866 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:13.297   777   866 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:13.297  6172  6172 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-12 11:37:13.297  6172  6172 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,07-12 11:37:13.297  6172  6172 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,07-12 11:37:13.297   777   866 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:13.297   777   866 D Tethering: interfaceStatusChanged wlan0, true
07-12 11:37:13.297   777  1727 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
07-12 11:37:13.297   777   866 D Tethering: interfaceLinkStateChanged wlan0, true
,07-12 11:37:13.297   777   866 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:13.307   777  1329 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-12 11:37:13.307   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{8604c4c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.307   777  1329 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-12 11:37:13.307  6172  6172 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,07-12 11:37:13.317  6172  6172 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
07-12 11:37:13.317   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{707d495: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.317  6172  6172 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-12 11:37:13.317  6172  6172 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-12 11:37:13.317  6172  6172 I wpa_supplicant: Blacklist: Clear (temp) 
07-12 11:37:13.317   306  1131 D Netd    : Iface wlan0 link up
,07-12 11:37:13.317   777   866 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:13.317   777   866 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:13.317   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{15919aa: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.327   777  1329 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-12 11:37:13.327  6341  6341 E Zygote  : v2
,07-12 11:37:13.327   777  1727 I ActivityManager: Start proc 6341:com.android.email/u0a162 for content provider com.android.email/.provider.EmailProvider
07-12 11:37:13.327   777  1327 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-12 11:37:13.327  6341  6341 I libpersona: KNOX_SDCARD checking this for 10162
,07-12 11:37:13.327  6341  6341 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:13.327  6341  6341 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:37:13.327  6341  6341 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:13.327  6321  6321 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-12 11:37:13.327  6341  6341 E Zygote  : accessInfo : 0
,07-12 11:37:13.327  6341  6341 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.email 
,07-12 11:37:13.327   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{c3de99b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.337   777  1329 V AlarmManager:  remove PendingIntent] PendingIntent{c6be138: PendingIntentRecord{1de2511 android broadcastIntent}}
,07-12 11:37:13.337   777   777 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-12 11:37:13.337   777   777 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:13.337   777   777 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-12 11:37:13.337   777  1329 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,07-12 11:37:13.337   777  1334 I WifiHs20Service: Message received 5007
,07-12 11:37:13.337   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{7072676: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.347   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{1078477: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.347   777  1329 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:13.347   777  1336 D ConnectivityService: Got NetworkAgent Messenger
07-12 11:37:13.347   777  1336 E ConnectivityService: updateNetworkInfo()
07-12 11:37:13.347   777  1336 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:13.347   777  1336 D ConnectivityService: NetworkAgent connected
,07-12 11:37:13.347   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{6880d05: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.347   306  1138 D CommandListener: Setting iface cfg
,07-12 11:37:13.347   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{2c3415a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.347   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{a86f8b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.347   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{a360868: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.357   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{82c7967: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.357   777  1329 D WifiStateMachine: Start Dhcp Watchdog 1
,07-12 11:37:13.357   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{878517b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.357   777  1329 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-12 11:37:13.357   777  1327 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:37:13.367  6341  6341 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:13.367  6341  6341 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:13.367   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{98b2a2d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.377   777   777 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@fc974f3
,07-12 11:37:13.377   777   777 D BluetoothHeadset: registerMessageListener
,07-12 11:37:13.377   777  1329 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,07-12 11:37:13.377   777  1336 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
07-12 11:37:13.377   777  1336 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,07-12 11:37:13.377   777  1336 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-12 11:37:13.377   777  1329 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-12 11:37:13.387  6150  6287 D HeadsetService: registerMessageListener
,07-12 11:37:13.387  6341  6341 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in com.android.email rsrc of package null
,07-12 11:37:13.387  6150  6287 D HeadsetService: registerMessageListener
07-12 11:37:13.387  6150  6285 D HeadsetStateMachine: Disconnected process message: 70, size: 0
07-12 11:37:13.387  6150  6285 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@9600311
,07-12 11:37:13.387   777   777 I Telecom : BluetoothManager : register MessageListener
07-12 11:37:13.387   777   777 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,07-12 11:37:13.387   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{15b05b0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.387  6150  6170 D A2dpStateMachine: getConnectedDevices : size=0
,07-12 11:37:13.397   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{59d3c29: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.397   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{cfd4bae: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.407   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{b7c6d4f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.407   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{762ccdc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.407   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{da471e5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.407   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{5d674ba: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.407   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{5bc8f6b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.417   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{cbddac8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.417   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{42f4761: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.417   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{5e72286: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.417   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{992b747: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.427   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{f39db74: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.427   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{c37f89d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.427   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{802e112: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.427   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{fb980e3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.427   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{9d33ae0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.437   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{4208199: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.437   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{ea9fc5e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.437   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{7f9483f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.437   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{8e1250c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.447   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{46e9e55: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.447   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{215806a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.447   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{c44295b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.447   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{50185f8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.447   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{e47cad1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.457   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{3033936: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.457   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{9920037: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.457   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{c509a4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.457   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{5ad430d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.467   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{e41b2c2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.467   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{a7c68d3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.467   777  2212 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:13.467   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{51b1c10: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.467   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{3780309: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.467   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{cfc390e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.477   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{f9abf2f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.477   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{87de93c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.477   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{b14c6c5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.477   777  1329 E WifiNative-wlan0: do suspend false
,07-12 11:37:13.477   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{dc6d81a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.477  1386  1386 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02061d/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f02017c/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-12 11:37:13.477  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:13.477  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:13.477  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:13.477  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:13.477   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{19e1f4b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.487   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{cde5d28: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.487   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{a41: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.487   777  1328 D WifiP2pService: InactiveState{ what=143375 }
,07-12 11:37:13.487   777  1328 D WifiP2pService: P2pEnabledState{ what=143375 }
07-12 11:37:13.487   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{26a5be6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.487   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{92d6527: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.497   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{5023d4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.497   777   790 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:13.507   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{702097d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.507   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{e705072: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.507   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{8812cc3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.517   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{c75a940: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.517   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{f2ac079: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.517  6357  6357 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-12 11:37:13.517   777  1719 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:13.517  6357  6357 I dhcpcd  : version 5.5.6 starting
07-12 11:37:13.517  6150  6281 D bt_upio : ..proc_btwrite_timeout..
07-12 11:37:13.517  6150  6281 D bt_upio : upio_set : pio 0 action 1, polarity 1
07-12 11:37:13.517   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{e8deb35: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.517   777  1727 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:13.517   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{157bca: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.517  6357  6357 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-12 11:37:13.527   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{d19713b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.527   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{2f76058: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.527   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{ebf05b1: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.527   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{2f78a96: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.527   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{5a3e617: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.537   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{3ae2a04: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.547   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{50d4bed: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.547   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{a19ba22: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.547   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{bf6ccb3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.547   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{fe5e270: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.557   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{27fb9e9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.557   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{e3d566e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.557   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{787810f: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.557   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{e9eb59c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.557   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{7910ba5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.567   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{ec6b7a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.567   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{7c51f2b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.567   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{4af8f88: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.567   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{7abbd21: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.577   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{45c546: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.577   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{9f48307: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.577   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{b721c34: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.587   777  2222 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-12 11:37:13.597   777  1678 I ActivityManager: Start proc 6370:com.sec.android.provider.badge/u0a77 for content provider com.sec.android.provider.badge/.BadgeProvider
,07-12 11:37:13.597  6370  6370 E Zygote  : v2
,07-12 11:37:13.597  6370  6370 I libpersona: KNOX_SDCARD checking this for 10077
07-12 11:37:13.597  6370  6370 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:13.597  6370  6370 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:37:13.597  6370  6370 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:13.597  6370  6370 E Zygote  : accessInfo : 0
,07-12 11:37:13.597  6370  6370 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,07-12 11:37:13.607   777  1718 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:13.607   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{8660a5d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.607   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{b88efd2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.607   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{cc48a3: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.617   777  1727 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:13.617   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{62ec7a0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.617  6150  6375 D BluetoothSocket: bindListen(): myUserId = 0
,07-12 11:37:13.617  6150  6375 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:13.617  6150  6375 I BtOppRfcommListener: Accept thread started.
,07-12 11:37:13.617  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.617  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.617  6150  6208 D bt_upio : upio_start_stop_timer : timer_settime success
07-12 11:37:13.617  6150  6208 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-12 11:37:13.627   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{87def59: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.627   777  1420 I ActivityManager: Killing 5381:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,07-12 11:37:13.637  6150  6150 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
07-12 11:37:13.637   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{462371e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.637  6150  6387 D BluetoothSocket: bindListen(): myUserId = 0
07-12 11:37:13.637  6150  6387 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:13.637  6150  6387 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,07-12 11:37:13.637  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.637  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.637  6150  6208 D bt_upio : BT_WAKE is asserted already
07-12 11:37:13.637  6150  6387 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-12 11:37:13.637  6150  6150 D BluetoothSocket: bindListen(): myUserId = 0
07-12 11:37:13.637  6150  6150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:13.637  6357  6357 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-12 11:37:13.637  6357  6357 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,07-12 11:37:13.647   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{9d0cbff: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.647  6357  6357 I dhcpcd  : bssid match
,07-12 11:37:13.647  6357  6357 I dhcpcd  : wlan0: rebinding lease of 192.168.1.123
,07-12 11:37:13.647   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{248bdcc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.647   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{a952815: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.647  6150  6150 D BluetoothSocket: bindListen(): myUserId = 0
,07-12 11:37:13.647  6150  6150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:13.657  6150  6150 D ObexServerSockets: Succeed to create listening sockets 
07-12 11:37:13.657  6150  6150 D ObexServerSockets: startAccept()
,07-12 11:37:13.657  6150  6388 D ObexServerSockets: Accepting socket connection for masId0
,07-12 11:37:13.657   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{8f6a72a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.657  6150  6389 D ObexServerSockets: Accepting socket connection for masId0
,07-12 11:37:13.667   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{c70291b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.667  6150  6150 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-12 11:37:13.667  6150  6150 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-12 11:37:13.667  6150  6150 D BluetoothSdpJni: SDP Create record success - handle: 1
07-12 11:37:13.667  6150  6208 D bt_vendor: op for 7
07-12 11:37:13.667  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:37:13.667  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:37:13.667  6370  6370 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:13.667  6370  6370 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:13.667   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{e29eab8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.667   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{fad3091: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.667  6150  6369 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-12 11:37:13.667  6150  6369 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-12 11:37:13.667  6150  6369 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-12 11:37:13.667  6150  6369 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:250)
,07-12 11:37:13.677   777  1718 I ActivityManager: Killing 5229:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,07-12 11:37:13.687   777  1421 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,07-12 11:37:13.687   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{ede3bf7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.687   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{2eefa64: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.697   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{d6344cd: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.697   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{5c8f182: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.697   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{cb0a093: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.707  6370  6370 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package null
07-12 11:37:13.707  6357  6357 I dhcpcd  : wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,07-12 11:37:13.707   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{cd358d0: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.707   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{bec60c9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.707   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{d98a3ce: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.707   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{b3ab2ef: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.717   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{e5d31fc: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.717   777  1420 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,07-12 11:37:13.717   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{7d14085: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.727   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{19f2eda: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.727   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{7a98f0b: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
07-12 11:37:13.727  6370  6370 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm
,07-12 11:37:13.727   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{a4971e8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.727   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{36a6001: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.737   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{f515ea6: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.737   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{ae010e7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.737   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{37c494: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.737   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{41bfb3d: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.747  6357  6357 I dhcpcd  : wlan0: leased 192.168.1.123 for 172800 seconds
,07-12 11:37:13.747   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{4a4bf32: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.747  6370  6370 D BadgeProvider: onCreate
,07-12 11:37:13.747   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{f12d483: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.747  6370  6370 D BadgeProvider: DatabaseHelper
,07-12 11:37:13.757   777  1336 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-12 11:37:13.767   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{8169600: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.777  6370  6384 D BaseReflect: null getOwnClass TEST
,07-12 11:37:13.777  6370  6384 D MethodReflector: android.content.ContentResolver getClass TEST
07-12 11:37:13.777  6370  6384 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
,07-12 11:37:13.777  6370  6384 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,07-12 11:37:13.777   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{7520e39: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.777   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{75b9c7e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.787   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{32435df: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.787   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{84f122c: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.787   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{b3c54f5: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.787  6370  6384 D MethodReflector: notifyChange is called
,07-12 11:37:13.787  1721  1721 D Launcher.Model: reloadBadges entered.
,07-12 11:37:13.797   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{511028a: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.797  6370  6384 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,07-12 11:37:13.797  6370  6384 D BadgeProvider: sendNotify, [notify] : null
,07-12 11:37:13.797  6370  6384 D BadgeProvider: update, getCallingPackage() : com.android.email
,07-12 11:37:13.797  1721  1721 D Launcher.Model: reloadBadges entered.
07-12 11:37:13.797  6370  6384 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
,07-12 11:37:13.797  6370  6384 D BadgeProvider: update, [uri.query] : null
07-12 11:37:13.797  6370  6384 D BadgeProvider: update, [BadgeCount] : badgecount=0
,07-12 11:37:13.807  6370  6384 D BadgeProvider: update, [UpdateCount] : 1
,07-12 11:37:13.807  6370  6386 D BadgeProvider: query, [selection] : null
,07-12 11:37:13.807   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{7c050fb: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.817   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{2b12518: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.817   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{74a4b71: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.827   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{804bd56: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.827   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{23901d7: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.827   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{41f7ac4: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.827   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{672dad: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.837   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{ca758e2: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.837  6370  6386 D BadgeProvider: query, [selection] : null
,07-12 11:37:13.837   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{121e473: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.847   777   787 I art     : Background partial concurrent mark sweep GC freed 68789(4MB) AllocSpace objects, 18(360KB) LOS objects, 27% free, 42MB/58MB, paused 1.952ms total 150.190ms
,07-12 11:37:13.847   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{2fb7f30: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.847   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{4f5f7a9: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:13.847   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{3e6212e: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:14.017  6321  6411 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
,07-12 11:37:14.017  6321  6411 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,07-12 11:37:14.017  6321  6411 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
,07-12 11:37:14.047  6341  6364 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:14.047  6341  6364 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:14.087   777  1329 E WifiNative-wlan0: do suspend true
,07-12 11:37:14.107   777  1328 D WifiP2pService: InactiveState{ what=143375 }
,07-12 11:37:14.107   777  1328 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-12 11:37:14.117   777  1336 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-12 11:37:14.117   777  1329 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-12 11:37:14.117   777  1329 D WifiStateMachine: VerifyingLinkState enter
,07-12 11:37:14.117   777  1336 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-12 11:37:14.117   777  1336 E ConnectivityService: updateNetworkInfo()
,07-12 11:37:14.117   777  1336 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,07-12 11:37:14.117   777  1336 D ConnectivityService: Adding iface wlan0 to network 502
,07-12 11:37:14.127   777   777 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-12 11:37:14.127   777   777 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:14.127   777   777 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-12 11:37:14.127   777  1350 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-12 11:37:14.127   777  1350 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:37:14.127   777  1350 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:37:14.127   777  1350 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:37:14.127   777  1350 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-12 11:37:14.137   777  1334 I WifiHs20Service: Message received 5007
,07-12 11:37:14.137   777  1350 I WifiManager: isCaptivePortalException
,07-12 11:37:14.137   777  1350 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-12 11:37:14.137   777  1350 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-12 11:37:14.137   777  1350 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
,07-12 11:37:14.137   777  1350 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {c8d6565}
07-12 11:37:14.137   777  1350 I WifiManager: isCaptivePortalException
,07-12 11:37:14.137   777  1350 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-12 11:37:14.137   777  1350 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,07-12 11:37:14.157   777  1329 D WifiNative-wlan0: callSECApiInt - ID [210]
,07-12 11:37:14.157   777  1329 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,07-12 11:37:14.157   777  1336 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,07-12 11:37:14.157   777  1336 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,07-12 11:37:14.157   777  1336 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,07-12 11:37:14.157   777  1329 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 11:37:14.167   777  1329 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 11:37:14.167   777  1336 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-12 11:37:14.167   777   777 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-12 11:37:14.167   777  1336 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
07-12 11:37:14.167   777   777 I WifiTrafficPoller: mBoosterFLAG : 0
,07-12 11:37:14.167   777   777 I WifiTrafficPoller: current booster mode : FullMode
07-12 11:37:14.167   777   777 D WifiNative-wlan0: callSECApiVoid - ID [212]
,07-12 11:37:14.167  6172  6172 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-12 11:37:14.167  6172  6172 I wpa_supplicant: P2P: Current p2p state = IDLE
07-12 11:37:14.167   777   777 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-12 11:37:14.167   777   777 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:14.167   777   777 D HS20StateMachine: SSID : "NG700"
07-12 11:37:14.167   777   777 D HS20StateMachine: NetId : 0
07-12 11:37:14.167   777   777 D HS20StateMachine: checkifOSUAP  null
07-12 11:37:14.167   777   777 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-12 11:37:14.167   777  1334 I WifiHs20Service: Message received 5007
,07-12 11:37:14.177   777  1336 V NetworkStats: updateIfacesLocked()
07-12 11:37:14.177   777  1336 V NetworkStats: performPollLocked(flags=0x1)
,07-12 11:37:14.177  6172  6172 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-12 11:37:14.177   777  1336 V NetworkStats: performPollLocked() took 3ms
,07-12 11:37:14.187   777  1336 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:14.187   777  1336 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-12 11:37:14.197   777  1336 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:14.197   777  1336 D ConnectivityService: Not required to send intent.
07-12 11:37:14.197   777  1336 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-12 11:37:14.197   777  1336 E ConnectivityService: updateNetworkInfo()
07-12 11:37:14.197   777  1336 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-12 11:37:14.197   777  1336 V NetworkStats: updateIfacesLocked()
07-12 11:37:14.197   777  1336 V NetworkStats: performPollLocked(flags=0x1)
07-12 11:37:14.197   777  1327 D NtpTrustedTime: forceRefresh: no connectivity
,07-12 11:37:14.197   777  1336 V NetworkStats: performPollLocked() took 3ms
,07-12 11:37:14.197   777  1336 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:14.197   777  1336 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-12 11:37:14.197   777  1327 D NtpTrustedTime: forceRefresh: no connectivity
,07-12 11:37:14.197   777  1336 D ConnectivityService: scheduleUnvalidatedPrompt 502
,07-12 11:37:14.197   777  6348 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:14.197   777  1336 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 502]
07-12 11:37:14.197   777  6348 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Connected
07-12 11:37:14.197   777  1329 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-12 11:37:14.197   777  6348 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:14.207   777  6348 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Validated
,07-12 11:37:14.207   777  1329 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 11:37:14.207   777  1336 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-12 11:37:14.207   777  1588 I ActivityManager: Killing 4577:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,07-12 11:37:14.207   777  1336 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:14.207   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,07-12 11:37:14.207  2119  2119 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
07-12 11:37:14.207   777  1336 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-12 11:37:14.207  1706  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-12 11:37:14.207  1706  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-12 11:37:14.207   777  1336 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-12 11:37:14.207   777  1336 D ConnectivityService: currentScore = 0, newScore = 20
07-12 11:37:14.207   777  1336 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:14.207   777  1336 D ConnectivityService:    accepting network in place of null
07-12 11:37:14.217   777  1336 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.217   777  1329 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.217   777  1329 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:14.217   777  1329 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:14.217   777  1329 D WIFI    : evalRequest
07-12 11:37:14.217   777  1329 D WIFI    :   done
,07-12 11:37:14.217   777  1329 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.217   777  1329 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:14.217   777  1329 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:14.217   777  1329 D WIFI    : evalRequest
07-12 11:37:14.217   777  1329 D WIFI    :   done
,07-12 11:37:14.217   777  2222 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.MessageCompose newState = 1 callingPackage = 10162
,07-12 11:37:14.217   777  1359 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.217   777  1359 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-12 11:37:14.217   777  1359 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-12 11:37:14.217   777  1359 D Ethernet: evalRequest
,07-12 11:37:14.217   777  1359 D Ethernet:   done
,07-12 11:37:14.217   777  1328 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.217   777  1328 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:14.217   777  1328 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-12 11:37:14.217   777  1719 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.AccountShortcutPicker newState = 2 callingPackage = 10162
07-12 11:37:14.217   777  1328 D WIFI_P2P: evalRequest
07-12 11:37:14.217   777  1328 D WIFI_P2P:   done
,07-12 11:37:14.217   777  1329 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.217   777  1329 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:14.217   777  1329 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,07-12 11:37:14.217   777  1329 D WIFI_UT : evalRequest
07-12 11:37:14.217   777  1329 D WIFI_UT :   done
07-12 11:37:14.217   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-12 11:37:14.217   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:14.217   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-12 11:37:14.217   777  1678 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.MailService newState = 2 callingPackage = 10162
07-12 11:37:14.217   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-12 11:37:14.217   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-12 11:37:14.217   777  1588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44c6160 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:14.217   777  1336 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:14.227   777  1727 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.AttachmentDownloadService newState = 2 callingPackage = 10162
,07-12 11:37:14.227   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44c6160 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
07-12 11:37:14.227   777  1420 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-12 11:37:14.237  2119  2119 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
,07-12 11:37:14.247   306  1138 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:37:14.247   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cc36eeb u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a073ef 1386:com.android.systemui/u0a58}
,07-12 11:37:14.257   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40448 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
,07-12 11:37:14.257  6321  6416 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-12 11:37:14.267   777  1718 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,07-12 11:37:14.277  4959  4959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 11:37:14.287   306  1138 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:37:14.287   777  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40448 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d29fce 2183:com.samsung.android.providers.context/u0a174}
,07-12 11:37:14.287   777  1336 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,07-12 11:37:14.287  4959  4959 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,07-12 11:37:14.287  1386  1386 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-12 11:37:14.287  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:14.287   777   909 D EntConnectivity: Not allowed due to - mEnabled false
,07-12 11:37:14.287   777  1300 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40448 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74eac8c 1852:com.sec.android.app.shealth:remote/u0a34}
,07-12 11:37:14.297  4959  4959 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-12 11:37:14.297  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:14.297  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:14.297  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:14.297  4959  4959 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,07-12 11:37:14.297   777  1336 D ConnectivityService: updateTcpDelayedAckSetting - WiFi setting
07-12 11:37:14.297   777  1336 D ConnectivityService: Setting TCP values: [1] which comes from [net.tcp.usercfg.wifi]
,07-12 11:37:14.307   777  1336 D ConnectivityService: Setting TCP values: [20] which comes from [net.tcp.delack.wifi]
,07-12 11:37:14.307   777  2222 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40448 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
,07-12 11:37:14.307   777  1336 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.307   777  1336 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.307   777  1336 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.307   777  1336 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:14.307   777  1336 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
07-12 11:37:14.307   777  1336 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,07-12 11:37:14.307   777  1336 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:14.317   777   909 D EntConnectivity: Not allowed due to - mEnabled false
,07-12 11:37:14.317   777  1300 D ConnectivityService: getVpnConfig > userId : 0
,07-12 11:37:14.317   777  1327 D NtpTrustedTime: forceRefresh() from cache miss
,07-12 11:37:14.317  4959  4959 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 11:37:14.327  1386  1386 D StatusBar.NetworkController: EthernetConnected: false
,07-12 11:37:14.327   777  1336 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:14.327  1386  1386 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-12 11:37:14.327  1386  1386 D StatusBar.NetworkController: updateDataNetType()
07-12 11:37:14.327  1386  1386 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,07-12 11:37:14.327   777  1336 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/777 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.327   777  1336 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:14.327   306  1134 D EnterpriseController: netId is 0
07-12 11:37:14.327   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-12 11:37:14.327   777  1336 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:14.327   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.327   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.327   777  1336 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.327   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:14.327   777  1336 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:14.327   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.327   777  1336 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.327   777   777 D Tethering: Tethering got CONNECTIVITY_ACTION
,07-12 11:37:14.327   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.337   777  1336 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.337   777   909 D Tethering: MasterInitialState.processMessage what=3
,07-12 11:37:14.337   777   777 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:14.337  1386  1386 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-12 11:37:14.337  1386  1386 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
,07-12 11:37:14.337   777  1336 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-12 11:37:14.337   777  1336 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] validation  passed
,07-12 11:37:14.337   777  1336 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-12 11:37:14.337   777  1336 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-12 11:37:14.337   777  1336 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:14.337   777  1650 D NtpTrustedTime: forceRefresh() from cache miss
07-12 11:37:14.337   777  1336 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,07-12 11:37:14.337   306  1134 D EnterpriseController: netId is 0
07-12 11:37:14.337   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 1000
07-12 11:37:14.337   777   777 V MARsPolicyManager: DataConnection: true
07-12 11:37:14.337  1386  1386 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-12 11:37:14.337   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-12 11:37:14.337   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:14.337   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-12 11:37:14.337   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:14.337   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-12 11:37:14.337  5909  5909 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-12 11:37:14.337   777  1336 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:14.337   777  1336 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/777 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.337   777  1336 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:14.337   777  1336 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:14.337   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.337   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.347   777  1337 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-12 11:37:14.347   777  1336 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.347  1706  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-12 11:37:14.347  1706  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-12 11:37:14.347   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-12 11:37:14.347   777  1337 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-12 11:37:14.347   777  1336 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:14.347   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.347   777  1336 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.347   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.347   777  1336 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.347  5909  5909 D BluetoothAdapter: STATE_ON
07-12 11:37:14.347   777  1336 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.347   777  1329 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.347   777  1359 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.347   777  1329 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:14.347   777  1329 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:14.347   777  1329 D WIFI    : evalRequest
07-12 11:37:14.347   777  1329 D WIFI    :   done
07-12 11:37:14.347   777  1329 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.347   777  1329 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:14.347   777  1329 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:14.347   777  1329 D WIFI    : evalRequest
07-12 11:37:14.347   777  1329 D WIFI    :   done
,07-12 11:37:14.347   777  1359 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-12 11:37:14.347   777  1359 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-12 11:37:14.347   777  1359 D Ethernet: evalRequest
07-12 11:37:14.347  5909  5909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:14.347  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:14.347  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 11:37:14.347  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:14.347  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:37:14.347  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 11:37:14.347  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 11:37:14.347  5909  5909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 11:37:14.347   777  1359 D Ethernet:   done
,07-12 11:37:14.347   777  1328 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.347   777  1328 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:14.347   777  1328 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-12 11:37:14.347   777  1328 D WIFI_P2P: evalRequest
07-12 11:37:14.347   777  1328 D WIFI_P2P:   done
,07-12 11:37:14.347   777  1329 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.347  5909  5909 D BluetoothAdapter: STATE_ON
07-12 11:37:14.347   777  1329 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-12 11:37:14.347   777  1329 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:14.347   777  1329 D WIFI_UT : evalRequest
07-12 11:37:14.347   777  1329 D WIFI_UT :   done
07-12 11:37:14.347   777  1336 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-12 11:37:14.357  2095  2095 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-12 11:37:14.357  5909  5909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 11:37:14.357   777  1329 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
,07-12 11:37:14.357   777  1336 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
07-12 11:37:14.357   777   777 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:14.357   777  1336 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-12 11:37:14.357  1386  1386 D StatusBar.NetworkController: EthernetConnected: false
07-12 11:37:14.357  1386  1386 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-12 11:37:14.357  1386  1386 D StatusBar.NetworkController: updateDataNetType()
07-12 11:37:14.357  1386  1386 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-12 11:37:14.357  6211  6211 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-12 11:37:14.357   777  1336 D ConnectivityService: identical MTU - not setting
,07-12 11:37:14.357   777  1336 V NetworkStats: updateIfacesLocked()
07-12 11:37:14.357   777  1336 V NetworkStats: performPollLocked(flags=0x1)
,07-12 11:37:14.357   777  1329 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,07-12 11:37:14.357  1386  1386 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-12 11:37:14.357  1386  1386 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
,07-12 11:37:14.357  1386  1386 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-12 11:37:14.357   777  1678 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:14.357   777  1336 V NetworkStats: performPollLocked() took 4ms
,07-12 11:37:14.367  4959  4959 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-12 11:37:14.367   777  1336 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-12 11:37:14.367   777  1336 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,07-12 11:37:14.367   777  1336 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,07-12 11:37:14.367   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.367  4959  4959 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-12 11:37:14.367   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.367   777  1336 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.367   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:14.367  4959  4959 E BluetoothHeadset: BTStateChangeCB is registed
07-12 11:37:14.367   777  1336 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:14.367   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.367   777  1336 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.377  4959  4959 D BluetoothMap: Create BluetoothMap proxy object
,07-12 11:37:14.377   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.377   777  1336 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.377   777  1336 D ConnectivityService: Not required to send intent.
07-12 11:37:14.377   777  1336 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:14.377   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.377   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:14.377   777  1336 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.377   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:14.377   777  1336 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:14.377   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.377   777  1336 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.377   777  1336 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.377   777  1336 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:14.377  4959  4959 D BluetoothSap: Create BluetoothSap proxy object
,07-12 11:37:14.407  4959  4959 D LocalBluetoothProfileManager: PANU : true
,07-12 11:37:14.417  4959  4959 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
07-12 11:37:14.417  4959  4959 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-12 11:37:14.417  4959  4959 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-12 11:37:14.417  4959  4959 D DockEventReceiver: finishStartingService: stopping service
,07-12 11:37:14.417  4959  4959 D BluetoothNotiBroadcastReceiver: onReceive
,07-12 11:37:14.427  6150  6281 D bt_upio : ..proc_btwrite_timeout..
07-12 11:37:14.427  6150  6281 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-12 11:37:14.427  4959  4959 D BluetoothA2dp: Proxy object connected
,07-12 11:37:14.427  4959  4959 D A2dpProfile: Bluetooth service connected
,07-12 11:37:14.427   777  1719 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40448 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a073ef 1386:com.android.systemui/u0a58}
,07-12 11:37:14.427  1386  1386 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:14.427  1386  1386 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-12 11:37:14.437   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40448 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{19eb859 6150:com.android.bluetooth/1002}
07-12 11:37:14.437  6150  6150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e98ea
07-12 11:37:14.437  6150  6150 D BtConfig.SecureMode: isSecureModeOn:false
,07-12 11:37:14.447   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40448 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{59c16d8 6321:com.google.android.apps.maps/u0a121}
,07-12 11:37:14.447   777  1354 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,07-12 11:37:14.467  1386  1386 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-12 11:37:14.467  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:14.467  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:14.467  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:14.467  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:14.467   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40448 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:14.467  6150  6170 D A2dpStateMachine: getConnectedDevices : size=0
,07-12 11:37:14.467  2119  2119 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,07-12 11:37:14.467  4959  4959 D BluetoothMap: Proxy object connected
,07-12 11:37:14.467  4959  4959 D MapProfile: Bluetooth service connected
07-12 11:37:14.467  4959  4959 D BluetoothMap: getConnectedDevices()
07-12 11:37:14.477  4959  4959 D BluetoothPbap: Proxy object connected
,07-12 11:37:14.477  4959  4959 D PbapServerProfile: Bluetooth service connected
07-12 11:37:14.477  2119  6448 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 11:37:14.477  4959  4959 D BluetoothSap: Proxy object connected
,07-12 11:37:14.477  4959  4959 D SapProfile: Bluetooth service connected
07-12 11:37:14.477  4959  4959 D BluetoothInputDevice: Proxy object connected
,07-12 11:37:14.487  4959  4959 D HidProfile: Bluetooth service connected
,07-12 11:37:14.487   777  1719 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc40448 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:14.487  2119  2119 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
,07-12 11:37:14.497  4959  4959 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:37:14.497  4959  4959 D PanProfile: Bluetooth service connected
,07-12 11:37:14.497  4959  4959 D HeadsetProfile: Bluetooth service connected
,07-12 11:37:14.507   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ebb3908 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a073ef 1386:com.android.systemui/u0a58}
,07-12 11:37:14.507   777   856 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:14.517   777   856 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:14.527   777  1719 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ebb3908 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
,07-12 11:37:14.527  4959  4959 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-12 11:37:14.527  4959  4959 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-12 11:37:14.527   777   789 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:14.527  4959  4959 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,07-12 11:37:14.527   777  1727 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:14.527  4959  4959 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-12 11:37:14.527  4959  4959 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,07-12 11:37:14.527  4959  4959 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-12 11:37:14.527  1706  1717 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-12 11:37:14.537  1706  1717 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-12 11:37:14.537   777   856 D TelephonyManager: getDataEnabled: retVal=true
,07-12 11:37:14.537   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ebb3908 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b7dc56 6211:tv.peel.smartremote/u0a170}
,07-12 11:37:14.547   777  1327 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1468316235127 mCachedNtpElapsedRealtime : 125189 mCachedNtpCertainty : 50
,07-12 11:37:14.547   777  1650 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1468316235127 mCachedNtpElapsedRealtime : 125191 mCachedNtpCertainty : 51
07-12 11:37:14.547   777  1650 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 11:37:14.547   777  1650 D AlarmManager: setTime : 1468316235127 calling from uid: 1000 pid :777
,07-12 11:37:14.547  1706  1717 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@9bcc25e, selection=nullselectionArgs=null, sort=name ASC
,07-12 11:37:14.547   777  1650 D AlarmManagerService: Setting time of day to sec=1468316235
07-12 11:37:14.547   777  1650 D AlarmManagerService: Trying to open a file
07-12 11:37:14.547   777  1650 E AlarmManagerService: File Open Failed
07-12 11:37:15.127   777  1650 W AlarmManagerService: Unable to set rtc to 1468316235: Invalid argument
07-12 11:37:15.127   777  1650 V AlarmManager:  remove PendingIntent] PendingIntent{1c746ae: PendingIntentRecord{1f64c4f android broadcastIntent}}
,07-12 11:37:15.127   777  1240 V AlarmManager: Expired Alarm result :65536
,07-12 11:37:15.127  1706  1717 D TelephonyProvider: query: match = 5
,07-12 11:37:15.127  6453  6453 E Zygote  : v2
07-12 11:37:15.127  6453  6453 I libpersona: KNOX_SDCARD checking this for 10163
07-12 11:37:15.127  6453  6453 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:15.127  6453  6453 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:15.127  6453  6453 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:15.127  6453  6453 E Zygote  : accessInfo : 0
,07-12 11:37:15.127  6453  6453 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.exchange 
,07-12 11:37:15.127   777  2222 I ActivityManager: Start proc 6453:com.android.exchange/u0a163 for broadcast-3 com.android.exchange/.service.ExchangeBroadcastReceiver
,07-12 11:37:15.137   777  1327 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 11:37:15.137   777  1327 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:15.137   777  1327 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
07-12 11:37:15.137   777  1327 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:37:15.137   777  1327 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 11:37:15.137   777  1327 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:37:15.137   777  1327 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:37:15.137   777  1327 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-12 11:37:15.137   777  1327 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 11:37:15.147  1706  1717 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,07-12 11:37:15.147   777   861 I ActivityManager: Start proc 6465:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,07-12 11:37:15.157  6465  6465 E Zygote  : v2
07-12 11:37:15.157  6465  6465 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:15.157  6465  6465 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:15.157  6465  6465 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:15.157  6465  6465 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:15.157  6465  6465 E Zygote  : accessInfo : 0
,07-12 11:37:15.157   777  1240 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=125196 batch.start=125318
,07-12 11:37:15.177  6453  6453 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:15.177  6453  6453 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:15.177  6150  6477 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-12 11:37:15.187  6150  6477 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
,07-12 11:37:15.187  6150  6477 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-12 11:37:15.187  6150  6477 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:250)
,07-12 11:37:15.187  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
,07-12 11:37:15.187  1386  1386 I PERF    : received broadcast android.intent.action.TIME_SET
07-12 11:37:15.187  1386  1386 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:37:15.187  6465  6465 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:15.187  6465  6465 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:15.187   777   777 I CAE     : handleMessage(CaTimeChangeManager.java:159) - Time Change, auto old:true new:true
,07-12 11:37:15.187   777   777 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1468316235200
07-12 11:37:15.197   777   777 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,07-12 11:37:15.197  1386  1386 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-12 11:37:15.197   777   777 V MARsPolicyManager: updateDBResetTimeForTimeChanged -- SystemTime Changed : 569
,07-12 11:37:15.197   777   777 V MARsPolicyManager: SystemTime Changed Less than 30 min, didn't care!!
,07-12 11:37:15.197  2095  2095 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionTIME_SET
,07-12 11:37:15.197  1386  1386 D SecKeyguardClockView: HomeTimezone(): 1
,07-12 11:37:15.197   777   777 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:15.207  2095  2095 D accuweather: [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,07-12 11:37:15.207   777   777 W System.err: java.io.FileNotFoundException: /data/drm/beforeTime.ini: open failed: EACCES (Permission denied)
,07-12 11:37:15.207   777   777 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 11:37:15.207   777   777 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:37:15.207   777   777 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
07-12 11:37:15.207   777   777 W System.err: 	at java.io.FileReader.<init>(FileReader.java:66)
07-12 11:37:15.207   777   777 W System.err: 	at com.android.server.DrmEventService.getBeforeTime(DrmEventService.java:280)
07-12 11:37:15.207   777   777 W System.err: 	at com.android.server.DrmEventService.handleUserUpdatedTimeUpdation(DrmEventService.java:372)
07-12 11:37:15.207   777   777 W System.err: 	at com.android.server.DrmEventService.userUpdateHandler(DrmEventService.java:262)
07-12 11:37:15.207   777   777 W System.err: 	at com.android.server.DrmEventService.access$200(DrmEventService.java:49)
07-12 11:37:15.207   777   777 W System.err: 	at com.android.server.DrmEventService$3.onReceive(DrmEventService.java:413)
07-12 11:37:15.207   777   777 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
07-12 11:37:15.207   777   777 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:37:15.207   777   777 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:37:15.207   777   777 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-12 11:37:15.207   777   777 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:508)
07-12 11:37:15.207   777   777 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:363)
07-12 11:37:15.207   777   777 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:15.207   777   777 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-12 11:37:15.207   777   777 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-12 11:37:15.207   777   777 W System.err: Caused by: android.system.ErrnoException: open failed: EACCES (Permission denied)
07-12 11:37:15.207   777   777 W System.err: 	at libcore.io.Posix.open(Native Method)
07-12 11:37:15.207   777   777 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 11:37:15.207   777   777 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 11:37:15.207   777   777 W System.err: 	... 17 more
07-12 11:37:15.207   777   777 I DrmEventService: handleUserUpdatedTimeUpdation beforeTime -100
,07-12 11:37:15.207  2095  2095 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,07-12 11:37:15.207  2095  2095 D accuweather: [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
07-12 11:37:15.207  2095  2095 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
07-12 11:37:15.207  2095  2095 D accuweather: [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
,07-12 11:37:15.207  2095  2095 D accuweather: [KK AccuPhone]>>> SM:1417 [0:0] setClockLayoutContent
,07-12 11:37:15.207  2095  2095 D accuweather: [KK AccuPhone]>>> U:850 [0:0] Locale format : MMM d, y
07-12 11:37:15.207  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.207  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.207  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.207  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.207  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.217  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.217  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.227   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e596ddd u0 com.android.email.intent.action.CHANGE_LOGGING qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{17b4d52 6453:com.android.exchange/u0a163}
,07-12 11:37:15.227  2119  6448 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-12 11:37:15.227   777   856 E GpsLocationProvider: No APN found to select.
,07-12 11:37:15.237  6453  6453 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in com.android.exchange rsrc of package null
,07-12 11:37:15.237   777   789 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ebb3908 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{27b1823 6465:com.sec.android.diagmonagent/1000}
,07-12 11:37:15.247   777  1354 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,07-12 11:37:15.247   777  1240 V AlarmManager: Expired Alarm result :4
,07-12 11:37:15.257  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.257  6465  6465 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package null
,07-12 11:37:15.267   777   777 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
07-12 11:37:15.267   777   777 V AlarmManagerEXT: <AppSync3 Whitelist>
07-12 11:37:15.267   777   777 V AlarmManagerEXT: (AppSync) ### 0 added ###
,07-12 11:37:15.267  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-12 11:37:15.267  1386  1386 I PERF    : received broadcast android.intent.action.TIME_TICK
07-12 11:37:15.267  1386  1386 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:37:15.277  6465  6465 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm
,07-12 11:37:15.277  1386  1386 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-12 11:37:15.287  1386  1386 D SecKeyguardClockView: HomeTimezone(): 1
,07-12 11:37:15.287  5422  5470 I Finsky  : [794] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-12 11:37:15.287  6453  6453 W System  : ClassLoader referenced unknown path: /system/app/SecExchange/lib/arm
,07-12 11:37:15.297  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.297  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.297  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-12 11:37:15.297  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.307  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.307  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.307  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:15.307   777  1727 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:15.307   777  1727 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-12 11:37:15.307   777  1727 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-12 11:37:15.307   777  1727 D BatteryService: stay LED for charging
,07-12 11:37:15.307   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:15.317   777   777 I MotionRecognitionService: Plugged
07-12 11:37:15.317   777   777 D MotionRecognitionService:   cableConnection= 1
07-12 11:37:15.317   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:37:15.317   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:15.317  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:37:15.317  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:15.317  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:15.317  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:15.327  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-12 11:37:15.327  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-12 11:37:15.327  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-12 11:37:15.327  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:15.327  6465  6465 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-12 11:37:15.327  3983  6485 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-12 11:37:15.337  2119  2119 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:37:15.367   777   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 38125, reason: UserStart, SyncResult: databaseError: true stats []
,07-12 11:37:15.377  1386  1386 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,07-12 11:37:15.387   777  1727 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:15.397   777   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 156814, reason: UserStart
,07-12 11:37:15.407  3068  3083 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-12 11:37:15.407  3068  3083 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-12 11:37:15.407  3068  3083 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-12 11:37:15.417   777  3287 D SSRM:n  : SIOP:: AP = 430, PST = 418, CUR = 450, LCD = 0
,07-12 11:37:15.417  3068  3083 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-12 11:37:15.417   777  2231 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-12 11:37:15.427   777  2222 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ebbf377 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{27b1823 6465:com.sec.android.diagmonagent/1000}
,07-12 11:37:15.457  3983  3983 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10011, CallingPid : 3983
,07-12 11:37:15.457   777   790 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/3983 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:15.457   777  1336 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-12 11:37:15.457   777  1336 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:15.457   777  1336 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-12 11:37:15.457   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:15.457   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:15.457   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:15.457   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-12 11:37:15.457   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:15.457   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-12 11:37:15.457   777  1336 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:15.497  3983  6450 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-12 11:37:15.517  3983  6486 W DriveInitializer: Awaiting to be initialized
,07-12 11:37:15.517  3983  6490 W DriveInitializer: Background init thread started
,07-12 11:37:15.587  6465  6465 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,07-12 11:37:15.597  6465  6465 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
,07-12 11:37:15.607  6465  6465 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-12 11:37:15.607  6465  6465 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-12 11:37:15.607  6465  6465 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-12 11:37:15.607  6465  6465 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-12 11:37:15.607  6465  6465 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-12 11:37:15.607  6465  6465 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-12 11:37:15.607  6465  6465 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-12 11:37:15.607  6465  6465 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-12 11:37:15.617  3983  6490 W DriveInitializer: Background init thread ended
,07-12 11:37:15.617  6499  6499 E Zygote  : v2
07-12 11:37:15.617  6499  6499 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:15.617  6499  6499 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:15.617  6499  6499 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:15.617  6499  6499 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:15.617   777   790 I ActivityManager: Start proc 6499:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,07-12 11:37:15.627  6499  6499 E Zygote  : accessInfo : 0
,07-12 11:37:15.637   777  1719 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ebbf377 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a073ef 1386:com.android.systemui/u0a58}
,07-12 11:37:15.647  6499  6499 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:15.647  6499  6499 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:15.647   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ebbf377 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
,07-12 11:37:15.647  4959  4959 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-12 11:37:15.647  4959  4959 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-12 11:37:15.657   777  2222 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ebb3908 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{867db68 6499:com.sec.knox.switcher/1000}
,07-12 11:37:15.667  6499  6499 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package null
,07-12 11:37:15.677   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ebbf377 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{867db68 6499:com.sec.knox.switcher/1000}
,07-12 11:37:15.677  6499  6499 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm
,07-12 11:37:15.697  6499  6499 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
,07-12 11:37:15.697  6499  6499 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,07-12 11:37:15.697  6499  6499 I usagelog: received in receiver
,07-12 11:37:15.697  6499  6499 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-12 11:37:15.707  6499  6499 I KnoxUsageLogPro: premStatus:2
,07-12 11:37:15.707  6499  6499 I KnoxUsageLogPro: isEulaShown : false
,07-12 11:37:15.707  6499  6499 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-12 11:37:15.707  6499  6499 I usagelog: received in receiver
,07-12 11:37:15.707  6499  6499 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-12 11:37:15.707  6499  6499 I KnoxUsageLogPro: premStatus:2
,07-12 11:37:15.717  6499  6499 I KnoxUsageLogPro: isEulaShown : false
,07-12 11:37:15.717  6499  6499 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-12 11:37:15.717  6511  6511 E Zygote  : v2
,07-12 11:37:15.717  6511  6511 I libpersona: KNOX_SDCARD checking this for 10203
07-12 11:37:15.717  6511  6511 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:15.717  6511  6511 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:37:15.727  6511  6511 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:15.727   777  1727 I ActivityManager: Start proc 6511:com.samsung.android.sm.policy/u0a203 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
,07-12 11:37:15.727  6511  6511 E Zygote  : accessInfo : 0
,07-12 11:37:15.727  6511  6511 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-12 11:37:15.737  6150  6208 D bt_vendor: op for 7
,07-12 11:37:15.737   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ebbf377 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b7dc56 6211:tv.peel.smartremote/u0a170}
07-12 11:37:15.737  6150  6208 D bt_upio : upio_set : pio 0 action 1, polarity 1
07-12 11:37:15.737  6150  6208 D bt_upio : BT_WAKE is de-asserted already
,07-12 11:37:15.747  6511  6511 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:15.747  6511  6511 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:15.757   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3824b81 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{27b1823 6465:com.sec.android.diagmonagent/1000}
,07-12 11:37:15.757  6465  6465 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-12 11:37:15.757  6465  6465 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-12 11:37:15.757  6465  6465 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-12 11:37:15.757  6465  6465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3634 
,07-12 11:37:15.767   777  1421 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ebb3908 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{841a426 6511:com.samsung.android.sm.policy/u0a203}
,07-12 11:37:15.777   777  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3824b81 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a073ef 1386:com.android.systemui/u0a58}
,07-12 11:37:15.777  6511  6511 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package null
,07-12 11:37:15.787   777  2212 I ActivityManager: Killing 5600:com.google.android.gms:car/u0a11 (adj 15): DHA:empty #37
,07-12 11:37:15.797   777  2231 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-12 11:37:15.807  6511  6511 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm
,07-12 11:37:15.807   777  2235 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,07-12 11:37:15.817   777  1727 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,07-12 11:37:15.817   777  1719 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
,07-12 11:37:15.817   777  1588 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,07-12 11:37:15.837  4959  4959 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-12 11:37:15.837  4959  4959 I NearbySettings: MountReceiver.onReceive - Keep current state
07-12 11:37:15.837   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3824b81 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84992b3 4959:com.android.settings/1000}
,07-12 11:37:15.837  1386  1386 D ViewRootImpl: #1 mView = android.widget.LinearLayout{d40f7c3 V.E...... ......I. 0,0-0,0 #10203a7 android:id/toast_layout_root}
,07-12 11:37:15.847   777  1589 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ebbf377 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{841a426 6511:com.samsung.android.sm.policy/u0a203}
,07-12 11:37:15.857   777  2231 D ISSUE_DEBUG: InputChannelName : a5f11fe Toast
,07-12 11:37:15.857   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3824b81 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{867db68 6499:com.sec.knox.switcher/1000}
,07-12 11:37:15.857   777  2231 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,07-12 11:37:15.857  6499  6499 I usagelog: received in receiver
07-12 11:37:15.867  6499  6499 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-12 11:37:15.867  6499  6499 I KnoxUsageLogPro: premStatus:2
,07-12 11:37:15.867  6499  6499 I KnoxUsageLogPro: isEulaShown : false
07-12 11:37:15.867  6499  6499 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-12 11:37:15.877   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3824b81 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{841a426 6511:com.samsung.android.sm.policy/u0a203}
,07-12 11:37:15.887   294   294 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=4, Uoast
,07-12 11:37:15.907   777  1420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3824b81 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b7dc56 6211:tv.peel.smartremote/u0a170}
,07-12 11:37:15.917   777   789 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=777
,07-12 11:37:15.937   777  2235 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b1e939 5909:com.test.thalitest/u0a4}
,07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:15.937   777  1421 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:15.947  1386  1386 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-12 11:37:15.947   777  1588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{69758ba 777:system/1000}
,07-12 11:37:15.957  1386  1386 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-12 11:37:15.967   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:15.967   777  1719 V WindowStateAnimator: Finishing drawing window Window{a5f11fe u0 d0 Toast}: mDrawState=DRAW_PENDING
,07-12 11:37:15.977   777  2222 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{25db01b 3983:com.google.android.gms/u0a11}
,07-12 11:37:15.987  3983  6526 I iu.SyncManager: SYNC; picasa accounts
,07-12 11:37:15.987   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbea01364
,07-12 11:37:15.987   306  1134 D EnterpriseController: netId is 0
07-12 11:37:15.987   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-12 11:37:15.997  3983  3983 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-12 11:37:16.007  3983  3983 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 11:37:16.007   777  1719 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{25db01b 3983:com.google.android.gms/u0a11}
,07-12 11:37:16.007  3983  6526 I iu.UploadsManager: num queued entries: 0
,07-12 11:37:16.017  3983  6526 I iu.UploadsManager: num updated entries: 0
,07-12 11:37:16.017  3983  6526 I iu.SyncManager: NEXT; no task
,07-12 11:37:16.037   777  1588 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.AccountsChangedReceiver newState = 2 callingPackage = 10011
,07-12 11:37:16.047   777  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8f416f1 2095:com.sec.android.widgetapp.ap.hero.accuweather/u0a70}
,07-12 11:37:16.067  2095  2095 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-12 11:37:16.067  2095  2095 D accuweather: [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,07-12 11:37:16.077  2095  2095 D accuweather: [KK AccuPhone]>>> UIMEM:91 [0:0] getInstance
,07-12 11:37:16.077  2095  2095 D accuweather: [KK AccuPhone]>>> UIMEM:79 [0:0] UIManager : create ui manager
,07-12 11:37:16.077  2095  2095 D accuweather: [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,07-12 11:37:16.077  2095  2095 D accuweather: [KK AccuPhone]>>> RM:136 [0:0]  V init 
,07-12 11:37:16.077  1520  1532 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:37:16.107  2095  2095 D accuweather: [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,07-12 11:37:16.127  1520  1558 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:37:16.147  2095  2095 D accuweather: [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,07-12 11:37:16.147  1520  1531 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:37:16.147  2095  2095 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,07-12 11:37:16.147  2095  2095 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,07-12 11:37:16.167   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{69758ba 777:system/1000}
,07-12 11:37:16.177   777   861 I ActivityManager: Start proc 6536:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,07-12 11:37:16.177  6536  6536 E Zygote  : v2
07-12 11:37:16.177  6536  6536 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:16.177  6536  6536 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:16.177   777   777 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bccfe00 4148:com.samsung.klmsagent/u0a18}
07-12 11:37:16.177  6536  6536 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:16.177  6536  6536 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:16.177  5422  5470 I Finsky  : [794] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-12 11:37:16.187  5422  5422 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-12 11:37:16.187  6536  6536 E Zygote  : accessInfo : 0
,07-12 11:37:16.187   777   790 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:16.187  4881  6535 D PicasaService: start picasa sync
,07-12 11:37:16.187  4881  6535 D PicasaService: end picasa sync
,07-12 11:37:16.197  4148  4148 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 } | timestamp: Tue Jul 12 11:37:16 GMT+02:00 2016
,07-12 11:37:16.207  4148  4148 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,07-12 11:37:16.207  4148  4148 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,07-12 11:37:16.207  4148  4148 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-12 11:37:16.207  4148  4148 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-12 11:37:16.207   777  1300 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b2a143 5474:com.sec.android.app.shealth/u0a34}
,07-12 11:37:16.207  4148  6547 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 }
,07-12 11:37:16.207  4148  6547 D KLMS-2.6.032: : KLMSIntentService(): TIME_CHANGED
,07-12 11:37:16.217  4148  6547 I KLMS-2.6.032: : Systemprocess(): dateTimeChanged().START : Tue Jul 12 11:37:16 GMT+02:00 2016
,07-12 11:37:16.217   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{9c6f8b0: PendingIntentRecord{95ee6ba com.google.android.apps.plus broadcastIntent}}
,07-12 11:37:16.227  4148  6547 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,07-12 11:37:16.227  4148  6547 I KLMS-2.6.032: : Systemprocess(): ModifySetAlarm().START
07-12 11:37:16.227  4148  6547 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,07-12 11:37:16.227  4148  6547 I KLMS-2.6.032: : Systemprocess(): ModifySetAlarm().END
,07-12 11:37:16.227  4148  6547 I KLMS-2.6.032: : Systemprocess(): dateTimeChanged().END
,07-12 11:37:16.237  4148  4148 I KLMS-2.6.032: : KLMSIntentService(): onDestroy()
,07-12 11:37:16.247   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{19db329: PendingIntentRecord{771f6ae com.google.android.apps.plus broadcastIntent}}
,07-12 11:37:16.247  6536  6536 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:16.247  6536  6536 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:16.257   777   790 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d433c4f 6536:com.policydm/1000}
,07-12 11:37:16.267   777  1589 I ActivityManager: Killing 5810:com.google.android.partnersetup/u0a14 (adj 15): DHA:empty #37
,07-12 11:37:16.277   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74eac8c 1852:com.sec.android.app.shealth:remote/u0a34}
,07-12 11:37:16.277  6536  6536 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package null
,07-12 11:37:16.277   777   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74eac8c 1852:com.sec.android.app.shealth:remote/u0a34}
,07-12 11:37:16.287   777  1719 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,07-12 11:37:16.307  6536  6536 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm
,07-12 11:37:16.327   777  1718 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d433c4f 6536:com.policydm/1000}
,07-12 11:37:16.327  1852  1852 D HealthDataStore: Service for HealthDataStore is connected
,07-12 11:37:16.327  1852  1852 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-12 11:37:16.347  2119  2119 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:37:16.347  2119  2119 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:37:16.367   777  1421 I ActivityManager: Killing 5825:com.samsung.groupcast/u0a15 (adj 15): DHA:empty #37
,07-12 11:37:16.377  1852  1852 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-12 11:37:16.377  1852  1852 E HealthDataStore: disconnectService: Context instance is invalid
,07-12 11:37:16.377   777  1727 D ActivityManager: isAutoRunBlockedApp:: com.samsung.groupcast, Auto Run ON
,07-12 11:37:16.387  6536  6536 I FOTA    : [com.policydm.db.XDB(1493/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-12 11:37:16.437  2119  6527 I qtaguid : Tagging socket 33 with tag 1000040700000000{268436487,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:16.437  2119  6527 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in com.google.android.gms rsrc of package null
,07-12 11:37:16.447  2119  6527 I GCM     : GCM config loaded
,07-12 11:37:16.477  6536  6536 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(54/<init>)] 
,07-12 11:37:16.477  6536  6536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:58 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:14 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:20 
,07-12 11:37:16.487  5394  6530 I art     : Note: end time exceeds epoch: 
,07-12 11:37:16.487  6557  6557 E Zygote  : v2
,07-12 11:37:16.487   777  1719 I ActivityManager: Start proc 6557:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
07-12 11:37:16.487  6557  6557 I libpersona: KNOX_SDCARD checking this for 10210
07-12 11:37:16.487  6557  6557 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:16.487  6536  6536 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-12 11:37:16.487  6557  6557 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:37:16.487  6557  6557 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:16.487  5394  5394 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10134, CallingPid : 5394
,07-12 11:37:16.497  6557  6557 E Zygote  : accessInfo : 0
,07-12 11:37:16.497  6557  6557 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,07-12 11:37:16.497   777  2231 D ConnectivityService: listenForNetwork for Listen from uid/pid:10134/5394 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:16.497   777  1336 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-12 11:37:16.497   777  1336 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:16.497   777  1336 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-12 11:37:16.497   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:16.497   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-12 11:37:16.497   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:16.497   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-12 11:37:16.497   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:16.497   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:16.497   777  1336 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-12 11:37:16.497   777  1336 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:16.507   777  1727 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10134
,07-12 11:37:16.507   777  1727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-12 11:37:16.527  6536  6536 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(236/llIIIIlllllIIllIIllI)] try read dbString
,07-12 11:37:16.527   306  1134 D EnterpriseController: netId is 0
07-12 11:37:16.527   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 10134
,07-12 11:37:16.527  6557  6557 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:16.527  6557  6557 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:16.537  6536  6536 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:16.537  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
07-12 11:37:16.537  6557  6557 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,07-12 11:37:16.537  6536  6536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.sec.android.policyagent.PolicyApplication.onCreate:61 android.app.Instrumentation.callApplicationOnCreate:1036 android.app.ActivityThread.handleBindApplication:6316 
,07-12 11:37:16.547  6536  6536 I DBG_POLICYDM: [com.sec.android.policyagent.PolicyApplication(64/onCreate)] PolicyApplication onCreated!
,07-12 11:37:16.547  6557  6557 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,07-12 11:37:16.557  6557  6557 D AASAservice: onCreate()
,07-12 11:37:16.557  6536  6536 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-12 11:37:16.567  6536  6536 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:16.567  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-12 11:37:16.577  6536  6536 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.intent.action.TIME_SET
,07-12 11:37:16.577   777   789 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:16.577  6536  6578 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
07-12 11:37:16.577   777  2222 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d433c4f 6536:com.policydm/1000}
,07-12 11:37:16.577  6536  6578 I DBG_POLICYDM: [com.policydm.XDMService(382/lllIlIlIIIllIIlIllIl)] a previous network is 0, current network is 2
,07-12 11:37:16.577  6536  6578 E DBG_POLICYDM: [com.policydm.XDMService(384/lllIlIlIIIllIIlIllIl)] network changed.... 
,07-12 11:37:16.577  6536  6578 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : true
,07-12 11:37:16.577  6536  6578 I DBG_POLICYDM: [com.policydm.lllIlIlIIIllIIlIllIl(93/run)] SPD SERVICE Start!!
,07-12 11:37:16.577  6536  6536 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
,07-12 11:37:16.577  6536  6578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.policydm.lllIlIlIIIllIIlIllIl.run:94 java.lang.Thread.run:818 
,07-12 11:37:16.587  6536  6578 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(196/llIIIIlllllIIllIIllI)] DM Not Init
,07-12 11:37:16.587  6536  6536 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,07-12 11:37:16.587  6536  6536 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,07-12 11:37:16.587  6536  6536 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/07/19/12:09:32
,07-12 11:37:16.587  6536  6578 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-12 11:37:16.587  6536  6536 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-12 11:37:16.597  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(122/onCreate)] 
,07-12 11:37:16.597  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(171/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,07-12 11:37:16.597  6536  6536 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
07-12 11:37:16.597  6536  6578 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:16.597  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(515/IIIIllIlIIlIIIIlllIl)] 
,07-12 11:37:16.597  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(520/IIIIllIlIIlIIIIlllIl)] m_WakeLock is acquire!!
,07-12 11:37:16.607   777  1727 I ActivityManager: Start proc 6582:com.samsung.android.scloud/5009 for broadcast-3 com.samsung.android.scloud/.receivers.SCloudReceiver
,07-12 11:37:16.607  6582  6582 E Zygote  : v2
07-12 11:37:16.607  6582  6582 I libpersona: KNOX_SDCARD checking this for 5009
07-12 11:37:16.607  6582  6582 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:16.607  6536  6536 I DBG_POLICYDM: [com.policydm.eng.core.IlIlIlIlIlIIlllllIlI(70/llIIIIlllllIIllIIllI)] waiting for DM_TaskHandler create
,07-12 11:37:16.607  6582  6582 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:16.607  6582  6582 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:16.607  6582  6582 E Zygote  : accessInfo : 0
,07-12 11:37:16.607  6582  6582 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud 
,07-12 11:37:16.607  6536  6578 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(316/llIIllllIIlllIIIIlll)] SPD SERVICE Stop!!
,07-12 11:37:16.607  6536  6578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1311 android.content.ContextWrapper.stopService:611 com.policydm.XDMBroadcastReceiver.llIIllllIIlllIIIIlll:317 com.policydm.XDMService.llllIIIllIlIIIIllllI:288 com.policydm.lllIlIlIIIllIIlIllIl.run:98 
,07-12 11:37:16.607  6536  6578 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : false
,07-12 11:37:16.627  6582  6582 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:16.627  6582  6582 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:16.637   777   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{356a85b 6582:com.samsung.android.scloud/5009}
,07-12 11:37:16.647  6582  6582 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in com.samsung.android.scloud rsrc of package null
,07-12 11:37:16.657  6582  6582 W System  : ClassLoader referenced unknown path: /system/priv-app/SCloudService/lib/arm
,07-12 11:37:16.677  6582  6582 I ExternalOEMControlProvider: onCreate
,07-12 11:37:16.687  6582  6582 I SCloudService: onCreate
,07-12 11:37:16.717  6582  6582 I SCloudService: SCloudService Version Info : 1.4.13
07-12 11:37:16.717  6582  6582 I SCloudReceiver: onReceive : android.intent.action.TIME_SET
,07-12 11:37:16.737  6598  6598 E Zygote  : v2
07-12 11:37:16.737  6598  6598 I libpersona: KNOX_SDCARD checking this for 10044
07-12 11:37:16.737  6598  6598 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:16.737  6598  6598 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:16.737  6598  6598 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:16.737   777  1718 I ActivityManager: Start proc 6598:com.osp.app.signin/u0a44 for broadcast-3 com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver
,07-12 11:37:16.737  6598  6598 E Zygote  : accessInfo : 0
,07-12 11:37:16.737  6598  6598 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
07-12 11:37:16.737   777  1727 I ActivityManager: Killing 5837:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): DHA:empty #37
,07-12 11:37:16.757  6582  6597 E SCLOUD_ERR- Time Manager : Time Difference not stored. 
07-12 11:37:16.757  6582  6597 E SCLOUD_ERR- Time Manager : android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
07-12 11:37:16.757  6582  6597 E SCLOUD_ERR- Time Manager : 	at android.provider.Settings$System.getLongForUser(Settings.java:2031)
07-12 11:37:16.757  6582  6597 E SCLOUD_ERR- Time Manager : 	at android.provider.Settings$System.getLong(Settings.java:2021)
07-12 11:37:16.757  6582  6597 E SCLOUD_ERR- Time Manager : 	at com.samsung.android.scloud.utils.TimeManager.updateTimeSettings(TimeManager.java:89)
07-12 11:37:16.757  6582  6597 E SCLOUD_ERR- Time Manager : 	at com.samsung.android.scloud.receivers.SCloudReceiver$5.run(SCloudReceiver.java:188)
07-12 11:37:16.757  6582  6597 E SCLOUD_ERR- Time Manager : 	at java.lang.Thread.run(Thread.java:818)
,07-12 11:37:16.757  6598  6598 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:16.757  6598  6598 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:16.767   777  1300 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,07-12 11:37:16.767   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{49398f8: PendingIntentRecord{26a8671 com.android.bluetooth broadcastIntent}}
,07-12 11:37:16.777   777  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{343e1d1 6598:com.osp.app.signin/u0a44}
,07-12 11:37:16.777  6598  6598 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in com.osp.app.signin rsrc of package null
,07-12 11:37:16.797  6598  6598 W System  : ClassLoader referenced unknown path: /system/priv-app/Samsungservice2_xxhdpi/lib/arm
,07-12 11:37:16.817   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{8cd6f37: PendingIntentRecord{b5b0436 com.google.android.gms broadcastIntent}}
,07-12 11:37:16.827  6598  6598 I SA      : [SSP] onCreated
,07-12 11:37:16.837  6598  6598 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@e83760
,07-12 11:37:16.837  5394  6573 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.google.android.apps.plus rsrc of package null
,07-12 11:37:16.847   777   787 I art     : Background partial concurrent mark sweep GC freed 87901(5MB) AllocSpace objects, 16(320KB) LOS objects, 27% free, 41MB/57MB, paused 1.818ms total 103.202ms
,07-12 11:37:16.857  6598  6598 I SA      : [TPM] There is no property file
,07-12 11:37:16.867  6598  6598 I SA      : [SCU] isHaveSA() - false
,07-12 11:37:16.867  6598  6598 I SA      : [TPM] getModelProperty : null
07-12 11:37:16.867  6598  6598 I SA      : [TPM] getCSCProperty : null
,07-12 11:37:16.867  6598  6598 I SA      : [DM] FLOATING AMOLED FEATURE: true
07-12 11:37:16.867  6598  6598 I SA      : [DM] PRODUCT AMOLED FEATURE: false
07-12 11:37:16.867  6598  6598 I SA      : [DM] TFT FEATURE: false
,07-12 11:37:16.867  6598  6598 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
07-12 11:37:16.867  6598  6598 I SA      : [DM] init START
,07-12 11:37:16.867  6598  6598 I SA      : [DM] This device is not a Vodafone
,07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
07-12 11:37:16.877  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 11:37:16.877  5909  6016 I jxcore-log: 
07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,07-12 11:37:16.877  6598  6598 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:37:16.877  6598  6598 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
07-12 11:37:16.877  6598  6598 W ResourceType: Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
07-12 11:37:16.887  6598  6598 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,07-12 11:37:16.887  6598  6598 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:37:16.887  6598  6598 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,07-12 11:37:16.887  6598  6598 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
07-12 11:37:16.887  6598  6598 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,07-12 11:37:16.887  6598  6598 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
07-12 11:37:16.887  6598  6598 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,07-12 11:37:16.887  6598  6598 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,07-12 11:37:16.887  6598  6598 I SA      : [SCU] isHaveSA() - false
07-12 11:37:16.887  6598  6598 I SA      : support phone number id : false
07-12 11:37:16.887  6598  6598 I SA      : [DM] Supports Ref Jpn : true
,07-12 11:37:16.887  6598  6598 I SA      : [DM] init END
,07-12 11:37:16.917  6613  6613 E Zygote  : v2
07-12 11:37:16.917  6613  6613 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:16.917  6613  6613 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:16.917   777  1727 I ActivityManager: Start proc 6613:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.service.ContextAgentReceiver
,07-12 11:37:16.917  6613  6613 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:16.917  6613  6613 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:16.917  6613  6613 E Zygote  : accessInfo : 0
07-12 11:37:16.917   777  1727 I ActivityManager: Killing 5860:com.sec.android.app.myfiles/u0a50 (adj 15): DHA:empty #37
,07-12 11:37:16.937  5394  6530 I art     : Note: end time exceeds epoch: 
,07-12 11:37:16.937   777  1718 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.myfiles, Auto Run ON
,07-12 11:37:16.937  6613  6613 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:16.937  6613  6613 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:16.947   777  1719 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{37fc7d3 6613:com.samsung.android.sm/1000}
,07-12 11:37:16.947  6613  6613 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,07-12 11:37:16.987   777  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b130a34 4976:com.android.mms/u0a49}
,07-12 11:37:16.997   777  1718 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{867db68 6499:com.sec.knox.switcher/1000}
,07-12 11:37:16.997  6499  6499 I usagelog: received in receiver
07-12 11:37:16.997  6499  6499 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.TIME_SET myUserId=0
07-12 11:37:16.997  6499  6499 I KnoxUsageLogPro: premStatus:2
,07-12 11:37:16.997  6499  6499 I KnoxUsageLogPro: isEulaShown : false
07-12 11:37:17.007  6499  6499 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-12 11:37:17.017   777  1718 I ActivityManager: Start proc 6625:com.sec.android.GeoLookout/u0a112 for broadcast-3 com.sec.android.GeoLookout/.widget.SafetyCareWidget
,07-12 11:37:17.017  6625  6625 E Zygote  : v2
07-12 11:37:17.017  6625  6625 I libpersona: KNOX_SDCARD checking this for 10112
07-12 11:37:17.017  6625  6625 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:17.017  6625  6625 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:17.017  6625  6625 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:17.017   777  1718 I ActivityManager: Killing 5875:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): DHA:empty #37
,07-12 11:37:17.017  6625  6625 E Zygote  : accessInfo : 0
,07-12 11:37:17.017  6625  6625 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.GeoLookout 
,07-12 11:37:17.037  6625  6625 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:17.037  6625  6625 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:17.047   777  1300 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7c8f10 6625:com.sec.android.GeoLookout/u0a112}
,07-12 11:37:17.047   777  2231 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,07-12 11:37:17.047  6625  6625 W ResourcesManager: getTopLevelResources: /system/app/GeoLookout/GeoLookout.apk / 1.0 running in com.sec.android.GeoLookout rsrc of package null
,07-12 11:37:17.067  6625  6625 W System  : ClassLoader referenced unknown path: /system/app/GeoLookout/lib/arm
,07-12 11:37:17.077  6625  6625 D GeoLookout: H: CVccN35zteEo7uWDJ0cWTbsuAnPmDHBG4p+ywI/gN9j8cnobeOUVeZgeK/+93LDsu89EQ821mpIbyCdOp1WNyQ==
,07-12 11:37:17.087  6625  6625 W GeoLookout: H: zOXtzplbN+8pOR8lXMN+zi7kXd24xZXWuIjld2hFBv004DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
,07-12 11:37:17.087  6625  6625 I GeoLookout: H: zOXtzplbN+8pOR8lXMN+zm/QpcPruwLHDXz9jGj9RlOeGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
,07-12 11:37:17.097  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,07-12 11:37:17.097  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
,07-12 11:37:17.097  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,07-12 11:37:17.097  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,07-12 11:37:17.097  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,07-12 11:37:17.097  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,07-12 11:37:17.097  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1Gkj0KYZpO99f1rsYZnglZtCc+mJqVQceay8W/Aon4dQ==
,07-12 11:37:17.097  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3NyUiHu5cWdT4SPPZ0OxqJQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,07-12 11:37:17.107  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2G1kMmI09JBmwwj0mFkR2L4tvU5wsp5Dwccfz++DFQoQ==
,07-12 11:37:17.107  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2sH9Musae3FSSYRxL/dVLnM4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,07-12 11:37:17.107  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2C8R3qbaE3iKzVn5nYcXDsaba68PSLy9IpSfBXGHVgOg==
,07-12 11:37:17.107   777  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7c8f10 6625:com.sec.android.GeoLookout/u0a112}
,07-12 11:37:17.107  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,07-12 11:37:17.107  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
,07-12 11:37:17.117  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,07-12 11:37:17.127   777  2222 I ActivityManager: Start proc 6639:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 for broadcast-3 com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider
,07-12 11:37:17.127  6639  6639 E Zygote  : v2
07-12 11:37:17.127  6639  6639 I libpersona: KNOX_SDCARD checking this for 10148
07-12 11:37:17.127  6639  6639 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:17.127   777  2222 I ActivityManager: Killing 5889:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #37
,07-12 11:37:17.127  6639  6639 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:17.127  6639  6639 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:17.127  6639  6639 E Zygote  : accessInfo : 0
,07-12 11:37:17.127  6639  6639 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.SPlannerAppWidget 
,07-12 11:37:17.147   777   789 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,07-12 11:37:17.147  6536  6579 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-12 11:37:17.147  6536  6579 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(191/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,07-12 11:37:17.147  6536  6579 I DBG_POLICYDM: [IIlIlIIIlIIlIlIIIIII(146/llIIIIlllllIIllIIllI)] nSync = 0
,07-12 11:37:17.157  6536  6579 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
07-12 11:37:17.157  6536  6536 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(126/IlIIIllllIIlIIIIIlII)] 
,07-12 11:37:17.157  6639  6639 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:17.157  6639  6639 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:17.157  6536  6579 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(200/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,07-12 11:37:17.157   777  1300 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{afffa09 6639:com.sec.android.widgetapp.SPlannerAppWidget/u0a148}
,07-12 11:37:17.167   777  1719 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:17.167  6536  6579 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-12 11:37:17.167  6536  6579 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-12 11:37:17.167  6639  6639 W ResourcesManager: getTopLevelResources: /system/app/SPlannerWidget_M_OS_UPG/SPlannerWidget_M_OS_UPG.apk / 1.0 running in com.sec.android.widgetapp.SPlannerAppWidget rsrc of package null
,07-12 11:37:17.167  6536  6579 I DBG_POLICYDM: [com.policydm.ui.IllIIIIIIlIIlIIIlIII(49/llIIIIlllllIIllIIllI)] Indicator id : 7
,07-12 11:37:17.167  6536  6536 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(160/IlIIIllllIIlIIIIIlII)] bExternalStorageAvailable [true]
,07-12 11:37:17.167  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(541/llllllIllIlIlllIIlIl)] 
,07-12 11:37:17.167  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(546/llllllIllIlIlllIIlIl)] m_WakeLock is release!!
,07-12 11:37:17.177  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
,07-12 11:37:17.177  6536  6579 I DBG_POLICYDM: [com.policydm.XDMService(572/llllIIIllIlIIIIllllI)] set NotibarState : 7
,07-12 11:37:17.177  6536  6579 I DBG_POLICYDM: [com.policydm.adapter.llllIIIllIlIIIIllllI(98/lllIlIlIIIllIIlIllIl)] 
,07-12 11:37:17.177  6536  6536 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,07-12 11:37:17.187  6536  6536 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:17.187  6536  6536 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
,07-12 11:37:17.187  6536  6536 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,07-12 11:37:17.187  6536  6536 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,07-12 11:37:17.187  6536  6536 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/07/19/12:09:32
,07-12 11:37:17.187  6639  6639 W System  : ClassLoader referenced unknown path: /system/app/SPlannerWidget_M_OS_UPG/lib/arm
,07-12 11:37:17.197  6536  6536 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-12 11:37:17.197  6536  6579 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:17.207  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
,07-12 11:37:17.207  6536  6536 I DBG_POLICYDM: [com.policydm.XDMService(105/onDestroy)] 
,07-12 11:37:17.207   777  1589 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{343e1d1 6598:com.osp.app.signin/u0a44}
,07-12 11:37:17.207  6598  6598 I SA      : [OR] onReceive log=[SA = 2.1.0300 V = 23 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = MMB29M M = SM-G900F OKLEFT false DIS MMB29M.G900FXXU1CPEM PSS = 5.219788042639568  ]
,07-12 11:37:17.207  6598  6598 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-12 11:37:17.207  6598  6598 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-12 11:37:17.207  6598  6598 I SA      : [SLFUCHKMGR] constructor called
,07-12 11:37:17.217  6536  6579 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-12 11:37:17.217   777  1420 I ActivityManager: Killing 5922:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #37
,07-12 11:37:17.217  6536  6580 I DBG_POLICYDM: [llllIlIIIllllIIlIlll(208/llllIIIllIlIIIIllllI)] XUI_DM_IDLE_STATE :true
,07-12 11:37:17.217   777  2235 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:17.217  6536  6580 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-12 11:37:17.227  6536  6579 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(232/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,07-12 11:37:17.227  6598  6598 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-12 11:37:17.227  6598  6598 I SA      : [OR] == isSIMCardReady false ==
,07-12 11:37:17.227  6598  6598 I SA      : [SCU] == networkStateCheck == true
,07-12 11:37:17.227  6536  6580 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
07-12 11:37:17.227  6598  6598 I SA      : [DM] getCountryCodeFromCSC : PL
07-12 11:37:17.227  6598  6598 I SA      : isChinaCountryCode : false
07-12 11:37:17.227  6598  6598 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-12 11:37:17.227  6598  6598 I SA      : [OR] == networkStateCheck true ==
,07-12 11:37:17.227  6536  6580 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/IIIlIIllIlIIllIlllII)] nSessionSaveState:0
,07-12 11:37:17.227   777  1420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13edff5 6184:com.samsung.android.securitylogagent/1000}
,07-12 11:37:17.237  6184  6184 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-12 11:37:17.237  6184  6184 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-12 11:37:17.237  6184  6184 D SecurityLogAgent: StateMachine : Current State = 1
,07-12 11:37:17.237   777   789 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:17.237   777  2212 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:17.237   777  1678 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,07-12 11:37:17.237  6536  6580 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/IIIlIIllIlIIllIlllII)] nNotiUiEvent:0
,07-12 11:37:17.237  6536  6580 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/IIIlIIllIlIIllIlllII)] nNotiRetryCount:0
,07-12 11:37:17.237  6536  6580 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/IIIlIIllIlIIllIlllII)] Current NOTI NOT SAVED State. EXIT.
,07-12 11:37:17.237  6536  6580 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/IIIIlllIIIlIlIlllIII)] 
,07-12 11:37:17.247  6536  6580 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(39/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-12 11:37:17.247  6536  6580 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(453/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus : 0
07-12 11:37:17.247   777  1420 I ActivityManager: Start proc 6653:com.sec.android.app.taskmanager/u0a175 for broadcast-3 com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver
07-12 11:37:17.247  6653  6653 E Zygote  : v2
07-12 11:37:17.247  6653  6653 I libpersona: KNOX_SDCARD checking this for 10175
07-12 11:37:17.247  6653  6653 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:17.257  6653  6653 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:17.257  6653  6653 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:17.257   777  1420 I ActivityManager: Killing 5941:com.google.android.apps.docs/u0a97 (adj 15): DHA:empty #37
07-12 11:37:17.257  6653  6653 E Zygote  : accessInfo : 0
07-12 11:37:17.257  6653  6653 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.taskmanager 
,07-12 11:37:17.257  6598  6598 I SA      : [OR] GetMyCountryZoneTask
,07-12 11:37:17.257  6598  6598 I SA      : [OR] onReceive END
,07-12 11:37:17.267  6536  6579 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(211/lllIlIlIIIllIIlIllIl)] 
,07-12 11:37:17.267  6598  6663 I SA      : [SRS_HTTPURLCONNECTION] prepareGetMyCountryZone
,07-12 11:37:17.267  6665  6665 E Zygote  : v2
07-12 11:37:17.267  6665  6665 I libpersona: KNOX_SDCARD checking this for 10002
07-12 11:37:17.267  6665  6665 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:17.267  6665  6665 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:17.267  6665  6665 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:17.277  6665  6665 E Zygote  : accessInfo : 0
,07-12 11:37:17.277  6665  6665 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.cloudagent 
,07-12 11:37:17.277   777  2235 I ActivityManager: Start proc 6665:com.sec.android.cloudagent/u0a2 for broadcast-5 com.sec.android.cloudagent/.detector.DetectorReceiver
,07-12 11:37:17.277   777  2235 I ActivityManager: Killing 6000:com.sec.android.automotive.drivelink/u0a98 (adj 15): DHA:empty #37
,07-12 11:37:17.277  6536  6579 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/sepolicy
,07-12 11:37:17.277  6653  6653 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:17.277  6653  6653 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:17.277  6536  6579 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/seapp_contexts
,07-12 11:37:17.287  6536  6579 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/property_contexts
,07-12 11:37:17.287   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{922640e 6653:com.sec.android.app.taskmanager/u0a175}
,07-12 11:37:17.297  6536  6580 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(552/llllIIIllIlIIIIllllI)] Initiated Type: 0
,07-12 11:37:17.297  6536  6579 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/file_contexts
,07-12 11:37:17.297  6653  6653 W ResourcesManager: getTopLevelResources: /system/app/TaskManager/TaskManager.apk / 1.0 running in com.sec.android.app.taskmanager rsrc of package null
,07-12 11:37:17.307  6536  6579 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/service_contexts
,07-12 11:37:17.307  6665  6665 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:17.307  6665  6665 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:17.307  6536  6579 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/mac_permissions.xml
,07-12 11:37:17.317   777  1678 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef50e2f 6665:com.sec.android.cloudagent/u0a2}
,07-12 11:37:17.317  6598  6663 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-12 11:37:17.317  6598  6663 I SA      : [SSP] query invoked
,07-12 11:37:17.317   777  1420 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.automotive.drivelink, Auto Run ON
,07-12 11:37:17.317  6536  6579 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(235/lllIlIlIIIllIIlIllIl)] Start resumecase for INIT
,07-12 11:37:17.327   777  1421 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:17.327   777  2222 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
07-12 11:37:17.327  6536  6579 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-12 11:37:17.327  6598  6663 I SA      : [TPMU] GetMccFromDB : null
07-12 11:37:17.327  6598  6663 I SA      : [SCU] getMccFromPreferece mcc = 260
07-12 11:37:17.327  6598  6663 I SA      : [LBE] isSupportCheckDomainRegion : true
,07-12 11:37:17.327  6598  6663 I SA      : [TPM] isNoProxy(default) : true
07-12 11:37:17.327  6665  6665 W ResourcesManager: getTopLevelResources: /system/priv-app/CloudAgent/CloudAgent.apk / 1.0 running in com.sec.android.cloudagent rsrc of package null
,07-12 11:37:17.337  6598  6663 E File    : fail readDirectory() errno=2
,07-12 11:37:17.347  6653  6653 W System  : ClassLoader referenced unknown path: /system/app/TaskManager/lib/arm
,07-12 11:37:17.347  6536  6579 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-12 11:37:17.347  6536  6579 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:17.347  6665  6665 W System  : ClassLoader referenced unknown path: /system/priv-app/CloudAgent/lib/arm
,07-12 11:37:17.347  6536  6580 I DBG_POLICYDM: [com.policydm.db.XDB(1781/IIIlIIllIlIIllIlllII)] 
,07-12 11:37:17.357  6679  6679 E Zygote  : v2
07-12 11:37:17.357  6679  6679 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:17.357  6679  6679 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:17.357   777  2231 I ActivityManager: Start proc 6679:com.qualcomm.timeservice/1000 for broadcast-3 com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
07-12 11:37:17.357  6679  6679 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:17.357  6679  6679 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:17.367  6679  6679 E Zygote  : accessInfo : 0
07-12 11:37:17.367   777  2231 I ActivityManager: Killing 6021:com.vlingo.midas/u0a32 (adj 15): DHA:empty #37
,07-12 11:37:17.387  5394  6530 I art     : Note: end time exceeds epoch: 
,07-12 11:37:17.387  5394  6530 I art     : Note: end time exceeds epoch: 
,07-12 11:37:17.387  6679  6679 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:17.387  6679  6679 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:17.397   777  1421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38c3c 6679:com.qualcomm.timeservice/1000}
,07-12 11:37:17.407   777  1300 D ActivityManager: isAutoRunBlockedApp:: com.vlingo.midas, Auto Run ON
,07-12 11:37:17.407  6679  6679 W ResourcesManager: getTopLevelResources: /system/app/TimeService/TimeService.apk / 1.0 running in com.qualcomm.timeservice rsrc of package null
,07-12 11:37:17.417  6679  6679 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,07-12 11:37:17.427  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 11:37:17.427  5909  6016 I jxcore-log: 
07-12 11:37:17.427  6679  6679 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1468316237438
07-12 11:37:17.427  6679  6679 D         : TimeServiceNative: User Time to be set is 1468316237438
07-12 11:37:17.427  6679  6679 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-12 11:37:17.427  6679  6679 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-12 11:37:17.427  6679  6679 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1468316237438
,07-12 11:37:17.427   372   700 D QC-time-services: Daemon: Connection accepted:time_genoff
07-12 11:37:17.427  6679  6679 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,07-12 11:37:17.437  6693  6693 E Zygote  : v2
07-12 11:37:17.437  6693  6693 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:17.437  6693  6693 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:17.437  6693  6693 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:17.437  6693  6693 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:17.437   777  2222 I ActivityManager: Start proc 6693:com.wssyncmldm/1000 for broadcast-5 com.wssyncmldm/com.samsung.android.app.fotaclient.NetworkReceiver
,07-12 11:37:17.437  6693  6693 E Zygote  : accessInfo : 0
,07-12 11:37:17.437   372  6695 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1468316237438
07-12 11:37:17.437   372  6695 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1468316237438, operation = 0
,07-12 11:37:17.437   372  6695 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/19/70 14:19:7
,07-12 11:37:17.437   372  6695 D QC-time-services: Daemon:Value read from RTC seconds = 27872347000
07-12 11:37:17.437   372  6695 D QC-time-services: Daemon:new time 1468316237438 
07-12 11:37:17.437   372  6695 D QC-time-services: Daemon: delta 1440443890438 genoff 1440443890438 
07-12 11:37:17.437   372  6695 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440443890438 to memory
07-12 11:37:17.437   372  6695 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-12 11:37:17.437   372  6695 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:37:17.447   777  2212 I ActivityManager: Killing 6035:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #37
,07-12 11:37:17.457   372  6695 D QC-time-services: Updating the TOD offset
07-12 11:37:17.457   372  6695 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440443890438 to memory
07-12 11:37:17.457   372  6695 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-12 11:37:17.457   372  6695 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:37:17.457   372  6695 E QC-time-services: Daemon:Update to modem bit set
07-12 11:37:17.457   372  6695 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-12 11:37:17.457   372  6695 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124479090438
,07-12 11:37:17.457  6679  6679 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,07-12 11:37:17.457   777  2231 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,07-12 11:37:17.467  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 11:37:17.467  5909  6016 I jxcore-log: 
,07-12 11:37:17.467   372   688 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,07-12 11:37:17.467   372   700 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,07-12 11:37:17.467  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 11:37:17.467  5909  6016 I jxcore-log: 
,07-12 11:37:17.467  6693  6693 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:17.467   777  1588 I ActivityManager: Killing 6051:com.samsung.helphub/1000 (adj 15): DHA:empty #37
07-12 11:37:17.467  6693  6693 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:17.467  5394  6530 I art     : Note: end time exceeds epoch: 
,07-12 11:37:17.477   777  1588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a0f5fd 1520:com.sec.android.daemonapp/u0a181}
,07-12 11:37:17.477   306  1134 D EnterpriseController: netId is 0
07-12 11:37:17.477   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 10134
,07-12 11:37:17.477  1520  1520 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-12 11:37:17.477  1520  1520 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-12 11:37:17.477  1520  1520 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:37:17.487  1520  1520 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:37:17.487   777  1300 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8a52dc5 6693:com.wssyncmldm/1000}
,07-12 11:37:17.487  6693  6693 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package null
,07-12 11:37:17.497  1520  1520 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : androidintentactionTIME_SET, run:true
,07-12 11:37:17.497  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 11:37:17.497  5909  6016 I jxcore-log: 
,07-12 11:37:17.497  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 11:37:17.497  5909  6016 I jxcore-log: 
,07-12 11:37:17.507  1520  1520 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:37:17.507  1520  1520 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-12 11:37:17.507  1520  1520 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-12 11:37:17.507  1520  1520 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:37:17.507  1520  1520 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-12 11:37:17.507  1520  1520 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-12 11:37:17.507   777   790 D ActivityManager: isAutoRunBlockedApp:: com.samsung.helphub, Auto Run ON
,07-12 11:37:17.507  1520  1520 D daemonapp: [MSC_Daemon]>>> WU:1609 [0:0] PakNme size = 5
,07-12 11:37:17.517  1520  1520 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-12 11:37:17.517  1520  1520 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-12 11:37:17.517  1520  1520 D daemonapp: [MSC_Daemon]>>> WU:1613 [0:0] CP Name cp_eng
,07-12 11:37:17.517  1520  1520 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-12 11:37:17.517  1520  1520 E daemonapp: [MSC_Daemon]>>> WU:1593 [0:0] [NameNotFoundException] !!
,07-12 11:37:17.517  6693  6693 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm
,07-12 11:37:17.527   777  1420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a0f5fd 1520:com.sec.android.daemonapp/u0a181}
,07-12 11:37:17.537  6536  6580 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-12 11:37:17.547  1520  1520 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
07-12 11:37:17.547  1520  1520 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,07-12 11:37:17.547  6693  6693 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,07-12 11:37:17.567   303   303 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c0a030
,07-12 11:37:17.567   303   303 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
07-12 11:37:17.567   303   303 I rmt_storage: wakelock acquired: 1, error no: 42
07-12 11:37:17.567   303   620 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1230239440)
,07-12 11:37:17.567   777  2231 I ActivityManager: Start proc 6708:com.sec.android.app.clockpackage/u0a90 for broadcast-3 com.sec.android.app.clockpackage/.alarm.AlarmReceiver
07-12 11:37:17.567  6708  6708 E Zygote  : v2
07-12 11:37:17.567  6708  6708 I libpersona: KNOX_SDCARD checking this for 10090
07-12 11:37:17.567  6708  6708 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:17.577  6708  6708 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:17.577  6708  6708 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:17.577  6708  6708 E Zygote  : accessInfo : 0
,07-12 11:37:17.577  6708  6708 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.clockpackage 
,07-12 11:37:17.587  6536  6580 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(37/llllIIIllIlIIIIllllI)] Noti Exist : false
,07-12 11:37:17.607  6708  6708 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:17.607  6708  6708 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:17.617   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{da4b31a 6708:com.sec.android.app.clockpackage/u0a90}
,07-12 11:37:17.617  6708  6708 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_MUPG/ClockPackage_MUPG.apk / 1.0 running in com.sec.android.app.clockpackage rsrc of package null
,07-12 11:37:17.627   303   620 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
07-12 11:37:17.627   303   620 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,07-12 11:37:17.627   303   620 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1230239440) wakelock released: 1, error no: 0
07-12 11:37:17.627   303   620 I rmt_storage: 
,07-12 11:37:17.637   303   303 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c0a030
,07-12 11:37:17.647  6693  6693 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2021/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-12 11:37:17.657  6708  6708 W System  : ClassLoader referenced unknown path: /system/app/ClockPackage_MUPG/lib/arm
,07-12 11:37:17.707   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{dce5e4b: PendingIntentRecord{a9b3028 com.sec.android.app.clockpackage broadcastIntent}}
,07-12 11:37:17.707   777  1718 D SettingsProvider: isChangeAllowed() : name = next_alarm_formatted
07-12 11:37:17.707   777  1718 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:17.707   777  1718 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:17.707   777  1718 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:17.707   777  1718 D SettingsProvider: selectionArgs: false
07-12 11:37:17.707   777  1718 D SettingsProvider: selectionArgs: 10090
,07-12 11:37:17.707   777  1718 D SettingsProvider: ret = -1
,07-12 11:37:17.717  5394  6530 I art     : Note: end time exceeds epoch: 
,07-12 11:37:17.727  6693  6693 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(271/llIlIIIIlIIIIIlIlIII)] Voice : true
,07-12 11:37:17.727  6693  6693 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(272/llIlIIIIlIIIIIlIlIII)] SMS : true
,07-12 11:37:17.727  6693  6693 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,07-12 11:37:17.747  6693  6693 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3216/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-12 11:37:17.747  6693  6693 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3268/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,07-12 11:37:17.767  6693  6693 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
,07-12 11:37:17.767   777  1727 I ActivityManager: Killing 6063:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #37
,07-12 11:37:17.767   777  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8f416f1 2095:com.sec.android.widgetapp.ap.hero.accuweather/u0a70}
,07-12 11:37:17.767  2095  2095 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,07-12 11:37:17.767  2095  2095 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,07-12 11:37:17.787  6724  6724 E Zygote  : v2
07-12 11:37:17.787  6724  6724 I libpersona: KNOX_SDCARD checking this for 10149
07-12 11:37:17.787  6724  6724 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:17.787  6724  6724 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:17.787  6724  6724 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:17.787   777  1678 I ActivityManager: Start proc 6724:com.android.calendar/u0a149 for broadcast-3 com.android.calendar/.alerts.AlertReceiver
07-12 11:37:17.787  6724  6724 E Zygote  : accessInfo : 0
07-12 11:37:17.787  6724  6724 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.calendar 
,07-12 11:37:17.797   777   789 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
,07-12 11:37:17.807  6693  6723 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:17.807   777  1678 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fd59faf 3675:com.sec.spp.push/u0a37}
,07-12 11:37:17.807   777  1589 I ActivityManager: Killing 6077:com.sec.kidsplat.installer/u0a165 (adj 15): DHA:empty #37
,07-12 11:37:17.817  3675  3675 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:17.817  3675  3675 E SPPClientService: [SystemStateMoniter] Current Time : 127890
,07-12 11:37:17.817  6724  6724 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:17.817  6724  6724 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:17.827  3675  3675 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-12 11:37:17.827   777  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cae6e6 6724:com.android.calendar/u0a149}
,07-12 11:37:17.827   777  2222 D ActivityManager: isAutoRunBlockedApp:: com.sec.kidsplat.installer, Auto Run ON
,07-12 11:37:17.837  6724  6724 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M_OS_UPG/SPlanner_M_OS_UPG.apk / 1.0 running in com.android.calendar rsrc of package null
,07-12 11:37:17.837   777  3287 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:17.837   777   789 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5bae8be 2664:android.process.media/u0a46}
,07-12 11:37:17.847  2664  2664 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:17.857  6724  6724 W System  : ClassLoader referenced unknown path: /system/app/SPlanner_M_OS_UPG/lib/arm
,07-12 11:37:17.857   777  1588 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd2e4d1 3068:com.android.contacts/u0a19}
,07-12 11:37:17.867   777  2231 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,07-12 11:37:17.877   777  1300 I ActivityManager: Start proc 6738:com.google.android.apps.photos/u0a199 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-12 11:37:17.877  6738  6738 E Zygote  : v2
07-12 11:37:17.877  6738  6738 I libpersona: KNOX_SDCARD checking this for 10199
07-12 11:37:17.877  6738  6738 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:17.877  6738  6738 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:37:17.877  6738  6738 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:17.877  6738  6738 E Zygote  : accessInfo : 0
,07-12 11:37:17.877  6738  6738 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,07-12 11:37:17.887  1520  1558 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:37:17.887  5394  6530 I art     : Note: end time exceeds epoch: 
,07-12 11:37:17.887  5394  6530 I art     : Note: end time exceeds epoch: 
,07-12 11:37:17.907  6738  6738 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:17.907  6738  6738 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:17.917   777  2212 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{88726d4 6738:com.google.android.apps.photos/u0a199}
,07-12 11:37:17.917   777  2235 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10134
07-12 11:37:17.917   777  2235 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-12 11:37:17.927  6738  6738 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package null
,07-12 11:37:17.947  6738  6738 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-12 11:37:17.967   777  1421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cae6e6 6724:com.android.calendar/u0a149}
,07-12 11:37:17.997  6761  6761 E Zygote  : v2
07-12 11:37:17.997  6761  6761 I libpersona: KNOX_SDCARD checking this for 10045
07-12 11:37:17.997  6761  6761 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:17.997   777  2235 I ActivityManager: Start proc 6761:com.android.providers.calendar/u0a45 for content provider com.android.providers.calendar/.CalendarProvider2
,07-12 11:37:17.997  6761  6761 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:17.997  6761  6761 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:17.997  6761  6761 E Zygote  : accessInfo : 0
,07-12 11:37:17.997  6761  6761 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.providers.calendar 
07-12 11:37:17.997   777  1327 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-12 11:37:18.007   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{25db01b 3983:com.google.android.gms/u0a11}
,07-12 11:37:18.007   777  1327 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:37:18.017   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:18.027  6761  6761 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:18.027  6761  6761 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:18.047  6761  6761 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk / 1.0 running in com.android.providers.calendar rsrc of package null
,07-12 11:37:18.067  6761  6761 W System  : ClassLoader referenced unknown path: /system/priv-app/SecCalendarProvider/lib/arm
,07-12 11:37:18.157   777  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed8d662 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{25db01b 3983:com.google.android.gms/u0a11}
,07-12 11:37:18.187   777  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0ef358 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:18.187   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{5929cb1: PendingIntentRecord{8607679 com.google.android.gms broadcastIntent}}
,07-12 11:37:18.197   777  2212 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d10d596 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{27b1823 6465:com.sec.android.diagmonagent/1000}
,07-12 11:37:18.197  6465  6465 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,07-12 11:37:18.197  6465  6465 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-12 11:37:18.197  6465  6465 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-12 11:37:18.207  6465  6465 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(18/llllIIIllIlIIIIllllI)] timeToActivate is not set. Do not anything.
,07-12 11:37:18.217   777  1421 I ActivityManager: Start proc 6775:com.google.android.talk/u0a116 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,07-12 11:37:18.217  6775  6775 E Zygote  : v2
07-12 11:37:18.217  6775  6775 I libpersona: KNOX_SDCARD checking this for 10116
07-12 11:37:18.217  6775  6775 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:18.217  6775  6775 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:18.217  6775  6775 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:18.217  6775  6775 E Zygote  : accessInfo : 0
,07-12 11:37:18.217  6775  6775 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,07-12 11:37:18.217   777  1421 I ActivityManager: Killing 6089:com.sec.android.app.sbrowser/u0a142 (adj 15): DHA:empty #37
,07-12 11:37:18.247  6775  6775 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:18.247  6775  6775 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:18.257   777   789 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{52bed04 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b0352ed 6775:com.google.android.talk/u0a116}
,07-12 11:37:18.257   777  1300 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sbrowser, Auto Run ON
,07-12 11:37:18.257   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:37:18.267  6775  6775 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-12 11:37:18.287   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{3fcb522: PendingIntentRecord{8607679 com.google.android.gms broadcastIntent}}
,07-12 11:37:18.307  6775  6775 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-12 11:37:18.377  3983  6789 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,07-12 11:37:18.377  3983  6789 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-12 11:37:18.437  2119  2119 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:37:18.437  6775  6775 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-12 11:37:18.447   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{b51e288: PendingIntentRecord{8607679 com.google.android.gms broadcastIntent}}
,07-12 11:37:18.497  6761  6790 D Holiday : [HolidayManager] HolidayManager() - Start of fillHolidayDataIntoDB()
,07-12 11:37:18.497  6761  6790 E Holiday : [HolidayManager] No supports the national holidays
,07-12 11:37:18.517   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{4c7d046: PendingIntentRecord{8607679 com.google.android.gms broadcastIntent}}
,07-12 11:37:18.527  6357  6357 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:37:18.617   306  1131 D Netd    : Iface wlan0 link up
07-12 11:37:18.617  6172  6172 I wpa_supplicant: nl80211: Received scan results (7 BSSes)
07-12 11:37:18.617   777   866 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:18.617   777   866 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:18.617   777  1328 D WifiP2pService: InactiveState{ what=147461 }
07-12 11:37:18.617   777  1328 D WifiP2pService: P2pEnabledState{ what=147461 }
07-12 11:37:18.617   777  1328 D WifiP2pService: DefaultState{ what=147461 }
,07-12 11:37:18.667   777  3287 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:18.697  6775  6799 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-12 11:37:18.697  6775  6799 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-12 11:37:18.757  6775  6775 I Babel_telephony: TeleModule.onApplicationCreate
,07-12 11:37:18.807  6738  6738 W Primes  : Memory instrumentations are turned off.
,07-12 11:37:18.807  6738  6738 W Primes  : Timer instrumentations are turned off.
,07-12 11:37:18.817  6738  6738 W Primes  : Crash monitoring is turned off.
,07-12 11:37:18.827  6738  6738 W Primes  : Network monitoring is turned off.
07-12 11:37:18.827  6738  6738 W Primes  : Package metrics are turned off by default
,07-12 11:37:18.837  6775  6813 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-12 11:37:18.837  6775  6813 I Babel_SMS: MmsConfig.loadMmsSettings
,07-12 11:37:18.837  6775  6813 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
07-12 11:37:18.837  6775  6813 I Babel_SMS: MmsConfig.loadFromDatabase
,07-12 11:37:18.947   777  2222 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{88726d4 6738:com.google.android.apps.photos/u0a199}
,07-12 11:37:18.967  6775  6813 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-12 11:37:18.967  6775  6813 I Babel_SMS: MmsConfig.loadFromResources
,07-12 11:37:18.967  6775  6813 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-12 11:37:18.967  6775  6813 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,07-12 11:37:18.967  6817  6817 E Zygote  : v2
07-12 11:37:18.967  6817  6817 I libpersona: KNOX_SDCARD checking this for 10011
07-12 11:37:18.967  6817  6817 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:18.967  6817  6817 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:18.967  6817  6817 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:18.977  6817  6817 E Zygote  : accessInfo : 0
,07-12 11:37:18.977  6817  6817 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,07-12 11:37:18.977   777  2212 I ActivityManager: Start proc 6817:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,07-12 11:37:18.977  6598  6663 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-12 11:37:18.987   777  1718 I ActivityManager: Start proc 6828:com.google.android.apps.magazines/u0a127 for broadcast-5 com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 11:37:18.987  6828  6828 E Zygote  : v2
07-12 11:37:18.987  6828  6828 I libpersona: KNOX_SDCARD checking this for 10127
07-12 11:37:18.987  6828  6828 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:18.987  6828  6828 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:18.987  6828  6828 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:18.987  6828  6828 E Zygote  : accessInfo : 0
,07-12 11:37:18.987  6828  6828 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.magazines 
,07-12 11:37:19.007  6817  6817 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:19.007  6817  6817 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:19.027  6828  6828 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:19.027  6828  6828 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:19.037   777  1589 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4fc01ef 6828:com.google.android.apps.magazines/u0a127}
,07-12 11:37:19.047  6817  6817 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,07-12 11:37:19.047  6775  6775 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-12 11:37:19.077  6828  6828 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.google.android.apps.magazines rsrc of package null
,07-12 11:37:19.077  6775  6775 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-12 11:37:19.107  6817  6817 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:37:19.107  6817  6817 I MultiDex: install
07-12 11:37:19.107  6817  6817 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:37:19.107  6598  6663 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-12 11:37:19.117  6775  6775 I Babel_Crash: Startup - clean
,07-12 11:37:19.127  6598  6663 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:19.127  6598  6663 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:19.137  6817  6817 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-12 11:37:19.137   777  1588 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10116
,07-12 11:37:19.157  6817  6817 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-12 11:37:19.157  6817  6817 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-12 11:37:19.157  6817  6817 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:37:19.167   777  2231 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10116
,07-12 11:37:19.167   777   790 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10116
,07-12 11:37:19.177   777  1589 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10116
,07-12 11:37:19.177   777   789 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10116
,07-12 11:37:19.187  6828  6828 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-12 11:37:19.197  6817  6817 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:37:19.197   777   787 I art     : Background partial concurrent mark sweep GC freed 24014(1369KB) AllocSpace objects, 6(120KB) LOS objects, 27% free, 41MB/57MB, paused 1.632ms total 133.377ms
,07-12 11:37:19.207  6817  6817 D ChimeraCfgMgr: Reading stored module config
,07-12 11:37:19.227  2119  2119 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=841318c7-b450-4949-8a33-4e3c93ce2570
,07-12 11:37:19.227   306  1134 D EnterpriseController: netId is 0
07-12 11:37:19.227   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 10044
,07-12 11:37:19.327  6828  6828 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:37:19.327  6828  6828 I MultiDex: install
07-12 11:37:19.327  6828  6828 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:37:19.327  6817  6849 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-12 11:37:19.367  1386  1386 D ViewRootImpl: #3 mView = null
,07-12 11:37:19.367   294   379 I SurfaceFlinger: id=17 Removed Uoast (8/9)
,07-12 11:37:19.377   294   379 I SurfaceFlinger: id=17 Removed Uoast (-2/9)
,07-12 11:37:19.377   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbea013a4
,07-12 11:37:19.387   777   789 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 777) eventTime = 129466
,07-12 11:37:19.387   777   789 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=777 (0x0)
,07-12 11:37:19.387   320   320 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6817)
,07-12 11:37:19.407   777   789 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=777, ws=WorkSource{10058}) (elapsedTime=3489)
,07-12 11:37:19.447   777  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab7c373 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b9b6b 2119:com.google.android.gms.persistent/u0a11}
,07-12 11:37:19.457   777  2212 I ActivityManager: Killing 6110:com.sec.android.app.samsungapps/u0a39 (adj 15): DHA:empty #37
,07-12 11:37:19.477   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bbd7230 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a073ef 1386:com.android.systemui/u0a58}
,07-12 11:37:19.477   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{9946ea9: PendingIntentRecord{8607679 com.google.android.gms broadcastIntent}}
,07-12 11:37:19.487   320   320 D WVCdm   : Instantiating CDM.
,07-12 11:37:19.487   320   982 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6817)
07-12 11:37:19.487   320   982 I WVCdm   : CdmEngine::OpenSession
07-12 11:37:19.487   320   982 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-12 11:37:19.487   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da0cc2e u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{88726d4 6738:com.google.android.apps.photos/u0a199}
,07-12 11:37:19.507   320   982 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-12 11:37:19.507  6817  6837 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:19.507  6817  6837 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:19.507   320   982 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
07-12 11:37:19.507   320   982 D DrmWidevineDash: Service_Initialize: starts!
07-12 11:37:19.507   320   982 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-12 11:37:19.507   306  1134 D EnterpriseController: netId is 0
07-12 11:37:19.507   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-12 11:37:19.507   320   982 D QSEECOMAPI: : App is not loaded in QSEE
07-12 11:37:19.507   320   982 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
07-12 11:37:19.507   320   982 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-12 11:37:19.507   320   982 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-12 11:37:19.507   320   982 D QSEECOMAPI: : App is not loaded in QSEE
07-12 11:37:19.507   320   982 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
07-12 11:37:19.507   320   982 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-12 11:37:19.507   320   982 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-12 11:37:19.507   320   982 D QSEECOMAPI: : App is not loaded in QSEE
,07-12 11:37:19.517  6817  6837 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6817, getuid(): 10011
,07-12 11:37:19.537   777  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6bf815c u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{88726d4 6738:com.google.android.apps.photos/u0a199}
,07-12 11:37:19.547   320   982 D QSEECOMAPI: : Loaded image: APP id = 3
,07-12 11:37:19.547   320   982 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-12 11:37:19.547   320   982 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaefd6000
07-12 11:37:19.547   320   982 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaefd6000
,07-12 11:37:19.567   320   982 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-12 11:37:19.567   320   982 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-12 11:37:19.567   320   982 D DrmWidevineDash: hlos api version =  10
07-12 11:37:19.567   320   982 D DrmWidevineDash: tz api version =  10
07-12 11:37:19.567   320   982 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-12 11:37:19.567   320   982 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-12 11:37:19.577   777  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9562deb u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{afffa09 6639:com.sec.android.widgetapp.SPlannerAppWidget/u0a148}
,07-12 11:37:19.587  6775  6775 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,07-12 11:37:19.587   320   982 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-12 11:37:19.587   320   982 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-12 11:37:19.587   320   982 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf300924
,07-12 11:37:19.587   320   982 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-12 11:37:19.587   320   982 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-12 11:37:19.587   320   982 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xae3ce1a8, dataLength=8
07-12 11:37:19.587   320   982 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-12 11:37:19.587   777  1678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9562deb u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cae6e6 6724:com.android.calendar/u0a149}
,07-12 11:37:19.607  6775  6775 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-12 11:37:19.617   320   982 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xae42fc00, wrapped_rsa_key_length=1280
,07-12 11:37:19.617   320   982 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-12 11:37:19.617   320   982 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-12 11:37:19.637   320   320 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-12 11:37:19.637   320   320 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-12 11:37:19.637   320   320 I WVCdm   : CdmEngine::GenerateKeyRequest
07-12 11:37:19.637   320   320 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xaea50a00, idLength=0xbeb48cbc
,07-12 11:37:19.647   777  1719 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.samsungapps, Auto Run ON
,07-12 11:37:19.657   777  1300 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9562deb u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1cae6e6 6724:com.android.calendar/u0a149}
,07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-12 11:37:19.677   320   320 D DrmWidevineDash: hlos api version =  10
07-12 11:37:19.677   320   320 D DrmWidevineDash: tz api version =  10
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-12 11:37:19.677   320   320 D WVCdm   : PrepareKeyRequest: nonce=3917505198
07-12 11:37:19.677   320   320 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1dc5800
07-12 11:37:19.677   320   320 D DrmWidevineDash: message_length=1631, signature=0xad453c80, signature_length=3199503764
,07-12 11:37:19.707  6817  6837 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6817, getuid(): 10011
,07-12 11:37:19.737  6828  6828 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-12 11:37:19.737  6828  6828 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:37:19.737  6828  6828 I GAv4    :   adb logcat -s GAv4
,07-12 11:37:19.747  6775  6775 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-12 11:37:19.757   320   320 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-12 11:37:19.777   320   974 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6817)
07-12 11:37:19.777   320   974 I WVCdm   : CdmEngine::CloseSession
07-12 11:37:19.777   320   974 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-12 11:37:19.777   320   974 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-12 11:37:19.777   320   974 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-12 11:37:19.777   320   974 D DrmWidevineDash: Service_Uninitialize: starts!
07-12 11:37:19.777   320   974 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-12 11:37:19.777   320   974 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,07-12 11:37:19.777   320   974 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-12 11:37:19.777   320   974 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-12 11:37:19.807  6828  6828 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.google.android.apps.magazines rsrc of package null
,07-12 11:37:19.817   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{96e9cde: PendingIntentRecord{9989ebf com.google.android.apps.magazines broadcastIntent}}
,07-12 11:37:19.817  6828  6828 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:19.817  6828  6828 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:19.817  6828  6876 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:19.827  6775  6775 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-12 11:37:19.827  6775  6775 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-12 11:37:19.827  6775  6775 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:37:19.847  6817  6837 I qtaguid : Untagging socket 21
,07-12 11:37:19.857  6775  6775 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:37:19.867   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{cab69b6: PendingIntentRecord{7f5a6b7 com.google.android.talk startService}}
,07-12 11:37:19.867   777  1589 I ActivityManager: Killing 5651:com.android.defcontainer/u0a5 (adj 15): DHA:empty #37
,07-12 11:37:19.877  6775  6879 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,07-12 11:37:19.887  6817  6837 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-12 11:37:19.887  6817  6837 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-12 11:37:19.897   777  1718 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,07-12 11:37:19.907  2119  2467 W GCoreFlp: No location to return for getLastLocation()
,07-12 11:37:19.977  3983  6796 D UdcContextInitService: registered all accounts: true
,07-12 11:37:19.997  2119  2492 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-12 11:37:20.047  2119  2573 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-12 11:37:20.057   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{6f1f3fd: PendingIntentRecord{8607679 com.google.android.gms broadcastIntent}}
,07-12 11:37:20.137  6598  6663 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 1032
,07-12 11:37:20.157  6828  6828 I NSApplication: Starting up...
,07-12 11:37:20.167   777   789 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ce8a82 5394:com.google.android.apps.plus/u0a134}
,07-12 11:37:20.177  6598  6663 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,07-12 11:37:20.187   777   790 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b81fb16 6341:com.android.email/u0a162}
,07-12 11:37:20.197  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 11:37:20.197  5909  6016 I jxcore-log: 
,07-12 11:37:20.207  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 11:37:20.207  5909  6016 I jxcore-log: 
,07-12 11:37:20.217  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 11:37:20.217  5909  6016 I jxcore-log: 
,07-12 11:37:20.217  6598  6663 I SA      : [OCP] update openData : PL
,07-12 11:37:20.227   777  1719 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:20.227   777  1420 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:20.247   777   789 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:20.247   777  2222 I ActivityManager: Killing 5733:com.samsung.android.sm.provider/1000 (adj 15): DHA:empty #37
,07-12 11:37:20.257  6598  6663 I SA      : [TPMU] getNetworkMcc : 
,07-12 11:37:20.277   777  1718 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b7dc56 6211:tv.peel.smartremote/u0a170}
,07-12 11:37:20.297  2119  2467 W GCoreFlp: No location to return for getLastLocation()
,07-12 11:37:20.297  6598  6663 I SA      : [SCU] saveMccToPreferece Start
07-12 11:37:20.297  6598  6663 I SA      : [SCU] RegionMCC : 260
07-12 11:37:20.297  6598  6663 I SA      : [SSP] query invoked
,07-12 11:37:20.307   777   789 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.provider, Auto Run ON
,07-12 11:37:20.317  6905  6905 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-12 11:37:20.327  6598  6663 I SA      : [TPMU] GetMccFromDB : null
07-12 11:37:20.327  6598  6663 I SA      : [SCU] getMccFromPreferece mcc = 260
07-12 11:37:20.327  6598  6663 I SA      : [SCU] saveMccToPreferece End
07-12 11:37:20.327  6598  6663 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1344
07-12 11:37:20.327  6598  6663 I SA_HTTPURLCONNECTION: [RC New] Execute end
,07-12 11:37:20.327  6598  6598 I SA      : [OR] GetMyCountryZoneTask mcc = 260
07-12 11:37:20.327  6598  6598 I SA      : [OR] GetMyCountryZoneTask Success
,07-12 11:37:20.367   777  1589 I ActivityManager: Start proc 6912:com.samsung.android.service.travel/u0a177 for broadcast-5 com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver
,07-12 11:37:20.367  6912  6912 E Zygote  : v2
07-12 11:37:20.367  6912  6912 I libpersona: KNOX_SDCARD checking this for 10177
07-12 11:37:20.367  6912  6912 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:20.367  6912  6912 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:37:20.367  6912  6912 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:20.367  6912  6912 E Zygote  : accessInfo : 0
,07-12 11:37:20.367  6912  6912 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.samsung.android.service.travel 
,07-12 11:37:20.377   777  2231 I ActivityManager: Killing 5672:com.sec.android.app.videoplayer/u0a53 (adj 15): DHA:empty #37
,07-12 11:37:20.407  6912  6912 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:20.407  6912  6912 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:20.417  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 11:37:20.417  5909  6016 I jxcore-log: 
,07-12 11:37:20.417   777  1421 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c1ab2a2 6912:com.samsung.android.service.travel/u0a177}
,07-12 11:37:20.427   777   790 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.videoplayer, Auto Run ON
,07-12 11:37:20.437  6912  6912 W ResourcesManager: getTopLevelResources: /system/app/TravelService_K/TravelService_K.apk / 1.0 running in com.samsung.android.service.travel rsrc of package null
,07-12 11:37:20.467  6912  6912 W System  : ClassLoader referenced unknown path: /system/app/TravelService_K/lib/arm
,07-12 11:37:20.477   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{5179b33: PendingIntentRecord{8c8cef0 com.samsung.android.service.travel broadcastIntent}}
,07-12 11:37:20.487  6211  6225 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-12 11:37:20.487  6211  6225 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-12 11:37:20.487  6905  6905 I dex2oat : ----------------------------------------------------
07-12 11:37:20.487  6905  6905 I dex2oat : <SS>: S T A R T I N G . . .
07-12 11:37:20.487  6905  6905 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,07-12 11:37:20.487  6905  6905 I dex2oat : dex2oat took 175.292ms (threads: 4) arena alloc=72KB java alloc=71KB native alloc=1669KB free=1658KB
,07-12 11:37:20.497   777  2212 I ActivityManager: Start proc 6930:com.sec.android.app.samsungapps/u0a39 for broadcast-5 com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver
07-12 11:37:20.497  6930  6930 E Zygote  : v2
,07-12 11:37:20.497  6930  6930 I libpersona: KNOX_SDCARD checking this for 10039
07-12 11:37:20.497  6930  6930 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:20.497  6930  6930 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:37:20.497  6930  6930 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:20.497  6930  6930 E Zygote  : accessInfo : 0
,07-12 11:37:20.497  6930  6930 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,07-12 11:37:20.507  6817  6837 W System  : ClassLoader referenced unknown path: 
,07-12 11:37:20.507   777  1727 I ActivityManager: Killing 6265:com.samsung.hs20provider/u0a202 (adj 15): DHA:empty #37
,07-12 11:37:20.507  6817  6837 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
07-12 11:37:20.507  6211  6225 I System.out: Thread-876(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-12 11:37:20.507  6211  6225 I System.out: Thread-876(ApacheHTTPLog):isSBSettingEnabled false
,07-12 11:37:20.507  6211  6225 I System.out: Thread-876(ApacheHTTPLog):isShipBuild true
07-12 11:37:20.507  6211  6225 I System.out: Thread-876(ApacheHTTPLog):getDebugLevel 0x4f4c
07-12 11:37:20.507  6211  6225 I System.out: Thread-876(ApacheHTTPLog):Smart Bonding Setting is false
07-12 11:37:20.507  6211  6225 I System.out: Thread-876(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-12 11:37:20.517   306  1134 D EnterpriseController: netId is 0
07-12 11:37:20.517   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 10170
,07-12 11:37:20.517  6817  6837 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-12 11:37:20.517  6817  6837 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-12 11:37:20.517  6817  6837 I Adreno-EGL: Build Date: 01/28/16 Thu
07-12 11:37:20.517  6817  6837 I Adreno-EGL: Local Branch: ss
07-12 11:37:20.517  6817  6837 I Adreno-EGL: Remote Branch: 
07-12 11:37:20.517  6817  6837 I Adreno-EGL: Local Patches: 
07-12 11:37:20.517  6817  6837 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:37:20.527  6817  6837 D libEGL  : eglInitialize EGLDisplay = 0xb2f0e264,
07-12 11:37:20.527  6930  6930 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:20.527  6930  6930 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:20.537   777  1588 D ActivityManager: isAutoRunBlockedApp:: com.samsung.hs20provider, Auto Run ON
,07-12 11:37:20.547   777  2235 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{46943ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2d6c69 6930:com.sec.android.app.samsungapps/u0a39}
,07-12 11:37:20.557  6930  6930 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.sec.android.app.samsungapps rsrc of package null
,07-12 11:37:20.597  6930  6930 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-2/lib/arm
,07-12 11:37:20.607  6817  6837 D libEGL  : eglTerminate EGLDisplay = 0xb2f0e2bc
,07-12 11:37:20.607  6817  6837 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-12 11:37:20.607  6817  6837 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-12 11:37:20.607  6817  6837 I Adreno-EGL: Build Date: 01/28/16 Thu
07-12 11:37:20.607  6817  6837 I Adreno-EGL: Local Branch: ss
07-12 11:37:20.607  6817  6837 I Adreno-EGL: Remote Branch: 
07-12 11:37:20.607  6817  6837 I Adreno-EGL: Local Patches: 
07-12 11:37:20.607  6817  6837 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:37:20.607  6817  6837 D libEGL  : eglInitialize EGLDisplay = 0xb2f0e264
,07-12 11:37:20.646  6817  6837 D libEGL  : eglTerminate EGLDisplay = 0xb2f0e2bc
,07-12 11:37:20.676  6930  6930 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-12 11:37:20.726  2119  6946 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:37:20.726  2119  6904 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:37:20.736  6817  6837 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-12 11:37:20.736  6817  6837 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-12 11:37:20.736  6817  6837 I Adreno-EGL: Build Date: 01/28/16 Thu
07-12 11:37:20.736  6817  6837 I Adreno-EGL: Local Branch: ss
07-12 11:37:20.736  6817  6837 I Adreno-EGL: Remote Branch: 
07-12 11:37:20.736  6817  6837 I Adreno-EGL: Local Patches: 
07-12 11:37:20.736  6817  6837 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:37:20.736  6817  6837 D libEGL  : eglInitialize EGLDisplay = 0xb2f0e264
,07-12 11:37:20.756  2119  6946 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:37:20.756  2119  6904 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:37:20.766  2119  2573 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:20.766  2119  2573 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:20.766   306  1134 D EnterpriseController: netId is 0
07-12 11:37:20.766   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-12 11:37:20.776  6817  6837 D libEGL  : eglTerminate EGLDisplay = 0xb2f0e2bc
,07-12 11:37:20.796  2119  6946 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:37:20.796  2119  2573 I qtaguid : Tagging socket 51 with tag 1000040100000000{268436481,0} uid 10011, pid: 2119, getuid(): 10011
,07-12 11:37:20.796  2119  6904 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-12 11:37:20.796  2119  6904 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-12 11:37:20.826  2119  6904 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:37:20.836  2119  2573 I qtaguid : Tagging socket 54 with tag 1000040100000000{268436481,0} uid 10011, pid: 2119, getuid(): 10011
,07-12 11:37:20.856  2119  6798 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:20.856  2119  6798 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:20.856  2119  6798 I qtaguid : Tagging socket 55 with tag 1000040100000000{268436481,0} uid 10011, pid: 2119, getuid(): 10011
,07-12 11:37:20.886  6930  6930 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-12 11:37:20.886  6930  6930 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-12 11:37:20.886  6930  6930 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-12 11:37:20.886  6930  6930 D InitializeManagerStateMachine: exit::IDLE
07-12 11:37:20.886  6930  6930 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-12 11:37:20.896  2119  6798 I qtaguid : Tagging socket 58 with tag 1000040100000000{268436481,0} uid 10011, pid: 2119, getuid(): 10011
,07-12 11:37:20.896   777  1718 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:20.896   777   790 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:20.896  6930  6930 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-12 11:37:20.896  6930  6930 D InitializeManagerStateMachine: exit::NETWORK_CHECK
,07-12 11:37:20.896  6930  6930 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-12 11:37:20.896  6930  6930 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-12 11:37:20.896  6930  6930 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-12 11:37:20.896  6930  6930 D InitializeManagerStateMachine: entry::SUCCESS
07-12 11:37:20.896  6930  6930 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-12 11:37:20.906  6930  6930 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,07-12 11:37:20.906  6930  6930 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-12 11:37:20.906  6930  6930 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
07-12 11:37:20.906   777  1421 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:20.916  6930  6930 D InitializeManagerStateMachine: exit::SUCCESS
,07-12 11:37:20.916  6930  6930 D InitializeManagerStateMachine: entry::IDLE
,07-12 11:37:20.926   777  2222 I ActivityManager: Killing 5364:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,07-12 11:37:20.936   777   789 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,07-12 11:37:20.946   777  1718 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:21.006  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:21.006  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:21.006   306  1134 D EnterpriseController: netId is 0
07-12 11:37:21.006   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-12 11:37:21.046  2119  6904 I qtaguid : Tagging socket 61 with tag fffffca200000000{4294966434,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:21.076  2119  6904 I qtaguid : Tagging socket 64 with tag fffffca200000000{4294966434,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:21.096   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{5f90852: PendingIntentRecord{8607679 com.google.android.gms broadcastIntent}}
,07-12 11:37:21.136  2119  2573 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:37:21.136  2119  2573 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-12 11:37:21.146  2119  2573 V BaseAppContext: GmsRequestQueue started.
,07-12 11:37:21.156  2119  6959 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:21.156  2119  6959 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:21.156   306  1134 D EnterpriseController: netId is 0
07-12 11:37:21.156   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-12 11:37:21.156  2119  6959 I qtaguid : Tagging socket 65 with tag 1000310500000000{268448005,0} uid 10011, pid: 2119, getuid(): 10011
,07-12 11:37:21.186  2119  6959 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} uid 10011, pid: 2119, getuid(): 10011
,07-12 11:37:21.256  6211  6225 I System.out: tr calls detatch()
,07-12 11:37:21.256  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 11:37:21.256  5909  6016 I jxcore-log: 
,07-12 11:37:21.316  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 11:37:21.316  5909  6016 I jxcore-log: 
,07-12 11:37:21.326  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 11:37:21.326  5909  6016 I jxcore-log: 
,07-12 11:37:21.336   777   789 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:21.346  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:21.346  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:21.346  2119  6904 I qtaguid : Tagging socket 61 with tag fffffb4c00000000{4294966092,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:21.416  2119  6959 I qtaguid : Untagging socket 65
,07-12 11:37:21.416  2119  2573 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-12 11:37:21.446   777  1421 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:21.446  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:21.446  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:21.446  2119  6904 I qtaguid : Tagging socket 61 with tag fffff33b00000000{4294964027,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:21.526  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 11:37:21.526  5909  6016 I jxcore-log: 
,07-12 11:37:21.546  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 11:37:21.546  5909  6016 I jxcore-log: 
,07-12 11:37:21.546  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 11:37:21.546  5909  6016 I jxcore-log: 
,07-12 11:37:21.556   777  2212 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:21.556  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 11:37:21.556  5909  6016 I jxcore-log: 
,07-12 11:37:21.566  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:21.566  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:21.566  2119  6904 I qtaguid : Tagging socket 61 with tag 11065c0800000000{285629448,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:21.576  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 11:37:21.576  5909  6016 I jxcore-log: 
,07-12 11:37:21.596  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 11:37:21.596  5909  6016 I jxcore-log: 
,07-12 11:37:21.676   777  1421 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:21.686  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 11:37:21.686  5909  6016 I jxcore-log: 
,07-12 11:37:21.686  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:21.686  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:21.686  2119  6904 I qtaguid : Tagging socket 61 with tag 1106541400000000{285627412,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:21.686  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 11:37:21.686  5909  6016 I jxcore-log: 
,07-12 11:37:21.716  5909  6016 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 11:37:21.716  5909  6016 I jxcore-log: 
,07-12 11:37:21.726  5909  6016 D BluetoothAdapter: STATE_ON
,07-12 11:37:21.726  5909  6016 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-12 11:37:21.726  5909  6016 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-12 11:37:21.726  5909  6016 I jxcore-log: 
,07-12 11:37:21.776  5909  6016 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 11:37:21.776  5909  6016 I jxcore-log: 
,07-12 11:37:21.776  5909  6016 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 11:37:21.776  5909  6016 I jxcore-log: 
,07-12 11:37:21.776  5909  6016 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 11:37:21.776  5909  6016 I jxcore-log: 
,07-12 11:37:21.896   777  1718 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:21.926  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:21.926  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:21.926  2119  6904 I qtaguid : Tagging socket 61 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:22.126   777  2212 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:22.126  2119  6904 W Uploader: UNKNOWN no longer exists, so no auth token.
,07-12 11:37:22.136  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:22.136  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:22.136  2119  6904 I qtaguid : Tagging socket 61 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:22.146  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,07-12 11:37:22.146  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,07-12 11:37:22.146  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
07-12 11:37:22.146  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,07-12 11:37:22.146  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1Gkj0KYZpO99f1rsYZnglZtCc+mJqVQceay8W/Aon4dQ==
07-12 11:37:22.146  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3NyUiHu5cWdT4SPPZ0OxqJQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,07-12 11:37:22.146  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2G1kMmI09JBmwwj0mFkR2L4tvU5wsp5Dwccfz++DFQoQ==
,07-12 11:37:22.146  6625  6625 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2sH9Musae3FSSYRxL/dVLnM4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,07-12 11:37:22.236   777  2235 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:22.236  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:22.236  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:22.236  2119  6904 I qtaguid : Tagging socket 61 with tag 11065fff00000000{285630463,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:22.346   777  1588 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:22.366  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:22.366  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:22.366  2119  6904 I qtaguid : Tagging socket 61 with tag 11065b5800000000{285629272,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:22.466   777   789 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:22.466  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:22.466  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:22.466  2119  6904 I qtaguid : Tagging socket 61 with tag 11065c9100000000{285629585,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:22.526  6357  6357 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:37:22.576   777  1588 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:22.586  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:22.586  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:22.586  2119  6904 I qtaguid : Tagging socket 61 with tag 11065fff00000000{285630463,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:22.706   777  2222 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:22.716  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:22.716  2119  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:22.716  2119  6904 I qtaguid : Tagging socket 61 with tag 11065e2100000000{285629985,0} uid -1, pid: 2119, getuid(): 10011
,07-12 11:37:22.776   777  1336 D ConnectivityService: handlePromptUnvalidated 502
,07-12 11:37:22.876   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{de5d420: PendingIntentRecord{8607679 com.google.android.gms broadcastIntent}}
,07-12 11:37:23.206   777  3303 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-12 11:37:23.216   777  3303 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-12 11:37:23.216   777  3303 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-12 11:37:23.226   777  3303 I System.out: Thread-174(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-12 11:37:23.226   777  3303 I System.out: Thread-174(ApacheHTTPLog):isSBSettingEnabled false
07-12 11:37:23.226   777  3303 I System.out: Thread-174(ApacheHTTPLog):isShipBuild true
07-12 11:37:23.226   777  3303 I System.out: Thread-174(ApacheHTTPLog):getDebugLevel 0x4f4c
07-12 11:37:23.226   777  3303 I System.out: Thread-174(ApacheHTTPLog):Smart Bonding Setting is false
07-12 11:37:23.226   777  3303 I System.out: Thread-174(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-12 11:37:23.226   306  1134 D EnterpriseController: netId is 0
07-12 11:37:23.226   306  1134 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-12 11:37:23.246  2119  6957 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:23.246  2119  6957 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:23.246  2119  6957 I qtaguid : Tagging socket 65 with tag 1000310200000000{268448002,0} uid 10011, pid: 2119, getuid(): 10011
,07-12 11:37:23.436  2119  6957 I qtaguid : Untagging socket 65
,07-12 11:37:23.436  2119  2573 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-12 11:37:23.476  3983  4860 V UdcCtxListenerSrv: handle intent
,07-12 11:37:23.496   777  3303 I System.out: Category Thread calls detatch()
,07-12 11:37:23.706   777  3287 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:24.916  6775  6775 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,07-12 11:37:24.946   777  1589 I ActivityManager: Killing 6308:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,07-12 11:37:25.016   777  1300 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,07-12 11:37:25.376   777  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:25.376   777  1420 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:37:25.376   777  1420 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-12 11:37:25.376   777  1420 D BatteryService: stay LED for charging
07-12 11:37:25.376   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:25.386   777   777 I MotionRecognitionService: Plugged
,07-12 11:37:25.386   777   777 D MotionRecognitionService:   cableConnection= 1
07-12 11:37:25.386   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:37:25.386   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:25.386  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:25.386  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:25.386  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:25.406  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:37:25.406  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:25.416  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-12 11:37:25.416  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-12 11:37:25.416  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-12 11:37:25.446   777  3287 D SSRM:n  : SIOP:: AP = 450, PST = 415, CUR = 450, LCD = 0
,07-12 11:37:25.866   777  1420 I ActivityManager: Killing 6370:com.sec.android.provider.badge/u0a77 (adj 15): DHA:empty #37
,07-12 11:37:25.926   777  1588 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.provider.badge, Auto Run ON
,07-12 11:37:26.526  6357  6357 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:37:26.536  6357  6357 I dhcpcd  : wlan0: no IPv6 Routers available
,07-12 11:37:30.956  6930  6930 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,07-12 11:37:30.956  6930  6930 D PreloadUpdateManagerStateMachine: exit::IDLE
07-12 11:37:30.956  6930  6930 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-12 11:37:30.966  6930  6930 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,07-12 11:37:30.966  6930  6930 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-12 11:37:30.966  6930  6930 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-12 11:37:30.976  6930  6930 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,07-12 11:37:30.976  6930  6930 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-12 11:37:33.736  6775  6805 W Babel   : aye TOOK TOO LONG! (15002ms > 10000ms)
,07-12 11:37:33.786  6775  6775 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-12 11:37:33.816  6775  6807 W Babel   : aye TOOK TOO LONG! (15038ms > 10000ms)
,07-12 11:37:33.826   777  2231 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10116
,07-12 11:37:33.846   777  2235 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-12 11:37:33.856  6775  6775 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-12 11:37:33.856  6775  6775 W Babel   : BAM#gBA: invalid account id: -1
07-12 11:37:33.856  6775  6775 W Babel   : BAM#gBA: invalid account id: -1
07-12 11:37:33.856  6775  6775 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-12 11:37:33.856   777  1589 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-12 11:37:34.356  6775  6855 W Babel   : aye TOOK TOO LONG! (15001ms > 10000ms)
,07-12 11:37:35.446   777   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:35.446   777   789 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:37:35.446   777   789 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:37:35.446   777   789 D BatteryService: stay LED for charging
,07-12 11:37:35.456   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:35.466   777   777 I MotionRecognitionService: Plugged
,07-12 11:37:35.466   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:37:35.466   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:37:35.466   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:35.476  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:35.486  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:35.486  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:35.516  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-12 11:37:35.516  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-12 11:37:35.516  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-12 11:37:35.526   777  3287 D SSRM:n  : SIOP:: AP = 400, PST = 411, CUR = 450, LCD = 0
,07-12 11:37:35.526  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:37:35.526  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:38.266   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:37:40.776   777  1594 E Watchdog: !@Sync 4 [07-12 11:37:40.787]
,07-12 11:37:41.866  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:37:44.756   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:37:44.756   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:37:44.756   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:37:45.586   777  3287 D SSRM:n  : SIOP:: AP = 360, PST = 403, CUR = 450, LCD = 0
,07-12 11:37:48.136   777  1240 V AlarmManager: Expired Alarm result :4
,07-12 11:37:48.226   777  1718 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:48.226   777  1718 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:37:48.226   777  1718 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:37:48.226   777  1718 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 777) 
,07-12 11:37:48.236   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:48.236   777   777 I MotionRecognitionService: Plugged
,07-12 11:37:48.236   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:37:48.236   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:37:48.236   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:48.246   777  1718 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,07-12 11:37:48.256  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:48.256  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:48.256  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:48.266  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:48.266   777  1718 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-12 11:37:48.276   777  1718 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-12 11:37:48.286   777  1718 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-12 11:37:48.286  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:48.296  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:48.296  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:48.306   777  1718 D BatteryService: turn on LED for fully charged
,07-12 11:37:48.306  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:37:48.306  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:48.656   777   921 D LightsService: [SvcLED]  onSensorChanged::light value = 31
,07-12 11:37:48.666   777   921 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-12 11:37:48.676   777   921 D SensorManager: unregisterListener ::   
,07-12 11:37:48.676   777   921 D lights  : led_pattern : 5 +
,07-12 11:37:48.686   777   921 D lights  : led_pattern : 5 -
,07-12 11:37:48.686   777   921 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-12 11:37:48.686   777   921 V AlarmManager:  remove PendingIntent] PendingIntent{8d40e9f: PendingIntentRecord{23fbbb5 android broadcastIntent}}
,07-12 11:37:48.956  3983  7023 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-12 11:37:48.966   777   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 156814, reason: UserStart, SyncResult: databaseError: true stats []
,07-12 11:37:48.966   777   856 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 221773, reason: UserStart
,07-12 11:37:48.986  3068  3083 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-12 11:37:48.986  3068  3083 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-12 11:37:48.996  3068  3083 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-12 11:37:48.996  3068  3083 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-12 11:37:48.996   777  1678 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-12 11:37:49.116   777   787 I art     : Background partial concurrent mark sweep GC freed 42971(2MB) AllocSpace objects, 29(720KB) LOS objects, 27% free, 41MB/57MB, paused 1.647ms total 118.365ms
,07-12 11:37:55.646   777  3287 D SSRM:n  : SIOP:: AP = 340, PST = 393, CUR = 450, LCD = 0
,07-12 11:37:58.266   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:37:58.316   777  2235 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:58.316   777  2235 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:37:58.326   777  2235 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:37:58.326   777  2235 D BatteryService: stay LED for fully charged
,07-12 11:37:58.326   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:58.336   777   777 I MotionRecognitionService: Plugged
,07-12 11:37:58.346   777   777 D MotionRecognitionService:   cableConnection= 1
07-12 11:37:58.346   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:37:58.346   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:58.346  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:58.346  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:58.346  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:58.366  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:37:58.366  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:58.376  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:58.376  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:58.376  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:59.986   777  1240 V AlarmManager: Expired Alarm result :8
,07-12 11:38:04.596  2119  3170 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:38:05.706   777  3287 D SSRM:n  : SIOP:: AP = 330, PST = 386, CUR = 450, LCD = 0
,07-12 11:38:08.406   777  2231 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:08.406   777  2231 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:38:08.406   777  2231 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:38:08.416   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:08.426   777   777 I MotionRecognitionService: Plugged
,07-12 11:38:08.426   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:38:08.426   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:38:08.426   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:38:08.436   777  2231 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-12 11:38:08.436   777  2231 D BatteryService: stay LED for fully charged
,07-12 11:38:08.446  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:08.446  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:08.446  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:08.466  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:08.466  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:38:08.466  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:08.466  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:08.466  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:10.786   777  1594 E Watchdog: !@Sync 5 [07-12 11:38:10.794]
,07-12 11:38:10.996   777  3288 I ActivityManager: Start proc 7028:com.samsung.android.sm.provider/1000 for content provider com.samsung.android.sm.provider/com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider
,07-12 11:38:11.006  7028  7028 E Zygote  : v2
,07-12 11:38:11.006  7028  7028 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:38:11.006  7028  7028 I libpersona: KNOX_SDCARD not a persona
,07-12 11:38:11.016  7028  7028 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:38:11.016  7028  7028 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:38:11.016  7028  7028 E Zygote  : accessInfo : 0
,07-12 11:38:11.056  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:38:11.056  7028  7028 D ActivityThread: Added TimaKeyStore provider
,07-12 11:38:11.076  7028  7028 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManagerProvider/SmartManagerProvider.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-12 11:38:11.106  7028  7028 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManagerProvider/lib/arm
,07-12 11:38:11.146   777   777 I ActivityManager: Killing 6321:com.google.android.apps.maps/u0a121 (adj 15): DHA:empty #37
,07-12 11:38:11.156   777  3288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,07-12 11:38:11.166   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef532f3 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{edeebb0 7028:com.samsung.android.sm.provider/1000}
,07-12 11:38:11.256   777  3288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-12 11:38:11.256   777  1588 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.maps, Auto Run ON
,07-12 11:38:11.266   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c72a1ae u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{edeebb0 7028:com.samsung.android.sm.provider/1000}
,07-12 11:38:15.776   777  3287 D SSRM:n  : SIOP:: AP = 330, PST = 383, CUR = 450, LCD = 0
,07-12 11:38:18.276   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:38:18.486   777   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:18.496   777   789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:38:18.496   777   789 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:38:18.496   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:18.516   777   777 I MotionRecognitionService: Plugged
,07-12 11:38:18.516   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:38:18.516   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:38:18.516   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:38:18.526   777   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-12 11:38:18.526   777   789 D BatteryService: stay LED for fully charged
,07-12 11:38:18.536  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:18.536  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:18.536  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:18.556  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:18.556  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:38:18.556  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:18.556  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:18.556  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:20.776   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:38:20.776   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:38:20.776   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:38:25.846   777  3287 D SSRM:n  : SIOP:: AP = 320, PST = 379, CUR = 450, LCD = 0
,07-12 11:38:28.576   777  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:35.906   777  3287 D SSRM:n  : SIOP:: AP = 320, PST = 371, CUR = 450, LCD = 0
,07-12 11:38:38.276   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:38:38.646   777  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:38.656   777  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:38:38.656   777  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:38:38.656   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:38.676   777   777 I MotionRecognitionService: Plugged
,07-12 11:38:38.676   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:38:38.676   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:38:38.676   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:38:38.686   777  1421 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-12 11:38:38.686   777  1421 D BatteryService: stay LED for fully charged
,07-12 11:38:38.686  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:38.686  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:38.686  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:38.706  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:38.706  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:38:38.716  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:38.716  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:38.716  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:40.796   777  1594 E Watchdog: !@Sync 6 [07-12 11:38:40.802]
,07-12 11:38:40.876   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:38:40.876   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:38:40.876   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:38:41.876  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:38:45.966   777  3287 D SSRM:n  : SIOP:: AP = 310, PST = 359, CUR = 450, LCD = 0
,07-12 11:38:48.736   777  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:48.736   777  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:38:48.736   777  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:38:48.746   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:48.756   777   777 I MotionRecognitionService: Plugged
,07-12 11:38:48.756   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:38:48.756   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:38:48.766   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:38:48.766   777  1589 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-12 11:38:48.766   777  1589 D BatteryService: stay LED for fully charged
,07-12 11:38:48.786  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:48.786  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:48.786  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:48.796  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:48.796  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:38:48.806  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:48.806  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:48.806  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:56.016   777  3287 D SSRM:n  : SIOP:: AP = 310, PST = 347, CUR = 450, LCD = 0
,07-12 11:38:58.286   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:38:58.806   777  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:06.076   777  3287 D SSRM:n  : SIOP:: AP = 310, PST = 333, CUR = 450, LCD = 0
,07-12 11:39:08.886   777  1727 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:08.896   777  1727 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:39:08.896   777  1727 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:39:08.896   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:39:08.916   777   777 I MotionRecognitionService: Plugged
,07-12 11:39:08.916   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:39:08.916   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:39:08.916   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:39:08.926   777  1727 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-12 11:39:08.926   777  1727 D BatteryService: stay LED for fully charged
,07-12 11:39:08.936  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:39:08.936  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:08.936  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:08.956  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:39:08.956  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:39:08.956  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:08.966  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:08.966  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:10.796   777  1594 E Watchdog: !@Sync 7 [07-12 11:39:10.808]
,07-12 11:39:16.146   777  3287 D SSRM:n  : SIOP:: AP = 310, PST = 324, CUR = 450, LCD = 0
,07-12 11:39:18.286   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:39:18.976   777   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:18.976   777   789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:39:18.976   777   789 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:39:18.986   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:39:18.996   777   777 I MotionRecognitionService: Plugged
,07-12 11:39:18.996   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:39:18.996   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:39:19.006   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:39:19.006   777   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-12 11:39:19.006   777   789 D BatteryService: stay LED for fully charged
,07-12 11:39:19.026  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:39:19.026  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:39:19.026  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:19.046  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:39:19.046  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:39:19.056  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:19.056  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:19.056  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:26.206   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 318, CUR = 450, LCD = 0
,07-12 11:39:29.046   777  2231 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:36.266   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 314, CUR = 450, LCD = 0
,07-12 11:39:38.286   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:39:39.126   777  2222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:40.806   777  1594 E Watchdog: !@Sync 8 [07-12 11:39:40.812]
,07-12 11:39:41.886  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:39:46.326   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 311, CUR = 450, LCD = 0
,07-12 11:39:49.226   777  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:49.236   777  1420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:39:49.236   777  1420 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:39:49.236   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:39:49.246   777   777 I MotionRecognitionService: Plugged
,07-12 11:39:49.246   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:39:49.246   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:39:49.246   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:39:49.256   777  1420 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms
,07-12 11:39:49.256   777  1420 D BatteryService: stay LED for fully charged
,07-12 11:39:49.266  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:39:49.266  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:39:49.266  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:49.296  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:39:49.296  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:39:49.296  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:49.296  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:49.296  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:56.386   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450, LCD = 0
,07-12 11:39:58.296   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:06.446   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450, LCD = 0
,07-12 11:40:10.806   777  1594 E Watchdog: !@Sync 9 [07-12 11:40:10.816]
,07-12 11:40:16.506   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,07-12 11:40:18.296   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:19.296   777  2231 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:40:19.296   777  2231 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:40:19.296   777  2231 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:40:19.306   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:40:19.316   777   777 I MotionRecognitionService: Plugged
,07-12 11:40:19.316   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:40:19.316   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:40:19.326   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:40:19.326   777  2231 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-12 11:40:19.326   777  2231 D BatteryService: stay LED for fully charged
,07-12 11:40:19.336  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:40:19.336  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:40:19.336  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:40:19.356  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:40:19.356  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:40:19.356  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:19.366  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:19.366  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:25.566   777  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 11:40:25.576   777  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:40:25.586   777  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:40:25.606   777  1233 I TLC_TIMA_PKM_initialize: initializing...
,07-12 11:40:25.606   777  1233 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-12 11:40:25.606   777  1233 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-12 11:40:25.606   777  1233 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-12 11:40:25.616   777  1233 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-12 11:40:25.616   777  1233 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-12 11:40:25.616   777  1233 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-12 11:40:25.616   777  1233 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-12 11:40:25.626   777  1233 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-12 11:40:25.626   777  1233 D QSEECOMAPI: : App is not loaded in QSEE
,07-12 11:40:25.656   777  1233 D QSEECOMAPI: : Loaded image: APP id = 3
,07-12 11:40:25.656   777  1233 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-12 11:40:25.666   777  1233 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-12 11:40:26.566   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,07-12 11:40:28.986   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-12 11:40:28.986   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:40:28.996   777  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:40:29.006   777  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:40:36.636   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-12 11:40:38.296   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:40.816   777  1594 E Watchdog: !@Sync 10 [07-12 11:40:40.820]
,07-12 11:40:41.966  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:40:42.146  1734  1794 E ContactsProvider_EventLog: Flush buffer to file cnt : 8 size : 1Kb duration : 172ms lastUpdatedAfter : 173121ms
,07-12 11:40:46.696   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-12 11:40:49.356   777   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:40:49.366   777   789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:40:49.366   777   789 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:40:49.376   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:40:49.386   777   777 I MotionRecognitionService: Plugged
,07-12 11:40:49.386   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:40:49.386   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:40:49.396   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:40:49.396   777   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-12 11:40:49.406   777   789 D BatteryService: stay LED for fully charged
,07-12 11:40:49.416  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:40:49.426  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:40:49.426  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:40:49.446  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:40:49.446  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:40:49.456  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:49.456  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:49.456  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:56.756   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-12 11:40:58.306   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:59.996   777  1240 V AlarmManager: Expired Alarm result :8
,07-12 11:40:59.996   777  1240 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=350072 batch.start=363598
,07-12 11:41:00.016  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-12 11:41:00.016  1386  1386 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-12 11:41:00.016  1386  1386 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:41:00.086  1386  1386 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-12 11:41:00.096  1386  1386 D SecKeyguardClockView: HomeTimezone(): 1
,07-12 11:41:00.096  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:41:00.106  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:41:00.106  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:41:00.106  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:41:00.106  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:41:00.106  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:41:00.106  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:41:00.176  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:41:06.806   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-12 11:41:10.816   777  1594 E Watchdog: !@Sync 11 [07-12 11:41:10.825]
,07-12 11:41:13.516   777  1240 V AlarmManager: Expired Alarm result :4
,07-12 11:41:13.556  6172  6172 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-12 11:41:13.556  6172  6172 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-12 11:41:13.586  6172  6172 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-12 11:41:13.616   777  1240 I ActivityManager: Start proc 7087:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-12 11:41:13.626  7087  7087 E Zygote  : v2
,07-12 11:41:13.626  7087  7087 I libpersona: KNOX_SDCARD checking this for 1000
,07-12 11:41:13.626  7087  7087 I libpersona: KNOX_SDCARD not a persona
,07-12 11:41:13.626  7087  7087 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:41:13.626  7087  7087 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:41:13.636  7087  7087 E Zygote  : accessInfo : 0
,07-12 11:41:13.666  7087  7087 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:41:13.666  7087  7087 D ActivityThread: Added TimaKeyStore provider
,07-12 11:41:13.686  7087  7087 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,07-12 11:41:13.706  7087  7087 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-12 11:41:13.736   777  2212 I ActivityManager: Killing 5422:com.android.vending/u0a29 (adj 15): DHA:empty #37
,07-12 11:41:13.766   777  1719 D ActivityManager: isAutoRunBlockedApp:: com.android.vending, Auto Run ON
,07-12 11:41:16.896   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-12 11:41:17.446   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:41:17.446   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:41:17.446   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:41:17.466  6172  6172 I wpa_supplicant: nl80211: Received scan results (10 BSSes)
07-12 11:41:17.466  6172  6172 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
07-12 11:41:17.476   306  1131 D Netd    : Iface wlan0 link up
,07-12 11:41:17.496   777   866 D Tethering: interfaceLinkStateChanged wlan0, true
,07-12 11:41:17.516   777   866 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:41:17.516   777  1328 D WifiP2pService: InactiveState{ what=147461 }
,07-12 11:41:17.516   777  1328 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-12 11:41:17.516   777  1328 D WifiP2pService: DefaultState{ what=147461 }
,07-12 11:41:17.576   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e1880c8 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a073ef 1386:com.android.systemui/u0a58}
,07-12 11:41:18.306   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:41:19.426   777  1588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:41:19.426   777  1588 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:41:19.426   777  1588 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:41:19.436   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:41:19.446   777   777 I MotionRecognitionService: Plugged
,07-12 11:41:19.446   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:41:19.456   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:41:19.456   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:41:19.456   777  1588 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-12 11:41:19.466   777  1588 D BatteryService: stay LED for fully charged
,07-12 11:41:19.486  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:41:19.486  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:41:19.486  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:41:19.496  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:41:19.496  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:41:19.506  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:19.506  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:41:19.506  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:26.946   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-12 11:41:36.996   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-12 11:41:38.316   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:41:38.996   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:41:38.996   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:41:38.996   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:41:40.826   777  1594 E Watchdog: !@Sync 12 [07-12 11:41:40.830]
,07-12 11:41:42.156  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:41:47.046   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-12 11:41:49.486   777  2231 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:41:49.496   777  2231 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:41:49.496   777  2231 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:41:49.496   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:41:49.516   777   777 I MotionRecognitionService: Plugged
,07-12 11:41:49.516   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:41:49.516   777  2231 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-12 11:41:49.526   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:41:49.526   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:41:49.536   777  2231 D BatteryService: stay LED for fully charged
,07-12 11:41:49.536  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:41:49.536  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:41:49.536  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:41:49.556  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:41:49.556  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:41:49.566  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:49.566  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:41:49.566  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:57.096   777  3287 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-12 11:41:58.316   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:41:59.996   777  1240 V AlarmManager: Expired Alarm result :8
,07-12 11:42:07.156   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450, LCD = 0
,07-12 11:42:10.826   777  1594 E Watchdog: !@Sync 13 [07-12 11:42:10.837]
,07-12 11:42:17.206   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,07-12 11:42:18.316   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:42:19.556   777   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:19.566   777   789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:42:19.566   777   789 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:42:19.566   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:42:19.586   777   777 I MotionRecognitionService: Plugged
,07-12 11:42:19.586   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:42:19.586   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:42:19.586   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:42:19.596   777   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-12 11:42:19.596   777   789 D BatteryService: stay LED for fully charged
,07-12 11:42:19.606  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:42:19.606  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:42:19.606  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:42:19.636  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:19.636  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:42:19.636  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:19.646  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:42:19.646  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:42:19.846   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:42:19.846   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:42:19.846   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:42:27.266   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450, LCD = 0
,07-12 11:42:37.316   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,07-12 11:42:38.326   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:42:38.516   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:42:38.516   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:42:38.516   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:42:40.836   777  1594 E Watchdog: !@Sync 14 [07-12 11:42:40.841]
,07-12 11:42:42.236  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:42:47.376   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,07-12 11:42:49.626   777  1727 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:49.626   777  1727 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:42:49.626   777  1727 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:42:49.636   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:42:49.646   777   777 I MotionRecognitionService: Plugged
,07-12 11:42:49.646   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:42:49.656   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:42:49.656   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:42:49.656   777  1727 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-12 11:42:49.666   777  1727 D BatteryService: stay LED for fully charged
,07-12 11:42:49.686  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:42:49.686  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:42:49.686  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:42:49.696  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:42:49.696  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:42:49.706  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:49.706  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:49.706  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:57.436   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,07-12 11:42:58.326   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:43:07.496   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,07-12 11:43:10.836   777  1594 E Watchdog: !@Sync 15 [07-12 11:43:10.845]
,07-12 11:43:15.336   364   364 I bootchecker: bootchecker wake up!!
,07-12 11:43:17.556   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-12 11:43:18.326   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:43:19.696   777  2212 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:43:19.696   777  2212 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:43:19.696   777  2212 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:43:19.706   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:43:19.716   777   777 I MotionRecognitionService: Plugged
,07-12 11:43:19.716   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:43:19.716   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:43:19.726   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:43:19.726   777  2212 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-12 11:43:19.726   777  2212 D BatteryService: stay LED for fully charged
,07-12 11:43:19.736  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:43:19.736  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:43:19.736  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:43:19.756  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:43:19.756  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:43:19.756  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:19.766  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:43:19.766  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:27.616   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-12 11:43:37.666   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:43:38.336   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:43:40.846   777  1594 E Watchdog: !@Sync 16 [07-12 11:43:40.849]
,07-12 11:43:42.306  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:43:42.466  1734  1794 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 137ms lastUpdatedAfter : 180317ms
,07-12 11:43:47.726   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:43:49.766   777  2231 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:43:49.766   777  2231 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:43:49.776   777  2231 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:43:49.776   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:43:49.786   777   777 I MotionRecognitionService: Plugged
,07-12 11:43:49.796   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:43:49.796   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:43:49.796   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:43:49.806   777  2231 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-12 11:43:49.806   777  2231 D BatteryService: stay LED for fully charged
,07-12 11:43:49.816  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:43:49.816  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:43:49.816  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:43:49.846  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:43:49.846  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:43:49.846  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:49.846  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:43:49.846  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:57.806   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:43:58.336   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:07.866   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:44:10.846   777  1594 E Watchdog: !@Sync 17 [07-12 11:44:10.854]
,07-12 11:44:17.926   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:44:18.346   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:19.826   777  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:44:27.996   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:44:38.056   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:44:38.346   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:40.846   777  1594 E Watchdog: !@Sync 18 [07-12 11:44:40.858]
,07-12 11:44:42.506  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:44:48.106   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:44:49.886   777  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:44:49.896   777  1678 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:44:49.896   777  1678 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:44:49.896   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:44:49.906   777   777 I MotionRecognitionService: Plugged
,07-12 11:44:49.916   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:44:49.916   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:44:49.916   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:44:49.926   777  1678 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-12 11:44:49.926   777  1678 D BatteryService: stay LED for fully charged
,07-12 11:44:49.936  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:44:49.936  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:44:49.936  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:44:49.956  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:44:49.956  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:44:49.956  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:49.956  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:49.956  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:58.166   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:44:58.346   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:45:08.216   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:45:10.856   777  1594 E Watchdog: !@Sync 19 [07-12 11:45:10.866]
,07-12 11:45:18.276   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:45:18.356   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:45:19.956   777  1588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:45:19.956   777  1588 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:45:19.956   777  1588 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:45:19.966   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:45:19.976   777   777 I MotionRecognitionService: Plugged
,07-12 11:45:19.976   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:45:19.986   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:45:19.986   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:45:19.986   777  1588 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-12 11:45:19.986   777  1588 D BatteryService: stay LED for fully charged
,07-12 11:45:19.996  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:45:20.006  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:45:20.006  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:45:20.036  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:20.036  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:45:20.036  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:20.036  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:45:20.046  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:45:25.566   777  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 11:45:25.566   777  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:45:25.566   777  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:45:27.036   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-12 11:45:27.036   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:45:27.046   777  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:45:27.056   777  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:45:28.326   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:45:38.356   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:45:38.386   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:45:40.866   777  1594 E Watchdog: !@Sync 20 [07-12 11:45:40.870]
,07-12 11:45:42.536  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.096   777   856 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.106   777   856 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
,07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-12 11:45:44.116   777   856 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:44.126   777   856 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:44.216   777   912 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-12 11:45:44.216   777   912 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-12 11:45:48.446   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:45:50.026   777  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:45:50.026   777  1420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:45:50.026   777  1420 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:45:50.036   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:45:50.046   777   777 I MotionRecognitionService: Plugged
,07-12 11:45:50.046   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:45:50.046   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:45:50.056   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:45:50.056   777  1420 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-12 11:45:50.056   777  1420 D BatteryService: stay LED for fully charged
,07-12 11:45:50.076  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:45:50.076  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:45:50.086  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:45:50.096  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:45:50.096  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:45:50.106  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:50.106  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:50.106  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:58.356   777  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:45:58.506   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:46:08.556   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:46:10.866   777  1594 E Watchdog: !@Sync 21 [07-12 11:46:10.875]
,07-12 11:46:14.406   777  1240 V AlarmManager: Expired Alarm result :8
,07-12 11:46:18.606   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:46:20.096   777  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:46:20.096   777  1719 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:46:20.096   777  1719 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:46:20.106   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:46:20.116   777   777 I MotionRecognitionService: Plugged
,07-12 11:46:20.116   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:46:20.116   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:46:20.116   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:46:20.126   777  1719 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-12 11:46:20.126   777  1719 D BatteryService: stay LED for fully charged
,07-12 11:46:20.136  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:46:20.136  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:46:20.136  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:46:20.156  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:46:20.156  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:46:20.156  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:20.156  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:20.166  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:24.716   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:46:24.716   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:46:24.716   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:46:24.736   777  1718 I ActivityManager: Killing 4435:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 625s, lastActivityTime 625s
,07-12 11:46:24.736   777  1718 I ActivityManager: Killing 3777:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 629s, lastActivityTime 629s
,07-12 11:46:24.796   293   293 I ServiceManager: service 'AtCmdFwd' died
,07-12 11:46:24.806   371  4908 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-12 11:46:24.806   371  4908 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:46:24.806   777  2235 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-12 11:46:24.806   777  2235 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-12 11:46:24.806   777  2235 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-12 11:46:24.836   777  1300 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,07-12 11:46:24.836   777  1300 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-12 11:46:24.836   777  1300 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10974ms
,07-12 11:46:25.806   371  4908 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:46:25.886   777   861 I ActivityManager: Start proc 7118:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-12 11:46:25.886  7118  7118 E Zygote  : v2
,07-12 11:46:25.886  7118  7118 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:46:25.886  7118  7118 I libpersona: KNOX_SDCARD not a persona
,07-12 11:46:25.886  7118  7118 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:46:25.886  7118  7118 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:46:25.896  7118  7118 E Zygote  : accessInfo : 0
,07-12 11:46:25.936  7118  7118 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:46:25.936  7118  7118 D ActivityThread: Added TimaKeyStore provider
,07-12 11:46:25.956  7118  7118 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-12 11:46:25.976  7118  7118 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-12 11:46:25.976  7118  7118 D AtFwdService: onCreate method
,07-12 11:46:25.976  7118  7118 I AtFwdService: Instantiate AtCmdFwd Service
,07-12 11:46:25.996  7118  7130 D AtCkpdCmdHandler: De-queing command
,07-12 11:46:28.676   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:46:35.876   777   861 I ActivityManager: Start proc 7132:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-12 11:46:35.886  7132  7132 E Zygote  : v2
,07-12 11:46:35.886  7132  7132 I libpersona: KNOX_SDCARD checking this for 10026
07-12 11:46:35.886  7132  7132 I libpersona: KNOX_SDCARD not a persona
,07-12 11:46:35.886  7132  7132 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:46:35.886  7132  7132 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:46:35.896  7132  7132 E Zygote  : accessInfo : 0
,07-12 11:46:35.896  7132  7132 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-12 11:46:35.936  7132  7132 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:46:35.936  7132  7132 D ActivityThread: Added TimaKeyStore provider
,07-12 11:46:35.956  7132  7132 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-12 11:46:35.986  7132  7132 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-12 11:46:35.996  7132  7132 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-12 11:46:35.996  7132  7132 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-12 11:46:38.726   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:46:39.756   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:46:39.756   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:46:39.756   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:46:40.876   777  1594 E Watchdog: !@Sync 22 [07-12 11:46:40.879]
,07-12 11:46:42.656  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:46:42.826  1734  1794 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 154ms lastUpdatedAfter : 180368ms
,07-12 11:46:48.786   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:46:50.156   777  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:46:58.836   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:47:08.896   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:47:10.876   777  1594 E Watchdog: !@Sync 23 [07-12 11:47:10.886]
,07-12 11:47:18.946   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:47:20.216   777  1588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:47:20.226   777  1588 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:47:20.226   777  1588 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:47:20.226   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:47:20.246   777   777 I MotionRecognitionService: Plugged
,07-12 11:47:20.246   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:47:20.246   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:47:20.246   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:47:20.246   777  1588 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-12 11:47:20.256   777  1588 D BatteryService: stay LED for fully charged
,07-12 11:47:20.276  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:47:20.276  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:47:20.276  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:47:20.296  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:47:20.296  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:47:20.306  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:20.306  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:20.306  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:28.996   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:47:39.056   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:47:40.886   777  1594 E Watchdog: !@Sync 24 [07-12 11:47:40.890]
,07-12 11:47:42.956  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:47:48.686   777  1240 V AlarmManager: Expired Alarm result :8
,07-12 11:47:49.106   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:47:50.286   777  1718 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:47:50.296   777  1718 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:47:50.296   777  1718 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:47:50.296   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:47:50.316   777   777 I MotionRecognitionService: Plugged
,07-12 11:47:50.326   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:47:50.326   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:47:50.326   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:47:50.336   777  1718 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 39ms
,07-12 11:47:50.336   777  1718 D BatteryService: stay LED for fully charged
,07-12 11:47:50.336  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:47:50.336  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:47:50.336  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:47:50.356  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:47:50.356  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:47:50.356  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:50.366  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:50.366  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:59.216   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:48:09.286   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:48:10.886   777  1594 E Watchdog: !@Sync 25 [07-12 11:48:10.897]
,07-12 11:48:19.366   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:48:20.356   777  2231 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:48:20.356   777  2231 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:48:20.356   777  2231 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:48:20.366   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:48:20.376   777   777 I MotionRecognitionService: Plugged
,07-12 11:48:20.376   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:48:20.386   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:48:20.386   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:48:20.386   777  2231 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-12 11:48:20.386   777  2231 D BatteryService: stay LED for fully charged
,07-12 11:48:20.386  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:48:20.386  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:48:20.386  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:48:20.406  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:48:20.406  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:48:20.416  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:20.416  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:20.416  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:29.416   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:48:39.476   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:48:40.896   777  1594 E Watchdog: !@Sync 26 [07-12 11:48:40.903]
,07-12 11:48:42.976  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:48:44.346   777  2249 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-12 11:48:44.346   777  2249 V MARsPolicyManager: updateSMDBValues
,07-12 11:48:44.346   777   908 E MARsDBManager: updateDBAll : begin --size 0
,07-12 11:48:44.356   777   908 E MARsDBManager: updateDBAll : end
,07-12 11:48:49.536   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:48:50.426   777  2235 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:48:59.606   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:49:09.666   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:49:10.896   777  1594 E Watchdog: !@Sync 27 [07-12 11:49:10.907]
,07-12 11:49:19.726   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:49:20.496   777  2222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:49:29.796   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:49:32.826   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:49:32.826   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:49:32.826   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:49:32.846   777  1678 I ActivityManager: Killing 3675:com.sec.spp.push/u0a37 (adj 5): SSR - service for lastStateTime 817s, lastActivityTime 731s
,07-12 11:49:32.846   777  1678 I ActivityManager: Killing 1520:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 808s, lastActivityTime 734s
,07-12 11:49:32.856   777  1678 I ActivityManager: Killing 1852:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 829s, lastActivityTime 736s
,07-12 11:49:32.946   777  1727 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,07-12 11:49:32.946   777  1727 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,07-12 11:49:32.966   777  1719 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,07-12 11:49:32.966   777  1719 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-12 11:49:32.966   777  1719 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,07-12 11:49:32.976  5474  5474 D HealthConsole: Service for HealthDataStore is disconnected
,07-12 11:49:32.976   777  2231 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,07-12 11:49:32.976   777  2231 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-12 11:49:32.976   777  2231 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10983ms
07-12 11:49:32.976   777  2231 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-12 11:49:32.976   777  2231 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 20983ms
,07-12 11:49:33.006  7164  7164 E Zygote  : v2
07-12 11:49:33.006  7164  7164 I libpersona: KNOX_SDCARD checking this for 10034
07-12 11:49:33.006  7164  7164 I libpersona: KNOX_SDCARD not a persona
,07-12 11:49:33.006  7164  7164 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-12 11:49:33.006   777  1727 I ActivityManager: Start proc 7164:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
07-12 11:49:33.006  7164  7164 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:49:33.006  7164  7164 E Zygote  : accessInfo : 0
,07-12 11:49:33.006  7164  7164 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-12 11:49:33.036  7164  7164 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:49:33.036  7164  7164 D ActivityThread: Added TimaKeyStore provider
,07-12 11:49:33.046  7164  7164 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-12 11:49:33.106  7164  7164 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-12 11:49:33.116  7164  7164 I MultiDex: VM with version 2.1.0 has multidex support
,07-12 11:49:33.116  7164  7164 I MultiDex: install
07-12 11:49:33.116  7164  7164 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-12 11:49:33.116  7164  7164 I MultiDex: install
07-12 11:49:33.116  7164  7164 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:49:33.196  7180  7180 E Zygote  : v2
07-12 11:49:33.196  7180  7180 I libpersona: KNOX_SDCARD checking this for 10016
07-12 11:49:33.196  7180  7180 I libpersona: KNOX_SDCARD not a persona
,07-12 11:49:33.196  7180  7180 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:49:33.196  7180  7180 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:49:33.196   777  2231 I ActivityManager: Start proc 7180:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,07-12 11:49:33.196  7180  7180 E Zygote  : accessInfo : 0
07-12 11:49:33.196  7180  7180 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,07-12 11:49:33.236  7180  7180 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:49:33.236  7180  7180 D ActivityThread: Added TimaKeyStore provider
,07-12 11:49:33.256  7180  7180 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,07-12 11:49:33.286  7164  7164 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-12 11:49:33.286  7164  7164 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-12 11:49:33.306   777  1588 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,07-12 11:49:33.306  1386  1386 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-12 11:49:33.306   777  1421 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,07-12 11:49:33.306   777  1589 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,07-12 11:49:33.316   777  1719 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,07-12 11:49:33.326  1386  1386 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{e77786c VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
07-12 11:49:33.326  1386  1386 D AdaptiveEventManager: M updateContainers()
07-12 11:49:33.326  1386  1386 D AdaptiveEventContainerSmall: C updatePedoContainer()
07-12 11:49:33.326  1386  1386 D AdaptiveEventContainerSmall: handlePedoUpdate()
07-12 11:49:33.326  1386  1386 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-12 11:49:33.346  7164  7164 I Health.HealthService: HealthService: onCreate() start (7164)
,07-12 11:49:33.486  5474  5474 D HealthDataStore: Service for HealthDataStore is connected
,07-12 11:49:33.506  5474  5474 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-12 11:49:33.506   777  1719 I ActivityManager: Killing 6453:com.android.exchange/u0a163 (adj 15): DHA:empty #37
,07-12 11:49:33.546  5474  5474 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-12 11:49:33.546  5474  5474 E HealthDataStore: disconnectService: Context instance is invalid
,07-12 11:49:33.556   777  2235 D ActivityManager: isAutoRunBlockedApp:: com.android.exchange, Auto Run ON
,07-12 11:49:33.586  7164  7164 D HealthDataStore: Service for HealthDataStore is connected
,07-12 11:49:33.586  7164  7164 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-12 11:49:33.586  7164  7164 D HealthConsole: Service for HealthDataConsole is connected
,07-12 11:49:33.596  7164  7164 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-12 11:49:33.596  7164  7164 E HealthDataStore: disconnectService: Context instance is invalid
,07-12 11:49:33.766  7164  7200 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-12 11:49:33.806  7164  7205 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-12 11:49:33.816  7180  7190 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-12 11:49:33.826   391   391 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7180
07-12 11:49:33.826   391   391 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,07-12 11:49:33.986   777   861 I ActivityManager: Start proc 7210:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,07-12 11:49:33.986   777  1327 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-12 11:49:33.986  7210  7210 E Zygote  : v2
07-12 11:49:33.986  7210  7210 I libpersona: KNOX_SDCARD checking this for 10181
07-12 11:49:33.986  7210  7210 I libpersona: KNOX_SDCARD not a persona
,07-12 11:49:33.986  7210  7210 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 11:49:33.986  7210  7210 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:49:33.996  7210  7210 E Zygote  : accessInfo : 0
,07-12 11:49:33.996  7210  7210 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-12 11:49:34.026  7210  7210 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:49:34.026  7210  7210 D ActivityThread: Added TimaKeyStore provider
,07-12 11:49:34.036   777  1327 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-12 11:49:34.046  7210  7210 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-12 11:49:34.066  7210  7210 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-12 11:49:34.066  7180  7190 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,07-12 11:49:34.086  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-12 11:49:34.096  7210  7210 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-12 11:49:34.106   777   861 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{533c327 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3aa29d4 7210:com.sec.android.daemonapp/u0a181}
,07-12 11:49:34.106  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-12 11:49:34.106  7210  7210 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-12 11:49:34.106  7210  7210 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
07-12 11:49:34.106  7210  7210 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-12 11:49:34.106  7210  7210 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-12 11:49:34.106  7210  7210 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-12 11:49:34.126  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-12 11:49:34.126  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-12 11:49:34.126  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-12 11:49:34.126  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-12 11:49:34.126  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-12 11:49:34.126  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-12 11:49:34.126  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-12 11:49:34.136  7164  7205 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-12 11:49:34.146  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-12 11:49:34.156  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-12 11:49:34.156  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-12 11:49:34.156  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-12 11:49:34.156  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-12 11:49:34.156  7210  7210 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-12 11:49:34.156  7210  7210 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:49:34.156  7210  7210 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-12 11:49:34.156  7210  7210 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-12 11:49:34.156  7210  7210 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:49:34.156  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-12 11:49:34.156  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-12 11:49:34.156  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-12 11:49:34.156  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-12 11:49:34.156  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-12 11:49:34.166  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:49:34.166  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-12 11:49:34.166   777   790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{26a0f40 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3aa29d4 7210:com.sec.android.daemonapp/u0a181}
,07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-12 11:49:34.176  7210  7210 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:49:34.176  7210  7210 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-12 11:49:34.176  7210  7210 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-12 11:49:34.176  7210  7210 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-12 11:49:34.176  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:49:34.186  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-12 11:49:34.186   777  1588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{34e2e79 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3aa29d4 7210:com.sec.android.daemonapp/u0a181}
,07-12 11:49:34.186  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-12 11:49:34.186  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-12 11:49:34.186  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:49:34.196  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:49:34.196  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-12 11:49:34.196  7210  7210 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:49:34.196  7210  7210 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-12 11:49:34.196  7210  7210 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-12 11:49:34.196  7210  7210 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-12 11:49:34.196  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-12 11:49:34.196  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-12 11:49:34.196  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-12 11:49:34.196  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-12 11:49:34.196  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-12 11:49:34.196  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:49:34.196  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-12 11:49:34.206   777  1420 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{508d7be u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3aa29d4 7210:com.sec.android.daemonapp/u0a181}
,07-12 11:49:34.216  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-12 11:49:34.216  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-12 11:49:34.216  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:49:34.216  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:49:34.216  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-12 11:49:34.216  7210  7210 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:49:34.226  7210  7210 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-12 11:49:34.226  7210  7210 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-12 11:49:34.226  7210  7210 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-12 11:49:34.226  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-12 11:49:34.226  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-12 11:49:34.226  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-12 11:49:34.226  7210  7210 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,07-12 11:49:34.226  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-12 11:49:34.226  7210  7210 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:49:34.226  7210  7210 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-12 11:49:34.266  7164  7205 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
07-12 11:49:34.266  7164  7205 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-12 11:49:34.566   391   391 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,07-12 11:49:34.606  7180  7190 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
07-12 11:49:34.606  7180  7190 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,07-12 11:49:34.606  7180  7190 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,07-12 11:49:39.856   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:49:40.906   777  1594 E Watchdog: !@Sync 28 [07-12 11:49:40.914]
,07-12 11:49:43.016  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:49:43.156  1734  1794 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 119ms lastUpdatedAfter : 180325ms
,07-12 11:49:47.836   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-12 11:49:47.836   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:49:47.836   306  1130 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:49:49.916   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:49:50.576   777  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:49:50.586   777  1678 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:49:50.586   777  1678 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:49:50.586   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:49:50.606   777   777 I MotionRecognitionService: Plugged
,07-12 11:49:50.606   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:49:50.606   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:49:50.606   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:49:50.616   777  1678 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-12 11:49:50.616   777  1678 D BatteryService: stay LED for fully charged
,07-12 11:49:50.616  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:49:50.616  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:49:50.616  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:49:50.636  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:49:50.636  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:49:50.646  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:50.646  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:50.646  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:59.976   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:50:05.486   777   787 I art     : Background sticky concurrent mark sweep GC freed 66119(8MB) AllocSpace objects, 365(7MB) LOS objects, 27% free, 42MB/57MB, paused 2.495ms total 131.036ms
,07-12 11:50:10.056   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:50:10.906   777  1594 E Watchdog: !@Sync 29 [07-12 11:50:10.918]
,07-12 11:50:20.126   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:50:20.646   777  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:50:20.646   777  1420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:50:20.656   777  1420 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:50:20.656   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:50:20.666   777   777 I MotionRecognitionService: Plugged
,07-12 11:50:20.666   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:50:20.676   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:50:20.676   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:50:20.676   777  1420 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-12 11:50:20.686   777  1420 D BatteryService: stay LED for fully charged
,07-12 11:50:20.696  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:50:20.706  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:50:20.706  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:50:20.726  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:50:20.726  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:50:20.736  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:20.736  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:20.736  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:25.566   777  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 11:50:25.566   777  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:50:25.566   777  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:50:28.956   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-12 11:50:28.956   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:50:28.966   777  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:50:28.976   777  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:50:30.176   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:50:40.236   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:50:40.916   777  1594 E Watchdog: !@Sync 30 [07-12 11:50:40.924]
,07-12 11:50:43.186  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:50:50.296   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:50:50.726   777  1727 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:50:50.726   777  1727 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:50:50.726   777  1727 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:50:50.736   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:50:50.746   777   777 I MotionRecognitionService: Plugged
,07-12 11:50:50.746   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:50:50.756   777  1727 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-12 11:50:50.756   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:50:50.756   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:50:50.756   777  1727 D BatteryService: stay LED for fully charged
,07-12 11:50:50.766  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:50:50.766  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:50:50.766  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:50:50.786  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:50:50.786  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:50:50.786  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:50.796  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:50.796  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:00.376   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:51:10.436   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:51:10.916   777  1594 E Watchdog: !@Sync 31 [07-12 11:51:10.928]
,07-12 11:51:20.506   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0,
,07-12 11:51:20.806   777  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:51:20.806   777  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:51:20.816   777  1589 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:51:20.816   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:51:20.826   777   777 I MotionRecognitionService: Plugged
,07-12 11:51:20.826   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:51:20.836   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:51:20.836   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:51:20.836   777  1589 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-12 11:51:20.846   777  1589 D BatteryService: stay LED for fully charged
,07-12 11:51:20.866  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:51:20.866  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:51:20.866  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:51:20.886  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:51:20.886  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:51:20.886  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:20.886  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:51:20.886  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:30.596   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:51:40.666   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:51:40.926   777  1594 E Watchdog: !@Sync 32 [07-12 11:51:40.933]
,07-12 11:51:43.286  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:51:50.716   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:51:50.876   777   790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:51:50.886   777   790 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:51:50.886   777   790 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:51:50.886   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:51:50.906   777   777 I MotionRecognitionService: Plugged
,07-12 11:51:50.906   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:51:50.906   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:51:50.906   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:51:50.916   777   790 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-12 11:51:50.916   777   790 D BatteryService: stay LED for fully charged
,07-12 11:51:50.916  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:51:50.916  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:51:50.916  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:51:50.936  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:51:50.936  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:51:50.946  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:50.946  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:50.946  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:00.776   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:52:10.836   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:52:10.926   777  1594 E Watchdog: !@Sync 33 [07-12 11:52:10.938]
,07-12 11:52:13.286   777  1240 V AlarmManager: Expired Alarm result :4
,07-12 11:52:13.346  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-12 11:52:13.346  1386  1386 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-12 11:52:13.346  1386  1386 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:52:13.376  1386  1386 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-12 11:52:13.396  1386  1386 D SecKeyguardClockView: HomeTimezone(): 1
,07-12 11:52:13.396   777   861 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-12 11:52:13.406  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:13.406  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:13.406  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:13.406  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:13.416  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:13.416   777   777 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-12 11:52:13.416  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:13.416   777   777 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-12 11:52:13.416  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:13.416   777   777 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-12 11:52:13.436   777   777 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-12 11:52:13.446  6150  6178 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-12 11:52:13.446  6150  6178 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-12 11:52:13.446  6150  6178 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
07-12 11:52:13.446  6150  6178 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
07-12 11:52:13.446  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.446  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-12 11:52:13.456  6150  6208 D bt_upio : upio_start_stop_timer : timer_settime success
,07-12 11:52:13.456  6150  6208 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-12 11:52:13.456  6150  6208 D bt_vendor: op for 7
,07-12 11:52:13.456  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.456  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.456  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.456  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.466  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.466  6150  6208 D bt_vendor: op for 7
,07-12 11:52:13.466  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.466  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.466  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.466  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.466  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.466  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.466  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.466  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.466  6150  6208 D bt_vendor: op for 7
,07-12 11:52:13.466  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.466  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.466  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.466  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.466  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.466  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.466  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-12 11:52:13.466  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.476  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.476  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.476  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.476  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.476  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.476  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.476  6150  6208 D bt_vendor: op for 7
,07-12 11:52:13.476  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.476  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.476  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.476  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.476  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.476  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.476  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.476  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.476  6150  6208 D bt_vendor: op for 7
,07-12 11:52:13.476  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.476  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.486  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.486  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-12 11:52:13.486  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.496  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.496  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-12 11:52:13.496  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.496  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.496  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.496  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.496  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.496  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-12 11:52:13.496  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.496  6150  6208 D bt_vendor: op for 7
07-12 11:52:13.496  6150  6208 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-12 11:52:13.496  6150  6208 D bt_upio : BT_WAKE is asserted already
,07-12 11:52:13.516   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{a2233b1: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.526   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{8362096: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.526  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:13.536   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{6fdc417: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.536   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{c95b004: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.556   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{e7559ed: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.566   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{3abb022: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.576   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{c108ab3: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.576   777  1420 V AlarmManager:  remove PendingIntent] PendingIntent{6bfc870: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.576   777  1678 V AlarmManager:  remove PendingIntent] PendingIntent{55aa7e9: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.586   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{df8ac6e: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.586   777  1719 V AlarmManager:  remove PendingIntent] PendingIntent{27f1f0f: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.586   777  2212 V AlarmManager:  remove PendingIntent] PendingIntent{30fb9c: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.596   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{82cd9a5: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.596   777  1589 V AlarmManager:  remove PendingIntent] PendingIntent{7217a: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.606   777   790 V AlarmManager:  remove PendingIntent] PendingIntent{d989d2b: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.606   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{4203588: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.606   777   789 V AlarmManager:  remove PendingIntent] PendingIntent{1366b21: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.616   777  1727 V AlarmManager:  remove PendingIntent] PendingIntent{555db46: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.616   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{c81e107: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.626   777  2231 V AlarmManager:  remove PendingIntent] PendingIntent{8472234: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.626   777  2222 V AlarmManager:  remove PendingIntent] PendingIntent{aed985d: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.636   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{8465d2: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.636   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{1d186a3: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.646   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{24e2da0: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.646   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{6f05d59: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.646   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{c9f0d1e: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.656   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{8ebe9ff: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.656   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{7f883cc: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.656   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{8c07615: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.666   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{72add2a: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.666   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{51f271b: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.666   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{61010b8: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.676   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{3f5e91: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.676   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{ef1a1f6: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.676   777  1300 V AlarmManager:  remove PendingIntent] PendingIntent{67f19f7: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.686   777  1588 V AlarmManager:  remove PendingIntent] PendingIntent{a118064: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.686   777  1718 V AlarmManager:  remove PendingIntent] PendingIntent{fea52cd: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.686   777  1421 V AlarmManager:  remove PendingIntent] PendingIntent{38de782: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.696   777  2235 V AlarmManager:  remove PendingIntent] PendingIntent{815e93: PendingIntentRecord{a528658 com.android.bluetooth broadcastIntent}}
,07-12 11:52:13.806   777   921 D LightsService: [SvcLED]  onSensorChanged::light value = 35
07-12 11:52:13.806   777   921 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-12 11:52:13.816   777   921 D SensorManager: unregisterListener ::   
07-12 11:52:13.816   777   921 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-12 11:52:13.816   777   921 V AlarmManager:  remove PendingIntent] PendingIntent{8d40e9f: PendingIntentRecord{23fbbb5 android broadcastIntent}}
,07-12 11:52:14.256  6150  6281 D bt_upio : ..proc_btwrite_timeout..
07-12 11:52:14.256  6150  6281 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-12 11:52:20.906   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:52:20.966   777  1718 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:20.966   777  1718 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:52:20.976   777  1718 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:52:20.976   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:52:20.986   777   777 I MotionRecognitionService: Plugged
,07-12 11:52:20.986   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:52:20.996   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:52:20.996   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:52:20.996   777  1718 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-12 11:52:20.996   777  1718 D BatteryService: stay LED for fully charged
,07-12 11:52:21.016  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:52:21.016  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:52:21.016  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:52:21.046  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:21.046  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:21.046  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:21.056  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:52:21.056  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:52:30.976   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:52:40.936   777  1594 E Watchdog: !@Sync 34 [07-12 11:52:40.944]
,07-12 11:52:41.026   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:52:43.356  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:52:43.516  1734  1794 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 136ms lastUpdatedAfter : 180356ms
,07-12 11:52:51.056   777  2212 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:51.066   777  2212 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:52:51.066   777  2212 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:52:51.066   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:52:51.076   777   777 I MotionRecognitionService: Plugged
,07-12 11:52:51.076   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:52:51.086   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:52:51.086   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:52:51.086   777  2212 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,07-12 11:52:51.096   777  2212 D BatteryService: stay LED for fully charged
,07-12 11:52:51.096  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:52:51.096  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:52:51.096  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:52:51.116  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:52:51.116  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:52:51.116   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:52:51.126  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:51.126  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:51.126  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:59.986   777  1240 V AlarmManager: Expired Alarm result :8
,07-12 11:53:01.196   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:53:10.936   777  1594 E Watchdog: !@Sync 35 [07-12 11:53:10.948]
,07-12 11:53:11.246   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:53:21.106   777  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:53:21.106   777  1678 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:53:21.116   777  1678 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:53:21.116   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:53:21.136   777   777 I MotionRecognitionService: Plugged
,07-12 11:53:21.136   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:53:21.136   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:53:21.136   777  1678 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-12 11:53:21.146   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:53:21.146   777  1678 D BatteryService: stay LED for fully charged
,07-12 11:53:21.146  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:53:21.146  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:53:21.146  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:53:21.166  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:53:21.166  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:53:21.176  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:21.176  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:53:21.176  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:21.316   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:53:31.396   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:53:40.946   777  1594 E Watchdog: !@Sync 36 [07-12 11:53:40.952]
,07-12 11:53:41.446   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:53:43.576  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:53:51.186   777  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:53:51.496   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:54:01.576   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:54:10.946   777  1594 E Watchdog: !@Sync 37 [07-12 11:54:10.957]
,07-12 11:54:11.646   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:54:21.256   777  2222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:54:21.706   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:54:31.756   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:54:40.956   777  1594 E Watchdog: !@Sync 38 [07-12 11:54:40.961]
,07-12 11:54:41.816   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:54:43.676  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:54:51.336   777  1588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:54:51.896   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:55:01.976   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:55:10.956   777  1594 E Watchdog: !@Sync 39 [07-12 11:55:10.965]
,07-12 11:55:12.056   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:55:21.416   777  2231 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:55:21.426   777  2231 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:55:21.426   777  2231 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:55:21.426   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:55:21.446   777   777 I MotionRecognitionService: Plugged
,07-12 11:55:21.446   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:55:21.446   777  2231 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-12 11:55:21.456   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:55:21.456   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:55:21.456   777  2231 D BatteryService: stay LED for fully charged
,07-12 11:55:21.466  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:55:21.466  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:55:21.476  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:55:21.496  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:55:21.496  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:55:21.506  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:21.506  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:55:21.506  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:22.126   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:55:25.566   777  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 11:55:25.566   777  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:55:25.566   777  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:55:27.066   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-12 11:55:27.066   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:55:27.076   777  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:55:27.076   777  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:55:32.186   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:55:37.586   777   856 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 11:55:40.966   777  1594 E Watchdog: !@Sync 40 [07-12 11:55:40.969]
,07-12 11:55:42.246   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:55:43.706  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:55:43.856  1734  1794 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 140ms lastUpdatedAfter : 180345ms
,07-12 11:55:51.496   777   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:55:52.306   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:56:02.366   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:56:10.966   777  1594 E Watchdog: !@Sync 41 [07-12 11:56:10.974]
,07-12 11:56:12.426   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:56:21.576   777  2222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:56:21.576   777  2222 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:56:21.586   777  2222 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:56:21.586   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:56:21.596   777   777 I MotionRecognitionService: Plugged
,07-12 11:56:21.596   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:56:21.606   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:56:21.606   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:56:21.606   777  2222 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-12 11:56:21.616   777  2222 D BatteryService: stay LED for fully charged
,07-12 11:56:21.636  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:56:21.636  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:56:21.636  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:56:21.656  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:56:21.656  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:56:21.666  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:21.666  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:21.666  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:22.506   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:56:32.566   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:56:40.966   777  1594 E Watchdog: !@Sync 42 [07-12 11:56:40.979]
,07-12 11:56:42.616   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:56:43.886  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:56:51.646   777  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:56:52.676   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:57:02.756   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:57:10.976   777  1594 E Watchdog: !@Sync 43 [07-12 11:57:10.984]
,07-12 11:57:12.826   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:57:21.716   777  1727 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:57:21.726   777  1727 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:57:21.726   777  1727 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:57:21.726   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:57:21.746   777   777 I MotionRecognitionService: Plugged
,07-12 11:57:21.746   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:57:21.746   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:57:21.746   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:57:21.756   777  1727 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-12 11:57:21.756   777  1727 D BatteryService: stay LED for fully charged
,07-12 11:57:21.766  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:57:21.766  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:57:21.766  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:57:21.796  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:21.796  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:57:21.796  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:21.806  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:57:21.806  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:57:22.886   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:57:32.946   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:57:40.976   777  1594 E Watchdog: !@Sync 44 [07-12 11:57:40.988]
,07-12 11:57:43.006   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:57:43.966  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:57:51.796   777  1718 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:57:53.066   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:58:03.116   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:58:10.986   777  1594 E Watchdog: !@Sync 45 [07-12 11:58:10.994]
,07-12 11:58:13.176   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:58:21.866   777  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:58:21.876   777  1719 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:58:21.876   777  1719 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:58:21.876   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:58:21.896   777   777 I MotionRecognitionService: Plugged
,07-12 11:58:21.896   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:58:21.896   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:58:21.896   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:58:21.906   777  1719 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-12 11:58:21.906   777  1719 D BatteryService: stay LED for fully charged
,07-12 11:58:21.916  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:58:21.916  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:58:21.916  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:58:21.946  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:58:21.956  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:58:21.956  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:21.956  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:58:21.956  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:23.226   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:58:33.286   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:58:40.986   777  1594 E Watchdog: !@Sync 46 [07-12 11:58:40.999]
,07-12 11:58:43.336   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:58:43.996  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:58:44.126  1734  1794 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 117ms lastUpdatedAfter : 180269ms
,07-12 11:58:51.936   777   790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:58:53.396   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:59:03.446   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:59:10.996   777  1594 E Watchdog: !@Sync 47 [07-12 11:59:11.003]
,07-12 11:59:13.496   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:59:22.016   777  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:59:23.556   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:59:33.606   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:59:40.996   777  1594 E Watchdog: !@Sync 48 [07-12 11:59:41.007]
,07-12 11:59:43.656   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 11:59:44.136  1734  1794 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-12 11:59:52.086   777  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:59:52.096   777  1719 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 11:59:52.096   777  1719 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 11:59:52.096   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:59:52.106   777   777 I MotionRecognitionService: Plugged
,07-12 11:59:52.116   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 11:59:52.116   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:59:52.116   777   777 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:59:52.126   777  1719 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-12 11:59:52.126   777  1719 D BatteryService: stay LED for fully charged
,07-12 11:59:52.146  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:59:52.146  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:59:52.146  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:59:52.156  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:59:52.156  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:59:52.166  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:52.166  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:52.166  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:53.716   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 12:00:03.776   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 12:00:11.006   777  1594 E Watchdog: !@Sync 49 [07-12 12:00:11.011]
,07-12 12:00:13.826   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 12:00:22.156   777  1718 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 12:00:22.166   777  1718 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-12 12:00:22.166   777  1718 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-12 12:00:22.166   777   777 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 12:00:22.186   777   777 I MotionRecognitionService: Plugged
,07-12 12:00:22.186   777   777 D MotionRecognitionService:   cableConnection= 1
,07-12 12:00:22.186   777   777 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 12:00:22.186   777  1718 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-12 12:00:22.196   777   777 D MotionRecognitionService: skip setTransmitPower. 
07-12 12:00:22.196   777  1718 D BatteryService: stay LED for fully charged
,07-12 12:00:22.196  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 12:00:22.196  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 12:00:22.196  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 12:00:22.216  6150  6150 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 12:00:22.216  6150  6285 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 12:00:22.226  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 12:00:22.226  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 12:00:22.226  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 12:00:23.876   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-12 12:00:25.566   777  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 12:00:25.566   777  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 12:00:25.566   777  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 12:00:28.956   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-12 12:00:28.956   777  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 12:00:28.966   777  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 12:00:28.976   777  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,TIME-OUT KILL (timeout was 1400000ms),07-12 12:00:33.936   777  3287 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
07-12 12:00:37.566  2151  2151 E audit   : type=1400 msg=audit(1468317637.566:293): avc:  denied  { execmod } for  pid=7301 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-12 12:00:37.566  2151  2151 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-12 12:00:37.566  2151  2151 E audit   : type=1300 msg=audit(1468317637.566:293): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f98000 a1=51000 a2=5 a3=4 items=0 ppid=3446 ppcomm=adbd pid=7301 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-12 12:00:37.566  2151  2151 E audit   : type=1327 msg=audit(1468317637.566:293): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-12 12:00:37.566  2151  2151 E audit   : type=1320 msg=audit(1468317637.566:293): 
07-12 12:00:37.616  2151  2151 E audit   : type=1400 msg=audit(1468317637.616:294): avc:  denied  { execmod } for  pid=7301 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-12 12:00:37.616  2151  2151 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-12 12:00:37.616  2151  2151 E audit   : type=1300 msg=audit(1468317637.616:294): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f58000 a1=51000 a2=5 a3=4 items=0 ppid=3446 ppcomm=adbd pid=7301 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-12 12:00:37.616  2151  2151 E audit   : type=1327 msg=audit(1468317637.616:294): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-12 12:00:37.616  2151  2151 E audit   : type=1320 msg=audit(1468317637.616:294): 
07-12 12:00:37.666  2151  2151 E audit   : type=1400 msg=audit(1468317637.656:295): avc:  denied  { execmod } for  pid=7301 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-12 12:00:37.666  2151  2151 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-12 12:00:37.666  2151  2151 E audit   : type=1300 msg=audit(1468317637.656:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f58000 a1=51000 a2=5 a3=4 items=0 ppid=3446 ppcomm=adbd pid=7301 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-12 12:00:37.666  2151  2151 E audit   : type=1327 msg=audit(1468317637.656:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-12 12:00:37.666  2151  2151 E audit   : type=1320 msg=audit(1468317637.656:295): 
07-12 12:00:37.666  7301  7301 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 12:00:37.666  7301  7301 D AndroidRuntime: CheckJNI is OFF
07-12 12:00:37.666  7301  7301 D AndroidRuntime: readGMSProperty: start
07-12 12:00:37.666  7301  7301 D AndroidRuntime: readGMSProperty: already setted!!
07-12 12:00:37.666  7301  7301 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-12 12:00:37.666  7301  7301 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-12 12:00:37.666  7301  7301 D AndroidRuntime: readGMSProperty: end
07-12 12:00:37.666  7301  7301 D AndroidRuntime: addProductProperty: start
07-12 12:00:37.676  7301  7301 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-12 12:00:37.676  7301  7301 W art     : aedbf000-b1ce5000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-12 12:00:37.676  7301  7301 W art     : b1ce5000-b3f54000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-12 12:00:37.676  7301  7301 W art     : b3f54000-b3f55000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-12 12:00:37.676  7301  7301 W art     : b3f55000-b3f56000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.676  7301  7301 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-12 12:00:37.676  7301  7301 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
07-12 12:00:37.676  7301  7301 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-12 12:00:37.676  7301  7301 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-12 12:00:37.676  7301  7301 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
07-12 12:00:37.676  7301  7301 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-12 12:00:37.676  7301  7301 W art     : b4801000-b482a000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-12 12:00:37.676  7301  7301 W art     : b482a000-b482d000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-12 12:00:37.676  7301  7301 W art     : b482d000-b482e000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-12 12:00:37.676  7301  7301 W art     : b482e000-b482f000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-12 12:00:37.676  7301  7301 W art     : b482f000-b4830000 r--p 00000000 00:00 0 
07-12 12:00:37.676  7301  7301 W art     : b4830000-b4850000 r--s 00000000 00:0b 6706       /dev/__properties__
07-12 12:00:37.676  7301  7301 W art     : b4850000-b5261000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-12 12:00:37.676  7301  7301 W art     : b5261000-b5262000 ---p 00000000 00:00 0 
07-12 12:00:37.676  7301  7301 W art     : b5262000-b52ab000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-12 12:00:37.676  7301  7301 W art     : b52ab000-b52ac000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-12 12:00:37.676  7301  7301 W art     : b52ac000-b52b4000 rw-p 00000000 00:00 0 
07-12 12:00:37.676  7301  7301 W art     : b52b4000-b52b5000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.676  7301  7301 W art     : b52b5000-b52ea000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-12 12:00:37.676  7301  7301 W art     : b52ea000-b52eb000 ---p 00000000 00:00 0 
07-12 12:00:37.676  7301  7301 W art     : b52eb000-b52ec000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-12 12:00:37.676  7301  7301 W art     : b52ec000-b52ed000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-12 12:00:37.676  7301  7301 W art     : b52ed000-b5345000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-12 12:00:37.676  7301  7301 W art     : b5345000-b5346000 ---p 00000000 00:00 0 
07-12 12:00:37.676  7301  7301 W art     : b5346000-b5347000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-12 12:00:37.676  7301  7301 W art     : b5347000-b5348000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-12 12:00:37.676  7301  7301 W art     : b5349000-b534f000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-12 12:00:37.676  7301  7301 W art     : b534f000-b5350000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-12 12:00:37.676  7301  7301 W art     : b5350000-b5351000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-12 12:00:37.676  7301  7301 W art     : b5351000-b5353000 rw-p 00000000 00:00 0 
07-12 12:00:37.676  7301  7301 W art     : b5354000-b535e000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-12 12:00:37.676  7301  7301 W art     : b535e000-b5361000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-12 12:00:37.676  7301  7301 W art     : b5361000-b5362000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-12 12:00:37.676  7301  7301 W art     : b5363000-b537a000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-12 12:00:37.676  7301  7301 W art     : b537a000-b537b000 ---p 00000000 00:00 0 
07-12 12:00:37.676  7301  7301 W art     : b537b000-b537c000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-12 12:00:37.676  7301  7301 W art     : b537c000-b537d000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-12 12:00:37.676  7301  7301 W art     : b537e000-b5388000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-12 12:00:37.676  7301  7301 W art     : b5388000-b5389000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-12 12:00:37.676  7301  7301 W art     : b5389000-b538a000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-12 12:00:37.676  7301  7301 W art     : b538a000-b538e000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-12 12:00:37.676  7301  7301 W art     : b538e000-b538f000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-12 12:00:37.676  7301  7301 W art     : b538f000-b5390000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-12 12:00:37.676  7301  7301 W art     : b5390000-b53a6000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-12 12:00:37.676  7301  7301 W art     : b53a6000-b53a7000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-12 12:00:37.676  7301  7301 W art     : b53a7000-b53a8000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-12 12:00:37.676  7301  7301 W art     : b53a8000-b53b5000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-12 12:00:37.676  7301  7301 W art     : b53b5000-b53b6000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-12 12:00:37.686  7301  7301 W art     : b53b6000-b53b7000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-12 12:00:37.686  7301  7301 W art     : b53b7000-b5417000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-12 12:00:37.686  7301  7301 W art     : b5417000-b541a000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-12 12:00:37.686  7301  7301 W art     : b541a000-b541e000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b541e000-b547f000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-12 12:00:37.686  7301  7301 W art     : b547f000-b5480000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-12 12:00:37.686  7301  7301 W art     : b5480000-b54cf000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-12 12:00:37.686  7301  7301 W art     : b54cf000-b54d1000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-12 12:00:37.686  7301  7301 W art     : b54d1000-b54d2000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-12 12:00:37.686  7301  7301 W art     : b54d2000-b54d3000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b54d3000-b54da000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-12 12:00:37.686  7301  7301 W art     : b54da000-b54db000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-12 12:00:37.686  7301  7301 W art     : b54db000-b54dc000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
07-12 12:00:37.686  7301  7301 W art     : avc_common.so
07-12 12:00:37.686  7301  7301 W art     : b54dd000-b54e0000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-12 12:00:37.686  7301  7301 W art     : b54e0000-b54e1000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-12 12:00:37.686  7301  7301 W art     : b54e1000-b54e2000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
07-12 12:00:37.686  7301  7301 W art     : enc_common.so
07-12 12:00:37.686  7301  7301 W art     : b54e3000-b54e7000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-12 12:00:37.686  7301  7301 W art     : b54e7000-b54e8000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b54e8000-b54e9000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-12 12:00:37.686  7301  7301 W art     : b54e9000-b54ea000 rw-p 00005000 b3:17 2510       /syste
07-12 12:00:37.686  7301  7301 W art     : m/lib/libpowermanager.so
07-12 12:00:37.686  7301  7301 W art     : b54eb000-b5508000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-12 12:00:37.686  7301  7301 W art     : b5508000-b5509000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-12 12:00:37.686  7301  7301 W art     : b5509000-b550a000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-12 12:00:37.686  7301  7301 W art     : b550b000-b5510000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-12 12:00:37.686  7301  7301 W art     : b5510000-b5511000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-12 12:00:37.686  7301  7301 W art     : b5511000-b5512000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-12 12:00:37.686  7301  7301 W art     : b5513000-b5544000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-12 12:00:37.686  7301  7301 W art     : b5544000-b5547000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-12 12:00:37.686  7301  7301 W art     : b5547000-b5548000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-12 12:00:37.686  7301  7301 W art     : b5549000-b5584000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-12 12:00:37.686  7301  7301 W art     : b5584000-b5585000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-12 12:00:37.686  7301  7301 W art     : b5585000-b5586000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-12 12:00:37.686  7301  7301 W art     : b5587000-b558e000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-12 12:00:37.686  7301  7301 W art     : b558e000-b558f000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b558f000-b5590000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-12 12:00:37.686  7301  7301 W art     : b5590000-b5591000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-12 12:00:37.686  7301  7301 W art     : b5591000-b5592000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b5592000-b55a9000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-12 12:00:37.686  7301  7301 W art     : b55a9000-b55aa000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b55aa000-b55ad000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-12 12:00:37.686  7301  7301 W art     : b55ad000-b55ae000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-12 12:00:37.686  7301  7301 W art     : b55ae000-b55cd000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-12 12:00:37.686  7301  7301 W art     : b55cd000-b55ce000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-12 12:00:37.686  7301  7301 W art     : b55ce000-b55cf000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-12 12:00:37.686  7301  7301 W art     : b55cf000-b560d000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-12 12:00:37.686  7301  7301 W art     : b560d000-b560e000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b560e000-b5610000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-12 12:00:37.686  7301  7301 W art     : b5610000-b5611000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-12 12:00:37.686  7301  7301 W art     : b5612000-b5619000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-12 12:00:37.686  7301  7301 W art     : b5619000-b561a000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-12 12:00:37.686  7301  7301 W art     : b561a000-b561b000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-12 12:00:37.686  7301  7301 W art     : b561c000-b561f000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-12 12:00:37.686  7301  7301 W art     : b561f000-b5620000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-12 12:00:37.686  7301  7301 W art     : b5620000-b5621000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-12 12:00:37.686  7301  7301 W art     : b5621000-b5627000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-12 12:00:37.686  7301  7301 W art     : b5627000-b5628000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5628000-b5629000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-12 12:00:37.686  7301  7301 W art     : b5629000-b562a000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-12 12:00:37.686  7301  7301 W art     : b562a000-b5633000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-12 12:00:37.686  7301  7301 W art     : b5633000-b5634000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-12 12:00:37.686  7301  7301 W art     : b5634000-b5635000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-12 12:00:37.686  7301  7301 W art     : b5635000-b56c6000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-12 12:00:37.686  7301  7301 W art     : b56c6000-b56c7000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b56c7000-b56d2000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-12 12:00:37.686  7301  7301 W art     : b56d2000-b56d3000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-12 12:00:37.686  7301  7301 W art     : b56d4000-b56e6000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-12 12:00:37.686  7301  7301 W art     : b56e6000-b56e7000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-12 12:00:37.686  7301  7301 W art     : b56e7000-b56e8000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-12 12:00:37.686  7301  7301 W art     : b56e9000-b56ee000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-12 12:00:37.686  7301  7301 W art     : b56ee000-b56ef000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-12 12:00:37.686  7301  7301 W art     : b56ef000-b56f0000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-12 12:00:37.686  7301  7301 W art     : b56f1000-b575e000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-12 12:00:37.686  7301  7301 W art     : b575e000-b575f000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b575f000-b5761000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-12 12:00:37.686  7301  7301 W art     : b5761000-b5762000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-12 12:00:37.686  7301  7301 W art     : b5762000-b5763000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b5763000-b576a000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-12 12:00:37.686  7301  7301 W art     : b576a000-b576b000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-12 12:00:37.686  7301  7301 W art     : b576b000-b576c000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-12 12:00:37.686  7301  7301 W art     : b576d000-b57ed000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-12 12:00:37.686  7301  7301 W art     : b57ed000-b57ee000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b57ee000-b57ef000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-12 12:00:37.686  7301  7301 W art     : b57ef000-b57f0000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-12 12:00:37.686  7301  7301 W art     : b57f0000-b5807000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5807000-b583e000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-12 12:00:37.686  7301  7301 W art     : ib/libqc-opt.so
07-12 12:00:37.686  7301  7301 W art     : b583e000-b583f000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-12 12:00:37.686  7301  7301 W art     : b583f000-b5840000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-12 12:00:37.686  7301  7301 W art     : b5840000-b585c000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-12 12:00:37.686  7301  7301 W art     : b585c000-b585d000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-12 12:00:37.686  7301  7301 W art     : b585d000-b585e000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-12 12:00:37.686  7301  7301 W art     : b585f000-b58c0000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-12 12:00:37.686  7301  7301 W art     : b58c0000-b58c2000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-12 12:00:37.686  7301  7301 W art     : b58c2000-b58c3000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-12 12:00:37.686  7301  7301 W art     : b58c4000-b58eb000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-12 12:00:37.686  7301  7301 W art     : b58eb000-b58ec000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b58ec000-b58ed000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-12 12:00:37.686  7301  7301 W art     : b58ed000-b58ee000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-12 12:00:37.686  7301  7301 W art     : b58ef000-b58f7000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-12 12:00:37.686  7301  7301 W art     : b58f7000-b58f9000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-12 12:00:37.686  7301  7301 W art     : b58f9000-b58fa000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-12 12:00:37.686  7301  7301 W art     : b58fb000-b58fe000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-12 12:00:37.686  7301  7301 W art     : b58fe000-b58ff000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-12 12:00:37.686  7301  7301 W art     : b58ff000-b5900000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-12 12:00:37.686  7301  7301 W art     : b5900000-b5904000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-12 12:00:37.686  7301  7301 W art     : b5904000-b5905000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5905000-b5906000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-12 12:00:37.686  7301  7301 W art     : b5906000-b5907000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-12 12:00:37.686  7301  7301 W art     : b5907000-b5917000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-12 12:00:37.686  7301  7301 W art     : b5917000-b5918000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-12 12:00:37.686  7301  7301 W art     : b5918000-b5919000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-12 12:00:37.686  7301  7301 W art     : b5919000-b595f000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b595f000-b5968000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-12 12:00:37.686  7301  7301 W art     : b5968000-b5969000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-12 12:00:37.686  7301  7301 W art     : b5969000-b596a000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-12 12:00:37.686  7301  7301 W art     : b596b000-b5970000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-12 12:00:37.686  7301  7301 W art     : b5970000-b5971000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-12 12:00:37.686  7301  7301 W art     : b5971000-b5972000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-12 12:00:37.686  7301  7301 W art     : b5972000-b5975000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-12 12:00:37.686  7301  7301 W art     : b5975000-b5976000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5976000-b5977000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-12 12:00:37.686  7301  7301 W art     : b5977000-b5978000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-12 12:00:37.686  7301  7301 W art     : b5979000-b5991000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-12 12:00:37.686  7301  7301 W art     : b5991000-b5992000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5992000-b5993000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-12 12:00:37.686  7301  7301 W art     : b5993000-b5994000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-12 12:00:37.686  7301  7301 W art     : b5995000-b5b2f000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-12 12:00:37.686  7301  7301 W art     : b5b2f000-b5b30000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5b30000-b5b3d000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-12 12:00:37.686  7301  7301 W art     : b5b3d000-b5b3e000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-12 12:00:37.686  7301  7301 W art     : b5b3e000-b5b42000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-12 12:00:37.686  7301  7301 W art     : b5b42000-b5b43000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5b43000-b5b44000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-12 12:00:37.686  7301  7301 W art     : b5b44000-b5b45000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-12 12:00:37.686  7301  7301 W art     : b5b45000-b5b58000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-12 12:00:37.686  7301  7301 W art     : b5b58000-b5b59000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-12 12:00:37.686  7301  7301 W art     : b5b59000-b5b5a000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-12 12:00:37.686  7301  7301 W art     : b5b5a000-b5b5b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 12:00:37.686  7301  7301 W art     : b5b5b000-b5ba6000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-12 12:00:37.686  7301  7301 W art     : b5ba6000-b5ba7000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-12 12:00:37.686  7301  7301 W art     : b5ba7000-b5ba8000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-12 12:00:37.686  7301  7301 W art     : b5ba8000-b5baa000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5bab000-b5bbc000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-12 12:00:37.686  7301  7301 W art     : b5bbc000-b5bbd000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5bbd000-b5bbe000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-12 12:00:37.686  7301  7301 W art     : b5bbe000-b5bbf000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-12 12:00:37.686  7301  7301 W art     : b5bc0000-b5bca000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-12 12:00:37.686  7301  7301 W art     : b5bca000-b5bcc000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-12 12:00:37.686  7301  7301 W art     : b5bcc000-b5bcd000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-12 12:00:37.686  7301  7301 W art     : b5bcd000-b5be6000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-12 12:00:37.686  7301  7301 W art     : b5be6000-b5be7000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-12 12:00:37.686  7301  7301 W art     : b5be7000-b5bea000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-12 12:00:37.686  7301  7301 W art     : b5bea000-b5bee000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5bee000-b5c62000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-12 12:00:37.686  7301  7301 W art     : b5c62000-b5c63000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5c63000-b5c66000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-12 12:00:37.686  7301  7301 W art     : b5c66000-b5c67000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-12 12:00:37.686  7301  7301 W art     : b5c67000-b5c68000 r--p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5c68000-b5c6b000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-12 12:00:37.686  7301  7301 W art     : b5c6b000-b5c6c000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-12 12:00:37.686  7301  7301 W art     : b5c6c000-b5c6d000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-12 12:00:37.686  7301  7301 W art     : b5c6d000-b5c6e000 r--p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5c6e000-b5c73000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-12 12:00:37.686  7301  7301 W art     : b5c73000-b5c74000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-12 12:00:37.686  7301  7301 W art     : b5c74000-b5c75000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-12 12:00:37.686  7301  7301 W art     : b5c75000-b5c76000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b5c76000-b5c79000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-12 12:00:37.686  7301  7301 W art     : b5c79000-b5c7a000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-12 12:00:37.686  7301  7301 W art     : b5c7a000-b5c7b000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-12 12:00:37.686  7301  7301 W art     : b5c7b000-b5c7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b5c7c000-b5c80000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-12 12:00:37.686  7301  7301 W art     : b5c80000-b5c81000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-12 12:00:37.686  7301  7301 W art     : b5c81000-b5c82000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-12 12:00:37.686  7301  7301 W art     : b5c82000-b5c83000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 12:00:37.686  7301  7301 W art     : b5c83000-b5c87000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-12 12:00:37.686  7301  7301 W art     : b5c87000-b5c88000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-12 12:00:37.686  7301  7301 W art     : b5c88000-b5c89000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-12 12:00:37.686  7301  7301 W art     : b5c89000-b5c8a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b5c8a000-b5c98000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-12 12:00:37.686  7301  7301 W art     : b5c98000-b5c99000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b5c99000-b5c9a000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-12 12:00:37.686  7301  7301 W art     : b5c9a000-b5c9b000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-12 12:00:37.686  7301  7301 W art     : b5c9b000-b5ca5000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-12 12:00:37.686  7301  7301 W art     : b5ca5000-b5ca8000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-12 12:00:37.686  7301  7301 W art     : b5ca8000-b5ca9000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-12 12:00:37.686  7301  7301 W art     : b5ca9000-b5caa000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b5caa000-b5cb4000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-12 12:00:37.686  7301  7301 W art     : b5cb4000-b5cb7000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-12 12:00:37.686  7301  7301 W art     : b5cb7000-b5cb8000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-12 12:00:37.686  7301  7301 W art     : b5cb8000-b5cbc000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-12 12:00:37.686  7301  7301 W art     : b5cbc000-b5cbd000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-12 12:00:37.686  7301  7301 W art     : b5cbd000-b5cbe000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-12 12:00:37.686  7301  7301 W art     : b5cbe000-b5cbf000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b5cbf000-b5ccc000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-12 12:00:37.686  7301  7301 W art     : b5ccc000-b5cce000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-12 12:00:37.686  7301  7301 W art     : b5cce000-b5ccf000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-12 12:00:37.686  7301  7301 W art     : b5ccf000-b60e1000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-12 12:00:37.686  7301  7301 W art     : b60e1000-b60e2000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b60e2000-b60eb000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-12 12:00:37.686  7301  7301 W art     : b60eb000-b60ef000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-12 12:00:37.686  7301  7301 W art     : b60ef000-b60f0000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b60f0000-b60f7000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-12 12:00:37.686  7301  7301 W art     : b60f7000-b60f8000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-12 12:00:37.686  7301  7301 W art     : b60f8000-b60f9000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-12 12:00:37.686  7301  7301 W art     : b60f9000-b60fa000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b60fa000-b6115000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-12 12:00:37.686  7301  7301 W art     : b6115000-b6116000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-12 12:00:37.686  7301  7301 W art     : b6116000-b6117000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-12 12:00:37.686  7301  7301 W art     : b6117000-b6118000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b6118000-b6164000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-12 12:00:37.686  7301  7301 W art     : b6164000-b6165000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6165000-b6166000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-12 12:00:37.686  7301  7301 W art     : b6166000-b6167000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-12 12:00:37.686  7301  7301 W art     : b6167000-b6168000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b6168000-b616c000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-12 12:00:37.686  7301  7301 W art     : b616c000-b616d000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b616d000-b616e000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-12 12:00:37.686  7301  7301 W art     : b616e000-b616f000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-12 12:00:37.686  7301  7301 W art     : b616f000-b61a7000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-12 12:00:37.686  7301  7301 W art     : b61a7000-b61a8000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-12 12:00:37.686  7301  7301 W art     : b61a8000-b61a9000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-12 12:00:37.686  7301  7301 W art     : b61a9000-b61aa000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b61aa000-b6248000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-12 12:00:37.686  7301  7301 W art     : b6248000-b6249000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6249000-b6267000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-12 12:00:37.686  7301  7301 W art     : b6267000-b6268000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-12 12:00:37.686  7301  7301 W art     : b6268000-b63db000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-12 12:00:37.686  7301  7301 W art     : b63db000-b63e6000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-12 12:00:37.686  7301  7301 W art     : b63e6000-b63e7000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-12 12:00:37.686  7301  7301 W art     : b63e7000-b64fe000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-12 12:00:37.686  7301  7301 W art     : b64fe000-b6509000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-12 12:00:37.686  7301  7301 W art     : b6509000-b650a000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-12 12:00:37.686  7301  7301 W art     : b650a000-b650e000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b650e000-b6532000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-12 12:00:37.686  7301  7301 W art     : b6532000-b6534000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-12 12:00:37.686  7301  7301 W art     : b6534000-b6535000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-12 12:00:37.686  7301  7301 W art     : b6535000-b65db000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-12 12:00:37.686  7301  7301 W art     : b65db000-b65e8000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-12 12:00:37.686  7301  7301 W art     : b65e8000-b65e9000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-12 12:00:37.686  7301  7301 W art     : b65e9000-b65ea000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b65ea000-b663d000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-12 12:00:37.686  7301  7301 W art     : b663d000-b663e000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b663e000-b663f000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-12 12:00:37.686  7301  7301 W art     : b663f000-b6640000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-12 12:00:37.686  7301  7301 W art     : b6640000-b6645000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6645000-b6657000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-12 12:00:37.686  7301  7301 W art     : b6657000-b6658000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6658000-b6659000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-12 12:00:37.686  7301  7301 W art     : b6659000-b665a000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-12 12:00:37.686  7301  7301 W art     : b665a000-b6661000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-12 12:00:37.686  7301  7301 W art     : b6661000-b6662000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-12 12:00:37.686  7301  7301 W art     : b6662000-b6663000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-12 12:00:37.686  7301  7301 W art     : b6663000-b6664000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6664000-b6667000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-12 12:00:37.686  7301  7301 W art     : b6667000-b6668000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-12 12:00:37.686  7301  7301 W art     : b6668000-b6669000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-12 12:00:37.686  7301  7301 W art     : b6669000-b666d000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-12 12:00:37.686  7301  7301 W art     : b666d000-b666e000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-12 12:00:37.686  7301  7301 W art     : b666e000-b666f000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-12 12:00:37.686  7301  7301 W art     : b666f000-b667d000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-12 12:00:37.686  7301  7301 W art     : b667d000-b667e000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b667e000-b667f000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-12 12:00:37.686  7301  7301 W art     : b667f000-b6680000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-12 12:00:37.686  7301  7301 W art     : b6680000-b6689000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-12 12:00:37.686  7301  7301 W art     : b6689000-b668a000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-12 12:00:37.686  7301  7301 W art     : b668a000-b668b000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-12 12:00:37.686  7301  7301 W art     : b668b000-b66f1000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-12 12:00:37.686  7301  7301 W art     : b66f1000-b66f2000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b66f2000-b66f4000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-12 12:00:37.686  7301  7301 W art     : b66f4000-b66fd000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-12 12:00:37.686  7301  7301 W art     : b66fd000-b6700000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6700000-b6797000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-12 12:00:37.686  7301  7301 W art     : b6797000-b6799000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-12 12:00:37.686  7301  7301 W art     : b6799000-b679a000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-12 12:00:37.686  7301  7301 W art     : b679a000-b679b000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b679b000-b6abc000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-12 12:00:37.686  7301  7301 W art     : b6abc000-b6abd000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6abd000-b6ad8000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-12 12:00:37.686  7301  7301 W art     : b6ad8000-b6adc000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-12 12:00:37.686  7301  7301 W art     : b6adc000-b6ae1000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6ae1000-b6ae9000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-12 12:00:37.686  7301  7301 W art     : b6ae9000-b6aea000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-12 12:00:37.686  7301  7301 W art     : b6aea000-b6aeb000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-12 12:00:37.686  7301  7301 W art     : b6aeb000-b6b19000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-12 12:00:37.686  7301  7301 W art     : b6b19000-b6b1a000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6b1a000-b6b21000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-12 12:00:37.686  7301  7301 W art     : b6b21000-b6b22000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-12 12:00:37.686  7301  7301 W art     : b6b22000-b6b68000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-12 12:00:37.686  7301  7301 W art     : b6b68000-b6b69000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6b69000-b6b6c000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-12 12:00:37.686  7301  7301 W art     : b6b6c000-b6b6d000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-12 12:00:37.686  7301  7301 W art     : b6b6d000-b6b88000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-12 12:00:37.686  7301  7301 W art     : b6b88000-b6b8c000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-12 12:00:37.686  7301  7301 W art     : b6b8c000-b6b8d000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-12 12:00:37.686  7301  7301 W art     : b6b8d000-b6bda000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-12 12:00:37.686  7301  7301 W art     : b6bda000-b6bdb000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6bdb000-b6be7000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-12 12:00:37.686  7301  7301 W art     : b6be7000-b6be8000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-12 12:00:37.686  7301  7301 W art     : b6be8000-b6bf5000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-12 12:00:37.686  7301  7301 W art     : b6bf5000-b6bf6000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6bf6000-b6bf7000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-12 12:00:37.686  7301  7301 W art     : b6bf7000-b6bf8000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-12 12:00:37.686  7301  7301 W art     : b6bf8000-b6c00000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-12 12:00:37.686  7301  7301 W art     : b6c00000-b6c01000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6c01000-b6c02000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-12 12:00:37.686  7301  7301 W art     : b6c02000-b6c03000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-12 12:00:37.686  7301  7301 W art     : b6c03000-b6c0a000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-12 12:00:37.686  7301  7301 W art     : b6c0a000-b6c0b000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-12 12:00:37.686  7301  7301 W art     : b6c0b000-b6c0c000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-12 12:00:37.686  7301  7301 W art     : b6c0c000-b6c20000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-12 12:00:37.686  7301  7301 W art     : b6c20000-b6c22000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-12 12:00:37.686  7301  7301 W art     : b6c22000-b6c23000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-12 12:00:37.686  7301  7301 W art     : b6c23000-b6c4b000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-12 12:00:37.686  7301  7301 W art     : b6c4b000-b6c4d000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-12 12:00:37.686  7301  7301 W art     : b6c4d000-b6c4e000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-12 12:00:37.686  7301  7301 W art     : b6c4e000-b6c51000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-12 12:00:37.686  7301  7301 W art     : b6c51000-b6c52000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-12 12:00:37.686  7301  7301 W art     : b6c52000-b6c53000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-12 12:00:37.686  7301  7301 W art     : b6c53000-b6c5c000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-12 12:00:37.686  7301  7301 W art     : b6c5c000-b6c5d000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-12 12:00:37.686  7301  7301 W art     : b6c5d000-b6c5e000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-12 12:00:37.686  7301  7301 W art     : b6c5e000-b6c7e000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-12 12:00:37.686  7301  7301 W art     : b6c7e000-b6c7f000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-12 12:00:37.686  7301  7301 W art     : b6c7f000-b6c80000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-12 12:00:37.686  7301  7301 W art     : b6c80000-b6cf3000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-12 12:00:37.686  7301  7301 W art     : b6cf3000-b6cf7000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-12 12:00:37.686  7301  7301 W art     : b6cf7000-b6cfa000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-12 12:00:37.686  7301  7301 W art     : b6cfa000-b6d04000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6d04000-b6d8c000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-12 12:00:37.686  7301  7301 W art     : b6d8c000-b6d8d000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6d8d000-b6d91000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-12 12:00:37.686  7301  7301 W art     : b6d91000-b6d92000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-12 12:00:37.686  7301  7301 W art     : b6d92000-b6d93000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6d93000-b6dbc000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-12 12:00:37.686  7301  7301 W art     : b6dbc000-b6dbd000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6dbd000-b6dc0000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-12 12:00:37.686  7301  7301 W art     : b6dc0000-b6dc1000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-12 12:00:37.686  7301  7301 W art     : b6dc1000-b6e9b000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-12 12:00:37.686  7301  7301 W art     : b6e9b000-b6ea2000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-12 12:00:37.686  7301  7301 W art     : b6ea2000-b6eaa000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-12 12:00:37.686  7301  7301 W art     : b6eaa000-b6eab000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6eab000-b6eac000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 12:00:37.686  7301  7301 W art     : b6eac000-b6ead000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-12 12:00:37.686  7301  7301 W art     : b6ead000-b6eae000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b6eae000-b6eb1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b6eb1000-b6ed6000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-12 12:00:37.686  7301  7301 W art     : b6ed6000-b6ed7000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6ed7000-b6ede000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-12 12:00:37.686  7301  7301 W art     : b6ede000-b6edf000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-12 12:00:37.686  7301  7301 W art     : b6edf000-b6ee6000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-12 12:00:37.686  7301  7301 W art     : b6ee6000-b6ee7000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-12 12:00:37.686  7301  7301 W art     : b6ee7000-b6ee8000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-12 12:00:37.686  7301  7301 W art     : b6ee8000-b6ee9000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b6ee9000-b6f01000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-12 12:00:37.686  7301  7301 W art     : b6f01000-b6f02000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6f02000-b6f03000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-12 12:00:37.686  7301  7301 W art     : b6f03000-b6f04000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-12 12:00:37.686  7301  7301 W art     : b6f04000-b6f12000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-12 12:00:37.686  7301  7301 W art     : b6f12000-b6f13000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6f13000-b6f14000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-12 12:00:37.686  7301  7301 W art     : b6f14000-b6f15000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-12 12:00:37.686  7301  7301 W art     : b6f15000-b6f16000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 12:00:37.686  7301  7301 W art     : b6f16000-b6f18000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b6f18000-b6f19000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b6f19000-b6f1a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-12 12:00:37.686  7301  7301 W art     : b6f1a000-b6f1b000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-12 12:00:37.686  7301  7301 W art     : b6f1b000-b6f1c000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-12 12:00:37.686  7301  7301 W art     : b6f1c000-b6f3c000 r--s 00000000 00:0b 6706       /dev/__properties__
07-12 12:00:37.686  7301  7301 W art     : b6f3c000-b6f3d000 r--p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6f3d000-b6f3e000 ---p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6f3e000-b6f40000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-12 12:00:37.686  7301  7301 W art     : b6f40000-b6f41000 r-xp 00000000 00:00 0          [sigpage]
07-12 12:00:37.686  7301  7301 W art     : b6f41000-b6f5c000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-12 12:00:37.686  7301  7301 W art     : b6f5c000-b6f5d000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-12 12:00:37.686  7301  7301 W art     : b6f5d000-b6f5f000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-12 12:00:37.686  7301  7301 W art     : b6f5f000-b6f61000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : b6f61000-b6f66000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-12 12:00:37.686  7301  7301 W art     : b6f66000-b6f67000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-12 12:00:37.686  7301  7301 W art     : b6f67000-b6f68000 rw-p 00000000 00:00 0 
07-12 12:00:37.686  7301  7301 W art     : bed87000-beda8000 rw-p 00000000 00:00 0          [stack]
07-12 12:00:37.686  7301  7301 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-12 12:00:37.726  7301  7301 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 12:00:37.776  7301  7301 I Radio-JNI: register_android_hardware_Radio DONE
07-12 12:00:37.786  7301  7301 E AffinityControl: AffinityControl: registerfunction enter
07-12 12:00:37.796  7301  7301 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-12 12:00:37.816   777  1421 D PackageManager: START PACKAGE DELETE: observer{177749712}
07-12 12:00:37.816   777  1421 D PackageManager: pkg{<packageName>}
07-12 12:00:37.816   777  1421 D PackageManager: user{0}
07-12 12:00:37.816   777  1421 D PackageManager: caller{2000}
07-12 12:00:37.816   777  1421 D PackageManager: flags{2}
07-12 12:00:37.816   777  1421 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-12 12:00:37.816   777  1421 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-12 12:00:37.816   777  1421 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-12 12:00:37.816   777  1421 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-12 12:00:37.816   777  1421 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-12 12:00:37.816   777   939 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-12 12:00:37.816   777   939 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-12 12:00:37.816   777   939 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-12 12:00:37.816   777   939 D ApplicationPolicy: getApplicationUninstallationEnabled
07-12 12:00:37.816   777   939 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-12 12:00:37.816   777   939 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-12 12:00:37.816   777   939 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-12 12:00:37.816   777   939 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
07-12 12:00:37.816   777   861 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
07-12 12:00:37.816   777   939 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-12 12:00:37.826   777   939 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-12 12:00:37.826   777   861 I ActivityManager: Killing 5909:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
07-12 12:00:37.836   777   861 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-12 12:00:37.836   777   861 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-12 12:00:37.836   777   861 D ActivityManager: mDVFSHelper.acquire()
07-12 12:00:37.856   777   861 I ActivityManager: Start proc 7316:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-12 12:00:37.856   777   861 I ActivityManager: Killing 7210:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 663s, lastActivityTime 663s
07-12 12:00:37.856   777   861 I ActivityManager: Killing 7164:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 664s, lastActivityTime 664s
07-12 12:00:37.856   777   861 I ActivityManager: Killing 7132:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 841s, lastActivityTime 841s
07-12 12:00:37.856   777   861 I ActivityManager: Killing 7118:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 851s, lastActivityTime 851s
07-12 12:00:37.856  7316  7316 E Zygote  : v2
07-12 12:00:37.856  7316  7316 I libpersona: KNOX_SDCARD checking this for 10004
07-12 12:00:37.856  7316  7316 I libpersona: KNOX_SDCARD not a persona
07-12 12:00:37.856  7316  7316 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-12 12:00:37.856  7316  7316 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 12:00:37.856   777   861 I ActivityManager:   Force finishing activity ActivityRecord{8748049 u0 com.test.thalitest/.MainActivity t104}
07-12 12:00:37.856  7316  7316 E Zygote  : accessInfo : 0
07-12 12:00:37.866  7316  7316 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-12 12:00:37.866   777   912 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-12 12:00:37.866   777   912 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-12 12:00:37.866   777   912 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
07-12 12:00:37.866   777   912 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
07-12 12:00:37.866   777   912 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4342)
07-12 12:00:37.866   777   912 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
07-12 12:00:37.866   777   912 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 12:00:37.866   777   912 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-12 12:00:37.866   777   912 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 12:00:37.866   777   912 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-12 12:00:37.896   293   293 I ServiceManager: service 'AtCmdFwd' died
07-12 12:00:37.896   371  4911 I Atfwd_Sendcmd: AtCmdFwd : binderDied
07-12 12:00:37.896   371  4911 I ServiceManager: Waiting for service AtCmdFwd...
07-12 12:00:37.896  7316  7316 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 12:00:37.896  7316  7316 D ActivityThread: Added TimaKeyStore provider
07-12 12:00:37.906   777   939 D AASAinstall: there is not AASApackages.xml file
07-12 12:00:37.936   777   790 D GraphicsStats: Buffer count: 4
07-12 12:00:37.936   777  1678 I WindowState: WIN DEATH: Window{c3a2f6a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 12:00:37.946   777  1718 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@30517e8)
07-12 12:00:37.946   777  1336 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 12:00:37.946   777  1336 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 12:00:37.946   294   384 I SurfaceFlinger: id=16 Removed NainActivit (6/8)
07-12 12:00:37.946   294   379 I SurfaceFlinger: id=16 Removed NainActivit (-2/8)
07-12 12:00:37.956   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbea013a4
07-12 12:00:37.956   777  1336 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 12:00:37.956   777  1678 D InputDispatcher: Focus left window: 5909
07-12 12:00:38.216   777   939 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
07-12 12:00:38.236   777   939 W PackageSettings: Skipping PackageSetting{c5b591e com.example.hello/10192} due to missing metadata
07-12 12:00:38.306   777   939 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-12 12:00:38.306   777   912 D SecWifiDisplayUtil: Metadata value : none
07-12 12:00:38.306   777   912 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{be40e01 V.E...... R.....ID 0,0-0,0}
07-12 12:00:38.316   777   912 D ISSUE_DEBUG: InputChannelName : 3746ee7 Starting com.test.thalitest

```
