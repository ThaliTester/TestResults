#### Test 50388019385b4d9_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
E/Auth    ( 1134): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1191): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/InstanceID/Rpc(  981): Found 10007
D/dalvikvm( 1774): GC_CONCURRENT freed 337K, 3% free 17158K/17524K, paused 3ms+1ms, total 26ms
I/Gmail   ( 1774): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 1774): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 1774): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
I/Gmail   ( 1774): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 1774): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 1774): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
--------- beginning of /dev/log/system
I/ActivityManager(  773): Delay finish: com.google.android.keep/.notification.AlertReceiver
I/Gmail   ( 1774): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/Gmail   ( 1774): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^iim (has extras) }
I/ActivityManager(  773): Resuming delayed broadcast
D/dalvikvm( 1811): GC_CONCURRENT freed 244K, 2% free 16899K/17172K, paused 4ms+4ms, total 37ms
I/LauncherIconVisibilityManager(  967): Boot has been completed
I/LauncherIconVisibilityManager(  967): Activity has already been disabled: ComponentInfo{com.google.android.inputmethod.latin/com.android.inputmethod.latin.setup.SetupActivity}
I/ActivityManager(  773): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=1840 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
D/dalvikvm(  182): GC_EXPLICIT freed 41K, 1% free 16699K/16772K, paused 3ms+3ms, total 39ms
D/dalvikvm(  182): WAIT_FOR_CONCURRENT_GC blocked 1ms
I/ActivityManager(  773): Killing 1074:com.android.printspooler/u0a64 (adj 15): empty #17
I/ActivityManager(  773): Killing 1448:com.google.android.apps.magazines/u0a56 (adj 15): empty #17
D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+2ms, total 35ms
D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+2ms, total 17ms
I/ActivityManager(  773): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=1853 uid=1001 gids={41001, 3002, 3001, 3003, 2001, 1028, 1015}
D/QcrilMsgTunnelAutoboot( 1853): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/QcrilMsgTunnelService( 1853): onCreate method
D/QcrilMsgTunnelIfaceManager( 1853): : Instantiated
W/BroadcastQueue(  773): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.apps.plus/com.google.android.libraries.social.notifications.impl.BootCompletedReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
V/QcrilMsgTunnelSocket( 1853): Starting QcRilReceiver
D/QcrilMsgTunnelIfaceManager( 1853):  Registered for UNSOL OEM HOOK Responses to deliver external apps
D/QcrilMsgTunnelSocket( 1853): Connecting to socket android.net.LocalSocket@4264b838 impl:android.net.LocalSocketImpl@4264b860 fd:FileDescriptor[42]
I/QcrilMsgTunnelSocket( 1853): Connected to 'qmux_radio/rild_oem0' socket
V/QcrilMsgTunnelSocket( 1853): Before reading offset = 0 remaining = 4 countRead = 0
D/dalvikvm( 1298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1298): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1298): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 1298): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1298): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 1298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1298): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1298): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1298): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1298): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1298): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 1298): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1298): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
D/dalvikvm( 1298): GC_FOR_ALLOC freed 170K, 5% free 17980K/18736K, paused 20ms, total 20ms
D/FileApkUtils( 1298): Spent 46ms computing apk sha1.
D/FileApkUtils( 1298): Module already staged or being staged:chimera-modules/MapsModule.apk
D/DexOptUtils( 1298): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1298): Keeping up-to-date module: module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3
D/ChimeraCfgMgr( 1298): Reading stored module config
W/InstanceID/Rpc( 1298): Found 10007
D/GmsModuleFndr( 1298): Beginning GMS chimera module scan
D/dalvikvm( 1298): GC_FOR_ALLOC freed 201K, 4% free 18025K/18736K, paused 14ms, total 14ms
D/ChimeraCfgMgr( 1298): Beginning module configuration check
D/ChimeraCfgMgr( 1298): Module APKs unchanged, check complete
E/dalvikvm( 1298): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1298): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
D/dalvikvm( 1298): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1298): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1298): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1298): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1298): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1298): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1298): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
D/dalvikvm( 1298): VFY: replacing opcode 0x6e at 0x0021
D/dalvikvm( 1298): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1298): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1298): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/dalvikvm( 1298): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
E/dalvikvm(  981): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm(  981): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
D/dalvikvm(  981): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm(  981): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm(  981): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm(  981): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm(  981): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
E/dalvikvm( 1298): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1298): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 1298): VFY: replacing opcode 0x1f at 0x000e
I/dalvikvm(  981): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm(  981): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
D/dalvikvm(  981): VFY: replacing opcode 0x6e at 0x0021
D/dalvikvm(  981): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm(  981): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm(  981): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/dalvikvm(  981): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
E/dalvikvm( 1298): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1298): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
D/dalvikvm( 1298): VFY: replacing opcode 0x1f at 0x00f6
D/dalvikvm( 1298): GC_CONCURRENT freed 425K, 4% free 18086K/18736K, paused 3ms+6ms, total 63ms
D/dalvikvm( 1298): WAIT_FOR_CONCURRENT_GC blocked 17ms
W/dalvikvm( 1298): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1298): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1298): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
D/dalvikvm( 1298): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1298): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1298): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
I/dalvikvm( 1298): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
D/dalvikvm(  981): GC_CONCURRENT freed 534K, 4% free 18588K/19220K, paused 4ms+5ms, total 59ms
D/dalvikvm( 1298): GC_FOR_ALLOC freed 108K, 4% free 18098K/18736K, paused 15ms, total 15ms
I/CheckinService( 1298): Checkin interval check for package: unspecified last checkin: 1450186148736 min interval config: 0 actual interval: 3143051
D/GCM     ( 1298): COMPAT: Multi user not supported
D/GCM     ( 1134): COMPAT: Multi user not supported
W/dalvikvm( 1298): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1134): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
W/dalvikvm( 1134): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1134): VFY: replacing opcode 0x6e at 0x000f
W/dalvikvm( 1298): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/CheckinService( 1298): Disabling old GoogleServicesFramework version
I/dalvikvm( 1134): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 1134): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
D/dalvikvm( 1134): VFY: replacing opcode 0x6e at 0x0010
I/GCoreUlr( 1298): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
D/ChimeraCfgMgr( 1298): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/BootCompletedReceiver( 1298): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 1298): Got an BootCompleted event.
I/GCoreUlr(  981): DispatchingService.onCreate()
D/BootCompletedReceiver( 1298): Will NOT schedule AdAttestation signal task because it's disabled.
D/SystemUpdateService( 1298): onCreate
D/dalvikvm( 1134): GC_CONCURRENT freed 320K, 5% free 17847K/18720K, paused 2ms+3ms, total 49ms
D/dalvikvm( 1298): GC_FOR_ALLOC freed 203K, 4% free 18161K/18736K, paused 48ms, total 48ms
I/GCoreUlr(  981): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/dalvikvm( 1298): GC_FOR_ALLOC freed 13K, 3% free 18181K/18736K, paused 27ms, total 27ms
I/dalvikvm-heap( 1298): Grow heap (frag case) to 17.797MB for 16400-byte allocation
D/dalvikvm( 1134): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1134): VFY: unable to resolve instance field 161
D/dalvikvm( 1134): VFY: replacing opcode 0x52 at 0x0006
D/dalvikvm( 1298): GC_FOR_ALLOC freed 1K, 3% free 18195K/18756K, paused 26ms, total 26ms
,I/GCoreUlr(  981): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/dalvikvm( 1298): GC_FOR_ALLOC freed 46K, 4% free 18178K/18756K, paused 25ms, total 25ms
I/GCoreUlr(  981): Unbound from all location providers
I/GCoreUlr(  981): Place inference reporting - stopped
I/dalvikvm( 1134): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1134): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1134): VFY: replacing opcode 0x6e at 0x0059
D/SystemUpdateService( 1298): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/dalvikvm( 1298): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1298): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
D/dalvikvm( 1298): VFY: replacing opcode 0x6e at 0x0409
V/AuthZen ( 1298): Handling intent: android.intent.action.BOOT_COMPLETED
I/dalvikvm( 1134): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1134): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1134): VFY: replacing opcode 0x6e at 0x0022
I/CheckinService( 1298): Checking schedule, now: 1450189292057 next: 1450228637710
D/AuthZenEventHandler( 1298): Handling event: android.intent.action.BOOT_COMPLETED
I/CheckinService( 1298): active receiver: disabled
D/GCM     ( 1134): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr(  981): DispatchingService.onDestroy()
I/GCoreUlr(  981): Stopping handler for UlrDispSvcFast
V/GLSActivity( 1134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/SocketClient(  178): write error (Broken pipe)
D/ConnectivityService(  773): handleInetConditionChange: no active default network - ignore
I/GCoreUlr(  981): Unbound from all location providers
I/GCoreUlr(  981): Place inference reporting - stopped
V/GLSActivity( 1134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1134): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1134): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1134): VFY: replacing opcode 0x6e at 0x0053
W/Auth    ( 1134): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 1298): GC_FOR_ALLOC freed 264K, 3% free 18249K/18756K, paused 61ms, total 63ms
W/BaseAppContext( 1298): Using Auth Proxy for data requests.
I/SystemUpdateService( 1298): active receiver: enabled
W/dalvikvm( 1298): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1298): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/PersistentNotificationBroadcastReceiver(  981): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
W/dalvikvm( 1298): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1298): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1298): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1298): VFY: replacing opcode 0x6e at 0x00bb
D/dalvikvm( 1134): GC_CONCURRENT freed 319K, 5% free 17930K/18720K, paused 2ms+4ms, total 61ms
E/BaseAppContext( 1298): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/ActivityManager(  773): Start proc com.google.android.email for broadcast com.google.android.email/com.android.email.service.EmailBroadcastReceiver: pid=1931 uid=10036 gids={50036, 3003, 1028, 1015}
D/AndroidRuntime( 1910): 
D/AndroidRuntime( 1910): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 1910): CheckJNI is OFF
D/dalvikvm( 1298): GC_CONCURRENT freed 365K, 3% free 18392K/18788K, paused 7ms+12ms, total 88ms
D/dalvikvm( 1910): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 1910): Added shared lib libjavacore.so 0x0
I/dalvikvm( 1298): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1298): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
D/dalvikvm( 1298): VFY: replacing opcode 0x6e at 0x002f
D/dalvikvm( 1910): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 1910): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 1910): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SystemUpdateService( 1298): Already downloaded, skipping offpeak checks.
I/AuthZen ( 1298): Fetching signing key...
I/SystemUpdateService( 1298): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
W/dalvikvm( 1298): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/dalvikvm( 1910): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
I/DownloadAttempt( 1298): current file is /cache/update.zip
I/DownloadAttempt( 1298): mSize 2571501 mDownloaded 2571501
I/SystemUpdateService( 1298): status is 0 (complete)
I/SystemUpdateService( 1298): now status is 0 (complete)
I/SystemUpdateService( 1298): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1298): file has been verified
I/SystemUpdateService( 1298): OTA package size = 2571501
I/AuthZen ( 1298): Signing key fetched successfully!
D/dalvikvm( 1298): GC_CONCURRENT freed 450K, 3% free 18505K/18988K, paused 4ms+2ms, total 50ms
D/dalvikvm( 1298): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/dalvikvm( 1298): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 1298): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 1298): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 1298): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 1298): WAIT_FOR_CONCURRENT_GC blocked 12ms
I/SystemUpdateService( 1298): showing system update notification
W/BaseAppContext( 1298): Using Auth Proxy for data requests.
D/SystemUpdateService( 1298): onDestroy
D/AuthZenTransactionCache( 1298): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1298): Clearing transaction cache
D/ActivityThread( 1931): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
D/AndroidRuntime( 1910): Calling main entry com.android.commands.am.Am
D/ActivityThread( 1931): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
I/ActivityManager(  773): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 1910
D/ActivityThread( 1931): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
D/dalvikvm( 1931): GC_CONCURRENT freed 191K, 2% free 16918K/17144K, paused 6ms+2ms, total 36ms
D/dalvikvm(  773): GC_EXPLICIT freed 1179K, 10% free 23977K/26520K, paused 4ms+6ms, total 121ms
D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (469 us)
D/dalvikvm(  773): GC_FOR_ALLOC freed 95K, 10% free 23891K/26520K, paused 55ms, total 55ms
I/dalvikvm-heap(  773): Grow heap (frag case) to 24.179MB for 856096-byte allocation
D/dalvikvm(  773): GC_FOR_ALLOC freed 3K, 10% free 24723K/27360K, paused 62ms, total 62ms
D/dalvikvm(  773): GC_FOR_ALLOC freed 2K, 10% free 24728K/27360K, paused 51ms, total 51ms
I/dalvikvm-heap(  773): Grow heap (frag case) to 24.998MB for 856096-byte allocation
D/dalvikvm(  773): GC_FOR_ALLOC freed <1K, 10% free 25564K/28200K, paused 55ms, total 55ms
D/AndroidRuntime( 1910): Shutting down VM
W/ActivityManager(  773): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
W/ActivityManager(  773): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
D/dalvikvm( 1910): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 1ms+1ms, total 7ms
I/ActivityManager(  773): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=1968 uid=10116 gids={50116, 3003, 3001, 3002}
W/ActivityManager(  773): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
I/ActivityManager(  773): Delay finish: com.google.android.email/com.android.email.service.EmailBroadcastReceiver
I/Email   ( 1931): Observing account changes for notifications
W/ActivityManager(  773): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
I/SearchController( 1191): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1191): mic_close
I/ActivityManager(  773): Delaying start of: ServiceRecord{42d84780 u0 com.google.android.exchange/com.android.exchange.service.EmailSyncAdapterService}
I/ActivityManager(  773): Start proc com.google.android.exchange for service com.google.android.exchange/com.android.exchange.service.EmailSyncAdapterService: pid=1989 uid=10037 gids={50037, 3003, 1028, 1015}
,I/MicroHotwordRecognitionRunner( 1191): Hotword detection finished
,I/ActivityManager(  773): Killing 1413:com.android.settings/1000 (adj 15): empty #17
I/MicroHotwordRecognitionRunner( 1191): Stopping hotword detection.
V/WebViewChromiumFactoryProvider( 1968): Binding Chromium to main looper Looper (main, tid 1) {42641898}
I/LibraryLoader( 1968): Expected native library version number "",actual native library version number ""
I/chromium( 1968): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 1968): Initializing chromium process, renderers=0
,D/BluetoothManagerService(  773): Message: 20
,D/BluetoothManagerService(  773): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c73df0:true
,D/BluetoothAdapter( 1968): 1113944416: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 1968): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,I/ActivityManager(  773): Killing 1359:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,W/chromium( 1968): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 1968): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 1968): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 1968): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 1968): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 1968): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 1968): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 1968): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 1968): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 1968): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 1968): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 1968): VFY: replacing opcode 0x6f at 0x001a
,D/dalvikvm(  981): GC_CONCURRENT freed 551K, 4% free 18576K/19224K, paused 5ms+15ms, total 118ms
,W/dalvikvm( 1968): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 1968): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 1968): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 1968): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 1968): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 1968): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 1968): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 1968): CordovaWebView is running on device made by: LGE
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=2021 uid=10051 gids={50051, 3003, 1028, 1015, 3002}
,I/ActivityManager(  773): Killing 1517:com.google.android.dialer/u0a8 (adj 15): empty #17
,D/OpenGLRenderer( 1968): Enabling debug mode 0
,W/AwContents( 1968): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  773): Displayed com.example.hello/.MainActivity: +650ms
,I/dalvikvm( 2021): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 2021): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 2021): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 2021): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 2021): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 2021): VFY: replacing opcode 0x22 at 0x0037
,W/dalvikvm( 2021): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 2021): Link of class 'Ldqp;' failed
W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 2021): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 2021): Link of class 'Ldqp;' failed
I/dalvikvm( 2021): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 2021): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 2021): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 2021): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 2021): Link of class 'Ldqp;' failed
,W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 2021): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 2021): Link of class 'Ldqp;' failed
I/dalvikvm( 2021): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 2021): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
,W/dalvikvm( 2021): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 2021): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 2021): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 2021): Link of class 'Ldqp;' failed
W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
,W/dalvikvm( 2021): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 2021): Link of class 'Ldqp;' failed
,D/dalvikvm( 2021): GC_CONCURRENT freed 254K, 2% free 16882K/17168K, paused 7ms+3ms, total 51ms
I/dalvikvm( 2021): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 2021): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 2021): Link of class 'Lax;' failed
E/dalvikvm( 2021): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 2021): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2021): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 2021): Link of class 'Laz;' failed
E/dalvikvm( 2021): Could not find class 'az', referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 2021): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 2021): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 2021): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2021): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 2021): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 2021): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 2021): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2021): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 2021): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 2021): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 2021): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 2021): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm( 2021): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 2021): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 2021): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 2021): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 2021): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 2021): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 2021): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 2021): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 2021): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 2021): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 2021): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 2021): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 2021): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 2021): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2021): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2021): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 2021): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 2021): Link of class 'Lax;' failed
,D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 2021): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 2021): Link of class 'Laz;' failed
,D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,I/chromium( 1968): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 1968): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/dalvikvm( 2021): GC_CONCURRENT freed 266K, 2% free 17022K/17328K, paused 4ms+2ms, total 19ms
,D/dalvikvm( 2021): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4264afd0
,D/dalvikvm( 2021): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4264afd0
,D/JsMessageQueue( 1968): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 1968): GC_CONCURRENT freed 264K, 2% free 16918K/17212K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 2021): GC_CONCURRENT freed 207K, 2% free 17288K/17512K, paused 4ms+4ms, total 31ms
,D/dalvikvm( 2021): GC_CONCURRENT freed 251K, 2% free 17548K/17828K, paused 4ms+3ms, total 44ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/dalvikvm( 2021): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 2021): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0076
,D/dalvikvm( 1968): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42646058
,I/Babel_SMS( 2021): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 2021): MmsConfig.loadMmsSettings
,I/Babel_SMS( 2021): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 2021): MmsConfig.loadFromDatabase
,D/dalvikvm( 1968): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42646058
D/jxcore_app_log( 1968): JniHelper::setJavaVM(0x4152df00), pthread_self() = 1979618264
,D/JX-Cordova( 1968): jxcore cordova android initializing
,I/GAV2    ( 1191): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 2021): GC_CONCURRENT freed 203K, 2% free 17844K/18088K, paused 14ms+7ms, total 114ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 65ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 66ms
I/GAv4-SVC( 1298): Google Analytics 8.4.89 is starting up.
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 67ms
,I/Babel_SMS( 2021): ApnsOta: OTA version -1
,D/dalvikvm( 1968): GC_CONCURRENT freed 258K, 2% free 17153K/17444K, paused 4ms+3ms, total 38ms
,D/dalvikvm( 1968): WAIT_FOR_CONCURRENT_GC blocked 9ms
,W/dalvikvm( 2021): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 2021): Link of class 'Lfzc;' failed
,E/dalvikvm( 2021): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 2021): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 2021): VFY: replacing opcode 0x22 at 0x0033
,D/dalvikvm( 1298): GC_CONCURRENT freed 599K, 4% free 18508K/19140K, paused 12ms+11ms, total 139ms
,D/dalvikvm( 1298): WAIT_FOR_CONCURRENT_GC blocked 56ms
,W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,D/dalvikvm( 2021): GC_CONCURRENT freed 252K, 2% free 18087K/18384K, paused 7ms+2ms, total 70ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 12ms
,W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 2021): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 2021): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 2021): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 2021): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 2021): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 2021): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 2021): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 2021): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 2021): Link of class 'Lfzc;' failed
D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,D/dalvikvm( 1968): GC_FOR_ALLOC freed 322K, 3% free 17207K/17608K, paused 25ms, total 25ms
,W/jxcore-log( 1968): Initializing JXcore engine
I/Babel   ( 2021): deleted: false for 0
,W/jxcore-log( 1968): JXcore engine is ready
E/Babel_SMS( 2021): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 2021): MmsConfig.loadFromResources
,E/Babel_SMS( 2021): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 2021): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,D/dalvikvm( 2021): GC_CONCURRENT freed 275K, 2% free 18304K/18628K, paused 4ms+2ms, total 35ms
D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 1968): GC_CONCURRENT freed 256K, 3% free 17341K/17740K, paused 3ms+4ms, total 28ms
,D/dalvikvm( 1968): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 1968): Starting JXcore engine
,W/Settings( 2021): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 2021): startup - clean
,I/dalvikvm( 2021): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,W/dalvikvm( 2021): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 2021): GC_CONCURRENT freed 162K, 2% free 18655K/18872K, paused 4ms+2ms, total 30ms
D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 2021): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 2021): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x004e
,W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 2021): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
,W/dalvikvm( 2021): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 2021): VFY: replacing opcode 0x22 at 0x0071
W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 2021): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 2021): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
D/dalvikvm( 2021): VFY: replacing opcode 0x1f at 0x0021
W/dalvikvm( 2021): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
D/dalvikvm( 2021): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,D/dalvikvm( 2021): GC_CONCURRENT freed 265K, 2% free 19013K/19340K, paused 4ms+4ms, total 47ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 25ms
,V/Babel   ( 2021): babel boot account: thalitester@gmail.com
I/dalvikvm( 2021): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 2021): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 2021): VFY: replacing opcode 0x6e at 0x0074
I/ActivityManager(  773): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
,I/vclib   ( 2021): onServiceConnected
,W/Babel   ( 2021): Attempted to change video mute state without an active call.
,W/jxcore-log( 1968): Platform android
W/jxcore-log( 1968): 
,W/jxcore-log( 1968): Process ARCH arm
W/jxcore-log( 1968): 
,D/dalvikvm( 2021): GC_CONCURRENT freed 532K, 3% free 19221K/19816K, paused 6ms+5ms, total 57ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 5ms
,I/jxcore-log( 1968): JXcore Cordova bridge is ready!
I/jxcore-log( 1968): 
,W/jxcore-log( 1968): JXcore engine is started
,I/Choreographer( 1968): Skipped 32 frames!  The application may be doing too much work on its main thread.
,D/dalvikvm( 2021): GC_FOR_ALLOC freed 131K, 4% free 19349K/20072K, paused 37ms, total 37ms
,I/dalvikvm-heap( 2021): Grow heap (frag case) to 19.419MB for 521860-byte allocation
,D/dalvikvm( 2021): GC_FOR_ALLOC freed 257K, 5% free 19602K/20584K, paused 31ms, total 31ms
,E/jxcore-log( 1968): >> LGE-Nexus 5
E/jxcore-log( 1968): 
I/jxcore-log( 1968): Total memory 1945137152
I/jxcore-log( 1968): 
,I/jxcore-log( 1968): Free memory 933761024
I/jxcore-log( 1968): 
I/jxcore-log( 1968): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1968): 
,I/jxcore-log( 1968): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1968): 
,I/jxcore-log( 1968): userPath [ 'www' ]
I/jxcore-log( 1968): 
,I/jxcore-log( 1968): Size 1080 1776
I/jxcore-log( 1968): 
,I/jxcore-log( 1968): Screen Brightness 1
I/jxcore-log( 1968): 
,E/jxcore-log( 1968): Dummy Error Log.
E/jxcore-log( 1968): 
,D/dalvikvm( 2021): GC_FOR_ALLOC freed 0K, 5% free 19602K/20584K, paused 48ms, total 48ms
,I/dalvikvm-heap( 2021): Grow heap (frag case) to 19.474MB for 319964-byte allocation
,D/dalvikvm( 2021): GC_FOR_ALLOC freed <1K, 5% free 19914K/20900K, paused 38ms, total 38ms
,D/dalvikvm( 2021): GC_FOR_ALLOC freed 765K, 6% free 19665K/20900K, paused 46ms, total 46ms
,D/dalvikvm( 2021): GC_FOR_ALLOC freed 271K, 5% free 19920K/20900K, paused 25ms, total 25ms
,I/dalvikvm-heap( 2021): Grow heap (frag case) to 19.785MB for 319911-byte allocation
,D/dalvikvm( 2021): GC_FOR_ALLOC freed <1K, 5% free 20232K/21216K, paused 29ms, total 29ms
,D/dalvikvm( 2021): GC_FOR_ALLOC freed 757K, 6% free 19982K/21216K, paused 24ms, total 24ms
,D/dalvikvm( 2021): GC_FOR_ALLOC freed 255K, 5% free 20236K/21216K, paused 17ms, total 17ms
,I/dalvikvm-heap( 2021): Grow heap (frag case) to 20.093MB for 319911-byte allocation
,D/dalvikvm( 2021): GC_FOR_ALLOC freed <1K, 5% free 20549K/21532K, paused 19ms, total 19ms
,E/dalvikvm( 2021): Could not find class 'android.content.pm.LauncherApps', referenced from method cbk.a
,W/dalvikvm( 2021): VFY: unable to resolve check-cast 469 (Landroid/content/pm/LauncherApps;) in Lcbk;
,D/dalvikvm( 2021): VFY: replacing opcode 0x1f at 0x0014
I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=2090 uid=10057 gids={50057, 3003, 1028, 1015}
,I/ActivityManager(  773): Killing 1543:com.android.providers.calendar/u0a1 (adj 15): empty #17
,D/dalvikvm( 2090): GC_CONCURRENT freed 317K, 3% free 16822K/17168K, paused 3ms+3ms, total 19ms
,D/dalvikvm( 2021): GC_CONCURRENT freed 920K, 5% free 20910K/21864K, paused 1ms+1ms, total 28ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2090): GC_CONCURRENT freed 304K, 2% free 17031K/17364K, paused 4ms+2ms, total 22ms
,D/dalvikvm( 2090): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2090): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2090): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 2090): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2090): WAIT_FOR_CONCURRENT_GC blocked 7ms
,I/ActivityManager(  773): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2115 uid=10071 gids={50071, 3003, 1028, 1015}
,I/ActivityManager(  773): Killing 1586:com.google.android.configupdater/u0a2 (adj 15): empty #17
,D/dalvikvm( 2090): Trying to load lib /data/app-lib/com.google.android.apps.maps-2/libcrashreporterer.so 0x426499a0
,D/dalvikvm( 2090): Added shared lib /data/app-lib/com.google.android.apps.maps-2/libcrashreporterer.so 0x426499a0
,D/dalvikvm( 2090): Trying to load lib /data/app-lib/com.google.android.apps.maps-2/libgmm-jni.so 0x426499a0
,I/jxcore-log( 1968): getBuffer is called!!!!
I/jxcore-log( 1968): 
,D/dalvikvm( 2090): GC_CONCURRENT freed 299K, 2% free 17243K/17572K, paused 18ms+13ms, total 78ms
,D/dalvikvm( 2090): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 2090): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/dalvikvm( 2090): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 2090): WAIT_FOR_CONCURRENT_GC blocked 46ms
,I/dalvikvm( 2090): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.d.a
D/dalvikvm( 2021): GC_CONCURRENT freed 453K, 3% free 21863K/22348K, paused 2ms+4ms, total 63ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/dalvikvm( 2090): VFY: unable to resolve virtual method 305: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2090): VFY: replacing opcode 0x6e at 0x0208
,I/dalvikvm( 2090): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.d.a
W/dalvikvm( 2090): VFY: unable to resolve virtual method 538: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2090): VFY: replacing opcode 0x6e at 0x000f
,D/dalvikvm( 2090): Added shared lib /data/app-lib/com.google.android.apps.maps-2/libgmm-jni.so 0x426499a0
,I/dalvikvm( 2090): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.d.c
W/dalvikvm( 2090): VFY: unable to resolve virtual method 305: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2090): VFY: replacing opcode 0x6e at 0x01c7
,I/dalvikvm( 2090): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method com.google.android.apps.gmm.iamhere.ble.o.b
W/dalvikvm( 2090): VFY: unable to resolve virtual method 1392: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 2090): VFY: replacing opcode 0x6e at 0x00a6
,D/dalvikvm( 1968): GC_FOR_ALLOC freed 646K, 5% free 16932K/17740K, paused 24ms, total 24ms
,D/dalvikvm( 2090): GC_CONCURRENT freed 275K, 2% free 17414K/17720K, paused 8ms+6ms, total 46ms
,D/dalvikvm( 1968): GC_CONCURRENT freed 304K, 4% free 17109K/17740K, paused 5ms+3ms, total 30ms
,D/dalvikvm( 1968): WAIT_FOR_CONCURRENT_GC blocked 8ms
,I/GAV2    ( 1774): Thread[GAThread,5,main]: No campaign data found.
,I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eoz.a
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2831: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 1774): GC_CONCURRENT freed 288K, 2% free 17269K/17588K, paused 12ms+4ms, total 87ms
,D/dalvikvm( 1968): GC_CONCURRENT freed 379K, 4% free 17147K/17740K, paused 3ms+3ms, total 48ms
D/dalvikvm( 1968): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/dalvikvm-heap( 1968): Grow heap (frag case) to 16.872MB for 104620-byte allocation
,D/dalvikvm( 1968): GC_FOR_ALLOC freed 68K, 4% free 17181K/17844K, paused 35ms, total 35ms
,W/com.google.a.a.b.d.a( 2090): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  773): Message: 20
,D/BluetoothManagerService(  773): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42be6b50:true
,D/dalvikvm( 2021): GC_CONCURRENT freed 1143K, 6% free 22434K/23616K, paused 6ms+3ms, total 180ms
,D/dalvikvm( 2021): WAIT_FOR_CONCURRENT_GC blocked 134ms
,D/dalvikvm( 2115): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2115): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2115): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 2115): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2115): VFY: unable to resolve instance field 36
,D/dalvikvm( 2115): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2115): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2115): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2115): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2115): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2115): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 2115): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4269af70
D/dalvikvm( 2115): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4269af70
,D/dalvikvm( 2115): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4269af70, skipping init
,D/dalvikvm( 2115): GC_CONCURRENT freed 324K, 3% free 16838K/17192K, paused 35ms+18ms, total 89ms
,D/dalvikvm( 2115): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4269af70
,D/dalvikvm( 1968): GC_CONCURRENT freed 313K, 3% free 17361K/17844K, paused 20ms+1ms, total 50ms
,D/dalvikvm( 1968): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/dalvikvm-heap( 1968): Grow heap (frag case) to 17.105MB for 130826-byte allocation
D/dalvikvm( 2115): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4269af70
,V/JNIHelp ( 2115): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 1968): GC_FOR_ALLOC freed 179K, 4% free 17309K/17972K, paused 30ms, total 30ms
,D/dalvikvm( 1968): GC_FOR_ALLOC freed <1K, 4% free 17309K/17972K, paused 23ms, total 24ms
,I/dalvikvm-heap( 1968): Grow heap (frag case) to 17.117MB for 196234-byte allocation
,D/dalvikvm( 2115): GC_CONCURRENT freed 300K, 2% free 17003K/17336K, paused 3ms+13ms, total 46ms
,D/dalvikvm( 2115): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4269af70
,D/dalvikvm( 2115): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4269af70
D/dalvikvm( 2115): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4269af70
,D/dalvikvm( 2115): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4269af70
,D/dalvikvm( 1968): GC_FOR_ALLOC freed 127K, 5% free 17373K/18164K, paused 37ms, total 37ms
,D/dalvikvm( 1968): GC_FOR_ALLOC freed 441K, 6% free 17078K/18164K, paused 13ms, total 14ms
,D/dalvikvm( 2115): GC_CONCURRENT freed 237K, 2% free 17250K/17520K, paused 7ms+3ms, total 34ms
,I/ProviderInstaller( 2115): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 2115): Could not find method android.app.Activity.finishAfterTransition, referenced from method cf.onBackPressed
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2360: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0012
,E/YouTube MDX( 2115): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 2115): GC_CONCURRENT freed 300K, 2% free 17414K/17744K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 2115): GC_CONCURRENT freed 256K, 2% free 17671K/17956K, paused 3ms+1ms, total 23ms
,I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 2115): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 2115): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 2115): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 2115): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 2115): GC_CONCURRENT freed 250K, 2% free 17933K/18212K, paused 4ms+2ms, total 22ms
,D/dalvikvm( 2115): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2115): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2115): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2115): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2115): DexOpt: --- BEGIN 'ads-1403496877.jar' (bootstrap=0) ---
,D/dalvikvm( 2169): DexOpt: load 2ms, verify+opt 10ms, 188892 bytes
,I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method asb.getActivityBanner
,W/dalvikvm( 2115): VFY: unable to resolve virtual method 2802: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method asb.getActivityBanner
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2803: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method asb.getApplicationBanner
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2810: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method asb.getApplicationBanner
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2811: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method asb.getLeanbackLaunchIntentForPackage
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2827: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method asb.getPackageInstaller
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2831: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method asb.getUserBadgedDrawableForDensity
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2847: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method asb.getUserBadgedIcon
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2848: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2115): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method asb.getUserBadgedLabel
W/dalvikvm( 2115): VFY: unable to resolve virtual method 2849: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 2115): VFY: replacing opcode 0x6e at 0x0002
,D/dalvikvm( 2115): DexOpt: --- END 'ads-1403496877.jar' (success) ---
,D/dalvikvm( 2115): DEX prep '/data/data/com.google.android.youtube/cache/ads-1403496877.jar': unzip in 0ms, rewrite 62ms
,W/InstanceID/Rpc( 2115): Found 10007
,D/dalvikvm( 2115): GC_CONCURRENT freed 381K, 3% free 18066K/18476K, paused 3ms+2ms, total 21ms
D/dalvikvm( 2115): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2115): WAIT_FOR_CONCURRENT_GC blocked 5ms
,I/ActivityManager(  773): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
,D/dalvikvm( 2115): GC_CONCURRENT freed 328K, 2% free 18208K/18556K, paused 2ms+3ms, total 22ms
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.ads.preload.PreloadVideosTransferService$DeviceStateReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Killing 1622:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
,I/ActivityManager(  773): Killing 1208:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,D/LocationInitializer( 1298): Restart initialization of location
D/WearableService(  981): callingUid 10007, callindPid: 981
I/ActivityManager(  773): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  773): Resuming delayed broadcast
D/AuthorizationBluetoothService( 1134): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1134): Proximity feature is not enabled.
E/MDM     (  981): [96] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  773): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
V/GLSActivity( 1134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  773): Resuming delayed broadcast
W/GCoreFlp(  981): No location to return for getLastLocation()
W/FusedLocationProvider(  981): location=null
E/MDM     (  981): [98] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 1298): Restart initialization of location
D/AuthorizationBluetoothService( 1134): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1134): Proximity feature is not enabled.
V/GLSActivity( 1134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  773): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2220 uid=10058 gids={50058, 3003, 1028, 1015}
W/GCoreFlp(  981): No location to return for getLastLocation()
W/FusedLocationProvider(  981): location=null
,I/MultiDex( 2220): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 2220): install
,I/MultiDex( 2220): MultiDexExtractor.load(/data/app/com.google.android.music-2.apk, false)
,I/MultiDex( 2220): loading existing secondary dex files
,I/MultiDex( 2220): load found 1 secondary dex files
,I/MultiDex( 2220): install done
,D/dalvikvm( 2220): GC_CONCURRENT freed 242K, 2% free 16908K/17180K, paused 1ms+2ms, total 14ms
,I/BaseStore( 2220): Store database version: 131
,I/dalvikvm( 2220): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zza
W/dalvikvm( 2220): VFY: unable to resolve virtual method 419: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2220): VFY: replacing opcode 0x6e at 0x00c8
I/dalvikvm( 2220): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 2220): VFY: unable to resolve virtual method 791: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2220): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm( 2220): GC_CONCURRENT freed 318K, 3% free 17024K/17372K, paused 2ms+1ms, total 12ms
,W/dalvikvm( 2220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2220): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.GoogleURLConnectionFactory.openConnection
,W/dalvikvm( 2220): VFY: unable to resolve virtual method 1596: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 2220): VFY: replacing opcode 0x6e at 0x00a0
,I/GoogleURLConnFactory( 2220): Using platform SSLCertificateSocketFactory
,I/GoogleHttpClient( 2220): Using GMS GoogleHttpClient
W/ActivityThread( 2220): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/dalvikvm(  773): GC_EXPLICIT freed 398K, 9% free 25646K/27992K, paused 2ms+3ms, total 50ms
,D/dalvikvm( 2220): GC_CONCURRENT freed 184K, 2% free 17226K/17452K, paused 3ms+1ms, total 12ms
,I/GHttpClientFactory( 2220): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2220): Using platform SSLCertificateSocketFactory
,D/MusicLifecycle( 2220): com.google.android.music.MusicApplication generated event: Application created
,D/dalvikvm( 2220): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2220): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2220): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2220): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2220): VFY: unable to resolve instance field 36
,D/dalvikvm( 2220): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2220): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2220): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2220): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2220): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2220): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 2220): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4270a428
D/dalvikvm( 2220): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4270a428
,D/dalvikvm( 2220): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4270a428, skipping init
,D/dalvikvm( 2220): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4270a428
D/dalvikvm( 2220): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4270a428
,V/JNIHelp ( 2220): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 2220): GC_CONCURRENT freed 324K, 2% free 17385K/17740K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2220): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4270a428
,D/dalvikvm( 2220): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4270a428
D/dalvikvm( 2220): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4270a428
,D/dalvikvm( 2220): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4270a428
,D/dalvikvm( 2220): GC_CONCURRENT freed 253K, 2% free 17534K/17860K, paused 2ms+2ms, total 14ms
,I/ProviderInstaller( 2220): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 2220): GMSCore installation verified
,I/BaseStore( 2220): ConfigStore database version: 1
,I/MediaRouter( 2220): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, deviceType=0, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/MusicLifecycle( 2220): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4272bd98 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/MusicLifecycle( 2220): com.google.android.music.net.NetworkMonitor generated event: Service created
I/ActivityManager(  773): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/MusicLifecycle( 2220): com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,D/MusicLifecycle( 2220): com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,D/MusicLifecycle( 2220): com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,I/ActivityManager(  773): Resuming delayed broadcast
D/MusicLifecycle( 2220): com.google.android.music.download.ArtDownloadQueueService generated event: Service created
,D/dalvikvm( 2220): GC_CONCURRENT freed 288K, 2% free 17680K/17992K, paused 1ms+3ms, total 19ms
,D/MusicLifecycle( 2220): com.google.android.music.download.cache.ArtCacheService generated event: Service created
,D/MusicLifecycle( 2220): com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,D/MusicLifecycle( 2220): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4272bd98 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/MusicLifecycle( 2220): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4272bd98 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/MusicLifecycle( 2220): com.google.android.music.store.MediaStoreImportService generated event: Service created
,D/MusicLifecycle( 2220): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
,D/AlertReceiver( 1685): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/AlertService( 1685): 0 Action = android.intent.action.PROVIDER_CHANGED
I/ActivityManager(  773): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/iu.UploadsManager( 1298): End new media; added: 0, uploading: 0, time: 58 ms
,D/BluetoothManagerService(  773): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  773): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  773): Message: 2
,I/jxcore-log( 1968): ****TEST TOOK:  5044  ms ****
I/jxcore-log( 1968): 
,I/jxcore-log( 1968): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1968): 
D/WifiService(  773): setWifiEnabled: false pid=1968, uid=10116
,D/AndroidRuntime( 2263): 
D/AndroidRuntime( 2263): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2263): CheckJNI is OFF
,D/dalvikvm( 2263): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 2263): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 2263): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2263): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 2263): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 2263): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/AndroidRuntime( 2263): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  773): Force stopping com.example.hello appid=10116 user=-1: uninstall pkg
,I/ActivityManager(  773): Killing 1968:com.example.hello/u0a116 (adj 0): stop com.example.hello
,W/ActivityManager(  773): Force removing ActivityRecord{42dbd840 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/InputDispatcher(  773): channel '42e06b30 com.example.hello/com.example.hello.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  773): channel '42e06b30 com.example.hello/com.example.hello.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  773): Attempted to unregister already unregistered input channel '42e06b30 com.example.hello/com.example.hello.MainActivity (server)'
I/WindowState(  773): WIN DEATH: Window{42e06b30 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  773): Skipping PackageSetting{427466e8 com.test.thalitest/10108} due to missing metadata
,W/Sidekick_LocationOracleImpl( 1191): Best location was null
,W/Binder  (  967): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  967): java.lang.NullPointerException
W/Binder  (  967): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  967): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  967): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  967): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  773): Got RemoteException sending setActive(false) notification to pid 1968 uid 10116
I/ActivityManager(  773): Force stopping com.example.hello appid=10116 user=0: pkg removed
,W/GeofencerStateMachine(  981): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  773): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "sms"
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/LatinIME:LogUtils(  967): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,D/dalvikvm( 1055): GC_EXPLICIT freed 1180K, 6% free 26209K/27844K, paused 4ms+37ms, total 66ms
,D/dalvikvm(  967): GC_CONCURRENT freed 301K, 2% free 17008K/17336K, paused 5ms+1ms, total 38ms
,D/Launcher.Workspace( 1055): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1055): 11683562 - stripEmptyScreens()
,I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  773):   Scheme: "smsto"
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "mms"
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  773): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  773): removePackageParticipantsLocked: uid=10116 #1
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "mmsto"
,I/Velvet.VelvetNetworkClient( 1191): Network connection not availble
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/GCoreFlp(  981): No location to return for getLastLocation()
,I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  773):   Scheme: "sms"
D/dalvikvm(  773): GC_EXPLICIT freed 1651K, 11% free 24924K/27992K, paused 3ms+5ms, total 84ms
D/dalvikvm( 1191): GC_FOR_ALLOC freed 925K, 6% free 17790K/18748K, paused 16ms, total 16ms
I/dalvikvm-heap( 1191): Grow heap (frag case) to 18.010MB for 640016-byte allocation
,D/AndroidRuntime( 2263): Shutting down VM
,D/dalvikvm( 2263): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 2ms
,D/dalvikvm( 1191): GC_FOR_ALLOC freed 0K, 2% free 18415K/18748K, paused 12ms, total 12ms
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  773):   Scheme: "smsto"
,I/MicroHotwordRecognitionRunner( 1191): Starting hotword detection.
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1191): GC_CONCURRENT freed 16K, 2% free 18407K/18748K, paused 3ms+1ms, total 15ms
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "mms"
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  773):   Action: "android.intent.action.SENDTO"
I/PackageManager(  773):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  773):   Scheme: "mmsto"
I/PackageManager(  773): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/audio_hw_primary(  184): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,I/SearchController( 1191): #onHotwordDetectorStarted

```
