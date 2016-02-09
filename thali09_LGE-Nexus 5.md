#### Test 583805004251330_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
,I/wpa_supplicant(  935): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/wpa_supplicant(  935): wlan0: Associated with c0:ff:d4:d3:aa:48
I/wpa_supplicant(  935): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  935): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
E/WifiStateMachine(  756): scanCount==0 - aborting
D/AndroidRuntime( 2369): 
D/AndroidRuntime( 2369): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2369): CheckJNI is OFF
D/dalvikvm( 2369): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2369): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2369): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2369): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2369): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2369): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2369): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 2369): Shutting down VM
D/dalvikvm( 2369): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 1ms+0ms, total 2ms
--------- beginning of /dev/log/system
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2369
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
,D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aef3a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  756): Waited long enough for: ServiceRecord{42e25220 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  756): Resuming delayed broadcast
,D/dalvikvm( 1736): GC_CONCURRENT freed 295K, 2% free 16798K/17124K, paused 1ms+1ms, total 13ms
,I/ActivityManager(  756): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2423 uid=10014 gids={50014, 3003, 1028, 1015}
,D/dalvikvm(  185): GC_EXPLICIT freed 43K, 1% free 16699K/16772K, paused 1ms+1ms, total 14ms
,D/dalvikvm(  185): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+2ms, total 11ms
,D/dalvikvm(  185): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+2ms, total 11ms
,D/dalvikvm(  952): GC_CONCURRENT freed 223K, 2% free 17111K/17360K, paused 1ms+1ms, total 11ms
,D/Finsky  ( 2423): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 2423): GC_CONCURRENT freed 247K, 2% free 16882K/17160K, paused 2ms+2ms, total 16ms
,D/Finsky  ( 2423): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2423): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2423): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 2423): GC_CONCURRENT freed 282K, 2% free 17066K/17376K, paused 1ms+2ms, total 14ms
,D/Finsky  ( 2423): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2423): [1] 2.run: Finished loading 1 libraries.
,I/Icing.InternalIcingCorporaProvider( 1219): Updating corpora: A: com.google.android.gms, C: MAYBE
,W/Launcher( 1033): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@425feae0 new=com.google.android.velvet.VelvetApplication@425feae0
,I/ActivityManager(  756): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2456 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
,D/Finsky  ( 2423): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2423): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1319): GC_CONCURRENT freed 504K, 4% free 18524K/19136K, paused 1ms+1ms, total 14ms
,I/ActivityManager(  756): Waited long enough for: ServiceRecord{42c8df48 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,E/dalvikvm( 2456): Could not find class 'android.app.Notification$Action$Builder', referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lorg/chromium/net/CronetEngine$Builder$Pkp;
,D/dalvikvm( 2456): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 2456): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
,W/dalvikvm( 2456): VFY: unable to resolve new-instance 578 (Landroid/graphics/drawable/RippleDrawable;) in Lorg/chromium/net/CronetEngine$Builder$Pkp;
,D/dalvikvm( 2456): VFY: replacing opcode 0x22 at 0x000b
,W/dalvikvm( 2456): VFY: unable to find class referenced in signature (Loze;)
,I/Icing.InternalIcingCorporaProvider( 1219): UpdateCorporaTask done [took 342 ms] updated apps [took 342 ms] 
,D/dalvikvm( 1219): GC_CONCURRENT freed 396K, 3% free 18226K/18652K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 2456): GC_CONCURRENT freed 171K, 2% free 16916K/17116K, paused 3ms+2ms, total 14ms
,E/dalvikvm( 2456): Could not find class 'android.app.Notification$Action$Builder', referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lorg/chromium/net/CronetEngine$Builder$Pkp;
,D/dalvikvm( 2456): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 2456): Unable to resolve superclass of Ldc; (806)
,W/dalvikvm( 2456): Link of class 'Ldc;' failed
E/dalvikvm( 2456): Could not find class 'dc', referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve new-instance 3384 (Ldc;) in Lorg/chromium/net/CronetEngine$Builder$Pkp;
D/dalvikvm( 2456): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2456): Unable to resolve superclass of Lde; (806)
W/dalvikvm( 2456): Link of class 'Lde;' failed
E/dalvikvm( 2456): Could not find class 'de', referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve new-instance 3438 (Lde;) in Lorg/chromium/net/CronetEngine$Builder$Pkp;
D/dalvikvm( 2456): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 2456): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve virtual method 5556: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2456): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 2456): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve virtual method 6095: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 2456): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2456): Could not find method android.view.View.getTransitionName, referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve virtual method 5899: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2456): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 2456): Could not find method android.transition.Transition.getTargetNames, referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve virtual method 5546: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 2456): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 2456): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve interface method 6143: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 2456): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2456): Could not find method android.view.ViewParent.onNestedFling, referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve interface method 6142: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 2456): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2456): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve interface method 6144: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
D/dalvikvm( 2456): VFY: replacing opcode 0x72 at 0x0000
W/dalvikvm( 2456): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 2456): Could not find class 'android.app.RemoteInput[]', referenced from method org.chromium.net.CronetEngine$Builder$Pkp.a
W/dalvikvm( 2456): VFY: unable to resolve new-array 13482 ([Landroid/app/RemoteInput;) in Lorg/chromium/net/CronetEngine$Builder$Pkp;
D/dalvikvm( 2456): VFY: replacing opcode 0x23 at 0x0005
W/dalvikvm( 2456): VFY: unable to find class referenced in signature (Loze;)
I/dalvikvm( 2456): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method org.chromium.net.CronetEngine$Builder$Pkp.b
W/dalvikvm( 2456): VFY: unable to resolve virtual method 5556: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2456): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 2456): VFY: unable to find class referenced in signature (Loze;)
,W/dalvikvm( 2456): VFY: unable to find class referenced in signature (Loze;)
,W/dalvikvm( 2456): VFY: unable to find class referenced in signature (Loze;)
,D/dalvikvm( 2456): DexOpt: unable to opt direct call 0x0a83 at 0x0e in Lorg/chromium/net/CronetEngine$Builder$Pkp;.a
,D/dalvikvm( 2456): DexOpt: unable to opt direct call 0x0e2a at 0x0e in Lorg/chromium/net/CronetEngine$Builder$Pkp;.a
D/dalvikvm( 2456): DexOpt: unable to opt direct call 0x0a83 at 0x0e in Lorg/chromium/net/CronetEngine$Builder$Pkp;.a
W/dalvikvm( 2456): Unable to resolve superclass of Ldc; (806)
W/dalvikvm( 2456): Link of class 'Ldc;' failed
D/dalvikvm( 2456): DexOpt: unable to opt direct call 0x5c72 at 0x08 in Lorg/chromium/net/CronetEngine$Builder$Pkp;.a
W/dalvikvm( 2456): Unable to resolve superclass of Lde; (806)
W/dalvikvm( 2456): Link of class 'Lde;' failed
D/dalvikvm( 2456): DexOpt: unable to opt direct call 0x5d48 at 0x30 in Lorg/chromium/net/CronetEngine$Builder$Pkp;.a
,D/dalvikvm( 2456): DexOpt: unable to opt direct call 0x0adb at 0x13 in Lorg/chromium/net/CronetEngine$Builder$Pkp;.a
,D/dalvikvm( 2456): GC_CONCURRENT freed 368K, 3% free 17051K/17448K, paused 1ms+3ms, total 17ms
,D/dalvikvm( 2456): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2456): GC_CONCURRENT freed 295K, 2% free 17230K/17556K, paused 1ms+2ms, total 11ms
,D/dalvikvm( 2456): GC_CONCURRENT freed 223K, 2% free 17393K/17648K, paused 2ms+1ms, total 11ms
,I/dalvikvm( 2456): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method efq.a
W/dalvikvm( 2456): VFY: unable to resolve virtual method 2727: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2456): VFY: replacing opcode 0x6e at 0x023c
I/dalvikvm( 2456): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method efq.a
W/dalvikvm( 2456): VFY: unable to resolve virtual method 3104: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2456): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 2456): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method efq.c
W/dalvikvm( 2456): VFY: unable to resolve virtual method 2727: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2456): VFY: replacing opcode 0x6e at 0x0207
,D/dalvikvm( 2456): Trying to load lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x425f8b68
,D/dalvikvm( 2456): Added shared lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x425f8b68
,D/dalvikvm( 2456): GC_CONCURRENT freed 269K, 2% free 17511K/17812K, paused 2ms+1ms, total 11ms
I/ActivityManager(  756): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  756): Resuming delayed broadcast
,D/PackageBroadcastService( 1319): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1319): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  756): Killing 1753:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/Icing   ( 1319): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1319): GC_CONCURRENT freed 472K, 4% free 18553K/19136K, paused 2ms+1ms, total 16ms
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,I/Icing   ( 1319): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/Icing   ( 1319): Loaded CLD2 Version V2.0 - 20141016
,D/AlertService( 1736): Beginning updateAlertNotification
D/AlertService( 1736): No fired or scheduled alerts
,D/AlertService( 1736): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1736): No events found starting within 1 week.
,I/Icing   ( 1319): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/Icing   ( 1319): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/dalvikvm( 1319): GC_CONCURRENT freed 516K, 3% free 18565K/19136K, paused 3ms+4ms, total 20ms
,I/Icing   ( 1319): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-10ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        (  756): Setting time of day to sec=1455033952
,W/        (  756): Unable to set rtc to 1455033952: Invalid argument
,D/MusicLifecycle( 2133): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@427136e0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) },
,I/NetworkMonitor( 2133): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1319): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,W/GCoreFlp(  978): No location to return for getLastLocation()
,D/SystemUpdateService( 1319): onCreate
,D/SystemUpdateService( 1319): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1319): active receiver: enabled
,I/SystemUpdateService( 1319): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1319): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1319): now status is 0 (complete)
I/SystemUpdateService( 1319): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1319): file has been verified
,I/SystemUpdateService( 1319): OTA package size = 2571501
,I/SystemUpdateService( 1319): showing system update notification
,I/iu.SyncManager( 1319): SYNC; picasa accounts
,D/NetworkLogImpl( 1319): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1319): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1319): onDestroy
,I/iu.UploadsManager( 1319): num queued entries: 0
,I/iu.UploadsManager( 1319): num updated entries: 0
,I/iu.SyncManager( 1319): NEXT; no task
,D/dalvikvm(  756): GC_CONCURRENT freed 1492K, 6% free 24079K/25608K, paused 3ms+4ms, total 48ms
,D/dalvikvm( 1319): GC_FOR_ALLOC freed 409K, 4% free 18582K/19216K, paused 17ms, total 17ms
,V/AlarmClock( 1769): AlarmInitReceiver android.intent.action.TIME_SET
,D/GpsLocationProvider(  756): NTP server returned: 1455033949936 (Tue Feb 09 17:05:49 CET 2016) reference: 37765 certainty: 9 system time offset: -3147
,I/AlarmClock( 1769): Displaying next alarm time: ''
,V/AlarmClock( 1769): AlarmInitReceiver finished
I/dalvikvm( 1319): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1319): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x003d
E/ActivityThread( 1319): Failed to find provider info for com.android.contacts.metadata
,I/ActivityManager(  756): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2536 uid=10068 gids={50068}
,D/SyncManager(  756): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 20895, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  756): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 40948, reason: UserStart
,D/dalvikvm( 2536): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x425f4780, skipping init
D/TimeService( 2536): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1455033953131
D/        ( 2536): TimeServiceNative: User Time to be set is 1455033953131
D/QC-time-services( 2536): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2536): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2536): Lib:time_genoff_operation: pargs->ts_val = 1455033953131
,D/QC-time-services(  202): Daemon: Connection accepted:time_genoff
D/QC-time-services( 2536): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  202): Daemon:Received base = 2, unit = 1, operation = 0,value = 1455033953131
D/QC-time-services(  202): Daemon:genoff_opr: Base = 2, val = 1455033953131, operation = 0
D/QC-time-services(  202): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/1/71 10:10:34
D/QC-time-services(  202): Daemon:Value read from RTC seconds = 39348634000
D/QC-time-services(  202): Daemon:new time 1455033953131 
,D/QC-time-services(  202): Daemon: delta 1415685319131 genoff 1415685319131 
D/QC-time-services(  202): Daemon:genoff_persistent_update: Writing genoff = 1415685319131 to memory
D/QC-time-services(  202): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  202): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  202): Updating the TOD offset
D/QC-time-services(  202): Daemon:genoff_persistent_update: Writing genoff = 1415685319131 to memory
D/QC-time-services(  202): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  202): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  202): Daemon:Update to modem bit set
D/QC-time-services(  202): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  202): Daemon: Base = 2, Value being sent to MODEM = 1139069153131
,E/QC-time-services( 2536): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  202): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  202): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  756): Killing 1784:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/GCM     ( 1122): GCM config loaded
,D/dalvikvm( 1122): GC_CONCURRENT freed 337K, 4% free 17917K/18552K, paused 2ms+3ms, total 27ms
,I/CheckinService( 1319): Checkin interval check for package: unspecified last checkin: 1455033605018 min interval config: 0 actual interval: 348198
,I/Babel   ( 2038): connection state changed from UNKNOWN to CONNECTED
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ActivityManager(  756): Killing 1838:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  756): Killing 1077:com.android.printspooler/u0a64 (adj 15): empty #17
,I/CheckinService( 1319): Done disabling old GoogleServicesFramework version
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.78/generate_204
W/ActivityThread(  756): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/GLSActivity( 1122): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1122): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1122): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 1122): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1122): VFY: replacing opcode 0x6e at 0x0046
,D/dalvikvm( 2423): GC_CONCURRENT freed 187K, 2% free 17275K/17496K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2423): GC_CONCURRENT freed 363K, 3% free 17301K/17696K, paused 2ms+2ms, total 14ms
,D/dalvikvm( 2423): GC_CONCURRENT freed 271K, 2% free 17417K/17720K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2423): GC_CONCURRENT freed 127K, 1% free 17704K/17876K, paused 2ms+2ms, total 14ms
,D/dalvikvm( 2423): GC_CONCURRENT freed 115K, 1% free 17973K/18136K, paused 2ms+1ms, total 12ms
,D/InitAlarmsService( 1736): Clearing and rescheduling alarms.
,D/dalvikvm( 2423): GC_CONCURRENT freed 269K, 2% free 18166K/18500K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 2423): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2423): GC_FOR_ALLOC freed 183K, 3% free 18229K/18628K, paused 12ms, total 12ms
,D/dalvikvm( 2423): GC_FOR_ALLOC freed 241K, 3% free 18354K/18756K, paused 12ms, total 12ms
,D/dalvikvm( 2423): GC_CONCURRENT freed 277K, 2% free 18621K/18936K, paused 1ms+2ms, total 15ms
,D/dalvikvm( 2423): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2423): GC_CONCURRENT freed 195K, 2% free 19072K/19296K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 2423): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2423): GC_CONCURRENT freed 502K, 3% free 19363K/19896K, paused 1ms+2ms, total 24ms
,D/dalvikvm( 2423): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Finsky  ( 2423): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/dalvikvm( 2423): GC_CONCURRENT freed 744K, 4% free 19505K/20284K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 2423): WAIT_FOR_CONCURRENT_GC blocked 14ms
,V/GLSActivity( 1122): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1122): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2423): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2423): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2423): untagSocket(52) failed with errno -22
,D/dalvikvm( 2423): GC_CONCURRENT freed 482K, 3% free 19842K/20400K, paused 2ms+1ms, total 20ms
,D/Finsky  ( 2423): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  756): Killing 1873:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  756): Service ServiceRecord{42c7a738 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{42d60bc8 1873:com.google.android.youtube/u0a71} not same as in map: null
,D/dalvikvm( 2133): GC_CONCURRENT freed 383K, 3% free 17897K/18312K, paused 3ms+2ms, total 50ms
,D/dalvikvm(  978): GC_CONCURRENT freed 460K, 3% free 18638K/19196K, paused 3ms+2ms, total 37ms
,D/dalvikvm( 2423): GC_CONCURRENT freed 1122K, 6% free 19686K/20848K, paused 4ms+11ms, total 40ms
,D/Finsky  ( 2423): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,D/dalvikvm( 1122): GC_CONCURRENT freed 452K, 4% free 17967K/18552K, paused 3ms+1ms, total 48ms
,I/VacuumService(  978): Vacuum at: now=1455034006619 tag=VacuumService
,D/dalvikvm( 1319): GC_CONCURRENT freed 473K, 3% free 18700K/19216K, paused 4ms+2ms, total 26ms
,W/SQLiteConnectionPool( 1319): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/dalvikvm( 1122): GC_CONCURRENT freed 484K, 4% free 17899K/18552K, paused 1ms+1ms, total 14ms
,I/PhenotypeConfigurator(  978): Scheduling Phenotype for one-off execution 1869 seconds from now (1455034006914)
,D/GetConfigurationSnapshotOperation(  978): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  978): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  978): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  978): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  978): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm(  978): GC_CONCURRENT freed 495K, 4% free 18712K/19304K, paused 5ms+3ms, total 33ms
I/dalvikvm(  978): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  978): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  978): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  978): Using platform SSLCertificateSocketFactory
,I/dalvikvm(  978): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  978): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  978): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1122): GC_CONCURRENT freed 371K, 4% free 17925K/18552K, paused 1ms+2ms, total 14ms
,D/dalvikvm(  978): GC_CONCURRENT freed 465K, 3% free 18876K/19436K, paused 3ms+4ms, total 34ms
,D/dalvikvm(  978): GC_CONCURRENT freed 547K, 4% free 18989K/19632K, paused 3ms+3ms, total 19ms
,D/dalvikvm(  978): GC_CONCURRENT freed 584K, 4% free 19115K/19792K, paused 3ms+3ms, total 20ms
,D/dalvikvm(  978): GC_CONCURRENT freed 723K, 5% free 19117K/19936K, paused 3ms+5ms, total 22ms
,D/dalvikvm(  978): GC_CONCURRENT freed 747K, 5% free 19078K/19964K, paused 3ms+3ms, total 21ms
,D/dalvikvm(  978): GC_CONCURRENT freed 703K, 5% free 19119K/19964K, paused 2ms+4ms, total 20ms
,V/GLSActivity( 1122): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1122): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1122): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1122): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1122): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1122): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1122): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1122): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1122): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1122): GC_CONCURRENT freed 435K, 4% free 17951K/18552K, paused 1ms+2ms, total 13ms
,D/dalvikvm(  756): GC_CONCURRENT freed 1566K, 7% free 24239K/25844K, paused 2ms+4ms, total 46ms
,D/dalvikvm(  978): GC_CONCURRENT freed 725K, 5% free 19106K/19964K, paused 2ms+5ms, total 23ms
,I/rmt_storage(  180): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb78f1160
I/rmt_storage(  180): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  180): wakelock acquired: 1, error no: 2
,I/rmt_storage(  180): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1215361328)
,I/rmt_storage(  180): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  180): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  180): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1215361328) wakelock released: 1, error no: 0
I/rmt_storage(  180): 
,I/rmt_storage(  180): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb78f1160
,I/PowerManagerService(  756): Going to sleep due to screen timeout...
,I/Adreno-EGL(  756): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  184): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (146 us)
,D/SurfaceFlinger(  184): Screen released, type=0 flinger=0xb84ed450
,D/qdhwcomposer(  184): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  184): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  756): Excessive delay in blankDisplay() while turning screen off: 289ms
,V/KeyguardServiceDelegate(  756): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42b2fe90)
,V/KeyguardServiceDelegate(  756): **** SHOWN CALLED ****
I/WindowManager(  756): No lock screen! windowToken=null
,I/SearchController( 1219): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1219): mic_close
,I/ActivityManager(  756): Killing 2083:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,I/ActivityManager(  756): Killing 2025:com.google.android.exchange/u0a37 (adj 15): empty #18
,D/NfcService( 1018): NFC-C OFF
,I/MicroHotwordRecognitionRunner( 1219): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1219): Stopping hotword detection.
,D/dalvikvm( 1219): GC_CONCURRENT freed 924K, 6% free 17725K/18692K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 1219): GC_CONCURRENT freed 266K, 5% free 17842K/18692K, paused 2ms+2ms, total 14ms
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,TIME-OUT KILL (timeout was 1200000ms)
```
