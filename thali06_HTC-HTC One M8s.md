#### Test 575312438097721_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/CheckinRequestBuilder( 4455): Classify the device as Phone.
,D/libc    ( 4455): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4455): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4455): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4455): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4455): [NET] android_getaddrinfo_proxy+
D/libc    ( 4455): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4455): [NET] android_getaddrinfo_proxy-, success
E/cutils-trace( 6414): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6414): ====startRecUseTime====
D/htc.customization.log.level( 6414):  is 
W/CustomizationLogLevel( 6414): Level value is invalid, use default level 2
I/wpa_supplicant( 1324): environment dirty rate=0 [1][0][0]
D/wpa_supplicant( 1324): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1324): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1324): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1324): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1324): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1324): wlan0: Scan completed in 2.166232 seconds
D/wpa_supplicant( 1324): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1324): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): nl80211: Received scan results (5 BSSes)
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
D/wpa_supplicant( 1324): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1324): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1324): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1324): [NULL] a0:c5:62:7a:49:97 freq=5180 level=-88
D/wpa_supplicant( 1324): wlan0: BSS: Start scan result update 5
E/WifiConfigStore(  936): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
D/wpa_supplicant( 1324): BSS: last_scan_res_used=5/32
D/wpa_supplicant( 1324): wlan0: Scan-only results received
D/wpa_supplicant( 1324): wlan0: Radio work 'scan'@0x55ca091860 done in 2.167108 seconds
E/WifiMonitor(  936): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  936): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  936): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.73 txretriesrate=0.00 rxrate=0.99 userTriggerdPenalty0
E/WifiStateMachine(  936):  good link -> stuck count =0
E/WifiStateMachine(  936):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  936):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  936): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  936): handleMessage: X
E/WifiStateMachine(  936): handleMessage: E msg.what=147461
E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  936): processMsg: ConnectModeState
E/WifiStateMachine(  936):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  936): processMsg: DriverStartedState
E/WifiStateMachine(  936):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  936): processMsg: SupplicantStartedState
E/WifiStateMachine(  936):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
--------- beginning of system
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiStateMachine(  936): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
W/ContextImpl(  936): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1324): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  936): [1,454,429,706,662 ms] noteScanEnd no scan source
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1324): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  936): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@86ef55 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  936): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  936): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  936): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  936): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  936):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  936): Gonzos 38:f8:89:11:e9:11 rssi=-78 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  936): UPC503894600 a0:c5:62:7a:49:97 rssi=-88 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  936): 01ABC c2:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  936): ageScanResultsOut delay 40000 size 5 now 1454429706665
E/WifiAutoJoinController (  936): newSupplicantResults size=5 known=1 true
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1324): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  936): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  936): ssid=NG700
E/WifiAutoJoinController (  936): id=0
E/WifiAutoJoinController (  936): mode=station
E/WifiAutoJoinController (  936): pairwise_cipher=CCMP
E/WifiAutoJoinController (  936): group_cipher=CCMP
E/WifiAutoJoinController (  936): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  936): wpa_state=COMPLETED
E/WifiAutoJoinController (  936): ip_address=192.168.1.130
E/WifiAutoJoinController (  936): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  936): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  936): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  936): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  936): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-58,-127) num=(1,0)
E/WifiAutoJoinController (  936): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  936): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-58 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  936): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  936): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  936): Done attemptAutoJoin status=0
E/WifiConfigStore(  936):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  936): handleMessage: X
D/WifiManager( 1806): getScanResults: Base Package Name=com.google.android.gms, uid=10024
D/libc    ( 4455): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4455): [NET] android_getaddrinfofornet-, err=8
D/CustomizationManager( 6414):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 6414): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6414): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6414): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6414): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6414): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6414): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6414): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6414): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6414): Parsing tag category name = system
I/CustomizationCIDLoader( 6414): Parsing tag category name = application
I/CustomizationCIDLoader( 6414): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6414): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6414): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6414): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6414): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6414): add string-array item, value = 42507
W/ContextImpl(  936): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
I/CustomizationCIDLoader( 6414): add string-array item, value = 21902
I/CustomizationCIDLoader( 6414): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6414): add string-array item, value = 23420
I/CustomizationCIDLoader( 6414): add string-array item, value = 22299
I/CustomizationCIDLoader( 6414): add string-array item, value = 24002
I/CustomizationCIDLoader( 6414): add string-array item, value = 23210
I/CustomizationCIDLoader( 6414): add string-array item, value = 23205
I/CustomizationCIDLoader( 6414): add string-array item, value = 23806
I/CustomizationCIDLoader( 6414): add string-array item, value = 23430
I/CustomizationCIDLoader( 6414): add string-array item, value = 23408
I/CustomizationCIDLoader( 6414): add string-array item, value = 27205
I/CustomizationCIDLoader( 6414): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6414): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6414):  Read CID file spent 0.111 (s)
D/CustomizationManager( 6414):  All configurations done spent 0.111 (s)
D/PMS     (  936): acquireHCC(11975b4a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 936 1000 null
I/ActivityManager(  936): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6414 on display 0
D/PMS     (  936): acquireHCC(7e9abb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 936 1000 null
W/asset   (  936): Copying FileAsset 0x559be535a0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  936): acquireWL(777e216): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 936 1000 null
I/FeedHostManager( 1623): [onPause]
I/FeedProviderManager( 1623): onPause
I/FeedHostManager( 1623): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@14be7774
I/SocialFeedProvider( 1623): +onPause
I/SocialFeedProvider( 1623): -onPause
I/AnimationUtil(  936): isHTCRecent(ThaliTest/Recent screens.)/5
W/HtcSystemUPManager(  936): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  936): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6432 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  409): Explicit concurrent mark sweep GC freed 8668(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 253us total 18.552ms
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 280us total 15.109ms
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 309us total 15.408ms
W/asset   ( 6432): Copying FileAsset 0xac578098 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/StatusBarManagerService(  936): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  936): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  936): hiding MENU key
I/TrimMemoryManager( 1623): [trimMemory] 20
D/libc    ( 4455): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4455): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4455): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4455): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4455): Sending checkin request (8410 bytes)
E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  936):  packet count Tx=205 Rx=291
E/WifiTrafficPoller(  936): notifying of data activity 3
D/WIFI_ICON( 1221): WifiActivity: 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/WebViewFactory( 6432): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6432): Time to load native libraries: 9 ms (timestamps 9996-5)
I/LibraryLoader( 6432): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6432): Binding Chromium to main looper Looper (main, tid 1) {413de63}
I/LibraryLoader( 6432): Expected native library version number "",actual native library version number ""
I/chromium( 6432): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6432): Initializing chromium process, singleProcess=true
W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6432): ApplicationContext is null in ApplicationStatus
W/chromium( 6432): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6432): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6432): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6432): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6432): Local Branch: 
I/Adreno-EGL( 6432): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6432): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6432):                  d74aa161a12b9c6fc6332151
W/System.err(  936): java.lang.Throwable: stack dump
W/System.err(  936): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  936): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  936): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  936): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  936): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  936): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b162487:true
D/BluetoothAdapter( 6432): 928775615: getState(). Returning 12
W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6432): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6432): CordovaWebView is running on device made by: HTC
W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
I/CheckinRequestBuilder( 4455): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  936): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4455): Failed to find provider info for com.google.android.wearable.settings
W/chromium( 6432): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6432): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/art     ( 1829): Explicit concurrent mark sweep GC freed 10913(567KB) AllocSpace objects, 6(504KB) LOS objects, 49% free, 4MB/8MB, paused 1.161ms total 45.181ms
I/InputMethodManager( 6432): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@113310bc, mServedView=org.apache.cordova.engine.SystemWebView{f3f9845 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@28d70b9a
I/HtcModeClient( 3248): handler message = 4011
E/HtcModeClient( 3248): Check connection and retry 12 times.
I/InputMethodManagerService(  936): Disable input method client, pid=1623
D/StatusBarManagerService(  936): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  936): Enable input method client, pid=6432
I/ActivityManager(  936): Displayed com.test.thalitest/.MainActivity: +814ms
I/GLSUser ( 1829): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1829): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1829): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1829): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/PMS     (  936): releaseWL(777e216): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/XT9_C   ( 1400): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1400): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1400): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/CheckinRequestBuilder( 4455): awaiting user notification for token
W/BindingManager( 6432): Cannot call determinedVisibility() - never saw a connection for the pid: 6432
I/RemoteViews( 1221): reapply : com.google.android.gms 1 40
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/CheckinRequestBuilder( 4455): Classify the device as Phone.
I/CheckinTask( 4455): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4455): Checking schedule, now: 1454429707717 next: 1454966539712
I/CheckinService( 4455): active receiver: disabled
I/PackageManager(  936):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4455, uid=10024, userID:0
D/PMS     (  936): releaseWL(5b42d24): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  936): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6486 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
D/JsMessageQueue( 6432): Set native->JS mode to OnlineEventsBridgeMode
D/PhoneMonitor( 6486): Register our PhoneStateListener
V/SetupWizard( 6486): Connected to Gservices successfully
D/PhoneMonitor( 6486): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/ChimeraCfgMgr( 4455): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 4455): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PhoneMonitor( 6486): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1829): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/GLSUser ( 1829): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1829): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1829): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1829): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Kids    ( 4455): [AccountUtils] Account not ready
W/Kids    ( 4455): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4455): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4455): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4455): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4455): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4455): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4455): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4455): 	at java.lang.Thread.run(Thread.java:818)
E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  936):  packet count Tx=209 Rx=297
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 5 40
D/jxcore_app_log( 6432): JniHelper::setJavaVM(0xab40b8f8), pthread_self() = -1402331608
I/chromium( 6432): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  936): releaseHCC(11975b4a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  936): releaseHCC(7e9abb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6432): Initializing JXcore engine
W/jxcore-log( 6432): JXcore engine is ready
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  936):  packet count Tx=209 Rx=297,
,E/WifiTrafficPoller(  936): notifying of data activity 0,
D/WIFI_ICON( 1221): WifiActivity: 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 6432): Starting JXcore engine
,W/jxcore-log( 6432): Platform android
W/jxcore-log( 6432): 
W/jxcore-log( 6432): Process ARCH arm
W/jxcore-log( 6432): 
,I/jxcore-log( 6432): JXcore Cordova bridge is ready!,
I/jxcore-log( 6432): 
W/jxcore-log( 6432): JXcore engine is started
,E/jxcore  ( 6432): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6432): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6432): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/PMS     (  936): acquireWL(1b3e620a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 936 1000 null
,W/PluginManager( 6432): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 55ms. Plugin should use CordovaInterface.getThreadPool().
,W/HtcSystemUPManager(  936): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1623): [onResume]
,I/FeedProviderManager( 1623): onResume
I/SocialFeedProvider( 1623): +onResume
I/SocialFeedProvider( 1623): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1623): -onResume
,D/StatusBarManagerService(  936): setSystemUiVisibility(0x700),
D/StatusBarManagerService(  936): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/FindExtension( 1623): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/StatusBarManagerService(  936): hiding MENU key
I/ThreadedRenderer( 1623): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  936): Disable input method client, pid=6432
D/StatusBarManagerService(  936): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  936): Enable input method client, pid=1623
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6432): reportFullscreenMode on inactive InputConnection
,D/PMS     (  936): releaseWL(1b3e620a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,E/WifiStateMachine(  936): handleMessage: E msg.what=131155,
E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564203683] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
,E/WifiStateMachine(  936):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564203682] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  936):  get link layer stats 0
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
D/StatusBarManagerService(  936): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  936): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  936): hiding MENU key
,I/wpa_supplicant( 1324): environment dirty rate=29 [17][5][0]
,E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  936): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  936): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.87 txretriesrate=0.00 rxrate=7.50 userTriggerdPenalty0
E/WifiStateMachine(  936):  good link -> stuck count =0
E/WifiStateMachine(  936):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  936):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  936): RSSI current: 3 new: -58, 3
,E/WifiStateMachine(  936): handleMessage: X
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3,
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  936):  packet count Tx=209 Rx=298
E/WifiTrafficPoller(  936): notifying of data activity 1
D/WIFI_ICON( 1221): WifiActivity: 1
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/OpenGLRenderer( 1623): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,D/Process (  936): killProcessQuiet, pid=5834
I/ActivityManager(  936): Killing 5834:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  936): Recipient 5834
,D/Process (  936): killProcessQuiet, pid=5801
I/ActivityManager(  936): Killing 5801:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,E/WifiDataStallTracker(  936): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  936): updateDataStallInfo: mDataStallTxRxSum={txSum=189 rxSum=173} preTxRxSum={txSum=171 rxSum=160}
D/WifiDataStallTracker(  936): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  936): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  936): Recipient 5801
,D/Process (  936): killProcessQuiet, pid=5883
I/ActivityManager(  936): Killing 5883:com.htc.calendar/u0a10 (adj 15): empty #18
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  936): Recipient 5883
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1221): WifiActivity: 3
E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=299
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  936): notifying of data activity 3
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=299
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  936): notifying of data activity 0
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 3248): handler message = 4011,
,E/HtcModeClient( 3248): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3248): Don't start project servcice
,D/HtcModeClient( 3248): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3248): connectState: CONNECTION_READY = false,
D/SilentMusic( 3248): call stop,
D/HtcModeClient( 3248): close connection,
W/HtcModeClient( 3248): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3248): read the terminate packet, so break
,D/Process (  936): killProcessQuiet, pid=3248,
I/ActivityManager(  936): Killing 3248:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiStateMachine(  936): handleMessage: E msg.what=131155
E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=8.9, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564200663] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=8.9, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1564200661] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  936):  get link layer stats 0
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [2][0][0],
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  936): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
,E/WifiStateMachine(  936): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.43 txretriesrate=0.00 rxrate=4.75 userTriggerdPenalty0
E/WifiStateMachine(  936):  good link -> stuck count =0,
E/WifiStateMachine(  936):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  936):  isHighRSSI       ---> score=65
,I/ActivityManager(  936): Recipient 3248
,E/WifiStateMachine(  936): handleMessage: X
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  936): RSSI current: 3 new: -58, 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=299
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 1
,E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=300
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  936): notifying of data activity 1
,D/AccTypeManager( 1756): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1756): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1623): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1623): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1623): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader(  936): Cannot find grip_rejection_width, use default value instead
,I/ActivityManager(  936): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6515 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager(  936): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1756): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1563): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1756): Unsupported attribute readOnly,
,W/ResourcesManager( 6515): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/PackageManager(  936): Unable to load service info ResolveInfo{32833110 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  936): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  936): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475),
W/PackageManager(  936): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  936): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  936): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  936): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  936): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  936): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  936): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  936): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  936): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  936): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  936): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  936): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  936): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  936): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  936): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1806): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  936): applying state to connected service,
,D/PMS     (  936): acquireWL(1ca9435c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1806 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  936): releaseWL(1ca9435c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  936): applying state to connected service
,D/PMS     (  936): acquireWL(3bbfe665): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1806 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(3bbfe665): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,V/GmsNetworkLocationProvi( 1806): DISABLE
,D/PMS     (  936): acquireWL(60f3a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1806 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(60f3a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel_SMS( 6515): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6515): MmsConfig.loadMmsSettings
,I/ActivityManager(  936): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6546 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  936): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6559 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  936): acquireWL(1c1457eb): PARTIAL_WAKE_LOCK  *alarm* 0x1 936 1000 WorkSource{10076}
V/AlarmManager(  936): sending alarm PendingIntent{12353948: PendingIntentRecord{dcd83e1 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454429714852, Int=60000
,D/PMS     (  936): releaseWL(1c1457eb): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076},
,W/HtcWrapAdjustableCursorFactory( 6546): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 6546): onCreate
,V/GetPrviateResource( 6546): GetPrviateResource,
D/MmsCustomizationProvider( 6546): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 6546): GetPrviateResource
D/SMSBackup( 6559): SMSBackupAgentService started
,D/SMSBackup( 6559): Checking restore status
D/SMSBackup( 6559): Restore complete
D/SMSBackup( 6559): cancelCheckAlarm
,D/SMSBackup( 6559): SMSBackupAgentService completed: completed in 0.0 seconds
,D/MessageCustFlag( 6546): sense_version=6.0
,D/BTAccessoryUtil( 6546): createReceiver
,D/MmsCustomizationProvider( 6546): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/BTAccessoryUtil( 6546): registerReceiver return intent = null
,D/MessageCustFlag( 6546): sku_id=118
,I/Babel_SMS( 6515): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6515): MmsConfig.loadFromDatabase
,D/HtcBuildUtils( 6546): getRATByHtcTelephonyCapability:1
,W/SystemReader( 6546): Cannot find qct_8960_interface, use default value instead
,E/Babel_SMS( 6515): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6515): MmsConfig.loadFromResources
,E/Babel_SMS( 6515): canonicalizeMccMnc: invalid mccmnc nullnull,
I/Babel_SMS( 6515): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6,
,E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=300
E/WifiTrafficPoller(  936): notifying of data activity 0
D/WIFI_ICON( 1221): WifiActivity: 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/art     (  936): Explicit concurrent mark sweep GC freed 32013(1724KB) AllocSpace objects, 6(312KB) LOS objects, 33% free, 18MB/28MB, paused 1.613ms total 159.926ms
,I/PackageManager(  936):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6515, uid=10112, userID:0
,W/Settings( 6515): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6515): startup - clean
,I/Babel   ( 6515): deleted: false for 0,
,I/PackageManager(  936):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6515, uid=10112, userID:0
,I/PackageManager(  936):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6515, uid=10112, userID:0
,I/PackageManager(  936):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6515, uid=10112, userID:0
,I/PackageManager(  936):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6515, uid=10112, userID:0,
I/PackageManager(  936):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6515, uid=10112, userID:0,
,D/PMS     (  936): acquireWL(384d8478): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6515 10112 null
,D/Process (  936): killProcessQuiet, pid=6047,
I/ActivityManager(  936): Killing 6047:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  936): Recipient 6047
,W/VideoCapabilities( 6515): Unrecognized profile 2130706433 for video/avc,
,I/[PluginManager]RegisterService( 1505): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1505): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4455): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4455): Null package name or gms related package.  Ignoreing.
,D/PMS     (  936): acquireWL(efbe153): PARTIAL_WAKE_LOCK  Icing 0x1 4455 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): acquireWL(39186a90): PARTIAL_WAKE_LOCK  AsyncService 0x1 6075 10167 null
,D/PMS     (  936): releaseWL(39186a90): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  936): acquireWL(3e1a6b8e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6075 10167 null
,D/PMS     (  936): releaseWL(3e1a6b8e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5918): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 4455): updateResources: need to parse f{com.google.android.gms}
,W/VideoCapabilities( 6515): Unsupported mime video/x-ms-wmv,
,W/Utils   ( 6515): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 6515): Unsupported mime audio/qcelp
,D/PMS     (  936): releaseWL(efbe153): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/AudioCapabilities( 6515): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6515): Unsupported mime audio/qcelp
E/WifiDataStallTracker(  936): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  936): updateDataStallInfo: mDataStallTxRxSum={txSum=191 rxSum=174} preTxRxSum={txSum=189 rxSum=173}
D/WifiDataStallTracker(  936): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  936): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/VideoCapabilities( 6515): Unsupported mime video/x-ms-wmv
,I/UpdateIcingCorporaServi( 5918): UpdateCorporaTask done [took 68 ms] updated apps [took 68 ms] 
,I/VideoCapabilities( 6515): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6515): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6515): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6515): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6515): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 6515): onServiceConnected
,W/Babel   ( 6515): Attempted to change video mute state without an active call.
,D/PMS     (  936): releaseWL(384d8478): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6515): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6515): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6515): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/WifiStateMachine(  936): WiFiStateMachine SCAN ALARM,
D/PMS     (  936): acquireWL(68427cb): PARTIAL_WAKE_LOCK  *alarm* 0x1 936 1000 WorkSource{1000}
E/WifiStateMachine(  936): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  936): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  936):     Client/Owner: Client
D/WifiDisplayAdapter(  936):     GroupId: 
D/WifiDisplayAdapter(  936):     Passphrase: 
D/WifiDisplayAdapter(  936):     SessionId: 0
D/WifiDisplayAdapter(  936):     IP Address: }
E/WifiStateMachine(  936): processMsg: ConnectedState
V/AlarmManager(  936): sending alarm PendingIntent{30254151: PendingIntentRecord{2f69adb6 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454429715635, Int=20000
E/WifiStateMachine(  936):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:2171 rssi=-58 f=2412 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.7 fiv=90000 [on:0 tx:0 rx:0 period:2789] from screen [on:0 period:-1564197706]
D/PMS     (  936): releaseWL(68427cb): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:2171 rssi=-58 f=2412 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.7 fiv=90000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1564197704]
E/WifiStateMachine(  936): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.43 rxSuccessRate=4.75 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-58
E/WifiStateMachine(  936): WifiStateMachine CMD_START_SCAN with age=11154 interval=90000 maxinterval=300000
E/WifiStateMachine(  936): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  936): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  936): has c0:ff:d4:d3:aa:48 freq=2412 age=2944 ?=true
E/WifiStateMachine(  936): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1324): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1324): wpa_supplicant_scan enter
D/wpa_supplicant( 1324): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1324): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1324): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1324): WPS:  * Request Type
D/wpa_supplicant( 1324): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1324): WPS:  * UUID-E
D/wpa_supplicant( 1324): WPS:  * Primary Device Type
D/wpa_supplicant( 1324): WPS:  * RF Bands (3)
D/wpa_supplicant( 1324): WPS:  * Association State
D/wpa_supplicant( 1324): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1324): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1324): WPS:  * Manufacturer
D/wpa_supplicant( 1324): WPS:  * Model Name
D/wpa_supplicant( 1324): WPS:  * Model Number
D/wpa_supplicant( 1324): WPS:  * Device Name
D/wpa_supplicant( 1324): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1324): P2P: * P2P IE header
D/wpa_supplicant( 1324): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1324): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1324): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1324): wlan0: Add radio work 'scan'@0x55ca091860
D/wpa_supplicant( 1324): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1324): wlan0: Starting radio work 'scan'@0x55ca091860 after 0.000043 second wait
D/wpa_supplicant( 1324): wlan0: nl80211: scan request
D/wpa_supplicant( 1324): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1324): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1324): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1324): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1324): wlan0: Own scan request started a scan in 0.000091 seconds
I/wpa_supplicant( 1324): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  936): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  936): [1,454,429,715,644 ms] noteScanstart no scan source
E/WifiStateMachine(  936): handleMessage: X
E/WifiMonitor(  936): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  936): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  936): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1324): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1324): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1324): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1324): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1324): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1324): wlan0: Scan completed in 0.050135 seconds
D/wpa_supplicant( 1324): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1324): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1324): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1324): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1324): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1324): [NULL] a0:c5:62:7a:49:97 freq=5180 level=-88
D/wpa_supplicant( 1324): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1324): BSS: last_scan_res_used=5/32
D/wpa_supplicant( 1324): wlan0: Scan-only results received
D/wpa_supplicant( 1324): wlan0: Radio work 'scan'@0x55ca091860 done in 0.051089 seconds
E/WifiMonitor(  936): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  936): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  936): handleMessage: E msg.what=147461
E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  936): processMsg: ConnectModeState
,E/WifiStateMachine(  936):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  936): processMsg: DriverStartedState
E/WifiStateMachine(  936):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  936): processMsg: SupplicantStartedState
E/WifiStateMachine(  936):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
W/System  ( 6515): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
D/WifiStateMachine(  936): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1324): wlan0: Control interface command 'LIST_DONGLES'
I/ProviderInstaller( 6515): Installed default security provider GmsCore_OpenSSL
,W/ContextImpl(  936): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  936): [1,454,429,715,698 ms] noteScanEnd no scan source
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1324): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  936): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@86ef55 sup_state=COMPLETED debouncing=false
,E/WifiAutoJoinController (  936): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  936): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  936): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  936): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  936):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  936): Gonzos 38:f8:89:11:e9:11 rssi=-78 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  936): UPC503894600 a0:c5:62:7a:49:97 rssi=-88 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  936): 01ABC c2:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  936): ageScanResultsOut delay 40000 size 5 now 1454429715701
E/WifiAutoJoinController (  936): newSupplicantResults size=5 known=1 true
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1324): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  936): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  936): ssid=NG700
E/WifiAutoJoinController (  936): id=0
E/WifiAutoJoinController (  936): mode=station
E/WifiAutoJoinController (  936): pairwise_cipher=CCMP
E/WifiAutoJoinController (  936): group_cipher=CCMP
E/WifiAutoJoinController (  936): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  936): wpa_state=COMPLETED
E/WifiAutoJoinController (  936): ip_address=192.168.1.130
E/WifiAutoJoinController (  936): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  936): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  936): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  936): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  936): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-58,-127) num=(1,0)
E/WifiAutoJoinController (  936): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  936): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-58 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  936): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  936): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  936): Done attemptAutoJoin status=0
E/WifiConfigStore(  936):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  936): handleMessage: X
E/WifiStateMachine(  936): handleMessage: E msg.what=131155
E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:61] from screen [on:0 period:-1564197638] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564197637] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  936):  get link layer stats 0
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  936): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  936): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.72 txretriesrate=0.00 rxrate=2.87 userTriggerdPenalty0
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  936):  good link -> stuck count =0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  936):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  936):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  936): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  936): handleMessage: X
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=301
E/WifiTrafficPoller(  936): notifying of data activity 1,
D/WIFI_ICON( 1221): WifiActivity: 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/Prism.ItemManager( 1623): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1623): loadItems() com.htc.launcher.pageview.WidgetManager@31a423a9 +
I/Prism.WidgetManager( 1623): onLoadItems() +
,W/ResourcesManager( 1623): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1623): Copying FileAsset 0x559c0ad270 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1623): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1623): onLoadItems() -
,I/Prism.ItemManager( 1623): loadItems() com.htc.launcher.pageview.WidgetManager@31a423a9 -,
,D/PhoneApp( 1563): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1563): -- N1 =0
D/PhoneApp( 1563): -- N2 =0
D/PhoneApp( 1563): -- N3 =0
,D/Messaging( 6546): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6546): networkCode: 
D/MessageCustFlag( 6546): sku_id=118
D/MmsConfig( 6546): SIE smsPri: null
,D/MmsConfig( 6546): networkCode: 
,D/MmsConfig( 6546): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 6546): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 6546): 
D/MmsAsyncWorkHandler( 6546): HM tk = 20001
D/ReportIndicatorCache( 6546): MSG_QUERY_REPORTS >>
,D/Messaging( 6546): mNeedToUpdateDate2 start
,D/SettingsManager( 6546): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2dca0a60
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=301
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  936): notifying of data activity 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/DraftCache( 6546): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6546): [DraftCache/1] refresh
D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 78
D/AccFlag ( 1563): sku_id=118
,D/DraftCache( 6546): [DraftCache/161] rebuildCache
,D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55,
D/MmsSmsV2Provider( 1563):  slotId = -1000
D/MmsSmsV2Provider( 1563): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
I/Messaging( 6546): mccmnc> 
,D/MmsConfig( 6546): networkCode: 
,D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 78
D/MmsSmsV2Provider( 1563):  slotId = -1000
D/MmsSmsV2Provider( 1563): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6546): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/MmsSmsV2Provider( 1563):  slotId = -1000
D/MmsSmsV2Provider( 1563): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
,D/MmsSmsV2Provider( 1563):  slotId = -1000
D/MmsSmsV2Provider( 1563): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 6546): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Messaging( 6546): mNeedToUpdateDate2: false,
D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
D/Jerry   ( 1563): URI_DRAFT
,D/DraftCache( 6546): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 6546): [DraftCache/161] rebuildCache time: 14
D/MmsAsyncWorkHandler( 6546): 
D/MmsAsyncWorkHandler( 6546): HM tk = 20002
,D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 98,
D/AccFlag ( 1563): sku_id=118
,D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 78
,D/AccFlag ( 1563): sku_id=118
D/MessageCustFlag( 6546): sense_version=6.0
D/Jerry   ( 6546): start to preload cursor >>>>>>>
,D/PhoneStorageUtil( 6546): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6546): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6546): createReceiver
,D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 98
D/MmsSmsV2Provider( 1563):  slotId = -1000
,D/Messaging( 6546): ViewCache CreatePreload
,D/Messaging( 6546): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1563): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 78
,V/MmsProvider( 1563): Update uri=content://mms, match=0
V/MmsProvider( 1563): selection=st=129 AND m_type!=134
,D/Messaging( 6546): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6546): TransactionService is going to be woken up.
,V/TransactionService( 6546): 1-Creating TransactionService,
,D/Cust_MMSMS( 6546): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6546): def_index: 0
,D/MsgPreferenceUtils( 6546): globalIndex = 1
,V/TransactionService( 6546): onStartCommand: 1,
D/MmsSystemEventReceiver( 6546): unRegisterForConnectionStateChanges
V/TransactionService( 6546): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6546): Loading previous transactions.
,D/MsgPreferenceUtils( 6546): phone state: true,
,D/MsgPreferenceUtils( 6546): sd state: false
D/MsgPreferenceUtils( 6546): vIndex = 0
,D/TelephUtils( 1563): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/AccFlag ( 1563): device_type: 1
,D/TransactionService( 6546): Force clearing mTransactionList,
D/TransactionService( 6546): Force set service start id to 1
,V/TransactionService( 6546): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 6546): unRegisterForConnectionStateChanges
D/TransactionService( 6546): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6546): Destroying TransactionService
,V/TransactionService( 6546): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=301
,E/WifiStateMachine(  936): handleMessage: E msg.what=131155,
E/WifiStateMachine(  936): processMsg: ConnectedState
,E/WifiStateMachine(  936):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564194617] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564194616] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  936):  get link layer stats 0
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0]
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiConfigStore(  936): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  936): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.36 txretriesrate=0.00 rxrate=2.44 userTriggerdPenalty0
E/WifiStateMachine(  936):  good link -> stuck count =0
E/WifiStateMachine(  936):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  936):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  936): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  936): handleMessage: X
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=302
E/WifiTrafficPoller(  936): notifying of data activity 1
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/ActivityManager(  936): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{1f5967ab #7 A=.Prism U=0 sz=1}
I/PMS     (  936): Going to sleep due to screen timeout (uid 1000)...
,W/PMS     (  936): mWirelessDisplayManager is null
I/SensorManager(  936): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@8079630
W/PMS     (  936): mWirelessDisplayManager is still null
W/SensorService(  936): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  936): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  936): pid=936, uid=1000
W/PMN     (  936): goingToSleep
W/SensorService(  936): Active sensors: size = 4
I/PMS     (  936): Sleeping (uid 1000)...
W/SensorService(  936): Accelerometer Sensor (handle=0x00000000, connections=1)
D/XAN-DPS (  936): prepareColorFade 1
W/SensorService(  936): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  936): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  936): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  936): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@8079630, eanble = 0, strlen(mName) = 90
W/SensorService(  936): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  936): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@26b267ba
W/SensorService(  936): Listener[1] = com.htc.smartdim.sensor_eye@1b2e56b7
W/SensorService(  936): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  936): acquireWL(2fe96e08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 936 1000 null
,I/Adreno-EGL(  936): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  936): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  936): Build Date: 03/09/15 Mon
I/Adreno-EGL(  936): Local Branch: 
I/Adreno-EGL(  936): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  936): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  936):                  d74aa161a12b9c6fc6332151
,W/PMN     (  936): goingToSleep done
I/FeedHostManager( 1623): [onPause]
,I/FeedProviderManager( 1623): onPause
I/FeedHostManager( 1623): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@14be7774
I/SocialFeedProvider( 1623): +onPause
I/SocialFeedProvider( 1623): -onPause
,W/HtcSystemUPManager(  936): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/ActivityManager(  936): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6633 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
D/PMS     (  936): releaseWL(2fe96e08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  936): ACTION_SCREEN_ON,
,I/AlarmManager(  936): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  936): [AlarmQueuing] done recovering
I/AlarmManager(  936): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  936): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  936): ENABLE_TRAFFIC_STATS_POLL true Token 11,
E/WifiTrafficPoller(  936):  packet count Tx=211 Rx=302
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  936): notifying of data activity 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiDataStallTracker(  936): ENABLE_DATA_MONITOR_POLL true Token 1
,E/WifiStateMachine(  936): handleMessage: E msg.what=131167,
,E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  936): processMsg: ConnectModeState
E/WifiStateMachine(  936):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  936): processMsg: DriverStartedState
E/WifiStateMachine(  936):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  936): processMsg: SupplicantStartedState
E/WifiStateMachine(  936):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  936): processMsg: DefaultState
E/WifiStateMachine(  936):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  936):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1324): SET_SCREEN_ON:On
I/wpa_supplicant( 1324): htc_wext_set_keepalive +
D/WifiDisplayAdapter(  936): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  936):     Client/Owner: Client
D/WifiDisplayAdapter(  936):     GroupId: 
D/WifiDisplayAdapter(  936):     Passphrase: 
D/WifiDisplayAdapter(  936):     SessionId: 0
D/WifiDisplayAdapter(  936):     IP Address: }
I/wpa_supplicant( 1324): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1324): getPrivFuncNum +	
I/wpa_supplicant( 1324): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1324): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1324): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  936): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  936): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  936): handleScreenStateChanged Exit: true
E/WifiStateMachine(  936): handleMessage: X
E/WifiStateMachine(  936): handleMessage: E msg.what=131154
E/WifiStateMachine(  936): processMsg: ConnectedState
,E/WifiStateMachine(  936):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiDataStallTracker(  936): updateDataStallInfo: mDataStallTxRxSum={txSum=191 rxSum=174} preTxRxSum={txSum=191 rxSum=174}
D/WifiDataStallTracker(  936): updateDataStallInfo: NONE
D/WifiDataStallTracker(  936): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
V/SRS_Proc(  400): ParamSet string: screen_state=on
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
,I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  936): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  936): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  936): handleMessage: X
E/WifiStateMachine(  936): handleMessage: E msg.what=131127
,E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  936): processMsg: ConnectModeState
E/WifiStateMachine(  936):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  936): handleMessage: X
E/WifiStateMachine(  936): handleMessage: E msg.what=131129
E/WifiStateMachine(  936): processMsg: ConnectedState
,E/WifiStateMachine(  936):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  936): processMsg: ConnectModeState,
E/WifiStateMachine(  936):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
D/NetworkPolicy(  936): updateScreenOn: false
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
V/NetworkPolicy(  936): updateIfacesLocked()
D/wpa_supplicant( 1324): wlan0: Control interface command 'BLACKLIST clear'
D/WifiController(  936): handleMessage: E msg.what=155650
D/WifiController(  936): processMsg: DeviceActiveState
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
E/wpa_supplicant( 1324): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  936): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  936): WifiMonitor:wlan0 cnt=35 dispatchEvent: BLACKLIST CLEAR 
D/WifiController(  936): handleMessage: X
E/WifiStateMachine(  936): handleMessage: X
,D/NetworkManagementService(  936): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/Process (  936): killProcessQuiet, pid=5957
I/ActivityManager(  936): Killing 5957:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager( 6633): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/XAN-DPS (  936): prepareColorFade done
D/XAN-DPS (  936): setBrightness to 0
,I/SensorManager(  936): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@26b267ba
W/SensorService(  936): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  936): disable: get sensor name = CM32181 Light sensor,
I/DisplayManagerService(  936): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
V/ActivityManager(  936): Display changed displayId=0
E/JavaBinder(  936): !!! FAILED BINDER TRANSACTION !!!
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
W/SensorService(  936): pid=936, uid=1000
W/SensorService(  936): Active sensors: size = 3
W/SensorService(  936): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  936): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  936): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  936): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@26b267ba, eanble = 0, strlen(mName) = 67
W/SensorService(  936): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  936): Listener[0] = com.htc.smartdim.sensor_eye@1b2e56b7
W/SensorService(  936): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,W/DisplayManagerService(  936): Failed to notify process 5957 that displays changed, assuming it died.
W/DisplayManagerService(  936): android.os.TransactionTooLargeException
W/DisplayManagerService(  936): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  936): 	at android.os.BinderProxy.transact(Binder.java:504)
W/DisplayManagerService(  936): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  936): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1143)
W/DisplayManagerService(  936): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:977)
W/DisplayManagerService(  936): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:120)
W/DisplayManagerService(  936): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1072)
W/DisplayManagerService(  936): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService(  936): ,	at android.os.Looper.loop(Looper.java:155)
W/DisplayManagerService(  936): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  936): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL true Token 12 num clients 6,
,I/ActivityManager(  936): Recipient 5957,
,I/CalendarProvider2( 6633): Created com.android.providers.calendar.CalendarAlarmManager@413de63(com.htc.providers.calendar.HtcCalendarProvider@2dca0a60)
,D/CalendarProvider2( 6633): wait start:true,
,D/GpsLocationProvider(  936): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/CalendarProvider2( 6633): wait end:false,
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false),
,D/PMS     (  936): acquireWL(88061aa): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1806 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  936): acquireWL(2fe7919b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1806 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(88061aa): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(2fe7919b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node,
D/PMS     (  936): Setting HAL interactive mode to false
D/SurfaceControl(  936): Excessive delay in setPowerMode(): 297ms
,D/PMS     (  936): Setting HAL interactive mode to false done
D/PMS     (  936): Setting HAL auto-suspend mode to true
,D/PMS     (  936): Setting HAL auto-suspend mode done
W/HtcSystemUPManager(  936): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/HABCtrl (  936): TPE algorithm. remove timeout.
D/PMS     (  936): OOBE c monitor 11
,D/PMS     (  936): acquireWL(2cd86938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/BatteryService(  936): n_update end
D/PMS     (  936): releaseWL(2cd86938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  936): updateBatteryInfo
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/InputMethodManagerService(  936): screenObserver, isScreenOn=false
D/StatusBarManagerService(  936): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  936): Disable input method client, pid=1623
,D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/NotificationService(  936): plugged=true pluggin=true
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/PMS     (  936): runPSCheck
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  936): Checking...
,D/UsbnetService(  936): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  936): >> updateStatus
D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): battery changed pluggedType: 2
D/WifiController(  936): processMsg: DeviceActiveState
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  936): << updateStatus
D/NfcService( 1579): ScreenObserver: OFF
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1579): applyRouting - 0
,D/PMS     (  936): acquireWL(29a3ac77): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1579 1027 null
,D/NfcService( 1579): applyRouting -2
D/NfcService( 1579): applyRouting
,D/NfcService( 1579): Ignore this applyRouting...
D/PMS     (  936): releaseWL(29a3ac77): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ActivityManager(  936): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6663 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/PowerUI ( 1221): closing low battery warning: level=100
I/InputManager(  936): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,D/AlarmManager(  936): ACTION_SCREEN_OFF
,I/AlarmManager(  936): [AlarmQueuing] screen off now: 
,I/AlarmManager(  936): [AlarmQueuing] data connection: true
I/AlarmManager(  936): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  936): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  936): stopDataStallAlarm 
,E/WifiDataStallTracker(  936): ENABLE_DATA_MONITOR_POLL false Token 2,
E/WifiStateMachine(  936): handleMessage: E msg.what=131167
E/WifiStateMachine(  936): processMsg: ConnectedState
I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@27e7d7ff, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
E/WifiStateMachine(  936):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  400): ParamSet string: screen_state=off
E/WifiStateMachine(  936): processMsg: ConnectModeState
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  936):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  936): processMsg: DriverStartedState
E/WifiStateMachine(  936):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  936): processMsg: SupplicantStartedState
E/WifiStateMachine(  936):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  936): processMsg: DefaultState
E/WifiStateMachine(  936):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  936):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  936): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/NetworkPolicy(  936): updateScreenOn: false
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_SCREEN_ON 0'
,I/wpa_supplicant( 1324): SET_SCREEN_ON:Off
I/wpa_supplicant( 1324): htc_wext_set_keepalive +
D/WifiDisplayAdapter(  936): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  936):     Client/Owner: Client
D/WifiDisplayAdapter(  936):     GroupId: 
D/WifiDisplayAdapter(  936):     Passphrase: 
D/WifiDisplayAdapter(  936):     SessionId: 0
D/WifiDisplayAdapter(  936):     IP Address: }
I/wpa_supplicant( 1324): htc_wext_set_keepalive: enable=1, type=2, interval=15
V/NetworkPolicy(  936): updateIfacesLocked()
D/wpa_supplicant( 1324): getPrivFuncNum +	
,D/NetworkManagementService(  936): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/wpa_supplicant( 1324): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1324): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1324): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1324): htc_wext_set_keepalive - ret = 0
W/SensorService(  936): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  936): enable: get sensor name = hTC Gesture Motion HIDI
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  936): handleMessage: E msg.what=155651
D/WifiController(  936): processMsg: DeviceActiveState
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
E/WifiStateMachine(  936): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
,D/WifiController(  936): handleMessage: X
D/WifiStateMachine(  936): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  936): handleScreenStateChanged Exit: false
E/WifiStateMachine(  936): handleMessage: X
E/WifiStateMachine(  936): handleMessage: E msg.what=131154
E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  936): handleMessage: X
D/DotMatrix( 1311): [EventService] getTotalRam: 1842 Mb
W/SensorService(  936): pid=1221, uid=10041
W/SensorService(  936): Active sensors: size = 4
W/SensorService(  936): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  936): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  936): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  936): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  936): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@27e7d7ff, eanble = 1, strlen(mName) = 57
W/SensorService(  936): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  936): Listener[0] = com.htc.smartdim.sensor_eye@1b2e56b7
W/SensorService(  936): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@27e7d7ff
W/SensorService(  936): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/ClockController( 1221): stop clock update:screen off
,D/GpsLocationProvider(  936): receive broadcast intent, action: android.intent.action.SCREEN_OFF,
,D/ContactMessageStore( 1563): start background delete task...,
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false)
D/ContactMessageStore( 1563): size: 0 , 0
,D/ContactMessageStore( 1563): Background delete complete
,D/PMS     (  936): acquireWL(3446e0e4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1806 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  936): releaseWL(3446e0e4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  936): acquireWL(2f0b694d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1806 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
D/PMS     (  936): releaseWL(2f0b694d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,E/WifiDataStallTracker(  936): DATA_MONITOR_POLL false Token 3
,D/PowerUsageList:PowerUsageHelper( 6663): MY_DEBUG = false
,D/SmartSyncUtils( 6663): isEpsOn(), nState = 0
,D/PMS     (  936): acquireWL(36032750): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6663 1000 null
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145)
,I/RemoteViews( 1221): apply : com.htc.updater 0 11 0 36
,W/ContextImpl(  936): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  936): Init customizeScreenOffDelayClass error
,D/PMS     (  936): releaseWL(36032750): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 6663): isEpsOn(), nState = 0
D/SmartSyncUtils( 6663): isEpsOn(), nState = 0
,W/ContextImpl( 6663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  936): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  936): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1b2e56b7
W/SensorService(  936): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  936): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  936): pid=936, uid=1000
,W/SensorService(  936): Active sensors: size = 3
W/SensorService(  936): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  936): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  936): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  936): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1b2e56b7, eanble = 0, strlen(mName) = 36
W/SensorService(  936): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  936): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@27e7d7ff
W/SensorService(  936): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  936): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  936): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  936): pid=936, uid=1000
W/SensorService(  936): Active sensors: size = 2
W/SensorService(  936): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  936): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  936): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@1b2e56b7, eanble = 0, strlen(mName) = 36
W/SensorService(  936): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  936): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@27e7d7ff
W/SensorService(  936): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  936): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@1b2e56b7
,I/ActivityManager(  936): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6696 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,E/ActivityThread(  936): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@39b0de24 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  936): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@39b0de24 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  936): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  936): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767),
E/ActivityThread(  936): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  936): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  936): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  936): ,	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  936): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  936): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  936): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  936): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  936): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  936): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  936): 	at android.os.Looper.loop(Looper.java:155),
E/ActivityThread(  936): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  936): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  936): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  936): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  936): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  936): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/PowerUsageList:PowerUsageHelper( 6663): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/SmartSyncUtils( 6663): getMobilePolicyEnabled, result = true,
D/Process (  936): killProcessQuiet, pid=6261
I/ActivityManager(  936): Killing 6261:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/PowerUsageList:BatterySipperExt( 6663): gen(), null == sipper.uidObj, userId = 0,
,D/WifiService(  936): New client listening to asynchronous messages,
E/WifiTrafficPoller(  936): ADD_CLIENT: 7
,I/ActivityManager(  936): Recipient 6261
,E/WifiTrafficPoller(  936): TRAFFIC_STATS_POLL false Token 13 num clients 7
,D/PowerUsageList:PowerUsageHelper( 6663): MY_DEBUG = false
,D/Process (  936): killProcessQuiet, pid=6284
,I/ActivityManager(  936): Killing 6284:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  936): Recipient 6284,
,I/CalendarProvider2( 6633): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6633): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  936): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6721 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  936): killProcessQuiet, pid=6315,
,I/ActivityManager(  936): Killing 6315:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  936): Recipient 6315
,I/ActivityManager(  936): Killing 5725:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  936): killProcessQuiet, pid=5725
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  936): releaseWL(3ad2edab): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  936): Recipient 5725
,W/ResourcesManager( 6721): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6721): onCreate
,D/ProviderChangeReceiver( 6721): ---------------------------------------------------
,D/ProviderChangeReceiver( 6721): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  936): killProcessQuiet, pid=5441
I/ActivityManager(  936): Killing 5441:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6721): start to updateAlertNotification!
,I/ActivityManager(  936): Recipient 5441
,D/HtcAlertService( 6721): No fired or scheduled alerts
,D/HtcAlertUtils( 6721): -- cancelReminderNotification --
,D/HtcAlertUtils( 6721): broadcastExistReminder!,
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  936): handleMessage: E msg.what=131155
E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564191594] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1564191592] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  936): handleMessage: X
,E/WifiStateMachine(  936): handleMessage: E msg.what=131155,
E/WifiStateMachine(  936): processMsg: ConnectedState
E/WifiStateMachine(  936):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1068] from screen [on:0 period:-1564190522] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  936): processMsg: L2ConnectedState
E/WifiStateMachine(  936):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1564190520] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  936): handleMessage: X
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  936): DATA_MONITOR_POLL false Token 3
,D/ContactMessageStore( 1563): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1563): MSG_NOTIFY_CS_TO_SYNC <<,
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/Process (  936): killProcessQuiet, pid=5564,
I/ActivityManager(  936): Killing 5564:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  936): Recipient 5564
,D/PMS     (  936): acquireWL(1a2db36f): PARTIAL_WAKE_LOCK  *alarm* 0x1 936 1000 WorkSource{10024},
V/AlarmManager(  936): sending alarm PendingIntent{8fb687c: PendingIntentRecord{38c97505 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143325, Int=0
,D/PMS     (  936): releaseWL(1a2db36f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  936): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  936): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  936): acquireWL(164c895a): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 936 1000 null
,D/libc    (  936): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  936): [NET] android_getaddrinfofornet-, err=8
D/libc    (  936): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  936): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  936): [NET] android_getaddrinfo_proxy+
D/libc    (  936): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  936): [NET] android_getaddrinfo_proxy-, success
D/libc    (  936): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  936): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  936): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  936): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  936): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  936):  [handleDownloadXtraData]inject done.
,D/PMS     (  936): acquireWL(2db9e126): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 936 1000 null
D/PMS     (  936): releaseWL(164c895a): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/GpsLocationProvider(  936): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  936): releaseWL(2db9e126): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1563): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1563): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  936): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  936): acquireWL(2422a167): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null,
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  936): n_update end
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  936): releaseWL(2422a167): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  936): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  936): plugged=true pluggin=true
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/PMS     (  936): runPSCheck
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  936): Checking...
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  936): >> updateStatus
D/UsbnetService(  936): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): battery changed pluggedType: 2
D/WifiController(  936): processMsg: DeviceActiveState
I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  936): processMsg: StaEnabledState
,I/HtcPowerSaver(  936): << updateStatus
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1563): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  936): acquireWL(2c964b14): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 936 1000 WorkSource{1000}
V/AlarmManager(  936): sending alarm PendingIntent{1598ae65: PendingIntentRecord{3e43373a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=152913, Int=0
V/AlarmManager(  936): sending alarm PendingIntent{2c563fbd: PendingIntentRecord{3152e9b2 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454429774774, Int=0
V/AlarmManager(  936): sending alarm PendingIntent{352ded03: PendingIntentRecord{36170480 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203101, Int=0
,V/AlarmManager(  936): sending alarm PendingIntent{62c1ab9: PendingIntentRecord{3501eefe com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189969, Int=0
,D/PMS     (  936): acquireWL(3f18565f): PARTIAL_WAKE_LOCK  *backup* 0x1 936 1000 null,
,W/BackupManagerService(  936): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  936): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  936): releaseWL(3f18565f): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  936): acquireWL(3427e8ac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(2c964b14): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  936): acquireWL(3eeaa975): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  936): releaseWL(3427e8ac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  936): releaseWL(3eeaa975): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  936): acquireWL(380b257): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(380b257): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  936): acquireWL(3a6ca144): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(3a6ca144): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  936): acquireWL(37fb922d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): acquireWL(38752362): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  936): acquireWL(1b348db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(37fb922d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1829): Vacuum at: now=1454429810410 tag=VacuumService,
,I/GoogleURLConnFactory( 1829): Using platform SSLCertificateSocketFactory,
,D/PMS     (  936): releaseWL(38752362): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  936): acquireWL(230613ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(230613ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): acquireWL(2a29954f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(2a29954f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1829): No account for auth token provided,
,D/libc    ( 1829): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1829): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1829): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1829): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1829): [NET] android_getaddrinfo_proxy+
D/libc    ( 1829): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1829): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1829): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1829): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1829): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1829): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1829): No account for auth token provided,
,W/Uploader( 1829): No account for auth token provided
,W/Uploader( 1829):  no longer exists, so no auth token.,
,W/Uploader( 1829): No account for auth token provided,
,I/GLSUser ( 1829): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1829): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1829): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1829): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1829): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1829): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1829): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1829): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1829): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1829): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1829): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1829): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1829): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1829): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1829): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1829): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1829): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1829): No account for auth token provided,
,D/PMS     (  936): releaseWL(1b348db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  936): acquireWL(3040703f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(3040703f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  936): acquireWL(3d5d2d0c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  936): releaseWL(3d5d2d0c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/art     (  936): Explicit concurrent mark sweep GC freed 37327(2MB) AllocSpace objects, 5(1116KB) LOS objects, 33% free, 18MB/28MB, paused 1.760ms total 209.609ms
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40,
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1505): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1cca7aaa
I/ActivityManager(  936): Killing 6486:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  936): killProcessQuiet, pid=6486
,D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  936): Recipient 6486
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  936): acquireWL(27ae0655): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/BatteryService(  936): n_update end
D/PMS     (  936): releaseWL(27ae0655): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  936): updateBatteryInfo
D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/NotificationService(  936): plugged=true pluggin=true
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/PMS     (  936): runPSCheck
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  936): Checking...
D/UsbnetService(  936): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  936): >> updateStatus
D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): battery changed pluggedType: 2
D/WifiController(  936): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  936): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  936): acquireWL(25c4c86a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/BatteryService(  936): n_update end
D/PMS     (  936): releaseWL(25c4c86a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  936): updateBatteryInfo
,D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/NotificationService(  936): plugged=true pluggin=true
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/PMS     (  936): runPSCheck
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  936): battery changed pluggedType: 2
D/UsbnetService(  936): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  936): Checking...
D/WifiController(  936): handleMessage: E msg.what=155652
I/HtcPowerSaver(  936): >> updateStatus
D/WifiController(  936): processMsg: DeviceActiveState
I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  936): processMsg: StaEnabledState
I/HtcPowerSaver(  936): << updateStatus
D/WifiController(  936): processMsg: DefaultState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  936): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1324): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  936): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  936): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
,D/WifiMonitor(  936): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  936): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48
D/WifiMonitor(  936): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  936): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  936): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  936): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  936): acquireWL(35d5d15b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 936 1000 WorkSource{1000}
V/AlarmManager(  936): sending alarm PendingIntent{1598ae65: PendingIntentRecord{3e43373a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=212913, Int=0
,V/AlarmManager(  936): sending alarm PendingIntent{3a15b2d1: PendingIntentRecord{365f0136 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454429947820, Int=0,
,D/PMS     (  936): releaseWL(35d5d15b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1829): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1829): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1829): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1829): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1829): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1829): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1829): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1829): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1829): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1829): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1829): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 6006): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6006): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6006): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6006): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6006): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6006): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6006): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,W/System  ( 6006): Ignoring header User-Agent because its value was null.
,D/libc    ( 6006): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6006): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6006): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6006): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6006): [NET] android_getaddrinfo_proxy+
D/libc    ( 6006): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6006): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 1
,D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
D/PMS     (  936): acquireWL(1b44e528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  936): n_update end
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  936): releaseWL(1b44e528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  936): updateBatteryInfo
D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/NotificationService(  936): plugged=true pluggin=true
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  936): BroadcastReceiver::onReceive-
,D/PMS     (  936): runPSCheck
D/WifiController(  936): handleMessage: E msg.what=155652
D/HtcPowerSaver(  936): Checking...
D/WifiController(  936): processMsg: DeviceActiveState
I/HtcPowerSaver(  936): >> updateStatus
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): battery changed pluggedType: 2
D/WifiController(  936): handleMessage: X
,I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  936): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  446): AtCmdFwd service not published, waiting... retryCnt : 5
D/PMS     (  936): acquireWL(3f17f241): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/BatteryService(  936): n_update end
D/PMS     (  936): releaseWL(3f17f241): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  936): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  936): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  936): runPSCheck
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  936): battery changed pluggedType: 2
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  936): Checking...
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  936): >> updateStatus
D/UsbnetService(  936): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): processMsg: DeviceActiveState
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  936): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  936): acquireWL(84823e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/BatteryService(  936): n_update end
D/PMS     (  936): releaseWL(84823e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  936): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  936): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  936): runPSCheck
D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  936): Checking...
D/UsbnetService(  936): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  936): >> updateStatus
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  936): battery changed pluggedType: 2
D/UsbnetService(  936): BroadcastReceiver::onReceive-
D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): processMsg: DeviceActiveState
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
,I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  936): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1563): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1563): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1563): sku_id=118
D/ContactMessageStore( 1563): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1563): start background delete task...
,D/ContactMessageStore( 1563): size: 0 , 0
,D/ContactMessageStore( 1563): Background delete complete
,D/PMS     (  936): acquireWL(2b8b8d27): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/BatteryService(  936): n_update end,
D/PMS     (  936): releaseWL(2b8b8d27): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  936): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/NotificationService(  936): plugged=true pluggin=true
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/PMS     (  936): runPSCheck
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  936): Checking...
,D/UsbnetService(  936): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  936): >> updateStatus
D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): battery changed pluggedType: 2
D/WifiController(  936): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  936): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  936): acquireWL(22972bd4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  936): n_update end
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  936): releaseWL(22972bd4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  936): updateBatteryInfo
D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/NotificationService(  936): plugged=true pluggin=true
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  936): runPSCheck
D/UsbnetService(  936): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  936): Checking...
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  936): >> updateStatus
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): processMsg: DeviceActiveState
D/WifiController(  936): battery changed pluggedType: 2
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
,I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  936): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/bt-btm  ( 3120): Received oneshot timer event complete
D/PMS     (  936): acquireWL(3b0717d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 936 1000 WorkSource{1000}
V/AlarmManager(  936): sending alarm PendingIntent{1598ae65: PendingIntentRecord{3e43373a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=392913, Int=0
I/bt-btm  ( 3120): btm_ble_timeout
V/AlarmManager(  936): sending alarm PendingIntent{18629872: PendingIntentRecord{699d4c3 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940732, Int=0
I/bt-btm  ( 3120): btm_gen_resolvable_private_addr
,D/PMS     (  936): acquireWL(253140): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3120 1002 null
,D/bt-btm  ( 3120): btm_ble_rand_enc_complete
I/bt-btm  ( 3120): btm_gen_resolve_paddr_low
D/bt-smp  ( 3120): smp_encrypt_data
,W/bt-smp  ( 3120): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3120): Plain text(LSB ~ MSB) = 31 20 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3120): Encrypted text(LSB ~ MSB) = d5 ed e1 94 c0 19 ed 7c 84 10 d1 95 ee 45 14 a9 
I/bt-btm  ( 3120): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3120): Stopping oneshot timer
D/bt-btm  ( 3120): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  936): releaseWL(3b0717d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  936): releaseWL(253140): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  936): acquireWL(3c57a879): PARTIAL_WAKE_LOCK  *alarm* 0x1 936 1000 WorkSource{10024}
V/AlarmManager(  936): sending alarm PendingIntent{2d3dc9be: PendingIntentRecord{1dbafa1f com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454430210393, Int=1800000
V/AlarmManager(  936): sending alarm PendingIntent{33cc216c: PendingIntentRecord{5a15335 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936913, Int=0
V/AlarmManager(  936): sending alarm PendingIntent{de79719: PendingIntentRecord{31fb23de android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804788, Int=0
,I/ActivityManager(  936): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6759 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  936): sending alarm PendingIntent{1d08c3ca: PendingIntentRecord{9f193b com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454430448208, Int=0,
V/AlarmManager(  936): sending alarm PendingIntent{3c0fe858: PendingIntentRecord{2c84ed5f com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454430573930, Int=0
,D/PMS     (  936): acquireWL(37a0edb1): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4455 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  936): acquireWL(3fdc0e17): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1829 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  936): releaseWL(3fdc0e17): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  936): acquireWL(39c73204): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4455 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 6663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  936): releaseWL(37a0edb1): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  936): releaseWL(3c57a879): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6663): MY_DEBUG = false
,D/PowerUsageService( 6663): repeat time = 1454431474025
,D/PMS     (  936): acquireWL(358974b3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1829): Message class com.google.f.a.a.i
D/PMS     (  936): releaseWL(358974b3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4455): Aggregate from 1454429704538 (log), 1454428410362 (data)
,D/PMS     (  936): releaseWL(39c73204): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,E/cutils-trace( 6782): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6782): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6782): dex2oat: override thread count:4
,I/PowerUsageList:PowerUsageHelper( 6663): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6663): gen(), null == sipper.uidObj, userId = 0,
,I/dex2oat ( 6782): dex2oat took 700.283ms (threads: 4),
,I/PushClient( 6759): ApplicationMonitor {301a0fd5}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
I/PushClient( 6759): ApplicationMonitor {301a0fd5}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6759): ApplicationMonitor {301a0fd5}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6759): ApplicationMonitor {301a0fd5}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6759): ApplicationMonitor {301a0fd5}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6759): ApplicationMonitor {301a0fd5}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6759): ApplicationMonitor {301a0fd5}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6759): ApplicationMonitor {301a0fd5}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6759): ApplicationMonitor {301a0fd5}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6759): PnsModel {1a356c8c}: update(): Update registration caused by: alarm,
,I/PushClient( 6759): PnsConfigModel {6e92653}: <init>(): Use dm-client for provisioning.
,W/System.err( 6759): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6759): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6759): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.,
,W/ContextImpl( 6759): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  936): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6789 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6789): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6789 dbg=false s=true
,I/DeviceManagement( 6789): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6789): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6789): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6789): WorkflowService: Starting workflow service
,I/DeviceManagement( 6789): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1a356c8c] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6789): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6789): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6789): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6789): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6789): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6789): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6789): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6789): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1a356c8c],
,I/DeviceManagement( 6789): WorkflowService: Stopping workflow service,
,D/Process (  936): killProcessQuiet, pid=6368
I/ActivityManager(  936): Killing 6368:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6759): PnsModel {1a356c8c}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  936): Recipient 6368
,D/Process (  936): killProcessQuiet, pid=6432,
I/ActivityManager(  936): Killing 6432:com.test.thalitest/u0a366 (adj 15): empty #17
D/Process (  936): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  936): Recipient 6432
,E/InputEventReceiver( 1400): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{dcc3a13 uid 10366 pid 6432} (c)'
,D/PMS     (  936): acquireWL(2c3f37d2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 936 1000 WorkSource{1000},
V/AlarmManager(  936): sending alarm PendingIntent{1598ae65: PendingIntentRecord{3e43373a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=992913, Int=0
V/AlarmManager(  936): sending alarm PendingIntent{1858f0a3: PendingIntentRecord{38424fa0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454430620495, Int=0
,D/SmartSyncUtils( 6663): isEpsOn(), nState = 0
,D/PMS     (  936): acquireWL(1e3ed759): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6663 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6663): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 6663): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/PMS     (  936): releaseWL(2c3f37d2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 6663): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6663): SettingOnTime = 1454479200000, randomSettingOnTime = 1454477596000
D/SmartSyncScreenOnOffTimeReceiver( 6663): SettingOffTime = 1454457600000, randomSettingOffTime = 1454458709000
D/SmartSyncScreenOnOffTimeReceiver( 6663): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6663): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6663): bNightModeTurnOffOnce = false
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  936): releaseWL(1e3ed759): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  936): acquireWL(2e34ff1e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null,
I/BatteryService(  936): n_update end
D/PMS     (  936): releaseWL(2e34ff1e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  936): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  936): plugged=true pluggin=true
D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  936): BroadcastReceiver::onReceive-
D/PMS     (  936): runPSCheck
D/HtcPowerSaver(  936): Checking...
I/HtcPowerSaver(  936): >> updateStatus
,D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): battery changed pluggedType: 2
D/WifiController(  936): processMsg: DeviceActiveState
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  936): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  936): acquireWL(17ff3ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/BatteryService(  936): n_update end
D/PMS     (  936): releaseWL(17ff3ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  936): BroadcastReceiver::onReceive+
D/NotificationService(  936): plugged=true pluggin=true
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/WifiController(  936): battery changed pluggedType: 2
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  936): updateBatteryInfo
D/UsbnetService(  936): BroadcastReceiver::onReceive-
D/PMS     (  936): runPSCheck
D/WifiController(  936): handleMessage: E msg.what=155652
D/HtcPowerSaver(  936): Checking...
D/WifiController(  936): processMsg: DeviceActiveState
I/HtcPowerSaver(  936): >> updateStatus
D/WifiController(  936): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100,
D/WifiController(  936): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  936): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  936): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  936): acquireWL(160cc5cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/BatteryService(  936): n_update end
D/PMS     (  936): releaseWL(160cc5cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  936): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  936): runPSCheck
D/HtcPowerSaver(  936): Checking...
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  936): >> updateStatus
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  936): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  936): << updateStatus
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/NotificationService(  936): plugged=true pluggin=true
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  936): BroadcastReceiver::onReceive-
D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): battery changed pluggedType: 2
,D/WifiController(  936): processMsg: DeviceActiveState
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  936): User[0] Flushing usage stats to disk
,D/PMS     (  936): acquireWL(f7c9015): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 936 1000 null
I/BatteryService(  936): n_update end
D/PMS     (  936): releaseWL(f7c9015): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  936): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  936): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  936): runPSCheck
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  936): Checking...
D/UsbnetService(  936): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  936): >> updateStatus
D/UsbnetService(  936): onReceive BATTERY_CHANGED
D/WifiController(  936): battery changed pluggedType: 2
D/UsbnetService(  936):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  936): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  936): handleMessage: E msg.what=155652
D/WifiController(  936): processMsg: DeviceActiveState
D/WifiController(  936): processMsg: StaEnabledState
D/WifiController(  936): processMsg: DefaultState
D/WifiController(  936): handleMessage: X
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  936): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  936): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms)
```
