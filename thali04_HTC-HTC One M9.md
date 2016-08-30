#### Test 82642184ea62b6e_thali04_HTC-HTC One M9 Logs


```
--------- beginning of system
08-30 23:15:09.911  1116  3756 D PMS     : acquireWL(14ffa75e): PARTIAL_WAKE_LOCK  Icing 0x1 4036 10019 null
--------- beginning of main
08-30 23:15:09.951  8267  8267 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8267 dbg=false s=true
08-30 23:15:09.951  8267  8267 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
08-30 23:15:09.951  6541  8265 I ApplicationLogger: canRun() : Opted Out
08-30 23:15:09.951  6541  8265 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 444 ms] updated apps [took 444 ms] 
08-30 23:15:09.961  1116  3585 D Process : killProcessQuiet, pid=7855
08-30 23:15:09.961  1116  3585 I ActivityManager: Start proc 8295:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-30 23:15:09.961  1116  3585 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
08-30 23:15:09.961  1116  3585 I ActivityManager: Killing 7855:com.htc.calendar/u0a6 (adj 15): empty #17
08-30 23:15:09.971  8295  8295 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:09.971  8295  8295 W HTCLOG  : mask=0x18
08-30 23:15:09.991  3157  3157 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 23:15:09.991  3157  3157 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 23:15:09.991  3157  3157 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-30 23:15:10.001  1116  3043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-30 23:15:09.991  3157  3157 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: Scan completed in 3.602390 seconds
08-30 23:15:09.991  3157  3157 D wpa_supplicant: nl80211: Received scan results (48 BSSes)
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-45
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-46
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-44
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-44
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-59
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-59
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-60
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-60
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-72
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-72
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d5 freq=2437 level=-72
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-72
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-72
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d0 freq=2437 level=-73
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d4 freq=2437 level=-73
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d2 freq=2437 level=-73
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d6 freq=2437 level=-73
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-73
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-78
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-78
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-78
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:36 freq=2412 level=-74
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-74
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:34 freq=2412 level=-74
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-79
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-75
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-79
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:9a freq=5180 level=-87
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:90 freq=2462 level=-85
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:95 freq=2462 level=-85
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] e4:aa:5d:fc:5b:f5 freq=2437 level=-86
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:04 freq=2462 level=-86
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:00 freq=2462 level=-86
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:21:47:56 freq=2437 level=-86
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:21:47:50 freq=2437 level=-87
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:02 freq=2462 level=-87
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] e4:aa:5d:fc:5b:f4 freq=2437 level=-88
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7e freq=5200 level=-60
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-69
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-72
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-72
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-73
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-78
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-74
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-75
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-86
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:21:47:53 freq=2437 level=-87
08-30 23:15:09.991  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:91 freq=2462 level=-88
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Start scan result update 6
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 75 BSSID 84:b2:61:12:64:95 SSID '\x00'
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 76 BSSID e4:aa:5d:fc:5b:f5 SSID '\x00'
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 77 BSSID 00:fe:c8:73:02:00 SSID '\x00'
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 78 BSSID 84:b2:61:21:47:56 SSID '\x00'
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 79 BSSID 84:b2:61:21:47:50 SSID '\x00'
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 80 BSSID 00:fe:c8:73:02:02 SSID '\x00'
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 53 BSSID 84:b2:61:0f:9c:35 SSID '\x00' due to no match in scan
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 59 BSSID 84:b2:61:12:64:96 SSID '\x00' due to no match in scan
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 60 BSSID 84:b2:61:12:64:94 SSID '\x00' due to no match in scan
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 61 BSSID 84:b2:61:21:47:5b SSID '\x00' due to no match in scan
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 62 BSSID 84:b2:61:21:47:5f SSID '\x00' due to no match in scan
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 55 BSSID 00:fe:c8:73:02:05 SSID '\x00' due to no match in scan
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 64 BSSID 84:b2:61:21:47:52 SSID '\x00' due to no match in scan
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 66 BSSID 00:fe:c8:73:00:43 SSID 'RA-WINGS' due to no match in scan
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: BSS: last_scan_res_used=48/64
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: Scan-only results received
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:09.991  3157  3157 D wpa_supplicant: wlan0: Radio work 'scan'@0x55828990a0 done in 3.645865 seconds
08-30 23:15:10.001  3157  3157 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 23:15:10.001  3157  3157 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 23:15:10.001  3157  3157 D wpa_supplicant: wlan0: Cancelling scan request
08-30 23:15:10.001  3157  3157 D wpa_supplicant: PNO: No configured SSIDs
08-30 23:15:10.001  1116  3043 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 23:15:10.001  3157  3157 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 23:15:10.041  1116  3518 I ActivityManager: Recipient 7855
08-30 23:15:10.111  3157  3157 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-30 23:15:10.151  3157  3157 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-30 23:15:10.151  1116  3043 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-30 23:15:10.161  4328  4328 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 23:15:10.161  1116  1116 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 12
08-30 23:15:10.161  4328  5848 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 23:15:10.201  1116  3520 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 23:15:10.201  1116  3581 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 23:15:10.231  8295  8295 D DocsApplication: Plugin installer initialized.
08-30 23:15:10.231  1116  1135 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 23:15:10.251  8295  8295 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3e8537fd com.google.android.apps.docs}
08-30 23:15:10.271  8295  8295 D TAG     : onCreate()
08-30 23:15:10.281  8295  8295 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 23:15:10.291  1116  3518 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 23:15:10.431  3542  3972 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-30 23:15:10.431  3542  3972 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@24310bb3 +
08-30 23:15:10.431  3542  3972 I Prism.WidgetManager: onLoadItems() +
08-30 23:15:10.451  3542  3972 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
08-30 23:15:10.541  3521  4326 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-30 23:15:10.541  3521  4326 D PhoneApp: -- N1 =0
08-30 23:15:10.541  3521  4326 D PhoneApp: -- N2 =0
08-30 23:15:10.541  3521  4326 D PhoneApp: -- N3 =0
08-30 23:15:10.661  3542  3972 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 23:15:10.741   560   560 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
08-30 23:15:10.871  8316  8316 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-30 23:15:10.871  8316  8316 W HTCLOG  : mask=0x18
08-30 23:15:10.871  3542  3972 I Prism.WidgetManager: onLoadItems() -
08-30 23:15:10.871  3542  3972 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@24310bb3 -
08-30 23:15:10.951  4036  6758 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-30 23:15:10.981  4036  6758 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 23:15:11.021  8316  8319 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-30 23:15:11.021  8316  8319 W HTCLOG  : mask=0x18
08-30 23:15:11.021  8316  8319 E cutils-trace: Error opening trace file: Permission denied (13)
08-30 23:15:11.021  4036  6758 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
08-30 23:15:11.031  1116  3797 D PMS     : releaseWL(14ffa75e): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-30 23:15:11.081  8316  8316 D CustomizationManager: ====startRecUseTime====
08-30 23:15:11.081  8316  8316 D htc.customization.log.level:  is 
08-30 23:15:11.081  8316  8316 W CustomizationLogLevel: Level value is invalid, use default level 2
08-30 23:15:11.151  8316  8316 D CustomizationManager:  Read ACC file spent 0.037 (s)
08-30 23:15:11.151  8316  8316 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-30 23:15:11.151  8316  8316 I CustomizationCIDLoader: Parsing tag category name = application
08-30 23:15:11.161  8316  8316 I CustomizationCIDLoader: Parsing tag category name = system
08-30 23:15:11.161  8316  8316 I CustomizationCIDLoader: Parsing tag category name = Settings
08-30 23:15:11.161  8316  8316 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-30 23:15:11.161  8316  8316 I CustomizationCIDLoader: Parsing tag category name = ACC
08-30 23:15:11.161  8316  8316 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-30 23:15:11.161  8316  8316 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-30 23:15:11.161  8316  8316 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-30 23:15:11.161  8316  8316 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-30 23:15:11.161  8316  8316 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-30 23:15:11.161  8316  8316 D CustomizationManager:  Read CID file spent 0.082 (s)
08-30 23:15:11.161  8316  8316 D CustomizationManager:  All configurations done spent 0.082 (s)
08-30 23:15:11.201  1116  1135 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8316 on display 0
08-30 23:15:11.211  1116  1181 D PMS     : acquireHCC(20e2480c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1116 1000 null
08-30 23:15:11.211  1116  1181 D PMS     : acquireHCC(37948555): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1116 1000 null
08-30 23:15:11.211  1116  1135 V WindowManager: addAppToken: AppWindowToken{1f71d8f8 token=Token{1c5e85b ActivityRecord{1f9adb6a u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-30 23:15:11.221  1116  1135 I ActivityManager: Start proc 8333:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-30 23:15:11.221  8316  8316 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-30 23:15:11.221  8316  8316 W HTCLOG  : mask=0x18
08-30 23:15:11.221  8316  8332 W HTCLOG  : use specified tag [Vector], func [0].
08-30 23:15:11.221  8316  8332 W HTCLOG  : mask=0x18
08-30 23:15:11.221  8316  8331 W HTCLOG  : use specified tag [Vector], func [0].
08-30 23:15:11.221  8316  8331 W HTCLOG  : mask=0x18
08-30 23:15:11.231  8333  8333 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:11.231  8333  8333 W HTCLOG  : mask=0x18
08-30 23:15:11.241  1116  1116 V ActivityManager: Display changed displayId=0
08-30 23:15:11.251  3328  3328 D DotMatrix: [EventService]  onDisplayChanged: 0
08-30 23:15:11.251  3328  3328 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-30 23:15:11.251  1116  4214 D ActivityManager: screenshot for ActivityRecord{1f9adb6a u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-30 23:15:11.271  3542  3542 I TrimMemoryManager: [trimMemory] 20
08-30 23:15:11.301  8333  8333 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-30 23:15:11.331  1116  3030 D PMS     : acquireWL(33034436): PARTIAL_WAKE_LOCK  *alarm* 0x1 1116 1000 WorkSource{1000}
08-30 23:15:11.331  1116  3030 V AlarmManager: sending alarm PendingIntent{d678ca4: PendingIntentRecord{2cc90a0d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=82208, Int=0
08-30 23:15:11.331  1116  3030 V AlarmManager: sending alarm PendingIntent{25b76dc2: PendingIntentRecord{189707d3 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1472591708422, Int=0
08-30 23:15:11.331  1116  3030 V AlarmManager: sending alarm PendingIntent{1ce2cf10: PendingIntentRecord{1e0a2138 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=88215, Int=0
08-30 23:15:11.351  8333  8333 I LibraryLoader: Time to load native libraries: 28 ms (timestamps 8215-8243)
08-30 23:15:11.351  8333  8333 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 23:15:11.361  8333  8333 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19f256f9}
08-30 23:15:11.361  8333  8333 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 23:15:11.361  8333  8333 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 23:15:11.371  8333  8333 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 23:15:11.371  8333  8333 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 23:15:11.371  8333  8333 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 23:15:11.401  8333  8358 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
08-30 23:15:11.411  5473  5506 D BluetoothAdapterService(71843651): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28b934b4
08-30 23:15:11.421  8333  8333 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-30 23:15:11.421  8333  8333 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
08-30 23:15:11.421  8333  8333 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
08-30 23:15:11.421  8295  8363 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:11.421  8295  8363 W HTCLOG  : mask=0x18
08-30 23:15:11.421  8333  8333 W HTCLOG  : use specified tag [libEGL], func [3].
08-30 23:15:11.421  8333  8333 W HTCLOG  : mask=0x18
08-30 23:15:11.431  8333  8333 W HTCLOG  : use specified tag [libEGL], func [3].
08-30 23:15:11.431  8333  8333 W HTCLOG  : mask=0x18
08-30 23:15:11.431  8333  8333 I Adreno  : QUALCOMM build                   : 065751b, 
08-30 23:15:11.431  8333  8333 I Adreno  : Build Date                       : 04/15/15
08-30 23:15:11.431  8333  8333 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-30 23:15:11.431  8333  8333 I Adreno  : Local Branch                     : 
08-30 23:15:11.431  8333  8333 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-30 23:15:11.431  8333  8333 I Adreno  : Remote Branch                    : NONE
08-30 23:15:11.431  8333  8333 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,08-30 23:15:11.471  1116  1135 D Process : killProcessQuiet, pid=7460
08-30 23:15:11.471  1116  1135 I ActivityManager: Start proc 8377:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
08-30 23:15:11.471  1116  1135 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
08-30 23:15:11.471  1116  1135 I ActivityManager: Killing 7460:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
,08-30 23:15:11.481  8377  8377 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:11.481  8377  8377 W HTCLOG  : mask=0x18
,08-30 23:15:11.571  1116  3520 I ActivityManager: Recipient 7460
,08-30 23:15:11.601  8295  8295 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-30 23:15:11.611  8377  8377 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 23:15:11.621  8333  8369 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,08-30 23:15:11.631  8333  8333 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-30 23:15:11.641  8333  8333 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,08-30 23:15:11.651  8333  8333 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,08-30 23:15:11.651  8333  8333 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
08-30 23:15:11.651  8333  8333 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 23:15:11.691  8333  8408 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 23:15:11.691  8333  8408 W HTCLOG  : mask=0x18
,08-30 23:15:11.691  1116  1135 V WindowManager: Adding window Window{dccebb3 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{2038d1e1 u0 com.htc.launcher/com.htc.launcher.Launcher})
,08-30 23:15:11.701  1116  3606 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,08-30 23:15:11.721  8333  8333 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
08-30 23:15:11.721  8333  8333 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-30 23:15:11.721  8333  8333 W HTCLOG  : mask=0x18
08-30 23:15:11.721  8333  8333 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 23:15:11.721  8333  8333 W HTCLOG  : mask=0x18
,08-30 23:15:11.731  8333  8408 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
08-30 23:15:11.731  8333  8408 W HTCLOG  : mask=0x18
08-30 23:15:11.731  8333  8408 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 23:15:11.731  8333  8408 W HTCLOG  : mask=0x18
08-30 23:15:11.731  8333  8408 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 23:15:11.731  8333  8408 W HTCLOG  : mask=0x18
08-30 23:15:11.731  8333  8408 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 23:15:11.731  8333  8408 W HTCLOG  : mask=0x18
,08-30 23:15:11.741  8333  8408 W HTCLOG  : use specified tag [Surface], func [3].
,08-30 23:15:11.741  8333  8408 W HTCLOG  : mask=0x18
08-30 23:15:11.741  8333  8408 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-30 23:15:11.741  8333  8408 W HTCLOG  : mask=0x18
08-30 23:15:11.741  8333  8408 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-30 23:15:11.741  8333  8408 W HTCLOG  : mask=0x18
,08-30 23:15:11.801  1116  1172 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +550ms (total +589ms),
,08-30 23:15:11.821  1116  3479 D PMS     : acquireWL(65c189c): PARTIAL_WAKE_LOCK  AsyncService 0x1 8377 10128 null
,08-30 23:15:11.821  1116  4214 D PMS     : releaseWL(65c189c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,08-30 23:15:11.851  8333  8333 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8333,
,08-30 23:15:11.851  3563  3563 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 23:15:11.851  3563  3563 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
08-30 23:15:11.851  3563  3563 D c       : Getting all permits...
,08-30 23:15:11.851  3563  3563 D a       : Opening database...
,08-30 23:15:11.861  3563  3563 D a       : Opening database auth.proximity.permit_store...
08-30 23:15:11.861  3563  3563 D a       : Closing database...
,08-30 23:15:11.861  4036  4036 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-30 23:15:11.871  1116  1116 D PMS     : acquireWL(2128067a): PARTIAL_WAKE_LOCK  *backup* 0x1 1116 1000 null
,08-30 23:15:11.871  1116  3113 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
08-30 23:15:11.871  1116  3113 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
08-30 23:15:11.871  1116  3113 D PMS     : releaseWL(2128067a): PARTIAL_WAKE_LOCK  *backup* 0x1 null
08-30 23:15:11.871  7627  7627 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 23:15:11.881  4036  8421 D LocationInitializer: Restart initialization of location
,08-30 23:15:11.881  7627  7627 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 23:15:11.881  7627  7627 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 23:15:11.881  7627  7627 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 23:15:11.881  1116  1116 D PMS     : releaseWL(33034436): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-30 23:15:11.881  7627  7627 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 23:15:11.891  7627  8423 D HtcModeClient: start the htcmodeservice thread,
08-30 23:15:11.891  7627  8423 D HtcModeClient: initCanAgent
08-30 23:15:11.891  7627  8423 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 23:15:11.901  7627  8423 D HtcModeClient: sense info: version = none, id = 2
,08-30 23:15:11.901  7627  8423 D HtcModeClient: display info: width = 1080, height = 1776
08-30 23:15:11.901  7627  8423 D HtcModeClient: display info: mode = 10
,08-30 23:15:11.911  8333  8333 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,08-30 23:15:11.951  8333  8413 D jxcore_app_log: JniHelper::setJavaVM(0xab140b70), pthread_self() = -1408621696,
08-30 23:15:11.951  8333  8413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 23:15:11.951  8333  8413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 23:15:11.951  8333  8413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 23:15:11.951  8333  8413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 23:15:11.951  8333  8413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 23:15:11.951  8333  8413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d4a664c added. We now have 1 listener(s)
,08-30 23:15:11.951  1116  3479 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
08-30 23:15:11.951  8333  8413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
08-30 23:15:11.951  8333  8413 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-30 23:15:11.951  8333  8413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 23:15:11.951  8333  8413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 23:15:11.961  8333  8413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da4b9b added. We now have 1 listener(s),
08-30 23:15:11.961  8333  8413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 23:15:11.961  1116  3075 D WifiService: New client listening to asynchronous messages
08-30 23:15:11.961  8333  8413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 23:15:11.961  8333  8413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 23:15:11.961  8333  8413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 23:15:11.961  8333  8413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 23:15:11.961  8333  8413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 23:15:11.961  8333  8413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 23:15:11.961  1116  3463 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-30 23:15:11.961  8333  8413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
08-30 23:15:11.971  5473  5956 D BluetoothAdapterService(71843651): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28b934b4
08-30 23:15:11.971  8333  8413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 23:15:11.971  8333  8413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:15:11.971  8333  8413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:15:11.971  8333  8413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:15:11.971  8333  8413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:15:11.971  8333  8413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:15:11.971  8333  8413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 23:15:11.971  8333  8413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 23:15:11.971  8333  8413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 23:15:11.971  8333  8413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 23:15:11.971  8333  8413 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 23:15:11.971  8333  8413 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 23:15:11.971  8333  8333 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 23:15:12.001  7627  7627 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-30 23:15:12.001  7627  7627 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 23:15:12.001  7627  7627 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 23:15:12.001  7627  7627 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 23:15:12.001  7627  7627 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 23:15:12.001  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 23:15:12.001  7627  7627 D HtcModeClient: connectState: Force_AWAKE = false
08-30 23:15:12.001  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 23:15:12.001  7627  7627 D HtcModeClient: connectState: POWERCONNECTED_READY = true
08-30 23:15:12.021  8333  8333 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 23:15:12.201  1116  1181 D PMS     : releaseHCC(20e2480c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,08-30 23:15:12.201  1116  1181 D PMS     : releaseHCC(37948555): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-30 23:15:12.381  8333  8427 W jxcore-log: Initializing JXcore engine
08-30 23:15:12.381  8333  8427 W jxcore-log: JXcore engine is ready
,08-30 23:15:12.441  8333  8427 W jxcore-log: Starting JXcore engine
,08-30 23:15:12.541  8333  8427 W jxcore-log: Platform android
08-30 23:15:12.541  8333  8427 W jxcore-log: 
08-30 23:15:12.541  8333  8427 W jxcore-log: Process ARCH arm,
08-30 23:15:12.541  8333  8427 W jxcore-log: 
,08-30 23:15:12.731  8333  8427 I jxcore-log: JXcore Cordova bridge is ready!
08-30 23:15:12.731  8333  8427 I jxcore-log: 
08-30 23:15:12.731  8333  8427 W jxcore-log: JXcore engine is started
,08-30 23:15:12.741  8333  8413 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 23:15:12.751  8333  8333 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 23:15:13.981  8156  8171 E AndroidHttpClient: Leak found,
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: ,	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
,08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442),
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: ,	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:13.981  8156  8171 E AndroidHttpClient: ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 23:15:14.011  7627  8423 I HtcModeClient: handler message = 4011
08-30 23:15:14.011  7627  8423 D HtcModeClient: getConnectionCheckCount first 0
08-30 23:15:14.011  7627  8423 D HtcModeClient: getConnectionCheckCount count = 7
08-30 23:15:14.011  7627  8423 E HtcModeClient: Check connection and retry 8 times.
08-30 23:15:14.011  7627  8423 D HtcModeClient: setConnectionCheckCount count = 8
08-30 23:15:14.011  7627  8423 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 23:15:14.011  7627  7627 D HtcModeClient: setBtPriority priority = on
08-30 23:15:14.011  7627  7627 D HtcModeClient: unbindBlueToothService,
08-30 23:15:14.011  7627  7627 D HtcModeClient: Don't start project servcice
08-30 23:15:14.011  7627  7627 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 23:15:14.011  7627  7627 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 23:15:14.011  7627  7627 D SilentMusic: call stop,
08-30 23:15:14.011  7627  7627 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 23:15:14.011  7627  8424 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 23:15:14.021  7627  7627 D HtcModeClient: onDestroy,
,08-30 23:15:14.571  8211  8211 D Process : killProcess, pid=8211,
08-30 23:15:14.571  8211  8211 D Process : com.google.android.gms.car.gt.run:127 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
08-30 23:15:14.571  8211  8211 W HTCLOG  : use specified tag [Process], func [0].,
08-30 23:15:14.571  8211  8211 W HTCLOG  : mask=0x18
08-30 23:15:14.571   494   494 E lowmemorykiller: Error writing /proc/8211/oom_score_adj; errno=22,
,08-30 23:15:14.721  1116  2261 I ActivityManager: Recipient 8211
,08-30 23:15:14.721  1116  2261 I ActivityManager: Process com.google.android.gms:car (pid 8211) has died
,08-30 23:15:15.101  1116  1116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,08-30 23:15:15.451  8295  8295 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-30 23:15:16.381  1116  1135 D PMS     : releaseWL(266eebc): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,08-30 23:15:16.411  8295  8357 I GAV2    : Thread[GAThread,5,main]: No campaign data found.,
,08-30 23:15:19.011  1116  3030 D PMS     : acquireWL(3aa53db8): PARTIAL_WAKE_LOCK  *alarm* 0x1 1116 1000 WorkSource{10027}
08-30 23:15:19.021  1116  3030 V AlarmManager: sending alarm PendingIntent{5798791: PendingIntentRecord{1e0a2138 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=93904, Int=0
08-30 23:15:19.021  7627  7627 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 23:15:19.021  1116  1116 D PMS     : releaseWL(3aa53db8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
,08-30 23:15:19.031  7627  7627 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 23:15:19.031  7627  7627 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 23:15:19.031  7627  7627 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 23:15:19.031  7627  7627 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 23:15:19.051  7627  8435 D HtcModeClient: start the htcmodeservice thread,
08-30 23:15:19.051  7627  8435 D HtcModeClient: initCanAgent,
,08-30 23:15:19.051  7627  8435 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-30 23:15:19.051  7627  8435 D HtcModeClient: sense info: version = none, id = 2
,08-30 23:15:19.051  7627  8435 D HtcModeClient: display info: width = 1080, height = 1776
08-30 23:15:19.051  7627  8435 D HtcModeClient: display info: mode = 10
,08-30 23:15:19.151  7627  7627 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,08-30 23:15:19.151  7627  7627 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 23:15:19.151  7627  7627 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 23:15:19.151  7627  7627 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false,
08-30 23:15:19.151  7627  7627 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
,08-30 23:15:19.151  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 23:15:19.151  7627  7627 D HtcModeClient: connectState: Force_AWAKE = false,
08-30 23:15:19.151  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 23:15:19.151  7627  7627 D HtcModeClient: connectState: POWERCONNECTED_READY = true,
,08-30 23:15:21.161  7627  8435 I HtcModeClient: handler message = 4011
,08-30 23:15:21.171  7627  8435 D HtcModeClient: getConnectionCheckCount first 0
08-30 23:15:21.171  7627  8435 D HtcModeClient: getConnectionCheckCount count = 8
08-30 23:15:21.171  7627  8435 E HtcModeClient: Check connection and retry 9 times.
,08-30 23:15:21.171  7627  8435 D HtcModeClient: setConnectionCheckCount count = 9,
08-30 23:15:21.171  7627  8435 D HtcModeClient: setupRestart delayedTime = 3000,
,08-30 23:15:21.181  7627  7627 D HtcModeClient: setBtPriority priority = on
08-30 23:15:21.181  7627  7627 D HtcModeClient: unbindBlueToothService
08-30 23:15:21.181  7627  7627 D HtcModeClient: Don't start project servcice,
,08-30 23:15:21.181  7627  7627 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 23:15:21.181  7627  7627 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 23:15:21.181  7627  7627 D SilentMusic: call stop,
08-30 23:15:21.181  7627  7627 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 23:15:21.181  7627  8436 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 23:15:21.191  7627  7627 D HtcModeClient: onDestroy
,08-30 23:15:21.201  1116  1116 D UsbnetService: BroadcastReceiver::onReceive+
08-30 23:15:21.201  1116  3756 D PMS     : acquireWL(38120ece): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1116 1000 null
08-30 23:15:21.201  1116  1116 D UsbnetService: onReceive BATTERY_CHANGED
08-30 23:15:21.201  1116  3756 I BatteryService: n_update end
08-30 23:15:21.201  1116  1116 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,08-30 23:15:21.201  1116  3756 D PMS     : releaseWL(38120ece): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-30 23:15:21.201  1116  1116 D UsbnetService: BroadcastReceiver::onReceive-
08-30 23:15:21.201  1116  1177 D HtcPowerSaver: updateBatteryInfo
08-30 23:15:21.201  3200  3665 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-30 23:15:21.201  1116  1116 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-30 23:15:21.201  3328  3328 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-30 23:15:21.201  1116  1116 D HtcPowerSaver: Checking...
08-30 23:15:21.201  3328  3328 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-30 23:15:21.201  1116  1116 I HtcPowerSaver: >> updateStatus
08-30 23:15:21.201  3328  3328 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true,
08-30 23:15:21.201  3200  3200 D PowerUI : closing low battery warning: level=100
08-30 23:15:21.201  1116  3075 D WifiController: handleMessage: E msg.what=155652
08-30 23:15:21.201  1116  3075 D WifiController: battery changed pluggedType: 2
08-30 23:15:21.201  1116  3075 D WifiController: processMsg: DeviceActiveState
08-30 23:15:21.211  3200  3200 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-30 23:15:21.201  1116  3075 D WifiController: processMsg: StaEnabledState
08-30 23:15:21.211  1116  1116 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-30 23:15:21.201  1116  3075 D WifiController: processMsg: DefaultState
08-30 23:15:21.211  1116  1116 I HtcPowerSaver: << updateStatus
08-30 23:15:21.201  1116  3075 D WifiController: handleMessage: X
,08-30 23:15:21.251  3200  3200 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-30 23:15:21.251  3200  3200 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-30 23:15:21.251  3200  3200 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-30 23:15:21.251  3200  3200 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-30 23:15:21.251  3200  3200 I FlashlightController: batteryLevelChange:100
,08-30 23:15:21.361  1116  3043 D WifiStateMachine: startScan Pid: 1116 Uid -1,
08-30 23:15:21.361  1116  3043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-30 23:15:21.361  1116  3043 D WifiDisplayAdapter:     Client/Owner: Client
08-30 23:15:21.361  1116  3043 D WifiDisplayAdapter:     GroupId: 
08-30 23:15:21.361  1116  3043 D WifiDisplayAdapter:     Passphrase: 
08-30 23:15:21.361  1116  3043 D WifiDisplayAdapter:     SessionId: 0
08-30 23:15:21.361  1116  3043 D WifiDisplayAdapter:     IP Address: }
08-30 23:15:21.361  3157  3157 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-30 23:15:21.361  3157  3157 D wpa_supplicant: CTRL_IFACE SET 'pno'='0'
,08-30 23:15:21.361  3157  3157 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-30 23:15:21.361  3157  3157 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-30 23:15:21.361  3157  3157 I wpa_supplicant: wpa_supplicant_scan enter
08-30 23:15:21.361  3157  3157 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-30 23:15:21.361  3157  3157 D wpa_supplicant: wlan0: Add radio work 'scan'@0x5582890710
08-30 23:15:21.361  3157  3157 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-30 23:15:21.361  3157  3157 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x5582890710 after 0.000021 second wait
08-30 23:15:21.361  3157  3157 D wpa_supplicant: wlan0: nl80211: scan request
,08-30 23:15:21.401  3157  3157 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
08-30 23:15:21.401  3157  3157 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
08-30 23:15:21.401  3157  3157 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-30 23:15:21.401  3157  3157 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
08-30 23:15:21.401  3157  3157 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000152 seconds
08-30 23:15:21.401  3157  3157 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 23:15:21.401  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
,08-30 23:15:23.641  1116  1162 I ActivityManager: Waited long enough for: ServiceRecord{147128db u0 com.google.android.gms/.wearable.service.WearableService}
,08-30 23:15:25.001  3157  3157 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-30 23:15:25.011  1116  3043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 23:15:25.001  3157  3157 D wpa_supplicant: nl80211: Scan probed for SSID ''
,08-30 23:15:25.001  3157  3157 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-30 23:15:25.001  3157  3157 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: Scan completed in 3.594207 seconds
08-30 23:15:25.001  3157  3157 D wpa_supplicant: nl80211: Received scan results (46 BSSes)
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-46
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-47
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-43
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-43
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-59
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-60
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-60
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-70
,08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-70
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-70
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-70
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-70
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-71
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d4 freq=2437 level=-73
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-73
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-73
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:34 freq=2412 level=-73
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-78
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-78
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d2 freq=2437 level=-74
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d0 freq=2437 level=-74
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:36 freq=2412 level=-74
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-74
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d6 freq=2437 level=-74
,08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-79
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-75
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:9a freq=5180 level=-87
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:99 freq=5180 level=-87
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:21:47:5f freq=5180 level=-88
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:96 freq=2462 level=-84
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:21:47:5b freq=5180 level=-89
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:00 freq=2462 level=-86
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:02 freq=2462 level=-88
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-68
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-70
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-73
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-73
,08-30 23:15:25.001  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-73
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-73
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-78
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-86
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:91 freq=2462 level=-86
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:01 freq=2462 level=-87
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:21:47:53 freq=2437 level=-87
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-87
08-30 23:15:25.001  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:a6:38 freq=2412 level=-89
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Start scan result update 7
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 81 BSSID 84:b2:61:21:47:5f SSID '\x00'
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 82 BSSID 84:b2:61:12:64:96 SSID '\x00'
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
,08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 83 BSSID 84:b2:61:21:47:5b SSID '\x00'
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 84 BSSID 00:fe:c8:73:02:01 SSID '\x00'
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 85 BSSID 84:b2:61:1c:a6:38 SSID '\x00'
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 68 BSSID e4:aa:5d:fc:5b:f6 SSID '\x00' due to no match in scan
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 63 BSSID 00:fe:c8:73:02:06 SSID '\x00' due to no match in scan
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 34 BSSID 84:b2:61:21:47:54 SSID '\x00' due to no match in scan
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 71 BSSID 24:a4:3c:de:76:f2 SSID 'skup' due to no match in scan
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 72 BSSID 00:fe:c8:73:00:40 SSID '\x00' due to no match in scan
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 73 BSSID 00:1f:27:54:70:91 SSID 'TEST_KTW01' due to no match in scan
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: BSS: last_scan_res_used=46/64
,08-30 23:15:25.021  1116  1116 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 14
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: Scan-only results received
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: Radio work 'scan'@0x5582890710 done in 3.639492 seconds
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 23:15:25.001  3157  3157 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 23:15:25.001  3157  3157 D wpa_supplicant: wlan0: Cancelling scan request
08-30 23:15:25.001  3157  3157 D wpa_supplicant: PNO: No configured SSIDs
08-30 23:15:25.001  1116  3043 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 23:15:25.011  3157  3157 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 23:15:25.011  3157  3157 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-30 23:15:25.021  3157  3157 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-30 23:15:25.021  1116  3043 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-30 23:15:25.021  4328  4328 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 23:15:25.021  4328  5848 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
,08-30 23:15:26.201  1116  3030 I ActivityManager: Start proc 8437:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService
08-30 23:15:26.201  1116  3030 D PMS     : acquireWL(218741ef): PARTIAL_WAKE_LOCK  *alarm* 0x1 1116 1000 WorkSource{10058}
08-30 23:15:26.201  1116  3030 V AlarmManager: sending alarm PendingIntent{2a8814fc: PendingIntentRecord{93de785 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1472591720644, Int=60000
,08-30 23:15:26.201  1116  3030 V AlarmManager: sending alarm PendingIntent{27b00e0b: PendingIntentRecord{31bf84e8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1472591724227, Int=0
08-30 23:15:26.201  1116  3030 V AlarmManager: sending alarm PendingIntent{3c7a7701: PendingIntentRecord{1e0a2138 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=101066, Int=0
,08-30 23:15:26.211  7627  7627 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 23:15:26.211  7627  7627 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 23:15:26.211  1116  1116 D PMS     : releaseWL(218741ef): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-30 23:15:26.211  7627  7627 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 23:15:26.211  7627  7627 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 23:15:26.211  7627  7627 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 23:15:26.221  8437  8437 W HTCLOG  : use specified tag [FDManager], func [0].,
08-30 23:15:26.221  8437  8437 W HTCLOG  : mask=0x18
,08-30 23:15:26.251  7627  8459 D HtcModeClient: start the htcmodeservice thread
,08-30 23:15:26.251  7627  8459 D HtcModeClient: initCanAgent
,08-30 23:15:26.261  7627  8459 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 23:15:26.261  7627  8459 D HtcModeClient: sense info: version = none, id = 2
08-30 23:15:26.261  7627  8459 D HtcModeClient: display info: width = 1080, height = 1776
08-30 23:15:26.261  7627  8459 D HtcModeClient: display info: mode = 10
,08-30 23:15:26.271  8437  8461 D SMSBackup: SMSBackupAgentService started
,08-30 23:15:26.271  8437  8461 D SMSBackup: Checking restore status
,08-30 23:15:26.271  8437  8461 D SMSBackup: Restore complete
,08-30 23:15:26.271  8437  8461 D SMSBackup: cancelCheckAlarm
,08-30 23:15:26.281  8437  8461 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
,08-30 23:15:26.361  7627  7627 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-30 23:15:26.361  7627  7627 D HtcModeClient: connectState: BT_TURNON_BYME = false,
08-30 23:15:26.361  7627  7627 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 23:15:26.361  7627  7627 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 23:15:26.361  7627  7627 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 23:15:26.361  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 23:15:26.361  7627  7627 D HtcModeClient: connectState: Force_AWAKE = false
,08-30 23:15:26.361  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 23:15:26.361  7627  7627 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 23:15:26.421  1116  3795 I art     : Explicit concurrent mark sweep GC freed 31758(1651KB) AllocSpace objects, 11(196KB) LOS objects, 33% free, 16MB/24MB, paused 1.844ms total 143.429ms
,08-30 23:15:26.511  8156  8156 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.,
,08-30 23:15:28.371  7627  8459 I HtcModeClient: handler message = 4011,
08-30 23:15:28.371  7627  8459 D HtcModeClient: getConnectionCheckCount first 0
,08-30 23:15:28.371  7627  8459 D HtcModeClient: getConnectionCheckCount count = 9,
,08-30 23:15:28.371  7627  8459 E HtcModeClient: Check connection and retry 10 times.
,08-30 23:15:28.381  7627  8459 D HtcModeClient: setConnectionCheckCount count = 10
,08-30 23:15:28.381  7627  8459 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 23:15:28.381  7627  7627 D HtcModeClient: setBtPriority priority = on
,08-30 23:15:28.381  7627  7627 D HtcModeClient: unbindBlueToothService
,08-30 23:15:28.381  7627  7627 D HtcModeClient: Don't start project servcice
08-30 23:15:28.391  7627  7627 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 23:15:28.391  7627  7627 D HtcModeClient: connectState: CONNECTION_READY = false
,08-30 23:15:28.391  7627  7627 D SilentMusic: call stop
08-30 23:15:28.391  7627  7627 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 23:15:28.391  7627  8460 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 23:15:28.391  7627  7627 D HtcModeClient: onDestroy,
,08-30 23:15:28.391  1116  3479 I ActivityManager: Killing 7535:com.htc.sdm/u0a61 (adj 15): empty #17
08-30 23:15:28.401  1116  3479 D Process : killProcessQuiet, pid=7535
,08-30 23:15:28.401  1116  3479 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-30 23:15:28.471  1116  3520 I ActivityManager: Recipient 7535,
,08-30 23:15:31.861  8333  8427 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 23:15:31.861  8333  8427 I jxcore-log: 
,08-30 23:15:31.871  8333  8427 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 23:15:31.871  8333  8427 I jxcore-log: 
,08-30 23:15:31.871  5473  5956 D BluetoothAdapterService(71843651): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28b934b4
08-30 23:15:31.871  8333  8427 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:15:31.871  8333  8427 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:15:31.871  8333  8427 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:15:31.871  8333  8427 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:15:31.871  8333  8427 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:15:31.871  8333  8427 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 23:15:31.871  8333  8427 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 23:15:31.871  8333  8427 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 23:15:31.881  5473  5956 D BluetoothAdapterService(71843651): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28b934b4
08-30 23:15:31.881  8333  8427 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 23:15:31.881  8333  8427 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 23:15:31.881  8333  8427 I jxcore-log: 
08-30 23:15:31.881  8333  8427 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 23:15:31.881  8333  8427 I jxcore-log: 
,08-30 23:15:32.361  8333  8427 I jxcore-log: Running unit tests
08-30 23:15:32.361  8333  8427 I jxcore-log: 
08-30 23:15:32.361  8333  8427 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 23:15:32.361  8333  8427 I jxcore-log: Failed to execute UT.
08-30 23:15:32.361  8333  8427 I jxcore-log: 
,08-30 23:15:32.371  8333  8427 I jxcore-log: Unit Test app is loaded
08-30 23:15:32.371  8333  8427 I jxcore-log: 
,08-30 23:15:32.381  8333  8427 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 23:15:32.381  8333  8427 I jxcore-log: 
08-30 23:15:32.381  8333  8427 I jxcore-log: My device name is: HTC-HTC One M9
08-30 23:15:32.381  8333  8427 I jxcore-log: 
08-30 23:15:32.391  8333  8427 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 23:15:32.391  8333  8427 I jxcore-log: 
,08-30 23:15:32.391  8333  8333 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 23:15:33.381  1116  3030 D PMS     : acquireWL(293284df): PARTIAL_WAKE_LOCK  *alarm* 0x1 1116 1000 WorkSource{10027}
08-30 23:15:33.381  1116  3030 V AlarmManager: sending alarm PendingIntent{1278b52c: PendingIntentRecord{1e0a2138 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=108275, Int=0
,08-30 23:15:33.401  7627  7627 D AlarmReceiver: ACTION_RESTART_INTENT
08-30 23:15:33.401  1116  1116 D PMS     : releaseWL(293284df): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-30 23:15:33.401  7627  7627 D LocalBluetoothProfile: getPriorityOnValue = 100
,08-30 23:15:33.401  7627  7627 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 23:15:33.401  7627  7627 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 23:15:33.401  7627  7627 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 23:15:33.431  7627  8465 D HtcModeClient: start the htcmodeservice thread
,08-30 23:15:33.431  7627  8465 D HtcModeClient: initCanAgent
,08-30 23:15:33.431  7627  8465 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 23:15:33.431  7627  8465 D HtcModeClient: sense info: version = none, id = 2
,08-30 23:15:33.431  7627  8465 D HtcModeClient: display info: width = 1080, height = 1776
08-30 23:15:33.431  7627  8465 D HtcModeClient: display info: mode = 10
,08-30 23:15:33.531  7627  7627 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-30 23:15:33.531  7627  7627 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 23:15:33.531  7627  7627 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 23:15:33.531  7627  7627 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 23:15:33.531  7627  7627 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 23:15:33.531  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 23:15:33.531  7627  7627 D HtcModeClient: connectState: Force_AWAKE = false
08-30 23:15:33.531  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 23:15:33.531  7627  7627 D HtcModeClient: connectState: POWERCONNECTED_READY = true,
,08-30 23:15:35.541  7627  8465 I HtcModeClient: handler message = 4011
,08-30 23:15:35.541  7627  8465 D HtcModeClient: getConnectionCheckCount first 0
,08-30 23:15:35.551  7627  8465 D HtcModeClient: getConnectionCheckCount count = 10,
,08-30 23:15:35.551  7627  8465 E HtcModeClient: Check connection and retry 11 times.,
,08-30 23:15:35.551  7627  8465 D HtcModeClient: setConnectionCheckCount count = 11
,08-30 23:15:35.551  7627  8465 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 23:15:35.561  7627  7627 D HtcModeClient: setBtPriority priority = on,
08-30 23:15:35.561  7627  7627 D HtcModeClient: unbindBlueToothService
08-30 23:15:35.561  7627  7627 D HtcModeClient: Don't start project servcice
08-30 23:15:35.561  7627  7627 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 23:15:35.561  7627  7627 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 23:15:35.561  7627  7627 D SilentMusic: call stop
08-30 23:15:35.561  7627  7627 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 23:15:35.561  7627  8466 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 23:15:35.571  7627  7627 D HtcModeClient: onDestroy
,08-30 23:15:35.711  8333  8427 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
08-30 23:15:35.711  8333  8427 I jxcore-log: 
,08-30 23:15:36.291  8333  8427 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-30 23:15:36.291  8333  8427 I jxcore-log: 
,08-30 23:15:36.321  8333  8427 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js,
08-30 23:15:36.321  8333  8427 I jxcore-log: 
,08-30 23:15:36.371  1116  3043 D WifiStateMachine: startScan Pid: 1116 Uid -1
08-30 23:15:36.371  1116  3043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-30 23:15:36.371  1116  3043 D WifiDisplayAdapter:     Client/Owner: Client
08-30 23:15:36.371  1116  3043 D WifiDisplayAdapter:     GroupId: 
08-30 23:15:36.371  1116  3043 D WifiDisplayAdapter:     Passphrase: 
08-30 23:15:36.371  1116  3043 D WifiDisplayAdapter:     SessionId: 0
08-30 23:15:36.371  1116  3043 D WifiDisplayAdapter:     IP Address: }
08-30 23:15:36.371  3157  3157 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-30 23:15:36.371  3157  3157 D wpa_supplicant: CTRL_IFACE SET 'pno'='0'
08-30 23:15:36.371  3157  3157 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-30 23:15:36.371  3157  3157 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-30 23:15:36.371  3157  3157 I wpa_supplicant: wpa_supplicant_scan enter
08-30 23:15:36.371  3157  3157 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-30 23:15:36.371  3157  3157 D wpa_supplicant: wlan0: Add radio work 'scan'@0x5582890710
08-30 23:15:36.371  3157  3157 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-30 23:15:36.371  3157  3157 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x5582890710 after 0.000026 second wait
08-30 23:15:36.371  3157  3157 D wpa_supplicant: wlan0: nl80211: scan request
,08-30 23:15:36.411  3157  3157 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-30 23:15:36.411  3157  3157 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
08-30 23:15:36.411  3157  3157 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-30 23:15:36.411  3157  3157 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
08-30 23:15:36.411  3157  3157 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000147 seconds
,08-30 23:15:36.411  3157  3157 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 23:15:36.411  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
,08-30 23:15:38.381  8333  8427 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js,
08-30 23:15:38.381  8333  8427 I jxcore-log: 
,08-30 23:15:38.691  8333  8427 I jxcore-log: ERROR runTests: ,
08-30 23:15:38.691  8333  8427 I jxcore-log: 
,08-30 23:15:38.701  8333  8427 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger',
08-30 23:15:38.701  8333  8427 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 23:15:38.701  8333  8427 I jxcore-log: WARN testUtils: logCallback not set!
08-30 23:15:38.701  8333  8427 I jxcore-log: 
,08-30 23:15:38.711  8333  8427 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',,
,08-30 23:15:38.711  8333  8427 I jxcore-log:     _functionName: 'loadFile',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _lineNumber: '26',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _columnNumber: '11',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },,
08-30 23:15:38.711  8333  8427 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _functionName: '',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _lineNumber: '38',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _columnNumber: '7',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 23:15:38.711  8333  8427 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _functionName: '',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _lineNumber: '35',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _columnNumber: '3',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 23:15:38.711  8333  8427 I jxcore-log:   { _fileName: 'module.js',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _functionName: '$w.prototype._compile',,
08-30 23:15:38.711  8333  8427 I jxcore-log:     _lineNumber: '621',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _columnNumber: '8',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 23:15:38.711  8333  8427 I jxcore-log:   { _fileName: 'module.js',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _lineNumber: '651',
08-30 23:15:38.711  8333  8427 I jxcore-log:     _columnNumber: '1',
08-30 23:15:38.711  8333  8427 I jxcore-log:    
08-30 23:15:38.721  8333  8427 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 23:15:38.721  8333  8427 I jxcore-log: 
08-30 23:15:38.721  8333  8427 E jxcore-log: Error: 
08-30 23:15:38.721  8333  8427 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 23:15:38.721  8333  8427 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 23:15:38.721  8333  8427 E jxcore-log: 
,08-30 23:15:38.921  8467  8467 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
08-30 23:15:38.921  8467  8467 W HTCLOG  : mask=0x18
,08-30 23:15:39.091  8467  8470 W HTCLOG  : use specified tag [cutils-trace], func [0].,
08-30 23:15:39.091  8467  8470 W HTCLOG  : mask=0x18
08-30 23:15:39.091  8467  8470 E cutils-trace: Error opening trace file: Permission denied (13)
,08-30 23:15:39.161  8467  8467 D CustomizationManager: ====startRecUseTime====,
08-30 23:15:39.161  8467  8467 D htc.customization.log.level:  is 
08-30 23:15:39.161  8467  8467 W CustomizationLogLevel: Level value is invalid, use default level 2
,08-30 23:15:39.251  8467  8467 D CustomizationManager:  Read ACC file spent 0.043 (s),
,08-30 23:15:39.251  8467  8467 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
08-30 23:15:39.251  8467  8467 I CustomizationCIDLoader: Parsing tag category name = application
08-30 23:15:39.251  8467  8467 I CustomizationCIDLoader: Parsing tag category name = system
,08-30 23:15:39.251  8467  8467 I CustomizationCIDLoader: Parsing tag category name = Settings
08-30 23:15:39.251  8467  8467 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-30 23:15:39.251  8467  8467 I CustomizationCIDLoader: Parsing tag category name = ACC
,08-30 23:15:39.261  8467  8467 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240,
08-30 23:15:39.261  8467  8467 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-30 23:15:39.261  8467  8467 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-30 23:15:39.261  8467  8467 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-30 23:15:39.261  8467  8467 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-30 23:15:39.261  8467  8467 D CustomizationManager:  Read CID file spent 0.102 (s),
08-30 23:15:39.261  8467  8467 D CustomizationManager:  All configurations done spent 0.103 (s)
,08-30 23:15:39.311  1116  3756 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8467, uid=2000,
08-30 23:15:39.311  1116  1162 D Process : killProcessQuiet, pid=8333
08-30 23:15:39.311  1116  1162 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
,08-30 23:15:39.311  1116  1162 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
08-30 23:15:39.311  1116  1162 I ActivityManager: Killing 8333:com.test.thalitest/u0a142 (adj 0): stop com.test.thalitest
,08-30 23:15:39.411   527   527 W HTCLOG  : use specified tag [Vector], func [0].
,08-30 23:15:39.411   527   527 W HTCLOG  : mask=0x18
,08-30 23:15:39.421  1116  3034 W InputDispatcher: channel 'dccebb3 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9,
08-30 23:15:39.421  1116  3034 I WindowManager: WINDOW DIED Window{dccebb3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 23:15:39.421  1116  3034 E InputDispatcher: channel 'dccebb3 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
08-30 23:15:39.421  1116  3463 I ActivityManager: Recipient 8333
08-30 23:15:39.421  1116  3034 W InputDispatcher: Attempted to unregister already unregistered input channel 'dccebb3 com.test.thalitest.MainActivity (s)'
08-30 23:15:39.421  1116  3075 D WifiService: Client connection lost with reason: 4
08-30 23:15:39.421  1116  3276 W WindowManager: Failed looking up window
,08-30 23:15:39.421  1116  3276 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@908f522 does not exist
08-30 23:15:39.421  1116  3276 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8901)
08-30 23:15:39.421  1116  3276 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8892)
08-30 23:15:39.421  1116  3276 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1139),
08-30 23:15:39.421  1116  3276 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:559)
08-30 23:15:39.421  1116  3276 I WindowState: WIN DEATH: null
,08-30 23:15:39.531  1116  1162 I ActivityManager:   Force finishing activity 3 ActivityRecord{1f9adb6a u0 com.test.thalitest/.MainActivity t451}
08-30 23:15:39.561  1116  3463 W ActivityManager: Spurious death for ProcessRecord{331174ad 8333:com.test.thalitest/u0a142}, curProc for 8333: null
,08-30 23:15:39.571  1116  1183 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed,
,08-30 23:15:39.691  3328  3328 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,08-30 23:15:39.691  3328  3328 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
08-30 23:15:39.691  1116  3035 W SystemReader: Cannot find grip_rejection_width, use default value instead
08-30 23:15:39.701  1116  3276 D PMS     : acquireWL(35af0373): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4328 10019 null
08-30 23:15:39.701  1116  3143 D TaskPersister: removeObsoleteFile: deleting file=451_task.xml
08-30 23:15:39.701  4328  4653 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 23:15:39.701  3765  4138 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
08-30 23:15:39.711  1116  3797 D PMS     : releaseWL(35af0373): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,08-30 23:15:39.721  3542  3542 I art     : Explicit concurrent mark sweep GC freed 5022(250KB) AllocSpace objects, 18(2MB) LOS objects, 40% free, 20MB/33MB, paused 1.169ms total 44.742ms,
,08-30 23:15:39.731  3521  3521 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
08-30 23:15:39.731  3765  4138 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
08-30 23:15:39.731  3765  4138 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,08-30 23:15:39.741  4036  4036 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-30 23:15:39.741  3765  4138 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,08-30 23:15:39.741  1116  3756 D PMS     : acquireWL(11710c2e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4036 10019 null
,08-30 23:15:39.751  3747  8484 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 23:15:39.761  1116  3041 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
08-30 23:15:39.761  1116  3041 V NetworkPolicy: writePolicyLocked()
08-30 23:15:39.761  3563  3563 I ConfigService: onCreate
08-30 23:15:39.761  1116  3040 D PMS     : acquireWL(2105bd3a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1116 1000 null,
,08-30 23:15:39.761  3563  3563 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-30 23:15:39.771  4036  4036 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-30 23:15:39.781  3765  4138 E ExternalAccountType: Unsupported attribute readOnly
08-30 23:15:39.781  1116  3040 D PMS     : releaseWL(2105bd3a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
08-30 23:15:39.781  6541  6541 I art     : Explicit concurrent mark sweep GC freed 12319(760KB) AllocSpace objects, 2(48KB) LOS objects, 34% free, 3MB/5MB, paused 440us total 98.821ms
,08-30 23:15:39.781  1116  3041 D NetworkPolicy: notifyPoliciesChangeLocked: no change
08-30 23:15:39.781  1116  3041 V NetworkPolicy: updateNetworkEnabledLocked()
,08-30 23:15:39.781  1116  3041 V NetworkPolicy: updateNotificationsLocked()
,08-30 23:15:39.801  3563  3563 I ConfigService: onBind returning update interface,
,08-30 23:15:39.811  3563  3563 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 23:15:39.811  3563  3563 I ConfigService: onBind returning config service
08-30 23:15:39.811  3563  3563 I ConfigService: onDestroy
,08-30 23:15:39.821  1116  1136 D PMS     : acquireWL(3fdadff4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3563 10019 null
,08-30 23:15:39.831  1116  3581 I ActivityManager: Start proc 8486:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver,
,08-30 23:15:39.831  8486  8486 W HTCLOG  : use specified tag [FDManager], func [0].,
08-30 23:15:39.831  1116  3520 D PMS     : releaseWL(3fdadff4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
08-30 23:15:39.831  8486  8486 W HTCLOG  : mask=0x18,
,08-30 23:15:39.841  1116  1116 I art     : Explicit concurrent mark sweep GC freed 21204(1556KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 16MB/24MB, paused 1.939ms total 171.443ms
08-30 23:15:39.841  1116  3030 D PMS     : acquireWL(c00760): PARTIAL_WAKE_LOCK  *alarm* 0x1 1116 1000 WorkSource{10027}
08-30 23:15:39.841  1116  3030 V AlarmManager: sending alarm PendingIntent{28429419: PendingIntentRecord{1e0a2138 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=115451, Int=0
08-30 23:15:39.841  1116  1183 I art     : WaitForGcToComplete blocked for 91.010ms for cause Explicit
08-30 23:15:39.841  1116  3030 V AlarmManager: sending alarm PendingIntent{2d992f71: PendingIntentRecord{3913d156 android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=116731, Int=0
08-30 23:15:39.851  1116  1161 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,08-30 23:15:39.871  1116  1161 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-30 23:15:39.881  8486  8486 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 23:15:39.881  8486  8486 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 23:15:39.891  3470  3470 D Nfc-Utils: isNxpCodebase: isNxp=false,
,08-30 23:15:39.901  3542  3542 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,08-30 23:15:39.901  3542  3542 I ThreadedRenderer: Defer allocateBuffers to drawing time
08-30 23:15:39.901  8486  8486 I MultiDex: VM with version 2.1.0 has multidex support
08-30 23:15:39.901  8486  8486 I MultiDex: install
08-30 23:15:39.901  8486  8486 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 23:15:39.911  8486  8486 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 23:15:39.921  8486  8486 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest,
,08-30 23:15:39.941  1116  2261 D Process : killProcessQuiet, pid=7713
,08-30 23:15:39.941  1116  2261 I ActivityManager: Killing 7713:com.google.android.gm/u0a97 (adj 15): empty #17
08-30 23:15:39.941  1116  2261 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-30 23:15:39.961  1116  1116 W PackageManager: Unable to load service info ResolveInfo{2da6f2a2 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
08-30 23:15:39.961  1116  1116 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
08-30 23:15:39.961  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:39.961  1116  1116 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 23:15:40.001  1116  1183 I art     : Explicit concurrent mark sweep GC freed 5524(289KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.193ms total 156.261ms,
,08-30 23:15:40.021  3157  3157 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 23:15:40.021  3157  3157 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 23:15:40.021  3157  3157 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
,08-30 23:15:40.021  3157  3157 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: Scan completed in 3.609005 seconds
08-30 23:15:40.021  3157  3157 D wpa_supplicant: nl80211: Received scan results (48 BSSes)
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-46
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-47,
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-44
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-53
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-59
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-60
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-60
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-70
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-71
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-71
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-71
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-71
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-72
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-72
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d2 freq=2437 level=-73
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d5 freq=2437 level=-73
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d0 freq=2437 level=-73
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-78
08-30 23:15:40.031  1116  3043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-78
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-78
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-74
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-74
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d6 freq=2437 level=-74
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-75
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:34 freq=2412 level=-75
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:04 freq=2462 level=-83
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:99 freq=5180 level=-88
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:21:47:5f freq=5180 level=-88
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:90 freq=2462 level=-84
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:92 freq=2462 level=-85
,08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:06 freq=2462 level=-85
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:12:64:94 freq=2462 level=-85
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:00 freq=2462 level=-86
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:05 freq=2462 level=-86
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:02 freq=2462 level=-87
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:21:47:50 freq=2437 level=-87
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:7e freq=5200 level=-60
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-71
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-72
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-73
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-73
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-78
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-75
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-75
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-85
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [RA-WINGS] 84:b2:61:21:47:53 freq=2437 level=-86
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [] 00:fe:c8:73:02:01 freq=2462 level=-87
08-30 23:15:40.021  3157  3157 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-87
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: BSS: Start scan result update 8
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 86 BSSID 84:b2:61:12:64:92 SSID '\x00'
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 87 BSSID 00:fe:c8:73:02:06 SSID '\x00'
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 88 BSSID 84:b2:61:12:64:94 SSID '\x00'
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: BSS: Add new id 89 BSSID 00:fe:c8:73:02:05 SSID '\x00'
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 75 BSSID 84:b2:61:12:64:95 SSID '\x00' due to no match in scan
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 76 BSSID e4:aa:5d:fc:5b:f5 SSID '\x00' due to no match in scan
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 78 BSSID 84:b2:61:21:47:56 SSID '\x00' due to no match in scan
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: BSS: Remove ID 57 BSSID e4:aa:5d:fc:5b:f4 SSID '\x00' due to no match in scan
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: BSS: last_scan_res_used=48/64
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: Scan-only results received
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/mi,sc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1116-2\x00
08-30 23:15:40.021  3157  3157 D wpa_supplicant: wlan0: Radio work 'scan'@0x5582890710 done in 3.654164 seconds
08-30 23:15:40.031  3157  3157 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 23:15:40.031  3157  3157 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 23:15:40.031  3157  3157 D wpa_supplicant: wlan0: Cancelling scan request
08-30 23:15:40.031  3157  3157 D wpa_supplicant: PNO: No configured SSIDs
08-30 23:15:40.031  1116  3043 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 23:15:40.031  3157  3157 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 23:15:40.051  1116  3479 I ActivityManager: Recipient 7713
,08-30 23:15:40.071  8467  8467 I art     : System.exit called, status: 0
08-30 23:15:40.071  8467  8467 W HTCLOG  : use specified tag [Vector], func [0].
,08-30 23:15:40.071  8467  8467 W HTCLOG  : mask=0x18
,08-30 23:15:40.121  1116  1116 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
,08-30 23:15:40.151  3157  3157 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-30 23:15:40.151  4036  8512 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 23:15:40.151  4036  8512 D AccountUtils: Clearing selected account for com.test.thalitest
,08-30 23:15:40.161  3157  3157 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
,08-30 23:15:40.161  1116  3043 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-30 23:15:40.161  3542  3972 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
08-30 23:15:40.161  3542  3972 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
08-30 23:15:40.171  3542  3542 I Launcher: Deferring update until onResume
08-30 23:15:40.171  3542  3542 D Launcher: waitUntilResume // bindAppsRemoved
,08-30 23:15:40.181  1116  3518 I ActivityManager: Start proc 8515:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver,
,08-30 23:15:40.181  1116  1116 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 14
08-30 23:15:40.191  4328  4328 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 23:15:40.191  4328  5848 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
,08-30 23:15:40.201  8515  8515 W HTCLOG  : use specified tag [FDManager], func [0].
,08-30 23:15:40.201  8515  8515 W HTCLOG  : mask=0x18
,08-30 23:15:40.251  1116  3479 D Process : killProcessQuiet, pid=7401,
,08-30 23:15:40.251  1116  3479 I ActivityManager: Killing 7401:com.google.android.music:main/u0a115 (adj 15): empty #17
08-30 23:15:40.251  1116  3479 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-30 23:15:40.251  7890  8540 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 23:15:40.311  1116  3463 I ActivityManager: Recipient 7401,
08-30 23:15:40.311  1116  3276 D MediaRouterService: Client com.google.android.music (pid 7401): Died!
,08-30 23:15:40.361  3765  3765 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
,08-30 23:15:40.371  4036  8542 I PeopleContactsSync: CP2 sync disabled
08-30 23:15:40.371  1116  3520 D PMS     : acquireWL(22097886): PARTIAL_WAKE_LOCK  Icing 0x1 4036 10019 null
,08-30 23:15:40.371  1116  1135 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4036, uid=10019, userID:0
,08-30 23:15:40.371  3642  8543 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,08-30 23:15:40.371  4036  6758 I Icing   : doRemovePackageData com.test.thalitest
,08-30 23:15:40.381  3642  8543 E SQLiteLog: (3850) statement aborts at 41: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
,08-30 23:15:40.381  3642  8543 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 23:15:40.381  3642  8543 W HTCLOG  : mask=0x18,
08-30 23:15:40.381  3642  8543 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.sense.hsp/databases/registry.db, handle: 0x55a47e0be0
08-30 23:15:40.381  4036  6758 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 for write failed: Read-only file system
08-30 23:15:40.381  4036  6758 E Icing   : Could not init tag ds.tag.corpusid-0
08-30 23:15:40.381  4036  6758 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
08-30 23:15:40.381  4036  6758 E Icing   : Could not init tag ds.tag.deleted
08-30 23:15:40.381  4036  6758 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
08-30 23:15:40.381  4036  6758 E Icing   : Writing status failed
,08-30 23:15:40.381  1116  1136 D PMS     : releaseWL(22097886): PARTIAL_WAKE_LOCK  Icing 0x1 null
,08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: provider may killed!
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: ,	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	,at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.381  3642  8543 W [PluginM,anager]RegisterService: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.381  3642  8543 W [PluginManager]RegisterService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.381  3642  8543 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,08-30 23:15:40.391  3542  3542 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED,
08-30 23:15:40.391  3542  3542 I ContextualWidget: package com.test.thalitest removed
,08-30 23:15:40.391  3542  3991 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
,08-30 23:15:40.391  4036  8544 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:591)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:585)
08-30 23:15:40.391  4036  8544 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.run(SourceFile:608)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: FATAL EXCEPTION: Open database in background
08-30 23:15:40.401  4036  8544 E AndroidRuntime: Process: com.google.android.gms, PID: 4036
08-30 23:15:40.401  4036  8544 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatab,aseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.b(SourceFile:591)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:585)
08-30 23:15:40.401  4036  8544 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.run(SourceFile:608)
08-30 23:15:40.401  1116  2261 E ActivityManager: App crashed! Process: com.google.android.gms
08-30 23:15:40.401  4036  8544 D Process : killProcess, pid=4036
08-30 23:15:40.401  4036  8544 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
08-30 23:15:40.401  4036  8544 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:40.401  4036  8544 W HTCLOG  : mask=0x18
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: Can't write: system_app_crash
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.401  1116  8546 E DropBoxManagerService: 	... 5 more
08-30 23:15:40.411  3542  8545 I ContextualWidget: com.test.thalitest is not installed
08-30 23:15:40.411  3542  8545 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
08-30 23:15:40.411  3542  8545 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
08-30 23:15:40.411  3542  8545 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 23:15:40.411  3542  8545 W HTCLOG  : mask=0x18
08-30 23:15:40.411  3542  8545 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xabd87a58
08-30 23:15:40.411  3542  8545 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
08-30 23:15:40.411  3542  8545 E AndroidRuntime: Process: com.htc.launcher, PID: 3542
08-30 23:15:40.411  3542  8545 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.removeItemsFromDownloadListIfNeed(MFUDataManager.java:2133)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageRemoved(HtcContextualWidgetService.java:277)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:184)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.411  3542  8545 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.421  1116  3585 I ActivityManager: Start proc 8547:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
08-30 23:15:40.421  1116  1136 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 23:15:40.431  1116  1136 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 23:15:40.431  1116  1136 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.431  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.431  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.431  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.431  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:40.431  1116  1136 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.431  1116  1136 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:40.431  1116  1136 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.431  1116  1136 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.431  1116  1136 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.431  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.431  1116  1136 W System.err: 	... 14 more
08-30 23:15:40.431  1116  1136 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.431  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.431  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.431  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.431  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:40.431  1116  1136 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.431  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.431  1116  1136 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:40.441  1116  1136 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 23:15:40.431  1116  1136 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.431  1116  1136 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.431  1116  1136 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.431  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.431  1116  1136 W System.err: 	... 14 more
08-30 23:15:40.441  8547  8547 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:40.441  8547  8547 W HTCLOG  : mask=0x18
08-30 23:15:40.441  1116  8561 E ErrorReport: HtcErrorReportManager.Error in dumping error information
,08-30 23:15:40.441  1116  8561 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472591740452.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:40.441  1116  8561 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.441  1116  8561 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.441  1116  8561 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:40.441  1116  8561 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:40.441  1116  8561 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:40.441  1116  8561 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.441  1116  8561 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.441  1116  8561 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.441  1116  8561 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.441  1116  8561 E ErrorReport: 	... 4 more
08-30 23:15:40.441  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.441  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.441  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.441  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.441  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.441  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:40.441  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 23:15:40.441  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:40.441  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 23:15:40.441  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:40.441  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:40.441  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.441  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.441  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.441  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.441  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.441  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.441  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.441  1116  3606 W System.err: 	... 12 more
08-30 23:15:40.441  3542  8545 D Process : killProcess, pid=3542
08-30 23:15:40.441  3542  8545 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:40.441  3542  8545 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:40.441  3542  8545 W HTCLOG  : mask=0x18
,08-30 23:15:40.511  1116  3797 I ActivityManager: Recipient 4036
08-30 23:15:40.511  1116  2261 D PMS     : handleWLDeath(11710c2e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
,08-30 23:15:40.511  1116  3276 D PMS     : handleWLDeath(a40ab7a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-30 23:15:40.511  1116  3463 I ActivityManager: Recipient 3542
08-30 23:15:40.511  1116  3520 I WindowState: WIN DEATH: Window{2038d1e1 u0 com.htc.launcher/com.htc.launcher.Launcher}
,08-30 23:15:40.511  1116  3797 I ActivityManager: Process com.google.android.gms (pid 4036) has died
08-30 23:15:40.521  1116  3797 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
08-30 23:15:40.521  1116  3797 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
08-30 23:15:40.521  1116  3797 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
,08-30 23:15:40.521  1116  3797 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
,08-30 23:15:40.531   494   494 E lowmemorykiller: Error opening /proc/3542/oom_score_adj; errno=2
08-30 23:15:40.531  1116  3797 V WindowManager: addAppToken: AppWindowToken{32f49712 token=Token{5a6c69d ActivityRecord{d0b2174 u0 com.htc.launcher/.Launcher t452}}} to stack=0 task=452 at 0
,08-30 23:15:40.531  1116  3797 W ActivityManager: Exception when starting activity com.htc.launcher/.Launcher,
08-30 23:15:40.531  1116  3797 W ActivityManager: android.os.DeadObjectException
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:504)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:855)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1227)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1327)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1994)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1536)
,08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2575)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStack.startActivityLocked(ActivityStack.java:2262)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLockedImpl(ActivityStackSupervisor.java:2309)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLocked(ActivityStackSupervisor.java:1668)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startActivityLocked(ActivityStackSupervisor.java:1577)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startHomeActivity(ActivityStackSupervisor.java:844)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityManagerService.startHomeActivityLocked(ActivityManagerService.java:3352)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeHomeStackTask(ActivityStackSupervisor.java:467)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1583)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1536)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2575)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2564)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4800)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4967)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1268)
08-30 23:15:40.531  1116  3797 W ActivityManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:559)
08-30 23:15:40.531  1116  3797 W ActivityManager: Scheduling restart of crashed service com.htc.launcher/.htcwidget.HtcContextualWidgetService in 10987ms
,08-30 23:15:40.541  1116  3797 I ActivityManager: Start proc 8572:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-30 23:15:40.541  1116  3463 W ActivityManager: Spurious death for ProcessRecord{1e1ad83d 8572:com.htc.launcher/u0a56}, curProc for 3542: null
,08-30 23:15:40.551  8572  8572 W HTCLOG  : use specified tag [FDManager], func [0].
,08-30 23:15:40.551  8572  8572 W HTCLOG  : mask=0x18
,08-30 23:15:40.551  1116  1135 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
,08-30 23:15:40.551  8547  8547 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
,08-30 23:15:40.551  8547  8547 D IdefixUninstallListener: package_removed = com.test.thalitest
,08-30 23:15:40.591  8547  8547 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:40.591  8547  8547 W HTCLOG  : mask=0x18
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.591  8547  8547 E SQLiteDatabase,: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.591  8547  8547 W System.err: java.sql.SQLException: Getting a writable database from helper a@1ff67fa failed
08-30 23:15:40.591  8547  8547 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
08-30 23:15:40.591  8547  8547 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
08-30 23:15:40.591  8547  8547 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-30 23:15:40.591  8547  8547 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-30 23:15:40.591  8547  8547 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-30 23:15:40.591  8547  8547 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-30 23:15:40.591  8547  8547 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 23:15:40.591  1116  3581 I ActivityManager: Killing 7942:com.htc.mobiledata:remote/u0a40 (adj 15): empty #17
08-30 23:15:40.591  8547  8547 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.591  8547  8547 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.591  8547  8547 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.591  8547  8547 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.591  8547  8547 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.591  8547  8547 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.591  8547  8547 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.591  8547  8547 W ,System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.591  8547  8547 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-30 23:15:40.591  8547  8547 W System.err: 	... 15 more
08-30 23:15:40.591  1116  3581 D Process : killProcessQuiet, pid=7942
08-30 23:15:40.591  1116  3581 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-30 23:15:40.601  8572  8572 I MultiDex: VM with version 2.1.0 has multidex support
08-30 23:15:40.601  8572  8572 I MultiDex: install
08-30 23:15:40.601  8572  8572 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 23:15:40.611  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 23:15:40.611  8572  8572 D FaceDetectTask: checkIsOmronEnable start
08-30 23:15:40.611  8572  8572 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
08-30 23:15:40.611  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.611  8572  8572 D FaceDetectTask: IsOmronEnable : true
08-30 23:15:40.611  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.611  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 23:15:40.611  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.611  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.611  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.611  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.621  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.621  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.621  8572  8572 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.621  8572  8572 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-30 23:15:40.621  8572  8572 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:40.621  8572  8572 W HTCLOG  : mask=0x18
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java,:1030)
08-30 23:15:40.621  8572  8572 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.621  8572  8572 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.621  8572  8572 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 23:15:40.621  8572  8572 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.621  8572  8572 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.621  8572  8572 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.621  8572  8572 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.621  8572  8572 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.621  8572  8572 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.631  8572  8572 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: FATAL EXCEPTION: main
08-30 23:15:40.631  8572  8572 E AndroidRuntime: Process: com.htc.launcher, PID: 8572
08-30 23:15:40.631  8572  8572 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:40.631  8572  8572 E AndroidRuntime: 	... 11 more
,08-30 23:15:40.691  1116  3797 I ActivityManager: Recipient 7942
08-30 23:15:40.701  1116  3520 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 23:15:40.701  1116  3520 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 23:15:40.701  1116  3520 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.701  1116  3520 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.701  1116  3520 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.701  1116  3520 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.701  1116  3520 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.701  1116  3520 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.701  1116  3520 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:40.701  1116  3520 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 23:15:40.701  1116  3520 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:40.701  1116  3520 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:40.701  1116  3520 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.701  1116  3520 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.701  1116  3520 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:40.701  1116  3520 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.701  1116  3520 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.701  1116  3520 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:40.701  1116  3520 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.701  1116  3520 W System.err: 	at libcore.io.Posix.open(Native Method),
08-30 23:15:40.701  1116  3520 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.701  1116  3520 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
,08-30 23:15:40.701  1116  3520 W System.err: 	... 14 more
08-30 23:15:40.711  1116  3520 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.711  1116  3520 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 23:15:40.711  1116  3520 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.711  1116  3520 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.711  1116  3520 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.711  1116  3520 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.711  1116  3520 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.711  1116  3520 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:40.711  1116  3520 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:40.711  1116  3520 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 23:15:40.711  1116  3520 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:40.711  1116  3520 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.711  1116  3520 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.711  1116  3520 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:40.711  1116  3520 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.711  1116  3520 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.711  1116  3520 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:40.711  1116  3520 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.711  1116  3520 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.711  1116  3520 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.711  1116  3520 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.711  1116  3520 W System.err: 	... 14 more
08-30 23:15:40.711  1116  8602 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 23:15:40.711  1116  8602 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472591740725.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:40.711  1116  8602 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.711  1116  8602 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.711  1116  8602 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:40.711  1116  8602 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:40.711  1116  8602 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:40.711  1116  8602 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.711  1116  8602 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.711  1116  8602 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.711  1116  8602 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.711  1116  8602 E ErrorReport: 	... 4 more
08-30 23:15:40.711  8572  85,72 D Process : killProcess, pid=8572
08-30 23:15:40.711  8572  8572 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:40.711  8572  8572 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:40.711  8572  8572 W HTCLOG  : mask=0x18
08-30 23:15:40.711  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.711  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.711  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.711  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.711  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.711  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:40.711  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 23:15:40.711  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:40.711  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294),
08-30 23:15:40.711  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:40.711  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:40.711  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.711  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.711  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 23:15:40.711  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.711  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.711  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.711  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.711  1116  3606 W System.err: 	... 12 more
,08-30 23:15:40.721  6541  8603 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 23:15:40.751  1116  1136 I ActivityManager: Start proc 8604:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-30 23:15:40.761  8604  8604 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:40.761  8604  8604 W HTCLOG  : mask=0x18
,08-30 23:15:40.761  6541  8603 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 23:15:40.761  6541  8603 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 23:15:40.761  6541  8603 W HTCLOG  : mask=0x18
08-30 23:15:40.761  6541  8603 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55a4719150
,08-30 23:15:40.771  6541  8603 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
,08-30 23:15:40.771  6541  8603 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService],
08-30 23:15:40.771  6541  8603 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6541
08-30 23:15:40.771  6541  8603 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	,at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.771  6541  8603 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.771  1116  3581 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: Can't write: system_app_crash
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.771  1116  8627 E DropBoxManagerService: 	... 5 more
08-30 23:15:40.771  6541  8603 D Process : killProcess, pid=6541
08-30 23:15:40.771  6541  8603 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
08-30 23:15:40.771  6541  8603 W HTCLOG  : use specified tag [Process], func [0].,
08-30 23:15:40.771  6541  8603 W HTCLOG  : mask=0x18
,08-30 23:15:40.791  8604  8604 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 ,
,08-30 23:15:40.801  1116  2261 D PMS     : acquireWL(1601125e): PARTIAL_WAKE_LOCK  AsyncService 0x1 8377 10128 null
,08-30 23:15:40.811  8604  8628 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:40.811  8604  8628 W HTCLOG  : mask=0x18
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
,08-30 23:15:40.811  8604  8628 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-30 23:15:40.811  8604  8628 E AndroidRuntime: Process: com.android.keychain, PID: 8604
08-30 23:15:40.811  8604  8628 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.811  8604  8628 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.811  1116  3276 I ActivityManager: Recipient 8572
08-30 23:15:40.811  1116  3276 I ActivityManager: Process com.htc.launcher (pid 8572) has died
08-30 23:15:40.811  1116  3276 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 23:15:40.811  1116  3520 D PMS     : releaseWL(1601125e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-30 23:15:40.811  1116  3276 V WindowManager: addAppToken: AppWindowToken{37292c55 token=Token{1ad52b0c ActivityRecord{4c1a63f u0 com.htc.launcher/.Launcher t453}}} to stack=0 task=453 at 0
,08-30 23:15:40.821  1116  3276 I ActivityManager: Start proc 8630:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-30 23:15:40.831  1116  3797 E ActivityManager: App crashed! Process: com.android.keychain
08-30 23:15:40.831  1116  3797 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 23:15:40.831  1116  3606 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-30 23:15:40.831  1116  3797 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.831  1116  3797 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.831  1116  3797 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.831  1116  3797 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.831  1116  3797 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:40.831  1116  3797 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.831  1116  3797 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:40.831  1116  3797 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.831  1116  3797 W System.err: 	at libcore.io.Posix.open(Native Method)
,08-30 23:15:40.831  1116  3797 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.831  1116  3797 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.831  1116  3797 W System.err: 	... 14 more
08-30 23:15:40.831  1116  3797 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.831  1116  3797 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.831  1116  3797 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.831  1116  3797 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.831  1116  3797 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:40.841  1116  8643 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 23:15:40.841  1116  8643 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472591740850.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:40.841  1116  8643 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.841  1116  8643 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.841  1116  8643 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:40.841  1116  8643 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:40.841  1116  8643 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:40.841  1116  8643 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.841  1116  8643 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.841  1116  8643 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.841  1116  8643 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.841  1116  8643 E ErrorReport: 	... 4 more
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
,08-30 23:15:40.831  1116  3797 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.831  1116  3797 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.831  1116  3797 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:40.831  1116  3797 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.831  1116  3797 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.831  1116  3797 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.831  1116  3797 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.831  1116  3797 W System.err: 	... 14 more
08-30 23:15:40.831  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.831  8267  8267 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
08-30 23:15:40.841  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.841  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.841  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.841  8604  8628 D Process : killProcess, pid=8604
08-30 23:15:40.841  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.841  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:40.841  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 23:15:40.841  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:40.841  8630  8630 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:40.841  8630  8630 W HTCLOG  : mask=0x18
08-30 23:15:40.841  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 23:15:40.841  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:40.841  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:40.841  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.841  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.841  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.841  8604  8628 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:40.841  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.841  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.841  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.841  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.841  1116  3606 W System.err: 	... 12 more
08-30 23:15:40.841  8604  8628 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:40.841  8604  8628 W HTCLOG  : mask=0x18
08-30 23:15:40.841  8267  8267 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,08-30 23:15:40.851  8267  8267 I DeviceManagement: WorkflowService: Starting workflow service
,08-30 23:15:40.851  8267  8650 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@2a78584a] args=[Bundle[mParcelledData.dataSize=112]]
08-30 23:15:40.851  8267  8650 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-30 23:15:40.851  8267  8650 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
08-30 23:15:40.851  8267  8650 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,08-30 23:15:40.861  1116  3518 I ActivityManager: Recipient 8604
,08-30 23:15:40.861  1116  3585 I ActivityManager: Start proc 8653:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
,08-30 23:15:40.861  8653  8653 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:40.861  8653  8653 W HTCLOG  : mask=0x18
,08-30 23:15:40.871  8267  8650 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,08-30 23:15:40.871  1116  3756 I ActivityManager: Recipient 6541
,08-30 23:15:40.871  1116  3075 D WifiService: Client connection lost with reason: 4
,08-30 23:15:40.891  8630  8630 I MultiDex: VM with version 2.1.0 has multidex support
08-30 23:15:40.891  8630  8630 I MultiDex: install
,08-30 23:15:40.891  8630  8630 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 23:15:40.891  8267  8650 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,08-30 23:15:40.901  8267  8674 I DeviceManagement: SessionStateController: Checking invariants...
,08-30 23:15:40.901  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : null,
08-30 23:15:40.901  8630  8630 D FaceDetectTask: checkIsOmronEnable start
,08-30 23:15:40.901  8630  8630 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
,08-30 23:15:40.901  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-30 23:15:40.901  8630  8630 D FaceDetectTask: IsOmronEnable : true
08-30 23:15:40.901  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 23:15:40.901  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : null,
08-30 23:15:40.911  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.911  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.911  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 23:15:40.911  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 23:15:40.921  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-30 23:15:40.921  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.921  1116  3518 I ActivityManager: Process com.android.keychain (pid 8604) has died
08-30 23:15:40.921  8630  8630 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:40.921  1116  3518 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10596ms
08-30 23:15:40.921  8630  8630 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-30 23:15:40.921  1116  3756 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6541) has died
08-30 23:15:40.921  8630  8630 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:40.921  1116  3756 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10593ms
08-30 23:15:40.921  8630  8630 W HTCLOG  : mask=0x18
08-30 23:15:40.921  1116  3756 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10593ms
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
,08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.921  8630  8630 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.931  1116  3276 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,08-30 23:15:40.921  8630  8630 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.931  1116  3276 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.941  1116  8683 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 23:15:40.941  1116  8683 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472591740949.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:40.941  1116  8683 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.941  1116  8683 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.941  1116  8683 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:40.941  1116  8683 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:40.941  1116  8683 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:40.941  1116  8683 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.941  1116  8683 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.941  1116  8683 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.941  1116  8683 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.941  1116  8683 E ErrorReport: 	... 4 more
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.921  8630  8630 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 23:15:40.921  8630  8630 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.app.ActivityThread.handleBindAppl,ication(ActivityThread.java:4940)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.921  8630  8630 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.921  8630  8630 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.921  8630  8630 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.921  8630  8630 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.921  8630  8630 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.931  8630  8630 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 23:15:40.931  8630  8630 E AndroidRuntime: FATAL EXCEPTION: main
08-30 23:15:40.931  8630  8630 E AndroidRuntime: Process: com.htc.launcher, PID: 8630
08-30 23:15:40.931  8630  8630 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:40.931  8630  8630 E AndroidRuntime: 	... 11 more
,08-30 23:15:40.931  1116  3276 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 23:15:40.931  1116  3276 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.931  1116  3276 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.931  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.931  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.931  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
,08-30 23:15:40.931  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:40.931  1116  3276 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.931  1116  3276 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:40.931  1116  3276 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.931  1116  3276 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.931  1116  3276 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.931  1116  3276 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.931  1116  3276 W System.err: 	... 14 more
08-30 23:15:40.931  1116  3276 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.931  1116  3276 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,08-30 23:15:40.931  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.931  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.931  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
,08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:40.931  1116  3276 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.931  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.931  1116  3276 W System.err: 	at android.os.Binder.execTransact(Binder.java:454),
08-30 23:15:40.931  1116  3276 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.931  1116  3276 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.931  1116  3276 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.931  1116  3276 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.931  1116  3276 W System.err: 	... 14 more
08-30 23:15:40.931  8630  8630 D Process : killProcess, pid=8630
08-30 23:15:40.931  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
,08-30 23:15:40.931  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.931  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.931  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.931  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.931  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:40.931  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
,08-30 23:15:40.931  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:40.931  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 23:15:40.931  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:40.931  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:40.931  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.931  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
,08-30 23:15:40.931  8630  8630 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:40.931  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.931  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.931  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.931  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.931  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
,08-30 23:15:40.931  1116  3606 W System.err: 	... 12 more
08-30 23:15:40.931  8630  8630 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:40.931  8630  8630 W HTCLOG  : mask=0x18
,08-30 23:15:40.981  8653  8653 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:40.981  8653  8653 W HTCLOG  : mask=0x18
,08-30 23:15:40.981  8653  8653 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.981  8653  8653 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: FATAL EXCEPTION: main
08-30 23:15:40.981  8653  8653 E AndroidRuntime: Process: com.android.documentsui, PID: 8653
08-30 23:15:40.981  8653  8653 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 23:15:40.981  8653  8653 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752),
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 23:15:40.981  8653  8653 E AndroidRuntime: 	... 9 more
08-30 23:15:40.991  1116  1136 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 23:15:40.991  1116  1136 E ActivityManager: App crashed! Process: com.android.documentsui
08-30 23:15:40.991  1116  8685 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 23:15:40.991  1116  8685 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472591741007.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:40.991  1116  8685 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.991  1116  8685 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.991  1116  8685 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:40.991  1116  8685 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:40.991  1116  8685 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:40.991  1116  8685 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.991  1116  8685 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.991  1116  8685 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.991  1116  8685 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.991  1116  8685 E ErrorReport: 	... 4 more
08-30 23:15:40.991  1116  1136 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.001  1116  3518 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 23:15:40.991  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.991  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,08-30 23:15:40.991  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.991  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:40.991  1116  1136 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.991  1116  1136 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:40.991  1116  1136 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.991  1116  1136 W System.err: 	at libcore.io.Posix.open(Native Method)
,08-30 23:15:40.991  1116  1136 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.991  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.991  1116  1136 W System.err: 	... 14 more
08-30 23:15:40.991  1116  1136 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.991  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.991  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.001  1116  8686 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 23:15:41.001  1116  8686 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472591741017.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:41.001  1116  8686 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.001  1116  8686 E ErrorReport: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.001  1116  8686 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:41.001  1116  8686 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:41.001  1116  8686 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:41.001  1116  8686 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.001  1116  8686 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.001  1116  8686 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.001  1116  8686 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.001  1116  8686 E ErrorReport: 	... 4 more
,08-30 23:15:40.991  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.991  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303),
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:40.991  1116  1136 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:40.991  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:40.991  1116  1136 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:40.991  1116  1136 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.991  5553  5764 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
08-30 23:15:40.991  5553  5764 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 23:15:40.991  5553  5764 W HTCLOG  : mask=0x18
08-30 23:15:40.991  1116  1136 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.991  5553  5764 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x55a474b0e0
08-30 23:15:40.991  1116  1136 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.991  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.991  1116  1136 W System.err: 	... 14 more
08-30 23:15:40.991  5553  5764 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-30 23:15:40.991  5553  5764 E AndroidRuntime: Process: android.process.media, PID: 5553
08-30 23:15:40.991  5553  5764 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.991  5553  5764 E AndroidRuntime: 	at androi,d.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.991  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 23:15:40.991  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:40.991  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:40.991  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:40.991  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:40.991  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:40.991  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 23:15:40.991  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:40.991  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 23:15:40.991  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:40.991  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:40.991  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:40.991  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:40.991  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:40.991  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:40.991  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:40.991  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:40.991  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:40.991  1116  3606 W System.err: 	... 12 more
08-30 23:15:41.001  1116  3518 E ActivityManager: App crashed! Process: android.process.media
08-30 23:15:41.001  1116  3518 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.001  1116  3518 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.001  1116  3518 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.001  1116  3518 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.001  1116  3518 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.001  1116  3518 W System.err: 	at android.app.ActivityManage,rNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:41.001  1116  3518 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.001  1116  3518 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.011  1116  3585 I ActivityManager: Recipient 8630
08-30 23:15:41.001  1116  3518 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.001  1116  3518 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.001  1116  3518 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.011  1116  1162 I ActivityManager: Start proc 8688:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
08-30 23:15:41.001  1116  3518 W System.err: 	... 14 more
08-30 23:15:41.001  1116  3518 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.001  1116  3518 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.001  1116  3518 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.001  1116  3518 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.001  1116  3518 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.001  1116  3518 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.001  1116  3518 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:41.001  1116  3518 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.001  1116  3518 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.001  1116  3518 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.001  1116  3518 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.001  1116  3518 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.001  1116  3518 W System.err: 	... 14 more
08-30 23:15:41.001  8653  8653 D Process : killProcess, pid=8653
08-30 23:15:41.001  8653  8653 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:41.001  8653  8653 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:41.001  8653  8653 W HTCLOG  : mask=0x18
08-30 23:15:41.001  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.001  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.001  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.001  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.001  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.001  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:41.001  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 23:15:41.001  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:41.001  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 23:15:41.001  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:41.001  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:41.001  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.001  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.001  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.001  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.001  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.001  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.001  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.001  1116  3606 W System.err: 	... 12 more
08-30 23:15:41.021  5553  5764 D Process : killProcess, pid=5553
08-30 23:15:41.021  5553  5764 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:41.021  5553  5764 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:41.021  5553  5764 W HTCLOG  : mask=0x18
08-30 23:15:41.031  8688  8688 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:41.031  8688  8688 W HTCLOG  : mask=0x18
08-30 23:15:41.031  1116  3585 I ActivityManager: Process com.htc.launcher (pid 8630) has died
08-30 23:15:41.031  1116  3585 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 23:15:41.041  1116  3585 V WindowManager: addAppToken: AppWindowToken{387666d3 token=Token{2c0ce8c2 ActivityRecord{76b910d u0 com.htc.launcher/.Launcher t454}}} to stack=0 task=454 at 0
08-30 23:15:41.041   548   548 I art     : Explicit concurrent mark sweep GC freed 8664(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 123us total 22.436ms
08-30 23:15:41.041  1116  3756 I ActivityManager: Recipient 8653
,08-30 23:15:41.051  1116  3585 I ActivityManager: Start proc 8708:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
08-30 23:15:41.051  1116  3585 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-30 23:15:41.051   494   494 E lowmemorykiller: Error writing /proc/5553/oom_score_adj; errno=22
08-30 23:15:41.051  1116  3756 I ActivityManager: Process com.android.documentsui (pid 8653) has died
08-30 23:15:41.051  1116  3606 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-30 23:15:41.051   548   548 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 120us total 17.950ms
08-30 23:15:41.061  8708  8708 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:41.061  1116  1136 I ActivityManager: Recipient 5553
08-30 23:15:41.061  8708  8708 W HTCLOG  : mask=0x18
08-30 23:15:41.061  1116  1136 I ActivityManager: Process android.process.media (pid 5553) has died
08-30 23:15:41.061  8267  8674 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:41.061  1116  1136 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 20456ms
08-30 23:15:41.061  8267  8674 W HTCLOG  : mask=0x18
08-30 23:15:41.061  3328  3361 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-30 23:15:41.071  8267  8674 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:41.071  3200  3200 I NotificationStackScrollLayout: setBlockTouchEnabled:false
08-30 23:15:41.081   548   548 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 132us total 23.485ms
08-30 23:15:41.081  8267  8674 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.081  8267  8650 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.081  8267  8650 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,08-30 23:15:41.091  8267  8650 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.091  8267  8650 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.091  8267  8650 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@2a78584a]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.091  8267  8650 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.091  8267  8267 I DeviceManagement: WorkflowService: Stopping workflow service
08-30 23:15:41.101  8708  8708 I MultiDex: VM with version 2.1.0 has multidex support
08-30 23:15:41.101  8708  8708 I MultiDex: install
08-30 23:15:41.101  8708  8708 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 23:15:41.111  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 23:15:41.111  8708  8708 D FaceDetectTask: checkIsOmronEnable start
08-30 23:15:41.111  8708  8708 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.121  8708  8708 D FaceDetectTask: IsOmronEnable : true
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.121  8688  8688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.121  8708  8708 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.121  8708  8708 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-30 23:15:41.121  8708  8708 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:41.121  8708  8708 W HTCLOG  : mask=0x18
08-30 23:15:41.131  8688  8739 D PowerUtils: getUserIdOfProcess, curUserId = 0
08-30 23:15:41.131  8688  8739 D PowerUtils: isRunningUnderOwner, isOwner = true
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
,08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:41.131  8708  8708 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.131  8708  8708 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 23:15:41.131  8708  8708 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.131  8708  8708 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:41.131  8708  8708 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:41.131  8708  8708 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:41.131  8708  8708 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:41.131  8708  8708 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:41.131  8708  8708 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: FATAL EXCEPTION: main
08-30 23:15:41.131  8708  8708 E AndroidRuntime: Process: com.htc.launcher, PID: 8708
08-30 23:15:41.131  8708  8708 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:41.131  8708  8708 E AndroidRuntime: 	... 11 more
08-30 23:15:41.141  1116  1135 I ActivityManager: Start proc 8740:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
08-30 23:15:41.141  1116  4214 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 23:15:41.141  1116  4214 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 23:15:41.141  1116  4214 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.141  1116  4214 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 23:15:41.141  1116  4214 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.141  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.141  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.141  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:41.141  1116  8753 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 23:15:41.141  1116  8753 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472591741159.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:41.141  1116  8753 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.141  1116  8753 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.141  1116  8753 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:41.141  1116  8753 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:41.141  1116  8753 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:41.141  1116  8753 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.141  1116  8753 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.141  1116  8753 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.141  1116  8753 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.141  1116  8753 E ErrorReport: 	... 4 more
08-30 23:15:41.141  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.141  1116  4214 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:41.141  1116  4214 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.141  1116  4214 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.141  1116  4214 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.141  1116  4214 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.141  1116  4214 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.141  1116  4214 W System.err: 	... 14 more
08-30 23:15:41.141  1116  4214 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.141  1116  4214 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.141  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.141  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.141  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.141  1116  4214 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.141  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:41.141  1116  4214 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.141  1116  4214 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.141  1116  4214 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.141  1116  4214 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.141  1116  4214 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.141  1116  4214 W System.err: 	... 14 more
08-30 23:15:41.141  8688  8739 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
08-30 23:15:41.141  8708  8708 D Process : killProcess, pid=8708
08-30 23:15:41.141  8708  8708 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:41.141  8708  8708 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:41.141  8708  8708 W HTCLOG  : mask=0x18
08-30 23:15:41.151  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.151  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.151  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.151  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.151  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.151  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:41.151  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 23:15:41.151  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:41.151  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 23:15:41.151  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:41.151  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:41.151  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.151  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.151  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.151  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.151  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.151  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.151  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.151  1116  3606 W System.err: 	... 12 more
08-30 23:15:41.151  8740  8740 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:41.151  8740  8740 W HTCLOG  : mask=0x18
08-30 23:15:41.151  8688  8739 D PowerUsageService: removed uid = 10142
08-30 23:15:41.151  8688  8739 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:41.151  8688  8739 W HTCLOG  : mask=0x18
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.161  8688  8739 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
08-30 23:15:41.161  8688  8739 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 8688
08-30 23:15:41.161  8688  8739 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.161  8688  8739 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.161  1116  1136 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 23:15:41.161  1116  1136 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
08-30 23:15:41.161  1116  1136 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.161  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.161  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.161  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.161  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.161  1116  1136 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:41.161  1116  1136 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.161  1116  1136 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.161  1116  1136 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.161  1116  1136 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.161  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.161  1116  1136 W System.err: 	... 14 more
08-30 23:15:41.161  1116  1136 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.161  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.161  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.161  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.161  1116  1136 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.161  1116  8762 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 23:15:41.161  1116  8762 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472591741179.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:41.161  1116  8762 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.161  1116  8762 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.161  1116  8762 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:41.161  1116  8762 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:41.161  1116  8762 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:41.161  1116  8762 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.161  1116  8762 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.161  1116  8762 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.161  1116  8762 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.161  1116  8762 E ErrorReport: 	... 4 more
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.161  1116  1136 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.161  1116  1136 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:41.161  1116  1136 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.161  1116  1136 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.161  1116  1136 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.161  1116  1136 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.161  1116  1136 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.161  1116  1136 W System.err: 	... 14 more
08-30 23:15:41.171  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.171  8688  8739 D Process : killProcess, pid=8688
08-30 23:15:41.171  8688  8739 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:41.171  8688  8739 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:41.171  8688  8739 W HTCLOG  : mask=0x18
,08-30 23:15:41.171  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.171  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.171  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.171  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.171  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:41.171  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 23:15:41.171  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:41.171  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 23:15:41.171  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:41.171  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:41.171  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.171  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.171  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.171  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.171  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.171  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.171  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.171  1116  3606 W System.err: 	... 12 more
,08-30 23:15:41.211  1116  3276 I ActivityManager: Recipient 8708
,08-30 23:15:41.211  8740  8763 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 23:15:41.211  1116  3276 I ActivityManager: Process com.htc.launcher (pid 8708) has died
08-30 23:15:41.211  8740  8763 W HTCLOG  : mask=0x18
08-30 23:15:41.211  1116  3276 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 23:15:41.221  1116  3276 V WindowManager: addAppToken: AppWindowToken{1919dd4b token=Token{702ce1a ActivityRecord{308ed4c5 u0 com.htc.launcher/.Launcher t455}}} to stack=0 task=455 at 0
,08-30 23:15:41.221  8740  8763 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.221  8740  8763 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.221  8740  8740 V UpdaterAPK | DownloadService: Service onStart
08-30 23:15:41.221  8740  8764 V UpdaterAPK | DownloadService: Updating for startId 1
,08-30 23:15:41.221  8740  8763 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-30 23:15:41.221  8740  8763 E AndroidRuntime: Process: com.htc.updater, PID: 8740
08-30 23:15:41.221  8740  8763 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
,08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.221  8740  8763 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 23:15:41.231  1116  3276 I ActivityManager: Start proc 8766:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-30 23:15:41.231  1116  4214 E ActivityManager: App crashed! Process: com.htc.updater
08-30 23:15:41.231  1116  4214 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 23:15:41.231  1116  3606 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-30 23:15:41.231  1116  4214 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.231  1116  4214 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.231  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87),
08-30 23:15:41.231  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.231  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.231  1116  4214 W System.err: ,	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 23:15:41.231  1116  4214 W System.err: ,	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.231  1116  4214 W System.err: ,	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:98)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.231  8740  8764 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:41.241  1116  3463 I ActivityManager: Recipient 8688
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.241  1116  8779 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 23:15:41.241  1116  8779 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472591741251.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:41.241  1116  8779 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.241  1116  8779 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.241  1116  8779 E ErrorReport: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:41.241  1116  8779 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:41.241  1116  8779 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:41.241  1116  8779 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.241  1116  8779 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.241  1116  8779 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.241  1116  8779 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.241  1116  8779 E ErrorReport: 	... 4 more
08-30 23:15:41.231  1116  4214 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.241  1116  3463 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 8688) has died
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:41.241  1116  3463 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 30277ms
08-30 23:15:41.231  1116  4214 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.231  1116  4214 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: Couldn't open downloads.db for writing (will try read-only):
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at and,roid.content.ContentResolver.query(ContentResolver.java:443)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:98)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.231  8740  8764 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.231  1116  4214 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.231  1116  4214 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.231  1116  4214 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.231  1116  4214 W System.err: 	... 14 more
08-30 23:15:41.231  1116  4214 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.231  1116  4214 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.231  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.231  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.231  1116  4214 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.251  1116  1116 D PMS     : releaseWL(c00760): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.231  1116  4214 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.231  1116  4214 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
,08-30 23:15:41.231  1116  4214 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.231  1116  4214 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.231  1116  4214 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.231  1116  4214 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.231  1116  4214 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.231  1116  4214 W System.err: 	... 14 more
,08-30 23:15:41.231  8740  8764 W SQLiteOpenHelper: Opened downloads.db in read-only mode
08-30 23:15:41.231  8740  8764 V UpdaterAPK | DownloadProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-30 23:15:41.241  8740  8764 V UpdaterAPK | DownloadProvider: created cursor android.database.sqlite.SQLiteCursor@136053bb on behalf of 8740
08-30 23:15:41.241  8740  8763 D Process : killProcess, pid=8740
08-30 23:15:41.241  8766  8766 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:41.241  8766  8766 W HTCLOG  : mask=0x18
08-30 23:15:41.241  8740  8763 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:41.241  8740  8763 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:41.241  8740  8763 W HTCLOG  : mask=0x18
08-30 23:15:41.241  7627  7627 D AlarmReceiver: ACTION_RESTART_INTENT
08-30 23:15:41.241  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.241  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.241  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.241  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.241  1116  3606 W System.err: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.241  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:41.241  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 23:15:41.241  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:41.241  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 23:15:41.241  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:41.241  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:41.241  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.241  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.241  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.241  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.241  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.241  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.241  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.241  1116  3606 W System.err: 	... 12 more
08-30 23:15:41.251  7627  7627 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 23:15:41.251  7627  7627 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 23:15:41.251  7627  7627 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 23:15:41.251  7627  7627 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-30 23:15:41.251  3563  3563 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 23:15:41.261  1116  3520 I ActivityManager: Start proc 8789:com.google.android.gms/u0a19 for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver
,08-30 23:15:41.271  8789  8789 W HTCLOG  : use specified tag [FDManager], func [0].
,08-30 23:15:41.271  8789  8789 W HTCLOG  : mask=0x18
,08-30 23:15:41.281  7627  8810 D HtcModeClient: start the htcmodeservice thread
08-30 23:15:41.281  7627  8810 D HtcModeClient: initCanAgent
,08-30 23:15:41.281  7627  8810 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-30 23:15:41.281  7627  8810 D HtcModeClient: sense info: version = none, id = 2
08-30 23:15:41.291  1116  3479 I ActivityManager: Recipient 8740
08-30 23:15:41.291  7627  8810 D HtcModeClient: display info: width = 1080, height = 1776
08-30 23:15:41.291  7627  8810 D HtcModeClient: display info: mode = 10
,08-30 23:15:41.291  1116  3479 I ActivityManager: Process com.htc.updater (pid 8740) has died,
08-30 23:15:41.291  1116  3479 W ActivityManager: Scheduling restart of crashed service com.htc.updater/.download.DownloadService in 40229ms
08-30 23:15:41.301  8766  8766 I MultiDex: VM with version 2.1.0 has multidex support
08-30 23:15:41.301  8766  8766 I MultiDex: install
08-30 23:15:41.301  8766  8766 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-30 23:15:41.311  8766  8766 D FaceDetectTask: checkIsOmronEnable start
,08-30 23:15:41.311  8766  8766 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
,08-30 23:15:41.311  8789  8789 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 23:15:41.311  8789  8789 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 23:15:41.311  8766  8766 D FaceDetectTask: IsOmronEnable : true
08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 23:15:41.311  8766  8766 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 23:15:41.321  8766  8766 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection(),
08-30 23:15:41.321  8766  8766 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
08-30 23:15:41.321  8766  8766 W HTCLOG  : mask=0x18
,08-30 23:15:41.321  8766  8766 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 23:15:41.321  8766  8766 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
,08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.321  8766  8766 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 23:15:41.321  8766  8766 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
,08-30 23:15:41.321  8766  8766 W System.err: ,	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
,08-30 23:15:41.331  1116  3276 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 23:15:41.321  8766  8766 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
,08-30 23:15:41.331  1116  3276 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 23:15:41.321  8766  8766 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:41.331  1116  8820 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 23:15:41.331  1116  8820 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472591741346.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 23:15:41.331  1116  8820 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.331  1116  8820 E ErrorReport: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.331  1116  8820 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 23:15:41.331  1116  8820 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 23:15:41.331  1116  8820 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 23:15:41.331  1116  8820 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.331  1116  8820 E ErrorReport: 	at libcore.io.Posix.open(Native Method),
08-30 23:15:41.331  1116  8820 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.331  1116  8820 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.331  1116  8820 E ErrorReport: 	... 4 more
08-30 23:15:41.321  8766  8766 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
,08-30 23:15:41.321  8766  8766 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.321  8766  8766 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
,08-30 23:15:41.321  8766  8766 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:41.321  8766  8766 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:41.321  8766  8766 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:41.321  8766  8766 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at com,.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:41.321  8766  8766 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 23:15:41.331  8766  8766 E AndroidRuntime: FATAL EXCEPTION: main
08-30 23:15:41.331  8766  8766 E AndroidRuntime: Process: com.htc.launcher, PID: 8766
08-30 23:15:41.331  8766  8766 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(Cont,entProvider.java:1712)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 23:15:41.331  8766  8766 E AndroidRuntime: 	... 11 more
08-30 23:15:41.331  1116  3276 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 23:15:41.331  1116  3276 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.331  1116  3276 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.331  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,08-30 23:15:41.331  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.331  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
,08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.331  1116  3276 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:41.331  1116  3276 W System.err: 	,at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.331  1116  3276 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.331  1116  3276 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.331  1116  3276 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.331  1116  3276 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.331  1116  3276 W System.err: 	... 14 more
08-30 23:15:41.331  1116  3276 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,08-30 23:15:41.331  1116  3276 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.331  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.331  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.331  1116  3276 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
,08-30 23:15:41.331  1116  3276 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
,08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 23:15:41.331  1116  3276 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 23:15:41.331  1116  3276 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 23:15:41.331  1116  3276 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 23:15:41.331  1116  3276 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.331  1116  3276 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.331  1116  3276 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.331  1116  3276 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.331  1116  3276 W System.err: 	... 14 more
08-30 23:15:41.331  8789  8789 I MultiDex: VM with version 2.1.0 has multidex support
08-30 23:15:41.331  8789  8789 I MultiDex: install
08-30 23:15:41.331  8789  8789 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 23:15:41.331  8766  8766 D Process : killProcess, pid=8766
08-30 23:15:41.331  8766  8766 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 23:15:41.331  8766  8766 W HTCLOG  : use specified tag [Process], func [0].
08-30 23:15:41.331  8766  8766 W HTCLOG  : mask=0x18
08-30 23:15:41.331  1116  3606 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 23:15:41.331  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 23:15:41.331  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 23:15:41.331  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 23:15:41.331  1116  3606 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 23:15:41.331  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 23:15:41.331  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 23:15:41.331  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 23:15:41.331  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 23:15:41.331  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 23:15:41.331  1116  3606 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 23:15:41.331  1116  3606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:15:41.331  1116  3606 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 23:15:41.331  1116  3606 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 23:15:41.331  1116  3606 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 23:15:41.331  1116  3606 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 23:15:41.331  1116  3606 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 23:15:41.331  1116  3606 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 23:15:41.331  1116  3606 W System.err: 	... 12 more
,08-30 23:15:41.381  7627  7627 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-30 23:15:41.381  7627  7627 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 23:15:41.381  7627  7627 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 23:15:41.381  7627  7627 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 23:15:41.381  7627  7627 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 23:15:41.381  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 23:15:41.381  7627  7627 D HtcModeClient: connectState: Force_AWAKE = false
08-30 23:15:41.381  7627  7627 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 23:15:41.381  7627  7627 D HtcModeClient: connectState: POWERCONNECTED_READY = true,
,08-30 23:15:41.391  7627  7664 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak,
08-30 23:15:41.391  7627  7664 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,08-30 23:15:41.401  1116  3756 I ActivityManager: Recipient 8766
08-30 23:15:41.401  1116  3756 I ActivityManager: Process com.htc.launcher (pid 8766) has died
08-30 23:15:41.401  1116  3756 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 23:15:41.401  1116  3756 V WindowManager: addAppToken: AppWindowToken{233af1ca token=Token{5a77935 ActivityRecord{111b1f6c u0 com.htc.launcher/.Launcher t456}}} to stack=0 task=456 at 0
,08-30 23:15:41.411  1116  3756 I ActivityManager: Start proc 8823:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher,
,08-30 23:15:41.421  1116  3606 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-30 23:15:41.421  8789  8789 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 23:15:41.421  8823  8823 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 23:15:41.421  8823  8823 W HTCLOG  : mask=0x18
,08-30 23:15:41.471  8823  8823 I MultiDex: VM with version 2.1.0 has multidex support,
08-30 23:15:41.471  8823  8823 I MultiDex: install
08-30 23:15:41.471  8823  8823 I MultiDex: VM has multidex support, MultiDex support library is disabled.

```
