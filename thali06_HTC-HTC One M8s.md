#### Test 57321924b5e4f25_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  969): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  969): handleMessage: E msg.what=131143
E/WifiStateMachine(  969): processMsg: ConnectedState
E/WifiStateMachine(  969):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2495 rssi=-70 f=2412 sc=60 link=43 tx=2.3, 0.0, 0.0  rx=1.9 fiv=90000 [on:0 tx:0 rx:0 period:1318] from screen [on:0 period:-2114102217]
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:2495 rssi=-70 f=2412 sc=60 link=43 tx=2.3, 0.0, 0.0  rx=1.9 fiv=90000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2114102216]
E/WifiStateMachine(  969): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.28 rxSuccessRate=1.85 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-70
E/WifiStateMachine(  969): WifiStateMachine CMD_START_SCAN with age=11348 interval=90000 maxinterval=300000
E/WifiStateMachine(  969): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  969): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  969): has c0:ff:d4:d3:aa:48 freq=2412 age=1325 ?=true
E/WifiStateMachine(  969): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1306): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1306): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1306): wpa_supplicant_scan enter
D/wpa_supplicant( 1306): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1306): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1306): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1306): WPS:  * Request Type
D/wpa_supplicant( 1306): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1306): WPS:  * UUID-E
D/wpa_supplicant( 1306): WPS:  * Primary Device Type
D/wpa_supplicant( 1306): WPS:  * RF Bands (3)
D/wpa_supplicant( 1306): WPS:  * Association State
D/wpa_supplicant( 1306): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1306): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1306): WPS:  * Manufacturer
D/wpa_supplicant( 1306): WPS:  * Model Name
D/wpa_supplicant( 1306): WPS:  * Model Number
D/wpa_supplicant( 1306): WPS:  * Device Name
D/wpa_supplicant( 1306): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1306): P2P: * P2P IE header
D/wpa_supplicant( 1306): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1306): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1306): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1306): wlan0: Add radio work 'scan'@0x5587a12680
D/wpa_supplicant( 1306): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1306): wlan0: Starting radio work 'scan'@0x5587a12680 after 0.000044 second wait
D/wpa_supplicant( 1306): wlan0: nl80211: scan request
D/wpa_supplicant( 1306): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1306): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1306): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1306): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1306): wlan0: Own scan request started a scan in 0.000108 seconds
I/wpa_supplicant( 1306): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  969): [1,453,879,811,130 ms] noteScanstart no scan source
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  969): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  969): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  969): handleMessage: X
--------- beginning of system
D/PMS     (  969): acquireWL(3f7d852e): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1000}
D/WifiDisplayAdapter(  969): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  969):     Client/Owner: Client
D/WifiDisplayAdapter(  969):     GroupId: 
D/WifiDisplayAdapter(  969):     Passphrase: 
D/WifiDisplayAdapter(  969):     SessionId: 0
D/WifiDisplayAdapter(  969):     IP Address: }
V/AlarmManager(  969): sending alarm PendingIntent{2f21e198: PendingIntentRecord{37b98df1 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1453879811124, Int=20000
D/PMS     (  969): releaseWL(3f7d852e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/wpa_supplicant( 1306): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1306): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1306): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1306): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1306): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1306): wlan0: Scan completed in 0.040670 seconds
D/wpa_supplicant( 1306): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1306): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1306): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1306): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1306): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-70
I/wpa_supplicant( 1306): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 1306): [NULL] 00:37:b7:9d:3e:73 freq=5500 level=-88
I/wpa_supplicant( 1306): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-85
D/wpa_supplicant( 1306): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1306): BSS: last_scan_res_used=5/32
D/wpa_supplicant( 1306): wlan0: Scan-only results received
D/wpa_supplicant( 1306): wlan0: Radio work 'scan'@0x5587a12680 done in 0.041761 seconds
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  969): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  969): handleMessage: E msg.what=147461
E/WifiStateMachine(  969): processMsg: ConnectedState
E/WifiStateMachine(  969):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
E/WifiStateMachine(  969):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
D/WifiStateMachine(  969): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1306): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  969): [1,453,879,811,177 ms] noteScanEnd no scan source
W/ContextImpl(  969): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1306): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  969): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@236393eb sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  969): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  969): NG700 c0:ff:d4:d3:aa:48 rssi=-70 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  969): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  969): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  969):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-70 freq=2412
E/WifiAutoJoinController (  969): Gonzos 38:f8:89:11:e9:11 rssi=-76 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  969): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-85 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P] is not scored
E/WifiAutoJoinController (  969): FunBox2-3E72 00:37:b7:9d:3e:73 rssi=-88 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  969): ageScanResultsOut delay 40000 size 5 now 1453879811179
E/WifiAutoJoinController (  969): newSupplicantResults size=5 known=1 true
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1306): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  969): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  969): ssid=NG700
E/WifiAutoJoinController (  969): id=0
E/WifiAutoJoinController (  969): mode=station
E/WifiAutoJoinController (  969): pairwise_cipher=CCMP
E/WifiAutoJoinController (  969): group_cipher=CCMP
E/WifiAutoJoinController (  969): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  969): wpa_state=COMPLETED
E/WifiAutoJoinController (  969): ip_address=192.168.1.130
E/WifiAutoJoinController (  969): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  969): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  969): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  969): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  969): attemptAutoJoin good candidate seen, bumped soft -> status=0 "NG700"WPA_PSK rssi=(-70,-127) num=(1,0)
E/WifiAutoJoinController (  969): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  969): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-70 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  969): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  969): Done attemptAutoJoin status=0
E/WifiConfigStore(  969):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  969): handleMessage: X
,I/Prism.ItemManager( 1579): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1579): loadItems() com.htc.launcher.pageview.WidgetManager@36eb8698 +
I/Prism.WidgetManager( 1579): onLoadItems() +
E/cutils-trace( 6803): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6803): ====startRecUseTime====
D/htc.customization.log.level( 6803):  is 
W/CustomizationLogLevel( 6803): Level value is invalid, use default level 2
E/Prism.WidgetManager( 1579): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1579): onLoadItems() -
I/Prism.ItemManager( 1579): loadItems() com.htc.launcher.pageview.WidgetManager@36eb8698 -
D/CustomizationManager( 6803):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 6803): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6803): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6803): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6803): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6803): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6803): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6803): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6803): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6803): Parsing tag category name = system
I/CustomizationCIDLoader( 6803): Parsing tag category name = application
I/CustomizationCIDLoader( 6803): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6803): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6803): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6803): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6803): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6803): add string-array item, value = 42507
I/CustomizationCIDLoader( 6803): add string-array item, value = 21902
I/CustomizationCIDLoader( 6803): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6803): add string-array item, value = 23420
I/CustomizationCIDLoader( 6803): add string-array item, value = 22299
I/CustomizationCIDLoader( 6803): add string-array item, value = 24002
I/CustomizationCIDLoader( 6803): add string-array item, value = 23210
I/CustomizationCIDLoader( 6803): add string-array item, value = 23205
I/CustomizationCIDLoader( 6803): add string-array item, value = 23806
I/CustomizationCIDLoader( 6803): add string-array item, value = 23430
I/CustomizationCIDLoader( 6803): add string-array item, value = 23408
I/CustomizationCIDLoader( 6803): add string-array item, value = 27205
I/CustomizationCIDLoader( 6803): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6803): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6803):  Read CID file spent 0.102 (s)
D/CustomizationManager( 6803):  All configurations done spent 0.102 (s)
I/ActivityManager(  969): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6803 on display 0
D/PMS     (  969): acquireHCC(3699e8cf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 969 1000 null
D/PMS     (  969): acquireHCC(391625c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 969 1000 null
D/PMS     (  969): acquireWL(37f642eb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 969 1000 null
I/AnimationUtil(  969): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1579): [onPause]
I/FeedProviderManager( 1579): onPause
I/FeedHostManager( 1579): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@16cc765c
I/SocialFeedProvider( 1579): +onPause
I/SocialFeedProvider( 1579): -onPause
W/HtcSystemUPManager(  969): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  969): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6821 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/TrimMemoryManager( 1579): [trimMemory] 20
E/WifiTrafficPoller(  969): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  969):  packet count Tx=210 Rx=257
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  969): notifying of data activity 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/StatusBarManagerService(  969): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
D/PhoneApp( 1543): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1543): -- N1 =0
D/PhoneApp( 1543): -- N2 =0
D/PhoneApp( 1543): -- N3 =0
,I/WebViewFactory( 6821): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6821): Time to load native libraries: 9 ms (timestamps 9934-9943)
I/LibraryLoader( 6821): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6821): Binding Chromium to main looper Looper (main, tid 1) {dd3f8ae}
I/LibraryLoader( 6821): Expected native library version number "",actual native library version number ""
I/chromium( 6821): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6821): Initializing chromium process, singleProcess=true
W/art     ( 6821): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6821): ApplicationContext is null in ApplicationStatus
W/chromium( 6821): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6821): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6821): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6821): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6821): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6821): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6821): Local Branch: 
I/Adreno-EGL( 6821): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6821): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6821):                  d74aa161a12b9c6fc6332151
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  969): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b7a5378:true
W/System.err(  969): java.lang.Throwable: stack dump
W/System.err(  969): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  969): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  969): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6821): 32174522: getState(). Returning 12
W/art     ( 6821): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6821): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6821): CordovaWebView is running on device made by: HTC
W/art     ( 6821): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6821): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  969): Explicit concurrent mark sweep GC freed 33800(1868KB) AllocSpace objects, 4(272KB) LOS objects, 33% free, 16MB/25MB, paused 1.608ms total 173.176ms
W/chromium( 6821): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6821): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6821): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1fd3a25b, mServedView=org.apache.cordova.engine.SystemWebView{35f60af8 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@24ea6bd1
I/InputMethodManagerService(  969): Disable input method client, pid=1579
D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  969): Enable input method client, pid=6821
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/PMS     (  969): releaseWL(37f642eb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  969): Displayed com.test.thalitest/.MainActivity: +837ms
W/BindingManager( 6821): Cannot call determinedVisibility() - never saw a connection for the pid: 6821
W/XT9_C   ( 1401): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1401): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1401): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1401): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/JsMessageQueue( 6821): Set native->JS mode to OnlineEventsBridgeMode
E/WifiStateMachine(  969): handleMessage: E msg.what=131155
E/WifiStateMachine(  969): processMsg: ConnectedState
E/WifiStateMachine(  969):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-70 f=2412 sc=60 link=43 tx=2.3, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:1682] from screen [on:0 period:-2114100532] gl hn u24 rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-70 f=2412 sc=60 link=43 tx=2.3, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-2114100527] gl hn u24 rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  969):  get link layer stats 0
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1306): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1306): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  969): fetchRssiLinkSpeedAndFrequencyNative RSSI = -69 abnormalRssiCnt = 0 newLinkSpeed = 57
E/WifiStateMachine(  969): fetchRssiLinkSpeedAndFrequencyNative rssi=-69 linkspeed=57
E/WifiConfigStore(  969): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-69 "NG700"WPA_PSK
E/WifiStateMachine(  969): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.14 txretriesrate=0.00 rxrate=1.93 userTriggerdPenalty0
E/WifiStateMachine(  969):  good link -> stuck count =0
E/WifiStateMachine(  969):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  969):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  969): RSSI current: 3 new: -69, 3
E/WifiStateMachine(  969): handleMessage: X
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  969): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  969):  packet count Tx=210 Rx=258
E/WifiTrafficPoller(  969): notifying of data activity 1
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/jxcore_app_log( 6821): JniHelper::setJavaVM(0xaab148f8), pthread_self() = -1411200904
I/chromium( 6821): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  969): releaseHCC(3699e8cf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  969): releaseHCC(391625c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6821): Initializing JXcore engine,
W/jxcore-log( 6821): JXcore engine is ready
,W/jxcore-log( 6821): Starting JXcore engine,
,E/WifiTrafficPoller(  969): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  969):  packet count Tx=210 Rx=258
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  969): notifying of data activity 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 6821): Platform android,
W/jxcore-log( 6821): 
W/jxcore-log( 6821): Process ARCH arm
W/jxcore-log( 6821): 
,I/jxcore-log( 6821): JXcore Cordova bridge is ready!,
I/jxcore-log( 6821): 
W/jxcore-log( 6821): JXcore engine is started
,I/jxcore-log( 6821): Toggling radios to true,
I/jxcore-log( 6821): 
,D/BluetoothAdapter( 6821): enable(): BT is already enabled..!
,D/WifiService(  969): New client listening to asynchronous messages,
E/WifiTrafficPoller(  969): ADD_CLIENT: 7
,D/WifiManager( 6821): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
W/Settings:Agent(  969): MONITOR_LOG
D/WifiService(  969): setWifiEnabled: true pid=6821, uid=10366
W/Settings:Agent(  969): name: wifi_on,
E/WifiService(  969): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  969): value: 2
I/WifiService(  969): isSprintWifiRestricted(): false
W/Settings:Agent(  969): >> traceCallingStack()
I/WifiService(  969): isMdmWifiRestricted(): false
W/Settings:Agent(  969): Process.myPid(): 969
W/Settings:Agent(  969): Process.myTid(): 990
W/Settings:Agent(  969): Process.myUid(): 1000
W/Settings:Agent(  969): 
W/Settings:Agent(  969): 
W/System.err(  969): java.lang.Throwable: stack dump
,W/System.err(  969): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  969): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,W/System.err(  969): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  969): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  969): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  969): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  969): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  969): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  969): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
,W/System.err(  969): ,	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  969): 
W/Settings:Agent(  969): << traceCallingStack(): 14(ms)
D/WifiController(  969): handleMessage: E msg.what=155656
D/WifiManager( 6821): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): handleMessage: X
D/WifiManager( 6821): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  969): handleMessage: E msg.what=131145
,E/WifiStateMachine(  969): processMsg: ConnectedState
E/WifiStateMachine(  969):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/jxcore-log( 6821): Radios toggled
I/jxcore-log( 6821): 
D/wpa_supplicant( 1306): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1306): wlan0: Cancelling scan request
D/wpa_supplicant( 1306): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1306): TDLS: Tear down peers
D/wpa_supplicant( 1306): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6821): My device name is: HTC-HTC One M8s
I/jxcore-log( 6821): 
,D/wpa_supplicant( 1306): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1306): wlan0: Deauthentication notification
D/wpa_supplicant( 1306): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1306): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1306): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1306): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1306): enter disconnect check
I/wpa_supplicant( 1306): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
,E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  969): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  969): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  969): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1306): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1306): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  969): interfaceLinkStateChanged wlan0, false
D/Tethering(  969): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  969): interfaceLinkStateChanged wlan0, false
D/Tethering(  969): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  969): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  969): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  969): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  969): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  969): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  969): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  969): acquireWL(108506c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 969 1000 null
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1306): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1306): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1306): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1306): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1306): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5587a0ff88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1306):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1306): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1306): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1306): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1306): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1306): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1306): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1306): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1306): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1306): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1306): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1306): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1306): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1306): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1306): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1306): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1306): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1306): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1306): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1306): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/WifiDisplayAdapter(  969): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  969):     Client/Owner: Client
D/WifiDisplayAdapter(  969):     GroupId: 
D/WifiDisplayAdapter(  969):     Passphrase: 
D/WifiDisplayAdapter(  969):     SessionId: 0
D/WifiDisplayAdapter(  969):     IP Address: }
D/wpa_supplicant( 1306): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  969): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  969): handleMessage: new destination call exit/enter
E/WifiStateMachine(  969): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  969): invokeExitMethods: ConnectedState
E/WifiStateMachine(  969): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  969): release()
E/WifiStateMachine(  969): PerfLock released for exiting ConnectedState
D/WifiMonitor(  969): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  969): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/TetherSettings( 5917): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5917): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5917): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5917): Cust_ConnectToPC   : spcsc>false
D/        ( 5917): Cust_ConnectToPC   : IPT>true
D/        ( 5917): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5917): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5917): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5917): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5917): onReceive : android.net.conn.TETH,ER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  969): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  969): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  969): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  969): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  969): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  969): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1306): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1306): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1306): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1306): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1306): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1306): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1306): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/ContextImpl( 5917): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5917): setISNotification
E/WifiStateMachine(  969): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1306): Power_Mode_Type mode = 0
I/wpa_supplicant( 1306): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  969): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1306): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  969): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/SmartNS_Utility( 5917): usb_cable_connect = 1
D/WifiDataStallTracker(  969): setDhcpActive: false
D/SmartNS_Utility( 5917): usb_denied = 0
V/NativeCrypto( 1876): Read error: ssl=0x55b69fe360: I/O error during system call, Connection timed out
I/SmartNS_PSService( 5917): usb notificaiton:true
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/PMS     (  969): acquireWL(9328ff9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
,V/NativeCrypto( 1876): SSL shutdown failed: ssl=0x55b69fe360: I/O error during system call, Broken pipe,
D/PMS     (  969): releaseWL(108506c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  969): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  969): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  969): setDetailed state send new extra info<unknown ssid>
V/NetworkPolicy(  969): updateNetworkEnabledLocked()
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  969): updateNotificationsLocked()
E/WifiStateMachine(  969): NetworkAgent != null
D/ConnectivityService(  969): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  969): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  969):  packet count Tx=210 Rx=258
I/ActionCombine( 5917): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/WifiDataStallTracker(  969): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  969): stopDataStallAlarm 
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false),
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 12
,D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiDataStallTracker(  969): ENABLE_DATA_MONITOR_POLL false Token 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  969): releaseWL(9328ff9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): DefaultState{ when=-6ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  969): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  969): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  969): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  969): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1306): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1306): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1306): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1306): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1306): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1306): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1306): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  969): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  969): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): Forcing reevaluation
E/WifiStateMachine(  969): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  969):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  969): Start Disconnecting Watchdog 1
E/WifiStateMachine(  969): handleMessage: X
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  969): handleMessage: E msg.what=131146
E/WifiStateMachine(  969): processMsg: DisconnectingState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): Validated
E/WifiStateMachine(  969):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !CMD_RECONNECT 0 0
,W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1306): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1306): wlan0: Selecting BSS from priority group 565
D/wpa_supplicant( 1306): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-52 wps
D/wpa_supplicant( 1306): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1306): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1306): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-70 wps
D/wpa_supplicant( 1306): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1306): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1306): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1306):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1306): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1306): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x5587a11c00  current_ssid=0x0
,D/wpa_supplicant( 1306): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1306): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1306): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1306): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1306): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1306): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1306): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1306): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1306): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1306): wlan0: Add radio work 'connect'@0x5587a12680
D/wpa_supplicant( 1306): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1306): wlan0: Starting radio work 'connect'@0x5587a12680 after 0.000136 second wait
I/wpa_supplicant( 1306): check if in concurrent case
I/wpa_supplicant( 1306): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  969): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=37 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=147460
E/WifiStateMachine(  969): processMsg: DisconnectingState
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  969):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=112485
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  969): processMsg: ConnectModeState
D/SmartNS_Utility( 5917): usb_cable_connect = 1
E/WifiStateMachine(  969):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=112485
E/WifiStateMachine(  969): ConnectModeState: Network connection lost 
E/WifiStateMachine(  969): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  969): handleMessage: new destination call exit/enter
E/WifiStateMachine(  969): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  969): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  969): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  969): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  969): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  969): DisconnectedState call setCountryCode()
,E/WifiStateMachine(  969):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/SmartNS_Utility( 5917): usb_denied = 0
I/SmartNS_PSService( 5917): usb notificaiton:true
,D/wpa_supplicant( 1306): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1306): wlan0: Cancelling scan request
D/wpa_supplicant( 1306): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1306): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1306): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1306): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1306): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1306): RSN: PMKSA cache search - network_ctx=0x5587a11c00 try_opportunistic=0
D/wpa_supplicant( 1306): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1306): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1306): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1306): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1306): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1306): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1306): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1306): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1306): wlan0: WPA: using KEY_MGMT WPA-PSK
D/WifiDisplayAdapter(  969): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  969):     Client/Owner: Client
D/WifiDisplayAdapter(  969):     GroupId: 
D/WifiDisplayAdapter(  969):     Passphrase: 
D/WifiDisplayAdapter(  969):     SessionId: 0
D/WifiDisplayAdapter(  969):     IP Address: }
D/wpa_supplicant( 1306): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1306): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1306): wlan0: State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1306): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1306): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1306): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1306): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1306): nl80211: Unsubscribe mgmt frames handle 0x888888dd0f299989 (mode change)
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  969): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1306): nl80211: Subscribe to mgmt frames with non-AP handle 0x5587a11100
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=0104
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=040a
,D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=040b
D/WifiMonitor(  969): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=040c
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=040d
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=090a
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=090b
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=090c
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=090d
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=0409506f9a09
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=7f506f9a09
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=0801
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=040e
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=06
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=0a07
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=0a11
D/wpa_supplicant( 1306): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5587a11100 match=0a1a
D/wpa_supplicant( 1306): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1306):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306):   * freq=2412
D/wpa_supplicant( 1306):   * freq_hint=2412
D/wpa_supplicant( 1306):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1306):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1306):   * WPA Versions 0x2
D/wpa_supplicant( 1306):   * pairwise=0xfac04
D/wpa_supplicant( 1306):   * group=0xfac04
D/wpa_supplicant( 1306):   * akm=0xfac02
D/wpa_supplicant( 1306):   * Auth Type 0
D/wpa_supplicant( 1306): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5587a11c3a
D/wpa_supplicant( 1306): nl80211: Connect request send successfully
D/wpa_supplicant( 1306): wlan0: Setting authentication timeout: 10 sec 0 usec
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/wpa_supplicant( 1306): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1306): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1306): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1306): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1306): Ongoing scan action - reject new request
E/WifiStateMachine(  969): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
,E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131101
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
E/WifiStateMachine(  969):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  969): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  969): Default got CMD_TETHER_STATE_CHANGE
,E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=147462
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=112496  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  969): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  969): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=112497  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine(  969): handleMessage: X
D/WifiNetworkAgent(  969): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  969): handleMessage: E msg.what=131213
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState !CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112498
,E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112498
E/WifiStateMachine(  969): processMsg: DriverStartedState
,E/WifiStateMachine(  969):  DriverStartedState !CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112499
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
,E/WifiStateMachine(  969):  SupplicantStartedState !CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112500
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=147462
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=112501  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  969): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  969): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  969): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  969): NetworkAgent == null
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=112506  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/RemoteViews( 1221): reapply : com.android.settings 1 36
E/WifiStateMachine(  969): handleMessage: X
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
,D/SmartNS_NSReceiver( 5917): Tethered state change:false isNSOpening:false
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:4
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0,
,D/WISPrService( 5917): >>>>>WISPrService start isConnected = true<<<<<
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
,E/WifiTrafficPoller(  969): ADD_CLIENT: 8
D/WifiService(  969): New client listening to asynchronous messages
E/WifiStateMachine(  969): handleMessage: E msg.what=131131
E/WifiStateMachine(  969): processMsg: DisconnectedState
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  969):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine(  969): handleMessage: X
D/ConnectivityService(  969): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  969):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
D/ConnectivityService(  969):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  969): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  969): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  969):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Nat464Xlat(  969): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/usbnet  (  969): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  969): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  969): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  969): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  969):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  969): Removing idletimer
D/WIFI    (  969): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/SecurityController( 1221): onLost 100
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): Disconnected - quitting
W/WISPrService( 5917): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5917): trigger connection
D/WISPrService( 5917): continue
,D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5917): start DataConnection
D/PMS     (  969): acquireWL(11c6ed9f): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 969 1000 null
D/libc    ( 5917): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,D/libc    ( 5917): [NET] android_getaddrinfofornet-, err=8
D/CSLegacyTypeTracker(  969): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/libc    ( 5917): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/ConnectivityService(  969): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc    ( 5917): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5917): [NET] android_getaddrinfo_proxy+
D/libc    ( 5917): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5917): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  969): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6886 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/libc    ( 5917): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 5917): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  969): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6901 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/wpa_supplicant( 1306): Wireless event: cmd=0x8c02 len=271
,I/wpa_supplicant( 1306): WEXT: Custom wireless event: 'BEACONIEs='
D/ConnectivityService(  969): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  969): interfaceLinkStateChanged wlan0, false
E/ConnectivityService(  969): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  969): interfaceStatusChanged wlan0, false
V/NetworkPolicy(  969): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  969): acquireWL(d859416): PARTIAL_WAKE_LOCK  NetworkStats 0x1 969 1000 null
D/Tethering(  969): interfaceLinkStateChanged wlan0, false
E/ConnectivityService(  969): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  969): interfaceStatusChanged wlan0, false
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbDeviceManager(  969): [USBNET] bCheckSuppFunc: cdc_network
D/Tethering(  969): interfaceLinkStateChanged wlan0, false
D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/Tethering(  969): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  969): interfaceLinkStateChanged wlan0, true
D/Tethering(  969): interfaceStatusChanged wlan0, true
D/NetworkPolicy(  969): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
V/NetworkPolicy(  969): updateNetworkEnabledLocked()
D/wpa_supplicant( 1306): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
V/NetworkPolicy(  969): updateIfacesLocked()
D/wpa_supplicant( 1306): Wireless event: cmd=0x8c02 len=152
V/NetworkPolicy(  969): updateNotificationsLocked()
I/wpa_supplicant( 1306): WEXT: Custom wireless event: 'BEACONIEs='
D/DATA_ICON( 1221): dataConnected: false/false
D/wpa_supplicant( 1306): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1306): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1306): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1306): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
V/Tethering(  969): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1306): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1306): nl80211: Connect event
D/wpa_supplicant( 1306): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1306): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1306): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1306): wlan0: Association info event
D/wpa_supplicant( 1306): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1306): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1306): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1306): wlan0: freq=2412 MHz
D/wpa_supplicant( 1306): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1306): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1306): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1306): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1306): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/WISPrService( 5917): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/wpa_supplicant( 1306): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1306): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1306): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1306): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1306): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1306): TDLS: Remove peers on association
D/wpa_supplicant( 1306): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1306): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1306): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1306): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1306): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1306): EAPOL: enable timer tick
D/wpa_supplicant( 1306): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1306): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1306): wlan0: Cancelling scan request
I/wpa_supplicant( 1306): htc_wext_set_keepalive +
I/wpa_supplicant( 1306): htc_w,ext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1306): getPrivFuncNum +	
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1306): getPrivFuncNum -, cmd = 0x8bf6
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 1306): htc_wext_set_keepalive fnum = 0x8bf6
D/NetworkManagementService(  969): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/wpa_supplicant( 1306): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1306): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1306): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1306): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1306): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1306): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1306):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1306):   key_nonce - hexdump(len=32): e7 d7 d9 86 61 4a ce 9e 9b a3 1e 14 c9 1e cd 7b 4d 61 be 08 95 54 4d 47 de 7d 5b 63 a0 31 8f a5
D/wpa_supplicant( 1306):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1306):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1306):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1306):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1306): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1306): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1306): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  969): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  969): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  969): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  969): handleMessage: E msg.what=147462
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=40 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  969): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  969): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  969): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  969): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  969): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  969): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  969): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  969): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  969): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
E/WifiStateMachine(  969):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=112612  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  969): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  969): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=,7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  969): setDetailed state send new extra info0x
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiMonitor(  969): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/wpa_supplicant( 1306): WPA: Renewed SNonce - hexdump(len=32): 46 7f f5 7b ac df a8 06 f8 ac 37 a0 ec ed 68 7c b1 df 88 96 df 98 bf 1d 97 9c 8b 4e 86 b9 d2 93
D/wpa_supplicant( 1306): WPA: Nonce1 - hexdump(len=32): 46 7f f5 7b ac df a8 06 f8 ac 37 a0 ec ed 68 7c b1 df 88 96 df 98 bf 1d 97 9c 8b 4e 86 b9 d2 93
D/wpa_supplicant( 1306): WPA: Nonce2 - hexdump(len=32): e7 d7 d9 86 61 4a ce 9e 9b a3 1e 14 c9 1e cd 7b 4d 61 be 08 95 54 4d 47 de 7d 5b 63 a0 31 8f a5
D/wpa_supplicant( 1306): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1306): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1306): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1306): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1306): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1306): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1306): WPA: Derived Key MIC - hexdump(len=16): 1f 64 b2 ff 48 5d 24 d4 e3 30 58 d3 ca 04 21 0a
D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Tethering(  969): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  969): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  969): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/UsbnetService(  969): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  969): releaseWL(d859416): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=112618  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=147500
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  969):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  969): Enter handleAssociatedWithEvent
D/WifiStateMachine(  969): Associated
D/wpa_supplicant( 1306): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1306): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1306): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1306): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1306):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/PMS     (  969): acquireWL(1402f197): PARTIAL_WAKE_LOCK  NetworkStats 0x1 969 1000 null
D/wpa_supplicant( 1306):   key_nonce - hexdump(len=32): e7 d7 d9 86 61 4a ce 9e 9b a3 1e 14 c9 1e cd 7b 4d 61 be 08 95 54 4d 47 de 7d 5b 63 a0 31 8f a5
D/wpa_supplicant( 1306):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1306):   key_rsc - hexdump(len=8): b0 a6 00 00 00 00 00 00
D/wpa_supplicant( 1306):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1306):   key_mic - hexdump(len=16): 8c 18 9d b5 86 16 e7 a5 78 fa 26 77 7a 6e e3 31
D/wpa_supplicant( 1306): RSN: encrypted key data - hexdump(len=56): f1 71 6b 75 0c 6d 68 77 43 72 f2 7f 20 60 7b 7c 54 66 fa 83 87 dd 0d a2 0a d6 13 52 1f 46 18 9f ...
D/wpa_supplicant( 1306): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1306): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1306): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1306): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 cc be ...
D/wpa_supplicant( 1306): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1306): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1306): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1306): WPA: KCK - hexdump(len=16): [REMOVED]
V/NetworkPolicy(  969): updateNetworkEnabledLocked()
D/wpa_supplicant( 1306): WPA: Derived Key MIC - hexdump(len=16): f3 1d 30 ac 4d 9f 6c 70 0b 92 ba 7a 8d 15 e9 b7
V/NetworkPolicy(  969): updateNotificationsLocked()
D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1306): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1306): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5587a12390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1306): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1306): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1306):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  969): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  969): Exit handleAssociatedWithEvent
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=147462
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=112624  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  969): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  969): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/wpa_supplicant( 1306): EAPOL: External notification - portValid=1
E/WifiStateMachine(  969): setDetailed state send new extra info"NG700"
D/wpa_supplicant( 1306): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1306): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1306): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1306): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1306): WPA: RSC - hexdump(len=6): b0 a6 00 00 00 00
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1306): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x557a7b0e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1306): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1306): nl80211: KEY_SEQ - hexdump(len=6): b0 a6 00 00 00 00
D/wpa_supplicant( 1306):    broadcast key
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  969): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/WifiStateMachine(  969): NetworkAgent == null
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/wpa_supplicant( 1306): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1306): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1306): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1306): wlan0: Radio work 'connect'@0x5587a12680 done in 0.144267 seconds
I/wpa_supplicant( 1306): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1306): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  969): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=43 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  969): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  969): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=44 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  969): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1306): wlan0: Connect to SSID: NG700
D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1306): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1306): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
E/WifiStateMachine(  969): processMsg: ConnectModeState
I/wpa_supplicant( 1306): set send_ind_to_ndc = 0
I/wpa_supplicant( 1306): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1306): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1306): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1306): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1306): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1306): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1306): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1306): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1306): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1306): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1306): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1306): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1306): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/WifiStateMachine(  969):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=112629  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  969): handleMessage: X
D/wpa_supplicant( 1306): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiStateMachine(  969): handleMessage: E msg.what=131101
E/WifiStateMachine(  969): processMsg: DisconnectedState
D/WifiMonitor(  969): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=46 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  969): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  969): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: FOUR_WAY_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  969): interfaceLinkStateChanged wlan0, true
D/Tethering(  969): interfaceStatusChanged wlan0, true
D/WifiMonitor(  969): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  969):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  969):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  969): [MLHD] enter handleMediaLinkEvent DefaultState
D/PMS     (  969): releaseWL(1402f197): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiStateMachine(  969): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  969): handleMessage: X
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  969): handleMessage: E msg.what=147462
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=112639  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  969): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  969): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  969): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  969):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=112639  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
V/NetworkPolicy(  969): updateNetworkEnabledLocked()
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: FOUR_WAY_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
V/NetworkPolicy(  969): updateNotificationsLocked()
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=147459
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112640
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112641
E/WifiStateMachine(  969): Network connection established
D/WifiStateMachine(  969): fetchFrequency(), freq = 2412
E/WifiStateMachine(  969): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  969): NetworkAgent == null
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/art     (  457): Explicit concurrent mark sweep GC freed 8643(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 269us total 31.703ms
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 19
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  969): transitionTo: destState=ObtainingIpState
D/WifiDisplayAdapter(  969): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  969):     Client/Owner: Client
D/WifiDisplayAdapter(  969):     GroupId: 
D/WifiDisplayAdapter(  969):     Passphrase: 
D/WifiDisplayAdapter(  969):     SessionId: 0
D/WifiDisplayAdapter(  969):     IP Address: }
E/WifiStateMachine(  969): handleMessage: new destination call exit/enter
E/WifiStateMachine(  969): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  969): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  969): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  969): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  969): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  969): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  969): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  969): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  969): NetworkAgent == null
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/PMS     (  969): Going to sleep due to screen timeout (uid 1000)...
I/SensorManager(  969): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3fbfb66d
W/SensorService(  969): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  969): disable: get sensor name = Accelerometer Sensor
W/SensorService(  969): pid=969, uid=1000
W/SensorService(  969): Active sensors: size = 4
W/SensorService(  969): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  969): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  969): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  969): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  969): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3fbfb66d, eanble = 0, strlen(mName) = 91
W/SensorService(  969): Active Listeners: mActiveListeners.size() = 2
W/PMN     (  969): goingToSleep
W/SensorService(  969): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@32fdcc18
W/SensorService(  969): Listener[1] = com.htc.smartdim.sensor_eye@193e9f1
W/SensorService(  969): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/art     (  457): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 271us total 26.047ms
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
W/ResourcesManager( 6886): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
W/PMS     (  969): mWirelessDisplayManager is null
W/PMS     (  969): mWirelessDisplayManager is still null
E/WifiStateMachine(  969): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  969): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  969): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  969): Got NetworkAgent Messenger
E/WifiConfigStore(  969): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  969): QCOM Debug skip set_network part for security concern!
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1306): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/ConnectivityService(  969): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/wpa_supplicant( 1306): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/ConnectivityService(  969): NetworkAgent connected
D/wpa_supplicant( 1306): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
I/art     (  457): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 19.126ms
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1306): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1306): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1306): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1306): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  969): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  969): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  969): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  969): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  969): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  969): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1306): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1306): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1306): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/PMS     (  969): acquireWL(2fdb7d08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 969 1000 null
W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
D/wpa_supplicant( 1306): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1306): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1306): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1306): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
I/PMS     (  969): Sleeping (uid 1000)...
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/XAN-DPS (  969): prepareColorFade 1
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  969): Start Dhcp Watchdog 2
E/WifiStateMachine(  969): handleMessage: X
I/Adreno-EGL(  969): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  969): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  969): Build Date: 03/09/15 Mon
I/Adreno-EGL(  969): Local Branch: 
I/Adreno-EGL(  969): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  969): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  969):                  d74aa161a12b9c6fc6332151
,W/PMN     (  969): goingToSleep done
,E/WifiTrafficPoller(  969): TRAFFIC_STATS_POLL false Token 21 num clients 8
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 21
,E/WifiStateMachine(  969): handleMessage: E msg.what=147462
E/WifiStateMachine(  969): processMsg: ObtainingIpState
,E/WifiStateMachine(  969):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=112727  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  969): processMsg: L2ConnectedState
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  969):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=112727  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  969): processMsg: ConnectModeState,
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
D/AlarmManager(  969): ACTION_SCREEN_ON
E/WifiStateMachine(  969):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=112728  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  969): handleMessage: X
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
W/HtcSystemUPManager(  969): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/WISPrService( 5917): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5917): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  969): handleMessage: E msg.what=131155
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2051] from screen [on:0 period:-2114098458] gl hn u24 rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2114098457] gl hn u24 rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  969):  get link layer stats 0
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/AlarmManager(  969): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  969): [AlarmQueuing] done recovering
I/AlarmManager(  969): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  969): [AlarmQueuing] done EPS screen off alarm recovering
D/wpa_supplicant( 1306): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1306): environment dirty rate=0 [3][0][0],
E/WifiStateMachine(  969): fetchRssiLinkSpeedAndFrequencyNative RSSI = -70 abnormalRssiCnt = 0 newLinkSpeed = 43
D/PMS     (  969): releaseWL(2fdb7d08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/WifiStateMachine(  969): fetchRssiLinkSpeedAndFrequencyNative rssi=-70 linkspeed=43
D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
E/WifiConfigStore(  969): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-69 "NG700"WPA_PSK
E/WifiStateMachine(  969): calculateWifiScore freq=2412 speed=43 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=105.50 txretriesrate=0.00 rxrate=129.00 userTriggerdPenalty0
E/WifiStateMachine(  969):  good link -> stuck count =0
E/WifiStateMachine(  969):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  969):  isHighRSSI       ---> score=65
E/WifiStateMachine(  969): calculateWifiScore() report new score 60
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 22
,D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,E/WifiStateMachine(  969): handleMessage: X
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  969): handleMessage: E msg.what=131212,
D/ConnectivityService(  969): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
,E/WifiStateMachine(  969):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,E/WifiStateMachine(  969):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
,E/WifiStateMachine(  969):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
,D/WifiWatchdogStateMachine(  969): RSSI current: 3 new: -70, 3
,E/WifiStateMachine(  969):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  969): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  969): handleMessage: X
D/ConnectivityService(  969): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  969): handleMessage: E msg.what=196612
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=211,0,0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=211,0,0
D/WifiStateMachine(  969): handlePreDhcpSetup Held wake lock during DHCP
D/WifiDataStallTracker(  969): setDhcpActive: true
D/PMS     (  969): acquireWL(39ed6e87): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 969 1000 null
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiStateMachine(  969): handlePreDhcpSetup mBluetoothConnectionActive: false
D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/wpa_supplicant( 1306): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
,E/WifiStateMachine(  969): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  969): do suspend false
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 1306): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1306): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1306): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1306): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1306): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1306): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1306): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  969): Unexpected BatchedScanResults :null
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1306): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  969): noteBatchedScanstop()
E/WifiStateMachine(  969): handleMessage: X
D/WifiP2pService(  969): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d415c5e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  969): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d415c5e target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  969): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6934 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,E/WifiStateMachine(  969): handleMessage: E msg.what=131167
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
E/WifiStateMachine(  969):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  969):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 0 mUserWantsSuspendOpt=false state ObtainingIpState suppState:CompletedState
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
,D/wpa_supplicant( 1306): wlan0: Control interface command 'SET_SCREEN_ON 1'
,I/wpa_supplicant( 1306): SET_SCREEN_ON:On
I/wpa_supplicant( 1306): htc_wext_set_keepalive +
I/wpa_supplicant( 1306): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1306): getPrivFuncNum +	
I/wpa_supplicant( 1306): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1306): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1306): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1306): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1306): htc_wext_set_TX_TRACKING - ret = 0
D/WifiStateMachine(  969): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  969): handleScreenStateChanged Exit: true
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131154
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1306): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1306): environment dirty rate=0 [0][0][0]
I/CalendarProvider2( 6886): Created com.android.providers.calendar.CalendarAlarmManager@1e7d29(com.htc.providers.calendar.HtcCalendarProvider@dd3f8ae)
E/WifiStateMachine(  969): fetchRssiLinkSpeedAndFrequencyNative RSSI = -70 abnormalRssiCnt = 0 newLinkSpeed = 43
E/WifiStateMachine(  969): fetchRssiLinkSpeedAndFrequencyNative rssi=-70 linkspeed=43
E/WifiConfigStore(  969): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-69 "NG700"WPA_PSK
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131127,
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
,E/WifiStateMachine(  969):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131129
,E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1306): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1306): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  969): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=48 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  969): handleMessage: X
V/SRS_Proc(  440): ParamSet string: screen_state=on
E/audio_a2dp_hw(  440): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WifiController(  969): handleMessage: E msg.what=155650
D/WifiController(  969): processMsg: DeviceActiveState
,D/WifiController(  969): processMsg: StaEnabledState
,D/WifiController(  969): processMsg: DefaultState
,D/WifiController(  969): handleMessage: X
,D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/CalendarProvider2( 6886): wait start:true
D/NetworkPolicy(  969): updateScreenOn: false
V/NetworkPolicy(  969): updateIfacesLocked()
,D/NetworkManagementService(  969): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/GpsLocationProvider(  969): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  969): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/XAN-DPS (  969): prepareColorFade done
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false),
,D/XAN-DPS (  969): setBrightness to 0,
,I/SensorManager(  969): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@32fdcc18,
W/SensorService(  969): Following SensorService logs are not warning, just make sure they are printed
I/DisplayManagerService(  969): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS},
W/SensorService(  969): disable: get sensor name = CM32181 Light sensor
V/ActivityManager(  969): Display changed displayId=0
D/DotMatrix( 1333): [EventService]  onDisplayChanged: 0
W/ContextImpl( 5917): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
W/SensorService(  969): pid=969, uid=1000
D/PMS     (  969): acquireWL(20ec3838): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1836 10024 WorkSource{10024 com.google.android.gms}
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  969): acquireWL(31053011): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1836 10024 WorkSource{10024 com.google.android.gms}
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  969): releaseWL(20ec3838): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/SensorService(  969): Active sensors: size = 3
D/PMS     (  969): releaseWL(31053011): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
W/SensorService(  969): Accelerometer Sensor (handle=0x00000000, connections=1)
D/AlarmManager(  969): ACTION_SCREEN_OFF
W/SensorService(  969): CM36686 Proximity sensor (handle=0x00000004, connections=1)
I/AlarmManager(  969): [AlarmQueuing] screen off now: 
W/SensorService(  969): Significant Motion (handle=0x0000000d, connections=1)
I/AlarmManager(  969): [AlarmQueuing] data connection: true
W/SensorService(  969): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@32fdcc18, eanble = 0, strlen(mName) = 67
I/AlarmManager(  969): [AlarmQueuing] wifi connection: true
W/SensorService(  969): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  969): Listener[0] = com.htc.smartdim.sensor_eye@193e9f1
W/SensorService(  969): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/FlexNetS( 6886): updateSvcAllowedInSettings:false
D/CalendarProvider2( 6886): wait end:false
D/TetherSettings( 5917): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/WifiDisplayAdapter(  969): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  969):     Client/Owner: Client
D/WifiDisplayAdapter(  969):     GroupId: 
D/WifiDisplayAdapter(  969):     Passphrase: 
D/WifiDisplayAdapter(  969):     SessionId: 0
D/WifiDisplayAdapter(  969):     IP Address: }
D/        ( 5917): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5917): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5917): Cust_ConnectToPC   : spcsc>false
D/        ( 5917): Cust_ConnectToPC   : IPT>true
D/        ( 5917): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5917): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5917): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5917): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5917): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
I/SmartNS_Utility( 5917): setISNotification
D/DotMatrix( 1333): [EventService] mbHDMIConnect: false, mCoverOn:false
D/SmartNS_Utility( 5917): usb_cable_connect = 1
D/SmartNS_Utility( 5917): usb_denied = 0
I/SmartNS_PSService( 5917): usb notificaiton:true
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartNS_Utility( 5917): usb_cable_connect = 1
D/SmartNS_Utility( 5917): usb_denied = 0
I/SmartNS_PSService( 5917): usb notificaiton:true
E/WifiStateMachine(  9,69): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 5917): Tethered state change:false isNSOpening:false
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/FlexNetS( 6886): updateSvcAllowedInSettings:false
E/dhcpcd  ( 6963): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
D/FlexNetS( 6886): updateSvcAllowedInSettings:false
I/dhcpcd  ( 6963): version 5.5.6 starting
E/dhcpcd  ( 6963): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6963): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6963): autoip env[11]:autoip=DISABLE
I/RemoteViews( 1221): reapply : com.android.settings 1 36
I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/FlexNetS( 6886): updateSvcAllowedInSettings:false
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 23
D/WifiDataStallTracker(  969): stopDataStallAlarm 
E/WifiDataStallTracker(  969): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  969): handleMessage: E msg.what=131167
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
E/WifiStateMachine(  969):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  969):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 0 mUserWantsSuspendOpt=false state ObtainingIpState suppState:CompletedState
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1306): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1306): SET_SCREEN_ON:Off
I/wpa_supplicant( 1306): htc_wext_set_keepalive +
I/wpa_supplicant( 1306): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1306): getPrivFuncNum +	
I/wpa_supplicant( 1306): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1306): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1306): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1306): get_ip_address source addr = ffffffff
I/wpa_supplicant( 1306): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1306): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  969): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  969): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  969): handleScreenStateChanged Exit: false
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131154
E/WifiStateMachine(  969): processMsg: ObtainingIpState
I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@377b608f, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
E/WifiStateMachine(  969):  ObtainingIpState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  969): handleMessage: X
V/SRS_Proc(  440): ParamSet string: screen_state=off
E/audio_a2dp_hw(  440): adev_set_parameters: ERROR: set param called even when stream out is nul,l
W/SensorService(  969): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  969): enable: get sensor name = hTC Gesture Motion HIDI
D/WifiController(  969): handleMessage: E msg.what=155651
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
W/SensorService(  969): pid=1221, uid=10041
W/SensorService(  969): Active sensors: size = 4
W/SensorService(  969): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  969): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  969): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  969): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  969): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@377b608f, eanble = 1, strlen(mName) = 57
W/SensorService(  969): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  969): Listener[0] = com.htc.smartdim.sensor_eye@193e9f1
W/SensorService(  969): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@377b608f
W/SensorService(  969): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/NetworkPolicy(  969): updateScreenOn: false
V/NetworkPolicy(  969): updateIfacesLocked()
D/NetworkManagementService(  969): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/dhcpcd  ( 6963): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6963): wlan0: sending REQUEST (xid 0x6fbb5f2e), next in 1.31 seconds
D/GpsLocationProvider(  969): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] getTotalRam: 1842 Mb
I/ActivityManager(  969): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6975 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/MdScPhnSt( 6934): [b2d.2.]  listen tmrbb8
,D/ContactMessageStore( 1543): start background delete task...,
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1543): size: 0 , 0
,D/ContactMessageStore( 1543): Background delete complete
,D/PMS     (  969): acquireWL(51ca413): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1836 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(51ca413): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(20e1d650): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1836 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(20e1d650): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  969): Setting HAL interactive mode to false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  969): Excessive delay in setPowerMode(): 288ms
D/PMS     (  969): Setting HAL interactive mode to false done
,D/PMS     (  969): Setting HAL auto-suspend mode to true
D/PMS     (  969): Setting HAL auto-suspend mode done
,D/PMS     (  969): acquireWL(2154d049): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(2154d049): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  969): updateBatteryInfo
W/HtcSystemUPManager(  969): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/NotificationService(  969): plugged=true pluggin=true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/InputMethodManagerService(  969): screenObserver, isScreenOn=false
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
,D/UsbnetService(  969): onReceive BATTERY_CHANGED
I/InputMethodManagerService(  969): Disable input method client, pid=6821
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PMS     (  969): runPSCheck
D/HtcPowerSaver(  969): Checking...
I/HtcPowerSaver(  969): >> updateStatus
I/InputMethodManager( 6821): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{35f60af8 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@17c69085
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
,D/WifiController(  969): processMsg: DeviceActiveState
D/HABCtrl (  969): TPE algorithm. remove timeout.
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): << updateStatus
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  969): OOBE c monitor 11
,D/NfcService( 1557): ScreenObserver: OFF
,D/NfcService( 1557): applyRouting - 0
,D/PMS     (  969): acquireWL(2a091d4e): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1557 1027 null
D/NfcService( 1557): applyRouting -2
D/NfcService( 1557): applyRouting
D/NfcService( 1557): Ignore this applyRouting...
D/PMS     (  969): releaseWL(2a091d4e): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/RemoteViews( 1221): apply : com.htc.updater 1 13 1 36
,W/ContextImpl( 6975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/MdProvGlob( 6901): remove item 101 (p2d27in505) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6934): [b2d.2.] summary 118:p2 ignore
,D/PowerUI ( 1221): closing low battery warning: level=100
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false),
,W/ContextImpl( 6975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6975): MY_DEBUG = false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/InputManager(  969): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
,I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/SmartSyncUtils( 6975): isEpsOn(), nState = 0
,D/PMS     (  969): acquireWL(20112805): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6975 1000 null
,W/ContextImpl(  969): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  969): releaseWL(20112805): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartDim(  969): Init customizeScreenOffDelayClass error
,D/FlexNetS( 6886): updateSvcAllowedInSettings:false
,I/ActivityManager(  969): Killing 6526:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  969): killProcessQuiet, pid=6526
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ClockController( 1221): stop clock update:screen off
,E/WifiTrafficPoller(  969): TRAFFIC_STATS_POLL false Token 24 num clients 8
,I/ActivityManager(  969): Recipient 6526
,D/Process (  969): killProcessQuiet, pid=5705
I/ActivityManager(  969): Killing 5705:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/wpa_supplicant( 1306): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1306): EAPOL: disable timer tick
,D/FlexNetS( 6886): updateSvcAllowedInSettings:false,
,I/ActivityManager(  969): Recipient 5705
,E/WifiStateMachine(  969): handleMessage: E msg.what=131155
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-70 f=2412 sc=60 link=43 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:932] from screen [on:0 period:-2114097507] gl hn u24 rssi=-65 ag=0 hr ticks 0,0,5 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-70 f=2412 sc=60 link=43 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2114097504] gl hn u24 rssi=-65 ag=0 hr ticks 0,0,5 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  969): handleMessage: X
,D/Process (  969): killProcessQuiet, pid=6548
I/ActivityManager(  969): Killing 6548:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/FlexNetS( 6886): updateSvcAllowedInSettings:false,
,E/WifiDataStallTracker(  969): DATA_MONITOR_POLL false Token 3,
,I/CalendarProvider2( 6886): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,W/ContentResolver( 6886): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  969): Recipient 6548,
,I/PowerUsageList:PowerUsageHelper( 6975): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/FlexNetS( 6886): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6886): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6886): updateSvcAllowedInSettings:false,
D/FlexNetS( 6886): updateSvcAllowedInSettings:false
D/FlexNetS( 6886): updateSvcAllowedInSettings:false
D/PowerUsageList:BatterySipperExt( 6975): gen(), null == sipper.uidObj, userId = 0
D/FlexNetS( 6886): updateSvcAllowedInSettings:false
D/FlexNetS( 6886): updateSvcAllowedInSettings:false
,D/FlexNetS( 6886): updateSvcAllowedInSettings:false
,D/Process (  969): killProcessQuiet, pid=6434
I/ActivityManager(  969): Killing 6434:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  969): handleMessage: E msg.what=131212
,E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
D/ConnectivityService(  969): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  969):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  969): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  969): handleMessage: X
,I/ActivityManager(  969): Recipient 6434,
,W/ContextImpl( 6975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  969): acquireWL(1a5dc05a): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10024}
V/AlarmManager(  969): sending alarm PendingIntent{36fa1f68: PendingIntentRecord{10813f81 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=114121, Int=0
,W/ContextImpl( 6975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6975): MY_DEBUG = false
,D/SmartSyncUtils( 6975): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6975): isEpsOn(), nState = 0
,W/ContextImpl( 6975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl(  969): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  969): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=7010 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/SensorManager(  969): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@193e9f1
,W/SensorService(  969): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  969): disable: get sensor name = Accelerometer Sensor
,I/dhcpcd  ( 6963): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,W/SensorService(  969): pid=969, uid=1000
W/SensorService(  969): Active sensors: size = 3
W/SensorService(  969): CM36686 Proximity sensor (handle=0x00000004, connections=1),
W/SensorService(  969): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  969): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  969): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@193e9f1, eanble = 0, strlen(mName) = 35
W/SensorService(  969): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  969): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@377b608f
W/SensorService(  969): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  969): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  969): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  969): pid=969, uid=1000
E/ActivityThread(  969): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1ea839d6 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  969): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1ea839d6 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  969): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  969): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  969): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  969): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  969): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  969): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  969): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  969): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  969): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  969): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  969): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  969): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  969): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  969): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  969): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  969): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  969): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  969): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,W/SensorService(  969): Active sensors: size = 2
W/SensorService(  969): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  969): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  969): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@193e9f1, eanble = 0, strlen(mName) = 35
W/SensorService(  969): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  969): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@377b608f
W/SensorService(  969): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  969): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@193e9f1
,W/ResourcesManager( 7010): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/dhcpcd  ( 6963): wlan0: leased 192.168.1.130 for 86400 seconds
I/dhcpcd  ( 6963): autoip env[11]:autoip=DISABLE
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  969): handleMessage: E msg.what=131212
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
,E/WifiStateMachine(  969):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
E/WifiStateMachine(  969):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  969): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  969): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  969): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  969): handleMessage: X
,D/SmartSyncUtils( 6975): getMobilePolicyEnabled, result = true
,D/WifiService(  969): New client listening to asynchronous messages
E/WifiTrafficPoller(  969): ADD_CLIENT: 9
,D/CalendarApplication( 7010): onCreate
,D/ProviderChangeReceiver( 7010): ---------------------------------------------------
D/ProviderChangeReceiver( 7010): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 7010): start to updateAlertNotification!
D/Process (  969): killProcessQuiet, pid=6601
,I/ActivityManager(  969): Killing 6601:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/PMS     (  969): acquireWL(3f05ca14): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1876): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1876): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1876): [NET] android_getaddrinfo_proxy+
D/libc    ( 1876): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1876): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  969): acquireWL(3f05ca14): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1876): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  969): releaseWL(296d794b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  969): releaseWL(3f05ca14): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  969): Recipient 6601,
,I/dhcpcd  ( 6963): bind_interface: daemonise,
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  969): handleMessage: E msg.what=196613,
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  969): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1306): Power_Mode_Type mode = 0
I/wpa_supplicant( 1306): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  969): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  969): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1306): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/PMS     (  969): releaseWL(39ed6e87): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiDataStallTracker(  969): setDhcpActive: false
E/WifiStateMachine(  969): handlePostDhcpSetup release wake lock during DHCP
,E/WifiStateMachine(  969): WifiStateMachine DHCP successful,
,E/WifiStateMachine(  969): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  969): link address 192.168.1.130/24
,E/WifiStateMachine(  969): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  969): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  969): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  969): gateway: /192.168.1.1
D/PMS     (  969): releaseWL(1a5dc05a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
,D/wpa_supplicant( 1306): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
D/ConnectivityService(  969): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/wpa_supplicant( 1306): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1306): htc_wext_set_keepalive +
I/wpa_supplicant( 1306): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1306): getPrivFuncNum +	
I/wpa_supplicant( 1306): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1306): htc_wext_set_keepalive fnum = 0x8bf6
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
I/wpa_supplicant( 1306): get_ip_address source addr = c0a80182
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1306): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1306): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  969): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131210
D/ConnectivityService(  969): Adding iface wlan0 to network 101
E/WifiStateMachine(  969): processMsg: ObtainingIpState
E/WifiStateMachine(  969):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1306): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1306): environment dirty rate=0 [4][0][0]
E/WifiStateMachine(  969): fetchRssiLinkSpeedAndFrequencyNative RSSI = -64 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  969): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=72
E/WifiConfigStore(  969): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-66 "NG700"WPA_PSK
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1306): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1306): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  969): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=49 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  969): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  969): NetworkAgent != null
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -64, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiWatchdogStateMachine(  969): RSSI current: 3 new: -64, 3
E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -64, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  969): transitionTo: destState=ConnectedState
D/HtcWifiWanDetect(  969): WAN detection
E/WifiStateMachine(  969): handleMessage: new destination call exit/enter
D/HtcWifiWanDetect(  969): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiStateMachine(  969): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  969): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  969): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  969): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  969): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  969): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  969): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiDataStallTracker(  969): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiTrafficPoller(  969): ENABLE_TRAFF,IC_STATS_POLL false Token 24
E/WifiDataStallTracker(  969): ENABLE_DATA_MONITOR_POLL true Token 3
E/WifiDataStallTracker(  969): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
V/NetworkPolicy(  969): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 25
V/NetworkPolicy(  969): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5917): >>>>>WISPrService start isConnected = true<<<<<
D/HtcAlertService( 7010): No fired or scheduled alerts
D/HtcAlertUtils( 7010): -- cancelReminderNotification --
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/HtcAlertUtils( 7010): broadcastExistReminder!,
E/ConnectivityService(  969): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  969): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/ConnectivityService(  969): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  969): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  969): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
,D/Nat464Xlat(  969): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  969): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): Connected
D/ConnectivityService(  969): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  969): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): Validated
D/ConnectivityService(  969):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  969):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  969): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  969):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  969):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  969): currentScore = 0, newScore = 20
D/usbnet  (  969): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  969):    accepting network in place of null,
E/WifiStateMachine(  969): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiStateMachine(  969): handleMessage: X
D/ConnectivityService(  969): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
E/WifiStateMachine(  969): handleMessage: E msg.what=131131
D/CSLegacyTypeTracker(  969): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
E/WifiStateMachine(  969): processMsg: ConnectedState
D/ConnectivityService(  969): sendGeneralBroadcast, restrictEnable=false
E/WifiStateMachine(  969):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  969): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  969): processMsg: L2ConnectedState
D/ConnectivityService(  969): sendGeneralBroadcastDelayed, restrictEnable=false
E/WifiStateMachine(  969):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  969): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  969): processMsg: ConnectModeState
D/ConnectivityService(  969): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
E/WifiStateMachine(  969):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
V/NetworkPolicy(  969): ensureActiveMobilePolicyLocked()
D/Tethering(  969): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  969): acquireWL(317400b2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 969 1000 null
D/Tethering(  969): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  969): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  969): handleMessage: X
D/ConnectivityService(  969):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  969): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  969):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  969):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  969): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/WIFI    (  969): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  969): Validated NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  969): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  969): Validated
D/ConnectivityService(  969):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
D/ConnectivityService(  969):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  969): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  969): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/WIFI    (  969): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  969): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  969):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  969):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  969):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  969):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  969): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  969): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  969): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested,
D/ConnectivityService(  969): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  969): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
D/ConnectivityService(  969): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  969): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  969): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
D/ConnectivityService(  969):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  969):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  969): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  969): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  969):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  969):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  969): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkPolicy(  969): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  969): updateNetworkEnabledLocked()
V/NetworkPolicy(  969): updateIfacesLocked()
D/DATA_ICON( 1221): dataConnected: false/false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/DATA_ICON( 1221): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
V/NetworkPolicy(  969): updateNotificationsLocked()
D/NetworkManagementService(  969): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/PMS     (  969): releaseWL(317400b2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/DATA_ICON( 1221): dataConnected: false/false
D/WISPrService( 5917): >>>>>WISPrService start isConnected = true<<<<<
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NetworkPolicy(  969): updateNetworkEnabledLocked()
V/NetworkPolicy(  969): updateNotificationsLocked()
,I/ActivityManager(  969): Killing 5367:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  969): killProcessQuiet, pid=5367
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/ActivityManager(  969): Recipient 5367
,D/ConnectivityService(  969): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  969): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  969): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  969): acquireWL(2246b803): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 969 1000 null
D/GpsLocationProvider(  969): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  969): [AlarmQueuing] connectivity wifi: false
D/htcCheckinService(  969): ConnectivityReceiver - onReceive() - original mNetworkConnected = true,
I/ConnectivityHelper( 1579): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  969): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7063 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/PMS     (  969): releaseWL(11c6ed9f): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  969): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/GpsLocationProvider(  969): No APN found to select.
,D/MdScPhnSt( 6934): [5c3.1.]  listen tmrbb8,
,D/PMS     (  969): releaseWL(2246b803): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  969): acquireWL(172847ac): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 969 1000 null
,D/PMS     (  969): releaseWL(172847ac): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MdScDataSum( 6934): [5c3.1.] summary 118:p1 ignore,
,E/WifiStateMachine(  969): handleMessage: E msg.what=131155
,E/WifiStateMachine(  969): processMsg: ConnectedState
,E/WifiStateMachine(  969):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2062] from screen [on:0 period:-2114095441] gl hn u24 rssi=-65 ag=0 hr ticks 0,0,5 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2114095437] gl hn u24 rssi=-65 ag=0 hr ticks 0,0,5 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  969): handleMessage: X
,I/MusicStore( 7063): Database version: 120,
,E/WifiStateMachine(  969): handleMessage: E msg.what=131155,
E/WifiStateMachine(  969): processMsg: ConnectedState
E/WifiStateMachine(  969):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:35] from screen [on:0 period:-2114095401] gl hn u24 rssi=-65 ag=0 hr ticks 0,0,5 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2114095400] gl hn u24 rssi=-65 ag=0 hr ticks 0,0,5 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  969): handleMessage: X
,D/VoldConnector(  969): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 7063): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  969): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 7063): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  969): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 7063): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 7063): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7063): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7063): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 7063): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7063): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3da7f5cd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7063): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7063): GMSCore installation verified
,I/ConfigStore( 7063): Config Database version: 1
,I/PackageManager(  969):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=7063, uid=10159, userID:0
,D/WifiDisplayAdapter(  969): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  969):     Client/Owner: Client
D/WifiDisplayAdapter(  969):     GroupId: 
D/WifiDisplayAdapter(  969):     Passphrase: 
D/WifiDisplayAdapter(  969):     SessionId: 0
D/WifiDisplayAdapter(  969):     IP Address: }
,D/MediaRouterService(  969): Client com.google.android.music (pid 7063): Registered,
,D/WifiDisplayAdapter(  969): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  969):     Client/Owner: Client
D/WifiDisplayAdapter(  969):     GroupId: 
D/WifiDisplayAdapter(  969):     Passphrase: 
D/WifiDisplayAdapter(  969):     SessionId: 0
D/WifiDisplayAdapter(  969):     IP Address: },
,I/MediaRouter( 7063): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 7063): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7063): type=WIFI subType= reason=null isConnected=true,
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,I/NetworkMonitor( 7063): type=WIFI subType= reason=null isConnected=true,
,D/AutoSetting( 1640): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/PackageManager(  969):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=7063, uid=10159, userID:0
,D/MobileConnectivityChangeReceiver( 6705): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6705): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1640): service - onCreate(),
,I/GHttpClientFactory( 7063): Using our fixed implementation of GMSCore's GoogleHttpClient,
,D/LocationManagerService(  969): request 2956095b passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052),
D/LocationManagerService(  969): provider request: passive ProviderRequest[ON interval=0]
,I/art     (  969): Explicit concurrent mark sweep GC freed 62813(3MB) AllocSpace objects, 5(976KB) LOS objects, 33% free, 18MB/28MB, paused 1.902ms total 156.171ms,
D/AutoSetting( 1640): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1640): service - onStartCommand() screen is off, don't request location
,I/GoogleURLConnFactory( 7063): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4416): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4416): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  969): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7107 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 6746): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 6746): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6746): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6746): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6746): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6746): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6746): [NET] android_getaddrinfo_proxy-, success
,I/GLSUser ( 1876): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1876): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1876): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1876): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1876): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Babel   ( 6746): connection state changed from UNKNOWN to CONNECTED
,W/Kids    ( 4416): [AccountUtils] Account not ready,
W/Kids    ( 4416): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4416): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4416): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4416): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4416): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4416): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4416): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4416): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4416): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4416): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4416): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4416): 	at java.lang.Thread.run(Thread.java:818)
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/VoldConnector(  969): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 7107): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7107): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7107):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7107):   adb logcat -s GAv4,
D/VoldConnector(  969): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 7107): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  969): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 7107): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7107): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
D/VoldConnector(  969): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 7107): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7107): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 7107): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 7107): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7107): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 7107): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 7107): Time to load native libraries: 2 ms (timestamps 6945-6947),
I/LibraryLoader( 7107): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7107): Binding Chromium to main looper Looper (main, tid 1) {2e949722}
,I/LibraryLoader( 7107): Expected native library version number "",actual native library version number "",
,I/chromium( 7107): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 7107): Initializing chromium process, singleProcess=true,
,W/art     ( 7107): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 7107): ApplicationContext is null in ApplicationStatus,
,W/chromium( 7107): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 7107): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 7107): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,I/Adreno-EGL( 7107): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 7107): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7107): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7107): Local Branch: 
I/Adreno-EGL( 7107): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7107): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7107):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 7107): Requires BLUETOOTH permission,
,I/NSApplication( 7107): Starting up...,
,I/ActivityManager(  969): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7167 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  969): Killing 6732:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
D/Process (  969): killProcessQuiet, pid=6732
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6821): 
,I/ActivityManager(  969): Recipient 6732,
,D/Process (  969): killProcessQuiet, pid=6660
,I/ActivityManager(  969): Killing 6660:com.google.android.gms.unstable/u0a24 (adj 15): empty #18
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiStateMachine(  969): handleMessage: E msg.what=131168,
E/WifiStateMachine(  969): processMsg: ConnectedState
E/WifiStateMachine(  969):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  969): processMsg: SupplicantStartedState,
E/WifiStateMachine(  969):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  969): handleMessage: X
,I/ActivityManager(  969): Recipient 6660
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, err=8
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
,D/libc    (  969): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  969): [NET] android_getaddrinfo_proxy+
D/libc    (  969): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  969): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
I/AlarmManager(  969): [AlarmQueuing] connectivity wifi: true
D/GpsLocationProvider(  969): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
D/PMS     (  969): acquireWL(20778315): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 969 1000 null
,D/PMS     (  969): acquireWL(3411662a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 969 1000 null
,I/NetworkMonitor( 7063): type=WIFI subType= reason=null isConnected=true
D/PMS     (  969): releaseWL(3411662a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ConnectivityHelper( 1579): [onReceive] WIFI(1): CONNECTED
D/GpsLocationProvider(  969): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  969): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/htcCheckinService(  969): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,E/GpsLocationProvider(  969): No APN found to select.
,D/PMS     (  969): releaseWL(20778315): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,D/MdScPhnSt( 6934): [ae9.1.]  listen tmrbb8
,D/PMS     (  969): acquireWL(28f5bef7): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10024},
V/AlarmManager(  969): sending alarm PendingIntent{3adbc164: PendingIntentRecord{10813f81 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=117726, Int=0
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  969): [NET] android_getaddrinfo_proxy-, success
,D/HtcWifiWanDetect(  969): Find DNS Address www.htc.com/23.59.123.86
,D/MdScDataSum( 6934): [ae9.1.] summary 118:p1 ignore,
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 6821): 
,D/Process (  969): killProcessQuiet, pid=6360
,I/ActivityManager(  969): Killing 6360:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6821): 
,I/ActivityManager(  969): Recipient 6360
,V/MusicLeanback( 7063): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AutoSetting( 1640): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,D/MobileConnectivityChangeReceiver( 6705): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6705): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1640): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1640): service - onStartCommand() screen is off, don't request location,
,I/PackageManager(  969):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4416, uid=10024, userID:0,
,D/ChimeraCfgMgr( 4416): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4416): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PMS     (  969): acquireWL(17b9a20b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(28f5bef7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1876): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1876): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1876): [NET] android_getaddrinfo_proxy+
D/libc    ( 1876): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1876): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1876): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1876): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1876): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1876): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1876): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4416): [AccountUtils] Account not ready,
W/Kids    ( 4416): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4416): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4416): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4416): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4416): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4416): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4416): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4416): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4416): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4416): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4416): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4416): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1876): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1876): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  969): acquireWL(75e53e7): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1876 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1876): Connected
D/PMS     (  969): releaseWL(17b9a20b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
I/jxcore-log( 6821): Test app app.js loaded
I/jxcore-log( 6821): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6821): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6821): BLE advertisement is supported
I/jxcore-log( 6821): 
,D/PMS     (  969): releaseWL(75e53e7): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(2c644b94): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,I/chromium( 6821): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/GCM     ( 1876): Message class com.google.f.a.a.p
,D/PMS     (  969): releaseWL(2c644b94): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  969): acquireWL(1a1e1e32): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7063 10159 null
,I/PackageManager(  969):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7063, uid=10159, userID:0,
,I/MusicLeanback( 7063): Conditions not met for autocaching. okToAttempt=false
D/PMS     (  969): releaseWL(1a1e1e32): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 7063): Stop autocaching.
,D/WearableService( 5625): callingUid 10024, callindPid: 5625
,E/GmsUtils( 7063): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7063): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Process (  969): killProcessQuiet, pid=5538
,I/ActivityManager(  969): Killing 5538:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 5538,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  969): acquireWL(8d368ad): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10024}
,V/AlarmManager(  969): sending alarm PendingIntent{eb677e2: PendingIntentRecord{37041773 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143314, Int=0
,D/PMS     (  969): releaseWL(8d368ad): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  969): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  969): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  969): acquireWL(1d53630): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 969 1000 null
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  969): [NET] android_getaddrinfofornet-, err=8
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  969): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  969): [NET] android_getaddrinfo_proxy+
D/libc    (  969): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  969): [NET] android_getaddrinfo_proxy-, success
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233392e),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  969): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  969): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  969): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  969):  [handleDownloadXtraData]inject done.
D/GpsLocationProvider(  969): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  969): acquireWL(208f855c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 969 1000 null
D/PMS     (  969): releaseWL(1d53630): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  969): releaseWL(208f855c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/AutoSetting( 1640): service - handleMessage() stop self
,D/AutoSetting( 1640): service - handleMessage() quit looper
,D/AutoSetting( 1640): service - onDestroy() END
,D/PMS     (  969): acquireWL(18e60065): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(18e60065): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  969): processMsg: DefaultState
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: X
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/WifiStateMachine(  969): handleMessage: E msg.what=131165,
E/WifiStateMachine(  969): processMsg: ConnectedState
E/WifiStateMachine(  969):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0,
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
E/WifiStateMachine(  969):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  969): handleMessage: X
,W/ContextImpl(  969): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/WifiStateMachine(  969): handleMessage: E msg.what=131326
E/WifiStateMachine(  969): processMsg: ConnectedState
E/WifiStateMachine(  969):  ConnectedState what:131326 2 0
E/WifiStateMachine(  969): processMsg: L2ConnectedState
E/WifiStateMachine(  969):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  969): handleMessage: X
,D/TelephonyReceiver( 1543): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  969): acquireWL(212b213a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
V/AlarmManager(  969): sending alarm PendingIntent{14866664: PendingIntentRecord{5c440cd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157856, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{305901eb: PendingIntentRecord{1b3d9b48 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453879870222, Int=0,
V/AlarmManager(  969): sending alarm PendingIntent{3b3de1: PendingIntentRecord{231a1706 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202143, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{39c3d1c7: PendingIntentRecord{93523f4 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189547, Int=0
,D/PMS     (  969): acquireWL(1f4cd71d): PARTIAL_WAKE_LOCK  *backup* 0x1 969 1000 null
,D/PMS     (  969): acquireWL(3ab09d92): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  969): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  969): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  969): releaseWL(1f4cd71d): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  969): releaseWL(212b213a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  969): acquireWL(3e21c363): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(3ab09d92): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1876): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  969): releaseWL(3e21c363): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(2c70ccd5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(2c70ccd5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(c2e4cea): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(c2e4cea): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(32223bdb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(2d326678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(371c4db6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(32223bdb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1876): Vacuum at: now=1453879904579 tag=VacuumService
,D/PMS     (  969): releaseWL(2d326678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1876): Using platform SSLCertificateSocketFactory
,D/PMS     (  969): acquireWL(e637224): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(e637224): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  969): acquireWL(18f6c18d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1876): No account for auth token provided,
,D/PMS     (  969): releaseWL(18f6c18d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1876): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1876): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1876): [NET] android_getaddrinfo_proxy+
D/libc    ( 1876): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1876): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1876): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 1876): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1876): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1876): No account for auth token provided,
,W/Uploader( 1876): No account for auth token provided,
,W/Uploader( 1876):  no longer exists, so no auth token.,
,W/Uploader( 1876): No account for auth token provided,
,I/GLSUser ( 1876): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1876): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1876): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1876): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1876): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40,
,E/Uploader( 1876): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1876): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1876): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1876): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1876): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1876): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1876): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1876): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1876): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1876): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1876): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1876): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1876): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1876): No account for auth token provided,
,D/PMS     (  969): releaseWL(371c4db6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(2c4940c1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(2c4940c1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(3319066): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1876 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(3319066): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(afdbfa7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
I/BatteryService(  969): n_update end
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): releaseWL(afdbfa7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive-
,D/NotificationService(  969): plugged=true pluggin=true
D/WifiController(  969): handleMessage: E msg.what=155652
D/PMS     (  969): runPSCheck
D/WifiController(  969): processMsg: DeviceActiveState
D/HtcPowerSaver(  969): Checking...,
I/HtcPowerSaver(  969): >> updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  969): battery changed pluggedType: 2
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): processMsg: StaEnabledState,
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: X
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1640): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2395d488
D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  969): Killing 6391:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  969): killProcessQuiet, pid=6391
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 6391
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6821): --= Surplus to requirements =--
I/jxcore-log( 6821): 
,I/jxcore-log( 6821): ****TEST TOOK:  ms ****,
I/jxcore-log( 6821): 
I/jxcore-log( 6821): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6821): 
,E/cutils-trace( 7232): Error opening trace file: Permission denied (13),
,D/CustomizationManager( 7232): ====startRecUseTime====
,D/htc.customization.log.level( 7232):  is 
W/CustomizationLogLevel( 7232): Level value is invalid, use default level 2
,D/CustomizationManager( 7232):  Read ACC file spent 0.051 (s),
,D/CIDMapFileReader( 7232): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 7232): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7232): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7232): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7232): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7232): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7232): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 7232): full path : /system/customize/CID/HTC__102.xml,
,I/CustomizationCIDLoader( 7232): Parsing tag category name = system
,I/CustomizationCIDLoader( 7232): Parsing tag category name = application
,I/CustomizationCIDLoader( 7232): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 7232): Parsing tag category name = AutomotiveHome,
I/CustomizationCIDLoader( 7232): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7232): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7232): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 7232): add string-array item, value = 42507
,I/CustomizationCIDLoader( 7232): add string-array item, value = 21902
I/CustomizationCIDLoader( 7232): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7232): add string-array item, value = 23420
I/CustomizationCIDLoader( 7232): add string-array item, value = 22299
,I/CustomizationCIDLoader( 7232): add string-array item, value = 24002
I/CustomizationCIDLoader( 7232): add string-array item, value = 23210
I/CustomizationCIDLoader( 7232): add string-array item, value = 23205
I/CustomizationCIDLoader( 7232): add string-array item, value = 23806
I/CustomizationCIDLoader( 7232): add string-array item, value = 23430
,I/CustomizationCIDLoader( 7232): add string-array item, value = 23408
I/CustomizationCIDLoader( 7232): add string-array item, value = 27205
I/CustomizationCIDLoader( 7232): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7232): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7232): add string-array item, value = 26006:D:1:0
,I/CustomizationCIDLoader( 7232): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7232): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7232): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7232): add string-array item, value = 23210:D:2:0
,I/CustomizationCIDLoader( 7232): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7232): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7232): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7232): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7232): add string-array item, value = 27205:C:1:0
,D/CustomizationManager( 7232):  Read CID file spent 0.108 (s)
D/CustomizationManager( 7232):  All configurations done spent 0.109 (s)
,D/PackageManager(  969): deletePackageAsUser: pkg=com.test.thalitest, pid=7232, uid=2000 userid=0,
,I/ActivityManager(  969): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
,D/Process (  969): killProcessQuiet, pid=6821
I/ActivityManager(  969): Killing 6821:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  969): Skipping PackageSetting{2ae020d1 com.example.hello/10374} due to missing metadata,
,I/ActivityManager(  969): Recipient 6821
,E/InputEventReceiver( 1401): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{32eb69c1 uid 10366 pid 6821} (c)'
D/WifiService(  969): Client connection lost with reason: 4
,I/WindowState(  969): WIN DEATH: Window{7e58aa8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  969):   Force finishing activity ActivityRecord{71965 u0 com.test.thalitest/.MainActivity t8}
,W/ActivityManager(  969): Spurious death for ProcessRecord{2099ac54 6821:com.test.thalitest/u0a366}, curProc for 6821: null
,I/ActivityManager(  969): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
,D/DotMatrix( 1333): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1333): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/AccTypeManager( 1757): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,D/PMS     (  969): acquireWL(558463e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1836 10024 WorkSource{10024 com.google.android.gms}
,W/SystemReader(  969): Cannot find grip_rejection_width, use default value instead
W/GeofencerStateMachine( 1836): Ignoring removeGeofence because network location is disabled.
D/PMS     (  969): releaseWL(558463e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 5865): Explicit concurrent mark sweep GC freed 27856(1740KB) AllocSpace objects, 0(0B) LOS objects, 42% free, 2MB/4MB, paused 1.449ms total 86.716ms
,D/AccTypeManager( 1757): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,D/VoicemailCleanupService( 1722): Cleaning up data for package: com.test.thalitest
,I/art     ( 1579): Explicit concurrent mark sweep GC freed 5628(301KB) AllocSpace objects, 4(176KB) LOS objects, 34% free, 29MB/45MB, paused 1.013ms total 108.217ms
D/Prism.PackageStateRece_( 1579): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1579): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1579): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/[PluginManager]RegisterService( 1640): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,D/AccTypeManager( 1757): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Launcher( 1579): Deferring update until onResume
,D/Launcher( 1579): waitUntilResume // bindAppsRemoved
,I/[PluginManager]RegisterService( 1640): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  969): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7252 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/ExternalAccountType( 1757): Unsupported attribute readOnly
,D/PhoneApp( 1543): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/InputMethodManagerService(  969): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/PackageManager(  969): Unable to load service info ResolveInfo{1d5811ab com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  969): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  969): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  969): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  969): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  969): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  969): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  969): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  969): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  969): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  969): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  969): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/JobSchedulerService(  969): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  969): Explicit concurrent mark sweep GC freed 39975(2MB) AllocSpace objects, 6(324KB) LOS objects, 33% free, 18MB/28MB, paused 1.943ms total 270.702ms,
,D/TaskPersister(  969): removeObsoleteFile: deleting file=8_task.xml
,D/TaskPersister(  969): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/ResourcesManager(  969): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/StatusBarManagerService(  969): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
,W/ContextImpl( 7252): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  969): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
D/StatusBarManagerService(  969): hiding MENU key
,D/FindExtension( 1579): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1579): Defer allocateBuffers to drawing time
,W/InputMethodManagerService(  969): Got RemoteException sending setActive(false) notification to pid 6821 uid 10366
,D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
,I/ActivityManager(  969): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7279 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false),
D/Process (  969): killProcessQuiet, pid=5865
I/ActivityManager(  969): Killing 5865:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 5865
,I/PackageManager(  969):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7279, uid=10072, userID:0,
,W/global  ( 7279): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7279): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 7279): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7279): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7279): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  969): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7318 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7279): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SQLiteDatabase( 7279): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 7279): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7279): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7279): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
E/SQLiteDatabase( 7279): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 7279): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 7279): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 7279): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7279): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7279): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7279): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Settings( 7279): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/AndroidRuntime( 7279): FATAL EXCEPTION: libraries-thread,
E/AndroidRuntime( 7279): Process: com.android.vending, PID: 7279
E/AndroidRuntime( 7279): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7279): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7279): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7279): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7279): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 7279): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 7279): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 7279): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 7279): ,	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7279): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7279): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  969): App crashed! Process: com.android.vending
,D/Process ( 7279): killProcess, pid=7279
,E/SQLiteDatabase( 7279): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7279): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7279): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7279): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7279): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7279): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7279): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7279): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7279): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7279): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7279): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 7279): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 7279): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7279): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7279): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7279): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7279): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7279): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 7279): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
,D/Process (  969): killProcessQuiet, pid=6975
I/ActivityManager(  969): Killing 6975:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,E/lowmemorykiller(  382): Error writing /proc/7279/oom_score_adj; errno=22
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
,E/DropBoxManagerService(  969): Can't write: system_app_crash
E/DropBoxManagerService(  969): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  969): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  969): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  969): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  969): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  969): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  969): 	... 5 more
,I/ActivityManager(  969): Recipient 7279,
,I/ActivityManager(  969): Recipient 6975
,D/WifiService(  969): Client connection lost with reason: 4
,I/ActivityManager(  969): Process com.android.vending (pid 7279) has died,
,W/ResourcesManager( 7318): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7318): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7318): VM with version 2.1.0 has multidex support
,I/MultiDex( 7318): install
,I/MultiDex( 7318): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7318): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 7318): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 7318): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bd96a3b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 7318): Installed default security provider GmsCore_OpenSSL
,E/SQLiteLog( 1876): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error,
E/SQLiteDBG( 1876): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x55b678c110
E/AndroidRuntime( 1876): FATAL EXCEPTION: main
E/AndroidRuntime( 1876): Process: com.google.process.gapps, PID: 1876
E/AndroidRuntime( 1876): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1876): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1876): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1876): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1876): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1876): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1876): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
,E/AndroidRuntime( 1876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1876): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1876): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1876): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1876): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1876): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1876): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1876): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1876): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1876): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321),
E/AndroidRuntime( 1876): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1876): 	... 9 more
E/ActivityManager(  969): App crashed! Process: com.google.process.gapps
D/Process ( 1876): killProcess, pid=1876
D/Process ( 1876): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  969): Can't write: system_app_crash
E/DropBoxManagerService(  969): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  969): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  969): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  969): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  969): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  969): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  969): 	... 5 more
,W/NativeLibraryUtils( 7318): Failed to open lock file
W/NativeLibraryUtils( 7318): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7318): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7318): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7318): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7318): 	,at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7318): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7318): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7318): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7318): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7318): 	... 3 more
,I/ActivityManager(  969): Recipient 1876,
,I/ActivityThread( 7318): Removing dead content provider:android.content.ContentProviderProxy@294626b1
,I/ActivityManager(  969): Process com.google.process.gapps (pid 1876) has died
W/ActivityManager(  969): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
W/ActivityManager(  969): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 11000ms,
W/ActivityManager(  969): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
W/ActivityManager(  969): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,I/ActivityManager(  969): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=7350 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 7350): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 7350): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,I/MultiDex( 7350): VM with version 2.1.0 has multidex support,
,I/MultiDex( 7350): install,
I/MultiDex( 7350): VM has multidex support, MultiDex support library is disabled.
,I/Prism.ItemManager( 1579): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1579): loadItems() com.htc.launcher.pageview.WidgetManager@36eb8698 +
,I/Prism.WidgetManager( 1579): onLoadItems() +
,I/GservicesProvider( 7350): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7350): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7350): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7350): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7350): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7350): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7350): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7350): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7350): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7350): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7350): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7350): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7350): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
,E/SQLiteDatabase( 7350): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7350): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7350): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7350): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7350): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7350): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7350): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/AndroidRuntime( 7350): FATAL EXCEPTION: main
E/AndroidRuntime( 7350): Process: com.google.process.gapps, PID: 7350
E/AndroidRuntime( 7350): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7350): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7350): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7350): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7350): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7350): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7350): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7350): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7350): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7350): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7350): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7350): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7350): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7350): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7350): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7350): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7350): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7350): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7350): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7350): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7350): 	... 11 more
E/DropBoxManagerService(  969): Can't write: system_app_crash
E/DropBoxManagerService(  969): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  969): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/,DropBoxManagerService(  969): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  969): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  969): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  969): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  969): 	... 5 more
E/ActivityManager(  969): App crashed! Process: com.google.process.gapps
D/Process ( 7350): killProcess, pid=7350
D/Process ( 7350): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/ResourcesManager( 1579): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PMS     (  969): acquireWL(23d0add4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
V/AlarmManager(  969): sending alarm PendingIntent{14866664: PendingIntentRecord{5c440cd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217856, Int=0
I/ActivityManager(  969): Recipient 7350
,I/ActivityManager(  969): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7372 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
V/AlarmManager(  969): sending alarm PendingIntent{1ac8cb7d: PendingIntentRecord{b035d39 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453879976799, Int=0
I/ActivityManager(  969): Process com.google.process.gapps (pid 7350) has died
,W/ActivityManager(  969): Service crashed 2 times, stopping: ServiceRecord{347ce332 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
W/ActivityManager(  969): Service crashed 2 times, stopping: ServiceRecord{30a4a22f u0 com.google.android.gms/.gcm.http.GoogleHttpService}
W/ActivityManager(  969): Service crashed 2 times, stopping: ServiceRecord{eb14810 u0 com.google.android.gms/.gcm.GcmService}
W/ActivityManager(  969): Service crashed 2 times, stopping: ServiceRecord{450065d u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}

```
