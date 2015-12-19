#### Test 50650278161ce7f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
--------- beginning of /dev/log/system
D/PMS     (  907): releaseWL(440e0058): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/cutils-trace( 4450): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4450): ====startRecUseTime====
D/htc.customization.log.level( 4450):  is 
W/CustomizationLogLevel( 4450): Level value is invalid, use default level 2
D/CustomizationManager( 4450):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4450): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4450): Parsing tag category name = system
I/CustomizationCIDLoader( 4450): Parsing tag category name = application
I/CustomizationCIDLoader( 4450): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4450): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4450): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4450): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4450): Parsing tag category name = Settings
D/CustomizationManager( 4450):  Read CID file spent 0.120 (s)
D/CustomizationManager( 4450):  All configurations done spent 0.120 (s)
W/HtcNativeFlag( 4450): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4450): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4450): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4450): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4450
D/PMS     (  907): acquireHCC(43b68660): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(43b5f680): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1111829640
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1164): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1164): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1164): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 1164): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1164): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1164): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1164): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1164): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1164): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1164): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1164): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1164): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1164):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1164):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1164): Start print parameters
I/wpa_supplicant( 1164): wpa_s->wpa_state is 9
I/wpa_supplicant( 1164): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1164): isConcurrentMode() is 0
I/wpa_supplicant( 1164): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1164): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1164): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1164): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1164): wpa_s->reassociate is 0
I/wpa_supplicant( 1164): wpa_s->is_screen_on 0
I/wpa_supplicant( 1164): wpa_s->ifname wlan0
I/wpa_supplicant( 1164): End print parameters
I/wpa_supplicant( 1164): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1164): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1164): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1164): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1164): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1164): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 1164): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1164): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1164): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1164): Add randomness: count=14 entropy=6
D/wpa_supplicant( 1164): Add randomness: count=15 entropy=7
D/wpa_supplicant( 1164): Add randomness: count=16 entropy=8
D/wpa_supplicant( 1164): Add randomness: count=17 entropy=9
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1164): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4461 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@41eb4660 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@41eb4660 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@41eb4660 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1164): reply (666) for get BSS: id=0
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-51
I/wpa_supplicant( 1164): tsf=0000000105884456
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=1
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-56
I/wpa_supplicant( 1164): tsf=0000000105884468
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=2
I/wpa_supplicant( 1164): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1164): freq=2427
I/wpa_supplicant( 1164): level=-76
I/wpa_supplicant( 1164): tsf=0000000105884472
I/wpa_supplicant( 1164): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1164): ssid=Gonzos
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=3
I/wpa_supplicant( 1164): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1164): freq=2462
I/wpa_supplicant( 1164): level=-90
I/wpa_supplicant( 1164): tsf=0000000022160086
I/wpa_supplicant( 1164): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1164): ssid=UPC Wi-Free
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=4
I/wpa_supplicant( 1164): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1164): freq=2462
I/wpa_supplicant( 1164): level=-91
I/wpa_supplicant( 1164): tsf=0000000105884478
I/wpa_supplicant( 1164): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=UPC5999698
I/wpa_supplicant( 1164): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-51], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 105884456, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 105884468, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 105884472, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 22160086, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 105884478, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/TrimMemoryManager( 1276): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4461): Binding Chromium to main looper Looper (main, tid 1) {41af8ce8}
I/LibraryLoader( 4461): Expected native library version number "",actual native library version number ""
I/chromium( 4461): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4461): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440b80f0:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4461): 1102115000: getState(). Returning 12
D/PMS     (  907): acquireWL(4243b5c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(42357318): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): releaseWL(4243b5c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4461): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4461): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4461): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4461): Local Branch: 
I/Adreno-EGL( 4461): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4461): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4461):                  aa63bbd948f41d15fc72f585e
W/chromium( 4461): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4461): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4461): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4461): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4461): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4461): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4461): CordovaWebView is running on device made by: HTC
,W/ResourceType( 4461): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4461): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b40768, mServedView=org.apache.cordova.engine.SystemWebView{41b063d0 VFEDH.C. .F....ID 0,0-720,1134 #64}
W/AwContents( 4461): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1276
W/IInputConnectionWrapper( 4461): reportFullscreenMode on inactive InputConnection
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +237ms (total +272ms)
D/JsMessageQueue( 4461): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4461): JniHelper::setJavaVM(0x415d2048), pthread_self() = 1663389064
D/JX-Cordova( 4461): jxcore cordova android initializing
I/dalvikvm-heap( 4461): Grow heap (frag case) to 11.601MB for 144892-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 11.716MB for 217334-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 11.893MB for 325996-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 12.167MB for 488990-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 12.574MB for 733480-byte allocation
,W/PluginManager( 4461): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 24ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 14.021MB for 1650320-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 15.436MB for 2475476-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 17.440MB for 3713210-byte allocation
,W/jxcore-log( 4461): Initializing JXcore engine
,W/jxcore-log( 4461): JXcore engine is ready
,W/jxcore-log( 4461): Starting JXcore engine
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(43b68660): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(43b5f680): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4461): Platform android
W/jxcore-log( 4461): 
,W/jxcore-log( 4461): Process ARCH arm
W/jxcore-log( 4461): 
,I/jxcore-log( 4461): JXcore Cordova bridge is ready!
I/jxcore-log( 4461): 
,W/jxcore-log( 4461): JXcore engine is started
,I/chromium( 4461): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  907): releaseWL(42357318): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/AutoSetting( 1536): service - handleMessage() stop self
,D/AutoSetting( 1536): service - onDestroy() END
,D/AutoSetting( 1536): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4209
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4209:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4209
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,I/jxcore-log( 4461): Toggling radios to true
I/jxcore-log( 4461): 
,D/BluetoothAdapter( 4461): enable(): BT is already enabled..!
,D/WifiManager( 4461): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
D/WifiService(  907): setWifiEnabled: true pid=4461, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1268
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
,W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 9(ms),
,D/WifiService(  907): New client listening to asynchronous messages
D/WifiManager( 4461): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
D/WifiManager( 4461): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): TDLS: Tear down peers
I/wpa_supplicant( 1164): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4461): Radios toggled
I/jxcore-log( 4461): 
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4461): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4461): 
I/jxcore-log( 4461): Perf Test app loaded loaded
I/jxcore-log( 4461): 
I/jxcore-log( 4461): check test folder
I/jxcore-log( 4461): 
I/jxcore-log( 4461): found test : ./testFindPeers.js
I/jxcore-log( 4461): 
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1164): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1164): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb85e0bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1164): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/jxcore-log( 4461): found test : ./testSendData.js
I/jxcore-log( 4461): 
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa,_supplicant( 1164): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1164): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  907):    returned true
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(43017a78): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1164): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1164): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1164):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1164):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1164): Start print parameters
I/wpa_supplicant( 1164): wpa_s->wpa_state is 0
I/wpa_supplicant( 1164): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1164): isConcurrentMode() is 0
I/wpa_supplicant( 1164): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1164): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1164): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1164): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1164): wpa_s->reassociate is 1
I/wpa_supplicant( 1164): wpa_s->is_screen_on 0
I/wpa_supplicant( 1164): wpa_s->ifname wlan0
I/wpa_supplicant( 1164): End print parameters
I/wpa_supplicant( 1164): selected network = 1
D/wpa_supplicant( 1164): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0xb85e24e8  current_ssid=0x0
D/wpa_supplicant( 1164): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1164): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1164): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1164): check if in concurrent case
I/wpa_supplicant( 1164): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1164): RSN: PMKSA cache search - network_ctx=0xb85e24e8 try_opportunistic=0
D/wpa_supplicant( 1164): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1164): State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1164): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1164): nl80211: Unsubscribe mgmt frames handle 0xb85e1718 (mode change)
D/wpa_supplicant( 1164): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85e1718
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211,: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20188 mDataStallAlarmIntent=null
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1164):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164):   * freq=2412
D/wpa_supplicant( 1164):   * Auth Type 0
D/wpa_supplicant( 1164):   * WPA Versions 0x2
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1164): nl80211: Connect request send successfully
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WISPrService( 4084): >>>>>WISPrService start isConnected = false<<<<<
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WISPrService( 4084): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  907):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1164): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1164): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  907):    returned false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
V/NativeCrypto( 1347): Read error: ssl=0x63fef898: I/O error during system call, Connection timed out
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
D/libc    (  363): [NET] entry_id:3   entry:0xb7452590  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7456e40  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb7456d90  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7456f70  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb744dc20  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7452458  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb74522a8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,V/NativeCrypto( 1347): SSL shutdown failed: ssl=0x63fef898: I/O error during system call, Broken pipe
D/WISPrService( 4084): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/PMS     (  907): acquireWL(43c6f5a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/PMS     (  907): acquireWL(440c6f80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/WISPrService( 4084): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1347/10029)
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
I//system/bin/ip(  363): RTNETLINK answers: No such process
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  907):    returned true
E/wpa_supplicant( 1164): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1164): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1164): Failed to initiate AP scan
I/wpa_supplicant( 1164): Failed to initiate AP scan, Failed_to_scan_counter:1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  907): releaseWL(43c6f5a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(440c6f80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,I/chromium( 4461): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Connect event
D/wpa_supplicant( 1164): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1164): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1164): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Add randomness: count=18 entropy=10
I/wpa_supplicant( 1164): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): TDLS: Remove peers on association
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1164): EAPOL: enable timer tick
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1164): getPrivFuncNum +	
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  907): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1164): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1164): Get randomness: len=32 entropy=11
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
,D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
,D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb85e19f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f69b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1164):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1164): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1164): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1164): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1164): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1164): set send_ind_to_ndc = 0
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (1)+
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=1
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1164): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1164): EAPOL authentication completed successfully
I/wpa_supplicant( 1164): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
,D/Tethering(  907): interfaceLinkStateChanged wlan0, true
,D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/WISPrService( 4084): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4084): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  907):    returned true
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 1
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1164): nl80211: Event message available
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/wpa_supplicant( 1164): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1164): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(432684d0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41db7d00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41db7d00 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4522 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/PMS     (  907): acquireWL(4412a208): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(4412a208): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
,I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/CaptivePortalTracker(  907): NoActiveNetworkState,
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTING
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1609/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4272/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4272/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/wpa_supplicant( 1164): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1164): EAPOL: disable timer tick
,I/MusicStore( 4522): Database version: 95
,W/ContextImpl( 4522): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4522): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4522, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4522): Registered
,I/MediaRouter( 4522): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4522/10154)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1987/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4542 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4522): getSelectedRoute
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4522/10154)
I/NetworkMonitor( 4522): type=WIFI subType= reason=null isConnected=false
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4522, uid=10154, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ACRA    ( 4542): ACRA is enabled for com.facebook.katana, intializing...
D/PMS     (  907): acquireWL(43b58b00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/Process (  907): killProcessQuiet, pid=3805
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ACRA    ( 4542): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4542): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/PMS     (  907): releaseWL(43b58b00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  907): Killing 3805:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3805
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4542): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4542): Preparing secondary program dexes.
V/DexLibLoader( 4542): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4542): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4542): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4542): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4542): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4542): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4542): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4542): Dex already copied
D/OdexVerifier( 4542): Odex verification is skipped.
,V/DexLibLoader( 4542): Creating class loader
,V/DexLibLoader( 4542): Finished creating class loader
V/DexLibLoader( 4542): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4542): Dex already copied
D/OdexVerifier( 4542): Odex verification is skipped.
,V/DexLibLoader( 4542): Creating class loader
,V/DexLibLoader( 4542): Finished creating class loader
V/DexLibLoader( 4542): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4542): Dex already copied
D/OdexVerifier( 4542): Odex verification is skipped.
,V/DexLibLoader( 4542): Creating class loader
,V/DexLibLoader( 4542): Finished creating class loader
V/DexLibLoader( 4542): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4542): Dex already copied
D/OdexVerifier( 4542): Odex verification is skipped.
,V/DexLibLoader( 4542): Creating class loader
V/DexLibLoader( 4542): Finished creating class loader
,V/DexLibLoader( 4542): Verifying classes from secondary dexes.
,D/DexLibLoader( 4542): DexLibLoader.ensureDexLoaded took 18 ms
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(432684d0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,W/dalvikvm( 4542): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/dalvikvm( 4542): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,W/dalvikvm( 4542): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
W/dalvikvm( 4542): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4542): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1164): getPrivFuncNum +	
W/dalvikvm( 4542): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1164): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1164): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,W/dalvikvm( 4542): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  907): WAN detection
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/WISPrService( 4084): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4247f080
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1164): Change stage from stage0 to stage3
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(435c6128): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(435c6128): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,W/dalvikvm( 4542): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4542): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4542): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4542): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4542): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4542): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4542): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=4021
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4021:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  907): Recipient 4021
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4593 uid=10079 gids={50079, 3003, 5012}
D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1332): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1332): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1332): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,W/fb4a(:<default>):UserScope( 4542): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4542): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4593): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4593): onReceive CONNECTIVITY_CHANGE networkType=1
,W/fb4a(:<default>):UserScope( 4542): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/PhoneMonitor( 4593): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4593): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4607 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4242
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4242:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
,I/ActivityManager(  907): Recipient 4242
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
,D/PMS     (  907): acquireWL(43c7d910): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
,D/PMS     (  907): acquireWL(43cf8c90): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450488639037 min interval config: 0 actual interval: 60080
D/PMS     (  907): releaseWL(43c7d910): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checking schedule, now: 1450488699125 next: 1450488669006
,I/CheckinService( 2176): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1450488635481
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4622 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4272
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4272:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4272
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4542): Grow heap (frag case) to 9.954MB for 84664-byte allocation
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4622): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4622): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4622): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4542): Grow heap (frag case) to 9.967MB for 28144-byte allocation
,W/ContextImpl( 4622): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4542): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4542): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4622): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4542): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4542): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4542): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4542): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4542): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4542): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4542): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4542): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4542): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/PMS     (  907): releaseWL(43017a78): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
W/dalvikvm( 4542): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4542): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4542): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4542): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4542): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4542): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4542): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/dalvikvm-heap( 4542): Grow heap (frag case) to 10.036MB for 39954-byte allocation
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43cb7d90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(43cb7d90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1609/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
I/Tethering(  907): Found interface wlan0
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTED
,D/AccTypeManager( 1358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/PMS     (  907): acquireWL(43b31dd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4522/10154)
,I/NetworkMonitor( 4522): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/dalvikvm-heap( 4542): Grow heap (frag case) to 10.112MB for 79892-byte allocation
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1609/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3858/10053)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/PMS     (  907): releaseWL(43b31dd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4622/10151)
V/WebViewChromiumFactoryProvider( 4622): Binding Chromium to main looper Looper (main, tid 1) {41afe2d0}
I/LibraryLoader( 4622): Expected native library version number "",actual native library version number ""
,I/chromium( 4622): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4622): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4622): BLUETOOTH permission is missing!
,E/ExternalAccountType( 1358): Unsupported attribute readOnly
D/PMS     (  907): acquireWL(43c694d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(43c10f98): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): releaseWL(43c694d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4622): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4622): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4622): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4622): Local Branch: 
I/Adreno-EGL( 4622): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4622): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4622):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4622): Starting up...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4622/10151)
,I/dalvikvm-heap( 4542): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4622/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c64d80 u0 ReceiverList{425b9920 4542 com.facebook.katana/10027/u0 remote:42613f60}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c64d80 u0 ReceiverList{425b9920 4542 com.facebook.katana/10027/u0 remote:42613f60}}
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43b8fef8 u0 ReceiverList{425ad520 4542 com.facebook.katana/10027/u0 remote:425f80e8}}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/Process (  907): killProcessQuiet, pid=4296
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
I/ActivityManager(  907): Killing 4296:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
I/ActivityManager(  907): Recipient 4296
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1987/10021)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  907): acquireWL(43c7f520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4593): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4593): onReceive CONNECTIVITY_CHANGE networkType=1
D/PMS     (  907): releaseWL(43c7f520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1332): service - onStartCommand() screen is off, don't request location
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4665 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/AutoSetting( 1332): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1332): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4622/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450488639037 min interval config: 0 actual interval: 60554
D/PMS     (  907): acquireWL(4323dfc8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4323dfc8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4542): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/dalvikvm( 4665): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/dalvikvm( 4665): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/ContextImpl( 4542): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/MultiDex( 4665): VM with version 1.6.0 does not have multidex support
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
I/MultiDex( 4665): install
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/MultiDex( 4665): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4542): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/MultiDex( 4665): loading existing secondary dex files
,I/MultiDex( 4665): load found 3 secondary dex files
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/MultiDex( 4665): install done
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/dalvikvm( 4665): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4665): VFY: unable to resolve instance field 36
,W/dalvikvm( 4665): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4665): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4665): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4665): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4665): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,W/dalvikvm( 4665): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4665): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4665): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
W/dalvikvm( 4665): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4665): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2176): Restart initialization of location
,E/MDM     ( 1224): [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1347): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1347): Proximity feature is not enabled.
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
D/PMS     (  907): acquireWL(425e5d08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(425e5d08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4665): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=634875205
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2847421615
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4665/10029)
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,D/Process (  907): killProcessQuiet, pid=3858
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3858:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3858
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4665): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+,
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =da97 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4461): threadid=1: thread exiting with uncaught exception (group=0x416cae30)
,E/AndroidRuntime( 4461): FATAL EXCEPTION: main
E/AndroidRuntime( 4461): Process: com.test.thalitest, PID: 4461
E/AndroidRuntime( 4461): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4461): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4461): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4461): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4461): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4461): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4461): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4461): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4461): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4461): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4461): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4461): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4461): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4461): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4461): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4461): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4461): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4461): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4461): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  907): App crashed! Process: com.test.thalitest
W/ActivityManager(  907):   Force finishing activity com.test.thalitest/.MainActivity
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 249
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
D/Process (  907): killProcessQuiet, pid=4259
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  907): Killing 4259:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process ( 4461): killProcess, pid=4461
D/Process ( 4461): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Recipient 4259
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,W/InputDispatcher(  907): channel '4244dd40 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '4244dd40 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '4244dd40 com.test.thalitest.MainActivity (s)'
I/WindowManager(  907): WINDOW DIED Window{4244dd40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4461
I/ActivityManager(  907): Process com.test.thalitest (pid 4461) has died.
D/WifiService(  907): Client connection lost with reason: 4
W/WindowManager(  907): Failed looking up window
W/WindowManager(  907): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42577e88 does not exist
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  907): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  907): WIN DEATH: null
,I/CheckinTask( 2176): Sending checkin request (12125 bytes)
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4461 uid 10389
W/Binder  ( 1211): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1211): java.lang.NullPointerException
W/Binder  ( 1211): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1211): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1211): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1211): 	at dalvik.system.NativeStart.run(Native Method)
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6a5e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 12
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=15 [20][3][0]
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2176): Checking schedule, now: 1450488701799 next: 1451011638795
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,I/CheckinService( 2176): Checking schedule, now: 1450488701835 next: 1451011638795
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1450488701841
D/PMS     (  907): releaseWL(43cf8c90): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/PMS     (  907): acquireWL(43c6f588): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1347): [NET] getaddrinfo-, 1
D/libc    ( 1347): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ba0a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,W/fb4a(:<default>):UserScope( 4542): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4542): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 271
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1347): [NET] getaddrinfo_proxy-, success
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
,D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4542): Called registerBroadcastReceiver twice.
,D/PMS     (  907): acquireWL(423b9af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  907): releaseWL(43c6f588): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(423b9af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43888798): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(43888798): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/PMS     (  907): releaseWL(43c10f98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  907): acquireWL(42649e48): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4522 10154 null
,W/ContextImpl( 4522): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4522, uid=10154, userID:0
,I/MusicLeanback( 4522): Conditions not met for autocaching.
,I/MusicLeanback( 4522): Stop autocaching.
,D/PMS     (  907): releaseWL(42649e48): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
W/ContextImpl( 4522): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [8][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4622): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4411fa80 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  907): acquireWL(425789d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42c4c7d8: PendingIntentRecord{425ee028 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121598, Int=0
,D/PMS     (  907): acquireWL(43b41748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(425789d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(43285b80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43285b80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43b41748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426b13d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(426b13d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4317fa40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42561d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4344d320): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1224): Vacuum at: now=1450488708109 tag=VacuumService
D/PMS     (  907): releaseWL(4317fa40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42561d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4411c760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(4411c760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4344d320): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4268d3f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4268d3f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(4407e8a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(4407e8a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(434755a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(434755a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42730920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43b52df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43b52df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4350cd28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42730920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426a4630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(426a4630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype for one-off execution 2506 seconds from now (1450488708707)
,D/GetConfigurationSnapshotOperation( 1224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
,D/libc    ( 1224): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =cb4d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 269
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4735 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,W/AccTypeManager( 1358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/dalvikvm-heap( 1276): Grow heap (frag case) to 12.592MB for 53840-byte allocation
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1276): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/Launcher( 1276): Deferring update until onResume
,D/Launcher( 1276): waitUntilResume // bindAppsUpdated
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1358): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907):   Scheme: "mmsto"
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4735): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4735): MmsConfig.loadMmsSettings
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/dalvikvm( 4735): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4735): VFY: unable to resolve instance field 36
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4735): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
V/JNIHelp ( 4735): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4758 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4735, uid=10111, userID:0
,W/Settings( 4735): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4735, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4735, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4735, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4735, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4735, uid=10111, userID:0
,D/MessageFrequencyProvider( 4758): onCreate
D/PMS     (  907): acquireWL(4348e8b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4735 10111 null
,D/MmsCustomizationProvider( 4758): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4758): GetPrviateResource
,V/GetPrviateResource( 4758): GetPrviateResource
,I/[PluginManager]RegisterService( 1332): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1332): handle notify Blinkfeed plugin client changed
,D/MmsCustomizationProvider( 4758): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/IcingCorporaProvider( 2810): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/PMS     (  907): releaseWL(4350cd28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42675578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
I/Babel   ( 4735): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4735): MmsConfig.loadFromDatabase
,W/PackageManager(  907): Unable to load service info ResolveInfo{43c3ccf0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,E/Babel   ( 4735): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4735): MmsConfig.loadFromResources
,E/Babel   ( 4735): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4735): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ProviderInstaller( 4735): Installed default security provider GmsCore_OpenSSL
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/MessageCustFlag( 4758): sense_version=6.0
D/BTAccessoryUtil( 4758): createReceiver
,D/PMS     (  907): acquireWL(440e6638): PARTIAL_WAKE_LOCK  AsyncService 0x1 4064 10160 null
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): releaseWL(4348e8b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/BTAccessoryUtil( 4758): registerReceiver return intent = null
,D/PMS     (  907): releaseWL(42675578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/MessageCustFlag( 4758): sku_id=99
W/SystemReader( 4758): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4758): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4758): networkCode: 
,D/MessageCustFlag( 4758): sku_id=99
D/MmsConfig( 4758): SIE smsPri: null
,D/MmsConfig( 4758): networkCode: 
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
D/HtcTelephonyCapability( 4758): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4758): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4758): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4758): Cannot find qct_8960_interface, use default value instead
D/PMS     (  907): acquireWL(440d70f8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(440d70a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(440e6638): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,I/ActivityManager(  907): Resuming delayed broadcast
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/Process (  907): killProcessQuiet, pid=4314
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4314:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4314
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(440d70a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  907): Resuming delayed broadcast
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  907): acquireWL(423f5680): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(423f5680): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(422805a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(41d59688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(41d59688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(422805a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2810): UpdateCorporaTask done [took 684 ms] updated apps [took 684 ms] 
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8ddb8 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(440d70f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1276): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1276): onLoadItems() -
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8ddb8 -
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,D/Messaging( 4758): mNeedToUpdateDate2 start
,D/MmsConfig( 4758): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4758): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4758): 
D/MmsAsyncWorkHandler( 4758): HM tk = 20001
,D/ReportIndicatorCache( 4758): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4758): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b0a3b0
,I/Messaging( 4758): mccmnc> 
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4758): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4758): [DraftCache/1] refresh
,D/MmsConfig( 4758): networkCode: 
,D/Messaging( 4758): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 4758): sense_version=6.0
D/PhoneStorageUtil( 4758): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4758): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4758): createReceiver
,D/Jerry   ( 4758): start to preload cursor >>>>>>>
,D/Messaging( 4758): mNeedToUpdateDate2: false
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1243): sku_id=99
D/TelephUtils( 1243): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1243): Update uri=content://mms, match=0
,V/MmsProvider( 1243): selection=st=129 AND m_type!=134
,D/Messaging( 4758): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4758): TransactionService is going to be woken up.
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/DraftCache( 4758): [DraftCache/472] rebuildCache
,V/TransactionService( 4758): 1-Creating TransactionService
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Jerry   ( 1243): URI_DRAFT
D/Messaging( 4758): ViewCache CreatePreload
,D/Messaging( 4758): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 4758): onStartCommand: 1
,D/MmsSystemEventReceiver( 4758): unRegisterForConnectionStateChanges
V/TransactionService( 4758): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4758): Loading previous transactions.
D/DraftCache( 4758): hasDraft() = false mNeedNotifyChange = true
D/Cust_MMSMS( 4758): _has_set_default_values_2=true
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/DraftCache( 4758): [DraftCache/472] rebuildCache time: 3
,D/MmsAsyncWorkHandler( 4758): 
D/MmsAsyncWorkHandler( 4758): HM tk = 20002
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1243): device_type: 1
,D/MsgPreferenceUtils( 4758): def_index: 0
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/AccFlag ( 1243): sku_id=99
D/TransactionService( 4758): Force set service start id to 1
V/TransactionService( 4758): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4758): unRegisterForConnectionStateChanges
,D/MsgPreferenceUtils( 4758): globalIndex = 1
D/TransactionService( 4758): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4758): Destroying TransactionService
,V/TransactionService( 4758): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MsgPreferenceUtils( 4758): phone state: true
D/MsgPreferenceUtils( 4758): sd state: false
,D/MsgPreferenceUtils( 4758): vIndex = 0
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4758): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1243): sku_id=99
,I/GAV4    ( 4735): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(424e5408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(424e5408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(425125b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=133696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425125b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(423ba600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42540c98: PendingIntentRecord{42657938 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134527, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  907): releaseWL(423ba600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43ced010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{422694b8: PendingIntentRecord{423b52b8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141745, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
,D/PMS     (  907): acquireWL(44167cd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): releaseWL(43ced010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =63ae +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
,D/AutoSetting( 1332): service - mHandler: update timezone
,D/AutoSetting( 1536): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1536): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1536): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1536): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1536): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1536): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1536): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1536): service - mHandler: update timezone
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/DotMatrix( 1597): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1597): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1536): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1536): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1536): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1536): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1597): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1597): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ddc738 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 7 3 11
,D/AutoSetting( 1332): service - mHandler: update timezone
,D/AutoSetting( 1536): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1332): service - handleMessage() stop self
D/AutoSetting( 1536): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1536): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1597): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1597): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1332): service - handleMessage() quit looper
,D/AutoSetting( 1332): service - onDestroy() END
,D/AutoSetting( 1536): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1536): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1536): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1536): service - mHandler: update timezone
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1536): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1536): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1536): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1536): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1597): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1597): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41b14360 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 9 3 11
,D/PMS     (  907): releaseWL(44167cd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  907): killProcessQuiet, pid=4345
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4345:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4345
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425f2578 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(4357deb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4357deb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(425d4428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{431beb30: PendingIntentRecord{43fb7f10 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=169444, Int=0
,D/PMS     (  907): releaseWL(425d4428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/AutoSetting( 1536): service - handleMessage() stop self
,D/AutoSetting( 1536): service - onDestroy() END
,D/AutoSetting( 1536): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4360
,I/ActivityManager(  907): Killing 4360:com.android.settings:remote/1000 (adj 15): empty #17,
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4360
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(43ce2ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43ce2ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(430d5240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=193696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(430d5240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43e53260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43e53260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4309d280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false),
V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=253696, Int=0
,D/PMS     (  907): releaseWL(4309d280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(440d3350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440d3350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  907): acquireWL(42649a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=313697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42649a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=3989,
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3989:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3989
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4405be50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4405be50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(43089b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=373697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43089b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(426be8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426be8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(434a8978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(434a8978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(41af13b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=433697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41af13b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(43299768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43299768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42675ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(42675ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(43b57c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=493697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b57c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(438be768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(438be768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/ContextImpl( 4417): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,D/TetherSettings( 4084): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4084): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4084): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4084): Cust_ConnectToPC   : spcsc>false
D/        ( 4084): Cust_ConnectToPC   : IPT>true
,D/        ( 4084): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4084): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4084): Index of the first 1 = 3
W/Settings( 4084): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4084): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4084): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4084): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4084): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4084): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4084): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43521170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43521170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4348c8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=553696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4348c8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425f16b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425f16b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b6ef28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41d6a2e0: PendingIntentRecord{424efba0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=589701, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4837 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{424df7e0: PendingIntentRecord{42703538 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450488797054, Int=10800000
,D/PMS     (  907): acquireWL(4257cf60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(43b6ef28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4249d8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4257cf60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(4249d8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4837/10049),
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,D/Process (  907): killProcessQuiet, pid=4392
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
I/ActivityManager(  907): Killing 4392:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4392
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,D/PMS     (  907): acquireWL(43476010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43476010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  907): acquireWL(43c6e0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=613697, Int=0
,D/PMS     (  907): releaseWL(43c6e0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Disconnect event
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1164): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
I/wpa_supplicant( 1164): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1164): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb85e0bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1164): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
,D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(43063c60): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20189 mDataStallAlarmIntent=null
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4084): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 4084): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 4084): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WISPrService( 4084): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,V/NativeCrypto( 1347): Read error: ssl=0x63fe30e0: I/O error during system call, Connection timed out
D/libc    (  363): [NET] entry_id:3   entry:0xb74520f8  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb7452958  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7452428  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb74524e0  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb74522c8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,V/NativeCrypto( 1347): SSL shutdown failed: ssl=0x63fe30e0: I/O error during system call, Broken pipe
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(435205e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/PMS     (  907): acquireWL(435ed508): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1164): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  907):    returned true
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/PMS     (  907): releaseWL(435205e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/PMS     (  907): releaseWL(435ed508): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
,I/Tethering(  907): No IPv4 upstream interface, giving up.
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4522/10154)
D/PMS     (  907): acquireWL(4308a400): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4522): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  907): releaseWL(4308a400): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1609/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1987/10021)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4593): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4593): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1332): Util - no network available!
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/AutoSetting( 1332): service - onCreate()
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4622/10151)
,D/AutoSetting( 1332): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  907): request 42580420 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1332): service - mHandler: cancel location update
D/AutoSetting( 1332): service -           changes count: 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/iu.Environment( 2176): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2176): num queued entries: 0
,I/iu.UploadsManager( 2176): num updated entries: 0
,I/iu.SyncManager( 2176): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1164): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1164): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1164): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1164): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=19 entropy=0
D/wpa_supplicant( 1164): Add randomness: count=20 entropy=1
D/wpa_supplicant( 1164): Add randomness: count=21 entropy=2
D/wpa_supplicant( 1164): Add randomness: count=22 entropy=3
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1164): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1164): 2: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1164): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1164): No APs found - clear blacklist and try again
E/wpa_supplicant( 1164): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1164): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1164): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1164): 2: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1164): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1164): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1164): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1164): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1164): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1164): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=23 entropy=4
D/wpa_supplicant( 1164): Add randomness: count=24 entropy=5
D/wpa_supplicant( 1164): Add randomness: count=25 entropy=6
D/wpa_supplicant( 1164): Add randomness: count=26 entropy=7
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wp,a_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1164): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1164): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1164): reply (666) for get BSS: id=1
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-56
I/wpa_supplicant( 1164): tsf=0000000105884468
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=5
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000636533641
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=6
I/wpa_supplicant( 1164): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1164): freq=2427
I/wpa_supplicant( 1164): level=-78
I/wpa_supplicant( 1164): tsf=0000000636533678
I/wpa_supplicant( 1164): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1164): ssid=Gonzos
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=7
I/wpa_supplicant( 1164): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1164): freq=2462
I/wpa_supplicant( 1164): level=-90
I/wpa_supplicant( 1164): tsf=0000000636533697
I/wpa_supplicant( 1164): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1164): ssid=UPC Wi-Free
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=8
I/wpa_supplicant( 1164): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1164): freq=2462
I/wpa_supplicant( 1164): level=-91
I/wpa_supplicant( 1164): tsf=0000000636533716
I/wpa_supplicant( 1164): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=UPC5999698
I/wpa_supplicant( 1164): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiStateMachine(  907): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 105884468, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 636533641, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 636533678, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 636533697, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 636533716, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1164): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1164): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1164): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1164): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1164): Failed to initiate AP scan
I/wpa_supplicant( 1164): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  907):    returned true
,I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1164): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1164): Failed to initiate AP scan
,I/wpa_supplicant( 1164): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1164): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1164): Failed to initiate AP scan
,I/wpa_supplicant( 1164): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1164): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
D/wpa_supplicant( 1164): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=27 entropy=8
D/wpa_supplicant( 1164): Add randomness: count=28 entropy=9
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1164): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1164): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1164): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
D/wpa_supplicant( 1164): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=29 entropy=10
D/wpa_supplicant( 1164): Add randomness: count=30 entropy=11
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1164): State: INACTIVE -> INACTIVE
,D/WifiNative-wlan0(  907): doBoolean: SET pno 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1164): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1164): nl80211: Event message available
,D/wpa_supplicant( 1164): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0,
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1164): reply (548) for get BSS: id=5
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000642391797
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=6
I/wpa_supplicant( 1164): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1164): freq=2427
I/wpa_supplicant( 1164): level=-78
I/wpa_supplicant( 1164): tsf=0000000642391823
I/wpa_supplicant( 1164): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1164): ssid=Gonzos
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=7
I/wpa_supplicant( 1164): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1164): freq=2462
I/wpa_supplicant( 1164): level=-90
I/wpa_supplicant( 1164): tsf=0000000636533697
I/wpa_supplicant( 1164): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1164): ssid=UPC Wi-Free
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=8
I/wpa_supplicant( 1164): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1164): freq=2462
I/wpa_supplicant( 1164): level=-91
I/wpa_supplicant( 1164): tsf=0000000636533716
I/wpa_supplicant( 1164): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=UPC5999698
I/wpa_supplicant( 1164): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 642391797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 642391823, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 636533697, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 636533716, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1164): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1164): Add randomness: count=31 entropy=12
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[2] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1164): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1164):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1164):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1164): Start print parameters
I/wpa_supplicant( 1164): wpa_s->wpa_state is 3
I/wpa_supplicant( 1164): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1164): isConcurrentMode() is 0
I/wpa_supplicant( 1164): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1164): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1164): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1164): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1164): wpa_s->reassociate is 0
I/wpa_supplicant( 1164): wpa_s->is_screen_on 0
I/wpa_supplicant( 1164): wpa_s->ifname wlan0
I/wpa_supplicant( 1164): End print parameters
I/wpa_supplicant( 1164): selected network = 9
D/wpa_supplicant( 1164): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85e24e8  current_ssid=0x0
D/wpa_supplicant( 1164): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1164): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1164): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1164): check if in concurrent case
I/wpa_supplicant( 1164): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1164): RSN: PMKSA cache search - network_ctx=0xb85e24e8 try_opportunistic=0
D/wpa_supplicant( 1164): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1164): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1164): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1164): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1164): nl80211: Unsubscribe mgmt frames handle 0xb85e1718 (mode change)
D/wpa_supplicant( 1164): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85e1718
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1164):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164):   * freq=2412
,D/wpa_supplicant( 1164):   * Auth Type 0
D/wpa_supplicant( 1164):   * WPA Versions 0x2
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1164): nl80211: Connect request send successfully
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1164): reply (376) for get BSS: id=5
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000642391797
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=6
I/wpa_supplicant( 1164): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1164): freq=2427
I/wpa_supplicant( 1164): level=-78
I/wpa_supplicant( 1164): tsf=0000000642391823
I/wpa_supplicant( 1164): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1164): ssid=Gonzos
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=9
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-55
I/wpa_supplicant( 1164): tsf=0000000644382198
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 642391797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 642391823, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 644382198, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (3) end of scan result ==,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Connect event
D/wpa_supplicant( 1164): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1164): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1164): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Add randomness: count=32 entropy=13
I/wpa_supplicant( 1164): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): TDLS: Remove peers on association
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=1
,D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1164): EAPOL: enable timer tick
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1164): getPrivFuncNum +	
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1164): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1164): Get randomness: len=32 entropy=14
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  907): Associated
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
,D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb85e19f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f69b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1164):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1164): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1164): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1164): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=6
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1164): set send_ind_to_ndc = 0
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1164): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1164): EAPOL authentication completed successfully
I/wpa_supplicant( 1164): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  907): This record is existed, only update it...
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4084): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WISPrService( 4084): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1164): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  907):    returned true
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(426c9028): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 1
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1164): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41db7d00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41db7d00 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 1164): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1164): EAPOL: disable timer tick
,D/PMS     (  907): acquireWL(44098738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/PMS     (  907): releaseWL(44098738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  907): releaseWL(426c9028): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=50 [4][2][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1164): getPrivFuncNum +	
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1164): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1164): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  907): doBoolean: SCAN TYPE=ONLY
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1164): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  907): WAN detection
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  907): Provision feature enable=false
,D/WISPrService( 4084): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4247f080
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1164): Change stage from stage0 to stage3
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,E/NetdConnector(  907): NDC Command {61 resolver setifdns wlan0  192.168.1.1} took too long (802ms)
D/WifiStateMachine(  907): syncGetConfiguredNetworks
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(435351d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(435351d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  907): acquireWL(4351fba0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  907): acquireWL(4269ba18): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4351fba0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450488701841 min interval config: 0 actual interval: 532056
,I/CheckinService( 2176): Checking schedule, now: 1450489233907 next: 1450488731795
,I/CheckinService( 2176): active receiver: enabled
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1450488699179
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  907): releaseWL(43063c60): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=978173754
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=317144633
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4665/10029)
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/CaptivePortalTracker(  907): NoActiveNetworkState
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/PMS     (  907): acquireWL(44071808): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/PMS     (  907): releaseWL(44071808): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1609/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4522/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
I/NetworkMonitor( 4522): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
W/Settings( 4665): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/PMS     (  907): acquireWL(43c43490): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/PMS     (  907): releaseWL(43c43490): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1987/10021)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4593): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1332): service - onStartCommand() screen is off, don't request location
D/MobileConnectivityChangeReceiver( 4593): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1332): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1332): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4622/10151)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
D/PMS     (  907): acquireWL(4359ff50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450488701841 min interval config: 0 actual interval: 533123
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4359ff50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2176): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2176): num queued entries: 0
I/iu.UploadsManager( 2176): num updated entries: 0
,I/iu.SyncManager( 2176): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  907): acquireWL(432e3320): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1347): [NET] getaddrinfo-, 1
D/libc    ( 1347): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b02b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+
V/NativeCrypto( 2176): SSL shutdown failed: ssl=0x6e2f0310: I/O error during system call, Connection timed out
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
V/NativeCrypto( 2176): SSL shutdown failed: ssl=0x6e21a6e8: I/O error during system call, Connection timed out
D/libc    (  363): [NET] +++++ res_nsend xid =c155 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1164): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1164): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1164): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=33 entropy=0
,D/wpa_supplicant( 1164): Add randomness: count=34 entropy=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1164): reply (238) for get BSS: id=5
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000648741481
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=9
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-55
I/wpa_supplicant( 1164): tsf=0000000648741495
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 648741481, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 648741495, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
,D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 150
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 188
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1347): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
,D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/CheckinTask( 2176): Sending checkin request (12246 bytes)
,D/PMS     (  907): acquireWL(43574770): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  907): releaseWL(432e3320): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(43574770): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4341c128): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(4341c128): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=10 [37][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8bba +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2176): Checking schedule, now: 1450489236051 next: 1451012173044
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,I/CheckinService( 2176): Checking schedule, now: 1450489236080 next: 1451012173044
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1450489236087
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(4269ba18): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42c4b698 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  907): acquireWL(4306db00): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4735 10111 null
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1276): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,W/AccTypeManager( 1358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1276): Deferring update until onResume
,D/Launcher( 1276): waitUntilResume // bindAppsUpdated
D/PMS     (  907): releaseWL(4306db00): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/[PluginManager]RegisterService( 1332): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1332): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/IcingCorporaProvider( 2810): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1358): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907):   Scheme: "mms"
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  907): acquireWL(42363ab8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4064 10160 null
D/PMS     (  907): acquireWL(4261f6c8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42363ab8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  907): Unable to load service info ResolveInfo{425b8858 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2810): UpdateCorporaTask done [took 738 ms] updated apps [took 738 ms] 
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  907): acquireWL(4356b9b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4356b9b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(43b5f190): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43b5f190): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(426464d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426464d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43436750): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43436750): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8ddb8 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(4261f6c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1276): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1276): onLoadItems() -
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8ddb8 -
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,D/PMS     (  907): acquireWL(43c96c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43c96c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(440adaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=673697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(440adaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1332): service - mHandler: update timezone
,D/AutoSetting( 1332): service - handleMessage() stop self
,D/AutoSetting( 1536): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1332): service - handleMessage() quit looper
,D/AutoSetting( 1332): service - onDestroy() END
,D/AutoSetting( 1536): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1536): service - onCreate()
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1536): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1536): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1597): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/AutoSetting( 1536): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1536): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1536): service - mHandler: update timezone
D/DotMatrix( 1597): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1536): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1536): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1536): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1536): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1597): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1597): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ddc738 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 7 2 11
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42673790 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(43cffa48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43cffa48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1536): service - handleMessage() stop self
,D/AutoSetting( 1536): service - onDestroy() END
,D/AutoSetting( 1536): service - handleMessage() quit looper
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Disconnect event
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1164): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1164): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1164): TDLS: Remove peers on disassociation
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb85e0bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1164): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/WifiN,ative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  907):    returned true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiPerfLock(  907): release()
,D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20190 mDataStallAlarmIntent=null
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/PMS     (  907): acquireWL(43488d98): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4084): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4084): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/NativeDaemonConnector.ResponseQueue(  907): more buffered than allowed: 10 >= 10
,E/NativeDaemonConnector.ResponseQueue(  907): Removing request: null (5)
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  907): doBoolean: SET pno 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '73 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 73 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1164): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '75 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 75 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WISPrService( 4084): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4084): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1347): Read error: ssl=0x660ff4f0: I/O error during system call, Connection timed out
D/libc    (  363): [NET] entry_id:2   entry:0xb7452410  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7456f68  removed 
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '76 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 76 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(431a8de8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/libc    (  363): [NET] entry_id:3   entry:0xb7456cf8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,V/NativeCrypto( 1347): SSL shutdown failed: ssl=0x660ff4f0: I/O error during system call, Broken pipe
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(429b5730): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 33
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1164): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1164): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1164): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1164): Failed to initiate AP scan
,I/wpa_supplicant( 1164): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  907):    returned true
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  907): releaseWL(431a8de8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/PMS     (  907): releaseWL(429b5730): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
,I/Tethering(  907): No IPv4 upstream interface, giving up.
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1164): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1164): Failed to initiate AP scan
I/wpa_supplicant( 1164): Failed to initiate AP scan, Failed_to_scan_counter:2
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1609/10029)
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 4522): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4522/10154)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/PMS     (  907): acquireWL(427125a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/PMS     (  907): releaseWL(427125a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1987/10021)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1332): Util - no network available!
,D/MobileConnectivityChangeReceiver( 4593): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4593): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1332): service - onCreate()
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
,D/AutoSetting( 1332): service - AddressCache: using context: com.htc.Weather,
D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  907): request 42580420 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1332): service - mHandler: cancel location update
,D/AutoSetting( 1332): service -           changes count: 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4622/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/iu.Environment( 2176): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2176): num queued entries: 0
,I/iu.UploadsManager( 2176): num updated entries: 0
,I/iu.SyncManager( 2176): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1164): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1164): Failed to initiate AP scan
,I/wpa_supplicant( 1164): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
D/wpa_supplicant( 1164): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=35 entropy=2
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1164): No APs found - clear blacklist and try again
E/wpa_supplicant( 1164): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1164): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1164): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
D/wpa_supplicant( 1164): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=36 entropy=3
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1164): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='1'
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 75,
D/wpa_supplicant( 1164): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1164): nl80211: Event message available
,D/wpa_supplicant( 1164): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1164): reply (238) for get BSS: id=5
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000717902092
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=9
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-55
I/wpa_supplicant( 1164): tsf=0000000648741495
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 717902092, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 648741495, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
,D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1164): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1164): Add randomness: count=37 entropy=4
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1164): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1164):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1164):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1164): Start print parameters
I/wpa_supplicant( 1164): wpa_s->wpa_state is 3
,I/wpa_supplicant( 1164): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1164): isConcurrentMode() is 0
I/wpa_supplicant( 1164): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1164): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1164): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1164): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1164): wpa_s->reassociate is 0
,I/wpa_supplicant( 1164): wpa_s->is_screen_on 0
I/wpa_supplicant( 1164): wpa_s->ifname wlan0
I/wpa_supplicant( 1164): End print parameters
I/wpa_supplicant( 1164): selected network = 9
D/wpa_supplicant( 1164): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85e24e8  current_ssid=0x0
D/wpa_supplicant( 1164): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1164): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1164): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1164): check if in concurrent case
I/wpa_supplicant( 1164): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1164): RSN: PMKSA cache search - network_ctx=0xb85e24e8 try_opportunistic=0
D/wpa_supplicant( 1164): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1164): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1164): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1164): nl80211: Unsubscribe mgmt frames handle 0xb85e1718 (mode change)
D/wpa_supplicant( 1164): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85e1718
,D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1164): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1164):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164):   * freq=2412
D/wpa_supplicant( 1164):   * Auth Type 0
,D/wpa_supplicant( 1164):   * WPA Versions 0x2
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1164): nl80211: Connect request send successfully
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1164): reply (238) for get BSS: id=5
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000717902092
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=9
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-56
I/wpa_supplicant( 1164): tsf=0000000719882059
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 717902092, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 719882059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1224): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1164): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
,D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1164): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1164): Failed to initiate AP scan
I/wpa_supplicant( 1164): Failed to initiate AP scan, Failed_to_scan_counter:4
D/WifiNative-wlan0(  907):    returned true
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Connect event
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1164): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1164): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 0
D/HTCRequest(  907): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  907): WifiMonitor:getStatusCodeFromEventString() 1
D/HTCRequest(  907): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  907): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiStateMachine(  907): Enter handleAssociateRejectEvent
D/WifiStateMachine(  907): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
,D/WifiStateMachine(  907): Exit handleAssociateRejectEvent
,I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1164): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
D/wpa_supplicant( 1164): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=38 entropy=5
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1164): No APs found - clear blacklist and try again
E/wpa_supplicant( 1164): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1164): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1164): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
D/wpa_supplicant( 1164): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=39 entropy=6
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): clear disabled list - type=1
I/wpa_supplicant( 1164): No suitable network found
W/wpa_supplicant( 1164): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1164): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
,D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 75
,D/wpa_supplicant( 1164): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1164): nl80211: Event message available
,D/wpa_supplicant( 1164): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1164): reply (238) for get BSS: id=5
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000717902092
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=9
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-56
I/wpa_supplicant( 1164): tsf=0000000719882059
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 717902092, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 719882059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1164): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1164): Add randomness: count=40 entropy=7
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1164): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1164):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1164):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1164): Start print parameters
I/wpa_supplicant( 1164): wpa_s->wpa_state is 3
I/wpa_supplicant( 1164): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1164): isConcurrentMode() is 0
I/wpa_supplicant( 1164): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1164): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1164): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1164): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1164): wpa_s->reassociate is 0
I/wpa_supplicant( 1164): wpa_s->is_screen_on 0
I/wpa_supplicant( 1164): wpa_s->ifname wlan0
I/wpa_supplicant( 1164): End print parameters
I/wpa_supplicant( 1164): selected network = 9
D/wpa_supplicant( 1164): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85e24e8  current_ssid=0x0
D/wpa_supplicant( 1164): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1164): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1164): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1164): check if in concurrent case
,I/wpa_supplicant( 1164): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1164): RSN: PMKSA cache search - network_ctx=0xb85e24e8 try_opportunistic=0
D/wpa_supplicant( 1164): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1164): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1164): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1164): nl80211: Unsubscribe mgmt frames handle 0xb85e1718 (mode change)
D/wpa_supplicant( 1164): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85e1718
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb85e1718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Connect (ifindex=22)
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1164):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164):   * freq=2412
D/wpa_supplicant( 1164):   * Auth Type 0
D/wpa_supplicant( 1164):   * WPA Versions 0x2
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1164): nl80211: Connect request send successfully
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1164): reply (238) for get BSS: id=5
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000717902092
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=9
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-55
I/wpa_supplicant( 1164): tsf=0000000726092503
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 717902092, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 726092503, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): nl80211: Event message available
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1164): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/wpa_supplicant( 1164): nl80211: Connect event
D/wpa_supplicant( 1164): nl80211: Associated on 2412 MHz
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1164): nl80211: Associated with c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1164): State: ASSOCIATING -> ASSOCIATED,
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Add randomness: count=41 entropy=8
I/wpa_supplicant( 1164): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): TDLS: Remove peers on association
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0,
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1164): EAPOL: enable timer tick
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
,I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1164): getPrivFuncNum +	
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1164): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1164): Get randomness: len=32 entropy=9
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412,
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb85e19f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 10
,D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f69b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1164):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1164): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1164): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1164): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): This record is existed, only update it...
E/wpa_supplicant( 1164): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1164): set send_ind_to_ndc = 0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1164): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  907): updateConnectedAP...
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1164): EAPOL authentication completed successfully
I/wpa_supplicant( 1164): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
,D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WISPrService( 4084): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4084): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1164): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 1
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(42bfe078): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  907):    returned null
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1164): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41db7d00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41db7d00 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/wpa_supplicant( 1164): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1164): EAPOL: disable timer tick
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(42bfe078): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=33 [3][1][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1164): getPrivFuncNum +	
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1164): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1164): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  907): doBoolean: SCAN TYPE=ONLY
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY",
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1164): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  907): WAN detection
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/WISPrService( 4084): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4247f080
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1164): Change stage from stage0 to stage3
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
E/NetdConnector(  907): NDC Command {82 resolver setifdns wlan0  192.168.1.1} took too long (799ms)
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  907): acquireWL(4411e930): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4411e930): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  907): acquireWL(43149d28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42688618): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450489236087 min interval config: 0 actual interval: 79914
D/PMS     (  907): releaseWL(43149d28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checking schedule, now: 1450489316009 next: 1450489266044
,I/CheckinService( 2176): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1450489233939
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  907): releaseWL(43488d98): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2128645293
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=1452973520
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4665/10029)
I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4665): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTED
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4593/10079)
D/PMS     (  907): acquireWL(42c64320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(42c64320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1609/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4522/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,I/NetworkMonitor( 4522): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43b35e08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/PMS     (  907): releaseWL(43b35e08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1987/10021)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4542/10027)
,D/AutoSetting( 1332): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4593): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4593): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1332): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1332): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
D/AutoSetting( 1332): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1332): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1332/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4622/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4064/10160)
,D/PMS     (  907): acquireWL(434301e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(434301e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450489236087 min interval config: 0 actual interval: 80996
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2176): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/iu.UploadsManager( 2176): num queued entries: 0
,I/iu.UploadsManager( 2176): num updated entries: 0
,I/iu.SyncManager( 2176): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1347): [NET] getaddrinfo-, 1
,D/libc    ( 1347): [NET] getaddrinfo_proxy+
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/PMS     (  907): acquireWL(4342a628): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e3c2 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2176): [NET] getaddrinfo-, 1
D/libc    ( 2176): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5a69 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1164): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1164): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1164): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=42 entropy=0
D/wpa_supplicant( 1164): Add randomness: count=43 entropy=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1164): reply (238) for get BSS: id=5
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000730871847
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=9
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-55
I/wpa_supplicant( 1164): tsf=0000000730871868
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 730871847, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 730871868, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1347): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 217
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
,D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2176): Sending checkin request (12250 bytes)
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43520d48 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  907): acquireWL(440c5bf0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d5c6 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/PMS     (  907): releaseWL(4342a628): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/PMS     (  907): releaseWL(440c5bf0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(440acac8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(440a16d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(440a16d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
D/PMS     (  907): releaseWL(440acac8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=13 [38][5][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2176): Checking schedule, now: 1450489318585 next: 1451012255578
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
I/CheckinService( 2176): Checking schedule, now: 1450489318608 next: 1451012255578
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429,
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1450489318615
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  907): releaseWL(42688618): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  907): acquireWL(43c625f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=733697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c625f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/PMS     (  907): acquireWL(43c5cc08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4735 10111 null
D/AccTypeManager( 1358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1276): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Launcher( 1276): Deferring update until onResume
,D/Launcher( 1276): waitUntilResume // bindAppsUpdated
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/[PluginManager]RegisterService( 1332): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1332): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
W/AccTypeManager( 1358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PMS     (  907): releaseWL(43c5cc08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/IcingCorporaProvider( 2810): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1358): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  907): acquireWL(425d4768): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(426f8850): PARTIAL_WAKE_LOCK  AsyncService 0x1 4064 10160 null
D/PMS     (  907): releaseWL(426f8850): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  907): Resuming delayed broadcast
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  907): Unable to load service info ResolveInfo{4253c1b0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,I/IcingCorporaProvider( 2810): UpdateCorporaTask done [took 494 ms] updated apps [took 494 ms] 
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  907): acquireWL(429d2348): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(429d2348): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(425ef500): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(425ef500): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43c96cc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43c96cc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8ddb8 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(425d4768): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1276): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1276): onLoadItems() -
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8ddb8 -
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,D/AutoSetting( 1332): service - mHandler: update timezone
,D/AutoSetting( 1332): service - handleMessage() stop self
,D/AutoSetting( 1332): service - handleMessage() quit looper
,D/AutoSetting( 1332): service - onDestroy() END
,D/AutoSetting( 1536): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1536): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1536): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1536): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1536): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1597): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1597): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1536): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1536): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1536): service - mHandler: update timezone
,D/AutoSetting( 1536): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1536): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1536): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1536): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1597): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1597): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ec5660 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  907): acquireWL(426d0e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426d0e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{434e73c0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(43564d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41df33e0: PendingIntentRecord{42489838 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781827, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{43b4af28: PendingIntentRecord{425d5b08 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450489218740, Int=1800000
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(43888718): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43564d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  907): acquireWL(43b6d768): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43888718): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2176): Aggregate from 1450489316048 (log), 1450487418684 (data)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(43b6d768): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1536): service - handleMessage() stop self
,D/AutoSetting( 1536): service - onDestroy() END
,D/AutoSetting( 1536): service - handleMessage() quit looper
,D/PMS     (  907): acquireWL(435909c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(435909c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(423ccc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=793697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(423ccc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(440910f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440910f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(44128df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44128df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  907): acquireWL(434c3588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=853697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(434c3588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4348efb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4348efb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(426869e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=913697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426869e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43067b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): releaseWL(43067b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43c3cca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43c3cca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(425f1960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=973696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425f1960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(426a4ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{425e7ac0: PendingIntentRecord{425511d0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450489517525, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{42579748: PendingIntentRecord{430376a8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450489590733, Int=0
,W/ContextImpl( 4417): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4417): call getInstance()
,D/SmartSyncUtils( 4417): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4417): MY_DEBUG = false
D/PMS     (  907): releaseWL(426a4ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c50be0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4417 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4417): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4417): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4417): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4417): SettingOnTime = 1450504800000, randomSettingOnTime = 1450501215000
D/SmartSyncScreenOnOffTimeReceiver( 4417): SettingOffTime = 1450490400000, randomSettingOffTime = 1450497480000
D/SmartSyncScreenOnOffTimeReceiver( 4417): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4417): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4417): bNightModeTurnOffOnce = false
D/PMS     (  907): releaseWL(43c50be0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(4365e330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(4365e330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(435aff78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): releaseWL(435aff78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4356b1f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1033696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4356b1f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4351e6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/BatteryService(  907): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(4351e6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(434779f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1093697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(434779f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(432d39a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(432d39a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42c3df20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42c3df20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4263d4c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1153697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4263d4c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42564cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42564cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41f6d338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41f6d338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(423bfcd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1213697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(423bfcd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42534b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42534b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4247c6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(4247c6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42639fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1273696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42639fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(421831c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/PMS     (  907): releaseWL(421831c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42725678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42725678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42679f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1333697, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42679f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425bb520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(425bb520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424996c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424996c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42359538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1393696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42359538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(440a3f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440a3f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424ded90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424ded90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b00920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1453696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b00920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4265f2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4265f2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(431ae008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1513697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(431ae008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(432d0da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(432d0da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41e53588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1573696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41e53588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4258e0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4258e0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4247f800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4247f800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42621b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41df33e0: PendingIntentRecord{42489838 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1501849, Int=0
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  907): sending alarm PendingIntent{43488830: PendingIntentRecord{42757800 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1631849, Int=0
,D/PMS     (  907): acquireWL(43237f48): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43237f48): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42621b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(43c86940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1633697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c86940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(432edf68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024186
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024429
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024496
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024498
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024501
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024504
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025980
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025993
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028541
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(432edf68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=22 [84][19][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(438d4930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): releaseWL(438d4930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42c1f7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42c1f7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(436c2ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1693697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(436c2ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4353b900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4353b900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(41d5f330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1753697, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41d5f330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4388bb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4388bb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(43b70d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43b70d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(43503248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1813696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1276): Grow heap (frag case) to 12.693MB for 50416-byte allocation
D/PMS     (  907): releaseWL(43503248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(440bfda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{4243e440: PendingIntentRecord{427498d0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1845727, Int=0
,I/ProcessStatsService(  907): Prepared write state in 60ms
,D/PMS     (  907): releaseWL(440bfda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2015-12-18-14-26-42.bin
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  907): acquireWL(43b6d630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43b6d630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b69918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b69918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1597): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4327f108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4225f8d0: PendingIntentRecord{41f70e60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1873696, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4327f108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5073): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5073): ====startRecUseTime====
D/htc.customization.log.level( 5073):  is 
W/CustomizationLogLevel( 5073): Level value is invalid, use default level 2
D/CustomizationManager( 5073):  Read ACC file spent 0.132 (s)
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5073): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5073): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5073): Parsing tag category name = system
I/CustomizationCIDLoader( 5073): Parsing tag category name = application
I/CustomizationCIDLoader( 5073): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5073): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5073): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5073): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5073): Parsing tag category name = Settings
D/CustomizationManager( 5073):  Read CID file spent 0.188 (s)
D/CustomizationManager( 5073):  All configurations done spent 0.188 (s)
W/HtcNativeFlag( 5073): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5073): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5073): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5073): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=5073, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  907): Skipping PackageSetting{41ea1b88 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1597): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1597): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1597): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  907): acquireWL(434d4558): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): releaseWL(434d4558): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/VoicemailCleanupService( 1288): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/Launcher( 1276): Deferring update until onResume
D/Launcher( 1276): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
W/SQLiteConnectionPool( 2176): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/[PluginManager]RegisterService( 1332): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/[PluginManager]RegisterService( 1332): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
D/Prism.PackageStateRece_( 1276): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
E/ExternalAccountType( 1358): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/IcingCorporaProvider( 2810): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5087 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  907): acquireWL(43c5e750): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2810): UpdateCorporaTask done [took 292 ms] updated apps [took 292 ms] 
W/PackageManager(  907): Unable to load service info ResolveInfo{42604cf0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5105 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (5087/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (5087/10100)
W/GAV2    ( 5087): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 5105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 5105): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5105): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5105): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5105): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5105): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5105): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5105): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5105): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5105): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5105): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5105): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5105): threadid=10: thread exiting with uncaught exception (group=0x416cae30)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5105): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5105): Process: com.android.keychain, PID: 5105
E/AndroidRuntime( 5105): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5105): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5105): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5105): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5105): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5105): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5105): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5105): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5105): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5105): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5105): killProcess, pid=5105
D/Process ( 5105): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450490505028.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 5105
I/ActivityManager(  907): Process com.android.keychain (pid 5105) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5127 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 5127): getInstance(Context context)
W/GAV2    ( 5087): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/AppTag  ( 5127): getInstance(Context context)
D/AppTag  ( 5127): onCreate()
D/PMS     (  907): acquireWL(4213ea38): PARTIAL_WAKE_LOCK  AsyncService 0x1 4064 10160 null
D/PMS     (  907): releaseWL(4213ea38): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4102): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  907): killProcessQuiet, pid=4758
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4758:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2176): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Recipient 4758
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2176): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65635988
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65d82008
W/dalvikvm( 2176): threadid=50: thread exiting with uncaught exception (group=0x416cae30)
E/DriveAsyncService( 2176): disk I/O error (code 3850)
E/DriveAsyncService( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2176): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2176): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2176): Process: com.google.android.gms, PID: 2176
E/AndroidRuntime( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2176): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2176): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2176): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2176): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
D/Process ( 2176): killProcess, pid=2176
D/Process ( 2176): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/SQLiteDatabase( 2176): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2176): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2176): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2176): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2176): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2176): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2176): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2176): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2176
I/ActivityManager(  907): Process com.google.android.gms (pid 2176) has died.
D/PMS     (  907): handleWLDeath(43c5e750): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10998ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10994ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10993ms
E/SQLiteLog( 1347): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1347): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fca6a0
W/dalvikvm( 1347): threadid=1: thread exiting with uncaught exception (group=0x416cae30)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1347): FATAL EXCEPTION: main
E/AndroidRuntime( 1347): Process: com.google.process.gapps, PID: 1347
E/AndroidRuntime( 1347): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1347): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1347): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1347): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1347): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1347): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1347): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1347): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1347): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1347): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1347): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1347): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1347): 	... 10 more
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
D/Process ( 1347): killProcess, pid=1347
D/Process ( 1347): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5157 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 5157): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5157 dbg=false s=true
I/DeviceManagement( 5157): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5157): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5157): WorkflowService: Starting workflow service
I/DeviceManagement( 5157): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b29fd0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5157): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5157): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5157): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5157): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5171 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5157): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5157): SessionStateController: Checking invariants...
I/ActivityManager(  907): Recipient 1347
I/ActivityManager(  907): Process com.google.process.gapps (pid 1347) has died.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20834ms
D/WifiService(  907): Client connection lost with reason: 4
D/Documents( 5171): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 5171): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5171): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5171): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5171): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5171): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5171): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5171): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5171): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5171): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5171): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5171): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5171): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5171): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5171): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5171): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5171): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5171): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5171): threadid=1: thread exiting with uncaught exception (group=0x416cae30)
E/AndroidRuntime( 5171): FATAL EXCEPTION: main
E/AndroidRuntime( 5171): Process: com.android.documentsui, PID: 5171
E/AndroidRuntime( 5171): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5171): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5171): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5171): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5171): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5171): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5171): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5171): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5171): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5171): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5171): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5171): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5171): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5171): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5171): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5171): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5171): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5171): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5171): 	... 10 more
D/Documents( 5171): Loading roots for com.android.externalstorage.documents
D/Process (  907): killProcessQuiet, pid=4837
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8ddb8 +
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5185 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  907): Killing 4837:com.htc.aurora/u0a49 (adj 15): empty #17
I/Prism.WidgetManager( 1276): onLoadItems() +
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4837
E/ActivityManager(  907): App crashed! Process: com.android.documentsui
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5197 uid=10023 gids={50023, 1028, 1015, 1023}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450490505723.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
D/Process (  907): killProcessQuiet, pid=4522
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
D/Process ( 5171): killProcess, pid=5171
D/Process ( 5171): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Killing 4522:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  907): Recipient 5171
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 5185): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
I/ActivityManager(  907): Process com.android.documentsui (pid 5171) has died.
W/dalvikvm( 5185): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 5185): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5185): install
I/MultiDex( 5185): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/ExternalStorage( 5197): After updating volumes, found 1 active roots
I/MultiDex( 5185): loading existing secondary dex files
I/MultiDex( 5185): load found 3 secondary dex files
E/SQLiteDatabase( 5157): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5157): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5157): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5157): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5157): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5157): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5157): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5157): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5157): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 5157): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5157): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5157): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5157): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5157): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5157): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 5157): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5157): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5157): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/MultiDex( 5185): install done
E/SQLiteDatabase( 5157): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5157): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5157): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5157): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5157): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5157): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5157): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5157): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5157): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 5157): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b29fd0]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 5157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 5157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5157): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5157): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5157): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5157): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5157): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5157): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5157): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5157): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 5157): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Recipient 4522
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 4522): Died!
I/ActivityManager(  907): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5214 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}

```
