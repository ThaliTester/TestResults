#### Test 832729920321fb3_thali04_HTC-HTC One M9 Logs


```
--------- beginning of main
08-30 17:28:37.091  8307  8307 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:28:37.091  8307  8307 W HTCLOG  : mask=0x18
08-30 17:28:37.091  6532  8304 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 17:28:37.091  6532  8304 W HTCLOG  : mask=0x18
--------- beginning of system
08-30 17:28:37.091  1126  3538 I ActivityManager: Start proc 8307:com.htc.cs.dm/u0a89 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
08-30 17:28:37.161  8307  8307 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8307 dbg=false s=true
08-30 17:28:37.161  8307  8307 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
08-30 17:28:37.171  1126  3531 I ActivityManager: Start proc 8332:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-30 17:28:37.171  1126  3531 D Process : killProcessQuiet, pid=7490
08-30 17:28:37.171  1126  3531 I ActivityManager: Killing 7490:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
08-30 17:28:37.171  1126  3531 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
08-30 17:28:37.181  8332  8332 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:28:37.181  8332  8332 W HTCLOG  : mask=0x18
,08-30 17:28:37.221  1126  4181 I ActivityManager: Recipient 7490
08-30 17:28:37.251  1126  3070 D PMS     : acquireWL(2bc9d440): PARTIAL_WAKE_LOCK  Icing 0x1 4004 10019 null
08-30 17:28:37.301  1126  3536 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 17:28:37.301  6532  8304 I ApplicationLogger: canRun() : Opted Out
08-30 17:28:37.301  6532  8304 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 222 ms] updated apps [took 222 ms] 
08-30 17:28:37.301  1126  3069 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 17:28:37.331  8332  8332 D DocsApplication: Plugin installer initialized.
08-30 17:28:37.331  1126  3538 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 17:28:37.351  8332  8332 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1f805150 com.google.android.apps.docs}
08-30 17:28:37.361  8332  8332 D TAG     : onCreate()
08-30 17:28:37.371  8353  8353 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-30 17:28:37.371  8353  8353 W HTCLOG  : mask=0x18
08-30 17:28:37.371  8332  8332 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 17:28:37.381  1126  3519 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 17:28:37.381  3140  3140 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-30 17:28:37.391  1126  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 17:28:37.401  1126  1126 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 11
08-30 17:28:37.381  3140  3140 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 17:28:37.381  3140  3140 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-30 17:28:37.381  3140  3140 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: Scan completed in 3.591766 seconds
08-30 17:28:37.381  3140  3140 D wpa_supplicant: nl80211: Received scan results (43 BSSes)
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-46
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-46
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-52
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-54
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-61
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-61
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-62
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-71
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-72
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-77
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-77
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-77
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-73
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-73
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-78
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-74
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-74
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-75
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-75
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-76
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-77
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:35 freq=2412 level=-77
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:36 freq=2412 level=-77
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:34 freq=2412 level=-77
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:90 freq=2462 level=-80
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:95 freq=2462 level=-82
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:96 freq=2462 level=-82
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:94 freq=2462 level=-82
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5a freq=5180 level=-87
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:59 freq=5180 level=-88
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:9f freq=5180 level=-88
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5f freq=5180 level=-89
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 00:fe:c8:73:02:06 freq=2462 level=-85
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:54 freq=2437 level=-87
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7e freq=5200 level=-61
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-70
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-76
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-73
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-75
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-80
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:91 freq=2462 level=-81
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5e freq=5180 level=-89
08-30 17:28:37.381  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:21:47:53 freq=2437 level=-88
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: BSS: Start scan result update 6
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 70 BSSID 84:b2:61:12:64:9f SSID '\x00'
08-30 17:28:37.381  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 71 BSSID 84:b2:61:21:47:54 SSID '\x00'
08-30 17:28:37.381  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 72 BSSID 84:b2:61:21:47:5e SSID '\x00'
08-30 17:28:37.381  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 20 BSSID 00:fe:c8:73:02:04 SSID '\x00' due to no match in scan
08-30 17:28:37.381  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 28 BSSID 00:fe:c8:73:02:02 SSID '\x00' due to no match in scan
08-30 17:28:37.381  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 32 BSSID 00:fe:c8:73:02:05 SSID '\x00' due to no match in scan
08-30 17:28:37.381  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 53 BSSID 00:fe:c8:73:02:01 SSID '\x00' due to no match in scan
08-30 17:28:37.381  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:37.381  3140  3140 D wpa_supplicant: BSS: last_scan_res_used=43/64
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: Scan-only results received
08-30 17:28:37.381  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:37.381  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:37.381  3140  3140 D wpa_supplicant: wlan0: Radio work 'scan'@0x5587ad8710 done in 3.635479 seconds
08-30 17:28:37.391  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 17:28:37.391  3140  3140 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 17:28:37.391  3140  3140 D wpa_supplicant: wlan0: Cancelling scan request
08-30 17:28:37.391  3140  3140 D wpa_supplicant: PNO: No configured SSIDs
08-30 17:28:37.391  1126  3060 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 17:28:37.391  3140  3140 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 17:28:37.391  3140  3140 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-30 17:28:37.401  3140  3140 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-30 17:28:37.401  1126  3060 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-30 17:28:37.401  4373  4373 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 17:28:37.401  4373  5877 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 17:28:37.551  8353  8358 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-30 17:28:37.551  8353  8358 W HTCLOG  : mask=0x18
08-30 17:28:37.551  8353  8358 E cutils-trace: Error opening trace file: Permission denied (13)
08-30 17:28:37.611  8353  8353 D CustomizationManager: ====startRecUseTime====
08-30 17:28:37.611  8353  8353 D htc.customization.log.level:  is 
08-30 17:28:37.611  8353  8353 W CustomizationLogLevel: Level value is invalid, use default level 2
08-30 17:28:37.621  3563  3981 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-30 17:28:37.621  3563  3981 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@16e42f79 +
08-30 17:28:37.621  3563  3981 I Prism.WidgetManager: onLoadItems() +
08-30 17:28:37.641  3563  3981 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
08-30 17:28:37.691  8353  8353 D CustomizationManager:  Read ACC file spent 0.039 (s)
08-30 17:28:37.691  8353  8353 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-30 17:28:37.691  8353  8353 I CustomizationCIDLoader: Parsing tag category name = application
08-30 17:28:37.701  8353  8353 I CustomizationCIDLoader: Parsing tag category name = system
08-30 17:28:37.701  8353  8353 I CustomizationCIDLoader: Parsing tag category name = Settings
08-30 17:28:37.701  8353  8353 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-30 17:28:37.701  8353  8353 I CustomizationCIDLoader: Parsing tag category name = ACC
08-30 17:28:37.701  8353  8353 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-30 17:28:37.701  8353  8353 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-30 17:28:37.701  8353  8353 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-30 17:28:37.701  8353  8353 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-30 17:28:37.701  8353  8353 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-30 17:28:37.701  8353  8353 D CustomizationManager:  Read CID file spent 0.088 (s)
08-30 17:28:37.701  8353  8353 D CustomizationManager:  All configurations done spent 0.088 (s)
08-30 17:28:37.721  3539  4159 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-30 17:28:37.721  3539  4159 D PhoneApp: -- N1 =0
08-30 17:28:37.721  3539  4159 D PhoneApp: -- N2 =0
08-30 17:28:37.731   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
08-30 17:28:37.731  3539  4159 D PhoneApp: -- N3 =0
08-30 17:28:37.741  1126  3069 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8353 on display 0
08-30 17:28:37.751  1126  1178 D PMS     : acquireHCC(3cb42a35): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1126 1000 null
08-30 17:28:37.751  1126  1178 D PMS     : acquireHCC(17904eca): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1126 1000 null
08-30 17:28:37.751  1126  3069 V WindowManager: addAppToken: AppWindowToken{28a34b1 token=Token{3d45eb58 ActivityRecord{3aaf483b u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-30 17:28:37.761  1126  3069 I ActivityManager: Start proc 8372:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-30 17:28:37.761  8353  8353 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-30 17:28:37.761  8353  8353 W HTCLOG  : mask=0x18
08-30 17:28:37.761  8353  8370 W HTCLOG  : use specified tag [Vector], func [0].
08-30 17:28:37.761  8353  8370 W HTCLOG  : mask=0x18
08-30 17:28:37.771  8372  8372 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:28:37.771  8372  8372 W HTCLOG  : mask=0x18
08-30 17:28:37.791  1126  1126 V ActivityManager: Display changed displayId=0
08-30 17:28:37.791  3336  3336 D DotMatrix: [EventService]  onDisplayChanged: 0
08-30 17:28:37.791  3336  3336 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-30 17:28:37.801  1126  4182 D ActivityManager: screenshot for ActivityRecord{3aaf483b u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-30 17:28:37.811  3563  3563 I TrimMemoryManager: [trimMemory] 20
08-30 17:28:37.821  3563  3981 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:28:37.851  8372  8372 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-30 17:28:37.901  8372  8372 I LibraryLoader: Time to load native libraries: 29 ms (timestamps 6934-6963)
08-30 17:28:37.901  8372  8372 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:28:37.911  8372  8372 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e21327c}
08-30 17:28:37.911  8372  8372 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:28:37.911  8372  8372 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:28:37.921  8372  8372 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 17:28:37.921  8372  8372 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:28:37.931  8372  8372 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 17:28:37.931  3563  3981 I Prism.WidgetManager: onLoadItems() -
08-30 17:28:37.931  3563  3981 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@16e42f79 -
08-30 17:28:37.951  8372  8395 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
08-30 17:28:37.961  5529  5581 D BluetoothAdapterService(84381774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394aef3
,08-30 17:28:37.971  8372  8372 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-30 17:28:37.971  8372  8372 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
08-30 17:28:37.971  8372  8372 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
08-30 17:28:37.971  8372  8372 W HTCLOG  : use specified tag [libEGL], func [3].
08-30 17:28:37.971  8372  8372 W HTCLOG  : mask=0x18
08-30 17:28:37.981  8372  8372 W HTCLOG  : use specified tag [libEGL], func [3].
08-30 17:28:37.981  8372  8372 W HTCLOG  : mask=0x18
08-30 17:28:37.981  8372  8372 I Adreno  : QUALCOMM build                   : 065751b, 
08-30 17:28:37.981  8372  8372 I Adreno  : Build Date                       : 04/15/15
08-30 17:28:37.981  8372  8372 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-30 17:28:37.981  8372  8372 I Adreno  : Local Branch                     : 
08-30 17:28:37.981  8372  8372 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-30 17:28:37.981  8372  8372 I Adreno  : Remote Branch                    : NONE
08-30 17:28:37.981  8372  8372 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
08-30 17:28:38.041  8372  8405 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
08-30 17:28:38.061  8372  8372 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:28:38.071  8372  8372 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 17:28:38.071  8372  8372 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
08-30 17:28:38.081  8372  8372 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:28:38.081  8372  8372 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:28:38.111  8372  8416 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 17:28:38.111  8372  8416 W HTCLOG  : mask=0x18
08-30 17:28:38.111  1126  3531 V WindowManager: Adding window Window{16c1be59 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{abf310d u0 com.htc.launcher/com.htc.launcher.Launcher})
08-30 17:28:38.121  1126  3654 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-30 17:28:38.141  8372  8372 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
08-30 17:28:38.141  8372  8372 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-30 17:28:38.141  8372  8372 W HTCLOG  : mask=0x18
08-30 17:28:38.141  8372  8372 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 17:28:38.141  8372  8372 W HTCLOG  : mask=0x18
08-30 17:28:38.141  8372  8416 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 17:28:38.141  8372  8416 W HTCLOG  : mask=0x18
08-30 17:28:38.141  8372  8416 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 17:28:38.141  8372  8416 W HTCLOG  : mask=0x18
08-30 17:28:38.141  8372  8416 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 17:28:38.141  8372  8416 W HTCLOG  : mask=0x18
08-30 17:28:38.141  8372  8416 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 17:28:38.141  8372  8416 W HTCLOG  : mask=0x18
08-30 17:28:38.151  8372  8416 W HTCLOG  : use specified tag [Surface], func [3].
08-30 17:28:38.151  8372  8416 W HTCLOG  : mask=0x18
08-30 17:28:38.151  8372  8416 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-30 17:28:38.151  8372  8416 W HTCLOG  : mask=0x18
08-30 17:28:38.151  8372  8416 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-30 17:28:38.151  8372  8416 W HTCLOG  : mask=0x18
08-30 17:28:38.211  1126  1167 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +415ms (total +462ms)
08-30 17:28:38.231  8332  8422 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 17:28:38.231  8332  8422 W HTCLOG  : mask=0x18
08-30 17:28:38.251  8372  8372 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8372
08-30 17:28:38.271  8332  8332 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-30 17:28:38.281  1126  3538 I ActivityManager: Start proc 8431:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
08-30 17:28:38.291  8431  8431 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:28:38.291  8431  8431 W HTCLOG  : mask=0x18
08-30 17:28:38.301  4004  6776 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-30 17:28:38.311  8431  8431 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:28:38.311  8372  8372 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 17:28:38.321  4004  6776 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 17:28:38.341  4004  6776 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
08-30 17:28:38.341  1126  3538 D PMS     : releaseWL(2bc9d440): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-30 17:28:38.361  8372  8421 D jxcore_app_log: JniHelper::setJavaVM(0xaacddb70), pthread_self() = -1413142112
08-30 17:28:38.361  8372  8421 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:28:38.361  8372  8421 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:28:38.361  8372  8421 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:28:38.361  8372  8421 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:28:38.361  8372  8421 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 17:28:38.361  8372  8421 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c75096b added. We now have 1 listener(s)
08-30 17:28:38.361  1126  3524 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-30 17:28:38.371  8372  8421 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
08-30 17:28:38.371  8372  8421 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-30 17:28:38.371  8372  8421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:28:38.371  8372  8421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:28:38.371  8372  8421 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed6486 added. We now have 1 listener(s)
08-30 17:28:38.371  8372  8421 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:28:38.371  8372  8421 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:28:38.371  1126  3061 D WifiService: New client listening to asynchronous messages
08-30 17:28:38.371  8372  8421 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:28:38.371  8372  8421 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:28:38.371  8372  8421 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:28:38.371  8372  8421 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 17:28:38.371  8372  8421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:28:38.371  1126  3538 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-30 17:28:38.381  8372  8421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
08-30 17:28:38.381  5529  5552 D BluetoothAdapterService(84381774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394aef3
08-30 17:28:38.381  8372  8421 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 17:28:38.381  8372  8421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:28:38.381  8372  8421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:28:38.381  8372  8421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:28:38.381  8372  8421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:28:38.381  8372  8421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:28:38.381  8372  8421 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:28:38.381  8372  8421 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:28:38.381  8372  8421 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:28:38.381  8372  8421 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:28:38.381  8372  8421 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:28:38.381  8372  8421 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:28:38.381  8372  8372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:28:38.411  8372  8372 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-30 17:28:38.521  1126  4182 D PMS     : acquireWL(24df4cfc): PARTIAL_WAKE_LOCK  AsyncService 0x1 8431 10128 null
08-30 17:28:38.531  1126  3049 D PMS     : acquireWL(370bf85): PARTIAL_WAKE_LOCK  *alarm* 0x1 1126 1000 WorkSource{10019}
08-30 17:28:38.531  1126  3049 V AlarmManager: sending alarm PendingIntent{373a41da: PendingIntentRecord{19078771 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=81401, Int=0
08-30 17:28:38.531  1126  3049 V AlarmManager: sending alarm PendingIntent{c7aa60b: PendingIntentRecord{26523ce8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=81781, Int=0
08-30 17:28:38.531  1126  3049 V AlarmManager: sending alarm PendingIntent{2302cf01: PendingIntentRecord{1f0aa1a6 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1472570915658, Int=0
08-30 17:28:38.531  1126  3049 V AlarmManager: sending alarm PendingIntent{212b97e7: PendingIntentRecord{6d01362 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=86682, Int=0
08-30 17:28:38.531  1126  3589 D PMS     : releaseWL(24df4cfc): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-30 17:28:38.561  1126  1148 I ActivityManager: Killing 7567:com.htc.sdm/u0a61 (adj 15): empty #17
08-30 17:28:38.561  1126  1148 D Process : killProcessQuiet, pid=7567
08-30 17:28:38.561  1126  1148 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
08-30 17:28:38.671  1126  4185 I ActivityManager: Recipient 7567
,08-30 17:28:38.751  8372  8457 W jxcore-log: Initializing JXcore engine
,08-30 17:28:38.751  8372  8457 W jxcore-log: JXcore engine is ready
,08-30 17:28:38.761  1126  1178 D PMS     : releaseHCC(3cb42a35): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,08-30 17:28:38.761  1126  1178 D PMS     : releaseHCC(17904eca): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-30 17:28:38.771  3610  3610 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 17:28:38.791  3610  3610 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 17:28:38.791  3610  3610 D c       : Getting all permits...
08-30 17:28:38.791  3610  3610 D a       : Opening database...,
,08-30 17:28:38.791  3610  3610 D a       : Opening database auth.proximity.permit_store...
08-30 17:28:38.801  3610  3610 D a       : Closing database...
,08-30 17:28:38.801  4004  4004 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-30 17:28:38.811  8372  8457 W jxcore-log: Starting JXcore engine
,08-30 17:28:38.821  4004  8465 D LocationInitializer: Restart initialization of location
08-30 17:28:38.821  1126  3524 D PMS     : acquireWL(164c5a3d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 3610 10019 null
,08-30 17:28:38.821  3610  8466 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
08-30 17:28:38.821  3610  8466 D libc    : [NET] android_getaddrinfofornet-, err=8
08-30 17:28:38.831  3610  8466 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
08-30 17:28:38.831  3610  8466 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-30 17:28:38.831  3610  8466 D libc    : [NET] android_getaddrinfo_proxy+
,08-30 17:28:38.831  3610  8466 D libc    : [NET] android_getaddrinfo_proxy get netid:0
08-30 17:28:38.831   517  8467 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
08-30 17:28:38.831  1126  1126 D PMS     : acquireWL(a2f3232): PARTIAL_WAKE_LOCK  *backup* 0x1 1126 1000 null
08-30 17:28:38.831   517  8467 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
08-30 17:28:38.831   517  8467 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
08-30 17:28:38.831   517  8467 D libc    : [NET] android_getaddrinfofornet-, err=7
08-30 17:28:38.831  3610  8466 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
08-30 17:28:38.831  7612  7612 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 17:28:38.831  1126  3131 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
08-30 17:28:38.841  7612  7612 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 17:28:38.841  7612  7612 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 17:28:38.841  1126  3131 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
08-30 17:28:38.841  7612  7612 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 17:28:38.841  1126  3131 D PMS     : releaseWL(a2f3232): PARTIAL_WAKE_LOCK  *backup* 0x1 null
08-30 17:28:38.841  7612  7612 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-30 17:28:38.841  1126  1126 D PMS     : releaseWL(370bf85): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
,08-30 17:28:38.851  1126  3524 D PMS     : releaseWL(164c5a3d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null,
,08-30 17:28:38.871  7612  8469 D HtcModeClient: start the htcmodeservice thread
08-30 17:28:38.871  7612  8469 D HtcModeClient: initCanAgent
,08-30 17:28:38.871  7612  8469 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 17:28:38.871  7612  8469 D HtcModeClient: sense info: version = none, id = 2,
08-30 17:28:38.871  7612  8469 D HtcModeClient: display info: width = 1080, height = 1776
08-30 17:28:38.871  7612  8469 D HtcModeClient: display info: mode = 10
,08-30 17:28:38.971  7612  7612 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-30 17:28:38.971  7612  7612 D HtcModeClient: connectState: BT_TURNON_BYME = false
,08-30 17:28:38.971  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 17:28:38.971  7612  7612 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 17:28:38.971  7612  7612 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 17:28:38.971  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 17:28:38.971  7612  7612 D HtcModeClient: connectState: Force_AWAKE = false,
08-30 17:28:38.971  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 17:28:38.971  7612  7612 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 17:28:40.981  7612  8469 I HtcModeClient: handler message = 4011,
08-30 17:28:40.981  7612  8469 D HtcModeClient: getConnectionCheckCount first 0
08-30 17:28:40.981  7612  8469 D HtcModeClient: getConnectionCheckCount count = 7
08-30 17:28:40.981  7612  8469 E HtcModeClient: Check connection and retry 8 times.
08-30 17:28:40.981  7612  8469 D HtcModeClient: setConnectionCheckCount count = 8
08-30 17:28:40.981  7612  8469 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 17:28:40.991  7612  7612 D HtcModeClient: setBtPriority priority = on
,08-30 17:28:40.991  7612  7612 D HtcModeClient: unbindBlueToothService
08-30 17:28:40.991  7612  7612 D HtcModeClient: Don't start project servcice
08-30 17:28:40.991  7612  7612 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 17:28:40.991  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 17:28:40.991  7612  7612 D SilentMusic: call stop
08-30 17:28:40.991  7612  7612 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,08-30 17:28:40.991  7612  8470 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 17:28:40.991  7612  7612 D HtcModeClient: onDestroy
,08-30 17:28:41.101  8190  8206 E AndroidHttpClient: Leak found,
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
,08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 17:28:41.101  8190  8206 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 17:28:41.861  8235  8235 D Process : killProcess, pid=8235,
08-30 17:28:41.861  8235  8235 D Process : com.google.android.gms.car.gt.run:127 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
08-30 17:28:41.861  8235  8235 W HTCLOG  : use specified tag [Process], func [0].
08-30 17:28:41.861  8235  8235 W HTCLOG  : mask=0x18
,08-30 17:28:41.961  1126  3537 I ActivityManager: Recipient 8235
,08-30 17:28:41.961  1126  3537 I ActivityManager: Process com.google.android.gms:car (pid 8235) has died,
,08-30 17:28:42.321  8332  8332 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-30 17:28:42.321  1126  1126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,08-30 17:28:43.221  8332  8420 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 17:28:43.281  1126  1149 D PMS     : releaseWL(43a1833): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,08-30 17:28:45.751  4004  8150 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1V49NceOM0yFDyEsh7yFEGUYmwCFmI42guEVDAHj3yxKn83nol6xUptlzRy0pYsK1V-YlpXDQAh5lEhOwPyrjzo9vG8mQjBjfQW0tYph8xJHzhofu54pxyXsT_OhK1GotEaVCWgFHnM4bbqopUInWVzGgroURrR7GQYXbTfLZeeAMMdnekatiTb4XvFsltCxSm2_W1g
,08-30 17:28:45.761  4004  8150 I GoogleURLConnFactory: binding HttpService
,08-30 17:28:45.761  4004  8150 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 17:28:45.771  4004  8150 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
08-30 17:28:45.771  4004  8150 D libc    : [NET] android_getaddrinfofornet-, err=8
,08-30 17:28:45.771  4004  8150 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
08-30 17:28:45.771  4004  8150 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-30 17:28:45.771  4004  8150 D libc    : [NET] android_getaddrinfo_proxy+
,08-30 17:28:45.771  4004  8150 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,08-30 17:28:45.771   517  8477 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,08-30 17:28:45.771   517  8477 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
,08-30 17:28:45.771   517  8477 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
08-30 17:28:45.771   517  8477 D libc    : [NET] android_getaddrinfofornet-, err=7
,08-30 17:28:45.781  4004  8150 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,08-30 17:28:45.781  4004  8150 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-30 17:28:45.781  4004  8150 I GoogleURLConnFactory: unbinding HttpService
,08-30 17:28:45.781  4004  4004 I ConfigFetchService: fetch service done; releasing wakelock
08-30 17:28:45.781  1126  4182 D PMS     : releaseWL(c028e8c): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 null
08-30 17:28:45.781  4004  4004 I ConfigFetchService: stopping self
,08-30 17:28:45.791  3610  3610 I ConfigService: onDestroy
,08-30 17:28:45.981  1126  3049 D PMS     : acquireWL(307eb5c4): PARTIAL_WAKE_LOCK  *alarm* 0x1 1126 1000 WorkSource{10027}
08-30 17:28:45.991  1126  3049 V AlarmManager: sending alarm PendingIntent{1aed4cad: PendingIntentRecord{6d01362 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=93047, Int=0
,08-30 17:28:45.991  7612  7612 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 17:28:46.001  1126  1126 D PMS     : releaseWL(307eb5c4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
,08-30 17:28:46.001  7612  7612 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 17:28:46.001  7612  7612 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 17:28:46.001  7612  7612 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 17:28:46.001  7612  7612 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 17:28:46.031  7612  8479 D HtcModeClient: start the htcmodeservice thread,
08-30 17:28:46.031  7612  8479 D HtcModeClient: initCanAgent
08-30 17:28:46.031  7612  8479 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-30 17:28:46.031  7612  8479 D HtcModeClient: sense info: version = none, id = 2
08-30 17:28:46.031  7612  7612 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,08-30 17:28:46.031  7612  7612 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 17:28:46.031  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 17:28:46.031  7612  7612 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 17:28:46.031  7612  7612 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 17:28:46.031  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 17:28:46.031  7612  7612 D HtcModeClient: connectState: Force_AWAKE = false
08-30 17:28:46.031  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 17:28:46.031  7612  8479 D HtcModeClient: display info: width = 1080, height = 1776
08-30 17:28:46.031  7612  8479 D HtcModeClient: display info: mode = 10
,08-30 17:28:46.031  7612  7612 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 17:28:46.971  8372  8457 W jxcore-log: Platform android
08-30 17:28:46.971  8372  8457 W jxcore-log: 
,08-30 17:28:46.971  8372  8457 W jxcore-log: Process ARCH arm,
08-30 17:28:46.971  8372  8457 W jxcore-log: 
,08-30 17:28:47.181  8372  8457 I jxcore-log: JXcore Cordova bridge is ready!,
08-30 17:28:47.181  8372  8457 I jxcore-log: 
08-30 17:28:47.181  8372  8457 W jxcore-log: JXcore engine is started
,08-30 17:28:47.181  8372  8421 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,08-30 17:28:47.191  8372  8372 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 17:28:48.041  7612  8479 I HtcModeClient: handler message = 4011
,08-30 17:28:48.041  7612  8479 D HtcModeClient: getConnectionCheckCount first 0
08-30 17:28:48.041  7612  8479 D HtcModeClient: getConnectionCheckCount count = 8
08-30 17:28:48.041  7612  8479 E HtcModeClient: Check connection and retry 9 times.
08-30 17:28:48.041  7612  8479 D HtcModeClient: setConnectionCheckCount count = 9
08-30 17:28:48.041  7612  8479 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 17:28:48.051  7612  7612 D HtcModeClient: setBtPriority priority = on
,08-30 17:28:48.051  7612  7612 D HtcModeClient: unbindBlueToothService
08-30 17:28:48.051  7612  7612 D HtcModeClient: Don't start project servcice
08-30 17:28:48.051  7612  7612 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-30 17:28:48.051  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 17:28:48.051  7612  7612 D SilentMusic: call stop
08-30 17:28:48.051  7612  7612 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 17:28:48.051  7612  8480 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 17:28:48.061  7612  7612 D HtcModeClient: onDestroy
,08-30 17:28:48.761  1126  3060 D WifiStateMachine: startScan Pid: 1126 Uid -1
08-30 17:28:48.761  1126  3060 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-30 17:28:48.761  1126  3060 D WifiDisplayAdapter:     Client/Owner: Client
08-30 17:28:48.761  1126  3060 D WifiDisplayAdapter:     GroupId: 
08-30 17:28:48.761  1126  3060 D WifiDisplayAdapter:     Passphrase: 
08-30 17:28:48.761  1126  3060 D WifiDisplayAdapter:     SessionId: 0
08-30 17:28:48.761  1126  3060 D WifiDisplayAdapter:     IP Address: }
08-30 17:28:48.761  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-30 17:28:48.761  3140  3140 D wpa_supplicant: CTRL_IFACE SET 'pno'='0'
,08-30 17:28:48.761  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-30 17:28:48.761  3140  3140 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-30 17:28:48.761  3140  3140 I wpa_supplicant: wpa_supplicant_scan enter
08-30 17:28:48.761  3140  3140 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-30 17:28:48.761  3140  3140 D wpa_supplicant: wlan0: Add radio work 'scan'@0x5587ad8710
08-30 17:28:48.761  3140  3140 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-30 17:28:48.761  3140  3140 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x5587ad8710 after 0.000024 second wait
08-30 17:28:48.761  3140  3140 D wpa_supplicant: wlan0: nl80211: scan request
,08-30 17:28:48.801  3140  3140 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-30 17:28:48.801  3140  3140 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
08-30 17:28:48.801  3140  3140 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-30 17:28:48.801  3140  3140 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
08-30 17:28:48.801  3140  3140 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000135 seconds
08-30 17:28:48.801  3140  3140 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 17:28:48.801  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
,08-30 17:28:49.831  1126  3519 D PMS     : acquireWL(38d7b53a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1126 1000 null,
08-30 17:28:49.831  1126  3519 I BatteryService: n_update end
08-30 17:28:49.841  3185  3719 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-30 17:28:49.841  3336  3336 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-30 17:28:49.841  1126  3519 D PMS     : releaseWL(38d7b53a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-30 17:28:49.841  3336  3336 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-30 17:28:49.841  3185  3185 D PowerUI : closing low battery warning: level=100
08-30 17:28:49.841  3336  3336 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-30 17:28:49.841  1126  1174 D HtcPowerSaver: updateBatteryInfo
08-30 17:28:49.841  1126  1126 D UsbnetService: BroadcastReceiver::onReceive+
08-30 17:28:49.841  1126  1126 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-30 17:28:49.841  1126  1126 D UsbnetService: onReceive BATTERY_CHANGED,
08-30 17:28:49.841  1126  1126 D HtcPowerSaver: Checking...
08-30 17:28:49.841  1126  1126 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-30 17:28:49.841  1126  1126 I HtcPowerSaver: >> updateStatus
08-30 17:28:49.841  1126  1126 D UsbnetService: BroadcastReceiver::onReceive-
08-30 17:28:49.841  1126  3061 D WifiController: battery changed pluggedType: 2
08-30 17:28:49.841  1126  3061 D WifiController: handleMessage: E msg.what=155652
08-30 17:28:49.841  3185  3185 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-30 17:28:49.841  1126  3061 D WifiController: processMsg: DeviceActiveState
,08-30 17:28:49.841  1126  3061 D WifiController: processMsg: StaEnabledState
08-30 17:28:49.841  1126  3061 D WifiController: processMsg: DefaultState
08-30 17:28:49.841  1126  3061 D WifiController: handleMessage: X
08-30 17:28:49.851  1126  1126 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-30 17:28:49.851  1126  1126 I HtcPowerSaver: << updateStatus
,08-30 17:28:49.891  3185  3185 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-30 17:28:49.891  3185  3185 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-30 17:28:49.891  3185  3185 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-30 17:28:49.891  3185  3185 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-30 17:28:49.891  3185  3185 I FlashlightController: batteryLevelChange:100
,08-30 17:28:50.891  1126  1161 I ActivityManager: Waited long enough for: ServiceRecord{268bbac u0 com.google.android.gms/.wearable.service.WearableService}
,08-30 17:28:52.401  3140  3140 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 17:28:52.401  3140  3140 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 17:28:52.401  3140  3140 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
,08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-30 17:28:52.401  3140  3140 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: Scan completed in 3.598485 seconds
08-30 17:28:52.401  3140  3140 D wpa_supplicant: nl80211: Received scan results (39 BSSes)
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-46
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-46
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-44
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-60
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-60
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-61
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-76
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-72
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-77
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-77
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-73
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-73
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-74
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-75
08-30 17:28:52.411  1126  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-76
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:34 freq=2412 level=-77
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:35 freq=2412 level=-78
,08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:9f freq=5180 level=-87
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5a freq=5180 level=-87
,08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:59 freq=5180 level=-87
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:9a freq=5180 level=-88
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 00:fe:c8:73:02:06 freq=2462 level=-84
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5b freq=5180 level=-89
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:90 freq=2462 level=-86
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] e4:aa:5d:fc:5b:f6 freq=2437 level=-87
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:50 freq=2437 level=-87
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:56 freq=2437 level=-88
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-84
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7e freq=5200 level=-60
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-71
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-76
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-73
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-76
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-77
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-83
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-83
,08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5e freq=5180 level=-88
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:91 freq=2462 level=-85
08-30 17:28:52.401  3140  3140 I wpa_supplicant: [] e4:aa:5d:fc:5b:f1 freq=2437 level=-86
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: BSS: Start scan result update 7
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 73 BSSID 84:b2:61:12:64:9a SSID '\x00'
08-30 17:28:52.401  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 74 BSSID 84:b2:61:21:47:50 SSID '\x00'
08-30 17:28:52.401  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 75 BSSID 84:b2:61:21:47:56 SSID '\x00'
08-30 17:28:52.401  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 76 BSSID 00:fe:c8:73:02:03 SSID 'RA-WINGS'
08-30 17:28:52.401  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 65 BSSID e4:aa:5d:fc:5b:f4 SSID '\x00' due to no match in scan
,08-30 17:28:52.401  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 57 BSSID e4:aa:5d:fc:5b:f5 SSID '\x00' due to no match in scan
08-30 17:28:52.401  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 68 BSSID 84:b2:61:12:64:92 SSID '\x00' due to no match in scan
08-30 17:28:52.401  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:52.401  3140  3140 D wpa_supplicant: BSS: last_scan_res_used=39/64
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: Scan-only results received
08-30 17:28:52.401  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:52.401  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:28:52.401  3140  3140 D wpa_supplicant: wlan0: Radio work 'scan'@0x5587ad8710 done in 3.643870 seconds
08-30 17:28:52.411  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
,08-30 17:28:52.411  3140  3140 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 17:28:52.411  3140  3140 D wpa_supplicant: wlan0: Cancelling scan request
08-30 17:28:52.411  3140  3140 D wpa_supplicant: PNO: No configured SSIDs
08-30 17:28:52.411  1126  3060 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 17:28:52.411  3140  3140 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 17:28:52.411  3140  3140 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,08-30 17:28:52.421  3140  3140 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
,08-30 17:28:52.431  1126  3060 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
,08-30 17:28:52.431  4373  4373 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 17:28:52.431  1126  1126 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 12
08-30 17:28:52.431  4373  5877 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
,08-30 17:28:53.081  1126  3049 I ActivityManager: Start proc 8481:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService
,08-30 17:28:53.081  1126  3049 D PMS     : acquireWL(11ec05eb): PARTIAL_WAKE_LOCK  *alarm* 0x1 1126 1000 WorkSource{10058}
08-30 17:28:53.081  1126  3049 V AlarmManager: sending alarm PendingIntent{a0e4f48: PendingIntentRecord{3defe1e1 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1472570926856, Int=60000
,08-30 17:28:53.081  1126  3049 V AlarmManager: sending alarm PendingIntent{3b8315c7: PendingIntentRecord{265d17f4 com.android.vending startService}}, i=null, t=0, cnt=1, w=1472570931373, Int=0
08-30 17:28:53.081  1126  3049 V AlarmManager: sending alarm PendingIntent{2da7bb1d: PendingIntentRecord{6d01362 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=100111, Int=0
,08-30 17:28:53.081  7612  7612 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 17:28:53.091  7612  7612 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 17:28:53.091  1126  1126 D PMS     : releaseWL(11ec05eb): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-30 17:28:53.091  7612  7612 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 17:28:53.091  7612  7612 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,08-30 17:28:53.091  7612  7612 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-30 17:28:53.101  8481  8481 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:28:53.101  8481  8481 W HTCLOG  : mask=0x18
,08-30 17:28:53.121  7612  8503 D HtcModeClient: start the htcmodeservice thread
,08-30 17:28:53.121  7612  8503 D HtcModeClient: initCanAgent
,08-30 17:28:53.121  7612  8503 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 17:28:53.121  7612  8503 D HtcModeClient: sense info: version = none, id = 2
,08-30 17:28:53.121  7612  8503 D HtcModeClient: display info: width = 1080, height = 1776
08-30 17:28:53.121  7612  8503 D HtcModeClient: display info: mode = 10
,08-30 17:28:53.141  8481  8505 D SMSBackup: SMSBackupAgentService started
,08-30 17:28:53.141  8481  8505 D SMSBackup: Checking restore status
,08-30 17:28:53.141  8481  8505 D SMSBackup: Restore complete
,08-30 17:28:53.141  8481  8505 D SMSBackup: cancelCheckAlarm
,08-30 17:28:53.151  8481  8505 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds,
,08-30 17:28:53.221  7612  7612 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,08-30 17:28:53.221  7612  7612 D HtcModeClient: connectState: BT_TURNON_BYME = false
,08-30 17:28:53.221  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false,
,08-30 17:28:53.231  7612  7612 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 17:28:53.231  7612  7612 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 17:28:53.231  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 17:28:53.231  7612  7612 D HtcModeClient: connectState: Force_AWAKE = false
08-30 17:28:53.231  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 17:28:53.231  7612  7612 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 17:28:53.281  1126  3879 I art     : Explicit concurrent mark sweep GC freed 29943(1612KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 16MB/24MB, paused 1.826ms total 145.982ms
,08-30 17:28:53.381  8190  8190 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.,
,08-30 17:28:55.241  7612  8503 I HtcModeClient: handler message = 4011,
08-30 17:28:55.241  7612  8503 D HtcModeClient: getConnectionCheckCount first 0
08-30 17:28:55.241  7612  8503 D HtcModeClient: getConnectionCheckCount count = 9
,08-30 17:28:55.241  7612  8503 E HtcModeClient: Check connection and retry 10 times.
,08-30 17:28:55.241  7612  8503 D HtcModeClient: setConnectionCheckCount count = 10
08-30 17:28:55.241  7612  8503 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 17:28:55.251  7612  7612 D HtcModeClient: setBtPriority priority = on
,08-30 17:28:55.251  7612  7612 D HtcModeClient: unbindBlueToothService
08-30 17:28:55.251  7612  7612 D HtcModeClient: Don't start project servcice
08-30 17:28:55.251  7612  7612 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 17:28:55.251  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 17:28:55.251  7612  7612 D SilentMusic: call stop
08-30 17:28:55.251  7612  7612 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,08-30 17:28:55.251  7612  8504 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 17:28:55.251  7612  7612 D HtcModeClient: onDestroy
08-30 17:28:55.251  1126  3069 I ActivityManager: Killing 7898:com.htc.calendar/u0a6 (adj 15): empty #17
08-30 17:28:55.251  1126  3069 D Process : killProcessQuiet, pid=7898
08-30 17:28:55.251  1126  3069 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-30 17:28:55.411  1126  4182 I ActivityManager: Recipient 7898,
,08-30 17:29:00.241  1126  3049 D PMS     : acquireWL(307e3fdb): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1126 1000 WorkSource{1000},
08-30 17:29:00.241  1126  3049 V AlarmManager: sending alarm PendingIntent{b2ed938: PendingIntentRecord{271bd11 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=109057, Int=0
08-30 17:29:00.241  1126  3049 V AlarmManager: sending alarm PendingIntent{1b981a78: PendingIntentRecord{6d01362 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=107307, Int=0
08-30 17:29:00.251  7612  7612 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 17:29:00.261  7612  7612 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 17:29:00.261  7612  7612 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 17:29:00.261  7612  7612 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 17:29:00.261  7612  7612 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 17:29:00.281  1126  1126 D PMS     : releaseWL(307e3fdb): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,08-30 17:29:00.281  7612  8508 D HtcModeClient: start the htcmodeservice thread
08-30 17:29:00.291  7612  8508 D HtcModeClient: initCanAgent,
08-30 17:29:00.291  7612  8508 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 17:29:00.291  7612  8508 D HtcModeClient: sense info: version = none, id = 2
,08-30 17:29:00.291  7612  8508 D HtcModeClient: display info: width = 1080, height = 1776
08-30 17:29:00.291  7612  8508 D HtcModeClient: display info: mode = 10
,08-30 17:29:00.391  7612  7612 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-30 17:29:00.391  7612  7612 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 17:29:00.391  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 17:29:00.391  7612  7612 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 17:29:00.391  7612  7612 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 17:29:00.391  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = false
,08-30 17:29:00.391  7612  7612 D HtcModeClient: connectState: Force_AWAKE = false
08-30 17:29:00.391  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 17:29:00.391  7612  7612 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 17:29:02.401  7612  8508 I HtcModeClient: handler message = 4011,
08-30 17:29:02.401  7612  8508 D HtcModeClient: getConnectionCheckCount first 0
08-30 17:29:02.401  7612  8508 D HtcModeClient: getConnectionCheckCount count = 10
08-30 17:29:02.401  7612  8508 E HtcModeClient: Check connection and retry 11 times.
08-30 17:29:02.401  7612  8508 D HtcModeClient: setConnectionCheckCount count = 11
08-30 17:29:02.401  7612  8508 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 17:29:02.411  7612  7612 D HtcModeClient: setBtPriority priority = on
,08-30 17:29:02.411  7612  7612 D HtcModeClient: unbindBlueToothService
08-30 17:29:02.411  7612  7612 D HtcModeClient: Don't start project servcice
08-30 17:29:02.411  7612  7612 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 17:29:02.411  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 17:29:02.411  7612  7612 D SilentMusic: call stop
08-30 17:29:02.411  7612  7612 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode,
08-30 17:29:02.411  7612  8509 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 17:29:02.421  7612  7612 D HtcModeClient: onDestroy,
,08-30 17:29:03.771  1126  3060 D WifiStateMachine: startScan Pid: 1126 Uid -1,
08-30 17:29:03.771  1126  3060 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-30 17:29:03.771  1126  3060 D WifiDisplayAdapter:     Client/Owner: Client
08-30 17:29:03.771  1126  3060 D WifiDisplayAdapter:     GroupId: 
08-30 17:29:03.771  1126  3060 D WifiDisplayAdapter:     Passphrase: 
08-30 17:29:03.771  1126  3060 D WifiDisplayAdapter:     SessionId: 0
08-30 17:29:03.771  1126  3060 D WifiDisplayAdapter:     IP Address: }
08-30 17:29:03.771  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-30 17:29:03.771  3140  3140 D wpa_supplicant: CTRL_IFACE SET 'pno'='0'
08-30 17:29:03.771  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
,08-30 17:29:03.771  3140  3140 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-30 17:29:03.771  3140  3140 I wpa_supplicant: wpa_supplicant_scan enter
08-30 17:29:03.771  3140  3140 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-30 17:29:03.771  3140  3140 D wpa_supplicant: wlan0: Add radio work 'scan'@0x5587adf8b0
08-30 17:29:03.771  3140  3140 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-30 17:29:03.771  3140  3140 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x5587adf8b0 after 0.000033 second wait
08-30 17:29:03.771  3140  3140 D wpa_supplicant: wlan0: nl80211: scan request
,08-30 17:29:03.821  3140  3140 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
08-30 17:29:03.821  3140  3140 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
08-30 17:29:03.821  3140  3140 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-30 17:29:03.821  3140  3140 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
08-30 17:29:03.821  3140  3140 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000147 seconds
08-30 17:29:03.821  3140  3140 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 17:29:03.821  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
,08-30 17:29:06.401  8372  8457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-30 17:29:06.401  8372  8457 I jxcore-log: 
,08-30 17:29:06.411  8372  8457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-30 17:29:06.411  8372  8457 I jxcore-log: 
,08-30 17:29:06.421  5529  5552 D BluetoothAdapterService(84381774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394aef3,
08-30 17:29:06.421  8372  8457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:29:06.421  8372  8457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:29:06.421  8372  8457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-30 17:29:06.421  8372  8457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:29:06.421  8372  8457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:29:06.421  8372  8457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:29:06.421  8372  8457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:29:06.421  8372  8457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:29:06.421  5529  5552 D BluetoothAdapterService(84381774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394aef3
,08-30 17:29:06.421  8372  8457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:29:06.431  8372  8457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-30 17:29:06.431  8372  8457 I jxcore-log: 
,08-30 17:29:06.431  8372  8457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-30 17:29:06.431  8372  8457 I jxcore-log: 
,08-30 17:29:07.401  1126  3049 D PMS     : acquireWL(20d10d89): PARTIAL_WAKE_LOCK  *alarm* 0x1 1126 1000 WorkSource{10027}
,08-30 17:29:07.411  1126  3049 V AlarmManager: sending alarm PendingIntent{2c18b18e: PendingIntentRecord{6d01362 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=114467, Int=0
,08-30 17:29:07.411  7612  7612 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 17:29:07.411  7612  7612 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 17:29:07.421  1126  1126 D PMS     : releaseWL(20d10d89): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-30 17:29:07.411  7612  7612 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 17:29:07.411  7612  7612 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 17:29:07.411  7612  7612 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 17:29:07.431  3140  3140 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-30 17:29:07.431  1126  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 17:29:07.431  3140  3140 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 17:29:07.431  3140  3140 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-30 17:29:07.431  3140  3140 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: Scan completed in 3.610911 seconds
08-30 17:29:07.431  3140  3140 D wpa_supplicant: nl80211: Received scan results (50 BSSes)
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-49
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-49
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-46
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-47
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-61
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-62
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-62
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-77
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-77
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-77
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-73
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-74
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-75
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-75
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-75
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-75
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:35 freq=2412 level=-77
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:34 freq=2412 level=-77
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:9a freq=5180 level=-86
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:99 freq=5180 level=-86
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:9f freq=5180 level=-87
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:90 freq=2462 level=-83
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5b freq=5180 level=-88
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5a freq=5180 level=-88
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5f freq=5180 level=-88
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 00:fe:c8:73:02:02 freq=2462 level=-84
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 00:fe:c8:73:02:05 freq=2462 level=-84
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:94 freq=2462 level=-84
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:59 freq=5180 level=-89
08-30 17:29:07.431  3140  3,140 I wpa_supplicant: [] 00:fe:c8:73:02:06 freq=2462 level=-85
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] e4:aa:5d:fc:5b:f0 freq=2437 level=-85
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:92 freq=2462 level=-85
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:96 freq=2462 level=-85
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 00:fe:c8:73:02:04 freq=2462 level=-87
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] e4:aa:5d:fc:5b:f6 freq=2437 level=-87
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:50 freq=2437 level=-89
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7e freq=5200 level=-61
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-77
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-74
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-75
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-77
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-78
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-82
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:9e freq=5180 level=-87
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 00:fe:c8:73:02:01 freq=2462 level=-83
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:21:47:53 freq=2437 level=-83
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5e freq=5180 level=-88
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:91 freq=2462 level=-84
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-85
08-30 17:29:07.431  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:51 freq=2437 level=-88
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Start scan result update 8
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 77 BSSID 84:b2:61:12:64:99 SSID '\x00'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 78 BSSID 00:fe:c8:73:02:02 SSID '\x00'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 79 BSSID 00:fe:c8:73:02:05 SSID '\x00'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 80 BSSID e4:aa:5d:fc:5b:f0 SSID '\x00'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 81 BSSID 84:b2:61:12:64:92 SSID '\x00'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 82 BSSID 00:fe:c8:73:02:04 SSID '\x00'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 83 BSSID 84:b2:61:12:64:9e SSID '\x00'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 84 BSSID 00:fe:c8:73:02:01 SSID '\x00'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 85 BSSID 84:b2:61:21:47:51 SSID '\x00'
08-,30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 15 BSSID 84:b2:61:1a:ce:70 SSID '\x00' due to no match in scan
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 11 BSSID 00:16:a6:1e:e0:a4 SSID '' due to no match in scan
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 64 BSSID 84:b2:61:0f:9c:32 SSID '\x00' due to no match in scan
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 25 BSSID 84:b2:61:0f:9c:36 SSID '\x00' due to no match in scan
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 29 BSSID 84:b2:61:12:64:95 SSID '\x00' due to no match in scan
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 71 BSSID 84:b2:61:21:47:54 SSID '\x00' due to no match in scan
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: BSS: last_scan_res_used=50/64
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: Scan-only results received
,08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: Radio work 'scan'@0x5587adf8b0 done in 3.656809 seconds
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: Cancelling scan request
08-30 17:29:07.431  3140  3140 D wpa_supplicant: PNO: No configured SSIDs
08-30 17:29:07.431  1126  3060 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 17:29:07.431  3140  3140 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 17:29:07.441  3140  3140 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-30 17:29:07.451  3140  3140 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-30 17:29:07.451  1126  3060 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-30 17:29:07.451  1126  1126 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 15
08-30 17:29:07.451  4373  4373 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 17:29:07.451  4373  5877 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
,08-30 17:29:07.461  7612  8511 D HtcModeClient: start the htcmodeservice thread
08-30 17:29:07.461  7612  8511 D HtcModeClient: initCanAgent
08-30 17:29:07.461  7612  8511 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-30 17:29:07.461  7612  8511 D HtcModeClient: sense info: version = none, id = 2
,08-30 17:29:07.461  7612  8511 D HtcModeClient: display info: width = 1080, height = 1776
08-30 17:29:07.461  7612  8511 D HtcModeClient: display info: mode = 10
,08-30 17:29:07.561  7612  7612 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-30 17:29:07.561  7612  7612 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 17:29:07.561  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 17:29:07.561  7612  7612 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 17:29:07.561  7612  7612 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 17:29:07.561  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 17:29:07.561  7612  7612 D HtcModeClient: connectState: Force_AWAKE = false
08-30 17:29:07.561  7612  7612 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 17:29:07.561  7612  7612 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 17:29:09.571  7612  8511 I HtcModeClient: handler message = 4011,
08-30 17:29:09.571  7612  8511 D HtcModeClient: getConnectionCheckCount first 0
08-30 17:29:09.571  7612  8511 D HtcModeClient: getConnectionCheckCount count = 11
08-30 17:29:09.571  7612  8511 E HtcModeClient: Check connection and retry 12 times. Time out!
08-30 17:29:09.571  7612  8511 D HtcModeClient: setConnectionCheckCount count = 0
08-30 17:29:09.571  7612  8511 D HtcModeClient: cancelRestart
,08-30 17:29:09.581  7612  7612 D HtcModeClient: setBtPriority priority = on
08-30 17:29:09.581  7612  7612 D HtcModeClient: unbindBlueToothService
08-30 17:29:09.581  7612  7612 D HtcModeClient: Don't start project servcice
,08-30 17:29:09.581  7612  7612 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 17:29:09.581  7612  7612 D HtcModeClient: connectState: CONNECTION_READY = false,
08-30 17:29:09.581  7612  7612 D SilentMusic: call stop
08-30 17:29:09.581  7612  7612 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 17:29:09.591  7612  8512 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 17:29:09.591  7612  7612 D HtcModeClient: onDestroy,
,08-30 17:29:12.241  8372  8457 I jxcore-log: Running unit tests,
08-30 17:29:12.241  8372  8457 I jxcore-log: 
08-30 17:29:12.241  8372  8457 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 17:29:12.241  8372  8457 I jxcore-log: Failed to execute UT.
08-30 17:29:12.241  8372  8457 I jxcore-log: 
,08-30 17:29:12.251  8372  8457 I jxcore-log: Unit Test app is loaded,
08-30 17:29:12.251  8372  8457 I jxcore-log: 
,08-30 17:29:12.261  8372  8457 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 17:29:12.261  8372  8457 I jxcore-log: 
08-30 17:29:12.261  8372  8457 I jxcore-log: My device name is: HTC-HTC One M9
08-30 17:29:12.261  8372  8457 I jxcore-log: 
08-30 17:29:12.261  8372  8372 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 17:29:12.261  8372  8457 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 17:29:12.261  8372  8457 I jxcore-log: 
,08-30 17:29:12.731   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-30 17:29:18.781  1126  3060 D WifiStateMachine: startScan Pid: 1126 Uid -1,
08-30 17:29:18.781  1126  3060 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-30 17:29:18.781  1126  3060 D WifiDisplayAdapter:     Client/Owner: Client
08-30 17:29:18.781  1126  3060 D WifiDisplayAdapter:     GroupId: 
08-30 17:29:18.781  1126  3060 D WifiDisplayAdapter:     Passphrase: 
08-30 17:29:18.781  1126  3060 D WifiDisplayAdapter:     SessionId: 0
08-30 17:29:18.781  1126  3060 D WifiDisplayAdapter:     IP Address: }
08-30 17:29:18.781  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-30 17:29:18.781  3140  3140 D wpa_supplicant: CTRL_IFACE SET 'pno'='0'
,08-30 17:29:18.781  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-30 17:29:18.781  3140  3140 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-30 17:29:18.781  3140  3140 I wpa_supplicant: wpa_supplicant_scan enter
08-30 17:29:18.781  3140  3140 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-30 17:29:18.781  3140  3140 D wpa_supplicant: wlan0: Add radio work 'scan'@0x5587ad8710
08-30 17:29:18.781  3140  3140 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-30 17:29:18.781  3140  3140 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x5587ad8710 after 0.000026 second wait
08-30 17:29:18.781  3140  3140 D wpa_supplicant: wlan0: nl80211: scan request
,08-30 17:29:18.821  3140  3140 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
08-30 17:29:18.821  3140  3140 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
08-30 17:29:18.821  3140  3140 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-30 17:29:18.821  3140  3140 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
08-30 17:29:18.821  3140  3140 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000156 seconds
08-30 17:29:18.821  3140  3140 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 17:29:18.821  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
,08-30 17:29:22.441  3140  3140 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 17:29:22.441  3140  3140 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 17:29:22.441  3140  3140 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-30 17:29:22.441  3140  3140 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: Scan completed in 3.614573 seconds
,08-30 17:29:22.441  3140  3140 D wpa_supplicant: nl80211: Received scan results (34 BSSes)
08-30 17:29:22.451  1126  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-47
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-47
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-45
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-46
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-61
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-61
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-61
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-71
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-72
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-72
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-73
,08-30 17:29:22.441  3140  3140 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-73,
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-78
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-78
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-78
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-78
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-76
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-80
,08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-81
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-83
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5f freq=5180 level=-88
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:9b freq=5180 level=-88
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5b freq=5180 level=-88
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:21:47:5a freq=5180 level=-88
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:94 freq=2462 level=-85
,08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 00:fe:c8:73:02:02 freq=2462 level=-86
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 00:fe:c8:73:02:04 freq=2462 level=-86
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] e4:aa:5d:fc:5b:f5 freq=2437 level=-88
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-71
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-73
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 84:b2:61:12:64:9e freq=5180 level=-87
,08-30 17:29:22.441  3140  3140 I wpa_supplicant: [] 00:fe:c8:73:02:01 freq=2462 level=-85
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-86
08-30 17:29:22.441  3140  3140 I wpa_supplicant: [RA-WINGS] 84:b2:61:21:47:53 freq=2437 level=-87
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: BSS: Start scan result update 9
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 86 BSSID 84:b2:61:1a:ce:70 SSID '\x00'
08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 87 BSSID 00:16:a6:1e:e0:a4 SSID ''
,08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 88 BSSID 84:b2:61:0f:9c:32 SSID '\x00'
08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 89 BSSID 84:b2:61:12:64:9b SSID '\x00'
08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: BSS: Add new id 90 BSSID e4:aa:5d:fc:5b:f5 SSID '\x00'
08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00,
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 75 BSSID 84:b2:61:21:47:56 SSID '\x00' due to no match in scan
08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: BSS: Remove ID 60 BSSID e4:aa:5d:fc:5b:f1 SSID '\x00' due to no match in scan
08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:22.441  3140  3140 D wpa_supplicant: BSS: last_scan_res_used=34/64
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: Scan-only results received
,08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1126-2\x00
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: Radio work 'scan'@0x5587ad8710 done in 3.660238 seconds
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 17:29:22.441  3140  3140 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 17:29:22.441  3140  3140 D wpa_supplicant: wlan0: Cancelling scan request
08-30 17:29:22.441  3140  3140 D wpa_supplicant: PNO: No configured SSIDs
,08-30 17:29:22.451  1126  3060 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 17:29:22.451  3140  3140 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 17:29:22.451  3140  3140 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,08-30 17:29:22.461  3140  3140 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-30 17:29:22.461  1126  3060 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-30 17:29:22.461  1126  1126 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 14
08-30 17:29:22.461  4373  4373 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 17:29:22.461  4373  5877 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
,08-30 17:29:22.741   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 17:29:26.251  8372  8457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
08-30 17:29:26.251  8372  8457 I jxcore-log: 
,08-30 17:29:26.821  8372  8457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-30 17:29:26.821  8372  8457 I jxcore-log: 
,08-30 17:29:26.861  8372  8457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js,
08-30 17:29:26.861  8372  8457 I jxcore-log: 
,08-30 17:29:28.971  8372  8457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js,
08-30 17:29:28.971  8372  8457 I jxcore-log: 
,08-30 17:29:29.251  8372  8457 I jxcore-log: ERROR runTests: ,
08-30 17:29:29.251  8372  8457 I jxcore-log: 
,08-30 17:29:29.251  8372  8457 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger',
08-30 17:29:29.251  8372  8457 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-30 17:29:29.261  8372  8457 I jxcore-log: WARN testUtils: logCallback not set!
08-30 17:29:29.261  8372  8457 I jxcore-log: 
,08-30 17:29:29.271  8372  8457 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _functionName: 'loadFile',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _lineNumber: '26',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _columnNumber: '11',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 17:29:29.271  8372  8457 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _functionName: '',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _lineNumber: '38',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _columnNumber: '7',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 17:29:29.271  8372  8457 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',,
08-30 17:29:29.271  8372  8457 I jxcore-log:     _functionName: '',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _lineNumber: '35',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _columnNumber: '3',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 17:29:29.271  8372  8457 I jxcore-log:   { _fileName: 'module.js',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _lineNumber: '621',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _columnNumber: '8',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 17:29:29.271  8372  8457 I jxcore-log:   { _fileName: 'module.js',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _lineNumber: '651',
08-30 17:29:29.271  8372  8457 I jxcore-log:     _columnNumber: '1',
08-30 17:29:29.271  8372  8457 I jxcore-log:    
08-30 17:29:29.271  8372  8457 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 17:29:29.271  8372  8457 I jxcore-log: 
08-30 17:29:29.281  8372  8457 E jxcore-log: Error: 
08-30 17:29:29.281  8372  8457 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
,08-30 17:29:29.281  8372  8457 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 17:29:29.281  8372  8457 E jxcore-log: 
,08-30 17:29:29.481  8513  8513 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
08-30 17:29:29.481  8513  8513 W HTCLOG  : mask=0x18
,08-30 17:29:29.661  8513  8519 W HTCLOG  : use specified tag [cutils-trace], func [0].
,08-30 17:29:29.661  8513  8519 W HTCLOG  : mask=0x18
08-30 17:29:29.661  8513  8519 E cutils-trace: Error opening trace file: Permission denied (13)
,08-30 17:29:29.721  8513  8513 D CustomizationManager: ====startRecUseTime====,
08-30 17:29:29.721  8513  8513 D htc.customization.log.level:  is 
08-30 17:29:29.721  8513  8513 W CustomizationLogLevel: Level value is invalid, use default level 2
,08-30 17:29:29.801  8513  8513 D CustomizationManager:  Read ACC file spent 0.042 (s),
,08-30 17:29:29.801  8513  8513 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
,08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: Parsing tag category name = application
08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: Parsing tag category name = system
08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: Parsing tag category name = Settings
08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome,
08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: Parsing tag category name = ACC
,08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
,08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-30 17:29:29.811  8513  8513 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-30 17:29:29.811  8513  8513 D CustomizationManager:  Read CID file spent 0.094 (s)
08-30 17:29:29.811  8513  8513 D CustomizationManager:  All configurations done spent 0.094 (s)
,08-30 17:29:29.861  1126  3538 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8513, uid=2000,
08-30 17:29:29.861  1126  1161 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
08-30 17:29:29.871  1126  1161 D Process : killProcessQuiet, pid=8372
08-30 17:29:29.871  1126  1161 I ActivityManager: Killing 8372:com.test.thalitest/u0a142 (adj 0): stop com.test.thalitest
08-30 17:29:29.871  1126  1161 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,08-30 17:29:29.941   528   528 W HTCLOG  : use specified tag [Vector], func [0].
,08-30 17:29:29.941   528   528 W HTCLOG  : mask=0x18
,08-30 17:29:30.011  1126  3519 I ActivityManager: Recipient 8372
08-30 17:29:30.011  1126  3589 I WindowState: WIN DEATH: Window{16c1be59 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 17:29:30.021  1126  3061 D WifiService: Client connection lost with reason: 4
,08-30 17:29:30.081  1126  1161 I ActivityManager:   Force finishing activity 3 ActivityRecord{3aaf483b u0 com.test.thalitest/.MainActivity t451},
,08-30 17:29:30.091  1126  3519 W ActivityManager: Spurious death for ProcessRecord{15af03a7 8372:com.test.thalitest/u0a142}, curProc for 8372: null
08-30 17:29:30.091  1126  1180 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed,
,08-30 17:29:30.111  3336  3336 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
08-30 17:29:30.121  1126  3524 D PMS     : acquireWL(8cba054): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4373 10019 null,
,08-30 17:29:30.111  3336  3336 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
08-30 17:29:30.121  1126  3536 D PMS     : releaseWL(8cba054): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
08-30 17:29:30.121  3764  4169 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
08-30 17:29:30.121  1126  3057 D PMS     : acquireWL(afb60f2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1126 1000 null
08-30 17:29:30.121  4373  4495 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 17:29:30.121  1126  3058 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
08-30 17:29:30.121  1126  3052 W SystemReader: Cannot find grip_rejection_width, use default value instead
08-30 17:29:30.131  1126  3139 D TaskPersister: removeObsoleteFile: deleting file=451_task.xml
08-30 17:29:30.121  3764  4169 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
08-30 17:29:30.151  1126  3519 D PMS     : acquireWL(1c1b6af9): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4004 10019 null
08-30 17:29:30.141  3764  4169 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
08-30 17:29:30.151  1126  3057 D PMS     : releaseWL(afb60f2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
08-30 17:29:30.141  3764  4169 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
08-30 17:29:30.161  1126  3058 V NetworkPolicy: writePolicyLocked()
08-30 17:29:30.151  4004  4004 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 17:29:30.181  1126  3058 V NetworkPolicy: updateNetworkEnabledLocked()
08-30 17:29:30.151  3539  3539 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
08-30 17:29:30.181  1126  3058 V NetworkPolicy: updateNotificationsLocked()
08-30 17:29:30.151  3610  3610 I ConfigService: onCreate
08-30 17:29:30.151  3610  3610 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 17:29:30.161  6532  6532 I art     : Explicit concurrent mark sweep GC freed 12312(760KB) AllocSpace objects, 2(48KB) LOS objects, 34% free, 3MB/5MB, paused 885us total 62.757ms
08-30 17:29:30.161  4004  4004 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 17:29:30.161  3803  8530 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 17:29:30.171  3764  4169 E ExternalAccountType: Unsupported attribute readOnly
08-30 17:29:30.181  1126  3058 D NetworkPolicy: notifyPoliciesChangeLocked: no change
08-30 17:29:30.191  3610  3610 I ConfigService: onBind returning update interface
08-30 17:29:30.191  3563  3563 I art     : Explicit concurrent mark sweep GC freed 2703(142KB) AllocSpace objects, 8(1340KB) LOS objects, 40% free, 20MB/33MB, paused 1.033ms total 90.394ms
08-30 17:29:30.191  3610  3610 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
,08-30 17:29:30.201  3610  3610 I ConfigService: onBind returning config service
,08-30 17:29:30.211  1126  3524 I ActivityManager: Start proc 8532:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver,
,08-30 17:29:30.211  3610  3610 I ConfigService: onDestroy
,08-30 17:29:30.221  1126  1149 D PMS     : acquireWL(62db316): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3610 10019 null
,08-30 17:29:30.231  8532  8532 W HTCLOG  : use specified tag [FDManager], func [0].,
08-30 17:29:30.231  1126  4182 D PMS     : releaseWL(62db316): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-30 17:29:30.231  8532  8532 W HTCLOG  : mask=0x18
,08-30 17:29:30.281  1126  1126 I art     : Explicit concurrent mark sweep GC freed 29752(1944KB) AllocSpace objects, 8(148KB) LOS objects, 33% free, 16MB/24MB, paused 1.851ms total 170.366ms
,08-30 17:29:30.281  1126  1180 I art     : WaitForGcToComplete blocked for 160.588ms for cause Explicit
,08-30 17:29:30.281  8532  8532 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 17:29:30.281  8532  8532 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 17:29:30.301  1126  1160 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
,08-30 17:29:30.311  3563  3563 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,08-30 17:29:30.311  3563  3563 I ThreadedRenderer: Defer allocateBuffers to drawing time
,08-30 17:29:30.311  8532  8532 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:29:30.311  8532  8532 I MultiDex: install
08-30 17:29:30.311  8532  8532 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:29:30.331  8532  8532 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 17:29:30.341  8532  8532 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-30 17:29:30.351  1126  3531 D Process : killProcessQuiet, pid=7754,
08-30 17:29:30.351  1126  3531 I ActivityManager: Killing 7754:com.google.android.gm/u0a97 (adj 15): empty #17
08-30 17:29:30.351  1126  3531 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-30 17:29:30.381  1126  1160 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-30 17:29:30.401  1126  1126 W PackageManager: Unable to load service info ResolveInfo{31642f67 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
08-30 17:29:30.401  1126  1126 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
08-30 17:29:30.401  1126  1126 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
08-30 17:29:30.401  1126  1126 W PackageManager: 	,at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:29:30.401  1126  1126 W PackageManager: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 17:29:30.401  1126  1126 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 17:29:30.431  1126  3069 I ActivityManager: Recipient 7754,
,08-30 17:29:30.461  1126  1180 I art     : Explicit concurrent mark sweep GC freed 6651(334KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.089ms total 176.099ms
,08-30 17:29:30.471  4004  8556 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
08-30 17:29:30.471  4004  8556 D AccountUtils: Clearing selected account for com.test.thalitest
08-30 17:29:30.471  3473  3473 D Nfc-Utils: isNxpCodebase: isNxp=false
,08-30 17:29:30.491  1126  3591 I ActivityManager: Start proc 8558:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver
,08-30 17:29:30.501  8558  8558 W HTCLOG  : use specified tag [FDManager], func [0].,
08-30 17:29:30.501  8558  8558 W HTCLOG  : mask=0x18
,08-30 17:29:30.521  7933  8582 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 17:29:30.551  1126  3519 D Process : killProcessQuiet, pid=7417,
08-30 17:29:30.551  1126  3519 I ActivityManager: Killing 7417:com.google.android.music:main/u0a115 (adj 15): empty #17
08-30 17:29:30.551  1126  3519 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-30 17:29:30.561  4004  8584 I PeopleContactsSync: CP2 sync disabled,
,08-30 17:29:30.561  1126  3531 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4004, uid=10019, userID:0,
,08-30 17:29:30.571  1126  3537 D MediaRouterService: Client com.google.android.music (pid 7417): Died!
08-30 17:29:30.571  1126  3524 I ActivityManager: Recipient 7417
,08-30 17:29:30.571  8513  8513 I art     : System.exit called, status: 0
08-30 17:29:30.571  8513  8513 W HTCLOG  : use specified tag [Vector], func [0].
,08-30 17:29:30.601  1126  1126 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
,08-30 17:29:30.661  3764  3764 E PackageActionReceiver: ACTION_PACKAGE_REMOVED,
,08-30 17:29:30.661  1126  3537 D PMS     : acquireWL(f98576c): PARTIAL_WAKE_LOCK  Icing 0x1 4004 10019 null
,08-30 17:29:30.671  3563  3981 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
08-30 17:29:30.671  3563  3981 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
08-30 17:29:30.671  4004  6776 I Icing   : doRemovePackageData com.test.thalitest
08-30 17:29:30.671  3563  3563 I Launcher: Deferring update until onResume
08-30 17:29:30.671  1126  3537 D PMS     : releaseWL(f98576c): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-30 17:29:30.671  3563  3563 D Launcher: waitUntilResume // bindAppsRemoved
,08-30 17:29:30.681  3657  8590 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest,
,08-30 17:29:30.691  4004  8583 W GmsApplication: Using Auth Proxy for data requests.
,08-30 17:29:30.691  3657  8590 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,08-30 17:29:30.701  4004  8583 W GmsApplication: Using Auth Proxy for data requests.
,08-30 17:29:30.711  3563  3563 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
08-30 17:29:30.711  3563  3563 I ContextualWidget: package com.test.thalitest removed
,08-30 17:29:30.711  3563  4180 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
,08-30 17:29:30.721  3563  8591 I ContextualWidget: com.test.thalitest is not installed
08-30 17:29:30.721  3563  8591 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,08-30 17:29:30.741  1126  4185 I ActivityManager: Start proc 8592:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
,08-30 17:29:30.741  8592  8592 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:29:30.741  8592  8592 W HTCLOG  : mask=0x18
,08-30 17:29:30.781  4004  8571 W DriveInitializer: Awaiting to be initialized,
,08-30 17:29:30.781  4004  8614 W DriveInitializer: Background init thread started
,08-30 17:29:30.791  3563  4180 I ContextualWidget: MFU.onDownloadDataSetChanged
08-30 17:29:30.791  3563  4180 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
08-30 17:29:30.791  3563  3563 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId 06a8375b-272d-4903-98c7-cd05387552aa, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
08-30 17:29:30.791  3563  3563 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 06a8375b-272d-4903-98c7-cd05387552aa, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,08-30 17:29:30.821  4004  8614 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
08-30 17:29:30.821  1126  3589 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.google.android.gms/files/
,08-30 17:29:30.851  1126  3070 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
,08-30 17:29:30.851  8592  8592 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
08-30 17:29:30.861  8592  8592 D IdefixUninstallListener: package_removed = com.test.thalitest
,08-30 17:29:30.861  4004  8614 W DriveInitializer: Background init thread ended,
,08-30 17:29:30.861  4004  8571 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 17:29:30.871  4004  8571 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 17:29:30.871  4004  8571 W HTCLOG  : mask=0x18
08-30 17:29:30.871  4004  8571 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55994c8d70
08-30 17:29:30.871  4004  8571 E DriveAsyncService: disk I/O error (code 3850)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:495)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	,at com.google.android.gms.drive.database.d.g(SourceFile:1406)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: ,	at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:30.871  4004  8571 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:29:30.891  8592  8592 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,08-30 17:29:30.891  8592  8592 W HTCLOG  : mask=0x18
,08-30 17:29:30.891  8592  8592 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.database.sqli,te.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 17:29:30.891  8592  8592 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 17:29:30.901  1126  1148 I ActivityManager: Killing 7983:com.htc.mobiledata:remote/u0a40 (adj 15): empty #17
08-30 17:29:30.901  8592  8592 W System.err: java.sql.SQLException: Getting a writable database from helper a@312709f1 failed
08-30 17:29:30.901  8592  8592 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
08-30 17:29:30.901  8592  8592 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
08-30 17:29:30.901  8592  8592 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-30 17:29:30.901  8592  8592 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-30 17:29:30.901  8592  8592 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-30 17:29:30.901  8592  8592 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-30 17:29:30.901  8592  8592 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 17:29:30.901  8592  8592 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:29:30.901  8592  8592 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:29:30.901  8592  8592 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 17:29:30.901  8592  8592 W System.err: 	at com.android.internal.os.Zy,goteInit.main(ZygoteInit.java:825)
08-30 17:29:30.901  8592  8592 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:30.901  8592  8592 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:30.901  8592  8592 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-30 17:29:30.901  8592  8592 W System.err: 	... 15 more
08-30 17:29:30.901  1126  1148 D Process : killProcessQuiet, pid=7983
08-30 17:29:30.901  1126  1148 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-30 17:29:30.901  4004  8617 I art     : Explicit concurrent mark sweep GC freed 13488(908KB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 4MB/6MB, paused 666us total 76.230ms
08-30 17:29:30.911  4004  4023 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-30 17:29:30.911  4004  4023 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-30 17:29:30.911  4004  4023 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-30 17:29:30.991  1126  3069 I ActivityManager: Recipient 7983
,08-30 17:29:31.011  6532  8624 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,08-30 17:29:31.041  1126  1149 I ActivityManager: Start proc 8625:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver,
,08-30 17:29:31.051  6532  8624 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-30 17:29:31.051  6532  8624 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 17:29:31.051  6532  8624 W HTCLOG  : mask=0x18
08-30 17:29:31.051  6532  8624 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x559939ee80
,08-30 17:29:31.061  6532  8624 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
,08-30 17:29:31.061  8625  8625 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:29:31.061  8625  8625 W HTCLOG  : mask=0x18
08-30 17:29:31.061  6532  8624 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-30 17:29:31.061  6532  8624 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6532
08-30 17:29:31.061  6532  8624 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.061  6532  8624 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.061  1126  1148 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
,08-30 17:29:31.061  6532  8624 D Process : killProcess, pid=6532,
,08-30 17:29:31.071  6532  8624 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
08-30 17:29:31.071  6532  8624 W HTCLOG  : use specified tag [Process], func [0].
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.071  1126  8643 E DropBoxManagerService: 	... 5 more
08-30 17:29:31.071  6532  8624 W HTCLOG  : mask=0x18
,08-30 17:29:31.081  3563  3923 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
,08-30 17:29:31.091  8625  8625 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 
,08-30 17:29:31.111  1126  1149 D PMS     : acquireWL(280d3fe9): PARTIAL_WAKE_LOCK  AsyncService 0x1 8431 10128 null,
08-30 17:29:31.111  8625  8648 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 17:29:31.111  8625  8648 W HTCLOG  : mask=0x18
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286),
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396),
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.111  8625  8648 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-30 17:29:31.111  8625  8648 E AndroidRuntime: Process: com.android.keychain, PID: 8625
08-30 17:29:31.111  8625  8648 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.111  8625  8648 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.111  1126  3591 D PMS     : releaseWL(280d3fe9): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-30 17:29:31.111  1126  3519 E ActivityManager: App crashed! Process: com.android.keychain
08-30 17:29:31.121  1126  3519 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 17:29:31.121  1126  3519 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.121  1126  3519 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.121  1126  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.121  1126  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.121  1126  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(Activit,yManagerService.java:12238)
08-30 17:29:31.121  1126  3519 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 17:29:31.121  1126  3519 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.121  1126  3519 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.121  1126  3519 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.121  1126  3519 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.121  1126  3519 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.121  1126  3519 W System.err: 	... 14 more
08-30 17:29:31.121  1126  3519 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.121  1126  3519 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.121  1126  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.121  1126  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.121  1126  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.121  1126  8650 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 17:29:31.121  1126  8650 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472570971131.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 17:29:31.121  1126  8650 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.121  1126  8650 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.121  1126  8650 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:29:31.121  1126  8650 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 17:29:31.121  1126  8650 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:29:31.121  1126  8650 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.121  1126  8650 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.121  1126  8650 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.121  1126  8650 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.121  1126  8650 E ErrorReport: 	... 4 more
08-30 17:29:31.121  1126  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 17:29:31.121  1126  3519 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.121  1126  3519 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 17:29:31.131  1126  1148 I ActivityManager: Recipient 6532
08-30 17:29:31.121  1126  3519 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.131  1126  3061 D WifiService: Client connection lost with reason: 4
08-30 17:29:31.121  1126  3519 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.121  1126  3519 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.121  1126  3519 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.121  1126  3519 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.131  1126  1148 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6532) has died
08-30 17:29:31.121  1126  3519 W System.err: 	... 14 more
08-30 17:29:31.131  1126  1148 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
08-30 17:29:31.121  8307  8307 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
08-30 17:29:31.131  1126  1148 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
08-30 17:29:31.131  1126  3654 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.131  8625  8648 D Process : killProcess, pid=8625
08-30 17:29:31.131  8625  8648 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 17:29:31.131  8625  8648 W HTCLOG  : use specified tag [Process], func [0].
08-30 17:29:31.131  8625  8648 W HTCLOG  : mask=0x18
08-30 17:29:31.131  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.131  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.131  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.131  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.131  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 17:29:31.131  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 17:29:31.131  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 17:29:31.131  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 17:29:31.131  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 17:29:31.131  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 17:29:31.131  1126  3654 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.131  1126  3654 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.131  1126  3654 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.131  8307  8307 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
08-30 17:29:31.131  1126  3654 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.131  1126  3654 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.131  1126  3654 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.131  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.131  1126  3654 W System.err: 	... 12 more
08-30 17:29:31.141  1126  3537 I ActivityManager: Start proc 8652:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
08-30 17:29:31.141  8307  8307 I DeviceManagement: WorkflowService: Starting workflow service
08-30 17:29:31.151  8307  8651 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@25c27e81] args=[Bundle[mParcelledData.dataSize=112]]
08-30 17:29:31.151  8307  8651 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-30 17:29:31.151  8307  8651 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
08-30 17:29:31.151  8307  8651 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-30 17:29:31.151  8652  8652 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:29:31.151  8652  8652 W HTCLOG  : mask=0x18
08-30 17:29:31.151  8307  8651 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,08-30 17:29:31.181  8307  8651 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
08-30 17:29:31.181  8307  8673 I DeviceManagement: SessionStateController: Checking invariants...
,08-30 17:29:31.211  1126  3537 I ActivityManager: Recipient 8625
,08-30 17:29:31.211  1126  3537 I ActivityManager: Process com.android.keychain (pid 8625) has died
08-30 17:29:31.211  1126  3537 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10918ms
,08-30 17:29:31.221  8652  8652 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,08-30 17:29:31.221  8652  8652 W HTCLOG  : mask=0x18
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.,
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 17:29:31.221  8652  8652 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:29:31.221  8652  8652 E AndroidRuntime: Process: com.android.documentsui, PID: 8652
08-30 17:29:31.221  8652  8652 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.221  8652  8652 ,E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: ,	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 17:29:31.221  8652  8652 E AndroidRuntime: 	... 9 more
08-30 17:29:31.221  1126  1148 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 17:29:31.221  1126  1148 E ActivityManager: App crashed! Process: com.android.documentsui
08-30 17:29:31.231  1126  1148 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.231  1126  1148 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456),
08-30 17:29:31.231  1126  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.231  1126  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.231  1126  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,08-30 17:29:31.231  1126  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 17:29:31.231  1126  1148 W System.err: 	,at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
,08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 17:29:31.231  1126  1148 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
,08-30 17:29:31.231  1126  1148 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.231  1126  1148 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.231  1126  1148 W System.err: 	at libcore.io.Posix.open(Native Method)
,08-30 17:29:31.231  1126  1148 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.231  1126  1148 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.231  1126  1148 W System.err: 	... 14 more
08-30 17:29:31.231  1126  1148 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system),
08-30 17:29:31.231  1126  1148 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.231  5629  5785 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
08-30 17:29:31.231  5629  5785 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
,08-30 17:29:31.231  5629  5785 W HTCLOG  : mask=0x18
08-30 17:29:31.241  1126  8675 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 17:29:31.241  1126  8675 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472570971245.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 17:29:31.241  1126  8675 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.241  1126  8675 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.241  1126  8675 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:29:31.241  1126  8675 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 17:29:31.241  1126  8675 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:29:31.241  1126  8675 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.241  1126  8675 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.241  1126  8675 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.241  1126  8675 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.241  1126  8675 E ErrorReport: 	... 4 more
08-30 17:29:31.231  5629  5785 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x55993699f0
08-30 17:29:31.241  1126  1149 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox,
08-30 17:29:31.231  1126  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.231  1126  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.231  1126  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.231  1126  1148 W System.err: 	,at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 17:29:31.231  1126  1148 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.231  1126  1148 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 17:29:31.231  1126  1148 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.231  1126  1148 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.231  1126  1148 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.231  1126  1148 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.231  1126  1148 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.231  1126  1148 W System.err: 	,... 14 more
08-30 17:29:31.241  1126  3654 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.241  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.241  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.241  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.241  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.241  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 17:29:31.241  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 17:29:31.241  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 17:29:31.241  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 17:29:31.241  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 17:29:31.241  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 17:29:31.241  1126  3654 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.241  1126  3654 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.241  1126  3654 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.241  1126  3654 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.241  1126  3654 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.241  1126  3654 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.241  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.241  1126  3654 W System.err: 	... 12 more
08-30 17:29:31.241  5629  5785 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-30 17:29:31.241  5629  5785 E AndroidRuntime: Process: android.process.media, PID: 5629
08-30 17:29:31.241  5629  5785 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.os.Handler.,dispatchMessage(Handler.java:95)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.241  5629  5785 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.241  1126  1149 E ActivityManager: App crashed! Process: android.process.media
08-30 17:29:31.241  1126  1149 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.241  1126  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.241  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.241  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.241  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 17:29:31.241  1126  1149 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 17:29:31.241  1126  1149 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.241  8652  8652 D Process : killProcess, pid=8652
08-30 17:29:31.241  1126  1149 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.241  8652  8652 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 17:29:31.241  1126  1149 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.241  1126  1149 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.241  1126  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.241  1126  1149 W System.err: 	... 14 more
08-30 17:29:31.241  8652  8652 W HTCLOG  : use specified tag [Process], func [0].
08-30 17:29:31.241  8652  8652 W HTCLOG  : mask=0x18
08-30 17:29:31.241  1126  1149 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.241  1126  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.241  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.261  1126  1161 I ActivityManager: Start proc 8677:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
08-30 17:29:31.241  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.241  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStr,eam.java:116)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 17:29:31.261  1126  8676 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 17:29:31.261  1126  8676 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472570971262.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 17:29:31.261  1126  8676 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.261  1126  8676 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.261  1126  8676 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:29:31.261  1126  8676 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 17:29:31.261  1126  8676 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:29:31.261  1126  8676 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.261  1126  8676 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.261  1126  8676 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.261  1126  8676 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.261  1126  8676 E ErrorReport: 	... 4 more
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 17:29:31.241  1126  1149 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.241  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 17:29:31.241  1126  1149 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.241  1126  1149 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.241  1126  1149 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.241  1126  1149 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.241  1126  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.241  1126  1149 W System.err: 	... 14 more
08-30 17:29:31.241  5629  5785 D Process : killProcess, pid=5629
08-30 17:29:31.241  5629  5785 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 17:29:31.241  5629  5785 W HTCLOG  : use specified tag [Process], func [0].
08-30 17:29:31.241  5629  5785 W HTCLOG  : mask=0x18
08-30 17:29:31.251  1126  3654 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.251  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.251  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.251  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.251  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.251  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 17:29:31.251  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 17:29:31.251  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 17:29:31.251  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 17:29:31.251  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 17:29:31.251  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 17:29:31.251  1126  3654 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.251  1126  3654 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.251  1126  3654 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.251  1126  3654 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.251  1126  3654 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.251  1126  3654 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.251  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.251  1126  3654 W System.err: 	... 12 more
08-30 17:29:31.271   555   555 I art     : Explicit concurrent mark sweep GC freed 8644(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 107us total 18.379ms
08-30 17:29:31.281  8677  8677 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:29:31.281  8677  8677 W HTCLOG  : mask=0x18
08-30 17:29:31.291   494   494 E lowmemorykiller: Error writing /proc/5629/oom_score_adj; errno=22
08-30 17:29:31.291  1126  3524 W HTCLOG  : use specified tag [JavaBinder], func [0].
08-30 17:29:31.291  1126  3524 W HTCLOG  : mask=0x18
08-30 17:29:31.291  1126  3524 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-30 17:29:31.291   555   555 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 129us total 17.543ms
,08-30 17:29:31.301  1126  3538 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-30 17:29:31.301  1126  3538 I ActivityManager: Recipient 5629
08-30 17:29:31.301  8307  8673 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 17:29:31.301  1126  3538 I ActivityManager: Process android.process.media (pid 5629) has died
08-30 17:29:31.301  8307  8673 W HTCLOG  : mask=0x18
08-30 17:29:31.301  1126  3538 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 10830ms
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-30 17:29:31.301  8307  8673 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:29:31.301  3336  3370 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
08-30 17:29:31.311  1126  3537 I ActivityManager: Killing 7708:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-30 17:29:31.301  8307  8673 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.301  8307  8651 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.301  8307  8651 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.311  8307  8651 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.311  3185  3185 I NotificationStackScrollLayout: setBlockTouchEnabled:false
08-30 17:29:31.321  1126  3591 I ActivityManager: Recipient 7708
08-30 17:29:31.311  8307  8651 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@25c27e81]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.311  8307  8651 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.311   555   555 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 123us total 16.486ms
08-30 17:29:31.311  8307  8307 I DeviceManagement: WorkflowService: Stopping workflow service
08-30 17:29:31.311  1126  3537 D Process : killProcessQuiet, pid=7708
08-30 17:29:31.311  1126  3537 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-30 17:29:31.361  1126  3538 I ActivityManager: Recipient 8652
,08-30 17:29:31.421  1126  3538 I ActivityManager: Process com.android.documentsui (pid 8652) has died,
,08-30 17:29:31.431  8677  8677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
,08-30 17:29:31.461  1126  1149 I ActivityManager: Start proc 8700:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver,
08-30 17:29:31.481  8700  8700 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:29:31.481  8700  8700 W HTCLOG  : mask=0x18
,08-30 17:29:31.491  8677  8699 D PowerUtils: getUserIdOfProcess, curUserId = 0
,08-30 17:29:31.491  8677  8699 D PowerUtils: isRunningUnderOwner, isOwner = true
,08-30 17:29:31.501  8677  8699 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,08-30 17:29:31.501  8677  8699 D PowerUsageService: removed uid = 10142
,08-30 17:29:31.511  8677  8699 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,08-30 17:29:31.511  8677  8699 W HTCLOG  : mask=0x18
,08-30 17:29:31.521  8677  8699 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.,
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182),
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.521  8677  8699 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
08-30 17:29:31.521  8677  8699 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 8677
08-30 17:29:31.521  8677  8699 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-30 17:,29:31.521  8677  8699 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.521  8677  8699 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.521  1126  1149 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 17:29:31.521  1126  1149 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
08-30 17:29:31.531  1126  8721 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 17:29:31.531  1126  8721 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472570971534.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 17:29:31.531  1126  8721 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.531  1126  8721 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.531  1126  8721 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:29:31.531  1126  8721 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 17:29:31.531  1126  8721 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:29:31.531  1126  8721 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.531  1126  8721 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.531  1126  8721 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.531  1126  8721 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.531  1126  8721 E ErrorReport: 	... 4 more
08-30 17:29:31.521  1126  1149 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.521  1126  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.521  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.521  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.521  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 17:29:31.521  1126  1149 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityMana,gerService.java:2379)
08-30 17:29:31.521  1126  1149 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.521  1126  1149 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.521  1126  1149 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.521  1126  1149 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.521  1126  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.521  1126  1149 W System.err: 	... 14 more
08-30 17:29:31.521  1126  1149 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.521  1126  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.521  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.521  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.521  1126  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 17:29:31.521  1126  1149 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.521  1126  1149 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 17:29:31.521  1126  1149 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.521  1126  1149 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.521  1126  1149 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.521  1126  1149 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.521  1126  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.521  1126  1149 W System.err: 	... 14 more
08-30 17:29:31.531  1126  3654 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.531  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.531  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.531  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.531  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.531  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 17:29:31.531  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 17:29:31.531  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 17:29:31.531  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 17:29:31.531  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 17:29:31.531  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 17:29:31.531  1126  3654 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.531  1126  3654 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.531  1126  3654 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.531  8677  8699 D Process : killProcess, pid=8677
08-30 17:29:31.531  1126  3654 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.531  8677  8699 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 17:29:31.531  8677  8699 W HTCLOG  : use specified tag [Process], func [0].
08-30 17:29:31.531  8677  8699 W HTCLOG  : mask=0x18
08-30 17:29:31.541  1126  3654 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.541  1126  3654 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.541  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.541  1126  3654 W System.err: 	... 12 more
08-30 17:29:31.561  8700  8722 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 17:29:31.561  8700  8722 W HTCLOG  : mask=0x18
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.561  8700  8722 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.561  8700  8700 V UpdaterAPK | DownloadService: Service onStart
08-30 17:29:31.561  8700  8723 V UpdaterAPK | DownloadService: Updating for startId 1
08-30 17:29:31.561  8700  8722 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-30 17:29:31.561  8700  8722 E AndroidRuntime: Process: com.htc.updater, PID: 8700
08-30 17:29:31.561  8700  8722 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.561  8700  8722 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.571  1126  3537 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 17:29:31.571  1126  3537 E ActivityManager: App crashed! Process: com.htc.updater
08-30 17:29:31.571  1126  3537 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.571  1126  3537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.571  1126  3537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.571  1126  3537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.571  1126,  3537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 17:29:31.571  1126  3537 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 17:29:31.571  1126  3537 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.571  1126  3537 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.571  1126  3537 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.571  1126  3537 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.571  1126  3537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.571  1126  3537 W System.err: 	... 14 more
08-30 17:29:31.571  1126  3537 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.571  1126  8725 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 17:29:31.571  1126  8725 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472570971579.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 17:29:31.571  1126  8725 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.571  1126  8725 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.571  1126  8725 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:29:31.571  1126  8725 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 17:29:31.571  1126  8725 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:29:31.571  1126  8725 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.571  1126  8725 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.571  1126  8725 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.571  1126  8725 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.571  1126  8725 E ErrorReport: 	... 4 more
08-30 17:29:31.571  1126  3537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.571  1126  3537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.571  1126  3537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.571  1126  3537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 17:29:31.571  1126  3537 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 17:29:31.571  1126  3537 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 17:29:31.571  1126  3537 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 17:29:31.571  1126  3537 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.571  1126  3537 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.571  1126  3537 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.571  1126  3537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.571  1126  3537 W System.err: 	... 14 more
08-30 17:29:31.571  1126  3654 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 17:29:31.571  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.571  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.571  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 17:29:31.571  1126  3654 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 17:29:31.571  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 17:29:31.571  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 17:29:31.571  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 17:29:31.571  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 17:29:31.571  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 17:29:31.571  1126  3654 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 17:29:31.571  1126  3654 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.571  1126  3654 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.571  1126  3654 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:29:31.571  1126  3654 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.571  1126  3654 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.571  1126  3654 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.571  1126  3654 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.571  1126  3654 W System.err: 	... 12 more
08-30 17:29:31.571  8700  8722 D Process : killProcess, pid=8700
08-30 17:29:31.571  8700  8722 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 17:29:31.571  3610  3610 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 17:29:31.571  8700  8722 W HTCLOG  : use specified tag [Process], func [0].
08-30 17:29:31.571  8700  8722 W HTCLOG  : mask=0x18
08-30 17:29:31.581  3610  3610 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 17:29:31.581  3610  3610 D c       : Getting all permits...
08-30 17:29:31.581  3610  3610 D a       : Opening database...
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/auth.proximity.permit_store'.
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.b.a.a(SourceFile:52)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.b.c.a(SourceFile:185)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.authorization.bt.b.a(SourceFile:217)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter.onReceive(SourceFile:239)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 17:29:31.591  3610  3610 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 17:29:31.591  1126  3589 I ActivityManager: Recipient 8677
08-30 17:29:31.591  3610  3610 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:29:31.591  3610  3610 E AndroidRuntime: Process: com.google.process.gapps, PID: 3610
08-30 17:29:31.591  3610  3610 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.b.a.a(SourceFile:52)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.b.c.a(SourceFile:185)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.authorization.bt.b.a(SourceFile:217)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter.onReceive(SourceFile:239)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 17:29:31.591  3610  3610 E AndroidRuntime: 	... 9 more
08-30 17:29:31.591  1126  3589 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 8677) has died
08-30 17:29:31.591  1126  3591 E ActivityManager: App crashed! Process: com.google.process.gapps
08-30 17:29:31.591  1126  3589 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 20540ms
08-30 17:29:31.591  3610  3610 D Process : killProcess, pid=3610
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:29:31.591  1126  8726 E DropBoxManagerService: 	... 5 more
08-30 17:29:31.591  3610  3610 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
08-30 17:29:31.591  3610  3610 W HTCLOG  : use specified tag [Process], func [0].
08-30 17:29:31.591  3610  3610 W HTCLOG  : mask=0x18
08-30 17:29:31.591  4004  4004 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
08-30 17:29:31.611  1126  3591 I ActivityManager: Recipient 3610
08-30 17:29:31.611  4004  4004 I GoogleURLConnFactory: binding HttpService
,08-30 17:29:31.691  1126  1148 I ActivityManager: Recipient 8700
,08-30 17:29:31.821  1126  3591 I ActivityManager: Process com.google.process.gapps (pid 3610) has died
08-30 17:29:31.821  1126  3591 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 30310ms
08-30 17:29:31.821  1126  3591 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 40310ms
,08-30 17:29:31.861  1126  3589 I ActivityManager: Start proc 8729:com.google.process.gapps/u0a19 for service com.google.android.gms/.gcm.http.GoogleHttpService,
08-30 17:29:31.861  1126  1148 I ActivityManager: Process com.htc.updater (pid 8700) has died
08-30 17:29:31.881  8729  8729 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 17:29:31.861  1126  1148 W ActivityManager: Scheduling restart of crashed service com.htc.updater/.download.DownloadService in 50265ms
08-30 17:29:31.881  8729  8729 W HTCLOG  : mask=0x18
08-30 17:29:31.891  4004  8728 D LocationInitializer: Restart initialization of location
,08-30 17:29:31.941  8729  8729 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 17:29:31.941  8729  8729 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 17:29:31.961  8729  8729 I MultiDex: VM with version 2.1.0 has multidex support,
08-30 17:29:31.961  8729  8729 I MultiDex: install
08-30 17:29:31.961  8729  8729 I MultiDex: VM has multidex support, MultiDex support library is disabled.

```
