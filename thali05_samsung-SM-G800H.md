#### Test 57659382b63fd0b_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/TimaKeyStoreProvider( 3711): in addTimaSignatureService
D/TimaKeyStoreProvider( 3711): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3711): Added TimaKesytore provider
--------- beginning of /dev/log/system
W/ContextImpl( 3711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2698 
E/AtFwd AutoBoot( 3711): AtFwd Auto Boot Started Successfully
D/AtFwdService( 3711): onCreate method
I/AtFwdService( 3711): Instantiate AtCmdFwd Service
D/AtCkpdCmdHandler( 3711): De-queing command
W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.location.LocationServiceReceiver.onReceive:41 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 3740): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3740):  
,D/dalvikvm(  249): GC_EXPLICIT freed 44K, 50% free 9510K/18884K, paused 2ms+2ms, total 24ms
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9510K/18884K, paused 2ms+2ms, total 18ms
I/SELinux ( 3740): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3740):  
I/SELinux ( 3740):  
I/SELinux ( 3740): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3740): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3740): >>>>> Normal User
E/dalvikvm( 3740): >>>>> com.android.vending [ userId:0 | appId:10030 ]
E/SELinux ( 3740): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9510K/18884K, paused 2ms+2ms, total 19ms
I/GoogleConversionPing( 3654): Ping responded with response code 200
D/TimaKeyStoreProvider( 3740): in addTimaSignatureService
D/TimaKeyStoreProvider( 3740): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3740): Added TimaKesytore provider
I/dalvikvm( 3740): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 3740): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 3740): VFY: replacing opcode 0x6e at 0x000e
D/Finsky  ( 3740): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/dalvikvm( 3740): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 3740): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3740): VFY: replacing opcode 0x6e at 0x01d3
D/AmoledAdjustTimer(  751): prevTemp = 281, currTemp = 284, prevStep = 4, currStep = 4
I/dalvikvm( 3740): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 3740): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 3740): VFY: replacing opcode 0x6e at 0x000a
D/AndroidRuntime( 3752): 
D/AndroidRuntime( 3752): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3752): CheckJNI is OFF
D/AndroidRuntime( 3752): setted country_code = Poland
D/AndroidRuntime( 3752): setted countryiso_code = PL
D/AndroidRuntime( 3752): setted sales_code = XEO
D/AndroidRuntime( 3752): readGMSProperty: start
D/AndroidRuntime( 3752): readGMSProperty: already setted!!
D/AndroidRuntime( 3752): readGMSProperty: end
D/AndroidRuntime( 3752): addProductProperty: start
D/dalvikvm( 3752): Trying to load lib libjavacore.so 0x0
D/Finsky  ( 3740): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/dalvikvm( 3752): Added shared lib libjavacore.so 0x0
I/dalvikvm( 3740): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3740): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 3740): VFY: replacing opcode 0x6e at 0x0032
D/dalvikvm( 3752): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3752): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3752): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/Settings( 3740): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3740): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/dalvikvm( 3740): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3740): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3740): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 3740): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3740): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3740): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 3740): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3740): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3740): VFY: replacing opcode 0x6e at 0x0385
I/dalvikvm( 3740): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 3740): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 3740): VFY: replacing opcode 0x6e at 0x0019
D/Volley  ( 3740): [347] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 3740): Skipping gmscore version check
D/Finsky  ( 3740): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3740): [1] Libraries$2.run: Finished loading 1 libraries.
D/Volley  ( 3740): [354] DiskBasedCache.clear: Cache cleared.
D/Finsky  ( 3740): [1] GmsCoreHelper.cleanupNlp: result=false type=4
E/memtrack( 3752): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3752): failed to load memtrack module: -2
D/Finsky  ( 3740): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/dalvikvm( 3752): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 3752): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 3752): Shutting down VM
D/dalvikvm( 3752): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 1ms+1ms, total 3ms
D/dalvikvm( 1751): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1751): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1751): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1751): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 1751): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1751): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 1751): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1751): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1751): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1751): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1751): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1751): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1751): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1751): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1751): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 1751): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1751): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1751): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
D/FileApkUtils( 1751): Spent 44ms computing apk sha1.
D/FileApkUtils( 1751): Module already staged or being staged:chimera-modules/MapsModule.apk
D/DexOptUtils( 1751): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1751): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 1751): Reading stored module config
D/dalvikvm( 1300): GC_EXPLICIT freed 2145K, 44% free 10697K/18884K, paused 3ms+4ms, total 34ms
D/GmsModuleFndr( 1751): Beginning GMS chimera module scan
W/InstanceID/Rpc( 1751): Found 10011
D/ChimeraCfgMgr( 1751): Beginning module configuration check
D/ChimeraCfgMgr( 1751): Module APKs unchanged, check complete
,E/dalvikvm( 1751): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1751): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1751): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1751): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1751): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1751): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1751): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1751): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1751): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1751): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1751): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,W/dalvikvm( 1751): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1751): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1751): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1217): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 1217): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1217): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1217): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1217): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1217): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1217): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,I/dalvikvm( 1217): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x0021
E/dalvikvm( 1751): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1751): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 1751): VFY: replacing opcode 0x1f at 0x000e
,D/dalvikvm( 1217): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1217): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1217): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1217): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1751): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1751): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1751): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 1751): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1751): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1751): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
D/dalvikvm( 1751): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1751): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1751): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1751): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1751): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1751): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/GCM     ( 1751): COMPAT: Multi user not supported
,I/CheckinService( 1751): Checkin interval check for package: unspecified last checkin: 1453985581353 min interval config: 0 actual interval: 97004080
,I/dalvikvm( 1300): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
,W/dalvikvm( 1300): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 1300): VFY: replacing opcode 0x6e at 0x0010
,D/dalvikvm( 1751): GC_CONCURRENT freed 1645K, 41% free 11267K/18884K, paused 6ms+4ms, total 58ms
,D/dalvikvm( 1751): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 1751): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/CheckinService( 1751): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 1751): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/dalvikvm( 1751): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1751): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/GCoreUlr( 1217): DispatchingService.onCreate()
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 1751): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1751): Got an BootCompleted event.
,D/BootCompletedReceiver( 1751): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 1751): onCreate
,D/dalvikvm( 1300): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1300): VFY: unable to resolve instance field 161
,D/dalvikvm( 1300): VFY: replacing opcode 0x52 at 0x0006
,I/CheckinService( 1751): Checking schedule, now: 1454082585519 next: 1454573107295
,D/SystemUpdateService( 1751): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/CheckinService( 1751): active receiver: disabled
I/dalvikvm( 1751): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1751): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
D/dalvikvm( 1751): VFY: replacing opcode 0x6e at 0x0409
V/AuthZen ( 1751): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 1751): cancelUpdate (empty URL)
I/SystemUpdateService( 1751): active receiver: disabled
,D/EnterpriseDeviceManagerService(  751): Creating context as user 0
,I/dalvikvm( 1751): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 1751): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1751): VFY: replacing opcode 0x6e at 0x002b
,W/dalvikvm( 1751): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/GCoreUlr( 1217): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 1751): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x425ecd88
,I/dalvikvm( 1300): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1300): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1300): VFY: replacing opcode 0x6e at 0x0059
,I/dalvikvm( 1300): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
,W/dalvikvm( 1300): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1300): VFY: replacing opcode 0x6e at 0x0022
,D/dalvikvm( 1217): GC_CONCURRENT freed 1689K, 40% free 11437K/18884K, paused 7ms+14ms, total 63ms
,D/EnterpriseDeviceManagerService(  751): Creating context as user 0
,D/SystemUpdateService( 1751): onDestroy
,D/dalvikvm( 1751): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x425ecd88
,D/dalvikvm( 1751): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x425ecd88, skipping init
,D/AuthZenEventHandler( 1751): Handling event: android.intent.action.BOOT_COMPLETED
,D/GCM     ( 1300): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 1300): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1300): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1300): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1300): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1300): VFY: replacing opcode 0x6e at 0x0053
,W/Auth    ( 1300): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/GCoreUlr( 1217): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,V/GLSActivity( 1300): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1217): Unbound from all location providers
,I/GCoreUlr( 1217): Place inference reporting - stopped
,W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,D/LockPatternUtils( 1066): isPcwEnable = null
,I/GCoreUlr( 1217): DispatchingService.onDestroy()
,W/dalvikvm( 1751): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/GCoreUlr( 1217): Stopping handler for UlrDispSvcFast
,W/dalvikvm( 1751): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/GCoreUlr( 1217): Unbound from all location providers
,I/GCoreUlr( 1217): Place inference reporting - stopped
,W/dalvikvm( 1751): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1751): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1751): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1751): VFY: replacing opcode 0x6e at 0x00bb
,E/BaseAppContext( 1751): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/PersistentNotificationBroadcastReceiver( 1217): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/dalvikvm( 1751): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
,W/dalvikvm( 1751): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1751): VFY: replacing opcode 0x6e at 0x002f
,I/BootupListener( 1238): mPendingNetworkManualSelection : false
,D/StatusChecker( 3337): onReceive : android.intent.action.SERVICE_STATE
,D/StatusChecker( 3337): Service state changed : 3
,I/AuthZen ( 1751): Fetching signing key...
,I/AuthZen ( 1751): Signing key fetched successfully!
,D/WearableService( 1217): callingUid 10011, callindPid: 1217
,E/MDM     ( 1217): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,D/LocationInitializer( 1751): Restart initialization of location
D/AuthorizationBluetoothService( 1300): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1300): Proximity feature is not enabled.
,V/GLSActivity( 1300): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AuthZenTransactionCache( 1751): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1751): Clearing transaction cache
,W/GCoreFlp( 1217): No location to return for getLastLocation()
,W/FusedLocationProvider( 1217): location=null
V/AlarmManager(  751): waitForAlarm result :8
,E/MDM     ( 1217): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1751): Restart initialization of location
,D/AuthorizationBluetoothService( 1300): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1300): Proximity feature is not enabled.
,W/GCoreFlp( 1217): No location to return for getLastLocation()
,W/FusedLocationProvider( 1217): location=null
,V/AlarmManager(  751): waitForAlarm result :8
,V/GLSActivity( 1300): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCM     ( 1300): GCM config loaded
,I/SELinux ( 3880): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3880):  
,D/QuickConnect[1.1][2] ( 3353): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3353): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1664): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 1664): performUpdate:widgetCount=0
V/AlarmManager(  751): waitForAlarm result :8
,D/ContactProvider( 2427): getAllContactInfoList Start
,I/SELinux ( 3880): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3880):  
I/SELinux ( 3880):  
,I/SELinux ( 3880): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3880): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3880): >>>>> Normal User
,E/dalvikvm( 3880): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
,E/SELinux ( 3880): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3880): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3880): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3880): Added TimaKesytore provider
,W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=3880, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
V/TaskCloserActivity( 3880): TaskCloserActivity enter()
E/SMD     (  242): DCD ON
,D/dalvikvm(  751): GC_EXPLICIT freed 2206K, 13% free 23460K/26952K, paused 8ms+12ms, total 150ms
,I/SELinux ( 3898): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3898):  
,D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
,D/QuickConnect[1.1][2] ( 3353): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3353): CONTACT_Info.getMyMobileNumber - null 
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService(  751):   -0.0 -0.1 9.6
,D/Mms/Contact( 1664): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3353): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3353): CONTACT_Info.getMyMobileNumber - 
,D/QuickConnect[1.1][2] ( 3353): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3353): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2427): getAllContactInfoList End
,I/syncContacts( 2427): thread: 170, onChange
,D/ContactProvider( 2427): getAllContactInfoList Start
,I/SELinux ( 3898): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3898):  
I/SELinux ( 3898):  
,I/SELinux ( 3898): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3898): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3898): >>>>> Normal User
,E/dalvikvm( 3898): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 3898): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/ContactProvider( 2427): getAllContactInfoList End
,I/syncContacts( 2427): thread: 170, onChange
,D/TimaKeyStoreProvider( 3898): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3898): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3898): Added TimaKesytore provider
,D/FactoryTestApp( 3898): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3898): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3898): User mode
,I/SELinux ( 3910): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3910):  
I/ActivityManager(  751): Killing 2804:com.osp.app.signin/u0a43 (adj 15): empty #43
,I/SELinux ( 3910): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3910):  
I/SELinux ( 3910):  
,I/SELinux ( 3910): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3910): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3910): >>>>> Normal User
,E/dalvikvm( 3910): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3910): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3910): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3910): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3910): Added TimaKesytore provider
,E/MTPRx   ( 3910): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3910): check value of boot_completed is1
,E/MTPRx   ( 3910): check booting is completed_sys.boot_completed
D/ConnectivityService(  751): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,E/MTPRx   ( 3910): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3910): Status for mount/Unmount :removed
,E/MTPRx   ( 3910): SDcard is not available
,W/MTPRx   ( 3910): value of connected istrue
W/MTPRx   ( 3910): value of configured istrue
W/MTPRx   ( 3910): value of mtpEnabled istrue
,W/MTPRx   ( 3910): value of ptpEnabled isfalse
E/MTPRx   ( 3910): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3910): mFirstTime: false
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/        ( 3910): MTP: reading debug level property
,E/MTPRx   ( 3910):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3910): Getting CryptionKey from JAVA
,E/MTPRx   ( 3910): currentUserId is 0
,E/MTPRx   ( 3910): Start observing USB_STATE_MATCH 
E/MTPRx   ( 3910): usbMode is 0200
E/MTPRx   ( 3910): is_secretmode is NOT 1
W/MTPRx   ( 3910): Phone is lockedtrue
D/LockPatternUtils( 1066): isPcwEnable = null
D/MTPRx   ( 3910):  inside checkKnoxStatus
,D/MTPRx   ( 3910):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3910): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3910): noti = 17
,E/MTPRx   ( 3910): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3910): else part ... so first time!!!
E/MTPPlaObsrvr( 3910): inside setContext()
,E/MTPPlaObsrvr( 3910):  inside createplafiles
,E/MTPPlaObsrvr( 3910): playlist count is0
,E/MTPPlaObsrvr( 3910):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3910):  inside deleteing plas createplafiles
,D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
,E/MTPPlaObsrvr( 3910): Inside registerContentObserver
,E/MtpAdbObserver( 3910): inside setContext()
E/MtpAdbObserver( 3910): Inside registerContentObserver
,W/Settings( 3910): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 3910): onCreate.
,E/MtpService( 3910): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3910): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3910): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3910): onStartCommand.
W/MTPRx   ( 3910): calling native method
,E/MTPJNIInterface( 3910): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3910): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 3910): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3910): noti = 10
,W/MTPRx   ( 3910): calling native method
E/MTPRx   ( 3910): Checking the driver time out
E/MTPJNIInterface( 3910): noti = 2
,D/        ( 3910): deleting sockets before message queue initialization
D/        ( 3910): event handler thread is created, so set the flag
,E/MTPRx   ( 3910): called native method
E/MTPJNIInterface( 3910): setting Media scanner status0
E/MTPJNIInterface( 3910): After setting Media scanner status0
,E/MtpService( 3910): onStartCommand.
,E/MTPJNIInterface( 3910): Getting media scanner status0
,W/MTPRx   ( 3910): notification from stack 1
,E/MTPJNIInterface( 3910): DeviceName is Galaxy S5-2
,E/MtpService( 3910): handleMessage. msg= { when=-6ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,I/knox    ( 3287): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3287): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3287): KNOXAgentService : onCreate()
D/knox    ( 3287): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3287): KNOXAgentService. startJobThread() start
D/knox    ( 3287): KNOXAgentService. JobThread()
D/knox    ( 3287): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3287): KNOXAgentService. startJobThread() wait
D/knox    ( 3287): KNOXAgentService : onDestroy().
D/knox    ( 3287): ModuleBase.cancelAllAlarmManageModule()
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1462): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1462): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1462): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1462): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454104140000
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454082586894
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1295): onReceive
,D/AuthorizationBluetoothService( 1300): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3287): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3287): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,I/knox    ( 3287): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3287): KNOXAgentService : onCreate()
,D/knox    ( 3287): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3287): KNOXAgentService. startJobThread() start
D/knox    ( 3287): KNOXAgentService. JobThread()
,D/knox    ( 3287): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3287): KNOXAgentService. startJobThread() wait
,W/ContextImpl( 3287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3287): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/knox    ( 3287): KNOXAgentService : onDestroy().
D/knox    ( 3287): ModuleBase.cancelAllAlarmManageModule()
I/knox    ( 3287): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
D/FileShare-Server( 3031): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 3031): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3941): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3941):  
,I/SELinux ( 3941): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3941):  
I/SELinux ( 3941):  
I/SELinux ( 3941): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3941): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3941): >>>>> Normal User
E/dalvikvm( 3941): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
E/SELinux ( 3941): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3941): in addTimaSignatureService
D/TimaKeyStoreProvider( 3941): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3941): Added TimaKesytore provider
I/System.out( 3941): Inside WakeupProvider
I/System.out( 3941): Inside onCreate() of WakeupTriggerProvide
I/VlingoApplication( 3941): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
D/VlingoApplication( 3941): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 3941): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
D/DialogFlow( 3941): initQueue()
W/ContextImpl( 1295): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/LocalBluetoothProfileManager( 1295): Adding local A2DP profile
D/LocalBluetoothProfileManager( 1295): Adding local HEADSET profile
W/ContextImpl( 1295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
E/BluetoothHeadset( 1295): BTStateChangeCB is registed
E/BluetoothHeadset( 1295): BluetoothHeadset service is binded
D/Bluetoothsap( 1295): bindService called to Bluetooth SAP Service
W/ContextImpl( 1295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
W/ContextImpl( 1295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
W/ContextImpl( 1295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
I/Atfwd_Daemon(  291): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  291): ATFWD --> QMI Port : rmnet1
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
D/LocalBluetoothProfileManager( 1295): PANU : true
D/LocalBluetoothProfileManager( 1295): Adding local MAP profile
I/Atfwd_Daemon(  291): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  291): Trying to register 8 commands:
I/Atfwd_Daemon(  291): cmd0: +CKPD
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  291): cmd1: +CTSA
D/BluetoothMap( 1295): Create BluetoothMap proxy object
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  291): cmd2: +CFUN
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  291): cmd3: +CMAR
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  291): cmd4: +CDIS
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  291): cmd5: +CRSL
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  291): cmd6: +CSS
W/ContextImpl( 1295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  291): cmd7: $QCPWRDN
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  291): Registered AT Commands event handler
D/dalvikvm( 1295): GC_CONCURRENT freed 7533K, 47% free 10066K/18884K, paused 3ms+2ms, total 59ms
W/ContextImpl( 1295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
W/ContextImpl( 1295): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 1295): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 1295): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 1295): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 1295): onReceive
D/BluetoothA2dp( 1295): Proxy object connected
D/A2dpProfile( 1295): Bluetooth service connected
D/BtConfig.SecureMode( 1936): isSecureModeOn:false
D/HeadsetProfile( 1295): Bluetooth service connected
D/AuthorizationBluetoothService( 1300): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1300): Proximity feature is not enabled.
D/BluetoothInputDevice( 1295): Proxy object connected
D/HidProfile( 1295): Bluetooth service connected
D/BluetoothPan( 1295): BluetoothPAN Proxy object connected
D/PanProfile( 1295): Bluetooth service connected
D/BluetoothMap( 1295): Proxy object connected
D/MapProfile( 1295): Bluetooth service connected
D/BluetoothPbap( 1295): Proxy object connected
D/PbapServerProfile( 1295): Bluetooth service connected
W/BluetoothAdapter( 1936): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1936): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 1936): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
I/BtOppRfcommListener( 1936): Accept thread started.
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
D/Toast   ( 1295):  checkMirrorLinkEnabled returns : false
D/Toast   ( 1295): showing allowed
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
I/SurfaceFlinger(  248): id=15 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  751): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=751
D/DisplayPowerController(  751): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/SELinux ( 3979): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3979):  
D/PowerManagerService(  751): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/GKI_LINUX( 1936): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/lights  (  751): lcd : 8 +
D/dalvikvm( 1205): GC_EXPLICIT freed 3900K, 47% free 10047K/18884K, paused 3ms+7ms, total 47ms
D/RampAnimator(  751): Light Animator Finished currentValue=8
D/lights  (  751): lcd : 8 -
E/MTPJNIInterface( 3910): Status for mount/Unmount :removed
E/MTPJNIInterface( 3910): SDcard is not available
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SELinux ( 3979): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3979):  
I/SELinux ( 3979):  
I/SELinux ( 3979): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3979): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3979): >>>>> Normal User
E/dalvikvm( 3979): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux ( 3979): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/MTPJNIInterface( 3910): Status for mount/Unmount :removed
E/MTPJNIInterface( 3910): SDcard is not available
E/SQLiteLog( 3910): (21) API call with NULL database connection pointer
E/SQLiteLog( 3910): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3910): (21) API call with NULL database connection pointer
E/SQLiteLog( 3910): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3910): (21) API call with NULL database connection pointer
E/SQLiteLog( 3910): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3910): (21) API call with NULL database connection pointer
E/SQLiteLog( 3910): (21) misuse at line 96833 of [00bb9c9ce4]
W/MTPRx   ( 3910): notification from stack 2
D/        ( 3910): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3910): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3910): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
D/        ( 3910): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/dalvikvm( 3979): Enabling JNI app bug workarounds for target SDK version 8...

```
