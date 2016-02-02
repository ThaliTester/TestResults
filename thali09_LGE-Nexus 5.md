#### Test 575312431be71d2_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/Icing   ( 1334): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
D/Icing   ( 1334): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1334): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
I/Icing   ( 1334): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/Icing   ( 1334): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,D/AndroidRuntime( 2587): 
D/AndroidRuntime( 2587): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2587): CheckJNI is OFF
D/dalvikvm( 2587): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2587): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2587): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2587): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2587): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2587): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2587): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 2587): Shutting down VM
D/dalvikvm( 2587): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
--------- beginning of /dev/log/system
I/ActivityManager(  772): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2587
,D/AlertService( 1731): Beginning updateAlertNotification
,D/AlertService( 1731): No fired or scheduled alerts
,D/AlertService( 1731): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1731): No events found starting within 1 week.
,I/ActivityManager(  772): Killing 1088:com.android.printspooler/u0a64 (adj 15): empty #17
,I/CheckinService( 1334): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  772): Killing 1881:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  772): Service ServiceRecord{42c37840 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{42b7a8d8 1881:com.google.android.youtube/u0a71} not same as in map: null
,V/GLSActivity( 1133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1133): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 1133): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1133): VFY: replacing opcode 0x6e at 0x0046
,D/dalvikvm( 2516): GC_CONCURRENT freed 187K, 2% free 17275K/17496K, paused 2ms+2ms, total 13ms
,D/InitAlarmsService( 1731): Clearing and rescheduling alarms.
,D/dalvikvm( 2516): GC_CONCURRENT freed 281K, 2% free 17382K/17692K, paused 2ms+2ms, total 14ms
,D/dalvikvm( 2516): GC_CONCURRENT freed 187K, 2% free 17665K/17888K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 2516): GC_CONCURRENT freed 154K, 2% free 18009K/18208K, paused 2ms+4ms, total 29ms
,D/dalvikvm( 2516): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 2516): GC_CONCURRENT freed 254K, 2% free 18159K/18492K, paused 2ms+1ms, total 14ms
,D/dalvikvm( 2516): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2516): GC_FOR_ALLOC freed 183K, 3% free 18221K/18620K, paused 10ms, total 10ms
,D/dalvikvm( 2516): GC_FOR_ALLOC freed 211K, 3% free 18314K/18748K, paused 10ms, total 10ms
,D/dalvikvm( 2516): GC_CONCURRENT freed 253K, 3% free 18490K/18876K, paused 2ms+3ms, total 15ms
,D/dalvikvm( 2516): GC_CONCURRENT freed 177K, 2% free 18893K/19100K, paused 2ms+1ms, total 14ms
,D/dalvikvm( 2516): GC_CONCURRENT freed 444K, 3% free 19088K/19568K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 2516): GC_CONCURRENT freed 253K, 2% free 19622K/19904K, paused 3ms+1ms, total 18ms
,D/Finsky  ( 2516): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,V/GLSActivity( 1133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2516): GC_CONCURRENT freed 1066K, 6% free 19464K/20584K, paused 3ms+1ms, total 41ms
,D/dalvikvm( 2516): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/qtaguid ( 2516): Failed write_ctrl(u 52) res=-1 errno=22
I/qtaguid ( 2516): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2516): untagSocket(52) failed with errno -22
,D/dalvikvm( 2516): GC_CONCURRENT freed 433K, 4% free 19862K/20584K, paused 1ms+1ms, total 24ms
,D/Finsky  ( 2516): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  772): Killing 2054:com.google.android.exchange/u0a37 (adj 15): empty #17
,D/dalvikvm( 2152): GC_CONCURRENT freed 366K, 3% free 17890K/18288K, paused 3ms+4ms, total 39ms
,D/dalvikvm( 1334): GC_CONCURRENT freed 527K, 4% free 18638K/19284K, paused 2ms+2ms, total 21ms
,D/Finsky  ( 2516): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  772): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  772): Done.
,D/ConnectivityService(  772): Setting timer for 720seconds
,D/dalvikvm( 1133): GC_CONCURRENT freed 307K, 3% free 18051K/18568K, paused 3ms+11ms, total 31ms
,I/VacuumService(  995): Vacuum at: now=1454419084143 tag=VacuumService
,D/dalvikvm( 1133): GC_CONCURRENT freed 561K, 4% free 17890K/18568K, paused 2ms+1ms, total 22ms
,I/rmt_storage(  177): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb7d3c160
I/rmt_storage(  177): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  177): wakelock acquired: 1, error no: 2
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1210858976)
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1210858976) wakelock released: 1, error no: 0
I/rmt_storage(  177): 
,I/rmt_storage(  177): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb7d3c160
,I/PowerManagerService(  772): Going to sleep due to screen timeout...
,I/Adreno-EGL(  772): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (144 us)
,D/SurfaceFlinger(  181): Screen released, type=0 flinger=0xb8dd3450
,D/qdhwcomposer(  181): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  181): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  772): Excessive delay in blankDisplay() while turning screen off: 289ms
,V/KeyguardServiceDelegate(  772): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42d13148)
,V/KeyguardServiceDelegate(  772): **** SHOWN CALLED ****
I/WindowManager(  772): No lock screen! windowToken=null
,I/SearchController( 1221): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1221): mic_close
,I/ActivityManager(  772): Killing 2137:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  772): Killing 2098:com.google.android.apps.maps/u0a57 (adj 15): empty #18
,D/NfcService( 1046): NFC-C OFF
,I/MicroHotwordRecognitionRunner( 1221): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1221): Stopping hotword detection.
,D/dalvikvm( 1221): GC_CONCURRENT freed 1099K, 6% free 17855K/18984K, paused 2ms+5ms, total 20ms
,D/dalvikvm( 1133): GC_CONCURRENT freed 312K, 4% free 17967K/18568K, paused 2ms+1ms, total 18ms
,I/PhenotypeConfigurator(  995): Scheduling Phenotype for one-off execution 4621 seconds from now (1454419164038)
,D/GetConfigurationSnapshotOperation(  995): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm(  995): GC_CONCURRENT freed 438K, 3% free 18720K/19252K, paused 2ms+2ms, total 17ms
,I/PhenotypeFlagCommitter(  995): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  995): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  995): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  995): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm(  995): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  995): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  995): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  995): Using platform SSLCertificateSocketFactory
,I/dalvikvm(  995): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm(  995): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  995): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  995): GC_CONCURRENT freed 528K, 4% free 18890K/19512K, paused 3ms+5ms, total 31ms
,D/dalvikvm(  995): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm(  995): GC_CONCURRENT freed 574K, 4% free 18969K/19636K, paused 2ms+3ms, total 19ms
,D/dalvikvm(  995): GC_CONCURRENT freed 530K, 4% free 19110K/19736K, paused 2ms+4ms, total 20ms
,D/dalvikvm(  995): GC_CONCURRENT freed 704K, 5% free 19125K/19924K, paused 2ms+7ms, total 29ms
,D/dalvikvm(  995): GC_CONCURRENT freed 756K, 5% free 19101K/19952K, paused 2ms+2ms, total 21ms
,D/dalvikvm(  995): GC_CONCURRENT freed 693K, 5% free 19116K/19952K, paused 2ms+4ms, total 22ms
,D/dalvikvm(  772): GC_EXPLICIT freed 1028K, 6% free 24140K/25600K, paused 1ms+4ms, total 46ms
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x753c10f0 clazz=0x5f400001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,V/NativeCrypto( 1133): Read error: ssl=0x79022bf0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1133): SSL shutdown failed: ssl=0x79022bf0: I/O error during system call, Broken pipe
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  951): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  951): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,D/dalvikvm( 1263): GC_CONCURRENT freed 329K, 3% free 16765K/17132K, paused 17ms+0ms, total 29ms
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/SystemUpdateService( 1334): active receiver: enabled
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1334): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
,I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/iu.UploadsManager( 1334): num updated entries: 0
I/SystemUpdateService( 1334): showing system update notification
,I/Babel   ( 2067): connection state changed from CONNECTED to DISCONNECTED
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
I/iu.SyncManager( 1334): NEXT; no task
D/SystemUpdateService( 1334): onDestroy
,I/wpa_supplicant(  951): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a998c0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2152): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1334): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1334): file has been verified
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/SystemUpdateService( 1334): OTA package size = 2571501
I/ActivityManager(  772): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/iu.SyncManager( 1334): NEXT; no task
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,I/Babel   ( 2067): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
,D/dalvikvm( 1133): GC_CONCURRENT freed 466K, 4% free 17941K/18568K, paused 8ms+1ms, total 96ms
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://173.194.112.142/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x753c10f0 clazz=0x80400001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,V/NativeCrypto( 1133): Read error: ssl=0x79022bf0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1133): SSL shutdown failed: ssl=0x79022bf0: I/O error during system call, Broken pipe
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  951): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  951): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  951): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/iu.SyncManager( 1334): NEXT; no task
,D/dalvikvm( 2346): GC_CONCURRENT freed 268K, 2% free 17592K/17892K, paused 7ms+42ms, total 63ms
,I/Babel   ( 2067): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1334): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1334): now status is 0 (complete)
,I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a998c0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2152): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1334): NEXT; no task
I/SystemUpdateService( 1334): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,D/dalvikvm( 1334): GC_CONCURRENT freed 501K, 4% free 18661K/19316K, paused 2ms+2ms, total 18ms
,I/Babel   ( 2067): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/dalvikvm(  772): GC_CONCURRENT freed 1788K, 8% free 24185K/26012K, paused 26ms+3ms, total 98ms
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  772): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  772): Done.
,D/ConnectivityService(  772): Setting timer for 720seconds
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x753c10f0 clazz=0xc2d00001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,V/NativeCrypto( 1133): Read error: ssl=0x7905d0d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1133): SSL shutdown failed: ssl=0x7905d0d8: I/O error during system call, Broken pipe
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  951): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/dalvikvm(  995): GC_CONCURRENT freed 743K, 5% free 19076K/19972K, paused 11ms+3ms, total 36ms
,I/wpa_supplicant(  951): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  951): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/SystemUpdateService( 1334): active receiver: enabled
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2067): connection state changed from CONNECTED to DISCONNECTED
I/SystemUpdateService( 1334): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/iu.SyncManager( 1334): NEXT; no task
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a998c0
,D/dalvikvm( 1019): GC_CONCURRENT freed 337K, 3% free 17072K/17436K, paused 4ms+2ms, total 29ms
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2152): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/iu.SyncManager( 1334): NEXT; no task
,I/SystemUpdateService( 1334): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,I/Babel   ( 2067): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1133): GC_CONCURRENT freed 449K, 4% free 17912K/18568K, paused 1ms+1ms, total 12ms
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x753c10f0 clazz=0xe0a00001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1133): Read error: ssl=0x7905ec40: I/O error during system call, Connection timed out
,V/NativeCrypto( 1133): SSL shutdown failed: ssl=0x7905ec40: I/O error during system call, Broken pipe
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  178): write error (Broken pipe)
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  951): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  951): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  951): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/Babel   ( 2067): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
I/iu.UploadsManager( 1334): num queued entries: 0
,I/iu.UploadsManager( 1334): num updated entries: 0
I/iu.SyncManager( 1334): NEXT; no task
I/SystemUpdateService( 1334): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a998c0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,W/ProcessCpuTracker(  772): Skipping unknown process pid 3130
,W/ProcessCpuTracker(  772): Skipping unknown process pid 3133
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2152): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/iu.SyncManager( 1334): NEXT; no task
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1334): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,D/dalvikvm( 2067): GC_CONCURRENT freed 1624K, 7% free 22794K/24460K, paused 2ms+2ms, total 50ms
,D/dalvikvm( 2067): WAIT_FOR_CONCURRENT_GC blocked 44ms
,I/Babel   ( 2067): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm(  772): GC_CONCURRENT freed 1763K, 7% free 24205K/26012K, paused 16ms+3ms, total 71ms
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x753c10f0 clazz=0x200001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,V/NativeCrypto( 1133): Read error: ssl=0x79022bf0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1133): SSL shutdown failed: ssl=0x79022bf0: I/O error during system call, Broken pipe
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  951): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  951): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  951): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2067): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1334): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/SystemUpdateService( 1334): showing system update notification
,I/iu.SyncManager( 1334): NEXT; no task
,D/SystemUpdateService( 1334): onDestroy
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a998c0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2152): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/iu.SyncManager( 1334): NEXT; no task
,I/SystemUpdateService( 1334): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/SystemUpdateService( 1334): showing system update notification
I/ActivityManager(  772): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
I/ActivityManager(  772): Resuming delayed broadcast
,D/SystemUpdateService( 1334): onDestroy
,I/Babel   ( 2067): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
,D/dalvikvm( 1133): GC_CONCURRENT freed 455K, 4% free 17914K/18568K, paused 8ms+1ms, total 57ms
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=6 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x753c10f0 clazz=0x20500001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1133): Read error: ssl=0x7905d0d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1133): SSL shutdown failed: ssl=0x7905d0d8: I/O error during system call, Broken pipe
D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  951): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  951): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  951): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/Babel   ( 2067): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1334): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/iu.SyncManager( 1334): NEXT; no task
,D/dalvikvm( 1334): GC_CONCURRENT freed 541K, 4% free 18671K/19348K, paused 3ms+1ms, total 18ms
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a998c0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-8ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2152): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/iu.SyncManager( 1334): NEXT; no task
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1334): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,I/Babel   ( 2067): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=7 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm(  772): GC_CONCURRENT freed 1770K, 7% free 24206K/26012K, paused 3ms+3ms, total 47ms
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x753c10f0 clazz=0x43300001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1133): Read error: ssl=0x79022bf0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1133): SSL shutdown failed: ssl=0x79022bf0: I/O error during system call, Broken pipe
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  951): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  951): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  951): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  951): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1334): num queued entries: 0
I/Babel   ( 2067): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1334): num updated entries: 0
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1334): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
I/SystemUpdateService( 1334): showing system update notification
,I/iu.SyncManager( 1334): NEXT; no task
,D/SystemUpdateService( 1334): onDestroy
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a998c0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MusicLifecycle( 2152): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c2740 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2152): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1334): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1334): onCreate
,D/SystemUpdateService( 1334): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1334): active receiver: enabled
,I/iu.Environment( 1334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1334): num queued entries: 0
,I/SystemUpdateService( 1334): Already downloaded, skipping offpeak checks.
I/iu.UploadsManager( 1334): num updated entries: 0
,I/iu.SyncManager( 1334): NEXT; no task
I/SystemUpdateService( 1334): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1334): now status is 0 (complete)
I/SystemUpdateService( 1334): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1334): file has been verified
,I/SystemUpdateService( 1334): OTA package size = 2571501
,I/SystemUpdateService( 1334): showing system update notification
,D/SystemUpdateService( 1334): onDestroy
,I/Babel   ( 2067): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1133): GC_CONCURRENT freed 395K, 4% free 17912K/18568K, paused 1ms+1ms, total 13ms
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=8 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,TIME-OUT KILL (timeout was 1200000ms)
```
