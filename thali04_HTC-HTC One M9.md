#### Test 833712394bbb446_thali04_HTC-HTC One M9 Logs


```
--------- beginning of main
08-31 03:05:24.471  1113  3568 D Process : killProcessQuiet, pid=7928
08-31 03:05:24.471  1113  3568 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
--------- beginning of system
08-31 03:05:24.471  1113  3568 I ActivityManager: Killing 7928:com.google.android.talk/u0a103 (adj 15): empty #17
08-31 03:05:24.481  8264  8264 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
08-31 03:05:24.481  8319  8339 I CAR.SERVICE: listener not found in list
08-31 03:05:24.531  1113  3831 I ActivityManager: Recipient 7928
,08-31 03:05:24.601  6054  8379 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-31 03:05:24.621  1113  3588 I ActivityManager: Start proc 8380:com.htc.cs.dm/u0a89 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
08-31 03:05:24.631  8380  8380 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:24.631  8380  8380 W HTCLOG  : mask=0x18
08-31 03:05:24.691  8380  8380 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8380 dbg=false s=true
08-31 03:05:24.691  8380  8380 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
08-31 03:05:24.701  1113  1134 I ActivityManager: Start proc 8404:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-31 03:05:24.711  1113  1134 D Process : killProcessQuiet, pid=7964
08-31 03:05:24.711  1113  1134 I ActivityManager: Killing 7964:com.htc.calendar/u0a6 (adj 15): empty #17
08-31 03:05:24.711  1113  1134 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
08-31 03:05:24.711  8404  8404 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:24.711  8404  8404 W HTCLOG  : mask=0x18
08-31 03:05:24.751  8391  8391 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-31 03:05:24.751  8391  8391 W HTCLOG  : mask=0x18
08-31 03:05:24.821  3179  3179 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-31 03:05:24.831  1113  3069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-31 03:05:24.821  3179  3179 D wpa_supplicant: wlan0: nl80211: New scan results available
08-31 03:05:24.821  3179  3179 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-31 03:05:24.821  3179  3179 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-31 03:05:24.821  3179  3179 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-31 03:05:24.821  3179  3179 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-31 03:05:24.821  3179  3179 D wpa_supplicant: wlan0: Scan completed in 3.594390 seconds
08-31 03:05:24.821  3179  3179 D wpa_supplicant: nl80211: Received scan results (54 BSSes)
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-48
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-49
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-50
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-60
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-60
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-60
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-60
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-69
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-70
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-70
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d4 freq=2437 level=-73
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d5 freq=2437 level=-73
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d0 freq=2437 level=-73
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d6 freq=2437 level=-73
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-78
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:36 freq=2412 level=-74
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d2 freq=2437 level=-74
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-74
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-74
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-79
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-79
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:35 freq=2412 level=-75
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:34 freq=2412 level=-75
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-75
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:96 freq=2462 level=-82
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:9a freq=5180 level=-87
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:90 freq=2462 level=-83
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:92 freq=2462 level=-83
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:da freq=5180 level=-88
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:db freq=5180 level=-88
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:9f freq=5180 level=-88
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:5f freq=5180 level=-88
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-84
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:99 freq=5180 level=-89
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:59 freq=5180 level=-89
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:5b freq=5180 level=-89
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:5a freq=5180 level=-89
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 00:fe:c8:73:02:00 freq=2462 level=-85
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 00:fe:c8:73:02:05 freq=2462 level=-85
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:52 freq=2437 level=-86
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:56 freq=2437 level=-86
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-69
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-70
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-73
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-74
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-74
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-79
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-75
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-81
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:91 freq=2462 level=-83
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:9e freq=5180 level=-88
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:de freq=5180 level=-88
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-84
08-31 03:05:24.831  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:21:47:53 freq=2437 level=-85
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: BSS: Start scan result update 6
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 82 BSSID 84:b2:61:1c:62:da SSID '\x00'
08-31 03:05:24.831  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 83 BSSID 84:b2:61:21:47:52 SSID '\x00'
08-31 03:05:24.831  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 84 BSSID 84:b2:61:21:47:56 SSID '\x00'
08-31 03:05:24.831  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 85 BSSID 84:b2:61:1a:ce:71 SSID '\x00'
08-31 03:05:24.831  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 68 BSSID 84:b2:61:1c:62:d9 SSID '\x00' due to no match in scan
08-31 03:05:24.831  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 75 BSSID 84:b2:61:21:47:55 SSID '\x00' due to no match in scan
08-31 03:05:24.831  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:24.831  3179  3179 D wpa_supplicant: BSS: last_scan_res_used=54/64
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: Scan-only results received
08-31 03:05:24.831  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:24.831  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: Radio work 'scan'@0x555b80cca0 done in 3.639189 seconds
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-31 03:05:24.831  3179  3179 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: Cancelling scan request
08-31 03:05:24.831  3179  3179 D wpa_supplicant: PNO: No configured SSIDs
08-31 03:05:24.831  1113  3069 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-31 03:05:24.831  3179  3179 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-31 03:05:24.851  1113  3577 I ActivityManager: Recipient 7964
08-31 03:05:24.931  8391  8426 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-31 03:05:24.931  3593  3964 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-31 03:05:24.931  3593  3964 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@395d2433 +
08-31 03:05:24.931  3593  3964 I Prism.WidgetManager: onLoadItems() +
08-31 03:05:24.931  3179  3179 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-31 03:05:24.931  8391  8426 W HTCLOG  : mask=0x18
08-31 03:05:24.931  8391  8426 E cutils-trace: Error opening trace file: Permission denied (13)
08-31 03:05:24.951  3179  3179 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-31 03:05:24.951  1113  3069 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-31 03:05:24.951  1113  1113 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 17
08-31 03:05:24.951  4416  4416 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-31 03:05:24.951  4416  5879 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-31 03:05:24.961  1113  3575 D PMS     : acquireWL(267bbc60): PARTIAL_WAKE_LOCK  Icing 0x1 4108 10019 null
08-31 03:05:24.961  3593  3964 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
08-31 03:05:25.011  6054  8379 I ApplicationLogger: canRun() : Opted Out
08-31 03:05:25.011  6054  8379 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 409 ms] updated apps [took 409 ms] 
08-31 03:05:25.011  1113  3568 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-31 03:05:25.011  1113  1135 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-31 03:05:25.041  8391  8391 D CustomizationManager: ====startRecUseTime====
08-31 03:05:25.041  8391  8391 D htc.customization.log.level:  is 
08-31 03:05:25.041  8391  8391 W CustomizationLogLevel: Level value is invalid, use default level 2
08-31 03:05:25.061  8404  8404 D DocsApplication: Plugin installer initialized.
08-31 03:05:25.061  1113  3820 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-31 03:05:25.071  8404  8404 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1fc55840 com.google.android.apps.docs}
08-31 03:05:25.081  3569  4234 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-31 03:05:25.081  3569  4234 D PhoneApp: -- N1 =0
08-31 03:05:25.081  3569  4234 D PhoneApp: -- N2 =0
08-31 03:05:25.081  3569  4234 D PhoneApp: -- N3 =0
08-31 03:05:25.091  8404  8404 D TAG     : onCreate()
08-31 03:05:25.101  8404  8404 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-31 03:05:25.111  1113  3577 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-31 03:05:25.121  8391  8391 D CustomizationManager:  Read ACC file spent 0.037 (s)
08-31 03:05:25.131  8391  8391 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: Parsing tag category name = application
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: Parsing tag category name = system
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: Parsing tag category name = Settings
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: Parsing tag category name = ACC
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-31 03:05:25.131  8391  8391 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-31 03:05:25.131  8391  8391 D CustomizationManager:  Read CID file spent 0.087 (s)
08-31 03:05:25.131  8391  8391 D CustomizationManager:  All configurations done spent 0.087 (s)
08-31 03:05:25.161  3593  3964 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 03:05:25.171  1113  1135 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8391 on display 0
08-31 03:05:25.181  1113  1180 D PMS     : acquireHCC(3ffdf5ea): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1113 1000 null
08-31 03:05:25.181  1113  1180 D PMS     : acquireHCC(3d0b30db): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1113 1000 null
08-31 03:05:25.181  1113  1135 V WindowManager: addAppToken: AppWindowToken{396cde51 token=Token{b08b778 ActivityRecord{1e8179d5 u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-31 03:05:25.191  1113  1135 I ActivityManager: Start proc 8442:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-31 03:05:25.191  8391  8391 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-31 03:05:25.191  8391  8391 W HTCLOG  : mask=0x18
08-31 03:05:25.191  8391  8440 W HTCLOG  : use specified tag [Vector], func [0].
08-31 03:05:25.191  8391  8441 W HTCLOG  : use specified tag [Vector], func [0].
08-31 03:05:25.191  8391  8441 W HTCLOG  : mask=0x18
08-31 03:05:25.191  8391  8440 W HTCLOG  : mask=0x18
08-31 03:05:25.201  8442  8442 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:25.201  8442  8442 W HTCLOG  : mask=0x18
08-31 03:05:25.211  3363  3363 D DotMatrix: [EventService]  onDisplayChanged: 0
08-31 03:05:25.211  1113  1113 V ActivityManager: Display changed displayId=0
08-31 03:05:25.211  3363  3363 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-31 03:05:25.221  1113  3588 D ActivityManager: screenshot for ActivityRecord{1e8179d5 u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-31 03:05:25.241  3593  3593 I TrimMemoryManager: [trimMemory] 20
08-31 03:05:25.261  8442  8442 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-31 03:05:25.321  8442  8442 I LibraryLoader: Time to load native libraries: 30 ms (timestamps 6196-6226)
08-31 03:05:25.321  8442  8442 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 03:05:25.331  3593  3964 I Prism.WidgetManager: onLoadItems() -
08-31 03:05:25.331  3593  3964 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@395d2433 -
08-31 03:05:25.331  8442  8442 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ac7b86c}
08-31 03:05:25.331  8442  8442 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 03:05:25.341  8442  8442 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 03:05:25.341  8442  8442 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 03:05:25.341  8442  8442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 03:05:25.351  8442  8442 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 03:05:25.381  8442  8465 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
08-31 03:05:25.391  5515  5535 D BluetoothAdapterService(727959742): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@542d3a3
08-31 03:05:25.401  8442  8442 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-31 03:05:25.401  8442  8442 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
08-31 03:05:25.401  8442  8442 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
,08-31 03:05:25.411  8442  8442 W HTCLOG  : use specified tag [libEGL], func [3].
08-31 03:05:25.411  8442  8442 W HTCLOG  : mask=0x18
08-31 03:05:25.411  8442  8442 W HTCLOG  : use specified tag [libEGL], func [3].
08-31 03:05:25.411  8442  8442 W HTCLOG  : mask=0x18
08-31 03:05:25.411  8442  8442 I Adreno  : QUALCOMM build                   : 065751b, 
08-31 03:05:25.411  8442  8442 I Adreno  : Build Date                       : 04/15/15
08-31 03:05:25.411  8442  8442 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-31 03:05:25.411  8442  8442 I Adreno  : Local Branch                     : 
08-31 03:05:25.411  8442  8442 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-31 03:05:25.411  8442  8442 I Adreno  : Remote Branch                    : NONE
08-31 03:05:25.411  8442  8442 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
08-31 03:05:25.481  8442  8475 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
08-31 03:05:25.501  8442  8442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 03:05:25.511  8442  8442 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 03:05:25.521  8442  8442 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
08-31 03:05:25.521  8442  8442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 03:05:25.521  8442  8442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 03:05:25.561  8442  8486 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-31 03:05:25.561  8442  8486 W HTCLOG  : mask=0x18
08-31 03:05:25.561  1113  3831 V WindowManager: Adding window Window{1136a3f9 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{25638207 u0 com.htc.launcher/com.htc.launcher.Launcher})
08-31 03:05:25.571  1113  3638 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-31 03:05:25.601  8442  8442 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
08-31 03:05:25.601  8442  8442 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-31 03:05:25.601  8442  8442 W HTCLOG  : mask=0x18
08-31 03:05:25.601  8442  8442 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-31 03:05:25.601  8442  8442 W HTCLOG  : mask=0x18
08-31 03:05:25.601  8442  8486 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-31 03:05:25.601  8442  8486 W HTCLOG  : mask=0x18
08-31 03:05:25.601  8442  8486 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-31 03:05:25.601  8442  8486 W HTCLOG  : mask=0x18
08-31 03:05:25.601  8442  8486 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-31 03:05:25.601  8442  8486 W HTCLOG  : mask=0x18
08-31 03:05:25.611  8442  8486 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-31 03:05:25.611  8442  8486 W HTCLOG  : mask=0x18
08-31 03:05:25.611  8442  8486 W HTCLOG  : use specified tag [Surface], func [3].
08-31 03:05:25.611  8442  8486 W HTCLOG  : mask=0x18
08-31 03:05:25.611  8442  8486 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-31 03:05:25.611  8442  8486 W HTCLOG  : mask=0x18
08-31 03:05:25.621  8442  8486 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-31 03:05:25.621  8442  8486 W HTCLOG  : mask=0x18
08-31 03:05:25.671  1113  1171 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +457ms (total +495ms)
08-31 03:05:25.711   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
08-31 03:05:25.721  8442  8442 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8442
08-31 03:05:25.781  8442  8442 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-31 03:05:25.811  8404  8495 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-31 03:05:25.811  8404  8495 W HTCLOG  : mask=0x18
08-31 03:05:25.831  8442  8489 D jxcore_app_log: JniHelper::setJavaVM(0xab7a5b70), pthread_self() = -1401915360
08-31 03:05:25.831  8442  8489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 03:05:25.831  8442  8489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 03:05:25.831  8442  8489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 03:05:25.831  8442  8489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 03:05:25.831  8442  8489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 03:05:25.831  8442  8489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31cd141b added. We now have 1 listener(s)
08-31 03:05:25.841  1113  3588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-31 03:05:25.841  8442  8489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
08-31 03:05:25.841  8442  8489 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-31 03:05:25.841  8442  8489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 03:05:25.841  8442  8489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 03:05:25.841  8442  8489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f632f6 added. We now have 1 listener(s)
08-31 03:05:25.841  8442  8489 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 03:05:25.841  8442  8489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 03:05:25.841  1113  3101 D WifiService: New client listening to asynchronous messages
08-31 03:05:25.841  8442  8489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 03:05:25.841  8442  8489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 03:05:25.841  8442  8489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 03:05:25.841  8442  8489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 03:05:25.851  8442  8489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 03:05:25.851  1113  3109 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-31 03:05:25.851  8442  8489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
08-31 03:05:25.851  5515  5535 D BluetoothAdapterService(727959742): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@542d3a3
08-31 03:05:25.851  8442  8489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 03:05:25.851  8442  8489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 03:05:25.851  8442  8489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:05:25.851  8442  8489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 03:05:25.851  8442  8489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:05:25.851  8442  8489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:05:25.851  8442  8489 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 03:05:25.851  8442  8489 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 03:05:25.851  8442  8489 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 03:05:25.851  8442  8489 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 03:05:25.851  8442  8489 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 03:05:25.851  8442  8489 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 03:05:25.851  8442  8442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 03:05:25.871  1113  3840 D Process : killProcessQuiet, pid=7562
08-31 03:05:25.871  1113  3840 I ActivityManager: Start proc 8502:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
08-31 03:05:25.871  1113  3840 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
08-31 03:05:25.871  1113  3840 I ActivityManager: Killing 7562:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
08-31 03:05:25.871  8502  8502 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:25.871  8502  8502 W HTCLOG  : mask=0x18
08-31 03:05:25.941  8442  8442 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-31 03:05:26.011  4108  5614 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-31 03:05:26.011  1113  3831 I ActivityManager: Recipient 7562
08-31 03:05:26.081  1113  3056 D PMS     : acquireWL(3f75b08f): PARTIAL_WAKE_LOCK  *alarm* 0x1 1113 1000 WorkSource{1000}
08-31 03:05:26.081  1113  3056 V AlarmManager: sending alarm PendingIntent{3e81ef1c: PendingIntentRecord{3fd58725 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=81162, Int=0
08-31 03:05:26.081  8404  8404 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-31 03:05:26.081  1113  3056 V AlarmManager: sending alarm PendingIntent{28b600fa: PendingIntentRecord{526c6ab android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1472605523267, Int=0
08-31 03:05:26.081  1113  3056 V AlarmManager: sending alarm PendingIntent{154ce108: PendingIntentRecord{32f0c5cd com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=86083, Int=0
08-31 03:05:26.091  8502  8502 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 03:05:26.101  4108  5614 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-31 03:05:26.171  1113  1180 D PMS     : releaseHCC(3ffdf5ea): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,08-31 03:05:26.171  1113  1180 D PMS     : releaseHCC(3d0b30db): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-31 03:05:26.271  4108  5614 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
,08-31 03:05:26.281  8442  8501 W jxcore-log: Initializing JXcore engine
,08-31 03:05:26.281  1113  3840 D PMS     : releaseWL(267bbc60): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-31 03:05:26.281  8442  8501 W jxcore-log: JXcore engine is ready
,08-31 03:05:26.341  8442  8501 W jxcore-log: Starting JXcore engine,
,08-31 03:05:26.351  1113  3568 D PMS     : acquireWL(6d332c6): PARTIAL_WAKE_LOCK  AsyncService 0x1 8502 10128 null,
,08-31 03:05:26.361  1113  3831 D PMS     : releaseWL(6d332c6): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,08-31 03:05:26.401  3467  3467 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-31 03:05:26.411  3467  3467 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-31 03:05:26.411  3467  3467 D c       : Getting all permits...
08-31 03:05:26.411  3467  3467 D a       : Opening database...
,08-31 03:05:26.411  3467  3467 D a       : Opening database auth.proximity.permit_store...
,08-31 03:05:26.411  3467  3467 D a       : Closing database...
,08-31 03:05:26.421  4108  4108 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-31 03:05:26.441  8442  8501 W jxcore-log: Platform android
08-31 03:05:26.441  8442  8501 W jxcore-log: 
08-31 03:05:26.441  1113  1113 D PMS     : acquireWL(1a5305b4): PARTIAL_WAKE_LOCK  *backup* 0x1 1113 1000 null
08-31 03:05:26.441  8442  8501 W jxcore-log: Process ARCH arm
08-31 03:05:26.441  8442  8501 W jxcore-log: 
08-31 03:05:26.441  1113  1113 D PMS     : releaseWL(3f75b08f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-31 03:05:26.441  7681  7681 D AlarmReceiver: ACTION_RESTART_INTENT
08-31 03:05:26.441  7681  7681 D LocalBluetoothProfile: getPriorityOnValue = 100
08-31 03:05:26.441  7681  7681 D LocalBluetoothProfile: getPriorityOffValue = 0
08-31 03:05:26.441  7681  7681 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-31 03:05:26.441  7681  7681 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-31 03:05:26.451  1113  3139 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
08-31 03:05:26.451  4108  8533 D LocationInitializer: Restart initialization of location
08-31 03:05:26.451  1113  3139 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
,08-31 03:05:26.451  1113  3139 D PMS     : releaseWL(1a5305b4): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,08-31 03:05:26.471  7681  8535 D HtcModeClient: start the htcmodeservice thread
,08-31 03:05:26.471  7681  8535 D HtcModeClient: initCanAgent
,08-31 03:05:26.471  7681  8535 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-31 03:05:26.481  7681  8535 D HtcModeClient: sense info: version = none, id = 2
,08-31 03:05:26.481  7681  8535 D HtcModeClient: display info: width = 1080, height = 1776,
08-31 03:05:26.481  7681  8535 D HtcModeClient: display info: mode = 10
,08-31 03:05:26.571  7681  7681 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,08-31 03:05:26.571  7681  7681 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-31 03:05:26.571  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
08-31 03:05:26.571  7681  7681 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-31 03:05:26.571  7681  7681 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-31 03:05:26.571  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = false
08-31 03:05:26.571  7681  7681 D HtcModeClient: connectState: Force_AWAKE = false
08-31 03:05:26.571  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = true
08-31 03:05:26.571  7681  7681 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-31 03:05:26.621  8442  8501 I jxcore-log: JXcore Cordova bridge is ready!,
08-31 03:05:26.621  8442  8501 I jxcore-log: 
08-31 03:05:26.621  8442  8501 W jxcore-log: JXcore engine is started
,08-31 03:05:26.631  8442  8489 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
08-31 03:05:26.631  8442  8442 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 03:05:28.551  8264  8279 E AndroidHttpClient: Leak found,
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	,at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155),
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:28.551  8264  8279 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-31 03:05:28.581  7681  8535 I HtcModeClient: handler message = 4011,
08-31 03:05:28.581  7681  8535 D HtcModeClient: getConnectionCheckCount first 0
,08-31 03:05:28.591  7681  8535 D HtcModeClient: getConnectionCheckCount count = 7
08-31 03:05:28.591  7681  8535 E HtcModeClient: Check connection and retry 8 times.
,08-31 03:05:28.591  7681  8535 D HtcModeClient: setConnectionCheckCount count = 8
,08-31 03:05:28.591  7681  8535 D HtcModeClient: setupRestart delayedTime = 3000,
,08-31 03:05:28.591  7681  7681 D HtcModeClient: setBtPriority priority = on,
08-31 03:05:28.591  7681  7681 D HtcModeClient: unbindBlueToothService
,08-31 03:05:28.601  7681  7681 D HtcModeClient: Don't start project servcice
,08-31 03:05:28.601  7681  7681 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-31 03:05:28.601  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
08-31 03:05:28.601  7681  7681 D SilentMusic: call stop
08-31 03:05:28.601  7681  7681 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-31 03:05:28.601  7681  8536 W CANMesgAgentLocalSocket: read the terminate packet, so break,
,08-31 03:05:28.611  7681  7681 D HtcModeClient: onDestroy,
,08-31 03:05:28.921  1113  1113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,08-31 03:05:29.521  8319  8319 D Process : killProcess, pid=8319
,08-31 03:05:29.521  8319  8319 D Process : com.google.android.gms.car.gt.run:127 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,08-31 03:05:29.531  8319  8319 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:29.531  8319  8319 W HTCLOG  : mask=0x18
,08-31 03:05:29.571  3467  8540 W HTCLOG  : use specified tag [JavaBinder], func [0].,
08-31 03:05:29.571  3467  8540 W HTCLOG  : mask=0x18,
08-31 03:05:29.571  3467  8540 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 03:05:29.581  1113  3840 I ActivityManager: Recipient 8319,
08-31 03:05:29.581  1113  3840 I ActivityManager: Process com.google.android.gms:car (pid 8319) has died
,08-31 03:05:29.841  8404  8404 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().,
,08-31 03:05:30.131  1113  3588 D PMS     : releaseWL(3423d43f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,08-31 03:05:30.811  8404  8494 I GAV2    : Thread[GAThread,5,main]: No campaign data found.,
,08-31 03:05:33.081  4108  8206 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1V49NceOM0yFDyEsh7yFEGUYmwCFmI42guEVDAHj3yxKn83nol6xUptlzRy0pYsK1V-YlpXDQAh5lEhOwPyrjzo9vG8mQjBjfQW0tYph8xJHzhofu54pxyXsT_OhK1GotEaVCWgFHnM4bbqopUInWVzGgroURrR7GQYXbTfLZeeAMMdnekatiTb4XvFsltCxSm2_W1g,
,08-31 03:05:33.081  4108  8206 I GoogleURLConnFactory: binding HttpService,
,08-31 03:05:33.091  4108  8206 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory,
,08-31 03:05:33.091  4108  8206 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
08-31 03:05:33.091  4108  8206 D libc    : [NET] android_getaddrinfofornet-, err=8,
,08-31 03:05:33.101  4108  8206 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
08-31 03:05:33.101  4108  8206 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-31 03:05:33.101  4108  8206 D libc    : [NET] android_getaddrinfo_proxy+
,08-31 03:05:33.111  4108  8206 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
08-31 03:05:33.111   518  8546 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,08-31 03:05:33.111   518  8546 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
08-31 03:05:33.111   518  8546 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
08-31 03:05:33.111   518  8546 D libc    : [NET] android_getaddrinfofornet-, err=7
,08-31 03:05:33.111  4108  8206 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
08-31 03:05:33.111  4108  8206 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
08-31 03:05:33.111  4108  8206 I GoogleURLConnFactory: unbinding HttpService
08-31 03:05:33.111  1113  1134 D PMS     : releaseWL(3c21744c): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 null
08-31 03:05:33.111  4108  4108 I ConfigFetchService: fetch service done; releasing wakelock
,08-31 03:05:33.111  4108  4108 I ConfigFetchService: stopping self
,08-31 03:05:33.121  3467  3467 I ConfigService: onDestroy
,08-31 03:05:33.131  4108  8544 I art     : Explicit concurrent mark sweep GC freed 13512(872KB) AllocSpace objects, 6(120KB) LOS objects, 35% free, 3MB/5MB, paused 527us total 45.392ms
,08-31 03:05:33.591  1113  3056 D PMS     : acquireWL(3599bb77): PARTIAL_WAKE_LOCK  *alarm* 0x1 1113 1000 WorkSource{10027},
08-31 03:05:33.591  1113  3056 V AlarmManager: sending alarm PendingIntent{1e9d43e4: PendingIntentRecord{32f0c5cd com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=92497, Int=0
,08-31 03:05:33.601  7681  7681 D AlarmReceiver: ACTION_RESTART_INTENT,
08-31 03:05:33.601  1113  1113 D PMS     : releaseWL(3599bb77): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-31 03:05:33.611  7681  7681 D LocalBluetoothProfile: getPriorityOnValue = 100
08-31 03:05:33.611  7681  7681 D LocalBluetoothProfile: getPriorityOffValue = 0
08-31 03:05:33.611  7681  7681 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-31 03:05:33.611  7681  7681 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-31 03:05:33.631  7681  8548 D HtcModeClient: start the htcmodeservice thread
,08-31 03:05:33.631  7681  8548 D HtcModeClient: initCanAgent
,08-31 03:05:33.641  7681  8548 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-31 03:05:33.641  7681  8548 D HtcModeClient: sense info: version = none, id = 2
,08-31 03:05:33.641  7681  8548 D HtcModeClient: display info: width = 1080, height = 1776
,08-31 03:05:33.641  7681  8548 D HtcModeClient: display info: mode = 10
,08-31 03:05:33.741  7681  7681 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,08-31 03:05:33.741  7681  7681 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-31 03:05:33.741  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
08-31 03:05:33.741  7681  7681 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-31 03:05:33.741  7681  7681 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-31 03:05:33.741  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = false
08-31 03:05:33.741  7681  7681 D HtcModeClient: connectState: Force_AWAKE = false
08-31 03:05:33.741  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = true
08-31 03:05:33.741  7681  7681 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-31 03:05:35.751  7681  8548 I HtcModeClient: handler message = 4011
,08-31 03:05:35.751  7681  8548 D HtcModeClient: getConnectionCheckCount first 0,
08-31 03:05:35.751  7681  8548 D HtcModeClient: getConnectionCheckCount count = 8,
08-31 03:05:35.751  7681  8548 E HtcModeClient: Check connection and retry 9 times.,
,08-31 03:05:35.761  7681  8548 D HtcModeClient: setConnectionCheckCount count = 9
08-31 03:05:35.761  7681  8548 D HtcModeClient: setupRestart delayedTime = 3000
,08-31 03:05:35.761  7681  7681 D HtcModeClient: setBtPriority priority = on,
08-31 03:05:35.761  7681  7681 D HtcModeClient: unbindBlueToothService
08-31 03:05:35.761  7681  7681 D HtcModeClient: Don't start project servcice,
,08-31 03:05:35.761  7681  7681 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-31 03:05:35.761  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
,08-31 03:05:35.761  7681  7681 D SilentMusic: call stop
08-31 03:05:35.761  7681  7681 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-31 03:05:35.761  7681  8549 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-31 03:05:35.761  7681  7681 D HtcModeClient: onDestroy
,08-31 03:05:36.201  1113  3069 D WifiStateMachine: startScan Pid: 1113 Uid -1
08-31 03:05:36.201  1113  3069 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-31 03:05:36.201  1113  3069 D WifiDisplayAdapter:     Client/Owner: Client
08-31 03:05:36.201  1113  3069 D WifiDisplayAdapter:     GroupId: 
08-31 03:05:36.201  1113  3069 D WifiDisplayAdapter:     Passphrase: 
08-31 03:05:36.201  1113  3069 D WifiDisplayAdapter:     SessionId: 0
08-31 03:05:36.201  1113  3069 D WifiDisplayAdapter:     IP Address: }
08-31 03:05:36.201  3179  3179 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-31 03:05:36.201  3179  3179 D wpa_supplicant: CTRL_IFACE SET 'pno'='0'
08-31 03:05:36.201  3179  3179 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-31 03:05:36.201  3179  3179 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
,08-31 03:05:36.201  3179  3179 I wpa_supplicant: wpa_supplicant_scan enter
08-31 03:05:36.201  3179  3179 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-31 03:05:36.201  3179  3179 D wpa_supplicant: wlan0: Add radio work 'scan'@0x555b80cca0
08-31 03:05:36.201  3179  3179 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-31 03:05:36.201  3179  3179 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x555b80cca0 after 0.000023 second wait
08-31 03:05:36.201  3179  3179 D wpa_supplicant: wlan0: nl80211: scan request
,08-31 03:05:36.241  3179  3179 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
08-31 03:05:36.241  3179  3179 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
08-31 03:05:36.241  3179  3179 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-31 03:05:36.241  3179  3179 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received,
08-31 03:05:36.241  3179  3179 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000141 seconds
08-31 03:05:36.241  3179  3179 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-31 03:05:36.241  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
,08-31 03:05:37.031  1113  1113 D UsbnetService: BroadcastReceiver::onReceive+,
08-31 03:05:37.031  1113  3588 D PMS     : acquireWL(1cf97c05): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1113 1000 null
08-31 03:05:37.031  1113  1113 D UsbnetService: onReceive BATTERY_CHANGED
08-31 03:05:37.031  1113  3588 I BatteryService: n_update end
08-31 03:05:37.031  1113  1113 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-31 03:05:37.031  1113  3588 D PMS     : releaseWL(1cf97c05): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
08-31 03:05:37.031  1113  1113 D UsbnetService: BroadcastReceiver::onReceive-
08-31 03:05:37.031  1113  1113 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-31 03:05:37.031  3245  3245 D PowerUI : closing low battery warning: level=100
08-31 03:05:37.041  3245  3740 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-31 03:05:37.041  1113  3101 D WifiController: handleMessage: E msg.what=155652
08-31 03:05:37.041  1113  3101 D WifiController: battery changed pluggedType: 2
08-31 03:05:37.041  1113  3101 D WifiController: processMsg: DeviceActiveState
08-31 03:05:37.041  3245  3245 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-31 03:05:37.041  1113  3101 D WifiController: processMsg: StaEnabledState
08-31 03:05:37.041  1113  1176 D HtcPowerSaver: updateBatteryInfo
08-31 03:05:37.041  1113  3101 D WifiController: processMsg: DefaultState
08-31 03:05:37.041  1113  1113 D HtcPowerSaver: Checking...
08-31 03:05:37.041  1113  3101 D WifiController: handleMessage: X
08-31 03:05:37.041  1113  1113 I HtcPowerSaver: >> updateStatus
08-31 03:05:37.041  3363  3363 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-31 03:05:37.041  3363  3363 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-31 03:05:37.041  3363  3363 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,08-31 03:05:37.041  1113  1113 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-31 03:05:37.041  1113  1113 I HtcPowerSaver: << updateStatus
,08-31 03:05:37.081  3245  3245 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-31 03:05:37.081  3245  3245 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-31 03:05:37.091  3245  3245 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-31 03:05:37.091  3245  3245 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-31 03:05:37.091  3245  3245 I FlashlightController: batteryLevelChange:100
,08-31 03:05:38.201  1113  1158 I ActivityManager: Waited long enough for: ServiceRecord{97bc410 u0 com.google.android.gms/.wearable.service.WearableService}
,08-31 03:05:39.851  3179  3179 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-31 03:05:39.861  1113  3069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: nl80211: New scan results available
08-31 03:05:39.851  3179  3179 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-31 03:05:39.851  3179  3179 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-31 03:05:39.851  3179  3179 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: Scan completed in 3.609197 seconds
,08-31 03:05:39.851  3179  3179 D wpa_supplicant: nl80211: Received scan results (53 BSSes)
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-48
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-48
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-44
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-53
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-59
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-60
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-60
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-70
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-70
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-71
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d5 freq=2437 level=-73
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d0 freq=2437 level=-73
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d4 freq=2437 level=-73
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d2 freq=2437 level=-73
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-78
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-78
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-74
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-74
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-74
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-74
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-79
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-79
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:35 freq=2412 level=-75
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:36 freq=2412 level=-75
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-76
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:99 freq=5180 level=-87
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:9b freq=5180 level=-88
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:da freq=5180 level=-88
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d9 freq=5180 level=-88
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:90 freq=2462 level=-84
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:94 freq=2462 level=-84
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 00:fe:c8:73:02:00 freq=2462 level=-84
,08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:5f freq=5180 level=-89
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:5a freq=5180 level=-89
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:59 freq=5180 level=-89
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 00:fe:c8:73:02:04 freq=2462 level=-85
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] e4:aa:5d:fc:5b:f4 freq=2437 level=-87
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:55 freq=2437 level=-88
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:7e freq=5200 level=-60
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-69
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-70
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-73
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-73
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-78
,08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-74
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-75
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:91 freq=2462 level=-81
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:9e freq=5180 level=-88
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:5e freq=5180 level=-88
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [] 00:fe:c8:73:02:01 freq=2462 level=-84
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-84
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-84
08-31 03:05:39.851  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:21:47:53 freq=2437 level=-87
,08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: BSS: Start scan result update 7
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 86 BSSID 84:b2:61:1c:62:d9 SSID '\x00'
08-31 03:05:39.851  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 87 BSSID e4:aa:5d:fc:5b:f4 SSID '\x00'
08-31 03:05:39.851  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 88 BSSID 84:b2:61:21:47:55 SSID '\x00'
08-31 03:05:39.851  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 13 BSSID 84:b2:61:1a:ce:72 SSID '\x00' due to no match in scan
08-31 03:05:39.851  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 12 BSSID 84:b2:61:1a:ce:74 SSID '\x00' due to no match in scan
,08-31 03:05:39.851  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 74 BSSID 84:b2:61:12:64:95 SSID '\x00' due to no match in scan
08-31 03:05:39.851  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.851  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 70 BSSID 00:fe:c8:73:02:02 SSID '\x00' due to no match in scan
08-31 03:05:39.861  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.861  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 79 BSSID 84:b2:61:21:47:50 SSID '\x00' due to no match in scan
08-31 03:05:39.861  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.861  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 35 BSSID 00:fe:c8:73:02:06 SSID '\x00' due to no match in scan
08-31 03:05:39.861  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
,08-31 03:05:39.861  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 81 BSSID e4:aa:5d:fc:5b:f3 SSID 'RA-WINGS' due to no match in scan
08-31 03:05:39.861  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.861  3179  3179 D wpa_supplicant: BSS: last_scan_res_used=53/64
08-31 03:05:39.861  3179  3179 D wpa_supplicant: wlan0: Scan-only results received
08-31 03:05:39.861  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.861  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:39.861  3179  3179 D wpa_supplicant: wlan0: Radio work 'scan'@0x555b80cca0 done in 3.654411 seconds
08-31 03:05:39.861  3179  3179 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-31 03:05:39.861  3179  3179 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
,08-31 03:05:39.861  3179  3179 D wpa_supplicant: wlan0: Cancelling scan request
08-31 03:05:39.861  3179  3179 D wpa_supplicant: PNO: No configured SSIDs
08-31 03:05:39.861  1113  3069 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-31 03:05:39.861  3179  3179 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-31 03:05:39.871  3179  3179 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,08-31 03:05:39.881  3179  3179 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-31 03:05:39.881  1113  3069 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
,08-31 03:05:39.881  4416  4416 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
,08-31 03:05:39.881  1113  1113 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 16
08-31 03:05:39.881  4416  5879 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
,08-31 03:05:40.781  1113  3056 I ActivityManager: Start proc 8550:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService,
08-31 03:05:40.781  1113  3056 D PMS     : acquireWL(ae1845a): PARTIAL_WAKE_LOCK  *alarm* 0x1 1113 1000 WorkSource{10058}
08-31 03:05:40.781  1113  3056 V AlarmManager: sending alarm PendingIntent{ff4f68b: PendingIntentRecord{28ed8368 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1472605534665, Int=60000
,08-31 03:05:40.781  1113  3056 V AlarmManager: sending alarm PendingIntent{36238c26: PendingIntentRecord{2d3a7067 com.android.vending startService}}, i=null, t=0, cnt=1, w=1472605538899, Int=0,
,08-31 03:05:40.781  1113  3056 V AlarmManager: sending alarm PendingIntent{26cb6e14: PendingIntentRecord{32f0c5cd com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=99661, Int=0,
08-31 03:05:40.791  7681  7681 D AlarmReceiver: ACTION_RESTART_INTENT
,08-31 03:05:40.791  7681  7681 D LocalBluetoothProfile: getPriorityOnValue = 100
08-31 03:05:40.801  1113  1113 D PMS     : releaseWL(ae1845a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-31 03:05:40.791  7681  7681 D LocalBluetoothProfile: getPriorityOffValue = 0
08-31 03:05:40.791  7681  7681 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-31 03:05:40.791  7681  7681 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-31 03:05:40.801  8550  8550 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:40.801  8550  8550 W HTCLOG  : mask=0x18
,08-31 03:05:40.831  7681  8573 D HtcModeClient: start the htcmodeservice thread
08-31 03:05:40.841  7681  8573 D HtcModeClient: initCanAgent
,08-31 03:05:40.841  7681  8573 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-31 03:05:40.841  8550  8574 D SMSBackup: SMSBackupAgentService started
08-31 03:05:40.841  8550  8574 D SMSBackup: Checking restore status
08-31 03:05:40.841  7681  8573 D HtcModeClient: sense info: version = none, id = 2,
08-31 03:05:40.841  8550  8574 D SMSBackup: Restore complete
08-31 03:05:40.841  8550  8574 D SMSBackup: cancelCheckAlarm
,08-31 03:05:40.841  8550  8574 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
08-31 03:05:40.841  7681  8573 D HtcModeClient: display info: width = 1080, height = 1776
08-31 03:05:40.841  7681  8573 D HtcModeClient: display info: mode = 10
,08-31 03:05:40.931  7681  7681 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-31 03:05:40.931  7681  7681 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-31 03:05:40.931  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
08-31 03:05:40.931  7681  7681 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-31 03:05:40.931  7681  7681 D HtcModeClient: connectState: ENTER_PROJECTMODE = false,
08-31 03:05:40.931  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = false
08-31 03:05:40.931  7681  7681 D HtcModeClient: connectState: Force_AWAKE = false
08-31 03:05:40.931  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = true
08-31 03:05:40.941  7681  7681 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-31 03:05:40.971  1113  3821 I art     : Explicit concurrent mark sweep GC freed 33070(1687KB) AllocSpace objects, 11(204KB) LOS objects, 33% free, 16MB/24MB, paused 1.704ms total 145.368ms,
,08-31 03:05:41.021  8264  8264 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.,
,08-31 03:05:42.941  7681  8573 I HtcModeClient: handler message = 4011,
,08-31 03:05:42.951  7681  8573 D HtcModeClient: getConnectionCheckCount first 0
08-31 03:05:42.951  7681  8573 D HtcModeClient: getConnectionCheckCount count = 9
,08-31 03:05:42.951  7681  8573 E HtcModeClient: Check connection and retry 10 times.
,08-31 03:05:42.951  7681  8573 D HtcModeClient: setConnectionCheckCount count = 10,
08-31 03:05:42.951  7681  8573 D HtcModeClient: setupRestart delayedTime = 3000
,08-31 03:05:42.961  7681  7681 D HtcModeClient: setBtPriority priority = on
08-31 03:05:42.961  7681  7681 D HtcModeClient: unbindBlueToothService
08-31 03:05:42.961  7681  7681 D HtcModeClient: Don't start project servcice
,08-31 03:05:42.961  7681  7681 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-31 03:05:42.961  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
,08-31 03:05:42.961  7681  7681 D SilentMusic: call stop
08-31 03:05:42.971  7681  7681 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode,
08-31 03:05:42.971  7681  8575 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-31 03:05:42.981  7681  7681 D HtcModeClient: onDestroy,
,08-31 03:05:42.981  1113  3568 D Process : killProcessQuiet, pid=7639
08-31 03:05:42.981  1113  3568 I ActivityManager: Killing 7639:com.htc.sdm/u0a61 (adj 15): empty #17
08-31 03:05:42.981  1113  3568 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-31 03:05:43.051  1113  3577 I ActivityManager: Recipient 7639,
,08-31 03:05:45.551  8442  8501 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-31 03:05:45.551  8442  8501 I jxcore-log: 
,08-31 03:05:45.551  8442  8501 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-31 03:05:45.551  8442  8501 I jxcore-log: 
,08-31 03:05:45.561  5515  5535 D BluetoothAdapterService(727959742): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@542d3a3,
08-31 03:05:45.561  8442  8501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 03:05:45.561  8442  8501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:05:45.561  8442  8501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 03:05:45.561  8442  8501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:05:45.561  8442  8501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:05:45.561  8442  8501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 03:05:45.561  8442  8501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-31 03:05:45.561  8442  8501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 03:05:45.561  5515  5536 D BluetoothAdapterService(727959742): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@542d3a3
08-31 03:05:45.561  8442  8501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 03:05:45.571  8442  8501 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 03:05:45.571  8442  8501 I jxcore-log: 
,08-31 03:05:45.571  8442  8501 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-31 03:05:45.571  8442  8501 I jxcore-log: 
,08-31 03:05:46.031  8442  8501 I jxcore-log: Running unit tests,
08-31 03:05:46.031  8442  8501 I jxcore-log: 
08-31 03:05:46.031  8442  8501 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests,
08-31 03:05:46.031  8442  8501 I jxcore-log: Failed to execute UT.
08-31 03:05:46.031  8442  8501 I jxcore-log: 
,08-31 03:05:46.031  8442  8501 I jxcore-log: Unit Test app is loaded,
08-31 03:05:46.031  8442  8501 I jxcore-log: 
,08-31 03:05:46.041  8442  8501 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 03:05:46.041  8442  8501 I jxcore-log: 
08-31 03:05:46.051  8442  8501 I jxcore-log: My device name is: HTC-HTC One M9
08-31 03:05:46.051  8442  8501 I jxcore-log: 
,08-31 03:05:46.051  8442  8442 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 03:05:46.051  8442  8501 I jxcore-log: WARN testUtils: myNameCallback not set!,
08-31 03:05:46.051  8442  8501 I jxcore-log: 
,08-31 03:05:47.961  1113  3056 D PMS     : acquireWL(c53b80a): PARTIAL_WAKE_LOCK  *alarm* 0x1 1113 1000 WorkSource{10027}
,08-31 03:05:47.961  1113  3056 V AlarmManager: sending alarm PendingIntent{2374987b: PendingIntentRecord{32f0c5cd com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=106860, Int=0
,08-31 03:05:47.961  7681  7681 D AlarmReceiver: ACTION_RESTART_INTENT
,08-31 03:05:47.971  7681  7681 D LocalBluetoothProfile: getPriorityOnValue = 100
,08-31 03:05:47.971  1113  1113 D PMS     : releaseWL(c53b80a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-31 03:05:47.971  7681  7681 D LocalBluetoothProfile: getPriorityOffValue = 0
08-31 03:05:47.971  7681  7681 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-31 03:05:47.971  7681  7681 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-31 03:05:48.001  7681  8578 D HtcModeClient: start the htcmodeservice thread,
08-31 03:05:48.001  7681  8578 D HtcModeClient: initCanAgent
08-31 03:05:48.001  7681  8578 I CANMesgAgentLocalSocket: CANAgent Id = 0,
08-31 03:05:48.001  7681  8578 D HtcModeClient: sense info: version = none, id = 2
08-31 03:05:48.001  7681  8578 D HtcModeClient: display info: width = 1080, height = 1776
08-31 03:05:48.001  7681  8578 D HtcModeClient: display info: mode = 10
,08-31 03:05:48.101  7681  7681 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,08-31 03:05:48.101  7681  7681 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-31 03:05:48.101  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
08-31 03:05:48.101  7681  7681 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-31 03:05:48.101  7681  7681 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-31 03:05:48.101  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = false
08-31 03:05:48.101  7681  7681 D HtcModeClient: connectState: Force_AWAKE = false
08-31 03:05:48.101  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = true
08-31 03:05:48.101  7681  7681 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-31 03:05:49.341  8442  8501 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
08-31 03:05:49.341  8442  8501 I jxcore-log: 
,08-31 03:05:49.891  8442  8501 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-31 03:05:49.891  8442  8501 I jxcore-log: 
,08-31 03:05:49.931  8442  8501 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js,
08-31 03:05:49.931  8442  8501 I jxcore-log: 
,08-31 03:05:50.111  7681  8578 I HtcModeClient: handler message = 4011,
08-31 03:05:50.111  7681  8578 D HtcModeClient: getConnectionCheckCount first 0,
08-31 03:05:50.121  7681  8578 D HtcModeClient: getConnectionCheckCount count = 10,
,08-31 03:05:50.121  7681  8578 E HtcModeClient: Check connection and retry 11 times.,
,08-31 03:05:50.121  7681  8578 D HtcModeClient: setConnectionCheckCount count = 11,
08-31 03:05:50.121  7681  8578 D HtcModeClient: setupRestart delayedTime = 3000,
,08-31 03:05:50.131  7681  7681 D HtcModeClient: setBtPriority priority = on
,08-31 03:05:50.131  7681  7681 D HtcModeClient: unbindBlueToothService
08-31 03:05:50.131  7681  7681 D HtcModeClient: Don't start project servcice
,08-31 03:05:50.131  7681  7681 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-31 03:05:50.131  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
08-31 03:05:50.131  7681  7681 D SilentMusic: call stop
08-31 03:05:50.131  7681  7681 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-31 03:05:50.131  7681  8579 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-31 03:05:50.131  7681  7681 D HtcModeClient: onDestroy,
,08-31 03:05:51.221  1113  3069 D WifiStateMachine: startScan Pid: 1113 Uid -1
08-31 03:05:51.221  1113  3069 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-31 03:05:51.221  1113  3069 D WifiDisplayAdapter:     Client/Owner: Client
08-31 03:05:51.221  1113  3069 D WifiDisplayAdapter:     GroupId: 
08-31 03:05:51.221  1113  3069 D WifiDisplayAdapter:     Passphrase: 
08-31 03:05:51.221  1113  3069 D WifiDisplayAdapter:     SessionId: 0
08-31 03:05:51.221  1113  3069 D WifiDisplayAdapter:     IP Address: }
08-31 03:05:51.221  3179  3179 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-31 03:05:51.221  3179  3179 D wpa_supplicant: CTRL_IFACE SET 'pno'='0'
08-31 03:05:51.221  3179  3179 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-31 03:05:51.221  3179  3179 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-31 03:05:51.221  3179  3179 I wpa_supplicant: wpa_supplicant_scan enter
08-31 03:05:51.221  3179  3179 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-31 03:05:51.221  3179  3179 D wpa_supplicant: wlan0: Add radio work 'scan'@0x555b80cca0
08-31 03:05:51.221  3179  3179 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-31 03:05:51.221  3179  3179 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x555b80cca0 after 0.000026 second wait
08-31 03:05:51.221  3179  3179 D wpa_supplicant: wlan0: nl80211: scan request
,08-31 03:05:51.261  3179  3179 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
08-31 03:05:51.261  3179  3179 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
08-31 03:05:51.261  3179  3179 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-31 03:05:51.261  3179  3179 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
08-31 03:05:51.261  3179  3179 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000136 seconds
08-31 03:05:51.261  3179  3179 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 03:05:51.261  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
,08-31 03:05:51.891  8442  8501 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js,
08-31 03:05:51.891  8442  8501 I jxcore-log: 
,08-31 03:05:52.211  8442  8501 I jxcore-log: ERROR runTests: ,
08-31 03:05:52.211  8442  8501 I jxcore-log: 
08-31 03:05:52.211  8442  8501 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:05:52.211  8442  8501 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-31 03:05:52.221  8442  8501 I jxcore-log: WARN testUtils: logCallback not set!
08-31 03:05:52.221  8442  8501 I jxcore-log: 
,08-31 03:05:52.231  8442  8501 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',,
08-31 03:05:52.231  8442  8501 I jxcore-log:     _functionName: 'loadFile',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _lineNumber: '26',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _columnNumber: '11',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 03:05:52.231  8442  8501 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _functionName: '',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _lineNumber: '38',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _columnNumber: '7',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 03:05:52.231  8442  8501 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
,08-31 03:05:52.231  8442  8501 I jxcore-log:     _functionName: '',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _lineNumber: '35',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _columnNumber: '3',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 03:05:52.231  8442  8501 I jxcore-log:   { _fileName: 'module.js',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _lineNumber: '621',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _columnNumber: '8',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 03:05:52.231  8442  8501 I jxcore-log:   { _fileName: 'module.js',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _lineNumber: '651',
08-31 03:05:52.231  8442  8501 I jxcore-log:     _columnNumber: '1',
08-31 03:05:52.231  8442  8501 I jxcore-log:    
08-31 03:05:52.231  8442  8501 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 03:05:52.231  8442  8501 I jxcore-log: 
08-31 03:05:52.231  8442  8501 E jxcore-log: Error: 
08-31 03:05:52.231  8442  8501 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:05:52.231  8442  8501 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 03:05:52.231  8442  8501 E jxcore-log: 
,08-31 03:05:52.461  8580  8580 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
08-31 03:05:52.461  8580  8580 W HTCLOG  : mask=0x18
,08-31 03:05:52.611  8580  8584 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-31 03:05:52.611  8580  8584 W HTCLOG  : mask=0x18
08-31 03:05:52.611  8580  8584 E cutils-trace: Error opening trace file: Permission denied (13)
,08-31 03:05:52.671  8580  8580 D CustomizationManager: ====startRecUseTime====,
08-31 03:05:52.671  8580  8580 D htc.customization.log.level:  is 
08-31 03:05:52.671  8580  8580 W CustomizationLogLevel: Level value is invalid, use default level 2
,08-31 03:05:52.751  8580  8580 D CustomizationManager:  Read ACC file spent 0.042 (s),
,08-31 03:05:52.761  8580  8580 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
,08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: Parsing tag category name = application,
08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: Parsing tag category name = system
,08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: Parsing tag category name = Settings
08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: Parsing tag category name = ACC
,08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240,
08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-31 03:05:52.761  8580  8580 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-31 03:05:52.771  8580  8580 D CustomizationManager:  Read CID file spent 0.096 (s),
08-31 03:05:52.771  8580  8580 D CustomizationManager:  All configurations done spent 0.096 (s)
,08-31 03:05:52.811  1113  3568 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8580, uid=2000
,08-31 03:05:52.821  1113  1158 D Process : killProcessQuiet, pid=8442
08-31 03:05:52.821  1113  1158 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
08-31 03:05:52.821  1113  1158 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
08-31 03:05:52.821  1113  1158 I ActivityManager: Killing 8442:com.test.thalitest/u0a142 (adj 0): stop com.test.thalitest
,08-31 03:05:52.911   530   530 W HTCLOG  : use specified tag [Vector], func [0].
08-31 03:05:52.911   530   530 W HTCLOG  : mask=0x18
,08-31 03:05:52.971  1113  3577 I ActivityManager: Recipient 8442,
,08-31 03:05:52.971  1113  3820 I WindowState: WIN DEATH: Window{1136a3f9 u0 com.test.thalitest/com.test.thalitest.MainActivity},
08-31 03:05:52.971  1113  3101 D WifiService: Client connection lost with reason: 4
,08-31 03:05:53.031  1113  1158 I ActivityManager:   Force finishing activity 3 ActivityRecord{1e8179d5 u0 com.test.thalitest/.MainActivity t451}
,08-31 03:05:53.051  1113  1182 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed
08-31 03:05:53.051  1113  1182 I ActivityManager:   Force finishing activity 3 ActivityRecord{1e8179d5 u0 com.test.thalitest/.MainActivity t451 f}
08-31 03:05:53.051  1113  1182 W ActivityManager: Duplicate finish request for ActivityRecord{1e8179d5 u0 com.test.thalitest/.MainActivity t451 f}
,08-31 03:05:53.061  3363  3363 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
08-31 03:05:53.061  3363  3363 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,08-31 03:05:53.071  1113  3391 D PMS     : acquireWL(2e53a0b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4416 10019 null
,08-31 03:05:53.071  3778  4163 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,08-31 03:05:53.081  3778  4163 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,08-31 03:05:53.081  3778  4163 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,08-31 03:05:53.091  1113  3577 W ActivityManager: Spurious death for ProcessRecord{2cb13b29 8442:com.test.thalitest/u0a142}, curProc for 8442: null
,08-31 03:05:53.091  1113  3178 D TaskPersister: removeObsoleteFile: deleting file=451_task.xml
08-31 03:05:53.091  4416  4567 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 03:05:53.091  1113  3577 D PMS     : releaseWL(2e53a0b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,08-31 03:05:53.101  3778  4163 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
08-31 03:05:53.101  1113  3577 D PMS     : acquireWL(245237ba): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4108 10019 null
08-31 03:05:53.101  4108  4108 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-31 03:05:53.101  1113  3059 W SystemReader: Cannot find grip_rejection_width, use default value instead
08-31 03:05:53.111  3593  3593 I art     : Explicit concurrent mark sweep GC freed 3394(178KB) AllocSpace objects, 12(990KB) LOS objects, 40% free, 19MB/33MB, paused 2.062ms total 51.949ms
,08-31 03:05:53.111  1113  3067 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
08-31 03:05:53.111  1113  3066 D PMS     : acquireWL(17d8966b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1113 1000 null
08-31 03:05:53.121  1113  1157 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,08-31 03:05:53.131  3467  3467 I ConfigService: onCreate
08-31 03:05:53.131  3467  3467 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-31 03:05:53.131  3778  4163 E ExternalAccountType: Unsupported attribute readOnly
,08-31 03:05:53.141  4108  4108 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-31 03:05:53.141  3467  3467 I ConfigService: onBind returning update interface
08-31 03:05:53.141  1113  3066 D PMS     : releaseWL(17d8966b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
08-31 03:05:53.141  1113  3067 V NetworkPolicy: writePolicyLocked()
08-31 03:05:53.141  1113  1157 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-31 03:05:53.151  3467  3467 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-31 03:05:53.151  3467  3467 I ConfigService: onBind returning config service
08-31 03:05:53.151  3569  3569 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,08-31 03:05:53.151  3771  8597 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 03:05:53.161  6054  6054 I art     : Explicit concurrent mark sweep GC freed 9833(658KB) AllocSpace objects, 2(48KB) LOS objects, 34% free, 3MB/5MB, paused 465us total 102.860ms
,08-31 03:05:53.161  1113  3568 D PMS     : acquireWL(2488036a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3467 10019 null
,08-31 03:05:53.171  1113  1135 I ActivityManager: Start proc 8599:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
,08-31 03:05:53.181  8599  8599 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:53.181  1113  3577 D PMS     : releaseWL(2488036a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
08-31 03:05:53.181  8599  8599 W HTCLOG  : mask=0x18
,08-31 03:05:53.191  1113  3056 D PMS     : acquireWL(347d3710): PARTIAL_WAKE_LOCK  *alarm* 0x1 1113 1000 WorkSource{10027}
08-31 03:05:53.201  1113  3056 V AlarmManager: sending alarm PendingIntent{26778209: PendingIntentRecord{32f0c5cd com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=114028, Int=0
08-31 03:05:53.201  1113  3056 V AlarmManager: sending alarm PendingIntent{1a833d5a: PendingIntentRecord{142ebb8b android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=114096, Int=0
08-31 03:05:53.201  1113  3067 D NetworkPolicy: notifyPoliciesChangeLocked: no change
08-31 03:05:53.201  1113  3067 V NetworkPolicy: updateNetworkEnabledLocked()
08-31 03:05:53.201  1113  3067 V NetworkPolicy: updateNotificationsLocked()
,08-31 03:05:53.211  3467  3467 I ConfigService: onDestroy
,08-31 03:05:53.231  1113  1113 I art     : Explicit concurrent mark sweep GC freed 23415(1661KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 16MB/24MB, paused 1.800ms total 175.636ms
08-31 03:05:53.231  1113  1182 I art     : WaitForGcToComplete blocked for 116.760ms for cause Explicit
,08-31 03:05:53.231  8599  8599 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 03:05:53.231  8599  8599 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,08-31 03:05:53.241  3593  3593 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,08-31 03:05:53.251  3593  3593 I ThreadedRenderer: Defer allocateBuffers to drawing time
,08-31 03:05:53.261  8599  8599 I MultiDex: VM with version 2.1.0 has multidex support,
08-31 03:05:53.261  8599  8599 I MultiDex: install
08-31 03:05:53.261  8599  8599 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 03:05:53.271  8599  8599 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-31 03:05:53.291  8599  8599 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-31 03:05:53.301  3516  3516 D Nfc-Utils: isNxpCodebase: isNxp=false
,08-31 03:05:53.301  1113  1135 D Process : killProcessQuiet, pid=7847,
08-31 03:05:53.301  1113  1135 I ActivityManager: Killing 7847:com.google.android.gm/u0a97 (adj 15): empty #17
08-31 03:05:53.301  1113  1135 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-31 03:05:53.391  1113  1113 W PackageManager: Unable to load service info ResolveInfo{202d22ff com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
08-31 03:05:53.391  1113  1113 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
08-31 03:05:53.391  1113  1113 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
08-31 03:05:53.391  1113  1113 W PackageManager: ,	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
08-31 03:05:53.391  1113  1113 W PackageManager: 	,at com.android.server.SystemServer.main(SystemServer.java:232)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:53.391  1113  1113 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:53.391  1113  3575 I ActivityManager: Recipient 7847,
,08-31 03:05:53.411  3593  3964 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
08-31 03:05:53.411  3593  3964 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,08-31 03:05:53.411  3593  3593 I Launcher: Deferring update until onResume
,08-31 03:05:53.411  3593  3593 D Launcher: waitUntilResume // bindAppsRemoved
08-31 03:05:53.421  1113  1113 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 03:05:53.431  4108  8623 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
08-31 03:05:53.431  4108  8623 D AccountUtils: Clearing selected account for com.test.thalitest
08-31 03:05:53.431  1113  3577 I ActivityManager: Start proc 8624:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver
,08-31 03:05:53.431  1113  1182 I art     : Explicit concurrent mark sweep GC freed 6114(329KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 3.065ms total 205.026ms
,08-31 03:05:53.441  8624  8624 W HTCLOG  : use specified tag [FDManager], func [0].,
08-31 03:05:53.441  8624  8624 W HTCLOG  : mask=0x18
,08-31 03:05:53.481  8001  8649 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id),
,08-31 03:05:53.481  4108  8651 I PeopleContactsSync: CP2 sync disabled
08-31 03:05:53.491  1113  3588 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4108, uid=10019, userID:0
,08-31 03:05:53.491  1113  3588 D PMS     : acquireWL(3edb85c7): PARTIAL_WAKE_LOCK  Icing 0x1 4108 10019 null
,08-31 03:05:53.491  1113  3575 D Process : killProcessQuiet, pid=7488
,08-31 03:05:53.491  1113  3575 I ActivityManager: Killing 7488:com.google.android.music:main/u0a115 (adj 15): empty #17
08-31 03:05:53.491  1113  3575 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-31 03:05:53.491  4108  5614 I Icing   : doRemovePackageData com.test.thalitest
08-31 03:05:53.491  1113  3820 D PMS     : releaseWL(3edb85c7): PARTIAL_WAKE_LOCK  Icing 0x1 null
,08-31 03:05:53.511  8580  8580 I art     : System.exit called, status: 0,
08-31 03:05:53.511  8580  8580 W HTCLOG  : use specified tag [Vector], func [0].
08-31 03:05:53.511  8580  8580 W HTCLOG  : mask=0x18
,08-31 03:05:53.651  1113  3568 I ActivityManager: Recipient 7488,
08-31 03:05:53.651  1113  3840 D MediaRouterService: Client com.google.android.music (pid 7488): Died!
,08-31 03:05:53.711  3778  3778 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
,08-31 03:05:53.751  3690  8658 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,08-31 03:05:53.761  3690  8658 E SQLiteLog: (3850) statement aborts at 41: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
,08-31 03:05:53.761  3690  8658 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-31 03:05:53.761  3690  8658 W HTCLOG  : mask=0x18
08-31 03:05:53.761  3690  8658 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.sense.hsp/databases/registry.db, handle: 0x558daf5600
,08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: provider may killed!
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
,08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: ,	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	,at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.761  3690  8658 W [PluginManager]RegisterService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 03:05:53.771  4108  8650 W GmsApplication: Using Auth Proxy for data requests.
08-31 03:05:53.771  3690  8658 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,08-31 03:05:53.781  4108  8650 W GmsApplication: Using Auth Proxy for data requests.
,08-31 03:05:53.781  3593  3593 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
,08-31 03:05:53.781  3593  3593 I ContextualWidget: package com.test.thalitest removed
08-31 03:05:53.781  3593  4018 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.781  4108  8650 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: Runtime exception while performing operation
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.791  4108  8650 E ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.791  4108  8650 F ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:53.791  3593  8659 I ContextualWidget: com.test.thalitest is not installed
08-31 03:05:53.791  3593  8659 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
08-31 03:05:53.801  3593  8659 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
08-31 03:05:53.801  3593  8659 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-31 03:05:53.801  3593  8659 W HTCLOG  : mask=0x18
08-31 03:05:53.801  3593  8659 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xac3f9ad8
08-31 03:05:53.801  3593  8659 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
08-31 03:05:53.801  3593  8659 E AndroidRuntime: Process: com.htc.launcher, PID: 3593
08-31 03:05:53.801  3593  8659 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.removeItemsFromDownloadListIfNeed(MFUDataManager.java:2133)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageRemoved(HtcContextualWidgetService.java:277)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:184)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.801  3593  8659 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: Can't write: system_app_wtf
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:53.801  1113  8660 E DropBoxManagerService: 	... 5 more
08-31 03:05:53.811  1113  1134 I ActivityManager: Start proc 8661:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
08-31 03:05:53.821  1113  3109 E ActivityManager: App crashed! Process: com.htc.launcher
08-31 03:05:53.821  1113  3109 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:53.821  1113  3109 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:53.821  1113  3109 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,08-31 03:05:53.821  1113  3109 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:53.821  1113  3109 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:53.821  1113  3109 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:53.821  1113  3109 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:53.821  1113  3109 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:53.821  1113  3109 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:53.821  1113  3109 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:53.821  1113  3109 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:53.821  1113  3109 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:53.821  1113  3109 W System.err: 	... 14 more
08-31 03:05:53.821  1113  3109 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:53.821  1113  3109 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:53.821  1113  3109 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:53.821  1113  3109 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:53.821  1113  3109 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:53.821  1113  3109 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:53.821  1113  3109 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:53.821  1113  3109 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:53.821  1113  3109 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:53.821  1113  3109 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:53.821  1113  3109 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:53.821  1113  3109 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:53.821  1113  3109 W System.err: 	... 14 more
08-31 03:05:53.821  8661  8661 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:53.821  8661  8661 W HTCLOG  : mask=0x18
08-31 03:05:53.831  1113  8679 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:53.831  1113  8679 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472605553835.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:53.831  1113  8679 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:53.831  1113  8679 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:53.831  1113  8679 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:53.831  1113  8679 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:53.831  1113  8679 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:53.831  1113  8679 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:53.831  1113  8679 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:53.831  1113  8679 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:53.831  1113  8679 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:53.831  1113  8679 E ErrorReport: 	... 4 more
08-31 03:05:53.831  1113  3109 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-31 03:05:53.841  3593  3593 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@149fdccc for type 0
08-31 03:05:53.841  3593  3593 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@149fdccc for type 1
08-31 03:05:53.841  3593  3593 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@149fdccc for type 3
08-31 03:05:53.841  3593  3593 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@149fdccc for type 2
08-31 03:05:53.841  3593  8659 D Process : killProcess, pid=3593
08-31 03:05:53.841  3593  8659 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:53.841  3593  8659 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:53.841  3593  8659 W HTCLOG  : mask=0x18
08-31 03:05:53.841  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-31 03:05:53.841  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:53.841  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:53.841  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:53.841  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:53.841  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:53.841  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:53.841  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:53.841  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:53.841  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:53.841  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:53.841  1113  3638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:53.841  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.841  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:53.841  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:53.841  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:53.841  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:53.841  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:53.841  1113  3638 W System.err: 	... 12 more
,08-31 03:05:53.871  4108  8639 W DriveInitializer: Awaiting to be initialized
,08-31 03:05:53.871  4108  8684 W DriveInitializer: Background init thread started
,08-31 03:05:53.881  4108  8684 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock43] disk I/O error
08-31 03:05:53.881  4108  8684 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-31 03:05:53.881  4108  8684 W HTCLOG  : mask=0x18
,08-31 03:05:53.881  4108  8684 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x558dad1050
,08-31 03:05:53.881  4108  8684 E DocListDatabase: Failed to delete from ContentFileDeletionLock43
08-31 03:05:53.881  4108  8684 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850),
08-31 03:05:53.881  4108  8684 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 03:05:53.881  4108  8684 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-31 03:05:53.881  4108  8684 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 03:05:53.881  4108  8684 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 03:05:53.881  4108  8684 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-31 03:05:53.881  4108  8684 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
,08-31 03:05:53.881  4108  8684 E DocListDatabase: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
08-31 03:05:53.881  4108  8684 E DocListDatabase: 	at com.google.android.gms.drive.v.run(SourceFile:69)
08-31 03:05:53.881  4108  8639 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-31 03:05:53.881  4108  8639 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x558dad1050
,08-31 03:05:53.881  4108  8639 E DriveAsyncService: disk I/O error (code 3850)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:495)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1406)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	,at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.881  4108  8639 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:53.881  4108  8684 W DriveInitializer: Background init thread ended
,08-31 03:05:53.881  4108  8684 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
08-31 03:05:53.881  4108  8684 E AndroidRuntime: Process: com.google.android.gms, PID: 4108
08-31 03:05:53.881  4108  8684 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 03:05:53.881  4108  8684 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 03:05:53.881  4108  8684 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-31 03:05:53.881  4108  8684 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 03:05:53.881  4108  8684 E AndroidRuntime: ,	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 03:05:53.881  4108  8684 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-31 03:05:53.881  4108  8684 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
08-31 03:05:53.881  4108  8684 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
08-31 03:05:53.881  4108  8684 E AndroidRuntime: 	at com.google.android.gms.drive.v.run(SourceFile:69)
08-31 03:05:53.891  1113  3588 E ActivityManager: App crashed! Process: com.google.android.gms
,08-31 03:05:53.891  4108  8684 D Process : killProcess, pid=4108
08-31 03:05:53.891  4108  8684 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: Can't write: system_app_crash
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method),
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:53.891  1113  8685 E DropBoxManagerService: 	... 5 more
08-31 03:05:53.891  4108  8684 W HTCLOG  : use specified tag [Process], func [0].,
08-31 03:05:53.891  4108  8684 W HTCLOG  : mask=0x18
,08-31 03:05:53.921  1113  3831 I ActivityManager: Recipient 3593,
08-31 03:05:53.921  1113  3575 I WindowState: WIN DEATH: Window{25638207 u0 com.htc.launcher/com.htc.launcher.Launcher}
,08-31 03:05:53.921  8661  8661 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files,
,08-31 03:05:53.921  1113  1135 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/,
08-31 03:05:53.931  1113  3831 I ActivityManager: Process com.htc.launcher (pid 3593) has died
08-31 03:05:53.931  1113  3831 W ActivityManager: Scheduling restart of crashed service com.htc.launcher/.htcwidget.HtcContextualWidgetService in 1000ms
08-31 03:05:53.931  1113  3831 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
,08-31 03:05:53.931  1113  3831 V WindowManager: addAppToken: AppWindowToken{3c1edc19 token=Token{14c06f60 ActivityRecord{f00b763 u0 com.htc.launcher/.Launcher t452}}} to stack=0 task=452 at 0
,08-31 03:05:53.941  8661  8661 D IdefixUninstallListener: package_removed = com.test.thalitest
,08-31 03:05:53.951  8687  8687 W HTCLOG  : use specified tag [FDManager], func [0].,
08-31 03:05:53.951  8687  8687 W HTCLOG  : mask=0x18
,08-31 03:05:53.961  1113  3831 I ActivityManager: Start proc 8687:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-31 03:05:53.971  8661  8661 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-31 03:05:53.971  8661  8661 W HTCLOG  : mask=0x18
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874),
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	,at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467),
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:53.971  8661  8661 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:53.981  8661  8661 W System.err: java.sql.SQLException: Getting a writable database from helper a@1e776021 failed
08-31 03:05:53.981  1113  3577 I ActivityManager: Recipient 4108
08-31 03:05:53.981  8661  8661 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
08-31 03:05:53.981  1113  3575 D PMS     : handleWLDeath(245237ba): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-31 03:05:53.981  8661  8661 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
08-31 03:05:53.981  1113  3840 D PMS     : handleWLDeath(1db727c6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-31 03:05:53.981  8661  8661 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-31 03:05:53.981  1113  3577 I ActivityManager: Process com.google.android.gms (pid 4108) has died
08-31 03:05:53.981  8661  8661 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-31 03:05:53.981  1113  3577 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
08-31 03:05:53.981  8661  8661 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-31 03:05:53.981  1113  3391 I ActivityManager: Killing 8055:com.htc.mobiledata:remote/u0a40 (adj 15): empty #17
08-31 03:05:53.981  8661  8661 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-31 03:05:53.981  8661  8661 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:53.981  8661  8661 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:53.981  8661  8661 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:53.981  8661  8661 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:53.981  8661  8661 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:53.981  8661  8661 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219),
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:53.981  8661  8661 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:53.981  8661  8661 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-31 03:05:53.981  8661  8661 W System.err: 	... 15 more
08-31 03:05:53.981  1113  3391 D Process : killProcessQuiet, pid=8055
08-31 03:05:53.981  1113  3391 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-31 03:05:54.001  8687  8687 I MultiDex: VM with version 2.1.0 has multidex support
,08-31 03:05:54.001  8687  8687 I MultiDex: install,
08-31 03:05:54.001  8687  8687 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-31 03:05:54.011  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-31 03:05:54.011  8687  8687 D FaceDetectTask: checkIsOmronEnable start
08-31 03:05:54.011  8687  8687 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
,08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.021  8687  8687 D FaceDetectTask: IsOmronEnable : true
08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.021  8687  8687 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.021  8687  8687 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
,08-31 03:05:54.031  8687  8687 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-31 03:05:54.031  8687  8687 W HTCLOG  : mask=0x18
,08-31 03:05:54.031  8687  8687 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000),
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-31 03:05:54.031  8687  8687 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.031  8687  8687 W System.err: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,08-31 03:05:54.031  8687  8687 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.031  8687  8687 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-31 03:05:54.031  8687  8687 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
,08-31 03:05:54.031  8687  8687 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.031  8687  8687 W System.err: 	at android.os.Looper.loop(Looper.java:155)
,08-31 03:05:54.031  8687  8687 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.031  8687  8687 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.031  8687  8687 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.031  8687  8687 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.031  8687  8687 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: ,	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.031  8687  8687 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-31 03:05:54.041  8687  8687 E AndroidRuntime: FATAL EXCEPTION: main
08-31 03:05:54.041  8687  8687 E AndroidRuntime: Process: com.htc.launcher, PID: 8687
08-31 03:05:54.041  8687  8687 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(Cont,entProvider.java:1712)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.041  8687  8687 E AndroidRuntime: 	... 11 more
,08-31 03:05:54.041  1113  3109 I ActivityManager: Recipient 8055
,08-31 03:05:54.091  1113  3575 E ActivityManager: App crashed! Process: com.htc.launcher
08-31 03:05:54.091  1113  3575 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:54.101  1113  3575 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.101  1113  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.101  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.101  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.101  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.101  1113  3575 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.101  1113  3575 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.101  1113  3575 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.101  1113  3575 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.101  1113  3575 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.101  1113  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.101  1113  3575 W System.err: 	... 14 more
08-31 03:05:54.101  1113  3575 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.101  1113  3575 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-31 03:05:54.101  1113  3575 W System.err: 	,at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.101  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.101  1113  8717 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:54.101  1113  8717 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472605554109.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.101  1113  8717 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.101  1113  8717 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.101  1113  8717 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.101  1113  8717 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:54.101  1113  8717 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.101  1113  8717 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.101  1113  8717 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
,08-31 03:05:54.101  1113  8717 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.101  1113  8717 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.101  1113  8717 E ErrorReport: 	... 4 more
08-31 03:05:54.101  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.101  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
,08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.101  1113  3575 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.101  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.101  1113  3575 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.101  1113  3575 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.101  1113  3575 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.101  1113  3575 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.101  1113  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.101  1113  3575 W System.err: 	... 14 more
08-31 03:05:54.101  8687  8687 D Process : killProcess, pid=8687
08-31 03:05:54.101  8687  8687 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:54.101  8687  8687 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.101  8687  8687 W HTCLOG  : mask=0x18
08-31 03:05:54.101  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.101  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.101  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.101  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.101  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.101  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:54.101  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:54.101  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:54.101  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:54.101  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:54.101  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:54.101  1113  3638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.101  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.101  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.101  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.101  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.101  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.101  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.101  1113  3638 W System.err: 	... 12 more
08-31 03:05:54.111  6054  8718 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-31 03:05:54.131  1113  3588 I ActivityManager: Start proc 8719:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-31 03:05:54.141  8719  8719 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:54.141  8719  8719 W HTCLOG  : mask=0x18
,08-31 03:05:54.151  6054  8718 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 03:05:54.151  6054  8718 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-31 03:05:54.151  6054  8718 W HTCLOG  : mask=0x18
08-31 03:05:54.151  6054  8718 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x558da46bd0
,08-31 03:05:54.161  6054  8718 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-31 03:05:54.161  6054  8718 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-31 03:05:54.161  6054  8718 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6054
08-31 03:05:54.161  6054  8718 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: ,	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.161  6054  8718 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 03:05:54.161  1113  3831 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: Can't write: system_app_crash
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.161  1113  8741 E DropBoxManagerService: 	... 5 more
08-31 03:05:54.161  6054  8718 D Process : killProcess, pid=6054
08-31 03:05:54.161  6054  8718 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
08-31 03:05:54.161  6054  8718 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.161  6054  8718 W HTCLOG  : mask=0x18
,08-31 03:05:54.171  8719  8719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 
,08-31 03:05:54.181  1113  3391 I ActivityManager: Recipient 8687
,08-31 03:05:54.181  1113  3391 I ActivityManager: Process com.htc.launcher (pid 8687) has died
08-31 03:05:54.181  1113  3391 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-31 03:05:54.181  1113  3391 V WindowManager: addAppToken: AppWindowToken{a3820d5 token=Token{aad218c ActivityRecord{6bd66bf u0 com.htc.launcher/.Launcher t453}}} to stack=0 task=453 at 0
,08-31 03:05:54.201  1113  3391 I ActivityManager: Start proc 8742:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-31 03:05:54.201  1113  3638 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,08-31 03:05:54.201  8742  8742 W HTCLOG  : use specified tag [FDManager], func [0].,
08-31 03:05:54.201  8742  8742 W HTCLOG  : mask=0x18
,08-31 03:05:54.211  8719  8756 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,08-31 03:05:54.211  8719  8756 W HTCLOG  : mask=0x18
08-31 03:05:54.211  1113  1135 D PMS     : acquireWL(20d0ca78): PARTIAL_WAKE_LOCK  AsyncService 0x1 8502 10128 null
,08-31 03:05:54.211  8719  8756 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.211  8719  8756 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 03:05:54.221  8719  8756 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-31 03:05:54.221  8719  8756 E AndroidRuntime: Process: com.android.keychain, PID: 8719
08-31 03:05:54.221  8719  8756 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.221  8719  8756 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.221  8380  8380 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
08-31 03:05:54.221  1113  3577 D PMS     : releaseWL(20d0ca78): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,08-31 03:05:54.221  8380  8380 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,08-31 03:05:54.241  1113  1135 E ActivityManager: App crashed! Process: com.android.keychain,
08-31 03:05:54.241  1113  1135 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:54.241  1113  1135 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.241  1113  1135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.241  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.241  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.241  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.241  1113  1135 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.241  1113  1135 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.241  1113  1135 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.241  1113  1135 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.241  1113  1135 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.241  1113  1135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.241  1113  1135 W System.err: 	... 14 more
08-31 03:05:54.241  1113  1135 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,08-31 03:05:54.241  1113  1135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.241  1113  1135 W System.err: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.241  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.241  1113  1134 I ActivityManager: Recipient 6054
,08-31 03:05:54.241  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.241  1113  3101 D WifiService: Client connection lost with reason: 4
,08-31 03:05:54.241  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:54.251  1113  8766 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:54.251  1113  8766 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472605554256.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.251  1113  8766 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456),
08-31 03:05:54.251  1113  8766 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.251  1113  8766 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.251  1113  8766 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:54.251  1113  8766 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.251  1113  8766 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.251  1113  8766 E ErrorReport: 	at libcore.io.Posix.open(Native Method),
08-31 03:05:54.251  1113  8766 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.251  1113  8766 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.251  1113  8766 E ErrorReport: 	... 4 more
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303),
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
,08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
,08-31 03:05:54.241  1113  1135 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.241  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.241  1113  1135 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.241  1113  1135 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,08-31 03:05:54.241  1113  1135 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.241  1113  1135 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.241  1113  1135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.241  1113  1135 W System.err: 	,... 14 more
08-31 03:05:54.251  8380  8380 I DeviceManagement: WorkflowService: Starting workflow service
08-31 03:05:54.251  8380  8765 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@b0be8b1] args=[Bundle[mParcelledData.dataSize=112]]
08-31 03:05:54.251  8380  8765 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-31 03:05:54.251  8380  8765 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
08-31 03:05:54.251  8380  8765 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-31 03:05:54.261  8380  8765 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
08-31 03:05:54.261  8742  8742 I MultiDex: VM with version 2.1.0 has multidex support
08-31 03:05:54.261  8742  8742 I MultiDex: install
08-31 03:05:54.261  8742  8742 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 03:05:54.271  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system),
08-31 03:05:54.271  1113  3568 I ActivityManager: Start proc 8767:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
,08-31 03:05:54.271  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.271  1113  1134 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6054) has died
08-31 03:05:54.271  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.271  1113  1134 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10710ms
08-31 03:05:54.271  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.271  1113  1134 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20710ms
08-31 03:05:54.271  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.271  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:54.271  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:54.271  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:54.271  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:54.271  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:54.271  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:54.271  1113  3638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.271  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.271  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.271  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.271  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-31 03:05:54.271  8742  8742 D FaceDetectTask: checkIsOmronEnable start
08-31 03:05:54.271  8767  8767 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:54.271  8767  8767 W HTCLOG  : mask=0x18
08-31 03:05:54.271  8719  8756 D Process : killProcess, pid=8719
08-31 03:05:54.281  8742  8742 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
08-31 03:05:54.281  8719  8756 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:54.281  8719  8756 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.281  8719  8756 W HTCLOG  : mask=0x18
08-31 03:05:54.281  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.281  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.281  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.281  1113  3638 W System.err: 	... 12 more
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.281  8742  8742 D FaceDetectTask: IsOmronEnable : true
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedet,ect.OmronFaceDetectTask
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.281  8742  8742 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.281  8742  8742 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-31 03:05:54.281  8742  8742 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-31 03:05:54.281  8742  8742 W HTCLOG  : mask=0x18
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.os.Han,dler.dispatchMessage(Handler.java:102)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.281  8742  8742 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.291  8380  8765 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
08-31 03:05:54.291  8742  8742 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.291  1113  3831 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:54.291  8742  8742 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-31 03:05:54.291  8742  8742 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.291  8742  8742 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.291  8742  8742 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.291  8742  8742 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.291  8742  8742 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.291  8742  8742 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.291  8380  8795 I DeviceManagement: SessionStateController: Checking invariants...
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.291  8742  8742 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: FATAL EXCEPTION: main
08-31 03:05:54.291  8742  8742 E AndroidRuntime: Process: com.htc.launcher, PID: 8742
08-31 03:05:54.291  8742  8742 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.291  8742  8742 E AndroidRuntime: 	... 11 more
08-31 03:05:54.301  1113  3831 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-31 03:05:54.291  1113  3831 E ActivityManager: App crashed! Process: com.htc.launcher
08-31 03:05:54.301  1113  8797 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:54.301  1113  8797 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472605554308.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.301  1113  8797 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.301  1113  8797 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.301  1113  8797 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.301  1113  8797 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:54.301  1113  8797 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.301  1113  8797 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.301  1113  8797 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.301  1113  8797 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.301  1113  8797 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.301  1113  8797 E ErrorReport: 	... 4 more
08-31 03:05:54.301  1113  3831 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.301  1113  3831 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.301  1113  3831 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.301  1113  3831 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.301  1113  3831 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.301  1113  3831 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.301  1113  3831 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.301  1113  3831 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.301  1113  3831 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.301  1113  3831 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.301  1113  3831 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.301  1113  3831 W System.err: 	... 14 more
08-31 03:05:54.301  1113  3831 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.301  1113  3831 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.301  1113  3831 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.301  1113  3831 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.301  1113  3831 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.301  1113  3831 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.301  1113  3831 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.301  1113  3831 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.301  1113  3831 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.301  1113  3831 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.301  1113  3831 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.301  1113  3831 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.301  1113  3831 W System.err: 	... 14 more
08-31 03:05:54.301  8742  8742 D Process : killProcess, pid=8742
08-31 03:05:54.301  8742  8742 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:54.301  8742  8742 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.301  8742  8742 W HTCLOG  : mask=0x18
08-31 03:05:54.321  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.321  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.321  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.321  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.321  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.321  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:54.321  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:54.321  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:54.321  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:54.321  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:54.321  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:54.321  1113  3638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.321  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.321  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.321  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.321  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.321  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.321  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.321  1113  3638 W System.err: 	... 12 more
08-31 03:05:54.321  1113  3588 I ActivityManager: Recipient 8719
08-31 03:05:54.321  1113  3588 I ActivityManager: Process com.android.keychain (pid 8719) has died
08-31 03:05:54.321  1113  3588 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20660ms
08-31 03:05:54.331  1113  3588 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-31 03:05:54.331  1113  3588 V WindowManager: addAppToken: AppWindowToken{27841624 token=Token{beb6eb7 ActivityRecord{333b51b6 u0 com.htc.launcher/.Launcher t454}}} to stack=0 task=454 at 0
,08-31 03:05:54.351  8767  8767 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-31 03:05:54.351  8767  8767 W HTCLOG  : mask=0x18
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.351  8767  8767 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: FATAL EXCEPTION: main
08-31 03:05:54.351  8767  8767 E AndroidRuntime: Process: com.android.documentsui, PID: 8767
08-31 03:05:54.351  8767  8767 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-31 03:05:54.351  8767  8767 E AndroidRuntime: 	... 9 more
08-31 03:05:54.351  1113  3575 E ActivityManager: App crashed! Process: com.android.documentsui
08-31 03:05:54.351  1113  3575 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:54.351  1113  3575 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.351  1113  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.351  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.351  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.351  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.351  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.351  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.351  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:54.351  1113  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:54.351  1113  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.351  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.351  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.351  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.351  1113  3575 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.351  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.351  1113  3575 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.351  1113  3575 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.351  1113  3575 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.351  1113  3575 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.351  1113  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.351  1113  3575 W System.err: 	... 14 more
08-31 03:05:54.361  5593  5779 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
08-31 03:05:54.361  5593  5779 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-31 03:05:54.361  5593  5779 W HTCLOG  : mask=0x18
08-31 03:05:54.361  1113  3575 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.361  1113  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.361  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.361  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.361  1113  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.361  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.361  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.361  1113  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:54.361  1113  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-31 03:05:54.361  1113  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.361  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12,602)
08-31 03:05:54.361  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.361  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.361  1113  3575 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.361  1113  3575 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.361  1113  3575 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.361  1113  3575 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.361  1113  3575 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.361  1113  3575 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.361  1113  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.361  1113  8799 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:54.361  1113  8799 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472605554369.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.361  1113  8799 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.361  1113  8799 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.361  1113  8799 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.361  1113  8799 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:54.361  1113  8799 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.361  1113  8799 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.361  1113  8799 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.361  1113  8799 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.361  1113  8799 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.361  1113  8799 E ErrorReport: 	... 4 more
08-31 03:05:54.361  1113  3575 W System.err: 	... 14 more
08-31 03:05:54.361  5593  5779 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x558da5e700
08-31 03:05:54.361  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.361  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.361  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.361  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.361  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.361  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:54.361  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:54.361  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:54.361  1113  3588 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:54.361  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:54.361  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:54.361  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:54.361 , 1113  3638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.361  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.361  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.361  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.361  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.361  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.361  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.361  1113  3638 W System.err: 	... 12 more
08-31 03:05:54.361  8767  8767 D Process : killProcess, pid=8767
08-31 03:05:54.361  8767  8767 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:54.361  8767  8767 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.361  8767  8767 W HTCLOG  : mask=0x18
08-31 03:05:54.361  5593  5779 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-31 03:05:54.361  5593  5779 E AndroidRuntime: Process: android.process.media, PID: 5593
08-31 03:05:54.361  5593  5779 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.361  5593  5779 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.361  1113  3588 E ActivityManager: App crashed! Process: android.process.media
08-31 03:05:54.371  1113  3588 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.371  1113  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.371  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.371  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.371  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.371  1113  3588 W System.,err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.371  1113  3588 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.371  1113  3588 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.371  1113  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.371  1113  3588 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.371  1113  3588 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.371  1113  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.371  1113  3588 W System.err: 	... 14 more
08-31 03:05:54.371  1113  3588 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.371  1113  8800 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:54.371  1113  8800 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472605554379.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.371  1113  8800 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.371  1113  8800 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.371  1113  8800 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.371  1113  8800 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:54.371  1113  8800 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.371  1113  8800 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.371  1113  8800 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.371  1113  8800 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.371  1113  8800 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.371  1113  8800 E ErrorReport: 	... 4 more
08-31 03:05:54.371  1113  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.371  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.371  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.371  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.371  1113  3588 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.371  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.371  1113  3588 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.371  1113  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.371  1113  3588 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.371  1113  3588 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.371  1113  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.371  1113  3588 W System.err: 	... 14 more
08-31 03:05:54.371  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.381  1113  1158 I ActivityManager: Start proc 8801:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
08-31 03:05:54.381  5593  5779 D Process : killProcess, pid=5593
08-31 03:05:54.381  5593  5779 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:54.381  5593  5779 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.381  5593  5779 W HTCLOG  : mask=0x18
08-31 03:05:54.381  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.381  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.381  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.381  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.381  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:54.381  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:54.381  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:54.381  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:54.381  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:54.381  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:54.381  1113  3638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.381  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.381  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.381  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.381  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.381  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.381  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.381  1113  3638 W System.err: 	... 12 more
08-31 03:05:54.401  8801  8801 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:54.401  8801  8801 W HTCLOG  : mask=0x18
08-31 03:05:54.401   545   545 I art     : Explicit concurrent mark sweep GC freed 8659(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 130us total 20.367ms
08-31 03:05:54.401  1113  3587 I ActivityManager: Recipient 8742
08-31 03:05:54.411  8380  8795 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-31 03:05:54.411  8380  8795 W HTCLOG  : mask=0x18
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.,
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-31 03:05:54.411  8380  8795 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.411  1113  3587 I ActivityManager: Process com.htc.launcher (pid 8742) has died
08-31 03:05:54.421  1113  3587 I ActivityManager: Start proc 8823:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
08-31 03:05:54.421   492   492 E lowmemorykiller: Error writing /proc/5593/oom_score_adj; errno=22
08-31 03:05:54.421  1113  3587 W HTCLOG  : use specified tag [JavaBinder], func [0].
08-31 03:05:54.421  1113  3587 W HTCLOG  : mask=0x18
08-31 03:05:54.421  1113  3587 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-31 03:05:54.421  1113  3638 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-31 03:05:54.421   545   545 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 226us total 18.456ms
08-31 03:05:54.421  8380  8795 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.431  8380  8765 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.431  8380  8765 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
08-31 03:05:54.431  8823  8823 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:54.431  8823  8823 W HTCLOG  : mask=0x18
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.431  8380  8765 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.431  8380  8765 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@b0be8b1]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.431  8380  8765 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.441   545   545 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 107us total 17.238ms
08-31 03:05:54.441  8380  8380 I DeviceManagement: WorkflowService: Stopping workflow service
08-31 03:05:54.441  1113  1134 I ActivityManager: Killing 7781:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-31 03:05:54.441  1113  1134 D Process : killProcessQuiet, pid=7781
08-31 03:05:54.441  1113  1134 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-31 03:05:54.461  1113  3568 I ActivityManager: Recipient 8767
08-31 03:05:54.461  1113  3587 I ActivityManager: Recipient 5593
,08-31 03:05:54.531  1113  3820 I ActivityManager: Recipient 7781,
,08-31 03:05:54.571  1113  3568 I ActivityManager: Process com.android.documentsui (pid 8767) has died
08-31 03:05:54.571  1113  3587 I ActivityManager: Process android.process.media (pid 5593) has died
08-31 03:05:54.581  1113  3587 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 20406ms
,08-31 03:05:54.591  8801  8801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
,08-31 03:05:54.591  3363  3389 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false,
08-31 03:05:54.591  8823  8823 I MultiDex: VM with version 2.1.0 has multidex support
08-31 03:05:54.591  8823  8823 I MultiDex: install
,08-31 03:05:54.591  8823  8823 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 03:05:54.601  3245  3245 I NotificationStackScrollLayout: setBlockTouchEnabled:false
,08-31 03:05:54.601  8801  8844 D PowerUtils: getUserIdOfProcess, curUserId = 0
,08-31 03:05:54.601  8801  8844 D PowerUtils: isRunningUnderOwner, isOwner = true
,08-31 03:05:54.611  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-31 03:05:54.621  1113  3587 I ActivityManager: Start proc 8845:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
08-31 03:05:54.611  8823  8823 D FaceDetectTask: checkIsOmronEnable start
08-31 03:05:54.621  8823  8823 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
08-31 03:05:54.621  8801  8844 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.621  8823  8823 D FaceDetectTask: IsOmronEnable : true
08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.621  8823  8823 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.621  8801  8844 D PowerUsageService: removed uid = 10142
08-31 03:05:54.621  8845  8845 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:54.621  8845  8845 W HTCLOG  : mask=0x18
08-31 03:05:54.621  8823  8823 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
,08-31 03:05:54.631  8823  8823 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-31 03:05:54.631  8823  8823 W HTCLOG  : mask=0x18
08-31 03:05:54.631  8801  8844 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,08-31 03:05:54.631  8823  8823 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase:, 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.631  8823  8823 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.631  1113  3840 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.631  8823  8823 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-31 03:05:54.631  8823  8823 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(Hi,ghlightSelectCacheHelper.java:83)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.631  8823  8823 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.631  8823  8823 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.631  8823  8823 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.631  8823  8823 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.631  8823  8823 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.631  1113  3820 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:54.631  8801  8844 W HTCLOG  : mask=0x18
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:54.631  8801  8844 E SQLiteDa,tabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.631  8801  8844 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
08-31 03:05:54.631  8801  8844 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 8801
08-31 03:05:54.631  8801  8844 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.631  8801  8844 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.631  1113  3840 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.631  8823  8823 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.631  1113  3840 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.641  1113  3820 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-31 03:05:54.631  1113  3840 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.641  1113  8874 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:54.641  1113  8874 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472605554651.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.641  1113  8874 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.641  1113  8874 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.641  1113  8874 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.641  1113  8874 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:54.641  1113  8874 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.641  1113  8874 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.641  1113  8874 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.641  1113  8874 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.641  1113  8874 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.641  1113  8874 E ErrorReport: 	... 4 more
08-31 03:05:54.631  1113  3840 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.651  1113  8875 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:54.651  1113  8875 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472605554654.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.651  1113  8875 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.651  1113  8875 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.651  1113  8875 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.651  1113  8875 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:54.651  1113  8875 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.651  1113  8875 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.651  1113  8875 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.651  1113  8875 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.651  1113  8875 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.651  1113  8875 E ErrorReport: 	... 4 more
08-31 03:05:54.631  1113  3840 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.631  1113  3840 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.631  1113  3840 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.631  1113  3840 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: FATAL EXCEPTION: main
08-31 03:05:54.631  8823  8823 E AndroidRuntime: Process: com.htc.launcher, PID: 8823
08-31 03:05:54.631  8823  8823 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.631  8823  8823 E AndroidRuntime: 	... 11 more
08-31 03:05:54.631  1113  3840 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.631  1113  3840 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.631  1113  3840 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.631  1113  3840 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.631  1113  3840 W System.err: 	... 14 more
08-31 03:05:54.631  1113  3820 E ActivityManager: App crashed! Process: com.htc.launcher
08-31 03:05:54.631  1113  3840 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.631  1113  3840 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.631  1113  3840 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.631  1113  3840 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.631  1113  3840 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.631  1113  3840 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:54.641  1113  3840 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-31 03:05:54.641  1113  3840 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.641  1113  3840 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.641  1113  3840 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.641  1113  3840 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.641  1113  3840 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.641  1113  3840 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.641  1113  3840 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.641  1113  3840 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.641  1113  3840 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.641  1113  3840 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.641  1113  3840 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.641  1113  3840 W System.err: 	... 14 more
08-31 03:05:54.641  1113  3820 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.641  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.641  1113  3820 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.641  1113  3820 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.641  1113  3820 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.641  1113  3820 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.641  1113  3820 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.641  1113  3820 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.641  1113  3820 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.641  8801  8844 D Process : killProcess, pid=8801
08-31 03:05:54.641  1113  3820 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.641  1113  3820 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.641  8801  8844 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:54.641  1113  3820 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.641  1113  3820 W System.err: 	... 14 more
08-31 03:05:54.641  1113  3820 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.641  1113  3820 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.641  1113  3820 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.641  1113  3820 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.641  1113  3820 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.641  1113  3820 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.641  1113  3820 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.641  1113  3820 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.641  1113  3820 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.641  1113  3820 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.641  1113  3820 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.641  1113  3820 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.641  1113  3820 W System.err: 	... 14 more
08-31 03:05:54.641  8801  8844 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.641  8801  8844 W HTCLOG  : mask=0x18
08-31 03:05:54.641  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.641  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.641  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.641  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.641  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:54.641  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:54.641  8823  8823 D Process : killProcess, pid=8823
08-31 03:05:54.641  8823  8823 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:54.641  8823  8823 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.641  8823  8823 W HTCLOG  : mask=0x18
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:54.651  1113  3638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.651  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.651  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.651  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.651  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.651  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.651  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.651  1113  3638 W System.err: 	... 12 more
08-31 03:05:54.651  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.651  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.651  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.651  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.651  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:54.651  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:54.651  1113  3638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.651  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.651  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.651  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.651  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.651  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.651  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.651  1113  3638 W System.err: 	... 12 more
,08-31 03:05:54.691  8845  8877 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-31 03:05:54.691  8845  8877 W HTCLOG  : mask=0x18
08-31 03:05:54.701  1113  3587 I ActivityManager: Recipient 8823
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.701  8845  8877 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-31 03:05:54.701  8845  8877 E AndroidRuntime: Process: com.htc.updater, PID: 8845
08-31 03:05:54.701  8845  8877 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.701  8845  8877 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.701  1113  3831 I ActivityManager: Recipient 8801
08-31 03:05:54.701  1113  3587 I ActivityManager: Process com.htc.launcher (pid 8823) has died
08-31 03:05:54.701  1113  3587 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-31 03:05:54.701  1113  3587 V WindowManager: addAppToken: AppWindowToken{17199466 token=Token{267ed4c1 ActivityRecord{747c1a8 u0 com.htc.launcher/.Launcher t455}}} to stack=0 task=455 at 0
08-31 03:05:54.711  8845  8845 V UpdaterAPK | DownloadService: Service onStart
08-31 03:05:54.711  8845  8878 V UpdaterAPK | DownloadService: Updating for startId 1
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:98)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.711  8845  8878 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: Couldn't open downloads.db for writing (will try read-only):
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:98)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.711  8845  8878 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.711  1113  3587 I ActivityManager: Start proc 8880:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
08-31 03:05:54.721  8880  8880 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:54.721  8880  8880 W HTCLOG  : mask=0x18
08-31 03:05:54.721  1113  3831 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 8801) has died
08-31 03:05:54.721  8845  8878 W SQLiteOpenHelper: Opened downloads.db in read-only mode
08-31 03:05:54.721  1113  3831 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 30265ms
08-31 03:05:54.721  1113  3588 E ActivityManager: App crashed! Process: com.htc.updater
08-31 03:05:54.721  1113  3588 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:54.721  1113  3588 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.721  1113  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.721  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.721  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.721  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.721  1113  3588 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.721  1113  3588 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.721  1113  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.721  1113  3588 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.721  1113  3588 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.721  1113  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.721  1113  3588 W System.err: 	... 14 more
08-31 03:05:54.721  1113  3588 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.721  1113  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.721  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.721  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.721  1113  3588 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.721  1113  3588 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.721  1113  3588 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.721  1113  3588 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,08-31 03:05:54.721  1113  3588 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.721  1113  3588 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.721  1113  3588 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.721  1113  3588 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.721  1113  3588 W System.err: 	... 14 more
08-31 03:05:54.721  1113  3638 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-31 03:05:54.721  8845  8878 V UpdaterAPK | DownloadProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-31 03:05:54.731  8845  8878 V UpdaterAPK | DownloadProvider: created cursor android.database.sqlite.SQLiteCursor@3ede3196 on behalf of 8845
08-31 03:05:54.731  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.731  7681  7681 D AlarmReceiver: ACTION_RESTART_INTENT
08-31 03:05:54.731  8845  8877 D Process : killProcess, pid=8845
08-31 03:05:54.731  1113  8901 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:54.731  1113  8901 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472605554735.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.731  1113  8901 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.731  1113  8901 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.731  1113  8901 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.731  1113  8901 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:54.731  1113  8901 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.731  1113  8901 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.731  1113  8901 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.731  1113  8901 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.731  1113  8901 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.731  1113  8901 E ErrorReport: 	... 4 more
08-31 03:05:54.731  8845  8877 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:54.731  8845  8877 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.731  8845  8877 W HTCLOG  : mask=0x18
08-31 03:05:54.731  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.731  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.731  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.731  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.731  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:54.731  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:54.731  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:54.731  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:54.731  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:54.731  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:54.731  1113  3638 W System.err: 	at android.os.Handler.dispatchMessag,e(Handler.java:102)
08-31 03:05:54.731  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.731  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.731  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.731  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.731  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.731  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.731  1113  3638 W System.err: 	... 12 more
,08-31 03:05:54.741  7681  7681 D LocalBluetoothProfile: getPriorityOnValue = 100
08-31 03:05:54.741  1113  1113 D PMS     : releaseWL(347d3710): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
08-31 03:05:54.741  7681  7681 D LocalBluetoothProfile: getPriorityOffValue = 0
08-31 03:05:54.741  7681  7681 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-31 03:05:54.741  7681  7681 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-31 03:05:54.741  1113  1134 I ActivityManager: Recipient 8845
,08-31 03:05:54.751  3467  3467 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-31 03:05:54.771  8880  8880 I MultiDex: VM with version 2.1.0 has multidex support
08-31 03:05:54.771  8880  8880 I MultiDex: install
,08-31 03:05:54.771  8880  8880 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-31 03:05:54.771  7681  8903 D HtcModeClient: start the htcmodeservice thread
08-31 03:05:54.771  7681  8903 D HtcModeClient: initCanAgent
08-31 03:05:54.771  7681  8903 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-31 03:05:54.771  7681  8903 D HtcModeClient: sense info: version = none, id = 2
,08-31 03:05:54.771  7681  8903 D HtcModeClient: display info: width = 1080, height = 1776
08-31 03:05:54.771  7681  8903 D HtcModeClient: display info: mode = 10
,08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-31 03:05:54.781  8880  8880 D FaceDetectTask: checkIsOmronEnable start
,08-31 03:05:54.781  8880  8880 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
,08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.781  8880  8880 D FaceDetectTask: IsOmronEnable : true
08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.781  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-31 03:05:54.791  8880  8880 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-31 03:05:54.791  8880  8880 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-31 03:05:54.791  8880  8880 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-31 03:05:54.791  8880  8880 W HTCLOG  : mask=0x18
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Metho,d.java:372)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.791  8880  8880 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.791  8880  8880 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-31 03:05:54.791  8880  8880 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.791  8880  8880 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.791  8880  8880 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.791  8880  8880 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.791  8880  8880 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
,08-31 03:05:54.791  8880  8880 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429),
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.791  8880  8880 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: FATAL EXCEPTION: main
08-31 03:05:54.791  8880  8880 E AndroidRuntime: Process: com.htc.launcher, PID: 8880
08-31 03:05:54.791  8880  8880 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	,at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
,08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-31 03:05:54.791  8880  8880 E AndroidRuntime: 	... 11 more
,08-31 03:05:54.861  1113  1134 I ActivityManager: Process com.htc.updater (pid 8845) has died,
08-31 03:05:54.861  1113  1135 E ActivityManager: App crashed! Process: com.htc.launcher,
08-31 03:05:54.861  1113  1134 W ActivityManager: Scheduling restart of crashed service com.htc.updater/.download.DownloadService in 40127ms
,08-31 03:05:54.861  1113  1135 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.861  1113  1135 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-31 03:05:54.861  1113  1135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.861  1113  1135 W System.err: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.861  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.861  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
,08-31 03:05:54.861  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
,08-31 03:05:54.861  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
,08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.861  1113  1135 W System.err: 	,at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-31 03:05:54.861  1113  1135 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
,08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.861  1113  1135 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.861  1113  1135 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.861  1113  1135 W System.err: 	,at libcore.io.Posix.open(Native Method)
08-31 03:05:54.861  1113  1135 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.861  1113  1135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.861  1113  1135 W System.err: 	... 14 more
,08-31 03:05:54.861  1113  1135 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.861  1113  1135 W System.err: ,	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.861  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.861  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,08-31 03:05:54.861  1113  1135 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
,08-31 03:05:54.861  1113  1135 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
,08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
,08-31 03:05:54.861  1113  1135 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-31 03:05:54.861  1113  1135 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-31 03:05:54.861  1113  1135 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-31 03:05:54.861  1113  1135 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,08-31 03:05:54.861  1113  1135 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.861  1113  1135 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.861  1113  1135 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.861  1113  1135 W System.err: ,	... 14 more
08-31 03:05:54.871  7681  7681 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-31 03:05:54.871  7681  7681 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-31 03:05:54.871  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
08-31 03:05:54.871  7681  7681 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
,08-31 03:05:54.871  7681  7681 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-31 03:05:54.871  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = false
08-31 03:05:54.871  7681  7681 D HtcModeClient: connectState: Force_AWAKE = false
08-31 03:05:54.871  7681  7681 D HtcModeClient: connectState: PHONE_PULGIN = true
08-31 03:05:54.871  7681  7681 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-31 03:05:54.871  3179  3179 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: nl80211: New scan results available
08-31 03:05:54.881  1113  3069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-31 03:05:54.871  3179  3179 D wpa_supplicant: nl80211: Scan probed for SSID ''
,08-31 03:05:54.871  3179  3179 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-31 03:05:54.871  3179  3179 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: Scan completed in 3.605452 seconds
08-31 03:05:54.871  7681  7739 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,08-31 03:05:54.871  7681  7739 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
08-31 03:05:54.871  3179  3179 D wpa_supplicant: nl80211: Received scan results (41 BSSes)
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-47
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-47
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-50
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-51,
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-59
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-59
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-68
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-70
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-71,
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-72
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-72
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-72
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-72
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d2 freq=2437 level=-73
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-78
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-78
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d5 freq=2437 level=-74,
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-79
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:35 freq=2412 level=-75
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-75
,08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:36 freq=2412 level=-76
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-76
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-80
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:9f freq=5180 level=-87
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:9b freq=5180 level=-87
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:95 freq=2462 level=-83
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:99 freq=5180 level=-88
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:96 freq=2462 level=-84
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 00:fe:c8:73:02:06 freq=2462 level=-86
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 00:fe:c8:73:02:02 freq=2462 level=-87
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:7e freq=5200 level=-60
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-70
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-71
08-31 03:05:54.881  1113  3577 I ActivityManager: Start proc 8913:com.google.android.gms/u0a19 for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-73
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-74
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-74
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-79
08-31 03:05:54.881  1113  1135 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
,08-31 03:05:54.871  3179  3179 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-75
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:12:64:9e freq=5180 level=-88
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [] 84:b2:61:21:47:5e freq=5180 level=-89
08-31 03:05:54.871  3179  3179 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-85
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Start scan result update 8
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 89 BSSID 84:b2:61:1a:ce:72 SSID '\x00'
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 90 BSSID 84:b2:61:1a:ce:74 SSID '\x00'
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 91 BSSID 84:b2:61:12:64:95 SSID '\x00'
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.891  1113  8919 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-31 03:05:54.891  1113  8919 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472605554894.dbox_tmp: open failed: EROFS (Read-only file system)
08-31 03:05:54.891  1113  8919 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.891  1113  8919 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.891  1113  8919 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:54.891  1113  8919 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-31 03:05:54.891  1113  8919 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-31 03:05:54.891  1113  8919 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.891  1113  8919 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.891  1113  8919 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.891  1113  8919 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.891  1113  8919 E ErrorReport: 	... 4 more
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 92 BSSID 00:fe:c8:73:02:06 SSID '\x00'
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Add new id 93 BSSID 00:fe:c8:73:02:02 SSID '\x00'
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 6 BSSID 84:b2:61:1a:ce:7b SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 20 BSSID 84:b2:61:1c:62:d6 SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 26 BSSID 84:b2:61:0f:9c:34 SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 29 BSSID 84:b2:61:12:64:9a SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D ,wpa_supplicant: wlan0: BSS: Remove ID 73 BSSID 84:b2:61:12:64:92 SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 72 BSSID 84:b2:61:1c:62:db SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 52 BSSID 84:b2:61:21:47:5b SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 58 BSSID 00:fe:c8:73:02:05 SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 83 BSSID 84:b2:61:21:47:52 SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 84 BSSID 84:b2:61:21:47:56 SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: BSS: Remove ID 76 BSSID 84:b2:61:1c:62:de SSID '\x00' due to no match in scan
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: BSS: last_scan_res_used=41/64
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: Scan-only results received
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1113-2\x00
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: Radio work 'scan'@0x555b80cca0 done in 3.650922 seconds
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-31 03:05:54.871  3179  3179 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: Cancelling scan request
08-31 03:05:54.871  3179  3179 D wpa_supplicant: PNO: No configured SSIDs
08-31 03:05:54.871  1113  3069 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-31 03:05:54.871  3179  3179 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-31 03:05:54.881  3179  3179 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-31 03:05:54.891  8880  8880 D Process : killProcess, pid=8880
08-31 03:05:54.891  8880  8880 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-31 03:05:54.891  8880  8880 W HTCLOG  : use specified tag [Process], func [0].
08-31 03:05:54.891  8880  8880 W HTCLOG  : mask=0x18
08-31 03:05:54.891  1113  3638 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-31 03:05:54.891  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 03:05:54.891  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:54.891  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-31 03:05:54.891  1113  3638 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-31 03:05:54.891  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPre,ference.writeProperty(HtcSystemUPPreference.java:119)
08-31 03:05:54.901  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-31 03:05:54.901  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-31 03:05:54.901  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-31 03:05:54.901  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-31 03:05:54.901  1113  3638 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-31 03:05:54.901  1113  3638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:54.901  1113  3638 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-31 03:05:54.901  1113  3638 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:54.901  1113  3638 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:54.901  3179  3179 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-31 03:05:54.901  1113  3069 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-31 03:05:54.901  1113  1113 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 15
08-31 03:05:54.901  4416  4416 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-31 03:05:54.901  4416  5879 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-31 03:05:54.901  8913  8913 W HTCLOG  : use specified tag [FDManager], func [0].
08-31 03:05:54.901  8913  8913 W HTCLOG  : mask=0x18
08-31 03:05:54.901  1113  3638 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:54.911  1113  3638 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:54.911  1113  3638 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 03:05:54.911  1113  3638 W System.err: 	... 12 more
08-31 03:05:54.931  8913  8913 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 03:05:54.931  8913  8913 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 03:05:54.941  8913  8913 I MultiDex: VM with version 2.1.0 has multidex support,
08-31 03:05:54.941  8913  8913 I MultiDex: install
08-31 03:05:54.941  8913  8913 I MultiDex: VM has multidex support, MultiDex support library is disabled.

```
