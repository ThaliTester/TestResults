#### Test 503880196b4ec73_thali05_HTC-HTC One_M8 Logs


```
--------- beginning of system
W/ResourcesManager( 4137): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
--------- beginning of main
I/DeviceManagement( 4137): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001186, versionName=2.2.821083
I/DeviceManagement( 4137): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 4137): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 4137): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 4137): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 4137): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 4137): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
I/DeviceManagement( 4137): EnabledAppController: Nothing appears to have changed for appID=com.htc.videohub.ui
I/DeviceManagement( 4137): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
I/DeviceManagement( 4137): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 4137): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 4137): Perf: Scan enabled apps - complete: 580 ms
I/DeviceManagement( 4137): Perf: *** Enabled app cache update - complete: 582 ms
I/DeviceManagement( 4137): Perf: *** Config cache update - start...
I/DeviceManagement( 4137): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4137): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 4137): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 4137): ConfigCacheController: No changes need to be broadcasted.
E/WifiStateMachine(  892): handleMessage: E msg.what=131155
E/WifiStateMachine(  892): processMsg: ConnectedState
E/WifiStateMachine(  892):  ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-53 f=5220 sc=60 link=150 tx=4.8, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:902490533] gl hn rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  892): processMsg: L2ConnectedState
E/WifiStateMachine(  892):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-53 f=5220 sc=60 link=150 tx=4.8, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:902490534] gl hn rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  892):  get link layer stats 0
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1374): wlan0: Control interface command 'SIGNAL_POLL'
I/DeviceManagement( 4137): AlarmController: Scheduling TTL alarm for: 2015.11.24 at 20:20:59.576 CET (due to: com.htc.launcher)
I/DeviceManagement( 4137): Perf: *** Config cache update - complete: 14 ms
I/DeviceManagement( 4137): Perf: *** Cache update - complete: 597 ms
I/DeviceManagement( 4137): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@33cfd34e]
I/DeviceManagement( 4137): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@263bb194] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 4137): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 4137): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/wpa_supplicant( 1374): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  892): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  892): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  892): updateConfiguration freq=5220 BSSID=c0:ff:d4:d3:aa:4a RSSI=-53 "NG7005g"WPA_PSK
I/DeviceManagement( 4137): SessionStateController: Checking invariants...
E/WifiStateMachine(  892): calculateWifiScore freq=5220 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.40 txretriesrate=0.00 rxrate=3.11 userTriggerdPenalty0
E/WifiStateMachine(  892):  good link -> stuck count =0
E/WifiStateMachine(  892):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  892):  isHighRSSI       ---> score=61
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4137, uid=10105, userID:0
D/WifiWatchdogStateMachine(  892): RSSI current: 3 new: -53, 3
E/WifiStateMachine(  892): handleMessage: X
D/WIFI_ICON( 1121): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/DeviceManagement( 4137): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 4137): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@263bb194]
I/DeviceManagement( 4137): WorkflowService: Stopping workflow service
D/Process (  892): killProcessQuiet, pid=3652
I/ActivityManager(  892): Killing 3652:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  892): Recipient 3652
D/Process (  892): killProcessQuiet, pid=3652
W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_3652/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/Atfwd_Sendcmd(  480): AtCmdFwd service not published, waiting... retryCnt : 3
I/ActivityManager(  892): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4192 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  892): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4210 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
D/Process (  892): killProcessQuiet, pid=3679
I/ActivityManager(  892): Killing 3679:com.htc.HTCSpeaker/u0a57 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  892): Recipient 3679
E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  892):  packet count Tx=56 Rx=57
I/Prism.ItemManager( 1459): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1459): loadItems() com.htc.launcher.pageview.WidgetManager@2a278d97 +
I/Prism.WidgetManager( 1459): onLoadItems() +
D/Process (  892): killProcessQuiet, pid=3679
W/libprocessgroup(  892): failed to open /acct/uid_10057/pid_3679/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/ResetNotifyBootCompleteReceiver( 1400): Receive bootcomplete intent
I/HtcCupdXmlParser( 4210): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  892): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4230 uid=10163 gids={50163, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AutoSetting( 1528): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1528): Util - check NLP state, Allowned:true, Enabled:true
D/AutoSetting( 1528): service - mHandler: request location update
D/ActivityThread( 4210): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
D/LocationManagerService(  892): request 92ead65 network Request[POWER_LOW network requested=+1s0ms fastest=+1s0ms] from com.htc.sense.hsp(10054)
D/LocationManagerService(  892): provider request: network ProviderRequest[ON interval=+1s0ms]
V/GmsNetworkLocationProvi( 1727): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 1000
V/GmsNetworkLocationProvi( 1727): SET-REQUEST
V/GmsNetworkLocationProvi( 1727): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 20000
D/PMS     (  892): acquireWL(22d2ca3a): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 WorkSource{10054 com.htc.sense.hsp}
D/PMS     (  892): releaseWL(22d2ca3a): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{10054 com.htc.sense.hsp}
D/PMS     (  892): acquireWL(3039f6eb): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 WorkSource{10054 com.htc.sense.hsp}
D/WifiService(  892): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@16abec48}
E/WifiStateMachine(  892): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  892):     Client/Owner: Client
D/WifiDisplayAdapter(  892):     GroupId: 
D/WifiDisplayAdapter(  892):     Passphrase: 
D/WifiDisplayAdapter(  892):     SessionId: 0
D/WifiDisplayAdapter(  892):     IP Address: }
E/WifiStateMachine(  892): processMsg: ConnectedState
E/WifiStateMachine(  892):  ConnectedState !CMD_START_SCAN 10025 1 ic=1 proc(ms):0 dur:4675 rssi=-53 f=5220 sc=60 link=150 tx=2.4, 0.0, 0.0  rx=3.1 fiv=40000 [on:0 tx:0 rx:0 period:598] from screen [on:0 period:902491145]
E/WifiStateMachine(  892): processMsg: L2ConnectedState
E/WifiStateMachine(  892):  L2ConnectedState !CMD_START_SCAN 10025 1 ic=1 proc(ms):1 dur:4675 rssi=-53 f=5220 sc=60 link=150 tx=2.4, 0.0, 0.0  rx=3.1 fiv=40000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:902491145]
E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN source 10025 txSuccessRate=2.40 rxSuccessRate=3.11 targetRoamBSSID=c0:ff:d4:d3:aa:4a RSSI=-53
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1374): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1374): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1374): wpa_supplicant_scan enter
D/wpa_supplicant( 1374): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1374): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1374): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1374): WPS:  * Request Type
D/wpa_supplicant( 1374): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1374): WPS:  * UUID-E
D/wpa_supplicant( 1374): WPS:  * Primary Device Type
D/wpa_supplicant( 1374): WPS:  * RF Bands (3)
D/wpa_supplicant( 1374): WPS:  * Association State
D/wpa_supplicant( 1374): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1374): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1374): WPS:  * Manufacturer
D/wpa_supplicant( 1374): WPS:  * Model Name
D/wpa_supplicant( 1374): WPS:  * Model Number
D/wpa_supplicant( 1374): WPS:  * Device Name
D/wpa_supplicant( 1374): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1374): P2P: * P2P IE header
E/WifiStateMachine(  892): [1,448,306,469,898 ms] noteScanStartWorkSource{10054} uid 10025
D/wpa_supplicant( 1374): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1374): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1374): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1374): wlan0: Add radio work 'scan'@0xb8ea8410
D/wpa_supplicant( 1374): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1374): wlan0: Starting radio work 'scan'@0xb8ea8410 after 0.000037 second wait
D/wpa_supplicant( 1374): wlan0: nl80211: scan request
D/wpa_supplicant( 1374): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1374): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
E/WifiStateMachine(  892): handleMessage: X
D/wpa_supplicant( 1374): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1374): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1374): wlan0: Own scan request started a scan in 0.000079 seconds
I/wpa_supplicant( 1374): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  892): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  892): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  892): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/Prism.WidgetManager( 1459): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1459): onLoadItems() -
I/Prism.ItemManager( 1459): loadItems() com.htc.launcher.pageview.WidgetManager@2a278d97 -
D/QXDM2SD:HtcNative( 1400): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
I/HtcCupdXmlParser( 4210): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  892): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4251 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/AlarmManager(  892): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  892): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  892): [AlarmQueuing] init alarm queuing list
V/Settings:HtcSettingsApplication( 4251): [4251/4251] onCreate()
W/ContextImpl( 4251): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2712 
I/ActivityManager(  892): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4269 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
I/ActivityManager(  892): Killing 3714:com.htc.lmw/u0a61 (adj 15): empty #17
D/Process (  892): killProcessQuiet, pid=3714
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/wpa_supplicant( 1374): Wireless event: cmd=0x8b19 len=8
I/ActivityManager(  892): Recipient 3714
D/wpa_supplicant( 1374): RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1374): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1374): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1374): nl80211: Scan included frequencies: 2462 5220
W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:13935 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14100 com.android.server.wifi.WifiStateMachine.access$5400:265 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7908 
D/wpa_supplicant( 1374): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1374): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1374): wlan0: Scan completed in 0.241444 seconds
D/wpa_supplicant( 1374): nl80211: Associated on 5220 MHz
D/wpa_supplicant( 1374): nl80211: Associated with c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1374): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1374): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:4a as associated
I/wpa_supplicant( 1374): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-53
I/wpa_supplicant( 1374): [NULL] c2:ff:d4:d3:aa:48 freq=2462 level=-59
I/wpa_supplicant( 1374): [NULL] c0:ff:d4:d3:aa:48 freq=2462 level=-59
I/wpa_supplicant( 1374): [NULL] 38:f8:89:11:e9:11 freq=2447 level=-85
D/wpa_supplicant( 1374): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 1374): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1374): wlan0: Scan-only results received
D/wpa_supplicant( 1374): wlan0: Radio work 'scan'@0xb8ea8410 done in 0.242110 seconds
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  892): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  892): handleMessage: E msg.what=147461
E/WifiStateMachine(  892): processMsg: ConnectedState
E/WifiStateMachine(  892):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
E/WifiStateMachine(  892): processMsg: L2ConnectedState
E/WifiStateMachine(  892):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
E/WifiStateMachine(  892): processMsg: ConnectModeState
E/WifiStateMachine(  892):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
E/WifiStateMachine(  892): processMsg: DriverStartedState
D/Tethering(  892): interfaceLinkStateChanged wlan0, true
D/Tethering(  892): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  892):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
E/WifiStateMachine(  892): processMsg: SupplicantStartedState
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  892):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=2 got=4 bcn=0
D/WifiStateMachine(  892): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1374): wlan0: Control interface command 'LIST_DONGLES'
I/ActivityManager(  892): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4287 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
E/WifiStateMachine(  892): [1,448,306,470,192 ms] noteScanEnd WorkSource{10054}
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1374): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/Process (  892): killProcessQuiet, pid=3714
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10061/pid_3714/cgroup.procs: No such file or directory
E/WifiStateMachine(  892): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@27056670 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  892): NG7005g c0:ff:d4:d3:aa:4a rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  892): updateSavedNetworkHistory(): try "NG7005g"WPA_PSK SSID="NG7005g" NG7005g [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  892): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  892): linkConfiguration link due to same gw "NG700" and "NG7005g" GW c0:ff:d4:d3:aa:48
E/WifiConfigStore(  892): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore(  892): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore(  892): readNetworkVariablesFromSupplicantFile key=psk
I/art     (  472): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 232us total 13.913ms
E/WifiConfigStore(  892): readNetworkVariableFromSupplicantFile ssid=["NG7005g"] key=psk
E/WifiConfigStore(  892): linkConfiguration: will link "NG700"WPA_PSK and "NG7005g"WPA_PSK
E/WifiConfigStore(  892):         got known scan result c0:ff:d4:d3:aa:4a key : "NG7005g"WPA_PSK num: 1 rssi=-53 freq=5220
E/WifiAutoJoinController (  892): 01ABC c2:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  892): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  892): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  892): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  892): linkConfiguration link due to same gw "NG7005g" and "NG700" GW c0:ff:d4:d3:aa:48
E/WifiConfigStore(  892): readNetworkVariablesFromSupplicantFile key=psk
D/PhoneApp( 1400): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1400): -- N1 =0
D/PhoneApp( 1400): -- N2 =0
D/PhoneApp( 1400): -- N3 =0
I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 237us total 15.500ms
E/WifiConfigStore(  892): readNetworkVariableFromSupplicantFile ssid=["NG7005g"] key=psk
E/WifiConfigStore(  892): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore(  892): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore(  892): linkConfiguration: will link "NG7005g"WPA_PSK and "NG700"WPA_PSK
E/WifiConfigStore(  892):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2462
E/WifiAutoJoinController (  892): Gonzos 38:f8:89:11:e9:11 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  892): ageScanResultsOut delay 40000 size 4 now 1448306470234
E/WifiAutoJoinController (  892): newSupplicantResults size=4 known=2 true
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1374): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  892): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:4a
E/WifiAutoJoinController (  892): ssid=NG7005g
E/WifiAutoJoinController (  892): id=3
E/WifiAutoJoinController (  892): mode=station
E/WifiAutoJoinController (  892): pairwise_cipher=CCMP
E/WifiAutoJoinController (  892): group_cipher=CCMP
E/WifiAutoJoinController (  892): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  892): wpa_state=COMPLETED
E/WifiAutoJoinController (  892): ip_address=192.168.1.127
E/WifiAutoJoinController (  892): p2p_device_address=02:ee:bd:dd:33:d2
E/WifiAutoJoinController (  892): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  892): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  892): attemptAutoJoin() num recent config 2 current="NG7005g"WPA_PSK ---> suppNetId=3
E/WifiAutoJoinController (  892): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG7005g"WPA_PSK rssi=(-127,-53) num=(0,1)
E/WifiAutoJoinController (  892): attemptAutoJoin skip current candidate  3 key "NG7005g"WPA_PSK
E/WifiAutoJoinController (  892): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-59,-127) num=(1,0)
E/WifiAutoJoinController (  892): attemptAutoJoin trying id=2 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  892): compareNetwork will compare "NG700"WPA_PSK with current "NG7005g"WPA_PSK
E/WifiAutoJoinController (  892):     getConfigNetworkScore for "NG7005g"WPA_PSK -> no available score
E/WifiAutoJoinController (  892):     getConfigNetworkScore for "NG700"WPA_PSK -> no available score
E/WifiAutoJoinController (  892):     compareWifiConfigurationsWithScorer no-scores: "NG7005g"WPA_PSK "NG700"WPA_PSK
E/WifiAutoJoinController (  892):     compareWifiConfigurationsRSSI: "NG7005g"WPA_PSK -127,-53 boost=10 "NG700"WPA_PSK -59,-127 boost=0
E/WifiAutoJoinController (  892):         "NG7005g"WPA_PSK->:    rssi5 -53 boost 50
E/WifiAutoJoinController (  892):     compareWifiConfigurationsRSSI "NG7005g"WPA_PSK rssi=(-127,-53) num=(0,1) scorea=7 > "NG700"WPA_PSK rssi=(-59,-127) num=(1,0) scoreb=-59 -> -50
E/WifiAutoJoinController (  892): compareWifiConfigurations: "NG7005g"WPA_PSK > "NG700"WPA_PSK order -50
E/WifiAutoJoinController (  892): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK with current "NG7005g"WPA_PSK linked=true : delta=-50  -> not switching
E/WifiAutoJoinController (  892): attemptRoam: "NG7005g"WPA_PSK Found c0:ff:d4:d3:aa:4a rssi=-53 freq=5220 Current: c0:ff:d4:d3:aa:4a
D/HtcWifiControlRoamOffload: (  892): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:4a
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  892): Done attemptAutoJoin status=0
E/WifiConfigStore(  892):  writeKnownNetworkHistory() num networks:4 needWrite=false
I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 228us total 15.406ms
I/ActivityManager(  892): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=4304 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a
E/WifiStateMachine(  892): handleMessage: X
I/AlarmManager(  892): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@be217bf
D/WifiManager( 1727): getScanResults: Base Package Name=com.google.android.gms, uid=10025
I/AlarmManager(  892): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@f3a7e8c
I/AlarmManager(  892): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@3abeb9d5
D/Process (  892): killProcessQuiet, pid=3745
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.google.android.apps.maps
D/WirelessDisplayService(  892): getDiscoveryDongleList
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.google.android.gsf
D/WirelessDisplayService(  892): getDiscoveryDongleList
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  892): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  892): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  892): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  892): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  892): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  892): Killing 3745:com.android.managedprovisioning/u0a66 (adj 15): empty #17
W/ResourcesManager( 4304): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  892): Recipient 3745
D/HtcFingerPrintQuickLaunchProvider( 4287): -onCreate()
D/PMS     (  892): acquireWL(2f9235ea): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
D/Process (  892): killProcessQuiet, pid=3745
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10066/pid_3745/cgroup.procs: No such file or directory
D/PMS     (  892): releaseWL(2f9235ea): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  892): acquireWL(1755c6b6): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 WorkSource{10054 com.htc.sense.hsp}
D/PMS     (  892): releaseWL(1755c6b6): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{10054 com.htc.sense.hsp}
D/LocationManagerService(  892): incoming location from: network
D/PMS     (  892): acquireWL(38d53fb7): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
D/LocationManagerService(  892):  Report location to Reciever:  PackageName= com.htc.sense.hsp Request interval=+1s0ms
I/CalendarProvider2( 4304): Created com.android.providers.calendar.CalendarAlarmManager@7904213(com.htc.providers.calendar.HtcCalendarProvider@1a401c50)
D/PMS     (  892): acquireWL(2ac01324): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 892 1000 WorkSource{10054 com.htc.sense.hsp}
D/PMS     (  892): releaseWL(2ac01324): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{10054 com.htc.sense.hsp}
D/PMS     (  892): acquireWL(2b754e8d): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 892 1000 WorkSource{1000 android}
D/AutoSetting( 1528): service - onStartCommand() action: com.htc.app.autosetting.location
D/PMS     (  892): acquireWL(18754689): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 892 1000 WorkSource{10054 com.htc.sense.hsp}
D/PMS     (  892): acquireWL(3c62f68e): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 892 1000 WorkSource{10025 com.google.android.gms}
D/PMS     (  892): releaseWL(38d53fb7): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
V/Settings:HtcSettingsApplication( 4287): [4287/4287] onCreate()
D/PMS     (  892): acquireWL(1d166eaf): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1727 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  892): acquireWL(2a0a2bc): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 892 1000 WorkSource{10025 com.google.android.gms}
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
D/WifiService(  892): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@16abec48}
D/AutoSetting( 1528): service - AddressCache: calling geocoder COUNTME
D/PMS     (  892): acquireWL(7f23dc1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1727 10025 null
D/PMS     (  892): releaseWL(3c62f68e): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  892): releaseWL(2a0a2bc): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  892): releaseWL(3039f6eb): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{10054 com.htc.sense.hsp}
D/CalendarProvider2( 4304): wait start:true
D/PMS     (  892): releaseWL(1d166eaf): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  892): releaseWL(2b754e8d): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{1000 android}
D/PMS     (  892): releaseWL(7f23dc1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  892): releaseWL(18754689): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{10054 com.htc.sense.hsp}
I/GoogleURLConnFactory( 1727): Using platform SSLCertificateSocketFactory
D/CalendarProvider2( 4304): wait end:false
D/TetherSettings( 4287): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4287): Cust_ConnectToPC   : Internet_Sharing>true
W/GoogleHttpClient( 1727): Ignoring unsupported parameter: http.conn-manager.max-per-route
D/        ( 4287): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4287): Cust_ConnectToPC   : spcsc>false
D/        ( 4287): Cust_ConnectToPC   : IPT>true
D/        ( 4287): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4287): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4287): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4287): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4287): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
D/Process (  892): killProcessQuiet, pid=2103
I/ActivityManager(  892): Killing 2103:com.google.android.gms.wearable/u0a25 (adj 15): empty #17
I/SmartNS_Utility( 4287): setISNotification
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/SmartNS_Utility( 4287): usb_cable_connect = 1
D/SmartNS_Utility( 4287): usb_denied = 0
I/SmartNS_PSService( 4287): usb notificaiton:true
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
D/libc    ( 1727): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1727): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1727): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1727): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1727): [NET] android_getaddrinfo_proxy+
D/libc    ( 1727): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  461): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
I/ActivityManager(  892): Recipient 2103
D/libc    (  461): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/Process (  892): killProcessQuiet, pid=2103
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10025/pid_2103/cgroup.procs: No such file or directory
I/ActionCombine( 4287): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/SmartNS_Utility( 4287): usb_cable_connect = 1
D/SmartNS_Utility( 4287): usb_denied = 0
I/SmartNS_PSService( 4287): usb notificaiton:true
D/DotMatrix( 1211): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1121): reapply : com.android.settings 0 36
D/DotMatrix( 1211): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1121): reapply : com.android.settings 1 36
I/ActivityManager(  892): Killing 2008:com.google.android.gms/u0a25 (adj 15): empty #17
D/Process (  892): killProcessQuiet, pid=2008
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager(  892): Recipient 2008
D/libc    (  461): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  461): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1727): [NET] android_getaddrinfo_proxy-, success
D/Process (  892): killProcessQuiet, pid=2008
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10025/pid_2008/cgroup.procs: No such file or directory
W/ContextImpl(  892): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
I/ActivityManager(  892): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4331 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
D/SmartDim(  892): Init customizeScreenOffDelayClass error
E/MP-Decision( 2354): Update arg 2
W/BroadcastQueue(  892): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{446619f u0 ReceiverList{25c01f3e 892 system/1000/u0 local:35bfe3f9}}
I/SensorManager(  892): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@3495c443, sensor = {Sensor name="Accelerometer Sensor", vendor="HTC Group Ltd.", version=1, type=1, maxRange=19.6133, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  892): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  892): enable: get sensor name = Accelerometer Sensor
W/SensorService(  892): pid=892, uid=1000
W/SensorService(  892): Active sensors: size = 2
W/SensorService(  892): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  892): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  892): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3495c443, eanble = 1, strlen(mName) = 36
W/SensorService(  892): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  892): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@9fa3978
W/SensorService(  892): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@243b2712
W/SensorService(  892): Listener[2] = com.htc.smartdim.sensor_eye@3495c443
W/SensorService(  892): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  892): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@3495c443, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  892): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  892): enable: get sensor name = CM36282 Proximity sensor
W/SensorService(  892): pid=892, uid=1000
W/SensorService(  892): Active sensors: size = 3
W/SensorService(  892): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  892): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  892): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  892): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3495c443, eanble = 1, strlen(mName) = 36
W/SensorService(  892): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  892): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@9fa3978
W/SensorService(  892): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@243b2712
W/SensorService(  892): Listener[2] = com.htc.smartdim.sensor_eye@3495c443
W/SensorService(  892): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/libc    ( 1727): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1727): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1727): [NET] android_getaddrinfofornet+,hn 14(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1727): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  892): Killing 3872:com.htc.cs.pns/u0a74 (adj 15): empty #17
D/Process (  892): killProcessQuiet, pid=3872
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager(  892): Recipient 3872
E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  892):  packet count Tx=66 Rx=66
E/WifiTrafficPoller(  892): notifying of data activity 3
D/WIFI_ICON( 1121): WifiActivity: 3
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/Process (  892): killProcessQuiet, pid=3872
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10074/pid_3872/cgroup.procs: No such file or directory
D/AutoSetting( 1528): service - AddressCache: calling geocoder COUNTME
I/ActivityManager(  892): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4352 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/MP-Decision( 2354): Update arg 1
D/AutoSetting( 1528): service - handleMessage() process successful, send out updated city
D/AutoSetting( 1528): service - saveAndNotify() save bundle as current, complete info: true
I/art     (  892): Explicit concurrent mark sweep GC freed 25053(1391KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 16MB/25MB, paused 976us total 92.285ms
D/AutoSetting( 1528): service - handleMessage() remove all retry messages
I/ActivityManager(  892): Waited long enough for: ServiceRecord{160b7eed u0 com.google.android.gms/.gcm.GcmService}
E/cutils-trace( 4368): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4368): ====startRecUseTime====
D/htc.customization.log.level( 4368):  is 
W/CustomizationLogLevel( 4368): Level value is invalid, use default level 2
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4352, uid=10075, userID:0
D/Finsky  ( 4352): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/CustomizationManager( 4368):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__203
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__405
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__304
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 4368): Parsing tag item name = HTC__002
V/CustomizationCIDLoader( 4368): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4368): Parsing tag category name = system
I/CustomizationCIDLoader( 4368): Parsing tag category name = application
I/CustomizationCIDLoader( 4368): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4368): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4368): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4368): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4368): Parsing tag category name = ACC
D/CustomizationManager( 4368):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4368):  All configurations done spent 0.088 (s)
E/ActTriggerJNI( 4368): open library fail.
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PMS     (  892): acquireHCC(71af14a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 892 1000 null
D/PMS     (  892): acquireHCC(253978bb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 892 1000 null
E/MP-Decision( 2354): Update arg 2
W/asset   (  892): Copying FileAsset 0xb91f5410 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/MP-Decision( 2354): Update arg 4
D/PMS     (  892): acquireWL(209ed816): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 892 1000 null
E/MP-Decision( 2354): Update arg "0 190 240 240".
E/MP-Decision( 2354): Update arg "0 75 400 400".
I/FeedHostManager( 1459): [onPause]
I/FeedProviderManager( 1459): onPause
I/FeedHostManager( 1459): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@380e5815
I/SocialFeedProvider( 1459): +onPause
I/SocialFeedProvider( 1459): -onPause
I/AnimationUtil(  892): isHTCRecent(HelloWorld/Recent screens.)/6
D/HtcSystemUPManager(  892): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
D/Finsky  ( 4352): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  892): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4403 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/StatusBarManagerService(  892): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  892): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  892): hiding MENU key
W/asset   ( 4403): Copying FileAsset 0xb8e85bc0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1459): [trimMemory] 20
I/ActivityManager(  892): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4420 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/Settings( 4352): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4352): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ResourcesManager( 4420): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4420): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/WebViewFactory( 4403): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4352, uid=10075, userID:0
I/MultiDex( 4420): VM with version 2.1.0 has multidex support
I/MultiDex( 4420): install
I/MultiDex( 4420): VM has multidex support, MultiDex support library is disabled.
D/Volley  ( 4352): [583] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4352): [576] DiskBasedCache.clear: Cache cleared.
V/JNIHelp ( 4420): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/LibraryLoader( 4403): Time to load native libraries: 17 ms (timestamps 2718-2735)
I/LibraryLoader( 4403): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4403): Binding Chromium to main looper Looper (main, tid 1) {7904213}
I/LibraryLoader( 4403): Expected native library version number "",actual native library version number ""
,I/chromium( 4403): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager(  892): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4442 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Process (  892): killProcessQuiet, pid=3929
I/ActivityManager(  892): Killing 3929:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  892): Recipient 3929
I/BrowserStartupController( 4403): Initializing chromium process, singleProcess=true
,W/art     ( 4403): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4403): ApplicationContext is null in ApplicationStatus,
,W/ActivityThread( 4420): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4420): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fdb2755: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4420): Installed default security provider GmsCore_OpenSSL
,W/chromium( 4403): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4403): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4403): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4403): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 4403): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4403): Build Date: 12/11/14 Thu
I/Adreno-EGL( 4403): Local Branch: 
,I/Adreno-EGL( 4403): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 4403): Local Patches: NONE
I/Adreno-EGL( 4403): Reconstruct Branch: NOTHING
,D/Process (  892): killProcessQuiet, pid=3929
,W/libprocessgroup(  892): failed to open /acct/uid_10079/pid_3929/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Finsky  ( 4352): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4352): [1] 2.run: Finished loading 1 libraries.
,W/System.err(  892): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c2cc395:true
W/System.err(  892): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  892): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  892): ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  892): 	at android.os.Binder.execTransact(Binder.java:454)
I/CalendarProvider2( 4304): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 4304): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/BluetoothAdapter( 4403): 506653807: getState(). Returning 12
,W/ResourcesManager( 4442): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,D/Finsky  ( 4352): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/ResourcesManager( 4442): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4352): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  892): killProcessQuiet, pid=3948
,I/ActivityManager(  892): Killing 3948:com.htc.showme/u0a85 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/HtcModeClient( 3285): handler message = 4011
,E/HtcModeClient( 3285): Check connection and retry 2 times.
,I/ActivityManager(  892): Recipient 3948
,I/MultiDex( 4442): VM with version 2.1.0 has multidex support
,I/MultiDex( 4442): install
I/MultiDex( 4442): VM has multidex support, MultiDex support library is disabled.
,W/art     ( 4403): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4403): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 4403): CordovaWebView is running on device made by: HTC
,D/Process (  892): killProcessQuiet, pid=3948
,W/libprocessgroup(  892): failed to open /acct/uid_10085/pid_3948/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/art     ( 4403): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4403): Attempt to remove local handle scope entry from IRT, ignoring
,D/Atlas   ( 4403): Validating map...,
,W/chromium( 4403): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  892): Killing 3967:com.htc.feedback/u0a87 (adj 15): empty #17
D/Process (  892): killProcessQuiet, pid=3967
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/InputMethodManager( 4403): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@129a6dac, mServedView=org.apache.cordova.engine.SystemWebView{38334a75 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1a048a0a
,E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL true Token 11 num clients 5,
E/WifiTrafficPoller(  892):  packet count Tx=69 Rx=71
I/InputMethodManagerService(  892): Disable input method client, pid=1459
D/StatusBarManagerService(  892): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  892): Enable input method client, pid=4403
I/ActivityManager(  892): Recipient 3967
,D/Process (  892): killProcessQuiet, pid=3967
W/libprocessgroup(  892): failed to open /acct/uid_10087/pid_3967/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  892): releaseWL(209ed816): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  892): Displayed com.example.hello/.MainActivity: +574ms
,W/XT9_C   ( 1285): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1285): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1285): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1285): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,V/JNIHelp ( 4442): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,V/Finsky  ( 4352): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/BindingManager( 4403): Cannot call determinedVisibility() - never saw a connection for the pid: 4403
,I/chromium( 4403): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/System  ( 4442): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19f4223b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 4442): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
I/ProviderInstaller( 4442): Installed default security provider GmsCore_OpenSSL
,D/Process (  892): killProcessQuiet, pid=3831
I/ActivityManager(  892): Killing 3831:com.htc.sense.mms/u0a67 (adj 15): empty #17,
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  892): Recipient 3831
,D/JsMessageQueue( 4403): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4403): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/Process (  892): killProcessQuiet, pid=3831,
W/libprocessgroup(  892): failed to open /acct/uid_10067/pid_3831/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,V/GLSUser ( 1778): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED,
,D/PMS     (  892): acquireWL(2defdef1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1778 10025 null,
,V/GmsCoreStatsServiceLauncher( 4442): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/NotificationStore( 1778): System rebooted after Notification storage file was last written
I/NotificationStore( 1778): Deleting the file
,D/PMS     (  892): releaseWL(2defdef1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,E/SQLiteLog( 1778): (283) recovered 63 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
,D/PersistentNotificationBroadcastReceiver( 1778): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/InstanceID/Rpc( 4442): Found 10025
,D/jxcore_app_log( 4403): JniHelper::setJavaVM(0xb7dc8b98), pthread_self() = -1191081648
,D/JX-Cordova( 4403): jxcore cordova android initializing
,W/jxcore-log( 4403): Initializing JXcore engine
,W/jxcore-log( 4403): JXcore engine is ready
,W/jxcore-log( 4403): Starting JXcore engine,
,D/FileApkUtils( 4442): Spent 15ms computing apk sha1.
,D/FileApkUtils( 4442): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 4442): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4442): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4442): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,D/PMS     (  892): acquireWL(28f31eae): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4442 10025 null
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1778, uid=10025, userID:0
,D/GmsModuleFndr( 4442): Beginning GMS chimera module scan
,W/asset   ( 4442): Copying FileAsset 0xb8f20ab0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.,
,D/PMS     (  892): acquireWL(2b71444f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4442 10025 WorkSource{10025 com.google.android.gms},
,D/GmsModuleFndr( 4442): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping,
D/ChimeraCfgMgr( 4442): Beginning module configuration check
,D/ChimeraCfgMgr( 4442): Module APKs unchanged, check complete,
,D/PMS     (  892): acquireWL(2066a0e5): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4442 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  892): acquireWL(3d8d15c8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4442 10025 null
D/PMS     (  892): acquireWL(12656661): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4442 10025 WorkSource{10025 com.google.android.gms}
,I/ActivityManager(  892): Delay finish: com.google.android.gms/.tron.AlarmReceiver
D/GCM     ( 4442): COMPAT: Multi user not supported
D/PMS     (  892): acquireWL(2a6b6e47): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4442 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  892): releaseWL(2b71444f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  892): releaseWL(28f31eae): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  892): releaseWL(12656661): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms}
D/GCM     ( 1778): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 4442): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}],
I/CheckinService( 4442): Disabling old GoogleServicesFramework version
,D/PMS     (  892): acquireWL(27eed5e0): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1727 10025 WorkSource{10025 com.google.android.gms}
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4442, uid=10025, userID:0
,D/SystemUpdateService( 4442): onCreate
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4442, uid=10025, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4442, uid=10025, userID:0
,I/GCoreUlr( 1727): DispatchingService.onCreate()
,W/jxcore-log( 4403): Platform android
W/jxcore-log( 4403): 
W/jxcore-log( 4403): Process ARCH arm
W/jxcore-log( 4403): 
,D/SystemUpdateService( 4442): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
I/ConfigService( 1778): onCreate
,I/ConfigFetchService( 4442): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  892): acquireWL(187dd5c2): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1727 10025 WorkSource{10025 com.google.android.gms}
,I/CheckinService( 4442): Checking schedule, now: 1448306472199 next: 1448870374586,
I/CheckinService( 4442): active receiver: disabled
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4442, uid=10025, userID:0
,I/jxcore-log( 4403): JXcore Cordova bridge is ready!,
I/jxcore-log( 4403): 
W/jxcore-log( 4403): JXcore engine is started
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4442, uid=10025, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4442, uid=10025, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0
,W/art     ( 4442): Suspending all threads took: 8.706ms,
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0
,I/art     ( 4442): Background sticky concurrent mark sweep GC freed 41(3KB) AllocSpace objects, 0(0B) LOS objects, 2% free, 4MB/4MB, paused 10.140ms total 24.154ms
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0,
V/AuthZen ( 4442): Handling intent: android.intent.action.BOOT_COMPLETED
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0,
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4442, uid=10025, userID:0
D/AuthZenEventHandler( 4442): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4442, uid=10025, userID:0
,D/PMS     (  892): acquireWL(6ad9c27): PARTIAL_WAKE_LOCK  Icing 0x1 4442 10025 WorkSource{10025 com.google.android.gms}
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4442, uid=10025, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4442, uid=10025, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4442, uid=10025, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4442, uid=10025, userID:0,
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4442, uid=10025, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4442, uid=10025, userID:0
,I/GCoreUlr( 1727): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,E/jxcore-log( 4403): >> HTC-HTC One_M8,
E/jxcore-log( 4403): 
,I/jxcore-log( 4403): Total memory 1912020992,
I/jxcore-log( 4403): 
I/jxcore-log( 4403): Free memory 159633408
I/jxcore-log( 4403): 
I/jxcore-log( 4403): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4403): 
I/jxcore-log( 4403): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4403): 
,I/jxcore-log( 4403): userPath [ 'www' ]
I/jxcore-log( 4403): 
I/jxcore-log( 4403): Size 1080 1776
I/jxcore-log( 4403): 
I/jxcore-log( 4403): Screen Brightness 142
I/jxcore-log( 4403): 
E/jxcore-log( 4403): Dummy Error Log.
E/jxcore-log( 4403): 
,I/art     ( 4442): Background sticky concurrent mark sweep GC freed 111(6KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 4MB/4MB, paused 9.293ms total 32.790ms,
I/ConfigFetchService( 4442): service connected
,E/WifiStateMachine(  892): handleMessage: E msg.what=131155
E/WifiStateMachine(  892): processMsg: ConnectedState
E/WifiStateMachine(  892):  ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-53 f=5220 sc=60 link=150 tx=2.4, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:2401] from screen [on:0 period:902493547] gl hn rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  892): processMsg: L2ConnectedState
E/WifiStateMachine(  892):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-53 f=5220 sc=60 link=150 tx=2.4, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:902493548] gl hn rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  892):  get link layer stats 0
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1374): wlan0: Control interface command 'SIGNAL_POLL'
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4442, uid=10025, userID:0,
,I/wpa_supplicant( 1374): environment dirty rate=0 [13][0][0]
W/System.err(  892): java.lang.Throwable: stack dump
W/System.err(  892): 	at java.lang.Thread.dumpStack(Thread.java:490)
E/WifiStateMachine(  892): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150,
E/WifiStateMachine(  892): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  892): updateConfiguration freq=5220 BSSID=c0:ff:d4:d3:aa:4a RSSI=-53 "NG7005g"WPA_PSK
W/System.err(  892): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
E/WifiStateMachine(  892): calculateWifiScore freq=5220 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=7.70 txretriesrate=0.00 rxrate=8.55 userTriggerdPenalty0
E/WifiStateMachine(  892):  good link -> stuck count =0
E/WifiStateMachine(  892):  badRSSI count0 lowRSSI count0 --> score 60,
W/System.err(  892): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  892): 	at android.os.Binder.execTransact(Binder.java:454)
E/WifiStateMachine(  892):  isHighRSSI       ---> score=65
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fae987d:true
,E/WifiStateMachine(  892): handleMessage: X,
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0
D/WifiWatchdogStateMachine(  892): RSSI current: 3 new: -53, 3
D/WIFI_ICON( 1121): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/art     ( 4442): Suspending all threads took: 9.675ms,
,I/ActivityManager(  892): Resuming delayed broadcast
,I/SystemUpdateService( 4442): cancelUpdate (empty URL)
I/SystemUpdateService( 4442): active receiver: disabled
,I/art     ( 4442): Background partial concurrent mark sweep GC freed 2774(234KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 14.316ms total 56.205ms
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4442, uid=10025, userID:0
D/PMS     (  892): releaseWL(2a6b6e47): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms}
D/ChimeraCfgMgr( 4442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PMS     (  892): releaseWL(6ad9c27): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
D/ConfigFetchService( 4442): ConfigApi connection successful.,
I/art     ( 1778): Explicit concurrent mark sweep GC freed 5539(349KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 3MB/7MB, paused 697us total 32.845ms
D/PMS     (  892): releaseWL(2066a0e5): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10025 com.google.android.gms}
,D/ChimeraCfgMgr( 4442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 4442): onDestroy
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1727, uid=10025, userID:0
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4558 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4442): Using Auth Proxy for data requests.
,I/GLSUser ( 4442): [ChannelManager] Attempting to channel bind connection HttpClient.,
,I/GLSUser ( 4442): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true,
I/GLSActivity( 1778): [ac] getting account id
,W/ResourcesManager( 4558): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 1778): [ChannelManager] Attempting to channel bind connection HttpClient.
I/AuthZen ( 4442): Fetching signing key...
I/GLSUser ( 1778): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1778): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/AuthZen ( 4442): Signing key fetched successfully!
,W/BaseAppContext( 4442): Using Auth Proxy for data requests.
,I/AuthZen ( 4442): Starting Enrollment...,
,I/art     (  892): Explicit concurrent mark sweep GC freed 21727(1166KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 16MB/25MB, paused 1.019ms total 76.413ms
D/AuthZen ( 4442): getting auth token. Attempt 0
,I/GCoreUlr( 1727): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/PMS     (  892): acquireWL(486195d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1727 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  892): releaseWL(486195d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 1727): Unbound from all location providers
,D/PMS     (  892): releaseWL(187dd5c2): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms}
,I/GLSUser ( 1778): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1778): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1778): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1778): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1778): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1778): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1778): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GLSActivity( 1778): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  892): releaseWL(27eed5e0): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10025 com.google.android.gms}
,E/AuthZen ( 4442): Error getting auth token
E/AuthZen ( 4442): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4442): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4442): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4442): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4442): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4442): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/GCoreUlr( 1727): DispatchingService.onDestroy()
D/PMS     (  892): acquireWL(310afef6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1727 10025 WorkSource{10025 com.google.android.gms}
,E/AuthZen ( 4442): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4442): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4442): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4442): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4442): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4442): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4442): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/GCoreUlr( 1727): Unbound from all location providers
,D/PMS     (  892): releaseWL(310afef6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/ActionCombine( 1778): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/ResourcesManager( 1121): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1121): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1211): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1211): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/a       ( 4442): Opening database auth.proximity.permit_store...
W/ResourcesManager( 1211): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1211): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DotMatrix( 1211): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1211): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/Kids    ( 4442): [AccountUtils] Account not ready
W/Kids    ( 4442): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4442): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4442): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4442): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4442): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4442): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4442): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4442): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4442): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4442): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4442): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4442): 	at java.lang.Thread.run(Thread.java:818)
,D/AuthZenTransactionCache( 4442): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4442): Clearing transaction cache
,I/RemoteViews( 1121): apply : com.google.android.gms 0 5 8 40,
,E/WifiDataStallTracker(  892): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  892): updateDataStallInfo: mDataStallTxRxSum={txSum=56 rxSum=57} preTxRxSum={txSum=44 rxSum=45}
D/WifiDataStallTracker(  892): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  892): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL true Token 11 num clients 5,
E/WifiTrafficPoller(  892):  packet count Tx=69 Rx=71
E/WifiTrafficPoller(  892): notifying of data activity 0
D/WIFI_ICON( 1121): WifiActivity: 0
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  892): acquireWL(23a1b2f7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 892 1000 null
,D/PMS     (  892): acquireWL(126aa564): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 892 1000 WorkSource{10025}
,D/PMS     (  892): releaseWL(23a1b2f7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,I/IntentController( 1121): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/PMS     (  892): acquireWL(3f7c1fc9): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 892 1000 null,
,D/PMS     (  892): releaseWL(3f7c1fc9): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/PhoneStatusBar( 1121): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020652 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,I/jxcore-log( 4403): getBuffer is called!!!!
I/jxcore-log( 4403): 
,I/Babel_SMS( 4558): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 4558): MmsConfig.loadMmsSettings
,I/ActivityManager(  892): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4597 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4558, uid=10120, userID:0,
,W/HtcWrapAdjustableCursorFactory( 4597): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 4597): onCreate,
,D/MmsCustomizationProvider( 4597): query uri: content://htc-mms-customization/mms-ua/ua_string,
V/GetPrviateResource( 4597): GetPrviateResource
,W/Settings( 4558): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,V/GetPrviateResource( 4597): GetPrviateResource
,D/MmsCustomizationProvider( 4597): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel_SMS( 4558): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
I/Babel_SMS( 4558): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4558): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 4558): MmsConfig.loadFromResources
I/Babel_Crash( 4558): startup - clean
E/Babel_SMS( 4558): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4558): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
,D/MessageCustFlag( 4597): sense_version=6.0
,I/Babel   ( 4558): deleted: false for 0
,D/BTAccessoryUtil( 4597): createReceiver
,D/BTAccessoryUtil( 4597): registerReceiver return intent = null
,D/MessageCustFlag( 4597): sku_id=99
,D/HtcBuildUtils( 4597): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4597): Cannot find qct_8960_interface, use default value instead,
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4558, uid=10120, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4558, uid=10120, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4558, uid=10120, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4558, uid=10120, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4558, uid=10120, userID:0,
,D/PMS     (  892): acquireWL(9cf8d39): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 892 1000 null
,D/PMS     (  892): releaseWL(126aa564): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10025}
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4558, uid=10120, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4558, uid=10120, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4558, uid=10120, userID:0
,I/IntentController( 1121): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4558, uid=10120, userID:0,
D/PMS     (  892): releaseWL(9cf8d39): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4558, uid=10120, userID:0
,W/VideoCapabilities( 4558): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4558): Unsupported mime video/x-ms-wmv
,W/AudioCapabilities( 4558): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4558): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4558): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4558): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 4558): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4558): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4558): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4558): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4558): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4558): onServiceConnected
,W/Babel   ( 4558): Attempted to change video mute state without an active call.
,I/ActivityManager(  892): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4619 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
D/Process (  892): killProcessQuiet, pid=3997
I/ActivityManager(  892): Killing 3997:com.htc.updater/u0a88 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  892): Recipient 3997,
,D/Process (  892): killProcessQuiet, pid=3997,
W/libprocessgroup(  892): failed to open /acct/uid_10088/pid_3997/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/PMS     (  892): releaseHCC(71af14a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
E/MP-Decision( 2354): Update arg 1
D/PMS     (  892): releaseHCC(253978bb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/ResourcesManager( 4619): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4619): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4619): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 4619): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 4619): Installed default security provider GmsCore_OpenSSL
,E/cutils-trace( 4647): Error opening trace file: No such file or directory (2),
I/dex2oat ( 4647): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1709379986.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads-1709379986.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 4619): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 4619): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,D/libc    ( 4619): [NET] android_getaddrinfofornet-, SUCCESS
,I/dex2oat ( 4647): dex2oat took 62.273ms (threads: 4),
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4619): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL true Token 11 num clients 5,
E/WifiTrafficPoller(  892):  packet count Tx=69 Rx=72
E/WifiTrafficPoller(  892): notifying of data activity 1
D/WIFI_ICON( 1121): WifiActivity: 1
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/Vold    (  363): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4619): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/,
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4619): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/,
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4619): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 4619): Found 10025,
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4619): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4706 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/libc    ( 4619): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 4619): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4619): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 4619): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4619): [NET] android_getaddrinfo_proxy+
D/libc    ( 4619): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  461): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  461): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/Process (  892): killProcessQuiet, pid=4052,
,I/ActivityManager(  892): Killing 4052:com.htc.android.worldclock/u0a96 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  892): Recipient 4052,
,D/libc    (  461): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  461): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4619): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4619): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 4619): [NET] android_getaddrinfofornet-, SUCCESS
,D/Process (  892): killProcessQuiet, pid=4052
,D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10096/pid_4052/cgroup.procs: No such file or directory
,D/libc    ( 4619): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 4619): [NET] android_getaddrinfofornet-, err=8
,D/LocationManagerService(  892): getProviders()=[passive, network]
,I/ActivityManager(  892): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4741 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a,
,I/art     (  472): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 184us total 14.490ms,
I/art     (  472): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 169us total 10.727ms,
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4706, uid=10089, userID:0
,I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 173us total 10.938ms,
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4706, uid=10089, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4706, uid=10089, userID:0,
,D/WifiService(  892): New client listening to asynchronous messages,
E/WifiTrafficPoller(  892): ADD_CLIENT: 6
,I/ActivityManager(  892): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4780 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Process (  892): killProcessQuiet, pid=4030,
I/ActivityManager(  892): Killing 4030:com.htc.videocenter/u0a91 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
I/SearchBackgroundTaskFac( 4706): refreshing internal icing corpora
,I/ActivityManager(  892): Recipient 4030,
,D/Process (  892): killProcessQuiet, pid=4030
W/libprocessgroup(  892): failed to open /acct/uid_10091/pid_4030/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/UpdateIcingCorporaServi( 4706): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE,
,I/art     ( 1727): Explicit concurrent mark sweep GC freed 24415(1760KB) AllocSpace objects, 9(167KB) LOS objects, 42% free, 5MB/9MB, paused 577us total 40.500ms,
,W/LocationOracleImpl( 4706): Best location was null,
,I/GLSUser ( 1778): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow,
I/GLSUser ( 1778): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1778): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1778): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1211): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1211): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/UpdateIcingCorporaServi( 4706): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
,I/RemoteViews( 1121): reapply : com.google.android.gms 2 40
,W/Search.LoginHelper( 4706): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow,
W/Search.LoginHelper( 4706): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4706): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4706): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4706): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4706): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4706): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4706): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4706): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4706): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4706): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4706): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4706): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4706): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4706): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4706): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4706): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4706): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,E/VelvetNetworkClient( 4706): Failed to get auth token
,I/WebViewFactory( 4706): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4706): Time to load native libraries: 1 ms (timestamps 6031-6032)
,I/LibraryLoader( 4706): Expected native library version number "",actual native library version number ""
,W/art     ( 4706): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  892):  packet count Tx=79 Rx=80
E/WifiTrafficPoller(  892): notifying of data activity 3
,D/WIFI_ICON( 1121): WifiActivity: 3
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/art     ( 4706): Attempt to remove local handle scope entry from IRT, ignoring
,I/Gmail   ( 4780): getAccountsCursor
,I/art     (  892): Explicit concurrent mark sweep GC freed 15942(842KB) AllocSpace objects, 5(145KB) LOS objects, 33% free, 17MB/25MB, paused 1.159ms total 102.067ms
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4780, uid=10115, userID:0
,W/ActivityManager(  892): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4780, uid=10115, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4780, uid=10115, userID:0
I/Gmail   ( 4780): Observing account changes for notifications
,W/GAV2    ( 4780): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/libc    ( 4706): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    ( 4706): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4706): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4706): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  461): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    (  461): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,E/Gmail   ( 4780): Error finding the version of the Email provider.....,
E/Gmail   ( 4780): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4780): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4780): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4780): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4780): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4780): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4780): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4780): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4780): We do not support migrating this version of the Email provider.
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4780, uid=10115, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4780, uid=10115, userID:0
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4780, uid=10115, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4780, uid=10115, userID:0
,I/Gmail   ( 4780): getAccountsCursor
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/htcbackup-core( 4158): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF,
I/htcbackup-core( 4158): SuperSaverModeReceiver: going to send resume event
,I/ActivityManager(  892): Delay finish: com.htc.backup/.receiver.SuperSaverModeReceiver
,D/libc    (  461): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  461): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 4706): [NET] android_getaddrinfo_proxy-, success
,I/htcbackup-core( 4158): BackupRestoreManager: onHandleIntent
,I/htcbackup-core( 4158): BackupRestoreManager: resume
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4780, uid=10115, userID:0
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4780, uid=10115, userID:0
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  892): Resuming delayed broadcast
,E/ActivityThread( 4780): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@114c806b that was originally bound here
E/ActivityThread( 4780): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@114c806b that was originally bound here
E/ActivityThread( 4780): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4780): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4780): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1880)
E/ActivityThread( 4780): 	at android.app.ContextImpl.bindService(ContextImpl.java:1863)
E/ActivityThread( 4780): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4780): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4780): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4780): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4780): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4780): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4780): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4780): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
,E/ActivityThread( 4780): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4780): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4780): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4780): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4780): (283) recovered 12 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/GCM     ( 1778): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1778): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ActivityManager(  892): Unbind failed: could not find connection for android.os.BinderProxy@31cf7a4c
,E/htcbackup-core( 4158): BackupRestoreManager: Storage is not configured
,V/GmsCoreStatsServiceLauncher( 4442): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/htcbackup-core( 4158): BackupStatus: Ignoring failure message - backup already failed with message:  CONNECTION_FAIL_STORAGE,
,I/ActivityManager(  892): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4856 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4442, uid=10025, userID:0,
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65
D/AccFlag ( 1400): sku_id=99
,V/AlarmManager(  892): sending alarm PendingIntent{121d6a77: PendingIntentRecord{3c00c6e4 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=44382, Int=259200000
,V/AlarmManager(  892): sending alarm PendingIntent{c1ad202: PendingIntentRecord{2f43713 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1448306474964, Int=0
,V/AlarmManager(  892): sending alarm PendingIntent{3da2ab8d: PendingIntentRecord{a963142 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1448306474063, Int=20000
D/LocationInitializer( 4442): Restart initialization of location
D/PMS     (  892): acquireWL(16756d50): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
,I/GCoreUlr( 1727): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.android.location.internal.server.ACTION_RESTARTED}]
D/Messaging( 4597): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4597): networkCode: 
D/MessageCustFlag( 4597): sku_id=99
D/MmsConfig( 4597): SIE smsPri: null
D/MmsConfig( 4597): networkCode: 
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
D/AccFlag ( 1400): sku_id=99
,I/Gmail   ( 4780): calculateUnknownSyncRationalesAndPurgeInBackground: exiting (labelMap not synced
,I/GCoreUlr( 1727): DispatchingService.onCreate()
,W/ResourcesManager( 4856): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4856): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  892): acquireWL(12f9758b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4442 10025 null
D/MmsConfig( 4597): packageName: com.htc.vvm.att does not exist,
D/ReportIndicatorCache( 4597): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4597): 
D/MmsAsyncWorkHandler( 4597): HM tk = 20001
D/ReportIndicatorCache( 4597): MSG_QUERY_REPORTS >>
D/SettingsManager( 4597): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1a401c50
,D/PMS     (  892): acquireWL(a899668): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4442 10025 WorkSource{10025 com.google.android.gms},
D/PMS     (  892): releaseWL(12f9758b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null,
D/PMS     (  892): releaseWL(a899668): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms}
,D/DraftCache( 4597): [DraftCache/1] DraftCache.constructor,
D/DraftCache( 4597): [DraftCache/1] refresh
,I/Messaging( 4597): mccmnc> 
,D/Messaging( 4597): mNeedToUpdateDate2 start,
,D/MmsConfig( 4597): networkCode: 
,I/MultiDex( 4856): VM with version 2.1.0 has multidex support
I/MultiDex( 4856): install
I/MultiDex( 4856): VM has multidex support, MultiDex support library is disabled.
,I/Gmail   ( 4780): calculateUnknownSyncRationalesAndPurgeInBackground: exiting (labelMap not synced
,D/Messaging( 4597): ViewCache CreatePreloadOnlyConversationList,
,I/ActivityManager(  892): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4891 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
,D/PMS     (  892): acquireWL(24d8ea81): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1727 10025 WorkSource{10025 com.google.android.gms},
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
,D/MmsSmsV2Provider( 1400):  slotId = -1000
D/MmsSmsV2Provider( 1400): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65
D/AccFlag ( 1400): sku_id=99
,V/JNIHelp ( 4856): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/iu.UploadsManager( 4442): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 102
D/AccFlag ( 1400): sku_id=99
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4780, uid=10115, userID:0
D/PMS     (  892): acquireWL(1587df67): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 1727 10025 null
D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1400): sku_id=99
I/Gmail   ( 4780): getAccountsCursor
D/MessageCustFlag( 4597): sense_version=6.0
,D/Process (  892): killProcessQuiet, pid=4077
I/ActivityManager(  892): Killing 4077:com.htc.tiber2/u0a91 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
D/Jerry   ( 4597): start to preload cursor >>>>>>>
,D/PMS     (  892): acquireWL(1228adbd): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 1727 10025 null
,I/ActivityManager(  892): Recipient 4077
,D/DraftCache( 4597): [DraftCache/596] rebuildCache
,D/PMS     (  892): acquireWL(3d6fbfb2): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 1727 10025 null
,W/ActivityThread( 4856): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4856): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fdb2755: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4856): Installed default security provider GmsCore_OpenSSL
,I/SensorManager( 1727): registerListenerImpl: listener = com.google.android.location.collectionlib.cm@2e992a22, sensor = {Sensor name="Accelerometer Sensor", vendor="HTC Group Ltd.", version=1, type=1, maxRange=19.6133, resolution=0.01, power=0.17, minDelay=10000}, delay = 0, handler = Handler (com.google.android.location.collectionlib.ak) {3a597cb3}
,W/SensorService(  892): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  892): enable: get sensor name = Accelerometer Sensor
W/SensorService(  892): pid=1727, uid=10025
W/SensorService(  892): Active sensors: size = 3
,W/SensorService(  892): Accelerometer Sensor (handle=0x00000000, connections=3)
W/SensorService(  892): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  892): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  892): SensorService::listenerSensor++: mName = com.google.android.location.collectionlib.cm@2e992a22, eanble = 1, strlen(mName) = 53
,W/SensorService(  892): Active Listeners: mActiveListeners.size() = 4
W/SensorService(  892): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@9fa3978
W/SensorService(  892): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@243b2712
W/SensorService(  892): Listener[2] = com.htc.smartdim.sensor_eye@3495c443
W/SensorService(  892): Listener[3] = com.google.android.location.collectionlib.cm@2e992a22
W/SensorService(  892): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  892): acquireWL(2aa90b03): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
,D/Process (  892): killProcessQuiet, pid=4077
,W/libprocessgroup(  892): failed to open /acct/uid_10091/pid_4077/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
,D/Jerry   ( 1400): URI_DRAFT
,D/PhoneStorageUtil( 4597): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 4597): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4597): createReceiver
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103,
D/MmsSmsV2Provider( 1400):  slotId = -1000
D/MmsSmsV2Provider( 1400): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Process (  892): killProcessQuiet, pid=4100
I/ActivityManager(  892): Killing 4100:com.google.android.configupdater/u0a104 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,D/DraftCache( 4597): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4597): [DraftCache/596] rebuildCache time: 1
D/MmsAsyncWorkHandler( 4597): 
D/MmsAsyncWorkHandler( 4597): HM tk = 20002
,D/Messaging( 4597): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
,D/MmsSmsV2Provider( 1400):  slotId = -1000
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/MmsSmsV2Provider( 1400):  slotId = -1000
D/MmsSmsV2Provider( 1400): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/Messaging( 4597): ViewCache CreatePreload
D/Messaging( 4597): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,I/ActivityManager(  892): Recipient 4100
D/AccFlag ( 1400): sku_id=99
W/System.err( 4158): Starting the HTTP client
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
D/MmsSmsV2Provider( 1400):  slotId = -1000
D/MmsSmsV2Provider( 1400): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Cust_MMSMS( 4597): _has_set_default_values_2=true
,D/Messaging( 4597): mNeedToUpdateDate2: false
,D/MsgPreferenceUtils( 4597): def_index: 0
,W/htcbackup-core( 4158): BackupServiceClientResourceProxy: Reseting appServerErrorCount
,I/ImageRamCache( 4891): create image Cache, size: 31457280.
,I/ImageRamCache( 4891): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4891): create image Cache, size: 31457280.
,I/FeedSettings( 4891): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
,I/FeedSettings( 4891): GroupBudget 0.500000 0.380000
I/FeedSettings( 4891): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4891): changeLocale(): en_GB
,D/Process (  892): killProcessQuiet, pid=4100
W/libprocessgroup(  892): failed to open /acct/uid_10104/pid_4100/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/MsgPreferenceUtils( 4597): globalIndex = 1
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/AccFlag ( 1400): sku_id=99
,I/Prism.AllAppsOptionsMa_( 4891): loadSortType() with Custom,
,I/Prism.AllAppsOptionsMa_( 4891): loadGridSize() with Alternative
,D/WearableService( 4856): callingUid 10025, callindPid: 4856
I/art     ( 1778): Explicit concurrent mark sweep GC freed 13983(801KB) AllocSpace objects, 6(486KB) LOS objects, 49% free, 4MB/8MB, paused 427us total 26.202ms
,D/TelephUtils( 1400): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
V/MmsProvider( 1400): Update uri=content://mms, match=0
D/PMS     (  892): acquireWL(36695e6a): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
V/MmsProvider( 1400): selection=st=129 AND m_type!=134
D/MsgPreferenceUtils( 4597): phone state: true
,D/MsgPreferenceUtils( 4597): sd state: false
D/MsgPreferenceUtils( 4597): vIndex = 0
W/htcbackup-core( 4158): BackupRestoreManager: No sense account found - aborting
D/Messaging( 4597): Reset downloading state: 0
,D/WifiService(  892): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3bb6f736}
,I/GCoreUlr( 1727): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.android.location.internal.server.ACTION_RESTARTED,
,D/PMS     (  892): releaseWL(16756d50): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null,
,D/CustomHighlightReceiver( 4891): [custom highlight] onReceive
,V/MmsSystemEventReceiver( 4597): TransactionService is going to be woken up.
,D/CustomHighlightService( 4891): [custom highlight] onHandleIntent,
,D/NewsDB  ( 4891): set custom highlight []
,I/ActivityManager(  892): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4938 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/TransactionService( 4597): 1-Creating TransactionService,
D/CustomHighlightService( 4891): [custom highlight] set tags 
I/iu.UploadsManager( 4442): End new media; added: 0, uploading: 0, time: 244 ms
D/PMS     (  892): releaseWL(2aa90b03): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,E/WifiStateMachine(  892): handleMessage: E msg.what=131155
E/WifiStateMachine(  892): processMsg: ConnectedState
E/MDM     ( 1727): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/WifiStateMachine(  892):  ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-53 f=5220 sc=60 link=150 tx=7.7, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:2992] from screen [on:0 period:902496563] gl hn rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  892): processMsg: L2ConnectedState
E/WifiStateMachine(  892):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG7005g" c0:ff:d4:d3:aa:4a rssi=-53 f=5220 sc=60 link=150 tx=7.7, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:902496563] gl hn rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  892):  get link layer stats 0
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1374): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1374): environment dirty rate=0 [33][0][0]
,D/WIFI_ICON( 1121): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  892): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  892): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  892): updateConfiguration freq=5220 BSSID=c0:ff:d4:d3:aa:4a RSSI=-53 "NG7005g"WPA_PSK
E/WifiStateMachine(  892): calculateWifiScore freq=5220 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=20.35 txretriesrate=0.00 rxrate=18.78 userTriggerdPenalty0
E/WifiStateMachine(  892):  good link -> stuck count =0
E/WifiStateMachine(  892):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  892):  isHighRSSI       ---> score=65
V/TransactionService( 4597): onStartCommand: 1
D/MmsSystemEventReceiver( 4597): unRegisterForConnectionStateChanges
E/WifiStateMachine(  892): handleMessage: X
D/WifiWatchdogStateMachine(  892): RSSI current: 3 new: -53, 3
V/TransactionService( 4597): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4597): Loading previous transactions.
D/WifiService(  892): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3bb6f736}
,D/PMS     (  892): releaseWL(36695e6a): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/art     (  892): Explicit concurrent mark sweep GC freed 10866(554KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 796us total 68.655ms
,D/TelephUtils( 1400): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
D/AccFlag ( 1400): device_type: 1
,D/TransactionService( 4597): Force set service start id to 1
V/TransactionService( 4597): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4597): unRegisterForConnectionStateChanges
,D/TransactionService( 4597): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4597): Destroying TransactionService
,D/Process (  892): killProcessQuiet, pid=4137
I/ActivityManager(  892): Killing 4137:com.htc.cs.dm/u0a105 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  892): Recipient 4137
,V/TransactionService( 4597): 4-Handling incoming message: { when=-30ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/Process (  892): killProcessQuiet, pid=4137
W/libprocessgroup(  892): failed to open /acct/uid_10105/pid_4137/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/Gmail   ( 4780): master sync=false, engine sync=true,
,E/Gmail.LabelManager( 4780): Unable to get label ^i for account thalitester@gmail.com
,E/Gmail   ( 4780): Couldn't find label: ^i
,I/MusicStore( 4938): Database version: 120,
,I/GCoreUlr( 1727): WorldUpdater:com.google.android.location.internal.server.ACTION_RESTARTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]},
,D/PMS     (  892): acquireWL(34a9b70e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1727 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  892): releaseWL(34a9b70e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms},
I/GCoreUlr( 1727): Unbound from all location providers
,D/PMS     (  892): releaseWL(24d8ea81): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms},
,I/GCoreUlr( 1727): DispatchingService.onDestroy()
,D/PMS     (  892): acquireWL(4dd652f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1727 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  892): releaseWL(4dd652f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,I/GCoreUlr( 1727): Unbound from all location providers
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/Vold    (  363): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4938): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  892):  packet count Tx=102 Rx=100
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 4938): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4938): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 4938): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4938): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4938): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 4938): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4938): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ea74ed: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4938): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4938): GMSCore installation verified
,I/ConfigStore( 4938): Config Database version: 1,
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4938, uid=10167, userID:0,
,D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  892):     Client/Owner: Client
D/WifiDisplayAdapter(  892):     GroupId: 
D/WifiDisplayAdapter(  892):     Passphrase: 
D/WifiDisplayAdapter(  892):     SessionId: 0
D/WifiDisplayAdapter(  892):     IP Address: }
,D/MediaRouterService(  892): Client com.google.android.music (pid 4938): Registered,
,D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  892):     Client/Owner: Client
D/WifiDisplayAdapter(  892):     GroupId: 
D/WifiDisplayAdapter(  892):     Passphrase: 
,D/WifiDisplayAdapter(  892):     SessionId: 0
D/WifiDisplayAdapter(  892):     IP Address: }
,I/MediaRouter( 4938): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 4938): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 4938): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 4938): type=WIFI subType= reason=null isConnected=true,
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4938, uid=10167, userID:0,
,I/ActivityManager(  892): Start proc com.fitbit.FitbitMobile for broadcast com.fitbit.FitbitMobile/.NetworkStateReceiver: pid=4974 uid=10023 gids={50023, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a,
,I/GHttpClientFactory( 4938): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 4938): Using platform SSLCertificateSocketFactory,
,D/Process (  892): killProcessQuiet, pid=4192,
I/ActivityManager(  892): Killing 4192:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  892): Recipient 4192
,D/Process (  892): killProcessQuiet, pid=4192,
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_4192/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{3d01990b u0 com.htc.autobot/.htcmodeclient.HtcModeService}
W/System.err(  892): java.lang.Throwable: stack dump
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ca021f7:true
W/System.err(  892): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  892): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  892): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  892): 	at android.os.Binder.execTransact(Binder.java:454)
,D/HockeyApp( 4974): Current handler class = com.android.internal.os.RuntimeInit$UncaughtHandler
,D/Process (  892): killProcessQuiet, pid=4210,
I/ActivityManager(  892): Killing 4210:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  892): Recipient 4210,
,D/Process (  892): killProcessQuiet, pid=4210,
W/libprocessgroup(  892): failed to open /acct/uid_10013/pid_4210/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/AutoSetting( 1528): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  892): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5012 uid=10080 gids={50080, 9997, 3003} abi=armeabi-v7a
,D/AutoSetting( 1528): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate,
D/AutoSetting( 1528): service - requestNLP() to last request within 2hrs, don't request 6559
D/AutoSetting( 1528): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1528): service - handleMessage() setting current location null
,D/AutoSetting( 1528): Util - check NLP state, Allowned:true, Enabled:true
,D/PhoneMonitor( 5012): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5012): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
,D/MobileConnectivityChangeReceiver( 5012): onReceive CONNECTIVITY_CHANGE networkType=1
,D/PhoneMonitor( 5012): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 5012): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/Process (  892): killProcessQuiet, pid=4269,
I/ActivityManager(  892): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.NetworkChangeReceiver: pid=5031 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  892): Killing 4269:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,I/HtcModeClient( 3285): handler message = 4011,
,E/HtcModeClient( 3285): Check connection and retry 3 times.,
,I/ActivityManager(  892): Recipient 4269
,D/Process (  892): killProcessQuiet, pid=4269
W/libprocessgroup(  892): failed to open /acct/uid_10013/pid_4269/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  892): acquireWL(1f095685): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4442 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  892): acquireWL(36e6950b): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4442 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  892): releaseWL(1f095685): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
,I/CheckinService( 4442): Checking schedule, now: 1448306476541 next: 1448301414586
,I/CheckinService( 4442): active receiver: enabled
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4442, uid=10025, userID:0,
,I/CheckinService( 4442): Preparing to send checkin request,
I/EventLogService( 4442): Accumulating logs since 1448305934872
,I/DeviceManagement( 5031): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=5031 dbg=false s=true
I/DeviceManagement( 5031): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
,I/DeviceManagement( 5031): WorkflowService: Starting workflow service,
,I/DeviceManagement( 5031): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@33cfd34e] args=[Bundle[mParcelledData.dataSize=728]]
,I/DeviceManagement( 5031): NetworkChangeWorkflow: ==================================================,
I/DeviceManagement( 5031): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
I/DeviceManagement( 5031): NetworkChangeWorkflow: ==================================================
,I/DeviceManagement( 5031): ModelRegistry: Loading model meta data from resources...,
,I/ActivityManager(  892): Start proc com.twitter.android for broadcast com.twitter.android/.client.AppBroadcastReceiver: pid=5051 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DeviceManagement( 5031): SessionStateController: Checking invariants...
,E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1121): WifiActivity: 1
E/WifiTrafficPoller(  892):  packet count Tx=102 Rx=102
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  892): notifying of data activity 1
,I/DeviceManagement( 5031): BackgroundController: Invariants are unchanged.,
,I/DeviceManagement( 5031): SessionStateController: Checking invariants...
,I/ActivityManager(  892): Killing 4251:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  892): killProcessQuiet, pid=4251
,D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  892): Recipient 4251
,D/Process (  892): killProcessQuiet, pid=4251
,D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_4251/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4442): Checkin reason type: 8 attempt count: 1,
,I/DeviceManagement( 5031): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,D/WifiService(  892): New client listening to asynchronous messages
E/WifiTrafficPoller(  892): ADD_CLIENT: 7
,I/ActivityManager(  892): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4442): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 4442): Explicit concurrent mark sweep GC freed 22850(1797KB) AllocSpace objects, 22(352KB) LOS objects, 48% free, 4MB/8MB, paused 636us total 33.568ms,
,I/Crashlytics( 5051): Initializing Crashlytics 1.1.13.10,
,I/DeviceManagement( 5031): Perf: *** Cache update - start...,
I/DeviceManagement( 5031): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 5031): EnabledAppController: *** Updating enabled app database...,
I/DeviceManagement( 5031): Perf: *** Enabled app cache update - complete: 4 ms
I/DeviceManagement( 5031): Perf: *** Config cache update - start...
,I/DeviceManagement( 5031): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 5031): ConfigCacheController: *** Updating stale config cache entries...
,I/DeviceManagement( 5031): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 5031): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 5031): AlarmController: Scheduling TTL alarm for: 2015.11.24 at 20:20:59.576 CET (due to: com.htc.launcher)
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=5031, uid=10105, userID:0
,I/DeviceManagement( 5031): Perf: *** Config cache update - complete: 13 ms
,I/DeviceManagement( 5031): Perf: *** Cache update - complete: 19 ms
I/DeviceManagement( 5031): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@33cfd34e]
,I/DeviceManagement( 5031): WorkflowService: Stopping workflow service
,D/Process (  892): killProcessQuiet, pid=4331
I/ActivityManager(  892): Killing 4331:com.android.smith/1000 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  892): Recipient 4331
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.twitter.android/cache/
,W/ContextImpl( 5051): Failed to ensure directory: /storage/ext_sd/Android/data/com.twitter.android/cache
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
,D/Process (  892): killProcessQuiet, pid=4331
,D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_4331/cgroup.procs: No such file or directory
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.twitter.android/cache/,
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5051): Failed to ensure directory: /storage/ext_sd/Android/data/com.twitter.android/cache
,I/GLSUser ( 1778): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1778): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1778): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1778): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.twitter.android, clsName=com.twitter.android.samsung.single.TwitterWidgetProvider, state=2, flag=1, pid=5051, uid=10181, userID:0,
,W/CheckinRequestBuilder( 4442): awaiting user notification for token,
,I/RemoteViews( 1121): reapply : com.google.android.gms 2 40
,D/DotMatrix( 1211): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1211): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/ActivityManager(  892): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5102 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,W/ResourcesManager( 5102): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5102): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4442, uid=10025, userID:0
,I/iu.SyncManager( 4442): SYNC; picasa accounts
,D/NetworkLogImpl( 4442): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4442): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/MultiDex( 5102): VM with version 2.1.0 has multidex support
,I/MultiDex( 5102): install
I/MultiDex( 5102): VM has multidex support, MultiDex support library is disabled.
,I/iu.UploadsManager( 4442): num queued entries: 0,
I/iu.UploadsManager( 4442): num updated entries: 0,
,I/iu.SyncManager( 4442): NEXT; no task,
,D/ChimeraCfgMgr( 4442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  892): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5132 uid=10169 gids={50169, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/libc    ( 4558): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4558): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4558): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4558): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4558): [NET] android_getaddrinfo_proxy+
D/libc    ( 4558): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  461): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  461): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/GLSUser ( 1778): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1778): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1778): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1778): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1778): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1211): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1211): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Kids    ( 4442): [AccountUtils] Account not ready
W/Kids    ( 4442): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4442): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4442): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4442): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4442): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4442): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4442): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4442): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4442): 	at com.google.android.gms.chimera.f.run(SourceFile:179),
W/Kids    ( 4442): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4442): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4442): 	at java.lang.Thread.run(Thread.java:818)
I/RemoteViews( 1121): reapply : com.google.android.gms 1 40
,I/art     (  892): Explicit concurrent mark sweep GC freed 13431(716KB) AllocSpace objects, 3(113KB) LOS objects, 33% free, 17MB/25MB, paused 928us total 91.857ms
,D/libc    (  461): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  461): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4558): [NET] android_getaddrinfo_proxy-, success
,V/JNIHelp ( 5102): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/BluetoothManagerService(  892): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  892): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@18591dae mBinding = false
W/Settings:Agent(  892): MONITOR_LOG
W/Settings:Agent(  892): name: bluetooth_on
W/Settings:Agent(  892): value: 0
W/Settings:Agent(  892): >> traceCallingStack()
W/Settings:Agent(  892): Process.myPid(): 892
W/Settings:Agent(  892): Process.myTid(): 1637
W/Settings:Agent(  892): Process.myUid(): 1000
W/Settings:Agent(  892): 
W/Settings:Agent(  892): 
W/System.err(  892): java.lang.Throwable: stack dump
W/System.err(  892): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  892): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  892): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  892): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  892): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  892): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  892): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
W/System.err(  892): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:625)
W/System.err(  892): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  892): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  892): 
W/Settings:Agent(  892): << traceCallingStack(): 2(ms)
,I/Babel   ( 4558): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  892): Killing 4287:com.android.settings/1000 (adj 15): empty #17,
D/Process (  892): killProcessQuiet, pid=4287
,D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
W/System  ( 5102): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fdb2755: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 5102): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 5102): Installed default security provider GmsCore_OpenSSL,
W/ContextImpl( 5132): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/ActivityManager(  892): Recipient 4287,
,I/GAv4    ( 5132): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5132):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5132):   adb logcat -s GAv4
E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 5132): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5132): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  363): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
D/BluetoothManagerService(  892): Message: MESSAGE_DISABLE
W/Vold    (  363): Returning OperationFailed - no handler for errno 0
,D/BluetoothManagerService(  892): Sending off request.
W/ContextImpl( 5132): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/BluetoothAdapterState( 3054): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3054): Setting state to 13
I/BluetoothAdapterState( 3054): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  892): +onBluetoothStateChange prev=12 new=13
,D/BluetoothAdapterProperties( 3054): onBluetoothDisable()
,D/BluetoothManagerService(  892): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/bt-btm  ( 3054): BTM_SetDiscoverability
D/WifiService(  892): New client listening to asynchronous messages
D/BluetoothManagerService(  892): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/WifiService(  892): setWifiEnabled: false pid=4403, uid=10380
I/bt-btm  ( 3054): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
E/WifiService(  892): Invoking mWifiStateMachine.setWifiEnabled
D/bt-btm  ( 3054): disc_mode 0000
D/PMS     (  892): acquireWL(1863b21d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3054 1002 null
I/bt-btm  ( 3054): evt_type=0x0 p-cb->evt_type=0x0 
I/WifiService(  892): isSprintWifiRestricted(): false
I/bt-btm  ( 3054): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/WifiService(  892): isMdmWifiRestricted(): false
D/BluetoothManagerService(  892): Bluetooth State Change Intent: 12 -> 13
D/WifiManager( 4403): setWifiEnabled: Base Package Name=com.example.hello, uid=10380
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
,W/Settings:Agent(  892): MONITOR_LOG
W/Settings:Agent(  892): name: wifi_on
W/Settings:Agent(  892): value: 0
W/Settings:Agent(  892): >> traceCallingStack()
W/Settings:Agent(  892): Process.myPid(): 892
W/Settings:Agent(  892): Process.myTid(): 1315
W/Settings:Agent(  892): Process.myUid(): 1000
W/Settings:Agent(  892): 
W/Settings:Agent(  892): 
W/System.err(  892): java.lang.Throwable: stack dump
W/System.err(  892): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  892): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  892): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64),
W/System.err(  892): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  892): 	at android.provider.Settings$Global.putString(Settings.java:7403)
I/bt-btif ( 3054): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 3054): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 3054): BTM_SetConnectability
I/bt-btm  ( 3054): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3054): disc_mode 0000
I/bt-btm  ( 3054): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
E/WifiTrafficPoller(  892): ADD_CLIENT: 8
,W/System.err(  892): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  892): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
W/System.err(  892): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  892): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
W/System.err(  892): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  892): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  892): 
W/Settings:Agent(  892): << traceCallingStack(): 1(ms)
,D/Process (  892): killProcessQuiet, pid=4287
W/libprocessgroup(  892): failed to open /acct/uid_1000/pid_4287/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/WirelessDisplayService(  892): getMirrorDisplayStatus:falsecurState:1
E/WifiStateMachine(  892): handleMessage: E msg.what=131084
I/jxcore-log( 4403): ****TEST TOOK:  5073  ms ****
I/jxcore-log( 4403): 
E/WifiStateMachine(  892): processMsg: ConnectedState
I/jxcore-log( 4403): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4403): 
E/WifiStateMachine(  892):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  892): processMsg: L2ConnectedState
E/WifiStateMachine(  892):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  892): processMsg: ConnectModeState
D/BluetoothAdapterProperties( 3054): Scan Mode:21
D/BluetoothAdapterState( 3054): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 3054): BTA_JvDeleteRecord
,I/bt-btif ( 3054): BTA_JvRfcommStopServer
D/bt-btm  ( 3054): BTM_FreeSCN 
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:14
I/bt-btif ( 3054): BTA_JvDeleteRecord
I/bt-btm  ( 3054): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 3054): BTA_JvRfcommStopServer
D/bt-btm  ( 3054): BTM_FreeSCN 
I/bt-btm  ( 3054): BTM_SEC_CLR[14]: id 56
I/bt-btif ( 3054): BTA_JvDeleteRecord
E/BtOppRfcommListener( 3054): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/bt-btif ( 3054): BTA_JvRfcommStopServer
D/bt-btm  ( 3054): BTM_FreeSCN 
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3054): BTM_SEC_CLR[15]: id 57
I/IntentController( 1121): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
E/WifiStateMachine(  892):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
I/bt-btif ( 3054): BTA_JvDeleteRecord
I/bt-btif ( 3054): BTA_JvRfcommStopServer
D/bt-btm  ( 3054): BTM_FreeSCN 
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3054): BTM_SEC_CLR[16]: id 58
I/bt-btif ( 3054): BTA_JvDeleteRecord
I/bt-btif ( 3054): BTA_JvRfcommStopServer
D/bt-btm  ( 3054): BTM_FreeSCN 
,I/bt-btif ( 3054): BTA_JvDeleteRecord
D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  892):     Client/Owner: Client
D/WifiDisplayAdapter(  892):     GroupId: 
D/WifiDisplayAdapter(  892):     Passphrase: 
D/WifiDisplayAdapter(  892):     SessionId: 0
D/WifiDisplayAdapter(  892):     IP Address: }
I/bt-btif ( 3054): BTA_JvRfcommStopServer
D/bt-btm  ( 3054): BTM_FreeSCN 
E/bt-btif ( 3054): cmd socket is not created
V/BluetoothSapService( 3054): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3054): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3054): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3054): Write Extended Inquiry Response to controller
I/bt-btm  ( 3054): Write Extended Inquiry Response to controller
I/bt-btm  ( 3054): Write Extended Inquiry Response to controller
I/bt-btm  ( 3054): Write Extended Inquiry Response to controller
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3054): BTM_SetDiscoverability
I/bt-btm  ( 3054): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3054): disc_mode 0000
I/bt-btm  ( 3054): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3054): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3054): BTM_SetConnectability
I/bt-btm  ( 3054): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3054): disc_mode 0000
D/bt-btm  ( 3054): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3054): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3054): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3054): BTM_IsInquiryActive
I/bt-btm  ( 3054): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3054): btm_ble_clear_white_list
W/bt-btif ( 3054): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
E/WifiStateMachine(  892): processMsg: DriverStartedState
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3054): BTM_FreeSCN 
I/bt-btm  ( 3054): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3054): BTM_FreeSCN 
I/bt-btm  ( 3054): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3054): AVRC_Close handle:0
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3054): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3054): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3054): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3054): GATT_Deregister gatt_if=3
I/bt-att  ( 3054): GATT_Listen gatt_if=3
I/bt-btm  ( 3054): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3054): BTM_ReadConnectability
I/bt-btm  ( 3054): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3054): disc_mode 0000
I/bt-att  ( 3054): GATT_Deregister gatt_if=4
I/bt-att  ( 3054): GATT_Listen gatt_if=4
I/bt-btm  ( 3054): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3054): BTM_ReadConnectability
I/bt-btm  ( 3054): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3054): disc_mode 0000
E/bt-btif ( 3054): bta_gattc_deregister Deregister Failedm unknown client cif
E/WifiStateMachine(  892):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  892): processMsg: SupplicantStartedState
E/WifiStateMachine(  892): , SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
D/NGFService( 3697): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/bt-btm  ( 3054): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3054): btm_ble_clear_white_list_complete
E/WifiStateMachine(  892): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  892): handleMessage: new destination call exit/enter
E/WifiStateMachine(  892): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  892): invokeExitMethods: ConnectedState
E/WifiStateMachine(  892): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  892): release()
E/WifiStateMachine(  892): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  892): setScanAlarm false period 20000 initial delay 0
D/WirelessDisplayService(  892): getMirrorDisplayStatus:falsecurState:1
E/WifiStateMachine(  892): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  892): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$12700 - exit - invokeExitMethods
E/WifiStateMachine(  892): handleNetworkDisconnect c0:ff:d4:d3:aa:4a config "NG7005g"WPA_PSK config.bssid any
E/WifiStateMachine(  892): handleNetworkDisconnect "NG7005g" nid=3
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
W/WifiHW  (  892): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1374): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1374): CTRL_IFACE: SET_NETWORK id=3 name='bssid'
D/wpa_supplicant( 1374): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1374): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1374): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1374): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1374): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/GAv4    ( 5132): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1374): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1374): Power_Mode_Type mode = 0
I/wpa_supplicant( 1374): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1374): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1374): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 4096
D/WifiDataStallTracker(  892): setDhcpActive: false
,V/BluetoothPbapReceiver( 3054): ***********action = android.bluetooth.adapter.action.STATE_CHANGED,
D/PMS     (  892): acquireWL(2225dc92): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1778 10025 WorkSource{10025 com.google.android.gms}
V/BluetoothPbapReceiver( 3054): ***********state = 13
,D/ConnectivityService(  892): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10025
I/BtOppRfcommListener( 3054): stopping Accept Thread
D/ConnectivityService(  892): Validated NetworkAgentInfo [WIFI () - 100]
I/BtOppRfcommListener( 3054): BluetoothSocket listen thread finished
D/ConnectivityService(  892): rematching NetworkAgentInfo [WIFI () - 100]
V/NativeCrypto( 1778): Read error: ssl=0xb8fba210: I/O error during system call, Connection timed out
D/ConnectivityService(  892):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NativeCrypto( 1778): SSL shutdown failed: ssl=0xb8fba210: I/O error during system call, Broken pipe
D/ConnectivityService(  892):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  892): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  892): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/libc    (  892): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  892): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): ValidatedState{ when=-1ms what=532488 arg1=10025 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): DefaultState{ when=-1ms what=532488 arg1=10025 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Forcing reevaluation
D/ConnectivityService(  892): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  892): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5162 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Validated
D/ConnectivityManager.CallbackHandler( 1121): CM callback handler got msg 524290
I/SecurityController( 1121): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  892): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  892): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  892): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  892): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  892): [NET] android_getaddrinfofornet-, SUCCESS
V/BluetoothPbapService( 3054): Pbap Service closeService in
I/QuickSettingBluetooth( 1121): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
,E/WifiStateMachine(  892): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  892): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  892): ignoring duplicate network state non-change
V/BluetoothPbapService( 3054): successfully stopped pbap service
D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/BluetoothPbapService( 3054): Pbap Service closeService out
D/PMS     (  892): releaseWL(2225dc92): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
I/art     (  472): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 150us total 9.104ms
V/NetworkPolicy(  892): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  892): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/WIFI_ICON( 1121): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  892):  packet count Tx=107 Rx=106
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  892): notifying of data activity 3
D/WIFI_ICON( 1121): WifiActivity: 3
D/libc    (  892): [NET] android_getaddrinfofornet+,hn 24(0x666538303a3a32),sn(),hints(known),family 0,flags 4
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T],
D/libc    (  892): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1121): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/GAv4    ( 5132): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/art     (  472): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 147us total 8.896ms
D/WifiDisplayController(  892): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
I/IntentController( 1121): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  892):     Client/Owner: Client
D/WifiDisplayAdapter(  892):     GroupId: 
D/WifiDisplayAdapter(  892):     Passphrase: 
D/WifiDisplayAdapter(  892):     SessionId: 0
D/WifiDisplayAdapter(  892):     IP Address: }
D/WifiDataStallTracker(  892): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1121): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiDataStallTracker(  892): stopDataStallAlarm 
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  892): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  892): ENABLE_DATA_MONITOR_POLL false Token 1
I/IntentController( 1121): receive(android.net.wifi.STATE_CHANGE,1,false)
I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 131us total 9.665ms
V/BluetoothPbapService( 3054): Pbap Service onDestroy
V/BluetoothPbapService( 3054): Pbap Service closeService in
V/BluetoothPbapService( 3054): Pbap Service closeService out
E/WifiStateMachine(  892): autoRoamSetBSSID any key="NG7005g"WPA_PSK
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
W/WifiHW  (  892): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1374): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1374): CTRL_IFACE: SET_NETWORK id=3 name='bssid'
D/wpa_supplicant( 1374): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
I/IntentController( 1121): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1374): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1374): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiTrafficPoller(  892): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/wpa_supplicant( 1374): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1374): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  892): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  892): invokeExitMethods: DriverStartedState
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1374): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1374): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  892): Unexpected BatchedScanResults :null
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1374): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1374): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  892): noteBatchedScanstop()
E/WifiStateMachine(  892): [1,448,306,477,423 ms] noteScanEnd no scan source
E/WifiStateMachine(  892): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  892): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiS,tateMachine(  892): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  892): handleMessage: X
E/WifiStateMachine(  892): handleMessage: E msg.what=131212
E/WifiStateMachine(  892): processMsg: WaitForP2pDisableState
D/WifiMonitor(  892): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@2669add
E/WifiStateMachine(  892):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  892): processMsg: SupplicantStartedState
E/WifiStateMachine(  892):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  892): processMsg: DefaultState
D/WifiScanningService(  892): SCAN_AVAILABLE : 1
D/RttService(  892): SCAN_AVAILABLE : 1
D/WifiScanningService(  892): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler },
D/RttService(  892): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
W/GAv4    ( 5132): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/AudioService(  892): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  892):     Client/Owner: Client
V/AudioService(  892):     GroupId: 
V/AudioService(  892):     Passphrase: 
,V/AudioService(  892):     SessionId: 0
V/AudioService(  892):     IP Address: }
D/HtcEffectManagerBase(  892): onEventChanged id=5 status=false
D/HtcEffectManager(  892): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  892): convertEffect before=902
D/HtcEffectManager(  892): convertEffect after=902
E/WifiStateMachine(  892):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  892): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  892): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  892): handleMessage: X
E/WifiStateMachine(  892): handleMessage: E msg.what=131212
E/WifiStateMachine(  892): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  892):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  892): processMsg: SupplicantStartedState
E/WifiStateMachine(  892):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  892): processMsg: DefaultState
E/WifiStateMachine(  892):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  892): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0},
E/WifiStateMachine(  892): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES,
E/WifiStateMachine(  892): handleMessage: X
D/WifiNetworkAgent(  892): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  892): handleMessage: E msg.what=131205
E/WifiStateMachine(  892): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  892):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  892): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  892): handleMessage: new destination call exit/enter,
E/WifiStateMachine(  892): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  892): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  892): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  892): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  892): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  892): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  892): Call handleNetworkDisconnect() in SupplicantStoppingState
E/WifiStateMachine(  892): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$12700 - enter - invokeEnterMethods
E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1374): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1374): Power_Mode_Type mode = 0
I/wpa_supplicant( 1374): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  892): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1374): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1374): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 4096
D/WifiDataStallTracker(  892): setDhcpActive: false
I/QuickSettingWifi( 1121): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
E/WifiStateMachine(  892): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  892): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  892): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  892): stopping supplicant
D/WIFI_ICON( 1121): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  892): QCOM Debug wifi_send_command "TERMINATE"
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1374): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/ConnectivityService(  892):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1374): wlan0: Removing interface wlan0
D/ConnectivityService(  892): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1374): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:4a pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1374): TDLS: Tear down peers
D/WIFI_ICON( 1121): updateWifiState: WIFI_STATE_CHANGED disabled
D/wpa_supplicant( 1374): wpa_driver_nl80211_disconnect(reason_code=3)
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  892): setWifiState: disabling
E/WifiStateMachine(  892): handleMessage: X
E/WifiTrafficPoller(  892): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/WirelessDisplayService(  892): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/Nat464Xlat(  892): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
I/QuickSettingWifi( 1121): receive.wifiConnect:false wifiAPname:null elapse:6
D/ConnectivityService(  892): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
I/IntentController( 1121): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  892): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
I/IntentController( 1121): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/NetworkManagementService(  892): Removing idletimer
I/QuickSettingWifi( 1121): receive.wifiConnect:false wifiAPname:null elapse:1
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Disconnected - quitting,
D/ConnectivityManager.CallbackHandler( 1121): CM callback handler got msg 524292
D/PMS     (  892): acquireWL(148b35bf): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 892 1000 null
I/SecurityController( 1121): onLost 100
D/CSLegacyTypeTracker(  892): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/WIFI    (  892): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
,D/WIFI    (  892):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiDisplayAdapter(  892): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  892):     Client/Owner: Client
D/WifiDisplayAdapter(  892):     GroupId: 
D/WifiDisplayAdapter(  892):     Passphrase: 
D/WifiDisplayAdapter(  892):     SessionId: 0
D/WifiDisplayAdapter(  892):     IP Address: }
D/WIFI    (  892): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/ConnectivityService(  892): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  892): enter WifiNetworkFactory startNetwork. mIPTStart:false
V/NetworkPolicy(  892): ensureActiveMobilePolicyLocked()
D/usbnet  (  892): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/DATA_ICON( 1121): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Connected:false/Type:-1/Status:0
D/usbnet  (  892):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  892): acquireWL(3a60448c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 892 1000 null
D/usbnet  (  892): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
V/NetworkPolicy(  892): updateNetworkEnabledLocked()
D/WirelessDisplayService(  892): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
V/NetworkPolicy(  892): updateIfacesLocked()
D/WirelessDisplayService(  892): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/DATA_ICON( 1121): dataConnected: false/false
E/WifiStateMachine(  892): handleMessage: E msg.what=131143
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  892): processMsg: SupplicantStoppingState
V/NetworkPolicy(  892): updateNotificationsLocked()
E/WifiStateMachine(  892):  SupplicantStoppingState !CMD_START_SCAN 1000 2 ic=1 proc(ms):1 dur:294 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:2161] from screen [on:0 period:902498729]
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
E/WifiStateMachine(  892): processMsg: DefaultState
D/UsbDeviceManager(  892): [USBNET] bCheckSuppFunc: cdc_network
E/WifiStateMachine(  892):  DefaultState !CMD_START_SCAN 1000 2 ic=1 proc(ms):1 dur:294 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:902498729]
D/PMS     (  892): releaseWL(3a60448c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  892): handleMessage: X
D/PMS     (  892): acquireWL(2807d5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 892 1000 null
D/HtcFingerPrintQuickLaunchProvider( 5162): -onCreate()
D/PMS     (  892): releaseWL(2807d5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1374): wlan0: Event DEAUTH (12) received
V/NetworkPolicy(  892): updateNetworkEnabledLocked()
D/wpa_supplicant( 1374): wlan0: Deauthentication notification
V/NetworkPolicy(  892): updateNotificationsLocked()
D/wpa_supplicant( 1374): wlan0:  * reason 3 (locally generated)
V/NetworkPolicy(  892): updateNetworkEnabledLocked()
D/wpa_supplicant( 1374): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
V/NetworkPolicy(  892): updateNotificationsLocked()
I/wpa_supplicant( 1374): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1374): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220
E/wpa_supplicant( 1374): enter disconnect check
I/w,pa_supplicant( 1374): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/Tethering(  892): interfaceLinkStateChanged wlan0, false
D/Tethering(  892): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  892): interfaceLinkStateChanged wlan0, false
D/Tethering(  892): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1374): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1374): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 1374): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1374): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1374): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1374): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1374): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8ea5398 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1374):    addr=c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1374): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1374): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1374): netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1374): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1374): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1374): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1374): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1374): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1374): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1374): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1374): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1374): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1374): netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1374): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1374): EAPOL: External notification - portValid=0
D/Tethering(  892): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  892): TetherInterfaceSM: wlan0: exit InitialState
D/WifiMonitor(  892): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220]
V/Tethering(  892): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220
E/WifiMonitor(  892): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220
D/HTCRequest(  892): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1 ssid='NG7005g' freq=5220
E/WifiMonitor(  892): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:4a reason=3
D/WifiMonitor(  892): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=3 state=0 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g]
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=3 state=0 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  892): WifiMonitor:handleSupplicantStateChange():id=3 state=0 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  892): WifiMonitor:getSSIDFromString id=3 state=0 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/Tethering(  892): interfaceLinkStateChanged wlan0, false
D/Tethering(  892): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  892): WifiMonitor:handleSupplicantStateChange(): SSIDNG7005g
D/WifiMonitor(  892): WifiMonitor: prevSupplica,ntState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  892): handleMessage: E msg.what=147460
E/WifiStateMachine(  892): processMsg: SupplicantStoppingState
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  892):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:4a nid=1 reason=3 rt=48891
E/WifiStateMachine(  892): processMsg: DefaultState
E/WifiStateMachine(  892):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:4a nid=1 reason=3 rt=48891
E/WifiStateMachine(  892): handleMessage: X
D/Tethering(  892): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  892): handleMessage: E msg.what=147462
E/WifiStateMachine(  892): processMsg: SupplicantStoppingState
D/UsbnetService(  892): BroadcastReceiver::onReceive+
E/WifiStateMachine(  892):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=48891  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: DISCONNECTED
E/WifiStateMachine(  892): processMsg: DefaultState
D/UsbnetService(  892): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  892): BroadcastReceiver::onReceive-
E/WifiStateMachine(  892):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=48891  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: DISCONNECTED
E/WifiStateMachine(  892): handleMessage: X
E/WifiStateMachine(  892): handleMessage: E msg.what=131101
E/WifiStateMachine(  892): processMsg: SupplicantStoppingState
E/WifiStateMachine(  892):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  892): processMsg: DefaultState
E/WifiStateMachine(  892):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  892): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  892): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  892): handleMessage: X
I/QuickSettingWifi( 1121): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1121): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
I/ActivityManager(  892): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5188 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
V/Settings:HtcSettingsApplication( 5162): [5162/5162] onCreate()
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WISPrService( 5162): >>>>>WISPrService start isConnected = true<<<<<
W/bt-btif ( 3054): ag scb idx 1 not allocated
W/bt-btif ( 3054): ag scb idx 2 not allocated
E/bt-btif ( 3054): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3054): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3054): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3054): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0017
D/PMS     (  892): acquireWL(29ee4c51): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5162 1000 null
W/bt-l2cap( 3054): L2CAP - PSM: 0x0017 not found for deregistration
W/ContextImpl( 5162): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
W/bt-l2cap( 3054): L2CAP - PSM: 0x0019 not found for deregistration
D/PMS     (  892): releaseWL(29ee4c51): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
W/bt-l2cap( 3054): L2CAP - L2CA_Deregister() called for PSM: 0x0017
,D/PMS     (  892): acquireWL(dc41db7): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5162 1000 null
,W/bt-l2cap( 3054): L2CAP - PSM: 0x0017 not found for deregistration
D/WifiService(  892): New client listening to asynchronous messages
E/bt-btif ( 3054): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_userial_mct( 3054): pthread_join() FAILED result:3
E/WifiTrafficPoller(  892): ADD_CLIENT: 9
W/System.err(  892): java.lang.Throwable: stack dump
W/System.err(  892): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  892): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  892): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  892): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2efa5c8d:true
E/WifiStateMachine(  892): handleMessage: E msg.what=131131
E/WifiStateMachine(  892): processMsg: SupplicantStoppingState
E/WifiStateMachine(  892):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
E/WifiStateMachine(  892): processMsg: DefaultState
E/WifiStateMachine(  892):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
E/WifiStateMachine(  892): handleMessage: X
,I/ActivityManager(  892): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5208 uid=10036 gids={50036, 9997, 3002, 3001} abi=armeabi-v7a,
,D/WISPrService( 5162): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  892): handleMessage: E msg.what=196614
,E/WifiStateMachine(  892): processMsg: SupplicantStoppingState
E/WifiStateMachine(  892):  SupplicantStoppingState !CMD_ON_QUIT 0 0,
E/WifiStateMachine(  892): processMsg: DefaultState
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
E/WifiStateMachine(  892):  DefaultState !CMD_ON_QUIT 0 0
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
E/WifiStateMachine(  892): handleMessage: X
D/WISPrService( 5162): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothAdapter( 5162): 506653807: getState(). Returning 13
D/WISPrService( 5162): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5162): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothInputDevice( 5162): BluetoothInputDevice()
D/BluetoothManagerService(  892): registerStateChangeCallback+
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WISPrService( 5162): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5162): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothManagerService(  892): Registered receivers: 10
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/BluetoothPan( 5162): BluetoothPan()
,D/BluetoothManagerService(  892): registerStateChangeCallback+
D/BluetoothMap( 5162): Create BluetoothMap proxy object
D/BluetoothManagerService(  892): registerStateChangeCallback+
E/BluetoothMap( 5162): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  892): Registered receivers: 11
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK,
D/BluetoothManagerService(  892): Registered receivers: 12
D/BluetoothManagerService(  892): registerStateChangeCallback+
D/BluetoothSap( 5162): BluetoothSap() call bindService
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  892): Registered receivers: 13
W/ContextImpl( 5162): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1862 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/BluetoothPbap( 5162): BluetoothPbap()
D/BluetoothManagerService(  892): registerStateChangeCallback+
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  892): Registered receivers: 14
E/WifiDataStallTracker(  892): DATA_MONITOR_POLL false Token 2
D/LocalBluetoothProfileManager( 5162): LocalBluetoothProfileManager construction complete
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/DockEventReceiver( 5162): finishStartingService: stopping service
D/BluetoothInputDevice( 5162): Proxy object connected
,D/HidProfile( 5162): Bluetooth service connected
,E/wpa_supplicant( 1374): wlan0: BLACKLIST CLEAR ,
D/wpa_supplicant( 1374): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush,
D/wpa_supplicant( 1374): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush,
D/wpa_supplicant( 1374): wlan0: BSS: Remove id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1374): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush
D/wpa_supplicant( 1374): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1374): wlan0: Cancelling scan request
D/wpa_supplicant( 1374): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1374): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  892): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=30 dispatchEvent: BLACKLIST CLEAR 
D/WifiMonitor(  892): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  892): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
,D/WifiMonitor(  892): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48
D/WifiMonitor(  892): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
D/WifiMonitor(  892): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=35 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
D/wpa_supplicant( 1374): Remove interface wlan0 from radio phy0
,I/WVCdm   (  466): CdmEngine::OpenSession
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
I/WVCdm   (  466): Level3 Library Sep 25 2014 17:10:03
D/PMS     (  892): releaseWL(dc41db7): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothAdapter( 5162): 506653807: getState(). Returning 13
D/PMS     (  892): releaseWL(1863b21d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
D/BluetoothPan( 5162): BluetoothPAN Proxy object connected
I/ActivityManager(  892): Killing 4420:com.google.android.gms:car/u0a25 (adj 15): empty #17
D/PanProfile( 5162): Bluetooth service connected
D/SapServerProfile( 5162): Bluetooth service connected
D/Process (  892): killProcessQuiet, pid=4420
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL false Token 15 num clients 9
,W/WVCdm   (  466): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/ActivityManager(  892): Recipient 4420,
,D/HtcBtWidget_BTWidgetProvider( 5208): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5208): updateWidget(context) for widget: 
,D/DrmWidevineDash(  466): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13,
D/DrmWidevineDash(  466): Service_Initialize: starts!
D/QSEECOMAPI: (  466): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  466): App is not loaded in QSEE
,D/wpa_supplicant( 1374): nl80211: Remove monitor interface: refcount=0,
D/wpa_supplicant( 1374): netlink: Operstate: ifindex=22 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
D/Tethering(  892): interfaceLinkStateChanged wlan0, false
D/Tethering(  892): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false,
D/wpa_supplicant( 1374): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 1374): nl80211: Unsubscribe mgmt frames handle 0x3062e8e9 (mode change)
,I/wpa_supplicant( 1374): htc_wext_command_deinit +
,I/wpa_supplicant( 1374): htc_wext_command_deinit -
D/QSEECOMAPI: (  466): Loaded image: APP id = 3
I/wpa_supplicant( 1374): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor(  892): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  892): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1374): Control interface directory not empty - leaving it behind
D/WifiMonitor(  892): Disconnecting from the supplicant, no more events
D/wpa_supplicant( 1374): p2p0: Removing interface p2p0
D/wpa_supplicant( 1374): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1374): TDLS: Tear down peers
D/wpa_supplicant( 1374): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1374): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1374): netlink: Operstate: ifindex=23 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 1374): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1374): EAPOL: External notification - portValid=0
E/WifiStateMachine(  892): handleMessage: E msg.what=147458
E/WifiStateMachine(  892): processMsg: SupplicantStoppingState
E/WifiStateMachine(  892):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 36 0
E/WifiStateMachine(  892): Supplicant connection lost
D/DrmWidevineDash(  466): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  466): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb46d8000
E/DrmWidevineDash(  466): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb46d8000
,D/DrmWidevineDash(  466): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  466): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  466): hlos api version =  9
D/DrmWidevineDash(  466): tz api version =  8
D/DrmWidevineDash(  466): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  466): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  466): OEMCrypto_IsKeyboxValid: ends! returns 0,
D/WVCdm   (  466): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  466): OEMCrypto_OpenSession: starts! SID=0xb4900948
D/DrmWidevineDash(  466): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  466): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  466): OEMCrypto_GetRandom: starts! randomData=0xb85be458, dataLength=8,
D/DrmWidevineDash(  466): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  466): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb857f6b8, wrapped_rsa_key_length=1280,
,D/DrmWidevineDash(  466): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  466): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  466): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  466): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  466): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  466): OEMCrypto_GetDeviceID: starts! deviceID=0xb85c3a80, idLength=0xbea520d8
,D/DrmWidevineDash(  466): OEMCrypto_GetDeviceID: ends! returns 0,
D/DrmWidevineDash(  466): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  466): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  466): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  466): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  466): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  466): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  466): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  466): hlos api version =  9
D/DrmWidevineDash(  466): tz api version =  8
D/DrmWidevineDash(  466): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  466): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  466): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  466): PrepareKeyRequest: nonce=2879848386
D/DrmWidevineDash(  466): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8593068
D/DrmWidevineDash(  466): message_length=1591, signature=0xb858dae0, signature_length=3198492860
,D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,I/bt-btif ( 3054): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3054): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3054): mProfilesStarted : true supportedProfileServices.length : 6
,D/Process (  892): killProcessQuiet, pid=4420
I/ActivityManager(  892): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5229 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
,D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10025/pid_4420/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  466): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  466): CdmEngine::CloseSession
D/DrmWidevineDash(  466): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  466): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  466): L3 Terminate.
D/DrmWidevineDash(  466): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  466): Service_Uninitialize: starts!
D/QSEECOMAPI: (  466): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  466): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  466): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  466): OEMCrypto_Terminate: ends! returns 0
,D/Process (  892): killProcessQuiet, pid=4352
I/ActivityManager(  892): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/com.htc.videohub.engine.LiteLRBroadcastReceiver: pid=5247 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  892): Killing 4352:com.android.vending/u0a75 (adj 15): empty #17
E/cutils-trace( 5182): Error opening trace file: No such file or directory (2)
,I/ActivityManager(  892): Recipient 4352,
,D/CustomizationManager( 5182): ====startRecUseTime====,
D/htc.customization.log.level( 5182):  is 
W/CustomizationLogLevel( 5182): Level value is invalid, use default level 2
,I/wpa_ctrl(  892): [wpa_ctrl_close] ctrl=0xb8ffc5c0,
I/wpa_ctrl(  892): [wpa_ctrl_close] ctrl=0xb8ffc6c8
,I/WVCdm   (  466): CdmEngine::OpenSession,
W/libprocessgroup(  892): failed to open /acct/uid_10075/pid_4352/cgroup.procs: No such file or directory
I/WVCdm   (  466): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  466): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/Process (  892): killProcessQuiet, pid=4352
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/HeadsetService( 3054): Received stop request...Stopping profile...
E/WifiStateMachine(  892): setWifiState: disabled
D/WifiStateMachine(  892): Enter handleNetworkDisconnect
E/WifiStateMachine(  892): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$11600 - processMessage
E/WifiStateMachine(  892): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  892): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  892): Exit handleNetworkDisconnect
D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
E/WifiStateMachine(  892): [MLHD] Error! unhandled message 6 { when=-233ms what=147458 arg1=36 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  892): acquireWL(c08274a): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 892 1000 null
E/WifiStateMachine(  892): transitionTo: destState=InitialState
D/WIFI_ICON( 1121): updateWifiState: WIFI_STATE_CHANGED disabled
E/WifiStateMachine(  892): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  892): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WIFI_ICON( 1121): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  892): invokeExitMethods: SupplicantStoppingState
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  892): moveTempStackToStateStack: i=0,j=1
D/WirelessDisplayService(  892): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
E/WifiStateMachine(  892): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WirelessDisplayService(  892): WIFI Trun OFF
E/WifiStateMachine(  892): invokeEnterMethods: InitialState
D/WirelessDisplayService(  892): getDiscoveryDongleList
E/WifiTrafficPoller(  892): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a401c50
D/HeadsetStateMachine( 3054): Exit Disconnected: -1
I/IntentController( 1121): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
I/IntentController( 1121): receive(android.net.wifi.STATE_CHANGE,1,false)
W/Settings( 4558): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothHeadset(  892): Proxy object disconnected
D/BluetoothHeadset(  892): Proxy object disconnected
W/Settings( 1727): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DrmWidevineDash(  466): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  466): Service_Initialize: starts!
D/QSEECOMAPI: (  466): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  466): App is not loaded in QSEE
D/A2dpService( 3054): Received stop request...Stopping profile...
D/A2dpStateMachine( 3054): Exit Disconnected: -1
W/ResourcesManager( 5247): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/BluetoothHeadset( 1121): Proxy object disconnected
I/QuickSettingMiniLite( 1121): btListener.disconnect:HEADSET
D/BluetoothHeadset( 3697): Proxy object disconnected
D/NGFService( 3697): BluetoothHeadset onServiceDisconnected: main,
,W/ResourceType( 5247): ResTable_typeSpec entry count inconsistent: given 1, previously 1426,
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a401c50
D/BluetoothA2dp(  892): Proxy object disconnected
,D/HidService( 3054): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a401c50
D/BluetoothAdapterState( 3054): Stopping profile services that were post enabled
D/QSEECOMAPI: (  466): Loaded image: APP id = 3
D/DrmWidevineDash(  466): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  466): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb46d8000
,E/DrmWidevineDash(  466): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb46d8000
V/AlarmManager(  892): sending alarm PendingIntent{1baab7d8: PendingIntentRecord{14c44731 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=49343, Int=0
D/DrmWidevineDash(  466): OEMCrypto_Initialize: ends! returns 0
,D/WifiService(  892): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
D/DrmWidevineDash(  466): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  466): hlos api version =  9
D/DrmWidevineDash(  466): tz api version =  8
D/DrmWidevineDash(  466): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  466): OEMCrypto_IsKeyboxValid: starts!
,D/BluetoothA2dp( 3697): Proxy object disconnected
D/NGFService( 3697): BluetoothA2dp onServiceDisconnected: main
D/HealthService( 3054): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a401c50
D/DrmWidevineDash(  466): OEMCrypto_IsKeyboxValid: ends! returns 0,
D/WVCdm   (  466): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  466): OEMCrypto_OpenSession: starts! SID=0xb4900948
D/DrmWidevineDash(  466): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  466): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  466): OEMCrypto_GetRandom: starts! randomData=0xb8571c78, dataLength=8
D/DrmWidevineDash(  466): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  466): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb857f1c8, wrapped_rsa_key_length=1280
D/PanService( 3054): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a401c50
D/DrmWidevineDash(  466): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  466): CdmEngine::QueryKeyControlInfo
D/BluetoothInputDevice( 5162): Proxy object disconnected
D/HidProfile( 5162): Bluetooth service disconnected
D/WISPrService( 5162): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothPan( 5162): BluetoothPAN Proxy object disconnected
D/PanProfile( 5162): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 3054): Cleaning up Bluetooth Handsfree Interface...
W/WVCdm   (  466): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  466): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  466): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  466): OEMCrypto_GetDeviceID: starts! deviceID=0xb85c3ac0, idLength=0xb2de5718
W/BluetoothHeadsetServiceJni( 3054): Cleaning up Bluetooth Handsfree callback object
D/WISPrService( 5162): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/BtGatt.DebugUtils( 3054): handleDebugAction() action=null
D/BtGatt.GattService( 3054): Received stop request...Stopping profile...
D/BtGatt.GattService( 3054): stop()
,D/BtGatt.AdvertiseManager( 3054): advertise clients cleared,
,D/PMS     (  892): acquireWL(26296e16): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a401c50
I/ActivityManager(  892): Killing 4619:com.google.android.youtube/u0a186 (adj 15): empty #17
D/DrmWidevineDash(  466): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  466): OEMCrypto_SupportsUsageTable: starts!
W/BluetoothHidServiceJni( 3054): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 3054): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3054): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3054): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3054): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3054): Cleaning up Bluetooth PAN callback object
D/DrmWidevineDash(  466): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  466): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  466): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  466): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  466): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  466): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  466): hlos api version =  9
D/DrmWidevineDash(  466): tz api version =  8
D/DrmWidevineDash(  466): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  466): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  466): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  466): PrepareKeyRequest: nonce=3491004887
D/DrmWidevineDash(  466): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8593068
D/DrmWidevineDash(  466): message_length=1626, signature=0xb85936c8, signature_length=3000915708
D/BluetoothAdapterState( 3054): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3054): Setting state to 10
,I/BluetoothAdapterState( 3054): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  892): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  892): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  892): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  892): Broadcasting onBluetoothStateChange(false) to 14 receivers.
I/BluetoothAdapterState( 3054): Entering OffState
D/BluetoothHeadset( 1400): Proxy object disconnected
D/BluetoothPhoneService( 1400): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 1400): Proxy object disconnected
D/BluetoothHeadset( 1400): Proxy object disconnected
I/BluetoothAdapterState( 3054): notBluetoothOff()
,D/BluetoothSap( 5162): onBluetoothStateChange on: false
V/BluetoothSapService( 3054): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@3eb6693f
D/BluetoothHeadset( 1400): onBluetoothStateChange: up=false
D/BluetoothHeadset( 3697): onBluetoothStateChange: up=false
D/BluetoothHeadset(  892): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1400): onBluetoothStateChange: up=false
D/BluetoothPbap( 5162): onBluetoothStateChange: up=false
D/BluetoothHeadset(  892): onBluetoothStateChange: up=false
D/BluetoothA2dp(  892): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1121): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3697): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1400): onBluetoothStateChange: up=false
I/QuickSettingWifi( 1121): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
I/QuickSettingWifi( 1121): receive.wifiConnect:false wifiAPname:null elapse:0
D/BluetoothInputDevice( 5162): onBluetoothStateChange: up=false
D/Process (  892): killProcessQuiet, pid=4619
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,I/ActivityManager(  892): Recipient 4619
,D/CustomizationManager( 5182):  Read ACC file spent 0.124 (s)
,D/CIDMapFileReader( 5182): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__102
W/BluetoothHeadset( 1121): Proxy not attached to service
I/QuickSettingMiniLite( 1121): updateLiteState:no connect device!
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__203
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__405,
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__304
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__J15
,D/CIDMapFileReader( 5182): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 5182): Parsing tag item name = HTC__002
,V/CustomizationCIDLoader( 5182): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 5182): Parsing tag category name = system
,I/CustomizationCIDLoader( 5182): Parsing tag category name = application
,I/CustomizationCIDLoader( 5182): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5182): Parsing tag category name = Settings
,I/CustomizationCIDLoader( 5182): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5182): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5182): Parsing tag category name = ACC
D/DrmWidevineDash(  466): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  466): CdmEngine::CloseSession
,D/DrmWidevineDash(  466): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  466): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  466): L3 Terminate.
D/DrmWidevineDash(  466): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  466): Service_Uninitialize: starts!
D/QSEECOMAPI: (  466): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  466): QSEECom_shutdown_app, app_id = 3,
D/CustomizationManager( 5182):  Read CID file spent 0.167 (s)
D/DrmWidevineDash(  466): Service_Uninitialize: ends! returns 0x0
D/CustomizationManager( 5182):  All configurations done spent 0.167 (s)
D/DrmWidevineDash(  466): OEMCrypto_Terminate: ends! returns 0
,E/ActTriggerJNI( 5182): open library fail.,
,D/PackageManager(  892): deletePackageAsUser: pkg=com.example.hello, pid=5182, uid=2000 userid=0,
,D/Process (  892): killProcessQuiet, pid=4619,
W/libprocessgroup(  892): failed to open /acct/uid_10186/pid_4619/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/PMS     (  892): releaseWL(26296e16): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/BluetoothMap( 5162): onBluetoothStateChange: up=false
I/ActivityManager(  892): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
E/BluetoothMap( 5162): 
E/BluetoothMap( 5162): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@149cd6b2
E/BluetoothMap( 5162): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5162): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1914)
E/BluetoothMap( 5162): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5162): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 5162): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5162): 	at android.os.Binder.execTransact(Binder.java:454)
I/ActivityManager(  892): Killing 4403:com.example.hello/u0a380 (adj 0): stop com.example.hello
D/BluetoothPan( 5162): onBluetoothStateChange on: false
D/Process (  892): killProcessQuiet, pid=4403
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,I/WindowState(  892): WIN DEATH: Window{3d0dae14 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  892): Recipient 4403
D/WifiService(  892): Client connection lost with reason: 4
,W/ActivityManager(  892): Force removing ActivityRecord{37e391d8 u0 com.example.hello/.MainActivity t27}: app died, no saved state
,W/PackageSettings(  892): Skipping PackageSetting{1c152d4c com.test.thalitest/10373} due to missing metadata
,E/MP-Decision( 2354): Update arg "0 380 380 380".
,E/MP-Decision( 2354): Update arg "0 400 400 400".
,D/PMS     (  892): acquireWL(354655a2): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 WorkSource{10054 com.htc.sense.hsp},
D/PMS     (  892): acquireWL(3a560233): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1727 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  892): releaseWL(3a560233): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  892): acquireWL(31bca9f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1727 10025 null
D/PMS     (  892): releaseWL(31bca9f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/ActivityManager(  892): Spurious death for ProcessRecord{8bbab69 4403:com.example.hello/u0a380}, curProc for 4403: null,
D/BluetoothManagerService(  892): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  892): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 4974): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3e213979
D/BluetoothAdapter( 4974): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1121): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@219e1bee
D/BluetoothAdapter( 1121): onBluetoothServiceDown: done
D/BluetoothAdapter( 5162): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@fddd603
D/BluetoothAdapter( 5162): onBluetoothServiceDown: done
D/BluetoothAdapter( 3054): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@2c92ad7c
D/BluetoothAdapter( 3054): onBluetoothServiceDown: done
D/BluetoothAdapter(  892): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@18591dae
D/BluetoothAdapter(  892): onBluetoothServiceDown: done
D/BluetoothAdapter( 3697): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3a0fc0bd
D/BluetoothAdapter( 3697): onBluetoothServiceDown: done
D/BluetoothAdapter( 1727): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@380e5815
D/BluetoothAdapter( 1727): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1425): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3a0fc0bd
D/BluetoothAdapter( 1425): onBluetoothServiceDown: done
D/BluetoothAdapter( 1400): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@8f25a2d
D/BluetoothAdapter( 1400): onBluetoothServiceDown: done
D/BluetoothManagerService(  892): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@18591dae mBinding = false
D/BluetoothManagerService(  892): Sending unbind request.
D/BluetoothManagerService(  892): Bluetooth State Change Intent: 13 -> 10
I/ActivityManager(  892): Force stopping com.example.hello appid=10380 user=0: pkg removed
,D/MdUtils ( 5229): [577.1.] subId list: (0)r0 (s0)-1,
,D/PMS     (  892): releaseWL(354655a2): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{10054 com.htc.sense.hsp},
I/art     ( 1778): Explicit concurrent mark sweep GC freed 9081(481KB) AllocSpace objects, 5(405KB) LOS objects, 49% free, 4MB/8MB, paused 540us total 24.670ms
,D/PMS     (  892): acquireWL(8445ea1): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
I/bt-btif ( 3054): HAL bt_hal_cbacks->thread_evt_cb
D/MdScPhnSt( 5229): [577.1.]  listen tmrbb8
,I/FeedHostManager( 1459): [onResume]
D/PMS     (  892): releaseWL(8445ea1): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
I/FeedProviderManager( 1459): onResume
I/SocialFeedProvider( 1459): +onResume
I/SocialFeedProvider( 1459): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1459): -onResume
I/ConnectivityHelper( 1459): [getCurrentConnectionType] no network connection
,I/WebViewFactory( 5132): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 3054): System.exit called, status: 0,
D/DotMatrix( 1211): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1211): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1211): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/PMS     (  892): acquireWL(25066f20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1727 10025 WorkSource{10025 com.google.android.gms}
D/NGFService( 3697): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  892): releaseWL(25066f20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
D/NGFService( 3697): Bluetooth Adapter: OFF
D/LocalBluetoothProfileManager( 5162): setBluetoothStateOff
,W/BluetoothEventManager( 5162): unregister mProfileBroadcastReceiver fail
D/AccTypeManager( 1577): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/IntentController( 1121): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/ActivityManager(  892): Recipient 3054
D/MdUtils ( 5229): [577.2.] subId list: (0)r0 (s0)-1
,D/StatusBarManagerService(  892): setSystemUiVisibility(0x700)
D/Process (  892): killProcessQuiet, pid=3054
D/StatusBarManagerService(  892): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/StatusBarManagerService(  892): hiding MENU key
,W/ResourcesManager( 1400): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1459): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
,I/Prism.ItemManager( 1459): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4891): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4891): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1577): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
D/PhoneApp( 1400): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ExternalAccountType( 1577): Unsupported attribute readOnly
D/TetherPref( 5162): persistRestoreBluetoothState false,
W/PackageManager(  892): Unable to load service info ResolveInfo{17f7a5a com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  892): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  892): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
W/PackageManager(  892): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
W/PackageManager(  892): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  892): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  892): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  892): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  892): 	,at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  892): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  892): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  892): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  892): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  892): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  892): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  892): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
W/PackageManager(  892): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,D/BluetoothAdapter( 1121): 652421411: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1121): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/MdUtils ( 5229): [577.3.] subId list: (0)r0 (s0)-1
,I/ActivityManager(  892): Process com.android.bluetooth (pid 3054) has died,
W/ActivityManager(  892): Scheduling restart of crashed service com.android.bluetooth/.ftp.BluetoothFtpService in 1000ms
W/ActivityManager(  892): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 10999ms
W/ActivityManager(  892): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 20999ms
,I/BroadcastQueue(  892): Schedule to resend BroadcastRecord{1bc6c236 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=892 callingUid=1000} for ResolveInfo{e915537 com.android.bluetooth/.opp.BluetoothOppReceiver m=0x108000} of com.android.bluetooth,
E/cutils-trace( 5301): Error opening trace file: No such file or directory (2)
I/dex2oat ( 5301): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=43 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/InputMethodManagerService(  892): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
,D/JobSchedulerService(  892): Receieved: android.intent.action.PACKAGE_REMOVED,
,W/InputMethodManagerService(  892): Got RemoteException sending setActive(false) notification to pid 4403 uid 10380
,D/StatusBarManagerService(  892): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  892): Enable input method client, pid=1459
,I/LibraryLoader( 5132): Time to load native libraries: 1 ms (timestamps 9758-9759),
,I/LibraryLoader( 5132): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5132): Binding Chromium to main looper Looper (main, tid 1) {74eb6a4},
,I/LibraryLoader( 5132): Expected native library version number "",actual native library version number ""
I/ActivityManager(  892): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=5308 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a,
D/TaskPersister(  892): removeObsoleteFile: deleting file=27_task.xml
,I/chromium( 5132): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/dex2oat ( 5301): dex2oat took 72.755ms (threads: 4)
W/ResourcesManager( 5308): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
I/Adreno-EGL( 5102): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 5102): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5102): Build Date: 12/11/14 Thu
I/Adreno-EGL( 5102): Local Branch: 
I/Adreno-EGL( 5102): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 5102): Local Patches: NONE
I/Adreno-EGL( 5102): Reconstruct Branch: NOTHING
D/Tethering(  892): interfaceRemoved wlan0
E/Tethering(  892): attempting to remove unknown iface (wlan0), ignoring
E/WifiTrafficPoller(  892): TRAFFIC_STATS_POLL false Token 16 num clients 8
W/ResourcesManager(  892): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/MdScDataSum( 5229): [577.1.] summary 99:p3 ignore
I/BrowserStartupController( 5132): Initializing chromium process, singleProcess=true
D/AdapterServiceConfig( 5308): Adding HeadsetService
D/AdapterServiceConfig( 5308): Adding A2dpService
D/AdapterServiceConfig( 5308): Adding HidService
D/AdapterServiceConfig( 5308): Adding HealthService
D/AdapterServiceConfig( 5308): Adding PanService
D/AdapterServiceConfig( 5308): Adding GattService
W/art     ( 5132): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5132): ApplicationContext is null in ApplicationStatus
,I/SensorManager( 1727): unregisterListenerImpl++: listener = com.google.android.location.collectionlib.cm@2e992a22
,W/SensorService(  892): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  892): disable: get sensor name = Accelerometer Sensor
W/SensorService(  892): pid=1727, uid=10025
W/SensorService(  892): Active sensors: size = 3
W/SensorService(  892): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  892): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  892): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  892): SensorService::listenerSensor++: mName = com.google.android.location.collectionlib.cm@2e992a22, eanble = 0, strlen(mName) = 53
W/SensorService(  892): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  892): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@9fa3978
W/SensorService(  892): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@243b2712
W/SensorService(  892): Listener[2] = com.htc.smartdim.sensor_eye@3495c443
W/SensorService(  892): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  892): acquireWL(245411c3): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
,D/PMS     (  892): releaseWL(245411c3): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  892): releaseWL(3d6fbfb2): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
D/MdUtils ( 5229): [577.1.4.] subId list: (0)r0 (s0)-1
D/PMS     (  892): acquireWL(15072a40): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
,W/System.err(  892): java.lang.Throwable: stack dump
D/PMS     (  892): releaseWL(1228adbd): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
D/BluetoothManagerService(  892): Message: MESSAGE_REGISTER_ADAPTER
D/PMS     (  892): releaseWL(15072a40): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3fb6eabe:true
,D/PMS     (  892): acquireWL(295c071f): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1727 10025 null
W/System.err(  892): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  892): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  892): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  892): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 5308): 535997005: getState() :  mService = null. Returning STATE_OFF
E/BluetoothMasService( 5308): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/PMS     (  892): releaseWL(1587df67): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
,D/MdUtils ( 5229): [577.4.] subId list: (0)r0 (s0)-1,
D/BluetoothMasService( 5308): Add permission for SmsProvider.
,V/BluetoothMasService( 5308): Starting MAS instances
,D/BluetoothAdapter( 5308): 535997005: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  892): releaseWL(295c071f): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
I/MailMessageReceiver( 5308): reg:com.android.bluetooth.btservice.AdapterApp@7904213 with com.htc.util.mail.MailMessageReceiver@1a401c50
D/StatusBarManagerService(  892): setSystemUiVisibility(0xc0000700)
I/MailManager( 5308): MailManager contruct! com.htc.util.mail.MailMessageReceiver@1a401c50,
,D/StatusBarManagerService(  892): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/EmailUtils( 5308): Manager Instance is not NULL
D/StatusBarManagerService(  892): hiding MENU key
,W/chromium( 5132): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5132): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5132): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/MdUtils ( 5229): [577.5.] subId list: (0)r0 (s0)-1
,I/Adreno-EGL( 5132): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 5132): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5132): Build Date: 12/11/14 Thu
I/Adreno-EGL( 5132): Local Branch: 
I/Adreno-EGL( 5132): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 5132): Local Patches: NONE
I/Adreno-EGL( 5132): Reconstruct Branch: NOTHING
,D/MdUtils ( 5229): [577.6.] subId list: (0)r0 (s0)-1,
,I/ActivityManager(  892): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5332 uid=10065 gids={50065, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  892): interfaceLinkStateChanged p2p0, false
,D/Tethering(  892): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  892): WiFiDisplay: getWifidisplayApEnabled=false
,I/art     (  892): Explicit concurrent mark sweep GC freed 38339(2MB) AllocSpace objects, 3(113KB) LOS objects, 33% free, 17MB/26MB, paused 1.403ms total 343.546ms
,D/Tethering(  892): interfaceRemoved p2p0,
E/Tethering(  892): attempting to remove unknown iface (p2p0), ignoring
,D/NfcHandover( 1425): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false,
,D/HtcAdjCursorFactory( 5332): Set CursorWindow size to: 4194304 KB, Tid: 5347,
,D/EmailUtils( 5308): ============NULL aList========
V/EmailUtils( 5308): <-getEmailAccountIdList
V/BluetoothMasService( 5308): onCreate: mIsEmailEnabled: true
,D/Process (  892): killProcessQuiet, pid=4741,
I/ActivityManager(  892): Killing 4741:com.google.android.partnersetup/u0a28 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
W/AudioManagerAndroid( 5132): Requires BLUETOOTH permission
,I/ActivityManager(  892): Recipient 4741
,D/BluetoothFtpService( 5308): ACTION_STATE_CHANGED: state: 13mHasStarted: false,
,D/BluetoothMasReceiver( 5308): Bluetooth STATE CHANGED to 13
D/Process (  892): killProcessQuiet, pid=4741
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10028/pid_4741/cgroup.procs: No such file or directory
,V/BluetoothSapReceiver( 5308): SapReceiver onReceive 
,V/BluetoothSapReceiver( 5308): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5308):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 5308): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 5308): Sap Service onCreate
,V/BluetoothSapService( 5308): initBinder
D/AuthorizationBluetoothService( 1778): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothSapService( 5308): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@2c92ad7c
V/BluetoothSapService( 5308): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 5308): state: 13
,V/BluetoothPbapReceiver( 5308): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5308): ***********state = 10
D/PMS     (  892): acquireWL(1dba90f7): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5162 1000 null
,W/ContextImpl( 5162): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 ,
D/Process (  892): killProcessQuiet, pid=4706
I/ActivityManager(  892): Killing 4706:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  892): Recipient 4706,
D/WifiService(  892): Client connection lost with reason: 4
,I/Adreno-EGL( 5102): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU (),
I/Adreno-EGL( 5102): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5102): Build Date: 12/11/14 Thu
I/Adreno-EGL( 5102): Local Branch: 
I/Adreno-EGL( 5102): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 5102): Local Patches: NONE
I/Adreno-EGL( 5102): Reconstruct Branch: NOTHING
,I/Adreno-EGL( 5102): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 5102): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5102): Build Date: 12/11/14 Thu
I/Adreno-EGL( 5102): Local Branch: 
I/Adreno-EGL( 5102): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 5102): Local Patches: NONE
I/Adreno-EGL( 5102): Reconstruct Branch: NOTHING
,I/CheckinRequestBuilder( 4442): Classify the device as Phone.,
,W/OpenGLRenderer( 1459): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/Process (  892): killProcessQuiet, pid=4706
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10089/pid_4706/cgroup.procs: No such file or directory,
,D/PMS     (  892): releaseWL(1dba90f7): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  892): acquireWL(2ae421cd): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5162 1000 null
,I/NSApplication( 5132): Starting up...
,D/DockEventReceiver( 5162): finishStartingService: stopping service
D/PMS     (  892): releaseWL(2ae421cd): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/HtcBtWidget_BTWidgetProvider( 5208): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 5208): updateWidget(context) for widget: 
,I/ActivityManager(  892): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5373 uid=10102 gids={50102, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4780:com.google.android.gm/u0a115 (adj 15): empty #17,
D/Process (  892): killProcessQuiet, pid=4780
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  892): Recipient 4780
,I/ActivityManager(  892): Killing 4891:com.htc.sense.news/u0a77 (adj 15): empty #17
,D/Process (  892): killProcessQuiet, pid=4891
,D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  892): Recipient 4891
,D/Process (  892): killProcessQuiet, pid=4891
W/libprocessgroup(  892): failed to open /acct/uid_10077/pid_4891/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/Process (  892): killProcessQuiet, pid=4780
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10115/pid_4780/cgroup.procs: No such file or directory
,D/BluetoothMasReceiver( 5308): Bluetooth STATE CHANGED to 10
V/BluetoothMasService( 5308): onDestroy: mIsEmailEnabled: true
,V/BluetoothSapReceiver( 5308): SapReceiver onReceive 
V/BluetoothSapReceiver( 5308): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5308):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 5308): startService = false
,D/AuthorizationBluetoothService( 1778): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/libc    ( 4442): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4442): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4442): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4442): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4442): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4442): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  461): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  461): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  461): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  461): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4442): [NET] android_getaddrinfo_proxy-, NODATA
E/CheckinTask( 4442): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
E/SharedPreferencesImpl( 4442): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
,I/CheckinService( 4442): Checking schedule, now: 1448306479066 next: 1448306489063
,I/CheckinService( 4442): active receiver: disabled
I/PackageManager(  892):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4442, uid=10025, userID:0
F/PackageManager(  892): Unable to backup user packages state file, current changes will be lost at reboot
,D/PMS     (  892): releaseWL(36e6950b): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms}
,E/DropBoxManagerService(  892): Can't write: system_server_wtf
E/DropBoxManagerService(  892): java.io.FileNotFoundException: /data/system/dropbox/drop27.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  892): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  892): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  892): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  892): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
E/DropBoxManagerService(  892): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12642)
E/DropBoxManagerService(  892): 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12446)
,E/DropBoxManagerService(  892): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12418)
E/DropBoxManagerService(  892): 	at android.os.Handler.handleCallback(Handler.java:739)
E/DropBoxManagerService(  892): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService(  892): 	at android.os.Looper.loop(Looper.java:155)
E/DropBoxManagerService(  892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  892): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/DropBoxManagerService(  892): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  892): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  892): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  892): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  892): 	... 13 more
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{d5605cd u0 com.htc.HTCSpeaker/.NGFService}
,E/WifiStateMachine(  892): handleMessage: X
,D/PMS     (  892): releaseWL(c08274a): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  892): handleMessage: E msg.what=131155
E/WifiStateMachine(  892): processMsg: InitialState
E/WifiStateMachine(  892):  InitialState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1709] from screen [on:0 period:902500439] gl hn rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  892): processMsg: DefaultState
,E/WifiStateMachine(  892):  DefaultState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:902500439] gl hn rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  892): handleMessage: X
,D/Process (  892): killProcessQuiet, pid=4597
I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5396 uid=10176 gids={50176, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  892): Killing 4597:com.htc.sense.mms/u0a67 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4597
,D/Process (  892): killProcessQuiet, pid=4597,
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10067/pid_4597/cgroup.procs: No such file or directory
,W/ResourcesManager( 5396): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  892): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=5418 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4938:com.google.android.music:main/u0a167 (adj 15): empty #17
D/Process (  892): killProcessQuiet, pid=4938
,D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/Prism.ItemManager( 1459): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1459): loadItems() com.htc.launcher.pageview.WidgetManager@2a278d97 +
I/Prism.WidgetManager( 1459): onLoadItems() +
I/ActivityManager(  892): Recipient 4938
D/MediaRouterService(  892): Client com.google.android.music (pid 4938): Died!
,W/ResourcesManager( 1459): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Process (  892): killProcessQuiet, pid=4938
,D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  892): failed to open /acct/uid_10167/pid_4938/cgroup.procs: No such file or directory
,W/ResourcesManager( 5418): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  892): acquireWL(4aca7ef): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5418 10072 null
,D/Process (  892): killProcessQuiet, pid=4974,
I/ActivityManager(  892): Killing 4974:com.fitbit.FitbitMobile/u0a23 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/PMS     (  892): acquireWL(2a8882fc): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5418 10072 null
,I/ActivityManager(  892): Recipient 4974,
,D/Process (  892): killProcessQuiet, pid=4974,
W/libprocessgroup(  892): failed to open /acct/uid_10023/pid_4974/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/PMS     (  892): releaseWL(4aca7ef): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 5418): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference,
W/System.err( 5418): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5418): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
D/PMS     (  892): releaseWL(2a8882fc): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null,
W/System.err( 5418): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5418): 	at android.os.Looper.loop(Looper.java:155),
W/System.err( 5418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 5418): stopSelfResult true
,D/PMS     (  892): acquireWL(1d67da): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5418 10072 null,
,D/PMS     (  892): acquireWL(3c58d2e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5418 10072 null,
,W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  892): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5441 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/PMS     (  892): releaseWL(1d67da): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 5418): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5418): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5418): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 5418): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5418): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PMS     (  892): releaseWL(3c58d2e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 5418): stopSelfResult true
,E/SharedPreferencesImpl( 5188): Couldn't rename file /data/user/0/com.htc.mobiledata/shared_prefs/sp_BOOTUP.xml to backup file /data/user/0/com.htc.mobiledata/shared_prefs/sp_BOOTUP.xml.bak
,D/MdScBootUi( 5229): [612.1.2.] boot 99,
D/MdScBoot( 5229): [612.1.] 30@-192054 -> 40
,D/MdUtils ( 5229): [612.1.2.] subId list: (0)r0 (s0)-1,
,W/HtcWrapAdjustableCursorFactory( 5441): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 5441): onCreate,
,V/GetPrviateResource( 5441): GetPrviateResource
,V/GetPrviateResource( 5441): GetPrviateResource
,E/Prism.WidgetManager( 1459): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1459): onLoadItems() -
I/Prism.ItemManager( 1459): loadItems() com.htc.launcher.pageview.WidgetManager@2a278d97 -
,D/MessageCustFlag( 5441): sense_version=6.0
,D/BTAccessoryUtil( 5441): createReceiver
,E/SQLiteLog( 1459): (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=73] disk I/O error
E/SQLiteDBG( 1459): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xb8e8a8e0
,D/BTAccessoryUtil( 5441): registerReceiver return intent = null
,E/AndroidRuntime( 1459): FATAL EXCEPTION: TaskWorker
E/AndroidRuntime( 1459): Process: com.htc.launcher, PID: 1459
E/AndroidRuntime( 1459): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1459): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1459): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
E/AndroidRuntime( 1459): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1459): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1459): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1459): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1459): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 1459): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 1459): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1459): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1459): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1459): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1459): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1459): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/MessageCustFlag( 5441): sku_id=99
,D/HtcBuildUtils( 5441): getRATByHtcTelephonyCapability:1
,W/SystemReader( 5441): Cannot find qct_8960_interface, use default value instead
,E/ActivityManager(  892): App crashed! Process: com.htc.launcher,
D/ErrorReport(  892): HtcErrorReportManager Begin---add error logs to dropbox
,W/System.err(  892): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  892): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  892): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  892): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  892): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  892): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  892): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
,W/System.err(  892): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  892): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  892): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  892): 	at libcore.io.Posix.open(Native Method)
,W/System.err(  892): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  892): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  892): 	... 12 more
,D/MmsConfig( 5441): packageName: com.htc.vvm.att does not exist
D/MessageCustFlag( 5441): sku_id=99
,D/MessagingShortcutReceiver( 5441): keep hiding shortcut bubble,
,D/MessagingShortcut( 5441): updateMsgShortcut, msg count> -1,
,D/SettingsManager( 5441): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1a401c50
,W/System.err(  892): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  892): ,	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  892): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154),
W/System.err(  892): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  892): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  892): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:309)
W/System.err(  892): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
W/System.err(  892): ,	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
W/System.err(  892): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
W/System.err(  892): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
W/System.err(  892): ,	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  892): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/System.err(  892): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  892): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  892): 	at libcore.io.Posix.open(Native Method)
W/System.err(  892): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  892): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  892): 	... 14 more
D/MessagingShortcut( 5441): After query: 0
,D/MessagingShortcut( 5441): mPresentUnreadCount: -1
D/MessageUtils( 5441): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 5441): setMsgShortcutDrawable> 0, false
,W/System.err(  892): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  892): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  892): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
,W/System.err(  892): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  892): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  892): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:310)
W/System.err(  892): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
W/System.err(  892): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
W/System.err(  892): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
,W/System.err(  892): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
W/System.err(  892): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  892): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/System.err(  892): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  892): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  892): 	at libcore.io.Posix.open(Native Method)
W/System.err(  892): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  892): 	at libcore.io.IoBridge.open(IoBridge.java:442)
,W/System.err(  892): 	... 14 more
,D/MessagingShortcut( 5441): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2,
,D/DotMatrix( 1211): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1211): [EventService] reorderNotification, total:0
D/DotMatrix( 1211): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1211): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/ErrorReport(  892): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  892): java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1448306480003.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  892): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  892): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
E/ErrorReport(  892): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  892): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  892): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  892): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  892): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  892): 	... 4 more
,W/ActivityManager(  892):   Force finishing activity com.htc.launcher/.Launcher
D/PMS     (  892): acquireWL(60e183d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 892 1000 null
,W/ActivityManager(  892): Can't addPackageDependency on system process
,D/StatusBarManagerService(  892): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  892): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  892): hiding MENU key
,I/FeedHostManager( 1459): [onPause]
I/FeedProviderManager( 1459): onPause
I/FeedHostManager( 1459): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@380e5815
I/SocialFeedProvider( 1459): +onPause
I/SocialFeedProvider( 1459): -onPause
,D/TodoTaskshortcut( 5418): update TASK shortcut>
D/HtcSystemUPManager(  892): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,I/ActivityManager(  892): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0
,E/SQLiteDatabase( 5418): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 5418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5418): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5418): 	at com.htc.task.dm.DBProvider.query(DBProvider.java:505)
E/SQLiteDatabase( 5418): 	at com.htc.task.APICProviderDecorator.query(APICProviderDecorator.java:348)
E/SQLiteDatabase( 5418): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5418): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5418): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5418): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5418): 	at com.htc.shared.orm.Query.fetch(Query.java:415)
E/SQLiteDatabase( 5418): 	at com.htc.task.TaskShortcut.generateIcon(TaskShortcut.java:48)
E/SQLiteDatabase( 5418): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:140)
E/SQLiteDatabase( 5418): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5418): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 5418): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 5418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteOpenHelper( 5418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5418): 	at com.htc.task.dm.DBProvider.query(DBProvider.java:505)
E/SQLiteOpenHelper( 5418): 	at com.htc.task.APICProviderDecorator.query(APICProviderDecorator.java:348)
E/SQLiteOpenHelper( 5418): ,	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5418): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5418): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteOpenHelper( 5418): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteOpenHelper( 5418): 	at com.htc.shared.orm.Query.fetch(Query.java:415)
E/SQLiteOpenHelper( 5418): 	at com.htc.task.TaskShortcut.generateIcon(TaskShortcut.java:48)
E/SQLiteOpenHelper( 5418): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:140)
E/SQLiteOpenHelper( 5418): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 5418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5418): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 5418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/OrientationManager( 1459): [release]
,I/Prism.IndicatorPagedVi_( 1459): IndicatorPagedView.nCapability with type count = 1 and capability = 20
,W/SQLiteOpenHelper( 5418): Opened MyDB.db in read-only mode
,I/ActivityManager(  892): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5469 uid=10037 gids={50037, 9997} abi=armeabi-v7a
,I/art     (  472): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 171us total 12.310ms
,D/Process (  892): killProcessQuiet, pid=4304,
I/ActivityManager(  892): Killing 4304:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  892): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 433us total 13.256ms,
,I/ActivityManager(  892): Recipient 4304,
E/ActivityThread( 1459): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@1d461e8 that was originally registered here. Are you missing a call to unregisterReceiver()?,
E/ActivityThread( 1459): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@1d461e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1459): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1459): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1459): 	,at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1459): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1459): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1459): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1459): 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:709)
E/ActivityThread( 1459): 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
E/ActivityThread( 1459): 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
E/ActivityThread( 1459): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
E/ActivityThread( 1459): 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1459): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
,E/ActivityThread( 1459): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1459): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1459): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1459): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1459): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1459): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/qdoverlay(  365): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  365): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  365): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  365): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  365): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  365): MdpCtrl close error in unset
I/art     (  472): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 167us total 12.080ms
,D/Process (  892): killProcessQuiet, pid=4304,
W/libprocessgroup(  892): failed to open /acct/uid_10011/pid_4304/cgroup.procs: No such file or directory
D/Process (  892): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PhoneApp( 1400): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1400): -- N1 =0
D/PhoneApp( 1400): -- N2 =0
,D/PhoneApp( 1400): -- N3 =0
,E/qdoverlay(  365): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  365): MdpCtrl close error in unset
E/qdoverlay(  365): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  365): MdpCtrl close error in unset
,E/qdoverlay(  365): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,E/qdoverlay(  365): MdpCtrl close error in unset
,E/ActivityThread( 1459): Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@1a04d91b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1459): android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@1a04d91b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 1459): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread( 1459): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread( 1459): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
E/ActivityThread( 1459): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
E/ActivityThread( 1459): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread( 1459): 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
E/ActivityThread( 1459): 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:689)
E/ActivityThread( 1459): 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
E/ActivityThread( 1459): 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
E/ActivityThread( 1459): 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
E/ActivityThread( 1459): 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
E/ActivityThread( 1459): 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
E/ActivityThread( 1459): 	at com.htc.launcher.Laun,cherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
E/ActivityThread( 1459): 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
E/ActivityThread( 1459): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/ActivityThread( 1459): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/ActivityThread( 1459): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1459): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1459): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
